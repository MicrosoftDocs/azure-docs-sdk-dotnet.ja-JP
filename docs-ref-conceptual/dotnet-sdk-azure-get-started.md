---
title: Azure .NET および .NET Core API の概要
description: ご利用の Azure サブスクリプションでの .NET および .NET Core 用 Azure ライブラリの基本的な使用方法について説明します。
keywords: Azure, .NET, .NET Core, ASP.NET, ASP.NET Core SDK, API ,認証, 概要
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 08/22/2018
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: ad894e47704fcccc83f7d02acb8e418b167993f9
ms.sourcegitcommit: b2a53a3aea9de6720bd975fb7fe4e722e9d182a3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/23/2018
ms.locfileid: "42703055"
---
# <a name="get-started-with-the-azure-net-and-net-core-apis"></a>Azure .NET および .NET Core API の概要

このチュートリアルでは、いくつかの [.NET 用 Azure API](/dotnet/api/overview/azure/) の使い方を示します。  認証の設定、Azure Storage アカウントの作成と使用、Azure SQL Database の作成と使用、仮想マシンのデプロイ、GitHub からの Azure App Service Web アプリのデプロイについて説明します。

## <a name="prerequisites"></a>前提条件

- Azure アカウント。 所有していない場合は、[無料試用版を入手](https://azure.microsoft.com/free/)してください。

## <a name="set-up-authentication"></a>認証の設定

[!include[Create service principal](includes/create-sp.md)]

[!include[File-based authentication](includes/file-based-auth.md)]

## <a name="create-a-new-project"></a>新しいプロジェクトを作成する 

新しいコンソール アプリケーション プロジェクトを作成します。  Visual Studio でこれを行うには、**[ファイル]**、**[新規]** の順にクリックし、**[プロジェクト]** をクリックします。Visual C# テンプレートで、**[コンソール アプリ (.NET Core)]** を選び、プロジェクトの名前を設定して、**[OK]** をクリックします。

![[新しいプロジェクト] ダイアログ](media/dotnet-sdk-azure-get-started/new-project.png)

新しいコンソール アプリが作成されたら、**[ツール]**、**[NuGet パッケージ マネージャー]**、**[パッケージ マネージャー コンソール]** の順にクリックして、パッケージ マネージャー コンソールを開きます。  コンソールで、次の 3 つのコマンドを実行して、必要なパッケージを入手します。

```powershell
# Azure Management Libraries for .NET (Fluent)
Install-Package Microsoft.Azure.Management.Fluent

# Azure Store client libraries
Install-Package WindowsAzure.Storage

# SQL Database client libraries
Install-Package System.Data.SqlClient
```

## <a name="directives"></a>ディレクティブ

アプリケーションの `Program.cs` ファイルを編集します。  最上部の `using` ディレクティブを次の内容で置き換えます。

```csharp
using System;
using System.Linq;
using Microsoft.Azure.Management.Compute.Fluent;
using Microsoft.Azure.Management.Compute.Fluent.Models;
using Microsoft.Azure.Management.Fluent;
using Microsoft.Azure.Management.ResourceManager.Fluent;
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
using Microsoft.WindowsAzure.Storage;
using Microsoft.WindowsAzure.Storage.Blob;
using System.Data.SqlClient;
```

## <a name="create-a-virtual-machine"></a>仮想マシンの作成

この例では、仮想マシンをデプロイします。 

`Main` メソッドを次のコードで置き換えます。  仮想マシンの実際の `username` と `password` を指定してください。

```csharp
static void Main(string[] args)
{
    // Set some variables...
    string username = "MY_USERNAME";
    string password = "MY_PASSWORD";
    string rgName = "sampleResourceGroup";
    string windowsVmName = "sampleWindowsVM";
    string publicIpDnsLabel = "samplePublicIP" + (new Random().Next(0,100000)).ToString();

    // Authenticate
    var credentials = SdkContext.AzureCredentialsFactory
        .FromFile(Environment.GetEnvironmentVariable("AZURE_AUTH_LOCATION"));

    var azure = Azure
        .Configure()
        .WithLogLevel(HttpLoggingDelegatingHandler.Level.Basic)
        .Authenticate(credentials)
        .WithDefaultSubscription();

    // Create the VM
    Console.WriteLine("Creating VM...");
    var windowsVM = azure.VirtualMachines.Define(windowsVmName)
        .WithRegion(Region.USEast)
        .WithNewResourceGroup(rgName)
        .WithNewPrimaryNetwork("10.0.0.0/28")
        .WithPrimaryPrivateIPAddressDynamic()
        .WithNewPrimaryPublicIPAddress(publicIpDnsLabel)
        .WithPopularWindowsImage(KnownWindowsVirtualMachineImage.WindowsServer2012R2Datacenter)
        .WithAdminUsername(username)
        .WithAdminPassword(password)
        .WithSize(VirtualMachineSizeTypes.StandardD2V2)
        .Create();

    // Wait for the user
    Console.WriteLine("Press enter to continue...");
    Console.ReadLine();
}
```

**F5** キーを押してサンプルを実行します。

数分後、プログラムが終了すると、Enter キーを押すように求められます。 Enter キーを押した後、Cloud Shell を使ってサブスクリプション内の仮想マシンを確認します。

```azurecli-interactive
az vm list
```

## <a name="deploy-a-web-app-from-a-github-repo"></a>GitHub リポジトリからの Web アプリのデプロイ

次に、既存の GitHub リポジトリから新しい Web アプリを作成してデプロイするように、コードを変更します。 `Main` メソッドを次のコードに置き換えます。

```csharp
static void Main(string[] args)
{
    // Set some variables...
    string rgName = "sampleResourceGroup";
    string appName = SdkContext.RandomResourceName("WebApp", 20);

    // Authenticate
    var credentials = SdkContext.AzureCredentialsFactory
        .FromFile(Environment.GetEnvironmentVariable("AZURE_AUTH_LOCATION"));

    var azure = Azure
        .Configure()
        .Authenticate(credentials)
        .WithDefaultSubscription();

    // Create the web app
    Console.WriteLine("Creating Web App...");
    var app = azure.WebApps.Define(appName)
        .WithRegion(Region.USEast)
        .WithNewResourceGroup(rgName)
        .WithNewFreeAppServicePlan()
        .DefineSourceControl()
        .WithPublicGitRepository("https://github.com/Azure-Samples/app-service-web-dotnet-get-started")
        .WithBranch("master")
        .Attach()
        .Create();
    Console.WriteLine("Your web app is live at: https://{0}", app.HostNames.First());

    // Wait for the user
    Console.WriteLine("Press enter to continue...");
    Console.ReadLine();
}
```

前と同じように **F5** キーを押してコードを実行します。  ブラウザーを開き、コンソールに表示される URL に移動して、デプロイを確認します。

## <a name="connect-to-a-sql-database"></a>SQL Database への接続

この例では、新しい Azure SQL Database を作成し、いくつかの SQL 操作を実行します。

`Main` メソッドを次のように置き換えて、`dbPassword` に強力なパスワードを割り当てます。

```csharp
 static void Main(string[] args)
{
    // Set some variables...
    string rgName = "sampleResourceGroup";
    string adminUser = SdkContext.RandomResourceName("db", 8);
    string sqlServerName = SdkContext.RandomResourceName("sql", 10);
    string sqlDbName = SdkContext.RandomResourceName("dbname", 8);
    string dbPassword = "YOUR_PASSWORD_HERE";

    // Authenticate
    var credentials = SdkContext.AzureCredentialsFactory
        .FromFile(Environment.GetEnvironmentVariable("AZURE_AUTH_LOCATION"));

    var azure = Azure
        .Configure()
        .Authenticate(credentials)
        .WithDefaultSubscription();

    // Create the SQL server and database
    Console.WriteLine("Creating server...");
    var sqlServer = azure.SqlServers.Define(sqlServerName)
        .WithRegion(Region.USEast)
        .WithNewResourceGroup(rgName)
        .WithAdministratorLogin(adminUser)
        .WithAdministratorPassword(dbPassword)
        .WithNewFirewallRule("0.0.0.0", "255.255.255.255")
        .Create();

    Console.WriteLine("Creating database...");
    var sqlDb = sqlServer.Databases.Define(sqlDbName).Create();

    // Display information for connecting later...
    Console.WriteLine("Created database {0} in server {1}.", sqlDbName, sqlServer.FullyQualifiedDomainName);
    Console.WriteLine("Your user name is {0}.", adminUser + "@" + sqlServer.Name);

    // Build the connection string
    var builder = new SqlConnectionStringBuilder();
    builder.DataSource = sqlServer.FullyQualifiedDomainName;
    builder.InitialCatalog = sqlDbName;
    builder.UserID = adminUser + "@" + sqlServer.Name; // Format user ID as "user@server"
    builder.Password = dbPassword;
    builder.Encrypt = true;
    builder.TrustServerCertificate = true;

    // connect to the database, create a table and insert an entry into it
    using (var conn = new SqlConnection(builder.ConnectionString))
    {
        conn.Open();

        Console.WriteLine("Populating database...");
        var createCommand = new SqlCommand("CREATE TABLE CLOUD (name varchar(255), code int);", conn);
        createCommand.ExecuteNonQuery();

        var insertCommand = new SqlCommand("INSERT INTO CLOUD (name, code ) VALUES ('Azure', 1);", conn);
        insertCommand.ExecuteNonQuery();

        Console.WriteLine("Reading from database...");
        var selectCommand = new SqlCommand("SELECT * FROM CLOUD", conn);
        var results = selectCommand.ExecuteReader();
        while(results.Read())
        {
            Console.WriteLine("Name: {0} Code: {1}", results[0], results[1]);
        }
    }

    // Wait for the user
    Console.WriteLine("Press enter to continue...");
    Console.ReadLine();
}
```

前と同じように **F5** キーを押してコードを実行します。  サーバーが作成されて意図したとおりに動作していることはコンソール出力で確認できますが、好みに応じて、SQL Server Management Studio などのツールで直接接続してもかまいません。

## <a name="write-a-blob-into-a-new-storage-account"></a>新しいストレージ アカウントへの BLOB の書き込み

この例では、ストレージ アカウントを作成し、BLOB をアップロードします。  

`Main` メソッドを次のコードで置き換えます。

```csharp
static void Main(string[] args)
{
    // Set some variables...
    string rgName = "sampleResourceGroup";
    string storageAccountName = SdkContext.RandomResourceName("st", 10);

    // Authenticate
    var credentials = SdkContext.AzureCredentialsFactory
        .FromFile(Environment.GetEnvironmentVariable("AZURE_AUTH_LOCATION"));

    var azure = Azure
        .Configure()
        .Authenticate(credentials)
        .WithDefaultSubscription();

    // Create the storage account
    Console.WriteLine("Creating storage account...");
    var storage = azure.StorageAccounts.Define(storageAccountName)
        .WithRegion(Region.USEast)
        .WithNewResourceGroup(rgName)
        .Create();

    var storageKeys = storage.GetKeys();
    string storageConnectionString = "DefaultEndpointsProtocol=https;"
        + "AccountName=" + storage.Name
        + ";AccountKey=" + storageKeys[0].Value
        + ";EndpointSuffix=core.windows.net";

    var account = CloudStorageAccount.Parse(storageConnectionString);
    var serviceClient = account.CreateCloudBlobClient();

    // Create container. Name must be lower case.
    Console.WriteLine("Creating container...");
    var container = serviceClient.GetContainerReference("helloazure");
    container.CreateIfNotExistsAsync().Wait();

    // Make the container public
    var containerPermissions = new BlobContainerPermissions()
        { PublicAccess = BlobContainerPublicAccessType.Container };
    container.SetPermissionsAsync(containerPermissions).Wait();

    // write a blob to the container
    Console.WriteLine("Uploading blob...");
    var blob = container.GetBlockBlobReference("helloazure.txt");
    blob.UploadTextAsync("Hello, Azure!").Wait();
    Console.WriteLine("Your blob is located at {0}", blob.StorageUri.PrimaryUri);

    // Wait for the user
    Console.WriteLine("Press enter to continue...");
    Console.ReadLine();
}
```

**F5** キーを押してサンプルを実行します。

数分後、プログラムが終了します。 コンソールに表示される URL を参照して、BLOB がアップロードされたことを確認します。  "Hello, Azure!" というテキストが ブラウザーに表示されるはずです。

## <a name="clean-up"></a>クリーンアップ

> [!IMPORTANT]
> このチュートリアルで作成したリソースをクリーンアップしないと、引き続き課金されます。  忘れずにこの手順を実行してください。

Cloud Shell で次のように入力して、作成したすべてのリソースを削除します。

```azurecli-interactive
az group delete --name sampleResourceGroup
```

## <a name="explore-more-samples"></a>その他のサンプルを探す

.NET 用 Azure ライブラリを使ってリソースを管理したりタスクを自動化したりする方法をさらに詳しく知るには、[仮想マシン](dotnet-sdk-azure-virtual-machine-samples.md)、[Web アプリ](dotnet-sdk-azure-web-apps-samples.md)、[SQL データベース](dotnet-sdk-azure-sql-database-samples.md)に関するサンプル コードを参照してください。

## <a name="reference"></a>リファレンス

すべてのパッケージには、[リファレンス](http://docs.microsoft.com/dotnet/api)が提供されています。

[!include[Contribute and community](includes/contribute.md)]
