---
title: .NET 用 Azure App Service ライブラリ
description: .NET 用 Azure App Service ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Web アプリ, app service, モバイル, asp.net
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: app-service
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 0fee28930dff5075cdd84fe3cb88850e07bc6ccb
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065802"
---
# <a name="azure-app-service-libraries-for-net"></a><span data-ttu-id="dbea1-104">.NET 用 Azure App Service ライブラリ</span><span class="sxs-lookup"><span data-stu-id="dbea1-104">Azure App Service libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="dbea1-105">概要</span><span class="sxs-lookup"><span data-stu-id="dbea1-105">Overview</span></span>

<span data-ttu-id="dbea1-106">[Azure App Service](/azure/app-service/app-service-value-prop-what-is) は、Web サイト、Web アプリケーション、サービス、REST API のデプロイと拡張を可能にします。</span><span class="sxs-lookup"><span data-stu-id="dbea1-106">[Azure App Service](/azure/app-service/app-service-value-prop-what-is) allows you to deploy and scale websites, web applications, services, and REST APIs.</span></span>

## <a name="management-api"></a><span data-ttu-id="dbea1-107">管理 API</span><span class="sxs-lookup"><span data-stu-id="dbea1-107">Management API</span></span>

<span data-ttu-id="dbea1-108">Azure App Service でホストされている要素のデプロイ、管理、拡張を行うには、管理 API を使います。</span><span class="sxs-lookup"><span data-stu-id="dbea1-108">Deploy, manage, and scale elements hosted in Azure App Service with the management API.</span></span>

<span data-ttu-id="dbea1-109">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="dbea1-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>


#### <a name="visual-studio-package-manager"></a><span data-ttu-id="dbea1-110">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="dbea1-110">Visual Studio package manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.AppService.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="dbea1-111">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="dbea1-111">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.AppService.Fluent
```

### <a name="code-example"></a><span data-ttu-id="dbea1-112">コード例</span><span class="sxs-lookup"><span data-stu-id="dbea1-112">Code Example</span></span>

<span data-ttu-id="dbea1-113">新しい Web アプリを作成します。</span><span class="sxs-lookup"><span data-stu-id="dbea1-113">Create a new web app.</span></span>

```csharp
/* Include these "using" directives...
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
using Microsoft.Azure.Management.AppService.Fluent;
*/

IWebApp app1 = azure.WebApps
    .Define("MyUniqueWebAddress")
    .WithRegion(Region.USWest)
    .WithNewResourceGroup("MyResourceGroup")
    .WithNewWindowsPlan(PricingTier.StandardS1)
    .Create();
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="dbea1-114">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="dbea1-114">Explore the Management APIs</span></span>](/dotnet/api/overview/azure/appservice/management)

### <a name="samples"></a><span data-ttu-id="dbea1-115">サンプル</span><span class="sxs-lookup"><span data-stu-id="dbea1-115">Samples</span></span>

* [<span data-ttu-id="dbea1-116">.NET SDK for Azure で Web アプリを管理する</span><span class="sxs-lookup"><span data-stu-id="dbea1-116">Manage your web apps with the .NET SDK for Azure</span></span>](https://azure.microsoft.com/resources/samples/app-service-web-dotnet-manage/)
* [<span data-ttu-id="dbea1-117">Azure App Service に関する ASP.NET のサンプル</span><span class="sxs-lookup"><span data-stu-id="dbea1-117">ASP.NET sample for Azure App Service</span></span>](https://azure.microsoft.com/resources/samples/app-service-web-dotnet-get-started/)

<span data-ttu-id="dbea1-118">Azure App Service のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=app%20service)を表示します。</span><span class="sxs-lookup"><span data-stu-id="dbea1-118">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=app%20service) of Azure App Service samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package