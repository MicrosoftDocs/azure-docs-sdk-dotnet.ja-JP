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
# <a name="tutorials-for-authenticating-users-in-your-net-apps-running-on-azure"></a><span data-ttu-id="4c1f9-103">Azure で実行する .NET アプリでのユーザーの認証に関するチュートリアル</span><span class="sxs-lookup"><span data-stu-id="4c1f9-103">Tutorials for authenticating users in your .NET apps running on Azure</span></span>

<span data-ttu-id="4c1f9-104">次の表では、ユーザーの認証と、Azure で実行する .NET アプリケーションのセキュリティ保護に関する詳細なチュートリアルへのリンクを示します。</span><span class="sxs-lookup"><span data-stu-id="4c1f9-104">The following table links to in-depth tutorials for authenticating users and securing .NET applications running on Azure.</span></span>

<span data-ttu-id="4c1f9-105">サンプルのソース コードについては、「[Azure のコード サンプル](https://azure.microsoft.com/resources/samples/?platform=dotnet)」の一覧をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="4c1f9-105">For sample source code, see the list of [Azure service samples](https://azure.microsoft.com/resources/samples/?platform=dotnet).</span></span>

| | |
|---|---|
|<span data-ttu-id="4c1f9-106">**Active Directory**</span><span class="sxs-lookup"><span data-stu-id="4c1f9-106">**Active Directory**</span></span>||
| <span data-ttu-id="4c1f9-107">[Azure AD を使用した Web アプリへのサインインおよびサインアウト][1]</span><span class="sxs-lookup"><span data-stu-id="4c1f9-107">[Web app sign-in and sign-out with Azure AD][1]</span></span> | <span data-ttu-id="4c1f9-108">ADAL ライブラリを使って、ユーザーの ASP.NET へのサインインおよび ASP.NET からのサインアウトを行います。</span><span class="sxs-lookup"><span data-stu-id="4c1f9-108">Sign users in and out of your ASP.NET with the ADAL library.</span></span>
| <span data-ttu-id="4c1f9-109">[Azure AD でのデスクトップ アプリケーションの認証][2]</span><span class="sxs-lookup"><span data-stu-id="4c1f9-109">[Desktop application authentication with Azure AD][2]</span></span>| <span data-ttu-id="4c1f9-110">ADAL を使って Windows デスクトップ WPF アプリに Azure AD を統合します。</span><span class="sxs-lookup"><span data-stu-id="4c1f9-110">Integrate Azure AD into a Windows Desktop WPF app using ADAL.</span></span> | 
| <span data-ttu-id="4c1f9-111">[Azure AD での Web API の認証][3]</span><span class="sxs-lookup"><span data-stu-id="4c1f9-111">[Web API authentication with Azure AD][3]</span></span> | <span data-ttu-id="4c1f9-112">Azure AD からベアラー トークンを使って Web API を保護します。</span><span class="sxs-lookup"><span data-stu-id="4c1f9-112">Protect a web API using bearer tokens from Azure AD.</span></span> |
|<span data-ttu-id="4c1f9-113">**Key Vault**</span><span class="sxs-lookup"><span data-stu-id="4c1f9-113">**Key Vault**</span></span>||
| <span data-ttu-id="4c1f9-114">[Web アプリケーションから Azure Key Vault を使う][4]</span><span class="sxs-lookup"><span data-stu-id="4c1f9-114">[Use Azure Key Vault from a Web Application][4]</span></span> | <span data-ttu-id="4c1f9-115">Web アプリケーションで使うことができるように、Azure Key Vault からシークレットにアクセスします。</span><span class="sxs-lookup"><span data-stu-id="4c1f9-115">Access a secret from an Azure Key Vault so that it can be used in your web application.</span></span> | 

[1]: /azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet
[2]: /azure/active-directory/develop/active-directory-devquickstarts-dotnet
[3]: /azure/active-directory/develop/active-directory-devquickstarts-webapi-dotnet
[4]: /azure/key-vault/key-vault-use-from-web-application