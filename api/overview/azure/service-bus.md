---
title: ".NET 用 Azure Service Bus ライブラリ"
description: ".NET 用 Azure Service Bus ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Service Bus
author: camsoper
ms.author: casoper
manager: douge
ms.date: 08/01/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: d4d3ac982794fc7533b97fe8c053730b4b39ff58
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-service-bus-libraries-for-net"></a>.NET 用 Azure Service Bus ライブラリ

## <a name="overview"></a>概要

[Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview) は、アプリケーション間のメッセージング インフラストラクチャであり、アプリケーションによるメッセージ交換を可能にすることでスケールと回復性を向上させます。

## <a name="client-library"></a>クライアント ライブラリ

[NuGet パッケージ](https://www.nuget.org/packages/WindowsAzure.ServiceBus)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package WindowsAzure.ServiceBus
```

### <a name="code-example"></a>コード例

この例では、Service Bus キューにメッセージを送信します。

```csharp
// using Microsoft.ServiceBus.Messaging;

QueueClient client = QueueClient.CreateFromConnectionString(connectionString, queueName);
BrokeredMessage message = new BrokeredMessage("This is a test message!");
client.Send(message);
```

> [!div class="nextstepaction"]
> [クライアント API を探す](/dotnet/api/overview/azure/servicebus/client)


## <a name="management-library"></a>管理ライブラリ

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceBus.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.ServiceBus.Fluent
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.Management.ServiceBus.Fluent
```

### <a name="code-example"></a>コード例

この例では、最大サイズが 1024 MB の Service Bus キューを作成します。

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
> [Management API を探す](/dotnet/api/overview/azure/servicebus/management)

## <a name="samples"></a>サンプル

- [Service Bus キューの基本 - .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-queue-with-basic-features/)
- [Service Bus キューの高度な機能 - .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-queue-with-advanced-features/)
- [Service Bus の発行/サブスクライブの基本 - .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-publish-subscribe-with-basic-features/)
- [Service Bus の発行/サブスクライブの高度な機能 - .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-publish-subscribe-with-advanced-features/)
- [Service Bus とクレーム ベースの承認 - .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-with-claims-based-authorization/)

Azure Service Bus のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?term=service+bus)を表示します。


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
