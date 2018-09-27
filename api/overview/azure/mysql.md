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
# <a name="azure-database-for-mysql-libraries-for-net"></a><span data-ttu-id="ce3de-103">.NET 用 Azure Database for MySQL ライブラリ</span><span class="sxs-lookup"><span data-stu-id="ce3de-103">Azure Database for MySQL libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="ce3de-104">概要</span><span class="sxs-lookup"><span data-stu-id="ce3de-104">Overview</span></span>

<span data-ttu-id="ce3de-105">[Azure Database for MySQL](/azure/mysql/overview) に格納されているデータとリソースを操作します。</span><span class="sxs-lookup"><span data-stu-id="ce3de-105">Work with data and resources stored in [Azure Database for MySQL](/azure/mysql/overview).</span></span>

## <a name="client-apis"></a><span data-ttu-id="ce3de-106">クライアント API</span><span class="sxs-lookup"><span data-stu-id="ce3de-106">Client APIs</span></span>

<span data-ttu-id="ce3de-107">Azure Database for MySQL にアクセスするための推奨されるクライアント ライブラリは、MySQL の [Connector/Net](https://dev.mysql.com/doc/connector-net/en) です。</span><span class="sxs-lookup"><span data-stu-id="ce3de-107">The recommended client library for accessing Azure Database for MySQL is MySQL's [Connector/Net](https://dev.mysql.com/doc/connector-net/en).</span></span> <span data-ttu-id="ce3de-108">パッケージを使ってデータベースに接続し、SQL ステートメントを直接実行します。</span><span class="sxs-lookup"><span data-stu-id="ce3de-108">Use the package to connect to the database and execute SQL statements directly.</span></span> 

<span data-ttu-id="ce3de-109">[NuGet パッケージ](https://www.nuget.org/packages/MySql.Data)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="ce3de-109">Install the [NuGet package](https://www.nuget.org/packages/MySql.Data) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="ce3de-110">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="ce3de-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package MySql.Data
```

#### <a name="net-core-cli"></a><span data-ttu-id="ce3de-111">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="ce3de-111">.NET Core CLI</span></span>

```bash
dotnet add package MySql.Data
```

### <a name="code-example"></a><span data-ttu-id="ce3de-112">コード例</span><span class="sxs-lookup"><span data-stu-id="ce3de-112">Code Example</span></span>

<span data-ttu-id="ce3de-113">MySQL データベースに接続してクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="ce3de-113">Connect to a MySQL database and execute a query:</span></span>

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

## <a name="samples"></a><span data-ttu-id="ce3de-114">サンプル</span><span class="sxs-lookup"><span data-stu-id="ce3de-114">Samples</span></span>

- [<span data-ttu-id="ce3de-115">ADO.NET のコード例</span><span class="sxs-lookup"><span data-stu-id="ce3de-115">ADO.NET code examples</span></span>](/dotnet/framework/data/adonet/ado-net-code-examples)
- [<span data-ttu-id="ce3de-116">Azure CLI を使用して MySQL データベースを設計する</span><span class="sxs-lookup"><span data-stu-id="ce3de-116">Design a MySQL database using the Azure CLI</span></span>](https://docs.microsoft.com/azure/mysql/tutorial-design-database-using-cli) 

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
