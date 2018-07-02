---
title: .NET 用 Azure Active Directory ライブラリ
description: .NET 用 Azure Active Directory ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, AAD, Active Directory
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: active-directory
ms.custom: devcenter, svc-overview
ms.openlocfilehash: a5a228fcde29dbef6a6e8d0482121ee710b002a4
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065862"
---
# <a name="azure-active-directory-libraries-for-net"></a><span data-ttu-id="12624-104">.NET 用 Azure Active Directory ライブラリ</span><span class="sxs-lookup"><span data-stu-id="12624-104">Azure Active Directory libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="12624-105">概要</span><span class="sxs-lookup"><span data-stu-id="12624-105">Overview</span></span>

<span data-ttu-id="12624-106">Azure Active Directory でユーザーをサインオンし、アプリケーションと API へのアクセスを管理します。</span><span class="sxs-lookup"><span data-stu-id="12624-106">Sign-on users and manage access to applications and APIs with Azure Active Directory.</span></span>

<span data-ttu-id="12624-107">Azure Active Directory の概要については、「[Azure AD を使用した ASP.NET Web アプリへのサインインおよびサインアウト](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="12624-107">To get started with Azure Active Directory, see [ASP.NET web app sign-in and sign-out with Azure AD](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet).</span></span>

## <a name="client-library"></a><span data-ttu-id="12624-108">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="12624-108">Client library</span></span>

<span data-ttu-id="12624-109">ユーザーまたはアプリケーションを接続し、OAuth2、OpenID Connect、Active Directory Graph API 認証、または [SAML 2.0](https://docs.microsoft.com/azure/active-directory/develop/active-directory-saml-protocol-reference) で認証します。</span><span class="sxs-lookup"><span data-stu-id="12624-109">Connect and authenticate users or applications over OAuth2, OpenID Connect, Active Directory Graph API authentication or [SAML 2.0](https://docs.microsoft.com/azure/active-directory/develop/active-directory-saml-protocol-reference).</span></span>

<span data-ttu-id="12624-110">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="12624-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="12624-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="12624-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.IdentityModel.Clients.ActiveDirectory
```

#### <a name="net-core-cli"></a><span data-ttu-id="12624-112">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="12624-112">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.IdentityModel.Clients.ActiveDirectory
```

### <a name="code-example"></a><span data-ttu-id="12624-113">コード例</span><span class="sxs-lookup"><span data-stu-id="12624-113">Code Example</span></span>

<span data-ttu-id="12624-114">デスクトップ アプリケーション用のアクセス トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="12624-114">Retrieve an access token for a desktop application.</span></span>

```csharp
/* Include this "using" directive...
using Microsoft.IdentityModel.Clients.ActiveDirectory;
*/

AuthenticationResult result = null;
AuthenticationContext authContext = new AuthenticationContext("https://someauthority.com");
try
{
    result = await authContext.AcquireTokenAsync(graphResourceId, clientId, redirectUri, new PlatformParameters(PromptBehavior.Auto));
}
catch (AdalException ex)
{
    // An unexpected error occurred, or user canceled the sign in.
    if (ex.ErrorCode != "access_denied")
        MessageBox.Show(ex.Message);

    return;
}
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="12624-115">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="12624-115">Explore the client APIs</span></span>](/dotnet/api/overview/azure/activedirectory/client)

### <a name="samples"></a><span data-ttu-id="12624-116">サンプル</span><span class="sxs-lookup"><span data-stu-id="12624-116">Samples</span></span>

* [<span data-ttu-id="12624-117">OpenID Connect を使って Azure AD テナントからのユーザーを認証する</span><span class="sxs-lookup"><span data-stu-id="12624-117">Use OpenID Connect to authenticate users from an Azure AD tenant</span></span>](https://github.com/Azure-Samples/active-directory-dotnet-webapp-openidconnect)
* [<span data-ttu-id="12624-118">Oauth2 を使ってアプリケーションのアクセス許可を持つ Web API を呼び出す</span><span class="sxs-lookup"><span data-stu-id="12624-118">Use Oauth2 to call a web API with application permissions</span></span>](https://github.com/Azure-Samples/active-directory-dotnet-webapp-webapi-oauth2-appidentity)
* [<span data-ttu-id="12624-119">アプリケーションでロールベースのアクセス制御 (RBAC) を使う</span><span class="sxs-lookup"><span data-stu-id="12624-119">Use role-based access control (RBAC) in an application</span></span>](https://github.com/Azure-Samples/active-directory-dotnet-webapp-roleclaims)

<span data-ttu-id="12624-120">[Azure Active Directory コード サンプル](/azure/active-directory/develop/active-directory-code-samples)の完全なコレクションを確認してください。</span><span class="sxs-lookup"><span data-stu-id="12624-120">Explore the full collection of [Azure Active Directory code samples](/azure/active-directory/develop/active-directory-code-samples).</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
