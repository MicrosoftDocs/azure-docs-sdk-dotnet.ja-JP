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
# <a name="azure-cosmos-db-libraries-for-net"></a>.NET 用 Azure Cosmos DB ライブラリ

## <a name="overview"></a>概要

[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) は、グローバル分散型のマルチモデル データベース サービスです。 これは、包括的な SLA により、任意の数の地理的リージョン間でスループットとストレージを弾力的かつ個別にスケーリングできるように設計されています。 Azure Cosmos DB を使用すると、API とプログラミング モデルを使って、ドキュメント、キー値、ワイドカラム、およびグラフのデータベースを格納し、アクセスできます。 

[Cosmos DB を使い始めます](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet)。

## <a name="client-library"></a>クライアント ライブラリ

既存の Azure Cosmos DB データ ストアのデータにアクセスしたり、データを保存したりするには、Azure Cosmos DB .NET クライアント ライブラリを使用します。 新しい Azure Cosmos DB アカウントの作成を自動化するには、Azure Portal、CLI、または PowerShell を使用します。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.DocumentDB.Core
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.DocumentDB.Core
```

### <a name="code-example"></a>コード例

この例では、既存の Azure Cosmos DB SQL API データベースに接続し、コレクションからドキュメントを読み取って、`Item` オブジェクトとして逆シリアル化します。   

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Documents.Client;
*/

DocumentClient client = new DocumentClient(endpointUri, authKeyString);
Uri documentUri = UriFactory.CreateDocumentUri("MyDatabaseName", "MyCollectionName", "DocumentId");
SomeClass myObject = client.ReadDocumentAsync<SomeClass>(documentUri).ToString();
```

> [!div class="nextstepaction"]
> [クライアント API を探す](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a>サンプル

* [Azure Cosmos DB の MongoDB API を使用した .NET アプリの開発](https://azure.microsoft.com/resources/samples/azure-cosmos-db-mongodb-dotnet-getting-started/)

Azure Cosmos DB のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb)を表示します。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
