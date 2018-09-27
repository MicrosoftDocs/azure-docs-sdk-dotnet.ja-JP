---
title: .NET 用 Azure Service Bus ライブラリ
description: .NET 用 Azure Service Bus ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: service-bus
ms.openlocfilehash: 506be9a669a2418f2437271d128a963e351442e7
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190875"
---
# <a name="azure-service-bus-libraries-for-net"></a><span data-ttu-id="fbc99-103">.NET 用 Azure Service Bus ライブラリ</span><span class="sxs-lookup"><span data-stu-id="fbc99-103">Azure Service Bus libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="fbc99-104">概要</span><span class="sxs-lookup"><span data-stu-id="fbc99-104">Overview</span></span>

<span data-ttu-id="fbc99-105">[Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview) は、アプリケーション間のメッセージング インフラストラクチャであり、アプリケーションによるメッセージ交換を可能にすることでスケールと回復性を向上させます。</span><span class="sxs-lookup"><span data-stu-id="fbc99-105">[Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview) is a messaging infrastructure that sits between applications allowing them to exchange messages for improved scale and resiliency.</span></span>

## <a name="client-library"></a><span data-ttu-id="fbc99-106">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="fbc99-106">Client library</span></span>

<span data-ttu-id="fbc99-107">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.ServiceBus)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールします。</span><span class="sxs-lookup"><span data-stu-id="fbc99-107">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.ServiceBus) directly from the Visual Studio [Package Manager console][PackageManager].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="fbc99-108">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="fbc99-108">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.ServiceBus
```

### <a name="code-example"></a><span data-ttu-id="fbc99-109">コード例</span><span class="sxs-lookup"><span data-stu-id="fbc99-109">Code Example</span></span>

<span data-ttu-id="fbc99-110">この例では、Service Bus キューにメッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="fbc99-110">This example sends a message to a Service Bus queue.</span></span>

```csharp
// using Microsoft.Azure.ServiceBus;
// Microsoft.Azure.ServiceBus 2.0.0 (stable)

byte[] messageBody = System.Text.Encoding.Unicode.GetBytes("Hello, world!");
ServiceBusConnectionStringBuilder builder = new ServiceBusConnectionStringBuilder(connectionString);
QueueClient client = new QueueClient(builder, ReceiveMode.PeekLock);
client.SendAsync(new Message(messageBody));
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="fbc99-111">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="fbc99-111">Explore the client APIs</span></span>](/dotnet/api/overview/azure/servicebus/client)


## <a name="management-library"></a><span data-ttu-id="fbc99-112">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="fbc99-112">Management library</span></span>

<span data-ttu-id="fbc99-113">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceBus.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="fbc99-113">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceBus.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="fbc99-114">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="fbc99-114">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.ServiceBus.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="fbc99-115">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="fbc99-115">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.ServiceBus.Fluent
```

### <a name="code-example"></a><span data-ttu-id="fbc99-116">コード例</span><span class="sxs-lookup"><span data-stu-id="fbc99-116">Code Example</span></span>

<span data-ttu-id="fbc99-117">この例では、最大サイズが 1024 MB の Service Bus キューを作成します。</span><span class="sxs-lookup"><span data-stu-id="fbc99-117">This example creates a Service Bus queue with a maximum size of 1024 MB.</span></span>

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
> [<span data-ttu-id="fbc99-118">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="fbc99-118">Explore the management APIs</span></span>](/dotnet/api/overview/azure/servicebus/management)

## <a name="samples"></a><span data-ttu-id="fbc99-119">サンプル</span><span class="sxs-lookup"><span data-stu-id="fbc99-119">Samples</span></span>

- [<span data-ttu-id="fbc99-120">Service Bus キューの基本 - .Net</span><span class="sxs-lookup"><span data-stu-id="fbc99-120">Service Bus Queue Basics - .Net</span></span>](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-queue-with-basic-features/)
- [<span data-ttu-id="fbc99-121">Service Bus キューの高度な機能 - .Net</span><span class="sxs-lookup"><span data-stu-id="fbc99-121">Service Bus Queue Advanced Features - .Net</span></span>](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-queue-with-advanced-features/)
- [<span data-ttu-id="fbc99-122">Service Bus の発行/サブスクライブの基本 - .Net</span><span class="sxs-lookup"><span data-stu-id="fbc99-122">Service Bus Publish/Subscribe Basics - .Net</span></span>](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-publish-subscribe-with-basic-features/)
- [<span data-ttu-id="fbc99-123">Service Bus の発行/サブスクライブの高度な機能 - .Net</span><span class="sxs-lookup"><span data-stu-id="fbc99-123">Service Bus Publish/Subscribe Advanced Features - .Net</span></span>](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-publish-subscribe-with-advanced-features/)
- [<span data-ttu-id="fbc99-124">Service Bus とクレーム ベースの承認 - .Net</span><span class="sxs-lookup"><span data-stu-id="fbc99-124">Service Bus with Claims-Based Authorization - .Net</span></span>](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-with-claims-based-authorization/)

<span data-ttu-id="fbc99-125">Azure Service Bus のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?term=service+bus)を表示します。</span><span class="sxs-lookup"><span data-stu-id="fbc99-125">View the [complete list](https://azure.microsoft.com/resources/samples/?term=service+bus) of Azure Service Bus samples.</span></span>


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
