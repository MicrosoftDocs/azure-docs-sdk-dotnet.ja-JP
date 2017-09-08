<span data-ttu-id="e8a63-101">サービス プリンシパルの資格情報を使用して、`azureauth.properties` という名前のテキスト ファイルを作成します。</span><span class="sxs-lookup"><span data-stu-id="e8a63-101">Create a text file named `azureauth.properties` using the service principal credentials:</span></span>

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

- <span data-ttu-id="e8a63-102">subscription: `Login-AzureRmAccount` を実行したときの *SubscriptionId* 値を使用します。</span><span class="sxs-lookup"><span data-stu-id="e8a63-102">subscription: use the *SubscriptionId* value from when you ran `Login-AzureRmAccount`.</span></span>
- <span data-ttu-id="e8a63-103">client: サービス プリンシパルの出力の *ApplicationId* 値を使用します。</span><span class="sxs-lookup"><span data-stu-id="e8a63-103">client: use the *ApplicationId* value from the service principal output.</span></span>
- <span data-ttu-id="e8a63-104">key: `New-AzureRmADServicePrincipal` を実行したときに割り当てた *-Password* パラメーターを使用します (引用符は不要)。</span><span class="sxs-lookup"><span data-stu-id="e8a63-104">key: use the *-Password* parameter you assigned when you ran `New-AzureRmADServicePrincipal` (without quotes).</span></span>
- <span data-ttu-id="e8a63-105">tenant: `Login-AzureRmAccount` を実行したときの *TenantId* 値を使用します。</span><span class="sxs-lookup"><span data-stu-id="e8a63-105">tenant: use the *TenantId* value from when you ran `Login-AzureRmAccount`.</span></span>

<span data-ttu-id="e8a63-106">このファイルは、コードから読み取ることができるシステム上の安全な場所に保存してください。</span><span class="sxs-lookup"><span data-stu-id="e8a63-106">Save this file in a secure location on your system where your code can read it.</span></span> <span data-ttu-id="e8a63-107">PowerShell を使用して、`AZURE_AUTH_LOCATION` という名前の環境変数を設定します。このときに、保存したテキスト ファイルの完全なパスも指定します。次に例を示します。</span><span class="sxs-lookup"><span data-stu-id="e8a63-107">Use PowerShell to set an environment variable named `AZURE_AUTH_LOCATION` with the full path to the file, for example:</span></span>

```powershell
[Environment]::SetEnvironmentVariable("AZURE_AUTH_LOCATION", "C:\src\azureauth.properties", "User")
```
