---
title: .NET 用 Azure Batch ライブラリ
description: .NET 用 Azure Batch ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Batch
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: batch
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 79ca70e5d0f3d5555c8a691da6dbcc1e6a55ab0b
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/23/2017
ms.locfileid: "23487265"
---
# <a name="azure-batch-libraries-for-net"></a><span data-ttu-id="115fa-104">.NET 用 Azure Batch ライブラリ</span><span class="sxs-lookup"><span data-stu-id="115fa-104">Azure Batch libraries for .NET</span></span>

<span data-ttu-id="115fa-105">Azure Batch は、大規模な並列コンピューティングやハイ パフォーマンス コンピューティング (HPC) のアプリケーションをクラウドで効率的に実行するためのプラットフォーム サービスです。</span><span class="sxs-lookup"><span data-stu-id="115fa-105">Azure Batch is a platform service for running large-scale parallel and high-performance computing (HPC) applications efficiently in the cloud.</span></span> <span data-ttu-id="115fa-106">多くのコンピューティング処理を要する作業を管理された仮想マシンの集合で実行するようにスケジュール設定し、ジョブのニーズに合わせてコンピューティング リソースを自動的に拡大/縮小できます。</span><span class="sxs-lookup"><span data-stu-id="115fa-106">Azure Batch schedules compute-intensive work to run on a managed collection of virtual machines, and can automatically scale compute resources to meet the needs of your jobs.</span></span>

<span data-ttu-id="115fa-107">Azure Batch では、複数のアプリケーションを並列で大規模に実行するための Azure コンピューティング リソースを簡単に定義できます。</span><span class="sxs-lookup"><span data-stu-id="115fa-107">With Azure Batch, you can easily define Azure compute resources to execute your applications in parallel, and at scale.</span></span> <span data-ttu-id="115fa-108">HPC クラスター、個々の仮想マシン、仮想ネットワークや、複雑なジョブとタスクのスケジュール インフラストラクチャを手動で作成、構成、管理する必要がありません。</span><span class="sxs-lookup"><span data-stu-id="115fa-108">There's no need to manually create, configure, and manage an HPC cluster, individual virtual machines, virtual networks, or a complex job and task scheduling infrastructure.</span></span> <span data-ttu-id="115fa-109">Azure Batch によって、これらのタスクが自動化または簡略化されます。</span><span class="sxs-lookup"><span data-stu-id="115fa-109">Azure Batch automates or simplifies these tasks for you.</span></span>

<span data-ttu-id="115fa-110">[Batch で並列ワークロードを本質的に実行する](/azure/batch/batch-technical-overview)方法をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="115fa-110">Read more about how to [run intrinsically parallel workloads with Batch](/azure/batch/batch-technical-overview).</span></span> <span data-ttu-id="115fa-111">[.NET 向け Batch クライアント ライブラリを使ってソリューション作成を開始する](/azure/batch/batch-dotnet-get-started)方法もご覧ください。</span><span class="sxs-lookup"><span data-stu-id="115fa-111">You can also learn how to [get started building solutions with the Batch client library for .NET](/azure/batch/batch-dotnet-get-started).</span></span> <span data-ttu-id="115fa-112">さらに、[.NET 用の Batch 管理クライアント ライブラリを使って Batch アカウントとクォータを管理する](/azure/batch/batch-management-dotnet)方法をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="115fa-112">Discover how to [manage Batch accounts and quotas with the Batch Management library for .NET](/azure/batch/batch-management-dotnet).</span></span>

## <a name="client-library"></a><span data-ttu-id="115fa-113">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="115fa-113">Client library</span></span>

<span data-ttu-id="115fa-114">Batch で並列ワークロードを実行するには、クライアント ライブラリを使います。</span><span class="sxs-lookup"><span data-stu-id="115fa-114">Use the client library to run parallel workloads with Batch.</span></span>

