---
title: "Azure 仮想マシンへの ASP.NET Web アプリケーションの移行"
description: "ASP.NET Web アプリケーションをオンプレミスから Azure 仮想マシンに移行する方法について説明します。"
keywords: "Azure .NET, ASP.NET, VM, 仮想マシン, 移行する, 移行"
author: camsoper
manager: wpickett
ms.author: casoper
ms.date: 11/15/2017
ms.topic: article
ms.technology: azure
ms.devlang: dotnet
ms.service: virtual-machines
ms.custom: devcenter
ms.openlocfilehash: 718d91b98180a7584f78a2383d430c4700743306
ms.sourcegitcommit: c360a22d5bff6eedd714b28b847d2f26b06665f4
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/15/2017
---
# <a name="migrate-an-aspnet-web-application-to-an-azure-virtual-machine"></a><span data-ttu-id="8ca7a-104">Azure 仮想マシンへの ASP.NET Web アプリケーションの移行</span><span class="sxs-lookup"><span data-stu-id="8ca7a-104">Migrate an ASP.NET Web application to an Azure Virtual Machine</span></span>

<span data-ttu-id="8ca7a-105">このドキュメントでは、ASP.NET Web アプリケーションをオンプレミスから Azure 仮想マシンに移行する方法の概要を説明します。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-105">This document provides an overview of how to migrate an ASP.NET web application from on-premises to an Azure Virtual Machine.</span></span>

## <a name="get-started"></a><span data-ttu-id="8ca7a-106">作業の開始</span><span class="sxs-lookup"><span data-stu-id="8ca7a-106">Get Started</span></span>

<span data-ttu-id="8ca7a-107">次のチュートリアルでは、仮想マシンを作成 (または移行) する手順、Web アプリケーションを発行する手順、Azure でアプリケーションをサポートするために必要なその他のタスクについて説明しています。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-107">These tutorials demonstrate the steps to create (or migrate) a virtual machine, publish your web application to it, and other tasks that may be required to support your application in Azure.</span></span>

