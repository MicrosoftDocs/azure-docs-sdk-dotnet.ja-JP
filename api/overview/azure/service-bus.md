---
title: .NET 用 Azure Service Bus ライブラリ
description: .NET 用 Azure Service Bus ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Service Bus
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: service-bus
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 5ebd659121019c74ad607dc2a553f7e305a34021
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065472"
---
# <a name="azure-service-bus-libraries-for-net"></a><span data-ttu-id="c50e0-104">.NET 用 Azure Service Bus ライブラリ</span><span class="sxs-lookup"><span data-stu-id="c50e0-104">Azure Service Bus libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="c50e0-105">概要</span><span class="sxs-lookup"><span data-stu-id="c50e0-105">Overview</span></span>

<span data-ttu-id="c50e0-106">[Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview) は、アプリケーション間のメッセージング インフラストラクチャであり、アプリケーションによるメッセージ交換を可能にすることでスケールと回復性を向上させます。</span><span class="sxs-lookup"><span data-stu-id="c50e0-106">[Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview) is a messaging infrastructure that sits between applications allowing them to exchange messages for improved scale and resiliency.</span></span>

## <a name="client-library"></a><span data-ttu-id="c50e0-107">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="c50e0-107">Client library</span></span>

<span data-ttu-id="c50e0-108">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.ServiceBus)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールします。</span><span class="sxs-lookup"><span data-stu-id="c50e0-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.ServiceBus) directly from the Visual Studio [Package Manager console][PackageManager].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="c50e0-109">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="c50e0-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.ServiceBus
```

### <a name="code-example"></a><span data-ttu-id="c50e0-110">コード例</span><span class="sxs-lookup"><span data-stu-id="c50e0-110">Code Example</span></span>

<span data-ttu-id="c50e0-111">この例では、Service Bus キューにメッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="c50e0-111">This example sends a message to a Service Bus queue.</span></span>

```csharp
// using Microsoft.Azure.ServiceBus;
// Microsoft.Azure.ServiceBus 2.0.0 (stable)

byte[] messageBody = System.Text.Encoding.Unicode.GetBytes("Hello, world!");
ServiceBusConnectionStringBuilder builder = new ServiceBusConnectionStringBuilder(connectionString);
QueueClient client = new QueueClient(builder, ReceiveMode.PeekLock);
client.SendAsync(new Message(messageBody));
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="c50e0-112">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="c50e0-112">Explore the client APIs</span></span>](/dotnet/api/overview/azure/servicebus/client)


## <a name="management-library"></a><span data-ttu-id="c50e0-113">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="c50e0-113">Management library</span></span>

<span data-ttu-id="c50e0-114">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceBus.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="c50e0-114">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceBus.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="c50e0-115">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="c50e0-115">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.ServiceBus.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="c50e0-116">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="c50e0-116">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.ServiceBus.Fluent
```

### <a name="code-example"></a><span data-ttu-id="c50e0-117">コード例</span><span class="sxs-lookup"><span data-stu-id="c50e0-117">Code Example</span></span>

<span data-ttu-id="c50e0-118">この例では、最大サイズが 1024 MB の Service Bus キューを作成します。</span><span class="sxs-lookup"><span data-stu-id="c50e0-118">This example creates a Service Bus queue with a maximum size of 1024 MB.</span></span>

```csharp
// using Microsoft.Azure.Management.ServiceBus.Fluent;
// using Microsoft.Azure.Management.ServiceBus.Fluent.Models;

using (ServiceBusManagementClient client = new ServiceBusManagementClient(credentials))
{
    client.SubscriptionId = subscriptionId;
    QueueInner parameters = new QueueInner
    {
        MaxSizeInMegabytes = 1024
    };
    await client.Queues.CreateOrUpdateAsync(resourceGroupName, namespaceName, queueName, parameters);
}
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="c50e0-119">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="c50e0-119">Explore the management APIs</span></span>](/dotnet/api/overview/azure/servicebus/management)

## <a name="samples"></a><span data-ttu-id="c50e0-120">サンプル</span><span class="sxs-lookup"><span data-stu-id="c50e0-120">Samples</span></span>

- [<span data-ttu-id="c50e0-121">Service Bus キューの基本 - .Net</span><span class="sxs-lookup"><span data-stu-id="c50e0-121">Service Bus Queue Basics - .Net</span></span>](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-queue-with-basic-features/)
- [<span data-ttu-id="c50e0-122">Service Bus キューの高度な機能 - .Net</span><span class="sxs-lookup"><span data-stu-id="c50e0-122">Service Bus Queue Advanced Features - .Net</span></span>](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-queue-with-advanced-features/)
- [<span data-ttu-id="c50e0-123">Service Bus の発行/サブスクライブの基本 - .Net</span><span class="sxs-lookup"><span data-stu-id="c50e0-123">Service Bus Publish/Subscribe Basics - .Net</span></span>](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-publish-subscribe-with-basic-features/)
- [<span data-ttu-id="c50e0-124">Service Bus の発行/サブスクライブの高度な機能 - .Net</span><span class="sxs-lookup"><span data-stu-id="c50e0-124">Service Bus Publish/Subscribe Advanced Features - .Net</span></span>](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-publish-subscribe-with-advanced-features/)
- [<span data-ttu-id="c50e0-125">Service Bus とクレーム ベースの承認 - .Net</span><span class="sxs-lookup"><span data-stu-id="c50e0-125">Service Bus with Claims-Based Authorization - .Net</span></span>](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-with-claims-based-authorization/)

<span data-ttu-id="c50e0-126">Azure Service Bus のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?term=service+bus)を表示します。</span><span class="sxs-lookup"><span data-stu-id="c50e0-126">View the [complete list](https://azure.microsoft.com/resources/samples/?term=service+bus) of Azure Service Bus samples.</span></span>


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
