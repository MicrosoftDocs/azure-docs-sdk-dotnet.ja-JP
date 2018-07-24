---
title: Azure .NET および .NET Core 開発者向けツール
description: Windows、Linux、Mac 環境から Azure .NET ライブラリを使い始めるためのツールを入手します。
keywords: Azure .NET, SDK, Azure .NET API リファレンス, Azure .NET クラス ライブラリ
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 07/17/2018
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: 9c9d25e8f065408f81ed8b1fdb25817196f7e053
ms.sourcegitcommit: 779c1b202d3670cfa0b9428c89f830cad9ec7e9d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2018
ms.locfileid: "39135700"
---
# <a name="tools-for-net-and-net-core-azure-developers"></a>.NET および .NET Core Azure 開発者向けツール

お使いのオペレーティング システムが何であっても、.NET、.NET Core、ASP.NET、ASP.NET Core を使用した Azure での開発に役立つ一連の優れたツールが用意されています。

## <a name="windowstabwindows"></a>[Windows](#tab/windows)

<table>
  <tr>
    <td width="50">
        <img src="https://docs.microsoft.com/en-us/media/logos/logo_vs-ide.svg" width="50" height="50"></img>
    </td>
    <td>
        Visual Studio 2017 には、Azure 開発の組み込みサポートがあります。
    </td>
  </tr>
</table>

### <a name="step-1-download-visual-studio-2017"></a>ステップ 1: Visual Studio 2017 をダウンロードする

Visual Studio 2017 を既にインストールしてある場合は省略できます。

まだ Visual Studio 2015 をお使いの場合は、  [こちらをクリックしてインストール手順に従ってください](dotnet-sdk-vs2015-install.md)。

> [!div class="nextstepaction"]
> [Visual Studio 2017 をダウンロードする](https://www.visualstudio.com/downloads/)

### <a name="step-2-install-the-two-azure-workloads"></a>ステップ 2: 2 つの Azure ワークロードをインストールする

Visual Studio 2017 インストーラーを起動した後、Azure と ASP.NET Web の開発ワークロードがオンになっていることを確認します。

![Visual Studio インストーラー](media/dotnet-tools/azure-workloads.png)

### <a name="step-3-develop-with-net-on-azure"></a>ステップ 3: Azure で .NET を使って開発する

まず、[最初の ASP.NET Core Web アプリを Azure App Service にデプロイ](https://docs.microsoft.com/azure/app-service-web/app-service-web-get-started-dotnet)します。

## <a name="macostabmacos"></a>[macOS](#tab/macos)
<table>
  <tr>
    <td width="50">
        <img src="https://docs.microsoft.com/en-us/media/logos/logo_vs-mac.svg" width="50" height="50"></img>
    </td>
    <td>
        Visual Studio for Mac には、Azure での開発に必要なすべてのものが揃っています。
    </td>
  </tr>
</table>

### <a name="step-1-download-visual-studio-for-mac"></a>ステップ 1: Visual Studio for Mac をダウンロードする

> [!div class="nextstepaction"]
> [Visual Studio for Mac をダウンロードする](https://www.visualstudio.com/vs/visual-studio-mac/)

Azure ツールは、インストールの間に既定で有効になります。

![Visual Studio for Mac インストーラー](media/dotnet-tools/azure-vsmac.png)

## <a name="linuxtablinux"></a>[Linux](#tab/linux)

<img src="https://docs.microsoft.com/en-us/visualstudio/products/images/vs-code.svg" width="50" height="50"></img>

### <a name="step-1-download-the-net-core-sdk"></a>ステップ 1: .NET Core SDK をダウンロードする

.NET Core アプリ用の SDK とコマンド ライン ツールです。

> [!div class="nextstepaction"]
> [.NET Core SDK をダウンロードする](https://www.microsoft.com/net/core)

### <a name="step-2-visual-studio-code"></a>ステップ 2: Visual Studio Code

任意のオペレーティング システム (Windows、Mac、Linux) 上で .NET Core アプリを編集し、デバッグします。

> [!div class="nextstepaction"]
> [Visual Studio Code をダウンロードする](https://code.visualstudio.com)
