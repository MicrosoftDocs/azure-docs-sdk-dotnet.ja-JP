---
title: ".NET 用 Azure Traffic Manager ライブラリ"
description: ".NET 用 Azure Traffic Manager ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Traffic Manager
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 0fc747c25fe368b5d67f70af1e2b9afc5e07f615
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-traffic-manager-libraries-for-net"></a><span data-ttu-id="647b3-104">.NET 用 Azure Traffic Manager ライブラリ</span><span class="sxs-lookup"><span data-stu-id="647b3-104">Azure Traffic Manager libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="647b3-105">概要</span><span class="sxs-lookup"><span data-stu-id="647b3-105">Overview</span></span>

<span data-ttu-id="647b3-106">Microsoft Azure Traffic Manager では、さまざまなデータセンターのサービス エンドポイントへのユーザー トラフィックの分散を制御できます。</span><span class="sxs-lookup"><span data-stu-id="647b3-106">Microsoft Azure Traffic Manager allows you to control the distribution of user traffic for service endpoints in different datacenters.</span></span> <span data-ttu-id="647b3-107">Traffic Manager でサポートされるサービス エンドポイントには、Azure VM、Web Apps、およびクラウド サービスが含まれます。</span><span class="sxs-lookup"><span data-stu-id="647b3-107">Service endpoints supported by Traffic Manager include Azure VMs, Web Apps, and cloud services.</span></span> <span data-ttu-id="647b3-108">Azure 以外の外部エンドポイントで Traffic Manager を使用することもできます。</span><span class="sxs-lookup"><span data-stu-id="647b3-108">You can also use Traffic Manager with external, non-Azure endpoints.</span></span>

<span data-ttu-id="647b3-109">Azure Traffic Manager の詳細については、[こちら](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-overview)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="647b3-109">Learn more about [Azure Traffic Manager](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-overview).</span></span>  

## <a name="management-library"></a><span data-ttu-id="647b3-110">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="647b3-110">Management library</span></span>

<span data-ttu-id="647b3-111">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.TrafficManager.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="647b3-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.TrafficManager.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="647b3-112">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="647b3-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.TrafficManager.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.TrafficManager.Fluent
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="647b3-113">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="647b3-113">Explore the management APIs</span></span>](/dotnet/api/overview/azure/trafficmanager/management)

## <a name="samples"></a><span data-ttu-id="647b3-114">サンプル</span><span class="sxs-lookup"><span data-stu-id="647b3-114">Samples</span></span>

<span data-ttu-id="647b3-115">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="647b3-115">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package