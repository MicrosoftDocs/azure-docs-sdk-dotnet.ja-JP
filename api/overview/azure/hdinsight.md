---
title: Azure HDInsight .NET SDK
description: Azure HDInsight .NET SDK のリファレンス
ms.date: 9/19/2018
ms.topic: reference
ms.service: hdinsight
ms.openlocfilehash: 35e2c8c07fb2b86b2d0ae9be4f855e369c1aa86d
ms.sourcegitcommit: 1cf4550df8ed3236d838f561f6177d14d89b5e44
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2018
ms.locfileid: "49348204"
---
# <a name="azure-hdinsight-net-sdk"></a><span data-ttu-id="f9dfd-103">Azure HDInsight .NET SDK</span><span class="sxs-lookup"><span data-stu-id="f9dfd-103">Azure HDInsight .NET SDK</span></span>

## <a name="azure-hdinsight-libraries-for-net-2x"></a><span data-ttu-id="f9dfd-104">.NET 2.X 用 Azure HDInsight ライブラリ</span><span class="sxs-lookup"><span data-stu-id="f9dfd-104">Azure HDInsight libraries for .NET 2.X</span></span>

## <a name="overview"></a><span data-ttu-id="f9dfd-105">概要</span><span class="sxs-lookup"><span data-stu-id="f9dfd-105">Overview</span></span>

<span data-ttu-id="f9dfd-106">HDInsight Service .NET SDK は、Azure HDInsight Service によって管理される Hadoop ジョブの作成、構成、送信、監視に関連するクラスを提供します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-106">The HDInsight Service .NET SDK provides classes that relate to the creation, configuration, submission, and monitoring of Hadoop jobs managed by an Azure HDInsight Service.</span></span> <span data-ttu-id="f9dfd-107">また、HDInsight Service を使用して Azure サブスクリプションを管理するクラスや、クラスター、ストレージ アカウント、Azure サブスクリプションによって管理されている HDInsight クラスターに関連付けられた他の資産を構成するクラスも提供します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-107">In addition, it provides classes to manage Azure subscriptions using the HDInsight Service and to configure the clusters, storage accounts, and other assets associated with the HDInsight clusters that are managed by an Azure subscription.</span></span>

## <a name="management-libraries"></a><span data-ttu-id="f9dfd-108">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="f9dfd-108">Management libraries</span></span>

### <a name="jobs"></a><span data-ttu-id="f9dfd-109">[ジョブ]</span><span class="sxs-lookup"><span data-stu-id="f9dfd-109">Jobs</span></span>

<span data-ttu-id="f9dfd-110">Hadoop クラスターでジョブを作成、管理、監視するには、Azure HDInsight クライアント SDK を使用します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-110">Use the Azure HDInsight client SDK to create, manage, and monitor jobs on a Hadoop cluster.</span></span> 

<span data-ttu-id="f9dfd-111">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight.Job)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight.Job) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="f9dfd-112">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="f9dfd-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.HDInsight.Job
```

```bash
dotnet add package Microsoft.Azure.Management.HDInsight.Job
```

#### <a name="code-example"></a><span data-ttu-id="f9dfd-113">コード例</span><span class="sxs-lookup"><span data-stu-id="f9dfd-113">Code Example</span></span>

<span data-ttu-id="f9dfd-114">この例では、Hadoop クラスターで Hive ジョブを実行します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-114">This example runs a Hive job in a Hadoop cluster.</span></span>

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

### <a name="hdinsight"></a><span data-ttu-id="f9dfd-115">HDInsight</span><span class="sxs-lookup"><span data-stu-id="f9dfd-115">HDInsight</span></span>

<span data-ttu-id="f9dfd-116">Hadoop クラスターを作成、管理、起動、停止、スケールするには、Azure HDInsight 管理 SDK を使用します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-116">Use the Azure HDInsight management SDK to create, manage, start, stop, and scale Hadoop clusters.</span></span>

<span data-ttu-id="f9dfd-117">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-117">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="f9dfd-118">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="f9dfd-118">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.HDInsight
```

```bash
dotnet add package Microsoft.Azure.Management.HDInsight
```

#### <a name="code-example"></a><span data-ttu-id="f9dfd-119">コード例</span><span class="sxs-lookup"><span data-stu-id="f9dfd-119">Code Example</span></span>

<span data-ttu-id="f9dfd-120">この例では、既存の Azure Blob Storage を使用して、2 つのノードを持つ HDInsight Hadoop Linux クラスターを作成します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-120">This example creates an HDInsight two node Linux Hadoop cluster with an existing Azure Blob Storage.</span></span>

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
> [<span data-ttu-id="f9dfd-121">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="f9dfd-121">Explore the management APIs</span></span>](/dotnet/api/overview/azure/hdinsights/management)


