---
title: ".NET 用 Azure Service Bus Relay ライブラリ"
description: ".NET 用 Azure Service Bus Relay ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Service Bus Relay
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/14/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 13a875b837648a05401453e975c9cd70d5e203a1
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-service-bus-relay-libraries-for-net"></a>.NET 用 Azure Service Bus Relay ライブラリ

## <a name="overview"></a>概要

Azure Relay サービスでは、ファイアウォール接続の開放や企業ネットワーク インフラストラクチャの煩わしい変更を必要とせずに、企業のエンタープライズ ネットワーク内にあるサービスをパブリック クラウドに安全に公開できるハイブリッド アプリケーションを作成します。 Relay では、多様なトランスポート プロトコルと Web サービス標準がサポートされています。
          
Azure Relay の詳細については、[こちら](https://docs.microsoft.com/en-us/azure/service-bus-relay/relay-what-is-it)をご覧ください。

## <a name="client-library"></a>クライアント ライブラリ

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Relay)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Relay
```

```bash
dotnet add package Microsoft.Azure.Relay
```

> [!div class="nextstepaction"]
> [クライアント API を探す](/dotnet/api/overview/azure/relay/client)

## <a name="samples"></a>サンプル

アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package