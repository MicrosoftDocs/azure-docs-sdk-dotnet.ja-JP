---
title: .NET 用 Azure CosmosDB ライブラリ
description: .NET 用 Azure CosmosDB ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, CosmosDB
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 11/17/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: cosmos-db
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 4791e00c18d00fbed13bdf2c626a24fed2ff2863
ms.sourcegitcommit: dbec35008347b581dd238b882354300e427bec70
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/02/2018
---
# <a name="azure-cosmosdb-libraries-for-net"></a><span data-ttu-id="b9bfe-104">.NET 用 Azure CosmosDB ライブラリ</span><span class="sxs-lookup"><span data-stu-id="b9bfe-104">Azure CosmosDB libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="b9bfe-105">概要</span><span class="sxs-lookup"><span data-stu-id="b9bfe-105">Overview</span></span>

<span data-ttu-id="b9bfe-106">[Azure CosmosDB](https://docs.microsoft.com/azure/cosmos-db/introduction) は、複数の異なる種類のデータベースをサポートする、スケーラブルな分散型データ ストアです。</span><span class="sxs-lookup"><span data-stu-id="b9bfe-106">[Azure CosmosDB](https://docs.microsoft.com/azure/cosmos-db/introduction) is a distributed and scalable data store, supporting multiple different types of databases.</span></span>

<span data-ttu-id="b9bfe-107">[CosmosDB を使ってみる](https://docs.microsoft.com/azure/cosmos-db/create-documentdb-dotnet)。</span><span class="sxs-lookup"><span data-stu-id="b9bfe-107">[Get started with CosmosDB](https://docs.microsoft.com/azure/cosmos-db/create-documentdb-dotnet).</span></span>

## <a name="client-library"></a><span data-ttu-id="b9bfe-108">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="b9bfe-108">Client library</span></span>

<span data-ttu-id="b9bfe-109">既存の CosmosDB データ ストアのデータにアクセスしたり、既存の CosmosDB データ ストアにデータを保存したりするには、CosmosDB .NET クライアント ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="b9bfe-109">Use the CosmosDB .NET client library to access and store data in an existing CosmosDB data store.</span></span>  <span data-ttu-id="b9bfe-110">新しい CosmosDB アカウントの作成を自動化するには、Azure Portal、CLI、または PowerShell を使用します。</span><span class="sxs-lookup"><span data-stu-id="b9bfe-110">To automate creation of a new CosmosDB account, use the Azure portal, CLI, or PowerShell.</span></span>

<span data-ttu-id="b9bfe-111">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="b9bfe-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="b9bfe-112">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="b9bfe-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.DocumentDB.Core
```

#### <a name="net-core-cli"></a><span data-ttu-id="b9bfe-113">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="b9bfe-113">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.DocumentDB.Core
```

### <a name="code-example"></a><span data-ttu-id="b9bfe-114">コード例</span><span class="sxs-lookup"><span data-stu-id="b9bfe-114">Code Example</span></span>

<span data-ttu-id="b9bfe-115">この例では、既存の CosmosDB DocumentDB API データベースに接続し、コレクションからドキュメントを読み取って、`Item` オブジェクトとして逆シリアル化します。</span><span class="sxs-lookup"><span data-stu-id="b9bfe-115">This example connects to an existing CosmosDB DocumentDB API database, reads a document from a collection, and deserializes it as an `Item` object.</span></span>   

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Documents.Client;
*/

DocumentClient client = new DocumentClient(endpointUri, authKeyString);
Uri documentUri = UriFactory.CreateDocumentUri("MyDatabaseName", "MyCollectionName", "DocumentId");
SomeClass myObject = client.ReadDocumentAsync<SomeClass>(documentUri).ToString()).Result;
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="b9bfe-116">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="b9bfe-116">Explore the client APIs</span></span>](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a><span data-ttu-id="b9bfe-117">サンプル</span><span class="sxs-lookup"><span data-stu-id="b9bfe-117">Samples</span></span>

* [<span data-ttu-id="b9bfe-118">Azure Cosmos DB の MongoDB API を使用した .NET アプリの開発</span><span class="sxs-lookup"><span data-stu-id="b9bfe-118">Developing a .NET app using Azure Cosmos DB's MongoDB API</span></span>](https://azure.microsoft.com/resources/samples/azure-cosmos-db-mongodb-dotnet-getting-started/)

<span data-ttu-id="b9bfe-119">Azure Cosmos DB のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb)を表示します。</span><span class="sxs-lookup"><span data-stu-id="b9bfe-119">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb) of Azure Cosmos DB samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
