---
title: "Azure での .NET によるメッセージングと IoT に関するチュートリアル | Microsoft Docs"
description: ".NET と Azure サービスを使って、クラウド アプリケーション間およびデバイスとクラウドの間でメッセージを送信します。"
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: d733a7e76585e95b7618ad3defd4712a31192c2d
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/23/2017
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


