---
title: .NET 用 Azure DNS ライブラリ
description: .NET 用 Azure DNS ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, DNS
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: dns
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 34b50defa5f1524ab70c212b091f26016d59e81b
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/23/2017
ms.locfileid: "23487055"
---
# <a name="azure-dns-libraries-for-net"></a><span data-ttu-id="2f63d-104">.NET 用 Azure DNS ライブラリ</span><span class="sxs-lookup"><span data-stu-id="2f63d-104">Azure DNS libraries for .NET</span></span>

<span data-ttu-id="2f63d-105">Azure 内でホストされている DNS ゾーンとレコードを作成および変更するには、.NET 用 Microsoft Azure DNS ライブラリを使います。</span><span class="sxs-lookup"><span data-stu-id="2f63d-105">Use the Microsoft Azure DNS libraries for .NET to create and modify DNS zones and records hosted within Azure.</span></span> <span data-ttu-id="2f63d-106">ゾーンとレコードは、Azure のリソースとして管理されます。</span><span class="sxs-lookup"><span data-stu-id="2f63d-106">Zones and records are managed as Azure Resources.</span></span> <span data-ttu-id="2f63d-107">詳しくは、「[Azure DNS の概要](/azure/dns/dns-overview)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="2f63d-107">Learn more by reading the [Azure DNS overview](/azure/dns/dns-overview).</span></span>

## <a name="management-library"></a><span data-ttu-id="2f63d-108">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="2f63d-108">Management library</span></span>

<span data-ttu-id="2f63d-109">Azure でホストされる DNS ゾーンとレコードを作成および変更するには、管理ライブラリを使います。</span><span class="sxs-lookup"><span data-stu-id="2f63d-109">Use the management library to create and modify DNS zones and records that are hosted in Azure.</span></span>

<span data-ttu-id="2f63d-110">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Dns)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="2f63d-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Dns) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="2f63d-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="2f63d-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Dns
```

```bash
dotnet add package Microsoft.Azure.Management.Dns
```

### <a name="example"></a><span data-ttu-id="2f63d-112">例</span><span class="sxs-lookup"><span data-stu-id="2f63d-112">Example</span></span>

<span data-ttu-id="2f63d-113">次の例では、新しい DNS ゾーンを作成します。</span><span class="sxs-lookup"><span data-stu-id="2f63d-113">The following example creates a new DNS zone.</span></span>

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
> [<span data-ttu-id="2f63d-114">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="2f63d-114">Explore the management APIs</span></span>](/dotnet/api/overview/azure/dns/management)

## <a name="samples"></a><span data-ttu-id="2f63d-115">サンプル</span><span class="sxs-lookup"><span data-stu-id="2f63d-115">Samples</span></span>

* [<span data-ttu-id="2f63d-116">Azure DNS .NET SDK サンプル プロジェクト</span><span class="sxs-lookup"><span data-stu-id="2f63d-116">Azure DNS .NET SDK Sample Project</span></span>](https://www.microsoft.com/download/details.aspx?id=47268)

<span data-ttu-id="2f63d-117">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="2f63d-117">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
