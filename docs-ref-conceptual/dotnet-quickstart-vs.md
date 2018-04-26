---
title: Visual Studio から Azure へのデプロイ
description: このチュートリアルでは、Visual Studio と .NET を使用して、Microsoft Azure アプリケーションをビルドし、デプロイする手順について説明します。
keywords: Azure .NET, SDK, Azure .NET API リファレンス, Azure .NET クラス ライブラリ
author: camsoper
manager: douge
ms.author: casoper
ms.date: 06/20/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.openlocfilehash: 87f65d8b8b1b1a5184b9d71770c08be472c7e498
ms.sourcegitcommit: e1a0e91988bb849c75e9583a80e3e6d712083785
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/14/2018
---
# <a name="deploy-to-azure-from-visual-studio"></a><span data-ttu-id="f12f7-104">Visual Studio から Azure へのデプロイ</span><span class="sxs-lookup"><span data-stu-id="f12f7-104">Deploy to Azure from Visual Studio</span></span>

<span data-ttu-id="f12f7-105">このチュートリアルでは、Visual Studio と .NET を使用して、Microsoft Azure アプリケーションをビルドし、デプロイする手順について説明します。</span><span class="sxs-lookup"><span data-stu-id="f12f7-105">This tutorial will walk you through building and deploying a Microsoft Azure application using Visual Studio and .NET.</span></span>  <span data-ttu-id="f12f7-106">このチュートリアルを完了すると、ASP.NET MVC Core でビルドされ、Azure Web アプリとしてホストされた Web ベースの To Do アプリケーションを使用できるようになります。このアプリケーションでは、データ ストレージに Azure Cosmos DB を使用します。</span><span class="sxs-lookup"><span data-stu-id="f12f7-106">When finished, you'll have a web-based to-do application built in ASP.NET MVC Core, hosted as an Azure Web App, and using Azure Cosmos DB for data storage.</span></span>

## <a name="prerequisites"></a><span data-ttu-id="f12f7-107">前提条件</span><span class="sxs-lookup"><span data-stu-id="f12f7-107">Prerequisites</span></span>

