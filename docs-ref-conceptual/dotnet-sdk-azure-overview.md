---
title: Azure .NET API
description: ".NET 用 Azure API の概要"
keywords: "Azure, .NET, SDK, API, NuGet, ライブラリ, パッケージ"
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: cd0f8d6e0572fc9211af637e60d1a4f19e1ee1e8
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/23/2017
---
# <a name="azure-net-apis"></a><span data-ttu-id="7b0bf-104">Azure .NET API</span><span class="sxs-lookup"><span data-stu-id="7b0bf-104">Azure .NET APIs</span></span>

<span data-ttu-id="7b0bf-105">Azure .NET API を使うと、アプリケーションのコードから Azure サービスを使ったり Azure リソースを管理したりできます。</span><span class="sxs-lookup"><span data-stu-id="7b0bf-105">The Azure .NET APIs let you use Azure services and manage Azure resources from your application code.</span></span> <span data-ttu-id="7b0bf-106">API は、[NuGet パッケージ](/dotnet/api/overview/azure/)として .NET プロジェクトで使うことができます。</span><span class="sxs-lookup"><span data-stu-id="7b0bf-106">The APIs are available as [NuGet packages](/dotnet/api/overview/azure/) for use in your .NET projects.</span></span> 

## <a name="manage-azure-resources"></a><span data-ttu-id="7b0bf-107">Azure のリソースを管理する</span><span class="sxs-lookup"><span data-stu-id="7b0bf-107">Manage Azure resources</span></span>

<span data-ttu-id="7b0bf-108">.NET 用 Azure ライブラリを使うと、.NET アプリケーションから Azure リソースを作成して管理できます。</span><span class="sxs-lookup"><span data-stu-id="7b0bf-108">The Azure libraries for .NET let you create and manage Azure resources from your .NET applications.</span></span>

<span data-ttu-id="7b0bf-109">Azure リソース管理用パッケージの多くは、指定したとおりに正確にリソースを構成するための [fluent](dotnet-sdk-azure-concepts.md) インターフェイスを備えています。</span><span class="sxs-lookup"><span data-stu-id="7b0bf-109">Many of the packages for managing Azure resources have a [fluent](dotnet-sdk-azure-concepts.md) interface to configure resources exactly to your specifications.</span></span> <span data-ttu-id="7b0bf-110">たとえば、Windows VM を作成するコードは、次のようになります。</span><span class="sxs-lookup"><span data-stu-id="7b0bf-110">For example, to create a Windows VM you would write the following code:</span></span>

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

<span data-ttu-id="7b0bf-111">プロジェクトですぐにライブラリを使い始めるには、[.NET サービス リスト](/dotnet/api/overview/azure/)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="7b0bf-111">Review the [.NET service list](/dotnet/api/overview/azure/) to start using the libraries immediately with your projects.</span></span> <span data-ttu-id="7b0bf-112">その後、[使用開始の記事](dotnet-sdk-azure-get-started.md)を読み、認証を設定して、独自の Azure サブスクリプションに対してサンプル コードを実行します。</span><span class="sxs-lookup"><span data-stu-id="7b0bf-112">Then read the [get started article](dotnet-sdk-azure-get-started.md) to set up authentication and run sample code against your own Azure subscription.</span></span>  <span data-ttu-id="7b0bf-113">[概念記事](dotnet-sdk-azure-concepts.md)では、SDK で使われている規則と、それを使ってアプリケーションのコードを簡単にする方法が説明されています。</span><span class="sxs-lookup"><span data-stu-id="7b0bf-113">The [concepts article](dotnet-sdk-azure-concepts.md) goes into the conventions the SDK uses and how to leverage them to simplify your application code.</span></span> <span data-ttu-id="7b0bf-114">新機能、重大な変更、移行手順については、[リリース ノート](dotnet-sdk-azure-release-notes.md)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="7b0bf-114">New features, breaking changes, and migration instructions are available in the [release notes](dotnet-sdk-azure-release-notes.md).</span></span>

## <a name="consume-azure-services"></a><span data-ttu-id="7b0bf-115">Azure サービスを使う</span><span class="sxs-lookup"><span data-stu-id="7b0bf-115">Consume Azure services</span></span>

<span data-ttu-id="7b0bf-116">.NET API を使うと、Azure 内のリソースを作成してプログラムで管理できるだけでなく、実行時にアプリケーションをリソースに接続してリソースを使うこともできます。</span><span class="sxs-lookup"><span data-stu-id="7b0bf-116">In addition to using .NET APIs to create and programmatically manage resources within Azure, you can also then use .NET APIs to connect your applications to these resources and use them at runtime.</span></span>  <span data-ttu-id="7b0bf-117">たとえば、SQL Database に接続したり、Azure Storage にデータを格納したりできます。</span><span class="sxs-lookup"><span data-stu-id="7b0bf-117">For example, you might connect to a SQL Database or store data within Azure Storage.</span></span>  <span data-ttu-id="7b0bf-118">[サービス API の完全な一覧](/dotnet/api/overview/azure/)を参照すると、特定の Azure サービスに対して使う NuGet パッケージがわかります。</span><span class="sxs-lookup"><span data-stu-id="7b0bf-118">You can identify which NuGet package to use for a particular Azure service by browsing our [full list of service APIs](/dotnet/api/overview/azure/).</span></span>  

## <a name="samples"></a><span data-ttu-id="7b0bf-119">サンプル</span><span class="sxs-lookup"><span data-stu-id="7b0bf-119">Samples</span></span>

<span data-ttu-id="7b0bf-120">次のサンプルでは、.NET 用 Azure ライブラリでの一般的なオートメーション タスクが示されています。</span><span class="sxs-lookup"><span data-stu-id="7b0bf-120">The following samples cover common automation tasks with the Azure libraries for .NET:</span></span>

- [<span data-ttu-id="7b0bf-121">仮想マシン</span><span class="sxs-lookup"><span data-stu-id="7b0bf-121">Virtual machines</span></span>](dotnet-sdk-azure-virtual-machine-samples.md)
- [<span data-ttu-id="7b0bf-122">Web アプリ</span><span class="sxs-lookup"><span data-stu-id="7b0bf-122">Web apps</span></span>](dotnet-sdk-azure-web-apps-samples.md)
- [<span data-ttu-id="7b0bf-123">SQL Database</span><span class="sxs-lookup"><span data-stu-id="7b0bf-123">SQL Database</span></span>](dotnet-sdk-azure-sql-database-samples.md)

<span data-ttu-id="7b0bf-124">サービス ライブラリと管理ライブラリのすべてのパッケージをまとめた[リファレンス](/dotnet/api/overview/azure/?view=azure-dotnet)が公開されています。</span><span class="sxs-lookup"><span data-stu-id="7b0bf-124">A unified [reference](/dotnet/api/overview/azure/?view=azure-dotnet) is available for all packages in both the service and management libraries.</span></span> <span data-ttu-id="7b0bf-125">新機能、重大な変更、移行手順については、[リリース ノート](dotnet-sdk-azure-release-notes.md)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="7b0bf-125">New features, breaking changes, and migration instructions are available in the [release notes](dotnet-sdk-azure-release-notes.md).</span></span>

[!include[Contribute and community](includes/contribute.md)]