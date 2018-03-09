---
title: "Azure App Service への ASP.NET Web アプリケーションの移行"
description: "ASP.NET Web アプリケーションをオンプレミスから Azure App Service に移行する方法について説明します。"
keywords: "Azure .NET, ASP.NET, App Service, Web アプリ, 移行する, 移行"
author: camsoper
manager: wpickett
ms.author: casoper
ms.date: 11/15/2017
ms.topic: article
ms.technology: azure
ms.devlang: dotnet
ms.service: app-service
ms.custom: devcenter
ms.openlocfilehash: 050782871c3fe4ccb0d15bf9933c3b11c88ce661
ms.sourcegitcommit: dbec35008347b581dd238b882354300e427bec70
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/02/2018
---
# <a name="migrate-an-aspnet-web-application-to-azure-app-service"></a>Azure App Service への ASP.NET Web アプリケーションの移行

[App Service](https://docs.microsoft.com/azure/app-service/app-service-web-overview#why-use-web-apps) は、スケーラブルな Web サイトと Web アプリケーションをホストするために最適化された、完全に管理されたコンピューティング プラットフォーム サービスです。 このドキュメントでは、既存のアプリケーションを Azure App Service にリフトアンドシフトする方法、考慮すべき変更、クラウドへの移行に関するその他のリソースについて説明します。

使い始める準備はできていますか。 [ASP.NET および SQL アプリケーションを Azure App Service に発行](https://go.microsoft.com/fwlink/?linkid=863214)します。

# <a name="preparation"></a>準備   
* [アプリが App Service に適しているかどうかを判断する方法](https://azure.microsoft.com/downloads/migration-assistant/)
* [クラウドへのデータベースの移行](https://go.microsoft.com/fwlink/?linkid=863217)

# <a name="considerations"></a>考慮事項
アプリケーションを移行する前に、考慮する必要がある要素がいくつかあります。 アプリケーションに必要となる可能性のある変更とその方法を以下に示します。

## <a name="sql-database-configuration"></a>SQL Database の構成
アプリケーションがオンプレミス データベースを使用している場合、Web アプリ用のオプションがいくつかあります。 Azure への SQL Database の移行の詳細については、[こちら](https://go.microsoft.com/fwlink/?linkid=863217)をご覧ください。

## <a name="iis"></a>IIS
従来、アプリケーションの applicationHost.config で構成していたあらゆるものを、Azure Portal で構成できるようになりました。 AppPool のビット、WebSocket の有効化/無効化、マネージ パイプライン バージョン、.NET Framework バージョン (2.0/4.0) などがこれに該当します。[アプリケーション設定](https://docs.microsoft.com/azure/app-service/web-sites-configure)を変更するには、[Azure Portal](https://portal.azure.com) に移動し、Web アプリのブレードを開いて、**[アプリケーションの設定]** タブを選択します。

## <a name="authentication"></a>認証
アプリケーションがいずれかの時点でユーザーを認証する場合、アプリケーションを Azure Web Apps にデプロイした後に動作するように、この機能を変更する必要があります。 考えられる 1 つの方法として、Azure AD Connect を使用して、オンプレミスのディレクトリを Azure Active Directory と統合します。 オンプレミスのディレクトリを Azure Active Directory と統合する方法の詳細については、[こちら](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect)をご覧ください。

## <a name="virtual-network-modification"></a>仮想ネットワークの変更
複数の Azure サービスを使用する場合は、それらのサービス間で安全に通信するために仮想ネットワークの使用を検討します。 VPN または ExpressRoute を使用して、オンプレミス ネットワークから [Azure Virtual Network](https://docs.microsoft.com/azure/app-service/web-sites-integrate-with-vnet) への接続を構成できます。

## <a name="monitoring-and-diagnostics"></a>Monitoring and Diagnostics
監視と診断に現在使用しているオンプレミスのソリューションは、クラウドでは機能しない可能性があります。 ただし、Web アプリでの問題を特定し、デバッグできるように、Azure には、ログ記録、監視、診断用のツールが用意されています。 Web アプリの診断は、アプリの構成で簡単に有効にすることができます。また、記録されたログは、Azure Application Insights で表示できます。 Web アプリの診断ログの有効化の詳細については、[こちら](https://docs.microsoft.com/azure/app-service/web-sites-enable-diagnostic-log)をご覧ください。

## <a name="connection-strings-and-application-settings"></a>接続文字列とアプリケーション設定
情報を保護する 1 つの方法として、[Azure KeyVault](https://docs.microsoft.com/azure/key-vault/) を使用します。これは、アプリケーションで使用される機密情報を安全に格納するサービスです。 また、このデータを App Service 設定として保存することもできます。

## <a name="dns"></a>DNS
アプリケーションの要件に基づいて、DNS 構成を更新することが必要な場合があります。 これらの DNS 設定は、App Service の[カスタム ドメイン設定](https://docs.microsoft.com/azure/app-service/app-service-web-tutorial-custom-domain)で構成できます。 考慮すべきもう 1 つの要素は、[既存のカスタム SSL 証明書のバインド](https://docs.microsoft.com/azure/app-service/app-service-web-tutorial-custom-ssl)です。

## <a name="file-system-and-storage"></a>ファイル システムとストレージ
アプリケーションでデータを保持する場合は、代わりに Azure Storage を使用するようにアプリケーションを更新する必要があります。 Azure Storage は、SMB プロトコル、Blob Storage、単純キュー、非リレーショナル テーブルを使用した共有のためのファイル共有を提供するサービスです。 Azure Storage のファイル共有の詳細については、[こちら](https://docs.microsoft.com/azure/storage/files/storage-files-introduction)をご覧ください。

## <a name="next-steps"></a>次の手順

> [!div class="nextstepaction"]
> [Azure App Service への ASP.NET Web アプリケーションの移行](https://aka.ms/azure-webapp-migrate)
