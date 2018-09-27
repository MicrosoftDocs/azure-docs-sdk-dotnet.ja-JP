---
title: .NET 用 Azure Data Factory ライブラリ
description: .NET 用 Azure Data Factory ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: data-factory
ms.openlocfilehash: 9a779f223cd0e158e99afcf1ee011d121f2fe838
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190325"
---
# <a name="azure-data-factory-libraries-for-net"></a><span data-ttu-id="01436-103">.NET 用 Azure Data Factory ライブラリ</span><span class="sxs-lookup"><span data-stu-id="01436-103">Azure Data Factory libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="01436-104">概要</span><span class="sxs-lookup"><span data-stu-id="01436-104">Overview</span></span>

<span data-ttu-id="01436-105">Azure Data Factory は、クラウドベースのデータ統合サービスです。</span><span class="sxs-lookup"><span data-stu-id="01436-105">Azure Data Factory is a cloud-based data integration service.</span></span> <span data-ttu-id="01436-106">Azure Data Factory を使用すると、クラウドにデータ ドリブン ワークフローを作成して、データ移動とデータ変換を調整および自動化できます。</span><span class="sxs-lookup"><span data-stu-id="01436-106">It enables you to create data-driven workflows in the cloud to orchestrate and automate data movement and data transformation.</span></span>

<span data-ttu-id="01436-107">詳細については、「[Azure Data Factory の概要](/azure/data-factory/data-factory-introduction)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="01436-107">To learn more, read the [Introduction to Azure Data Factory](/azure/data-factory/data-factory-introduction).</span></span>

## <a name="management-library---data-factory-v2-preview"></a><span data-ttu-id="01436-108">管理ライブラリ - Data Factory V2 (プレビュー)</span><span class="sxs-lookup"><span data-stu-id="01436-108">Management library - Data Factory V2 (Preview)</span></span>

<span data-ttu-id="01436-109">Data Factory V2 (プレビュー) でデータドリブン ワークフロー (パイプライン) を作成し、スケジュールするには、管理ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="01436-109">Use the management library to create and schedule data-driven workflows (pipelines) in Data Factory V2 (Preview).</span></span>  <span data-ttu-id="01436-110">詳細については、「[Create a data factory and pipeline using .NET SDK (.NET SDK を使用してデータ ファクトリとパイプラインを作成する)](/azure/data-factory/quickstart-create-data-factory-dot-net)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="01436-110">For more information, see [Create a data factory and pipeline using .NET SDK](/azure/data-factory/quickstart-create-data-factory-dot-net).</span></span>

<span data-ttu-id="01436-111">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactory)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="01436-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactory) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="01436-112">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="01436-112">Visual Studio Package Manager</span></span>

```powershell
# Get the most recent prerelease package
Install-Package Microsoft.Azure.Management.DataFactory -Prerelease
```

```bash
# Be sure to include the most recent version from the NuGet package page
dotnet add package Microsoft.Azure.Management.DataFactory --version 0.2.0-preview
```

### <a name="code-example"></a><span data-ttu-id="01436-113">コード例</span><span class="sxs-lookup"><span data-stu-id="01436-113">Code Example</span></span>

<span data-ttu-id="01436-114">次の例では、管理ライブラリを使用してデータ ファクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="01436-114">The following example uses the management library to create a data factory.</span></span>

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
> [<span data-ttu-id="01436-115">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="01436-115">Explore the management APIs</span></span>](/dotnet/api/microsoft.azure.management.datafactory)

## <a name="management-library---data-factory-v1"></a><span data-ttu-id="01436-116">管理ライブラリ - Data Factory V1</span><span class="sxs-lookup"><span data-stu-id="01436-116">Management library - Data Factory V1</span></span>

<span data-ttu-id="01436-117">Data Factory バージョン 1 でデータドリブン ワークフロー (パイプライン) を作成し、スケジュールするには、管理ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="01436-117">Use the management library to create and schedule data-driven workflows (pipelines) in Data Factory Version 1.</span></span>  <span data-ttu-id="01436-118">詳細については、[Data Factory バージョン 1](/azure/data-factory/v1/data-factory-introduction)のドキュメントを参照してください。</span><span class="sxs-lookup"><span data-stu-id="01436-118">For more information, review the documentation for [Data Factory Version 1](/azure/data-factory/v1/data-factory-introduction).</span></span>

<span data-ttu-id="01436-119">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactories)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="01436-119">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactories) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="01436-120">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="01436-120">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.DataFactories
```

```bash
dotnet add package Microsoft.Azure.Management.DataFactories
```

### <a name="code-example"></a><span data-ttu-id="01436-121">コード例</span><span class="sxs-lookup"><span data-stu-id="01436-121">Code Example</span></span>

<span data-ttu-id="01436-122">次の例では、管理ライブラリを使用してデータ ファクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="01436-122">The following example uses the management library to create a data factory.</span></span>

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
> [<span data-ttu-id="01436-123">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="01436-123">Explore the management APIs</span></span>](/dotnet/api/overview/azure/datafactories/management)

## <a name="samples"></a><span data-ttu-id="01436-124">サンプル</span><span class="sxs-lookup"><span data-stu-id="01436-124">Samples</span></span>

* <span data-ttu-id="01436-125">Data Factory を使用して洞察を得るための [MyDriving - Azure IoT およびモバイル サンプル アプリケーション](https://azure.microsoft.com/resources/samples/mydriving/)。</span><span class="sxs-lookup"><span data-stu-id="01436-125">[MyDriving - An Azure IOT and Mobile Sample Application](https://azure.microsoft.com/resources/samples/mydriving/) that uses Data Factory to drive insights.</span></span>

<span data-ttu-id="01436-126">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="01436-126">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
