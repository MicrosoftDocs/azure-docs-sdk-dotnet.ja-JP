---
title: ".NET 用 Azure App Service ライブラリ"
description: ".NET 用 Azure App Service ライブラリのリファレンス"
keywords: "Azure, .NET, SDK, API, Web アプリ, app service, モバイル, asp.net"
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: app-service
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 9f54fb6aca934f07c6ae23a4ae40dc29fa48ec8b
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/26/2017
---
# <a name="azure-app-service-libraries-for-net"></a>.NET 用 Azure App Service ライブラリ

## <a name="overview"></a>概要

[Azure App Service](/azure/app-service/app-service-value-prop-what-is) は、Web サイト、Web アプリケーション、サービス、REST API のデプロイと拡張を可能にします。

## <a name="management-api"></a>管理 API

Azure App Service でホストされている要素のデプロイ、管理、拡張を行うには、管理 API を使います。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。


#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.AppService.Fluent
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.Management.AppService.Fluent
```

### <a name="code-example"></a>コード例

新しい Web アプリを作成します。

```csharp
/* Include these "using" directives...
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
using Microsoft.Azure.Management.AppService.Fluent;
*/

IWebApp app1 = azure.WebApps
    .Define("MyUniqueWebAddress")
    .WithRegion(Region.USWest)
    .WithNewResourceGroup("MyResourceGroup")
    .WithNewWindowsPlan(PricingTier.StandardS1)
    .Create();
```

> [!div class="nextstepaction"]
> [Management API を探す](/dotnet/api/overview/azure/appservice/management)

### <a name="samples"></a>サンプル

* [.NET SDK for Azure で Web アプリを管理する](https://azure.microsoft.com/en-us/resources/samples/app-service-web-dotnet-manage/)
* [Azure App Service に関する ASP.NET のサンプル](https://azure.microsoft.com/en-us/resources/samples/app-service-web-dotnet-get-started/)

Azure App Service のサンプルの[完全な一覧](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&term=app%20service)を表示します。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package