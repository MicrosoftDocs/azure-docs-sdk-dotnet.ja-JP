---
title: Azure .NET API
description: .NET 用 Azure API の概要
ms.date: 10/19/2017
ms.openlocfilehash: 04997caa99ed60db6ad98cabbc72b36bfbf99f4d
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190135"
---
# <a name="azure-net-apis"></a>Azure .NET API

Azure .NET API を使うと、アプリケーションのコードから Azure サービスを使ったり Azure リソースを管理したりできます。 API は、[NuGet パッケージ](/dotnet/api/overview/azure/)として .NET プロジェクトで使うことができます。 

## <a name="manage-azure-resources"></a>Azure のリソースを管理する

.NET 用 Azure ライブラリを使うと、.NET アプリケーションから Azure リソースを作成して管理できます。

Azure リソース管理用パッケージの多くは、指定したとおりに正確にリソースを構成するための [fluent](dotnet-sdk-azure-concepts.md) インターフェイスを備えています。 たとえば、Windows VM を作成するコードは、次のようになります。

```csharp
var windowsVM = azure.VirtualMachines.Define(windowsVmName)
    .WithRegion(Region.USEast)
    .WithNewResourceGroup(rgName)
    .WithNewPrimaryNetwork("10.0.0.0/28")
    .WithPrimaryPrivateIPAddressDynamic()
    .WithNewPrimaryPublicIPAddress(publicIpDnsLabel)
    .WithPopularWindowsImage(KnownWindowsVirtualMachineImage.WindowsServer2012R2Datacenter)
    .WithAdminUsername(username)
    .WithAdminPassword(password)
    .WithSize(VirtualMachineSizeTypes.StandardD3V2)
    .Create();
 ```

プロジェクトですぐにライブラリを使い始めるには、[.NET サービス リスト](/dotnet/api/overview/azure/)を確認してください。 その後、[使用開始の記事](dotnet-sdk-azure-get-started.md)を読み、認証を設定して、独自の Azure サブスクリプションに対してサンプル コードを実行します。  [概念記事](dotnet-sdk-azure-concepts.md)では、SDK で使われている規則と、それを使ってアプリケーションのコードを簡単にする方法が説明されています。 新機能、重大な変更、移行手順については、[リリース ノート](dotnet-sdk-azure-release-notes.md)をご覧ください。

## <a name="consume-azure-services"></a>Azure サービスを使う

.NET API を使うと、Azure 内のリソースを作成してプログラムで管理できるだけでなく、実行時にアプリケーションをリソースに接続してリソースを使うこともできます。  たとえば、SQL Database に接続したり、Azure Storage にデータを格納したりできます。  [サービス API の完全な一覧](/dotnet/api/overview/azure/)を参照すると、特定の Azure サービスに対して使う NuGet パッケージがわかります。  

## <a name="samples"></a>サンプル

次のサンプルでは、.NET 用 Azure ライブラリでの一般的なオートメーション タスクが示されています。

- [仮想マシン](dotnet-sdk-azure-virtual-machine-samples.md)
- [Web アプリ](dotnet-sdk-azure-web-apps-samples.md)
- [SQL Database](dotnet-sdk-azure-sql-database-samples.md)

サービス ライブラリと管理ライブラリのすべてのパッケージをまとめた[リファレンス](/dotnet/api/overview/azure/?view=azure-dotnet)が公開されています。 新機能、重大な変更、移行手順については、[リリース ノート](dotnet-sdk-azure-release-notes.md)をご覧ください。

[!include[Contribute and community](includes/contribute.md)]