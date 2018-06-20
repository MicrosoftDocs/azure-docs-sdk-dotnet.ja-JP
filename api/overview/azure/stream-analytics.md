---
title: .NET 用 Azure Stream Analytics ライブラリ
description: .NET 用 Azure Stream Analytics ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Stream Analytics
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: stream-analytics
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 2a5e8b8481548d6cfebc5104eb459f8772f51462
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/23/2017
ms.locfileid: "23487135"
---
# <a name="azure-stream-analytics-libraries-for-net"></a><span data-ttu-id="25cab-104">.NET 用 Azure Stream Analytics ライブラリ</span><span class="sxs-lookup"><span data-stu-id="25cab-104">Azure Stream Analytics libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="25cab-105">概要</span><span class="sxs-lookup"><span data-stu-id="25cab-105">Overview</span></span>

<span data-ttu-id="25cab-106">[Azure Stream Analytics](/azure/stream-analytics/stream-analytics-introduction) は、完全に管理されたイベント処理エンジンであり、ストリーミング データを対象としたリアルタイム分析の計算を設定することができます。</span><span class="sxs-lookup"><span data-stu-id="25cab-106">[Azure Stream Analytics](/azure/stream-analytics/stream-analytics-introduction) is a fully managed event-processing engine that lets you set up real-time analytic computations on streaming data.</span></span> <span data-ttu-id="25cab-107">対象となるデータは、デバイス、センサー、Web サイト、ソーシャル メディア フィード、アプリケーション、インフラストラクチャ システムなどから得ることができます。</span><span class="sxs-lookup"><span data-stu-id="25cab-107">The data can come from devices, sensors, web sites, social media feeds, applications, infrastructure systems, and more.</span></span> 

<span data-ttu-id="25cab-108">Azure Stream Analytics の詳細については、[Azure Stream Analytics のリアルタイムの不正行為検出の使用](/azure/stream-analytics/stream-analytics-real-time-fraud-detection)に関する記事をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="25cab-108">To learn more about Azure Stream Analytics, see [Get started with Azure Stream Analytics Real-time fraud detection](/azure/stream-analytics/stream-analytics-real-time-fraud-detection).</span></span>


## <a name="management-library"></a><span data-ttu-id="25cab-109">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="25cab-109">Management library</span></span>

<span data-ttu-id="25cab-110">Azure Stream Analytics ジョブを作成、開始、停止するには、Azure Stream Analytics 管理ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="25cab-110">Use the Azure Stream Analytics management library to create, start, and stop Azure Stream Analytics jobs.</span></span>

<span data-ttu-id="25cab-111">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.StreamAnalytics)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="25cab-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.StreamAnalytics) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="25cab-112">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="25cab-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.StreamAnalytics
```

```bash
dotnet add package Microsoft.Azure.Management.StreamAnalytics
```

### <a name="code-example"></a><span data-ttu-id="25cab-113">コード例</span><span class="sxs-lookup"><span data-stu-id="25cab-113">Code Example</span></span>

<span data-ttu-id="25cab-114">この例では、Stream Analytics クライアントをインスタンス化し、ストリーミング ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="25cab-114">This example instantiates a Stream Analytics client and creates a streaming job.</span></span>

```csharp
/* Include these 'using' directives:
using Microsoft.Azure.Management.StreamAnalytics;
*/
SynchronizationContext.SetSynchronizationContext(new SynchronizationContext());

// Get credentials
ServiceClientCredentials credentials = GetCredentials().Result;

// Create Stream Analytics management client
StreamAnalyticsManagementClient streamAnalyticsManagementClient = new StreamAnalyticsManagementClient(credentials)
{
    SubscriptionId = subscriptionId
};

// Create a streaming job
StreamingJob streamingJob = new StreamingJob()
{
    Tags = new Dictionary<string, string>()
    {
        { "Origin", ".NET SDK" },
        { "ReasonCreated", "Getting started tutorial" }
    },
    Location = "West US",
    EventsOutOfOrderPolicy = EventsOutOfOrderPolicy.Drop,
    EventsOutOfOrderMaxDelayInSeconds = 5,
    EventsLateArrivalMaxDelayInSeconds = 16,
    OutputErrorPolicy = OutputErrorPolicy.Drop,
    DataLocale = "en-US",
    CompatibilityLevel = CompatibilityLevel.OneFullStopZero,
    Sku = new Sku()
    {
        Name = SkuName.Standard
    }
};
StreamingJob createStreamingJobResult = streamAnalyticsManagementClient.StreamingJobs.CreateOrReplace(streamingJob, resourceGroupName, streamingJobName);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="25cab-115">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="25cab-115">Explore the management APIs</span></span>](/dotnet/api/overview/azure/streamanalytics/management)


## <a name="samples"></a><span data-ttu-id="25cab-116">サンプル</span><span class="sxs-lookup"><span data-stu-id="25cab-116">Samples</span></span>

- [<span data-ttu-id="25cab-117">管理用 .NET SDK: .NET 用 Azure Stream Analytics API を使用した分析ジョブの設定と実行</span><span class="sxs-lookup"><span data-stu-id="25cab-117">Management .NET SDK: Set up and run analytics jobs using the Azure Stream Analytics API for .NET</span></span>](/azure/stream-analytics/stream-analytics-dotnet-management-sdk)

<span data-ttu-id="25cab-118">Azure Stream Analytics のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=stream-analytics)を表示します。</span><span class="sxs-lookup"><span data-stu-id="25cab-118">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=stream-analytics) of Azure Stream Analytics samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
