---
title: .NET 用 Azure HDInsight ライブラリ
description: .NET 用 Azure HDInsight ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, HDInsight
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: hd-insight
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 2cdb080b4d224a77a36318cefd13ebfae2e3e2e1
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065812"
---
# <a name="azure-hdinsight-libraries-for-net"></a><span data-ttu-id="f93b4-104">.NET 用 Azure HDInsight ライブラリ</span><span class="sxs-lookup"><span data-stu-id="f93b4-104">Azure HDInsight libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="f93b4-105">概要</span><span class="sxs-lookup"><span data-stu-id="f93b4-105">Overview</span></span>

<span data-ttu-id="f93b4-106">HDInsight Service .NET SDK は、Azure HDInsight Service によって管理される Hadoop ジョブの作成、構成、送信、監視に関連するクラスを提供します。</span><span class="sxs-lookup"><span data-stu-id="f93b4-106">The HDInsight Service .NET SDK provides classes that relate to the creation, configuration, submission, and monitoring of Hadoop jobs managed by an Azure HDInsight Service.</span></span> <span data-ttu-id="f93b4-107">また、HDInsight Service を使用して Azure サブスクリプションを管理するクラスや、クラスター、ストレージ アカウント、Azure サブスクリプションによって管理されている HDInsight クラスターに関連付けられた他の資産を構成するクラスも提供します。</span><span class="sxs-lookup"><span data-stu-id="f93b4-107">In addition, it provides classes to manage Azure subscriptions using the HDInsight Service and to configure the clusters, storage accounts, and other assets associated with the HDInsight clusters that are managed by an Azure subscription.</span></span>

## <a name="management-libraries"></a><span data-ttu-id="f93b4-108">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="f93b4-108">Management libraries</span></span>

### <a name="jobs"></a><span data-ttu-id="f93b4-109">[ジョブ]</span><span class="sxs-lookup"><span data-stu-id="f93b4-109">Jobs</span></span>

<span data-ttu-id="f93b4-110">Hadoop クラスターでジョブを作成、管理、監視するには、Azure HDInsight クライアント SDK を使用します。</span><span class="sxs-lookup"><span data-stu-id="f93b4-110">Use the Azure HDInsight client SDK to create, manage, and monitor jobs on a Hadoop cluster.</span></span> 

<span data-ttu-id="f93b4-111">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight.Job)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="f93b4-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight.Job) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="f93b4-112">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="f93b4-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.HDInsight.Job
```

```bash
dotnet add package Microsoft.Azure.Management.HDInsight.Job
```

#### <a name="code-example"></a><span data-ttu-id="f93b4-113">コード例</span><span class="sxs-lookup"><span data-stu-id="f93b4-113">Code Example</span></span>

<span data-ttu-id="f93b4-114">この例では、Hadoop クラスターで Hive ジョブを実行します。</span><span class="sxs-lookup"><span data-stu-id="f93b4-114">This example runs a Hive job in a Hadoop cluster.</span></span>

```csharp
HDInsightJobManagementClient managementClient = new HDInsightJobManagementClient(clusterUri, credentials);

Dictionary<string, string> defines = new Dictionary<string, string> {
    { "hive.execution.engine", "tez" },
    { "hive.exec.reducers.max", "1" }
};
List<string> arguments = new List<string> { { "argA" }, { "argB" } };
HiveJobSubmissionParameters parameters = new HiveJobSubmissionParameters
{
    Query = "SHOW TABLES",
    Defines = defines,
    Arguments = arguments
};

JobSubmissionResponse jobResponse = managementClient.JobManagement.SubmitHiveJob(parameters);
```

### <a name="hdinsight"></a><span data-ttu-id="f93b4-115">HDInsight</span><span class="sxs-lookup"><span data-stu-id="f93b4-115">HDInsight</span></span>

<span data-ttu-id="f93b4-116">Hadoop クラスターを作成、管理、起動、停止、スケールするには、Azure HDInsight 管理 SDK を使用します。</span><span class="sxs-lookup"><span data-stu-id="f93b4-116">Use the Azure HDInsight management SDK to create, manage, start, stop, and scale Hadoop clusters.</span></span>

<span data-ttu-id="f93b4-117">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="f93b4-117">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="f93b4-118">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="f93b4-118">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.HDInsight
```

```bash
dotnet add package Microsoft.Azure.Management.HDInsight
```

#### <a name="code-example"></a><span data-ttu-id="f93b4-119">コード例</span><span class="sxs-lookup"><span data-stu-id="f93b4-119">Code Example</span></span>

<span data-ttu-id="f93b4-120">この例では、既存の Azure Blob Storage を使用して、2 つのノードを持つ HDInsight Hadoop Linux クラスターを作成します。</span><span class="sxs-lookup"><span data-stu-id="f93b4-120">This example creates an HDInsight two node Linux Hadoop cluster with an existing Azure Blob Storage.</span></span>

```csharp
HDInsightManagementClient managementClient = new HDInsightManagementClient(authToken);
// Set parameters for the new cluster
ClusterCreateParameters parameters = new ClusterCreateParameters
{
    ClusterSizeInNodes = 2,
    UserName = "admin",
    Password = "<Enter HTTP User Password>",
    ClusterType = "Hadoop",
    OSType = OSType.Linux,
    Version = "3.5",
    // Use an Azure storage account as the default storage
    DefaultStorageInfo = new AzureStorageInfo("<StorageAccount>", "<StorageKey>", "<BlobContainerName>"),
    Location = "EAST US 2",
    SshUserName = "sshuser",
    SshPassword = "<Enter SSH User Password>",
};

// Create the cluster
managementClient.Clusters.Create("<ExistingResourceGroupName>", "<NewClusterName>", parameters);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="f93b4-121">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="f93b4-121">Explore the management APIs</span></span>](/dotnet/api/overview/azure/hdinsights/management)


## <a name="samples"></a><span data-ttu-id="f93b4-122">サンプル</span><span class="sxs-lookup"><span data-stu-id="f93b4-122">Samples</span></span>

- [<span data-ttu-id="f93b4-123">クラスターの作成</span><span class="sxs-lookup"><span data-stu-id="f93b4-123">Cluster creation</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-create-linux-clusters-dotnet-sdk)
- [<span data-ttu-id="f93b4-124">クラスターの管理</span><span class="sxs-lookup"><span data-stu-id="f93b4-124">Cluster management</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-administer-use-dotnet-sdk)
- [<span data-ttu-id="f93b4-125">Hive ジョブの実行</span><span class="sxs-lookup"><span data-stu-id="f93b4-125">Run Hive jobs</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-use-hive-dotnet-sdk)
- [<span data-ttu-id="f93b4-126">Pig ジョブの実行</span><span class="sxs-lookup"><span data-stu-id="f93b4-126">Run Pig jobs</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-use-pig-dotnet-sdk)
- [<span data-ttu-id="f93b4-127">その他のジョブ</span><span class="sxs-lookup"><span data-stu-id="f93b4-127">More jobs</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-submit-hadoop-jobs-programmatically)

<span data-ttu-id="f93b4-128">Azure SQL Database のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=hdinsight)を表示します。</span><span class="sxs-lookup"><span data-stu-id="f93b4-128">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=hdinsight) of Azure SQL Database samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
