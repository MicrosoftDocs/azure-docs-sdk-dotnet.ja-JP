---
title: "Azure での .NET によるメッセージングと IoT に関するチュートリアル | Microsoft Docs"
description: ".NET と Azure サービスを使って、クラウド アプリケーション間およびデバイスとクラウドの間でメッセージを送信します。"
author: camsoper
manager: douge
ms.assetid: 2ce6ea06-7b0b-45e6-8ca0-44e4e4030b82
ms.devlang: dotnet
ms.topic: article
ms.service: Azure
ms.technology: Azure
ms.date: 4/10/2017
ms.author: casoper
ms.openlocfilehash: 0c3e81231ac88b2418778b83ecabcbb553608e24
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="net-tutorials-for-enterprise-messaging-and-internet-of-things-iot"></a>エンタープライズ メッセージングおよびモノのインターネット (IoT) に関する .NET チュートリアル

次の表では、Azure サービスを使って .NET コードからアプリケーションとデバイスの間のメッセージを送信したり読み取ったりする方法についての詳細なチュートリアルへのリンクを示します。

サンプルのソース コードについては、「[Azure のコード サンプル](https://azure.microsoft.com/resources/samples/?platform=dotnet)」の一覧をご覧ください。


| | |
|---|---|
| **Service Bus** | |
| [Service Bus キューの使用方法][1] | キューを作成、メッセージを送受信して、キューを削除します。 | 
| [Service Bus のトピックとサブスクリプションの使用方法][2] | Service Bus でパブリッシュ/サブスクライブ通信モデルを使う方法を説明します。
| [AMQP 1.0 で .NET から Service Bus を使用する][3] | Service Bus アプリケーションで AMQP を使う方法を説明します。
|**IoT Hub**|
| [シミュレーション対象デバイスを IoT Hub に接続する][4] | デバイス ID を作成し、メッセージを送信して、IoT Hub からのテレメトリ情報を処理します。 |   
| [デバイスからクラウドへのメッセージの処理][5] | シミュレーション対象デバイスからメッセージを送信し、クラウドでそれを処理します。 |
|**イベント ハブ**|
| [Event Hub にイベントを送信する][6] | コンソール アプリケーションから Event Hub にイベントを送信します。
| [Event Hubs からイベントを受信する][7] | 並列にメッセージを受信して処理します。


[1]: /azure/service-bus-messaging/service-bus-dotnet-get-started-with-queues
[2]: /azure/service-bus-messaging/service-bus-dotnet-how-to-use-topics-subscriptions
[3]: /azure/service-bus-messaging/service-bus-amqp-dotnet
[4]: /azure/iot-hub/iot-hub-csharp-csharp-getstarted
[5]: /azure/iot-hub/iot-hub-csharp-csharp-process-d2c
[6]: /azure/event-hubs/event-hubs-dotnet-standard-getstarted-send
[7]: /azure/event-hubs/event-hubs-dotnet-standard-getstarted-receive-eph


