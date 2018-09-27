---
title: 適切な Azure ホスティング オプションの選択
description: ASP.NET Web アプリケーションに適した Azure への移行パスについて説明します。
author: CESARDELATORRE
ms.author: cesardl
ms.date: 11/15/2017
ms.openlocfilehash: 7c0d10436efa86c3d4a60f80e2eebd935ee01cee
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190615"
---
# <a name="choose-the-right-azure-hosting-option"></a>適切な Azure ホスティング オプションの選択

このドキュメントでは、既存の .NET Framework アプリケーションをオンプレミスから Azure に移行する際の考慮事項について説明し、Azure における複数の選択肢を比較します。

既存の .NET アプリケーションを Azure に移行する際に考慮すべき基本的な領域は次のとおりです。

1.  コンピューティングの選択肢
2.  データベースの選択肢
3.  ネットワークとセキュリティに関する考慮事項
4.  認証と承認に関する考慮事項

## <a name="compute-choices"></a>コンピューティングの選択肢

既存の .NET Framework アプリケーションを Azure に移行する場合、複数の選択肢があります。  ただし、.NET Framework は Windows に依存しているため、次の選択肢は Windows ベースのコンピューティング サービスに限定されます。

既存の .NET アプリケーションに適したコンピューティング移行パスの選択に役立つ、比較と推奨事項を次の表に示します。

