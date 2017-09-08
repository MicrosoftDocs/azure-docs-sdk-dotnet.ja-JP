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
# <a name="azure-media-services-libraries-for-net"></a><span data-ttu-id="c7a61-104">.NET 用 Azure Media Services ライブラリ</span><span class="sxs-lookup"><span data-stu-id="c7a61-104">Azure Media Services libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="c7a61-105">概要</span><span class="sxs-lookup"><span data-stu-id="c7a61-105">Overview</span></span>

<span data-ttu-id="c7a61-106">Microsoft Azure Media Services は拡張可能なクラウド ベースのプラットフォームです。これにより、開発者はスケーラブルなメディア管理の構築、アプリケーションの配信を実行できます。</span><span class="sxs-lookup"><span data-stu-id="c7a61-106">Microsoft Azure Media Services is an extensible cloud-based platform that enables developers to build scalable media management and delivery applications.</span></span> <span data-ttu-id="c7a61-107">Media Services は、各種クライアント (TV、PC、モバイル デバイスなど) へのオンデマンドとライブ ストリーミングでの配信でビデオやオーディオのコンテンツの安全なアップロード、格納、エンコード、パッケージ化を可能にする REST API に基づいています。</span><span class="sxs-lookup"><span data-stu-id="c7a61-107">Media Services is based on REST APIs that enable you to securely upload, store, encode, and package video or audio content for both on-demand and live streaming delivery to various clients (for example, TV, PC, and mobile devices).</span></span> 

<span data-ttu-id="c7a61-108">詳しくは、「[Azure Media Services の概要](/azure/media-services/media-services-overview)」および「[.NET を使用した Media Services 開発](/azure/media-services/media-services-dotnet-how-to-use)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="c7a61-108">To learn more, see [Overview](/azure/media-services/media-services-overview) and [Getting started with .NET](/azure/media-services/media-services-dotnet-how-to-use).</span></span> 

## <a name="client-library"></a><span data-ttu-id="c7a61-109">クライアント ライブラリ</span><span class="sxs-lookup"><span data-stu-id="c7a61-109">Client library</span></span>

<span data-ttu-id="c7a61-110">Azure Media Services .NET SDK ライブラリを利用すると、.NET を使って Media Services に対するプログラミングを行うことができます。</span><span class="sxs-lookup"><span data-stu-id="c7a61-110">The Azure Media Services .NET SDK library enables you to program against Media Services using .NET.</span></span> <span data-ttu-id="c7a61-111">Media Services API に対する接続、認証、開発を行うには、Azure Media Services クライアント ライブラリを使います。</span><span class="sxs-lookup"><span data-stu-id="c7a61-111">Use the Azure Media Services client library to connect, authenticate, and develop against Media Services APIs.</span></span>  

<span data-ttu-id="c7a61-112">詳しくは、「[.NET SDK を使用したオンデマンド コンテンツ配信の概要](/azure/media-services/media-services-dotnet-get-started)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="c7a61-112">For more information, see [Get started with delivering content on demand using .NET SDK](/azure/media-services/media-services-dotnet-get-started).</span></span>

<span data-ttu-id="c7a61-113">[NuGet パッケージ](https://www.nuget.org/packages/windowsazure.mediaservices)を Visual Studio [パッケージ マネージャー コンソール][PackageManager]から直接インストールするか、[.NET Core CLI][DotNetCLI] を使ってインストールします。</span><span class="sxs-lookup"><span data-stu-id="c7a61-113">Install the [NuGet package](https://www.nuget.org/packages/windowsazure.mediaservices) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="c7a61-114">Visual Studio パッケージ マネージャー</span><span class="sxs-lookup"><span data-stu-id="c7a61-114">Visual Studio Package Manager</span></span>

```powershell
Install-Package windowsazure.mediaservices
```

### <a name="code-example"></a><span data-ttu-id="c7a61-115">コード例</span><span class="sxs-lookup"><span data-stu-id="c7a61-115">Code Example</span></span>

<span data-ttu-id="c7a61-116">次のコード サンプルでは、Media Services SDK を使用して次のタスクを実行します。</span><span class="sxs-lookup"><span data-stu-id="c7a61-116">The following code example uses Media Services .NET SDK to perform the following tasks:</span></span>

- <span data-ttu-id="c7a61-117">エンコード ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="c7a61-117">Create an encoding job.</span></span>
- <span data-ttu-id="c7a61-118">Media Encoder Standard エンコーダーの参照を取得します。</span><span class="sxs-lookup"><span data-stu-id="c7a61-118">Get a reference to the Media Encoder Standard encoder.</span></span>
- <span data-ttu-id="c7a61-119">アダプティブ ストリーミング プリセットを使うように指定します。</span><span class="sxs-lookup"><span data-stu-id="c7a61-119">Specify to use the Adaptive Streaming preset.</span></span>
- <span data-ttu-id="c7a61-120">1 つのエンコード タスクをジョブに追加します。</span><span class="sxs-lookup"><span data-stu-id="c7a61-120">Add a single encoding task to the job.</span></span>
- <span data-ttu-id="c7a61-121">エンコードする入力資産を指定します。</span><span class="sxs-lookup"><span data-stu-id="c7a61-121">Specify the input asset to be encoded.</span></span>
- <span data-ttu-id="c7a61-122">エンコードされた資産を受け取るための出力資産を作成します。</span><span class="sxs-lookup"><span data-stu-id="c7a61-122">Create an output asset to receive the encoded asset.</span></span>
- <span data-ttu-id="c7a61-123">ジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="c7a61-123">Submit the job.</span></span>


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
> [<span data-ttu-id="c7a61-124">クライアント API を探す</span><span class="sxs-lookup"><span data-stu-id="c7a61-124">Explore the client APIs</span></span>](/dotnet/api/overview/azure/mediaservices/client)

## <a name="samples"></a><span data-ttu-id="c7a61-125">サンプル</span><span class="sxs-lookup"><span data-stu-id="c7a61-125">Samples</span></span>

- [<span data-ttu-id="c7a61-126">Apple FairPlay で保護された HLS コンテンツをストリーミングする</span><span class="sxs-lookup"><span data-stu-id="c7a61-126">Stream your HLS content Protected with Apple FairPlay</span></span>](https://azure.microsoft.com/resources/samples/media-services-dotnet-dynamic-encryption-with-fairplay/)
- [<span data-ttu-id="c7a61-127">.NET SDK Extensions を使用して BLOB を Azure Media Services の資産にコピーする</span><span class="sxs-lookup"><span data-stu-id="c7a61-127">Copy blob into an Azure Media Services asset using .NET SDK Extensions</span></span>](https://azure.microsoft.com/resources/samples/media-services-dotnet-copy-blob-into-asset/)
- [<span data-ttu-id="c7a61-128">.NET SDK を使用して Azure Media Services でライブ ストリームをエンコードして配信する</span><span class="sxs-lookup"><span data-stu-id="c7a61-128">Encode and Deliver a Live Stream with Azure Media Services using .NET SDK</span></span>](https://azure.microsoft.com/resources/samples/media-services-dotnet-encode-live-stream-with-ams-clear/)

<span data-ttu-id="c7a61-129">Azure Media Services のサンプルの[完全な一覧](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=media-services)を表示します。</span><span class="sxs-lookup"><span data-stu-id="c7a61-129">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=media-services) of Azure Media Services samples.</span></span>


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
