---
title: .NET 用 Azure 管理ライブラリ リリース ノート | Microsoft Docs
description: .NET 用 Azure 管理ライブラリの新機能や重大な変更が記載されています。
ms.date: 10/19/2017
ms.openlocfilehash: dac9dee9c25fc349dedd50d6007f25c7d15b0928
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190675"
---
# <a name="release-notes"></a><span data-ttu-id="1a758-103">リリース ノート</span><span class="sxs-lookup"><span data-stu-id="1a758-103">Release Notes</span></span> 

## <a name="feature-availability-and-road-map-as-of-version-100"></a><span data-ttu-id="1a758-104">バージョン 1.0.0 の時点での機能の使用可能性とロード マップ</span><span class="sxs-lookup"><span data-stu-id="1a758-104">Feature Availability and Road Map as of Version 1.0.0</span></span> ##
### <a name="april-26-2017"></a><span data-ttu-id="1a758-105">2017 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="1a758-105">April 26, 2017</span></span>

<table>
  <tr>
    <th align="left"><span data-ttu-id="1a758-106">サービス | 機能</span><span class="sxs-lookup"><span data-stu-id="1a758-106">Service | feature</span></span></th>
    <th align="left"><span data-ttu-id="1a758-107">GA として利用可能</span><span class="sxs-lookup"><span data-stu-id="1a758-107">Available as GA</span></span></th>
    <th align="left"><span data-ttu-id="1a758-108">プレビューとして利用可能</span><span class="sxs-lookup"><span data-stu-id="1a758-108">Available as Preview</span></span></th>
    <th align="left"><span data-ttu-id="1a758-109">近日対応予定</span><span class="sxs-lookup"><span data-stu-id="1a758-109">Coming soon</span></span></th>
  </tr>
  <tr>
    <td><span data-ttu-id="1a758-110">コンピューティング</span><span class="sxs-lookup"><span data-stu-id="1a758-110">Compute</span></span></td>
    <td><span data-ttu-id="1a758-111">仮想マシンと VM 拡張機能</span><span class="sxs-lookup"><span data-stu-id="1a758-111">Virtual machines and VM extensions</span></span><br><span data-ttu-id="1a758-112">仮想マシン スケール セット</span><span class="sxs-lookup"><span data-stu-id="1a758-112">Virtual machine scale sets</span></span><br><span data-ttu-id="1a758-113">マネージド ディスク</span><span class="sxs-lookup"><span data-stu-id="1a758-113">Managed disks</span></span></td>
    <td></td>
    <td valign="top"><span data-ttu-id="1a758-114">Azure コンテナー サービス</span><span class="sxs-lookup"><span data-stu-id="1a758-114">Azure container services</span></span><br><span data-ttu-id="1a758-115">Azure コンテナー レジストリ</span><span class="sxs-lookup"><span data-stu-id="1a758-115">Azure container registry</span></span></td>
  </tr>
  <tr>
    <td><span data-ttu-id="1a758-116">Storage</span><span class="sxs-lookup"><span data-stu-id="1a758-116">Storage</span></span></td>
    <td><span data-ttu-id="1a758-117">ストレージ アカウント</span><span class="sxs-lookup"><span data-stu-id="1a758-117">Storage accounts</span></span></td>
    <td></td>
    <td><span data-ttu-id="1a758-118">暗号化</span><span class="sxs-lookup"><span data-stu-id="1a758-118">Encryption</span></span></td>
  </tr>
  <tr>
    <td><span data-ttu-id="1a758-119">SQL Database</span><span class="sxs-lookup"><span data-stu-id="1a758-119">SQL Database</span></span></td>
    <td><span data-ttu-id="1a758-120">データベース</span><span class="sxs-lookup"><span data-stu-id="1a758-120">Databases</span></span><br><span data-ttu-id="1a758-121">ファイアウォール</span><span class="sxs-lookup"><span data-stu-id="1a758-121">Firewalls</span></span><br><span data-ttu-id="1a758-122">エラスティック プール</span><span class="sxs-lookup"><span data-stu-id="1a758-122">Elastic pools</span></span></td>
    <td></td>
    <td valign="top"></td>
  </tr>
  <tr>
    <td><span data-ttu-id="1a758-123">ネットワーク</span><span class="sxs-lookup"><span data-stu-id="1a758-123">Networking</span></span></td>
    <td><span data-ttu-id="1a758-124">仮想ネットワーク</span><span class="sxs-lookup"><span data-stu-id="1a758-124">Virtual networks</span></span><br><span data-ttu-id="1a758-125">ネットワーク インターフェイス</span><span class="sxs-lookup"><span data-stu-id="1a758-125">Network interfaces</span></span><br><span data-ttu-id="1a758-126">IP アドレス</span><span class="sxs-lookup"><span data-stu-id="1a758-126">IP addresses</span></span><br><span data-ttu-id="1a758-127">ルーティング テーブル</span><span class="sxs-lookup"><span data-stu-id="1a758-127">Routing table</span></span><br><span data-ttu-id="1a758-128">ネットワーク セキュリティ グループ</span><span class="sxs-lookup"><span data-stu-id="1a758-128">Network security groups</span></span><br><span data-ttu-id="1a758-129">DNS</span><span class="sxs-lookup"><span data-stu-id="1a758-129">DNS</span></span><br><span data-ttu-id="1a758-130">Traffic Manager</span><span class="sxs-lookup"><span data-stu-id="1a758-130">Traffic managers</span></span></td>
    <td valign="top"><span data-ttu-id="1a758-131">ロード バランサー</span><span class="sxs-lookup"><span data-stu-id="1a758-131">Load balancers</span></span><br><span data-ttu-id="1a758-132">アプリケーション ゲートウェイ</span><span class="sxs-lookup"><span data-stu-id="1a758-132">Application gateways</span></span></td>
    <td valign="top"></td>
  </tr>
  <tr>
    <td><span data-ttu-id="1a758-133">その他のサービス</span><span class="sxs-lookup"><span data-stu-id="1a758-133">More services</span></span></td>
    <td><span data-ttu-id="1a758-134">リソース マネージャー</span><span class="sxs-lookup"><span data-stu-id="1a758-134">Resource Manager</span></span><br><span data-ttu-id="1a758-135">Key Vault</span><span class="sxs-lookup"><span data-stu-id="1a758-135">Key Vault</span></span><br><span data-ttu-id="1a758-136">Redis</span><span class="sxs-lookup"><span data-stu-id="1a758-136">Redis</span></span><br><span data-ttu-id="1a758-137">CDN</span><span class="sxs-lookup"><span data-stu-id="1a758-137">CDN</span></span><br><span data-ttu-id="1a758-138">Batch</span><span class="sxs-lookup"><span data-stu-id="1a758-138">Batch</span></span></td>
    <td valign="top"><span data-ttu-id="1a758-139">App Service - Web アプリ</span><span class="sxs-lookup"><span data-stu-id="1a758-139">App service - Web apps</span></span><br><span data-ttu-id="1a758-140">Functions</span><span class="sxs-lookup"><span data-stu-id="1a758-140">Functions</span></span><br><span data-ttu-id="1a758-141">Service Bus</span><span class="sxs-lookup"><span data-stu-id="1a758-141">Service bus</span></span></td>
    <td valign="top"><span data-ttu-id="1a758-142">監視</span><span class="sxs-lookup"><span data-stu-id="1a758-142">Monitor</span></span><br><span data-ttu-id="1a758-143">Graph RBAC</span><span class="sxs-lookup"><span data-stu-id="1a758-143">Graph RBAC</span></span><br><span data-ttu-id="1a758-144">Azure Cosmos DB</span><span class="sxs-lookup"><span data-stu-id="1a758-144">Azure Cosmos DB</span></span><br><span data-ttu-id="1a758-145">Scheduler</span><span class="sxs-lookup"><span data-stu-id="1a758-145">Scheduler</span></span></td>
  </tr>
  <tr>
    <td><span data-ttu-id="1a758-146">基礎</span><span class="sxs-lookup"><span data-stu-id="1a758-146">Fundamentals</span></span></td>
    <td><span data-ttu-id="1a758-147">認証 - コア</span><span class="sxs-lookup"><span data-stu-id="1a758-147">Authentication - core</span></span></td>
    <td><span data-ttu-id="1a758-148">非同期メソッド</span><span class="sxs-lookup"><span data-stu-id="1a758-148">Async methods</span></span></td>
    <td valign="top"></td>
  </tr>
</table>

> [!WARNING] 
> <span data-ttu-id="1a758-149">"*プレビュー*" 機能は、ライブラリ内のドキュメントのコメントにフラグが付けられています。</span><span class="sxs-lookup"><span data-stu-id="1a758-149">*Preview* features are flagged in documentation comments in libraries.</span></span> <span data-ttu-id="1a758-150">これらの機能は、変更されることがあります。</span><span class="sxs-lookup"><span data-stu-id="1a758-150">These features are subject to change.</span></span> <span data-ttu-id="1a758-151">将来、何らかの変更が行われる (または削除される) 可能性があります。</span><span class="sxs-lookup"><span data-stu-id="1a758-151">They can be modified in any way (or even removed) in the future.</span></span>

[!include[Contribute and community](includes/contribute.md)]
