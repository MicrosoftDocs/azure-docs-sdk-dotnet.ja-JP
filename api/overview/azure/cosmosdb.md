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
# <a name="azure-cosmosdb-libraries-for-net"></a>.NET 用 Azure CosmosDB ライブラリ

## <a name="overview"></a>概要

[Azure CosmosDB](https://docs.microsoft.com/azure/cosmos-db/introduction) は、複数の異なる種類のデータベースをサポートする、スケーラブルな分散型データ ストアです。

[CosmosDB を使ってみる](https://docs.microsoft.com/azure/cosmos-db/create-documentdb-dotnet)。

## <a name="client-library"></a>クライアント ライブラリ

既存の CosmosDB データ ストアのデータにアクセスしたり、既存の CosmosDB データ ストアにデータを保存したりするには、CosmosDB .NET クライアント ライブラリを使用します。  新しい CosmosDB アカウントの作成を自動化するには、Azure Portal、CLI、または PowerShell を使用します。

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

この例では、既存の CosmosDB DocumentDB API データベースに接続し、コレクションからドキュメントを読み取って、`Item` オブジェクトとして逆シリアル化します。   

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Documents.Client;
*/

DocumentClient client = new DocumentClient(endpointUri, authKeyString);
Uri documentUri = UriFactory.CreateDocumentUri("MyDatabaseName", "MyCollectionName", "DocumentId");
SomeClass myObject = client.ReadDocumentAsync<SomeClass>(documentUri).ToString()).Result;
```

> [!div class="nextstepaction"]
> [クライアント API を探す](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a>サンプル

* [Azure Cosmos DB の MongoDB API を使用した .NET アプリの開発](https://azure.microsoft.com/resources/samples/azure-cosmos-db-mongodb-dotnet-getting-started/)

Azure Cosmos DB のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb)を表示します。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
