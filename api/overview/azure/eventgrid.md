---
title: .NET 用 Azure Event Grid ライブラリ
description: .NET 用 Azure Event Grid ライブラリのリファレンス
author: rloutlaw
ms.author: routlaw
manager: angerobe
ms.date: 04/16/2018
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: event-grid
ms.custom: devcenter
ms.openlocfilehash: aa25f76f041e890de512c67d9380903f81216f62
ms.sourcegitcommit: 9f54e3334fc35c1066d0c591ff85b16d46416aa8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2018
---
# <a name="azure-event-grid-libraries-for-net"></a><span data-ttu-id="38c41-103">.NET 用 Azure Event Grid ライブラリ</span><span class="sxs-lookup"><span data-stu-id="38c41-103">Azure Event Grid libraries for .NET</span></span>

<span data-ttu-id="38c41-104">Azure Event Grid で簡単な HTTP ベースのイベント処理を使用して、Azure サービスやカスタム ソースのイベントをリッスンして対応するイベント ドリブン アプリケーションを構築します。</span><span class="sxs-lookup"><span data-stu-id="38c41-104">Build event-driven applications that listen and react to events from Azure services and custom sources using simple HTTP-based event handling with Azure Event Grid.</span></span>

<span data-ttu-id="38c41-105">Azure Event Grid の[詳細を確認](/azure/event-grid/overview)し、[Azure Blob Storage イベントのチュートリアル](/azure/storage/blobs/storage-blob-event-quickstart-powershell)を開始してください。</span><span class="sxs-lookup"><span data-stu-id="38c41-105">[Learn more](/azure/event-grid/overview) about Azure Event Grid and get started with the [Azure Blob storage event tutorial](/azure/storage/blobs/storage-blob-event-quickstart-powershell).</span></span> 

## <a name="publish-sdk"></a><span data-ttu-id="38c41-106">発行 SDK</span><span class="sxs-lookup"><span data-stu-id="38c41-106">Publish SDK</span></span>

<span data-ttu-id="38c41-107">Azure Event Grid 発行 SDK を使用して、イベントの作成、認証、トピックへの投稿を行います。</span><span class="sxs-lookup"><span data-stu-id="38c41-107">Create events, authenticate, and post to topics using the Azure Event Grid publish SDK.</span></span>

<span data-ttu-id="38c41-108">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="38c41-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="38c41-109">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="38c41-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.EventGrid
```

#### <a name="net-core-cli"></a><span data-ttu-id="38c41-110">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="38c41-110">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.EventGrid 
```

### <a name="sample-usage"></a><span data-ttu-id="38c41-111">使用例</span><span class="sxs-lookup"><span data-stu-id="38c41-111">Sample usage</span></span>

<span data-ttu-id="38c41-112">次のコードでは、Azure で認証し、カスタム型の `EventGridEvent` イベント (この例では `Contoso.Items.ItemsReceivedEvent`) の `List` をトピックに発行します。</span><span class="sxs-lookup"><span data-stu-id="38c41-112">The following code authenticates with Azure and publishes a `List` of  `EventGridEvent` events of a custom type (in this example, `Contoso.Items.ItemsReceivedEvent` ) to a topic.</span></span> <span data-ttu-id="38c41-113">このサンプルで使用されているトピック キーとエンドポイント アドレスは、Azure PowerShell から取得できます。</span><span class="sxs-lookup"><span data-stu-id="38c41-113">The topic key and endpoint address used in the sample can be retrieved from Azure PowerShell:</span></span>

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

<span data-ttu-id="38c41-114">次のスニペットでは、[Azure Storage](/azure/storage/blobs/storage-blob-event-overview) で新しい BLOB を作成するときに発行されたイベントを処理します。</span><span class="sxs-lookup"><span data-stu-id="38c41-114">This snippet handles events published when creating a new blob in [Azure Storage](/azure/storage/blobs/storage-blob-event-overview).</span></span>

```csharp
string response = string.Empty;
const string SubscriptionValidationEvent = "Microsoft.EventGrid.SubscriptionValidationEvent";
const string StorageBlobCreatedEvent = "Microsoft.Storage.BlobCreated";

string requestContent = await req.Content.ReadAsStringAsync();
EventGridEvent[] eventGridEvents = JsonConvert.DeserializeObject<EventGridEvent[]>(requestContent);

foreach (EventGridEvent eventGridEvent in eventGridEvents)
{
    JObject dataObject = eventGridEvent.Data as JObject;

    // Deserialize the event data into the appropriate type based on event type 
    if (string.Equals(eventGridEvent.EventType, SubscriptionValidationEvent, StringComparison.OrdinalIgnoreCase))
    {
        var eventData = dataObject.ToObject<SubscriptionValidationEventData>();
        log.Info($"Got SubscriptionValidation event data, validation code: {eventData.ValidationCode}, topic: {eventGridEvent.Topic}");

        // Do any additional validation (as required) and then return back the below response
        var responseData = new SubscriptionValidationResponseData();
        responseData.ValidationResponse = eventData.ValidationCode;
        return req.CreateResponse(HttpStatusCode.OK, responseData);
    }

    else if (string.Equals(eventGridEvent.EventType, StorageBlobCreatedEvent, StringComparison.OrdinalIgnoreCase))
    {
        var eventData = dataObject.ToObject<StorageBlobCreatedEventData>();
        log.Info($"Got BlobCreated event data, blob URI {eventData.Url}");
    }
}
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="38c41-115">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="38c41-115">Explore the client APIs</span></span>](/dotnet/api/overview/azure/eventgrid/client)

## <a name="management-sdk"></a><span data-ttu-id="38c41-116">管理 SDK</span><span class="sxs-lookup"><span data-stu-id="38c41-116">Management SDK</span></span>

<span data-ttu-id="38c41-117">管理 SDK を使用して、Event Grid のインスタンス、トピック、サブスクリプションを作成、更新、削除します。</span><span class="sxs-lookup"><span data-stu-id="38c41-117">Create, update, or delete Event Grid instances, topics, and subscriptions with the management SDK.</span></span>

<span data-ttu-id="38c41-118">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="38c41-118">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>


#### <a name="visual-studio-package-manager"></a><span data-ttu-id="38c41-119">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="38c41-119">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.EventGrid
```

#### <a name="net-core-cli"></a><span data-ttu-id="38c41-120">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="38c41-120">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.EventGrid
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="38c41-121">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="38c41-121">Explore the management APIs</span></span>](/dotnet/api/overview/azure/eventgrid/management)

## <a name="learn-more"></a><span data-ttu-id="38c41-122">詳細情報</span><span class="sxs-lookup"><span data-stu-id="38c41-122">Learn more</span></span>

- [<span data-ttu-id="38c41-123">Event Grid SDK を使用してイベントを受信する</span><span class="sxs-lookup"><span data-stu-id="38c41-123">Receive events using the Event Grid SDK</span></span>](/azure/event-grid/receive-events)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
