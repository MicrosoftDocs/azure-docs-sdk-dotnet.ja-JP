---
title: .NET 用 Azure DNS ライブラリ
description: .NET 用 Azure DNS ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: dns
ms.openlocfilehash: b9ab6359aaa1e4e9b6e99e7a7b007928d18f3453
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190195"
---
# <a name="azure-dns-libraries-for-net"></a>.NET 用 Azure DNS ライブラリ

Azure 内でホストされている DNS ゾーンとレコードを作成および変更するには、.NET 用 Microsoft Azure DNS ライブラリを使います。 ゾーンとレコードは、Azure のリソースとして管理されます。 詳しくは、「[Azure DNS の概要](/azure/dns/dns-overview)」をご覧ください。

## <a name="management-library"></a>管理ライブラリ

Azure でホストされる DNS ゾーンとレコードを作成および変更するには、管理ライブラリを使います。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Dns)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.Dns
```

```bash
dotnet add package Microsoft.Azure.Management.Dns
```

### <a name="example"></a>例

次の例では、新しい DNS ゾーンを作成します。

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
> [Management API を探す](/dotnet/api/overview/azure/dns/management)

## <a name="samples"></a>サンプル

* [Azure DNS .NET SDK サンプル プロジェクト](https://www.microsoft.com/download/details.aspx?id=47268)

アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
