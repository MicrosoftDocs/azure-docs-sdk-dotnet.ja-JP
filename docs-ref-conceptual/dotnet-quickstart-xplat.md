---
title: "Azure 開発者向け .NET"
description: "Azure 開発者向け .NET"
keywords: "Azure .NET, SDK, Azure .NET API リファレンス, Azure .NET クラス ライブラリ"
author: camsoper
manager: douge
ms.author: casoper
ms.date: 06/20/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.assetid: 
ms.openlocfilehash: 14374182ee0511e942940797465858b94ec08876
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="get-started-with-net-cli-tools-for-azure-developers"></a><span data-ttu-id="72c0f-104">Azure 開発者向け .NET CLI ツールの概要</span><span class="sxs-lookup"><span data-stu-id="72c0f-104">Get started with .NET CLI tools for Azure developers</span></span>

<span data-ttu-id="72c0f-105">このチュートリアルでは、.NET Core を使って、Microsoft Azure アプリケーションをビルドし、デプロイする手順について説明します。</span><span class="sxs-lookup"><span data-stu-id="72c0f-105">This tutorial will walk you through building and deploying a Microsoft Azure application using .NET Core.</span></span>  <span data-ttu-id="72c0f-106">このチュートリアルを完了すると、ASP.NET MVC Core で ビルドされ、Azure Web アプリとしてホストされた Web ベースの To Do アプリケーションを使用できるようになります。このアプリケーションは、データ ストレージに Azure CosmosDB を使用します。</span><span class="sxs-lookup"><span data-stu-id="72c0f-106">When finished, you'll have a web-based to-do application built in ASP.NET MVC Core, hosted as an Azure Web App, and using Azure CosmosDB for data storage.</span></span>

## <a name="prerequisites"></a><span data-ttu-id="72c0f-107">前提条件</span><span class="sxs-lookup"><span data-stu-id="72c0f-107">Prerequisites</span></span>

