---
title: .NET 用 Azure Resource Manager ライブラリ
description: .NET 用 Azure Resource Manager ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Resource Manager
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter, svc-overview
ms.openlocfilehash: f9fe96fcdc94d3d27445f462c5220def9f2966da
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/26/2017
ms.locfileid: "23566373"
---
# <a name="azure-resource-manager-libraries-for-net"></a><span data-ttu-id="800f3-104">.NET 用 Azure Resource Manager ライブラリ</span><span class="sxs-lookup"><span data-stu-id="800f3-104">Azure Resource Manager libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="800f3-105">概要</span><span class="sxs-lookup"><span data-stu-id="800f3-105">Overview</span></span>

<span data-ttu-id="800f3-106">Azure Resource Manager を使用すると、ソリューション内の複数のリソースを 1 つのグループとして作業できます。</span><span class="sxs-lookup"><span data-stu-id="800f3-106">Azure Resource Manager enables you to work with the resources in your solution as a group.</span></span>  <span data-ttu-id="800f3-107">Resource Manager について詳しくは、「[Azure Resource Manager の概要](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="800f3-107">For more information about Resource Manager, see [Azure Resource Manager overview](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview).</span></span>

## <a name="management-library"></a><span data-ttu-id="800f3-108">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="800f3-108">Management library</span></span>

<span data-ttu-id="800f3-109">.NET 用 Azure Resource Manager ライブラリを使うと、リソースおよびリソース グループの作成、更新、削除、一覧表示を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="800f3-109">The Azure Resource Manager library for .NET enables you to create, update, delete, and list resources and resource groups.</span></span>

<span data-ttu-id="800f3-110">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.ResourceManager.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="800f3-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.ResourceManager.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="800f3-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="800f3-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.ResourceManager.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.ResourceManager.Fluent
```

### <a name="example"></a><span data-ttu-id="800f3-112">例</span><span class="sxs-lookup"><span data-stu-id="800f3-112">Example</span></span>

<span data-ttu-id="800f3-113">この例では、新しいリソース グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="800f3-113">This example creates a new resource group.</span></span>

```csharp
/* Include these "using" directives.
using Microsoft.Azure.Management.ResourceManager.Fluent;
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
*/

IResourceGroup resourceGroup = azure.ResourceGroups
    .Define("ResourceGroupName")
    .WithRegion(Region.USWest)
    .Create();
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="800f3-114">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="800f3-114">Explore the management APIs</span></span>](/dotnet/api/overview/azure/resources/management)


## <a name="samples"></a><span data-ttu-id="800f3-115">サンプル</span><span class="sxs-lookup"><span data-stu-id="800f3-115">Samples</span></span>

* [<span data-ttu-id="800f3-116">リソース グループの管理</span><span class="sxs-lookup"><span data-stu-id="800f3-116">Manage resource groups</span></span>](https://github.com/Azure-Samples/resources-dotnet-manage-resource-group)
* [<span data-ttu-id="800f3-117">リソースの管理</span><span class="sxs-lookup"><span data-stu-id="800f3-117">Manage resources</span></span>](https://github.com/Azure-Samples/resources-dotnet-manage-resource)
* [<span data-ttu-id="800f3-118">ARM テンプレートを使ってリソースをデプロイする</span><span class="sxs-lookup"><span data-stu-id="800f3-118">Deploy resources with ARM templates</span></span>](https://github.com/Azure-Samples/resources-dotnet-deploy-using-arm-template)
* [<span data-ttu-id="800f3-119">ARM テンプレートを使ってリソースをデプロイする (進行状況表示付き)</span><span class="sxs-lookup"><span data-stu-id="800f3-119">Deploy resources with ARM templates (with progress)</span></span>](https://github.com/Azure-Samples/resources-dotnet-deploy-using-arm-template-with-progress)


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
