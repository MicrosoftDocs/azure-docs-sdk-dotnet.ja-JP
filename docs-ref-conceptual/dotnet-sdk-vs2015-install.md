---
title: Azure Tools for Visual Studio 2015
description: "ツールを入手し、Visual Studio 2015 からの Azure .NET ライブラリの使用を始めてください。"
keywords: Azure .NET, SDK, VS2015, Visual Studio 2015
author: camsoper
manager: douge
ms.author: casoper
ms.date: 07/25/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.openlocfilehash: bee09801efd4f7291981bc85cd9c6a5d0b795b6e
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-tools-for-visual-studio-2015"></a>Azure Tools for Visual Studio 2015

**Azure SDK for Visual Studio 2015** および **Service Fabric SDK and Tools for Visual Studio 2015** をインストールする最も速くて簡単方法は、[Web Platform Installer](https://www.microsoft.com/web/downloads/platform.aspx) を使うことです。  Microsoft Web Platform Installer は無料ツールであり、Azure Tools for Visual Studio 2015 などの Microsoft Web Platform の一部のコンポーネントのダウンロード、インストール、更新を効率化します。  これらの SDK は、[Azure のダウンロード ページ](https://azure.microsoft.com/downloads/)から個別のコンポーネントとしてダウンロードしてインストールすることもできます。 

## <a name="using-the-web-platform-installer"></a>Web Platform Installer の使用

1. この [Web Platform Installer ブートストラッパー](https://www.microsoft.com/web/handlers/webpi.ashx?command=getinstallerredirect&appid=VWDOrVs2015AzurePack;MicrosoftAzure-ServiceFabric-VS2015)をダウンロードして実行します。  

2. ブートストラッパーは、(必要に応じて) Web Platform Installer をインストールし、**Azure SDK for Visual Studio 2015** および **Service Fabric SDK and Tools for Visual Studio 2015** 項目の最新バージョンを、"*インストールする項目*" のリストに自動的に追加します。  **[インストール]**をクリックします。

    ![Web Platform Installer](media/dotnet-sdk-vs2015-install/webpi.png)

3. 次の画面で、**[同意する]** をクリックします。  Web PI が、選択したコンポーネントのダウンロードとインストールを始めます。

4. インストールが完了すると、確認画面が表示されます。  **[完了]**をクリックします。  Web Platform Installer を閉じてかまいません。

## <a name="verifying-the-installation"></a>インストールの確認

1. Visual Studio 2015 で、**[ツール]** メニューの **[拡張機能と更新プログラム...]** をクリックします。

2. 表示される一覧には、**Microsoft Azure App Service Tools**、**Microsoft Azure Storage 接続済みサービス**、**Service Fabric Tools** など、複数の Azure ツールが含まれます。

    ![拡張機能と更新プログラム](media\dotnet-sdk-vs2015-install\ext-tools.png)

## <a name="next-steps"></a>次のステップ

[.NET 用 Azure ライブラリの概要](dotnet-sdk-azure-get-started.md)。
