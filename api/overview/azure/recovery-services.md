---
title: ".NET 用 Azure Recovery Services および Backup ライブラリ"
description: ".NET 用 Azure Recovery Services および Backup ライブラリのリファレンス"
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
---
# <a name="azure-recovery-services-and-backup-libraries-for-net"></a>.NET 用 Azure Recovery Services および Backup ライブラリ

## <a name="overview"></a>概要

Azure Recovery Services は、[Azure Backup](/azure/backup/) と [Azure Site Recovery](/azure/site-recovery/) を含む、データ回復のための一連のサービスです。

## <a name="management-library"></a>管理ライブラリ

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.RecoveryServices)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.RecoveryServices
Install-Package Microsoft.Azure.Management.RecoveryServices.Backup
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.Management.RecoveryServices
dotnet add package Microsoft.Azure.Management.RecoveryServices.Backup
```

> [!div class="nextstepaction"]
> [Management API を探す](/dotnet/api/overview/azure/recoveryservices/management)


## <a name="code-example"></a>コード例

次のコード例では、管理ライブラリを使用してバックアップをトリガーします。

```csharp
RecoveryServicesBackupManagementClient client = new RecoveryServicesBackupManagementClient(credentials);
TriggerBackupRequest triggerBackupRequest = new TriggerBackupRequest();
BaseRecoveryServicesJobResponse resp =
    await client.Backups.TriggerBackupAsync(resourceGroupName, resourceName, null,
        fabricName, containerName, protectedItemName, triggerBackupRequest);
```

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
