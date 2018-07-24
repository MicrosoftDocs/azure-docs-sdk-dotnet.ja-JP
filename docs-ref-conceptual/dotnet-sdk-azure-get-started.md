---
title: Azure .NET および .NET Core API の概要
description: ご利用の Azure サブスクリプションでの .NET および .NET Core 用 Azure ライブラリの基本的な使用方法について説明します。
keywords: Azure, .NET, .NET Core, ASP.NET, ASP.NET Core SDK, API ,認証, 概要
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 07/17/2018
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: a8775993e71566b7659a8ae8ceb2c376ece14e45
ms.sourcegitcommit: 779c1b202d3670cfa0b9428c89f830cad9ec7e9d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2018
ms.locfileid: "39135780"
---
# <a name="get-started-with-the-azure-net-and-net-core-apis"></a><span data-ttu-id="47594-104">Azure .NET および .NET Core API の概要</span><span class="sxs-lookup"><span data-stu-id="47594-104">Get started with the Azure .NET and .NET Core APIs</span></span>

<span data-ttu-id="47594-105">このチュートリアルでは、いくつかの [.NET 用 Azure API](/dotnet/api/overview/azure/) の使い方を示します。</span><span class="sxs-lookup"><span data-stu-id="47594-105">This tutorial demonstrates the usage of several [Azure APIs for .NET](/dotnet/api/overview/azure/).</span></span>  <span data-ttu-id="47594-106">認証の設定、Azure Storage アカウントの作成と使用、Azure SQL Database の作成と使用、仮想マシンのデプロイ、GitHub からの Azure App Service Web アプリのデプロイについて説明します。</span><span class="sxs-lookup"><span data-stu-id="47594-106">You will set up authentication, create and use an Azure Storage account, create and use an Azure SQL Database, deploy some virtual machines, and deploy an Azure App Service Web App from GitHub.</span></span>

## <a name="prerequisites"></a><span data-ttu-id="47594-107">前提条件</span><span class="sxs-lookup"><span data-stu-id="47594-107">Prerequisites</span></span>

