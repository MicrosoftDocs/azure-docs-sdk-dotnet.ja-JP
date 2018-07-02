---
title: .NET 用 Azure Billing ライブラリ
description: .NET 用 Azure Billing ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Billing
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 97a4c642e8be03db7e31e8c9bc71dcf9c3fc1447
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065512"
---
# <a name="azure-billing-libraries-for-net"></a>.NET 用 Azure Billing ライブラリ

## <a name="overview"></a>概要

Azure Billing API (プレビュー) は、Azure の課金情報と請求書へのプログラムによるアクセスを提供します。

## <a name="management-library"></a>管理ライブラリ

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Billing)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.Billing
```

```bash
dotnet add package Microsoft.Azure.Management.Billing
```

### <a name="code-example"></a>コード例

Azure に接続し、請求書の一覧を取得します。

```csharp
/* Include these directives
using Microsoft.Rest.Azure.Authentication;
using Microsoft.Azure.Management.Billing;
using Microsoft.Azure.Management.Billing.Models;
*/

// Log into Azure
var serviceCreds = ApplicationTokenProvider.LoginSilentAsync(tenantId, clientId, secret);
var billingClient = new BillingClient(serviceCreds);
billingClient.SubscriptionId = subscriptionId;

// Get list of invoices
billingClient.Invoices.List();
```

> [!div class="nextstepaction"]
> [Management API を探す](/dotnet/api/overview/azure/billing/management)

## <a name="samples"></a>サンプル

* [Usage API](https://github.com/Azure-Samples/billing-dotnet-usage-api)
* [RateCard API](https://github.com/Azure-Samples/billing-dotnet-ratecard-api)
* [マルチテナント Web アプリケーション](https://github.com/Azure-Samples/billing-dotnet-webapp-multitenant)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
