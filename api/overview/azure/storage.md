---
title: Azure .NET Storage API
description: ".NET 用 Azure Storage ライブラリのリファレンス"
keywords: "Azure, .NET, SDK, API, ストレージ, BLOB"
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/17/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 4e494952b48bfbf3b10f9af9936648634353db78
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-storage-apis-for-net"></a>.NET 用 Azure Storage API

## <a name="overview"></a>概要

.NET アプリケーションから [Azure Storage](https://review.docs.microsoft.com/en-us/azure/storage/storage-introduction) を使って、ファイル、BLOB (オブジェクト) データ、キーと値のペア、メッセージの読み取りと書き込みを行います。

Azure Storage を使い始めるには、「[.NET を使用して Azure Blob Storage を使用する](/azure/storage/storage-dotnet-how-to-use-blobs)」をご覧ください。

## <a name="client-library"></a>クライアント ライブラリ

[接続文字列](/azure/storage/storage-create-storage-account#manage-your-storage-account)を使って Azure Storage アカウントに接続したうえで、クライアント ライブラリのクラスとメソッドを使って、BLOB、テーブル、ファイル、Queue Storage を操作します。

[NuGet パッケージ](https://www.nuget.org/packages/WindowsAzure.Storage)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package WindowsAzure.Storage
```

### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package WindowsAzure.Storage
```

### <a name="code-example"></a>コード例

この例では、既存のストレージ アカウントの新しいコンテナーに新しい BLOB を作成します。

```csharp
/* Include these "using" directives...
using Microsoft.WindowsAzure.Storage;
using Microsoft.WindowsAzure.Storage.Blob;
*/

string storageConnectionString = "DefaultEndpointsProtocol=https;"
    + "AccountName=[Storage Account Name]"
    + ";AccountKey=[Storage Account Key]"
    + ";EndpointSuffix=core.windows.net";

CloudStorageAccount account = CloudStorageAccount.Parse(storageConnectionString);
CloudBlobClient serviceClient = account.CreateCloudBlobClient();

// Create container. Name must be lower case.
Console.WriteLine("Creating container...");
var container = serviceClient.GetContainerReference("mycontainer");
container.CreateIfNotExistsAsync().Wait();

// write a blob to the container
CloudBlockBlob blob = container.GetBlockBlobReference("helloworld.txt");
blob.UploadTextAsync("Hello, World!").Wait();
```

> [!div class="nextstepactions"]
> [クライアント API を探す](/dotnet/api/overview/azure/storage/client)

## <a name="management-apis"></a>管理 API

Azure Storage アカウントと接続キーの作成と管理は、Management API を使って行います。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Storage.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.Storage.Fluent
```

#### <a name="net-core-cli"></a>.NET Core CLI

````bash
dotnet add package Microsoft.Azure.Management.Storage.Fluent
````

### <a name="code-example"></a>コード例

この例では、ストレージ アカウントを作成します。

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Management.Storage.Fluent
*/

IStorageAccount storage = azure.StorageAccounts.Define(storageAccountName)
    .WithRegion(Region.USEast)
    .WithNewResourceGroup(rgName)
    .Create();
```

> [!div class="nextstepactions"]
> [Management API を探す](/dotnet/api/overview/azure/storage/management)

## <a name="samples"></a>サンプル

* [.Net での Azure Blob Storage の概要](https://azure.microsoft.com/resources/samples/storage-blob-dotnet-getting-started/) 
* [.Net での Azure Queue Storage の概要](https://azure.microsoft.com/resources/samples/storage-queue-dotnet-getting-started/)

Azure Storage のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=storage)をご覧ください。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package