---
title: "コマンド ラインと .NET Core を使用した Azure へのデプロイ"
description: "この記事では、コマンドライン ツールを使用して Azure App Service に ASP.NET Core アプリケーションをデプロイする方法について説明します。"
keywords: "Azure .NET, SDK, Azure .NET API リファレンス, Azure .NET クラス ライブラリ"
author: camsoper
manager: douge
ms.author: casoper
ms.date: 06/20/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.openlocfilehash: bb5d4958fb4398192d8427391695da1a7b8cc3c8
ms.sourcegitcommit: 3ba0ff4463338a0ab0f3f15a7601b89417c06970
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/05/2018
---
# <a name="deploy-to-azure-from-the-command-line-with-net-core"></a><span data-ttu-id="a4a42-104">コマンド ラインと .NET Core を使用した Azure へのデプロイ</span><span class="sxs-lookup"><span data-stu-id="a4a42-104">Deploy to Azure from the command line with .NET Core</span></span>

<span data-ttu-id="a4a42-105">このチュートリアルでは、.NET Core を使って、Microsoft Azure アプリケーションをビルドし、デプロイする手順について説明します。</span><span class="sxs-lookup"><span data-stu-id="a4a42-105">This tutorial will walk you through building and deploying a Microsoft Azure application using .NET Core.</span></span>  <span data-ttu-id="a4a42-106">終了時には、ASP.NET MVC Core で ビルドされ、Azure Web アプリとしてホストされた Web ベースの To Do アプリケーションが手に入ります。このアプリケーションは、データ ストレージに Azure CosmosDB を使用します。</span><span class="sxs-lookup"><span data-stu-id="a4a42-106">When finished, you'll have a web-based to-do application built in ASP.NET MVC Core, hosted as an Azure Web App, and using Azure CosmosDB for data storage.</span></span>

## <a name="prerequisites"></a><span data-ttu-id="a4a42-107">前提条件</span><span class="sxs-lookup"><span data-stu-id="a4a42-107">Prerequisites</span></span>

