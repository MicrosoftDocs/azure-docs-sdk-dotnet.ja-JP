---
title: .NET 用 Azure Data Lake Store ライブラリ
description: .NET 用 Azure Data Lake Store ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Data Lake Store
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: data-lake-store
ms.custom: devcenter, svc-overview
ms.openlocfilehash: f1b014c4835784ed8ecfa1e3b4bfd62a6ebf9562
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065632"
---
# <a name="azure-data-lake-store-libraries-for-net"></a><span data-ttu-id="c3ee4-104">.NET 用 Azure Data Lake Store ライブラリ</span><span class="sxs-lookup"><span data-stu-id="c3ee4-104">Azure Data Lake Store libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="c3ee4-105">概要</span><span class="sxs-lookup"><span data-stu-id="c3ee4-105">Overview</span></span>

<span data-ttu-id="c3ee4-106">Azure Data Lake Store は、ビッグ データの分析ワークロードに対応するエンタープライズ規模のハイパースケール リポジトリです。</span><span class="sxs-lookup"><span data-stu-id="c3ee4-106">Azure Data Lake Store is an enterprise-wide hyper-scale repository for big data analytic workloads.</span></span> <span data-ttu-id="c3ee4-107">Azure Data Lake を使用すると、運用分析や調査分析を目的として任意のサイズ、種類、および取り込み速度のデータを 1 か所でキャプチャすることができます。</span><span class="sxs-lookup"><span data-stu-id="c3ee4-107">Azure Data Lake enables you to capture data of any size, type, and ingestion speed in one single place for operational and exploratory analytics.</span></span>

<span data-ttu-id="c3ee4-108">詳細については、「[Azure Data Lake Store の概要](/azure/data-lake-store/data-lake-store-overview)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="c3ee4-108">To learn more, see [Overview of Azure Data Lake Store](/azure/data-lake-store/data-lake-store-overview).</span></span>

## <a name="client-library"></a><span data-ttu-id="c3ee4-109">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="c3ee4-109">Client library</span></span>

<span data-ttu-id="c3ee4-110">クライアント ライブラリを使用して、Data Lake Store アカウントでのフォルダーの作成、ファイルのアップロード、ファイルのダウンロードなどのファイルシステム操作を、Data Lake Store に対して行います。</span><span class="sxs-lookup"><span data-stu-id="c3ee4-110">Use the client library to perform filesystem operations on Data Lake Store, such as creating folders in a Data Lake Store account, uploading files, and downloading files.</span></span>  <span data-ttu-id="c3ee4-111">.NET での Data Lake Store の使用に関する詳細なチュートリアルについては、「[.NET SDK を使用した Azure Data Lake Store に対するファイルシステム操作](/azure/data-lake-store/data-lake-store-data-operations-net-sdk)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c3ee4-111">For a full tutorial on using Data Lake Store with .NET, see [Filesystem operations on Azure Data Lake Store using .NET SDK](/azure/data-lake-store/data-lake-store-data-operations-net-sdk).</span></span>

<span data-ttu-id="c3ee4-112">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="c3ee4-112">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="c3ee4-113">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="c3ee4-113">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.DataLake.Store
```

```bash
dotnet add package Microsoft.Azure.DataLake.Store
```
### <a name="authentication"></a><span data-ttu-id="c3ee4-114">認証</span><span class="sxs-lookup"><span data-stu-id="c3ee4-114">Authentication</span></span>

* <span data-ttu-id="c3ee4-115">アプリケーションのエンドユーザー認証については、「[End-user authentication with Data Lake Store using .NET SDK (.NET SDK を使用した Data Lake Store に対するエンドユーザー認証)](/azure/data-lake-store/data-lake-store-end-user-authenticate-net-sdk)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c3ee4-115">For end-user authentication for your application, see [End-user authentication with Data Lake Store using .NET SDK](/azure/data-lake-store/data-lake-store-end-user-authenticate-net-sdk).</span></span>
* <span data-ttu-id="c3ee4-116">アプリケーションのサービス間認証については、「[Service-to-service authentication with Data Lake Store using .NET SDK (.NET SDK を使用した Data Lake Store に対するサービス間認証)](/azure/data-lake-store/data-lake-store-service-to-service-authenticate-net-sdk)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c3ee4-116">For service-to-service authentication for your application, see [Service-to-service authentication with Data Lake Store using .NET SDK](/azure/data-lake-store/data-lake-store-service-to-service-authenticate-net-sdk).</span></span>

### <a name="code-example"></a><span data-ttu-id="c3ee4-117">コード例</span><span class="sxs-lookup"><span data-stu-id="c3ee4-117">Code Example</span></span>

<span data-ttu-id="c3ee4-118">次のスニペットを使用して、サービスに要求を発行するために使用される Data Lake Store ファイルシステム クライアント オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="c3ee4-118">The following snippet creates the Data Lake Store filesystem client object, which is used to issue requests to the service.</span></span>

```csharp
// Create client objects
AdlsClient client = AdlsClient.CreateClient(_adlsAccountName, adlCreds);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="c3ee4-119">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="c3ee4-119">Explore the client APIs</span></span>](/dotnet/api/overview/azure/datalakestore/client)


## <a name="management-library"></a><span data-ttu-id="c3ee4-120">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="c3ee4-120">Management library</span></span>

<span data-ttu-id="c3ee4-121">ビッグ データ リポジトリに接続し、リポジトリを管理するには、管理ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="c3ee4-121">Use the management library to connect to and manage your big data repositories.</span></span>

<span data-ttu-id="c3ee4-122">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="c3ee4-122">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="c3ee4-123">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="c3ee4-123">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.DataLake.Store
```

```bash
dotnet add package Microsoft.Azure.Management.DataLake.Store
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="c3ee4-124">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="c3ee4-124">Explore the client APIs</span></span>](/dotnet/api/overview/azure/datalakestore/management)


## <a name="samples"></a><span data-ttu-id="c3ee4-125">サンプル</span><span class="sxs-lookup"><span data-stu-id="c3ee4-125">Samples</span></span>

* [<span data-ttu-id="c3ee4-126">Azure Data Lake .NET クライアントのサンプル</span><span class="sxs-lookup"><span data-stu-id="c3ee4-126">Azure Data Lake .NET Client Example</span></span>](https://azure.microsoft.com/en-us/resources/samples/data-lake-dotnet-client/)

<span data-ttu-id="c3ee4-127">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="c3ee4-127">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
