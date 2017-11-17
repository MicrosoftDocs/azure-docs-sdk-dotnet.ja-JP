---
title: ".NET 用 Azure 管理ライブラリ リリース ノート | Microsoft Docs"
description: ".NET 用 Azure 管理ライブラリの新機能や重大な変更が記載されています。"
keywords: "Azure, .NET, API, リファレンス, ノート, 更新, 非推奨"
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: 714bd05653c6b41b21b95581b1115b0bfa1956ed
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/23/2017
---
# <a name="release-notes"></a><span data-ttu-id="0b120-104">リリース ノート</span><span class="sxs-lookup"><span data-stu-id="0b120-104">Release Notes</span></span> 

## <a name="feature-availability-and-road-map-as-of-version-100"></a><span data-ttu-id="0b120-105">バージョン 1.0.0 の時点での機能の使用可能性とロード マップ</span><span class="sxs-lookup"><span data-stu-id="0b120-105">Feature Availability and Road Map as of Version 1.0.0</span></span> ##
### <a name="april-26-2017"></a><span data-ttu-id="0b120-106">2017 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="0b120-106">April 26, 2017</span></span>

<table>
  <tr>
    <th align="left"><span data-ttu-id="0b120-107">サービス | 機能</span><span class="sxs-lookup"><span data-stu-id="0b120-107">Service | feature</span></span></th>
    <th align="left"><span data-ttu-id="0b120-108">GA として利用可能</span><span class="sxs-lookup"><span data-stu-id="0b120-108">Available as GA</span></span></th>
    <th align="left"><span data-ttu-id="0b120-109">プレビューとして利用可能</span><span class="sxs-lookup"><span data-stu-id="0b120-109">Available as Preview</span></span></th>
    <th align="left"><span data-ttu-id="0b120-110">近日対応予定</span><span class="sxs-lookup"><span data-stu-id="0b120-110">Coming soon</span></span></th>
  </tr>
  <tr>
    <td><span data-ttu-id="0b120-111">コンピューティング</span><span class="sxs-lookup"><span data-stu-id="0b120-111">Compute</span></span></td>
    <td><span data-ttu-id="0b120-112">仮想マシンと VM 拡張機能</span><span class="sxs-lookup"><span data-stu-id="0b120-112">Virtual machines and VM extensions</span></span><br><span data-ttu-id="0b120-113">仮想マシン スケール セット</span><span class="sxs-lookup"><span data-stu-id="0b120-113">Virtual machine scale sets</span></span><br><span data-ttu-id="0b120-114">管理ディスク</span><span class="sxs-lookup"><span data-stu-id="0b120-114">Managed disks</span></span></td>
    <td></td>
    <td valign="top"><span data-ttu-id="0b120-115">Azure コンテナー サービス</span><span class="sxs-lookup"><span data-stu-id="0b120-115">Azure container services</span></span><br><span data-ttu-id="0b120-116">Azure コンテナー レジストリ</span><span class="sxs-lookup"><span data-stu-id="0b120-116">Azure container registry</span></span></td>
  </tr>
  <tr>
    <td><span data-ttu-id="0b120-117">ストレージ</span><span class="sxs-lookup"><span data-stu-id="0b120-117">Storage</span></span></td>
    <td><span data-ttu-id="0b120-118">ストレージ アカウント</span><span class="sxs-lookup"><span data-stu-id="0b120-118">Storage accounts</span></span></td>
    <td></td>
    <td><span data-ttu-id="0b120-119">暗号化</span><span class="sxs-lookup"><span data-stu-id="0b120-119">Encryption</span></span></td>
  </tr>
  <tr>
    <td><span data-ttu-id="0b120-120">SQL Database</span><span class="sxs-lookup"><span data-stu-id="0b120-120">SQL Database</span></span></td>
    <td><span data-ttu-id="0b120-121">データベース</span><span class="sxs-lookup"><span data-stu-id="0b120-121">Databases</span></span><br><span data-ttu-id="0b120-122">ファイアウォール</span><span class="sxs-lookup"><span data-stu-id="0b120-122">Firewalls</span></span><br><span data-ttu-id="0b120-123">エラスティック プール</span><span class="sxs-lookup"><span data-stu-id="0b120-123">Elastic pools</span></span></td>
    <td></td>
    <td valign="top"></td>
  </tr>
  <tr>
    <td><span data-ttu-id="0b120-124">ネットワーク</span><span class="sxs-lookup"><span data-stu-id="0b120-124">Networking</span></span></td>
    <td><span data-ttu-id="0b120-125">仮想ネットワーク</span><span class="sxs-lookup"><span data-stu-id="0b120-125">Virtual networks</span></span><br><span data-ttu-id="0b120-126">ネットワーク インターフェイス</span><span class="sxs-lookup"><span data-stu-id="0b120-126">Network interfaces</span></span><br><span data-ttu-id="0b120-127">IP アドレス</span><span class="sxs-lookup"><span data-stu-id="0b120-127">IP addresses</span></span><br><span data-ttu-id="0b120-128">ルーティング テーブル</span><span class="sxs-lookup"><span data-stu-id="0b120-128">Routing table</span></span><br><span data-ttu-id="0b120-129">ネットワーク セキュリティ グループ</span><span class="sxs-lookup"><span data-stu-id="0b120-129">Network security groups</span></span><br><span data-ttu-id="0b120-130">DNS</span><span class="sxs-lookup"><span data-stu-id="0b120-130">DNS</span></span><br><span data-ttu-id="0b120-131">Traffic Manager</span><span class="sxs-lookup"><span data-stu-id="0b120-131">Traffic managers</span></span></td>
    <td valign="top"><span data-ttu-id="0b120-132">ロード バランサー</span><span class="sxs-lookup"><span data-stu-id="0b120-132">Load balancers</span></span><br><span data-ttu-id="0b120-133">アプリケーション ゲートウェイ</span><span class="sxs-lookup"><span data-stu-id="0b120-133">Application gateways</span></span></td>
    <td valign="top"></td>
  </tr>
  <tr>
    <td><span data-ttu-id="0b120-134">その他のサービス</span><span class="sxs-lookup"><span data-stu-id="0b120-134">More services</span></span></td>
    <td><span data-ttu-id="0b120-135">リソース マネージャー</span><span class="sxs-lookup"><span data-stu-id="0b120-135">Resource Manager</span></span><br><span data-ttu-id="0b120-136">Key Vault</span><span class="sxs-lookup"><span data-stu-id="0b120-136">Key Vault</span></span><br><span data-ttu-id="0b120-137">Redis</span><span class="sxs-lookup"><span data-stu-id="0b120-137">Redis</span></span><br><span data-ttu-id="0b120-138">CDN</span><span class="sxs-lookup"><span data-stu-id="0b120-138">CDN</span></span><br><span data-ttu-id="0b120-139">Batch
