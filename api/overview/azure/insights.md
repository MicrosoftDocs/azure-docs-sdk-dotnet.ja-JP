---
title: ".NET 用 Azure Application Insights ライブラリ"
description: ".NET 用 Azure Application Insights ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Application AppInsights
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: application-insights
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 081143eafaeea2954703c337609a67fd5a7941c6
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/23/2017
---
# <a name="azure-application-insights-libraries-for-net"></a><span data-ttu-id="8f729-104">.NET 用 Azure Application Insights ライブラリ</span><span class="sxs-lookup"><span data-stu-id="8f729-104">Azure Application Insights libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="8f729-105">概要</span><span class="sxs-lookup"><span data-stu-id="8f729-105">Overview</span></span>

<span data-ttu-id="8f729-106">Application Insights は、強力なアドホック分析機能を備えた、Web 開発者のための拡張可能な監視および診断サービスです。</span><span class="sxs-lookup"><span data-stu-id="8f729-106">Application Insights is an extensible monitoring & diagnostics service for web developers with powerful ad-hoc analytics capabilities.</span></span> <span data-ttu-id="8f729-107">ApplicationInsights 名前空間のクラスを使って、テレメトリのコレクションを構成したり、監視対象のアプリケーションからカスタム テレメトリを送信したりできます。</span><span class="sxs-lookup"><span data-stu-id="8f729-107">You can use the classes in the ApplicationInsights namespace to configure telemetry collection and send any custom telemetry from your applications that you want to monitor.</span></span>

## <a name="client-library"></a><span data-ttu-id="8f729-108">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="8f729-108">Client library</span></span>

<span data-ttu-id="8f729-109">.NET 用の Application Insights クライアント SDK を使うと、イベント、集計データ、例外、依存関係、メトリックを、後で分析できるように Azure に記録できます。</span><span class="sxs-lookup"><span data-stu-id="8f729-109">The Application Insights client SDK for .NET allows you to log event, aggregated data, exceptions, dependency, and metrics to Azure for future analysis.</span></span>

<span data-ttu-id="8f729-110">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.ApplicationInsights )を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="8f729-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.ApplicationInsights ) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="8f729-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="8f729-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.ApplicationInsights 
```

```bash
dotnet add package Microsoft.ApplicationInsights 
```

### <a name="example"></a><span data-ttu-id="8f729-112">例</span><span class="sxs-lookup"><span data-stu-id="8f729-112">Example</span></span>

<span data-ttu-id="8f729-113">この例では、Application Insights へのカスタム イベントを追跡します。</span><span class="sxs-lookup"><span data-stu-id="8f729-113">This example tracks a custom event to Application Insights.</span></span>

```csharp
TelemetryClient client = new TelemetryClient();
client.TrackEvent("MyCustomEvent");
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="8f729-114">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="8f729-114">Explore the client APIs</span></span>](/dotnet/api/overview/azure/insights/client)



## <a name="samples"></a><span data-ttu-id="8f729-115">サンプル</span><span class="sxs-lookup"><span data-stu-id="8f729-115">Samples</span></span>

- [<span data-ttu-id="8f729-116">OpenSchema での Application Insights の分析</span><span class="sxs-lookup"><span data-stu-id="8f729-116">Application Insights Analytics with OpenSchema</span></span>](https://azure.microsoft.com/resources/samples/guidance-appinsights-openschema/)

<span data-ttu-id="8f729-117">Azure Application Insights のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?service=application-insights&platform=dotnet)を表示します。</span><span class="sxs-lookup"><span data-stu-id="8f729-117">View the [complete list](https://azure.microsoft.com/resources/samples/?service=application-insights&platform=dotnet) of Azure Application Insights samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
