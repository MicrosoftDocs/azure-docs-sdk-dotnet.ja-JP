---
title: ".NET 用 Azure Event Hubs ライブラリ"
description: ".NET 用 Azure Event Hubs ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Event Hubs
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: event-hubs
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 2ec234959ffc46d2399d1c763e05f173a311b0d2
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/23/2017
---
# <a name="azure-event-hubs-libraries-for-net"></a><span data-ttu-id="61777-104">.NET 用 Azure Event Hubs ライブラリ</span><span class="sxs-lookup"><span data-stu-id="61777-104">Azure Event Hubs libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="61777-105">概要</span><span class="sxs-lookup"><span data-stu-id="61777-105">Overview</span></span>

<span data-ttu-id="61777-106">Azure Event Hubs は、拡張性の高いデータ ストリーミング プラットフォームであり、イベント インジェスト サービスでもあります。</span><span class="sxs-lookup"><span data-stu-id="61777-106">Azure Event Hubs is a highly scalable data streaming platform and event ingestion service.</span></span>

<span data-ttu-id="61777-107">Azure Event Hubs の詳細については、「[Event Hubs とは](/azure/event-hubs/event-hubs-what-is-event-hubs)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="61777-107">To learn more about Azure Event Hubs, read the article [What is Event Hubs?](/azure/event-hubs/event-hubs-what-is-event-hubs).</span></span>  <span data-ttu-id="61777-108">作業を開始するには、「[Event Hubs のプログラミング ガイド](/azure/event-hubs/event-hubs-programming-guide)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="61777-108">To get started, check out the [Event Hubs Programming Guide](/azure/event-hubs/event-hubs-programming-guide).</span></span>

## <a name="client-library"></a><span data-ttu-id="61777-109">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="61777-109">Client library</span></span>

<span data-ttu-id="61777-110">Event Hubs との間でメッセージを送受信するには、Event Hubs クライアントを使用します。</span><span class="sxs-lookup"><span data-stu-id="61777-110">Use the Event Hubs client to send and receive messages to and from Event Hubs.</span></span>

<span data-ttu-id="61777-111">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.EventHubs)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="61777-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.EventHubs) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="61777-112">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="61777-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.EventHubs
```

```bash
dotnet add package Microsoft.Azure.EventHubs
```

### <a name="code-example"></a><span data-ttu-id="61777-113">コード例</span><span class="sxs-lookup"><span data-stu-id="61777-113">Code Example</span></span>

<span data-ttu-id="61777-114">次のコードでは、Event Hubs クライアントを作成し、ハブにメッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="61777-114">The following code creates an Event Hubs client and sends a message to the hub.</span></span>

```csharp
EventHubsConnectionStringBuilder connectionStringBuilder = new EventHubsConnectionStringBuilder(eventHubConnectionString)
{
    EntityPath = eventHubEntityPath
};

EventHubClient eventHubClient = EventHubClient.CreateFromConnectionString(connectionStringBuilder.ToString());
string message = $"Message {i}";
Console.WriteLine($"Sending message: {message}");
await eventHubClient.SendAsync(new EventData(Encoding.UTF8.GetBytes(message)));
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="61777-115">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="61777-115">Explore the client APIs</span></span>](/dotnet/api/overview/azure/eventhub/client)

## <a name="management-library"></a><span data-ttu-id="61777-116">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="61777-116">Management library</span></span>

<span data-ttu-id="61777-117">ハブとコンシューマー グループを作成、更新、削除するには、Event Hubs 管理ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="61777-117">Use the Event Hubs management library to create, update, and remove hubs and consumer groups.</span></span>

<span data-ttu-id="61777-118">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.EventHub)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="61777-118">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.EventHub) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="61777-119">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="61777-119">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.EventHub
```

```bash
dotnet add package Microsoft.Azure.Management.EventHub
```

### <a name="code-example"></a><span data-ttu-id="61777-120">コード例</span><span class="sxs-lookup"><span data-stu-id="61777-120">Code Example</span></span>

<span data-ttu-id="61777-121">次のコード例では、新しいイベント ハブを作成します。</span><span class="sxs-lookup"><span data-stu-id="61777-121">The following code creates a new event hub.</span></span>

```csharp
TokenCredentials creds = new TokenCredentials(token);
EventHubManagementClient ehClient = new EventHubManagementClient(creds)
{
    SubscriptionId = subscriptionId
};

EventHubCreateOrUpdateParameters ehParams = new EventHubCreateOrUpdateParameters()
{
    Location = location
};

Console.WriteLine("Creating Event Hub...");
await ehClient.EventHubs.CreateOrUpdateAsync(resourceGroupName, namespaceName, EventHubName, ehParams);
Console.WriteLine("Created Event Hub successfully.");
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="61777-122">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="61777-122">Explore the management APIs</span></span>](/dotnet/api/overview/azure/eventhub/management)

## <a name="tutorials"></a><span data-ttu-id="61777-123">Tutorials (チュートリアル)</span><span class="sxs-lookup"><span data-stu-id="61777-123">Tutorials</span></span>

* [<span data-ttu-id="61777-124">.NET Framework を使用して Azure Event Hubs にイベントを送信する</span><span class="sxs-lookup"><span data-stu-id="61777-124">Send events to Azure Event Hubs using the .NET Framework</span></span>](/azure/event-hubs/event-hubs-dotnet-framework-getstarted-send)

* [<span data-ttu-id="61777-125">.NET Framework を使用して Azure Event Hubs からイベントを受信する</span><span class="sxs-lookup"><span data-stu-id="61777-125">Receive events from Azure Event Hubs using the .NET Framework</span></span>](/azure/event-hubs/event-hubs-dotnet-framework-getstarted-receive-eph)

## <a name="samples"></a><span data-ttu-id="61777-126">サンプル</span><span class="sxs-lookup"><span data-stu-id="61777-126">Samples</span></span>

* [<span data-ttu-id="61777-127">Azure Event Hubs のサンプル</span><span class="sxs-lookup"><span data-stu-id="61777-127">Azure Event Hubs Samples</span></span>](https://github.com/Azure/azure-event-hubs/tree/master/samples)

<span data-ttu-id="61777-128">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="61777-128">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
