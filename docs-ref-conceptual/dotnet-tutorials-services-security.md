---
title: Azure アプリのセキュリティ保護に関する .NET チュートリアル
description: Azure で実行する .NET アプリでのアプリケーションのセキュリティと ID の管理に関するチュートリアルです。
ms.date: 10/19/2017
ms.openlocfilehash: 19960efa8faa762f0cde657d702f09a8dcb66e99
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190645"
---
# <a name="tutorials-for-authenticating-users-in-your-net-apps-running-on-azure"></a><span data-ttu-id="6266b-103">Azure で実行する .NET アプリでのユーザーの認証に関するチュートリアル</span><span class="sxs-lookup"><span data-stu-id="6266b-103">Tutorials for authenticating users in your .NET apps running on Azure</span></span>

<span data-ttu-id="6266b-104">次の表では、ユーザーの認証と、Azure で実行する .NET アプリケーションのセキュリティ保護に関する詳細なチュートリアルへのリンクを示します。</span><span class="sxs-lookup"><span data-stu-id="6266b-104">The following table links to in-depth tutorials for authenticating users and securing .NET applications running on Azure.</span></span>

<span data-ttu-id="6266b-105">サンプルのソース コードについては、「[Azure のコード サンプル](https://azure.microsoft.com/resources/samples/?platform=dotnet)」の一覧をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="6266b-105">For sample source code, see the list of [Azure service samples](https://azure.microsoft.com/resources/samples/?platform=dotnet).</span></span>

| | |
|---|---|
|<span data-ttu-id="6266b-106">**Active Directory**</span><span class="sxs-lookup"><span data-stu-id="6266b-106">**Active Directory**</span></span>||
| <span data-ttu-id="6266b-107">[Visual Studio 接続済みサービスを使用して Web アプリケーションに Azure Active Directory を追加する][5]</span><span class="sxs-lookup"><span data-stu-id="6266b-107">[Add Azure Active Directory to your web application by using Visual Studio Connected Services][5]</span></span> | <span data-ttu-id="6266b-108">Visual Studio で Web アプリを Azure AD に接続します</span><span class="sxs-lookup"><span data-stu-id="6266b-108">Connect a web app to Azure AD in Visual Studio</span></span> |
| <span data-ttu-id="6266b-109">[Azure AD を使用した Web アプリへのサインインおよびサインアウト][1]</span><span class="sxs-lookup"><span data-stu-id="6266b-109">[Web app sign-in and sign-out with Azure AD][1]</span></span> | <span data-ttu-id="6266b-110">ADAL ライブラリを使って、ユーザーの ASP.NET へのサインインおよび ASP.NET からのサインアウトを行います。</span><span class="sxs-lookup"><span data-stu-id="6266b-110">Sign users in and out of your ASP.NET with the ADAL library.</span></span> |
| <span data-ttu-id="6266b-111">[Azure AD でのデスクトップ アプリケーションの認証][2]</span><span class="sxs-lookup"><span data-stu-id="6266b-111">[Desktop application authentication with Azure AD][2]</span></span>| <span data-ttu-id="6266b-112">ADAL を使って Windows デスクトップ WPF アプリに Azure AD を統合します。</span><span class="sxs-lookup"><span data-stu-id="6266b-112">Integrate Azure AD into a Windows Desktop WPF app using ADAL.</span></span> | 
| <span data-ttu-id="6266b-113">[Azure AD での Web API の認証][3]</span><span class="sxs-lookup"><span data-stu-id="6266b-113">[Web API authentication with Azure AD][3]</span></span> | <span data-ttu-id="6266b-114">Azure AD からベアラー トークンを使って Web API を保護します。</span><span class="sxs-lookup"><span data-stu-id="6266b-114">Protect a web API using bearer tokens from Azure AD.</span></span> |
|<span data-ttu-id="6266b-115">**Key Vault**</span><span class="sxs-lookup"><span data-stu-id="6266b-115">**Key Vault**</span></span>||
| <span data-ttu-id="6266b-116">[Visual Studio 接続済みサービスを使用して Web アプリケーションに Key Vault を追加する][6]</span><span class="sxs-lookup"><span data-stu-id="6266b-116">[Add Key Vault to your web application by using Visual Studio Connected Services][6]</span></span> | <span data-ttu-id="6266b-117">Visual Studio で Web アプリを Azure Key Vault に接続します</span><span class="sxs-lookup"><span data-stu-id="6266b-117">Connect a web app to Azure Key Vault in Visual Studio</span></span> |
| <span data-ttu-id="6266b-118">[Web アプリケーションから Azure Key Vault を使う][4]</span><span class="sxs-lookup"><span data-stu-id="6266b-118">[Use Azure Key Vault from a Web Application][4]</span></span> | <span data-ttu-id="6266b-119">Web アプリケーションで使うことができるように、Azure Key Vault からシークレットにアクセスします。</span><span class="sxs-lookup"><span data-stu-id="6266b-119">Access a secret from an Azure Key Vault so that it can be used in your web application.</span></span> | 

[1]: /azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet
[2]: /azure/active-directory/develop/active-directory-devquickstarts-dotnet
[3]: /azure/active-directory/develop/active-directory-devquickstarts-webapi-dotnet
[4]: /azure/key-vault/key-vault-use-from-web-application
[5]: /azure/active-directory/develop/vs-active-directory-add-connected-service
[6]: /azure/key-vault/vs-key-vault-add-connected-service