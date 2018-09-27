---
title: .NET 用 Azure Search ライブラリ
description: .NET 用 Azure Search ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: search
ms.openlocfilehash: cf622ccb59f10a5270c02fa76d7396345fbb1a9b
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190245"
---
# <a name="azure-search-libraries-for-net"></a>.NET 用 Azure Search ライブラリ

## <a name="overview"></a>概要

[Azure Search](https://docs.microsoft.com/azure/search/search-what-is-azure-search) は、Web、モバイル、エンタープライズ アプリケーションでデータのリッチな検索エクスペリエンスを提供する、フル マネージドのクラウド検索サービスです。

## <a name="client-library"></a>クライアント ライブラリ

検索サービス、インデックス、ドキュメント、または他のオブジェクトに対するインデックス作成操作と検索操作にアクセスし、操作を実行するには、Azure Search クライアント ライブラリを使用します。 手順の概要については、「[.NET アプリケーションから Azure Search を使用する方法](https://docs.microsoft.com/azure/search/search-howto-dotnet-sdk)」をご覧ください。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Search)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Search
```

```bash
dotnet add package Microsoft.Azure.Search
```

### <a name="code-example"></a>コード例

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
> [クライアント API を探す](/dotnet/api/overview/azure/search/client)


## <a name="management-library"></a>管理ライブラリ

サービスのプロビジョニング、API キーの管理、リソースの調整を行うには、Azure Search 管理ライブラリを使用します。 サブスクライバーとテナントを識別するために、サービス管理には Azure Resource Manager への依存関係があります。 通常は、ワークフローをサポートするために、Azure Active Directory での認証とアプリケーションの登録も必要になります。 Azure Search サービスのプロビジョニングの概要については、[Management REST API の使用方法](https://docs.microsoft.com/rest/api/searchmanagement/search-howto-management-rest-api)に関する記事をご覧ください。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Search)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.Search
```

```bash
dotnet add package Microsoft.Azure.Management.Search
```

> [!div class="nextstepaction"]
> [Management API を探す](/dotnet/api/overview/azure/search/management)

## <a name="samples"></a>サンプル

 + [Azure Samples / search-dotnet-getting-started](https://github.com/Azure-Samples/search-dotnet-getting-started)
 + [Azure Samples / search-dotnet-management-api](https://github.com/Azure-Samples/search-dotnet-management-api)

その他の検索サンプルについては、Github の [Azure Samples リポジトリ](https://github.com/Azure-Samples/)を参照して下さい。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
