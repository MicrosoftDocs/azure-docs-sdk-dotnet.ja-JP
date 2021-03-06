---
title: .NET 用 Azure Stream Analytics ライブラリ
description: .NET 用 Azure Stream Analytics ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: stream-analytics
ms.openlocfilehash: c04a5c8a7b1d7e0f283d4fb81bd772de24f195eb
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190455"
---
# <a name="azure-stream-analytics-libraries-for-net"></a>.NET 用 Azure Stream Analytics ライブラリ

## <a name="overview"></a>概要

[Azure Stream Analytics](/azure/stream-analytics/stream-analytics-introduction) は、フル マネージドのイベント処理エンジンであり、ストリーミング データを対象としたリアルタイム分析の計算を設定することができます。 対象となるデータは、デバイス、センサー、Web サイト、ソーシャル メディア フィード、アプリケーション、インフラストラクチャ システムなどから得ることができます。 

Azure Stream Analytics の詳細については、[Azure Stream Analytics のリアルタイムの不正行為検出の使用](/azure/stream-analytics/stream-analytics-real-time-fraud-detection)に関する記事をご覧ください。


## <a name="management-library"></a>管理ライブラリ

Azure Stream Analytics ジョブを作成、開始、停止するには、Azure Stream Analytics 管理ライブラリを使用します。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.StreamAnalytics)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

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
