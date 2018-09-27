---
title: .NET 用 Azure CDN ライブラリ
description: .NET 用 Azure CDN ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: cdn
ms.openlocfilehash: 6475edbe4fa0d01739de5cff76038aa6e7fd2cf9
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190125"
---
# <a name="azure-cdn-libraries-for-net"></a><span data-ttu-id="71553-103">.NET 用 Azure CDN ライブラリ</span><span class="sxs-lookup"><span data-stu-id="71553-103">Azure CDN libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="71553-104">概要</span><span class="sxs-lookup"><span data-stu-id="71553-104">Overview</span></span>

<span data-ttu-id="71553-105">Azure Content Delivery Network (CDN) では、戦略的に配置された場所に静的 Web コンテンツをキャッシュし、ユーザーへのコンテンツ配信に最大スループットを使用できます。</span><span class="sxs-lookup"><span data-stu-id="71553-105">The Azure Content Delivery Network (CDN) caches static web content at strategically placed locations to provide maximum throughput for delivering content to users.</span></span> <span data-ttu-id="71553-106">CDN では、世界各地の物理ノードにコンテンツをキャッシュすることによって、高帯域幅コンテンツを配信するためのグローバル ソリューションを開発者に提供します。</span><span class="sxs-lookup"><span data-stu-id="71553-106">The CDN offers developers a global solution for delivering high-bandwidth content by caching the content at physical nodes across the world.</span></span>

<span data-ttu-id="71553-107">Azure CDN について詳しくは、「[Azure Content Delivery Network の概要](https://docs.microsoft.com/azure/cdn/cdn-overview)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="71553-107">To learn more about Azure CDN, see [Overview of the Azure Content Delivery Network](https://docs.microsoft.com/azure/cdn/cdn-overview).</span></span>


## <a name="management-library"></a><span data-ttu-id="71553-108">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="71553-108">Management library</span></span>

<span data-ttu-id="71553-109">.NET 用 Azure CDN ライブラリを使うと、CDN プロファイルとエンドポイントの作成と管理を自動化できます。</span><span class="sxs-lookup"><span data-stu-id="71553-109">You can use the Azure CDN Library for .NET to automate creation and management of CDN profiles and endpoints.</span></span> 

<span data-ttu-id="71553-110">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Cdn.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="71553-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Cdn.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="71553-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="71553-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Cdn.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Cdn.Fluent
```

### <a name="example"></a><span data-ttu-id="71553-112">例</span><span class="sxs-lookup"><span data-stu-id="71553-112">Example</span></span>

<span data-ttu-id="71553-113">この例では、`www.contoso.com` を指し示す新しいエンドポイントで新しい CDN プロファイルを作成します。</span><span class="sxs-lookup"><span data-stu-id="71553-113">This example creates a new CDN profile with a new endpoint pointed to `www.contoso.com`.</span></span>

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
> [<span data-ttu-id="71553-114">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="71553-114">Explore the management APIs</span></span>](/dotnet/api/overview/azure/cdn/management)


## <a name="samples"></a><span data-ttu-id="71553-115">サンプル</span><span class="sxs-lookup"><span data-stu-id="71553-115">Samples</span></span>

* [<span data-ttu-id="71553-116">CDN の概要 - CDN の管理 - .NET</span><span class="sxs-lookup"><span data-stu-id="71553-116">Getting started with CDN - Manage CDN - in .NET</span></span>](https://github.com/Azure-Samples/cdn-dotnet-manage-cdn)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
