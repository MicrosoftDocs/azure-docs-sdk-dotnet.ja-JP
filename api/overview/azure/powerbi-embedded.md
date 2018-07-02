---
title: .NET 用 Power BI Embedded ライブラリ
description: .NET 用 Power BI Embedded ライブラリのリファレンス
keywords: Azure, .NET, SDK, API, Power BI Embedded
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 3e28525f61ca8b4f8347b7a7e8994f9e479749ea
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065962"
---
# <a name="power-bi-embedded-libraries-for-net"></a><span data-ttu-id="6afac-104">.NET 用 Power BI Embedded ライブラリ</span><span class="sxs-lookup"><span data-stu-id="6afac-104">Power BI Embedded libraries for .NET</span></span>

<span data-ttu-id="6afac-105">[Power BI](https://powerbi.microsoft.com/) はクラウドベースのビジネス分析サービスであり、最も重要なビジネス データを 1 つのビューで見ることができます。</span><span class="sxs-lookup"><span data-stu-id="6afac-105">[Power BI](https://powerbi.microsoft.com/) is a cloud-based business analytics service that gives you a single view of your most critical business data.</span></span>

<span data-ttu-id="6afac-106">.NET での Power BI の使用について詳しくは、「[Power BI で埋め込み](https://powerbi.microsoft.com/en-us/documentation/powerbi-developer-embedding/)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="6afac-106">To learn more about using Power BI with .NET, see [Embedding with Power BI](https://powerbi.microsoft.com/en-us/documentation/powerbi-developer-embedding/).</span></span>

## <a name="client-library"></a><span data-ttu-id="6afac-107">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="6afac-107">Client library</span></span>

<span data-ttu-id="6afac-108">Power BI API と接続し、データ セットやレポートにアクセスして操作するには、クライアント ライブラリを使います。</span><span class="sxs-lookup"><span data-stu-id="6afac-108">Use the client library to connect with Power BI APIs to access and interact with data sets and reports.</span></span>

<span data-ttu-id="6afac-109">[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.PowerBI.Api)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールします。</span><span class="sxs-lookup"><span data-stu-id="6afac-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.PowerBI.Api) directly from the Visual Studio [Package Manager console][PackageManager].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="6afac-110">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="6afac-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.PowerBI.Api
```

### <a name="example"></a><span data-ttu-id="6afac-111">例</span><span class="sxs-lookup"><span data-stu-id="6afac-111">Example</span></span>

<span data-ttu-id="6afac-112">次の例では、データセットとレポートの一覧を取得して表示します。</span><span class="sxs-lookup"><span data-stu-id="6afac-112">The following example retrieves and displays a list of datasets and reports.</span></span>

```csharp
/* Include these'using' directive:
using Microsoft.PowerBI.Api.V2;
using Microsoft.PowerBI.Api.V2.Models;
*/
using (PowerBIClient client = new PowerBIClient(new Uri(apiUrl), tokenCredentials))
{

    Console.WriteLine("\r*** DATASETS ***\r");

    // List of datasets in a group/app workspace
    ODataResponseListDataset datasetList = client.Datasets.GetDatasetsInGroup(groupId);

    foreach(Dataset ds in datasetList.Value)
    {
        Console.WriteLine(ds.Id + " | " + ds.Name);
    }

    Console.WriteLine("\r*** REPORTS ***\r");

    // List of reports in a group/app workspace
    ODataResponseListReport reportList = client.Reports.GetReportsInGroup(groupId);

    foreach (Report rpt in reportList.Value)
    {
        Console.WriteLine(rpt.Id + " | " + rpt.Name +  " | DatasetID = " + rpt.DatasetId);
    }
}
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="6afac-113">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="6afac-113">Explore the client APIs</span></span>](https://powerbi.microsoft.com/documentation/powerbi-developer-rest-api-reference/)

## <a name="samples"></a><span data-ttu-id="6afac-114">サンプル</span><span class="sxs-lookup"><span data-stu-id="6afac-114">Samples</span></span>

* [<span data-ttu-id="6afac-115">Power BI 開発者向けサンプル</span><span class="sxs-lookup"><span data-stu-id="6afac-115">Power BI Developer Samples</span></span>](https://github.com/Microsoft/PowerBI-Developer-Samples)
* [<span data-ttu-id="6afac-116">Power BI .NET GitHub リポジトリ</span><span class="sxs-lookup"><span data-stu-id="6afac-116">Power BI .NET GitHub repo</span></span>](https://github.com/Microsoft/PowerBI-CSharp)

<span data-ttu-id="6afac-117">アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="6afac-117">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
