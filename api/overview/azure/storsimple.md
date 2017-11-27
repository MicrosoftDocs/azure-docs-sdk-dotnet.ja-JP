---
title: ".NET 用 Azure StorSimple ライブラリ"
description: ".NET 用 Azure StorSimple ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, StorSimple
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/27/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: storsimple
ms.custom: devcenter, svc-overview
ms.openlocfilehash: dcb6732bf1eded6852a3185546a09c96cfe84eca
ms.sourcegitcommit: 64c9e16e42894e8db8ed088487e55c5e0edd6861
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/31/2017
---
# <a name="azure-storsimple-libraries-for-net"></a><span data-ttu-id="3b8a1-104">.NET 用 Azure StorSimple ライブラリ</span><span class="sxs-lookup"><span data-stu-id="3b8a1-104">Azure StorSimple libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="3b8a1-105">概要</span><span class="sxs-lookup"><span data-stu-id="3b8a1-105">Overview</span></span>

<span data-ttu-id="3b8a1-106">Microsoft Azure StorSimple は、クラウドベースのストレージに物理的な iSCSI または SMB インターフェイスを提供するエンタープライズ ストレージ ソリューションです。</span><span class="sxs-lookup"><span data-stu-id="3b8a1-106">Microsoft Azure StorSimple is an enterprise storage solution that provides physical iSCSI or SMB interfaces to cloud-based storage.</span></span> 

<span data-ttu-id="3b8a1-107">[Azure StorSimple](/azure/storsimple/) の詳細を確認してください。</span><span class="sxs-lookup"><span data-stu-id="3b8a1-107">Learn more about [Azure StorSimple](/azure/storsimple/).</span></span>    

## <a name="management-library"></a><span data-ttu-id="3b8a1-108">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="3b8a1-108">Management library</span></span>

<span data-ttu-id="3b8a1-109">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.StorSimple.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="3b8a1-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.StorSimple.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="3b8a1-110">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="3b8a1-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.StorSimple.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.StorSimple.Fluent
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="3b8a1-111">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="3b8a1-111">Explore the management APIs</span></span>](/dotnet/api/overview/azure/monitor/management)

## <a name="samples"></a><span data-ttu-id="3b8a1-112">サンプル</span><span class="sxs-lookup"><span data-stu-id="3b8a1-112">Samples</span></span>

<span data-ttu-id="3b8a1-113">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="3b8a1-113">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package