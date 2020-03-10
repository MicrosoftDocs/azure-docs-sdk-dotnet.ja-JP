---
title: Azure HDInsight SDK for .NET
description: Azure HDInsight SDK for .NET のリファレンス
ms.date: 04/10/2019
ms.topic: reference
ms.service: hdinsight
ms.openlocfilehash: 2282a302b269a52c71ed88c26e021344cdca4382
ms.sourcegitcommit: 4328168172ac1b1a448e16988f75199262bc5c2d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/17/2019
ms.locfileid: "59700260"
---
# <a name="azure-hdinsight-sdk-for-net"></a>Azure HDInsight SDK for .NET

Azure HDInsight は、HDInsight クラスターの管理と Hadoop ジョブの送信および監視用のクラスを提供する .NET 用の管理とジョブの SDK を提供します。

## <a name="management"></a>管理

.NET 用の HDInsight management SDK には、HDInsight クラスターの管理に使用できるクラスとメソッドが用意されています。 これには、スクリプト アクションを作成、削除、更新、一覧表示、サイズ変更、実行したり、HDInsight クラスターのプロパティを監視、取得したりする操作が含まれます。

## <a name="prerequisites"></a>前提条件

* Azure アカウント。 所有していない場合は、[無料試用版を入手](https://azure.microsoft.com/free/)してください。
* [Visual Studio](https://visualstudio.microsoft.com/downloads/)

## <a name="sdk-installation"></a>SDK のインストール

Visual Studio プロジェクトから **[ツール]**、**[NuGet パッケージ マネージャー]**、**[パッケージ マネージャー コンソール]** の順にクリックして、パッケージ マネージャー コンソールを開きます。

パッケージ マネージャー コンソールで、次のコマンドを実行します。

```
  Install-Package Microsoft.Azure.Management.HDInsight
  Install-Package Microsoft.Azure.Management.Fluent
  Install-Package Microsoft.Azure.Management.ResourceManager.Fluent
```

## <a name="authentication"></a>Authentication

SDK は最初に Azure サブスクリプションで認証する必要があります。  以下の例に従って、サービス プリンシパルを作成し、これを使用して認証します。 その後、`HDInsightManagementClient` のインスタンスが生成されます。これには、管理操作の実行に使用できるメソッドが多数含まれています (以下のセクションで説明します)。

> [!NOTE]
> 認証方法は以下の例の他にもあり、そちらの方がご自身のニーズに適している可能性もあります。 すべてのメソッドの概要については、[.NET 用 Azure ライブラリを使った認証](https://docs.microsoft.com/en-us/dotnet/azure/dotnet-sdk-azure-authenticate?view=azure-dotnet)をご覧ください。

### <a name="authentication-example-using-a-service-principal"></a>サービス プリンシパルを使用した認証の例

まず、[Azure Cloud Shell](https://shell.azure.com/bash) にログインします。 現在、サービス プリンシパル作成対象のサブスクリプションを使用していることを確認します。 

```azurecli-interactive
az account show
```

ご自身のサブスクリプション情報が JSON として表示されます。

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

正しいサブスクリプションにログインしていない場合は、以下を実行して正しいサブスクリプションを選択します。 
```azurecli-interactive
az account set -s <name or ID of subscription>
```

> [!IMPORTANT]
> 他の方法で、たとえば Azure portal で HDInsight クラスターを作成する、といった方法で HDInsight リソース プロバイダーをまだ登録していない場合は、認証の前にこれを一度実行する必要があります。 これを [Azure Cloud Shell](https://shell.azure.com/bash) から実行するには、次のコマンドを実行します。
>```azurecli-interactive
>az provider register --namespace Microsoft.HDInsight
>```

次に、ご自身のサービス プリンシパルの名前を選択し、次のコマンドを使用して作成します。

```azurecli-interactive
az ad sp create-for-rbac --name <Service Principal Name> --sdk-auth
```

サービス プリンシパル情報が JSON として表示されます。

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
次のスニペットをコピーし、コマンド実行後に返された JSON の文字列を `TENANT_ID`、`CLIENT_ID`、`CLIENT_SECRET`、および `SUBSCRIPTION_ID` に入力して、サービス プリンシパルを作成します。

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

## <a name="cluster-management"></a>クラスターの管理

> [!NOTE]
> このセクションでは、`HDInsightManagementClient` インスタンスの認証と構成が既に完了していること、および `client` と呼ばれる変数にそのインスタンスが格納されていることを前提としています。 `HDInsightManagementClient` を認証および取得する方法については、上記の「認証」セクションを参照してください。

### <a name="create-a-cluster"></a>クラスターの作成

新しいクラスターを作成するには、`client.Clusters.Create()` を呼び出します。

#### <a name="samples"></a>サンプル

一般的な数種類のタイプの HDInsight クラスターを作成するためのコード サンプルが次にあります: [HDInsight .NET サンプル](https://github.com/Azure-Samples/hdinsight-dotnet-sdk-samples)。

#### <a name="example"></a>例

この例は、2 つのヘッド ノードと 1 つの worker ノードを含む Spark クラスターを作成する方法を示しています。

> [!NOTE]
> 次に示すように、最初にリソース グループとストレージ アカウントを作成する必要があります。 これらが既に作成済みの場合、この手順はスキップできます。

##### <a name="creating-a-resource-group"></a>リソース グループの作成

[Azure Cloud Shell](https://shell.azure.com/bash) を使用して次を実行することで、リソース グループを作成できます
```azurecli-interactive
az group create -l <Region Name (i.e. eastus)> --n <Resource Group Name>
```
##### <a name="creating-a-storage-account"></a>ストレージ アカウントの作成

[Azure Cloud Shell](https://shell.azure.com/bash) を使用して次を実行することで、ストレージ アカウントを作成できます。
```azurecli-interactive
az storage account create -n <Storage Account Name> -g <Existing Resource Group Name> -l <Region Name (i.e. eastus)> --sku <SKU i.e. Standard_LRS>
```
ここで、次のコマンドを実行して、ストレージ アカウントに対するキーを取得します (これはクラスターを作成するときに必要になります)。
```azurecli-interactive
az storage account keys list -n <Storage Account Name>
```
---
以下の .NET スニペットでは、2 つのヘッド ノードと 1 つの worker ノードを含む Spark クラスターが作成されます。 コメントの説明に従って空白の変数を入力します。また、ご自身のニーズに合わせて他のパラメーターを変更します。

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

### <a name="get-cluster-details"></a>クラスターの詳細の取得

特定のクラスターのプロパティを取得するには:

```csharp
client.Clusters.Get("<Resource Group Name>", "<Cluster Name>");
```

#### <a name="example"></a>例

`get` を使用すると、ご自身のクラスターを適切に作成できたことを確認できます。

```csharp
var myCluster = client.Clusters.Get("<Resource Group Name>", "<Cluster Name>");
Debug.WriteLine(myCluster.Name); //Prints the name of the cluster
Debug.WriteLine(myCluster.Id) //Prints the resource Id of the cluster
```

出力は次のようになります。

```
<Cluster Name>
/subscriptions/XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX/resourceGroups/<Resource Group Name>/providers/Microsoft.HDInsight/clusters/<Cluster Name>
```
> [!NOTE]
> `get` の戻り値は変数 `myCluster` に格納され、型は `Microsoft.Azure.Management.HDInsight.ModelsCluster` です。 このオブジェクトのプロパティの完全な一覧については、[こちら](https://docs.microsoft.com/en-us/dotnet/api/microsoft.azure.management.hdinsight.models.cluster?view=azure-dotnet-preview)をご覧ください。


### <a name="list-clusters"></a>クラスターの一覧表示

#### <a name="list-clusters-under-the-subscription"></a>サブスクリプションのクラスターの一覧表示

```csharp
client.Clusters.List();
```
#### <a name="list-clusters-by-resource-group"></a>リソース グループ別のクラスターの一覧表示

```csharp
client.Clusters.ListByResourceGroup("<Resource Group Name>");
```
> [!NOTE]
> `List()` と `ListByResourceGroup()` の両方が `IPage<Cluster>` オブジェクトを返します。 次のページを取得するには、`client.Clusters.ListNext("Next Page Link")` を呼び出します。 以下の例に示すように、これは `NextPageLink` が `null` になるまで繰り返すことができます。

#### <a name="example"></a>例
次の例では、現在のサブスクリプションのすべてのクラスターのプロパティが出力されます。

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

### <a name="delete-a-cluster"></a>クラスターの削除

クラスターを削除するには:

```csharp
client.Clusters.Delete("<Resource Group Name>", "<Cluster Name>");
```

### <a name="update-cluster-tags"></a>クラスター タグの更新

次のように、特定のクラスターのタグを更新できます。

```csharp
client.Clusters.Update("<Resource Group Name>", "<Cluster Name>", new ClusterPatchParameters(<Dictionary of Tags>));
```
#### <a name="example"></a>例

```csharp
client.Clusters.Update("<Resource Group Name>", "<Cluster Name>", new ClusterPatchParameters(new Dictionary<string, string> { { "tag1Name", "tag1Value" }, { "tag2Name", "tag2Value" } }));
```

### <a name="resize-cluster"></a>クラスターのサイズ変更

特定のクラスターの worker ノード数をサイズ変更するには、次のように新しいサイズを指定します。

```csharp
client.Clusters.Resize("<Resource Group Name>", "<Cluster Name>", <Num of Worker Nodes (int)>)
```

## <a name="cluster-monitoring"></a>クラスターの監視

HDInsight 管理 SDK を使用して、Operations Management Suite (OMS) でご自身のクラスターの監視を管理することもできます。

### <a name="enable-oms-monitoring"></a>OMS 監視の有効化

> [!NOTE]
> OMS の監視を有効にするには、既存の Log Analytics ワークスペースが必要です。 まだ作成していない場合、その方法については、「[Azure portal で Log Analytics ワークスペースを作成する](https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-quick-create-workspace)」を参照してください。

ご自身のクラスターで OMS 監視を有効にするには:

```csharp
client.Extension.EnableMonitoring("<Resource Group Name", "Cluster Name", new ClusterMonitoringRequest(workspaceId: "<Workspace Id>"));
```

### <a name="view-status-of-oms-monitoring"></a>OMS 監視の状態の表示

ご自身のクラスターに対する OMS の状態を取得するには:

```csharp
client.Extension.GetMonitoringStatus("<Resource Group Name", "Cluster Name");
```

### <a name="disable-oms-monitoring"></a>OMS 監視の無効化

ご自身のクラスターに対する OMS を無効にするには:

```csharp
client.Extension.DisableMonitoring("<Resource Group Name>", "<Cluster Name>");
```

## <a name="script-actions"></a>[スクリプト操作]

HDInsight には、クラスターをカスタマイズするためにカスタム スクリプトを呼び出すスクリプト アクションという構成方法があります。
> [!NOTE]
> スクリプト アクションの使用方法の詳細については、「[スクリプト アクションを使用して Linux ベースの HDInsight クラスターをカスタマイズする](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-customize-cluster-linux)」を参照してください

### <a name="execute-script-actions"></a>スクリプト アクションの実行

次のように、特定のクラスターに対してスクリプト アクションを実行できます。

```csharp
var scriptAction1 = new RuntimeScriptAction("<Script Name>", "<URL To Script>", <List<string> of roles>); //valid roles are "headnode", "workernode", "zookeepernode", and "edgenode"

client.Clusters.ExecuteScriptActions("<Resource Group Name>", "<Cluster Name>", new List<RuntimeScriptAction> { scriptAction1 }, <persistOnSuccess (bool)>); //add more RuntimeScriptActions to the list to execute multiple scripts
```

### <a name="delete-script-action"></a>スクリプト アクションの削除

特定のクラスターに対して指定した保存済みスクリプト アクションを削除するには:

```csharp
client.ScriptActions.Delete("<Resource Group Name>", "<Cluster Name>", "<Script Name>");
```

### <a name="list-persisted-script-actions"></a>保存済みスクリプト アクションの一覧表示

> [!NOTE]
> `ListPersistedScripts()` と `List()` が `IPage<RuntimeScriptActionDetail>` オブジェクトを返します。 次のページを取得するには、`client.ScriptActions.ListPersistedScriptsNext("Next Page Link")` または `client.ScriptExecutionHistory.ListNext("Next Page Link")` を呼び出します。 以下の例に示すように、これは `NextPageLink` が `null` になるまで繰り返すことができます。

指定したクラスターに対する保存済みスクリプト アクションを一覧表示するには:
```csharp
client.ScriptActions.ListPersistedScripts("<Resource Group Name>", "<Cluster Name>");
```

#### <a name="example"></a>例

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

### <a name="list-all-scripts-execution-history"></a>スクリプトの全実行履歴の一覧表示

指定したクラスターに対するスクリプトの実行履歴をすべて一覧表示するには:

```csharp
client.script_execution_history.list("<Resource Group Name>", "<Cluster Name>");
```

#### <a name="example"></a>例

この例では、過去のすべてのスクリプト実行の詳細が出力されます。

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

## <a name="jobs"></a>[ジョブ]

Hadoop クラスターでジョブを作成、管理、監視するには、.NET 用の Azure HDInsight ジョブ SDK を使用します。

### <a name="sdk-installation"></a>SDK のインストール

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight.Job)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.HDInsight.Job
```

```bash
dotnet add package Microsoft.Azure.Management.HDInsight.Job
```

### <a name="code-example"></a>コード例

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

### <a name="samples"></a>サンプル

- [Hive ジョブの実行](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-use-hive-dotnet-sdk)
- [Pig ジョブの実行](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-use-pig-dotnet-sdk)
- [その他のジョブ](https://docs.microsoft.com/azure/hdinsight/hdinsight-submit-hadoop-jobs-programmatically)
