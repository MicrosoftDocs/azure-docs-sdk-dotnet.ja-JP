---
title: .NET 用 Power BI Embedded ライブラリ
description: .NET 用 Power BI Embedded ライブラリのリファレンス
ms.date: 10/19/2017
ms.topic: reference
ms.service: multiple
ms.openlocfilehash: acb327b56e89522142e51016a6a9b279f995a674
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190375"
---
# <a name="power-bi-embedded-libraries-for-net"></a>.NET 用 Power BI Embedded ライブラリ

[Power BI](https://powerbi.microsoft.com/) はクラウドベースのビジネス分析サービスであり、最も重要なビジネス データを 1 つのビューで見ることができます。

.NET での Power BI の使用について詳しくは、「[Power BI で埋め込み](https://powerbi.microsoft.com/en-us/documentation/powerbi-developer-embedding/)」をご覧ください。

## <a name="client-library"></a>クライアント ライブラリ

Power BI API と接続し、データ セットやレポートにアクセスして操作するには、クライアント ライブラリを使います。

[NuGet パッケージ](https://www.nuget.org/packages/Microsoft.PowerBI.Api)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package Microsoft.PowerBI.Api
```

### <a name="example"></a>例

次の例では、データセットとレポートの一覧を取得して表示します。

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
> [クライアント API を探す](https://powerbi.microsoft.com/documentation/powerbi-developer-rest-api-reference/)

## <a name="samples"></a>サンプル

* [Power BI 開発者向けサンプル](https://github.com/Microsoft/PowerBI-Developer-Samples)
* [Power BI .NET GitHub リポジトリ](https://github.com/Microsoft/PowerBI-CSharp)

アプリで使用できるその他の[サンプル .NET コード](https://azure.microsoft.com/resources/samples/?platform=dotnet)を確認してください。

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
