---
title: ".NET 用 Azure 管理ライブラリ リリース ノート | Microsoft Docs"
description: ".NET 用 Azure 管理ライブラリの新機能や重大な変更が記載されています。"
keywords: "Azure, .NET, API, リファレンス, ノート, 更新, 非推奨"
author: camsoper
ms.author: casoper
manager: douge
ms.assetid: 
ms.service: Azure
ms.devlang: dotnet
ms.topic: reference
ms.technology: Azure
ms.date: 06/20/2017
ms.openlocfilehash: b4a66eb2860673f63a0d11c3cf31486337f36131
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/28/2017
---
# <a name="release-notes"></a><span data-ttu-id="dfed2-104">リリース ノート</span><span class="sxs-lookup"><span data-stu-id="dfed2-104">Release Notes</span></span> 

## <a name="feature-availability-and-road-map-as-of-version-100"></a><span data-ttu-id="dfed2-105">バージョン 1.0.0 の時点での機能の使用可能性とロード マップ</span><span class="sxs-lookup"><span data-stu-id="dfed2-105">Feature Availability and Road Map as of Version 1.0.0</span></span> ##
### <a name="april-26-2017"></a><span data-ttu-id="dfed2-106">2017 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="dfed2-106">April 26, 2017</span></span>

<table>
  <tr>
    <th align="left"><span data-ttu-id="dfed2-107">サービス | 機能</span><span class="sxs-lookup"><span data-stu-id="dfed2-107">Service | feature</span></span></th>
    <th align="left"><span data-ttu-id="dfed2-108">GA として利用可能</span><span class="sxs-lookup"><span data-stu-id="dfed2-108">Available as GA</span></span></th>
    <th align="left"><span data-ttu-id="dfed2-109">プレビューとして利用可能</span><span class="sxs-lookup"><span data-stu-id="dfed2-109">Available as Preview</span></span></th>
    <th align="left"><span data-ttu-id="dfed2-110">近日対応予定</span><span class="sxs-lookup"><span data-stu-id="dfed2-110">Coming soon</span></span></th>
  </tr>
  <tr>
    <td><span data-ttu-id="dfed2-111">コンピューティング</span><span class="sxs-lookup"><span data-stu-id="dfed2-111">Compute</span></span></td>
    <td><span data-ttu-id="dfed2-112">仮想マシンと VM 拡張機能</span><span class="sxs-lookup"><span data-stu-id="dfed2-112">Virtual machines and VM extensions</span></span><br><span data-ttu-id="dfed2-113">仮想マシン スケール セット</span><span class="sxs-lookup"><span data-stu-id="dfed2-113">Virtual machine scale sets</span></span><br><span data-ttu-id="dfed2-114">管理ディスク</span><span class="sxs-lookup"><span data-stu-id="dfed2-114">Managed disks</span></span></td>
    <td></td>
    <td valign="top"><span data-ttu-id="dfed2-115">Azure コンテナー サービス</span><span class="sxs-lookup"><span data-stu-id="dfed2-115">Azure container services</span></span><br><span data-ttu-id="dfed2-116">Azure コンテナー レジストリ</span><span class="sxs-lookup"><span data-stu-id="dfed2-116">Azure container registry</span></span></td>
  </tr>
  <tr>
    <td><span data-ttu-id="dfed2-117">Storage</span><span class="sxs-lookup"><span data-stu-id="dfed2-117">Storage</span></span></td>
    <td><span data-ttu-id="dfed2-118">ストレージ アカウント</span><span class="sxs-lookup"><span data-stu-id="dfed2-118">Storage accounts</span></span></td>
    <td></td>
    <td><span data-ttu-id="dfed2-119">暗号化</span><span class="sxs-lookup"><span data-stu-id="dfed2-119">Encryption</span></span></td>
  </tr>
  <tr>
    <td><span data-ttu-id="dfed2-120">SQL Database</span><span class="sxs-lookup"><span data-stu-id="dfed2-120">SQL Database</span></span></td>
    <td><span data-ttu-id="dfed2-121">データベース</span><span class="sxs-lookup"><span data-stu-id="dfed2-121">Databases</span></span><br><span data-ttu-id="dfed2-122">ファイアウォール</span><span class="sxs-lookup"><span data-stu-id="dfed2-122">Firewalls</span></span><br><span data-ttu-id="dfed2-123">エラスティック プール</span><span class="sxs-lookup"><span data-stu-id="dfed2-123">Elastic pools</span></span></td>
    <td></td>
    <td valign="top"></td>
  </tr>
  <tr>
    <td><span data-ttu-id="dfed2-124">ネットワーク</span><span class="sxs-lookup"><span data-stu-id="dfed2-124">Networking</span></span></td>
    <td><span data-ttu-id="dfed2-125">仮想ネットワーク</span><span class="sxs-lookup"><span data-stu-id="dfed2-125">Virtual networks</span></span><br><span data-ttu-id="dfed2-126">ネットワーク インターフェイス</span><span class="sxs-lookup"><span data-stu-id="dfed2-126">Network interfaces</span></span><br><span data-ttu-id="dfed2-127">IP アドレス</span><span class="sxs-lookup"><span data-stu-id="dfed2-127">IP addresses</span></span><br><span data-ttu-id="dfed2-128">ルーティング テーブル</span><span class="sxs-lookup"><span data-stu-id="dfed2-128">Routing table</span></span><br><span data-ttu-id="dfed2-129">ネットワーク セキュリティ グループ</span><span class="sxs-lookup"><span data-stu-id="dfed2-129">Network security groups</span></span><br><span data-ttu-id="dfed2-130">DNS</span><span class="sxs-lookup"><span data-stu-id="dfed2-130">DNS</span></span><br><span data-ttu-id="dfed2-131">Traffic Manager</span><span class="sxs-lookup"><span data-stu-id="dfed2-131">Traffic managers</span></span></td>
    <td valign="top"><span data-ttu-id="dfed2-132">ロード バランサー</span><span class="sxs-lookup"><span data-stu-id="dfed2-132">Load balancers</span></span><br><span data-ttu-id="dfed2-133">アプリケーション ゲートウェイ</span><span class="sxs-lookup"><span data-stu-id="dfed2-133">Application gateways</span></span></td>
    <td valign="top"></td>
  </tr>
  <tr>
    <td><span data-ttu-id="dfed2-134">その他のサービス</span><span class="sxs-lookup"><span data-stu-id="dfed2-134">More services</span></span></td>
    <td><span data-ttu-id="dfed2-135">リソース マネージャー</span><span class="sxs-lookup"><span data-stu-id="dfed2-135">Resource Manager</span></span><br><span data-ttu-id="dfed2-136">Key Vault</span><span class="sxs-lookup"><span data-stu-id="dfed2-136">Key Vault</span></span><br><span data-ttu-id="dfed2-137">Redis</span><span class="sxs-lookup"><span data-stu-id="dfed2-137">Redis</span></span><br><span data-ttu-id="dfed2-138">CDN</span><span class="sxs-lookup"><span data-stu-id="dfed2-138">CDN</span></span><br><span data-ttu-id="dfed2-139">Batch
