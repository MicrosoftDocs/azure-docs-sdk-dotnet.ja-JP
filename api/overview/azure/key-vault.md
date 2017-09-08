---
title: ".NET 用 Azure Key Vault ライブラリ"
description: ".NET 用 Azure Key Vault ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Key Vault
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/21/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 77a4e710e858bbeb98579a7b540b52b4cb9dd7b0
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-key-vault-libraries-for-net"></a><span data-ttu-id="9584b-104">.NET 用 Azure Key Vault ライブラリ</span><span class="sxs-lookup"><span data-stu-id="9584b-104">Azure Key Vault libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="9584b-105">概要</span><span class="sxs-lookup"><span data-stu-id="9584b-105">Overview</span></span>

<span data-ttu-id="9584b-106">Azure Key Vault は、クラウド アプリケーションやサービスで使用される暗号化キーとシークレットをセキュリティで保護するために役立ちます。</span><span class="sxs-lookup"><span data-stu-id="9584b-106">Azure Key Vault helps safeguard cryptographic keys and secrets used by cloud applications and services.</span></span>

<span data-ttu-id="9584b-107">[Key Vault の概要](/azure/key-vault/key-vault-whatis)に関する記事を読み、[Azure Key Vault を使い始める](/azure/key-vault/key-vault-get-started)か、[Web アプリから Key Vault を使用する](/azure/key-vault/key-vault-use-from-web-application)方法を確認します。</span><span class="sxs-lookup"><span data-stu-id="9584b-107">Read more about [What is Key Vault?](/azure/key-vault/key-vault-whatis) then [Get started with Azure Key Vault](/azure/key-vault/key-vault-get-started) or learn how to [Use Key Vault from a web app](/azure/key-vault/key-vault-use-from-web-application).</span></span>

## <a name="client-library"></a><span data-ttu-id="9584b-108">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="9584b-108">Client library</span></span>

<span data-ttu-id="9584b-109">キーと関連資産 (証明書やシークレットなど) を管理するには、クライアント ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="9584b-109">Use the client library to manage keys and related assets such as certificates and secrets.</span></span>

<span data-ttu-id="9584b-110">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.KeyVault)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="9584b-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.KeyVault) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="9584b-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="9584b-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.KeyVault
```

```bash
dotnet add package Microsoft.Azure.KeyVault
```

### <a name="example"></a><span data-ttu-id="9584b-112">例</span><span class="sxs-lookup"><span data-stu-id="9584b-112">Example</span></span>

<span data-ttu-id="9584b-113">次の例では、アプリケーション設定で指定されている特定のキーのシークレットを取得します。</span><span class="sxs-lookup"><span data-stu-id="9584b-113">The following example retrieves the secret for a specific key that is identified in the application settings.</span></span>

```csharp
KeyVaultClient kv = new KeyVaultClient(new KeyVaultClient.AuthenticationCallback(securityToken));

SecretBundle sec = await kv.GetSecretAsync(WebConfigurationManager.AppSettings["SecretUri"]);

// sec.Value holds the secret
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="9584b-114">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="9584b-114">Explore the client APIs</span></span>](/dotnet/api/overview/azure/keyvault/client)

## <a name="management-library"></a><span data-ttu-id="9584b-115">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="9584b-115">Management library</span></span>

<span data-ttu-id="9584b-116">キー コンテナーを作成、削除、照会するには、管理ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="9584b-116">Use the management library to create, delete, and query key vaults.</span></span>

<span data-ttu-id="9584b-117">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.KeyVault.Fluent)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="9584b-117">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.KeyVault.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="9584b-118">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="9584b-118">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.KeyVault.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.KeyVault.Fluent
```

### <a name="example"></a><span data-ttu-id="9584b-119">例</span><span class="sxs-lookup"><span data-stu-id="9584b-119">Example</span></span>

<span data-ttu-id="9584b-120">次の例は、リソース グループと場所を指定して新しいキー コンテナーを作成する方法を示しています。</span><span class="sxs-lookup"><span data-stu-id="9584b-120">The following example demonstrates how to create a new key vault for a given resource group and location.</span></span>

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
> [<span data-ttu-id="9584b-121">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="9584b-121">Explore the management APIs</span></span>](/dotnet/api/overview/azure/keyvault/management)

## <a name="samples"></a><span data-ttu-id="9584b-122">サンプル</span><span class="sxs-lookup"><span data-stu-id="9584b-122">Samples</span></span>

* [<span data-ttu-id="9584b-123">Azure Key Vault クライアント サンプルのダウンロード</span><span class="sxs-lookup"><span data-stu-id="9584b-123">Download the Azure Key Vault client samples</span></span>](https://www.microsoft.com/download/details.aspx?id=45343)
* [<span data-ttu-id="9584b-124">.NET での Azure クライアント側暗号化の概要</span><span class="sxs-lookup"><span data-stu-id="9584b-124">Getting Started with Azure Client Side Encryption in .NET</span></span>](https://azure.microsoft.com/resources/samples/storage-dotnet-client-side-encryption/)


<span data-ttu-id="9584b-125">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="9584b-125">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
