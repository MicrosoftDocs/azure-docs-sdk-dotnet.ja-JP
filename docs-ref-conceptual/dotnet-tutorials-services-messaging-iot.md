---
title: "Azure での .NET によるメッセージングと IoT に関するチュートリアル | Microsoft Docs"
description: ".NET と Azure サービスを使って、クラウド アプリケーション間およびデバイスとクラウドの間でメッセージを送信します。"
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: a6c50af1678c785c6a3fcd3f4f3689171069b2ee
ms.sourcegitcommit: 3ba0ff4463338a0ab0f3f15a7601b89417c06970
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/05/2018
---
# <a name="net-tutorials-for-enterprise-messaging-and-internet-of-things-iot"></a><span data-ttu-id="7dbd6-103">エンタープライズ メッセージングおよびモノのインターネット (IoT) に関する .NET チュートリアル</span><span class="sxs-lookup"><span data-stu-id="7dbd6-103">.NET tutorials for enterprise messaging and Internet of Things (IoT)</span></span>

<span data-ttu-id="7dbd6-104">次の表では、Azure サービスを使って .NET コードからアプリケーションとデバイスの間のメッセージを送信したり読み取ったりする方法についての詳細なチュートリアルへのリンクを示します。</span><span class="sxs-lookup"><span data-stu-id="7dbd6-104">The following table links to in-depth tutorials for sending and reading messages between applications and devices in from your .NET code using Azure services.</span></span>

<span data-ttu-id="7dbd6-105">サンプルのソース コードについては、「[Azure のコード サンプル](https://azure.microsoft.com/resources/samples/?platform=dotnet)」の一覧をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="7dbd6-105">For sample source code, see the list of [Azure service samples](https://azure.microsoft.com/resources/samples/?platform=dotnet).</span></span>


| | |
|---|---|
| <span data-ttu-id="7dbd6-106">**Service Bus**</span><span class="sxs-lookup"><span data-stu-id="7dbd6-106">**Service Bus**</span></span> | |
| <span data-ttu-id="7dbd6-107">[Service Bus キューの使用方法][1]</span><span class="sxs-lookup"><span data-stu-id="7dbd6-107">[How to use Service Bus queues][1]</span></span> | <span data-ttu-id="7dbd6-108">キューを作成、メッセージを送受信して、キューを削除します。</span><span class="sxs-lookup"><span data-stu-id="7dbd6-108">Create queues, send and receive messages, and delete queues.</span></span> | 
| <span data-ttu-id="7dbd6-109">[Service Bus のトピックとサブスクリプションの使用方法][2]</span><span class="sxs-lookup"><span data-stu-id="7dbd6-109">[How to use Service Bus topics and subscriptions][2]</span></span> | <span data-ttu-id="7dbd6-110">Service Bus でパブリッシュ/サブスクライブ通信モデルを使う方法を説明します。</span><span class="sxs-lookup"><span data-stu-id="7dbd6-110">Learn how to use publish/subscribe communication model with Service Bus.</span></span>
| <span data-ttu-id="7dbd6-111">[AMQP 1.0 で .NET から Service Bus を使用する][3]</span><span class="sxs-lookup"><span data-stu-id="7dbd6-111">[Using Service Bus from .NET with AMQP 1.0][3]</span></span> | <span data-ttu-id="7dbd6-112">Service Bus アプリケーションで AMQP を使う方法を説明します。</span><span class="sxs-lookup"><span data-stu-id="7dbd6-112">Learn how to use AMQP in you Service Bus applications.</span></span>
|<span data-ttu-id="7dbd6-113">**IoT Hub**</span><span class="sxs-lookup"><span data-stu-id="7dbd6-113">**IoT Hub**</span></span>|
| <span data-ttu-id="7dbd6-114">[シミュレーション対象デバイスを IoT Hub に接続する][4]</span><span class="sxs-lookup"><span data-stu-id="7dbd6-114">[Connect a simulated device to your IoT Hub][4]</span></span> | <span data-ttu-id="7dbd6-115">デバイス ID を作成し、メッセージを送信して、IoT Hub からのテレメトリ情報を処理します。</span><span class="sxs-lookup"><span data-stu-id="7dbd6-115">Create a device identity, send messages, and process telemetry from your IoT Hub.</span></span> |   
| <span data-ttu-id="7dbd6-116">[デバイスからクラウドへのメッセージの処理][5]</span><span class="sxs-lookup"><span data-stu-id="7dbd6-116">[Process device-to-cloud messages][5]</span></span> | <span data-ttu-id="7dbd6-117">シミュレーション対象デバイスからメッセージを送信し、クラウドでそれを処理します。</span><span class="sxs-lookup"><span data-stu-id="7dbd6-117">Send messages from a simulated device and process them in the cloud.</span></span> |
|<span data-ttu-id="7dbd6-118">**イベント ハブ**</span><span class="sxs-lookup"><span data-stu-id="7dbd6-118">**Event Hub**</span></span>|
| <span data-ttu-id="7dbd6-119">[Event Hub にイベントを送信する][6]</span><span class="sxs-lookup"><span data-stu-id="7dbd6-119">[Send events to an Event Hub][6]</span></span> | <span data-ttu-id="7dbd6-120">コンソール アプリケーションから Event Hub にイベントを送信します。</span><span class="sxs-lookup"><span data-stu-id="7dbd6-120">Send events to Event hub from a console application.</span></span>
| <span data-ttu-id="7dbd6-121">[Event Hubs からイベントを受信する][7]</span><span class="sxs-lookup"><span data-stu-id="7dbd6-121">[Receive events from Event Hubs][7]</span></span> | <span data-ttu-id="7dbd6-122">並列にメッセージを受信して処理します。</span><span class="sxs-lookup"><span data-stu-id="7dbd6-122">Receive messages and process them in parallel.</span></span>


[1]: /azure/service-bus-messaging/service-bus-dotnet-get-started-with-queues
[2]: /azure/service-bus-messaging/service-bus-dotnet-how-to-use-topics-subscriptions
[3]: /azure/service-bus-messaging/service-bus-amqp-dotnet
[4]: /azure/iot-hub/iot-hub-csharp-csharp-getstarted
[5]: /azure/iot-hub/iot-hub-csharp-csharp-process-d2c
[6]: /azure/event-hubs/event-hubs-dotnet-standard-getstarted-send
[7]: /azure/event-hubs/event-hubs-dotnet-standard-getstarted-receive-eph


