---
title: .NET 用 Azure Key Vault ライブラリ
description: .NET 用 Azure Key Vault ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: key-vault
ms.openlocfilehash: a42eb9684bcfb8e8d2209235f61bbf6962cf5e9e
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190555"
---
# <a name="azure-key-vault-libraries-for-net"></a>.NET 用 Azure Key Vault ライブラリ

## <a name="overview"></a>概要

Azure Key Vault は、クラウド アプリケーションやサービスで使用される暗号化キーとシークレットをセキュリティで保護するために役立ちます。

[Key Vault の概要](/azure/key-vault/key-vault-whatis)に関する記事を読み、[Azure Key Vault を使い始める](/azure/key-vault/key-vault-get-started)か、[Web アプリから Key Vault を使用する](/azure/key-vault/key-vault-use-from-web-application)方法を確認します。

## <a name="client-library"></a>クライアント ライブラリ

キーと関連資産 (証明書やシークレットなど) を管理するには、クライアント ライブラリを使用します。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.KeyVault)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.KeyVault
```

```bash
dotnet add package Microsoft.Azure.KeyVault
```

### <a name="example"></a>例

次の例では、アプリケーション設定で指定されている特定のキーのシークレットを取得します。

```csharp
KeyVaultClient kv = new KeyVaultClient(new KeyVaultClient.AuthenticationCallback(securityToken));

SecretBundle sec = await kv.GetSecretAsync(WebConfigurationManager.AppSettings["SecretUri"]);

// sec.Value holds the secret
```

> [!div class="nextstepaction"]
> [クライアント API を探す](/dotnet/api/overview/azure/keyvault/client)

## <a name="management-library"></a>管理ライブラリ

キー コンテナーを作成、削除、照会するには、管理ライブラリを使用します。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.KeyVault.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.KeyVault.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.KeyVault.Fluent
```

### <a name="example"></a>例

次の例は、リソース グループと場所を指定して新しいキー コンテナーを作成する方法を示しています。

```csharp
using (KeyVaultManagementClient client = new KeyVaultManagementClient(
    new TokenCloudCredentials(subscriptionId, accessToken)))
{
    client.Vaults.CreateOrUpdate(resourceGroupName, "myKeyVault", new VaultCreateOrUpdateParameters
    {
        Properties = new VaultProperties
        {
            EnabledForDeployment = true,
            EnabledForDiskEncryption = true,
            EnabledForTemplateDeployment = true,
            Location = resourceGroupLocation,
            // SKU level, access policies, tenants, etc.
        }
    });
}
```

> [!div class="nextstepaction"]
> [Management API を探す](/dotnet/api/overview/azure/keyvault/management)

## <a name="samples"></a>サンプル

* [Azure Key Vault クライアント サンプルのダウンロード](https://www.microsoft.com/download/details.aspx?id=45343)
* [.NET での Azure クライアント側暗号化の概要](https://azure.microsoft.com/resources/samples/storage-dotnet-client-side-encryption/)


アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
