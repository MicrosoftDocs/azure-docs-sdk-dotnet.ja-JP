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
# <a name="azure-storsimple-libraries-for-net"></a>.NET 用 Azure StorSimple ライブラリ

## <a name="overview"></a>概要

Microsoft Azure StorSimple は、クラウドベースのストレージに物理的な iSCSI または SMB インターフェイスを提供するエンタープライズ ストレージ ソリューションです。 

[Azure StorSimple](/azure/storsimple/) の詳細を確認してください。    

## <a name="management-library"></a>管理ライブラリ

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.StorSimple.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.StorSimple.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.StorSimple.Fluent
```

> [!div class="nextstepaction"]
> [Management API を探す](/dotnet/api/overview/azure/monitor/management)

## <a name="samples"></a>サンプル

アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package