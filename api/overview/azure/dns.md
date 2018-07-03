---
title: .NET 用 Azure DNS ライブラリ
description: .NET 用 Azure DNS ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, DNS
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: dns
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 0360c4d5a0e276b4adf05d43689896fab6622f51
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065332"
---
# <a name="azure-dns-libraries-for-net"></a><span data-ttu-id="2ddec-104">.NET 用 Azure DNS ライブラリ</span><span class="sxs-lookup"><span data-stu-id="2ddec-104">Azure DNS libraries for .NET</span></span>

<span data-ttu-id="2ddec-105">Azure 内でホストされている DNS ゾーンとレコードを作成および変更するには、.NET 用 Microsoft Azure DNS ライブラリを使います。</span><span class="sxs-lookup"><span data-stu-id="2ddec-105">Use the Microsoft Azure DNS libraries for .NET to create and modify DNS zones and records hosted within Azure.</span></span> <span data-ttu-id="2ddec-106">ゾーンとレコードは、Azure のリソースとして管理されます。</span><span class="sxs-lookup"><span data-stu-id="2ddec-106">Zones and records are managed as Azure Resources.</span></span> <span data-ttu-id="2ddec-107">詳しくは、「[Azure DNS の概要](/azure/dns/dns-overview)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="2ddec-107">Learn more by reading the [Azure DNS overview](/azure/dns/dns-overview).</span></span>

## <a name="management-library"></a><span data-ttu-id="2ddec-108">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="2ddec-108">Management library</span></span>

<span data-ttu-id="2ddec-109">Azure でホストされる DNS ゾーンとレコードを作成および変更するには、管理ライブラリを使います。</span><span class="sxs-lookup"><span data-stu-id="2ddec-109">Use the management library to create and modify DNS zones and records that are hosted in Azure.</span></span>

<span data-ttu-id="2ddec-110">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Dns)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="2ddec-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Dns) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="2ddec-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="2ddec-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Dns
```

```bash
dotnet add package Microsoft.Azure.Management.Dns
```

### <a name="example"></a><span data-ttu-id="2ddec-112">例</span><span class="sxs-lookup"><span data-stu-id="2ddec-112">Example</span></span>

<span data-ttu-id="2ddec-113">次の例では、新しい DNS ゾーンを作成します。</span><span class="sxs-lookup"><span data-stu-id="2ddec-113">The following example creates a new DNS zone.</span></span>

```csharp
/*
using Microsoft.Rest.Azure.Authentication;
using Microsoft.Azure.Management.Dns;
using Microsoft.Azure.Management.Dns.Models;
*/
Microsoft.Rest.ServiceClientCredentials serviceCreds = await ApplicationTokenProvider.LoginSilentAsync(tenantId, clientId, secret);
DnsManagementClient dnsClient = new DnsManagementClient(serviceCreds);            
Zone dnsZoneParams = new Zone("global");
dnsZoneParams.Tags = new Dictionary<string, string>();
dnsZoneParams.Tags.Add("dept", "finance");
Zone dnsZone =
    await dnsClient.Zones.CreateOrUpdateAsync(resourceGroupName, zoneName, dnsZoneParams, null, "*");
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="2ddec-114">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="2ddec-114">Explore the management APIs</span></span>](/dotnet/api/overview/azure/dns/management)

## <a name="samples"></a><span data-ttu-id="2ddec-115">サンプル</span><span class="sxs-lookup"><span data-stu-id="2ddec-115">Samples</span></span>

* [<span data-ttu-id="2ddec-116">Azure DNS .NET SDK サンプル プロジェクト</span><span class="sxs-lookup"><span data-stu-id="2ddec-116">Azure DNS .NET SDK Sample Project</span></span>](https://www.microsoft.com/download/details.aspx?id=47268)

<span data-ttu-id="2ddec-117">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="2ddec-117">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
