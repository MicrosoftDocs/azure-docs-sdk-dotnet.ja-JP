---
title: "Azure での .NET アプリの管理と監視に関するチュートリアル"
description: "Azure で実行する .NET アプリケーションの正常性とパフォーマンスを監視し、利用統計情報をインストルメント化してユーザーがアプリを使う方法に関する情報を保存します。"
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: 46912f3c31a56724de90e90c36370209ed5c7bd8
ms.sourcegitcommit: 3ba0ff4463338a0ab0f3f15a7601b89417c06970
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/05/2018
---
# <a name="tutorials-for-monitoring-and-managing-your-net-apps-in-azure"></a><span data-ttu-id="93bf4-103">Azure での .NET アプリの監視と管理に関するチュートリアル</span><span class="sxs-lookup"><span data-stu-id="93bf4-103">Tutorials for monitoring and managing your .NET apps in Azure</span></span>

<span data-ttu-id="93bf4-104">次の表では、Azure で実行する .NET アプリケーションの管理と監視に関する詳細なチュートリアルへのリンクを示します。</span><span class="sxs-lookup"><span data-stu-id="93bf4-104">The following table links to in-depth tutorials for managing and monitoring your .NET applications running on Azure.</span></span> 

<span data-ttu-id="93bf4-105">サンプルのソース コードについては、「[Azure のコード サンプル](https://azure.microsoft.com/resources/samples/?platform=dotnet)」の一覧をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="93bf4-105">For sample source code, see the list of [Azure service samples](https://azure.microsoft.com/resources/samples/?platform=dotnet).</span></span>

| | |
|---|---|
| <span data-ttu-id="93bf4-106">**Application Insights**</span><span class="sxs-lookup"><span data-stu-id="93bf4-106">**Application Insights**</span></span> ||
| <span data-ttu-id="93bf4-107">[ASP.NET Web サイトに Application Insights を設定する][1]</span><span class="sxs-lookup"><span data-stu-id="93bf4-107">[Set up Application Insights for your ASP.NET website][1]</span></span> | <span data-ttu-id="93bf4-108">Azure Application Insights サービスに利用統計情報を送信するように ASP.NET Web アプリを構成します。</span><span class="sxs-lookup"><span data-stu-id="93bf4-108">Configure your ASP.NET web app to send telemetry to the Azure Application Insights service.</span></span> | 
| <span data-ttu-id="93bf4-109">[Application Insights を使用した実行時の Web アプリのインストルメント化][2]</span><span class="sxs-lookup"><span data-stu-id="93bf4-109">[Instrument web apps at runtime with Application Insights][2]</span></span> | <span data-ttu-id="93bf4-110">コードを変更したり再デプロイしたりすることなく、ライブ Web アプリをインストルメント化します。</span><span class="sxs-lookup"><span data-stu-id="93bf4-110">Instrument a live web app without having to modify or redeploy your code..</span></span> | 
| <span data-ttu-id="93bf4-111">[Application Insights を .NET アプリケーション用に手動で構成する][3]</span><span class="sxs-lookup"><span data-stu-id="93bf4-111">[Manually configure Application Insights for .NET applications][3]</span></span> | <span data-ttu-id="93bf4-112">さまざまなアプリケーションやアプリケーション ロール、コンポーネント、またはマイクロサービスを監視するように、Application Insights を構成します。</span><span class="sxs-lookup"><span data-stu-id="93bf4-112">Configure Application Insights to monitor a wide variety of applications or application roles, components, or microservices.</span></span> | 
| <span data-ttu-id="93bf4-113">[Windows デスクトップ アプリでの使用状況とパフォーマンスの監視][4]</span><span class="sxs-lookup"><span data-stu-id="93bf4-113">[Monitoring usage and performance in Windows Desktop apps][4]</span></span> | <span data-ttu-id="93bf4-114">Application Insights と HockeyApp を使って、デプロイされたアプリケーションの使用状況とパフォーマンスを監視します。</span><span class="sxs-lookup"><span data-stu-id="93bf4-114">Use Application Insights and HockeyApp to monitor your deployed application for usage and performance.</span></span> | 
| <span data-ttu-id="93bf4-115">[Application Insights for ASP.NET Core][5]</span><span class="sxs-lookup"><span data-stu-id="93bf4-115">[Application Insights for ASP.NET Core][5]</span></span> | <span data-ttu-id="93bf4-116">ASP.NET Core アプリケーションの可用性、パフォーマンス、使用状況を監視します。</span><span class="sxs-lookup"><span data-stu-id="93bf4-116">Monitor your ASP.NET Core application for availability, performance and usage.</span></span> | 
| <span data-ttu-id="93bf4-117">[カスタムのイベントとメトリックのための Application Insights API][6]</span><span class="sxs-lookup"><span data-stu-id="93bf4-117">[Application Insights API for custom events and metrics][6]</span></span> | <span data-ttu-id="93bf4-118">アプリケーションに数行のコードを挿入して、ユーザーの行動を調べたり、問題の診断に役立つ情報を取得したりします。</span><span class="sxs-lookup"><span data-stu-id="93bf4-118">Insert a few lines of code in your application to find out what users are doing with it or help diagnose issues.</span></span> | 


[1]: /azure/application-insights/app-insights-asp-net
[2]: /azure/application-insights/app-insights-monitor-performance-live-website-now
[3]: /azure/application-insights/app-insights-windows-services
[4]: /azure/application-insights/app-insights-windows-desktop
[5]: /azure/application-insights/app-insights-asp-net-core
[6]: /azure/application-insights/app-insights-api-custom-events-metrics
