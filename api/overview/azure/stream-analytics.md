---
title: ".NET 用 Azure Stream Analytics ライブラリ"
description: ".NET 用 Azure Stream Analytics ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Stream Analytics
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: b812f0948b2153d717987fbc6912ed4665154b3f
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-stream-analytics-libraries-for-net"></a>.NET 用 Azure Stream Analytics ライブラリ

## <a name="overview"></a>概要

[Azure Stream Analytics](/azure/stream-analytics/stream-analytics-introduction) は、完全に管理されたイベント処理エンジンであり、ストリーミング データを対象としたリアルタイム分析の計算を設定することができます。 対象となるデータは、デバイス、センサー、Web サイト、ソーシャル メディア フィード、アプリケーション、インフラストラクチャ システムなどから得ることができます。 

Azure Stream Analytics の詳細については、[Azure Stream Analytics のリアルタイムの不正行為検出の使用](/azure/stream-analytics/stream-analytics-real-time-fraud-detection)に関する記事をご覧ください。


## <a name="management-library"></a>管理ライブラリ

Azure Stream Analytics ジョブを作成、開始、停止するには、Azure Stream Analytics 管理ライブラリを使用します。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.StreamAnalytics)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.StreamAnalytics
```

```bash
dotnet add package Microsoft.Azure.Management.StreamAnalytics
```

### <a name="code-example"></a>コード例

この例では、Stream Analytics クライアントをインスタンス化し、ストリーミング ジョブを作成します。

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
> [Management API を探す](/dotnet/api/overview/azure/streamanalytics/management)


## <a name="samples"></a>サンプル

- [管理用 .NET SDK: .NET 用 Azure Stream Analytics API を使用した分析ジョブの設定と実行](/azure/stream-analytics/stream-analytics-dotnet-management-sdk)

Azure Stream Analytics のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=stream-analytics)を表示します。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
