---
title: ".NET 用 Azure Service Fabric ライブラリ"
description: ".NET 用 Azure Service Fabric ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Service Fabric
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: service-fabric
ms.custom: devcenter, svc-overview
ms.openlocfilehash: f4b54933d31a4e1fc4c390baa57469cc1c02783a
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/26/2017
---
# <a name="azure-service-fabric-libraries-for-net"></a><span data-ttu-id="4a4e0-104">.NET 用 Azure Service Fabric ライブラリ</span><span class="sxs-lookup"><span data-stu-id="4a4e0-104">Azure Service Fabric libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="4a4e0-105">概要</span><span class="sxs-lookup"><span data-stu-id="4a4e0-105">Overview</span></span>

<span data-ttu-id="4a4e0-106">Azure Service Fabric は、スケーラブルで信頼性に優れたマイクロサービスとコンテナーのパッケージ化とデプロイ、管理を簡単に行うことができる分散システム プラットフォームです。</span><span class="sxs-lookup"><span data-stu-id="4a4e0-106">Azure Service Fabric is a distributed systems platform that makes it easy to package, deploy, and manage scalable and reliable microservices and containers.</span></span>  <span data-ttu-id="4a4e0-107">詳細については、「[Azure Service Fabric のドキュメント](/azure/service-fabric/)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4a4e0-107">For more information, see the [Azure Service Fabric Documentation](/azure/service-fabric/).</span></span>

## <a name="client-library"></a><span data-ttu-id="4a4e0-108">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="4a4e0-108">Client library</span></span>

<span data-ttu-id="4a4e0-109">既存の Service Fabric クラスターと対話するには、Service Fabric クライアント ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="4a4e0-109">Use the Service Fabric client library to interact with an existing Service Fabric cluster.</span></span>  <span data-ttu-id="4a4e0-110">このライブラリには、3 つのカテゴリの API が含まれています。</span><span class="sxs-lookup"><span data-stu-id="4a4e0-110">The library contains three categories of APIs:</span></span>

* <span data-ttu-id="4a4e0-111">**クライアント** API は、クラスターの管理、スケーリング、リサイクルに加え、アプリケーション パッケージのデプロイに使用されます。</span><span class="sxs-lookup"><span data-stu-id="4a4e0-111">**Client** APIs are used to manage, scale, and recycle the cluster, as well as deploy application packages.</span></span>
* <span data-ttu-id="4a4e0-112">**ランタイム** API は、実行中のアプリケーションが、ホストしているクラスターと対話する場合に使用されます。</span><span class="sxs-lookup"><span data-stu-id="4a4e0-112">**Runtime** APIs are used for the running application to interact with its hosting cluster.</span></span>
* <span data-ttu-id="4a4e0-113">**一般的な** API には、**クライアント** API と**ランタイム** API の両方で使用される種類が含まれています。</span><span class="sxs-lookup"><span data-stu-id="4a4e0-113">**Common** APIs contain types used in both **client** and **runtime** APIs.</span></span>

<span data-ttu-id="4a4e0-114">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.ServiceFabric)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="4a4e0-114">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.ServiceFabric) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="4a4e0-115">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="4a4e0-115">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.ServiceFabric
```

```bash
dotnet add package Microsoft.ServiceFabric
```

### <a name="code-examples"></a><span data-ttu-id="4a4e0-116">コード例</span><span class="sxs-lookup"><span data-stu-id="4a4e0-116">Code Examples</span></span>

<span data-ttu-id="4a4e0-117">次の例では、Service Fabric の**クライアント** API を使用してアプリケーション パッケージをイメージ ストアにコピーし、アプリケーションの種類をプロビジョニングして、アプリケーション インスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="4a4e0-117">The following example uses the Service Fabric **client** APIs to copy an application package to the image store, provisions the application type, and create an application instance.</span></span>

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
> [<span data-ttu-id="4a4e0-118">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="4a4e0-118">Explore the client APIs</span></span>](/dotnet/api/overview/azure/servicefabric/client)

<span data-ttu-id="4a4e0-119">この例では、ホストされるアプリケーション内から Service Fabric の**ランタイム** API と**一般的な** API を使用して、実行時に [Reliable Collection](/azure/service-fabric/service-fabric-reliable-services-reliable-collections) を更新します。</span><span class="sxs-lookup"><span data-stu-id="4a4e0-119">This example uses the Service Fabric **runtime** and **common** APIs from within a hosted application to update a [Reliable Collection](/azure/service-fabric/service-fabric-reliable-services-reliable-collections) at runtime.</span></span>

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
> [<span data-ttu-id="4a4e0-120">ランタイム API を探す</span><span class="sxs-lookup"><span data-stu-id="4a4e0-120">Explore the runtime APIs</span></span>](/dotnet/api/overview/azure/servicefabric/runtime)

> [!div class="nextstepaction"]
> [<span data-ttu-id="4a4e0-121">一般的な API を探す</span><span class="sxs-lookup"><span data-stu-id="4a4e0-121">Explore the common APIs</span></span>](/dotnet/api/overview/azure/servicefabric/common)

## <a name="management-library"></a><span data-ttu-id="4a4e0-122">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="4a4e0-122">Management Library</span></span>

<span data-ttu-id="4a4e0-123">管理ライブラリは、Service Fabric クラスターの作成、更新、削除に使用されます。</span><span class="sxs-lookup"><span data-stu-id="4a4e0-123">The management library is used to create, update, and delete Service Fabric clusters.</span></span>

<span data-ttu-id="4a4e0-124">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceFabric)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="4a4e0-124">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceFabric) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="4a4e0-125">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="4a4e0-125">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.ServiceFabric
```

```bash
dotnet add package Microsoft.Azure.Management.ServiceFabric
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="4a4e0-126">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="4a4e0-126">Explore the management APIs</span></span>](/dotnet/api/overview/azure/servicefabric/management)

## <a name="samples"></a><span data-ttu-id="4a4e0-127">サンプル</span><span class="sxs-lookup"><span data-stu-id="4a4e0-127">Samples</span></span>

* [<span data-ttu-id="4a4e0-128">FabricClient を使用してアプリケーションのデプロイと削除を実行する</span><span class="sxs-lookup"><span data-stu-id="4a4e0-128">Deploy and remove applications using FabricClient</span></span>](/azure/service-fabric/service-fabric-deploy-remove-applications-fabricclient)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
