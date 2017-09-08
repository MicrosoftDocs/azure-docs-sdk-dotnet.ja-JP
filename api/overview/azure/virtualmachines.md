---
title: ".NET 用 Azure コンピューティング ライブラリ"
description: ".NET 用 Azure コンピューティング ライブラリのリファレンス"
keywords: "Azure, .NET, SDK, API, VM, 仮想マシン, コンピューティング"
author: camsoper
ms.author: casoper
manager: douge
ms.date: 06/20/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: b30c1433b8f25941fc1d4ea4718aa07c0a870580
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-virtual-machine-libraries-for-net"></a><span data-ttu-id="94378-104">.NET 用 Azure 仮想マシン ライブラリ</span><span class="sxs-lookup"><span data-stu-id="94378-104">Azure virtual machine libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="94378-105">概要</span><span class="sxs-lookup"><span data-stu-id="94378-105">Overview</span></span>

<span data-ttu-id="94378-106">Linux または Windows を実行するオンデマンドのスケーラブルなコンピューティング リソースです。</span><span class="sxs-lookup"><span data-stu-id="94378-106">On-demand, scalable computing resources running Linux or Windows.</span></span>

<span data-ttu-id="94378-107">Azure 仮想マシンの概要については、「[Azure Portal で Linux 仮想マシンを作成する](https://review.docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-portal)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="94378-107">To get started with Azure virtual machines, see [Create a Linux virtual machine with the Azure portal](https://review.docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-portal).</span></span>

## <a name="management-apis"></a><span data-ttu-id="94378-108">管理 API</span><span class="sxs-lookup"><span data-stu-id="94378-108">Management APIs</span></span>

<span data-ttu-id="94378-109">Azure の Windows 仮想マシンと Linux 仮想マシンは、コードから Management API を使って作成、構成、スケールアウトすることができます。</span><span class="sxs-lookup"><span data-stu-id="94378-109">Create, configure, and scale out Windows and Linux virtual machines in Azure from your code with the management API.</span></span>

<span data-ttu-id="94378-110">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Compute.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="94378-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Compute.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="94378-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="94378-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Compute.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="94378-112">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="94378-112">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.Compute.Fluent
```

### <a name="code-example"></a><span data-ttu-id="94378-113">コード例</span><span class="sxs-lookup"><span data-stu-id="94378-113">Code Example</span></span>

<span data-ttu-id="94378-114">Windows VM を作成します。</span><span class="sxs-lookup"><span data-stu-id="94378-114">Create a Windows VM.</span></span>

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
> [<span data-ttu-id="94378-115">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="94378-115">Explore the management APIs</span></span>](https://review.docs.microsoft.com/en-us/dotnet/api/overview/azure/virtualmachines/management?view=azure-dotnet)

### <a name="samples"></a><span data-ttu-id="94378-116">サンプル</span><span class="sxs-lookup"><span data-stu-id="94378-116">Samples</span></span>

* [<span data-ttu-id="94378-117">仮想マシンの作成と管理</span><span class="sxs-lookup"><span data-stu-id="94378-117">Create and manage virtual machines</span></span>](/dotnet/azure/dotnet-sdk-azure-virtual-machine-samples)
* [<span data-ttu-id="94378-118">.NET からテンプレートを使用して SSH 対応 VM をデプロイする</span><span class="sxs-lookup"><span data-stu-id="94378-118">Deploy an SSH-enabled VM with a Template with .NET</span></span>](https://azure.microsoft.com/en-us/resources/samples/resource-manager-dotnet-template-deployment/)

<span data-ttu-id="94378-119">仮想マシン サンプルの[完全な一覧](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&term=VM)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="94378-119">View the [complete list](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&term=VM) of virtual machine samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
