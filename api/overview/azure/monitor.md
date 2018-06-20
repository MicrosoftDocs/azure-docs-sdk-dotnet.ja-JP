---
title: .NET 用 Azure Monitor ライブラリ
description: .NET 用 Azure Monitor ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Monitor
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/27/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 8055b8861f6991e021ff1ea3bfa87cf96f554fa2
ms.sourcegitcommit: 64c9e16e42894e8db8ed088487e55c5e0edd6861
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/31/2017
ms.locfileid: "23639640"
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