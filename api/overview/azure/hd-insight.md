---
title: ".NET 用 Azure HDInsight ライブラリ"
description: ".NET 用 Azure HDInsight ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, HDInsight
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/14/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 0c45170c5a1e3acaeb36c0c17c1d5f2834dd375c
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-hdinsight-libraries-for-net"></a><span data-ttu-id="b5a5b-104">.NET 用 Azure HDInsight ライブラリ</span><span class="sxs-lookup"><span data-stu-id="b5a5b-104">Azure HDInsight libraries for .NET</span></span>

## <a name="management-library"></a><span data-ttu-id="b5a5b-105">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="b5a5b-105">Management library</span></span>

<span data-ttu-id="b5a5b-106">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="b5a5b-106">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="b5a5b-107">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="b5a5b-107">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.HDInsight
Install-Package Microsoft.Azure.Management.HDInsight.Job
```

```bash
dotnet add package Microsoft.Azure.Management.HDInsight
dotnet add package Microsoft.Azure.Management.HDInsight.Job
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="b5a5b-108">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="b5a5b-108">Explore the management APIs</span></span>](/dotnet/api/overview/azure/hdinsights/management)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
