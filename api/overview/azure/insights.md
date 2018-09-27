---
title: .NET 用 Azure Application Insights ライブラリ
description: .NET 用 Azure Application Insights ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: application-insights
ms.openlocfilehash: 10b65f536c6461959b0be9b8f9bd3ec56a307bea
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190841"
---
# <a name="azure-application-insights-libraries-for-net"></a><span data-ttu-id="0fb40-103">.NET 用 Azure Application Insights ライブラリ</span><span class="sxs-lookup"><span data-stu-id="0fb40-103">Azure Application Insights libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="0fb40-104">概要</span><span class="sxs-lookup"><span data-stu-id="0fb40-104">Overview</span></span>

<span data-ttu-id="0fb40-105">Application Insights は、強力なアドホック分析機能を備えた、Web 開発者のための拡張可能な監視および診断サービスです。</span><span class="sxs-lookup"><span data-stu-id="0fb40-105">Application Insights is an extensible monitoring & diagnostics service for web developers with powerful ad-hoc analytics capabilities.</span></span> <span data-ttu-id="0fb40-106">ApplicationInsights 名前空間のクラスを使って、テレメトリのコレクションを構成したり、監視対象のアプリケーションからカスタム テレメトリを送信したりできます。</span><span class="sxs-lookup"><span data-stu-id="0fb40-106">You can use the classes in the ApplicationInsights namespace to configure telemetry collection and send any custom telemetry from your applications that you want to monitor.</span></span>

## <a name="client-library"></a><span data-ttu-id="0fb40-107">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="0fb40-107">Client library</span></span>

<span data-ttu-id="0fb40-108">.NET 用の Application Insights クライアント SDK を使うと、イベント、集計データ、例外、依存関係、メトリックを、後で分析できるように Azure に記録できます。</span><span class="sxs-lookup"><span data-stu-id="0fb40-108">The Application Insights client SDK for .NET allows you to log event, aggregated data, exceptions, dependency, and metrics to Azure for future analysis.</span></span>

<span data-ttu-id="0fb40-109">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.ApplicationInsights )を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="0fb40-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.ApplicationInsights ) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="0fb40-110">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="0fb40-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.ApplicationInsights 
```

```bash
dotnet add package Microsoft.ApplicationInsights 
```

### <a name="example"></a><span data-ttu-id="0fb40-111">例</span><span class="sxs-lookup"><span data-stu-id="0fb40-111">Example</span></span>

<span data-ttu-id="0fb40-112">この例では、Application Insights へのカスタム イベントを追跡します。</span><span class="sxs-lookup"><span data-stu-id="0fb40-112">This example tracks a custom event to Application Insights.</span></span>

```csharp
TelemetryClient client = new TelemetryClient();
client.TrackEvent("MyCustomEvent");
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="0fb40-113">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="0fb40-113">Explore the client APIs</span></span>](/dotnet/api/overview/azure/insights/client)



## <a name="samples"></a><span data-ttu-id="0fb40-114">サンプル</span><span class="sxs-lookup"><span data-stu-id="0fb40-114">Samples</span></span>

- [<span data-ttu-id="0fb40-115">OpenSchema での Application Insights の分析</span><span class="sxs-lookup"><span data-stu-id="0fb40-115">Application Insights Analytics with OpenSchema</span></span>](https://azure.microsoft.com/resources/samples/guidance-appinsights-openschema/)

<span data-ttu-id="0fb40-116">Azure Application Insights のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?service=application-insights&platform=dotnet)を表示します。</span><span class="sxs-lookup"><span data-stu-id="0fb40-116">View the [complete list](https://azure.microsoft.com/resources/samples/?service=application-insights&platform=dotnet) of Azure Application Insights samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
