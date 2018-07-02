---
title: .NET 用 Azure Monitor ライブラリ
description: .NET 用 Azure Monitor ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Monitor
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/27/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 7b86b752a354b5ab6f8482b81ecba3b08b8a9442
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065882"
---
# <a name="azure-monitor-libraries-for-net"></a><span data-ttu-id="32289-104">.NET 用 Azure Monitor ライブラリ</span><span class="sxs-lookup"><span data-stu-id="32289-104">Azure Monitor libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="32289-105">概要</span><span class="sxs-lookup"><span data-stu-id="32289-105">Overview</span></span>

<span data-ttu-id="32289-106">Azure Monitor は、パフォーマンスの追跡、セキュリティの維持、傾向の把握に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="32289-106">Azure Monitor helps you track performance, maintain security, and identify trends.</span></span>

<span data-ttu-id="32289-107">詳細については、「[Azure Monitor の概要](/azure/monitoring-and-diagnostics/)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="32289-107">Learn more about [Azure Monitor](/azure/monitoring-and-diagnostics/).</span></span>   

## <a name="management-library"></a><span data-ttu-id="32289-108">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="32289-108">Management library</span></span>

<span data-ttu-id="32289-109">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Monitor.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="32289-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Monitor.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="32289-110">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="32289-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Monitor.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Monitor.Fluent
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="32289-111">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="32289-111">Explore the management APIs</span></span>](/dotnet/api/overview/azure/monitor/management)

## <a name="samples"></a><span data-ttu-id="32289-112">サンプル</span><span class="sxs-lookup"><span data-stu-id="32289-112">Samples</span></span>

<span data-ttu-id="32289-113">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="32289-113">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package