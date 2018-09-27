---
title: コマンド ラインと .NET Core を使用した Azure へのデプロイ
description: この記事では、コマンドライン ツールを使用して Azure App Service に ASP.NET Core アプリケーションをデプロイする方法について説明します。
ms.date: 06/20/2017
ms.openlocfilehash: a29f5474dcfedc6f8d044f09ad4d54c5be6a371f
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190495"
---
# <a name="deploy-to-azure-from-the-command-line-with-net-core"></a><span data-ttu-id="39d62-103">コマンド ラインと .NET Core を使用した Azure へのデプロイ</span><span class="sxs-lookup"><span data-stu-id="39d62-103">Deploy to Azure from the command line with .NET Core</span></span>

<span data-ttu-id="39d62-104">このチュートリアルでは、.NET Core を使って、Microsoft Azure アプリケーションをビルドし、デプロイする手順について説明します。</span><span class="sxs-lookup"><span data-stu-id="39d62-104">This tutorial will walk you through building and deploying a Microsoft Azure application using .NET Core.</span></span>  <span data-ttu-id="39d62-105">このチュートリアルを完了すると、ASP.NET MVC Core でビルドされ、Azure Web アプリとしてホストされた Web ベースの To Do アプリケーションを使用できるようになります。このアプリケーションでは、データ ストレージに Azure Cosmos DB を使用します。</span><span class="sxs-lookup"><span data-stu-id="39d62-105">When finished, you'll have a web-based to-do application built in ASP.NET MVC Core, hosted as an Azure Web App, and using Azure Cosmos DB for data storage.</span></span>

## <a name="prerequisites"></a><span data-ttu-id="39d62-106">前提条件</span><span class="sxs-lookup"><span data-stu-id="39d62-106">Prerequisites</span></span>

