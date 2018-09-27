---
title: .NET 用 Azure SQL Database API
description: .NET 用 Azure SQL Database ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: sql-database
ms.openlocfilehash: e4c1620ddf488952c6720b9bedf2521c6512b9a3
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190635"
---
# <a name="azure-sql-database-apis-for-net"></a><span data-ttu-id="5a140-103">.NET 用 Azure SQL Database API</span><span class="sxs-lookup"><span data-stu-id="5a140-103">Azure SQL Database APIs for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="5a140-104">概要</span><span class="sxs-lookup"><span data-stu-id="5a140-104">Overview</span></span>

<span data-ttu-id="5a140-105">[Azure SQL Database](https://docs.microsoft.com/azure/sql-database/sql-database-technical-overview) は、リレーショナル データ、テーブル データ、JSON データ、空間データ、XML データに対応した、Microsoft SQL Server エンジンを使うデータベース サービスです。</span><span class="sxs-lookup"><span data-stu-id="5a140-105">[Azure SQL Database](https://docs.microsoft.com/azure/sql-database/sql-database-technical-overview) is a database service using the Microsoft SQL Server engine that supports relational, JSON, spatial, and XML data.</span></span> 

<span data-ttu-id="5a140-106">.NET での SQL Database の使い方について詳しくは、「[.NET (C#) と Visual Studio で Azure SQL Database に接続してデータベースに照会する](https://docs.microsoft.com/azure/sql-database/sql-database-connect-query-dotnet-visual-studio)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="5a140-106">To learn more about the using SQL Database with .NET, see [Use .NET with Visual Studio to connect and query an Azure SQL database](https://docs.microsoft.com/azure/sql-database/sql-database-connect-query-dotnet-visual-studio).</span></span>

## <a name="client-library"></a><span data-ttu-id="5a140-107">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="5a140-107">Client library</span></span>

<span data-ttu-id="5a140-108">データベースに接続して認証を行い、アドホックな T-SQL ステートメントとストアド プロシージャを実行するには、.NET SQL クライアント ライブラリを使います。</span><span class="sxs-lookup"><span data-stu-id="5a140-108">Use the .NET SQL client library to connect and authenticate with your database and execute ad-hoc T-SQL statements and stored procedures.</span></span>

<span data-ttu-id="5a140-109">[NuGet パッケージ]( https://www.nuget.org/packages/System.Data.SqlClient)を Visual Studio [パッケージ マネージャー コンソール](https://docs.microsoft.com/nuget/tools/package-manager-console)から直接インストールするか、[.NET Core CLI](https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package) を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="5a140-109">Install the [NuGet package]( https://www.nuget.org/packages/System.Data.SqlClient) directly from the Visual Studio [Package Manager console](https://docs.microsoft.com/nuget/tools/package-manager-console) or with the [.NET Core CLI](https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package).</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="5a140-110">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="5a140-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package System.Data.SqlClient
```

#### <a name="net-core-cli"></a><span data-ttu-id="5a140-111">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="5a140-111">.NET Core CLI</span></span>

```bash
dotnet add package System.Data.SqlClient
```

### <a name="code-example"></a><span data-ttu-id="5a140-112">コード例</span><span class="sxs-lookup"><span data-stu-id="5a140-112">Code Example</span></span>

<span data-ttu-id="5a140-113">この例では、データベースに接続し、テーブルから行を読み取ります。</span><span class="sxs-lookup"><span data-stu-id="5a140-113">This example connects to a database and reads rows from a table.</span></span>

```csharp
/* Include this 'using' directive...
using System.Data.SqlClient;
*/

// Always store connection strings securely. 
string connectionString = "Server=tcp:[serverName].database.windows.net;" 
    + "Database=myDataBase;User ID=[loginname]@[serverName];Password=myPassword;"
    + "Trusted_Connection=False;Encrypt=True;";

// Best practice is to scope the SqlConnection to a "using" block
using (SqlConnection conn = new SqlConnection(connectionString))
{
    // Connect to the database
    conn.Open();

    // Read rows
    SqlCommand selectCommand = new SqlCommand("SELECT * FROM MyTable", conn);
    SqlDataReader results = selectCommand.ExecuteReader();
    
    // Enumerate over the rows
    while(results.Read())
    {
        Console.WriteLine("Column 0: {0} Column 1: {1}", results[0], results[1]);
    }
}
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="5a140-114">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="5a140-114">Explore the client APIs</span></span>](/dotnet/api/overview/azure/sql/client)

## <a name="management-library"></a><span data-ttu-id="5a140-115">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="5a140-115">Management library</span></span>

<span data-ttu-id="5a140-116">Azure SQL Database サーバー インスタンスの作成、管理、拡張を行うには、Azure SQL Database 管理ライブラリを使います。</span><span class="sxs-lookup"><span data-stu-id="5a140-116">Use the Azure SQL Database management library to create, manage, and scale Azure SQL Database server instances.</span></span>

<span data-ttu-id="5a140-117">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Sql.Fluent/)を Visual Studio [パッケージ マネージャー コンソール](https://docs.microsoft.com/nuget/tools/package-manager-console)から直接インストールするか、[.NET Core CLI](https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package) を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="5a140-117">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Sql.Fluent/) directly from the Visual Studio [Package Manager console](https://docs.microsoft.com/nuget/tools/package-manager-console) or with the [.NET Core CLI](https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package).</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="5a140-118">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="5a140-118">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Sql.Fluent
``` 

#### <a name="net-core-command-line"></a><span data-ttu-id="5a140-119">.NET Core コマンド ライン</span><span class="sxs-lookup"><span data-stu-id="5a140-119">.NET Core command line</span></span>

```bash
dotnet add package Microsoft.Azure.Management.Sql.Fluent
```

### <a name="code-example"></a><span data-ttu-id="5a140-120">コード例</span><span class="sxs-lookup"><span data-stu-id="5a140-120">Code Example</span></span>

<span data-ttu-id="5a140-121">この例では、新しい SQL Database サーバー インスタンスを作成した後、そのインスタンスに新しいデータベースを作成します。</span><span class="sxs-lookup"><span data-stu-id="5a140-121">This example creates a new SQL Database server instance and then creates a new database on that instance.</span></span>

```csharp
/* Include these 'using' directives...
using Microsoft.Azure.Management.Sql.Fluent;
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
*/

string startAddress = "0.0.0.0";
string endAddress = "255.255.255.255";

// Create the SQL server instance
ISqlServer sqlServer = azure.SqlServers.Define("UniqueServerName")
    .WithRegion(Region.USEast)
    .WithNewResourceGroup("ResourceGroupName")
    .WithAdministratorLogin("UserName")
    .WithAdministratorPassword("Password")
    .WithNewFirewallRule(startAddress, endAddress)
    .Create();

// Create the database
ISqlDatabase sqlDb = sqlServer.Databases.Define("DatabaseName").Create();
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="5a140-122">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="5a140-122">Explore the management APIs</span></span>](/dotnet/api/overview/azure/sql/management)

## <a name="samples"></a><span data-ttu-id="5a140-123">サンプル</span><span class="sxs-lookup"><span data-stu-id="5a140-123">Samples</span></span>

- [<span data-ttu-id="5a140-124">ADO.NET のコード例</span><span class="sxs-lookup"><span data-stu-id="5a140-124">ADO.NET code examples</span></span>](/dotnet/framework/data/adonet/ado-net-code-examples)
- [<span data-ttu-id="5a140-125">SQL Database の .NET 用 Azure 管理ライブラリ サンプル</span><span class="sxs-lookup"><span data-stu-id="5a140-125">Azure management libraries for .NET samples for SQL Database</span></span>](/dotnet/azure/dotnet-sdk-azure-sql-database-samples)

<span data-ttu-id="5a140-126">Azure SQL Database のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=sql+database)を表示します。</span><span class="sxs-lookup"><span data-stu-id="5a140-126">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=sql+database) of Azure SQL Database samples.</span></span>

