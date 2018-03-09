---
title: "Azure でのデータ分析に関する .NET チュートリアル | Microsoft Docs"
description: "Microsoft Azure サービスでデータ分析アプリケーションを開発します。"
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: d843e605bf64fb475efe8fc1bba6a112ddca4d96
ms.sourcegitcommit: 3ba0ff4463338a0ab0f3f15a7601b89417c06970
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/05/2018
---
# <a name="data-analytics-tutorials-with-net-on-azure"></a><span data-ttu-id="d1a47-103">Azure での .NET を使用したデータ分析のチュートリアル</span><span class="sxs-lookup"><span data-stu-id="d1a47-103">Data analytics tutorials with .NET on Azure</span></span>

<span data-ttu-id="d1a47-104">次の表では、Azure で .NET を使ってデータ分析ソリューションを開発する方法についての詳細なチュートリアルへのリンクを示します。</span><span class="sxs-lookup"><span data-stu-id="d1a47-104">The following table links to in-depth tutorials for developing data analytics solutions using .NET on Azure.</span></span> 

<span data-ttu-id="d1a47-105">サンプルのソース コードについては、「[Azure のコード サンプル](https://azure.microsoft.com/resources/samples/?platform=dotnet)」の一覧をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="d1a47-105">For sample source code, see the list of [Azure service samples](https://azure.microsoft.com/resources/samples/?platform=dotnet).</span></span>

| | |
|---|---|
| <span data-ttu-id="d1a47-106">**HDInsight**</span><span class="sxs-lookup"><span data-stu-id="d1a47-106">**HDInsight**</span></span> | |
| <span data-ttu-id="d1a47-107">[Apache Storm トポロジを作成する][1]</span><span class="sxs-lookup"><span data-stu-id="d1a47-107">[Create an Apache Storm topology][1]</span></span> | <span data-ttu-id="d1a47-108">サンプル アプリを実装するトポロジを定義した後、プロジェクトをビルドして実行します。</span><span class="sxs-lookup"><span data-stu-id="d1a47-108">Define a topology that implements a sample app, then build and run the project.</span></span> | 
| <span data-ttu-id="d1a47-109">[HDInsight で Storm を使用して Azure Event Hubs のイベントを処理する (＃C)][2]</span><span class="sxs-lookup"><span data-stu-id="d1a47-109">[Process events from Azure Event Hubs with Storm on HDInsight][2]</span></span> | <span data-ttu-id="d1a47-110">HDInsight 上の Apache Storm で Event Hub スパウトを使って、Web サイト、アプリ、デバイスからのデータを処理します。</span><span class="sxs-lookup"><span data-stu-id="d1a47-110">Process data from websites, apps, and devices using the Event Hub spout with Apache Storm on HDInsight.</span></span>
| <span data-ttu-id="d1a47-111">[MapReduce アプリを開発し、HDInsight Hadoop クラスターで実行する][3]</span><span class="sxs-lookup"><span data-stu-id="d1a47-111">[Develop a MapReduce app and run it on a HDInsight Hadoop cluster][3]</span></span> | <span data-ttu-id="d1a47-112">単語数をカウントする簡単な MapReduce アプリケーションを作成し、Linux で動作している HDInsight Hadoop クラスターにデプロイします。</span><span class="sxs-lookup"><span data-stu-id="d1a47-112">Create a simple MapReduce application to count words and deploy it in a HDInsight Hadoop cluster running on Linux.</span></span> |
| <span data-ttu-id="d1a47-113">**Data Lake Analytics**</span><span class="sxs-lookup"><span data-stu-id="d1a47-113">**Data Lake Analytics**</span></span> | |
| <span data-ttu-id="d1a47-114">[Data Lake Analytics の使用][4]</span><span class="sxs-lookup"><span data-stu-id="d1a47-114">[Get started with Data Lake Analytics][4]</span></span> | <span data-ttu-id="d1a47-115">Azure .NET SDK を使って、U-SQL で記述されたジョブを Data Lake Analytics に送信する方法について説明します。</span><span class="sxs-lookup"><span data-stu-id="d1a47-115">Learn how to use the Azure .NET SDK to submit jobs written in U-SQL to Data Lake Analytics.</span></span>|


[1]: /azure/hdinsight/hdinsight-storm-develop-csharp-event-hub-topology
[2]: /azure/hdinsight/hdinsight-storm-develop-csharp-visual-studio-topology
[3]: /azure/hdinsight/hdinsight-hadoop-dotnet-csharp-mapreduce-streaming
[4]: /azure/data-lake-analytics/data-lake-analytics-get-started-net-sdk