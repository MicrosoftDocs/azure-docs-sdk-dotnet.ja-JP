---
title: "Azure の .NET アプリでのストレージの使用に関するチュートリアル"
description: "Azure で実行されている .NET アプリケーションでオブジェクトを保存し、ファイルを使用します"
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: 0a78559541f1bc4c94f94d991c44aee2cbf56fc3
ms.sourcegitcommit: 3ba0ff4463338a0ab0f3f15a7601b89417c06970
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/05/2018
---
# <a name="tutorials-for-working-with-storage-in-your-net-apps-on-azure"></a><span data-ttu-id="eebe4-103">Azure 上の .NET アプリでのストレージの使用に関するチュートリアル</span><span class="sxs-lookup"><span data-stu-id="eebe4-103">Tutorials for working with storage in your .NET apps on Azure.</span></span>

<span data-ttu-id="eebe4-104">次の表では、Azure で実行している .NET アプリでのファイルとストレージの使用に関する詳細なチュートリアルへのリンクを示します。</span><span class="sxs-lookup"><span data-stu-id="eebe4-104">The following table links to in-depth tutorials for working with files and storage in your .NET apps running on Azure.</span></span>

<span data-ttu-id="eebe4-105">サンプルのソース コードについては、「[Azure のコード サンプル](https://azure.microsoft.com/resources/samples/?platform=dotnet)」の一覧をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="eebe4-105">For sample source code, see the list of [Azure service samples](https://azure.microsoft.com/resources/samples/?platform=dotnet).</span></span>

| | |
|---|---|
| <span data-ttu-id="eebe4-106">**Azure Storage**</span><span class="sxs-lookup"><span data-stu-id="eebe4-106">**Azure Storage**</span></span> ||
| <span data-ttu-id="eebe4-107">[.NET から Blob Storage を使用する][1]</span><span class="sxs-lookup"><span data-stu-id="eebe4-107">[Use Blob storage from .NET][1]</span></span> | <span data-ttu-id="eebe4-108">BLOB をアップロード、一覧表示、ダウンロード、削除します。</span><span class="sxs-lookup"><span data-stu-id="eebe4-108">Upload, list, download, and delete blobs.</span></span> |
| <span data-ttu-id="eebe4-109">[.NET から File Storage を使用する][4]</span><span class="sxs-lookup"><span data-stu-id="eebe4-109">[Use File storage from .NET][4]</span></span> | <span data-ttu-id="eebe4-110">共有上のファイルとディレクトリを作成、変更、削除します。</span><span class="sxs-lookup"><span data-stu-id="eebe4-110">Create, modify, and delete files and directories on a share.</span></span> | 
| <span data-ttu-id="eebe4-111">[.NET から Table Storage を使用する][3]</span><span class="sxs-lookup"><span data-stu-id="eebe4-111">[Use Table storage from .NET][3]</span></span> | <span data-ttu-id="eebe4-112">テーブルとエンティティを作成、変更、削除します。</span><span class="sxs-lookup"><span data-stu-id="eebe4-112">Create, modify, and delete tables and entities.</span></span> |
| <span data-ttu-id="eebe4-113">[.NET から Queue Storage を使用する][2]</span><span class="sxs-lookup"><span data-stu-id="eebe4-113">[Use Queue storage from .NET][2]</span></span> | <span data-ttu-id="eebe4-114">キューを作成および削除し、メッセージの挿入、ピーク、取得、削除を行います。</span><span class="sxs-lookup"><span data-stu-id="eebe4-114">Create and delete queues and insert, peek, get, and delete messages.</span></span> |
| <span data-ttu-id="eebe4-115">[クライアント側の暗号化][5]</span><span class="sxs-lookup"><span data-stu-id="eebe4-115">[Client side encryption][5]</span></span> | <span data-ttu-id="eebe4-116">アップロードする前にデータを暗号化し、.NET アプリケーションにファイルをダウンロードする間にデータを復号化します。</span><span class="sxs-lookup"><span data-stu-id="eebe4-116">Encrypt data before uploading and decrypt data while downloading files to your .NET application.</span></span> 
|<span data-ttu-id="eebe4-117">**Data Lake**</span><span class="sxs-lookup"><span data-stu-id="eebe4-117">**Data Lake**</span></span>||
| <span data-ttu-id="eebe4-118">[.NET で Azure Data Lake Store の使用を開始する][6]</span><span class="sxs-lookup"><span data-stu-id="eebe4-118">[Get started with Data Lake Store using .NET][6]</span></span> | <span data-ttu-id="eebe4-119">フォルダーを作成し、Data Lake のファイルをアップロードおよびダウンロードします。</span><span class="sxs-lookup"><span data-stu-id="eebe4-119">Create folders, upload and download files into a Data Lake.</span></span> | 

[1]: /azure/storage/storage-dotnet-how-to-use-blobs
[2]: /azure/storage/storage-dotnet-how-to-use-queues
[3]: /azure/storage/storage-dotnet-how-to-use-tables
[4]: /azure/storage/storage-dotnet-how-to-use-files
[5]: /azure/storage/storage-client-side-encryption
[6]: /azure/data-lake-store/data-lake-store-get-started-net-sdk