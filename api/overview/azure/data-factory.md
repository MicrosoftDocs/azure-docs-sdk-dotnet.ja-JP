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
# <a name="azure-data-factory-libraries-for-net"></a>.NET 用 Azure Data Factory ライブラリ

## <a name="overview"></a>概要

Azure Data Factory は、クラウドベースのデータ統合サービスです。 Azure Data Factory を使用すると、クラウドにデータ ドリブン ワークフローを作成して、データ移動とデータ変換を調整および自動化できます。

詳細については、「[Azure Data Factory の概要](/azure/data-factory/data-factory-introduction)」をご覧ください。

## <a name="management-library"></a>管理ライブラリ

データ ドリブン ワークフロー (パイプライン) を作成し、スケジュールするには、管理ライブラリを使用します。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactories)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。

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
