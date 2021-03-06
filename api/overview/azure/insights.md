---
title: .NET 用 Azure Application Insights ライブラリ
description: .NET 用 Azure Application Insights ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: application-insights
ms.openlocfilehash: 10b65f536c6461959b0be9b8f9bd3ec56a307bea
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190841"
---
# <a name="azure-application-insights-libraries-for-net"></a>.NET 用 Azure Application Insights ライブラリ

## <a name="overview"></a>概要

Application Insights は、強力なアドホック分析機能を備えた、Web 開発者のための拡張可能な監視および診断サービスです。 ApplicationInsights 名前空間のクラスを使って、テレメトリのコレクションを構成したり、監視対象のアプリケーションからカスタム テレメトリを送信したりできます。

## <a name="client-library"></a>クライアント ライブラリ

.NET 用の Application Insights クライアント SDK を使うと、イベント、集計データ、例外、依存関係、メトリックを、後で分析できるように Azure に記録できます。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.ApplicationInsights )を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.ApplicationInsights 
```

```bash
dotnet add package Microsoft.ApplicationInsights 
```

### <a name="example"></a>例

この例では、Application Insights へのカスタム イベントを追跡します。

```csharp
TelemetryClient client = new TelemetryClient();
client.TrackEvent("MyCustomEvent");
```

> [!div class="nextstepaction"]
> [クライアント API を探す](/dotnet/api/overview/azure/insights/client)



## <a name="samples"></a>サンプル

- [OpenSchema での Application Insights の分析](https://azure.microsoft.com/resources/samples/guidance-appinsights-openschema/)

Azure Application Insights のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?service=application-insights&platform=dotnet)を表示します。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
