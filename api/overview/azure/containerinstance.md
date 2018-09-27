---
title: .NET 用 Azure Container Instances ライブラリ
description: .NET 用 Azure Container Instances ライブラリのリファレンス
ms.date: 06/11/2018
ms.topic: reference
ms.service: dcontainer-instances
ms.openlocfilehash: 93f537058e0ed11f51cc6cb6cece01da80559822
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190725"
---
# <a name="azure-container-instances-libraries-for-net"></a><span data-ttu-id="02342-103">.NET 用 Azure Container Instances ライブラリ</span><span class="sxs-lookup"><span data-stu-id="02342-103">Azure Container Instances libraries for .NET</span></span>

<span data-ttu-id="02342-104">.NET 用 Microsoft Azure Container Instances ライブラリを使用して、Azure コンテナー インスタンスを作成し、管理します。</span><span class="sxs-lookup"><span data-stu-id="02342-104">Use the Microsoft Azure Container Instances libraries for .NET to create and manage Azure container instances.</span></span> <span data-ttu-id="02342-105">詳細については、[Azure Container Instances の概要](/azure/container-instances/container-instances-overview)に関するページをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="02342-105">Learn more by reading the [Azure Container Instances overview](/azure/container-instances/container-instances-overview).</span></span>

## <a name="management-library"></a><span data-ttu-id="02342-106">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="02342-106">Management library</span></span>

<span data-ttu-id="02342-107">管理ライブラリを使用して、Azure で Azure コンテナー インスタンスを作成して管理します。</span><span class="sxs-lookup"><span data-stu-id="02342-107">Use the management library to create and manage Azure container instances in Azure.</span></span>

<span data-ttu-id="02342-108">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.ContainerInstance.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="02342-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.ContainerInstance.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

