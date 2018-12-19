---
title: .NET 用 Azure Cosmos DB ライブラリ
description: .NET 用 Azure Cosmos DB ライブラリのリファレンス
ms.date: 08/31/2018
ms.topic: reference
ms.service: cosmos-db
ms.openlocfilehash: 8ff565f1cd72eec2f574b45d04ceac526b8c5eb0
ms.sourcegitcommit: 01ec3adba39a6f946015552c28da0a9a6bb57180
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/08/2018
ms.locfileid: "53112020"
---
# <a name="azure-cosmos-db-libraries-for-net"></a>.NET 用 Azure Cosmos DB ライブラリ

## <a name="overview"></a>概要

[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) は、グローバル分散型のマルチモデル データベース サービスです。 これは、包括的な SLA により、任意の数の地理的リージョン間でスループットとストレージを弾力的かつ個別にスケーリングできるように設計されています。 Azure Cosmos DB を使用すると、API とプログラミング モデルを使って、ドキュメント、キー値、ワイドカラム、およびグラフのデータベースを格納し、アクセスできます。 

[Cosmos DB を使い始めます](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet)。

## <a name="client-library"></a>クライアント ライブラリ

既存の Azure Cosmos DB データ ストアのデータにアクセスしたり、データを保存したりするには、Azure Cosmos DB .NET クライアント ライブラリを使用します。 新しい Azure Cosmos DB アカウントの作成を自動化するには、Azure Portal、CLI、または PowerShell を使用します。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

バージョン 2.x をインストールするには、次の手順を実行します。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.DocumentDB.Core
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.DocumentDB.Core
```

.NET Standard を対象とするバージョン 3.0 のプレビューをインストールするには、次の手順を実行します。 

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Cosmos -prerelease
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.Cosmos
```


### <a name="code-example"></a>コード例

この例では、既存の Azure Cosmos DB SQL API データベースに接続し、コレクションからドキュメントを読み取って、`Item` オブジェクトとして逆シリアル化します。 この例では、.NET SDK のバージョン 2.x を使用しています。   

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Documents.Client;
*/

DocumentClient client = new DocumentClient(endpointUri, authKeyString);
Uri documentUri = UriFactory.CreateDocumentUri("MyDatabaseName", "MyCollectionName", "DocumentId");
SomeClass myObject = client.ReadDocumentAsync<SomeClass>(documentUri).ToString();
```

この例では、既存の Azure Cosmos DB SQL API データベースに接続して、新しいデータベースとコンテナーを作成し、コンテナーから項目を読み取って、`TodoItem` オブジェクトに逆シリアル化します。 この例では、.NET SDK のバージョン 3.x を使用しています。   

```csharp
using (CosmosClient cosmosClient = new CosmosClient("endpoint", "primaryKey"))
{
    // Read item from container
    CosmosItemResponse<TodoItem> todoItemResponse = await cosmosClient.Databases["DatabaseId"].Containers["ContainerId"].Items.ReadItemAsync<TodoItem>("partitionKeyValue", "ItemId");
}
```

> [!div class="nextstepaction"]
> [クライアント API を探す](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a>サンプル

* [Azure Cosmos DB の SQL API (バージョン 2.x) を使用した .NET アプリの開発](https://github.com/Azure-Samples/documentdb-dotnet-todo-app/)
* [Azure Cosmos DB の SQL API (バージョン 3.x プレビュー) を使用した .NET アプリの開発](https://github.com/Azure-Samples/cosmos-dotnet-todo-app/)
* [Azure Cosmos DB の SQL API (バージョン 3.x プレビュー) を使用した .NET Core アプリの開発](https://github.com/Azure-Samples/cosmos-dotnet-core-getting-started)

Azure Cosmos DB のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb)を表示します。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
