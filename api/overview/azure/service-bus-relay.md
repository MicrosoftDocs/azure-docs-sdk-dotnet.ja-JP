---
title: .NET 用 Azure Service Bus Relay ライブラリ
description: .NET 用 Azure Service Bus Relay ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: service-bus-relay
ms.openlocfilehash: 9190e8efdebe1c352b4fb2c98be189089b0975d2
ms.sourcegitcommit: 1cf4550df8ed3236d838f561f6177d14d89b5e44
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2018
ms.locfileid: "49348124"
---
# <a name="azure-service-bus-relay-libraries-for-net"></a><span data-ttu-id="dc6ad-103">.NET 用 Azure Service Bus Relay ライブラリ</span><span class="sxs-lookup"><span data-stu-id="dc6ad-103">Azure Service Bus Relay libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="dc6ad-104">概要</span><span class="sxs-lookup"><span data-stu-id="dc6ad-104">Overview</span></span>

<span data-ttu-id="dc6ad-105">Azure Relay サービスでは、ファイアウォール接続の開放や企業ネットワーク インフラストラクチャの煩わしい変更を必要とせずに、企業のエンタープライズ ネットワーク内にあるサービスをパブリック クラウドに安全に公開できるハイブリッド アプリケーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="dc6ad-105">The Azure Relay service creates hybrid applications by enabling you to securely expose services that reside within a corporate enterprise network to the public cloud, without having to open a firewall connection, or require intrusive changes to a corporate network infrastructure.</span></span> <span data-ttu-id="dc6ad-106">Relay では、多様なトランスポート プロトコルと Web サービス標準がサポートされています。</span><span class="sxs-lookup"><span data-stu-id="dc6ad-106">Relay supports a variety of different transport protocols and web services standards.</span></span>
          
<span data-ttu-id="dc6ad-107">Azure Relay の詳細については、[こちら](/azure/service-bus-relay/relay-what-is-it)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="dc6ad-107">Learn more about [Azure Relay](/azure/service-bus-relay/relay-what-is-it).</span></span>

## <a name="client-library"></a><span data-ttu-id="dc6ad-108">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="dc6ad-108">Client library</span></span>

<span data-ttu-id="dc6ad-109">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Relay)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="dc6ad-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Relay) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="dc6ad-110">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="dc6ad-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Relay
```

```bash
dotnet add package Microsoft.Azure.Relay
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="dc6ad-111">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="dc6ad-111">Explore the client APIs</span></span>](/dotnet/api/overview/azure/relay/client)

## <a name="samples"></a><span data-ttu-id="dc6ad-112">サンプル</span><span class="sxs-lookup"><span data-stu-id="dc6ad-112">Samples</span></span>

<span data-ttu-id="dc6ad-113">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="dc6ad-113">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package