## <a name="samples"></a><span data-ttu-id="f9dfd-122">サンプル</span><span class="sxs-lookup"><span data-stu-id="f9dfd-122">Samples</span></span>

- [<span data-ttu-id="f9dfd-123">クラスターの作成</span><span class="sxs-lookup"><span data-stu-id="f9dfd-123">Cluster creation</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-create-linux-clusters-dotnet-sdk)
- [<span data-ttu-id="f9dfd-124">クラスターの管理</span><span class="sxs-lookup"><span data-stu-id="f9dfd-124">Cluster management</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-administer-use-dotnet-sdk)
- [<span data-ttu-id="f9dfd-125">Hive ジョブの実行</span><span class="sxs-lookup"><span data-stu-id="f9dfd-125">Run Hive jobs</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-use-hive-dotnet-sdk)
- [<span data-ttu-id="f9dfd-126">Pig ジョブの実行</span><span class="sxs-lookup"><span data-stu-id="f9dfd-126">Run Pig jobs</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-use-pig-dotnet-sdk)
- [<span data-ttu-id="f9dfd-127">その他のジョブ</span><span class="sxs-lookup"><span data-stu-id="f9dfd-127">More jobs</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-submit-hadoop-jobs-programmatically)

<span data-ttu-id="f9dfd-128">Azure SQL Database のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=hdinsight)を表示します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-128">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=hdinsight) of Azure SQL Database samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package

## <a name="hdinsight-net-management-sdk-3x-preview"></a><span data-ttu-id="f9dfd-129">HDInsight .NET Management SDK 3.X プレビュー</span><span class="sxs-lookup"><span data-stu-id="f9dfd-129">HDInsight .NET Management SDK 3.X Preview</span></span>

## <a name="overview"></a><span data-ttu-id="f9dfd-130">概要</span><span class="sxs-lookup"><span data-stu-id="f9dfd-130">Overview</span></span>

<span data-ttu-id="f9dfd-131">HDInsight .NET SDK に用意されているクラスとメソッドを使用すると、お使いの HDInsight クラスターを管理することができます。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-131">The HDInsight .NET SDK provides classes and methods that allow you to manage your HDInsight clusters.</span></span> <span data-ttu-id="f9dfd-132">これには、スクリプト アクションを作成、削除、更新、一覧表示、サイズ変更、実行したり、HDInsight クラスターのプロパティを監視、取得したりする操作が含まれます。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-132">It includes operations to create, delete, update, list, resize, execute script actions, monitor, get properties of HDInsight clusters, and more.</span></span>

## <a name="prerequisites"></a><span data-ttu-id="f9dfd-133">前提条件</span><span class="sxs-lookup"><span data-stu-id="f9dfd-133">Prerequisites</span></span>

