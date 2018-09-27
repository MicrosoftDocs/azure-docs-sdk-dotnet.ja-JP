---
title: .NET 用 Azure Automation ライブラリ
description: .NET 用 Azure Automation ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: automation
ms.openlocfilehash: 4890faab86d1319fe802a30e3735419ac65e8d64
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190285"
---
# <a name="azure-automation-libraries-for-net"></a>.NET 用 Azure Automation ライブラリ

## <a name="overview"></a>概要

Microsoft Azure Automation を使用すると、ユーザーはクラウド環境およびエンタープライズ環境で一般的に実行されるタスクを自動化できます。 

詳細については、「[Azure Automation の概要](/azure/automation/automation-intro)」をご覧ください。

## <a name="management-library"></a>管理ライブラリ

Runbook とジョブを管理したり、Desired State Configuration の設定を管理したりするには、管理ライブラリを使用します。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Automation)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.Azure.Management.Automation
```

```bash
dotnet add package Microsoft.Azure.Management.Automation
```

### <a name="code-example"></a>コード例

次の例は、既存の Runbook に基づく新しいジョブを開始する方法を示しています。

```csharp
/*
  using Microsoft.Azure.Management.Automation;
*/
AutomationManagementClient client =
    new AutomationManagementClient(new CertificateCloudCredentials(subscriptionId, cert));

// Create job create parameters
JobCreateParameters jcParam = new JobCreateParameters
{
    Properties = new JobCreateProperties
    {
        Runbook = new RunbookAssociationProperty
        {
            Name = runbookName
        },
        Parameters = null // optional parameters here
    }
};

// create runbook job. This gives back the Job
Job job = automationManagementClient.Jobs.Create(automationAccountName, jcParam).Job;
```

> [!div class="nextstepaction"]
> [Management API を探す](/dotnet/api/overview/azure/automation/management)

## <a name="samples"></a>サンプル

* [AzureBot](https://github.com/Microsoft/AzureBot) では、Automation ライブラリを [Bot Framework](https://docs.microsoft.com/bot-framework/) および [Cognitive Services](/cognitive-services) と共に使用して、Azure での開発者の生産性を高めます。

アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
