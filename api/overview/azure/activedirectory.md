---
title: .NET 用 Azure Active Directory ライブラリ
description: .NET 用 Azure Active Directory ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: active-directory
ms.openlocfilehash: 0226f06546f7dc14b9ab3392008744754d47a19a
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190225"
---
# <a name="azure-active-directory-libraries-for-net"></a>.NET 用 Azure Active Directory ライブラリ

## <a name="overview"></a>概要

Azure Active Directory でユーザーをサインオンし、アプリケーションと API へのアクセスを管理します。

Azure Active Directory の概要については、「[Azure AD を使用した ASP.NET Web アプリへのサインインおよびサインアウト](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet)」をご覧ください。

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

[Azure Active Directory コード サンプル](/azure/active-directory/develop/active-directory-code-samples)の完全なコレクションを確認してください。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
