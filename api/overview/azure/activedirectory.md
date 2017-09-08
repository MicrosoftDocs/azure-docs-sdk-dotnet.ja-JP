---
title: ".NET 用 Azure Active Directory ライブラリ"
description: ".NET 用 Azure Active Directory ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, AAD, Active Directory
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/17/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: adbe907888e49066b6d67a4fb26410a6f6b3b095
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-active-directory-libraries-for-net"></a>.NET 用 Azure Active Directory ライブラリ

## <a name="overview"></a>概要

Azure Active Directory でユーザーをサインオンし、アプリケーションと API へのアクセスを管理します。

Azure Active Directory の概要については、「[Azure AD を使用した ASP.NET Web アプリへのサインインおよびサインアウト](https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet)」をご覧ください。

## <a name="client-library"></a>クライアント ライブラリ

ユーザーまたはアプリケーションを接続し、OAuth2、OpenID Connect、Active Directory Graph API 認証、または [SAML 2.0](https://docs.microsoft.com/azure/active-directory/develop/active-directory-saml-protocol-reference) で認証します。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.IdentityModel.Clients.ActiveDirectory
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.IdentityModel.Clients.ActiveDirectory
```

### <a name="code-example"></a>コード例

デスクトップ アプリケーション用のアクセス トークンを取得します。

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
> [クライアント API を探す](/dotnet/api/overview/azure/activedirectory/client)

### <a name="samples"></a>サンプル

* [OpenID Connect を使って Azure AD テナントからのユーザーを認証する](https://github.com/Azure-Samples/active-directory-dotnet-webapp-openidconnect)
* [Oauth2 を使ってアプリケーションのアクセス許可を持つ Web API を呼び出す](https://github.com/Azure-Samples/active-directory-dotnet-webapp-webapi-oauth2-appidentity)
* [アプリケーションでロールベースのアクセス制御 (RBAC) を使う](https://github.com/Azure-Samples/active-directory-dotnet-webapp-roleclaims)

[Azure Active Directory コード サンプル](https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-code-samples)の完全なコレクションを確認してください。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
