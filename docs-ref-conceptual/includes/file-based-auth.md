---
ms.service: multiple
ms.date: 9/20/2018
ms.topic: include
ms.openlocfilehash: 7f7c24957d2bc0574fc0b1bf2a8ae8fe8b4dfc64
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190715"
---
<span data-ttu-id="8929d-101">`azureauth.json` という名前でテキスト ファイルを作成します。</span><span class="sxs-lookup"><span data-stu-id="8929d-101">Create a text file named `azureauth.json`.</span></span> <span data-ttu-id="8929d-102">サービス プリンシパル作成時の JSON 出力を貼り付けます。</span><span class="sxs-lookup"><span data-stu-id="8929d-102">Paste the JSON output from when you created the service principal.</span></span>

<span data-ttu-id="8929d-103">このファイルは、コードで読み取ることができるシステム上の安全な場所に保存してください。</span><span class="sxs-lookup"><span data-stu-id="8929d-103">Save this file in a secure location on your system where your code can read it.</span></span> <span data-ttu-id="8929d-104">PowerShell を使用して、`AZURE_AUTH_LOCATION` という名前の環境変数を設定します。このときに、保存したテキスト ファイルの完全なパスも指定します。次に例を示します。</span><span class="sxs-lookup"><span data-stu-id="8929d-104">Use PowerShell to set an environment variable named `AZURE_AUTH_LOCATION` with the full path to the file, for example:</span></span>

```powershell
[Environment]::SetEnvironmentVariable("AZURE_AUTH_LOCATION", "C:\src\azureauth.json", "User")
```
