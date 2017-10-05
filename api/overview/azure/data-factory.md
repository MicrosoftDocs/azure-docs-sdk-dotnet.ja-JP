---
title: ".NET 用 Azure Data Factory ライブラリ"
description: ".NET 用 Azure Data Factory ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Data Factory
author: camsoper
ms.author: casoper
manager: douge
ms.date: 09/22/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: data-factory
ms.custom: devcenter
ms.openlocfilehash: 6f1a1cf9ac8189af59ff4e3f42dc1d8fb9620ea2
ms.sourcegitcommit: f35939d37f67485b3667739b02621e317db3e391
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/23/2017
---
# <a name="azure-data-factory-libraries-for-net"></a>.NET 用 Azure Data Factory ライブラリ

## <a name="overview"></a>概要

Azure Data Factory は、クラウドベースのデータ統合サービスです。 Azure Data Factory を使用すると、クラウドにデータ ドリブン ワークフローを作成して、データ移動とデータ変換を調整および自動化できます。

詳細については、「[Azure Data Factory の概要](/azure/data-factory/data-factory-introduction)」をご覧ください。

## <a name="management-library---data-factory-v2-preview"></a>管理ライブラリ - Data Factory V2 (プレビュー)

Data Factory V2 (プレビュー) でデータドリブン ワークフロー (パイプライン) を作成し、スケジュールするには、管理ライブラリを使用します。  詳細については、「[Create a data factory and pipeline using .NET SDK (.NET SDK を使用してデータ ファクトリとパイプラインを作成する)](/azure/data-factory/quickstart-create-data-factory-dot-net)」を参照してください。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactory)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
# Get the most recent prerelease package
Install-Package Microsoft.Azure.Management.DataFactory -Prerelease
```

```bash
# Be sure to include the most recent version from the NuGet package page
dotnet add package Microsoft.Azure.Management.DataFactory --version 0.2.0-preview
```

### <a name="code-example"></a>コード例

次の例では、管理ライブラリを使用してデータ ファクトリを作成します。

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
> [Management API を探す](/dotnet/api/microsoft.azure.management.datafactory)

## <a name="management-library---data-factory-v1"></a>管理ライブラリ - Data Factory V1

Data Factory バージョン 1 でデータドリブン ワークフロー (パイプライン) を作成し、スケジュールするには、管理ライブラリを使用します。  詳細については、[Data Factory バージョン 1](/azure/data-factory/v1/data-factory-introduction)のドキュメントを参照してください。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactories)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.DataFactories
```

```bash
dotnet add package Microsoft.Azure.Management.DataFactories
```

### <a name="code-example"></a>コード例

次の例では、管理ライブラリを使用してデータ ファクトリを作成します。

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
> [Management API を探す](/dotnet/api/overview/azure/datafactories/management)

## <a name="samples"></a>サンプル

* Data Factory を使用して洞察を得るための [MyDriving - Azure IoT およびモバイル サンプル アプリケーション](https://azure.microsoft.com/resources/samples/mydriving/)。

アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
