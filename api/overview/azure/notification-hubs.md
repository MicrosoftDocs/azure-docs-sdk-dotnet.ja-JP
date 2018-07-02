---
title: .NET 用 Azure Notification Hubs ライブラリ
description: .NET 用 Azure Notification Hubs ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Notification Hubs
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: notification-hubs
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 0cbbfbafd2d1900c00f08fd1ab2e0f1af80ae8ff
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065502"
---
# <a name="azure-notification-hubs-libraries-for-net"></a><span data-ttu-id="b98c2-104">.NET 用 Azure Notification Hubs ライブラリ</span><span class="sxs-lookup"><span data-stu-id="b98c2-104">Azure Notification Hubs libraries for .NET</span></span>

<span data-ttu-id="b98c2-105">Azure Notification Hubs は、使いやすいマルチプラットフォーム対応のスケール アウトされたプッシュ エンジンを提供します。</span><span class="sxs-lookup"><span data-stu-id="b98c2-105">Azure Notification Hubs provide an easy-to-use, multi-platform, scaled-out push engine.</span></span> <span data-ttu-id="b98c2-106">プラットフォームをまたぐ単一の API 呼び出しで、任意のバックエンド (クラウドまたはオンプレミス) から任意のモバイル プラットフォームに、対象を指定して個人用に設定したプッシュ通知を送信できます。</span><span class="sxs-lookup"><span data-stu-id="b98c2-106">With a single cross-platform API call, you can easily send targeted and personalized push notifications to any mobile platform from any cloud or on-premises backend.</span></span>

## <a name="client-library"></a><span data-ttu-id="b98c2-107">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="b98c2-107">Client library</span></span>

<span data-ttu-id="b98c2-108">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="b98c2-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

> [!NOTE]
> <span data-ttu-id="b98c2-109">[NuGet パッケージの新しいプレビュー バージョン](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs/2.0.0-preview1)では .NET Standard がサポートされるようになりました。これにより、バックエンドでの Notification Hubs の使用に対して.NET Core を使うことができます</span><span class="sxs-lookup"><span data-stu-id="b98c2-109">A [new preview version of the NuGet package](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs/2.0.0-preview1) now supports .NET Standard, which allows using .NET core for backend use of Notifications Hubs</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="b98c2-110">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="b98c2-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.NotificationHubs
```

```bash
dotnet add package Microsoft.Azure.NotificationHubs
```

### <a name="code-example"></a><span data-ttu-id="b98c2-111">コード例</span><span class="sxs-lookup"><span data-stu-id="b98c2-111">Code Example</span></span>

<span data-ttu-id="b98c2-112">この例では、Notification Hub に接続し、Windows プッシュ通知サービス (WNS) メッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="b98c2-112">This example connects to a Notification Hub and sends a Windows Push Notification Service (WNS) message.</span></span>

```csharp
NotificationHubClient hub = NotificationHubClient
                                .CreateClientFromConnectionString("<connection string with full access>", "<hub name>");
string toast = @"<toast><visual><binding template=""ToastText01""><text id=""1"">Hello from a .NET App!</text></binding></visual></toast>";
await hub.SendWindowsNativeNotificationAsync(toast);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="b98c2-113">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="b98c2-113">Explore the client APIs</span></span>](/dotnet/api/overview/azure/notificationhubs/client)


## <a name="management-library"></a><span data-ttu-id="b98c2-114">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="b98c2-114">Management library</span></span>

<span data-ttu-id="b98c2-115">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.NotificationHubs)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="b98c2-115">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.NotificationHubs) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="b98c2-116">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="b98c2-116">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.NotificationHubs
```

```bash
dotnet add package Microsoft.Azure.Management.NotificationHubs
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="b98c2-117">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="b98c2-117">Explore the management APIs</span></span>](/dotnet/api/overview/azure/notificationhubs/management)

## <a name="samples"></a><span data-ttu-id="b98c2-118">サンプル</span><span class="sxs-lookup"><span data-stu-id="b98c2-118">Samples</span></span>

- [<span data-ttu-id="b98c2-119">Windows ユニバーサルの概要</span><span class="sxs-lookup"><span data-stu-id="b98c2-119">Getting Started with Windows Universal</span></span>](https://github.com/Azure/azure-notificationhubs-samples/tree/master/dotnet/GetStartedWindowsUniversal)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
