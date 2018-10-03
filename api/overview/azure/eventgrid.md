---
title: .NET 用 Azure Event Grid ライブラリ
description: .NET 用 Azure Event Grid ライブラリのリファレンス
ms.date: 04/16/2018
ms.topic: reference
ms.service: event-grid
ms.openlocfilehash: 5b19f8aa8b28b3e4aef528da051b6e7d177f1a2f
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190395"
---
# <a name="azure-event-grid-libraries-for-net"></a><span data-ttu-id="0d4f8-103">.NET 用 Azure Event Grid ライブラリ</span><span class="sxs-lookup"><span data-stu-id="0d4f8-103">Azure Event Grid libraries for .NET</span></span>

<span data-ttu-id="0d4f8-104">Azure Event Grid で簡単な HTTP ベースのイベント処理を使用して、Azure サービスやカスタム ソースのイベントをリッスンして対応するイベント ドリブン アプリケーションを構築します。</span><span class="sxs-lookup"><span data-stu-id="0d4f8-104">Build event-driven applications that listen and react to events from Azure services and custom sources using simple HTTP-based event handling with Azure Event Grid.</span></span>

<span data-ttu-id="0d4f8-105">Azure Event Grid の[詳細を確認](/azure/event-grid/overview)し、[Azure Blob Storage イベントのチュートリアル](/azure/storage/blobs/storage-blob-event-quickstart-powershell)を開始してください。</span><span class="sxs-lookup"><span data-stu-id="0d4f8-105">[Learn more](/azure/event-grid/overview) about Azure Event Grid and get started with the [Azure Blob storage event tutorial](/azure/storage/blobs/storage-blob-event-quickstart-powershell).</span></span> 

## <a name="client-sdk"></a><span data-ttu-id="0d4f8-106">クライアント SDK</span><span class="sxs-lookup"><span data-stu-id="0d4f8-106">Client SDK</span></span>

<span data-ttu-id="0d4f8-107">Azure Event Grid クライアント SDK を使用して、イベントの作成、認証、トピックへの投稿を行います。</span><span class="sxs-lookup"><span data-stu-id="0d4f8-107">Create events, authenticate, and post to topics using the Azure Event Grid Client SDK.</span></span>

<span data-ttu-id="0d4f8-108">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="0d4f8-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="0d4f8-109">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="0d4f8-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.EventGrid
```

#### <a name="net-core-cli"></a><span data-ttu-id="0d4f8-110">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="0d4f8-110">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.EventGrid 
```

### <a name="publish-events"></a><span data-ttu-id="0d4f8-111">イベントの発行</span><span class="sxs-lookup"><span data-stu-id="0d4f8-111">Publish events</span></span>

<span data-ttu-id="0d4f8-112">次のコードでは、Azure で認証し、カスタム型の `EventGridEvent` イベント (この例では `Contoso.Items.ItemsReceivedEvent`) の `List` をトピックに発行します。</span><span class="sxs-lookup"><span data-stu-id="0d4f8-112">The following code authenticates with Azure and publishes a `List` of  `EventGridEvent` events of a custom type (in this example, `Contoso.Items.ItemsReceivedEvent` ) to a topic.</span></span> <span data-ttu-id="0d4f8-113">このサンプルで使用されているトピック キーとエンドポイント アドレスは、Azure PowerShell から取得できます。</span><span class="sxs-lookup"><span data-stu-id="0d4f8-113">The topic key and endpoint address used in the sample can be retrieved from Azure PowerShell:</span></span>

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

### <a name="consume-events"></a><span data-ttu-id="0d4f8-114">イベントの使用</span><span class="sxs-lookup"><span data-stu-id="0d4f8-114">Consume events</span></span>

<span data-ttu-id="0d4f8-115">このスニペットでは、カスタム イベント `Contoso.Items.ItemsReceived` などのイベントや、Blob Storage など、他の Azure サービスからトリガーされるイベントを使用します。</span><span class="sxs-lookup"><span data-stu-id="0d4f8-115">This snippet consumes events, including a custom event `Contoso.Items.ItemsReceived` as well as events triggered from other Azure services, such as Blob Storage.</span></span>

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
> [<span data-ttu-id="0d4f8-116">Publishing API を確認する</span><span class="sxs-lookup"><span data-stu-id="0d4f8-116">Explore the publishing APIs</span></span>](/dotnet/api/overview/azure/eventgrid/publish)

## <a name="management-sdk"></a><span data-ttu-id="0d4f8-117">管理 SDK</span><span class="sxs-lookup"><span data-stu-id="0d4f8-117">Management SDK</span></span>

<span data-ttu-id="0d4f8-118">管理 SDK を使用して、Event Grid のインスタンス、トピック、サブスクリプションを作成、更新、削除します。</span><span class="sxs-lookup"><span data-stu-id="0d4f8-118">Create, update, or delete Event Grid instances, topics, and subscriptions with the management SDK.</span></span>

<span data-ttu-id="0d4f8-119">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="0d4f8-119">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>


#### <a name="visual-studio-package-manager"></a><span data-ttu-id="0d4f8-120">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="0d4f8-120">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.EventGrid
```

#### <a name="net-core-cli"></a><span data-ttu-id="0d4f8-121">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="0d4f8-121">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.EventGrid
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="0d4f8-122">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="0d4f8-122">Explore the management APIs</span></span>](/dotnet/api/overview/azure/eventgrid/management)

## <a name="learn-more"></a><span data-ttu-id="0d4f8-123">詳細情報</span><span class="sxs-lookup"><span data-stu-id="0d4f8-123">Learn more</span></span>

- [<span data-ttu-id="0d4f8-124">Event Grid SDK を使用してイベントを受信する</span><span class="sxs-lookup"><span data-stu-id="0d4f8-124">Receive events using the Event Grid SDK</span></span>](/azure/event-grid/receive-events)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