</span><span class="sxs-lookup"><span data-stu-id="dfed2-139">Batch</span></span></td>
    <td valign="top"><span data-ttu-id="dfed2-140">App Service - Web アプリ</span><span class="sxs-lookup"><span data-stu-id="dfed2-140">App service - Web apps</span></span><br><span data-ttu-id="dfed2-141">関数</span><span class="sxs-lookup"><span data-stu-id="dfed2-141">Functions</span></span><br><span data-ttu-id="dfed2-142">Service Bus</span><span class="sxs-lookup"><span data-stu-id="dfed2-142">Service bus</span></span></td>
    <td valign="top"><span data-ttu-id="dfed2-143">監視</span><span class="sxs-lookup"><span data-stu-id="dfed2-143">Monitor</span></span><br><span data-ttu-id="dfed2-144">Graph RBAC</span><span class="sxs-lookup"><span data-stu-id="dfed2-144">Graph RBAC</span></span><br><span data-ttu-id="dfed2-145">DocumentDB</span><span class="sxs-lookup"><span data-stu-id="dfed2-145">DocumentDB</span></span><br><span data-ttu-id="dfed2-146">Scheduler</span><span class="sxs-lookup"><span data-stu-id="dfed2-146">Scheduler</span></span></td>
  </tr>
  <tr>
    <td><span data-ttu-id="dfed2-147">基礎</span><span class="sxs-lookup"><span data-stu-id="dfed2-147">Fundamentals</span></span></td>
    <td><span data-ttu-id="dfed2-148">認証 - コア</span><span class="sxs-lookup"><span data-stu-id="dfed2-148">Authentication - core</span></span></td>
    <td><span data-ttu-id="dfed2-149">非同期メソッド</span><span class="sxs-lookup"><span data-stu-id="dfed2-149">Async methods</span></span></td>
    <td valign="top"></td>
  </tr>
</table>

> [!WARNING] 
> <span data-ttu-id="dfed2-150">"*プレビュー*" 機能は、ライブラリ内のドキュメントのコメントにフラグが付けられています。</span><span class="sxs-lookup"><span data-stu-id="dfed2-150">*Preview* features are flagged in documentation comments in libraries.</span></span> <span data-ttu-id="dfed2-151">これらの機能は、変更されることがあります。</span><span class="sxs-lookup"><span data-stu-id="dfed2-151">These features are subject to change.</span></span> <span data-ttu-id="dfed2-152">将来、何らかの変更が行われる (または削除される) 可能性があります。</span><span class="sxs-lookup"><span data-stu-id="dfed2-152">They can be modified in any way (or even removed) in the future.</span></span>

[!include[Contribute and community](includes/contribute.md)]