<span data-ttu-id="115fa-115">[NuGet パッケージ](https://www.nuget.org/packages/Azure.Batch)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="115fa-115">Install the [NuGet package](https://www.nuget.org/packages/Azure.Batch) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="115fa-116">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="115fa-116">Visual Studio Package Manager</span></span>

```powershell
Install-Package Azure.Batch
```

#### <a name="net-core-cli"></a><span data-ttu-id="115fa-117">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="115fa-117">.NET Core CLI</span></span>

```bash
dotnet add package Azure.Batch
```

### <a name="example"></a><span data-ttu-id="115fa-118">例</span><span class="sxs-lookup"><span data-stu-id="115fa-118">Example</span></span>

<span data-ttu-id="115fa-119">次の例では、クライアント SDK を使って、Azure Batch で実行するジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="115fa-119">The following example uses the client SDK to create a job to run in Azure Batch.</span></span>

```csharp
/*
using Microsoft.Azure.Batch.Auth;
using Microsoft.Azure.Batch;
*/
BatchSharedKeyCredentials credentials = new BatchSharedKeyCredentials(batchUrl, accountName, accountKey);
using (BatchClient batchClient = await BatchClient.OpenAsync(credentials))
{
    //set up pool specification and information along with resource files here
    JobManagerTask jobManagerTask = new JobManagerTask()
    {
        ResourceFiles = jobManagerResourceFiles,
        CommandLine = Constants.JobManagerExecutable,

        //Determines if the job should terminate when the job manager process exits.
        KillJobOnCompletion = true,
        Id = jobManagerTaskId
    };

    string jobId = Environment.GetEnvironmentVariable("USERNAME") + DateTime.UtcNow.ToString("yyyyMMdd-HHmmss");

    CloudJob unboundJob = batchClient.JobOperations.CreateJob(jobId, poolInformation);
    unboundJob.JobManagerTask = jobManagerTask;

    // now interact with the job ...
}
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="115fa-120">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="115fa-120">Explore the client APIs</span></span>](/dotnet/api/overview/azure/batch/client)

## <a name="management-library"></a><span data-ttu-id="115fa-121">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="115fa-121">Management library</span></span>

<span data-ttu-id="115fa-122">Batch アカウント、クォータ、およびアプリケーション パッケージをプログラムで管理するには、管理ライブラリを使います。</span><span class="sxs-lookup"><span data-stu-id="115fa-122">Use the management library to programmatically manage Batch accounts, quotas, and application packages.</span></span>

<span data-ttu-id="115fa-123">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Batch)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="115fa-123">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Batch) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="115fa-124">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="115fa-124">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Batch
```

#### <a name="net-core-cli"></a><span data-ttu-id="115fa-125">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="115fa-125">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.Batch
```

### <a name="example"></a><span data-ttu-id="115fa-126">例</span><span class="sxs-lookup"><span data-stu-id="115fa-126">Example</span></span>

<span data-ttu-id="115fa-127">次の例では、サブスクリプションのクォータを取得し、アカウントを作成して、プライマリ アカウント キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="115fa-127">The following example retrieves the quota for the subscription, creates an account, and regenerates the primary account key.</span></span>

```csharp
/*
using Microsoft.Azure.Management.Batch;
using Microsoft.Azure.Management.Batch.Models;
using Microsoft.Rest;
*/
using (BatchManagementClient batchManagementClient = new BatchManagementClient(new TokenCredentials(accessToken)))
{
    batchManagementClient.SubscriptionId = subscriptionId;

    // Get the account quota for the subscription
    BatchLocationQuota quotaResponse = await batchManagementClient.Location.GetQuotasAsync(location);
    Console.WriteLine("Your subscription can create {0} account(s) in the {1} region.", quotaResponse.AccountQuota, location);

    // Create account
    await batchManagementClient.BatchAccount.CreateAsync(ResourceGroupName, accountName, 
        new BatchAccountCreateParameters() { Location = location });

    // Regenerate primary account key
    BatchAccountKeys newKeys = await batchManagementClient.BatchAccount.RegenerateKeyAsync(
        ResourceGroupName, account.Name, AccountKeyType.Primary);
}
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="115fa-128">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="115fa-128">Explore the management APIs</span></span>](/dotnet/api/overview/azure/batch/management)

## <a name="samples"></a><span data-ttu-id="115fa-129">サンプル</span><span class="sxs-lookup"><span data-stu-id="115fa-129">Samples</span></span>

* [<span data-ttu-id="115fa-130">.NET サンプル用の Azure Batch クライアントおよび管理 SDK</span><span class="sxs-lookup"><span data-stu-id="115fa-130">Azure Batch Client and Management SDK for .NET Samples</span></span>](https://github.com/Azure/azure-batch-samples/tree/master/CSharp)

<span data-ttu-id="115fa-131">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="115fa-131">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
