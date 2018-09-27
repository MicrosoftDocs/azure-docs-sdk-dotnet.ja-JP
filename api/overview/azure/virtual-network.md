---
title: .NET 用 Azure Virtual Network ライブラリ
description: .NET 用 Azure Virtual Network ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: virtual-network
ms.openlocfilehash: 54dd79cf0f5bed1eab7b606b8a6e3b30c797ecd0
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190665"
---
# <a name="azure-virtual-network-libraries-for-net"></a><span data-ttu-id="a8f2a-103">.NET 用 Azure Virtual Network ライブラリ</span><span class="sxs-lookup"><span data-stu-id="a8f2a-103">Azure Virtual Network libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="a8f2a-104">概要</span><span class="sxs-lookup"><span data-stu-id="a8f2a-104">Overview</span></span>
<span data-ttu-id="a8f2a-105">[Azure Virtual Network](/azure/virtual-network/virtual-networks-overview) サービスでは、仮想ネットワーク (VNet) を使って Azure リソースを安全に相互接続することができます。</span><span class="sxs-lookup"><span data-stu-id="a8f2a-105">The [Azure Virtual Network](/azure/virtual-network/virtual-networks-overview) service enables you to securely connect Azure resources to each other with virtual networks (VNets).</span></span> <span data-ttu-id="a8f2a-106">VNet とは、クラウド内のユーザー独自のネットワークを表したものです。</span><span class="sxs-lookup"><span data-stu-id="a8f2a-106">A VNet is a representation of your own network in the cloud.</span></span> <span data-ttu-id="a8f2a-107">また、VNet を相互に接続して、どちらかの VNet に接続されているリソースが相互に通信できるようにすることもできます。</span><span class="sxs-lookup"><span data-stu-id="a8f2a-107">You can also connect VNets to each other, enabling resources connected to either VNet to communicate with each other.</span></span> 

## <a name="management-library"></a><span data-ttu-id="a8f2a-108">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="a8f2a-108">Management library</span></span>

<span data-ttu-id="a8f2a-109">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="a8f2a-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="a8f2a-110">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="a8f2a-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Network.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="a8f2a-111">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="a8f2a-111">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.Network.Fluent
```

### <a name="code-example"></a><span data-ttu-id="a8f2a-112">コード例</span><span class="sxs-lookup"><span data-stu-id="a8f2a-112">Code Example</span></span>
<span data-ttu-id="a8f2a-113">この例では、仮想ネットワークを作成する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="a8f2a-113">This example shows how you can create a virtual network.</span></span>

```csharp
/* 
  Include these "using" directives...
  
  using Microsoft.Azure.Management.Network.Fluent;
  using Microsoft.Azure.Management.Network.Fluent.Models;
*/
using (NetworkManagementClient client = new NetworkManagementClient(credentials))
{
    // Define VNet
    VirtualNetworkInner vnet = new VirtualNetworkInner()
    {
        Location = "West US",
        AddressSpace = new AddressSpace()
        {
            AddressPrefixes = new List<string>() { "0.0.0.0/16" }
        },

        DhcpOptions = new DhcpOptions()
        {
            DnsServers = new List<string>() { "1.1.1.1", "1.1.2.4" }
        },

        Subnets = new List<Subnet>()
        {
            new Subnet()
            {
                Name = subnet1Name,
                AddressPrefix = "1.0.1.0/24",
            },
            new Subnet()
            {
                Name = subnet2Name,
               AddressPrefix = "1.0.2.0/24",
            }
        }
    };
    
    await client.VirtualNetworks.CreateOrUpdateAsync(resourceGroupName, vNetName, vnet);
}

```

> [!div class="nextstepaction"]
> [<span data-ttu-id="a8f2a-114">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="a8f2a-114">Explore the management APIs</span></span>](/dotnet/api/overview/azure/network/management)

## <a name="samples"></a><span data-ttu-id="a8f2a-115">サンプル</span><span class="sxs-lookup"><span data-stu-id="a8f2a-115">Samples</span></span>
- [<span data-ttu-id="a8f2a-116">サブネットのある仮想ネットワークを管理する</span><span class="sxs-lookup"><span data-stu-id="a8f2a-116">Managing Virtual Networks with subnets</span></span>](https://github.com/Azure-Samples/network-dotnet-manage-virtual-network)

<span data-ttu-id="a8f2a-117">アプリで使うことができる他の [.NET サンプル コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="a8f2a-117">Explore more [.NET sample code](https://azure.microsoft.com/resources/samples/?platform=dotnet) that you can use in your apps.</span></span>


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console 
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package 

