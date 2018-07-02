---
title: .NET 用 Azure Service Bus Relay ライブラリ
description: .NET 用 Azure Service Bus Relay ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Service Bus Relay
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: service-bus
ms.custom: devcenter, svc-overview
ms.openlocfilehash: e0dd9c9b0a187fe6ca81d764e60afd00cbaab654
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065952"
---
# <a name="azure-service-bus-relay-libraries-for-net"></a><span data-ttu-id="56cd0-104">.NET 用 Azure Service Bus Relay ライブラリ</span><span class="sxs-lookup"><span data-stu-id="56cd0-104">Azure Service Bus Relay libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="56cd0-105">概要</span><span class="sxs-lookup"><span data-stu-id="56cd0-105">Overview</span></span>

<span data-ttu-id="56cd0-106">Azure Relay サービスでは、ファイアウォール接続の開放や企業ネットワーク インフラストラクチャの煩わしい変更を必要とせずに、企業のエンタープライズ ネットワーク内にあるサービスをパブリック クラウドに安全に公開できるハイブリッド アプリケーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="56cd0-106">The Azure Relay service creates hybrid applications by enabling you to securely expose services that reside within a corporate enterprise network to the public cloud, without having to open a firewall connection, or require intrusive changes to a corporate network infrastructure.</span></span> <span data-ttu-id="56cd0-107">Relay では、多様なトランスポート プロトコルと Web サービス標準がサポートされています。</span><span class="sxs-lookup"><span data-stu-id="56cd0-107">Relay supports a variety of different transport protocols and web services standards.</span></span>
          
<span data-ttu-id="56cd0-108">Azure Relay の詳細については、[こちら](/azure/service-bus-relay/relay-what-is-it)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="56cd0-108">Learn more about [Azure Relay](/azure/service-bus-relay/relay-what-is-it).</span></span>

## <a name="client-library"></a><span data-ttu-id="56cd0-109">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="56cd0-109">Client library</span></span>

<span data-ttu-id="56cd0-110">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Relay)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="56cd0-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Relay) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="56cd0-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="56cd0-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Relay
```

```bash
dotnet add package Microsoft.Azure.Relay
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="56cd0-112">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="56cd0-112">Explore the client APIs</span></span>](/dotnet/api/overview/azure/relay/client)

## <a name="samples"></a><span data-ttu-id="56cd0-113">サンプル</span><span class="sxs-lookup"><span data-stu-id="56cd0-113">Samples</span></span>

<span data-ttu-id="56cd0-114">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="56cd0-114">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package