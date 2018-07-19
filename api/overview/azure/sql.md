---
title: .NET 用 Azure SQL Database API
description: .NET 用 Azure SQL Database ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, SQL, SQL Database
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: sql-database
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 8096e66be1263bc50648ef5b9b16f3fc2bd08ac8
ms.sourcegitcommit: 512e031ead61a578ac96835c8ea01829842740bf
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2018
ms.locfileid: "39116678"
---
# <a name="azure-sql-database-apis-for-net"></a>.NET 用 Azure SQL Database API

## <a name="overview"></a>概要

[Azure SQL Database](https://docs.microsoft.com/azure/sql-database/sql-database-technical-overview) は、リレーショナル データ、テーブル データ、JSON データ、空間データ、XML データに対応した、Microsoft SQL Server エンジンを使うデータベース サービスです。 

.NET での SQL Database の使い方について詳しくは、「[.NET (C#) と Visual Studio で Azure SQL Database に接続してデータベースに照会する](https://docs.microsoft.com/azure/sql-database/sql-database-connect-query-dotnet-visual-studio)」をご覧ください。

## <a name="client-library"></a>クライアント ライブラリ

データベースに接続して認証を行い、アドホックな T-SQL ステートメントとストアド プロシージャを実行するには、.NET SQL クライアント ライブラリを使います。

[NuGet パッケージ]( https://www.nuget.org/packages/System.Data.SqlClient)を Visual Studio [パッケージ マネージャー コンソール](https://docs.microsoft.com/nuget/tools/package-manager-console)から直接インストールするか、[.NET Core CLI](https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package) を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package System.Data.SqlClient
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package System.Data.SqlClient
```

### <a name="code-example"></a>コード例

この例では、データベースに接続し、テーブルから行を読み取ります。

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
> [クライアント API を探す](/dotnet/api/overview/azure/sql/client)

## <a name="management-library"></a>管理ライブラリ

Azure SQL Database サーバー インスタンスの作成、管理、拡張を行うには、Azure SQL Database 管理ライブラリを使います。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Sql.Fluent/)を Visual Studio [パッケージ マネージャー コンソール](https://docs.microsoft.com/nuget/tools/package-manager-console)から直接インストールするか、[.NET Core CLI](https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package) を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.Sql.Fluent
``` 

#### <a name="net-core-command-line"></a>.NET Core コマンド ライン

```bash
dotnet add package Microsoft.Azure.Management.Sql.Fluent
```

### <a name="code-example"></a>コード例

この例では、新しい SQL Database サーバー インスタンスを作成した後、そのインスタンスに新しいデータベースを作成します。

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
> [Management API を探す](/dotnet/api/overview/azure/sql/management)

## <a name="samples"></a>サンプル

- [ADO.NET のコード例](/dotnet/framework/data/adonet/ado-net-code-examples)
- [SQL Database の .NET 用 Azure 管理ライブラリ サンプル](/dotnet/azure/dotnet-sdk-azure-sql-database-samples)

Azure SQL Database のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=sql+database)を表示します。

