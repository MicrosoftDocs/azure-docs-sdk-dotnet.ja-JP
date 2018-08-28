`azureauth.json` という名前でテキスト ファイルを作成します。 サービス プリンシパル作成時の JSON 出力を貼り付けます。

このファイルは、コードで読み取ることができるシステム上の安全な場所に保存してください。 PowerShell を使用して、`AZURE_AUTH_LOCATION` という名前の環境変数を設定します。このときに、保存したテキスト ファイルの完全なパスも指定します。次に例を示します。

```powershell
[Environment]::SetEnvironmentVariable("AZURE_AUTH_LOCATION", "C:\src\azureauth.json", "User")
```
