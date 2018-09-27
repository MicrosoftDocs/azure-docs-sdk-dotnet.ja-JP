---
title: Visual Studio から Azure へのデプロイ
description: このチュートリアルでは、Visual Studio と .NET を使用して、Microsoft Azure アプリケーションをビルドし、デプロイする手順について説明します。
ms.date: 06/20/2017
ms.openlocfilehash: a4ddaa0dbf1cd71a0de031cc89b299baa381992c
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190426"
---
# <a name="deploy-to-azure-from-visual-studio"></a>Visual Studio から Azure へのデプロイ

このチュートリアルでは、Visual Studio と .NET を使用して、Microsoft Azure アプリケーションをビルドし、デプロイする手順について説明します。  このチュートリアルを完了すると、ASP.NET MVC Core でビルドされ、Azure Web アプリとしてホストされた Web ベースの To Do アプリケーションを使用できるようになります。このアプリケーションでは、データ ストレージに Azure Cosmos DB を使用します。

## <a name="prerequisites"></a>前提条件

* [Visual Studio 2017](https://www.visualstudio.com/downloads/)
* [Microsoft Azure サブスクリプション](https://azure.microsoft.com/free/)

## <a name="create-an-azure-cosmos-db-account"></a>Azure Cosmos DB アカウントを作成する

このチュートリアルでは、Azure Cosmos DB をデータ ストレージに使用するので、アカウントを作成する必要があります。  ローカルまたは Cloud Shell で次のスクリプトを実行して、Azure Cosmos DB SQL API アカウントを作成します。  次のコード ブロックの **[使ってみる]** をクリックして [Azure Cloud Shell](/azure/cloud-shell/) を起動し、スクリプト ブロックをコピーしてシェルに貼り付けます。

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

表示されている **authKey** と **endpoint** を書き留めておきます。 

## <a name="downloading-and-running-the-application"></a>アプリケーションをダウンロードして実行する

このチュートリアルのサンプル コードを取得し、Azure Cosmos DB アカウントに接続しましょう。

1. サンプル コードをダウンロードします。  サンプル コードは [GitHub から取得](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/)できます。また、[git コマンド ライン クライアント](https://git-scm.com/)を使用している場合は、次のコマンドを使用してサンプル コードをローカル コンピューターに複製します。

    ```cmd
    git clone https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart
    ```

2. Visual Studio で **todo.csproj** を開きます。

3. Web プロジェクトで **appsettings.json** を開きます。  次の行を探します。

    ```json
    "authKey": "AUTHKEYVALUE",
    "endpoint": "ENDPOINTVALUE",
    ```
    **AUTHKEYVALUE** と **ENDPOINTVALUE** を、先ほど書き留めた値に置き換えます。

4. **F5** キーを押して、プロジェクトの NuGet パッケージを復元し、プロジェクトをビルドしてローカルで実行します。

Web アプリケーションは、ブラウザーでローカルで実行されます。  **[Create New]** をクリックすると、To Do リストに新しい項目を追加できます。  アプリケーションで入力したデータは、Azure Cosmos DB アカウントに保存されます。  [Azure Portal](https://portal.azure.com) でデータを表示するには、左側のメニューから [Azure Cosmos DB] を選択し、アカウントを選択して、**[データ エクスプローラー]** を選択します。

## <a name="deploying-the-application-as-an-azure-web-app"></a>アプリケーションを Azure Web アプリとしてデプロイする

Azure Cosmos DB などの Azure サービスを使用するアプリケーションが正常にビルドされました。  次に、Web アプリケーションをクラウドにデプロイします。

> [!IMPORTANT]
> Azure サブスクリプションの関連付け先と同じアカウントで Visual Studio にサインインする必要があります。

1. Visual Studio のソリューション エクスプローラーで、プロジェクト名を右クリックし、**[発行...]** を選択します。

2. [発行] ダイアログで、**[Microsoft Azure App Service]** を選択し、**[新規作成]** を選択して、**[発行]** をクリックします。

3. [App Service の作成] ダイアログで、次の操作を行います。

    * 一意の **Web アプリ名**を入力します。  これはアプリの URL の一部になります。
    * デプロイ先となる Azure **サブスクリプション**を選択します。  以前に Cloud Shell にログインしたときと同じサブスクリプションを使用します。
    * Web アプリケーションの**リソース グループ**として、*DotNetAzureTutorial* を選択します。
    * **App Service プラン**を選択または作成して、アプリケーションの価格を決定します。  App Service プランの詳細については、[こちら](/azure/app-service/azure-web-sites-web-hosting-plans-in-depth-overview)をご覧ください。

4. **[作成]** をクリックしてアプリケーションをデプロイします。  デプロイが完了すると、ブラウザーが開き、デプロイされたアプリケーションが表示されます。

![完成したアプリ](./media/dotnet-quickstart/todo.png)

## <a name="clean-up"></a>クリーンアップ

アプリのテストおよびコードとリソースの検査が完了したら、Cloud Shell でリソース グループを削除することで、Web アプリと Azure Cosmos DB アカウントを削除できます。

```azurecli-interactive
az group delete -n DotNetAzureTutorial
```

## <a name="next-steps"></a>次の手順

* [ASP.NET Web アプリケーションで認証に Azure Active Directory を使用する](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet)
* [Azure SQL Database を使用して Azure Web アプリをビルドする](/azure/app-service-web/web-sites-dotnet-get-started)
* [Azure Storage で .NET サンプル アプリケーションを試す](/azure/storage/storage-samples-dotnet)


