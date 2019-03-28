---
ms.service: multiple
ms.date: 9/20/2018
ms.topic: include
ms.openlocfilehash: 5c8cb328802cfb94e944e4241852fb9568e8507f
ms.sourcegitcommit: e534dad2d96b72ab6a9bc4b5567508962bd7e05c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/22/2019
ms.locfileid: "58343331"
---
<span data-ttu-id="2b1dd-101">Azure Management Libraries for .NET を使うには、Azure サブスクリプション内のリソースの読み取りと作成を行うアクセス許可が、.NET アプリケーションに必要です。</span><span class="sxs-lookup"><span data-stu-id="2b1dd-101">Your .NET application needs permissions to read and create resources in your Azure subscription in order to use the Azure Management Libraries for .NET.</span></span> <span data-ttu-id="2b1dd-102">サービス プリンシパルを作成し、その資格情報で実行してこのアクセスを許可するようにアプリを構成してください。</span><span class="sxs-lookup"><span data-stu-id="2b1dd-102">Create a service principal and configure your app to run with its credentials to grant this access.</span></span> <span data-ttu-id="2b1dd-103">サービス プリンシパルによって、自分の ID に関連付けられた非対話型のアカウントを作成し、アプリの実行に必要な権限だけを付与することができます。</span><span class="sxs-lookup"><span data-stu-id="2b1dd-103">Service principals provide a way to create a non-interactive account associated with your identity to which you grant only the privileges your app needs to run.</span></span>

<span data-ttu-id="2b1dd-104">まず、[Azure Cloud Shell](https://shell.azure.com/bash) にログインします。</span><span class="sxs-lookup"><span data-stu-id="2b1dd-104">First, login to [Azure Cloud Shell](https://shell.azure.com/bash).</span></span> <span data-ttu-id="2b1dd-105">現在、サービス プリンシパル作成対象のサブスクリプションを使用していることを確認します。</span><span class="sxs-lookup"><span data-stu-id="2b1dd-105">Verify you are currently using the subscription in which you want the service principal created.</span></span> 

```azurecli-interactive
az account show
```

<span data-ttu-id="2b1dd-106">サブスクリプション情報が表示されます。</span><span class="sxs-lookup"><span data-stu-id="2b1dd-106">Your subscription information is displayed.</span></span>

```json
{
  "environmentName": "AzureCloud",
  "id": "15dbcfa8-4b93-4c9a-881c-6189d39f04d4",
  "isDefault": true,
  "name": "my-subscription",
  "state": "Enabled",
  "tenantId": "43413cc1-5886-4711-9804-8cfea3d1c3ee",
  "user": {
    "cloudShellID": true,
    "name": "jane@contoso.com",
    "type": "user"
  }
}
```

<span data-ttu-id="2b1dd-107">正しいサブスクリプションにログインしていない場合は、`az account set -s <name or ID of subscription>` を入力して正しいサブスクリプションを選択します。</span><span class="sxs-lookup"><span data-stu-id="2b1dd-107">If you're not logged into the correct subscription, select the correct one by typing `az account set -s <name or ID of subscription>`.</span></span>

<span data-ttu-id="2b1dd-108">次のコマンドを使って、サービス プリンシパルを作成します。</span><span class="sxs-lookup"><span data-stu-id="2b1dd-108">Create the service principal with the following command:</span></span>

```azurecli-interactive
az ad sp create-for-rbac --sdk-auth
```

<span data-ttu-id="2b1dd-109">サービス プリンシパル情報が JSON として表示されます。</span><span class="sxs-lookup"><span data-stu-id="2b1dd-109">The service principal information is displayed as JSON.</span></span>

```json
{
  "clientId": "b52dd125-9272-4b21-9862-0be667bdf6dc",
  "clientSecret": "ebc6e170-72b2-4b6f-9de2-99410964d2d0",
  "subscriptionId": "ffa52f27-be12-4cad-b1ea-c2c241b6cceb",
  "tenantId": "72f988bf-86f1-41af-91ab-2d7cd011db47",
  "activeDirectoryEndpointUrl": "https://login.microsoftonline.com",
  "resourceManagerEndpointUrl": "https://management.azure.com/",
  "activeDirectoryGraphResourceId": "https://graph.windows.net/",
  "sqlManagementEndpointUrl": "https://management.core.windows.net:8443/",
  "galleryEndpointUrl": "https://gallery.azure.com/",
  "managementEndpointUrl": "https://management.core.windows.net/"
}
```

<span data-ttu-id="2b1dd-110">後で使用できるように、JSON 出力をコピーして、テキスト エディターに貼り付けます。</span><span class="sxs-lookup"><span data-stu-id="2b1dd-110">Copy and paste the JSON output to a text editor for use later.</span></span>
