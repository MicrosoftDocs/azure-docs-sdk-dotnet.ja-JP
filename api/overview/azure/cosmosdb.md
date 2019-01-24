---
title: .NET 用 Azure Cosmos DB ライブラリ
description: .NET 用 Azure Cosmos DB ライブラリのリファレンス
ms.date: 08/31/2018
ms.topic: reference
ms.service: cosmos-db
ms.openlocfilehash: 95fcd8468c3d472cfcadeaae3b56ae789c3b1e7a
ms.sourcegitcommit: 55ee51501678d1575e5159f0ac0e475b5bf9daf3
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/22/2019
ms.locfileid: "54453996"
---
# <a name="azure-cosmos-db-libraries-for-net"></a><span data-ttu-id="4e80a-103">.NET 用 Azure Cosmos DB ライブラリ</span><span class="sxs-lookup"><span data-stu-id="4e80a-103">Azure Cosmos DB libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="4e80a-104">概要</span><span class="sxs-lookup"><span data-stu-id="4e80a-104">Overview</span></span>

<span data-ttu-id="4e80a-105">[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) は、グローバル分散型のマルチモデル データベース サービスです。</span><span class="sxs-lookup"><span data-stu-id="4e80a-105">[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) is a globally distributed, multi-model database service.</span></span> <span data-ttu-id="4e80a-106">これは、包括的な SLA により、任意の数の地理的リージョン間でスループットとストレージを弾力的かつ個別にスケーリングできるように設計されています。</span><span class="sxs-lookup"><span data-stu-id="4e80a-106">It is designed to elastically and independently scale throughput and storage across any number of geographical regions with a comprehensive SLA.</span></span> <span data-ttu-id="4e80a-107">Azure Cosmos DB を使用すると、API とプログラミング モデルを使って、ドキュメント、キー値、ワイドカラム、およびグラフのデータベースを格納し、アクセスできます。</span><span class="sxs-lookup"><span data-stu-id="4e80a-107">With Azure Cosmos DB, you can store and access document, key-value, wide-column, and graph databases by using APIs and programming models.</span></span> 

<span data-ttu-id="4e80a-108">[Cosmos DB を使い始めます](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet)。</span><span class="sxs-lookup"><span data-stu-id="4e80a-108">[Get started with Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet).</span></span>

## <a name="client-library"></a><span data-ttu-id="4e80a-109">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="4e80a-109">Client library</span></span>

<span data-ttu-id="4e80a-110">既存の Azure Cosmos DB データ ストアのデータにアクセスしたり、データを保存したりするには、Azure Cosmos DB .NET クライアント ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="4e80a-110">Use the Azure Cosmos DB .NET client library to access and store data in an existing Azure Cosmos DB data store.</span></span> <span data-ttu-id="4e80a-111">新しい Azure Cosmos DB アカウントの作成を自動化するには、Azure Portal、CLI、または PowerShell を使用します。</span><span class="sxs-lookup"><span data-stu-id="4e80a-111">To automate creation of a new Azure Cosmos DB account, use the Azure portal, CLI, or PowerShell.</span></span>

<span data-ttu-id="4e80a-112">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="4e80a-112">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

<span data-ttu-id="4e80a-113">バージョン 2.x をインストールするには、次の手順を実行します。</span><span class="sxs-lookup"><span data-stu-id="4e80a-113">To install version 2.x:</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="4e80a-114">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="4e80a-114">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.DocumentDB.Core
```

#### <a name="net-core-cli"></a><span data-ttu-id="4e80a-115">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="4e80a-115">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.DocumentDB.Core
```

<span data-ttu-id="4e80a-116">.NET Standard を対象とするバージョン 3.0 のプレビューをインストールするには、次の手順を実行します。</span><span class="sxs-lookup"><span data-stu-id="4e80a-116">To install the preview of version 3.0, which targets .NET standard:</span></span> 

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="4e80a-117">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="4e80a-117">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Cosmos -prerelease
```

#### <a name="net-core-cli"></a><span data-ttu-id="4e80a-118">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="4e80a-118">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Cosmos
```


