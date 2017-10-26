---
title: ".NET 用 Azure HDInsight ライブラリ"
description: ".NET 用 Azure HDInsight ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, HDInsight
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: hd-insight
ms.custom: devcenter, svc-overview
ms.openlocfilehash: da9023ab4e6106754d48acb31cda58cdb358f5cb
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/23/2017
---
# <a name="azure-hdinsight-libraries-for-net"></a>.NET 用 Azure HDInsight ライブラリ

## <a name="overview"></a>概要

HDInsight Service .NET SDK は、Azure HDInsight Service によって管理される Hadoop ジョブの作成、構成、送信、監視に関連するクラスを提供します。 また、HDInsight Service を使用して Azure サブスクリプションを管理するクラスや、クラスター、ストレージ アカウント、Azure サブスクリプションによって管理されている HDInsight クラスターに関連付けられた他の資産を構成するクラスも提供します。

## <a name="management-libraries"></a>管理ライブラリ

### <a name="jobs"></a>[ジョブ]

Hadoop クラスターでジョブを作成、管理、監視するには、Azure HDInsight クライアント SDK を使用します。 

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight.Job)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.HDInsight.Job
```

```bash
dotnet add package Microsoft.Azure.Management.HDInsight.Job
```

#### <a name="code-example"></a>コード例

この例では、Hadoop クラスターで Hive ジョブを実行します。

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

### <a name="hdinsight"></a>HDInsight

Hadoop クラスターを作成、管理、起動、停止、スケールするには、Azure HDInsight 管理 SDK を使用します。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.HDInsight
```

```bash
dotnet add package Microsoft.Azure.Management.HDInsight
```

#### <a name="code-example"></a>コード例

この例では、既存の Azure Blob Storage を使用して、2 つのノードを持つ HDInsight Hadoop Linux クラスターを作成します。

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
> [Management API を探す](/dotnet/api/overview/azure/hdinsights/management)


## <a name="samples"></a>サンプル

- [クラスターの作成](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-create-linux-clusters-dotnet-sdk)
- [クラスターの管理](https://docs.microsoft.com/azure/hdinsight/hdinsight-administer-use-dotnet-sdk)
- [Hive ジョブの実行](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-use-hive-dotnet-sdk)
- [Pig ジョブの実行](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-use-pig-dotnet-sdk)
- [その他のジョブ](https://docs.microsoft.com/azure/hdinsight/hdinsight-submit-hadoop-jobs-programmatically)

Azure SQL Database のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=hdinsight)を表示します。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
