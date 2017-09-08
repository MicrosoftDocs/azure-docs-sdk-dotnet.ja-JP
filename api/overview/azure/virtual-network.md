---
title: ".NET 用 Azure Virtual Network ライブラリ"
description: ".NET 用 Azure Virtual Network ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Virtual Network
author: camsoper
ms.author: casoper
manager: douge
ms.date: 08/01/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: ea605dbd632ef4deb9c97c8de3474246dd4be30d
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-virtual-network-libraries-for-net"></a>.NET 用 Azure Virtual Network ライブラリ

## <a name="overview"></a>概要
[Azure Virtual Network](/azure/virtual-network/virtual-networks-overview) サービスでは、仮想ネットワーク (VNet) を使って Azure リソースを安全に相互接続することができます。 VNet とは、クラウド内のユーザー独自のネットワークを表したものです。 また、VNet を相互に接続して、どちらかの VNet に接続されているリソースが相互に通信できるようにすることもできます。 

## <a name="management-library"></a>管理ライブラリ

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.Network.Fluent
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.Management.Network.Fluent
```

### <a name="code-example"></a>コード例
この例では、仮想ネットワークを作成する方法を示します。

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
> [Management API を探す](/dotnet/api/overview/azure/network/management)

## <a name="samples"></a>サンプル
- [サブネットのある仮想ネットワークを管理する](https://github.com/Azure-Samples/network-dotnet-manage-virtual-network)

アプリで使うことができる他の [.NET サンプル コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console 
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package 

