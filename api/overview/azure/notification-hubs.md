---
title: .NET 用 Azure Notification Hubs ライブラリ
description: .NET 用 Azure Notification Hubs ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Notification Hubs
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: notification-hubs
ms.custom: devcenter, svc-overview
ms.openlocfilehash: f863bf9d5d63129e04dd31ba96b3e803bead87bc
ms.sourcegitcommit: 4c42de7e066b6aa0a5b5df02cce4d1d245aa558d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/18/2018
ms.locfileid: "31447639"
---
# <a name="azure-notification-hubs-libraries-for-net"></a>.NET 用 Azure Notification Hubs ライブラリ

Azure Notification Hubs は、使いやすいマルチプラットフォーム対応のスケール アウトされたプッシュ エンジンを提供します。 プラットフォームをまたぐ単一の API 呼び出しで、任意のバックエンド (クラウドまたはオンプレミス) から任意のモバイル プラットフォームに、対象を指定して個人用に設定したプッシュ通知を送信できます。

## <a name="client-library"></a>クライアント ライブラリ

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

> [!NOTE]
> [NuGet パッケージの新しいプレビュー バージョン](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs/2.0.0-preview1)では .NET Standard がサポートされるようになりました。これにより、バックエンドでの Notification Hubs の使用に対して.NET Core を使うことができます

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.NotificationHubs
```

```bash
dotnet add package Microsoft.Azure.NotificationHubs
```

### <a name="code-example"></a>コード例

この例では、Notification Hub に接続し、Windows プッシュ通知サービス (WNS) メッセージを送信します。

```csharp
NotificationHubClient hub = NotificationHubClient
                                .CreateClientFromConnectionString("<connection string with full access>", "<hub name>");
string toast = @"<toast><visual><binding template=""ToastText01""><text id=""1"">Hello from a .NET App!</text></binding></visual></toast>";
await hub.SendWindowsNativeNotificationAsync(toast);
```

> [!div class="nextstepaction"]
> [クライアント API を探す](/dotnet/api/overview/azure/notificationhubs/client)


## <a name="management-library"></a>管理ライブラリ

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.NotificationHubs)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.NotificationHubs
```

```bash
dotnet add package Microsoft.Azure.Management.NotificationHubs
```

> [!div class="nextstepaction"]
> [Management API を探す](/dotnet/api/overview/azure/notificationhubs/management)

## <a name="samples"></a>サンプル

- [Windows ユニバーサルの概要](https://github.com/Azure/azure-notificationhubs-samples/tree/master/dotnet/GetStartedWindowsUniversal)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
