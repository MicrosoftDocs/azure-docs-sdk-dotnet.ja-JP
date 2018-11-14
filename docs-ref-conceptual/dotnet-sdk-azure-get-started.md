---
title: Azure と .NET を使用して作業を開始する
description: Azure と .NET について知っておくべき基本的事項について説明します。
ms.date: 09/19/2018
ms.openlocfilehash: 63587d7d5ccb79eee47185ff1f3ccb9cbd09c0ea
ms.sourcegitcommit: 0de939648fa01698016fed633200f8eb07c96eb7
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/08/2018
ms.locfileid: "51276582"
---
# <a name="get-started-with-azure-and-net"></a>Azure と .NET を使用して作業を開始する

このドキュメントでは、Azure サービスを使用してアプリの開発を始めるために .NET 開発者が知っておく必要がある主要な概念とサービスの概要を説明します。

## <a name="key-concepts"></a>主要な概念

**Azure アカウント**: Azure アカウントは、Azure サービス ([Azure portal](https://portal.azure.com) や [Cloud Shell](https://shell.azure.com) など) にサインインする際に使用する資格情報です。 Azure アカウントがない場合は、[アカウントを無料で作成](https://azure.microsoft.com/free/dotnet/)できます。

**Azure サブスクリプション**: サブスクリプションとは、Azure リソースを作成する際の料金プランです。 サブスクリプションには、個人用サブスクリプションと会社が管理するエンタープライズ サブスクリプションがあります。 Azure アカウントは複数のサブスクリプションに関連付けることができます。 この場合、リソースの作成時に適切なサブスクリプションを選択する必要があります。 詳細については、「[アカウント、サブスクリプション、課金の概要](https://docs.microsoft.com/azure/guides/developer/azure-developer-guide#understanding-accounts-subscriptions-and-billing)」をご覧ください。

> [!TIP]
> Visual Studio サブスクリプションをお持ちの場合は、[月単位の Azure クレジットをアクティブにする](https://azure.microsoft.com/pricing/member-offers/credit-for-visual-studio-subscribers/)ことができます。

**リソース グループ**: リソース グループを使用すると、管理のために Azure リソースをグループにまとめることができます。 コンピューター上のフォルダーにファイルを保存するのと同様に、Azure で作成されたリソースは、リソース グループに保存されます。

**ホスティング**: Azure でコードを実行するには、ユーザー指定のコードの実行をサポートするサービスでホストされている必要があります。

**マネージド サービス**: Azure には、ユーザーがデータや情報を Azure に提供するためのサービスが用意されており、Azure の実装によって適切なアクションが実行されます。 一例として Azure Blob Storage があります。このサービスでは、ユーザーがファイルを提供すると、Azure によってそれらの読み取り、書き込み、永続化が処理されます。

## <a name="choosing-a-hosting-option"></a>ホスティング オプションの選択

Azure でのホスティングは、3 つのカテゴリに分けることができます。

* **サービスとしてのインフラストラクチャ (IaaS)**: IaaS を使用して、関連付けられているネットワークおよびストレージ コンポーネントと共に、必要な仮想マシンをプロビジョニングします。 その後、必要なソフトウェアとアプリケーションをそれらの VM にデプロイします。 このモデルは従来のオンプレミス環境に最も近いものですが、Microsoft がインフラストラクチャを管理する点が異なります。 オペレーティング システム、カスタム ソフトウェア、セキュリティ更新プログラムなど、個々の VM は引き続きユーザーが管理します。

* **サービスとしてのプラットフォーム (PaaS)**: PaaS は、管理されたホスティング環境を提供します。この環境では、VM やネットワーク リソースを管理せずにアプリケーションをデプロイできます。 たとえば、個々の VM を作成するのではなく、インスタンス数を指定すると、サービスによって、必要なリソースがプロビジョニング、構成、および管理されます。 Azure App Service は PaaS サービスの例です。
  
* **サービスとしての関数 (FaaS)**: 一般に "サーバーレス コンピューティング" と呼ばれる FaaS は、PaaS よりもさらに先を行き、ホスティング環境に関する懸念を取り除きます。 コンピューティング インスタンスを作成し、それらのインスタンスにコードをデプロイするのではなく、コードをデプロイすると、サービスによってコードが自動的に実行されます。 コンピューティング リソースを管理する必要はありません。 プラットフォームによって、トラフィックを処理するために必要なレベルに、コードがシームレスにスケールアップまたはスケールダウンされ、コードの実行時間にのみ課金されます。 Azure Functions は FaaS サービスの 1 つです。

一般に、アプリケーションで FaaS モデルや PaaS モデルが重視されるようになると、クラウドでの実行によって得られるメリットが増えます。 Azure における 3 つの一般的なホスティングの選択肢とそれらを選ぶ状況の概要を次に示します。

* [Azure App Service](https://docs.microsoft.com/azure/app-service/app-service-value-prop-what-is): Web アプリケーションまたはサービスをホストする場合は、まず App Service を検討します。 App Service と ASP.NET、WCF、ASP.NET Core の各アプリを使った作業を開始する場合は、「[Azure に ASP.NET Core Web アプリを作成する](https://docs.microsoft.com/azure/app-service/app-service-web-get-started-dotnet)」をご覧ください。

* [Azure Functions](https://docs.microsoft.com/azure/azure-functions/functions-overview): Azure Functions はイベント ドリブン ワークフローに最適です。 例として、Webhook への応答、キューまたは Blob Storage 内の項目の処理、タイマーなどがあります。 Azure Functions を使った作業を開始する場合は、「[Visual Studio を使用して初めての関数を作成する](https://docs.microsoft.com/azure/azure-functions/functions-create-your-first-function-visual-studio)」をご覧ください。

* [Azure Virtual Machines](https://docs.microsoft.com/azure/virtual-machines/): 特定の依存関係のため、App Service では既存のアプリケーションのホスティングのニーズが満たされない場合は、Virtual Machines が最も簡単な出発点となります。 Virtual Machines と ASP.NET または WCF を使った作業を開始する場合は、「[Deploy an ASP.NET app to an Azure virtual machine (ASP.NET アプリを Azure 仮想マシンにデプロイする)](https://tutorials.visualstudio.com/aspnet-vm/intro)」をご覧ください。

> [!TIP]
> Azure サービスの詳細な一覧については、「[Azure コンピューティング オプションの概要](https://docs.microsoft.com/azure/architecture/guide/technology-choices/compute-overview#azure-compute-options)」をご覧ください。 サービスの選択の詳細については、「[Azure コンピューティング サービスのデシジョン ツリー](https://docs.microsoft.com/azure/architecture/guide/technology-choices/compute-decision-tree)」をご覧ください。

## <a name="choosing-a-data-storage-service"></a>データ ストレージ サービスの選択

Azure には、ニーズに応じてデータを格納するための複数のサービスが用意されています。 .NET 開発者向けの最も一般的なデータ サービスを次に示します。

* [Azure SQL Database](https://docs.microsoft.com/azure/sql-database/): SQL Server を既に使用しているアプリケーションをクラウドに移行する場合は、Azure SQL Database が自然な出発点です。 作業を開始するには、「[チュートリアル: SQL Database を使用して Azure に ASP.NET アプリを作成する](https://docs.microsoft.com/azure/app-service/app-service-web-tutorial-dotnet-sqldatabase)」をご覧ください。

* [Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/): Azure Cosmos DB は、クラウド向けに設計された最新のデータベースです。 特定のデータベース依存関係がまだない新しいアプリケーションを開始する場合は、Azure Cosmos DB を検討してください。 Cosmos DB は、自動スケール、予測可能なパフォーマンス、高速応答時間、スキーマレスなデータのクエリを実行できることが重要である、新しい Web、モバイル、ゲーム、IoT の各アプリケーションに適しています。 作業を開始するには、「[クイック スタート: SQL API と Azure Portal を使って Azure Cosmos DB による .NET Web アプリを作る](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet)」をご覧ください。

* [Azure Blob Storage](https://docs.microsoft.com/azure/storage/): Azure Blob Storage は、画像、ファイル、ストリームなどの大きなバイナリ オブジェクトの格納と取得に最適化されています。 オブジェクト ストアにより、大量の非構造化データの管理が可能になります。 作業を開始するには、「[Quickstart: Use .NET to create a blob in object storage (クイック スタート: .NET を使用してオブジェクト ストレージに BLOB を作成する)](https://docs.microsoft.com/azure/storage/blobs/storage-quickstart-blobs-dotnet)」をご覧ください。

> [!TIP]
> 詳細については、「[適切なデータ ストアの選択](https://docs.microsoft.com/azure/architecture/guide/technology-choices/data-store-overview)」をご覧ください。

## <a name="connecting-to-azure-services"></a>Azure サービスへの接続

Visual Studio を使用する場合は、特定の Azure サービスのサポートをプロジェクトに追加できます。  Visual Studio の **[接続済みサービス]** ダイアログを使用すると、必要な参照、接続コード、および構成設定をプロジェクトに簡単に追加できます。  よく使用される一部の Azure サービス ([Storage](/azure/vs-azure-tools-connected-services-storage)、[Azure Active Directory](/azure/active-directory/develop/vs-active-directory-add-connected-service) 認証、[Azure Key Vault](/azure/key-vault/vs-key-vault-add-connected-service)、([Computer Vision](/azure/cognitive-services/computer-vision/vs-computer-vision-connected-service) を含む) [Cognitive Services](/azure/cognitive-services/) など) は、すぐ使えるようにサポートされています。  サード パーティのサービスを含むその他のサービスは、拡張機能として [Visual Studio Marketplace](https://marketplace.visualstudio.com/search?term=connected%20service&target=VS&category=Tools&vsVersion=&subCategory=All&sortBy=Relevance) で入手できます。

## <a name="diagnosing-problems-in-the-cloud"></a>クラウドでの問題の診断
アプリケーションを Azure にデプロイした後、開発環境では動作していても、Azure では動作しない状況に遭遇することがあります。 問題を診断するときは、まず次の 2 つを使用することをお勧めします。

* **Visual Studio からのリモート デバッグ**: (このドキュメントで説明するサービスを含め) ほとんどの Azure コンピューティング サービスでは、Visual Studio を使用したリモート デバッグとログの取得がサポートされています。 アプリケーションで Visual Studio の機能を調べるには、Visual Studio のクイック起動ツール バー (右上隅) に「Cloud Explorer」と入力して、Cloud Explorer ツール ウィンドウを開き、ツリーで目的のアプリケーションを見つけます。 詳細については、[Visual Studio を使用した Azure App Service の Web アプリのトラブルシューティング](https://docs.microsoft.com/azure/app-service/web-sites-dotnet-troubleshoot-visual-studio#remotedebug)に関するページをご覧ください。

* **Application Insights**: [Application Insights](https://docs.microsoft.com/azure/application-insights/) は、診断データ、テレメトリ、パフォーマンス データをアプリケーションから自動的に取り込む、完全なアプリケーション パフォーマンス監視 (APM) ソリューションです。 アプリの診断データの収集を開始するには、「[ASP.NET Web アプリケーションの監視を開始する](https://docs.microsoft.com/azure/application-insights/quick-monitor-portal)」をご覧ください。

## <a name="next-steps"></a>次の手順

* [Azure に最初の ASP.NET Core Web アプリをデプロイする](https://docs.microsoft.com/azure/app-service/app-service-web-get-started-dotnet)
* [.NET 用 Azure API での認証の詳細を確認する](dotnet-sdk-azure-authenticate.md)
* [クラウド アプリのエラーを診断する](https://blogs.msdn.microsoft.com/webdev/2018/02/07/diagnosing-errors-on-your-cloud-apps)
* [.NET 開発者向けの Azure クイック スタート ガイド](https://www.microsoft.com/net/download/thank-you/azure-quick-start-ebook) (無料の電子書籍) をダウンロードする
