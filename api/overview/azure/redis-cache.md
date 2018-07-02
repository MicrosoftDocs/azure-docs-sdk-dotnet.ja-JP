---
title: .NET 用 Azure Redis Cache ライブラリ
description: .NET 用 Azure Redis Cache ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Redis Cache
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: redis-cache
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 879f42aa254103239fb0dceeb25cb99a7d5e9814
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065922"
---
# <a name="azure-redis-cache-libraries-for-net"></a><span data-ttu-id="24bb0-104">.NET 用 Azure Redis Cache ライブラリ</span><span class="sxs-lookup"><span data-stu-id="24bb0-104">Azure Redis Cache libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="24bb0-105">概要</span><span class="sxs-lookup"><span data-stu-id="24bb0-105">Overview</span></span>

<span data-ttu-id="24bb0-106">Azure Redis Cache は、アプリケーションに対してスループットが高く待機時間の短いデータ アクセスを提供する、セキュリティで保護されたデータ キャッシュおよびメッセージング ブローカーです。</span><span class="sxs-lookup"><span data-stu-id="24bb0-106">Azure Redis Cache is a secure data cache and messaging broker that provides high throughput and low-latency access to data for applications.</span></span>  <span data-ttu-id="24bb0-107">詳しくは、「[Redis Cache の使用方法](https://docs.microsoft.com/azure/redis-cache/cache-dotnet-how-to-use-azure-redis-cache)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="24bb0-107">For more information, see [How to Use Redis Cache](https://docs.microsoft.com/azure/redis-cache/cache-dotnet-how-to-use-azure-redis-cache).</span></span>

## <a name="client-library"></a><span data-ttu-id="24bb0-108">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="24bb0-108">Client library</span></span>

<span data-ttu-id="24bb0-109">Azure Redis Cache は、すべての Redis クライアント API (`StackExchange.Redis` など) と互換性があります。</span><span class="sxs-lookup"><span data-stu-id="24bb0-109">Azure Redis Cache is compatible with any Redis client API, including `StackExchange.Redis`.</span></span>

<span data-ttu-id="24bb0-110">[NuGet パッケージ](https://www.nuget.org/packages/StackExchange.Redis)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="24bb0-110">Install the [NuGet package](https://www.nuget.org/packages/StackExchange.Redis) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="24bb0-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="24bb0-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package StackExchange.Redis
```

```bash
dotnet add package StackExchange.Redis
```

### <a name="example"></a><span data-ttu-id="24bb0-112">例</span><span class="sxs-lookup"><span data-stu-id="24bb0-112">Example</span></span>

<span data-ttu-id="24bb0-113">この例では、Redis Cache データベース インスタンスに接続し、名前でキャッシュに文字列をいくつか追加した後、それをもう一度取得します。</span><span class="sxs-lookup"><span data-stu-id="24bb0-113">This example connects to a Redis Cache database instance, adds some strings to the cache by name, and then retrieves them again.</span></span>

```csharp
/* Include this "using" directive.
using StackExchange.Redis;
*/

ConnectionMultiplexer connection = 
    ConnectionMultiplexer.Connect("contoso.redis.cache.windows.net,abortConnect=false,ssl=true,password=...");
    IDatabase cache = connection.GetDatabase();

// Perform cache operations using the cache object...
// Simple put of integral data types into the cache
cache.StringSet("key1", "value");
cache.StringSet("key2", 25);

// Simple get of data types from the cache
string key1 = cache.StringGet("key1");
int key2 = (int)cache.StringGet("key2");
```

## <a name="management-library"></a><span data-ttu-id="24bb0-114">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="24bb0-114">Management library</span></span>

<span data-ttu-id="24bb0-115">Redis Cache の管理ライブラリを使うと、Redis Cache のリソースとアクセス キーを管理できます。</span><span class="sxs-lookup"><span data-stu-id="24bb0-115">The Redis Cache management library allows you to manage Redis Cache resources and access keys.</span></span>

<span data-ttu-id="24bb0-116">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Redis.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="24bb0-116">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Redis.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="24bb0-117">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="24bb0-117">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Redis.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Redis.Fluent
```

### <a name="example"></a><span data-ttu-id="24bb0-118">例</span><span class="sxs-lookup"><span data-stu-id="24bb0-118">Example</span></span>

<span data-ttu-id="24bb0-119">この例では、新しい Redis Cache を作成します。</span><span class="sxs-lookup"><span data-stu-id="24bb0-119">This example creates a new Redis Cache.</span></span>

```csharp
/* Include these "using" directives...
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
using Microsoft.Azure.Management.Redis.Fluent;
*/

IRedisCache redisCache1 = azure.RedisCaches.Define("RedisCacheName")
    .WithRegion(Region.USCentral)
    .WithNewResourceGroup("ResourceGroupName")
    .WithBasicSku()
    .Create();
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="24bb0-120">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="24bb0-120">Explore the management APIs</span></span>](/dotnet/api/overview/azure/rediscache/management)


## <a name="samples"></a><span data-ttu-id="24bb0-121">サンプル</span><span class="sxs-lookup"><span data-stu-id="24bb0-121">Samples</span></span>

* [<span data-ttu-id="24bb0-122">Redis の概要 - Redis を管理する - .NET</span><span class="sxs-lookup"><span data-stu-id="24bb0-122">Getting Started with Redis - Manage Redis - in .NET</span></span>](https://github.com/Azure-Samples/redis-cache-dotnet-manage-cache)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
