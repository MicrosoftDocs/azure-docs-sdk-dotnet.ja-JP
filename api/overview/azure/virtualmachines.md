---
title: .NET 用 Azure コンピューティング ライブラリ
description: .NET 用 Azure コンピューティング ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: virtual-machines
ms.openlocfilehash: ee481e0f2448a874629bec36a719e7682407d320
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190695"
---
# <a name="azure-virtual-machine-libraries-for-net"></a><span data-ttu-id="53083-103">.NET 用 Azure 仮想マシン ライブラリ</span><span class="sxs-lookup"><span data-stu-id="53083-103">Azure virtual machine libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="53083-104">概要</span><span class="sxs-lookup"><span data-stu-id="53083-104">Overview</span></span>

<span data-ttu-id="53083-105">Linux または Windows を実行するオンデマンドのスケーラブルなコンピューティング リソースです。</span><span class="sxs-lookup"><span data-stu-id="53083-105">On-demand, scalable computing resources running Linux or Windows.</span></span>

<span data-ttu-id="53083-106">Azure 仮想マシンの概要については、「[Azure Portal で Linux 仮想マシンを作成する](https://review.docs.microsoft.com/azure/virtual-machines/linux/quick-create-portal)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="53083-106">To get started with Azure virtual machines, see [Create a Linux virtual machine with the Azure portal](https://review.docs.microsoft.com/azure/virtual-machines/linux/quick-create-portal).</span></span>

## <a name="management-apis"></a><span data-ttu-id="53083-107">管理 API</span><span class="sxs-lookup"><span data-stu-id="53083-107">Management APIs</span></span>

<span data-ttu-id="53083-108">Azure の Windows 仮想マシンと Linux 仮想マシンは、コードから Management API を使って作成、構成、スケールアウトすることができます。</span><span class="sxs-lookup"><span data-stu-id="53083-108">Create, configure, and scale out Windows and Linux virtual machines in Azure from your code with the management API.</span></span>

<span data-ttu-id="53083-109">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Compute.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="53083-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Compute.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="53083-110">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="53083-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Compute.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="53083-111">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="53083-111">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.Compute.Fluent
```

### <a name="code-example"></a><span data-ttu-id="53083-112">コード例</span><span class="sxs-lookup"><span data-stu-id="53083-112">Code Example</span></span>

<span data-ttu-id="53083-113">Windows VM を作成します。</span><span class="sxs-lookup"><span data-stu-id="53083-113">Create a Windows VM.</span></span>

```csharp
/* Include these "using" directives...
using Microsoft.Azure.Management.Compute.Fluent;
using Microsoft.Azure.Management.Compute.Fluent.Models;
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
*/

IVirtualMachine windowsVM = azure.VirtualMachines.Define("MyVirtualMachine")
    .WithRegion(Region.USEast)
    .WithNewResourceGroup("MyResourceGroup")
    .WithNewPrimaryNetwork("10.0.0.0/28")
    .WithPrimaryPrivateIPAddressDynamic()
    .WithNewPrimaryPublicIPAddress("MyIPAddressLabel")
    .WithPopularWindowsImage(KnownWindowsVirtualMachineImage.WindowsServer2012R2Datacenter)
    .WithAdminUsername("UserName")
    .WithAdminPassword("Password")
    .WithSize(VirtualMachineSizeTypes.StandardD3V2)
    .Create();
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="53083-114">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="53083-114">Explore the management APIs</span></span>](https://docs.microsoft.com/dotnet/api/overview/azure/virtualmachines/management?view=azure-dotnet)

### <a name="samples"></a><span data-ttu-id="53083-115">サンプル</span><span class="sxs-lookup"><span data-stu-id="53083-115">Samples</span></span>

* [<span data-ttu-id="53083-116">仮想マシンの作成と管理</span><span class="sxs-lookup"><span data-stu-id="53083-116">Create and manage virtual machines</span></span>](/dotnet/azure/dotnet-sdk-azure-virtual-machine-samples)
* [<span data-ttu-id="53083-117">.NET からテンプレートを使用して SSH 対応 VM をデプロイする</span><span class="sxs-lookup"><span data-stu-id="53083-117">Deploy an SSH-enabled VM with a Template with .NET</span></span>](https://azure.microsoft.com/resources/samples/resource-manager-dotnet-template-deployment/)

<span data-ttu-id="53083-118">仮想マシン サンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=VM)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="53083-118">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=VM) of virtual machine samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
