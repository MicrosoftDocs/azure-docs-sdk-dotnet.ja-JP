---
title: .NET 用 Azure Recovery Services および Backup ライブラリ
description: .NET 用 Azure Recovery Services および Backup ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Recovery Services, Backup
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: recovery-services
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 3b399827f187fc2cb59c8698a555e63d08cee6c7
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/26/2017
ms.locfileid: "23566113"
---
# <a name="azure-recovery-services-and-backup-libraries-for-net"></a><span data-ttu-id="7937f-104">.NET 用 Azure Recovery Services および Backup ライブラリ</span><span class="sxs-lookup"><span data-stu-id="7937f-104">Azure Recovery Services and Backup libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="7937f-105">概要</span><span class="sxs-lookup"><span data-stu-id="7937f-105">Overview</span></span>

<span data-ttu-id="7937f-106">Azure Recovery Services は、[Azure Backup](/azure/backup/) と [Azure Site Recovery](/azure/site-recovery/) を含む、データ回復のための一連のサービスです。</span><span class="sxs-lookup"><span data-stu-id="7937f-106">Azure Recovery Services is a suite of services for data recovery, including [Azure Backup](/azure/backup/) and [Azure Site Recovery](/azure/site-recovery/).</span></span>

## <a name="management-library"></a><span data-ttu-id="7937f-107">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="7937f-107">Management library</span></span>

<span data-ttu-id="7937f-108">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.RecoveryServices)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="7937f-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.RecoveryServices) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="7937f-109">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="7937f-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.RecoveryServices
Install-Package Microsoft.Azure.Management.RecoveryServices.Backup
```

#### <a name="net-core-cli"></a><span data-ttu-id="7937f-110">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="7937f-110">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.RecoveryServices
dotnet add package Microsoft.Azure.Management.RecoveryServices.Backup
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="7937f-111">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="7937f-111">Explore the management APIs</span></span>](/dotnet/api/overview/azure/recoveryservices/management)


## <a name="code-example"></a><span data-ttu-id="7937f-112">コード例</span><span class="sxs-lookup"><span data-stu-id="7937f-112">Code Example</span></span>

<span data-ttu-id="7937f-113">次のコード例では、管理ライブラリを使用してバックアップをトリガーします。</span><span class="sxs-lookup"><span data-stu-id="7937f-113">The following code example uses the management library to trigger a backup.</span></span>

```csharp
RecoveryServicesBackupManagementClient client = new RecoveryServicesBackupManagementClient(credentials);
TriggerBackupRequest triggerBackupRequest = new TriggerBackupRequest();
BaseRecoveryServicesJobResponse resp =
    await client.Backups.TriggerBackupAsync(resourceGroupName, resourceName, null,
        fabricName, containerName, protectedItemName, triggerBackupRequest);
```

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
