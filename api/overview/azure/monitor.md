---
title: .NET 用 Azure Monitor ライブラリ
description: .NET 用 Azure Monitor ライブラリのリファレンス
ms.date: 10/27/2017
ms.topic: reference
ms.service: monitoring-alerts
ms.openlocfilehash: dbfeb845edf513cf2b4ce102ecdae7d008076641
ms.sourcegitcommit: 1cf4550df8ed3236d838f561f6177d14d89b5e44
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2018
ms.locfileid: "49348184"
---
# <a name="azure-monitor-libraries-for-net"></a><span data-ttu-id="afe8f-103">.NET 用 Azure Monitor ライブラリ</span><span class="sxs-lookup"><span data-stu-id="afe8f-103">Azure Monitor libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="afe8f-104">概要</span><span class="sxs-lookup"><span data-stu-id="afe8f-104">Overview</span></span>

<span data-ttu-id="afe8f-105">Azure Monitor は、パフォーマンスの追跡、セキュリティの維持、傾向の把握に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="afe8f-105">Azure Monitor helps you track performance, maintain security, and identify trends.</span></span>

<span data-ttu-id="afe8f-106">詳細については、「[Azure Monitor の概要](/azure/monitoring-and-diagnostics/)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="afe8f-106">Learn more about [Azure Monitor](/azure/monitoring-and-diagnostics/).</span></span>   

## <a name="management-library"></a><span data-ttu-id="afe8f-107">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="afe8f-107">Management library</span></span>

<span data-ttu-id="afe8f-108">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Monitor.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="afe8f-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Monitor.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="afe8f-109">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="afe8f-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Monitor.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Monitor.Fluent
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="afe8f-110">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="afe8f-110">Explore the management APIs</span></span>](/dotnet/api/overview/azure/monitor/management)

## <a name="samples"></a><span data-ttu-id="afe8f-111">サンプル</span><span class="sxs-lookup"><span data-stu-id="afe8f-111">Samples</span></span>

<span data-ttu-id="afe8f-112">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="afe8f-112">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package