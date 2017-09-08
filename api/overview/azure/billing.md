---
title: ".NET 用 Azure Billing ライブラリ"
description: ".NET 用 Azure Billing ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Billing
author: spboyer
ms.author: casoper
manager: douge
ms.date: 07/07/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 0a401bf9ccc345d3c6e99a010c74f9c7f6f5914e
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-billing-libraries-for-net"></a><span data-ttu-id="5474d-104">.NET 用 Azure Billing ライブラリ</span><span class="sxs-lookup"><span data-stu-id="5474d-104">Azure Billing libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="5474d-105">概要</span><span class="sxs-lookup"><span data-stu-id="5474d-105">Overview</span></span>

<span data-ttu-id="5474d-106">Azure Billing API (プレビュー) は、Azure の課金情報と請求書へのプログラムによるアクセスを提供します。</span><span class="sxs-lookup"><span data-stu-id="5474d-106">Azure Billing API (preview) provides programmatic access to your Azure billing information and invoices.</span></span>

## <a name="management-library"></a><span data-ttu-id="5474d-107">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="5474d-107">Management library</span></span>

<span data-ttu-id="5474d-108">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Billing)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="5474d-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Billing) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="5474d-109">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="5474d-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Billing
```

```bash
dotnet add package Microsoft.Azure.Management.Billing
```

### <a name="code-example"></a><span data-ttu-id="5474d-110">コード例</span><span class="sxs-lookup"><span data-stu-id="5474d-110">Code Example</span></span>

<span data-ttu-id="5474d-111">Azure に接続し、請求書の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5474d-111">Connect to Azure and get a list of invoices.</span></span>

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
> [<span data-ttu-id="5474d-112">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="5474d-112">Explore the management APIs</span></span>](/dotnet/api/overview/azure/billing/management)

## <a name="samples"></a><span data-ttu-id="5474d-113">サンプル</span><span class="sxs-lookup"><span data-stu-id="5474d-113">Samples</span></span>

* [<span data-ttu-id="5474d-114">Usage API</span><span class="sxs-lookup"><span data-stu-id="5474d-114">Usage API</span></span>](https://github.com/Azure-Samples/billing-dotnet-usage-api)
* [<span data-ttu-id="5474d-115">RateCard API</span><span class="sxs-lookup"><span data-stu-id="5474d-115">RateCard API</span></span>](https://github.com/Azure-Samples/billing-dotnet-ratecard-api)
* [<span data-ttu-id="5474d-116">マルチテナント Web アプリケーション</span><span class="sxs-lookup"><span data-stu-id="5474d-116">Multi-Tenant Web Application</span></span>](https://github.com/Azure-Samples/billing-dotnet-webapp-multitenant)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
