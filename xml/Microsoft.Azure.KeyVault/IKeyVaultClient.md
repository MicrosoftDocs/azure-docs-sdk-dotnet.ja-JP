<Type Name="IKeyVaultClient" FullName="Microsoft.Azure.KeyVault.IKeyVaultClient">
  <TypeSignature Language="C#" Value="public interface IKeyVaultClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IKeyVaultClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.IKeyVaultClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IKeyVaultClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IKeyVaultClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="1b43a-101">暗号化キーの操作を実行し、Key Vault サービスに対する操作が資格情報コンテナーのクライアント クラスです。</span><span class="sxs-lookup"><span data-stu-id="1b43a-101">Client class to perform cryptographic key operations and vault operations against the Key Vault service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.IKeyVaultClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.KeyVault.IKeyVaultClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b43a-102">取得または応答の優先言語を設定します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-102">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.IKeyVaultClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.KeyVault.IKeyVaultClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b43a-103">クライアント API のバージョンです。</span><span class="sxs-lookup"><span data-stu-id="1b43a-103">Client API version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt; BackupKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt; BackupKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.BackupKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BackupKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt;" Usage="iKeyVaultClient.BackupKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-104">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-104">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-105">キー名。</span><span class="sxs-lookup"><span data-stu-id="1b43a-105">The name of the key.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-108">指定したキーのバックアップをクライアントにダウンロードするように要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-108">Requests that a backup of the specified key be downloaded to the client.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-109">キーのバックアップ操作は、保護された形式で、Azure Key Vault からキーをエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="1b43a-109">The Key Backup operation exports a key from Azure Key Vault in a protected form.</span></span> <span data-ttu-id="1b43a-110">この操作では、Azure Key Vault システムの外部で使用できる形式では、キー マテリアルは返しません、返されるキー マテリアルは保護 Azure Key Vault HSM または Azure Key Vault 自体ことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="1b43a-110">Note that this operation does NOT return key material in a form that can be used outside the Azure Key Vault system, the returned key material is either protected to a Azure Key Vault HSM or to Azure Key Vault itself.</span></span> <span data-ttu-id="1b43a-111">この操作の目的は、キーのバックアップ、1 つの Azure Key Vault インスタンスでキーを生成し、別の Azure Key Vault インスタンスに復元してクライアントを許可するのにです。</span><span class="sxs-lookup"><span data-stu-id="1b43a-111">The intent of this operation is to allow a client to GENERATE a key in one Azure Key Vault instance, BACKUP the key, and then RESTORE it into another Azure Key Vault instance.</span></span> <span data-ttu-id="1b43a-112">バックアップ操作は、エクスポートする保護対象のフォームでは、Azure Key Vault からのすべてのキー タイプに使用可能性があります。</span><span class="sxs-lookup"><span data-stu-id="1b43a-112">The BACKUP operation may be used to export, in protected form, any key type from Azure Key Vault.</span></span>
            <span data-ttu-id="1b43a-113">キーの個別のバージョンは、バックアップすることはできません。</span><span class="sxs-lookup"><span data-stu-id="1b43a-113">Individual versions of a key cannot be backed up.</span></span> <span data-ttu-id="1b43a-114">バックアップ/復元は地理的な境界のみ; 内で実行できます別の地理的領域に 1 つの地理的領域からバックアップを復元できないことを意味します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-114">BACKUP / RESTORE can be performed within geographical boundaries only; meaning that a BACKUP from one geographical area cannot be restored to another geographical area.</span></span> <span data-ttu-id="1b43a-115">たとえば、米国の地理的領域からのバックアップを EU の地理的領域に復元できません。</span><span class="sxs-lookup"><span data-stu-id="1b43a-115">For example, a backup from the US geographical area cannot be restored in an EU geographical area.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt; BackupSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt; BackupSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.BackupSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BackupSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt;" Usage="iKeyVaultClient.BackupSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-116">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-116">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="1b43a-117">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-117">The name of the secret.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-118">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-120">指定したシークレットのバックアップをクライアントにダウンロードするように要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-120">Requests that a backup of the specified secret be downloaded to the client.</span></span> <span data-ttu-id="1b43a-121">認証:、シークレット/バックアップ権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-121">Authorization: requires the secrets/backup permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; CreateCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; CreateCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.CreateCertificateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateCertificateWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="iKeyVaultClient.CreateCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificatePolicy, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-122">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-122">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="1b43a-123">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-123">The name of the certificate.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="1b43a-124">証明書の管理ポリシー。</span><span class="sxs-lookup"><span data-stu-id="1b43a-124">The management policy for the certificate.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="1b43a-125">(省略可能) の証明書の属性。</span><span class="sxs-lookup"><span data-stu-id="1b43a-125">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="1b43a-126">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="1b43a-126">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-127">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-127">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-129">新しい証明書を作成します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-129">Creates a new certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-130">これが最初のバージョンである場合は、証明書リソースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-130">If this is the first version, the certificate resource is created.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; CreateKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string kty, Nullable&lt;int&gt; keySize = null, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string curve = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; CreateKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string kty, valuetype System.Nullable`1&lt;int32&gt; keySize, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string curve, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.CreateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyWithHttpMessagesAsync : string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="iKeyVaultClient.CreateKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, kty, keySize, keyOps, keyAttributes, tags, curve, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="kty" Type="System.String" />
        <Parameter Name="keySize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="curve" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-131">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-131">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-132">新しいキーの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-132">The name for the new key.</span></span> <span data-ttu-id="1b43a-133">システムでは、新しいキーのバージョン名を生成します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-133">The system will generate the version name for the new key.</span></span>
            </param>
        <param name="kty">
            <span data-ttu-id="1b43a-134">作成するキーの型。</span><span class="sxs-lookup"><span data-stu-id="1b43a-134">The type of key to create.</span></span> <span data-ttu-id="1b43a-135">有効な値は、JsonWebKeyType を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1b43a-135">For valid values, see JsonWebKeyType.</span></span>
            <span data-ttu-id="1b43a-136">使用可能な値が含まれます: 'EC'、' EC HSM'、'RSA'、' RSA-HSM '、'oct'</span><span class="sxs-lookup"><span data-stu-id="1b43a-136">Possible values include: 'EC', 'EC-HSM', 'RSA', 'RSA-HSM', 'oct'</span></span>
            </param>
        <param name="keySize">
            <span data-ttu-id="1b43a-137">キーのサイズ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="1b43a-137">The key size in bytes.</span></span> <span data-ttu-id="1b43a-138">たとえば、1024 または 2048。</span><span class="sxs-lookup"><span data-stu-id="1b43a-138">For example, 1024 or 2048.</span></span>
            </param>
        <param name="keyOps"></param>
        <param name="keyAttributes"></param>
        <param name="tags">
            <span data-ttu-id="1b43a-139">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="1b43a-139">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="curve">
            <span data-ttu-id="1b43a-140">楕円曲線の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-140">Elliptic curve name.</span></span> <span data-ttu-id="1b43a-141">有効な値は、JsonWebKeyCurveName を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1b43a-141">For valid values, see JsonWebKeyCurveName.</span></span>
            <span data-ttu-id="1b43a-142">使用可能な値が含まれます: 'P-256'、'P-384'、'P-521'、'SECP256K1'</span><span class="sxs-lookup"><span data-stu-id="1b43a-142">Possible values include: 'P-256', 'P-384', 'P-521', 'SECP256K1'</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-143">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-143">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-145">新しいキーを作成、格納、キー パラメーターを返し、属性をクライアントにします。</span><span class="sxs-lookup"><span data-stu-id="1b43a-145">Creates a new key, stores it, then returns key parameters and attributes to the client.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-146">キーの作成処理は、Azure Key Vault 内のすべてのキー タイプの作成に使用できます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-146">The create key operation can be used to create any key type in Azure Key Vault.</span></span> <span data-ttu-id="1b43a-147">名前付きのキーが既に存在する場合、Azure Key Vault には、キーの新しいバージョンが作成されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-147">If the named key already exists, Azure Key Vault creates a new version of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.IKeyVaultClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.KeyVault.IKeyVaultClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b43a-148">Azure に接続するクライアントに必要な資格情報です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-148">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; DecryptWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; DecryptWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.DecryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DecryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="iKeyVaultClient.DecryptWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-149">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-149">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-150">キー名。</span><span class="sxs-lookup"><span data-stu-id="1b43a-150">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="1b43a-151">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-151">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="1b43a-152">アルゴリズムの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-152">algorithm identifier.</span></span> <span data-ttu-id="1b43a-153">使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。</span><span class="sxs-lookup"><span data-stu-id="1b43a-153">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-154">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-154">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-156">暗号化されたデータの 1 つのブロックを解除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-156">Decrypts a single block of encrypted data.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-157">DECRYPT 操作は、ターゲット暗号化キーと指定されたアルゴリズムを使用して暗号テキストの整形式ブロックを解除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-157">The DECRYPT operation decrypts a well-formed block of ciphertext using the target encryption key and specified algorithm.</span></span> <span data-ttu-id="1b43a-158">この操作は、ENCRYPT 操作の逆だけでデータの 1 つのブロックは、暗号化が解除された可能性があります、このブロックのサイズは対象のキーと使用するアルゴリズムによって異なります。</span><span class="sxs-lookup"><span data-stu-id="1b43a-158">This operation is the reverse of the ENCRYPT operation; only a single block of data may be decrypted, the size of this block is dependent on the target key and the algorithm to be used.</span></span> <span data-ttu-id="1b43a-159">DECRYPT 操作は、非対称キーおよび対称キー、キーの秘密部分を使用しているので、Azure Key Vault に格納されているに適用されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-159">The DECRYPT operation applies to asymmetric and symmetric keys stored in Azure Key Vault since it uses the private portion of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateContactsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; DeleteCertificateContactsWithHttpMessagesAsync (string vaultBaseUrl, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; DeleteCertificateContactsWithHttpMessagesAsync(string vaultBaseUrl, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;" Usage="iKeyVaultClient.DeleteCertificateContactsWithHttpMessagesAsync (vaultBaseUrl, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-160">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-160">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-161">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-161">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-163">指定されたキー コンテナーの証明書の連絡先を削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-163">Deletes the certificate contacts for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-164">指定した資格情報コンテナー証明書の証明書の連絡先を削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-164">Deletes the certificate contacts for a specified key vault certificate.</span></span> <span data-ttu-id="1b43a-165">認証:、証明書/managecontacts 権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-165">Authorization: requires the certificates/managecontacts permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; DeleteCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; DeleteCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="iKeyVaultClient.DeleteCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-166">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-166">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="1b43a-167">発行者の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-167">The name of the issuer.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-168">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-168">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-169">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-170">指定された証明書の発行者を削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-170">Deletes the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-171">DeleteCertificateIssuer 操作は、資格情報コンテナーから、指定された証明書の発行者を完全に削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-171">The DeleteCertificateIssuer operation permanently removes the specified certificate issuer from the vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; DeleteCertificateOperationWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; DeleteCertificateOperationWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="iKeyVaultClient.DeleteCertificateOperationWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-172">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-172">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="1b43a-173">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-173">The name of the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-174">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-174">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-175">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-176">指定された証明書の操作を削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-176">Deletes the operation for a specified certificate.</span></span> <span data-ttu-id="1b43a-177">認証:、証明書/更新アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-177">Authorization: requires the certificates/update permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; DeleteCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; DeleteCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;" Usage="iKeyVaultClient.DeleteCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-178">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-178">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="1b43a-179">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-179">The name of the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-180">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-180">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-182">指定したキー資格情報コンテナーから証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-182">Deletes a certificate from a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-183">関連付けられているポリシーと共に証明書オブジェクトのすべてのバージョンを削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-183">Deletes all versions of a certificate object along with its associated policy.</span></span> <span data-ttu-id="1b43a-184">削除証明書オブジェクトの個々 のバージョンを削除する証明書を使用することはできません。</span><span class="sxs-lookup"><span data-stu-id="1b43a-184">Delete certificate cannot be used to remove individual versions of a certificate object.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; DeleteKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; DeleteKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;" Usage="iKeyVaultClient.DeleteKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-185">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-185">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-186">削除するキーの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-186">The name of the key to delete.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-187">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-187">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-189">Azure Key Vault に記憶域から任意の型のキーを削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-189">Deletes a key of any type from storage in Azure Key Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-190">キーの個別のバージョンを削除するキーの削除操作を使用できません。</span><span class="sxs-lookup"><span data-stu-id="1b43a-190">The delete key operation cannot be used to remove individual versions of a key.</span></span> <span data-ttu-id="1b43a-191">この操作は、キーが署名/検証、ラップ/ラップ解除または暗号化/暗号化解除操作に使用しないことを意味すると、キーに関連付けられている暗号化マテリアルを削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-191">This operation removes the cryptographic material associated with the key, which means the key is not usable for Sign/Verify, Wrap/Unwrap or Encrypt/Decrypt operations.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; DeleteSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; DeleteSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="iKeyVaultClient.DeleteSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-192">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-192">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1b43a-193">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-193">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="1b43a-194">SAS の定義の名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-194">The name of the SAS definition.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-195">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-195">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-197">指定されたストレージ アカウントから SAS 定義を削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-197">Deletes a SAS definition from a specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; DeleteSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; DeleteSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;" Usage="iKeyVaultClient.DeleteSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-198">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-198">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="1b43a-199">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-199">The name of the secret.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-200">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-200">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-201">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-201">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-202">指定された key vault からシークレットを削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-202">Deletes a secret from a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-203">削除操作は、Azure Key Vault に格納されているシークレットに適用されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-203">The DELETE operation applies to any secret stored in Azure Key Vault.</span></span> <span data-ttu-id="1b43a-204">削除は、個々 のバージョンのシークレットに適用できません。</span><span class="sxs-lookup"><span data-stu-id="1b43a-204">DELETE cannot be applied to an individual version of a secret.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; DeleteStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; DeleteStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="iKeyVaultClient.DeleteStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-205">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-205">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1b43a-206">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-206">The name of the storage account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-207">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-207">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-208">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-209">ストレージ アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-209">Deletes a storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.IKeyVaultClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.KeyVault.IKeyVaultClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b43a-210">取得または json に逆シリアル化の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-210">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; EncryptWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; EncryptWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.EncryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EncryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="iKeyVaultClient.EncryptWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-211">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-211">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-212">キー名。</span><span class="sxs-lookup"><span data-stu-id="1b43a-212">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="1b43a-213">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-213">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="1b43a-214">アルゴリズムの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-214">algorithm identifier.</span></span> <span data-ttu-id="1b43a-215">使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。</span><span class="sxs-lookup"><span data-stu-id="1b43a-215">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-216">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-216">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-217">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-218">Key vault に格納されている暗号化キーを使用してバイトの任意の順序を暗号化します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-218">Encrypts an arbitrary sequence of bytes using an encryption key that is stored in a key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-219">ENCRYPT 操作では、Azure Key Vault に格納されている暗号化キーを使用してバイトの任意の順序を暗号化します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-219">The ENCRYPT operation encrypts an arbitrary sequence of bytes using an encryption key that is stored in Azure Key Vault.</span></span> <span data-ttu-id="1b43a-220">暗号化操作はサイズが、対象のキーと使用する暗号化アルゴリズムに依存して、データの 1 つのブロックのみをサポートする注意してください。</span><span class="sxs-lookup"><span data-stu-id="1b43a-220">Note that the ENCRYPT operation only supports a single block of data, the size of which is dependent on the target key and the encryption algorithm to be used.</span></span> <span data-ttu-id="1b43a-221">暗号化操作は、キーの公開部分を使用して非対称キーで保護を実行できるので、Azure Key Vault に格納されている対称キーの厳密に必要だけです。</span><span class="sxs-lookup"><span data-stu-id="1b43a-221">The ENCRYPT operation is only strictly necessary for symmetric keys stored in Azure Key Vault since protection with an asymmetric key can be performed using public portion of the key.</span></span>
            <span data-ttu-id="1b43a-222">この操作は、キー参照であるが、パブリックのキー マテリアルにアクセスできない呼び出し元の便宜を図って非対称キーのサポートは。</span><span class="sxs-lookup"><span data-stu-id="1b43a-222">This operation is supported for asymmetric keys as a convenience for callers that have a key-reference but do not have access to the public key material.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.IKeyVaultClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.KeyVault.IKeyVaultClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b43a-223">設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-223">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="1b43a-224">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-224">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateContactsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; GetCertificateContactsWithHttpMessagesAsync (string vaultBaseUrl, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; GetCertificateContactsWithHttpMessagesAsync(string vaultBaseUrl, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;" Usage="iKeyVaultClient.GetCertificateContactsWithHttpMessagesAsync (vaultBaseUrl, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-225">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-225">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-226">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-226">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-227">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-228">指定されたキー コンテナーの証明書の連絡先の一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-228">Lists the certificate contacts for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-229">GetCertificateContacts 操作は、指定されたキー コンテナーに証明書の連絡先のリソースのセットを返します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-229">The GetCertificateContacts operation returns the set of certificate contact resources in the specified key vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuersNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateIssuersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateIssuersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetCertificateIssuersNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1b43a-230">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-230">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-231">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-231">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-232">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-232">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-233">指定されたキー コンテナーの証明書の発行者をリストします。</span><span class="sxs-lookup"><span data-stu-id="1b43a-233">List certificate issuers for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-234">GetCertificateIssuers 操作は、指定されたキー コンテナーに証明書発行者のリソースのセットを返します</span><span class="sxs-lookup"><span data-stu-id="1b43a-234">The GetCertificateIssuers operation returns the set of certificate issuer resources in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateIssuersWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateIssuersWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetCertificateIssuersWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-235">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-235">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="1b43a-236">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="1b43a-236">Maximum number of results to return in a page.</span></span> <span data-ttu-id="1b43a-237">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="1b43a-237">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-238">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-238">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-239">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-239">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-240">指定されたキー コンテナーの証明書の発行者をリストします。</span><span class="sxs-lookup"><span data-stu-id="1b43a-240">List certificate issuers for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-241">GetCertificateIssuers 操作は、指定されたキー コンテナーに証明書発行者のリソースのセットを返します</span><span class="sxs-lookup"><span data-stu-id="1b43a-241">The GetCertificateIssuers operation returns the set of certificate issuer resources in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; GetCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; GetCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="iKeyVaultClient.GetCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-242">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-242">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="1b43a-243">発行者の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-243">The name of the issuer.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-244">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-244">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-245">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-245">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-246">指定された証明書の発行者の一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-246">Lists the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-247">GetCertificateIssuer 操作は、指定されたキー コンテナーに指定された証明書発行者リソースを返します</span><span class="sxs-lookup"><span data-stu-id="1b43a-247">The GetCertificateIssuer operation returns the specified certificate issuer resources in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; GetCertificateOperationWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; GetCertificateOperationWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="iKeyVaultClient.GetCertificateOperationWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-248">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-248">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="1b43a-249">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-249">The name of the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-250">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-250">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-251">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-251">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-252">指定された証明書に関連付けられている操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-252">Gets the operation associated with a specified certificate.</span></span>
            <span data-ttu-id="1b43a-253">認証:、証明書/取得アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-253">Authorization: requires the certificates/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatePolicyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; GetCertificatePolicyWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; GetCertificatePolicyWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificatePolicyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificatePolicyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;" Usage="iKeyVaultClient.GetCertificatePolicyWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-254">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-254">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="1b43a-255">指定されたキー コンテナーに証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-255">The name of the certificate in a given key vault.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-256">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-256">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-257">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-257">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-258">証明書のポリシーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-258">Lists the policy for a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-259">GetCertificatePolicy 操作は、指定されたキー コンテナーに指定された証明書ポリシー リソースを返します</span><span class="sxs-lookup"><span data-stu-id="1b43a-259">The GetCertificatePolicy operation returns the specified certificate policy resources in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetCertificatesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1b43a-260">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-260">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-261">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-261">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-262">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-262">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-263">指定されたキー コンテナーに証明書の一覧</span><span class="sxs-lookup"><span data-stu-id="1b43a-263">List certificates in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-264">GetCertificates 操作は、指定されたキー コンテナーに証明書のリソースのセットを返します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-264">The GetCertificates operation returns the set of certificates resources in the specified key vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetCertificatesWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-265">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-265">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="1b43a-266">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="1b43a-266">Maximum number of results to return in a page.</span></span> <span data-ttu-id="1b43a-267">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="1b43a-267">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-268">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-268">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-269">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-269">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-270">指定されたキー コンテナーに証明書の一覧</span><span class="sxs-lookup"><span data-stu-id="1b43a-270">List certificates in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-271">GetCertificates 操作は、指定されたキー コンテナーに証明書のリソースのセットを返します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-271">The GetCertificates operation returns the set of certificates resources in the specified key vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateVersionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetCertificateVersionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1b43a-272">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-272">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-273">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-273">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-274">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-274">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-275">証明書のバージョンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-275">List the versions of a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-276">GetCertificateVersions 操作は、指定されたキー コンテナーに証明書のバージョンを返します</span><span class="sxs-lookup"><span data-stu-id="1b43a-276">The GetCertificateVersions operation returns the versions of a certificate in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateVersionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetCertificateVersionsWithHttpMessagesAsync (vaultBaseUrl, certificateName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-277">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-277">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="1b43a-278">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-278">The name of the certificate.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="1b43a-279">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="1b43a-279">Maximum number of results to return in a page.</span></span> <span data-ttu-id="1b43a-280">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="1b43a-280">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-281">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-281">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-282">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-282">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-283">証明書のバージョンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-283">List the versions of a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-284">GetCertificateVersions 操作は、指定されたキー コンテナーに証明書のバージョンを返します</span><span class="sxs-lookup"><span data-stu-id="1b43a-284">The GetCertificateVersions operation returns the versions of a certificate in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; GetCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, string certificateVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; GetCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, string certificateVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="iKeyVaultClient.GetCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificateVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-285">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-285">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="1b43a-286">指定された資格情報コンテナー内の証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-286">The name of the certificate in the given vault.</span></span>
            </param>
        <param name="certificateVersion">
            <span data-ttu-id="1b43a-287">証明書のバージョン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-287">The version of the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-288">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-288">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-289">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-289">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-290">指定された証明書に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-290">Gets information about a specified certificate.</span></span> <span data-ttu-id="1b43a-291">認証:、証明書/取得アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-291">Authorization: requires the certificates/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificatesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetDeletedCertificatesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1b43a-292">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-292">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-293">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-293">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-294">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-294">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-295">現在回復に使用できる、指定したコンテナーに削除された証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-295">Lists the deleted certificates in the specified vault, currently available for recovery.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-296">GetDeletedCertificates 操作では、削除済み状態の回復または削除の準備完了である現在の資格情報コンテナーに証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-296">The GetDeletedCertificates operation retrieves the certificates in the current vault which are in a deleted state and ready for recovery or purging.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificatesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetDeletedCertificatesWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-297">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-297">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="1b43a-298">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="1b43a-298">Maximum number of results to return in a page.</span></span> <span data-ttu-id="1b43a-299">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="1b43a-299">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-300">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-300">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-301">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-301">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-302">現在回復に使用できる、指定したコンテナーに削除された証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-302">Lists the deleted certificates in the specified vault, currently available for recovery.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-303">GetDeletedCertificates 操作では、削除済み状態の回復または削除の準備完了である現在の資格情報コンテナーに証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-303">The GetDeletedCertificates operation retrieves the certificates in the current vault which are in a deleted state and ready for recovery or purging.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; GetDeletedCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; GetDeletedCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;" Usage="iKeyVaultClient.GetDeletedCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-304">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-304">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="1b43a-305">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="1b43a-305">The name of the certificate</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-306">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-306">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-307">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-307">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-308">指定された削除済み証明書に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-308">Retrieves information about the specified deleted certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-309">GetDeletedCertificate 操作は、削除された証明書の情報と保有期間、スケジュールされた永続的な削除、および現在の回復レベルでの削除など、その属性を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-309">The GetDeletedCertificate operation retrieves the deleted certificate information plus its attributes, such as retention interval, scheduled permanent deletion and the current deletion recovery level.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeysNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetDeletedKeysNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1b43a-310">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-310">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-311">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-311">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-312">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-312">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-313">指定した資格情報コンテナー内のキーをリストが削除されました。</span><span class="sxs-lookup"><span data-stu-id="1b43a-313">List deleted keys in the specified vault.</span></span> <span data-ttu-id="1b43a-314">認証:、キー/一覧表示権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-314">Authorization: Requires the keys/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetDeletedKeysWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-315">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-315">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="1b43a-316">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="1b43a-316">Maximum number of results to return in a page.</span></span> <span data-ttu-id="1b43a-317">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="1b43a-317">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-318">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-318">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-319">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-319">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-320">指定した資格情報コンテナー内のキーをリストが削除されました。</span><span class="sxs-lookup"><span data-stu-id="1b43a-320">List deleted keys in the specified vault.</span></span> <span data-ttu-id="1b43a-321">認証:、キー/一覧表示権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-321">Authorization: Requires the keys/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; GetDeletedKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; GetDeletedKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;" Usage="iKeyVaultClient.GetDeletedKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-322">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-322">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-323">キーの名前</span><span class="sxs-lookup"><span data-stu-id="1b43a-323">The name of the key</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-324">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-324">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-325">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-325">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-326">削除済みのキー情報とその属性を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-326">Retrieves the deleted key information plus its attributes.</span></span>
            <span data-ttu-id="1b43a-327">認証:、キー/取得アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-327">Authorization: Requires the keys/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetDeletedSecretsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1b43a-328">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-328">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-329">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-329">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-330">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-330">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-331">指定した資格情報コンテナーに削除された機密情報を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-331">List deleted secrets in the specified vault.</span></span> <span data-ttu-id="1b43a-332">認証:、シークレット/リスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-332">Authorization: requires the secrets/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetDeletedSecretsWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-333">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-333">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="1b43a-334">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="1b43a-334">Maximum number of results to return in a page.</span></span> <span data-ttu-id="1b43a-335">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="1b43a-335">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-336">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-336">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-337">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-337">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-338">指定した資格情報コンテナーに削除された機密情報を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-338">List deleted secrets in the specified vault.</span></span> <span data-ttu-id="1b43a-339">認証:、シークレット/リスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-339">Authorization: requires the secrets/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; GetDeletedSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; GetDeletedSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;" Usage="iKeyVaultClient.GetDeletedSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-340">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-340">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="1b43a-341">シークレットの名前</span><span class="sxs-lookup"><span data-stu-id="1b43a-341">The name of the secret</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-342">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-342">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-343">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-343">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-344">削除された秘密情報とその属性を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-344">Retrieves the deleted secret information plus its attributes.</span></span>
            <span data-ttu-id="1b43a-345">認証:、シークレット/取得アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-345">Authorization: requires the secrets/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetKeysNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1b43a-346">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-346">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-347">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-347">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-348">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-348">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-349">指定した資格情報コンテナー内のキーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-349">List keys in the specified vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-350">格納されたキーのパブリック部分を含む JSON Web Key 構造として、Key Vault 内のキーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-350">Retrieves a list of the keys in the Key Vault as JSON Web Key structures that contain the public part of a stored key.</span></span> <span data-ttu-id="1b43a-351">LIST 操作はすべてのキー型に適用される、ただしのみ、基本キー識別子、属性、およびタグが応答で提供します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-351">The LIST operation is applicable to all key types, however only the base key identifier,attributes, and tags are provided in the response.</span></span>
            <span data-ttu-id="1b43a-352">キーの個別のバージョンは、応答には表示されません。</span><span class="sxs-lookup"><span data-stu-id="1b43a-352">Individual versions of a key are not listed in the response.</span></span>
            <span data-ttu-id="1b43a-353">認証:、キー/一覧表示権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-353">Authorization: Requires the keys/list permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetKeysWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-354">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-354">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="1b43a-355">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="1b43a-355">Maximum number of results to return in a page.</span></span> <span data-ttu-id="1b43a-356">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="1b43a-356">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-357">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-357">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-358">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-358">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-359">指定した資格情報コンテナー内のキーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-359">List keys in the specified vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-360">格納されたキーのパブリック部分を含む JSON Web Key 構造として、Key Vault 内のキーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-360">Retrieves a list of the keys in the Key Vault as JSON Web Key structures that contain the public part of a stored key.</span></span> <span data-ttu-id="1b43a-361">LIST 操作はすべてのキー型に適用される、ただしのみ、基本キー識別子、属性、およびタグが応答で提供します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-361">The LIST operation is applicable to all key types, however only the base key identifier,attributes, and tags are provided in the response.</span></span>
            <span data-ttu-id="1b43a-362">キーの個別のバージョンは、応答には表示されません。</span><span class="sxs-lookup"><span data-stu-id="1b43a-362">Individual versions of a key are not listed in the response.</span></span>
            <span data-ttu-id="1b43a-363">認証:、キー/一覧表示権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-363">Authorization: Requires the keys/list permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVersionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeyVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetKeyVersionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1b43a-364">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-364">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-365">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-365">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-366">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-366">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-367">同じキー名で個別キー バージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-367">Retrieves a list of individual key versions with the same key name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-368">完全なキー識別子、属性、およびタグは、応答で提供されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-368">The full key identifier, attributes, and tags are provided in the response.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVersionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsWithHttpMessagesAsync (string vaultBaseUrl, string keyName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsWithHttpMessagesAsync(string vaultBaseUrl, string keyName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeyVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetKeyVersionsWithHttpMessagesAsync (vaultBaseUrl, keyName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-369">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-369">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-370">キー名。</span><span class="sxs-lookup"><span data-stu-id="1b43a-370">The name of the key.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="1b43a-371">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="1b43a-371">Maximum number of results to return in a page.</span></span> <span data-ttu-id="1b43a-372">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="1b43a-372">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-373">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-373">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-374">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-374">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-375">同じキー名で個別キー バージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-375">Retrieves a list of individual key versions with the same key name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-376">完全なキー識別子、属性、およびタグは、応答で提供されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-376">The full key identifier, attributes, and tags are provided in the response.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; GetKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; GetKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="iKeyVaultClient.GetKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-377">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-377">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-378">取得するキーの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-378">The name of the key to get.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="1b43a-379">バージョン パラメーターを追加するには、特定のバージョンのキーを取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-379">Adding the version parameter retrieves a specific version of a key.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-380">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-380">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-381">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-381">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-382">格納されているキーのパブリックの部分を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-382">Gets the public part of a stored key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-383">キーの取得操作は、すべてのキー タイプに適用できます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-383">The get key operation is applicable to all key types.</span></span> <span data-ttu-id="1b43a-384">要求されたキーが対称の場合は、し、キー マテリアルではリリースされません応答します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-384">If the requested key is symmetric, then no key material is released in the response.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPendingCertificateSigningRequestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt; GetPendingCertificateSigningRequestWithHttpMessagesAsync (string vault, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;string&gt;&gt; GetPendingCertificateSigningRequestWithHttpMessagesAsync(string vault, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetPendingCertificateSigningRequestWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPendingCertificateSigningRequestWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt;" Usage="iKeyVaultClient.GetPendingCertificateSigningRequestWithHttpMessagesAsync (vault, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vault" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vault">
            <span data-ttu-id="1b43a-385">資格情報コンテナー名、https://myvault.vault.azure.net 例:</span><span class="sxs-lookup"><span data-stu-id="1b43a-385">The vault name, e.g. https://myvault.vault.azure.net</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="1b43a-386">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="1b43a-386">The name of the certificate</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-387">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-387">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-388">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-388">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-389">証明書の操作の応答を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-389">Gets the certificate operation response.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSasDefinitionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSasDefinitionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetSasDefinitionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1b43a-390">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-390">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-391">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-391">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-392">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-392">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-393">特定のストレージ アカウントのストレージの SAS の定義を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-393">List storage SAS definitions for the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSasDefinitionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSasDefinitionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetSasDefinitionsWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-394">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-394">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1b43a-395">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-395">The name of the storage account.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="1b43a-396">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="1b43a-396">Maximum number of results to return in a page.</span></span> <span data-ttu-id="1b43a-397">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="1b43a-397">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-398">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-398">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-399">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-399">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-400">特定のストレージ アカウントのストレージの SAS の定義を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-400">List storage SAS definitions for the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; GetSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; GetSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="iKeyVaultClient.GetSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-401">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-401">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1b43a-402">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-402">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="1b43a-403">SAS の定義の名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-403">The name of the SAS definition.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-404">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-404">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-405">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-405">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-406">指定されたストレージ アカウントの SAS の定義に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-406">Gets information about a SAS definition for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetSecretsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1b43a-407">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-407">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-408">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-408">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-409">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-409">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-410">指定された key vault にシークレットの一覧表示</span><span class="sxs-lookup"><span data-stu-id="1b43a-410">List secrets in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-411">LIST 操作はただしコンテナー全体に適用可能な基本のシークレット識別子と属性のみが応答で提供します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-411">The LIST operation is applicable to the entire vault, however only the base secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="1b43a-412">個別のシークレット バージョンは、応答には表示されません。</span><span class="sxs-lookup"><span data-stu-id="1b43a-412">Individual secret versions are not listed in the response.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetSecretsWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-413">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-413">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="1b43a-414">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="1b43a-414">Maximum number of results to return in a page.</span></span> <span data-ttu-id="1b43a-415">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="1b43a-415">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-416">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-416">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-417">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-417">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-418">指定された key vault にシークレットの一覧表示</span><span class="sxs-lookup"><span data-stu-id="1b43a-418">List secrets in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-419">LIST 操作はただしコンテナー全体に適用可能な基本のシークレット識別子と属性のみが応答で提供します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-419">The LIST operation is applicable to the entire vault, however only the base secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="1b43a-420">個別のシークレット バージョンは、応答には表示されません。</span><span class="sxs-lookup"><span data-stu-id="1b43a-420">Individual secret versions are not listed in the response.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretVersionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetSecretVersionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1b43a-421">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-421">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-422">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-422">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-423">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-423">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-424">指定したシークレットのバージョンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-424">List the versions of the specified secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-425">LIST VERSIONS 操作は、同じ key vault で同じシークレット名を持つすべてのバージョンに適用できます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-425">The LIST VERSIONS operation can be applied to all versions having the same secret name in the same key vault.</span></span> <span data-ttu-id="1b43a-426">完全なシークレット識別子および属性は、応答で提供されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-426">The full secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="1b43a-427">シークレットの値が返されないと、現行バージョンのシークレットのみが一覧表示されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-427">No values are returned for the secrets and only current versions of a secret are listed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretVersionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsWithHttpMessagesAsync (string vaultBaseUrl, string secretName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsWithHttpMessagesAsync(string vaultBaseUrl, string secretName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetSecretVersionsWithHttpMessagesAsync (vaultBaseUrl, secretName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-428">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-428">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="1b43a-429">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-429">The name of the secret.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="1b43a-430">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="1b43a-430">Maximum number of results to return in a page.</span></span> <span data-ttu-id="1b43a-431">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="1b43a-431">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-432">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-432">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-433">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-433">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-434">指定したシークレットのバージョンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-434">List the versions of the specified secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-435">LIST VERSIONS 操作は、同じ key vault で同じシークレット名を持つすべてのバージョンに適用できます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-435">The LIST VERSIONS operation can be applied to all versions having the same secret name in the same key vault.</span></span> <span data-ttu-id="1b43a-436">完全なシークレット識別子および属性は、応答で提供されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-436">The full secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="1b43a-437">シークレットの値が返されないと、現行バージョンのシークレットのみが一覧表示されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-437">No values are returned for the secrets and only current versions of a secret are listed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; GetSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, string secretVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; GetSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, string secretVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="iKeyVaultClient.GetSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, secretVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="secretVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-438">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-438">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="1b43a-439">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-439">The name of the secret.</span></span>
            </param>
        <param name="secretVersion">
            <span data-ttu-id="1b43a-440">シークレットのバージョン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-440">The version of the secret.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-441">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-441">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-442">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-442">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-443">指定されたキー コンテナーから、指定されたシークレットを取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-443">Get a specified secret from a given key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-444">GET 操作は、Azure Key Vault に格納されているシークレットに適用します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-444">The GET operation is applicable to any secret stored in Azure Key Vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetStorageAccountsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageAccountsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetStorageAccountsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1b43a-445">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-445">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-446">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-446">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-447">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-447">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-448">指定した資格情報コンテナーで管理されているストレージ アカウントを一覧表示</span><span class="sxs-lookup"><span data-stu-id="1b43a-448">List storage accounts managed by specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetStorageAccountsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageAccountsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;" Usage="iKeyVaultClient.GetStorageAccountsWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-449">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-449">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="1b43a-450">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="1b43a-450">Maximum number of results to return in a page.</span></span> <span data-ttu-id="1b43a-451">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="1b43a-451">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-452">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-452">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-453">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-453">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-454">指定した資格情報コンテナーで管理されているストレージ アカウントを一覧表示</span><span class="sxs-lookup"><span data-stu-id="1b43a-454">List storage accounts managed by specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; GetStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; GetStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="iKeyVaultClient.GetStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-455">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-455">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1b43a-456">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-456">The name of the storage account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-457">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-457">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-458">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-458">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-459">指定されたストレージ アカウントの情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-459">Gets information about a specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; ImportCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, string base64EncodedCertificate, string password = null, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; ImportCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, string base64EncodedCertificate, string password, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.ImportCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportCertificateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="iKeyVaultClient.ImportCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, base64EncodedCertificate, password, certificatePolicy, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="base64EncodedCertificate" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-460">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-460">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="1b43a-461">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-461">The name of the certificate.</span></span>
            </param>
        <param name="base64EncodedCertificate">
            <span data-ttu-id="1b43a-462">インポートする証明書オブジェクトの表現を Base64 にエンコードされます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-462">Base64 encoded representation of the certificate object to import.</span></span>
            <span data-ttu-id="1b43a-463">この証明書を秘密キーを含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b43a-463">This certificate needs to contain the private key.</span></span>
            </param>
        <param name="password">
            <span data-ttu-id="1b43a-464">Base64EncodedCertificate 内の秘密キーが暗号化されている場合、パスワードは暗号化に使用します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-464">If the private key in base64EncodedCertificate is encrypted, the password used for encryption.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="1b43a-465">証明書の管理ポリシー。</span><span class="sxs-lookup"><span data-stu-id="1b43a-465">The management policy for the certificate.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="1b43a-466">(省略可能) の証明書の属性。</span><span class="sxs-lookup"><span data-stu-id="1b43a-466">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="1b43a-467">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="1b43a-467">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-468">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-468">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-469">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-469">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-470">指定したキー資格情報コンテナーに証明書をインポートします。</span><span class="sxs-lookup"><span data-stu-id="1b43a-470">Imports a certificate into a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-471">既存有効な証明書を Azure Key Vault には秘密キーを含むをインポートします。</span><span class="sxs-lookup"><span data-stu-id="1b43a-471">Imports an existing valid certificate, containing a private key, into Azure Key Vault.</span></span> <span data-ttu-id="1b43a-472">インポートする証明書は、PFX または PEM のいずれかの形式であることができます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-472">The certificate to be imported can be in either PFX or PEM format.</span></span> <span data-ttu-id="1b43a-473">キーだけでなく x509 PEM ファイルを含める必要があります PEM 形式での証明書がある場合の証明書。</span><span class="sxs-lookup"><span data-stu-id="1b43a-473">If the certificate is in PEM format the PEM file must contain the key as well as x509 certificates.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; ImportKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, Nullable&lt;bool&gt; hsm = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; ImportKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, valuetype System.Nullable`1&lt;bool&gt; hsm, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.ImportKeyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Nullable{System.Boolean},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportKeyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Nullable&lt;bool&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="iKeyVaultClient.ImportKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, key, hsm, keyAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="key" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="hsm" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-474">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-474">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-475">インポートしたキーの名前です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-475">Name for the imported key.</span></span>
            </param>
        <param name="key">
            <span data-ttu-id="1b43a-476">Json web key</span><span class="sxs-lookup"><span data-stu-id="1b43a-476">The Json web key</span></span>
            </param>
        <param name="hsm">
            <span data-ttu-id="1b43a-477">ハードウェア キー (HSM) またはソフトウェア キーとしてインポートするかどうか。</span><span class="sxs-lookup"><span data-stu-id="1b43a-477">Whether to import as a hardware key (HSM) or software key.</span></span>
            </param>
        <param name="keyAttributes">
            <span data-ttu-id="1b43a-478">キー管理の属性です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-478">The key management attributes.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="1b43a-479">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="1b43a-479">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-480">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-480">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-481">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-481">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-482">外部で作成されたキーをインポートする格納し、キー パラメーターを返し、属性をクライアントにします。</span><span class="sxs-lookup"><span data-stu-id="1b43a-482">Imports an externally created key, stores it, and returns key parameters and attributes to the client.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-483">インポート キー操作は、すべてのキー タイプを Azure Key Vault にインポートするために使用可能性があります。</span><span class="sxs-lookup"><span data-stu-id="1b43a-483">The import key operation may be used to import any key type into an Azure Key Vault.</span></span> <span data-ttu-id="1b43a-484">名前付きのキーが既に存在する場合、Azure Key Vault には、キーの新しいバージョンが作成されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-484">If the named key already exists, Azure Key Vault creates a new version of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.IKeyVaultClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.KeyVault.IKeyVaultClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b43a-485">取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-485">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="1b43a-486">既定値は 30 です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-486">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; MergeCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.IList&lt;byte[]&gt; x509Certificates, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; MergeCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.IList`1&lt;unsigned int8[]&gt; x509Certificates, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.MergeCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.Byte[]},Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MergeCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;byte[]&gt; * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="iKeyVaultClient.MergeCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, x509Certificates, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="x509Certificates" Type="System.Collections.Generic.IList&lt;System.Byte[]&gt;" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-487">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-487">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="1b43a-488">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-488">The name of the certificate.</span></span>
            </param>
        <param name="x509Certificates">
            <span data-ttu-id="1b43a-489">証明書または証明書チェーンをマージします。</span><span class="sxs-lookup"><span data-stu-id="1b43a-489">The certificate or the certificate chain to merge.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="1b43a-490">(省略可能) の証明書の属性。</span><span class="sxs-lookup"><span data-stu-id="1b43a-490">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="1b43a-491">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="1b43a-491">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-492">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-492">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-493">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-493">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-494">既存のサーバーでキーのペアで、証明書または証明書チェーンをマージします。</span><span class="sxs-lookup"><span data-stu-id="1b43a-494">Merges a certificate or a certificate chain with a key pair existing on the server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-495">MergeCertificate 操作では、証明書またはサービスで現在使用できるキーのペアで証明書チェーンのマージを実行します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-495">The MergeCertificate operation performs the merging of a certificate or certificate chain with a key pair currently available in the service.</span></span> <span data-ttu-id="1b43a-496">認証:、証明書/更新アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-496">Authorization: requires the certificates/update permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.PurgeDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iKeyVaultClient.PurgeDeletedCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-497">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-497">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="1b43a-498">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="1b43a-498">The name of the certificate</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-499">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-499">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-500">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-500">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-501">指定された削除済み証明書を完全に削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-501">Permanently deletes the specified deleted certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-502">PurgeDeletedCertificate 操作では、指定された証明書を回復する可能性の元に戻すことの削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-502">The PurgeDeletedCertificate operation performs an irreversible deletion of the specified certificate, without possibility for recovery.</span></span> <span data-ttu-id="1b43a-503">操作は回復レベルで 'Purgeable' が指定されていない場合に使用できません。</span><span class="sxs-lookup"><span data-stu-id="1b43a-503">The operation is not available if the recovery level does not specify 'Purgeable'.</span></span> <span data-ttu-id="1b43a-504">明示的な '削除' 権限を許可する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b43a-504">Requires the explicit granting of the 'purge' permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.PurgeDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iKeyVaultClient.PurgeDeletedKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-505">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-505">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-506">キーの名前</span><span class="sxs-lookup"><span data-stu-id="1b43a-506">The name of the key</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-507">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-507">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-508">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-508">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-509">指定したキーを完全に削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-509">Permanently deletes the specified key.</span></span> <span data-ttu-id="1b43a-510">別名、キーを削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-510">aka purges the key.</span></span>
            <span data-ttu-id="1b43a-511">認証:、キー/削除アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-511">Authorization: Requires the keys/purge permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.PurgeDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iKeyVaultClient.PurgeDeletedSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-512">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-512">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="1b43a-513">シークレットの名前</span><span class="sxs-lookup"><span data-stu-id="1b43a-513">The name of the secret</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-514">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-514">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-515">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-515">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-516">指定されたシークレットを完全に削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-516">Permanently deletes the specified secret.</span></span> <span data-ttu-id="1b43a-517">別名、シークレットを削除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-517">aka purges the secret.</span></span>
            <span data-ttu-id="1b43a-518">認証:、シークレット/削除アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-518">Authorization: requires the secrets/purge permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; RecoverDeletedCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; RecoverDeletedCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.RecoverDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RecoverDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="iKeyVaultClient.RecoverDeletedCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-519">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-519">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="1b43a-520">削除済みの証明書の名前</span><span class="sxs-lookup"><span data-stu-id="1b43a-520">The name of the deleted certificate</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-521">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-521">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-522">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-522">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-523">現在のバージョンに戻す、削除された証明書を回復します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-523">Recovers the deleted certificate back to its current version under /certificates.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-524">RecoverDeletedCertificate 操作では、削除操作の取り消しを実行します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-524">The RecoverDeletedCertificate operation performs the reversal of the Delete operation.</span></span> <span data-ttu-id="1b43a-525">操作は、ソフト削除の有効な資格情報コンテナーに適用し、間隔、保有期間 (削除済み証明書の属性で使用可能) 発行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b43a-525">The operation is applicable in vaults enabled for soft-delete, and must be issued during the retention interval (available in the deleted certificate's attributes).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RecoverDeletedKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RecoverDeletedKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.RecoverDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RecoverDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="iKeyVaultClient.RecoverDeletedKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-526">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-526">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-527">削除されたキーの名前</span><span class="sxs-lookup"><span data-stu-id="1b43a-527">The name of the deleted key</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-528">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-528">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-529">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-529">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-530">削除されたキーに戻します/keys 下にある現在のバージョンを回復します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-530">Recovers the deleted key back to its current version under /keys.</span></span>
            <span data-ttu-id="1b43a-531">認証:、キー/回復のアクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-531">Authorization: Requires the keys/recover permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RecoverDeletedSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RecoverDeletedSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.RecoverDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RecoverDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="iKeyVaultClient.RecoverDeletedSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-532">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-532">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="1b43a-533">削除されたシークレットの名前</span><span class="sxs-lookup"><span data-stu-id="1b43a-533">The name of the deleted secret</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-534">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-534">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-535">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-535">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-536">/Secrets 下にある現在のバージョンに削除されたシークレット バックアップを復元します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-536">Recovers the deleted secret back to its current version under /secrets.</span></span> <span data-ttu-id="1b43a-537">認証:、シークレット/回復のアクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-537">Authorization: requires the secrets/recover permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateStorageAccountKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; RegenerateStorageAccountKeyWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; RegenerateStorageAccountKeyWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.RegenerateStorageAccountKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateStorageAccountKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="iKeyVaultClient.RegenerateStorageAccountKeyWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-538">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-538">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1b43a-539">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-539">The name of the storage account.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-540">ストレージ アカウント キーの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-540">The storage account key name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-541">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-541">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-542">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-542">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-543">指定されたストレージ アカウントの指定したキー値を再生成します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-543">Regenerates the specified key value for the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RestoreKeyWithHttpMessagesAsync (string vaultBaseUrl, byte[] keyBundleBackup, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RestoreKeyWithHttpMessagesAsync(string vaultBaseUrl, unsigned int8[] keyBundleBackup, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.RestoreKeyWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreKeyWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="iKeyVaultClient.RestoreKeyWithHttpMessagesAsync (vaultBaseUrl, keyBundleBackup, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyBundleBackup" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-544">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-544">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyBundleBackup">
            <span data-ttu-id="1b43a-545">キーのバンドルに関連付けられているバックアップ blob です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-545">The backup blob associated with a key bundle.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-546">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-546">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-547">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-547">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-548">資格情報コンテナーにキーをバックアップを復元します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-548">Restores a backed up key to a vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-549">Azure Key Vault、キー、そのキー識別子、属性、およびアクセス制御ポリシーを復元するのには、以前にバックアップ キーをインポートします。</span><span class="sxs-lookup"><span data-stu-id="1b43a-549">Imports a previously backed up key into Azure Key Vault, restoring the key, its key identifier, attributes and access control policies.</span></span> <span data-ttu-id="1b43a-550">復元操作は、以前にバックアップ キーをインポートするために使用可能性があります。</span><span class="sxs-lookup"><span data-stu-id="1b43a-550">The RESTORE operation may be used to import a previously backed up key.</span></span> <span data-ttu-id="1b43a-551">キーの個別のバージョンを復元することはできません。</span><span class="sxs-lookup"><span data-stu-id="1b43a-551">Individual versions of a key cannot be restored.</span></span> <span data-ttu-id="1b43a-552">キーにはバックアップ時と同じキー名で全体として復元されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-552">The key is restored in its entirety with the same key name as it had when it was backed up.</span></span> <span data-ttu-id="1b43a-553">キー名をターゲット Key Vault では使用できない場合、復元操作は拒否されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-553">If the key name is not available in the target Key Vault, the RESTORE operation will be rejected.</span></span> <span data-ttu-id="1b43a-554">キー名は、復元中に保持されますが、中に、最終的なキー識別子は、別の資格情報コンテナーにキーを復元した場合に変更されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-554">While the key name is retained during restore, the final key identifier will change if the key is restored to a different vault.</span></span> <span data-ttu-id="1b43a-555">復元では、すべてのバージョンを復元し、バージョン識別子を保持します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-555">Restore will restore all versions and preserve version identifiers.</span></span> <span data-ttu-id="1b43a-556">復元操作のセキュリティの制約があります。 ターゲット Key Vault はソース Key Vault、ユーザーがターゲット Key Vault で復元権限を必要と同じ Microsoft Azure サブスクリプションで所有する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b43a-556">The RESTORE operation is subject to security constraints: The target Key Vault must be owned by the same Microsoft Azure Subscription as the source Key Vault The user must have RESTORE permission in the target Key Vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RestoreSecretWithHttpMessagesAsync (string vaultBaseUrl, byte[] secretBundleBackup, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RestoreSecretWithHttpMessagesAsync(string vaultBaseUrl, unsigned int8[] secretBundleBackup, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.RestoreSecretWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreSecretWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="iKeyVaultClient.RestoreSecretWithHttpMessagesAsync (vaultBaseUrl, secretBundleBackup, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretBundleBackup" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-557">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-557">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretBundleBackup">
            <span data-ttu-id="1b43a-558">シークレットのバンドルに関連付けられているバックアップ blob です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-558">The backup blob associated with a secret bundle.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-559">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-559">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-560">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-560">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-561">資格情報コンテナーにシークレットをバックアップを復元します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-561">Restores a backed up secret to a vault.</span></span> <span data-ttu-id="1b43a-562">認証:、シークレット/復元権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-562">Authorization: requires the secrets/restore permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.IKeyVaultClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.KeyVault.IKeyVaultClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1b43a-563">サービスのベース URI。</span><span class="sxs-lookup"><span data-stu-id="1b43a-563">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetCertificateContactsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; SetCertificateContactsWithHttpMessagesAsync (string vaultBaseUrl, Microsoft.Azure.KeyVault.Models.Contacts contacts, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; SetCertificateContactsWithHttpMessagesAsync(string vaultBaseUrl, class Microsoft.Azure.KeyVault.Models.Contacts contacts, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetCertificateContactsWithHttpMessagesAsync(System.String,Microsoft.Azure.KeyVault.Models.Contacts,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetCertificateContactsWithHttpMessagesAsync : string * Microsoft.Azure.KeyVault.Models.Contacts * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;" Usage="iKeyVaultClient.SetCertificateContactsWithHttpMessagesAsync (vaultBaseUrl, contacts, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="contacts" Type="Microsoft.Azure.KeyVault.Models.Contacts" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-564">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-564">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="contacts">
            <span data-ttu-id="1b43a-565">キー コンテナーの証明書の連絡先。</span><span class="sxs-lookup"><span data-stu-id="1b43a-565">The contacts for the key vault certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-566">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-566">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-567">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-567">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-568">指定したキー資格情報コンテナーの証明書の連絡先を設定します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-568">Sets the certificate contacts for the specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-569">指定したキー資格情報コンテナーの証明書の連絡先を設定します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-569">Sets the certificate contacts for the specified key vault.</span></span>
            <span data-ttu-id="1b43a-570">認証:、証明書/managecontacts 権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-570">Authorization: requires the certificates/managecontacts permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; SetCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, string provider, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; SetCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="iKeyVaultClient.SetCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, provider, credentials, organizationDetails, attributes, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-571">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-571">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="1b43a-572">発行者の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-572">The name of the issuer.</span></span>
            </param>
        <param name="provider">
            <span data-ttu-id="1b43a-573">発行元プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="1b43a-573">The issuer provider.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="1b43a-574">発行者のための資格情報。</span><span class="sxs-lookup"><span data-stu-id="1b43a-574">The credentials to be used for the issuer.</span></span>
            </param>
        <param name="organizationDetails">
            <span data-ttu-id="1b43a-575">発行元に提供される組織の詳細です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-575">Details of the organization as provided to the issuer.</span></span>
            </param>
        <param name="attributes">
            <span data-ttu-id="1b43a-576">発行元のオブジェクトの属性。</span><span class="sxs-lookup"><span data-stu-id="1b43a-576">Attributes of the issuer object.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-577">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-577">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-578">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-578">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-579">指定された証明書の発行者を設定します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-579">Sets the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-580">SetCertificateIssuer 操作を追加または指定された証明書の発行者を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-580">The SetCertificateIssuer operation adds or updates the specified certificate issuer.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; SetSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; SetSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="iKeyVaultClient.SetSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, parameters, sasDefinitionAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-581">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-581">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1b43a-582">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-582">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="1b43a-583">SAS の定義の名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-583">The name of the SAS definition.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1b43a-584">Sas 定義は、キー/値ペアの形式でのメタデータを作成します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-584">Sas definition creation metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="sasDefinitionAttributes">
            <span data-ttu-id="1b43a-585">SAS の定義の属性です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-585">The attributes of the SAS definition.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="1b43a-586">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="1b43a-586">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-587">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-587">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-588">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-588">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-589">作成するか、指定されたストレージ アカウントに対して新しい SAS 定義を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-589">Creates or updates a new SAS definition for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; SetSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, string value, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; SetSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, string value, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="iKeyVaultClient.SetSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, value, tags, contentType, secretAttributes, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-590">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-590">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="1b43a-591">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-591">The name of the secret.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="1b43a-592">シークレットの値です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-592">The value of the secret.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="1b43a-593">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="1b43a-593">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="contentType">
            <span data-ttu-id="1b43a-594">パスワードなどの秘密の値の型。</span><span class="sxs-lookup"><span data-stu-id="1b43a-594">Type of the secret value such as a password.</span></span>
            </param>
        <param name="secretAttributes">
            <span data-ttu-id="1b43a-595">シークレットの管理の属性です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-595">The secret management attributes.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-596">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-596">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-597">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-597">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-598">指定された key vault のシークレットを設定します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-598">Sets a secret in a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-599">設定操作では、Azure Key Vault にシークレットを追加します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-599">The SET operation adds a secret to the Azure Key Vault.</span></span> <span data-ttu-id="1b43a-600">名前付きのシークレットが既に存在する場合、Azure Key Vault はシークレットの新しいバージョンを作成します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-600">If the named secret already exists, Azure Key Vault creates a new version of that secret.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; SetStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; SetStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Boolean,System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStorageAccountWithHttpMessagesAsync : string * string * string * string * bool * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="iKeyVaultClient.SetStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, resourceId, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Boolean" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-601">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-601">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1b43a-602">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-602">The name of the storage account.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="1b43a-603">ストレージ アカウントのリソース id です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-603">Storage account resource id.</span></span>
            </param>
        <param name="activeKeyName">
            <span data-ttu-id="1b43a-604">現在アクティブなストレージ アカウント キーの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-604">Current active storage account key name.</span></span>
            </param>
        <param name="autoRegenerateKey">
            <span data-ttu-id="1b43a-605">かどうか keyvault はユーザー用のストレージ アカウントを管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b43a-605">whether keyvault should manage the storage account for the user.</span></span>
            </param>
        <param name="regenerationPeriod">
            <span data-ttu-id="1b43a-606">キーの生成 ISO 8601 形式で指定されている期間。</span><span class="sxs-lookup"><span data-stu-id="1b43a-606">The key regeneration time duration specified in ISO-8601 format.</span></span>
            </param>
        <param name="storageAccountAttributes">
            <span data-ttu-id="1b43a-607">ストレージ アカウントの属性。</span><span class="sxs-lookup"><span data-stu-id="1b43a-607">The attributes of the storage account.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="1b43a-608">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="1b43a-608">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-609">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-609">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-610">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-610">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-611">作成するか、新しいストレージ アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-611">Creates or updates a new storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; SignWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; SignWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.SignWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SignWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="iKeyVaultClient.SignWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-612">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-612">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-613">キー名。</span><span class="sxs-lookup"><span data-stu-id="1b43a-613">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="1b43a-614">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-614">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="1b43a-615">署名/検証アルゴリズムの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-615">The signing/verification algorithm identifier.</span></span> <span data-ttu-id="1b43a-616">可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1b43a-616">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span>
            <span data-ttu-id="1b43a-617">使用可能な値が含まれます: 'PS256'、'PS384'、'PS512'、'RS256'、'RS384'、'RS512'、'RSNULL'、'ES256'、'ES384'、'ES512'、'ECDSA256'</span><span class="sxs-lookup"><span data-stu-id="1b43a-617">Possible values include: 'PS256', 'PS384', 'PS512', 'RS256', 'RS384', 'RS512', 'RSNULL', 'ES256', 'ES384', 'ES512', 'ECDSA256'</span></span>
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-618">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-618">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-619">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-619">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-620">指定したキーを使用してダイジェストをから署名を作成します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-620">Creates a signature from a digest using the specified key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-621">サインイン操作は、非対称キーおよび対称キーをこの操作は、キーの秘密部分を使用するために、Azure Key Vault に格納されているに適用されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-621">The SIGN operation is applicable to asymmetric and symmetric keys stored in Azure Key Vault since this operation uses the private portion of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnwrapKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; UnwrapKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; UnwrapKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.UnwrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UnwrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="iKeyVaultClient.UnwrapKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-622">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-622">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-623">キー名。</span><span class="sxs-lookup"><span data-stu-id="1b43a-623">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="1b43a-624">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-624">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="1b43a-625">アルゴリズムの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-625">algorithm identifier.</span></span> <span data-ttu-id="1b43a-626">使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。</span><span class="sxs-lookup"><span data-stu-id="1b43a-626">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-627">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-627">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-628">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-628">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-629">そのキーをラップするために使用された最初に指定したキーを使用して対称キーのラップを解除します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-629">Unwraps a symmetric key using the specified key that was initially used for wrapping that key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-630">UNWRAP 操作は、対象キーの暗号化キーを使用して対称キーの復号化をサポートします。</span><span class="sxs-lookup"><span data-stu-id="1b43a-630">The UNWRAP operation supports decryption of a symmetric key using the target key encryption key.</span></span> <span data-ttu-id="1b43a-631">この操作は、WRAP 操作の逆です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-631">This operation is the reverse of the WRAP operation.</span></span> <span data-ttu-id="1b43a-632">UNWRAP 操作は、非対称キーおよび対称キー、キーの秘密部分を使用しているので、Azure Key Vault に格納されているに適用されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-632">The UNWRAP operation applies to asymmetric and symmetric keys stored in Azure Key Vault since it uses the private portion of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; UpdateCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, string provider = null, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; UpdateCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="iKeyVaultClient.UpdateCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, provider, credentials, organizationDetails, attributes, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-633">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-633">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="1b43a-634">発行者の名前です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-634">The name of the issuer.</span></span>
            </param>
        <param name="provider">
            <span data-ttu-id="1b43a-635">発行元プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="1b43a-635">The issuer provider.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="1b43a-636">発行者のための資格情報。</span><span class="sxs-lookup"><span data-stu-id="1b43a-636">The credentials to be used for the issuer.</span></span>
            </param>
        <param name="organizationDetails">
            <span data-ttu-id="1b43a-637">発行元に提供される組織の詳細です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-637">Details of the organization as provided to the issuer.</span></span>
            </param>
        <param name="attributes">
            <span data-ttu-id="1b43a-638">発行元のオブジェクトの属性。</span><span class="sxs-lookup"><span data-stu-id="1b43a-638">Attributes of the issuer object.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-639">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-639">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-640">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-640">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-641">指定された証明書の発行者を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-641">Updates the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-642">UpdateCertificateIssuer 操作は、指定された証明書発行者のエンティティの更新プログラムを実行します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-642">The UpdateCertificateIssuer operation performs an update on the specified certificate issuer entity.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; UpdateCertificateOperationWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, bool cancellationRequested, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; UpdateCertificateOperationWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, bool cancellationRequested, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Boolean,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificateOperationWithHttpMessagesAsync : string * string * bool * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="iKeyVaultClient.UpdateCertificateOperationWithHttpMessagesAsync (vaultBaseUrl, certificateName, cancellationRequested, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationRequested" Type="System.Boolean" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-643">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-643">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="1b43a-644">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-644">The name of the certificate.</span></span>
            </param>
        <param name="cancellationRequested">
            <span data-ttu-id="1b43a-645">証明書の操作のキャンセルが要求されたかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-645">Indicates if cancellation was requested on the certificate operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-646">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-646">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-647">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-647">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-648">証明書の操作を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-648">Updates a certificate operation.</span></span> <span data-ttu-id="1b43a-649">認証:、証明書/更新アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-649">Authorization: requires the certificates/update permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificatePolicyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; UpdateCertificatePolicyWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; UpdateCertificatePolicyWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificatePolicyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificatePolicyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;" Usage="iKeyVaultClient.UpdateCertificatePolicyWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificatePolicy, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-650">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-650">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="1b43a-651">指定された資格情報コンテナー内の証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-651">The name of the certificate in the given vault.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="1b43a-652">証明書のポリシーです。</span><span class="sxs-lookup"><span data-stu-id="1b43a-652">The policy for the certificate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-653">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-653">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-654">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-654">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-655">証明書のポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-655">Updates the policy for a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-656">証明書のポリシーで指定したメンバーを設定します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-656">Set specified members in the certificate policy.</span></span> <span data-ttu-id="1b43a-657">Null として他のユーザーのままにします。</span><span class="sxs-lookup"><span data-stu-id="1b43a-657">Leave others as null.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; UpdateCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, string certificateVersion, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; UpdateCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, string certificateVersion, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="iKeyVaultClient.UpdateCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificateVersion, certificatePolicy, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVersion" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-658">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-658">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="1b43a-659">指定されたキー コンテナーに証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-659">The name of the certificate in the given key vault.</span></span>
            </param>
        <param name="certificateVersion">
            <span data-ttu-id="1b43a-660">証明書のバージョン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-660">The version of the certificate.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="1b43a-661">証明書の管理ポリシー。</span><span class="sxs-lookup"><span data-stu-id="1b43a-661">The management policy for the certificate.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="1b43a-662">(省略可能) の証明書の属性。</span><span class="sxs-lookup"><span data-stu-id="1b43a-662">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="1b43a-663">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="1b43a-663">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-664">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-664">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-665">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-665">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-666">特定の証明書に関連付けられている指定された属性を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-666">Updates the specified attributes associated with the given certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-667">UpdateCertificate 操作は指定された証明書の指定した更新プログラムを適用します。要素だけが更新中は、証明書の属性に注意してください。</span><span class="sxs-lookup"><span data-stu-id="1b43a-667">The UpdateCertificate operation applies the specified update on the given certificate; note the only elements being updated are the certificate's attributes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; UpdateKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; UpdateKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="iKeyVaultClient.UpdateKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, keyOps, keyAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-668">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-668">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-669">更新するキーの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-669">The name of key to update.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="1b43a-670">更新するキーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-670">The version of the key to update.</span></span>
            </param>
        <param name="keyOps">
            <span data-ttu-id="1b43a-671">Json web キー操作。</span><span class="sxs-lookup"><span data-stu-id="1b43a-671">Json web key operations.</span></span> <span data-ttu-id="1b43a-672">考えられるキーの操作の詳細については、JsonWebKeyOperation を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1b43a-672">For more information on possible key operations, see JsonWebKeyOperation.</span></span>
            </param>
        <param name="keyAttributes"></param>
        <param name="tags">
            <span data-ttu-id="1b43a-673">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="1b43a-673">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-674">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-674">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-675">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-675">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-676">キー操作の変更の更新は、格納されたキーの属性を指定し、任意のキーの型と Azure Key Vault に格納されているキーのバージョンに適用できます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-676">The update key operation changes specified attributes of a stored key and can be applied to any key type and key version stored in Azure Key Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-677">この操作を実行するために Key Vault にキーが既に存在しています。</span><span class="sxs-lookup"><span data-stu-id="1b43a-677">In order to perform this operation, the key must already exist in the Key Vault.</span></span> <span data-ttu-id="1b43a-678">注: キー自体の暗号化マテリアルは変更できません。</span><span class="sxs-lookup"><span data-stu-id="1b43a-678">Note: The cryptographic material of a key itself cannot be changed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; UpdateSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters = null, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; UpdateSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="iKeyVaultClient.UpdateSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, parameters, sasDefinitionAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-679">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-679">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1b43a-680">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-680">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="1b43a-681">SAS の定義の名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-681">The name of the SAS definition.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1b43a-682">Sas の定義は、キー/値ペアの形式でメタデータを更新します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-682">Sas definition update metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="sasDefinitionAttributes">
            <span data-ttu-id="1b43a-683">SAS の定義の属性です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-683">The attributes of the SAS definition.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="1b43a-684">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="1b43a-684">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-685">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-685">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-686">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-686">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-687">特定の SAS 定義に関連付けられている指定された属性を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-687">Updates the specified attributes associated with the given SAS definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; UpdateSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, string secretVersion, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; UpdateSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, string secretVersion, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateSecretWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="iKeyVaultClient.UpdateSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, secretVersion, contentType, secretAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="secretVersion" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-688">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-688">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="1b43a-689">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-689">The name of the secret.</span></span>
            </param>
        <param name="secretVersion">
            <span data-ttu-id="1b43a-690">シークレットのバージョン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-690">The version of the secret.</span></span>
            </param>
        <param name="contentType">
            <span data-ttu-id="1b43a-691">パスワードなどの秘密の値の型。</span><span class="sxs-lookup"><span data-stu-id="1b43a-691">Type of the secret value such as a password.</span></span>
            </param>
        <param name="secretAttributes">
            <span data-ttu-id="1b43a-692">シークレットの管理の属性です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-692">The secret management attributes.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="1b43a-693">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="1b43a-693">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-694">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-694">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-695">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-695">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-696">指定されたキー コンテナーに指定されたシークレットを使用して関連付けられている属性を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-696">Updates the attributes associated with a specified secret in a given key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-697">更新操作は、既存の格納されているシークレットの指定された属性を変更します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-697">The UPDATE operation changes specified attributes of an existing stored secret.</span></span> <span data-ttu-id="1b43a-698">要求で指定されていない属性のまま変更されません。</span><span class="sxs-lookup"><span data-stu-id="1b43a-698">Attributes that are not specified in the request are left unchanged.</span></span> <span data-ttu-id="1b43a-699">シークレット自体の値は変更できません。</span><span class="sxs-lookup"><span data-stu-id="1b43a-699">The value of a secret itself cannot be changed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; UpdateStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string activeKeyName = null, Nullable&lt;bool&gt; autoRegenerateKey = null, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; UpdateStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string activeKeyName, valuetype System.Nullable`1&lt;bool&gt; autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateStorageAccountWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="iKeyVaultClient.UpdateStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-700">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-700">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="1b43a-701">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1b43a-701">The name of the storage account.</span></span>
            </param>
        <param name="activeKeyName">
            <span data-ttu-id="1b43a-702">現在アクティブなストレージ アカウント キー名。</span><span class="sxs-lookup"><span data-stu-id="1b43a-702">The current active storage account key name.</span></span>
            </param>
        <param name="autoRegenerateKey">
            <span data-ttu-id="1b43a-703">かどうか keyvault はユーザー用のストレージ アカウントを管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="1b43a-703">whether keyvault should manage the storage account for the user.</span></span>
            </param>
        <param name="regenerationPeriod">
            <span data-ttu-id="1b43a-704">キーの生成 ISO 8601 形式で指定されている期間。</span><span class="sxs-lookup"><span data-stu-id="1b43a-704">The key regeneration time duration specified in ISO-8601 format.</span></span>
            </param>
        <param name="storageAccountAttributes">
            <span data-ttu-id="1b43a-705">ストレージ アカウントの属性。</span><span class="sxs-lookup"><span data-stu-id="1b43a-705">The attributes of the storage account.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="1b43a-706">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="1b43a-706">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-707">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-707">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-708">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-708">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-709">特定のストレージ アカウントに関連付けられている指定された属性を更新します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-709">Updates the specified attributes associated with the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt; VerifyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] digest, byte[] signature, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt; VerifyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] digest, unsigned int8[] signature, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.VerifyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyWithHttpMessagesAsync : string * string * string * string * byte[] * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt;" Usage="iKeyVaultClient.VerifyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, digest, signature, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-710">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-710">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-711">キー名。</span><span class="sxs-lookup"><span data-stu-id="1b43a-711">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="1b43a-712">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-712">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="1b43a-713">署名/検証アルゴリズムです。</span><span class="sxs-lookup"><span data-stu-id="1b43a-713">The signing/verification algorithm.</span></span> <span data-ttu-id="1b43a-714">可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1b43a-714">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span>
            <span data-ttu-id="1b43a-715">使用可能な値が含まれます: 'PS256'、'PS384'、'PS512'、'RS256'、'RS384'、'RS512'、'RSNULL'、'ES256'、'ES384'、'ES512'、'ECDSA256'</span><span class="sxs-lookup"><span data-stu-id="1b43a-715">Possible values include: 'PS256', 'PS384', 'PS512', 'RS256', 'RS384', 'RS512', 'RSNULL', 'ES256', 'ES384', 'ES512', 'ECDSA256'</span></span>
            </param>
        <param name="digest">
            <span data-ttu-id="1b43a-716">ダイジェストの署名に使用します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-716">The digest used for signing.</span></span>
            </param>
        <param name="signature">
            <span data-ttu-id="1b43a-717">検証対象の署名。</span><span class="sxs-lookup"><span data-stu-id="1b43a-717">The signature to be verified.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-718">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-718">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-719">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-719">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-720">指定したキーを使用して署名を確認します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-720">Verifies a signature using a specified key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-721">検証処理は、Azure Key Vault に格納された対称キーを適用されます。</span><span class="sxs-lookup"><span data-stu-id="1b43a-721">The VERIFY operation is applicable to symmetric keys stored in Azure Key Vault.</span></span> <span data-ttu-id="1b43a-722">確認は不要な厳密にキーのパブリック部分を使用して署名の検証を実行できますが、この操作は、キー参照のみを持つ呼び出し元の便宜を図ってサポートので、Azure Key Vault に格納されている非対称キーのないと、キーのパブリックの部分です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-722">VERIFY is not strictly necessary for asymmetric keys stored in Azure Key Vault since signature verification can be performed using the public portion of the key but this operation is supported as a convenience for callers that only have a key-reference and not the public portion of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WrapKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; WrapKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; WrapKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.IKeyVaultClient.WrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member WrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="iKeyVaultClient.WrapKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            <span data-ttu-id="1b43a-723">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-723">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1b43a-724">キー名。</span><span class="sxs-lookup"><span data-stu-id="1b43a-724">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="1b43a-725">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-725">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="1b43a-726">アルゴリズムの識別子です。</span><span class="sxs-lookup"><span data-stu-id="1b43a-726">algorithm identifier.</span></span> <span data-ttu-id="1b43a-727">使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。</span><span class="sxs-lookup"><span data-stu-id="1b43a-727">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            <span data-ttu-id="1b43a-728">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1b43a-728">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1b43a-729">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1b43a-729">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1b43a-730">指定したキーを使用して対称キーをラップします。</span><span class="sxs-lookup"><span data-stu-id="1b43a-730">Wraps a symmetric key using a specified key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1b43a-731">WRAP 操作では、以前、Azure Key Vault に格納されているキーの暗号化キーを使用して対称キーの暗号化をサポートします。</span><span class="sxs-lookup"><span data-stu-id="1b43a-731">The WRAP operation supports encryption of a symmetric key using a key encryption key that has previously been stored in an Azure Key Vault.</span></span> <span data-ttu-id="1b43a-732">WRAP 操作は、キーの公開部分を使用して非対称キーで保護を実行できるので、Azure Key Vault に格納されている対称キーの厳密に必要だけです。</span><span class="sxs-lookup"><span data-stu-id="1b43a-732">The WRAP operation is only strictly necessary for symmetric keys stored in Azure Key Vault since protection with an asymmetric key can be performed using the public portion of the key.</span></span> <span data-ttu-id="1b43a-733">この操作は、キー参照であるが、パブリックのキー マテリアルにアクセスできない呼び出し元の便宜を図って非対称キーのサポートは。</span><span class="sxs-lookup"><span data-stu-id="1b43a-733">This operation is supported for asymmetric keys as a convenience for callers that have a key-reference but do not have access to the public key material.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>