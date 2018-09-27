---
title: .NET 用 Azure Traffic Manager ライブラリ
description: .NET 用 Azure Traffic Manager ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: traffic-manager
ms.openlocfilehash: a75b5c566496f73475d24d62288a00c7d5775168
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190824"
---
# <a name="azure-traffic-manager-libraries-for-net"></a><span data-ttu-id="97e41-103">.NET 用 Azure Traffic Manager ライブラリ</span><span class="sxs-lookup"><span data-stu-id="97e41-103">Azure Traffic Manager libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="97e41-104">概要</span><span class="sxs-lookup"><span data-stu-id="97e41-104">Overview</span></span>

<span data-ttu-id="97e41-105">Microsoft Azure Traffic Manager では、さまざまなデータセンターのサービス エンドポイントへのユーザー トラフィックの分散を制御できます。</span><span class="sxs-lookup"><span data-stu-id="97e41-105">Microsoft Azure Traffic Manager allows you to control the distribution of user traffic for service endpoints in different datacenters.</span></span> <span data-ttu-id="97e41-106">Traffic Manager でサポートされるサービス エンドポイントには、Azure VM、Web Apps、およびクラウド サービスが含まれます。</span><span class="sxs-lookup"><span data-stu-id="97e41-106">Service endpoints supported by Traffic Manager include Azure VMs, Web Apps, and cloud services.</span></span> <span data-ttu-id="97e41-107">Azure 以外の外部エンドポイントで Traffic Manager を使用することもできます。</span><span class="sxs-lookup"><span data-stu-id="97e41-107">You can also use Traffic Manager with external, non-Azure endpoints.</span></span>

<span data-ttu-id="97e41-108">Azure Traffic Manager の詳細については、[こちら](/azure/traffic-manager/traffic-manager-overview)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="97e41-108">Learn more about [Azure Traffic Manager](/azure/traffic-manager/traffic-manager-overview).</span></span>  

## <a name="management-library"></a><span data-ttu-id="97e41-109">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="97e41-109">Management library</span></span>

<span data-ttu-id="97e41-110">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.TrafficManager.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="97e41-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.TrafficManager.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="97e41-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="97e41-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.TrafficManager.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.TrafficManager.Fluent
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="97e41-112">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="97e41-112">Explore the management APIs</span></span>](/dotnet/api/overview/azure/trafficmanager/management)

## <a name="samples"></a><span data-ttu-id="97e41-113">サンプル</span><span class="sxs-lookup"><span data-stu-id="97e41-113">Samples</span></span>

<span data-ttu-id="97e41-114">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="97e41-114">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package