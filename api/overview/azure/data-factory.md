---
title: .NET 用 Azure Data Factory ライブラリ
description: .NET 用 Azure Data Factory ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Data Factory
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: data-factory
ms.custom: devcenter, svc-overview
ms.openlocfilehash: b3c492fbfe4a4afa6f06f8c48a370c554a01719c
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065792"
---
# <a name="azure-data-factory-libraries-for-net"></a><span data-ttu-id="cbf07-104">.NET 用 Azure Data Factory ライブラリ</span><span class="sxs-lookup"><span data-stu-id="cbf07-104">Azure Data Factory libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="cbf07-105">概要</span><span class="sxs-lookup"><span data-stu-id="cbf07-105">Overview</span></span>

<span data-ttu-id="cbf07-106">Azure Data Factory は、クラウドベースのデータ統合サービスです。</span><span class="sxs-lookup"><span data-stu-id="cbf07-106">Azure Data Factory is a cloud-based data integration service.</span></span> <span data-ttu-id="cbf07-107">Azure Data Factory を使用すると、クラウドにデータ ドリブン ワークフローを作成して、データ移動とデータ変換を調整および自動化できます。</span><span class="sxs-lookup"><span data-stu-id="cbf07-107">It enables you to create data-driven workflows in the cloud to orchestrate and automate data movement and data transformation.</span></span>

<span data-ttu-id="cbf07-108">詳細については、「[Azure Data Factory の概要](/azure/data-factory/data-factory-introduction)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="cbf07-108">To learn more, read the [Introduction to Azure Data Factory](/azure/data-factory/data-factory-introduction).</span></span>

## <a name="management-library---data-factory-v2-preview"></a><span data-ttu-id="cbf07-109">管理ライブラリ - Data Factory V2 (プレビュー)</span><span class="sxs-lookup"><span data-stu-id="cbf07-109">Management library - Data Factory V2 (Preview)</span></span>

<span data-ttu-id="cbf07-110">Data Factory V2 (プレビュー) でデータドリブン ワークフロー (パイプライン) を作成し、スケジュールするには、管理ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="cbf07-110">Use the management library to create and schedule data-driven workflows (pipelines) in Data Factory V2 (Preview).</span></span>  <span data-ttu-id="cbf07-111">詳細については、「[Create a data factory and pipeline using .NET SDK (.NET SDK を使用してデータ ファクトリとパイプラインを作成する)](/azure/data-factory/quickstart-create-data-factory-dot-net)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="cbf07-111">For more information, see [Create a data factory and pipeline using .NET SDK](/azure/data-factory/quickstart-create-data-factory-dot-net).</span></span>

<span data-ttu-id="cbf07-112">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactory)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="cbf07-112">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactory) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="cbf07-113">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="cbf07-113">Visual Studio Package Manager</span></span>

```powershell
# Get the most recent prerelease package
Install-Package Microsoft.Azure.Management.DataFactory -Prerelease
```

```bash
# Be sure to include the most recent version from the NuGet package page
dotnet add package Microsoft.Azure.Management.DataFactory --version 0.2.0-preview
```

### <a name="code-example"></a><span data-ttu-id="cbf07-114">コード例</span><span class="sxs-lookup"><span data-stu-id="cbf07-114">Code Example</span></span>

<span data-ttu-id="cbf07-115">次の例では、管理ライブラリを使用してデータ ファクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="cbf07-115">The following example uses the management library to create a data factory.</span></span>

```csharp
/*
using Microsoft.Azure.Management.ResourceManager;
using Microsoft.Azure.Management.DataFactory;
using Microsoft.Azure.Management.DataFactory.Models;
*/

DataFactoryManagementClient client = new DataFactoryManagementClient(tokenCredentials) { SubscriptionId = subscriptionId };
Factory dataFactory = new Factory
{
    Location = region,
    Identity = new FactoryIdentity()
};
client.Factories.CreateOrUpdate(resourceGroup, dataFactoryName, dataFactory);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="cbf07-116">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="cbf07-116">Explore the management APIs</span></span>](/dotnet/api/microsoft.azure.management.datafactory)

## <a name="management-library---data-factory-v1"></a><span data-ttu-id="cbf07-117">管理ライブラリ - Data Factory V1</span><span class="sxs-lookup"><span data-stu-id="cbf07-117">Management library - Data Factory V1</span></span>

<span data-ttu-id="cbf07-118">Data Factory バージョン 1 でデータドリブン ワークフロー (パイプライン) を作成し、スケジュールするには、管理ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="cbf07-118">Use the management library to create and schedule data-driven workflows (pipelines) in Data Factory Version 1.</span></span>  <span data-ttu-id="cbf07-119">詳細については、[Data Factory バージョン 1](/azure/data-factory/v1/data-factory-introduction)のドキュメントを参照してください。</span><span class="sxs-lookup"><span data-stu-id="cbf07-119">For more information, review the documentation for [Data Factory Version 1](/azure/data-factory/v1/data-factory-introduction).</span></span>

<span data-ttu-id="cbf07-120">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactories)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="cbf07-120">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactories) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="cbf07-121">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="cbf07-121">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.DataFactories
```

```bash
dotnet add package Microsoft.Azure.Management.DataFactories
```

### <a name="code-example"></a><span data-ttu-id="cbf07-122">コード例</span><span class="sxs-lookup"><span data-stu-id="cbf07-122">Code Example</span></span>

<span data-ttu-id="cbf07-123">次の例では、管理ライブラリを使用してデータ ファクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="cbf07-123">The following example uses the management library to create a data factory.</span></span>

```csharp
DataFactoryManagementClient client = new DataFactoryManagementClient(aadTokenCredentials, resourceManagerUri);
client.DataFactories.CreateOrUpdate(resourceGroupName,
    new DataFactoryCreateOrUpdateParameters()
    {
        DataFactory = new DataFactory()
        {
            Name = dataFactoryName,
            Location = "westus",
            Properties = new DataFactoryProperties()
        }
    }
);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="cbf07-124">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="cbf07-124">Explore the management APIs</span></span>](/dotnet/api/overview/azure/datafactories/management)

## <a name="samples"></a><span data-ttu-id="cbf07-125">サンプル</span><span class="sxs-lookup"><span data-stu-id="cbf07-125">Samples</span></span>

* <span data-ttu-id="cbf07-126">Data Factory を使用して洞察を得るための [MyDriving - Azure IoT およびモバイル サンプル アプリケーション](https://azure.microsoft.com/resources/samples/mydriving/)。</span><span class="sxs-lookup"><span data-stu-id="cbf07-126">[MyDriving - An Azure IOT and Mobile Sample Application](https://azure.microsoft.com/resources/samples/mydriving/) that uses Data Factory to drive insights.</span></span>

<span data-ttu-id="cbf07-127">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="cbf07-127">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
