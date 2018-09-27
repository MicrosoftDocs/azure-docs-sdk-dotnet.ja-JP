---
title: .NET 用 Azure Cosmos DB ライブラリ
description: .NET 用 Azure Cosmos DB ライブラリのリファレンス
ms.date: 08/31/2018
ms.topic: reference
ms.service: cosmos-db
ms.openlocfilehash: 21a2f2168259528a0d27103783e34aa532d7e17a
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190798"
---
# <a name="azure-cosmos-db-libraries-for-net"></a><span data-ttu-id="07b46-103">.NET 用 Azure Cosmos DB ライブラリ</span><span class="sxs-lookup"><span data-stu-id="07b46-103">Azure Cosmos DB libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="07b46-104">概要</span><span class="sxs-lookup"><span data-stu-id="07b46-104">Overview</span></span>

<span data-ttu-id="07b46-105">[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) は、グローバル分散型のマルチモデル データベース サービスです。</span><span class="sxs-lookup"><span data-stu-id="07b46-105">[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) is a globally distributed, multi-model database service.</span></span> <span data-ttu-id="07b46-106">これは、包括的な SLA により、任意の数の地理的リージョン間でスループットとストレージを弾力的かつ個別にスケーリングできるように設計されています。</span><span class="sxs-lookup"><span data-stu-id="07b46-106">It is designed to elastically and independently scale throughput and storage across any number of geographical regions with a comprehensive SLA.</span></span> <span data-ttu-id="07b46-107">Azure Cosmos DB を使用すると、API とプログラミング モデルを使って、ドキュメント、キー値、ワイドカラム、およびグラフのデータベースを格納し、アクセスできます。</span><span class="sxs-lookup"><span data-stu-id="07b46-107">With Azure Cosmos DB, you can store and access document, key-value, wide-column, and graph databases by using APIs and programming models.</span></span> 

<span data-ttu-id="07b46-108">[Cosmos DB を使い始めます](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet)。</span><span class="sxs-lookup"><span data-stu-id="07b46-108">[Get started with Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet).</span></span>

## <a name="client-library"></a><span data-ttu-id="07b46-109">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="07b46-109">Client library</span></span>

<span data-ttu-id="07b46-110">既存の Azure Cosmos DB データ ストアのデータにアクセスしたり、データを保存したりするには、Azure Cosmos DB .NET クライアント ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="07b46-110">Use the Azure Cosmos DB .NET client library to access and store data in an existing Azure Cosmos DB data store.</span></span> <span data-ttu-id="07b46-111">新しい Azure Cosmos DB アカウントの作成を自動化するには、Azure Portal、CLI、または PowerShell を使用します。</span><span class="sxs-lookup"><span data-stu-id="07b46-111">To automate creation of a new Azure Cosmos DB account, use the Azure portal, CLI, or PowerShell.</span></span>

<span data-ttu-id="07b46-112">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="07b46-112">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="07b46-113">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="07b46-113">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.DocumentDB.Core
```

#### <a name="net-core-cli"></a><span data-ttu-id="07b46-114">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="07b46-114">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.DocumentDB.Core
```

### <a name="code-example"></a><span data-ttu-id="07b46-115">コード例</span><span class="sxs-lookup"><span data-stu-id="07b46-115">Code Example</span></span>

<span data-ttu-id="07b46-116">この例では、既存の Azure Cosmos DB SQL API データベースに接続し、コレクションからドキュメントを読み取って、`Item` オブジェクトとして逆シリアル化します。</span><span class="sxs-lookup"><span data-stu-id="07b46-116">This example connects to an existing Azure Cosmos DB SQL API database, reads a document from a collection, and deserializes it as an `Item` object.</span></span>   

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Documents.Client;
*/

DocumentClient client = new DocumentClient(endpointUri, authKeyString);
Uri documentUri = UriFactory.CreateDocumentUri("MyDatabaseName", "MyCollectionName", "DocumentId");
SomeClass myObject = client.ReadDocumentAsync<SomeClass>(documentUri).ToString();
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="07b46-117">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="07b46-117">Explore the client APIs</span></span>](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a><span data-ttu-id="07b46-118">サンプル</span><span class="sxs-lookup"><span data-stu-id="07b46-118">Samples</span></span>

* [<span data-ttu-id="07b46-119">Azure Cosmos DB の MongoDB API を使用した .NET アプリの開発</span><span class="sxs-lookup"><span data-stu-id="07b46-119">Developing a .NET app using Azure Cosmos DB's MongoDB API</span></span>](https://azure.microsoft.com/resources/samples/azure-cosmos-db-mongodb-dotnet-getting-started/)

<span data-ttu-id="07b46-120">Azure Cosmos DB のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb)を表示します。</span><span class="sxs-lookup"><span data-stu-id="07b46-120">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb) of Azure Cosmos DB samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
