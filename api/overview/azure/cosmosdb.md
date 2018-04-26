---
title: .NET 用 Azure Cosmos DB ライブラリ
description: .NET 用 Azure Cosmos DB ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Cosmos DB
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
ms.openlocfilehash: fa9bc7497ac189f18ee0ba14d72d4cdb23a05f0b
ms.sourcegitcommit: e1a0e91988bb849c75e9583a80e3e6d712083785
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/14/2018
---
# <a name="azure-cosmos-db-libraries-for-net"></a><span data-ttu-id="610f7-104">.NET 用 Azure Cosmos DB ライブラリ</span><span class="sxs-lookup"><span data-stu-id="610f7-104">Azure Cosmos DB libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="610f7-105">概要</span><span class="sxs-lookup"><span data-stu-id="610f7-105">Overview</span></span>

<span data-ttu-id="610f7-106">[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) は、複数の異なる種類のデータベースをサポートする、スケーラブルな分散型データ ストアです。</span><span class="sxs-lookup"><span data-stu-id="610f7-106">[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) is a distributed and scalable data store, supporting multiple different types of databases.</span></span>

<span data-ttu-id="610f7-107">[Cosmos DB を使い始めます](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet)。</span><span class="sxs-lookup"><span data-stu-id="610f7-107">[Get started with Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet).</span></span>

## <a name="client-library"></a><span data-ttu-id="610f7-108">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="610f7-108">Client library</span></span>

<span data-ttu-id="610f7-109">既存の Azure Cosmos DB データ ストアのデータにアクセスしたり、データを保存したりするには、Azure Cosmos DB .NET クライアント ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="610f7-109">Use the Azure Cosmos DB .NET client library to access and store data in an existing Azure Cosmos DB data store.</span></span>  <span data-ttu-id="610f7-110">新しい Azure Cosmos DB アカウントの作成を自動化するには、Azure Portal、CLI、または PowerShell を使用します。</span><span class="sxs-lookup"><span data-stu-id="610f7-110">To automate creation of a new Azure Cosmos DB account, use the Azure portal, CLI, or PowerShell.</span></span>

<span data-ttu-id="610f7-111">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="610f7-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="610f7-112">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="610f7-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.DocumentDB.Core
```

#### <a name="net-core-cli"></a><span data-ttu-id="610f7-113">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="610f7-113">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.DocumentDB.Core
```

### <a name="code-example"></a><span data-ttu-id="610f7-114">コード例</span><span class="sxs-lookup"><span data-stu-id="610f7-114">Code Example</span></span>

<span data-ttu-id="610f7-115">この例では、既存の Azure Cosmos DB SQL API データベースに接続し、コレクションからドキュメントを読み取って、`Item` オブジェクトとして逆シリアル化します。</span><span class="sxs-lookup"><span data-stu-id="610f7-115">This example connects to an existing Azure Cosmos DB SQL API database, reads a document from a collection, and deserializes it as an `Item` object.</span></span>   

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Documents.Client;
*/

DocumentClient client = new DocumentClient(endpointUri, authKeyString);
Uri documentUri = UriFactory.CreateDocumentUri("MyDatabaseName", "MyCollectionName", "DocumentId");
SomeClass myObject = client.ReadDocumentAsync<SomeClass>(documentUri).ToString()).Result;
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="610f7-116">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="610f7-116">Explore the client APIs</span></span>](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a><span data-ttu-id="610f7-117">サンプル</span><span class="sxs-lookup"><span data-stu-id="610f7-117">Samples</span></span>

* [<span data-ttu-id="610f7-118">Azure Cosmos DB の MongoDB API を使用した .NET アプリの開発</span><span class="sxs-lookup"><span data-stu-id="610f7-118">Developing a .NET app using Azure Cosmos DB's MongoDB API</span></span>](https://azure.microsoft.com/resources/samples/azure-cosmos-db-mongodb-dotnet-getting-started/)

<span data-ttu-id="610f7-119">Azure Cosmos DB のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb)を表示します。</span><span class="sxs-lookup"><span data-stu-id="610f7-119">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb) of Azure Cosmos DB samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
