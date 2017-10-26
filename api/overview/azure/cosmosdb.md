---
title: ".NET 用 Azure CosmosDB ライブラリ"
description: ".NET 用 Azure CosmosDB ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, CosmosDB
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: cosmos-db
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 890c00caeca06bf863425c7159d7833c4db8df38
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/26/2017
---
# <a name="azure-cosmosdb-libraries-for-net"></a>.NET 用 Azure CosmosDB ライブラリ

## <a name="overview"></a>概要

[Azure CosmosDB](https://docs.microsoft.com/azure/cosmos-db/introduction) は、複数の異なる種類のデータベースをサポートする、スケーラブルな分散型データ ストアです。

## <a name="client-library"></a>クライアント ライブラリ

CosmosDB データ ストアのデータにアクセスしたり、CosmosDB データ ストアにデータを保存したりするには、CosmosDB .NET クライアント ライブラリを使用します。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.DocumentDB.Core
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.DocumentDB.Core
```

### <a name="code-example"></a>コード例

この例では、既存の CosmosDB DocumentDB API データベースに接続し、コレクションからドキュメントを読み取って、`Item` オブジェクトとして逆シリアル化します。

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
> [クライアント API を探す](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a>サンプル

* [Azure Cosmos DB の MongoDB API を使用した .NET アプリの開発](https://azure.microsoft.com/en-us/resources/samples/azure-cosmos-db-mongodb-dotnet-getting-started/)

Azure Cosmos DB のサンプルの[完全な一覧](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&term=cosmosdb)を表示します。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