|                 | Azure VM | Azure App Service | Windows コンテナー |
|-----------------|-----------|-------------------|--------------------|
|いつ使用するか      |<ul><li>アプリケーションに、サーバーとローカルの .msi インストール ファイルに対する強固な依存関係がある場合。</li><li>最も簡単なアプリケーション移行パスを必要としている場合。</li></ul>|アプリにサーバーに対する依存関係がなく、データベース サーバーにアクセスするクリーンな ASP.NET Web アプリ (MVC、WebForm) または N 層アプリ (Web API、WCf) である場合。 |<ul><li>アプリケーションに元のサーバーに対する依存関係があるが、それらの依存関係を Docker の Windows イメージに含めることができる場合。</li><li>アプリを最新化して、[クラウド DevOps 対応](https://docs.microsoft.com/dotnet/standard/modernize-with-azure-and-containers/lift-and-shift-existing-apps-devops/reasons-to-lift-and-shift-existing-net-apps-to-cloud-devops-ready-applications)にする場合。</li></ul>|
|長所  |<ul><li>最も簡単な移行パス。</li><li>使い慣れた環境。 デプロイ環境は、オンプレミス サーバーとほぼ同じ VM。</li></ul> |PaaS の継続的なメンテナンス、Azure でアプリを管理およびスケールする最も簡単な方法。 |<ul><li>将来に備えて、アプリのコンテナーに依存関係が含まれているクラウド DevOps 対応。</li><li>.NET/C# コードのリファクタリングがほとんど不要。</li></ul> |
|短所             |IaaS。 メンテナンスにコストがかかる。 ネットワーク、ロード バランサー、スケールアウト、IIS 管理などについて VM インフラストラクチャを管理する必要がある。 |<ul><li>すべてのアプリが[サポート](http://www.migratetoazure.net/ReadinessAssessment)されているわけではない。</li><li>一部のアプリでは、Azure App Service をサポートするために、リファクタリングと若干の再設計が必要。</li></ul> |<ul><li>Docker のスキルの学習曲線。</li><li>一部のコードとアプリ構成設定の変更。</li></ul>|
|必要条件 |オンプレミスのアプリと同じ要件の Windows Server VM | [Azure App Service の互換性の分析](https://www.migratetoazure.net/Resources)に関するページで指定されている Azure App Service の要件 |<ul><li>[Windows Server 2016 with Containers - Azure VM](https://azuremarketplace.microsoft.com/marketplace/apps/Microsoft.WindowsServer?tab=Overview)<br />or</li><li>[Azure Container Service (AKS)](https://azure.microsoft.com/services/container-service/) (Kubernetes オーケストレーター)<br />or<li>[Azure Service Fabric](https://azure.microsoft.com/services/service-fabric/) オーケストレーター</li></ul> |
|移行方法 |[Azure 仮想マシンへの移行](https://go.microsoft.com/fwlink/?linkid=862531)に関する記事を参照 | [Azure App Service](https://go.microsoft.com/fwlink/?linkid=862532) への移行に関する記事を参照 | [Azure と Windows コンテナーによる既存の .NET アプリの最新化に関する電子ブック](https://aka.ms/liftandshiftwithcontainersebook)で説明する考慮事項、シナリオ、チュートリアルを参照 |

 次のフローチャート図は、既存の .NET Framework アプリケーションの Azure への移行を計画する際のデシジョン ツリーを示しています。オプション A は実行可能な場合に最初に試してみるものであり、オプション B は最も実行しやすいパスです。

![ホスティングのデシジョン ツリーを示すフローチャート](media/dotnet-howto-choose-migration/decision-tree.png)

## <a name="database-choices"></a>データベースの選択肢

リレーショナル データベースを Azure に移行する場合、複数の選択肢があります。 既存の .NET アプリケーションに適したデータベース移行パスの選択については、[Azure への SQL Server データベースの移行](https://go.microsoft.com/fwlink/?linkid=862533)に関する記事をご覧ください。

## <a name="networking-and-security-considerations"></a>ネットワークとセキュリティに関する考慮事項

Microsoft Azure のようなパブリック クラウドにアプリケーションをデプロイする場合、[Azue とオンプレミスの間の DMZ](https://docs.microsoft.com/azure/architecture/reference-architectures/dmz/secure-vnet-hybrid) や、[Azure とインターネットの間の DMZ](https://docs.microsoft.com/azure/architecture/reference-architectures/dmz/secure-vnet-dmz) など、[ネットワーク DMZ を作成](https://docs.microsoft.com/azure/architecture/reference-architectures/dmz/)して特定のネットワークを分離し、セキュリティで保護することができます。 DMZ は、[Azure Virtual Network](https://docs.microsoft.com/azure/virtual-network/virtual-networks-overview) を使用して実装できます。
Azure Virtual Network を使用すると、次のことが可能になります。

- 制御可能なハイブリッド インフラストラクチャを構築する
- 独自の IP アドレスと DNS サーバーを使用する
- IPsec VPN または ExpressRoute を使用して接続をセキュリティで保護する
- サブネット間のトラフィックをきめ細かく制御する
- 仮想アプライアンスを使用して高度なネットワーク トポロジを作成する
- アプリケーション用に安全性の高い分離された環境を実現する
 
独自の仮想ネットワークの構築を開始するには、[Azure Virtual Network のドキュメント](https://docs.microsoft.com/azure/virtual-network/)に関するページをご覧ください。

## <a name="authentication-and-authorization-considerations-when-migrating-to-azure"></a>Azure に移行する際の認証と承認に関する考慮事項

クラウドに移行する組織の最大の懸念事項はセキュリティです。 ほとんどの企業が、セキュリティ モデルの設計と開発にかなりの時間、資金、エンジニアリングを投資しており、ID ストアやシングル サインオン ソリューションなどの既存の投資を活用できることが重要です。

オンプレミスで実行されている多くの既存のエンタープライズ B2E .NET アプリケーションでは、認証と ID 管理に Active Directory を使用しています。  Azure AD Connect を使用すると、オンプレミスのディレクトリを Azure Active Directory と統合できます。  作業を開始するには、「[オンプレミスのディレクトリと Azure Active Directory の統合](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect)」をご覧ください。

Azure Active Directory に関する詳細な計画については、[ハイブリッド ID ソリューションの ID 要件](https://docs.microsoft.com/azure/active-directory/active-directory-hybrid-identity-design-considerations-business-needs)に関する記事をご覧ください。

認証プロトコルの他の選択として、コンシューマー向けのアプリケーションで一般的な [OAuth](https://en.wikipedia.org/wiki/OAuth) と [OpenID](https://en.wikipedia.org/wiki/OpenID) があります。  OAuth を使用する IdentityServer4 によってラップされた ASP.NET Identity SQL データベースなど、自律的な ID データベースを使用する場合は、通常、オンプレミスのデータベースやディレクトリへの接続は不要です。

## <a name="next-steps"></a>次の手順

> [!div class="nextstepaction"]
> [Azure App Service への ASP.NET Web アプリケーションの移行](dotnet-howto-migrate-app-service.md)