### <a name="code-example"></a><span data-ttu-id="4e80a-119">コード例</span><span class="sxs-lookup"><span data-stu-id="4e80a-119">Code Example</span></span>

<span data-ttu-id="4e80a-120">この例では、既存の Azure Cosmos DB SQL API データベースに接続し、コレクションからドキュメントを読み取って、`TodoItem` オブジェクトとして逆シリアル化します。</span><span class="sxs-lookup"><span data-stu-id="4e80a-120">This example connects to an existing Azure Cosmos DB SQL API database, reads a document from a collection, and deserializes it as an `TodoItem` object.</span></span> <span data-ttu-id="4e80a-121">この例では、.NET SDK のバージョン 2.x を使用しています。</span><span class="sxs-lookup"><span data-stu-id="4e80a-121">This example uses version 2.x of the .NET SDK.</span></span>   

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Documents.Client;
*/

DocumentClient client = new DocumentClient(endpointUri, authKeyString);
Uri documentUri = UriFactory.CreateDocumentUri("MyDatabaseName", "MyCollectionName", "DocumentId");
var todoItem = client.ReadDocumentAsync<TodoItem>(documentUri);
```

<span data-ttu-id="4e80a-122">この例では、既存の Azure Cosmos DB SQL API データベースに接続して、新しいデータベースとコンテナーを作成し、コンテナーから項目を読み取って、`TodoItem` オブジェクトに逆シリアル化します。</span><span class="sxs-lookup"><span data-stu-id="4e80a-122">This example connects to an existing Azure Cosmos DB SQL API database, creates a new database and container, reads an item from the container, and deserializes it to a `TodoItem` object.</span></span> <span data-ttu-id="4e80a-123">この例では、.NET SDK のバージョン 3.x を使用しています。</span><span class="sxs-lookup"><span data-stu-id="4e80a-123">This example uses version 3.x of the .NET SDK.</span></span>   

```csharp
using (CosmosClient cosmosClient = new CosmosClient("endpoint", "primaryKey"))
{
    // Read item from container
    CosmosItemResponse<TodoItem> todoItemResponse = await cosmosClient.Databases["DatabaseId"].Containers["ContainerId"].Items.ReadItemAsync<TodoItem>("partitionKeyValue", "ItemId");
}
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="4e80a-124">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="4e80a-124">Explore the client APIs</span></span>](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a><span data-ttu-id="4e80a-125">サンプル</span><span class="sxs-lookup"><span data-stu-id="4e80a-125">Samples</span></span>

* [<span data-ttu-id="4e80a-126">Azure Cosmos DB の SQL API (バージョン 2.x) を使用した .NET アプリの開発</span><span class="sxs-lookup"><span data-stu-id="4e80a-126">Developing a .NET app using Azure Cosmos DB's SQL API (Version 2.x)</span></span>](https://github.com/Azure-Samples/documentdb-dotnet-todo-app/)
* [<span data-ttu-id="4e80a-127">Azure Cosmos DB の SQL API (バージョン 3.x プレビュー) を使用した .NET アプリの開発</span><span class="sxs-lookup"><span data-stu-id="4e80a-127">Developing a .NET app using Azure Cosmos DB's SQL API (Version 3.x Preview)</span></span>](https://github.com/Azure-Samples/cosmos-dotnet-todo-app/)
* [<span data-ttu-id="4e80a-128">Azure Cosmos DB の SQL API (バージョン 3.x プレビュー) を使用した .NET Core アプリの開発</span><span class="sxs-lookup"><span data-stu-id="4e80a-128">Developing a .NET Core app using Azure Cosmos DB's SQL API (Version 3.x Preview)</span></span>](https://github.com/Azure-Samples/cosmos-dotnet-core-getting-started)

<span data-ttu-id="4e80a-129">Azure Cosmos DB のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb)を表示します。</span><span class="sxs-lookup"><span data-stu-id="4e80a-129">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb) of Azure Cosmos DB samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
