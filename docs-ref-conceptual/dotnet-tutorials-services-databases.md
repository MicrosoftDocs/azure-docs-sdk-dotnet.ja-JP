---
title: Azure データベースの使用に関する .NET チュートリアル
description: .NET アプリケーションで Azure データベースに接続して使う方法に関するチュートリアルです。
ms.date: 10/19/2017
ms.openlocfilehash: 38dcf7e288e4ec46705b31b9d00efc5477f92a85
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190625"
---
# <a name="tutorials-for-using-net-with-azure-databases"></a><span data-ttu-id="c99ae-103">Azure データベースでの .NET の使用に関するチュートリアル</span><span class="sxs-lookup"><span data-stu-id="c99ae-103">Tutorials for using .NET with Azure databases</span></span>

<span data-ttu-id="c99ae-104">次の表では、.NET アプリケーションで Azure データベースのデータに接続して操作する方法についての詳細なチュートリアルへのリンクを示します。</span><span class="sxs-lookup"><span data-stu-id="c99ae-104">The following table links to in-depth tutorials for connecting to and working with data in Azure databases in your .NET applications.</span></span>

<span data-ttu-id="c99ae-105">サンプルのソース コードについては、「[Azure のコード サンプル](https://azure.microsoft.com/resources/samples/?platform=dotnet)」の一覧をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="c99ae-105">For sample source code, see the list of [Azure service samples](https://azure.microsoft.com/resources/samples/?platform=dotnet).</span></span>

| | |
|---|---|
| <span data-ttu-id="c99ae-106">**SQL Database**</span><span class="sxs-lookup"><span data-stu-id="c99ae-106">**SQL Database**</span></span> ||
| <span data-ttu-id="c99ae-107">[.NET を使ってデータに接続し、クエリを行う][1]</span><span class="sxs-lookup"><span data-stu-id="c99ae-107">[Use .NET to connect and query data][1]</span></span> | <span data-ttu-id="c99ae-108">ADO.NET を使って Azure SQL データベースに接続し Transact-SQL ステートメントを使ってデータベース内のデータを照会、挿入、更新、削除します。</span><span class="sxs-lookup"><span data-stu-id="c99ae-108">Use ADO.NET to connect to an Azure SQL database, and then use Transact-SQL statements to query, insert, update, and delete data in the database</span></span> | 
| <span data-ttu-id="c99ae-109">**Azure Database for PostgreSQL**</span><span class="sxs-lookup"><span data-stu-id="c99ae-109">**Azure Database for PostgreSQL**</span></span> ||
| <span data-ttu-id="c99ae-110">[.NET を使ってデータに接続し、クエリを行う][2]</span><span class="sxs-lookup"><span data-stu-id="c99ae-110">[Use .NET to connect and query data][2]</span></span> | <span data-ttu-id="c99ae-111">SQL ステートメントを使ってデータベース内のデータを照会、挿入、更新、削除します。</span><span class="sxs-lookup"><span data-stu-id="c99ae-111">Use SQL statements to query, insert, update, and delete data in the database.</span></span> | 
| <span data-ttu-id="c99ae-112">**Azure Cosmos DB**</span><span class="sxs-lookup"><span data-stu-id="c99ae-112">**Azure Cosmos DB**</span></span> ||
| <span data-ttu-id="c99ae-113">[Azure Cosmos DB SQL API を使ってみる][4]</span><span class="sxs-lookup"><span data-stu-id="c99ae-113">[Getting started with the Azure Cosmos DB SQL API][4]</span></span> | <span data-ttu-id="c99ae-114">SQL API を使用して簡単なコンソール アプリケーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="c99ae-114">Create a simple console application with the SQL API.</span></span> | 
| <span data-ttu-id="c99ae-115">[Azure Cosmos DB SQL API を使用して ASP.NET Web アプリを作成する][3]</span><span class="sxs-lookup"><span data-stu-id="c99ae-115">[Create an ASP.NET web app with the Azure Cosmos DB SQL API][3]</span></span> | <span data-ttu-id="c99ae-116">Azure Cosmos DB SQL API を使用して、Web アプリケーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="c99ae-116">Create a web application with the Azure Cosmos DB SQL API.</span></span> | 
| <span data-ttu-id="c99ae-117">**Redis Cache**</span><span class="sxs-lookup"><span data-stu-id="c99ae-117">**Redis Cache**</span></span> | |
| <span data-ttu-id="c99ae-118">[Azure Redis Cache の使用方法][6]</span><span class="sxs-lookup"><span data-stu-id="c99ae-118">[How to use Azure Redis Cache][6]</span></span> | <span data-ttu-id="c99ae-119">Azure Redis Cache を使い始めます。</span><span class="sxs-lookup"><span data-stu-id="c99ae-119">Get started using Azure Redis Cache.</span></span> |
| <span data-ttu-id="c99ae-120">[Redis Cache で Web アプリを作成する][5]</span><span class="sxs-lookup"><span data-stu-id="c99ae-120">[Create a Web App with Redis Cache][5]</span></span> | <span data-ttu-id="c99ae-121">Visual Studio 2017 を使って ASP.NET Web アプリケーションを作成し、Azure App Service の Web アプリにデプロイします。</span><span class="sxs-lookup"><span data-stu-id="c99ae-121">Create and deploy an ASP.NET web application to a web app in Azure App Service using Visual Studio 2017.</span></span>  | 
| <span data-ttu-id="c99ae-122">[ASP.NET セッション状態プロバイダー][7]</span><span class="sxs-lookup"><span data-stu-id="c99ae-122">[ASP.NET Session State Provider][7]</span></span> | <span data-ttu-id="c99ae-123">Azure Redis Cache を使って、ASP.NET のセッション状態を保持します。</span><span class="sxs-lookup"><span data-stu-id="c99ae-123">Use Azure Redis Cache to maintain session state in ASP.NET.</span></span>  | 
| <span data-ttu-id="c99ae-124">[ASP.NET 出力キャッシュ プロバイダー][8]</span><span class="sxs-lookup"><span data-stu-id="c99ae-124">[ASP.NET Output Cache Provider][8]</span></span> | <span data-ttu-id="c99ae-125">ASP.NET 出力キャッシュに Azure Redis Cache を使います。</span><span class="sxs-lookup"><span data-stu-id="c99ae-125">Use Azure Redis Cache for ASP.NET output caching.</span></span>  | 
 

[1]: /azure/sql-database/sql-database-connect-query-dotnet
[2]: /azure/postgresql/connect-csharp
[3]: /azure/cosmos-db/sql-api-dotnet-application
[4]: /azure/cosmos-db/sql-api-get-started
[5]: /azure/redis-cache/cache-web-app-howto
[6]: /azure/redis-cache/cache-dotnet-how-to-use-azure-redis-cache
[7]: /azure/redis-cache/cache-aspnet-session-state-provider
[8]: /azure/redis-cache/cache-aspnet-output-cache-provider
