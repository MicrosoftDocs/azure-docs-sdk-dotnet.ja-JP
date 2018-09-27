---
title: .NET 用 Azure StorSimple ライブラリ
description: .NET 用 Azure StorSimple ライブラリのリファレンス
ms.date: 10/27/2017
ms.topic: reference
ms.service: storsimple
ms.openlocfilehash: ecaa1acb0d988f7312645c2e6ed8f3289e51237c
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190365"
---
# <a name="azure-storsimple-libraries-for-net"></a><span data-ttu-id="f3bd1-103">.NET 用 Azure StorSimple ライブラリ</span><span class="sxs-lookup"><span data-stu-id="f3bd1-103">Azure StorSimple libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="f3bd1-104">概要</span><span class="sxs-lookup"><span data-stu-id="f3bd1-104">Overview</span></span>

<span data-ttu-id="f3bd1-105">Microsoft Azure StorSimple は、クラウドベースのストレージに物理的な iSCSI または SMB インターフェイスを提供するエンタープライズ ストレージ ソリューションです。</span><span class="sxs-lookup"><span data-stu-id="f3bd1-105">Microsoft Azure StorSimple is an enterprise storage solution that provides physical iSCSI or SMB interfaces to cloud-based storage.</span></span> 

<span data-ttu-id="f3bd1-106">[Azure StorSimple](/azure/storsimple/) の詳細を確認してください。</span><span class="sxs-lookup"><span data-stu-id="f3bd1-106">Learn more about [Azure StorSimple](/azure/storsimple/).</span></span>    

## <a name="management-library"></a><span data-ttu-id="f3bd1-107">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="f3bd1-107">Management library</span></span>

<span data-ttu-id="f3bd1-108">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.StorSimple.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="f3bd1-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.StorSimple.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="f3bd1-109">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="f3bd1-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.StorSimple.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.StorSimple.Fluent
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="f3bd1-110">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="f3bd1-110">Explore the management APIs</span></span>](/dotnet/api/overview/azure/monitor/management)

## <a name="samples"></a><span data-ttu-id="f3bd1-111">サンプル</span><span class="sxs-lookup"><span data-stu-id="f3bd1-111">Samples</span></span>

<span data-ttu-id="f3bd1-112">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="f3bd1-112">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package