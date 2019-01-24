---
title: .NET 用 Azure Container Instances ライブラリ
description: .NET 用 Azure Container Instances ライブラリのリファレンス
ms.date: 06/11/2018
ms.topic: reference
ms.service: container-instances
ms.openlocfilehash: 552746b316f1ba80adce5f55bb22412749fd93bc
ms.sourcegitcommit: 4f7bc5c5cd333e41446a3ebe5639a211d8ac9b90
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/24/2019
ms.locfileid: "54841279"
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

## <a name="example-source"></a>サンプル ソース

以下のコード例をコンテキスト内で確認するには、次の GitHub リポジトリでサンプルを検索してください。

[Azure-Samples/aci-docs-sample-dotnet](https://github.com/Azure-Samples/aci-docs-sample-dotnet)

## <a name="authentication"></a>Authentication

SDK クライアントを認証する最も簡単な方法の 1 つは、[ファイル ベースの認証][sdk-auth]を使う方法です。 ファイル ベースの認証では、[IAzure][iazure] クライアント オブジェクトのインスタンス化時に資格情報ファイルが解析され、Azure での認証時にこれらの資格情報がオブジェクトによって使用されます。 ファイル ベースの認証を使用するには:

1. [Azure CLI](/cli/azure) または [Cloud Shell](https://shell.azure.com/) で資格情報ファイルを作成します。

   `az ad sp create-for-rbac --sdk-auth > my.azureauth`

   [Cloud Shell](https://shell.azure.com/) を使用して資格情報ファイルを生成する場合は、その内容を、お使いの .NET アプリケーションがアクセスできるローカル ファイルにコピーします。

2. `AZURE_AUTH_LOCATION` 環境変数を、生成された資格情報ファイルの完全なパスに設定します。 次に例を示します (Bash シェルの場合)。

   ```bash
   export AZURE_AUTH_LOCATION=/home/yourusername/my.azureauth
   ```

資格情報ファイルを作成し、`AZURE_AUTH_LOCATION` 環境変数を設定したら、[Azure.Authenticate][iazure-authenticate] メソッドを使用して、[IAzure][iazure] クライアント オブジェクトを初期化します。 例のプロジェクトでは、まず `AZURE_AUTH_LOCATION`値を取得し、次に、初期化された `IAzure` クライアント オブジェクト返すメソッドを呼び出します。

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[authenticate](~/aci-docs-sample-dotnet/Program.cs#L29-L35 "Get environment variable")]

サンプル アプリケーションのこのメソッドによって、初期化された[IAzure][iazure] インスタンスが返され、次にこのインスタンスは最初のパラメーターとしてサンプルの他のすべてのメソッドに渡されます。

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[authenticate](~/aci-docs-sample-dotnet/Program.cs#azure_auth "Authenticate IAzure client object")]

Azure の .NET 管理ライブラリで使用できる認証方法の詳細については、「[Authentication in Azure Management Libraries for .NET (.NET 用 Azure 管理ライブラリを使用した認証)][sdk-auth]」を参照してください。

## <a name="create-container-group---single-container"></a>コンテナー グループを作成する - 1 つのコンテナー

この例では、1 つのコンテナーを含むコンテナー グループが作成されます。

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[create_container_group](~/aci-docs-sample-dotnet/Program.cs#create_container_group "Create single-container group")]

## <a name="create-container-group---multiple-containers"></a>コンテナー グループを作成する - 複数のコンテナー

この例では、アプリケーション コンテナーとサイドカー コンテナーという 2 つのコンテナーを含むコンテナー グループが作成されます。

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[create_container_group_multi](~/aci-docs-sample-dotnet/Program.cs#create_container_group_multi "Create multi-container group")]

## <a name="asynchronous-container-create-with-polling"></a>ポーリングを使用して非同期でコンテナーを作成する

この例では、1 つのコンテナーを含むコンテナー グループを非同期で作成されます。 その後、コンテナー グループについて Azure にポーリングが実行され、状態が "実行中" になるまでコンテナー グループの状態が出力されます。

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[create_container_group_polling](~/aci-docs-sample-dotnet/Program.cs#create_container_group_polling "Create single-container group with async and polling")]

## <a name="create-task-based-container-group"></a>タスク ベースのコンテナー グループを作成する

この例では、1 つのタスク ベースのコンテナーを含むコンテナー グループが作成されます。 コンテナーは、[再起動ポリシー](/azure/container-instances/container-instances-restart-policy) "Never" と[カスタム コマンド ライン](/azure/container-instances/container-instances-restart-policy#command-line-override)で構成されます。

`echo FOO BAR` など、1 つのコマンドを、複数のコマンド ライン引数を指定して実行する場合、その引数は、1 つの文字列の配列として `WithStartingCommandLines` メソッドに指定する必要があります。 例: 

`WithStartingCommandLines("echo", "FOO", "BAR")`

ただし、複数のコマンドを、複数の (可能性がある) 引数を指定して実行する場合は、シェルを実行し、チェーンされたコマンドを 1 つの引数として渡す必要があります。 たとえば、これにより `echo` と `tail` コマンドの両方が実行されます。

`WithStartingCommandLines("/bin/sh", "-c", "echo FOO BAR && tail -f /dev/null")`

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[create_container_group_task](~/aci-docs-sample-dotnet/Program.cs#create_container_group_task "Run a task-based container")]

## <a name="list-container-groups"></a>コンテナー グループの一覧を表示する

この例では、リソース グループ内のコンテナー グループの一覧が表示されます。

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[list_container_groups](~/aci-docs-sample-dotnet/Program.cs#list_container_groups "List container groups")]

## <a name="get-an-existing-container-group"></a>既存のコンテナー グループを取得する

この例では、リソース グループ内に存在する特定のコンテナー グループが取得され、そのプロパティとその値がいくつか出力されます。

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[get_container_group](~/aci-docs-sample-dotnet/Program.cs#get_container_group "Get container group")]

## <a name="delete-a-container-group"></a>コンテナー グループを削除する

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

<!-- LINKS - External -->
[aci-docs-sample-dotnet]: https://github.com/Azure-Samples/aci-docs-sample-dotnet
[samples]: https://azure.microsoft.com/resources/samples/?sort=0&term=ACI
[sdk-auth]: https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md

<!-- LINKS - Internal -->
[DotNetCLI]: /dotnet/core/tools/dotnet-add-package
[PackageManager]: /nuget/tools/package-manager-console
[iazure]: /dotnet/api/microsoft.azure.management.fluent.azure
[iazure-authenticate]: /dotnet/api/microsoft.azure.management.fluent.azure.authenticate
