---
title: .NET 用 Azure Batch ライブラリ
description: .NET 用 Azure Batch ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Batch
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: batch
ms.custom: devcenter, svc-overview
ms.openlocfilehash: b6053e19d26247dd36ed7e38fc33030f96aecca8
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065562"
---
# <a name="azure-batch-libraries-for-net"></a>.NET 用 Azure Batch ライブラリ

Azure Batch は、大規模な並列コンピューティングやハイ パフォーマンス コンピューティング (HPC) のアプリケーションをクラウドで効率的に実行するためのプラットフォーム サービスです。 多くのコンピューティング処理を要する作業を管理された仮想マシンの集合で実行するようにスケジュール設定し、ジョブのニーズに合わせてコンピューティング リソースを自動的に拡大/縮小できます。

Azure Batch では、複数のアプリケーションを並列で大規模に実行するための Azure コンピューティング リソースを簡単に定義できます。 HPC クラスター、個々の仮想マシン、仮想ネットワークや、複雑なジョブとタスクのスケジュール インフラストラクチャを手動で作成、構成、管理する必要がありません。 Azure Batch によって、これらのタスクが自動化または簡略化されます。

[Batch で並列ワークロードを本質的に実行する](/azure/batch/batch-technical-overview)方法をご覧ください。 [.NET 向け Batch クライアント ライブラリを使ってソリューション作成を開始する](/azure/batch/batch-dotnet-get-started)方法もご覧ください。 さらに、[.NET 用の Batch 管理クライアント ライブラリを使って Batch アカウントとクォータを管理する](/azure/batch/batch-management-dotnet)方法をご覧ください。

## <a name="client-library"></a>クライアント ライブラリ

Batch で並列ワークロードを実行するには、クライアント ライブラリを使います。

[NuGet パッケージ](https://www.nuget.org/packages/Azure.Batch)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Azure.Batch
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Azure.Batch
```

### <a name="example"></a>例

次の例では、クライアント SDK を使って、Azure Batch で実行するジョブを作成します。

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
> [クライアント API を探す](/dotnet/api/overview/azure/batch/client)

## <a name="management-library"></a>管理ライブラリ

Batch アカウント、クォータ、およびアプリケーション パッケージをプログラムで管理するには、管理ライブラリを使います。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Batch)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.Batch
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.Management.Batch
```

### <a name="example"></a>例

次の例では、サブスクリプションのクォータを取得し、アカウントを作成して、プライマリ アカウント キーを再生成します。

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
> [Management API を探す](/dotnet/api/overview/azure/batch/management)

## <a name="samples"></a>サンプル

* [.NET サンプル用の Azure Batch クライアントおよび管理 SDK](https://github.com/Azure/azure-batch-samples/tree/master/CSharp)

アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
