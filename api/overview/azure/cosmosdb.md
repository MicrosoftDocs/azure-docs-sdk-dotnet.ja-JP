---
title: ".NET 用 Azure CosmosDB ライブラリ"
description: ".NET 用 Azure CosmosDB ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, CosmosDB
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/17/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: babf34e98dae439a2dc3d4c63bd638335428e935
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-cosmosdb-libraries-for-net"></a><span data-ttu-id="f848f-104">.NET 用 Azure CosmosDB ライブラリ</span><span class="sxs-lookup"><span data-stu-id="f848f-104">Azure CosmosDB libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="f848f-105">概要</span><span class="sxs-lookup"><span data-stu-id="f848f-105">Overview</span></span>

<span data-ttu-id="f848f-106">[Azure CosmosDB](https://docs.microsoft.com/azure/cosmos-db/introduction) は、複数の異なる種類のデータベースをサポートする、スケーラブルな分散型データ ストアです。</span><span class="sxs-lookup"><span data-stu-id="f848f-106">[Azure CosmosDB](https://docs.microsoft.com/azure/cosmos-db/introduction) is a distributed and scalable data store, supporting multiple different types of databases.</span></span>

## <a name="client-library"></a><span data-ttu-id="f848f-107">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="f848f-107">Client library</span></span>

<span data-ttu-id="f848f-108">CosmosDB データ ストアのデータにアクセスしたり、CosmosDB データ ストアにデータを保存したりするには、CosmosDB .NET クライアント ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="f848f-108">Use the CosmosDB .NET client library to access and store data in a CosmosDB data store.</span></span>

<span data-ttu-id="f848f-109">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="f848f-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="f848f-110">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="f848f-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.DocumentDB.Core
```

#### <a name="net-core-cli"></a><span data-ttu-id="f848f-111">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="f848f-111">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.DocumentDB.Core
```

### <a name="code-example"></a><span data-ttu-id="f848f-112">コード例</span><span class="sxs-lookup"><span data-stu-id="f848f-112">Code Example</span></span>

<span data-ttu-id="f848f-113">この例では、既存の CosmosDB DocumentDB API データベースに接続し、コレクションからドキュメントを読み取って、`Item` オブジェクトとして逆シリアル化します。</span><span class="sxs-lookup"><span data-stu-id="f848f-113">This example connects to an existing CosmosDB DocumentDB API database, reads a document from a collection, and deserializes it as an `Item` object.</span></span>

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Documents.Client;
*/

DocumentClient client = new DocumentClient(endpointUri, authKeyString);
Uri documentUri = UriFactory.CreateDocumentUri("MyDatabaseName", "MyCollectionName", "DocumentId");
// "Item" is a class defined elsewhere...
Item item = client.ReadDocumentAsync<Item>(documentUri).ToString()).Result;
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="f848f-114">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="f848f-114">Explore the client APIs</span></span>](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a><span data-ttu-id="f848f-115">サンプル</span><span class="sxs-lookup"><span data-stu-id="f848f-115">Samples</span></span>

* [<span data-ttu-id="f848f-116">Azure Cosmos DB の MongoDB API を使用した .NET アプリの開発</span><span class="sxs-lookup"><span data-stu-id="f848f-116">Developing a .NET app using Azure Cosmos DB's MongoDB API</span></span>](https://azure.microsoft.com/en-us/resources/samples/azure-cosmos-db-mongodb-dotnet-getting-started/)

<span data-ttu-id="f848f-117">Azure Cosmos DB のサンプルの[完全な一覧](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&term=cosmosdb)を表示します。</span><span class="sxs-lookup"><span data-stu-id="f848f-117">View the [complete list](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&term=cosmosdb) of Azure Cosmos DB samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
