---
title: Azure .NET Storage API
description: .NET 用 Azure Storage ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, ストレージ, BLOB
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: storage
ms.custom: devcenter, svc-overview
ms.openlocfilehash: e953f38f103631f94b844d803d20a6576e841ed3
ms.sourcegitcommit: 2a00655810b9b2c78a3edb31c974a9989bff8bc0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/11/2018
ms.locfileid: "42623354"
---
# <a name="azure-storage-apis-for-net"></a><span data-ttu-id="4e64b-104">.NET 用 Azure Storage API</span><span class="sxs-lookup"><span data-stu-id="4e64b-104">Azure Storage APIs for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="4e64b-105">概要</span><span class="sxs-lookup"><span data-stu-id="4e64b-105">Overview</span></span>

<span data-ttu-id="4e64b-106">.NET アプリケーションから [Azure Storage](https://docs.microsoft.com/azure/storage/storage-introduction) を使って、ファイル、BLOB (オブジェクト) データ、キーと値のペア、メッセージの読み取りと書き込みを行います。</span><span class="sxs-lookup"><span data-stu-id="4e64b-106">Read and write files, blob (object) data, key-value pairs, and messages from your .NET applications with [Azure Storage](https://docs.microsoft.com/azure/storage/storage-introduction).</span></span>

<span data-ttu-id="4e64b-107">Azure Storage を使い始めるには、「[.NET を使用して Azure Blob Storage を使用する](/azure/storage/storage-dotnet-how-to-use-blobs)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="4e64b-107">To get started with Azure Storage, see [Get started with Azure Blob storage using .NET](/azure/storage/storage-dotnet-how-to-use-blobs).</span></span>

## <a name="client-library"></a><span data-ttu-id="4e64b-108">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="4e64b-108">Client library</span></span>

<span data-ttu-id="4e64b-109">[接続文字列](/azure/storage/storage-create-storage-account#manage-your-storage-account)を使って Azure Storage アカウントに接続したうえで、クライアント ライブラリのクラスとメソッドを使って、BLOB、テーブル、ファイル、Queue Storage を操作します。</span><span class="sxs-lookup"><span data-stu-id="4e64b-109">Use [connection strings](/azure/storage/storage-create-storage-account#manage-your-storage-account) to connect to an Azure Storage account, then use the client libraries' classes and methods to work with blob, table, file, or queue storage.</span></span>

<span data-ttu-id="4e64b-110">[NuGet パッケージ](https://www.nuget.org/packages/WindowsAzure.Storage)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="4e64b-110">Install the [NuGet package](https://www.nuget.org/packages/WindowsAzure.Storage) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="4e64b-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="4e64b-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package WindowsAzure.Storage
```

### <a name="net-core-cli"></a><span data-ttu-id="4e64b-112">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="4e64b-112">.NET Core CLI</span></span>

```bash
dotnet add package WindowsAzure.Storage
```

### <a name="code-example"></a><span data-ttu-id="4e64b-113">コード例</span><span class="sxs-lookup"><span data-stu-id="4e64b-113">Code Example</span></span>

<span data-ttu-id="4e64b-114">この例では、既存のストレージ アカウントの新しいコンテナーに新しい BLOB を作成します。</span><span class="sxs-lookup"><span data-stu-id="4e64b-114">This example creates a new blob to a new container in an existing storage account.</span></span>

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
> [<span data-ttu-id="4e64b-115">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="4e64b-115">Explore the client APIs</span></span>](/dotnet/api/overview/azure/storage/client)

## <a name="management-apis"></a><span data-ttu-id="4e64b-116">管理 API</span><span class="sxs-lookup"><span data-stu-id="4e64b-116">Management APIs</span></span>

<span data-ttu-id="4e64b-117">Azure Storage アカウントと接続キーの作成と管理は、Management API を使って行います。</span><span class="sxs-lookup"><span data-stu-id="4e64b-117">Create and manage Azure Storage accounts and connection keys with the management API.</span></span>

<span data-ttu-id="4e64b-118">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Storage.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="4e64b-118">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Storage.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="4e64b-119">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="4e64b-119">Visual Studio package manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Storage.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="4e64b-120">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="4e64b-120">.NET Core CLI</span></span>

````bash
dotnet add package Microsoft.Azure.Management.Storage.Fluent
````

### <a name="code-example"></a><span data-ttu-id="4e64b-121">コード例</span><span class="sxs-lookup"><span data-stu-id="4e64b-121">Code Example</span></span>

<span data-ttu-id="4e64b-122">この例では、ストレージ アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="4e64b-122">This example creates a storage account.</span></span>

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
> [<span data-ttu-id="4e64b-123">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="4e64b-123">Explore the management APIs</span></span>](/dotnet/api/overview/azure/storage/management)

## <a name="samples"></a><span data-ttu-id="4e64b-124">サンプル</span><span class="sxs-lookup"><span data-stu-id="4e64b-124">Samples</span></span>

* [<span data-ttu-id="4e64b-125">.Net での Azure Blob Storage の概要</span><span class="sxs-lookup"><span data-stu-id="4e64b-125">Get started with Azure Blob Storage in .NET</span></span>](https://azure.microsoft.com/resources/samples/storage-blob-dotnet-getting-started/) 
* [<span data-ttu-id="4e64b-126">.Net での Azure Queue Storage の概要</span><span class="sxs-lookup"><span data-stu-id="4e64b-126">Get started with Azure Queue Storage in .NET</span></span>](https://azure.microsoft.com/resources/samples/storage-queue-dotnet-getting-started/)

<span data-ttu-id="4e64b-127">Azure Storage のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=storage)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="4e64b-127">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=storage) of Azure Storage samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package