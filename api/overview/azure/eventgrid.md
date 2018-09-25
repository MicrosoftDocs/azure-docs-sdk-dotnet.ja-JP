---
title: .NET 用 Azure Event Grid ライブラリ
description: .NET 用 Azure Event Grid ライブラリのリファレンス
author: rloutlaw
ms.author: routlaw
manager: angerobe
ms.date: 04/16/2018
ms.topic: reference
ms.devlang: dotnet
ms.service: event-grid
ms.custom: devcenter
ms.openlocfilehash: 894b8a5beaf0507ab50e8eed6a5ab20d10a71ba6
ms.sourcegitcommit: 61638b504b6c4d96b357894835c80c2680a99fe6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/17/2018
ms.locfileid: "45750600"
---
# <a name="azure-event-grid-libraries-for-net"></a>.NET 用 Azure Event Grid ライブラリ

Azure Event Grid で簡単な HTTP ベースのイベント処理を使用して、Azure サービスやカスタム ソースのイベントをリッスンして対応するイベント ドリブン アプリケーションを構築します。

Azure Event Grid の[詳細を確認](/azure/event-grid/overview)し、[Azure Blob Storage イベントのチュートリアル](/azure/storage/blobs/storage-blob-event-quickstart-powershell)を開始してください。 

## <a name="client-sdk"></a>クライアント SDK

Azure Event Grid クライアント SDK を使用して、イベントの作成、認証、トピックへの投稿を行います。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.EventGrid
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.EventGrid 
```

### <a name="publish-events"></a>イベントの発行

次のコードでは、Azure で認証し、カスタム型の `EventGridEvent` イベント (この例では `Contoso.Items.ItemsReceivedEvent`) の `List` をトピックに発行します。 このサンプルで使用されているトピック キーとエンドポイント アドレスは、Azure PowerShell から取得できます。

```powershell
$endpoint = (Get-AzureRmEventGridTopic -ResourceGroupName gridResourceGroup -Name <topic-name>).Endpoint
$keys = Get-AzureRmEventGridTopicKey -ResourceGroupName gridResourceGroup -Name <topic-name>
```

```csharp
string topicEndpoint = "https://<topic-name>.<region>-1.eventgrid.azure.net/api/events";
string topicKey = "<topic-key>";
string topicHostname = new Uri(topicEndpoint).Host;

TopicCredentials topicCredentials = new TopicCredentials(topicKey);
EventGridClient client = new EventGridClient(topicCredentials);

client.PublishEventsAsync(topicHostname, GetEventsList()).GetAwaiter().GetResult();
Console.Write("Published events to Event Grid.");

static IList<EventGridEvent> GetEventsList()
{
    List<EventGridEvent> eventsList = new List<EventGridEvent>();
    for (int i = 0; i < 1; i++)
    {
        eventsList.Add(new EventGridEvent()
        {
            Id = Guid.NewGuid().ToString(),
            EventType = "Contoso.Items.ItemReceivedEvent",
            Data = new ContosoItemReceivedEventData()
            {
                ItemUri = "ContosoSuperItemUri"
            },

            EventTime = DateTime.Now,
            Subject = "Door1",
            DataVersion = "2.0"
        });
    }
    return eventsList;
}
```

### <a name="consume-events"></a>イベントの使用

このスニペットでは、カスタム イベント `Contoso.Items.ItemsReceived` などのイベントや、Blob Storage など、他の Azure サービスからトリガーされるイベントを使用します。

```csharp
string response = string.Empty;
string requestContent = await req.Content.ReadAsStringAsync();

EventGridSubscriber eventGridSubscriber = new EventGridSubscriber();

// Optionally add one or more custom event type mappings
eventGridSubscriber.AddOrUpdateCustomEventMapping("Contoso.Items.ItemReceived", typeof(ContosoItemReceivedEventData));

var events = eventGridSubscriber.DeserializeEventGridEvents(requestContent);            
 
foreach (EventGridEvent receivedEvent in events)
{
    if (receivedEvent.Data is SubscriptionValidationEventData)
    {
        SubscriptionValidationEventData eventData = (SubscriptionValidationEventData)receivedEvent.Data;
        log.Info($"Got SubscriptionValidation event data, validationCode: {eventData.ValidationCode},  validationUrl: {eventData.ValidationUrl}, topic: {eventGridEvent.Topic}");
        // Handle subscription validation
    }
    else if (receivedEvent.Data is StorageBlobCreatedEventData)
    {
        StorageBlobCreatedEventData eventData = (StorageBlobCreatedEventData)receivedEvent.Data;
        log.Info($"Got BlobCreated event data, blob URI {eventData.Url}");
        // Handle StorageBlobCreatedEventData
    }
    else if (receivedEvent.Data is ContosoItemReceivedEventData)
    {
        ContosoItemReceivedEventData eventData = (ContosoItemReceivedEventData)receivedEvent.Data;
    }
}
```

> [!div class="nextstepaction"]
> [クライアント API を探す](/dotnet/api/overview/azure/eventgrid/client)

## <a name="management-sdk"></a>管理 SDK

管理 SDK を使用して、Event Grid のインスタンス、トピック、サブスクリプションを作成、更新、削除します。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。


#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.EventGrid
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.Management.EventGrid
```

> [!div class="nextstepaction"]
> [Management API を探す](/dotnet/api/overview/azure/eventgrid/management)

## <a name="learn-more"></a>詳細情報

- [Event Grid SDK を使用してイベントを受信する](/azure/event-grid/receive-events)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
