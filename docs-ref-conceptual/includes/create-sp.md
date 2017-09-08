<span data-ttu-id="4ce0a-101">Azure Management Libraries for .NET を使うには、Azure サブスクリプション内のリソースの読み取りと作成を行うアクセス許可が、.NET アプリケーションに必要です。</span><span class="sxs-lookup"><span data-stu-id="4ce0a-101">Your .NET application needs permissions to read and create resources in your Azure subscription in order to use the Azure Management Libraries for .NET.</span></span> <span data-ttu-id="4ce0a-102">サービス プリンシパルを作成し、その資格情報で実行してこのアクセスを許可するようにアプリを構成してください。</span><span class="sxs-lookup"><span data-stu-id="4ce0a-102">Create a service principal and configure your app to run with its credentials to grant this access.</span></span> <span data-ttu-id="4ce0a-103">サービス プリンシパルによって、自分の ID に関連付けられた非対話型のアカウントを作成し、アプリの実行に必要な特権だけを与えることができます。</span><span class="sxs-lookup"><span data-stu-id="4ce0a-103">Service principals provide a way to create a non-interactive account associated with your identity to which you grant only the privileges your app needs to run.</span></span>

<span data-ttu-id="4ce0a-104">最初に、Azure PowerShell にログインします。</span><span class="sxs-lookup"><span data-stu-id="4ce0a-104">First, login to Azure PowerShell:</span></span>

```powershell
Login-AzureRmAccount
```

<span data-ttu-id="4ce0a-105">表示されるテナントとサブスクリプションの情報に注意してください。</span><span class="sxs-lookup"><span data-stu-id="4ce0a-105">Note the information displayed about your tenant and subscription:</span></span>

```plaintext
Environment           : AzureCloud
Account               : jane@contoso.com
TenantId              : 43413cc1-5886-4711-9804-8cfea3d1c3ee
SubscriptionId        : 15dbcfa8-4b93-4c9a-881c-6189d39f04d4
SubscriptionName      : my-subscription
CurrentStorageAccount : 
```

<span data-ttu-id="4ce0a-106">次のように、[PowerShell を使ってサービス プリンシパルを作成](/powershell/azure/create-azure-service-principal-azureps)します。</span><span class="sxs-lookup"><span data-stu-id="4ce0a-106">[Create a service principal using PowerShell](/powershell/azure/create-azure-service-principal-azureps), like this:</span></span>

```powershell
# Create the service principal (use a strong password)
$sp = New-AzureRmADServicePrincipal -DisplayName "AzureDotNetTest" -Password "password"

# Give it the permissions it needs...
New-AzureRmRoleAssignment -ServicePrincipalName $sp.ApplicationId -RoleDefinitionName Contributor

# Display the Application ID, because we'll need it later.
$sp | Select DisplayName, ApplicationId
```

<span data-ttu-id="4ce0a-107">ApplicationId を書き留めておいてください。</span><span class="sxs-lookup"><span data-stu-id="4ce0a-107">Make sure to note the ApplicationId:</span></span>

```plaintext
DisplayName     ApplicationId
-----------     -------------
AzureDotNetTest a2ab11af-01aa-4759-8345-7803287dbd39
```
