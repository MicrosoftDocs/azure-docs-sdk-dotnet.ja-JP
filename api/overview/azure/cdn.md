---
title: .NET 用 Azure CDN ライブラリ
description: .NET 用 Azure CDN ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, CDN
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: cdn
ms.custom: devcenter, svc-overview
ms.openlocfilehash: afc63f943fcac3afd9afb7d85f6e699079829244
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/26/2017
ms.locfileid: "23566333"
---
# <a name="azure-cdn-libraries-for-net"></a><span data-ttu-id="7f05f-104">.NET 用 Azure CDN ライブラリ</span><span class="sxs-lookup"><span data-stu-id="7f05f-104">Azure CDN libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="7f05f-105">概要</span><span class="sxs-lookup"><span data-stu-id="7f05f-105">Overview</span></span>

<span data-ttu-id="7f05f-106">Azure Content Delivery Network (CDN) では、戦略的に配置された場所に静的 Web コンテンツをキャッシュし、ユーザーへのコンテンツ配信に最大スループットを使用できます。</span><span class="sxs-lookup"><span data-stu-id="7f05f-106">The Azure Content Delivery Network (CDN) caches static web content at strategically placed locations to provide maximum throughput for delivering content to users.</span></span> <span data-ttu-id="7f05f-107">CDN では、世界各地の物理ノードにコンテンツをキャッシュすることによって、高帯域幅コンテンツを配信するためのグローバル ソリューションを開発者に提供します。</span><span class="sxs-lookup"><span data-stu-id="7f05f-107">The CDN offers developers a global solution for delivering high-bandwidth content by caching the content at physical nodes across the world.</span></span>

<span data-ttu-id="7f05f-108">Azure CDN について詳しくは、「[Azure Content Delivery Network の概要](https://docs.microsoft.com/azure/cdn/cdn-overview)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="7f05f-108">To learn more about Azure CDN, see [Overview of the Azure Content Delivery Network](https://docs.microsoft.com/azure/cdn/cdn-overview).</span></span>


## <a name="management-library"></a><span data-ttu-id="7f05f-109">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="7f05f-109">Management library</span></span>

<span data-ttu-id="7f05f-110">.NET 用 Azure CDN ライブラリを使うと、CDN プロファイルとエンドポイントの作成と管理を自動化できます。</span><span class="sxs-lookup"><span data-stu-id="7f05f-110">You can use the Azure CDN Library for .NET to automate creation and management of CDN profiles and endpoints.</span></span> 

<span data-ttu-id="7f05f-111">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Cdn.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="7f05f-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Cdn.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="7f05f-112">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="7f05f-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Cdn.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Cdn.Fluent
```

### <a name="example"></a><span data-ttu-id="7f05f-113">例</span><span class="sxs-lookup"><span data-stu-id="7f05f-113">Example</span></span>

<span data-ttu-id="7f05f-114">この例では、`www.contoso.com` を指し示す新しいエンドポイントで新しい CDN プロファイルを作成します。</span><span class="sxs-lookup"><span data-stu-id="7f05f-114">This example creates a new CDN profile with a new endpoint pointed to `www.contoso.com`.</span></span>

```csharp
/* Include these "using" directives.
using Microsoft.Azure.Management.Cdn.Fluent;
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
*/

ICdnProfile profileDefinition = azure.CdnProfiles.Define("CdnProfileName")
    .WithRegion(Region.USCentral)
    .WithExistingResourceGroup("ResourceGroupName")
    .WithStandardVerizonSku()
    .WithNewEndpoint("www.contoso.com")
    .Create();

```

> [!div class="nextstepaction"]
> [<span data-ttu-id="7f05f-115">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="7f05f-115">Explore the management APIs</span></span>](/dotnet/api/overview/azure/cdn/management)


## <a name="samples"></a><span data-ttu-id="7f05f-116">サンプル</span><span class="sxs-lookup"><span data-stu-id="7f05f-116">Samples</span></span>

* [<span data-ttu-id="7f05f-117">CDN の概要 - CDN の管理 - .NET</span><span class="sxs-lookup"><span data-stu-id="7f05f-117">Getting started with CDN - Manage CDN - in .NET</span></span>](https://github.com/Azure-Samples/cdn-dotnet-manage-cdn)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
