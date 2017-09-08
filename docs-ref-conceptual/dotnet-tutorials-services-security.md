---
title: "Azure アプリのセキュリティ保護に関する .NET チュートリアル"
description: "Azure で実行する .NET アプリでのアプリケーションのセキュリティと ID の管理に関するチュートリアルです。"
author: camsoper
manager: douge
ms.devlang: dotnet
ms.topic: article
ms.service: Azure
ms.technology: Azure
ms.date: 06/09/2017
ms.author: casoper
ms.openlocfilehash: 1ac3b8168f8c2b11082536b635fc32b607354711
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="tutorials-for-authenticating-users-in-your-net-apps-running-on-azure"></a>Azure で実行する .NET アプリでのユーザーの認証に関するチュートリアル

次の表では、ユーザーの認証と、Azure で実行する .NET アプリケーションのセキュリティ保護に関する詳細なチュートリアルへのリンクを示します。

サンプルのソース コードについては、「[Azure のコード サンプル](https://azure.microsoft.com/resources/samples/?platform=dotnet)」の一覧をご覧ください。

| | |
|---|---|
|**Active Directory**||
| [Azure AD を使用した Web アプリへのサインインおよびサインアウト][1] | ADAL ライブラリを使って、ユーザーの ASP.NET へのサインインおよび ASP.NET からのサインアウトを行います。
| [Azure AD でのデスクトップ アプリケーションの認証][2]| ADAL を使って Windows デスクトップ WPF アプリに Azure AD を統合します。 | 
| [Azure AD での Web API の認証][3] | Azure AD からベアラー トークンを使って Web API を保護します。 |
|**Key Vault**||
| [Web アプリケーションから Azure Key Vault を使う][4] | Web アプリケーションで使うことができるように、Azure Key Vault からシークレットにアクセスします。 | 

[1]: /azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet
[2]: /azure/active-directory/develop/active-directory-devquickstarts-dotnet
[3]: /azure/active-directory/develop/active-directory-devquickstarts-webapi-dotnet
[4]: /azure/key-vault/key-vault-use-from-web-application