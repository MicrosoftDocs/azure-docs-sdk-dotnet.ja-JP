サービス プリンシパルの資格情報を使用して、`azureauth.properties` という名前のテキスト ファイルを作成します。

```plaintext
# sample management library properties file
subscription=15dbcfa8-4b93-4c9a-881c-6189d39f04d4
client=a2ab11af-01aa-4759-8345-7803287dbd39
key=password
tenant=43413cc1-5886-4711-9804-8cfea3d1c3ee
managementURI=https://management.core.windows.net/
baseURL=https://management.azure.com/
authURL=https://login.windows.net/
graphURL=https://graph.windows.net/
```

- subscription: `Login-AzureRmAccount` を実行したときの *SubscriptionId* 値を使用します。
- client: サービス プリンシパルの出力の *ApplicationId* 値を使用します。
- key: `New-AzureRmADServicePrincipal` を実行したときに割り当てた *-Password* パラメーターを使用します (引用符は不要)。
- tenant: `Login-AzureRmAccount` を実行したときの *TenantId* 値を使用します。

このファイルは、コードから読み取ることができるシステム上の安全な場所に保存してください。 PowerShell を使用して、`AZURE_AUTH_LOCATION` という名前の環境変数を設定します。このときに、保存したテキスト ファイルの完全なパスも指定します。次に例を示します。

```powershell
[Environment]::SetEnvironmentVariable("AZURE_AUTH_LOCATION", "C:\src\azureauth.properties", "User")
```
