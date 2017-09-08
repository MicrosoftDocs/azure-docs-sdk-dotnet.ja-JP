---
title: ".NET 用 Azure Data Factory ライブラリ"
description: ".NET 用 Azure Data Factory ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Data Factory
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/20/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: e0b85d7d3988febca6dce7f4038825d74e4b8d2e
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-data-factory-libraries-for-net"></a><span data-ttu-id="5c040-104">.NET 用 Azure Data Factory ライブラリ</span><span class="sxs-lookup"><span data-stu-id="5c040-104">Azure Data Factory libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="5c040-105">概要</span><span class="sxs-lookup"><span data-stu-id="5c040-105">Overview</span></span>

<span data-ttu-id="5c040-106">Azure Data Factory は、クラウドベースのデータ統合サービスです。</span><span class="sxs-lookup"><span data-stu-id="5c040-106">Azure Data Factory is a cloud-based data integration service.</span></span> <span data-ttu-id="5c040-107">Azure Data Factory を使用すると、クラウドにデータ ドリブン ワークフローを作成して、データ移動とデータ変換を調整および自動化できます。</span><span class="sxs-lookup"><span data-stu-id="5c040-107">It enables you to create data-driven workflows in the cloud to orchestrate and automate data movement and data transformation.</span></span>

<span data-ttu-id="5c040-108">詳細については、「[Azure Data Factory の概要](/azure/data-factory/data-factory-introduction)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="5c040-108">To learn more, read the [Introduction to Azure Data Factory](/azure/data-factory/data-factory-introduction).</span></span>

## <a name="management-library"></a><span data-ttu-id="5c040-109">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="5c040-109">Management library</span></span>

<span data-ttu-id="5c040-110">データ ドリブン ワークフロー (パイプライン) を作成し、スケジュールするには、管理ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="5c040-110">Use the management library to create and schedule data-driven workflows (pipelines).</span></span>

<span data-ttu-id="5c040-111">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactories)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="5c040-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactories) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="5c040-112">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="5c040-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.DataFactories
```

```bash
dotnet add package Microsoft.Azure.Management.DataFactories
```

### <a name="code-example"></a><span data-ttu-id="5c040-113">コード例</span><span class="sxs-lookup"><span data-stu-id="5c040-113">Code Example</span></span>

<span data-ttu-id="5c040-114">次の例では、管理ライブラリを使用してデータ ファクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="5c040-114">The following example uses the management library to create a data factory.</span></span>

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
> [<span data-ttu-id="5c040-115">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="5c040-115">Explore the management APIs</span></span>](/dotnet/api/overview/azure/datafactories/management)

## <a name="samples"></a><span data-ttu-id="5c040-116">サンプル</span><span class="sxs-lookup"><span data-stu-id="5c040-116">Samples</span></span>

* <span data-ttu-id="5c040-117">Data Factory を使用して洞察を得るための [MyDriving - Azure IoT およびモバイル サンプル アプリケーション](https://azure.microsoft.com/resources/samples/mydriving/)。</span><span class="sxs-lookup"><span data-stu-id="5c040-117">[MyDriving - An Azure IOT and Mobile Sample Application](https://azure.microsoft.com/resources/samples/mydriving/) that uses Data Factory to drive insights.</span></span>

<span data-ttu-id="5c040-118">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="5c040-118">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
