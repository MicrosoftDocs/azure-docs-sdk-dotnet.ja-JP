---
title: "Azure への SQL Server データベースの移行"
description: "SQL Server データベースをオンプレミスの SQL Server から Azure に移行する方法について説明します。"
keywords: "Azure .NET, ASP.NET, SQL, SQL Server, SQL Database, 移行する, 移行"
author: camsoper
manager: wpickett
ms.author: casoper
ms.date: 11/15/2017
ms.topic: article
ms.technology: azure
ms.devlang: dotnet
ms.service: sql-database
ms.custom: devcenter
ms.openlocfilehash: d118d39e2168686c851f0daa6cb611f0a0c9d2fc
ms.sourcegitcommit: dbec35008347b581dd238b882354300e427bec70
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/02/2018
---
## <a name="migrate-a-sql-server-database-to-azure"></a><span data-ttu-id="bee40-104">SQL Server データベースを Azure に移行する</span><span class="sxs-lookup"><span data-stu-id="bee40-104">Migrate a SQL Server database to Azure</span></span>

<span data-ttu-id="bee40-105">この短い記事では、SQL Server データベースを Azure に移行するための 2 つのオプションについて概説します。</span><span class="sxs-lookup"><span data-stu-id="bee40-105">This short article provides a brief outline of two options for migrating a SQL Server database to Azure.</span></span>

<span data-ttu-id="bee40-106">Azure では、運用 SQL Server データベースを移行する際の主な選択肢として、次の 2 つがあります。</span><span class="sxs-lookup"><span data-stu-id="bee40-106">Azure has two primary options for migrating a production SQL Server database:</span></span>