* <span data-ttu-id="72c0f-108">[Microsoft Azure サブスクリプション](https://azure.microsoft.com/free/)</span><span class="sxs-lookup"><span data-stu-id="72c0f-108">A [Microsoft Azure subscription](https://azure.microsoft.com/free/)</span></span>
* [<span data-ttu-id="72c0f-109">.NET Core</span><span class="sxs-lookup"><span data-stu-id="72c0f-109">.NET Core</span></span>](https://www.microsoft.com/net/download/core) (オプション)
* [<span data-ttu-id="72c0f-110">Azure CLI 2.0</span><span class="sxs-lookup"><span data-stu-id="72c0f-110">Azure CLI 2.0</span></span>](/cli/azure/install-az-cli2) (オプション)
* [<span data-ttu-id="72c0f-111">Git</span><span class="sxs-lookup"><span data-stu-id="72c0f-111">Git</span></span>](https://www.git-scm.com/) コマンド ライン クライアント (オプション)

<span data-ttu-id="72c0f-112">[Azure Cloud Shell](/azure/cloud-shell/) には、このチュートリアルのオプションの前提条件がすべてプレインストールされています。</span><span class="sxs-lookup"><span data-stu-id="72c0f-112">The [Azure Cloud Shell](/azure/cloud-shell/) has all of the optional prerequisites for this tutorial preinstalled.</span></span>  <span data-ttu-id="72c0f-113">チュートリアルをローカルに実行する場合にのみ、上記のオプション コンポーネントをインストールする必要があります。</span><span class="sxs-lookup"><span data-stu-id="72c0f-113">You only need to install the optional components above if you wish to run the tutorial locally.</span></span>  <span data-ttu-id="72c0f-114">Cloud Shell をすぐに起動するには、下のコード ブロックの右上にある **[試してみる]** ボタンをクリックしてください。</span><span class="sxs-lookup"><span data-stu-id="72c0f-114">To quickly launch the Cloud Shell, just click the **Try it** button in the top-right of any of the below code blocks.</span></span>

## <a name="create-a-cosmosdb-account"></a><span data-ttu-id="72c0f-115">CosmosDB アカウントを作成する</span><span class="sxs-lookup"><span data-stu-id="72c0f-115">Create a CosmosDB account</span></span>

<span data-ttu-id="72c0f-116">このチュートリアルでは、CosmosDB をデータ ストレージに使うので、アカウントを作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="72c0f-116">CosmosDB is used for data storage in this tutorial, so you'll need to create an account.</span></span>  <span data-ttu-id="72c0f-117">ローカルまたは Cloud Shell で次のスクリプトを実行して、Azure CosmosDB DocumentDB API アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="72c0f-117">Run this script locally or in the Cloud Shell to create an Azure CosmosDB DocumentDB API account.</span></span>

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

## <a name="download-and-configure-the-application"></a><span data-ttu-id="72c0f-118">アプリケーションをダウンロードして構成する</span><span class="sxs-lookup"><span data-stu-id="72c0f-118">Download and configure the application</span></span>

<span data-ttu-id="72c0f-119">デプロイしようとしているアプリケーションは、ASP.NET MVC Core と CosmosDB クライアント ライブラリを使って作成されている[簡単な To Do アプリ](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/)です。</span><span class="sxs-lookup"><span data-stu-id="72c0f-119">The application you're going to deploy is a [simple to-do app](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/) written using ASP.NET MVC Core using the CosmosDB client libraries.</span></span>  <span data-ttu-id="72c0f-120">このチュートリアルのコードを入手し、実際の CosmosDB の情報で構成してください。</span><span class="sxs-lookup"><span data-stu-id="72c0f-120">Now you'll get the code for this tutorial and configure it with your CosmosDB information.</span></span>

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
> <span data-ttu-id="72c0f-121">この環境でこれまでに `git commit` を実行したことがない場合は、ID の設定を求められることがあります。</span><span class="sxs-lookup"><span data-stu-id="72c0f-121">If you've never run `git commit` in this environment before, you may be prompted to set your identity.</span></span> <span data-ttu-id="72c0f-122">画面に表示される手順に従った後、`git commit` コマンドを再実行してください。</span><span class="sxs-lookup"><span data-stu-id="72c0f-122">Follow the on-screen instructions and then re-run the `git commit` command.</span></span>

<span data-ttu-id="72c0f-123">NuGet パッケージを復元して、アプリケーションをビルドします。</span><span class="sxs-lookup"><span data-stu-id="72c0f-123">Restore the NuGet packages and build the application.</span></span>

```azurecli-interactive
dotnet restore
dotnet build
```

> [!TIP]
> <span data-ttu-id="72c0f-124">自分のコンピューターでツールを使っている場合は、`dotnet run` を実行し、表示される `localhost` アドレスを参照することで、アプリケーションをテストできます。</span><span class="sxs-lookup"><span data-stu-id="72c0f-124">If you are using the tools on your own machine, you can test the application by running `dotnet run` and browsing to the displayed `localhost` address.</span></span>  <span data-ttu-id="72c0f-125">ただし、Cloud Shell でこのアドレスを参照することはできません。</span><span class="sxs-lookup"><span data-stu-id="72c0f-125">You are not able to browse to this address in the Cloud Shell, however.</span></span>  

## <a name="configure-azure-app-service-and-deploy-the-web-app"></a><span data-ttu-id="72c0f-126">Azure App Service を構成して Web アプリをデプロイする</span><span class="sxs-lookup"><span data-stu-id="72c0f-126">Configure Azure App Service and deploy the web app</span></span>

<span data-ttu-id="72c0f-127">Web アプリケーションのダウンロードとビルドが済めば、アプリケーションを Azure Web アプリとしてデプロイできる状態になります。</span><span class="sxs-lookup"><span data-stu-id="72c0f-127">You've successfully downloaded and built the web application, and you're ready to deploy it as an Azure Web App.</span></span>  <span data-ttu-id="72c0f-128">最初に Web アプリのリソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="72c0f-128">You'll start by creating the Web App resource.</span></span>

```azurecli-interactive
# Generate a unique Web App name
let randomNum=$RANDOM*$RANDOM
webappname=todoApp$randomNum

# Create an App Service plan.
az appservice plan create --name $webappname --resource-group DotNetAzureTutorial --sku FREE

# Create the Web App
az webapp create --name $webappname --resource-group DotNetAzureTutorial --plan $webappname

```

<span data-ttu-id="72c0f-129">デプロイする前に、アカウント レベルのデプロイ資格情報を設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="72c0f-129">Before you deploy, you need to set the account-level deployment credentials.</span></span>  <span data-ttu-id="72c0f-130">以下のスクリプトを使い、ユーザー名とパスワードを実際の値に置き換えます。</span><span class="sxs-lookup"><span data-stu-id="72c0f-130">Use the script below, making sure to include your own values for the user name and password.</span></span>

```azurecli-interactive
az webapp deployment user set --user-name <desired user name> --password <desired password>
```

<span data-ttu-id="72c0f-131">最後に、Azure にアプリケーションをデプロイします。</span><span class="sxs-lookup"><span data-stu-id="72c0f-131">Finally, deploy the application to Azure.</span></span>  <span data-ttu-id="72c0f-132">先ほど作成したパスワードを入力するように求められます。</span><span class="sxs-lookup"><span data-stu-id="72c0f-132">You will be prompted for the password you created above.</span></span>

```azurecli-interactive
# Get the Git deployment URL
giturl=$(az webapp deployment source config-local-git -n $webappname -g DotNetAzureTutorial --query [url] -o tsv)

# Add the URL as a Git remote repository
git remote add azure $giturl

# Push the local repository to the remote
git push azure master
```

<span data-ttu-id="72c0f-133">アプリケーションはリモートでビルドおよびデプロイされます。</span><span class="sxs-lookup"><span data-stu-id="72c0f-133">The application will be built remotely and deployed.</span></span>  <span data-ttu-id="72c0f-134">`https://<web app name>.azurewebsites.net` を参照してアプリケーションをテストします。</span><span class="sxs-lookup"><span data-stu-id="72c0f-134">Test the application by browsing to `https://<web app name>.azurewebsites.net`.</span></span>  <span data-ttu-id="72c0f-135">アドレスをコンソールに表示するには、次のようにします。</span><span class="sxs-lookup"><span data-stu-id="72c0f-135">To display the address in the console, use the following:</span></span>

```azurecli-interactive
az webapp show -n $webappname -g DotNetAzureTutorial --query defaultHostName -o tsv
```

<span data-ttu-id="72c0f-136">**[Create New]** をクリックすると、To Do リストに新しい項目を追加できます。</span><span class="sxs-lookup"><span data-stu-id="72c0f-136">You can add new items to the to-do list by clicking **Create New**.</span></span>

![完成したアプリ](./media/dotnet-quickstart/todo.png)

## <a name="clean-up"></a><span data-ttu-id="72c0f-138">クリーンアップ</span><span class="sxs-lookup"><span data-stu-id="72c0f-138">Clean up</span></span>

<span data-ttu-id="72c0f-139">アプリのテストおよびコードとリソースの検査が完了したら、リソース グループを削除することで、Web アプリと CosmosDB アカウントを削除できます。</span><span class="sxs-lookup"><span data-stu-id="72c0f-139">When you're done testing the app and inspecting the code and resources, you can delete the Web App and CosmosDB account by deleting the resource group.</span></span>

```azurecli-interactive
az group delete -n DotNetAzureTutorial
```

## <a name="next-steps"></a><span data-ttu-id="72c0f-140">次のステップ</span><span class="sxs-lookup"><span data-stu-id="72c0f-140">Next steps</span></span>

* [<span data-ttu-id="72c0f-141">ASP.NET Web アプリケーションで認証に Azure Active Directory を使用する</span><span class="sxs-lookup"><span data-stu-id="72c0f-141">Use Azure Active Directory for authentication in an ASP.NET web application</span></span>](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet)
* [<span data-ttu-id="72c0f-142">Azure SQL Database を使用して Azure Web アプリをビルドする</span><span class="sxs-lookup"><span data-stu-id="72c0f-142">Build an Azure Web App using Azure SQL Database</span></span>](/azure/app-service-web/web-sites-dotnet-get-started)
* [<span data-ttu-id="72c0f-143">Azure Storage で .NET サンプル アプリケーションを試す</span><span class="sxs-lookup"><span data-stu-id="72c0f-143">Try a .NET sample application with Azure Storage</span></span>](/azure/storage/storage-samples-dotnet)


