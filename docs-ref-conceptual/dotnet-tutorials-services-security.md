---
title: "Azure アプリのセキュリティ保護に関する .NET チュートリアル"
description: "Azure で実行する .NET アプリでのアプリケーションのセキュリティと ID の管理に関するチュートリアルです。"
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: 0cd530ef5f70778571e2f702aebc4a8b43c40e93
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/23/2017
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