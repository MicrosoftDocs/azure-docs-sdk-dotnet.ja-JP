---
title: .NET 用 Azure Database for MySQL ライブラリ
description: Azure Database for MySQL 用 .NET クライアント ライブラリのリファレンス ドキュメント
keywords: Azure, .NET, SDK, API, SQL, データベース, MySQL
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: mysql
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 6cf9d819b437a4524c71cdb2265455ef49efaea5
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065782"
---
# <a name="azure-database-for-mysql-libraries-for-net"></a><span data-ttu-id="ba279-104">.NET 用 Azure Database for MySQL ライブラリ</span><span class="sxs-lookup"><span data-stu-id="ba279-104">Azure Database for MySQL libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="ba279-105">概要</span><span class="sxs-lookup"><span data-stu-id="ba279-105">Overview</span></span>

<span data-ttu-id="ba279-106">[Azure Database for MySQL](/azure/mysql/overview) に格納されているデータとリソースを操作します。</span><span class="sxs-lookup"><span data-stu-id="ba279-106">Work with data and resources stored in [Azure Database for MySQL](/azure/mysql/overview).</span></span>

## <a name="client-apis"></a><span data-ttu-id="ba279-107">クライアント API</span><span class="sxs-lookup"><span data-stu-id="ba279-107">Client APIs</span></span>

<span data-ttu-id="ba279-108">Azure Database for MySQL にアクセスするための推奨されるクライアント ライブラリは、MySQL の [Connector/Net](https://dev.mysql.com/doc/connector-net/en) です。</span><span class="sxs-lookup"><span data-stu-id="ba279-108">The recommended client library for accessing Azure Database for MySQL is MySQL's [Connector/Net](https://dev.mysql.com/doc/connector-net/en).</span></span> <span data-ttu-id="ba279-109">パッケージを使ってデータベースに接続し、SQL ステートメントを直接実行します。</span><span class="sxs-lookup"><span data-stu-id="ba279-109">Use the package to connect to the database and execute SQL statements directly.</span></span> 

<span data-ttu-id="ba279-110">[NuGet パッケージ](https://www.nuget.org/packages/MySql.Data)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="ba279-110">Install the [NuGet package](https://www.nuget.org/packages/MySql.Data) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="ba279-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="ba279-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package MySql.Data
```

#### <a name="net-core-cli"></a><span data-ttu-id="ba279-112">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="ba279-112">.NET Core CLI</span></span>

```bash
dotnet add package MySql.Data
```

### <a name="code-example"></a><span data-ttu-id="ba279-113">コード例</span><span class="sxs-lookup"><span data-stu-id="ba279-113">Code Example</span></span>

<span data-ttu-id="ba279-114">MySQL データベースに接続してクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="ba279-114">Connect to a MySQL database and execute a query:</span></span>

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

## <a name="samples"></a><span data-ttu-id="ba279-115">サンプル</span><span class="sxs-lookup"><span data-stu-id="ba279-115">Samples</span></span>

- [<span data-ttu-id="ba279-116">ADO.NET のコード例</span><span class="sxs-lookup"><span data-stu-id="ba279-116">ADO.NET code examples</span></span>](/dotnet/framework/data/adonet/ado-net-code-examples)
- [<span data-ttu-id="ba279-117">Azure CLI を使用して MySQL データベースを設計する</span><span class="sxs-lookup"><span data-stu-id="ba279-117">Design a MySQL database using the Azure CLI</span></span>](https://docs.microsoft.com/azure/mysql/tutorial-design-database-using-cli) 

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
