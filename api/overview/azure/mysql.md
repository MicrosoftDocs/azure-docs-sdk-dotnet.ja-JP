---
title: .NET 用 Azure Database for MySQL ライブラリ
description: Azure Database for MySQL 用 .NET クライアント ライブラリのリファレンス ドキュメント
ms.date: 10/19/2017
ms.topic: reference
ms.service: mysql
ms.openlocfilehash: 34550c7089a2ec05164f7a16f24bfc8b18391f8a
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190155"
---
# <a name="azure-database-for-mysql-libraries-for-net"></a>.NET 用 Azure Database for MySQL ライブラリ

## <a name="overview"></a>概要

[Azure Database for MySQL](/azure/mysql/overview) に格納されているデータとリソースを操作します。

## <a name="client-apis"></a>クライアント API

Azure Database for MySQL にアクセスするための推奨されるクライアント ライブラリは、MySQL の [Connector/Net](https://dev.mysql.com/doc/connector-net/en) です。 パッケージを使ってデータベースに接続し、SQL ステートメントを直接実行します。 

[NuGet パッケージ](https://www.nuget.org/packages/MySql.Data)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package MySql.Data
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package MySql.Data
```

### <a name="code-example"></a>コード例

MySQL データベースに接続してクエリを実行します。

```csharp
/* Include this "using" directive...
using MySql.Data.MySqlClient;
*/

string connectionString = "Server=[servername].mysql.database.azure.com; " +
    "Database=myDataBase; Uid=[userid]@[servername]; Pwd=myPassword;";

// Best practice is to scope the MySqlConnection to a "using" block
using (MySqlConnection conn = new MySqlConnection(connectionString))
{
    // Connect to the database
    conn.Open();

    // Read rows
    MySqlCommand selectCommand = new MySqlCommand("SELECT * FROM MyTable", conn);
    MySqlDataReader results = selectCommand.ExecuteReader();
    
    // Enumerate over the rows
    while(results.Read())
    {
        Console.WriteLine("Column 0: {0} Column 1: {1}", results[0], results[1]);
    }
}
```

## <a name="samples"></a>サンプル

- [ADO.NET のコード例](/dotnet/framework/data/adonet/ado-net-code-examples)
- [Azure CLI を使用して MySQL データベースを設計する](https://docs.microsoft.com/azure/mysql/tutorial-design-database-using-cli) 

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