- <span data-ttu-id="47594-108">Azure アカウント。</span><span class="sxs-lookup"><span data-stu-id="47594-108">An Azure account.</span></span> <span data-ttu-id="47594-109">所有していない場合は、[無料試用版を入手](https://azure.microsoft.com/free/)してください。</span><span class="sxs-lookup"><span data-stu-id="47594-109">If you don't have one, [get a free trial](https://azure.microsoft.com/free/)</span></span>
- [<span data-ttu-id="47594-110">Azure PowerShell</span><span class="sxs-lookup"><span data-stu-id="47594-110">Azure PowerShell</span></span>](/powershell/azure/install-azurerm-ps)

## <a name="set-up-authentication"></a><span data-ttu-id="47594-111">認証の設定</span><span class="sxs-lookup"><span data-stu-id="47594-111">Set up authentication</span></span>

[!include[Create service principal](includes/create-sp.md)]

[!include[File-based authentication](includes/file-based-auth.md)]

## <a name="create-a-new-project"></a><span data-ttu-id="47594-112">新しいプロジェクトを作成する</span><span class="sxs-lookup"><span data-stu-id="47594-112">Create a new project</span></span> 

<span data-ttu-id="47594-113">新しいコンソール アプリケーション プロジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="47594-113">Create a new console application project.</span></span>  <span data-ttu-id="47594-114">Visual Studio でこれを行うには、**[ファイル]**、**[新規]** の順にクリックし、**[プロジェクト]** をクリックします。Visual C# テンプレートで、**[コンソール アプリ (.NET Core)]** を選び、プロジェクトの名前を設定して、**[OK]** をクリックします。</span><span class="sxs-lookup"><span data-stu-id="47594-114">In Visual Studio, do this by clicking **File**, **New**, and then clicking **Project...**.  Under the Visual C# templates, select **Console App (.NET Core)**, name your project, and then click **OK**.</span></span>

![[新しいプロジェクト] ダイアログ](media/dotnet-sdk-azure-get-started/new-project.png)

<span data-ttu-id="47594-116">新しいコンソール アプリが作成されたら、**[ツール]**、**[NuGet パッケージ マネージャー]**、**[パッケージ マネージャー コンソール]** の順にクリックして、パッケージ マネージャー コンソールを開きます。</span><span class="sxs-lookup"><span data-stu-id="47594-116">When the new console app is created, open the Package Manager Console by clicking **Tools**, **NuGet Package Manager**, and then click **Package Manager Console**.</span></span>  <span data-ttu-id="47594-117">コンソールで、次の 3 つのコマンドを実行して、必要なパッケージを入手します。</span><span class="sxs-lookup"><span data-stu-id="47594-117">In the console, get the packages you'll need by executing the following three commands:</span></span>

```powershell
# Azure Management Libraries for .NET (Fluent)
Install-Package Microsoft.Azure.Management.Fluent

# Azure Store client libraries
Install-Package WindowsAzure.Storage

# SQL Database client libraries
Install-Package System.Data.SqlClient
```

## <a name="directives"></a><span data-ttu-id="47594-118">ディレクティブ</span><span class="sxs-lookup"><span data-stu-id="47594-118">Directives</span></span>

<span data-ttu-id="47594-119">アプリケーションの `Program.cs` ファイルを編集します。</span><span class="sxs-lookup"><span data-stu-id="47594-119">Edit your application's `Program.cs` file.</span></span>  <span data-ttu-id="47594-120">最上部の `using` ディレクティブを次の内容で置き換えます。</span><span class="sxs-lookup"><span data-stu-id="47594-120">Replace the `using` directives at the top with the following:</span></span>

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

## <a name="create-a-virtual-machine"></a><span data-ttu-id="47594-121">仮想マシンの作成</span><span class="sxs-lookup"><span data-stu-id="47594-121">Create a virtual machine</span></span>

<span data-ttu-id="47594-122">この例では、仮想マシンをデプロイします。</span><span class="sxs-lookup"><span data-stu-id="47594-122">This example deploys a virtual machine.</span></span> 

<span data-ttu-id="47594-123">`Main` メソッドを次のコードで置き換えます。</span><span class="sxs-lookup"><span data-stu-id="47594-123">Replace the `Main` method with the following.</span></span>  <span data-ttu-id="47594-124">仮想マシンの実際の `username` と `password` を指定してください。</span><span class="sxs-lookup"><span data-stu-id="47594-124">Be sure to provide an actual `username` and `password` for the virtual machine.</span></span>

```csharp
static void Main(string[] args)
{
    // Set some variables...
    string username = "MY_USERNAME";
    string password = "MY_PASSWORD";
    string rgName = "sampleResourceGroup";
    string windowsVmName = "sampleWindowsVM";
    string publicIpDnsLabel = "samplePublicIP";

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

<span data-ttu-id="47594-125">**F5** キーを押してサンプルを実行します。</span><span class="sxs-lookup"><span data-stu-id="47594-125">Press **F5** to run the sample.</span></span>

<span data-ttu-id="47594-126">数分後、プログラムが終了すると、Enter キーを押すように求められます。</span><span class="sxs-lookup"><span data-stu-id="47594-126">After several minutes, the program will finish, prompting you to press enter.</span></span> <span data-ttu-id="47594-127">Enter キーを押した後、PowerShell を使ってサブスクリプションで仮想マシンを確認します。</span><span class="sxs-lookup"><span data-stu-id="47594-127">After pressing enter, verify the virtual machine in your subscription with PowerShell:</span></span>

```powershell
Get-AzureRmVm -ResourceGroupName sampleResourceGroup
```

## <a name="deploy-a-web-app-from-a-github-repo"></a><span data-ttu-id="47594-128">GitHub リポジトリからの Web アプリのデプロイ</span><span class="sxs-lookup"><span data-stu-id="47594-128">Deploy a web app from a GitHub repo</span></span>

<span data-ttu-id="47594-129">次に、既存の GitHub リポジトリから新しい Web アプリを作成してデプロイするように、コードを変更します。</span><span class="sxs-lookup"><span data-stu-id="47594-129">Now you'll modify your code to create a deploy a new web app from an existing GitHub repository.</span></span> <span data-ttu-id="47594-130">`Main` メソッドを次のコードに置き換えます。</span><span class="sxs-lookup"><span data-stu-id="47594-130">Replace the `Main` method with the following code:</span></span>

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

<span data-ttu-id="47594-131">前と同じように **F5** キーを押してコードを実行します。</span><span class="sxs-lookup"><span data-stu-id="47594-131">Run the code as before by pressing **F5**.</span></span>  <span data-ttu-id="47594-132">ブラウザーを開き、コンソールに表示される URL に移動して、デプロイを確認します。</span><span class="sxs-lookup"><span data-stu-id="47594-132">Verify the deployment by opening a browser and navigating to URL displayed in the console.</span></span>

## <a name="connect-to-a-sql-database"></a><span data-ttu-id="47594-133">SQL Database への接続</span><span class="sxs-lookup"><span data-stu-id="47594-133">Connect to a SQL database</span></span>

<span data-ttu-id="47594-134">この例では、新しい Azure SQL Database を作成し、いくつかの SQL 操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="47594-134">This example creates a new Azure SQL Database and performs a few SQL operations.</span></span>

<span data-ttu-id="47594-135">`Main` メソッドを次のように置き換えて、`dbPassword` に強力なパスワードを割り当てます。</span><span class="sxs-lookup"><span data-stu-id="47594-135">Replace the `Main` method with the following, making sure to assign a strong password for `dbPassword`:</span></span>

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

<span data-ttu-id="47594-136">前と同じように **F5** キーを押してコードを実行します。</span><span class="sxs-lookup"><span data-stu-id="47594-136">Run the code as before by pressing **F5**.</span></span>  <span data-ttu-id="47594-137">サーバーが作成されて意図したとおりに動作していることはコンソール出力で確認できますが、好みに応じて、SQL Server Management Studio などのツールで直接接続してもかまいません。</span><span class="sxs-lookup"><span data-stu-id="47594-137">The console output should validate that the server was created and works as expected, but you can connect to it directly with a tool like SQL Server Management Studio if you like.</span></span>

## <a name="write-a-blob-into-a-new-storage-account"></a><span data-ttu-id="47594-138">新しいストレージ アカウントへの BLOB の書き込み</span><span class="sxs-lookup"><span data-stu-id="47594-138">Write a blob into a new storage account</span></span>

<span data-ttu-id="47594-139">この例では、ストレージ アカウントを作成し、BLOB をアップロードします。</span><span class="sxs-lookup"><span data-stu-id="47594-139">This example creates a storage account and upload a blob.</span></span>  

<span data-ttu-id="47594-140">`Main` メソッドを次のコードで置き換えます。</span><span class="sxs-lookup"><span data-stu-id="47594-140">Replace the `Main` method with the following.</span></span>

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

<span data-ttu-id="47594-141">**F5** キーを押してサンプルを実行します。</span><span class="sxs-lookup"><span data-stu-id="47594-141">Press **F5** to run the sample.</span></span>

<span data-ttu-id="47594-142">数分後、プログラムが終了します。</span><span class="sxs-lookup"><span data-stu-id="47594-142">After several minutes, the program finishes.</span></span> <span data-ttu-id="47594-143">コンソールに表示される URL を参照して、BLOB がアップロードされたことを確認します。</span><span class="sxs-lookup"><span data-stu-id="47594-143">Verify the blob was uploaded by browsing to the URL displayed in the console.</span></span>  <span data-ttu-id="47594-144">"Hello, Azure!" というテキストが</span><span class="sxs-lookup"><span data-stu-id="47594-144">You should see the text "Hello, Azure!"</span></span> <span data-ttu-id="47594-145">ブラウザーに表示されるはずです。</span><span class="sxs-lookup"><span data-stu-id="47594-145">in your browser.</span></span>

## <a name="clean-up"></a><span data-ttu-id="47594-146">クリーンアップ</span><span class="sxs-lookup"><span data-stu-id="47594-146">Clean up</span></span>

> [!IMPORTANT]
> <span data-ttu-id="47594-147">このチュートリアルで作成したリソースをクリーンアップしないと、引き続き課金されます。</span><span class="sxs-lookup"><span data-stu-id="47594-147">If you don't clean up your resources from this tutorial, you will continue to be charged for them.</span></span>  <span data-ttu-id="47594-148">忘れずにこの手順を実行してください。</span><span class="sxs-lookup"><span data-stu-id="47594-148">Be sure to do this step.</span></span>

<span data-ttu-id="47594-149">PowerShell で次のように入力して、作成したすべてのリソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="47594-149">Delete all the resources you created by entering the following in PowerShell:</span></span>

```powershell
Remove-AzureRmResourceGroup -ResourceGroupName sampleResourceGroup
```

## <a name="explore-more-samples"></a><span data-ttu-id="47594-150">その他のサンプルを探す</span><span class="sxs-lookup"><span data-stu-id="47594-150">Explore more samples</span></span>

<span data-ttu-id="47594-151">.NET 用 Azure ライブラリを使ってリソースを管理したりタスクを自動化したりする方法をさらに詳しく知るには、[仮想マシン](dotnet-sdk-azure-virtual-machine-samples.md)、[Web アプリ](dotnet-sdk-azure-web-apps-samples.md)、[SQL データベース](dotnet-sdk-azure-sql-database-samples.md)に関するサンプル コードを参照してください。</span><span class="sxs-lookup"><span data-stu-id="47594-151">To learn more about how to use the Azure libraries for .NET to manage resources and automate tasks, see our sample code for [virtual machines](dotnet-sdk-azure-virtual-machine-samples.md), [web apps](dotnet-sdk-azure-web-apps-samples.md) and [SQL database](dotnet-sdk-azure-sql-database-samples.md).</span></span>

## <a name="reference"></a><span data-ttu-id="47594-152">リファレンス</span><span class="sxs-lookup"><span data-stu-id="47594-152">Reference</span></span>

<span data-ttu-id="47594-153">すべてのパッケージには、[リファレンス](http://docs.microsoft.com/dotnet/api)が提供されています。</span><span class="sxs-lookup"><span data-stu-id="47594-153">A [reference](http://docs.microsoft.com/dotnet/api) is available for all packages.</span></span>

[!include[Contribute and community](includes/contribute.md)]
