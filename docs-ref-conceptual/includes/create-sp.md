---
ms.service: multiple
ms.date: 9/20/2018
ms.topic: include
ms.openlocfilehash: 5c8cb328802cfb94e944e4241852fb9568e8507f
ms.sourcegitcommit: 70982e900bd4adfbc121eba55d94544f17c6b495
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/06/2018
ms.locfileid: "51196053"
---
Azure Management Libraries for .NET を使うには、Azure サブスクリプション内のリソースの読み取りと作成を行うアクセス許可が、.NET アプリケーションに必要です。 サービス プリンシパルを作成し、その資格情報で実行してこのアクセスを許可するようにアプリを構成してください。 サービス プリンシパルによって、自分の ID に関連付けられた非対話型のアカウントを作成し、アプリの実行に必要な権限だけを付与することができます。

まず、[Azure Cloud Shell](https://shell.azure.com/bash) にログインします。 現在、サービス プリンシパル作成対象のサブスクリプションを使用していることを確認します。 

```azurecli-interactive
az account show
```

サブスクリプション情報が表示されます。

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

正しいサブスクリプションにログインしていない場合は、`az account set -s <name or ID of subscription>` を入力して正しいサブスクリプションを選択します。

次のコマンドを使って、サービス プリンシパルを作成します。

```azurecli-interactive
az ad sp create-for-rbac --sdk-auth
```

サービス プリンシパル情報が JSON として表示されます。

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

後で使用できるように、JSON 出力をコピーして、テキスト エディターに貼り付けます。
