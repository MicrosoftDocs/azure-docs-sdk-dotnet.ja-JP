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
# <a name="azure-billing-libraries-for-net"></a><span data-ttu-id="38c8d-103">.NET 用 Azure Billing ライブラリ</span><span class="sxs-lookup"><span data-stu-id="38c8d-103">Azure Billing libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="38c8d-104">概要</span><span class="sxs-lookup"><span data-stu-id="38c8d-104">Overview</span></span>

<span data-ttu-id="38c8d-105">Azure Billing API (プレビュー) は、Azure の課金情報と請求書へのプログラムによるアクセスを提供します。</span><span class="sxs-lookup"><span data-stu-id="38c8d-105">Azure Billing API (preview) provides programmatic access to your Azure billing information and invoices.</span></span>

## <a name="management-library"></a><span data-ttu-id="38c8d-106">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="38c8d-106">Management library</span></span>

<span data-ttu-id="38c8d-107">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Billing)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="38c8d-107">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Billing) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="38c8d-108">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="38c8d-108">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Billing
```

```bash
dotnet add package Microsoft.Azure.Management.Billing
```

### <a name="code-example"></a><span data-ttu-id="38c8d-109">コード例</span><span class="sxs-lookup"><span data-stu-id="38c8d-109">Code Example</span></span>

<span data-ttu-id="38c8d-110">Azure に接続し、請求書の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="38c8d-110">Connect to Azure and get a list of invoices.</span></span>

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
> [<span data-ttu-id="38c8d-111">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="38c8d-111">Explore the management APIs</span></span>](/dotnet/api/overview/azure/billing/management)

## <a name="samples"></a><span data-ttu-id="38c8d-112">サンプル</span><span class="sxs-lookup"><span data-stu-id="38c8d-112">Samples</span></span>

* [<span data-ttu-id="38c8d-113">Usage API</span><span class="sxs-lookup"><span data-stu-id="38c8d-113">Usage API</span></span>](https://github.com/Azure-Samples/billing-dotnet-usage-api)
* [<span data-ttu-id="38c8d-114">RateCard API</span><span class="sxs-lookup"><span data-stu-id="38c8d-114">RateCard API</span></span>](https://github.com/Azure-Samples/billing-dotnet-ratecard-api)
* [<span data-ttu-id="38c8d-115">マルチテナント Web アプリケーション</span><span class="sxs-lookup"><span data-stu-id="38c8d-115">Multi-Tenant Web Application</span></span>](https://github.com/Azure-Samples/billing-dotnet-webapp-multitenant)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