* <span data-ttu-id="f9dfd-134">Azure アカウント。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-134">An Azure account.</span></span> <span data-ttu-id="f9dfd-135">所有していない場合は、[無料試用版を入手](https://azure.microsoft.com/free/)してください。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-135">If you don't have one, [get a free trial](https://azure.microsoft.com/free/).</span></span>
* [<span data-ttu-id="f9dfd-136">Visual Studio</span><span class="sxs-lookup"><span data-stu-id="f9dfd-136">Visual Studio</span></span>](https://visualstudio.microsoft.com/downloads/)

## <a name="sdk-installation"></a><span data-ttu-id="f9dfd-137">SDK のインストール</span><span class="sxs-lookup"><span data-stu-id="f9dfd-137">SDK Installation</span></span>

<span data-ttu-id="f9dfd-138">Visual Studio プロジェクトから **[ツール]**、**[NuGet パッケージ マネージャー]**、**[パッケージ マネージャー コンソール]** の順にクリックして、パッケージ マネージャー コンソールを開きます。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-138">From your Visual Studio project, open the Package Manager Console by clicking **Tools**, **NuGet Package Manager**, and then click **Package Manager Console**.</span></span>

<span data-ttu-id="f9dfd-139">パッケージ マネージャー コンソールで、次のコマンドを実行します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-139">In the Package Manager Console, execute the following commands:</span></span>

```
  Install-Package Microsoft.Azure.Management.HDInsight -Version 3.1.0-preview
  Install-Package Microsoft.Azure.Management.Fluent
  Install-Package Microsoft.Azure.Management.ResourceManager.Fluent
```

## <a name="authentication"></a><span data-ttu-id="f9dfd-140">Authentication</span><span class="sxs-lookup"><span data-stu-id="f9dfd-140">Authentication</span></span>

<span data-ttu-id="f9dfd-141">SDK は最初に Azure サブスクリプションで認証する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-141">The SDK first needs to be authenticated with your Azure subscription.</span></span>  <span data-ttu-id="f9dfd-142">以下の例に従って、サービス プリンシパルを作成し、これを使用して認証します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-142">Follow the example below to create a service principal and use it to authenticate.</span></span> <span data-ttu-id="f9dfd-143">その後、`HDInsightManagementClient` のインスタンスが生成されます。これには、管理操作の実行に使用できるメソッドが多数含まれています (以下のセクションで説明します)。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-143">After this is done, you will have an instance of an `HDInsightManagementClient`, which contains many methods (outlined in below sections) that can be used to perform management operations.</span></span>

> [!NOTE]
> <span data-ttu-id="f9dfd-144">認証方法は以下の例の他にもあり、そちらの方がご自身のニーズに適している可能性もあります。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-144">There are other ways to authenticate besides the below example that could potentially be better suited for your needs.</span></span> <span data-ttu-id="f9dfd-145">すべての方法については、「[.NET 用 Azure ライブラリを使った認証](https://docs.microsoft.com/en-us/dotnet/azure/dotnet-sdk-azure-authenticate?view=azure-dotnet)」を参照してください</span><span class="sxs-lookup"><span data-stu-id="f9dfd-145">All methods are outlined here: [Authenticate with the Azure Libraries for .NET](https://docs.microsoft.com/en-us/dotnet/azure/dotnet-sdk-azure-authenticate?view=azure-dotnet)</span></span>

### <a name="authentication-example-using-a-service-principal"></a><span data-ttu-id="f9dfd-146">サービス プリンシパルを使用した認証の例</span><span class="sxs-lookup"><span data-stu-id="f9dfd-146">Authentication Example Using a Service Principal</span></span>

<span data-ttu-id="f9dfd-147">まず、[Azure Cloud Shell](https://shell.azure.com/bash) にログインします。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-147">First, login to [Azure Cloud Shell](https://shell.azure.com/bash).</span></span> <span data-ttu-id="f9dfd-148">現在、サービス プリンシパル作成対象のサブスクリプションを使用していることを確認します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-148">Verify you are currently using the subscription in which you want the service principal created.</span></span> 

```azurecli-interactive
az account show
```

<span data-ttu-id="f9dfd-149">ご自身のサブスクリプション情報が JSON として表示されます。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-149">Your subscription information is displayed as JSON.</span></span>

```json
{
  "environmentName": "AzureCloud",
  "id": "XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX",
  "isDefault": true,
  "name": "XXXXXXX",
  "state": "Enabled",
  "tenantId": "XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX",
  "user": {
    "cloudShellID": true,
    "name": "XXX@XXX.XXX",
    "type": "user"
  }
}
```

<span data-ttu-id="f9dfd-150">正しいサブスクリプションにログインしていない場合は、以下を実行して正しいサブスクリプションを選択します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-150">If you're not logged into the correct subscription, select the correct one by running:</span></span> 
```azurecli-interactive
az account set -s <name or ID of subscription>
```

> [!IMPORTANT]
> <span data-ttu-id="f9dfd-151">他の方法で、たとえば Azure portal で HDInsight クラスターを作成する、といった方法で HDInsight リソース プロバイダーをまだ登録していない場合は、認証の前にこれを一度実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-151">If you have not already registered the HDInsight Resource Provider by another method (such as by creating an HDInsight Cluster through the Azure Portal), you need to do this once before you can authenticate.</span></span> <span data-ttu-id="f9dfd-152">これを [Azure Cloud Shell](https://shell.azure.com/bash) から実行するには、次のコマンドを実行します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-152">This can be done from the [Azure Cloud Shell](https://shell.azure.com/bash) by running the following command:</span></span>
>```azurecli-interactive
>az provider register --namespace Microsoft.HDInsight
>```

<span data-ttu-id="f9dfd-153">次に、ご自身のサービス プリンシパルの名前を選択し、次のコマンドを使用して作成します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-153">Next, choose a name for your service principal and create it with the following command:</span></span>

```azurecli-interactive
az ad sp create-for-rbac --name <Service Principal Name> --sdk-auth
```

<span data-ttu-id="f9dfd-154">サービス プリンシパル情報が JSON として表示されます。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-154">The service principal information is displayed as JSON.</span></span>

```json
{
  "clientId": "XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX",
  "clientSecret": "XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX",
  "subscriptionId": "XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX",
  "tenantId": "XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX",
  "activeDirectoryEndpointUrl": "https://login.microsoftonline.com",
  "resourceManagerEndpointUrl": "https://management.azure.com/",
  "activeDirectoryGraphResourceId": "https://graph.windows.net/",
  "sqlManagementEndpointUrl": "https://management.core.windows.net:8443/",
  "galleryEndpointUrl": "https://gallery.azure.com/",
  "managementEndpointUrl": "https://management.core.windows.net/"
}
```
<span data-ttu-id="f9dfd-155">次のスニペットをコピーし、コマンド実行後に返された JSON の文字列を `TENANT_ID`、`CLIENT_ID`、`CLIENT_SECRET`、および `SUBSCRIPTION_ID` に入力して、サービス プリンシパルを作成します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-155">Copy the below snippet and fill in `TENANT_ID`, `CLIENT_ID`, `CLIENT_SECRET`, and `SUBSCRIPTION_ID` with the strings from the JSON that was returned after running the command to create the service principal.</span></span>

```csharp
using Microsoft.Azure.Management.HDInsight;
using Microsoft.Azure.Management.HDInsight.Models;
using Microsoft.Azure.Management.ResourceManager.Fluent;

namespace HDI_SDK_Test
{
    class Program
    {
        static void Main(string[] args)
        {
            // Tenant ID for your Azure Subscription
            var TENANT_ID = "";
            // Your Service Principal App Client ID
            var CLIENT_ID = "";
            // Your Service Principal Client Secret
            var CLIENT_SECRET = "";
            // Azure Subscription ID
            var SUBSCRIPTION_ID = "";

            var credentials = SdkContext.AzureCredentialsFactory
                .FromServicePrincipal(
                CLIENT_ID,
                CLIENT_SECRET,
                TENANT_ID,
                AzureEnvironment.AzureGlobalCloud);

            var client = new HDInsightManagementClient(credentials);
            client.SubscriptionId = SUBSCRIPTION_ID;
        }
    }
}
```


## <a name="cluster-management"></a><span data-ttu-id="f9dfd-156">クラスターの管理</span><span class="sxs-lookup"><span data-stu-id="f9dfd-156">Cluster Management</span></span>

> [!NOTE]
> <span data-ttu-id="f9dfd-157">このセクションでは、`HDInsightManagementClient` インスタンスの認証と構成が既に完了していること、および `client` と呼ばれる変数にそのインスタンスが格納されていることを前提としています。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-157">This section assumes you have already authenticated and constructed an `HDInsightManagementClient` instance and store it in a variable called `client`.</span></span> <span data-ttu-id="f9dfd-158">`HDInsightManagementClient` を認証および取得する方法については、上記の「認証」セクションを参照してください。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-158">Instructions for authenticating and obtaining an `HDInsightManagementClient` can be found in the Authentication section above.</span></span>

### <a name="create-a-cluster"></a><span data-ttu-id="f9dfd-159">クラスターの作成</span><span class="sxs-lookup"><span data-stu-id="f9dfd-159">Create a Cluster</span></span>

<span data-ttu-id="f9dfd-160">新しいクラスターを作成するには、`client.Clusters.Create()` を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-160">A new cluster can be created by calling `client.Clusters.Create()`.</span></span> 

#### <a name="example"></a><span data-ttu-id="f9dfd-161">例</span><span class="sxs-lookup"><span data-stu-id="f9dfd-161">Example</span></span>

<span data-ttu-id="f9dfd-162">この例は、2 つのヘッド ノードと 1 つの worker ノードを含む Spark クラスターを作成する方法を示しています。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-162">This example demonstrates how to create a Spark cluster with 2 head nodes and 1 worker node.</span></span>

> [!NOTE]
> <span data-ttu-id="f9dfd-163">次に示すように、最初にリソース グループとストレージ アカウントを作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-163">You first need to create a Resource Group and Storage Account, as explained below.</span></span> <span data-ttu-id="f9dfd-164">これらが既に作成済みの場合、この手順はスキップできます。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-164">If you have already created these, you can skip these steps.</span></span>

##### <a name="creating-a-resource-group"></a><span data-ttu-id="f9dfd-165">リソース グループの作成</span><span class="sxs-lookup"><span data-stu-id="f9dfd-165">Creating a Resource Group</span></span>

<span data-ttu-id="f9dfd-166">[Azure Cloud Shell](https://shell.azure.com/bash) を使用して次を実行することで、リソース グループを作成できます</span><span class="sxs-lookup"><span data-stu-id="f9dfd-166">You can create a resource group using the [Azure Cloud Shell](https://shell.azure.com/bash) by running</span></span>
```azurecli-interactive
az group create -l <Region Name (i.e. eastus)> --n <Resource Group Name>
```
##### <a name="creating-a-storage-account"></a><span data-ttu-id="f9dfd-167">ストレージ アカウントの作成</span><span class="sxs-lookup"><span data-stu-id="f9dfd-167">Creating a Storage Account</span></span>

<span data-ttu-id="f9dfd-168">[Azure Cloud Shell](https://shell.azure.com/bash) を使用して次を実行することで、ストレージ アカウントを作成できます。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-168">You can create a storage account using the [Azure Cloud Shell](https://shell.azure.com/bash) by running:</span></span>
```azurecli-interactive
az storage account create -n <Storage Account Name> -g <Existing Resource Group Name> -l <Region Name (i.e. eastus)> --sku <SKU i.e. Standard_LRS>
```
<span data-ttu-id="f9dfd-169">ここで、次のコマンドを実行して、ストレージ アカウントに対するキーを取得します (これはクラスターを作成するときに必要になります)。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-169">Now run the following command to get the key for your storage account (you will need this to create a cluster):</span></span>
```azurecli-interactive
az storage account keys list -n <Storage Account Name>
```
---
<span data-ttu-id="f9dfd-170">以下の .NET スニペットでは、2 つのヘッド ノードと 1 つの worker ノードを含む Spark クラスターが作成されます。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-170">The below .NET snippet creates a Spark cluster with 2 head nodes and 1 worker node.</span></span> <span data-ttu-id="f9dfd-171">コメントの説明に従って空白の変数を入力します。また、ご自身のニーズに合わせて他のパラメーターを変更します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-171">Fill in the blank variables as explained in the comments and feel free to change other parameters to suit your specific needs.</span></span>

```csharp
// The name for the cluster you are creating
var clusterName = "";
// The name of your existing Resource Group
var resourceGroupName = "";
// Choose a username
var username = "";
// Choose a password
var password = "";
// Replace <> with the name of your storage account
var storageAccount = "<>.blob.core.windows.net";
// Storage account key you obtained above
var storageAccountKey = "";
// Choose a region
var location = "";
var container = "default";

var parameters = new ClusterCreateParametersExtended
{
    Location = location,
    Tags = new Dictionary<string, string>(),
    Properties = new ClusterCreateProperties
    {
        ClusterVersion = "3.6",
        OsType = OSType.Linux,
        ClusterDefinition = new ClusterDefinition
        {
            Kind = "Hadoop",            
            Configurations = new Dictionary<string, Dictionary<string, string>>()
            {                
                { "gateway", new Dictionary<string, string>
                    {
                        { "restAuthCredential.isEnabled", "true" },
                        { "restAuthCredential.username", username},
                        { "restAuthCredential.password", password}
                    }
                }
            }
        },
        Tier = Tier.Standard,
        ComputeProfile = new ComputeProfile
        {
            Roles = new List<Role>{
                new Role
                {
                    Name = "headnode",
                    TargetInstanceCount = 2,
                    HardwareProfile = new HardwareProfile
                    {
                        VmSize = "Large"
                    },
                    OsProfile = new OsProfile
                    {
                        LinuxOperatingSystemProfile = new LinuxOperatingSystemProfile
                        {
                            Username = username,
                            Password = password
                        }
                    }
                },
                new Role
                {
                    Name = "workernode",
                    TargetInstanceCount = 1,
                    HardwareProfile = new HardwareProfile
                    {
                        VmSize = "Large"
                    },
                    OsProfile = new OsProfile
                    {
                        LinuxOperatingSystemProfile = new LinuxOperatingSystemProfile
                        {
                            Username = username,
                            Password = password
                        }
                    }
                },
            }
        },
        StorageProfile = new StorageProfile
        {
            Storageaccounts = new[]
            {
                new StorageAccount
                {
                    Name = storageAccount,
                    Key = storageAccountKey,
                    Container = container,
                    IsDefault = true
                }
            }
        }
    }
};
client.Clusters.Create(
    resourceGroupName,
    clusterName,
    parameters
);
```

### <a name="get-cluster-details"></a><span data-ttu-id="f9dfd-172">クラスターの詳細の取得</span><span class="sxs-lookup"><span data-stu-id="f9dfd-172">Get Cluster Details</span></span>

<span data-ttu-id="f9dfd-173">特定のクラスターのプロパティを取得するには:</span><span class="sxs-lookup"><span data-stu-id="f9dfd-173">To get properties for a given cluster:</span></span>

```csharp
client.Clusters.Get("<Resource Group Name>", "<Cluster Name>");
```

#### <a name="example"></a><span data-ttu-id="f9dfd-174">例</span><span class="sxs-lookup"><span data-stu-id="f9dfd-174">Example</span></span>

<span data-ttu-id="f9dfd-175">`get` を使用すると、ご自身のクラスターを適切に作成できたことを確認できます。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-175">You can use `get` to confirm that you have successfully created your cluster.</span></span>

```csharp
var myCluster = client.Clusters.Get("<Resource Group Name>", "<Cluster Name>");
Debug.WriteLine(myCluster.Name); //Prints the name of the cluster
Debug.WriteLine(myCluster.Id) //Prints the resource Id of the cluster
```

<span data-ttu-id="f9dfd-176">出力は次のようになります。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-176">The output should look like:</span></span>

```
<Cluster Name>
/subscriptions/XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX/resourceGroups/<Resource Group Name>/providers/Microsoft.HDInsight/clusters/<Cluster Name>
```
> [!NOTE]
> <span data-ttu-id="f9dfd-177">`get` の戻り値は変数 `myCluster` に格納され、型は `Microsoft.Azure.Management.HDInsight.ModelsCluster` です。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-177">The return value of `get`, stored in variable `myCluster`, is of type `Microsoft.Azure.Management.HDInsight.ModelsCluster`.</span></span> <span data-ttu-id="f9dfd-178">このオブジェクトのプロパティの完全な一覧については、[こちら](https://docs.microsoft.com/en-us/dotnet/api/microsoft.azure.management.hdinsight.models.cluster?view=azure-dotnet-preview)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-178">A full list of this object's properties can be found [here](https://docs.microsoft.com/en-us/dotnet/api/microsoft.azure.management.hdinsight.models.cluster?view=azure-dotnet-preview).</span></span>


### <a name="list-clusters"></a><span data-ttu-id="f9dfd-179">クラスターの一覧表示</span><span class="sxs-lookup"><span data-stu-id="f9dfd-179">List Clusters</span></span>

#### <a name="list-clusters-under-the-subscription"></a><span data-ttu-id="f9dfd-180">サブスクリプションのクラスターの一覧表示</span><span class="sxs-lookup"><span data-stu-id="f9dfd-180">List Clusters Under The Subscription</span></span>

```csharp
client.Clusters.List();
```
#### <a name="list-clusters-by-resource-group"></a><span data-ttu-id="f9dfd-181">リソース グループ別のクラスターの一覧表示</span><span class="sxs-lookup"><span data-stu-id="f9dfd-181">List Clusters By Resource Group</span></span>

```csharp
client.Clusters.ListByResourceGroup("<Resource Group Name>");
```
> [!NOTE]
> <span data-ttu-id="f9dfd-182">`List()` と `ListByResourceGroup()` の両方が `IPage<Cluster>` オブジェクトを返します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-182">Both `List()` and `ListByResourceGroup()` return an `IPage<Cluster>` object.</span></span> <span data-ttu-id="f9dfd-183">次のページを取得するには、`client.Clusters.ListNext("Next Page Link")` を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-183">To get the next page, you can call `client.Clusters.ListNext("Next Page Link")`.</span></span> <span data-ttu-id="f9dfd-184">以下の例に示すように、これは `NextPageLink` が `null` になるまで繰り返すことができます。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-184">This can be repeated until `NextPageLink` is `null`, as shown in the example below.</span></span>

#### <a name="example"></a><span data-ttu-id="f9dfd-185">例</span><span class="sxs-lookup"><span data-stu-id="f9dfd-185">Example</span></span>
<span data-ttu-id="f9dfd-186">次の例では、現在のサブスクリプションのすべてのクラスターのプロパティが出力されます。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-186">The following example prints the properties of all clusters for the current subscription:</span></span>

```csharp
var clustersPaged = client.Clusters.List();
while (true)
{
  foreach (var cluster in clustersPaged)
  {
    Debug.WriteLine(cluster.Name);
  
}  if (clustersPaged.NextPageLink == null)
  {
    break;
  }
  clustersPaged = client.Clusters.ListNext(clustersPaged.NextPageLink);
}
```

### <a name="delete-a-cluster"></a><span data-ttu-id="f9dfd-187">クラスターの削除</span><span class="sxs-lookup"><span data-stu-id="f9dfd-187">Delete a Cluster</span></span>

<span data-ttu-id="f9dfd-188">クラスターを削除するには:</span><span class="sxs-lookup"><span data-stu-id="f9dfd-188">To delete a cluster:</span></span>

```csharp
client.Clusters.Delete("<Resource Group Name>", "<Cluster Name>");
```

### <a name="update-cluster-tags"></a><span data-ttu-id="f9dfd-189">クラスター タグの更新</span><span class="sxs-lookup"><span data-stu-id="f9dfd-189">Update Cluster Tags</span></span>

<span data-ttu-id="f9dfd-190">次のように、特定のクラスターのタグを更新できます。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-190">You can update the tags of a given cluster like so:</span></span>

```csharp
client.Clusters.Update("<Resource Group Name>", "<Cluster Name>", new ClusterPatchParameters(<Dictionary of Tags>));
```
#### <a name="example"></a><span data-ttu-id="f9dfd-191">例</span><span class="sxs-lookup"><span data-stu-id="f9dfd-191">Example</span></span>

```csharp
client.Clusters.Update("<Resource Group Name>", "<Cluster Name>", new ClusterPatchParameters(new Dictionary<string, string> { { "tag1Name", "tag1Value" }, { "tag2Name", "tag2Value" } }));
```

### <a name="resize-cluster"></a><span data-ttu-id="f9dfd-192">クラスターのサイズ変更</span><span class="sxs-lookup"><span data-stu-id="f9dfd-192">Resize Cluster</span></span>

<span data-ttu-id="f9dfd-193">特定のクラスターの worker ノード数をサイズ変更するには、次のように新しいサイズを指定します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-193">You can resize a given cluster's number of worker nodes by specifying a new size like so:</span></span>

```csharp
client.Clusters.Resize("<Resource Group Name>", "<Cluster Name>", <Num of Worker Nodes (int)>)
```

## <a name="cluster-monitoring"></a><span data-ttu-id="f9dfd-194">クラスターの監視</span><span class="sxs-lookup"><span data-stu-id="f9dfd-194">Cluster Monitoring</span></span>

<span data-ttu-id="f9dfd-195">HDInsight 管理 SDK を使用して、Operations Management Suite (OMS) でご自身のクラスターの監視を管理することもできます。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-195">The HDInsight Management SDK can also be used to manage monitoring on your clusters via the Operations Management Suite (OMS).</span></span>

### <a name="enable-oms-monitoring"></a><span data-ttu-id="f9dfd-196">OMS 監視の有効化</span><span class="sxs-lookup"><span data-stu-id="f9dfd-196">Enable OMS Monitoring</span></span>

> [!NOTE]
> <span data-ttu-id="f9dfd-197">OMS の監視を有効にするには、既存の Log Analytics ワークスペースが必要です。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-197">To enable OMS Monitoring, you must have an existing Log Analytics workspace.</span></span> <span data-ttu-id="f9dfd-198">まだ作成していない場合、その方法については、「[Azure ポータルで Log Analytics ワークスペースを作成する](https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-quick-create-workspace)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-198">If you have not already created one, you can learn how to do that here: [Create a Log Analytics workspace in the Azure portal](https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-quick-create-workspace).</span></span>

<span data-ttu-id="f9dfd-199">ご自身のクラスターで OMS 監視を有効にするには:</span><span class="sxs-lookup"><span data-stu-id="f9dfd-199">To enable OMS Monitoring on your cluster:</span></span>

```csharp
client.Extension.EnableMonitoring("<Resource Group Name", "Cluster Name", new ClusterMonitoringRequest(workspaceId: "<Workspace Id>"));
```

### <a name="view-status-of-oms-monitoring"></a><span data-ttu-id="f9dfd-200">OMS 監視の状態の表示</span><span class="sxs-lookup"><span data-stu-id="f9dfd-200">View Status Of OMS Monitoring</span></span>

<span data-ttu-id="f9dfd-201">ご自身のクラスターに対する OMS の状態を取得するには:</span><span class="sxs-lookup"><span data-stu-id="f9dfd-201">To get the status of OMS on your cluster:</span></span>

```csharp
client.Extension.GetMonitoringStatus("<Resource Group Name", "Cluster Name");
```

### <a name="disable-oms-monitoring"></a><span data-ttu-id="f9dfd-202">OMS 監視の無効化</span><span class="sxs-lookup"><span data-stu-id="f9dfd-202">Disable OMS Monitoring</span></span>

<span data-ttu-id="f9dfd-203">ご自身のクラスターに対する OMS を無効にするには:</span><span class="sxs-lookup"><span data-stu-id="f9dfd-203">To disable OMS on your cluster:</span></span>

```csharp
client.Extension.DisableMonitoring("<Resource Group Name>", "<Cluster Name>");
```

## <a name="script-actions"></a><span data-ttu-id="f9dfd-204">[スクリプト操作]</span><span class="sxs-lookup"><span data-stu-id="f9dfd-204">Script Actions</span></span>

<span data-ttu-id="f9dfd-205">HDInsight には、クラスターをカスタマイズするためにカスタム スクリプトを呼び出すスクリプト アクションという構成方法があります。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-205">HDInsight provides a configuration method called script actions that invokes custom scripts to customize the cluster.</span></span>
> [!NOTE]
> <span data-ttu-id="f9dfd-206">スクリプト アクションを使用する方法の詳細については、「[スクリプト アクションを使用して Linux ベースの HDInsight クラスターをカスタマイズする](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-customize-cluster-linux)」を参照してください</span><span class="sxs-lookup"><span data-stu-id="f9dfd-206">More information on how to use script actions can be found here: [Customize Linux-based HDInsight clusters using script actions](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-customize-cluster-linux)</span></span>

### <a name="execute-script-actions"></a><span data-ttu-id="f9dfd-207">スクリプト アクションの実行</span><span class="sxs-lookup"><span data-stu-id="f9dfd-207">Execute Script Actions</span></span>

<span data-ttu-id="f9dfd-208">次のように、特定のクラスターに対してスクリプト アクションを実行できます。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-208">You can execute script actions on a given cluster like so:</span></span>

```csharp
var scriptAction1 = new RuntimeScriptAction("<Script Name>", "<URL To Script>", <List<string> of roles>); //valid roles are "headnode", "workernode", "zookeepernode", and "edgenode"

client.Clusters.ExecuteScriptActions("<Resource Group Name>", "<Cluster Name>", new List<RuntimeScriptAction> { scriptAction1 }, <persistOnSuccess (bool)>); //add more RuntimeScriptActions to the list to execute multiple scripts
```

### <a name="delete-script-action"></a><span data-ttu-id="f9dfd-209">スクリプト アクションの削除</span><span class="sxs-lookup"><span data-stu-id="f9dfd-209">Delete Script Action</span></span>

<span data-ttu-id="f9dfd-210">特定のクラスターに対して指定した保存済みスクリプト アクションを削除するには:</span><span class="sxs-lookup"><span data-stu-id="f9dfd-210">To delete a specified persisted script action on a given cluster:</span></span>

```csharp
client.ScriptActions.Delete("<Resource Group Name>", "<Cluster Name>", "<Script Name>");
```

### <a name="list-persisted-script-actions"></a><span data-ttu-id="f9dfd-211">保存済みスクリプト アクションの一覧表示</span><span class="sxs-lookup"><span data-stu-id="f9dfd-211">List Persisted Script Actions</span></span>

> [!NOTE]
> <span data-ttu-id="f9dfd-212">`ListPersistedScripts()` と `List()` が `IPage<RuntimeScriptActionDetail>` オブジェクトを返します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-212">`ListPersistedScripts()` and `List()` return an `IPage<RuntimeScriptActionDetail>` object.</span></span> <span data-ttu-id="f9dfd-213">次のページを取得するには、`client.ScriptActions.ListPersistedScriptsNext("Next Page Link")` または `client.ScriptExecutionHistory.ListNext("Next Page Link")` を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-213">To get the next page, you can call `client.ScriptActions.ListPersistedScriptsNext("Next Page Link")` or `client.ScriptExecutionHistory.ListNext("Next Page Link")`.</span></span> <span data-ttu-id="f9dfd-214">以下の例に示すように、これは `NextPageLink` が `null` になるまで繰り返すことができます。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-214">This can be repeated until `NextPageLink` is `null`, as shown in the examples below.</span></span>

<span data-ttu-id="f9dfd-215">指定したクラスターに対する保存済みスクリプト アクションを一覧表示するには:</span><span class="sxs-lookup"><span data-stu-id="f9dfd-215">To list all persisted script actions for the specified cluster:</span></span>
```csharp
client.ScriptActions.ListPersistedScripts("<Resource Group Name>", "<Cluster Name>");
```

#### <a name="example"></a><span data-ttu-id="f9dfd-216">例</span><span class="sxs-lookup"><span data-stu-id="f9dfd-216">Example</span></span>

```csharp
var scriptsPaged = client.ScriptActions.ListPersistedScripts("<Resource Group Name>", "<Cluster Name>");
while (true)
{
    foreach (var script in scriptsPaged)
    {
        Debug.WriteLine(script.Name); //There are other properties of RuntimeScriptActionDetail besides Name, such as Status, Operation, StartTime, EndTime, etc. See reference documentation.
    }
    if (scriptsPaged.NextPageLink == null)
    {
        break;
    }
    scriptsPaged = client.ScriptActions.ListPersistedScriptsNext(scriptsPaged.NextPageLink);
}
```

### <a name="list-all-scripts-execution-history"></a><span data-ttu-id="f9dfd-217">スクリプトの全実行履歴の一覧表示</span><span class="sxs-lookup"><span data-stu-id="f9dfd-217">List All Scripts' Execution History</span></span>

<span data-ttu-id="f9dfd-218">指定したクラスターに対するスクリプトの実行履歴をすべて一覧表示するには:</span><span class="sxs-lookup"><span data-stu-id="f9dfd-218">To list all scripts' execution history for the specified cluster:</span></span>

```csharp
client.script_execution_history.list("<Resource Group Name>", "<Cluster Name>");
```

#### <a name="example"></a><span data-ttu-id="f9dfd-219">例</span><span class="sxs-lookup"><span data-stu-id="f9dfd-219">Example</span></span>

<span data-ttu-id="f9dfd-220">この例では、過去のすべてのスクリプト実行の詳細が出力されます。</span><span class="sxs-lookup"><span data-stu-id="f9dfd-220">This example prints all the details for all past script executions.</span></span>

```csharp
var scriptExecutionsPaged = client.ScriptExecutionHistory.List("<Resource Group Name>", "<Cluster Name>");
while (true)
{
    foreach (var script in scriptExecutionsPaged)
    {
        Debug.WriteLine(script.Name); //There are other properties of RuntimeScriptActionDetail besides Name, such as Status, Operation, StartTime, EndTime, etc. See reference documentation.

    }
    if (scriptExecutionsPaged.NextPageLink == null)
    {
        break;
    }
    scriptExecutionsPaged = client.ScriptExecutionHistory.ListNext(scriptExecutionsPaged.NextPageLink);
}
```