* <span data-ttu-id="39d62-107">[Microsoft Azure サブスクリプション](https://azure.microsoft.com/free/)</span><span class="sxs-lookup"><span data-stu-id="39d62-107">A [Microsoft Azure subscription](https://azure.microsoft.com/free/)</span></span>
* <span data-ttu-id="39d62-108">[.NET Core](https://www.microsoft.com/net/download/core) (オプション)</span><span class="sxs-lookup"><span data-stu-id="39d62-108">[.NET Core](https://www.microsoft.com/net/download/core) (optional)</span></span>
* <span data-ttu-id="39d62-109">[Azure CLI 2.0](/cli/azure/install-az-cli2) (オプション)</span><span class="sxs-lookup"><span data-stu-id="39d62-109">[Azure CLI 2.0](/cli/azure/install-az-cli2) (optional)</span></span>
* <span data-ttu-id="39d62-110">[Git](https://www.git-scm.com/) コマンド ライン クライアント (オプション)</span><span class="sxs-lookup"><span data-stu-id="39d62-110">[Git](https://www.git-scm.com/) command line client (optional)</span></span>

<span data-ttu-id="39d62-111">[Azure Cloud Shell](/azure/cloud-shell/) には、このチュートリアルのオプションの前提条件がすべてプレインストールされています。</span><span class="sxs-lookup"><span data-stu-id="39d62-111">The [Azure Cloud Shell](/azure/cloud-shell/) has all of the optional prerequisites for this tutorial preinstalled.</span></span>  <span data-ttu-id="39d62-112">チュートリアルをローカルに実行する場合にのみ、上記のオプション コンポーネントをインストールする必要があります。</span><span class="sxs-lookup"><span data-stu-id="39d62-112">You only need to install the optional components above if you wish to run the tutorial locally.</span></span>  <span data-ttu-id="39d62-113">Cloud Shell をすぐに起動するには、下のコード ブロックの右上にある **[試してみる]** ボタンをクリックしてください。</span><span class="sxs-lookup"><span data-stu-id="39d62-113">To quickly launch the Cloud Shell, just click the **Try it** button in the top-right of any of the below code blocks.</span></span>

## <a name="create-an-azure-cosmos-db-account"></a><span data-ttu-id="39d62-114">Azure Cosmos DB アカウントを作成する</span><span class="sxs-lookup"><span data-stu-id="39d62-114">Create an Azure Cosmos DB account</span></span>

<span data-ttu-id="39d62-115">このチュートリアルでは、Azure Cosmos DB をデータ ストレージに使用するので、アカウントを作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="39d62-115">Azure Cosmos DB is used for data storage in this tutorial, so you'll need to create an account.</span></span>  <span data-ttu-id="39d62-116">ローカルまたは Cloud Shell で次のスクリプトを実行して、Azure Cosmos DB SQL API アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="39d62-116">Run this script locally or in the Cloud Shell to create an Azure Cosmos DB SQL API account.</span></span>

```azurecli-interactive
# Create the DotNetAzureTutorial resource group
az group create --name DotNetAzureTutorial --location EastUS

# Generate a unique name for the account
let randomNum=$RANDOM*$RANDOM
cosmosdbname=dotnettutorial$randomNum

# Create the Azure Cosmos DB account
az cosmosdb create --name $cosmosdbname --resource-group DotNetAzureTutorial

# Retrieve the endpoint and key (you'll need these later)
cosmosEndpoint=$(az cosmosdb show -n $cosmosdbname -g DotNetAzureTutorial --query [documentEndpoint] -o tsv)
cosmosAuthKey=$(az cosmosdb list-keys -n $cosmosdbname -g DotNetAzureTutorial --query [primaryMasterKey] -o tsv)

```

## <a name="download-and-configure-the-application"></a><span data-ttu-id="39d62-117">アプリケーションをダウンロードして構成する</span><span class="sxs-lookup"><span data-stu-id="39d62-117">Download and configure the application</span></span>

<span data-ttu-id="39d62-118">デプロイしようとしているアプリケーションは、ASP.NET MVC Core と Azure Cosmos DB クライアント ライブラリを使って作成された[簡単な To Do アプリ](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/)です。</span><span class="sxs-lookup"><span data-stu-id="39d62-118">The application you're going to deploy is a [simple to-do app](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/) written using ASP.NET MVC Core using the Azure Cosmos DB client libraries.</span></span>  <span data-ttu-id="39d62-119">このチュートリアルのコードを入手し、実際の Azure Cosmos DB の情報で構成します。</span><span class="sxs-lookup"><span data-stu-id="39d62-119">Now you'll get the code for this tutorial and configure it with your Azure Cosmos DB information.</span></span>

```azurecli-interactive
# Get the code from GitHub
git clone https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart

# Change the working directory
cd dotnet-cosmosdb-quickstart

# Replace authKey and endpoint values in appsettings.json
sed -i "s|AUTHKEYVALUE|$cosmosAuthKey|g" appsettings.json
sed -i "s|ENDPOINTVALUE|$cosmosEndpoint|g" appsettings.json

# Now commit your changes to the local Git repository.
git commit -a -m "Modified settings"

```

> [!NOTE]
> <span data-ttu-id="39d62-120">この環境でこれまでに `git commit` を実行したことがない場合は、ID の設定を求められることがあります。</span><span class="sxs-lookup"><span data-stu-id="39d62-120">If you've never run `git commit` in this environment before, you may be prompted to set your identity.</span></span> <span data-ttu-id="39d62-121">画面に表示される手順に従った後、`git commit` コマンドを再実行してください。</span><span class="sxs-lookup"><span data-stu-id="39d62-121">Follow the on-screen instructions and then re-run the `git commit` command.</span></span>

<span data-ttu-id="39d62-122">NuGet パッケージを復元して、アプリケーションをビルドします。</span><span class="sxs-lookup"><span data-stu-id="39d62-122">Restore the NuGet packages and build the application.</span></span>

```azurecli-interactive
dotnet restore
dotnet build
```

> [!TIP]
> <span data-ttu-id="39d62-123">自分のコンピューターでツールを使っている場合は、`dotnet run` を実行し、表示される `localhost` アドレスを参照することで、アプリケーションをテストできます。</span><span class="sxs-lookup"><span data-stu-id="39d62-123">If you are using the tools on your own machine, you can test the application by running `dotnet run` and browsing to the displayed `localhost` address.</span></span>  <span data-ttu-id="39d62-124">ただし、Cloud Shell でこのアドレスを参照することはできません。</span><span class="sxs-lookup"><span data-stu-id="39d62-124">You are not able to browse to this address in the Cloud Shell, however.</span></span>  

## <a name="configure-azure-app-service-and-deploy-the-web-app"></a><span data-ttu-id="39d62-125">Azure App Service を構成して Web アプリをデプロイする</span><span class="sxs-lookup"><span data-stu-id="39d62-125">Configure Azure App Service and deploy the web app</span></span>

<span data-ttu-id="39d62-126">Web アプリケーションのダウンロードとビルドが済めば、アプリケーションを Azure Web アプリとしてデプロイできる状態になります。</span><span class="sxs-lookup"><span data-stu-id="39d62-126">You've successfully downloaded and built the web application, and you're ready to deploy it as an Azure Web App.</span></span>  <span data-ttu-id="39d62-127">最初に Web アプリのリソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="39d62-127">You'll start by creating the Web App resource.</span></span>

```azurecli-interactive
# Generate a unique Web App name
let randomNum=$RANDOM*$RANDOM
webappname=todoApp$randomNum

# Create an App Service plan.
az appservice plan create --name $webappname --resource-group DotNetAzureTutorial --sku FREE

# Create the Web App
az webapp create --name $webappname --resource-group DotNetAzureTutorial --plan $webappname

```

<span data-ttu-id="39d62-128">デプロイする前に、アカウント レベルのデプロイ資格情報を設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="39d62-128">Before you deploy, you need to set the account-level deployment credentials.</span></span>  <span data-ttu-id="39d62-129">以下のスクリプトを使い、ユーザー名とパスワードを実際の値に置き換えます。</span><span class="sxs-lookup"><span data-stu-id="39d62-129">Use the script below, making sure to include your own values for the user name and password.</span></span>

```azurecli-interactive
az webapp deployment user set --user-name <desired user name> --password <desired password>
```

<span data-ttu-id="39d62-130">最後に、Azure にアプリケーションをデプロイします。</span><span class="sxs-lookup"><span data-stu-id="39d62-130">Finally, deploy the application to Azure.</span></span>  <span data-ttu-id="39d62-131">先ほど作成したパスワードを入力するように求められます。</span><span class="sxs-lookup"><span data-stu-id="39d62-131">You will be prompted for the password you created above.</span></span>

```azurecli-interactive
# Get the Git deployment URL
giturl=$(az webapp deployment source config-local-git -n $webappname -g DotNetAzureTutorial --query [url] -o tsv)

# Add the URL as a Git remote repository
git remote add azure $giturl

# Push the local repository to the remote
git push azure master
```

<span data-ttu-id="39d62-132">アプリケーションはリモートでビルドおよびデプロイされます。</span><span class="sxs-lookup"><span data-stu-id="39d62-132">The application will be built remotely and deployed.</span></span>  <span data-ttu-id="39d62-133">`https://<web app name>.azurewebsites.net` を参照してアプリケーションをテストします。</span><span class="sxs-lookup"><span data-stu-id="39d62-133">Test the application by browsing to `https://<web app name>.azurewebsites.net`.</span></span>  <span data-ttu-id="39d62-134">アドレスをコンソールに表示するには、次のようにします。</span><span class="sxs-lookup"><span data-stu-id="39d62-134">To display the address in the console, use the following:</span></span>

```azurecli-interactive
az webapp show -n $webappname -g DotNetAzureTutorial --query defaultHostName -o tsv
```

<span data-ttu-id="39d62-135">**[Create New]** をクリックすると、To Do リストに新しい項目を追加できます。</span><span class="sxs-lookup"><span data-stu-id="39d62-135">You can add new items to the to-do list by clicking **Create New**.</span></span>

![完成したアプリ](./media/dotnet-quickstart/todo.png)

## <a name="clean-up"></a><span data-ttu-id="39d62-137">クリーンアップ</span><span class="sxs-lookup"><span data-stu-id="39d62-137">Clean up</span></span>

<span data-ttu-id="39d62-138">アプリのテストおよびコードとリソースの検査が完了したら、リソース グループを削除することで、Web アプリと Azure Cosmos DB アカウントを削除できます。</span><span class="sxs-lookup"><span data-stu-id="39d62-138">When you're done testing the app and inspecting the code and resources, you can delete the Web App and Azure Cosmos DB account by deleting the resource group.</span></span>

```azurecli-interactive
az group delete -n DotNetAzureTutorial
```

## <a name="next-steps"></a><span data-ttu-id="39d62-139">次の手順</span><span class="sxs-lookup"><span data-stu-id="39d62-139">Next steps</span></span>

* [<span data-ttu-id="39d62-140">ASP.NET Web アプリケーションで認証に Azure Active Directory を使用する</span><span class="sxs-lookup"><span data-stu-id="39d62-140">Use Azure Active Directory for authentication in an ASP.NET web application</span></span>](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet)
* [<span data-ttu-id="39d62-141">Azure SQL Database を使用して Azure Web アプリをビルドする</span><span class="sxs-lookup"><span data-stu-id="39d62-141">Build an Azure Web App using Azure SQL Database</span></span>](/azure/app-service-web/web-sites-dotnet-get-started)
* [<span data-ttu-id="39d62-142">Azure Storage で .NET サンプル アプリケーションを試す</span><span class="sxs-lookup"><span data-stu-id="39d62-142">Try a .NET sample application with Azure Storage</span></span>](/azure/storage/storage-samples-dotnet)


