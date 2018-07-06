Azure Management Libraries for .NET を使うには、Azure サブスクリプション内のリソースの読み取りと作成を行うアクセス許可が、.NET アプリケーションに必要です。 サービス プリンシパルを作成し、その資格情報で実行してこのアクセスを許可するようにアプリを構成してください。 サービス プリンシパルによって、自分の ID に関連付けられた非対話型のアカウントを作成し、アプリの実行に必要な特権だけを与えることができます。

最初に、Azure PowerShell にログインします。

```powershell
Login-AzureRmAccount
```

表示されるテナントとサブスクリプションの情報に注意してください。

```plaintext
Environment           : AzureCloud
Account               : jane@contoso.com
TenantId              : 43413cc1-5886-4711-9804-8cfea3d1c3ee
SubscriptionId        : 15dbcfa8-4b93-4c9a-881c-6189d39f04d4
SubscriptionName      : my-subscription
CurrentStorageAccount : 
```

次に示すように、[PowerShell を使ってサービス プリンシパルを作成](/powershell/azure/create-azure-service-principal-azureps)します。 

> [!NOTE]
> `New-AzureRmADServicePrincipal` コマンドレットによって "同じ identifierUris プロパティ値を持つ別のオブジェクトが既に存在します" が返される場合は、ご使用のテナント内にその名前のサービス プリンシパルが既に存在します。 **DisplayName** パラメーターに別の値を使用してください。 

```powershell
# Create the service principal (use a strong password)
$cred = Get-Credential
$sp = New-AzureRmADServicePrincipal -DisplayName "AzureDotNetTest" -Password $cred.Password

# Give it the permissions it needs...
New-AzureRmRoleAssignment -ServicePrincipalName $sp.ApplicationId -RoleDefinitionName Contributor

# Display the Application ID, because we'll need it later.
$sp | Select DisplayName, ApplicationId
```

ApplicationId を書き留めておいてください。

```plaintext
DisplayName     ApplicationId
-----------     -------------
AzureDotNetTest a2ab11af-01aa-4759-8345-7803287dbd39
```
