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
# <a name="get-started-with-net-cli-tools-for-azure-developers"></a>Azure 開発者向け .NET CLI ツールの概要

このチュートリアルでは、.NET Core を使って、Microsoft Azure アプリケーションをビルドし、デプロイする手順について説明します。  このチュートリアルを完了すると、ASP.NET MVC Core で ビルドされ、Azure Web アプリとしてホストされた Web ベースの To Do アプリケーションを使用できるようになります。このアプリケーションは、データ ストレージに Azure CosmosDB を使用します。

## <a name="prerequisites"></a>前提条件

* [Microsoft Azure サブスクリプション](https://azure.microsoft.com/free/)
* [.NET Core](https://www.microsoft.com/net/download/core) (オプション)
* [Azure CLI 2.0](/cli/azure/install-az-cli2) (オプション)
* [Git](https://www.git-scm.com/) コマンド ライン クライアント (オプション)

[Azure Cloud Shell](/azure/cloud-shell/) には、このチュートリアルのオプションの前提条件がすべてプレインストールされています。  チュートリアルをローカルに実行する場合にのみ、上記のオプション コンポーネントをインストールする必要があります。  Cloud Shell をすぐに起動するには、下のコード ブロックの右上にある **[試してみる]** ボタンをクリックしてください。

## <a name="create-a-cosmosdb-account"></a>CosmosDB アカウントを作成する

このチュートリアルでは、CosmosDB をデータ ストレージに使うので、アカウントを作成する必要があります。  ローカルまたは Cloud Shell で次のスクリプトを実行して、Azure CosmosDB DocumentDB API アカウントを作成します。

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

## <a name="download-and-configure-the-application"></a>アプリケーションをダウンロードして構成する

デプロイしようとしているアプリケーションは、ASP.NET MVC Core と CosmosDB クライアント ライブラリを使って作成されている[簡単な To Do アプリ](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/)です。  このチュートリアルのコードを入手し、実際の CosmosDB の情報で構成してください。

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
> この環境でこれまでに `git commit` を実行したことがない場合は、ID の設定を求められることがあります。 画面に表示される手順に従った後、`git commit` コマンドを再実行してください。

NuGet パッケージを復元して、アプリケーションをビルドします。

```azurecli-interactive
dotnet restore
dotnet build
```

> [!TIP]
> 自分のコンピューターでツールを使っている場合は、`dotnet run` を実行し、表示される `localhost` アドレスを参照することで、アプリケーションをテストできます。  ただし、Cloud Shell でこのアドレスを参照することはできません。  

## <a name="configure-azure-app-service-and-deploy-the-web-app"></a>Azure App Service を構成して Web アプリをデプロイする

Web アプリケーションのダウンロードとビルドが済めば、アプリケーションを Azure Web アプリとしてデプロイできる状態になります。  最初に Web アプリのリソースを作成します。

```azurecli-interactive
# Generate a unique Web App name
let randomNum=$RANDOM*$RANDOM
webappname=todoApp$randomNum

# Create an App Service plan.
az appservice plan create --name $webappname --resource-group DotNetAzureTutorial --sku FREE

# Create the Web App
az webapp create --name $webappname --resource-group DotNetAzureTutorial --plan $webappname

```

デプロイする前に、アカウント レベルのデプロイ資格情報を設定する必要があります。  以下のスクリプトを使い、ユーザー名とパスワードを実際の値に置き換えます。

```azurecli-interactive
az webapp deployment user set --user-name <desired user name> --password <desired password>
```

最後に、Azure にアプリケーションをデプロイします。  先ほど作成したパスワードを入力するように求められます。

```azurecli-interactive
# Get the Git deployment URL
giturl=$(az webapp deployment source config-local-git -n $webappname -g DotNetAzureTutorial --query [url] -o tsv)

# Add the URL as a Git remote repository
git remote add azure $giturl

# Push the local repository to the remote
git push azure master
```

アプリケーションはリモートでビルドおよびデプロイされます。  `https://<web app name>.azurewebsites.net` を参照してアプリケーションをテストします。  アドレスをコンソールに表示するには、次のようにします。

```azurecli-interactive
az webapp show -n $webappname -g DotNetAzureTutorial --query defaultHostName -o tsv
```

**[Create New]** をクリックすると、To Do リストに新しい項目を追加できます。

![完成したアプリ](./media/dotnet-quickstart/todo.png)

## <a name="clean-up"></a>クリーンアップ

アプリのテストおよびコードとリソースの検査が完了したら、リソース グループを削除することで、Web アプリと CosmosDB アカウントを削除できます。

```azurecli-interactive
az group delete -n DotNetAzureTutorial
```

## <a name="next-steps"></a>次のステップ

* [ASP.NET Web アプリケーションで認証に Azure Active Directory を使用する](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet)
* [Azure SQL Database を使用して Azure Web アプリをビルドする](/azure/app-service-web/web-sites-dotnet-get-started)
* [Azure Storage で .NET サンプル アプリケーションを試す](/azure/storage/storage-samples-dotnet)


