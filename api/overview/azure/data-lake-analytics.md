---
title: ".NET 用 Azure Data Lake Analytics ライブラリ"
description: ".NET 用 Azure Data Lake Analytics ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Data Lake Analytics
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: data-lake-analytics
ms.custom: devcenter, svc-overview
ms.openlocfilehash: aa99608ec5568450a90cc2b93c3f1c5d0e38bfb1
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/26/2017
---
# <a name="azure-data-lake-analytics-libraries-for-net"></a><span data-ttu-id="89023-104">.NET 用 Azure Data Lake Analytics ライブラリ</span><span class="sxs-lookup"><span data-stu-id="89023-104">Azure Data Lake Analytics libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="89023-105">概要</span><span class="sxs-lookup"><span data-stu-id="89023-105">Overview</span></span>

<span data-ttu-id="89023-106">Azure Data Lake Analytics は、ビッグ データ分析を簡略化するオンデマンド分析ジョブ サービスです。</span><span class="sxs-lookup"><span data-stu-id="89023-106">Azure Data Lake Analytics is an on-demand analytics job service to simplify big data analytics.</span></span>

<span data-ttu-id="89023-107">詳細については、「[Microsoft Azure Data Lake Analytics の概要](/azure/data-lake-analytics/data-lake-analytics-overview)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="89023-107">To learn more, see [Overview of Microsoft Azure Data Lake Analytics](/azure/data-lake-analytics/data-lake-analytics-overview).</span></span>

## <a name="management-library"></a><span data-ttu-id="89023-108">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="89023-108">Management library</span></span>

<span data-ttu-id="89023-109">サービスに接続し、分析ジョブを管理するには、管理ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="89023-109">Use the management library to connect to the service and manage analytics jobs.</span></span>

<span data-ttu-id="89023-110">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Analytics)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="89023-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Analytics) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="89023-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="89023-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.DataLake.Analytics
```

```bash
dotnet add package Microsoft.Azure.Management.DataLake.Analytics
```

### <a name="code-example"></a><span data-ttu-id="89023-112">コード例</span><span class="sxs-lookup"><span data-stu-id="89023-112">Code Example</span></span>

<span data-ttu-id="89023-113">この例では、Analytics アカウントに接続し、アカウントを管理するクライアントを作成します。</span><span class="sxs-lookup"><span data-stu-id="89023-113">This example creates the clients to connect with and manage the analytics account.</span></span>

```csharp
/*
using AdlClient 
*/

// Setup authentication for this demo
Authentication auth = new Authentication("microsoft.onmicrosoft.com"); // change this to YOUR tenant
auth.Authenticate();

// Identify the accounts
AnalyticsAccountRef adla_account = new AnalyticsAccountRef(subscriptionId, resourceGroup, userName);

// Create the clients
AzureClient az = new AzureClient(auth);
AnalyticsClient adla = new AnalyticsClient(auth, adla_account);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="89023-114">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="89023-114">Explore the management APIs</span></span>](/dotnet/api/overview/azure/datalakeanalytics/management)

## <a name="samples"></a><span data-ttu-id="89023-115">サンプル</span><span class="sxs-lookup"><span data-stu-id="89023-115">Samples</span></span>
* [<span data-ttu-id="89023-116">Azure Data Lake .NET クライアントのサンプル</span><span class="sxs-lookup"><span data-stu-id="89023-116">Azure Data Lake .NET Client Example</span></span>](https://azure.microsoft.com/en-us/resources/samples/data-lake-dotnet-client/)

<span data-ttu-id="89023-117">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="89023-117">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
