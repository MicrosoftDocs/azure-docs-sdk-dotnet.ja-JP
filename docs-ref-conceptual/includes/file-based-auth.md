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
`azureauth.json` という名前でテキスト ファイルを作成します。 サービス プリンシパル作成時の JSON 出力を貼り付けます。

このファイルは、コードで読み取ることができるシステム上の安全な場所に保存してください。 PowerShell を使用して、`AZURE_AUTH_LOCATION` という名前の環境変数を設定します。このときに、保存したテキスト ファイルの完全なパスも指定します。次に例を示します。

```powershell
[Environment]::SetEnvironmentVariable("AZURE_AUTH_LOCATION", "C:\src\azureauth.json", "User")
```
