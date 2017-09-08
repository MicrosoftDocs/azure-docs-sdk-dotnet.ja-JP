---
title: ".NET 用 Azure DNS ライブラリ"
description: ".NET 用 Azure DNS ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, DNS
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/31/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 57c578f12ea426dc5784658338473f0044d21e5c
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
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
