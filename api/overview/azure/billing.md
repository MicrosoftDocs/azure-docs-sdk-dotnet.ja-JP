---
title: .NET 用 Azure Billing ライブラリ
description: .NET 用 Azure Billing ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: multiple
ms.openlocfilehash: 88b90c71d29eacf61e4da2099f8a054d74df4a83
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190255"
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
