---
title: ".NET 用 Azure 管理ライブラリ サンプル手順"
description: ".NET 用 Azure 管理ライブラリを使ってリソースの作成と更新を行うサンプル コードを入手してください。"
keywords: "Azure, .NET, SDK, API, サンプル, 例"
author: camsoper
ms.author: casoper
manager: douge
ms.date: 06/20/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.assetid: 
ms.openlocfilehash: ffda7cca724962e6f953432c5cab04485ddabb03
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="azure-management-libraries-for-net-sample-instructions"></a><span data-ttu-id="49a67-104">.NET 用 Azure 管理ライブラリ サンプル手順</span><span class="sxs-lookup"><span data-stu-id="49a67-104">Azure management libraries for .NET sample instructions</span></span>

<span data-ttu-id="49a67-105">この記事では、.NET 用 Azure 管理ライブラリのサンプルを実行するために必要な前提条件と認証について説明します。</span><span class="sxs-lookup"><span data-stu-id="49a67-105">This article describes the prerequisites and authentication required for running the samples for the Azure management libraries for .NET.</span></span>

## <a name="prerequisties"></a><span data-ttu-id="49a67-106">前提条件</span><span class="sxs-lookup"><span data-stu-id="49a67-106">Prerequisties</span></span> 

* [<span data-ttu-id="49a67-107">Visual Studio 2017](https://www.visualstudio.com/vs/) または [.NET Core SDK</span><span class="sxs-lookup"><span data-stu-id="49a67-107">Visual Studio 2017](https://www.visualstudio.com/vs/) or [.NET Core SDK</span></span>](https://www.microsoft.com/net/download/core)
* <span data-ttu-id="49a67-108">[Microsoft Azure サブスクリプション](https://azure.microsoft.com/free/)</span><span class="sxs-lookup"><span data-stu-id="49a67-108">A [Microsoft Azure subscription](https://azure.microsoft.com/free/)</span></span>
* [<span data-ttu-id="49a67-109">Git コマンド ライン クライアント</span><span class="sxs-lookup"><span data-stu-id="49a67-109">Git command line client</span></span>](https://git-scm.com/)
* [<span data-ttu-id="49a67-110">Azure PowerShell</span><span class="sxs-lookup"><span data-stu-id="49a67-110">Azure PowerShell</span></span>](https://docs.microsoft.com/en-us/powershell/azure/install-azurerm-ps)

## <a name="authentication-for-all-samples"></a><span data-ttu-id="49a67-111">すべてのサンプルの認証</span><span class="sxs-lookup"><span data-stu-id="49a67-111">Authentication for all samples</span></span>

[!include[Create service principal](includes/create-sp.md)]

[!include[File-based authentication](includes/file-based-auth.md)]

## <a name="running-the-samples"></a><span data-ttu-id="49a67-112">サンプルの実行</span><span class="sxs-lookup"><span data-stu-id="49a67-112">Running the samples</span></span>

<span data-ttu-id="49a67-113">Git を使ってサンプルを複製した後は、Visual Studio でサンプルを開き、IDE を使ってサンプルを実行できます。</span><span class="sxs-lookup"><span data-stu-id="49a67-113">Once you have used Git to clone the sample, you can open the sample in Visual Studio and run the sample using the IDE.</span></span>  <span data-ttu-id="49a67-114">または、.NET Core SDK を使って、次のように、コマンド ラインからサンプルをビルドして実行します。</span><span class="sxs-lookup"><span data-stu-id="49a67-114">Alternatively, use the .NET Core SDK to build and run the sample from the command line, like this:</span></span>

```cmd
git clone https://github.com/Azure-Samples/app-service-dotnet-configure-deployment-sources-for-web-apps.git
cd app-service-dotnet-configure-deployment-sources-for-web-apps
dotnet restore
dotnet run
```