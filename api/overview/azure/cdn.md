---
title: .NET 用 Azure CDN ライブラリ
description: .NET 用 Azure CDN ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: azure-cdn
ms.openlocfilehash: b06b886531510d442c415fdc483d8083b6622c8e
ms.sourcegitcommit: 1cf4550df8ed3236d838f561f6177d14d89b5e44
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2018
ms.locfileid: "49348064"
---
# <a name="azure-cdn-libraries-for-net"></a>.NET 用 Azure CDN ライブラリ

## <a name="overview"></a>概要

Azure Content Delivery Network (CDN) では、戦略的に配置された場所に静的 Web コンテンツをキャッシュし、ユーザーへのコンテンツ配信に最大スループットを使用できます。 CDN では、世界各地の物理ノードにコンテンツをキャッシュすることによって、高帯域幅コンテンツを配信するためのグローバル ソリューションを開発者に提供します。

Azure CDN について詳しくは、「[Azure Content Delivery Network の概要](https://docs.microsoft.com/azure/cdn/cdn-overview)」をご覧ください。


## <a name="management-library"></a>管理ライブラリ

.NET 用 Azure CDN ライブラリを使うと、CDN プロファイルとエンドポイントの作成と管理を自動化できます。 

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Cdn.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.Cdn.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Cdn.Fluent
```

### <a name="example"></a>例

この例では、`www.contoso.com` を指し示す新しいエンドポイントで新しい CDN プロファイルを作成します。

```csharp
/* Include these "using" directives.
using Microsoft.Azure.Management.Cdn.Fluent;
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
*/

ICdnProfile profileDefinition = azure.CdnProfiles.Define("CdnProfileName")
    .WithRegion(Region.USCentral)
    .WithExistingResourceGroup("ResourceGroupName")
    .WithStandardVerizonSku()
    .WithNewEndpoint("www.contoso.com")
    .Create();

```

> [!div class="nextstepaction"]
> [Management API を探す](/dotnet/api/overview/azure/cdn/management)


## <a name="samples"></a>サンプル

* [CDN の概要 - CDN の管理 - .NET](https://github.com/Azure-Samples/cdn-dotnet-manage-cdn)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
