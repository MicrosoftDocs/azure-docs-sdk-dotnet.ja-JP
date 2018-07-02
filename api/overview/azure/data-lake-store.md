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
# <a name="azure-data-lake-store-libraries-for-net"></a>.NET 用 Azure Data Lake Store ライブラリ

## <a name="overview"></a>概要

Azure Data Lake Store は、ビッグ データの分析ワークロードに対応するエンタープライズ規模のハイパースケール リポジトリです。 Azure Data Lake を使用すると、運用分析や調査分析を目的として任意のサイズ、種類、および取り込み速度のデータを 1 か所でキャプチャすることができます。

詳細については、「[Azure Data Lake Store の概要](/azure/data-lake-store/data-lake-store-overview)」をご覧ください。

## <a name="client-library"></a>クライアント ライブラリ

クライアント ライブラリを使用して、Data Lake Store アカウントでのフォルダーの作成、ファイルのアップロード、ファイルのダウンロードなどのファイルシステム操作を、Data Lake Store に対して行います。  .NET での Data Lake Store の使用に関する詳細なチュートリアルについては、「[.NET SDK を使用した Azure Data Lake Store に対するファイルシステム操作](/azure/data-lake-store/data-lake-store-data-operations-net-sdk)」を参照してください。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.DataLake.Store
```

```bash
dotnet add package Microsoft.Azure.DataLake.Store
```
### <a name="authentication"></a>認証

* アプリケーションのエンドユーザー認証については、「[End-user authentication with Data Lake Store using .NET SDK (.NET SDK を使用した Data Lake Store に対するエンドユーザー認証)](/azure/data-lake-store/data-lake-store-end-user-authenticate-net-sdk)」を参照してください。
* アプリケーションのサービス間認証については、「[Service-to-service authentication with Data Lake Store using .NET SDK (.NET SDK を使用した Data Lake Store に対するサービス間認証)](/azure/data-lake-store/data-lake-store-service-to-service-authenticate-net-sdk)」を参照してください。

### <a name="code-example"></a>コード例

次のスニペットを使用して、サービスに要求を発行するために使用される Data Lake Store ファイルシステム クライアント オブジェクトを作成します。

```csharp
// Create client objects
AdlsClient client = AdlsClient.CreateClient(_adlsAccountName, adlCreds);
```

> [!div class="nextstepaction"]
> [クライアント API を探す](/dotnet/api/overview/azure/datalakestore/client)


## <a name="management-library"></a>管理ライブラリ

ビッグ データ リポジトリに接続し、リポジトリを管理するには、管理ライブラリを使用します。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.DataLake.Store
```

```bash
dotnet add package Microsoft.Azure.Management.DataLake.Store
```

> [!div class="nextstepaction"]
> [クライアント API を探す](/dotnet/api/overview/azure/datalakestore/management)


## <a name="samples"></a>サンプル

* [Azure Data Lake .NET クライアントのサンプル](https://azure.microsoft.com/en-us/resources/samples/data-lake-dotnet-client/)

アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
