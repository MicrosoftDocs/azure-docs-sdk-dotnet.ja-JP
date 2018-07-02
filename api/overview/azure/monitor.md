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
# <a name="azure-monitor-libraries-for-net"></a>.NET 用 Azure Monitor ライブラリ

## <a name="overview"></a>概要

Azure Monitor は、パフォーマンスの追跡、セキュリティの維持、傾向の把握に役立ちます。

詳細については、「[Azure Monitor の概要](/azure/monitoring-and-diagnostics/)」を参照してください。   

## <a name="management-library"></a>管理ライブラリ

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Monitor.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.Monitor.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Monitor.Fluent
```

> [!div class="nextstepaction"]
> [Management API を探す](/dotnet/api/overview/azure/monitor/management)

## <a name="samples"></a>サンプル

アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package