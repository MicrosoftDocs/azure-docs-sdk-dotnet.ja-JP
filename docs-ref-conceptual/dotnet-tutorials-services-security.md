---
title: Azure アプリのセキュリティ保護に関する .NET チュートリアル
description: Azure で実行する .NET アプリでのアプリケーションのセキュリティと ID の管理に関するチュートリアルです。
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: 88ecfc69fbd57becf1adf1163a063c0d2bb086a8
ms.sourcegitcommit: 61638b504b6c4d96b357894835c80c2680a99fe6
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/17/2018
ms.locfileid: "45750590"
---
# <a name="tutorials-for-authenticating-users-in-your-net-apps-running-on-azure"></a>Azure で実行する .NET アプリでのユーザーの認証に関するチュートリアル

次の表では、ユーザーの認証と、Azure で実行する .NET アプリケーションのセキュリティ保護に関する詳細なチュートリアルへのリンクを示します。

サンプルのソース コードについては、「[Azure のコード サンプル](https://azure.microsoft.com/resources/samples/?platform=dotnet)」の一覧をご覧ください。

| | |
|---|---|
|**Active Directory**||
| [Visual Studio 接続済みサービスを使用して Web アプリケーションに Azure Active Directory を追加する][5] | Visual Studio で Web アプリを Azure AD に接続します |
| [Azure AD を使用した Web アプリへのサインインおよびサインアウト][1] | ADAL ライブラリを使って、ユーザーの ASP.NET へのサインインおよび ASP.NET からのサインアウトを行います。 |
| [Azure AD でのデスクトップ アプリケーションの認証][2]| ADAL を使って Windows デスクトップ WPF アプリに Azure AD を統合します。 | 
| [Azure AD での Web API の認証][3] | Azure AD からベアラー トークンを使って Web API を保護します。 |
|**Key Vault**||
| [Visual Studio 接続済みサービスを使用して Web アプリケーションに Key Vault を追加する][6] | Visual Studio で Web アプリを Azure Key Vault に接続します |
| [Web アプリケーションから Azure Key Vault を使う][4] | Web アプリケーションで使うことができるように、Azure Key Vault からシークレットにアクセスします。 | 

[1]: /azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet
[2]: /azure/active-directory/develop/active-directory-devquickstarts-dotnet
[3]: /azure/active-directory/develop/active-directory-devquickstarts-webapi-dotnet
[4]: /azure/key-vault/key-vault-use-from-web-application
[5]: /azure/active-directory/develop/vs-active-directory-add-connected-service
[6]: /azure/key-vault/vs-key-vault-add-connected-service