---
title: .NET 用 Azure Notification Hubs ライブラリ
description: .NET 用 Azure Notification Hubs ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: notification-hubs
ms.openlocfilehash: 750a51e8dfa7323f6afb54735b4bfc517f9ec15f
ms.sourcegitcommit: 4b68c73652cb7e44cf4db36f70cb33a17dd863ce
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/19/2019
ms.locfileid: "58085839"
---
# <a name="azure-notification-hubs-libraries-for-net"></a>.NET 用 Azure Notification Hubs ライブラリ

Azure Notification Hubs は、使いやすいマルチプラットフォーム対応のスケール アウトされたプッシュ エンジンを提供します。 プラットフォームをまたぐ単一の API 呼び出しで、任意のバックエンド (クラウドまたはオンプレミス) から任意のモバイル プラットフォームに、対象を指定して個人用に設定したプッシュ通知を送信できます。

## <a name="client-library"></a>クライアント ライブラリ

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

> [!NOTE]
> [Azure Notification Hubs NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs)では .NET Standard がサポートされるようになりました。これにより、バックエンドでの Notification Hubs の使用に対して .NET Core を使うことができます

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
