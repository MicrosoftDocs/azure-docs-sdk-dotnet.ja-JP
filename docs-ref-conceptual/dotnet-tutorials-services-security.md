---
title: "Azure アプリのセキュリティ保護に関する .NET チュートリアル"
description: "Azure で実行する .NET アプリでのアプリケーションのセキュリティと ID の管理に関するチュートリアルです。"
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: f7f71e15dcd58473a61cfdf163a10dbc5f4f8d80
ms.sourcegitcommit: 3ba0ff4463338a0ab0f3f15a7601b89417c06970
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/05/2018
---
# <a name="tutorials-for-authenticating-users-in-your-net-apps-running-on-azure"></a><span data-ttu-id="dac52-103">Azure で実行する .NET アプリでのユーザーの認証に関するチュートリアル</span><span class="sxs-lookup"><span data-stu-id="dac52-103">Tutorials for authenticating users in your .NET apps running on Azure</span></span>

<span data-ttu-id="dac52-104">次の表では、ユーザーの認証と、Azure で実行する .NET アプリケーションのセキュリティ保護に関する詳細なチュートリアルへのリンクを示します。</span><span class="sxs-lookup"><span data-stu-id="dac52-104">The following table links to in-depth tutorials for authenticating users and securing .NET applications running on Azure.</span></span>

<span data-ttu-id="dac52-105">サンプルのソース コードについては、「[Azure のコード サンプル](https://azure.microsoft.com/resources/samples/?platform=dotnet)」の一覧をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="dac52-105">For sample source code, see the list of [Azure service samples](https://azure.microsoft.com/resources/samples/?platform=dotnet).</span></span>

| | |
|---|---|
|<span data-ttu-id="dac52-106">**Active Directory**</span><span class="sxs-lookup"><span data-stu-id="dac52-106">**Active Directory**</span></span>||
| <span data-ttu-id="dac52-107">[Azure AD を使用した Web アプリへのサインインおよびサインアウト][1]</span><span class="sxs-lookup"><span data-stu-id="dac52-107">[Web app sign-in and sign-out with Azure AD][1]</span></span> | <span data-ttu-id="dac52-108">ADAL ライブラリを使って、ユーザーの ASP.NET へのサインインおよび ASP.NET からのサインアウトを行います。</span><span class="sxs-lookup"><span data-stu-id="dac52-108">Sign users in and out of your ASP.NET with the ADAL library.</span></span>
| <span data-ttu-id="dac52-109">[Azure AD でのデスクトップ アプリケーションの認証][2]</span><span class="sxs-lookup"><span data-stu-id="dac52-109">[Desktop application authentication with Azure AD][2]</span></span>| <span data-ttu-id="dac52-110">ADAL を使って Windows デスクトップ WPF アプリに Azure AD を統合します。</span><span class="sxs-lookup"><span data-stu-id="dac52-110">Integrate Azure AD into a Windows Desktop WPF app using ADAL.</span></span> | 
| <span data-ttu-id="dac52-111">[Azure AD での Web API の認証][3]</span><span class="sxs-lookup"><span data-stu-id="dac52-111">[Web API authentication with Azure AD][3]</span></span> | <span data-ttu-id="dac52-112">Azure AD からベアラー トークンを使って Web API を保護します。</span><span class="sxs-lookup"><span data-stu-id="dac52-112">Protect a web API using bearer tokens from Azure AD.</span></span> |
|<span data-ttu-id="dac52-113">**Key Vault**</span><span class="sxs-lookup"><span data-stu-id="dac52-113">**Key Vault**</span></span>||
| <span data-ttu-id="dac52-114">[Web アプリケーションから Azure Key Vault を使う][4]</span><span class="sxs-lookup"><span data-stu-id="dac52-114">[Use Azure Key Vault from a Web Application][4]</span></span> | <span data-ttu-id="dac52-115">Web アプリケーションで使うことができるように、Azure Key Vault からシークレットにアクセスします。</span><span class="sxs-lookup"><span data-stu-id="dac52-115">Access a secret from an Azure Key Vault so that it can be used in your web application.</span></span> | 

[1]: /azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet
[2]: /azure/active-directory/develop/active-directory-devquickstarts-dotnet
[3]: /azure/active-directory/develop/active-directory-devquickstarts-webapi-dotnet
[4]: /azure/key-vault/key-vault-use-from-web-application