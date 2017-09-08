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
# <a name="azure-database-for-postgresql-libraries-for-net"></a><span data-ttu-id="88d20-104">.NET 用 Azure Database for PostgreSQL ライブラリ</span><span class="sxs-lookup"><span data-stu-id="88d20-104">Azure Database for PostgreSQL libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="88d20-105">概要</span><span class="sxs-lookup"><span data-stu-id="88d20-105">Overview</span></span>

<span data-ttu-id="88d20-106">[Azure Database for PostgreSQL](https://docs.microsoft.com/azure/postgresql/) に格納されているデータとリソースを操作します。</span><span class="sxs-lookup"><span data-stu-id="88d20-106">Work with data and resources stored in [Azure Database for PostgreSQL](https://docs.microsoft.com/azure/postgresql/).</span></span>

## <a name="client-api"></a><span data-ttu-id="88d20-107">クライアント API</span><span class="sxs-lookup"><span data-stu-id="88d20-107">Client API</span></span>

<span data-ttu-id="88d20-108">Azure Database for PostgreSQL にアクセスするための推奨されるクライアント ライブラリは、オープンソースの [Npgsql ADO.NET データ プロバイダー](http://www.npgsql.org/)です。</span><span class="sxs-lookup"><span data-stu-id="88d20-108">The recommended client library for accessing Azure Database for PostgreSQL is the open-source [Npgsql ADO.NET data provider](http://www.npgsql.org/).</span></span> <span data-ttu-id="88d20-109">この ADO.NET プロバイダーを使用してデータベースに接続し、SQL ステートメントを直接実行するか、Npgsql の [Entity Framework 6](http://www.npgsql.org/ef6/index.html) または [Entity Framework Core](http://www.npgsql.org/efcore/index.html) プロバイダーを使用して、Entity Framework 経由で SQL ステートメントを実行します。</span><span class="sxs-lookup"><span data-stu-id="88d20-109">Use the ADO.NET provider to connect to the database and execute SQL statements directly or through Entity Framework with the Npgsql's [Entity Framework 6](http://www.npgsql.org/ef6/index.html) or [Entity Framework Core](http://www.npgsql.org/efcore/index.html) providers.</span></span>

<span data-ttu-id="88d20-110">[NuGet パッケージ](https://www.nuget.org/packages/Npgsql)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="88d20-110">Install the [NuGet package](https://www.nuget.org/packages/Npgsql) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="88d20-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="88d20-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Npgsql
```

#### <a name="net-core-cli"></a><span data-ttu-id="88d20-112">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="88d20-112">.NET Core CLI</span></span>

```bash
dotnet add package Npgsql
```

### <a name="code-example"></a><span data-ttu-id="88d20-113">コード例</span><span class="sxs-lookup"><span data-stu-id="88d20-113">Code Example</span></span>

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

### <a name="samples"></a><span data-ttu-id="88d20-114">サンプル</span><span class="sxs-lookup"><span data-stu-id="88d20-114">Samples</span></span>

- [<span data-ttu-id="88d20-115">ADO.NET のコード例</span><span class="sxs-lookup"><span data-stu-id="88d20-115">ADO.NET code examples</span></span>](/dotnet/framework/data/adonet/ado-net-code-examples)
- <span data-ttu-id="88d20-116">[Azure CLI を使用した PostgreSQL データベースの設計](https://docs.microsoft.com/azure/postgresql/tutorial-design-database-using-azure-cli) [PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console [DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package</span><span class="sxs-lookup"><span data-stu-id="88d20-116">[Design a PostgreSQL database using the Azure CLI](https://docs.microsoft.com/azure/postgresql/tutorial-design-database-using-azure-cli) [PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console [DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package</span></span>