1. <span data-ttu-id="bee40-107">[Azure VM の SQL Server](https://docs.microsoft.com/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-server-iaas-overview): Azure で 実行されている Windows 仮想マシンにインストールされ、ホストされている SQL Server インスタンス。これは、サービスとしてのインフラストラクチャ (IaaS) とも呼ばれます。</span><span class="sxs-lookup"><span data-stu-id="bee40-107">[SQL Server on Azure VMs](https://docs.microsoft.com/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-server-iaas-overview): A SQL Server instance installed and hosted on a Windows Virtual Machine running in Azure, also known as Infrastructure as a Service (IaaS).</span></span>
2. <span data-ttu-id="bee40-108">[Azure SQL Database](https://docs.microsoft.com/azure/sql-database/sql-database-technical-overview): 完全に管理された Azure SQL データベース サービス。これは、サービスとしてのプラットフォーム (PaaS) とも呼ばれます。</span><span class="sxs-lookup"><span data-stu-id="bee40-108">[Azure SQL Database](https://docs.microsoft.com/azure/sql-database/sql-database-technical-overview): A fully managed SQL database Azure service, also known as Platform as a Service (PaaS).</span></span>

<span data-ttu-id="bee40-109">それぞれに、移行前に評価する必要がある長所と短所があります。</span><span class="sxs-lookup"><span data-stu-id="bee40-109">Both come with pros and cons that you will need to evaluate before migrating.</span></span>

## <a name="get-started"></a><span data-ttu-id="bee40-110">作業開始</span><span class="sxs-lookup"><span data-stu-id="bee40-110">Get started</span></span>

<span data-ttu-id="bee40-111">使用するサービスによっては、次の移行ガイドが役立ちます。</span><span class="sxs-lookup"><span data-stu-id="bee40-111">The following migration guides will be useful, depending on which service you use:</span></span>

* [<span data-ttu-id="bee40-112">Azure VM の SQL Server への SQL Server データベースの移行</span><span class="sxs-lookup"><span data-stu-id="bee40-112">Migrate a SQL Server database to SQL Server in an Azure VM</span></span>](https://docs.microsoft.com/azure/virtual-machines/windows/sql/virtual-machines-windows-migrate-sql)
* [<span data-ttu-id="bee40-113">SQL Server データベースを Azure SQL Database に移行する</span><span class="sxs-lookup"><span data-stu-id="bee40-113">Migrate your SQL Server database to Azure SQL Database</span></span>](https://docs.microsoft.com/azure/sql-database/sql-database-migrate-your-sql-server-database)

<span data-ttu-id="bee40-114">さらに、概念説明への次のリンクが、VM の理解を深めるうえで役立ちます。</span><span class="sxs-lookup"><span data-stu-id="bee40-114">Additionally, the following links to conceptual content will help you understand VMs better:</span></span>

* [<span data-ttu-id="bee40-115">Azure 仮想マシンにおける SQL Server の高可用性とディザスター リカバリー</span><span class="sxs-lookup"><span data-stu-id="bee40-115">High availability and disaster recovery for SQL Server in Azure Virtual Machines</span></span>](https://docs.microsoft.com/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-high-availability-dr)
* [<span data-ttu-id="bee40-116">Azure Virtual Machines における SQL Server のパフォーマンスに関するベスト プラクティス</span><span class="sxs-lookup"><span data-stu-id="bee40-116">Performance best practices for SQL Server in Azure Virtual Machines</span></span>](https://docs.microsoft.com/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-performance)
* [<span data-ttu-id="bee40-117">Azure Virtual Machines における SQL Server のアプリケーション パターンと開発計画</span><span class="sxs-lookup"><span data-stu-id="bee40-117">Application Patterns and Development Strategies for SQL Server in Azure Virtual Machines</span></span>](https://docs.microsoft.com/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-server-app-patterns-dev-strategies)

<span data-ttu-id="bee40-118">次のリンクは、Azure SQL Database データベースの理解を深めるうえで役立ちます。</span><span class="sxs-lookup"><span data-stu-id="bee40-118">And the following links will help you understand Azure SQL Database better:</span></span>

* [<span data-ttu-id="bee40-119">Azure SQL Database のサーバーとデータベースを作成し、管理する</span><span class="sxs-lookup"><span data-stu-id="bee40-119">Create and manage Azure SQL Database servers and databases</span></span>](https://docs.microsoft.com/azure/sql-database/sql-database-servers-databases)
* [<span data-ttu-id="bee40-120">データベース トランザクション ユニット (DTU) とエラスティック データベース トランザクション ユニット (eDTU)</span><span class="sxs-lookup"><span data-stu-id="bee40-120">Database Transaction Units (DTUs) and elastic Database Transaction Units (eDTUs)</span></span>](https://docs.microsoft.com/azure/sql-database/sql-database-what-is-a-dtu)
* [<span data-ttu-id="bee40-121">Azure SQL Database のリソース制限</span><span class="sxs-lookup"><span data-stu-id="bee40-121">Azure SQL Database resource limits</span></span>](https://docs.microsoft.com/azure/sql-database/sql-database-resource-limits)

## <a name="choosing-iaas-or-paas"></a><span data-ttu-id="bee40-122">IaaS または PaaS の選択</span><span class="sxs-lookup"><span data-stu-id="bee40-122">Choosing IaaS or PaaS</span></span>

<span data-ttu-id="bee40-123">データベースの移行先を評価する際に、IaaS または PaaS のどちらがより適切かを判断する必要があります。</span><span class="sxs-lookup"><span data-stu-id="bee40-123">When evaluating where to migrate your database, you should determine if IaaS or PaaS is more appropriate for you.</span></span>

<span data-ttu-id="bee40-124">次のような場合は、**Azure VM の SQL Server** を選択します。</span><span class="sxs-lookup"><span data-stu-id="bee40-124">**You should choose SQL Server in Azure VMs if:**</span></span>

* <span data-ttu-id="bee40-125">変更を最小限に抑えて、データベースとアプリケーションを "リフトアンドシフト" する場合。</span><span class="sxs-lookup"><span data-stu-id="bee40-125">You are looking to "lift and shift" your database and applications with minimal to no changes.</span></span>
* <span data-ttu-id="bee40-126">データベース サーバーとそのサーバーが実行される VM を完全に制御する場合。</span><span class="sxs-lookup"><span data-stu-id="bee40-126">You prefer having full control over your database server and the VM it runs on.</span></span>
* <span data-ttu-id="bee40-127">使用する SQL Server および Windows Server のライセンスが既にある場合。</span><span class="sxs-lookup"><span data-stu-id="bee40-127">You already have SQL Server and Windows Server licenses that you intend to use.</span></span>

<span data-ttu-id="bee40-128">次のような場合は、**Azure SQL Database** を選択します。</span><span class="sxs-lookup"><span data-stu-id="bee40-128">**You should choose Azure SQL Database if:**</span></span>

* <span data-ttu-id="bee40-129">アプリケーションを最新化し、Azure の他の PaaS サービスを使用するために移行する場合。</span><span class="sxs-lookup"><span data-stu-id="bee40-129">You are looking to modernize your applications and are migrating to use other PaaS services in Azure.</span></span>
* <span data-ttu-id="bee40-130">データベース サーバーとそのサーバーが実行される VM を管理するのは望ましくない場合。</span><span class="sxs-lookup"><span data-stu-id="bee40-130">You do not wish to manage your database server and the VM it runs on.</span></span>
* <span data-ttu-id="bee40-131">SQL Server または Windows Server のライセンスがない場合、または現在のライセンスを期限切れにする場合。</span><span class="sxs-lookup"><span data-stu-id="bee40-131">You do not have SQL Server or Windows Server licenses, or you intend to let licenses you have expire.</span></span>

<span data-ttu-id="bee40-132">一連のシナリオに基づく各サービスの違いを次の表に示します。</span><span class="sxs-lookup"><span data-stu-id="bee40-132">The following table describes differences between each service based on a set of scenarios.</span></span>

| <span data-ttu-id="bee40-133">シナリオ</span><span class="sxs-lookup"><span data-stu-id="bee40-133">Scenario</span></span> | <span data-ttu-id="bee40-134">Azure VM の SQL Server</span><span class="sxs-lookup"><span data-stu-id="bee40-134">SQL Server in Azure VMs</span></span> | <span data-ttu-id="bee40-135">の接続文字列</span><span class="sxs-lookup"><span data-stu-id="bee40-135">Azure SQL Database</span></span> |
|----------|-------------------------|--------------------|
| <span data-ttu-id="bee40-136">移行</span><span class="sxs-lookup"><span data-stu-id="bee40-136">Migration</span></span> | <span data-ttu-id="bee40-137">データベースの最小限の変更が必要です。</span><span class="sxs-lookup"><span data-stu-id="bee40-137">Requires minimal changes to your database.</span></span> | <span data-ttu-id="bee40-138">[Data Migration Assistant](https://www.microsoft.com/download/details.aspx?id=53595) によって Azure SQL で利用できないと判断された機能を使用する場合や、ローカルにインストールされた実行可能ファイルなどの他の依存関係がある場合、データベースの変更が必要になることがあります。</span><span class="sxs-lookup"><span data-stu-id="bee40-138">May require changes to your database if you use features unavailable in Azure SQL, as determined by the [Data Migration Assistant](https://www.microsoft.com/download/details.aspx?id=53595), or if you have other dependencies such as locally installed executables.</span></span>|
| <span data-ttu-id="bee40-139">可用性、復旧、アップグレードの管理</span><span class="sxs-lookup"><span data-stu-id="bee40-139">Managing availability, recovery, and upgrades</span></span> | <span data-ttu-id="bee40-140">可用性と復旧は手動で構成します。</span><span class="sxs-lookup"><span data-stu-id="bee40-140">Availability and recovery is configured manually.</span></span> <span data-ttu-id="bee40-141">アップグレードは、[VM Scale Sets](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-automatic-upgrade) を使用して自動化できます。</span><span class="sxs-lookup"><span data-stu-id="bee40-141">Upgrades can be automated with [VM Scale Sets](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-automatic-upgrade).</span></span> | <span data-ttu-id="bee40-142">自動的に管理されます。</span><span class="sxs-lookup"><span data-stu-id="bee40-142">Automatically managed for you.</span></span> |
| <span data-ttu-id="bee40-143">基になる OS 構成</span><span class="sxs-lookup"><span data-stu-id="bee40-143">Underlying OS configuration</span></span> | <span data-ttu-id="bee40-144">手動で構成します。</span><span class="sxs-lookup"><span data-stu-id="bee40-144">Manual configuration.</span></span> | <span data-ttu-id="bee40-145">自動的に管理されます。</span><span class="sxs-lookup"><span data-stu-id="bee40-145">Automatically managed for you.</span></span> |
| <span data-ttu-id="bee40-146">データベース サイズの管理</span><span class="sxs-lookup"><span data-stu-id="bee40-146">Managing database size</span></span> | <span data-ttu-id="bee40-147">SQL Server インスタンスごとに最大 64 TB のストレージをサポートします。</span><span class="sxs-lookup"><span data-stu-id="bee40-147">Supports up to 64TB of storage per SQL Server instance.</span></span> | <span data-ttu-id="bee40-148">行方向のパーティション分割が必要になるまでに 4 TB のストレージをサポートします。</span><span class="sxs-lookup"><span data-stu-id="bee40-148">Supports 4TB of storage before needing a horizontal partition.</span></span> |
| <span data-ttu-id="bee40-149">コストの管理</span><span class="sxs-lookup"><span data-stu-id="bee40-149">Managing costs</span></span> | <span data-ttu-id="bee40-150">SQL Server ライセンスのコスト、Windows Server ライセンスのコスト、VM のコスト (コア数、RAM、ストレージに基づく) を管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="bee40-150">You must manage SQL Server license costs, Windows Server license costs, and VM costs (based on cores, RAM, and storage).</span></span> | <span data-ttu-id="bee40-151">([eDTU または DTU](https://docs.microsoft.com/azure/sql-database/sql-database-what-is-a-dtu)、ストレージ、データベースの数 (エラスティック プールを使用している場合) に基づいて) サービス コストを管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="bee40-151">You must manage service costs (based on [eDTUs or DTUs](https://docs.microsoft.com/azure/sql-database/sql-database-what-is-a-dtu), storage, and number of databases if using an elastic pool).</span></span>  <span data-ttu-id="bee40-152">また、SLA のコストも管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="bee40-152">You must also manage the cost of any SLA.</span></span> |

<span data-ttu-id="bee40-153">この 2 つの違いの詳細については、クラウド SQL Server オプション ([Azure SQL Database または Azure VM の SQL Server](https://docs.microsoft.com/azure/sql-database/sql-database-paas-vs-sql-server-iaas)) の選択に関する記事をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="bee40-153">To learn more about the differences between the two, read Choose a cloud SQL Server option: [Azure SQL Database or SQL Server on Azure VMs](https://docs.microsoft.com/azure/sql-database/sql-database-paas-vs-sql-server-iaas).</span></span>

## <a name="faq"></a><span data-ttu-id="bee40-154">FAQ</span><span class="sxs-lookup"><span data-stu-id="bee40-154">FAQ</span></span>

* <span data-ttu-id="bee40-155">**SQL Server Management Studio や SQL Server Reporting Services (SSRS) などのツールは、Azure VM の SQL Server または Azure SQL Database で引き続き使用できますか?**</span><span class="sxs-lookup"><span data-stu-id="bee40-155">**Can I still use tools such as SQL Server Management Studio and SQL Server Reporting Services (SSRS) with SQL Server in Azure VMs or Azure SQL Database?**</span></span>

    <span data-ttu-id="bee40-156">はい。</span><span class="sxs-lookup"><span data-stu-id="bee40-156">Yes!</span></span> <span data-ttu-id="bee40-157">Microsoft SQL ツールはすべてどちらのサービスでも機能します。</span><span class="sxs-lookup"><span data-stu-id="bee40-157">All Microsoft SQL tooling works with both services.</span></span> <span data-ttu-id="bee40-158">SSRS は Azure SQL Database には含まれていませんが、このツールを Azure VM で実行し、データベース インスタンスを参照することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="bee40-158">SSRS is not part of Azure SQL Database, though, and it's recommended that you run it in an Azure VM and then point it to your database instance.</span></span>
    
* <span data-ttu-id="bee40-159">**PaaS に移行したいのですが、データベースに互換性があるのかどうかがわかりません。役立つツールはありますか?**</span><span class="sxs-lookup"><span data-stu-id="bee40-159">**I want to go PaaS but I'm not sure if my database is compatible. Are there tools to help?**</span></span>

    <span data-ttu-id="bee40-160">はい。</span><span class="sxs-lookup"><span data-stu-id="bee40-160">Yes.</span></span> <span data-ttu-id="bee40-161">[Data Migration Assistant](https://www.microsoft.com/download/details.aspx?id=53595) は、Azure SQL Database への移行の一環として使用されるツールです。</span><span class="sxs-lookup"><span data-stu-id="bee40-161">The [Data Migration Assistant](https://www.microsoft.com/download/details.aspx?id=53595) is a tool that is used as a part of migrating to Azure SQL Database.</span></span>  <span data-ttu-id="bee40-162">[Azure Database Migration Service](https://azure.microsoft.com/campaigns/database-migration/) は、IaaS または PaaS で使用できるプレビュー サービスです。</span><span class="sxs-lookup"><span data-stu-id="bee40-162">The [Azure Database Migration Service](https://azure.microsoft.com/campaigns/database-migration/) is a preview service which you can use for either IaaS or PaaS.</span></span>

* <span data-ttu-id="bee40-163">**コストを見積もることはできますか?**</span><span class="sxs-lookup"><span data-stu-id="bee40-163">**Can I estimate costs?**</span></span>

    <span data-ttu-id="bee40-164">はい。</span><span class="sxs-lookup"><span data-stu-id="bee40-164">Yes.</span></span>  <span data-ttu-id="bee40-165">[Azure 料金計算ツール](https://azure.microsoft.com/pricing/calculator/)を使用して、VM やデータベース サービスなど、すべての Azure サービスのコストを見積もることができます。</span><span class="sxs-lookup"><span data-stu-id="bee40-165">The [Azure Pricing Calculator](https://azure.microsoft.com/pricing/calculator/) can be used for estimating costs for all Azure services, including VMs and database services.</span></span>
    
## <a name="next-steps"></a><span data-ttu-id="bee40-166">次の手順</span><span class="sxs-lookup"><span data-stu-id="bee40-166">Next steps</span></span>

> [!div class="nextstepaction"]
> [<span data-ttu-id="bee40-167">適切な Azure ホスティング オプションの選択</span><span class="sxs-lookup"><span data-stu-id="bee40-167">Choose the right Azure hosting option</span></span>](dotnet-howto-choose-migration.md)
