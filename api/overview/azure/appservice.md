---
title: .NET 用 Azure App Service ライブラリ
description: .NET 用 Azure App Service ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: app-service
ms.openlocfilehash: 82f8eccfafd2f7b1cf1df1ce0f40212509ccddd3
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47189995"
---
# <a name="azure-app-service-libraries-for-net"></a><span data-ttu-id="d91cc-103">.NET 用 Azure App Service ライブラリ</span><span class="sxs-lookup"><span data-stu-id="d91cc-103">Azure App Service libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="d91cc-104">概要</span><span class="sxs-lookup"><span data-stu-id="d91cc-104">Overview</span></span>

<span data-ttu-id="d91cc-105">[Azure App Service](/azure/app-service/app-service-value-prop-what-is) は、Web サイト、Web アプリケーション、サービス、REST API のデプロイと拡張を可能にします。</span><span class="sxs-lookup"><span data-stu-id="d91cc-105">[Azure App Service](/azure/app-service/app-service-value-prop-what-is) allows you to deploy and scale websites, web applications, services, and REST APIs.</span></span>

## <a name="management-api"></a><span data-ttu-id="d91cc-106">管理 API</span><span class="sxs-lookup"><span data-stu-id="d91cc-106">Management API</span></span>

<span data-ttu-id="d91cc-107">Azure App Service でホストされている要素のデプロイ、管理、拡張を行うには、管理 API を使います。</span><span class="sxs-lookup"><span data-stu-id="d91cc-107">Deploy, manage, and scale elements hosted in Azure App Service with the management API.</span></span>

<span data-ttu-id="d91cc-108">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="d91cc-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>


#### <a name="visual-studio-package-manager"></a><span data-ttu-id="d91cc-109">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="d91cc-109">Visual Studio package manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.AppService.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="d91cc-110">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="d91cc-110">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.AppService.Fluent
```

### <a name="code-example"></a><span data-ttu-id="d91cc-111">コード例</span><span class="sxs-lookup"><span data-stu-id="d91cc-111">Code Example</span></span>

<span data-ttu-id="d91cc-112">新しい Web アプリを作成します。</span><span class="sxs-lookup"><span data-stu-id="d91cc-112">Create a new web app.</span></span>

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
> [<span data-ttu-id="d91cc-113">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="d91cc-113">Explore the Management APIs</span></span>](/dotnet/api/overview/azure/appservice/management)

### <a name="samples"></a><span data-ttu-id="d91cc-114">サンプル</span><span class="sxs-lookup"><span data-stu-id="d91cc-114">Samples</span></span>

* [<span data-ttu-id="d91cc-115">.NET SDK for Azure で Web アプリを管理する</span><span class="sxs-lookup"><span data-stu-id="d91cc-115">Manage your web apps with the .NET SDK for Azure</span></span>](https://azure.microsoft.com/resources/samples/app-service-web-dotnet-manage/)
* [<span data-ttu-id="d91cc-116">Azure App Service に関する ASP.NET のサンプル</span><span class="sxs-lookup"><span data-stu-id="d91cc-116">ASP.NET sample for Azure App Service</span></span>](https://azure.microsoft.com/resources/samples/app-service-web-dotnet-get-started/)

<span data-ttu-id="d91cc-117">Azure App Service のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=app%20service)を表示します。</span><span class="sxs-lookup"><span data-stu-id="d91cc-117">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=app%20service) of Azure App Service samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package