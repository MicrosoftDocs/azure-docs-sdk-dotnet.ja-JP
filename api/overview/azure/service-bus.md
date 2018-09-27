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
# <a name="azure-service-bus-libraries-for-net"></a>.NET 用 Azure Service Bus ライブラリ

## <a name="overview"></a>概要

[Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview) は、アプリケーション間のメッセージング インフラストラクチャであり、アプリケーションによるメッセージ交換を可能にすることでスケールと回復性を向上させます。

## <a name="client-library"></a>クライアント ライブラリ

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.ServiceBus)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.ServiceBus
```

### <a name="code-example"></a>コード例

この例では、Service Bus キューにメッセージを送信します。

```csharp
// using Microsoft.Azure.ServiceBus;
// Microsoft.Azure.ServiceBus 2.0.0 (stable)

byte[] messageBody = System.Text.Encoding.Unicode.GetBytes("Hello, world!");
ServiceBusConnectionStringBuilder builder = new ServiceBusConnectionStringBuilder(connectionString);
QueueClient client = new QueueClient(builder, ReceiveMode.PeekLock);
client.SendAsync(new Message(messageBody));
```

> [!div class="nextstepaction"]
> [クライアント API を探す](/dotnet/api/overview/azure/servicebus/client)


## <a name="management-library"></a>管理ライブラリ

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceBus.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

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
