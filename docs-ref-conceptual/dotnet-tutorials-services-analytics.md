---
title: "Azure でのデータ分析に関する .NET チュートリアル | Microsoft Docs"
description: "Microsoft Azure サービスでデータ分析アプリケーションを開発します。"
author: camsoper
manager: douge
ms.devlang: dotnet
ms.topic: article
ms.service: Azure
ms.technology: Azure
ms.date: 06/09/2017
ms.author: casoper
ms.openlocfilehash: a7ade4d66fb92b8c8d687bba7c092f888d745ff3
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="data-analytics-tutorials-with-net-on-azure"></a>Azure での .NET を使用したデータ分析のチュートリアル

次の表では、Azure で .NET を使ってデータ分析ソリューションを開発する方法についての詳細なチュートリアルへのリンクを示します。 

サンプルのソース コードについては、「[Azure のコード サンプル](https://azure.microsoft.com/resources/samples/?platform=dotnet)」の一覧をご覧ください。

| | |
|---|---|
| **HDInsight** | |
| [Apache Storm トポロジを作成する][1] | サンプル アプリを実装するトポロジを定義した後、プロジェクトをビルドして実行します。 | 
| [HDInsight で Storm を使用して Azure Event Hubs のイベントを処理する (＃C)][2] | HDInsight 上の Apache Storm で Event Hub スパウトを使って、Web サイト、アプリ、デバイスからのデータを処理します。
| [MapReduce アプリを開発し、HDInsight Hadoop クラスターで実行する][3] | 単語数をカウントする簡単な MapReduce アプリケーションを作成し、Linux で動作している HDInsight Hadoop クラスターにデプロイします。 |
| **Data Lake Analytics** | |
| [Data Lake Analytics の使用][4] | Azure .NET SDK を使って、U-SQL で記述されたジョブを Data Lake Analytics に送信する方法について説明します。|


[1]: /azure/hdinsight/hdinsight-storm-develop-csharp-event-hub-topology
[2]: /azure/hdinsight/hdinsight-storm-develop-csharp-visual-studio-topology
[3]: /azure/hdinsight/hdinsight-hadoop-dotnet-csharp-mapreduce-streaming
[4]: /azure/data-lake-analytics/data-lake-analytics-get-started-net-sdk