### <a name="visual-studio-package-manager"></a><span data-ttu-id="02342-109">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="02342-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.ContainerInstance.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.ContainerInstance.Fluent
```

## <a name="example-source"></a><span data-ttu-id="02342-110">サンプル ソース</span><span class="sxs-lookup"><span data-stu-id="02342-110">Example source</span></span>

<span data-ttu-id="02342-111">以下のコード例をコンテキスト内で確認するには、次の GitHub リポジトリでサンプルを検索してください。</span><span class="sxs-lookup"><span data-stu-id="02342-111">If you'd like to see the following code examples in context, you can find them in the following GitHub repository:</span></span>

[<span data-ttu-id="02342-112">Azure-Samples/aci-docs-sample-dotnet</span><span class="sxs-lookup"><span data-stu-id="02342-112">Azure-Samples/aci-docs-sample-dotnet</span></span>](https://github.com/Azure-Samples/aci-docs-sample-dotnet)

## <a name="authentication"></a><span data-ttu-id="02342-113">Authentication</span><span class="sxs-lookup"><span data-stu-id="02342-113">Authentication</span></span>

<span data-ttu-id="02342-114">SDK クライアントを認証する最も簡単な方法の 1 つは、[ファイル ベースの認証][sdk-auth]を使う方法です。</span><span class="sxs-lookup"><span data-stu-id="02342-114">One of the easiest ways to authenticate SDK clients is with [file-based authentication][sdk-auth].</span></span> <span data-ttu-id="02342-115">ファイル ベースの認証では、[IAzure][iazure] クライアント オブジェクトのインスタンス化時に資格情報ファイルが解析され、Azure での認証時にこれらの資格情報がオブジェクトによって使用されます。</span><span class="sxs-lookup"><span data-stu-id="02342-115">File-based authentication parses a credentials file when instantiating the [IAzure][iazure] client object, which then uses those credentials when authenticating with Azure.</span></span> <span data-ttu-id="02342-116">ファイル ベースの認証を使用するには:</span><span class="sxs-lookup"><span data-stu-id="02342-116">To use file-based authentication:</span></span>

1. <span data-ttu-id="02342-117">[Azure CLI](/cli/azure) または [Cloud Shell](https://shell.azure.com/) で資格情報ファイルを作成します。</span><span class="sxs-lookup"><span data-stu-id="02342-117">Create a credentials file with the [Azure CLI](/cli/azure) or [Cloud Shell](https://shell.azure.com/):</span></span>

   `az ad sp create-for-rbac --sdk-auth > my.azureauth`

   <span data-ttu-id="02342-118">[Cloud Shell](https://shell.azure.com/) を使用して資格情報ファイルを生成する場合は、その内容を、お使いの .NET アプリケーションがアクセスできるローカル ファイルにコピーします。</span><span class="sxs-lookup"><span data-stu-id="02342-118">If you use the [Cloud Shell](https://shell.azure.com/) to generate the credentials file, copy its contents into a local file that your .NET application can access.</span></span>

2. <span data-ttu-id="02342-119">`AZURE_AUTH_LOCATION` 環境変数を、生成された資格情報ファイルの完全なパスに設定します。</span><span class="sxs-lookup"><span data-stu-id="02342-119">Set the `AZURE_AUTH_LOCATION` environment variable to the full path of the generated credentials file.</span></span> <span data-ttu-id="02342-120">次に例を示します (Bash シェルの場合)。</span><span class="sxs-lookup"><span data-stu-id="02342-120">For example (in the Bash shell):</span></span>

   ```bash
   export AZURE_AUTH_LOCATION=/home/yourusername/my.azureauth
   ```

<span data-ttu-id="02342-121">資格情報ファイルを作成し、`AZURE_AUTH_LOCATION` 環境変数を設定したら、[Azure.Authenticate][iazure-authenticate] メソッドを使用して、[IAzure][iazure] クライアント オブジェクトを初期化します。</span><span class="sxs-lookup"><span data-stu-id="02342-121">Once you've created the credentials file and populated the `AZURE_AUTH_LOCATION` environment variable, use the [Azure.Authenticate][iazure-authenticate] method to initialize the [IAzure][iazure] client object.</span></span> <span data-ttu-id="02342-122">例のプロジェクトでは、まず `AZURE_AUTH_LOCATION`値を取得し、次に、初期化された `IAzure` クライアント オブジェクト返すメソッドを呼び出します。</span><span class="sxs-lookup"><span data-stu-id="02342-122">The example project first obtains the `AZURE_AUTH_LOCATION` value, then calls a method that returns an initialized `IAzure` client object:</span></span>

<span data-ttu-id="02342-123"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[authenticate](~/aci-docs-sample-dotnet/Program.cs#L29-L35 "Get environment variable")]</span><span class="sxs-lookup"><span data-stu-id="02342-123"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[authenticate](~/aci-docs-sample-dotnet/Program.cs#L29-L35 "Get environment variable")]</span></span>

<span data-ttu-id="02342-124">サンプル アプリケーションのこのメソッドによって、初期化された[IAzure][iazure] インスタンスが返され、次にこのインスタンスは最初のパラメーターとしてサンプルの他のすべてのメソッドに渡されます。</span><span class="sxs-lookup"><span data-stu-id="02342-124">This method from the sample application returns the initialized [IAzure][iazure] instance, which is then passed as the first parameter to all other methods in the sample:</span></span>

<span data-ttu-id="02342-125"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[authenticate](~/aci-docs-sample-dotnet/Program.cs#azure_auth "Authenticate IAzure client object")]</span><span class="sxs-lookup"><span data-stu-id="02342-125"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[authenticate](~/aci-docs-sample-dotnet/Program.cs#azure_auth "Authenticate IAzure client object")]</span></span>

<span data-ttu-id="02342-126">Azure の .NET 管理ライブラリで使用できる認証方法の詳細については、「[Authentication in Azure Management Libraries for .NET (.NET 用 Azure 管理ライブラリを使用した認証)][sdk-auth]」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="02342-126">For more details about the available authentication methods in the .NET management libraries for Azure, see [Authentication in Azure Management Libraries for .NET][sdk-auth].</span></span>

## <a name="create-container-group---single-container"></a><span data-ttu-id="02342-127">コンテナー グループを作成する - 1 つのコンテナー</span><span class="sxs-lookup"><span data-stu-id="02342-127">Create container group - single container</span></span>

<span data-ttu-id="02342-128">この例では、1 つのコンテナーを含むコンテナー グループが作成されます。</span><span class="sxs-lookup"><span data-stu-id="02342-128">This example creates a container group with a single container.</span></span>

<span data-ttu-id="02342-129"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[create_container_group](~/aci-docs-sample-dotnet/Program.cs#create_container_group "Create single-container group")]</span><span class="sxs-lookup"><span data-stu-id="02342-129"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[create_container_group](~/aci-docs-sample-dotnet/Program.cs#create_container_group "Create single-container group")]</span></span>

## <a name="create-container-group---multiple-containers"></a><span data-ttu-id="02342-130">コンテナー グループを作成する - 複数のコンテナー</span><span class="sxs-lookup"><span data-stu-id="02342-130">Create container group - multiple containers</span></span>

<span data-ttu-id="02342-131">この例では、アプリケーション コンテナーとサイドカー コンテナーという 2 つのコンテナーを含むコンテナー グループが作成されます。</span><span class="sxs-lookup"><span data-stu-id="02342-131">This example creates a container group with two containers: an application container and a sidecar container.</span></span>

<span data-ttu-id="02342-132"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[create_container_group_multi](~/aci-docs-sample-dotnet/Program.cs#create_container_group_multi "Create multi-container group")]</span><span class="sxs-lookup"><span data-stu-id="02342-132"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[create_container_group_multi](~/aci-docs-sample-dotnet/Program.cs#create_container_group_multi "Create multi-container group")]</span></span>

## <a name="asynchronous-container-create-with-polling"></a><span data-ttu-id="02342-133">ポーリングを使用して非同期でコンテナーを作成する</span><span class="sxs-lookup"><span data-stu-id="02342-133">Asynchronous container create with polling</span></span>

<span data-ttu-id="02342-134">この例では、1 つのコンテナーを含むコンテナー グループを非同期で作成されます。</span><span class="sxs-lookup"><span data-stu-id="02342-134">This example creates a container group with a single container using the async create method.</span></span> <span data-ttu-id="02342-135">その後、コンテナー グループについて Azure にポーリングが実行され、状態が "実行中" になるまでコンテナー グループの状態が出力されます。</span><span class="sxs-lookup"><span data-stu-id="02342-135">It then polls Azure for the container group, and outputs the container group's status until its state is "Running."</span></span>

<span data-ttu-id="02342-136"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[create_container_group_polling](~/aci-docs-sample-dotnet/Program.cs#create_container_group_polling "Create single-container group with async and polling")]</span><span class="sxs-lookup"><span data-stu-id="02342-136"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[create_container_group_polling](~/aci-docs-sample-dotnet/Program.cs#create_container_group_polling "Create single-container group with async and polling")]</span></span>

## <a name="create-task-based-container-group"></a><span data-ttu-id="02342-137">タスク ベースのコンテナー グループを作成する</span><span class="sxs-lookup"><span data-stu-id="02342-137">Create task-based container group</span></span>

<span data-ttu-id="02342-138">この例では、1 つのタスク ベースのコンテナーを含むコンテナー グループが作成されます。</span><span class="sxs-lookup"><span data-stu-id="02342-138">This example creates a container group with a single task-based container.</span></span> <span data-ttu-id="02342-139">コンテナーは、[再起動ポリシー](/azure/container-instances/container-instances-restart-policy) "Never" と[カスタム コマンド ライン](/azure/container-instances/container-instances-restart-policy#command-line-override)で構成されます。</span><span class="sxs-lookup"><span data-stu-id="02342-139">The container is configured with a [restart policy](/azure/container-instances/container-instances-restart-policy) of "Never" and a [custom command line](/azure/container-instances/container-instances-restart-policy#command-line-override).</span></span>

<span data-ttu-id="02342-140">`echo FOO BAR` など、1 つのコマンドを、複数のコマンド ライン引数を指定して実行する場合、その引数は、1 つの文字列の配列として `WithStartingCommandLines` メソッドに指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="02342-140">If you want to run a single command with several command-line arguments, for example `echo FOO BAR`, you must supply them as a string array to the `WithStartingCommandLines` method.</span></span> <span data-ttu-id="02342-141">例: </span><span class="sxs-lookup"><span data-stu-id="02342-141">For example:</span></span>

`WithStartingCommandLines("echo", "FOO", "BAR")`

<span data-ttu-id="02342-142">ただし、複数のコマンドを、複数の (可能性がある) 引数を指定して実行する場合は、シェルを実行し、チェーンされたコマンドを 1 つの引数として渡す必要があります。</span><span class="sxs-lookup"><span data-stu-id="02342-142">If, however, you want to run multiple commands with (potentially) multiple arguments, you must execute a shell and pass the chained commands as an argument.</span></span> <span data-ttu-id="02342-143">たとえば、これにより `echo` と `tail` コマンドの両方が実行されます。</span><span class="sxs-lookup"><span data-stu-id="02342-143">For example, this executes both an `echo` and a `tail` command:</span></span>

`WithStartingCommandLines("/bin/sh", "-c", "echo FOO BAR && tail -f /dev/null")`

<span data-ttu-id="02342-144"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[create_container_group_task](~/aci-docs-sample-dotnet/Program.cs#create_container_group_task "Run a task-based container")]</span><span class="sxs-lookup"><span data-stu-id="02342-144"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[create_container_group_task](~/aci-docs-sample-dotnet/Program.cs#create_container_group_task "Run a task-based container")]</span></span>

## <a name="list-container-groups"></a><span data-ttu-id="02342-145">コンテナー グループの一覧を表示する</span><span class="sxs-lookup"><span data-stu-id="02342-145">List container groups</span></span>

<span data-ttu-id="02342-146">この例では、リソース グループ内のコンテナー グループの一覧が表示されます。</span><span class="sxs-lookup"><span data-stu-id="02342-146">This example lists the container groups in a resource group.</span></span>

<span data-ttu-id="02342-147"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[list_container_groups](~/aci-docs-sample-dotnet/Program.cs#list_container_groups "List container groups")]</span><span class="sxs-lookup"><span data-stu-id="02342-147"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[list_container_groups](~/aci-docs-sample-dotnet/Program.cs#list_container_groups "List container groups")]</span></span>

## <a name="get-an-existing-container-group"></a><span data-ttu-id="02342-148">既存のコンテナー グループを取得する</span><span class="sxs-lookup"><span data-stu-id="02342-148">Get an existing container group</span></span>

<span data-ttu-id="02342-149">この例では、リソース グループ内に存在する特定のコンテナー グループが取得され、そのプロパティとその値がいくつか出力されます。</span><span class="sxs-lookup"><span data-stu-id="02342-149">This example gets a specific container group residing in a resource group and then prints a few of its properties and their values.</span></span>

<span data-ttu-id="02342-150"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[get_container_group](~/aci-docs-sample-dotnet/Program.cs#get_container_group "Get container group")]</span><span class="sxs-lookup"><span data-stu-id="02342-150"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[get_container_group](~/aci-docs-sample-dotnet/Program.cs#get_container_group "Get container group")]</span></span>

## <a name="delete-a-container-group"></a><span data-ttu-id="02342-151">コンテナー グループを削除する</span><span class="sxs-lookup"><span data-stu-id="02342-151">Delete a container group</span></span>

<span data-ttu-id="02342-152">この例では、リソース グループからコンテナー グループが削除されます。</span><span class="sxs-lookup"><span data-stu-id="02342-152">This example deletes a container group from a resource group.</span></span>

<span data-ttu-id="02342-153"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[delete_container_group](~/aci-docs-sample-dotnet/Program.cs#delete_container_group "Delete container group")]</span><span class="sxs-lookup"><span data-stu-id="02342-153"><!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[delete_container_group](~/aci-docs-sample-dotnet/Program.cs#delete_container_group "Delete container group")]</span></span>

## <a name="api-reference"></a><span data-ttu-id="02342-154">API リファレンス</span><span class="sxs-lookup"><span data-stu-id="02342-154">API reference</span></span>

> [!div class="nextstepaction"]
> [<span data-ttu-id="02342-155">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="02342-155">Explore the management APIs</span></span>](/dotnet/api/overview/azure/containerinstances/management)

## <a name="samples"></a><span data-ttu-id="02342-156">サンプル</span><span class="sxs-lookup"><span data-stu-id="02342-156">Samples</span></span>

* <span data-ttu-id="02342-157">前の例のソース コードは GitHub で確認できます。</span><span class="sxs-lookup"><span data-stu-id="02342-157">The source code for the preceding examples can be found on GitHub:</span></span>

  <span data-ttu-id="02342-158">[Azure-Samples/aci-docs-sample-dotnet][aci-docs-sample-dotnet]</span><span class="sxs-lookup"><span data-stu-id="02342-158">[Azure-Samples/aci-docs-sample-dotnet][aci-docs-sample-dotnet]</span></span>

* <span data-ttu-id="02342-159">Azure Container Instances のその他のコード サンプル:</span><span class="sxs-lookup"><span data-stu-id="02342-159">More Azure Container Instances code samples:</span></span>

  <span data-ttu-id="02342-160">[Azure のコード サンプル][samples]</span><span class="sxs-lookup"><span data-stu-id="02342-160">[Azure Code Samples][samples]</span></span>

<span data-ttu-id="02342-161">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="02342-161">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

<!-- LINKS - External -->
[aci-docs-sample-dotnet]: https://github.com/Azure-Samples/aci-docs-sample-dotnet
[samples]: https://azure.microsoft.com/resources/samples/?sort=0&term=ACI
[sdk-auth]: https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md

<!-- LINKS - Internal -->
[DotNetCLI]: /dotnet/core/tools/dotnet-add-package
[PackageManager]: /nuget/tools/package-manager-console
[iazure]: /dotnet/api/microsoft.azure.management.fluent.azure
[iazure-authenticate]: /dotnet/api/microsoft.azure.management.fluent.azure.authenticate
