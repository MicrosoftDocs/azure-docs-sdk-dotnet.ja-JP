---
title: .NET 用 Azure Traffic Manager ライブラリ
description: .NET 用 Azure Traffic Manager ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: traffic-manager
ms.openlocfilehash: a75b5c566496f73475d24d62288a00c7d5775168
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190824"
---
# <a name="azure-traffic-manager-libraries-for-net"></a>.NET 用 Azure Traffic Manager ライブラリ

## <a name="overview"></a>概要

Microsoft Azure Traffic Manager では、さまざまなデータセンターのサービス エンドポイントへのユーザー トラフィックの分散を制御できます。 Traffic Manager でサポートされるサービス エンドポイントには、Azure VM、Web Apps、およびクラウド サービスが含まれます。 Azure 以外の外部エンドポイントで Traffic Manager を使用することもできます。

Azure Traffic Manager の詳細については、[こちら](/azure/traffic-manager/traffic-manager-overview)をご覧ください。  

## <a name="management-library"></a>管理ライブラリ

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.TrafficManager.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.TrafficManager.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.TrafficManager.Fluent
```

> [!div class="nextstepaction"]
> [Management API を探す](/dotnet/api/overview/azure/trafficmanager/management)

## <a name="samples"></a>サンプル

アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package