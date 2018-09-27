---
title: .NET 用 Azure Resource Manager ライブラリ
description: .NET 用 Azure Resource Manager ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: multiple
ms.openlocfilehash: 6d3a27c5f7ba94f5579723cc4f798826c8bdefd6
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190845"
---
# <a name="azure-resource-manager-libraries-for-net"></a><span data-ttu-id="6a780-103">.NET 用 Azure Resource Manager ライブラリ</span><span class="sxs-lookup"><span data-stu-id="6a780-103">Azure Resource Manager libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="6a780-104">概要</span><span class="sxs-lookup"><span data-stu-id="6a780-104">Overview</span></span>

<span data-ttu-id="6a780-105">Azure Resource Manager を使用すると、ソリューション内の複数のリソースを 1 つのグループとして作業できます。</span><span class="sxs-lookup"><span data-stu-id="6a780-105">Azure Resource Manager enables you to work with the resources in your solution as a group.</span></span>  <span data-ttu-id="6a780-106">Resource Manager について詳しくは、「[Azure Resource Manager の概要](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="6a780-106">For more information about Resource Manager, see [Azure Resource Manager overview](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview).</span></span>

## <a name="management-library"></a><span data-ttu-id="6a780-107">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="6a780-107">Management library</span></span>

<span data-ttu-id="6a780-108">.NET 用 Azure Resource Manager ライブラリを使うと、リソースおよびリソース グループの作成、更新、削除、一覧表示を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="6a780-108">The Azure Resource Manager library for .NET enables you to create, update, delete, and list resources and resource groups.</span></span>

<span data-ttu-id="6a780-109">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.ResourceManager.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="6a780-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.ResourceManager.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="6a780-110">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="6a780-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.ResourceManager.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.ResourceManager.Fluent
```

### <a name="example"></a><span data-ttu-id="6a780-111">例</span><span class="sxs-lookup"><span data-stu-id="6a780-111">Example</span></span>

<span data-ttu-id="6a780-112">この例では、新しいリソース グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="6a780-112">This example creates a new resource group.</span></span>

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
> [<span data-ttu-id="6a780-113">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="6a780-113">Explore the management APIs</span></span>](/dotnet/api/overview/azure/resources/management)


## <a name="samples"></a><span data-ttu-id="6a780-114">サンプル</span><span class="sxs-lookup"><span data-stu-id="6a780-114">Samples</span></span>

* [<span data-ttu-id="6a780-115">リソース グループの管理</span><span class="sxs-lookup"><span data-stu-id="6a780-115">Manage resource groups</span></span>](https://github.com/Azure-Samples/resources-dotnet-manage-resource-group)
* [<span data-ttu-id="6a780-116">リソースの管理</span><span class="sxs-lookup"><span data-stu-id="6a780-116">Manage resources</span></span>](https://github.com/Azure-Samples/resources-dotnet-manage-resource)
* [<span data-ttu-id="6a780-117">ARM テンプレートを使ってリソースをデプロイする</span><span class="sxs-lookup"><span data-stu-id="6a780-117">Deploy resources with ARM templates</span></span>](https://github.com/Azure-Samples/resources-dotnet-deploy-using-arm-template)
* [<span data-ttu-id="6a780-118">ARM テンプレートを使ってリソースをデプロイする (進行状況表示付き)</span><span class="sxs-lookup"><span data-stu-id="6a780-118">Deploy resources with ARM templates (with progress)</span></span>](https://github.com/Azure-Samples/resources-dotnet-deploy-using-arm-template-with-progress)


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
