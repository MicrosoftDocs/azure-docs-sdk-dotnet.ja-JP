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
# <a name="azure-container-instances-libraries-for-net"></a><span data-ttu-id="5bfb7-104">.NET 用 Azure Container Instances ライブラリ</span><span class="sxs-lookup"><span data-stu-id="5bfb7-104">Azure Container Instances libraries for .NET</span></span>

<span data-ttu-id="5bfb7-105">.NET 用 Microsoft Azure Container Instances ライブラリを使用して、Azure コンテナー インスタンスを作成し、管理します。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-105">Use the Microsoft Azure Container Instances libraries for .NET to create and manage Azure container instances.</span></span> <span data-ttu-id="5bfb7-106">詳細については、[Azure Container Instances の概要](/azure/container-instances/container-instances-overview)に関するページをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-106">Learn more by reading the [Azure Container Instances overview](/azure/container-instances/container-instances-overview).</span></span>

## <a name="management-library"></a><span data-ttu-id="5bfb7-107">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="5bfb7-107">Management library</span></span>

<span data-ttu-id="5bfb7-108">管理ライブラリを使用して、Azure で Azure コンテナー インスタンスを作成して管理します。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-108">Use the management library to create and manage Azure container instances in Azure.</span></span>

<span data-ttu-id="5bfb7-109">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.ContainerInstance.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.ContainerInstance.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

