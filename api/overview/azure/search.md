---
title: ".NET 用 Azure Search ライブラリ"
description: ".NET 用 Azure Search ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Search
author: spboyer
ms.author: casoper
manager: douge
ms.date: 07/10/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 5330e0642bc27c97c4acc0857d4b92e6fc2a027c
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-search-libraries-for-net"></a><span data-ttu-id="b6644-104">.NET 用 Azure Search ライブラリ</span><span class="sxs-lookup"><span data-stu-id="b6644-104">Azure Search libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="b6644-105">概要</span><span class="sxs-lookup"><span data-stu-id="b6644-105">Overview</span></span>

<span data-ttu-id="b6644-106">[Azure Search](https://docs.microsoft.com/azure/search/search-what-is-azure-search) は、Web、モバイル、エンタープライズ アプリケーションでデータのリッチな検索エクスペリエンスを提供する、完全に管理されたクラウド検索サービスです。</span><span class="sxs-lookup"><span data-stu-id="b6644-106">[Azure Search](https://docs.microsoft.com/azure/search/search-what-is-azure-search) is a fully managed cloud search service that provides a rich search experience over data in web, mobile, and enterprise applications.</span></span>

## <a name="client-library"></a><span data-ttu-id="b6644-107">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="b6644-107">Client library</span></span>

<span data-ttu-id="b6644-108">検索サービス、インデックス、ドキュメント、または他のオブジェクトに対するインデックス作成操作と検索操作にアクセスし、操作を実行するには、Azure Search クライアント ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="b6644-108">Use the Azure Search client library to access and execute indexing and search operations on a search service, index, documents, or other object.</span></span> <span data-ttu-id="b6644-109">手順の概要については、「[.NET アプリケーションから Azure Search を使用する方法](https://docs.microsoft.com/azure/search/search-howto-dotnet-sdk)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="b6644-109">For a step-by-step introduction, see [How to use Azure Search from a .NET application](https://docs.microsoft.com/azure/search/search-howto-dotnet-sdk).</span></span>

<span data-ttu-id="b6644-110">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Search)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="b6644-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Search) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="b6644-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="b6644-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Search
```

```bash
dotnet add package Microsoft.Azure.Search
```

### <a name="code-example"></a><span data-ttu-id="b6644-112">コード例</span><span class="sxs-lookup"><span data-stu-id="b6644-112">Code Example</span></span>

```csharp
/* Include these 'using' directives:
   using Microsoft.Azure.Search;
   using Microsoft.Azure.Search.Models;
*/

// A service endpoint and an api-key are required on a connection.
// Set them in a config file (not shown) and then connect to the client.
IConfigurationBuilder builder = new ConfigurationBuilder().AddJsonFile("appsettings.json");
IConfigurationRoot configuration = builder.Build();

SearchServiceClient serviceClient = CreateSearchServiceClient(configuration);

// Create an index named hotels
ISearchIndexClient indexClient = serviceClient.Indexes.GetClient("hotels");

```

> [!div class="nextstepaction"]
> [<span data-ttu-id="b6644-113">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="b6644-113">Explore the client APIs</span></span>](/dotnet/api/overview/azure/search/client)


## <a name="management-library"></a><span data-ttu-id="b6644-114">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="b6644-114">Management library</span></span>

<span data-ttu-id="b6644-115">サービスのプロビジョニング、API キーの管理、リソースの調整を行うには、Azure Search 管理ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="b6644-115">Use the Azure Search management library to provision a service, manage api-keys, and adjust resources.</span></span> <span data-ttu-id="b6644-116">サブスクライバーとテナントを識別するために、サービス管理には Azure Resource Manager への依存関係があります。</span><span class="sxs-lookup"><span data-stu-id="b6644-116">Service management has a dependency on Azure Resource Manager for subscriber and tenant identification.</span></span> <span data-ttu-id="b6644-117">通常は、ワークフローをサポートするために、Azure Active Directory での認証とアプリケーションの登録も必要になります。</span><span class="sxs-lookup"><span data-stu-id="b6644-117">Typically, authentication and application registration with Azure Active Directory is also necessary to support the workflow.</span></span> <span data-ttu-id="b6644-118">Azure Search サービスのプロビジョニングの概要については、[Management REST API の使用方法](https://docs.microsoft.com/rest/api/searchmanagement/search-howto-management-rest-api)に関する記事をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="b6644-118">For an introduction to Azure Search service provisioning, see [How to use the Management REST API](https://docs.microsoft.com/rest/api/searchmanagement/search-howto-management-rest-api).</span></span>

<span data-ttu-id="b6644-119">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Search)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="b6644-119">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Search) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="b6644-120">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="b6644-120">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Search
```

```bash
dotnet add package Microsoft.Azure.Management.Search
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="b6644-121">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="b6644-121">Explore the management APIs</span></span>](/dotnet/api/overview/azure/search/management)

## <a name="samples"></a><span data-ttu-id="b6644-122">サンプル</span><span class="sxs-lookup"><span data-stu-id="b6644-122">Samples</span></span>

 + [<span data-ttu-id="b6644-123">Azure Samples / search-dotnet-getting-started</span><span class="sxs-lookup"><span data-stu-id="b6644-123">Azure Samples / search-dotnet-getting-started</span></span>](https://github.com/Azure-Samples/search-dotnet-getting-started)
 + [<span data-ttu-id="b6644-124">Azure Samples / search-dotnet-management-api</span><span class="sxs-lookup"><span data-stu-id="b6644-124">Azure Samples / search-dotnet-management-api</span></span>](https://github.com/Azure-Samples/search-dotnet-management-api)

<span data-ttu-id="b6644-125">その他の検索サンプルについては、Github の [Azure Samples リポジトリ](https://github.com/Azure-Samples/)を参照して下さい。</span><span class="sxs-lookup"><span data-stu-id="b6644-125">Find more search samples in the [Azure samples repository](https://github.com/Azure-Samples/) on Github.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
