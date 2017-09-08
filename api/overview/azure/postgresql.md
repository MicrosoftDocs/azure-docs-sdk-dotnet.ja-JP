---
title: ".NET 用 Azure Database for PostgreSQL ライブラリ"
description: "Azure Database for PostgreSQL 用 .NET クライアント ライブラリのリファレンス ドキュメント"
keywords: "Azure, .NET ODBC, SDK, API, SQL, ADO.NET, データベース, PostGres, PostgreSQL"
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/17/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: postgresql
ms.openlocfilehash: 899002b12dd36e6b23a05c8516670ff841abed79
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-database-for-postgresql-libraries-for-net"></a>.NET 用 Azure Database for PostgreSQL ライブラリ

## <a name="overview"></a>概要

[Azure Database for PostgreSQL](https://docs.microsoft.com/azure/postgresql/) に格納されているデータとリソースを操作します。

## <a name="client-api"></a>クライアント API

Azure Database for PostgreSQL にアクセスするための推奨されるクライアント ライブラリは、オープンソースの [Npgsql ADO.NET データ プロバイダー](http://www.npgsql.org/)です。 この ADO.NET プロバイダーを使用してデータベースに接続し、SQL ステートメントを直接実行するか、Npgsql の [Entity Framework 6](http://www.npgsql.org/ef6/index.html) または [Entity Framework Core](http://www.npgsql.org/efcore/index.html) プロバイダーを使用して、Entity Framework 経由で SQL ステートメントを実行します。

[NuGet パッケージ](https://www.nuget.org/packages/Npgsql)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Npgsql
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Npgsql
```

### <a name="code-example"></a>コード例

```csharp
/* Include this 'using' directive...
using Npgsql;
*/

// Always store connection strings securely. 
string connectionString = "Server=[servername].postgres.database.azure.com; " +
    "Port=5432; Database=myDataBase; User Id=[userid]@[servername]; Password=password;";

// Best practice is to scope the NpgsqlConnection to a "using" block
using (NpgsqlConnection conn = new NpgsqlConnection(connectionString))
{
    // Connect to the database
    conn.Open();

    // Read rows
    NpgsqlCommand selectCommand = new NpgsqlCommand("SELECT * FROM MyTable", conn);
    NpgsqlDataReader results = selectCommand.ExecuteReader();
    
    // Enumerate over the rows
    while(results.Read())
    {
        Console.WriteLine("Column 0: {0} Column 1: {1}", results[0], results[1]);
    }
}
```

### <a name="samples"></a>サンプル

- [ADO.NET のコード例](/dotnet/framework/data/adonet/ado-net-code-examples)
- [Azure CLI を使用した PostgreSQL データベースの設計](https://docs.microsoft.com/azure/postgresql/tutorial-design-database-using-azure-cli) [PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console [DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package