---
title: .NET 用 Azure Container Instances ライブラリ
description: .NET 用 Azure Container Instances ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Container Instances, ACI
author: mmacy
ms.author: marsma
manager: jeconnoc
ms.date: 05/25/2018
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: dcontainer-instances
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 033f67a989b0ed6cfcb67a6212c0d5c46c485afa
ms.sourcegitcommit: 4ae9f77a9300a4fe54d0179055ae61191078f207
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/07/2018
ms.locfileid: "34567184"
---
# <a name="azure-container-instances-libraries-for-net"></a>.NET 用 Azure Container Instances ライブラリ

.NET 用 Microsoft Azure Container Instances ライブラリを使用して、Azure コンテナー インスタンスを作成し、管理します。 詳細については、[Azure Container Instances の概要](/azure/container-instances/container-instances-overview)に関するページをご覧ください。

## <a name="management-library"></a>管理ライブラリ

管理ライブラリを使用して、Azure で Azure コンテナー インスタンスを作成して管理します。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.ContainerInstance.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.ContainerInstance.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.ContainerInstance.Fluent
```

## <a name="examples"></a>例

### <a name="create-container-group---single-container"></a>コンテナー グループを作成する - 1 つのコンテナー

この例では、1 つのコンテナーを含むコンテナー グループが作成されます。

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[create_container_group](~/aci-docs-sample-dotnet/Program.cs#create_container_group "Create single-container group")]

### <a name="create-container-group---multiple-containers"></a>コンテナー グループを作成する - 複数のコンテナー

この例では、アプリケーション コンテナーとサイドカー コンテナーという 2 つのコンテナーを含むコンテナー グループが作成されます。

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[create_container_group_multi](~/aci-docs-sample-dotnet/Program.cs#create_container_group_multi "Create multi-container group")]

### <a name="asynchronous-container-create-with-polling"></a>ポーリングを使用して非同期でコンテナーを作成する

この例では、1 つのコンテナーを含むコンテナー グループを非同期で作成されます。 その後、コンテナー グループについて Azure にポーリングが実行され、状態が "実行中" になるまでコンテナー グループの状態が出力されます。

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[create_container_group_polling](~/aci-docs-sample-dotnet/Program.cs#create_container_group_polling "Create single-container group with async and polling")]

### <a name="create-task-based-container-group"></a>タスク ベースのコンテナー グループを作成する

この例では、1 つのタスク ベースのコンテナーを含むコンテナー グループが作成されます。 コンテナーは、[再起動ポリシー](/azure/container-instances/container-instances-restart-policy) "Never" と[カスタム コマンド ライン](/azure/container-instances/container-instances-restart-policy#command-line-override)で構成されます。

`echo FOO BAR` など、1 つのコマンドを、複数のコマンド ライン引数を指定して実行する場合、その引数は、1 つの文字列の配列として `WithStartingCommandLines` メソッドに指定する必要があります。 例: 

`WithStartingCommandLines("echo", "FOO", "BAR")`

ただし、複数のコマンドを、複数の (可能性がある) 引数を指定して実行する場合は、シェルを実行し、チェーンされたコマンドを 1 つの引数として渡す必要があります。 たとえば、これにより `echo` と `tail` コマンドの両方が実行されます。

`WithStartingCommandLines("/bin/sh", "-c", "echo FOO BAR && tail -f /dev/null")`

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[create_container_group_task](~/aci-docs-sample-dotnet/Program.cs#create_container_group_task "Run a task-based container")]

### <a name="list-container-groups"></a>コンテナー グループの一覧を表示する

この例では、リソース グループ内のコンテナー グループの一覧が表示されます。

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[list_container_groups](~/aci-docs-sample-dotnet/Program.cs#list_container_groups "List container groups")]

### <a name="get-an-existing-container-group"></a>既存のコンテナー グループを取得する

この例では、リソース グループ内に存在する特定のコンテナー グループが取得され、そのプロパティとその値がいくつか出力されます。

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[get_container_group](~/aci-docs-sample-dotnet/Program.cs#get_container_group "Get container group")]

### <a name="delete-a-container-group"></a>コンテナー グループを削除する

この例では、リソース グループからコンテナー グループが削除されます。

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[delete_container_group](~/aci-docs-sample-dotnet/Program.cs#delete_container_group "Delete container group")]

## <a name="api-reference"></a>API リファレンス

> [!div class="nextstepaction"]
> [Management API を探す](/dotnet/api/overview/azure/containerinstances/management)

## <a name="samples"></a>サンプル

* 前の例のソース コードは GitHub で確認できます。

  [Azure-Samples/aci-docs-sample-dotnet][aci-docs-sample-dotnet]

* Azure Container Instances のその他のコード サンプル:

  [Azure のコード サンプル][samples]

アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
[samples]: https://azure.microsoft.com/resources/samples/?sort=0&term=ACI
[aci-docs-sample-dotnet]: https://github.com/Azure-Samples/aci-docs-sample-dotnet