### <a name="visual-studio-package-manager"></a><span data-ttu-id="5bfb7-110">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="5bfb7-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.ContainerInstance.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.ContainerInstance.Fluent
```

## <a name="examples"></a><span data-ttu-id="5bfb7-111">例</span><span class="sxs-lookup"><span data-stu-id="5bfb7-111">Examples</span></span>

### <a name="create-container-group---single-container"></a><span data-ttu-id="5bfb7-112">コンテナー グループを作成する - 1 つのコンテナー</span><span class="sxs-lookup"><span data-stu-id="5bfb7-112">Create container group - single container</span></span>

<span data-ttu-id="5bfb7-113">この例では、1 つのコンテナーを含むコンテナー グループが作成されます。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-113">This example creates a container group with a single container.</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[create_container_group](~/aci-docs-sample-dotnet/Program.cs#create_container_group "Create single-container group")]

### <a name="create-container-group---multiple-containers"></a><span data-ttu-id="5bfb7-114">コンテナー グループを作成する - 複数のコンテナー</span><span class="sxs-lookup"><span data-stu-id="5bfb7-114">Create container group - multiple containers</span></span>

<span data-ttu-id="5bfb7-115">この例では、アプリケーション コンテナーとサイドカー コンテナーという 2 つのコンテナーを含むコンテナー グループが作成されます。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-115">This example creates a container group with two containers: an application container and a sidecar container.</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[create_container_group_multi](~/aci-docs-sample-dotnet/Program.cs#create_container_group_multi "Create multi-container group")]

### <a name="asynchronous-container-create-with-polling"></a><span data-ttu-id="5bfb7-116">ポーリングを使用して非同期でコンテナーを作成する</span><span class="sxs-lookup"><span data-stu-id="5bfb7-116">Asynchronous container create with polling</span></span>

<span data-ttu-id="5bfb7-117">この例では、1 つのコンテナーを含むコンテナー グループを非同期で作成されます。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-117">This example creates a container group with a single container using the async create method.</span></span> <span data-ttu-id="5bfb7-118">その後、コンテナー グループについて Azure にポーリングが実行され、状態が "実行中" になるまでコンテナー グループの状態が出力されます。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-118">It then polls Azure for the container group, and outputs the container group's status until its state is "Running."</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[create_container_group_polling](~/aci-docs-sample-dotnet/Program.cs#create_container_group_polling "Create single-container group with async and polling")]

### <a name="create-task-based-container-group"></a><span data-ttu-id="5bfb7-119">タスク ベースのコンテナー グループを作成する</span><span class="sxs-lookup"><span data-stu-id="5bfb7-119">Create task-based container group</span></span>

<span data-ttu-id="5bfb7-120">この例では、1 つのタスク ベースのコンテナーを含むコンテナー グループが作成されます。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-120">This example creates a container group with a single task-based container.</span></span> <span data-ttu-id="5bfb7-121">コンテナーは、[再起動ポリシー](/azure/container-instances/container-instances-restart-policy) "Never" と[カスタム コマンド ライン](/azure/container-instances/container-instances-restart-policy#command-line-override)で構成されます。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-121">The container is configured with a [restart policy](/azure/container-instances/container-instances-restart-policy) of "Never" and a [custom command line](/azure/container-instances/container-instances-restart-policy#command-line-override).</span></span>

<span data-ttu-id="5bfb7-122">`echo FOO BAR` など、1 つのコマンドを、複数のコマンド ライン引数を指定して実行する場合、その引数は、1 つの文字列の配列として `WithStartingCommandLines` メソッドに指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-122">If you want to run a single command with several command-line arguments, for example `echo FOO BAR`, you must supply them as a string array to the `WithStartingCommandLines` method.</span></span> <span data-ttu-id="5bfb7-123">例: </span><span class="sxs-lookup"><span data-stu-id="5bfb7-123">For example:</span></span>

`WithStartingCommandLines("echo", "FOO", "BAR")`

<span data-ttu-id="5bfb7-124">ただし、複数のコマンドを、複数の (可能性がある) 引数を指定して実行する場合は、シェルを実行し、チェーンされたコマンドを 1 つの引数として渡す必要があります。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-124">If, however, you want to run multiple commands with (potentially) multiple arguments, you must execute a shell and pass the chained commands as an argument.</span></span> <span data-ttu-id="5bfb7-125">たとえば、これにより `echo` と `tail` コマンドの両方が実行されます。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-125">For example, this executes both an `echo` and a `tail` command:</span></span>

`WithStartingCommandLines("/bin/sh", "-c", "echo FOO BAR && tail -f /dev/null")`

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[create_container_group_task](~/aci-docs-sample-dotnet/Program.cs#create_container_group_task "Run a task-based container")]

### <a name="list-container-groups"></a><span data-ttu-id="5bfb7-126">コンテナー グループの一覧を表示する</span><span class="sxs-lookup"><span data-stu-id="5bfb7-126">List container groups</span></span>

<span data-ttu-id="5bfb7-127">この例では、リソース グループ内のコンテナー グループの一覧が表示されます。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-127">This example lists the container groups in a resource group.</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[list_container_groups](~/aci-docs-sample-dotnet/Program.cs#list_container_groups "List container groups")]

### <a name="get-an-existing-container-group"></a><span data-ttu-id="5bfb7-128">既存のコンテナー グループを取得する</span><span class="sxs-lookup"><span data-stu-id="5bfb7-128">Get an existing container group</span></span>

<span data-ttu-id="5bfb7-129">この例では、リソース グループ内に存在する特定のコンテナー グループが取得され、そのプロパティとその値がいくつか出力されます。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-129">This example gets a specific container group residing in a resource group and then prints a few of its properties and their values.</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[get_container_group](~/aci-docs-sample-dotnet/Program.cs#get_container_group "Get container group")]

### <a name="delete-a-container-group"></a><span data-ttu-id="5bfb7-130">コンテナー グループを削除する</span><span class="sxs-lookup"><span data-stu-id="5bfb7-130">Delete a container group</span></span>

<span data-ttu-id="5bfb7-131">この例では、リソース グループからコンテナー グループが削除されます。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-131">This example deletes a container group from a resource group.</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[delete_container_group](~/aci-docs-sample-dotnet/Program.cs#delete_container_group "Delete container group")]

## <a name="api-reference"></a><span data-ttu-id="5bfb7-132">API リファレンス</span><span class="sxs-lookup"><span data-stu-id="5bfb7-132">API reference</span></span>

> [!div class="nextstepaction"]
> [<span data-ttu-id="5bfb7-133">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="5bfb7-133">Explore the management APIs</span></span>](/dotnet/api/overview/azure/containerinstances/management)

## <a name="samples"></a><span data-ttu-id="5bfb7-134">サンプル</span><span class="sxs-lookup"><span data-stu-id="5bfb7-134">Samples</span></span>

* <span data-ttu-id="5bfb7-135">前の例のソース コードは GitHub で確認できます。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-135">The source code for the preceding examples can be found on GitHub:</span></span>

  <span data-ttu-id="5bfb7-136">[Azure-Samples/aci-docs-sample-dotnet][aci-docs-sample-dotnet]</span><span class="sxs-lookup"><span data-stu-id="5bfb7-136">[Azure-Samples/aci-docs-sample-dotnet][aci-docs-sample-dotnet]</span></span>

* <span data-ttu-id="5bfb7-137">Azure Container Instances のその他のコード サンプル:</span><span class="sxs-lookup"><span data-stu-id="5bfb7-137">More Azure Container Instances code samples:</span></span>

  <span data-ttu-id="5bfb7-138">[Azure のコード サンプル][samples]</span><span class="sxs-lookup"><span data-stu-id="5bfb7-138">[Azure Code Samples][samples]</span></span>

<span data-ttu-id="5bfb7-139">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="5bfb7-139">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
[samples]: https://azure.microsoft.com/resources/samples/?sort=0&term=ACI
[aci-docs-sample-dotnet]: https://github.com/Azure-Samples/aci-docs-sample-dotnet
