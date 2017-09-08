---
title: ".NET 用 Azure Data Lake Store ライブラリ"
description: ".NET 用 Azure Data Lake Store ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Data Lake Store
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/18/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 18746d745d64065a3d92215e704bce575130bdb0
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-data-lake-store-libraries-for-net"></a><span data-ttu-id="4ec43-104">.NET 用 Azure Data Lake Store ライブラリ</span><span class="sxs-lookup"><span data-stu-id="4ec43-104">Azure Data Lake Store libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="4ec43-105">概要</span><span class="sxs-lookup"><span data-stu-id="4ec43-105">Overview</span></span>

<span data-ttu-id="4ec43-106">Azure Data Lake Store は、ビッグ データの分析ワークロードに対応するエンタープライズ規模のハイパースケール リポジトリです。</span><span class="sxs-lookup"><span data-stu-id="4ec43-106">Azure Data Lake Store is an enterprise-wide hyper-scale repository for big data analytic workloads.</span></span> <span data-ttu-id="4ec43-107">Azure Data Lake を使用すると、運用分析や調査分析を目的として任意のサイズ、種類、および取り込み速度のデータを 1 か所でキャプチャすることができます。</span><span class="sxs-lookup"><span data-stu-id="4ec43-107">Azure Data Lake enables you to capture data of any size, type, and ingestion speed in one single place for operational and exploratory analytics.</span></span>

<span data-ttu-id="4ec43-108">詳細については、「[Azure Data Lake Store の概要](/azure/data-lake-store/data-lake-store-overview)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="4ec43-108">To learn more, see [Overview of Azure Data Lake Store](/azure/data-lake-store/data-lake-store-overview).</span></span>

## <a name="management-library"></a><span data-ttu-id="4ec43-109">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="4ec43-109">Management library</span></span>

<span data-ttu-id="4ec43-110">ビッグ データ リポジトリに接続し、リポジトリを管理するには、管理ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="4ec43-110">Use the management library to connect to and manage your big data repositories.</span></span>

<span data-ttu-id="4ec43-111">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="4ec43-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="4ec43-112">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="4ec43-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.DataLake.Store
```

```bash
dotnet add package Microsoft.Azure.Management.DataLake.Store
```

### <a name="code-example"></a><span data-ttu-id="4ec43-113">コード例</span><span class="sxs-lookup"><span data-stu-id="4ec43-113">Code Example</span></span>

<span data-ttu-id="4ec43-114">この例では、Analytics アカウントおよびストアに対して認証し、管理に必要なクライアントを作成します。</span><span class="sxs-lookup"><span data-stu-id="4ec43-114">This example authenticates to an analytics account and store and creates the clients necessary for management.</span></span>

```csharp
/*
using AdlClient
using AdlClient.Models 
*/

// Setup authentication 
Authentication auth = new Authentication("microsoft.onmicrosoft.com"); // change this to YOUR tenant
auth.Authenticate();

// Identify the accounts
StoreAccountRef adls_account = new StoreAccountRef(subscriptionId, resourceGroup, userName);

// Create the clients
AzureClient az = new AzureClient(auth);
StoreClient adls = new StoreClient(auth, adls_account);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="4ec43-115">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="4ec43-115">Explore the management APIs</span></span>](/dotnet/api/overview/azure/datalakestore/management)

## <a name="samples"></a><span data-ttu-id="4ec43-116">サンプル</span><span class="sxs-lookup"><span data-stu-id="4ec43-116">Samples</span></span>

* [<span data-ttu-id="4ec43-117">Azure Data Lake .NET クライアントのサンプル</span><span class="sxs-lookup"><span data-stu-id="4ec43-117">Azure Data Lake .NET Client Example</span></span>](https://azure.microsoft.com/en-us/resources/samples/data-lake-dotnet-client/)

<span data-ttu-id="4ec43-118">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="4ec43-118">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