* <span data-ttu-id="a4a42-108">[Microsoft Azure サブスクリプション](https://azure.microsoft.com/free/)</span><span class="sxs-lookup"><span data-stu-id="a4a42-108">A [Microsoft Azure subscription](https://azure.microsoft.com/free/)</span></span>
* <span data-ttu-id="a4a42-109">[.NET Core](https://www.microsoft.com/net/download/core) (オプション)</span><span class="sxs-lookup"><span data-stu-id="a4a42-109">[.NET Core](https://www.microsoft.com/net/download/core) (optional)</span></span>
* <span data-ttu-id="a4a42-110">[Azure CLI 2.0](/cli/azure/install-az-cli2) (オプション)</span><span class="sxs-lookup"><span data-stu-id="a4a42-110">[Azure CLI 2.0](/cli/azure/install-az-cli2) (optional)</span></span>
* <span data-ttu-id="a4a42-111">[Git](https://www.git-scm.com/) コマンド ライン クライアント (オプション)</span><span class="sxs-lookup"><span data-stu-id="a4a42-111">[Git](https://www.git-scm.com/) command line client (optional)</span></span>

<span data-ttu-id="a4a42-112">[Azure Cloud Shell](/azure/cloud-shell/) には、このチュートリアルのオプションの前提条件がすべてプレインストールされています。</span><span class="sxs-lookup"><span data-stu-id="a4a42-112">The [Azure Cloud Shell](/azure/cloud-shell/) has all of the optional prerequisites for this tutorial preinstalled.</span></span>  <span data-ttu-id="a4a42-113">チュートリアルをローカルに実行する場合にのみ、上記のオプション コンポーネントをインストールする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a4a42-113">You only need to install the optional components above if you wish to run the tutorial locally.</span></span>  <span data-ttu-id="a4a42-114">Cloud Shell をすぐに起動するには、下のコード ブロックの右上にある **[試してみる]** ボタンをクリックしてください。</span><span class="sxs-lookup"><span data-stu-id="a4a42-114">To quickly launch the Cloud Shell, just click the **Try it** button in the top-right of any of the below code blocks.</span></span>

## <a name="create-a-cosmosdb-account"></a><span data-ttu-id="a4a42-115">CosmosDB アカウントを作成する</span><span class="sxs-lookup"><span data-stu-id="a4a42-115">Create a CosmosDB account</span></span>

<span data-ttu-id="a4a42-116">このチュートリアルでは、CosmosDB をデータ ストレージに使うので、アカウントを作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a4a42-116">CosmosDB is used for data storage in this tutorial, so you'll need to create an account.</span></span>  <span data-ttu-id="a4a42-117">ローカルまたは Cloud Shell で次のスクリプトを実行して、Azure CosmosDB DocumentDB API アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="a4a42-117">Run this script locally or in the Cloud Shell to create an Azure CosmosDB DocumentDB API account.</span></span>

```azurecli-interactive
# Create the DotNetAzureTutorial resource group
az group create --name DotNetAzureTutorial --location EastUS

# Generate a unique name for the account
let randomNum=$RANDOM*$RANDOM
cosmosdbname=dotnettutorial$randomNum

# Create the CosmosDB account
az cosmosdb create --name $cosmosdbname --resource-group DotNetAzureTutorial

# Retrieve the endpoint and key (you'll need these later)
cosmosEndpoint=$(az cosmosdb show -n $cosmosdbname -g DotNetAzureTutorial --query [documentEndpoint] -o tsv)
cosmosAuthKey=$(az cosmosdb list-keys -n $cosmosdbname -g DotNetAzureTutorial --query [primaryMasterKey] -o tsv)

```

## <a name="download-and-configure-the-application"></a><span data-ttu-id="a4a42-118">アプリケーションをダウンロードして構成する</span><span class="sxs-lookup"><span data-stu-id="a4a42-118">Download and configure the application</span></span>

<span data-ttu-id="a4a42-119">デプロイしようとしているアプリケーションは、ASP.NET MVC Core と CosmosDB クライアント ライブラリを使って作成されている[簡単な To Do アプリ](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/)です。</span><span class="sxs-lookup"><span data-stu-id="a4a42-119">The application you're going to deploy is a [simple to-do app](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/) written using ASP.NET MVC Core using the CosmosDB client libraries.</span></span>  <span data-ttu-id="a4a42-120">このチュートリアルのコードを入手し、実際の CosmosDB の情報で構成してください。</span><span class="sxs-lookup"><span data-stu-id="a4a42-120">Now you'll get the code for this tutorial and configure it with your CosmosDB information.</span></span>

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
> <span data-ttu-id="a4a42-121">この環境でこれまでに `git commit` を実行したことがない場合は、ID の設定を求められることがあります。</span><span class="sxs-lookup"><span data-stu-id="a4a42-121">If you've never run `git commit` in this environment before, you may be prompted to set your identity.</span></span> <span data-ttu-id="a4a42-122">画面に表示される手順に従った後、`git commit` コマンドを再実行してください。</span><span class="sxs-lookup"><span data-stu-id="a4a42-122">Follow the on-screen instructions and then re-run the `git commit` command.</span></span>

<span data-ttu-id="a4a42-123">NuGet パッケージを復元して、アプリケーションをビルドします。</span><span class="sxs-lookup"><span data-stu-id="a4a42-123">Restore the NuGet packages and build the application.</span></span>

```azurecli-interactive
dotnet restore
dotnet build
```

> [!TIP]
> <span data-ttu-id="a4a42-124">自分のコンピューターでツールを使っている場合は、`dotnet run` を実行し、表示される `localhost` アドレスを参照することで、アプリケーションをテストできます。</span><span class="sxs-lookup"><span data-stu-id="a4a42-124">If you are using the tools on your own machine, you can test the application by running `dotnet run` and browsing to the displayed `localhost` address.</span></span>  <span data-ttu-id="a4a42-125">ただし、Cloud Shell でこのアドレスを参照することはできません。</span><span class="sxs-lookup"><span data-stu-id="a4a42-125">You are not able to browse to this address in the Cloud Shell, however.</span></span>  

## <a name="configure-azure-app-service-and-deploy-the-web-app"></a><span data-ttu-id="a4a42-126">Azure App Service を構成して Web アプリをデプロイする</span><span class="sxs-lookup"><span data-stu-id="a4a42-126">Configure Azure App Service and deploy the web app</span></span>

<span data-ttu-id="a4a42-127">Web アプリケーションのダウンロードとビルドが済めば、アプリケーションを Azure Web アプリとしてデプロイできる状態になります。</span><span class="sxs-lookup"><span data-stu-id="a4a42-127">You've successfully downloaded and built the web application, and you're ready to deploy it as an Azure Web App.</span></span>  <span data-ttu-id="a4a42-128">最初に Web アプリのリソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="a4a42-128">You'll start by creating the Web App resource.</span></span>

```azurecli-interactive
# Generate a unique Web App name
let randomNum=$RANDOM*$RANDOM
webappname=todoApp$randomNum

# Create an App Service plan.
az appservice plan create --name $webappname --resource-group DotNetAzureTutorial --sku FREE

# Create the Web App
az webapp create --name $webappname --resource-group DotNetAzureTutorial --plan $webappname

```

<span data-ttu-id="a4a42-129">デプロイする前に、アカウント レベルのデプロイ資格情報を設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a4a42-129">Before you deploy, you need to set the account-level deployment credentials.</span></span>  <span data-ttu-id="a4a42-130">以下のスクリプトを使い、ユーザー名とパスワードを実際の値に置き換えます。</span><span class="sxs-lookup"><span data-stu-id="a4a42-130">Use the script below, making sure to include your own values for the user name and password.</span></span>

```azurecli-interactive
az webapp deployment user set --user-name <desired user name> --password <desired password>
```

<span data-ttu-id="a4a42-131">最後に、Azure にアプリケーションをデプロイします。</span><span class="sxs-lookup"><span data-stu-id="a4a42-131">Finally, deploy the application to Azure.</span></span>  <span data-ttu-id="a4a42-132">先ほど作成したパスワードを入力するように求められます。</span><span class="sxs-lookup"><span data-stu-id="a4a42-132">You will be prompted for the password you created above.</span></span>

```azurecli-interactive
# Get the Git deployment URL
giturl=$(az webapp deployment source config-local-git -n $webappname -g DotNetAzureTutorial --query [url] -o tsv)

# Add the URL as a Git remote repository
git remote add azure $giturl

# Push the local repository to the remote
git push azure master
```

<span data-ttu-id="a4a42-133">アプリケーションはリモートでビルドおよびデプロイされます。</span><span class="sxs-lookup"><span data-stu-id="a4a42-133">The application will be built remotely and deployed.</span></span>  <span data-ttu-id="a4a42-134">`https://<web app name>.azurewebsites.net` を参照してアプリケーションをテストします。</span><span class="sxs-lookup"><span data-stu-id="a4a42-134">Test the application by browsing to `https://<web app name>.azurewebsites.net`.</span></span>  <span data-ttu-id="a4a42-135">アドレスをコンソールに表示するには、次のようにします。</span><span class="sxs-lookup"><span data-stu-id="a4a42-135">To display the address in the console, use the following:</span></span>

```azurecli-interactive
az webapp show -n $webappname -g DotNetAzureTutorial --query defaultHostName -o tsv
```

<span data-ttu-id="a4a42-136">**[Create New]** をクリックすると、To Do リストに新しい項目を追加できます。</span><span class="sxs-lookup"><span data-stu-id="a4a42-136">You can add new items to the to-do list by clicking **Create New**.</span></span>

![完成したアプリ](./media/dotnet-quickstart/todo.png)

## <a name="clean-up"></a><span data-ttu-id="a4a42-138">クリーンアップ</span><span class="sxs-lookup"><span data-stu-id="a4a42-138">Clean up</span></span>

<span data-ttu-id="a4a42-139">アプリのテストおよびコードとリソースの検査が完了したら、リソース グループを削除することで、Web アプリと CosmosDB アカウントを削除できます。</span><span class="sxs-lookup"><span data-stu-id="a4a42-139">When you're done testing the app and inspecting the code and resources, you can delete the Web App and CosmosDB account by deleting the resource group.</span></span>

```azurecli-interactive
az group delete -n DotNetAzureTutorial
```

## <a name="next-steps"></a><span data-ttu-id="a4a42-140">次の手順</span><span class="sxs-lookup"><span data-stu-id="a4a42-140">Next steps</span></span>

* [<span data-ttu-id="a4a42-141">ASP.NET Web アプリケーションで認証に Azure Active Directory を使用する</span><span class="sxs-lookup"><span data-stu-id="a4a42-141">Use Azure Active Directory for authentication in an ASP.NET web application</span></span>](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet)
* [<span data-ttu-id="a4a42-142">Azure SQL Database を使用して Azure Web アプリをビルドする</span><span class="sxs-lookup"><span data-stu-id="a4a42-142">Build an Azure Web App using Azure SQL Database</span></span>](/azure/app-service-web/web-sites-dotnet-get-started)
* [<span data-ttu-id="a4a42-143">Azure Storage で .NET サンプル アプリケーションを試す</span><span class="sxs-lookup"><span data-stu-id="a4a42-143">Try a .NET sample application with Azure Storage</span></span>](/azure/storage/storage-samples-dotnet)


