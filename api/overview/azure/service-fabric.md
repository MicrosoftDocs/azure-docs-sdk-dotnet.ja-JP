---
title: .NET 用 Azure Service Fabric ライブラリ
description: .NET 用 Azure Service Fabric ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: service-fabric
ms.openlocfilehash: 064f95a4eae3182c4ac5b31779a5d22b592a75b2
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190765"
---
# <a name="azure-service-fabric-libraries-for-net"></a>.NET 用 Azure Service Fabric ライブラリ

## <a name="overview"></a>概要

Azure Service Fabric は、スケーラブルで信頼性に優れたマイクロサービスとコンテナーのパッケージ化とデプロイ、管理を簡単に行うことができる分散システム プラットフォームです。  詳細については、「[Azure Service Fabric のドキュメント](/azure/service-fabric/)」を参照してください。

## <a name="client-library"></a>クライアント ライブラリ

既存の Service Fabric クラスターと対話するには、Service Fabric クライアント ライブラリを使用します。  このライブラリには、3 つのカテゴリの API が含まれています。

* **クライアント** API は、クラスターの管理、スケーリング、リサイクルに加え、アプリケーション パッケージのデプロイに使用されます。
* **ランタイム** API は、実行中のアプリケーションが、ホストしているクラスターと対話する場合に使用されます。
* **一般的な** API には、**クライアント** API と**ランタイム** API の両方で使用される種類が含まれています。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.ServiceFabric)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.ServiceFabric
```

```bash
dotnet add package Microsoft.ServiceFabric
```

### <a name="code-examples"></a>コード例

次の例では、Service Fabric の**クライアント** API を使用してアプリケーション パッケージをイメージ ストアにコピーし、アプリケーションの種類をプロビジョニングして、アプリケーション インスタンスを作成します。

```csharp
/* Include these dependencies
using System.Fabric;
using System.Fabric.Description;
*/

// Connect to the cluster.
FabricClient fabricClient = new FabricClient(clusterConnection);

// Copy the application package to a location in the image store
fabricClient.ApplicationManager.CopyApplicationPackage(imageStoreConnectionString, packagePath, packagePathInImageStore);

// Provision the application.
fabricClient.ApplicationManager.ProvisionApplicationAsync(packagePathInImageStore).Wait();

//  Create the application instance.
ApplicationDescription appDesc = new ApplicationDescription(new Uri(appName), appType, appVersion);
fabricClient.ApplicationManager.CreateApplicationAsync(appDesc).Wait();
```

> [!div class="nextstepaction"]
> [クライアント API を探す](/dotnet/api/overview/azure/servicefabric/client)

この例では、ホストされるアプリケーション内から Service Fabric の**ランタイム** API と**一般的な** API を使用して、実行時に [Reliable Collection](/azure/service-fabric/service-fabric-reliable-services-reliable-collections) を更新します。

```csharp
using System.Fabric;
using Microsoft.ServiceFabric.Data.Collections;
using Microsoft.ServiceFabric.Services.Communication.Runtime;
using Microsoft.ServiceFabric.Services.Runtime;

/// <summary>
/// This is the main entry point for your service replica.
/// This method executes when this replica of your service becomes primary and has write status.
/// </summary>
/// <param name="cancellationToken">Canceled when Service Fabric needs to shut down this service replica.</param>
protected override async Task RunAsync(CancellationToken cancellationToken)
{
    var myDictionary = await this.StateManager.GetOrAddAsync<IReliableDictionary<string, long>>("myDictionary");
    while (true)
    {
        cancellationToken.ThrowIfCancellationRequested();
        using (var tx = this.StateManager.CreateTransaction())
        {
            var result = await myDictionary.TryGetValueAsync(tx, "Counter");
            await myDictionary.AddOrUpdateAsync(tx, "Counter", 0, (key, value) => ++value);

            // If an exception is thrown before calling CommitAsync, the transaction aborts, all changes are
            // discarded, and nothing is saved to the secondary replicas.
            await tx.CommitAsync();
        }
        await Task.Delay(TimeSpan.FromSeconds(1), cancellationToken);
    }
}
```

> [!div class="nextstepaction"]
> [ランタイム API を探す](/dotnet/api/overview/azure/servicefabric/runtime)

> [!div class="nextstepaction"]
> [一般的な API を探す](/dotnet/api/overview/azure/servicefabric/common)

## <a name="management-library"></a>管理ライブラリ

管理ライブラリは、Service Fabric クラスターの作成、更新、削除に使用されます。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceFabric)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.ServiceFabric
```

```bash
dotnet add package Microsoft.Azure.Management.ServiceFabric
```

> [!div class="nextstepaction"]
> [Management API を探す](/dotnet/api/overview/azure/servicefabric/management)

## <a name="samples"></a>サンプル

* [FabricClient を使用してアプリケーションのデプロイと削除を実行する](/azure/service-fabric/service-fabric-deploy-remove-applications-fabricclient)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
