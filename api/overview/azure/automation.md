---
title: ".NET 用 Azure Automation ライブラリ"
description: ".NET 用 Azure Automation ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Automation
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/21/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 1e1b5a662947503ff71f3e4a9b67f20a1e2d5f87
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-automation-libraries-for-net"></a>.NET 用 Azure Automation ライブラリ

## <a name="overview"></a>概要

Microsoft Azure Automation を使用すると、ユーザーはクラウド環境およびエンタープライズ環境で一般的に実行されるタスクを自動化できます。 

詳細については、「[Azure Automation の概要](/azure/automation/automation-intro)」をご覧ください。

## <a name="management-library"></a>管理ライブラリ

Runbook とジョブを管理したり、Desired State Configuration の設定を管理したりするには、管理ライブラリを使用します。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Automation)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使用してインストールします。

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
