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
# <a name="azure-automation-libraries-for-net"></a><span data-ttu-id="ff101-103">.NET 用 Azure Automation ライブラリ</span><span class="sxs-lookup"><span data-stu-id="ff101-103">Azure Automation libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="ff101-104">概要</span><span class="sxs-lookup"><span data-stu-id="ff101-104">Overview</span></span>

<span data-ttu-id="ff101-105">Microsoft Azure Automation を使用すると、ユーザーはクラウド環境およびエンタープライズ環境で一般的に実行されるタスクを自動化できます。</span><span class="sxs-lookup"><span data-stu-id="ff101-105">Microsoft Azure Automation provides a way for users to automate the tasks that are commonly performed in a cloud and enterprise environment.</span></span> 

<span data-ttu-id="ff101-106">詳細については、「[Azure Automation の概要](/azure/automation/automation-intro)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="ff101-106">Learn more by reading the [Azure Automation Overview](/azure/automation/automation-intro).</span></span>

## <a name="management-library"></a><span data-ttu-id="ff101-107">管理ライブラリ</span><span class="sxs-lookup"><span data-stu-id="ff101-107">Management library</span></span>

<span data-ttu-id="ff101-108">Runbook とジョブを管理したり、Desired State Configuration の設定を管理したりするには、管理ライブラリを使用します。</span><span class="sxs-lookup"><span data-stu-id="ff101-108">Using the management library to manage runbooks and jobs and manage Desired State Configuration settings.</span></span>

<span data-ttu-id="ff101-109">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.Azure.Management.Automation)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="ff101-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Automation) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="ff101-110">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="ff101-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Automation
```

```bash
dotnet add package Microsoft.Azure.Management.Automation
```

### <a name="code-example"></a><span data-ttu-id="ff101-111">コード例</span><span class="sxs-lookup"><span data-stu-id="ff101-111">Code Example</span></span>

<span data-ttu-id="ff101-112">次の例は、既存の Runbook に基づく新しいジョブを開始する方法を示しています。</span><span class="sxs-lookup"><span data-stu-id="ff101-112">The following example illustrates how to start a new job based on an existing runbook.</span></span>

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
> [<span data-ttu-id="ff101-113">Management API を探す</span><span class="sxs-lookup"><span data-stu-id="ff101-113">Explore the management APIs</span></span>](/dotnet/api/overview/azure/automation/management)

## <a name="samples"></a><span data-ttu-id="ff101-114">サンプル</span><span class="sxs-lookup"><span data-stu-id="ff101-114">Samples</span></span>

* <span data-ttu-id="ff101-115">[AzureBot](https://github.com/Microsoft/AzureBot) では、Automation ライブラリを [Bot Framework](https://docs.microsoft.com/bot-framework/) および [Cognitive Services](/cognitive-services) と共に使用して、Azure での開発者の生産性を高めます。</span><span class="sxs-lookup"><span data-stu-id="ff101-115">[AzureBot](https://github.com/Microsoft/AzureBot) uses the automation library with the [Bot Framework](https://docs.microsoft.com/bot-framework/) and [Cognitive Services](/cognitive-services) to improve developer productivity on Azure</span></span>

<span data-ttu-id="ff101-116">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="ff101-116">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
