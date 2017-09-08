---
title: ".NET 用 Azure Backup ライブラリ"
description: ".NET 用 Azure Backup ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Backup
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/24/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 93eeaeda1860e3b7190dfb0ae917b4b85b5a3609
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-backup-libraries-for-net"></a><span data-ttu-id="a8f72-104">.NET 用 Azure Backup ライブラリ</span><span class="sxs-lookup"><span data-stu-id="a8f72-104">Azure Backup libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="a8f72-105">概要</span><span class="sxs-lookup"><span data-stu-id="a8f72-105">Overview</span></span>

<span data-ttu-id="a8f72-106">Azure Backup は、データのバックアップ、保護、復元に使用できるクラウド サービスです。</span><span class="sxs-lookup"><span data-stu-id="a8f72-106">Azure Backup is the cloud service you can use to back up, protect, and restore your data.</span></span>

<span data-ttu-id="a8f72-107">Azure Backup の詳細については、[Azure Backup の概要](/azure/backup/backup-introduction-to-azure-backup)に関する記事をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="a8f72-107">Learn more about Azure Backup by reading [What is Azure Backup?](/azure/backup/backup-introduction-to-azure-backup).</span></span>

## <a name="management-library"></a><span data-ttu-id="a8f72-108">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="a8f72-108">Management library</span></span>

<span data-ttu-id="a8f72-109">バックアップを管理し、Recovery Services コンテナーを設定するには、バックアップ管理ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="a8f72-109">Use the backup management library to manage backups and set up Recovery Services vaults.</span></span>

<span data-ttu-id="a8f72-110">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.RecoveryServices.Backup)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。</span><span class="sxs-lookup"><span data-stu-id="a8f72-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.RecoveryServices.Backup) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="a8f72-111">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="a8f72-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.RecoveryServices.Backup
```

```bash
dotnet add package Microsoft.Azure.Management.RecoveryServices.Backup
```

<span data-ttu-id="a8f72-112">次のコード例では、管理ライブラリを使用してバックアップをトリガーします。</span><span class="sxs-lookup"><span data-stu-id="a8f72-112">The following code example uses the management library to trigger a backup.</span></span>

```csharp
RecoveryServicesBackupManagementClient client = new RecoveryServicesBackupManagementClient(credentials);
TriggerBackupRequest triggerBackupRequest = new TriggerBackupRequest();
BaseRecoveryServicesJobResponse resp =
    await client.Backups.TriggerBackupAsync(resourceGroupName, resourceName, null,
        fabricName, containerName, protectedItemName, triggerBackupRequest);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="a8f72-113">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="a8f72-113">Explore the management APIs</span></span>](/dotnet/api/overview/azure/backup/management)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
