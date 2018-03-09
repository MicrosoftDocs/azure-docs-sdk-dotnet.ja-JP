---
title: ".NET 用 Azure ライブラリを使った認証"
description: ".NET 用 Azure ライブラリを使って認証を行います"
keywords: "Azure, .NET, SDK, API, 認証, active directory, サービス プリンシパル"
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: 783b5ebf14abad992c18726df7232e4f3a68b72b
ms.sourcegitcommit: 3ba0ff4463338a0ab0f3f15a7601b89417c06970
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/05/2018
---
# <a name="authenticate-with-the-azure-libraries-for-net"></a>.NET 用 Azure ライブラリを使った認証

## <a name="connect-to-services-with-connection-strings"></a>接続文字列を使ってサービスに接続する

ほとんどの Azure サービス ライブラリでは、認証のために接続文字列またはキーが必要です。 たとえば、SQL Database は標準の SQL 接続文字列を使います。

```csharp
var builder = new SqlConnectionStringBuilder();
builder.DataSource = "example.database.windows.net";
builder.InitialCatalog = "MyDatabase";
builder.UserID = "sampleuser@example"; // Format user ID as "user@server"
builder.Password = password;
builder.Encrypt = true;
builder.TrustServerCertificate = true;
                
using (var conn = new SqlConnection(builder.ConnectionString))
{
    conn.Open();
    // Do things with the connection...
    // ...
}
```

Azure Storage はストレージ キーを使います。

```csharp
string storageConnectionString = "DefaultEndpointsProtocol=https;"
        + "AccountName=" + storageName
        + ";AccountKey=" + storageKey
        + ";EndpointSuffix=core.windows.net";

var account = CloudStorageAccount.Parse(storageConnectionString);
// Do things with the account here...
```

サービス接続文字列は [CosmosDB](/azure/documentdb/documentdb-dotnet-application#a-nametoc395637769astep-5-wiring-up-azure-cosmos-db)、[Redis Cache](/azure/redis-cache/cache-dotnet-how-to-use-azure-redis-cache)、[Service Bus](/azure/service-bus-messaging/service-bus-dotnet-get-started-with-queues) などの他の Azure サービスで使われ、Azure Portal、CLI、または PowerShell を使ってこの文字列を取得できます。  また、コード内から .NET 用 Azure 管理ライブラリを使い、リソースを照会することによって接続文字列を作成することもできます。 

次のスニペットでは、管理ライブラリを使ってストレージ アカウントの接続文字列を作成しています。

```csharp
// Get a storage account
var storage = azure.StorageAccounts.GetByResourceGroup("myResourceGroup", "myStorageAccount");

// Extract the keys
var storageKeys = storage.GetKeys();

// Build the connection string
string storageConnectionString = "DefaultEndpointsProtocol=https;"
        + "AccountName=" + storage.Name
        + ";AccountKey=" + storageKeys[0].Value
        + ";EndpointSuffix=core.windows.net";

// Connect
var account = CloudStorageAccount.Parse(storageConnectionString);

// Do things with the account here...
```

その他のライブラリでは、[サービス プリンシパル](https://docs.microsoft.com/azure/active-directory/develop/active-directory-application-objects)を使ってアプリケーションを実行し、許可された資格情報で動作することをアプリケーションに承認する必要があります。 この構成は、以下に示した管理ライブラリのオブジェクト ベースの認証ステップと似ています。

## <a name="mgmt-auth"></a>.NET 認証のための Azure 管理ライブラリ

[!include[Create service principal](includes/create-sp.md)]

サービス プリンシパルを作成した後は、リソースを作成および管理するサービス プリンシパルの認証に 2 つのオプションを利用できます。

どちらのオプションでも、次の NuGet パッケージをプロジェクトに追加する必要があります。

```
Install-Package Microsoft.Azure.Management.Fluent
Install-Package Microsoft.Azure.Management.ResourceManager.Fluent
```

### <a name="authenticate-with-token-credentials"></a>トークン資格情報で認証を行う

最初の方法では、コードでトークン資格情報オブジェクトを作成します。  構成ファイル、レジストリ、または Azure Key Vault に、資格情報を安全に保存する必要があります。

```csharp
var credentials = SdkContext.AzureCredentialsFactory
    .FromServicePrincipal(clientId,
    clientSecret,
    tenantId, 
    AzureEnvironment.AzureGlobalCloud);
```

- clientId: サービス プリンシパルの出力の *ApplicationId* の値を使います。
- clientSecret: `New-AzureRmADServicePrincipal` を実行したときに割り当てた *-Password* パラメーターを使います (引用符は不要)。
- tenantId: `Login-AzureRmAccount` を実行したときの *TenantId* の値を使います。

その後、API を使うためのエントリ ポイントとなる `Azure` オブジェクトを作成します。

```csharp
var azure = Microsoft.Azure.Management.Fluent.Azure
    .Configure()
    .Authenticate(credentials)
    .WithDefaultSubscription();
```

### <a name="mgmt-file"></a>ファイルベースの認証

ファイルベースの認証を使うと、プレーンテキスト ファイルにサービス プリンシパルの資格情報を格納し、ファイル システム内で保護できます。

[!include[File-based authentication](includes/file-based-auth.md)]

ファイルの内容を読み取り、API を使うためのエントリ ポイントとなる `Azure` オブジェクトを作成します。

```csharp
// pull in the location of the authentication properties file from the environment 
var credentials = SdkContext.AzureCredentialsFactory
    .FromFile(Environment.GetEnvironmentVariable("AZURE_AUTH_LOCATION"));

var azure = Microsoft.Azure.Management.Fluent.Azure
    .Configure()
    .Authenticate(credentials)
    .WithDefaultSubscription();
```
