---
title: .NET 用 Azure Redis Cache ライブラリ
description: .NET 用 Azure Redis Cache ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Redis Cache
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: redis-cache
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 64bb5a43cec8c82412b3dc7b60fea1e8566ab399
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/26/2017
ms.locfileid: "23566343"
---
# <a name="azure-redis-cache-libraries-for-net"></a>.NET 用 Azure Redis Cache ライブラリ

## <a name="overview"></a>概要

Azure Redis Cache は、アプリケーションに対してスループットが高く待機時間の短いデータ アクセスを提供する、セキュリティで保護されたデータ キャッシュおよびメッセージング ブローカーです。  詳しくは、「[Redis Cache の使用方法](https://docs.microsoft.com/azure/redis-cache/cache-dotnet-how-to-use-azure-redis-cache)」をご覧ください。

## <a name="client-library"></a>クライアント ライブラリ

Azure Redis Cache は、すべての Redis クライアント API (`StackExchange.Redis` など) と互換性があります。

[NuGet パッケージ](https://www.nuget.org/packages/StackExchange.Redis)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package StackExchange.Redis
```

```bash
dotnet add package StackExchange.Redis
```

### <a name="example"></a>例

この例では、Redis Cache データベース インスタンスに接続し、名前でキャッシュに文字列をいくつか追加した後、それをもう一度取得します。

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

## <a name="management-library"></a>管理ライブラリ

Redis Cache の管理ライブラリを使うと、Redis Cache のリソースとアクセス キーを管理できます。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Redis.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.Redis.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Redis.Fluent
```

### <a name="example"></a>例

この例では、新しい Redis Cache を作成します。

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
> [Management API を探す](/dotnet/api/overview/azure/rediscache/management)


## <a name="samples"></a>サンプル

* [Redis の概要 - Redis を管理する - .NET](https://github.com/Azure-Samples/redis-cache-dotnet-manage-cache)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