- <span data-ttu-id="8ca7a-108">次の 2 つの方法のいずれかを使用して、Azure に ASP.NET アプリケーション用の仮想マシンを作成します。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-108">Create a virtual machine for your ASP.NET application in Azure using one of the following two options:</span></span>
    - [<span data-ttu-id="8ca7a-109">ASP.NET アプリケーション用の新しい仮想マシンを作成する</span><span class="sxs-lookup"><span data-stu-id="8ca7a-109">Create a new virtual machine for ASP.NET Applications</span></span>](https://go.microsoft.com/fwlink/?linkid=863237)
    - [<span data-ttu-id="8ca7a-110">オンプレミスの既存の仮想マシンを移行する</span><span class="sxs-lookup"><span data-stu-id="8ca7a-110">Migrate an existing on-premises virtual machine</span></span>](https://docs.microsoft.com/azure/site-recovery/tutorial-migrate-on-premises-to-azure)
- [<span data-ttu-id="8ca7a-111">Visual Studio を使用してアプリを発行する</span><span class="sxs-lookup"><span data-stu-id="8ca7a-111">Publish your app using Visual Studio</span></span>](https://go.microsoft.com/fwlink/?linkid=863240)
- [<span data-ttu-id="8ca7a-112">VM 用のセキュリティで保護された仮想ネットワークを作成する</span><span class="sxs-lookup"><span data-stu-id="8ca7a-112">Create a secure virtual network for your VMs</span></span>](https://docs.microsoft.com/azure/virtual-network/virtual-network-get-started-vnet-subnet)
- [<span data-ttu-id="8ca7a-113">アプリケーションの CI/CD パイプラインを作成する</span><span class="sxs-lookup"><span data-stu-id="8ca7a-113">Create a CI/CD pipeline for your application</span></span>](https://docs.microsoft.com/vsts/build-release/apps/cd/deploy-webdeploy-iis-deploygroups)
- [<span data-ttu-id="8ca7a-114">高可用性とスケーラビリティを確保するために VM スケール セットに移行する</span><span class="sxs-lookup"><span data-stu-id="8ca7a-114">Move to a VM scale set for high availability and scalability</span></span>](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-deploy-app)

## <a name="considerations"></a><span data-ttu-id="8ca7a-115">考慮事項</span><span class="sxs-lookup"><span data-stu-id="8ca7a-115">Considerations</span></span>

### <a name="benefits"></a><span data-ttu-id="8ca7a-116">メリット</span><span class="sxs-lookup"><span data-stu-id="8ca7a-116">Benefits</span></span>

<span data-ttu-id="8ca7a-117">仮想マシンを使用すると、アプリケーションをオンプレミスからクラウドに最も簡単に移行できます。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-117">Virtual machines offer the easiest path to migrate an application from on-premises to the cloud.</span></span>  <span data-ttu-id="8ca7a-118">仮想マシンを使用することで、アプリケーションがオンプレミスで使用している環境をレプリケートできると同時に、独自のデータ センターを管理する必要性が排除されます。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-118">They enable you to replicate the same environment your application uses on-premises, while removing the need to maintain your own data centers.</span></span>  <span data-ttu-id="8ca7a-119">Virtual Machine Scale Sets は、Virtual Machines で実行されているアプリケーションの高可用性とスケーラビリティを実現します。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-119">Virtual Machine Scale Sets provide high availability and scalability for applications running in Virtual Machines.</span></span>

### <a name="virtual-machine-size"></a><span data-ttu-id="8ca7a-120">仮想マシンのサイズ</span><span class="sxs-lookup"><span data-stu-id="8ca7a-120">Virtual Machine Size</span></span>

<span data-ttu-id="8ca7a-121">ワークロードに最も最適化された仮想マシンのサイズと種類を選択します。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-121">Choose the virtual machine size and type that is best optimized for your workload.</span></span>  <span data-ttu-id="8ca7a-122">詳細については、「[Azure の Windows 仮想マシンのサイズ](https://docs.microsoft.com/azure/virtual-machines/windows/sizes)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-122">See [sizes for Windows virtual machines in Azure](https://docs.microsoft.com/azure/virtual-machines/windows/sizes) for more information.</span></span>

### <a name="maintenance"></a><span data-ttu-id="8ca7a-123">メンテナンス </span><span class="sxs-lookup"><span data-stu-id="8ca7a-123">Maintenance</span></span>

<span data-ttu-id="8ca7a-124">オンプレミス コンピューターと同様に、仮想マシンの管理と更新はユーザーが行う必要があります<sup>&#42;</sup>。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-124">Just like an on-premises machine, you are responsible for maintaining and updating the virtual machine<sup>&#42;</sup>.</span></span>  <span data-ttu-id="8ca7a-125">[Azure App Service](https://docs.microsoft.com/azure/app-service/) や[コンテナー](https://docs.microsoft.com/azure/app-service/containers/)などのサービスとしてのプラットフォーム (PaaS) 環境でアプリケーションを実行できる場合、その必要はなくなります。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-125">If your application can run in a Platform as a Service (PaaS) environment such as [Azure App Service](https://docs.microsoft.com/azure/app-service/) or in a [container](https://docs.microsoft.com/azure/app-service/containers/), that will remove this need.</span></span>

<span data-ttu-id="8ca7a-126">*<sup>&#42;</sup>[仮想マシン スケール セットの OS の自動アップグレード](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-automatic-upgrade)は、現在、プレビュー サービスとして提供されています。*</span><span class="sxs-lookup"><span data-stu-id="8ca7a-126">*<sup>&#42;</sup>[Automatic OS upgrades for virtual machine scale sets](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-automatic-upgrade) is currently available as a Preview service.*</span></span>

### <a name="virtual-networks"></a><span data-ttu-id="8ca7a-127">Virtual Networks</span><span class="sxs-lookup"><span data-stu-id="8ca7a-127">Virtual Networks</span></span>

<span data-ttu-id="8ca7a-128">Azure Virtual Network を使用すると、次のことが可能になります。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-128">Azure Virtual Networks enable you to:</span></span>
- <span data-ttu-id="8ca7a-129">制御可能なハイブリッド インフラストラクチャを構築する</span><span class="sxs-lookup"><span data-stu-id="8ca7a-129">Build a hybrid infrastructure that you control</span></span>
- <span data-ttu-id="8ca7a-130">独自の IP アドレスと DNS サーバーを使用する</span><span class="sxs-lookup"><span data-stu-id="8ca7a-130">Bring your own IP addresses and DNS servers</span></span>
- <span data-ttu-id="8ca7a-131">アプリケーション用に安全性の高い分離された環境を作成する</span><span class="sxs-lookup"><span data-stu-id="8ca7a-131">Create an isolated and highly-secure environment for your applications</span></span>
- <span data-ttu-id="8ca7a-132">複数の[接続オプション](https://docs.microsoft.com/azure/vpn-gateway/vpn-gateway-about-vpngateways#s2smulti)のいずれかを使用して、VM をオンプレミス ネットワークに接続する</span><span class="sxs-lookup"><span data-stu-id="8ca7a-132">Connect your VM to your on-premises network using one of several [connectivity options](https://docs.microsoft.com/azure/vpn-gateway/vpn-gateway-about-vpngateways#s2smulti)</span></span>
- <span data-ttu-id="8ca7a-133">[ExpressRoute](https://azure.microsoft.com/services/expressroute/) を使用して、仮想マシンをオンプレミス ネットワークに統合する</span><span class="sxs-lookup"><span data-stu-id="8ca7a-133">Integrate your virtual machine into your on-premises network using [ExpressRoute](https://azure.microsoft.com/services/expressroute/)</span></span>

<span data-ttu-id="8ca7a-134">作業を開始するには、「[Virtual Network のドキュメント](https://docs.microsoft.com/azure/virtual-network/)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-134">To get started, see the [Virtual Network documentation](https://docs.microsoft.com/azure/virtual-network/)</span></span>

### <a name="active-directory"></a><span data-ttu-id="8ca7a-135">Active Directory</span><span class="sxs-lookup"><span data-stu-id="8ca7a-135">Active Directory</span></span>
<span data-ttu-id="8ca7a-136">多くのアプリケーションでは、認証と ID 管理に Active Directory を使用しています。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-136">Many applications use Active Directory for authentication and identity management.</span></span>  
- <span data-ttu-id="8ca7a-137">Azure AD Connect を使用すると、オンプレミスのディレクトリを Azure Active Directory と統合できます。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-137">Azure AD Connect enables you to integrate your on-premises directories with Azure Active Directory.</span></span>  <span data-ttu-id="8ca7a-138">作業を開始するには、「[オンプレミスのディレクトリと Azure Active Directory の統合](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-138">To get started, see [Integrate your on-premises directories with Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect).</span></span>  
- <span data-ttu-id="8ca7a-139">[ExpressRoute](https://azure.microsoft.com/services/expressroute/) を使用すると、アプリケーションはオンプレミスの Active Directory にアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-139">Alternatively, [ExpressRoute](https://azure.microsoft.com/services/expressroute/) enables your application to access your on-premises Active Directory.</span></span>

### <a name="sql-databases"></a><span data-ttu-id="8ca7a-140">[SQL データベース]</span><span class="sxs-lookup"><span data-stu-id="8ca7a-140">SQL Databases</span></span>

<span data-ttu-id="8ca7a-141">アプリケーションがオンプレミス データベースを使用している場合、既定ではアプリはデータベースと対話できません。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-141">If your application is using an on-premises database, your app will not be able to talk to it by default.</span></span> <span data-ttu-id="8ca7a-142">次のいずれかを実行できます。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-142">You can either:</span></span>
- <span data-ttu-id="8ca7a-143">アプリケーションがオンプレミスで実行されているデータベースにアクセスできるようにするためのハイブリッド ネットワークを構成する。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-143">Configure a hybrid network that enables your application to access your database running on-premises.</span></span>  
- <span data-ttu-id="8ca7a-144">データベースを Azure に移行する。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-144">Migrate your database to the Azure.</span></span>  <span data-ttu-id="8ca7a-145">詳細については、[Azure への SQL Server データベースの移行](dotnet-howto-migrate-sql.md)に関する記事をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-145">See [Migrate your SQL Server database to Azure](dotnet-howto-migrate-sql.md) for more information.</span></span>

### <a name="high-availability-and-scalability"></a><span data-ttu-id="8ca7a-146">高可用性とスケーラビリティ</span><span class="sxs-lookup"><span data-stu-id="8ca7a-146">High Availability and Scalability</span></span>

#### <a name="virtual-machine-scale-sets"></a><span data-ttu-id="8ca7a-147">Virtual Machine Scale Sets</span><span class="sxs-lookup"><span data-stu-id="8ca7a-147">Virtual Machine Scale Sets</span></span>
<span data-ttu-id="8ca7a-148">アプリケーションの高可用性とスケーラビリティを確保する場合、VM イメージを Azure 仮想マシン スケール セットに移行すると、アプリケーションの可用性とスケーラビリティが向上します。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-148">You want to make sure that your application is highly available and can scale, migrate your VM image to an Azure Virtual Machine Scale Set to improve the availability and scalability of your application.</span></span>  <span data-ttu-id="8ca7a-149">VM Scale Sets では、構成済みの既存の VM を使用したり、アプリケーションでイメージをビルドするためのビルド パイプラインを設定したりできます。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-149">VM Scale Sets provide the ability to use an existing VM you’ve already configured or set up a build pipeline to build an image with your application.</span></span>  

<span data-ttu-id="8ca7a-150">作業を開始するには、「[仮想マシン スケール セットへのアプリケーションのデプロイ](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-deploy-app)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-150">To get started, see [Deploy your application on virtual machine scale sets](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-deploy-app).</span></span>

#### <a name="centralized-logging"></a><span data-ttu-id="8ca7a-151">ログの一元化</span><span class="sxs-lookup"><span data-stu-id="8ca7a-151">Centralized Logging</span></span>
<span data-ttu-id="8ca7a-152">複数のインスタンスでアプリケーションを実行する場合は、[Azure Storage](https://docs.microsoft.com/azure/storage/) などの一元化された場所にログを保存することを検討します。</span><span class="sxs-lookup"><span data-stu-id="8ca7a-152">When running your application across multiple instances, consider storing your logs in a centralized location such as [Azure Storage](https://docs.microsoft.com/azure/storage/).</span></span>

## <a name="next-steps"></a><span data-ttu-id="8ca7a-153">次のステップ</span><span class="sxs-lookup"><span data-stu-id="8ca7a-153">Next steps</span></span>

> [!div class="nextstepaction"]
> [<span data-ttu-id="8ca7a-154">Azure への SQL Server データベースの移行</span><span class="sxs-lookup"><span data-stu-id="8ca7a-154">Migrate a SQL Server database to Azure</span></span>](dotnet-howto-migrate-sql.md)