* [<span data-ttu-id="f12f7-108">Visual Studio 2017</span><span class="sxs-lookup"><span data-stu-id="f12f7-108">Visual Studio 2017</span></span>](https://www.visualstudio.com/downloads/)
* <span data-ttu-id="f12f7-109">[Microsoft Azure サブスクリプション](https://azure.microsoft.com/free/)</span><span class="sxs-lookup"><span data-stu-id="f12f7-109">A [Microsoft Azure subscription](https://azure.microsoft.com/free/)</span></span>

## <a name="create-an-azure-cosmos-db-account"></a><span data-ttu-id="f12f7-110">Azure Cosmos DB アカウントを作成する</span><span class="sxs-lookup"><span data-stu-id="f12f7-110">Create an Azure Cosmos DB account</span></span>

<span data-ttu-id="f12f7-111">このチュートリアルでは、Azure Cosmos DB をデータ ストレージに使用するので、アカウントを作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f12f7-111">Azure Cosmos DB is used for data storage in this tutorial, so you'll need to create an account.</span></span>  <span data-ttu-id="f12f7-112">ローカルまたは Cloud Shell で次のスクリプトを実行して、Azure Cosmos DB SQL API アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="f12f7-112">Run this script locally or in the Cloud Shell to create an Azure Cosmos DB SQL API account.</span></span>  <span data-ttu-id="f12f7-113">次のコード ブロックの **[使ってみる]** をクリックして [Azure Cloud Shell](/azure/cloud-shell/) を起動し、スクリプト ブロックをコピーしてシェルに貼り付けます。</span><span class="sxs-lookup"><span data-stu-id="f12f7-113">Click the **Try it** button on the code block below to launch the [Azure Cloud Shell](/azure/cloud-shell/) and copy/paste the script block into the shell.</span></span>

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
printf "\n\nauthKey: $cosmosAuthKey\nendpoint: $cosmosEndpoint\n\n"

# Done!

```

<span data-ttu-id="f12f7-114">表示されている **authKey** と **endpoint** を書き留めておきます。</span><span class="sxs-lookup"><span data-stu-id="f12f7-114">Make a note of the displayed **authKey** and **endpoint**</span></span> 

## <a name="downloading-and-running-the-application"></a><span data-ttu-id="f12f7-115">アプリケーションをダウンロードして実行する</span><span class="sxs-lookup"><span data-stu-id="f12f7-115">Downloading and running the application</span></span>

<span data-ttu-id="f12f7-116">このチュートリアルのサンプル コードを取得し、Azure Cosmos DB アカウントに接続しましょう。</span><span class="sxs-lookup"><span data-stu-id="f12f7-116">Let's get the sample code for this walkthrough and hook it up to your Azure Cosmos DB account.</span></span>

1. <span data-ttu-id="f12f7-117">サンプル コードをダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="f12f7-117">Download the sample code.</span></span>  <span data-ttu-id="f12f7-118">サンプル コードは [GitHub から取得](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/)できます。また、[git コマンド ライン クライアント](https://git-scm.com/)を使用している場合は、次のコマンドを使用してサンプル コードをローカル コンピューターに複製します。</span><span class="sxs-lookup"><span data-stu-id="f12f7-118">You can [get it from GitHub](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/), or if you have the [git command line client](https://git-scm.com/), clone it to your local machine with the following command:</span></span>

    ```cmd
    git clone https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart
    ```

2. <span data-ttu-id="f12f7-119">Visual Studio で **todo.csproj** を開きます。</span><span class="sxs-lookup"><span data-stu-id="f12f7-119">Open **todo.csproj** in Visual Studio.</span></span>

3. <span data-ttu-id="f12f7-120">Web プロジェクトで **appsettings.json** を開きます。</span><span class="sxs-lookup"><span data-stu-id="f12f7-120">Open **appsettings.json** in the web project.</span></span>  <span data-ttu-id="f12f7-121">次の行を探します。</span><span class="sxs-lookup"><span data-stu-id="f12f7-121">Look for the following lines:</span></span>

    ```json
    "authKey": "AUTHKEYVALUE",
    "endpoint": "ENDPOINTVALUE",
    ```
    <span data-ttu-id="f12f7-122">**AUTHKEYVALUE** と **ENDPOINTVALUE** を、先ほど書き留めた値に置き換えます。</span><span class="sxs-lookup"><span data-stu-id="f12f7-122">Replace **AUTHKEYVALUE** and **ENDPOINTVALUE** with the values you noted earlier.</span></span>

4. <span data-ttu-id="f12f7-123">**F5** キーを押して、プロジェクトの NuGet パッケージを復元し、プロジェクトをビルドしてローカルで実行します。</span><span class="sxs-lookup"><span data-stu-id="f12f7-123">Press **F5** to restore the project's NuGet packages, build the project, and run it locally.</span></span>

<span data-ttu-id="f12f7-124">Web アプリケーションは、ブラウザーでローカルで実行されます。</span><span class="sxs-lookup"><span data-stu-id="f12f7-124">The web application should run locally in your browser.</span></span>  <span data-ttu-id="f12f7-125">**[Create New]** をクリックすると、To Do リストに新しい項目を追加できます。</span><span class="sxs-lookup"><span data-stu-id="f12f7-125">You can add new items to the to-do list by clicking **Create New**.</span></span>  <span data-ttu-id="f12f7-126">アプリケーションで入力したデータは、Azure Cosmos DB アカウントに保存されます。</span><span class="sxs-lookup"><span data-stu-id="f12f7-126">Note the data you enter in the application is being stored in your Azure Cosmos DB account.</span></span>  <span data-ttu-id="f12f7-127">[Azure Portal](https://portal.azure.com) でデータを表示するには、左側のメニューから [Azure Cosmos DB] を選択し、アカウントを選択して、**[データ エクスプローラー]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="f12f7-127">You can view your data in the [Azure portal](https://portal.azure.com) by selecting Azure Cosmos DB from the left menu, selecting your account, and then selecting **Data Explorer**.</span></span>

## <a name="deploying-the-application-as-an-azure-web-app"></a><span data-ttu-id="f12f7-128">アプリケーションを Azure Web アプリとしてデプロイする</span><span class="sxs-lookup"><span data-stu-id="f12f7-128">Deploying the application as an Azure Web App</span></span>

<span data-ttu-id="f12f7-129">Azure Cosmos DB などの Azure サービスを使用するアプリケーションが正常にビルドされました。</span><span class="sxs-lookup"><span data-stu-id="f12f7-129">You've successfully built an application that uses Azure services like Azure Cosmos DB.</span></span>  <span data-ttu-id="f12f7-130">次に、Web アプリケーションをクラウドにデプロイします。</span><span class="sxs-lookup"><span data-stu-id="f12f7-130">Next, we'll deploy our web application to the cloud.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="f12f7-131">Azure サブスクリプションの関連付け先と同じアカウントで Visual Studio にサインインする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f12f7-131">Be sure you're signed into Visual Studio with the same account your Azure subscription is associated with.</span></span>

1. <span data-ttu-id="f12f7-132">Visual Studio のソリューション エクスプローラーで、プロジェクト名を右クリックし、**[発行...]** を選択します。</span><span class="sxs-lookup"><span data-stu-id="f12f7-132">In Visual Studio Solution Explorer, right-click on the project name and select **Publish...**</span></span>

2. <span data-ttu-id="f12f7-133">[発行] ダイアログで、**[Microsoft Azure App Service]** を選択し、**[新規作成]** を選択して、**[発行]** をクリックします。</span><span class="sxs-lookup"><span data-stu-id="f12f7-133">Using the Publish dialog, select **Microsoft Azure App Service**, select **Create New**, and then click **Publish**</span></span>

3. <span data-ttu-id="f12f7-134">[App Service の作成] ダイアログで、次の操作を行います。</span><span class="sxs-lookup"><span data-stu-id="f12f7-134">Complete the Create App Service dialog as follows:</span></span>

    * <span data-ttu-id="f12f7-135">一意の **Web アプリ名**を入力します。</span><span class="sxs-lookup"><span data-stu-id="f12f7-135">Enter a unique **Web App Name**.</span></span>  <span data-ttu-id="f12f7-136">これはアプリの URL の一部になります。</span><span class="sxs-lookup"><span data-stu-id="f12f7-136">This will be part of the URL for your app.</span></span>
    * <span data-ttu-id="f12f7-137">デプロイ先となる Azure **サブスクリプション**を選択します。</span><span class="sxs-lookup"><span data-stu-id="f12f7-137">Select the Azure **Subscription** you're deploying to.</span></span>  <span data-ttu-id="f12f7-138">以前に Cloud Shell にログインしたときと同じサブスクリプションを使用します。</span><span class="sxs-lookup"><span data-stu-id="f12f7-138">Use same subscription with which you were logged into Cloud Shell earlier.</span></span>
    * <span data-ttu-id="f12f7-139">Web アプリケーションの**リソース グループ**として、*DotNetAzureTutorial* を選択します。</span><span class="sxs-lookup"><span data-stu-id="f12f7-139">Select *DotNetAzureTutorial* for the **Resource Group** for your web application.</span></span>
    * <span data-ttu-id="f12f7-140">**App Service プラン**を選択または作成して、アプリケーションの価格を決定します。</span><span class="sxs-lookup"><span data-stu-id="f12f7-140">Select or create an **App Service Plan** to determine the pricing your your application.</span></span>  <span data-ttu-id="f12f7-141">App Service プランの詳細については、[こちら](/azure/app-service/azure-web-sites-web-hosting-plans-in-depth-overview)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="f12f7-141">Here's [more information about App Service Plans](/azure/app-service/azure-web-sites-web-hosting-plans-in-depth-overview).</span></span>

4. <span data-ttu-id="f12f7-142">**[作成]** をクリックしてアプリケーションをデプロイします。</span><span class="sxs-lookup"><span data-stu-id="f12f7-142">Click **Create** to deploy the application.</span></span>  <span data-ttu-id="f12f7-143">デプロイが完了すると、ブラウザーが開き、デプロイされたアプリケーションが表示されます。</span><span class="sxs-lookup"><span data-stu-id="f12f7-143">When deployment is complete, a browser will open with your deployed application.</span></span>

![完成したアプリ](./media/dotnet-quickstart/todo.png)

## <a name="clean-up"></a><span data-ttu-id="f12f7-145">クリーンアップ</span><span class="sxs-lookup"><span data-stu-id="f12f7-145">Clean up</span></span>

<span data-ttu-id="f12f7-146">アプリのテストおよびコードとリソースの検査が完了したら、Cloud Shell でリソース グループを削除することで、Web アプリと Azure Cosmos DB アカウントを削除できます。</span><span class="sxs-lookup"><span data-stu-id="f12f7-146">When you're done testing the app and inspecting the code and resources, you can delete the Web App and Azure Cosmos DB account by deleting the resource group in the Cloud Shell.</span></span>

```azurecli-interactive
az group delete -n DotNetAzureTutorial
```

## <a name="next-steps"></a><span data-ttu-id="f12f7-147">次の手順</span><span class="sxs-lookup"><span data-stu-id="f12f7-147">Next steps</span></span>

* [<span data-ttu-id="f12f7-148">ASP.NET Web アプリケーションで認証に Azure Active Directory を使用する</span><span class="sxs-lookup"><span data-stu-id="f12f7-148">Use Azure Active Directory for authentication in an ASP.NET web application</span></span>](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet)
* [<span data-ttu-id="f12f7-149">Azure SQL Database を使用して Azure Web アプリをビルドする</span><span class="sxs-lookup"><span data-stu-id="f12f7-149">Build an Azure Web App using Azure SQL Database</span></span>](/azure/app-service-web/web-sites-dotnet-get-started)
* [<span data-ttu-id="f12f7-150">Azure Storage で .NET サンプル アプリケーションを試す</span><span class="sxs-lookup"><span data-stu-id="f12f7-150">Try a .NET sample application with Azure Storage</span></span>](/azure/storage/storage-samples-dotnet)