</span><span class="sxs-lookup"><span data-stu-id="0b120-139">Batch</span></span></td>
    <td valign="top"><span data-ttu-id="0b120-140">App Service - Web アプリ</span><span class="sxs-lookup"><span data-stu-id="0b120-140">App service - Web apps</span></span><br><span data-ttu-id="0b120-141">Functions</span><span class="sxs-lookup"><span data-stu-id="0b120-141">Functions</span></span><br><span data-ttu-id="0b120-142">Service Bus</span><span class="sxs-lookup"><span data-stu-id="0b120-142">Service bus</span></span></td>
    <td valign="top"><span data-ttu-id="0b120-143">監視</span><span class="sxs-lookup"><span data-stu-id="0b120-143">Monitor</span></span><br><span data-ttu-id="0b120-144">Graph RBAC</span><span class="sxs-lookup"><span data-stu-id="0b120-144">Graph RBAC</span></span><br><span data-ttu-id="0b120-145">DocumentDB</span><span class="sxs-lookup"><span data-stu-id="0b120-145">DocumentDB</span></span><br><span data-ttu-id="0b120-146">Scheduler</span><span class="sxs-lookup"><span data-stu-id="0b120-146">Scheduler</span></span></td>
  </tr>
  <tr>
    <td><span data-ttu-id="0b120-147">基礎</span><span class="sxs-lookup"><span data-stu-id="0b120-147">Fundamentals</span></span></td>
    <td><span data-ttu-id="0b120-148">認証 - コア</span><span class="sxs-lookup"><span data-stu-id="0b120-148">Authentication - core</span></span></td>
    <td><span data-ttu-id="0b120-149">非同期メソッド</span><span class="sxs-lookup"><span data-stu-id="0b120-149">Async methods</span></span></td>
    <td valign="top"></td>
  </tr>
</table>

> [!WARNING] 
> <span data-ttu-id="0b120-150">"*プレビュー*" 機能は、ライブラリ内のドキュメントのコメントにフラグが付けられています。</span><span class="sxs-lookup"><span data-stu-id="0b120-150">*Preview* features are flagged in documentation comments in libraries.</span></span> <span data-ttu-id="0b120-151">これらの機能は、変更されることがあります。</span><span class="sxs-lookup"><span data-stu-id="0b120-151">These features are subject to change.</span></span> <span data-ttu-id="0b120-152">将来、何らかの変更が行われる (または削除される) 可能性があります。</span><span class="sxs-lookup"><span data-stu-id="0b120-152">They can be modified in any way (or even removed) in the future.</span></span>

[!include[Contribute and community](includes/contribute.md)]
