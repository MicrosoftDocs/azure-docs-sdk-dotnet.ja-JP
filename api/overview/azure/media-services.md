---
title: ".NET 用 Azure Media Services ライブラリ"
description: ".NET 用 Azure Media Services ライブラリのリファレンス"
keywords: Azure, .NET, SDK, API, Media Services
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/21/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: ee852258819e75867888f4a5fa1cbd72c7f91685
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-media-services-libraries-for-net"></a>.NET 用 Azure Media Services ライブラリ

## <a name="overview"></a>概要

Microsoft Azure Media Services は拡張可能なクラウド ベースのプラットフォームです。これにより、開発者はスケーラブルなメディア管理の構築、アプリケーションの配信を実行できます。 Media Services は、各種クライアント (TV、PC、モバイル デバイスなど) へのオンデマンドとライブ ストリーミングでの配信でビデオやオーディオのコンテンツの安全なアップロード、格納、エンコード、パッケージ化を可能にする REST API に基づいています。 

詳しくは、「[Azure Media Services の概要](/azure/media-services/media-services-overview)」および「[.NET を使用した Media Services 開発](/azure/media-services/media-services-dotnet-how-to-use)」をご覧ください。 

## <a name="client-library"></a>クライアント ライブラリ

Azure Media Services .NET SDK ライブラリを利用すると、.NET を使って Media Services に対するプログラミングを行うことができます。 Media Services API に対する接続、認証、開発を行うには、Azure Media Services クライアント ライブラリを使います。  

詳しくは、「[.NET SDK を使用したオンデマンド コンテンツ配信の概要](/azure/media-services/media-services-dotnet-get-started)」をご覧ください。

[NuGet パッケージ](https://www.nuget.org/packages/windowsazure.mediaservices)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。

#### <a name="visual-studio-package-manager"></a>Visual Studio パッケージ マネージャー

```powershell
Install-Package windowsazure.mediaservices
```

### <a name="code-example"></a>コード例

次のコード サンプルでは、Media Services SDK を使用して次のタスクを実行します。

- エンコード ジョブを作成します。
- Media Encoder Standard エンコーダーの参照を取得します。
- アダプティブ ストリーミング プリセットを使うように指定します。
- 1 つのエンコード タスクをジョブに追加します。
- エンコードする入力資産を指定します。
- エンコードされた資産を受け取るための出力資産を作成します。
- ジョブを送信します。


```csharp
/* Include this 'using' directive:
using Microsoft.WindowsAzure.MediaServices.Client;
*/

CloudMediaContext context = new CloudMediaContext(new Uri(mediaServiceRESTAPIEndpoint), tokenProvider);

// Get an uploaded asset.
IAsset asset = context.Assets.FirstOrDefault();

// Encode and generate the output using the "Adaptive Streaming" preset.
// Declare a new job.
IJob job = context.Jobs.Create("Media Encoder Standard Job");
// Get a media processor reference, and pass to it the name of the 
// processor to use for the specific task.
IMediaProcessor processor = context.MediaProcessors.Where(p => p.Name == mediaProcessorName)
    .ToList().OrderBy(p => new Version(p.Version)).LastOrDefault();
if (processor == null) 
{
    throw new ArgumentException(string.Format("Unknown media processor", mediaProcessorName));
}

// Create a task with the encoding details, using a string preset.
// In this case "Adaptive Streaming" preset is used.
ITask task = job.Tasks.AddNew("My encoding task", processor, "Adaptive Streaming", TaskOptions.None);

// Specify the input asset to be encoded.
task.InputAssets.Add(asset);
// Add an output asset to contain the results of the job. 
// This output is specified as AssetCreationOptions.None, which 
// means the output asset is not encrypted. 
task.OutputAssets.AddNew("Output asset", AssetCreationOptions.None);

job.Submit();
job.GetExecutionProgressTask(CancellationToken.None).Wait();
```

> [!div class="nextstepaction"]
> [クライアント API を探す](/dotnet/api/overview/azure/mediaservices/client)

## <a name="samples"></a>サンプル

- [Apple FairPlay で保護された HLS コンテンツをストリーミングする](https://azure.microsoft.com/resources/samples/media-services-dotnet-dynamic-encryption-with-fairplay/)
- [.NET SDK Extensions を使用して BLOB を Azure Media Services の資産にコピーする](https://azure.microsoft.com/resources/samples/media-services-dotnet-copy-blob-into-asset/)
- [.NET SDK を使用して Azure Media Services でライブ ストリームをエンコードして配信する](https://azure.microsoft.com/resources/samples/media-services-dotnet-encode-live-stream-with-ams-clear/)

Azure Media Services のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=media-services)を表示します。


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
