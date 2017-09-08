---
title: ".NET 用 Azure Resource Manager ライブラリ"
description: ".NET 用 Azure Resource Manager ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Resource Manager
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/31/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 4dcfdb59e3cbe919053937a62602de6b602bbac1
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-resource-manager-libraries-for-net"></a>.NET 用 Azure Resource Manager ライブラリ

## <a name="overview"></a>概要

Azure Resource Manager を使用すると、ソリューション内の複数のリソースを 1 つのグループとして作業できます。  Resource Manager について詳しくは、「[Azure Resource Manager の概要](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview)」をご覧ください。

## <a name="management-library"></a>管理ライブラリ

.NET 用 Azure Resource Manager ライブラリを使うと、リソースおよびリソース グループの作成、更新、削除、一覧表示を行うことができます。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.ResourceManager.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.ResourceManager.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.ResourceManager.Fluent
```

### <a name="example"></a>例

この例では、新しいリソース グループを作成します。

```csharp
/* Include these "using" directives.
using Microsoft.Azure.Management.ResourceManager.Fluent
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
*/

IResourceGroup resourceGroup = azure.ResourceGroups
    .Define("ResourceGroupName")
    .WithRegion(Region.USWest)
    .Create();
```

> [!div class="nextstepaction"]
> [Management API を探す](/dotnet/api/overview/azure/resources/management)


## <a name="samples"></a>サンプル

* [リソース グループの管理](https://github.com/Azure-Samples/resources-dotnet-manage-resource-group)
* [リソースの管理](https://github.com/Azure-Samples/resources-dotnet-manage-resource)
* [ARM テンプレートを使ってリソースをデプロイする](https://github.com/Azure-Samples/resources-dotnet-deploy-using-arm-template)
* [ARM テンプレートを使ってリソースをデプロイする (進行状況表示付き)](https://github.com/Azure-Samples/resources-dotnet-deploy-using-arm-template-with-progress)


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
