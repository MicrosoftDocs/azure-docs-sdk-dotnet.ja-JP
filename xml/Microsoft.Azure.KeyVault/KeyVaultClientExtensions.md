<Type Name="KeyVaultClientExtensions" FullName="Microsoft.Azure.KeyVault.KeyVaultClientExtensions">
  <TypeSignature Language="C#" Value="public static class KeyVaultClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit KeyVaultClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.KeyVaultClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module KeyVaultClientExtensions" />
  <TypeSignature Language="F#" Value="type KeyVaultClientExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="726b2-101">KeyVaultClient の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="726b2-101">Extension methods for KeyVaultClient.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BackupKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt; BackupKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt; BackupKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.BackupKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BackupKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.BackupKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;BackupKeyAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-103">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-103">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-104">キー名。</span><span class="sxs-lookup"><span data-stu-id="726b2-104">The name of the key.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-106">指定したキーのバックアップをクライアントにダウンロードするように要求します。</span><span class="sxs-lookup"><span data-stu-id="726b2-106">Requests that a backup of the specified key be downloaded to the client.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-107">キーのバックアップ操作は、保護された形式で、Azure Key Vault からキーをエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="726b2-107">The Key Backup operation exports a key from Azure Key Vault in a protected form.</span></span> <span data-ttu-id="726b2-108">この操作では、Azure Key Vault システムの外部で使用できる形式では、キー マテリアルは返しません、返されるキー マテリアルは保護 Azure Key Vault HSM または Azure Key Vault 自体ことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-108">Note that this operation does NOT return key material in a form that can be used outside the Azure Key Vault system, the returned key material is either protected to a Azure Key Vault HSM or to Azure Key Vault itself.</span></span>
            <span data-ttu-id="726b2-109">この操作の目的は、キーのバックアップ、1 つの Azure Key Vault インスタンスでキーを生成し、別の Azure Key Vault インスタンスに復元してクライアントを許可するのにです。</span><span class="sxs-lookup"><span data-stu-id="726b2-109">The intent of this operation is to allow a client to GENERATE a key in one Azure Key Vault instance, BACKUP the key, and then RESTORE it into another Azure Key Vault instance.</span></span> <span data-ttu-id="726b2-110">バックアップ操作は、エクスポートする保護対象のフォームでは、Azure Key Vault からのすべてのキー タイプに使用可能性があります。</span><span class="sxs-lookup"><span data-stu-id="726b2-110">The BACKUP operation may be used to export, in protected form, any key type from Azure Key Vault.</span></span> <span data-ttu-id="726b2-111">キーの個別のバージョンは、バックアップすることはできません。</span><span class="sxs-lookup"><span data-stu-id="726b2-111">Individual versions of a key cannot be backed up.</span></span> <span data-ttu-id="726b2-112">バックアップ/復元は地理的な境界のみ; 内で実行できます別の地理的領域に 1 つの地理的領域からバックアップを復元できないことを意味します。</span><span class="sxs-lookup"><span data-stu-id="726b2-112">BACKUP / RESTORE can be performed within geographical boundaries only; meaning that a BACKUP from one geographical area cannot be restored to another geographical area.</span></span> <span data-ttu-id="726b2-113">たとえば、米国の地理的領域からのバックアップを EU の地理的領域に復元できません。</span><span class="sxs-lookup"><span data-stu-id="726b2-113">For example, a backup from the US geographical area cannot be restored in an EU geographical area.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt; BackupSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt; BackupSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.BackupSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BackupSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.BackupSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;BackupSecretAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-114">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-114">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-115">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-115">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="726b2-116">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-116">The name of the secret.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-118">指定したシークレットのバックアップをクライアントにダウンロードするように要求します。</span><span class="sxs-lookup"><span data-stu-id="726b2-118">Requests that a backup of the specified secret be downloaded to the client.</span></span>
            <span data-ttu-id="726b2-119">認証:、シークレット/バックアップ権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-119">Authorization: requires the secrets/backup permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; CreateCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; CreateCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateCertificateAsync (operations, vaultBaseUrl, certificateName, certificatePolicy, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;CreateCertificateAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-120">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-121">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-121">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="726b2-122">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-122">The name of the certificate.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="726b2-123">証明書の管理ポリシー。</span><span class="sxs-lookup"><span data-stu-id="726b2-123">The management policy for the certificate.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="726b2-124">(省略可能) の証明書の属性。</span><span class="sxs-lookup"><span data-stu-id="726b2-124">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="726b2-125">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="726b2-125">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-127">新しい証明書を作成します。</span><span class="sxs-lookup"><span data-stu-id="726b2-127">Creates a new certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-128">これが最初のバージョンである場合は、証明書リソースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-128">If this is the first version, the certificate resource is created.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; CreateKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, Microsoft.Azure.KeyVault.Models.NewKeyParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; CreateKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, class Microsoft.Azure.KeyVault.Models.NewKeyParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.Models.NewKeyParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.Models.NewKeyParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateKeyAsync (operations, vaultBaseUrl, keyName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;CreateKeyAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.KeyVault.Models.NewKeyParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl">To be added.</param>
        <param name="keyName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; CreateKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string kty, Nullable&lt;int&gt; keySize = null, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; CreateKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string kty, valuetype System.Nullable`1&lt;int32&gt; keySize, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateKeyAsync (operations, vaultBaseUrl, keyName, kty, keySize, keyOps, keyAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;CreateKeyAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="kty" Type="System.String" />
        <Parameter Name="keySize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-129">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-129">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-130">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-130">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-131">新しいキーの名前です。</span><span class="sxs-lookup"><span data-stu-id="726b2-131">The name for the new key.</span></span> <span data-ttu-id="726b2-132">システムでは、新しいキーのバージョン名を生成します。</span><span class="sxs-lookup"><span data-stu-id="726b2-132">The system will generate the version name for the new key.</span></span>
            </param>
        <param name="kty">
            <span data-ttu-id="726b2-133">作成するキーの型。</span><span class="sxs-lookup"><span data-stu-id="726b2-133">The type of key to create.</span></span> <span data-ttu-id="726b2-134">有効な値は、JsonWebKeyType を参照してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-134">For valid values, see JsonWebKeyType.</span></span> <span data-ttu-id="726b2-135">使用可能な値が含まれます: 'EC'、' EC HSM'、'RSA'、' RSA-HSM '、'oct'</span><span class="sxs-lookup"><span data-stu-id="726b2-135">Possible values include: 'EC', 'EC-HSM', 'RSA', 'RSA-HSM', 'oct'</span></span>
            </param>
        <param name="keySize">
            <span data-ttu-id="726b2-136">キーのサイズ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="726b2-136">The key size in bytes.</span></span> <span data-ttu-id="726b2-137">たとえば、1024 または 2048。</span><span class="sxs-lookup"><span data-stu-id="726b2-137">For example, 1024 or 2048.</span></span>
            </param>
        <param name="keyOps"></param>
        <param name="keyAttributes"></param>
        <param name="tags">
            <span data-ttu-id="726b2-138">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="726b2-138">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-140">新しいキーを作成、格納、キー パラメーターを返し、属性をクライアントにします。</span><span class="sxs-lookup"><span data-stu-id="726b2-140">Creates a new key, stores it, then returns key parameters and attributes to the client.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-141">キーの作成処理は、Azure Key Vault 内のすべてのキー タイプの作成に使用できます。</span><span class="sxs-lookup"><span data-stu-id="726b2-141">The create key operation can be used to create any key type in Azure Key Vault.</span></span> <span data-ttu-id="726b2-142">名前付きのキーが既に存在する場合、Azure Key Vault には、キーの新しいバージョンが作成されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-142">If the named key already exists, Azure Key Vault creates a new version of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; DecryptAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] cipherText, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; DecryptAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] cipherText, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DecryptAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DecryptAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DecryptAsync (operations, keyIdentifier, algorithm, cipherText, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DecryptAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="cipherText" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"><span data-ttu-id="726b2-143">完全なキー識別子</span><span class="sxs-lookup"><span data-stu-id="726b2-143">The full key identifier</span></span></param>
        <param name="algorithm"><span data-ttu-id="726b2-144">アルゴリズム。</span><span class="sxs-lookup"><span data-stu-id="726b2-144">The algorithm.</span></span> <span data-ttu-id="726b2-145">可能なアルゴリズムの種類の詳細については、JsonWebKeyEncryptionAlgorithm を参照してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-145">For more information on possible algorithm types, see JsonWebKeyEncryptionAlgorithm.</span></span></param>
        <param name="cipherText"><span data-ttu-id="726b2-146">暗号化テキスト</span><span class="sxs-lookup"><span data-stu-id="726b2-146">The cipher text</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-147">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-147">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-148">暗号化されたデータの 1 つのブロックを復号化します。</span><span class="sxs-lookup"><span data-stu-id="726b2-148">Decrypts a single block of encrypted data</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-149">復号化の結果</span><span class="sxs-lookup"><span data-stu-id="726b2-149">The decryption result</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; DecryptAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; DecryptAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DecryptAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DecryptAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DecryptAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DecryptAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-150">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-151">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-151">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-152">キー名。</span><span class="sxs-lookup"><span data-stu-id="726b2-152">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="726b2-153">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="726b2-153">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="726b2-154">アルゴリズムの識別子です。</span><span class="sxs-lookup"><span data-stu-id="726b2-154">algorithm identifier.</span></span> <span data-ttu-id="726b2-155">使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。</span><span class="sxs-lookup"><span data-stu-id="726b2-155">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-157">暗号化されたデータの 1 つのブロックを解除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-157">Decrypts a single block of encrypted data.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-158">DECRYPT 操作は、ターゲット暗号化キーと指定されたアルゴリズムを使用して暗号テキストの整形式ブロックを解除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-158">The DECRYPT operation decrypts a well-formed block of ciphertext using the target encryption key and specified algorithm.</span></span> <span data-ttu-id="726b2-159">この操作は、ENCRYPT 操作の逆だけでデータの 1 つのブロックは、暗号化が解除された可能性があります、このブロックのサイズは対象のキーと使用するアルゴリズムによって異なります。</span><span class="sxs-lookup"><span data-stu-id="726b2-159">This operation is the reverse of the ENCRYPT operation; only a single block of data may be decrypted, the size of this block is dependent on the target key and the algorithm to be used.</span></span> <span data-ttu-id="726b2-160">DECRYPT 操作は、非対称キーおよび対称キー、キーの秘密部分を使用しているので、Azure Key Vault に格納されているに適用されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-160">The DECRYPT operation applies to asymmetric and symmetric keys stored in Azure Key Vault since it uses the private portion of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt; DeleteCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt; DeleteCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteCertificateAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-161">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-162">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-162">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="726b2-163">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-163">The name of the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-165">指定したキー資格情報コンテナーから証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-165">Deletes a certificate from a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-166">関連付けられているポリシーと共に証明書オブジェクトのすべてのバージョンを削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-166">Deletes all versions of a certificate object along with its associated policy.</span></span> <span data-ttu-id="726b2-167">削除証明書オブジェクトの個々 のバージョンを削除する証明書を使用することはできません。</span><span class="sxs-lookup"><span data-stu-id="726b2-167">Delete certificate cannot be used to remove individual versions of a certificate object.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateContactsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt; DeleteCertificateContactsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt; DeleteCertificateContactsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateContactsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificateContactsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateContactsAsync (operations, vaultBaseUrl, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteCertificateContactsAsync&gt;d__62))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-168">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-169">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-169">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-171">指定されたキー コンテナーの証明書の連絡先を削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-171">Deletes the certificate contacts for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-172">指定した資格情報コンテナー証明書の証明書の連絡先を削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-172">Deletes the certificate contacts for a specified key vault certificate.</span></span>
            <span data-ttu-id="726b2-173">認証:、証明書/managecontacts 権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-173">Authorization: requires the certificates/managecontacts permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateIssuerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; DeleteCertificateIssuerAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; DeleteCertificateIssuerAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateIssuerAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificateIssuerAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateIssuerAsync (operations, vaultBaseUrl, issuerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteCertificateIssuerAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-174">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-174">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-175">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-175">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="726b2-176">発行者の名前です。</span><span class="sxs-lookup"><span data-stu-id="726b2-176">The name of the issuer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-178">指定された証明書の発行者を削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-178">Deletes the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-179">DeleteCertificateIssuer 操作は、資格情報コンテナーから、指定された証明書の発行者を完全に削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-179">The DeleteCertificateIssuer operation permanently removes the specified certificate issuer from the vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateOperationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; DeleteCertificateOperationAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; DeleteCertificateOperationAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateOperationAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificateOperationAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateOperationAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteCertificateOperationAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-180">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-180">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-181">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-181">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="726b2-182">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-182">The name of the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-183">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-184">指定された証明書の操作を削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-184">Deletes the operation for a specified certificate.</span></span> <span data-ttu-id="726b2-185">認証:、証明書/更新アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-185">Authorization: requires the certificates/update permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt; DeleteKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt; DeleteKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteKeyAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-186">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-187">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-187">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-188">削除するキーの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-188">The name of the key to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-189">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-190">Azure Key Vault に記憶域から任意の型のキーを削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-190">Deletes a key of any type from storage in Azure Key Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-191">キーの個別のバージョンを削除するキーの削除操作を使用できません。</span><span class="sxs-lookup"><span data-stu-id="726b2-191">The delete key operation cannot be used to remove individual versions of a key.</span></span> <span data-ttu-id="726b2-192">この操作は、キーが署名/検証、ラップ/ラップ解除または暗号化/暗号化解除操作に使用しないことを意味すると、キーに関連付けられている暗号化マテリアルを削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-192">This operation removes the cryptographic material associated with the key, which means the key is not usable for Sign/Verify, Wrap/Unwrap or Encrypt/Decrypt operations.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSasDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; DeleteSasDefinitionAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; DeleteSasDefinitionAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteSasDefinitionAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteSasDefinitionAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteSasDefinitionAsync (operations, vaultBaseUrl, storageAccountName, sasDefinitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteSasDefinitionAsync&gt;d__90))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-193">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-193">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-194">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-194">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="726b2-195">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-195">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="726b2-196">SAS の定義の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-196">The name of the SAS definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-197">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-198">指定されたストレージ アカウントから SAS 定義を削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-198">Deletes a SAS definition from a specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt; DeleteSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt; DeleteSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteSecretAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-199">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-199">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-200">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-200">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="726b2-201">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-201">The name of the secret.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-202">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-203">指定された key vault からシークレットを削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-203">Deletes a secret from a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-204">削除操作は、Azure Key Vault に格納されているシークレットに適用されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-204">The DELETE operation applies to any secret stored in Azure Key Vault.</span></span>
            <span data-ttu-id="726b2-205">削除は、個々 のバージョンのシークレットに適用できません。</span><span class="sxs-lookup"><span data-stu-id="726b2-205">DELETE cannot be applied to an individual version of a secret.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteStorageAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt; DeleteStorageAccountAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt; DeleteStorageAccountAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteStorageAccountAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteStorageAccountAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteStorageAccountAsync (operations, vaultBaseUrl, storageAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteStorageAccountAsync&gt;d__84))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-206">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-206">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-207">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-207">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="726b2-208">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-208">The name of the storage account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-209">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-210">ストレージ アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-210">Deletes a storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; EncryptAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] plainText, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; EncryptAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] plainText, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.EncryptAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EncryptAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.EncryptAsync (operations, keyIdentifier, algorithm, plainText, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;EncryptAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="plainText" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"><span data-ttu-id="726b2-211">完全なキー識別子</span><span class="sxs-lookup"><span data-stu-id="726b2-211">The full key identifier</span></span></param>
        <param name="algorithm"><span data-ttu-id="726b2-212">アルゴリズム。</span><span class="sxs-lookup"><span data-stu-id="726b2-212">The algorithm.</span></span> <span data-ttu-id="726b2-213">可能なアルゴリズムの種類の詳細については、JsonWebKeyEncryptionAlgorithm を参照してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-213">For more information on possible algorithm types, see JsonWebKeyEncryptionAlgorithm.</span></span></param>
        <param name="plainText"><span data-ttu-id="726b2-214">プレーン テキスト</span><span class="sxs-lookup"><span data-stu-id="726b2-214">The plain text</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-215">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-215">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-216">データの 1 つのブロックを暗号化します。</span><span class="sxs-lookup"><span data-stu-id="726b2-216">Encrypts a single block of data.</span></span> <span data-ttu-id="726b2-217">暗号化することがありますのあるデータの量は、対象キーの種類と暗号化アルゴリズムによって決まります。</span><span class="sxs-lookup"><span data-stu-id="726b2-217">The amount of data that may be encrypted is determined by the target key type and the encryption algorithm.</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-218">暗号化されたテキスト</span><span class="sxs-lookup"><span data-stu-id="726b2-218">The encrypted text</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; EncryptAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; EncryptAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.EncryptAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EncryptAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.EncryptAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;EncryptAsync&gt;d__36))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-219">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-219">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-220">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-220">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-221">キー名。</span><span class="sxs-lookup"><span data-stu-id="726b2-221">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="726b2-222">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="726b2-222">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="726b2-223">アルゴリズムの識別子です。</span><span class="sxs-lookup"><span data-stu-id="726b2-223">algorithm identifier.</span></span> <span data-ttu-id="726b2-224">使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。</span><span class="sxs-lookup"><span data-stu-id="726b2-224">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-225">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-226">Key vault に格納されている暗号化キーを使用してバイトの任意の順序を暗号化します。</span><span class="sxs-lookup"><span data-stu-id="726b2-226">Encrypts an arbitrary sequence of bytes using an encryption key that is stored in a key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-227">ENCRYPT 操作では、Azure Key Vault に格納されている暗号化キーを使用してバイトの任意の順序を暗号化します。</span><span class="sxs-lookup"><span data-stu-id="726b2-227">The ENCRYPT operation encrypts an arbitrary sequence of bytes using an encryption key that is stored in Azure Key Vault.</span></span> <span data-ttu-id="726b2-228">暗号化操作はサイズが、対象のキーと使用する暗号化アルゴリズムに依存して、データの 1 つのブロックのみをサポートする注意してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-228">Note that the ENCRYPT operation only supports a single block of data, the size of which is dependent on the target key and the encryption algorithm to be used.</span></span> <span data-ttu-id="726b2-229">暗号化操作は、キーの公開部分を使用して非対称キーで保護を実行できるので、Azure Key Vault に格納されている対称キーの厳密に必要だけです。</span><span class="sxs-lookup"><span data-stu-id="726b2-229">The ENCRYPT operation is only strictly necessary for symmetric keys stored in Azure Key Vault since protection with an asymmetric key can be performed using public portion of the key.</span></span> <span data-ttu-id="726b2-230">この操作は、キー参照であるが、パブリックのキー マテリアルにアクセスできない呼び出し元の便宜を図って非対称キーのサポートは。</span><span class="sxs-lookup"><span data-stu-id="726b2-230">This operation is supported for asymmetric keys as a convenience for callers that have a key-reference but do not have access to the public key material.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string certificateIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string certificateIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync (operations, certificateIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="certificateIdentifier" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="certificateIdentifier"><span data-ttu-id="726b2-231">証明書の URL です。</span><span class="sxs-lookup"><span data-stu-id="726b2-231">The URL for the certificate.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-232">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-232">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-233">証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-233">Gets a certificate.</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-234">取得した証明書</span><span class="sxs-lookup"><span data-stu-id="726b2-234">The retrieved certificate</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl"><span data-ttu-id="726b2-235">証明書を含む資格情報コンテナーの URL です。</span><span class="sxs-lookup"><span data-stu-id="726b2-235">The URL for the vault containing the certificate.</span></span></param>
        <param name="certificateName"><span data-ttu-id="726b2-236">指定された資格情報コンテナー内の証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-236">The name of the certificate in the given vault.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-237">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-237">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-238">証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-238">Gets a certificate.</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-239">取得した証明書</span><span class="sxs-lookup"><span data-stu-id="726b2-239">The retrieved certificate</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string certificateVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string certificateVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync (operations, vaultBaseUrl, certificateName, certificateVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateAsync&gt;d__74))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-240">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-240">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-241">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-241">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="726b2-242">指定された資格情報コンテナー内の証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-242">The name of the certificate in the given vault.</span></span>
            </param>
        <param name="certificateVersion">
            <span data-ttu-id="726b2-243">証明書のバージョン。</span><span class="sxs-lookup"><span data-stu-id="726b2-243">The version of the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-244">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-244">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-245">指定された証明書に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-245">Gets information about a specified certificate.</span></span> <span data-ttu-id="726b2-246">認証:、証明書/取得アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-246">Authorization: requires the certificates/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateContactsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt; GetCertificateContactsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt; GetCertificateContactsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateContactsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateContactsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateContactsAsync (operations, vaultBaseUrl, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateContactsAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-247">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-247">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-248">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-248">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-249">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-250">指定されたキー コンテナーの証明書の連絡先の一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="726b2-250">Lists the certificate contacts for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-251">GetCertificateContacts 操作は、指定されたキー コンテナーに証明書の連絡先のリソースのセットを返します。</span><span class="sxs-lookup"><span data-stu-id="726b2-251">The GetCertificateContacts operation returns the set of certificate contact resources in the specified key vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; GetCertificateIssuerAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; GetCertificateIssuerAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuerAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateIssuerAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuerAsync (operations, vaultBaseUrl, issuerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateIssuerAsync&gt;d__66))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-252">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-252">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-253">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-253">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="726b2-254">発行者の名前です。</span><span class="sxs-lookup"><span data-stu-id="726b2-254">The name of the issuer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-255">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-256">指定された証明書の発行者の一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="726b2-256">Lists the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-257">GetCertificateIssuer 操作は、指定されたキー コンテナーに指定された証明書発行者リソースを返します</span><span class="sxs-lookup"><span data-stu-id="726b2-257">The GetCertificateIssuer operation returns the specified certificate issuer resources in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt; GetCertificateIssuersAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt; GetCertificateIssuersAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuersAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateIssuersAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuersAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateIssuersAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-258">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-258">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-259">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-259">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="726b2-260">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="726b2-260">Maximum number of results to return in a page.</span></span> <span data-ttu-id="726b2-261">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="726b2-261">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-262">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-262">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-263">指定されたキー コンテナーの証明書の発行者をリストします。</span><span class="sxs-lookup"><span data-stu-id="726b2-263">List certificate issuers for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-264">GetCertificateIssuers 操作は、指定されたキー コンテナーに証明書発行者のリソースのセットを返します</span><span class="sxs-lookup"><span data-stu-id="726b2-264">The GetCertificateIssuers operation returns the set of certificate issuer resources in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuersNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt; GetCertificateIssuersNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt; GetCertificateIssuersNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuersNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateIssuersNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuersNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateIssuersNextAsync&gt;d__101))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-265">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-265">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="726b2-266">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="726b2-266">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-267">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-267">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-268">指定されたキー コンテナーの証明書の発行者をリストします。</span><span class="sxs-lookup"><span data-stu-id="726b2-268">List certificate issuers for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-269">GetCertificateIssuers 操作は、指定されたキー コンテナーに証明書発行者のリソースのセットを返します</span><span class="sxs-lookup"><span data-stu-id="726b2-269">The GetCertificateIssuers operation returns the set of certificate issuer resources in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateOperationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; GetCertificateOperationAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; GetCertificateOperationAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateOperationAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateOperationAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateOperationAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateOperationAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-270">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-270">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-271">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-271">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="726b2-272">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-272">The name of the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-273">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-273">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-274">指定された証明書に関連付けられている操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-274">Gets the operation associated with a specified certificate.</span></span> <span data-ttu-id="726b2-275">認証:、証明書/取得アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-275">Authorization: requires the certificates/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatePolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt; GetCertificatePolicyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt; GetCertificatePolicyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatePolicyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificatePolicyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatePolicyAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificatePolicyAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-276">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-276">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-277">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-277">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="726b2-278">指定されたキー コンテナーに証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-278">The name of the certificate in a given key vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-279">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-279">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-280">証明書のポリシーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="726b2-280">Lists the policy for a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-281">GetCertificatePolicy 操作は、指定されたキー コンテナーに指定された証明書ポリシー リソースを返します</span><span class="sxs-lookup"><span data-stu-id="726b2-281">The GetCertificatePolicy operation returns the specified certificate policy resources in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificatesAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificatesAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatesAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificatesAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatesAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificatesAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-282">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-282">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-283">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-283">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="726b2-284">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="726b2-284">Maximum number of results to return in a page.</span></span> <span data-ttu-id="726b2-285">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="726b2-285">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-286">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-286">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-287">指定されたキー コンテナーに証明書の一覧</span><span class="sxs-lookup"><span data-stu-id="726b2-287">List certificates in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-288">GetCertificates 操作は、指定されたキー コンテナーに証明書のリソースのセットを返します。</span><span class="sxs-lookup"><span data-stu-id="726b2-288">The GetCertificates operation returns the set of certificates resources in the specified key vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificatesNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificatesNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatesNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificatesNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificatesNextAsync&gt;d__100))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-289">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-289">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="726b2-290">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="726b2-290">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-291">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-291">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-292">指定されたキー コンテナーに証明書の一覧</span><span class="sxs-lookup"><span data-stu-id="726b2-292">List certificates in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-293">GetCertificates 操作は、指定されたキー コンテナーに証明書のリソースのセットを返します。</span><span class="sxs-lookup"><span data-stu-id="726b2-293">The GetCertificates operation returns the set of certificates resources in the specified key vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateVersionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificateVersionsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificateVersionsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateVersionsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateVersionsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateVersionsAsync (operations, vaultBaseUrl, certificateName, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateVersionsAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-294">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-294">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-295">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-295">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="726b2-296">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-296">The name of the certificate.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="726b2-297">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="726b2-297">Maximum number of results to return in a page.</span></span> <span data-ttu-id="726b2-298">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="726b2-298">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-299">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-299">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-300">証明書のバージョンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="726b2-300">List the versions of a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-301">GetCertificateVersions 操作は、指定されたキー コンテナーに証明書のバージョンを返します</span><span class="sxs-lookup"><span data-stu-id="726b2-301">The GetCertificateVersions operation returns the versions of a certificate in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateVersionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificateVersionsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificateVersionsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateVersionsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateVersionsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateVersionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateVersionsNextAsync&gt;d__102))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-302">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-302">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="726b2-303">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="726b2-303">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-304">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-304">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-305">証明書のバージョンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="726b2-305">List the versions of a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-306">GetCertificateVersions 操作は、指定されたキー コンテナーに証明書のバージョンを返します</span><span class="sxs-lookup"><span data-stu-id="726b2-306">The GetCertificateVersions operation returns the versions of a certificate in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt; GetDeletedCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt; GetDeletedCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificateAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedCertificateAsync&gt;d__80))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-307">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-307">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-308">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-308">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="726b2-309">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="726b2-309">The name of the certificate</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-310">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-310">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-311">指定された削除済み証明書に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-311">Retrieves information about the specified deleted certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-312">GetDeletedCertificate 操作は、削除された証明書の情報と保有期間、スケジュールされた永続的な削除、および現在の回復レベルでの削除など、その属性を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-312">The GetDeletedCertificate operation retrieves the deleted certificate information plus its attributes, such as retention interval, scheduled permanent deletion and the current deletion recovery level.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt; GetDeletedCertificatesAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt; GetDeletedCertificatesAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificatesAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedCertificatesAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificatesAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedCertificatesAsync&gt;d__79))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-313">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-313">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-314">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-314">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="726b2-315">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="726b2-315">Maximum number of results to return in a page.</span></span> <span data-ttu-id="726b2-316">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="726b2-316">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-317">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-317">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-318">現在回復に使用できる、指定したコンテナーに削除された証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="726b2-318">Lists the deleted certificates in the specified vault, currently available for recovery.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-319">GetDeletedCertificates 操作では、削除済み状態の回復または削除の準備完了である現在の資格情報コンテナーに証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-319">The GetDeletedCertificates operation retrieves the certificates in the current vault which are in a deleted state and ready for recovery or purging.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificatesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt; GetDeletedCertificatesNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt; GetDeletedCertificatesNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificatesNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedCertificatesNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificatesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedCertificatesNextAsync&gt;d__103))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-320">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-320">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="726b2-321">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="726b2-321">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-322">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-322">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-323">現在回復に使用できる、指定したコンテナーに削除された証明書を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="726b2-323">Lists the deleted certificates in the specified vault, currently available for recovery.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-324">GetDeletedCertificates 操作では、削除済み状態の回復または削除の準備完了である現在の資格情報コンテナーに証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-324">The GetDeletedCertificates operation retrieves the certificates in the current vault which are in a deleted state and ready for recovery or purging.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt; GetDeletedKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt; GetDeletedKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedKeyAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-325">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-325">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-326">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-326">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-327">キーの名前</span><span class="sxs-lookup"><span data-stu-id="726b2-327">The name of the key</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-328">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-328">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-329">削除済みのキー情報とその属性を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-329">Retrieves the deleted key information plus its attributes.</span></span> <span data-ttu-id="726b2-330">認証:、キー/取得アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-330">Authorization: Requires the keys/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt; GetDeletedKeysAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt; GetDeletedKeysAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeysAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedKeysAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeysAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedKeysAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-331">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-331">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-332">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-332">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="726b2-333">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="726b2-333">Maximum number of results to return in a page.</span></span> <span data-ttu-id="726b2-334">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="726b2-334">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-335">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-335">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-336">指定した資格情報コンテナー内のキーをリストが削除されました。</span><span class="sxs-lookup"><span data-stu-id="726b2-336">List deleted keys in the specified vault.</span></span> <span data-ttu-id="726b2-337">認証:、キー/一覧表示権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-337">Authorization: Requires the keys/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeysNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt; GetDeletedKeysNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt; GetDeletedKeysNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeysNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedKeysNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeysNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedKeysNextAsync&gt;d__96))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-338">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-338">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="726b2-339">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="726b2-339">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-340">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-340">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-341">指定した資格情報コンテナー内のキーをリストが削除されました。</span><span class="sxs-lookup"><span data-stu-id="726b2-341">List deleted keys in the specified vault.</span></span> <span data-ttu-id="726b2-342">認証:、キー/一覧表示権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-342">Authorization: Requires the keys/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt; GetDeletedSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt; GetDeletedSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedSecretAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-343">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-343">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-344">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-344">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="726b2-345">シークレットの名前</span><span class="sxs-lookup"><span data-stu-id="726b2-345">The name of the secret</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-346">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-346">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-347">削除された秘密情報とその属性を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-347">Retrieves the deleted secret information plus its attributes.</span></span>
            <span data-ttu-id="726b2-348">認証:、シークレット/取得アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-348">Authorization: requires the secrets/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt; GetDeletedSecretsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt; GetDeletedSecretsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedSecretsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretsAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedSecretsAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-349">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-349">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-350">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-350">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="726b2-351">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="726b2-351">Maximum number of results to return in a page.</span></span> <span data-ttu-id="726b2-352">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="726b2-352">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-353">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-353">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-354">指定した資格情報コンテナーに削除された機密情報を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="726b2-354">List deleted secrets in the specified vault.</span></span> <span data-ttu-id="726b2-355">認証:、シークレット/リスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-355">Authorization: requires the secrets/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt; GetDeletedSecretsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt; GetDeletedSecretsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedSecretsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedSecretsNextAsync&gt;d__99))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-356">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-356">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="726b2-357">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="726b2-357">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-358">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-358">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-359">指定した資格情報コンテナーに削除された機密情報を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="726b2-359">List deleted secrets in the specified vault.</span></span> <span data-ttu-id="726b2-360">認証:、シークレット/リスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-360">Authorization: requires the secrets/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync (operations, keyIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeyAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"><span data-ttu-id="726b2-361">キー識別子</span><span class="sxs-lookup"><span data-stu-id="726b2-361">The key identifier</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-362">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-362">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-363">キーとその属性の公開部分を取得します</span><span class="sxs-lookup"><span data-stu-id="726b2-363">Retrieves the public portion of a key plus its attributes</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-364">キーとその属性の KeyBundle</span><span class="sxs-lookup"><span data-stu-id="726b2-364">A KeyBundle of the key and its attributes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeyAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl"><span data-ttu-id="726b2-365">資格情報コンテナー名、https://myvault.vault.azure.net 例:</span><span class="sxs-lookup"><span data-stu-id="726b2-365">The vault name, e.g. https://myvault.vault.azure.net</span></span></param>
        <param name="keyName"><span data-ttu-id="726b2-366">キー名</span><span class="sxs-lookup"><span data-stu-id="726b2-366">The key name</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-367">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-367">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-368">キーとその属性の公開部分を取得します</span><span class="sxs-lookup"><span data-stu-id="726b2-368">Retrieves the public portion of a key plus its attributes</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-369">キーとその属性の KeyBundle</span><span class="sxs-lookup"><span data-stu-id="726b2-369">A KeyBundle of the key and its attributes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync (operations, vaultBaseUrl, keyName, keyVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeyAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-370">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-370">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-371">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-371">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-372">取得するキーの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-372">The name of the key to get.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="726b2-373">バージョン パラメーターを追加するには、特定のバージョンのキーを取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-373">Adding the version parameter retrieves a specific version of a key.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-374">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-374">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-375">格納されているキーのパブリックの部分を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-375">Gets the public part of a stored key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-376">キーの取得操作は、すべてのキー タイプに適用できます。</span><span class="sxs-lookup"><span data-stu-id="726b2-376">The get key operation is applicable to all key types.</span></span> <span data-ttu-id="726b2-377">要求されたキーが対称の場合は、し、キー マテリアルではリリースされません応答します。</span><span class="sxs-lookup"><span data-stu-id="726b2-377">If the requested key is symmetric, then no key material is released in the response.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeysAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeysAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeysAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeysAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeysAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeysAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-378">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-378">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-379">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-379">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="726b2-380">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="726b2-380">Maximum number of results to return in a page.</span></span> <span data-ttu-id="726b2-381">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="726b2-381">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-382">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-382">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-383">指定した資格情報コンテナー内のキーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="726b2-383">List keys in the specified vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-384">格納されたキーのパブリック部分を含む JSON Web Key 構造として、Key Vault 内のキーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-384">Retrieves a list of the keys in the Key Vault as JSON Web Key structures that contain the public part of a stored key.</span></span> <span data-ttu-id="726b2-385">LIST 操作はすべてのキー型に適用される、ただしのみ、基本キー識別子、属性、およびタグが応答で提供します。</span><span class="sxs-lookup"><span data-stu-id="726b2-385">The LIST operation is applicable to all key types, however only the base key identifier,attributes, and tags are provided in the response.</span></span> <span data-ttu-id="726b2-386">キーの個別のバージョンは、応答には表示されません。</span><span class="sxs-lookup"><span data-stu-id="726b2-386">Individual versions of a key are not listed in the response.</span></span> <span data-ttu-id="726b2-387">認証:、キー/一覧表示権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-387">Authorization: Requires the keys/list permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeysNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeysNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeysNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeysNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeysNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeysNextAsync&gt;d__95))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-388">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-388">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="726b2-389">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="726b2-389">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-390">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-390">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-391">指定した資格情報コンテナー内のキーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="726b2-391">List keys in the specified vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-392">格納されたキーのパブリック部分を含む JSON Web Key 構造として、Key Vault 内のキーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-392">Retrieves a list of the keys in the Key Vault as JSON Web Key structures that contain the public part of a stored key.</span></span> <span data-ttu-id="726b2-393">LIST 操作はすべてのキー型に適用される、ただしのみ、基本キー識別子、属性、およびタグが応答で提供します。</span><span class="sxs-lookup"><span data-stu-id="726b2-393">The LIST operation is applicable to all key types, however only the base key identifier,attributes, and tags are provided in the response.</span></span> <span data-ttu-id="726b2-394">キーの個別のバージョンは、応答には表示されません。</span><span class="sxs-lookup"><span data-stu-id="726b2-394">Individual versions of a key are not listed in the response.</span></span> <span data-ttu-id="726b2-395">認証:、キー/一覧表示権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-395">Authorization: Requires the keys/list permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVersionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeyVersionsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeyVersionsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyVersionsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeyVersionsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyVersionsAsync (operations, vaultBaseUrl, keyName, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeyVersionsAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-396">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-396">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-397">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-397">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-398">キー名。</span><span class="sxs-lookup"><span data-stu-id="726b2-398">The name of the key.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="726b2-399">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="726b2-399">Maximum number of results to return in a page.</span></span> <span data-ttu-id="726b2-400">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="726b2-400">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-401">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-401">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-402">同じキー名で個別キー バージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-402">Retrieves a list of individual key versions with the same key name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-403">完全なキー識別子、属性、およびタグは、応答で提供されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-403">The full key identifier, attributes, and tags are provided in the response.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVersionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeyVersionsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeyVersionsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyVersionsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeyVersionsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyVersionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeyVersionsNextAsync&gt;d__94))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-404">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-404">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="726b2-405">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="726b2-405">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-406">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-406">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-407">同じキー名で個別キー バージョンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-407">Retrieves a list of individual key versions with the same key name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-408">完全なキー識別子、属性、およびタグは、応答で提供されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-408">The full key identifier, attributes, and tags are provided in the response.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPendingCertificateSigningRequestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GetPendingCertificateSigningRequestAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GetPendingCertificateSigningRequestAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetPendingCertificateSigningRequestAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPendingCertificateSigningRequestAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetPendingCertificateSigningRequestAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetPendingCertificateSigningRequestAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl"><span data-ttu-id="726b2-409">証明書を含む資格情報コンテナーの URL</span><span class="sxs-lookup"><span data-stu-id="726b2-409">The URL for the vault containing the certificate</span></span></param>
        <param name="certificateName"><span data-ttu-id="726b2-410">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="726b2-410">The name of the certificate</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-411">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-411">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-412">保留中の証明書署名要求 (10 PKCS)、Base64 を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-412">Gets the Base64 pending certificate signing request (PKCS-10)</span></span> 
            </summary>
        <returns><span data-ttu-id="726b2-413">保留中の証明書署名要求を Base64 としてエンコードされた文字列。</span><span class="sxs-lookup"><span data-stu-id="726b2-413">The pending certificate signing request as Base64 encoded string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; GetSasDefinitionAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; GetSasDefinitionAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSasDefinitionAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionAsync (operations, vaultBaseUrl, storageAccountName, sasDefinitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSasDefinitionAsync&gt;d__91))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-414">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-414">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-415">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-415">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="726b2-416">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-416">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="726b2-417">SAS の定義の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-417">The name of the SAS definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-418">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-418">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-419">指定されたストレージ アカウントの SAS の定義に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-419">Gets information about a SAS definition for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt; GetSasDefinitionsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt; GetSasDefinitionsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSasDefinitionsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionsAsync (operations, vaultBaseUrl, storageAccountName, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSasDefinitionsAsync&gt;d__89))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-420">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-420">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-421">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-421">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="726b2-422">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-422">The name of the storage account.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="726b2-423">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="726b2-423">Maximum number of results to return in a page.</span></span> <span data-ttu-id="726b2-424">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="726b2-424">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-425">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-425">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-426">特定のストレージ アカウントのストレージの SAS の定義を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="726b2-426">List storage SAS definitions for the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt; GetSasDefinitionsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt; GetSasDefinitionsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSasDefinitionsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSasDefinitionsNextAsync&gt;d__105))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-427">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-427">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="726b2-428">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="726b2-428">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-429">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-429">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-430">特定のストレージ アカウントのストレージの SAS の定義を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="726b2-430">List storage SAS definitions for the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string secretIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string secretIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync (operations, secretIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="secretIdentifier" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="secretIdentifier"><span data-ttu-id="726b2-431">シークレットの URL です。</span><span class="sxs-lookup"><span data-stu-id="726b2-431">The URL for the secret.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-432">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-432">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-433">シークレットを取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-433">Gets a secret.</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-434">シークレットを含む応答メッセージ</span><span class="sxs-lookup"><span data-stu-id="726b2-434">A response message containing the secret</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl"><span data-ttu-id="726b2-435">シークレットを含む資格情報コンテナーの URL です。</span><span class="sxs-lookup"><span data-stu-id="726b2-435">The URL for the vault containing the secrets.</span></span></param>
        <param name="secretName"><span data-ttu-id="726b2-436">指定された資格情報コンテナーに機密情報の名前です。</span><span class="sxs-lookup"><span data-stu-id="726b2-436">The name the secret in the given vault.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-437">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-437">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-438">シークレットを取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-438">Gets a secret.</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-439">シークレットを含む応答メッセージ</span><span class="sxs-lookup"><span data-stu-id="726b2-439">A response message containing the secret</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string secretVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string secretVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync (operations, vaultBaseUrl, secretName, secretVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="secretVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-440">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-440">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-441">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-441">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="726b2-442">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-442">The name of the secret.</span></span>
            </param>
        <param name="secretVersion">
            <span data-ttu-id="726b2-443">シークレットのバージョン。</span><span class="sxs-lookup"><span data-stu-id="726b2-443">The version of the secret.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-444">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-444">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-445">指定されたキー コンテナーから、指定されたシークレットを取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-445">Get a specified secret from a given key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-446">GET 操作は、Azure Key Vault に格納されているシークレットに適用します。</span><span class="sxs-lookup"><span data-stu-id="726b2-446">The GET operation is applicable to any secret stored in Azure Key Vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretsAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretsAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-447">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-447">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-448">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-448">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="726b2-449">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="726b2-449">Maximum number of results to return in a page.</span></span> <span data-ttu-id="726b2-450">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="726b2-450">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-451">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-451">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-452">指定された key vault にシークレットの一覧表示</span><span class="sxs-lookup"><span data-stu-id="726b2-452">List secrets in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-453">LIST 操作はただしコンテナー全体に適用可能な基本のシークレット識別子と属性のみが応答で提供します。</span><span class="sxs-lookup"><span data-stu-id="726b2-453">The LIST operation is applicable to the entire vault, however only the base secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="726b2-454">個別のシークレット バージョンは、応答には表示されません。</span><span class="sxs-lookup"><span data-stu-id="726b2-454">Individual secret versions are not listed in the response.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretsNextAsync&gt;d__97))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-455">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-455">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="726b2-456">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="726b2-456">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-457">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-457">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-458">指定された key vault にシークレットの一覧表示</span><span class="sxs-lookup"><span data-stu-id="726b2-458">List secrets in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-459">LIST 操作はただしコンテナー全体に適用可能な基本のシークレット識別子と属性のみが応答で提供します。</span><span class="sxs-lookup"><span data-stu-id="726b2-459">The LIST operation is applicable to the entire vault, however only the base secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="726b2-460">個別のシークレット バージョンは、応答には表示されません。</span><span class="sxs-lookup"><span data-stu-id="726b2-460">Individual secret versions are not listed in the response.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretVersionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretVersionsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretVersionsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretVersionsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretVersionsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretVersionsAsync (operations, vaultBaseUrl, secretName, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretVersionsAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-461">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-461">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-462">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-462">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="726b2-463">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-463">The name of the secret.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="726b2-464">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="726b2-464">Maximum number of results to return in a page.</span></span> <span data-ttu-id="726b2-465">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="726b2-465">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-466">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-466">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-467">指定したシークレットのバージョンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="726b2-467">List the versions of the specified secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-468">LIST VERSIONS 操作は、同じ key vault で同じシークレット名を持つすべてのバージョンに適用できます。</span><span class="sxs-lookup"><span data-stu-id="726b2-468">The LIST VERSIONS operation can be applied to all versions having the same secret name in the same key vault.</span></span> <span data-ttu-id="726b2-469">完全なシークレット識別子および属性は、応答で提供されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-469">The full secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="726b2-470">シークレットの値が返されないと、現行バージョンのシークレットのみが一覧表示されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-470">No values are returned for the secrets and only current versions of a secret are listed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretVersionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretVersionsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretVersionsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretVersionsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretVersionsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretVersionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretVersionsNextAsync&gt;d__98))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-471">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-471">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="726b2-472">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="726b2-472">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-473">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-473">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-474">指定したシークレットのバージョンを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="726b2-474">List the versions of the specified secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-475">LIST VERSIONS 操作は、同じ key vault で同じシークレット名を持つすべてのバージョンに適用できます。</span><span class="sxs-lookup"><span data-stu-id="726b2-475">The LIST VERSIONS operation can be applied to all versions having the same secret name in the same key vault.</span></span> <span data-ttu-id="726b2-476">完全なシークレット識別子および属性は、応答で提供されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-476">The full secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="726b2-477">シークレットの値が返されないと、現行バージョンのシークレットのみが一覧表示されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-477">No values are returned for the secrets and only current versions of a secret are listed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt; GetStorageAccountAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt; GetStorageAccountAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStorageAccountAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountAsync (operations, vaultBaseUrl, storageAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetStorageAccountAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-478">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-478">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-479">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-479">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="726b2-480">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-480">The name of the storage account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-481">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-481">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-482">指定されたストレージ アカウントの情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="726b2-482">Gets information about a specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt; GetStorageAccountsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt; GetStorageAccountsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStorageAccountsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountsAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetStorageAccountsAsync&gt;d__83))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-483">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-483">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-484">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-484">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="726b2-485">ページに返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="726b2-485">Maximum number of results to return in a page.</span></span> <span data-ttu-id="726b2-486">サービスは最大 25 件の結果を返すが指定されていない場合。</span><span class="sxs-lookup"><span data-stu-id="726b2-486">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-487">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-487">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-488">指定した資格情報コンテナーで管理されているストレージ アカウントを一覧表示</span><span class="sxs-lookup"><span data-stu-id="726b2-488">List storage accounts managed by specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt; GetStorageAccountsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt; GetStorageAccountsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStorageAccountsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetStorageAccountsNextAsync&gt;d__104))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-489">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-489">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="726b2-490">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="726b2-490">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-491">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-491">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-492">指定した資格情報コンテナーで管理されているストレージ アカウントを一覧表示</span><span class="sxs-lookup"><span data-stu-id="726b2-492">List storage accounts managed by specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; ImportCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Security.Cryptography.X509Certificates.X509Certificate2Collection certificateCollection, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; ImportCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, class System.Security.Cryptography.X509Certificates.X509Certificate2Collection certificateCollection, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Security.Cryptography.X509Certificates.X509Certificate2Collection,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Security.Cryptography.X509Certificates.X509Certificate2Collection * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportCertificateAsync (operations, vaultBaseUrl, certificateName, certificateCollection, certificatePolicy, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;ImportCertificateAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateCollection" Type="System.Security.Cryptography.X509Certificates.X509Certificate2Collection" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl"><span data-ttu-id="726b2-493">証明書を含む資格情報コンテナーの URL</span><span class="sxs-lookup"><span data-stu-id="726b2-493">The URL for the vault containing the certificate</span></span></param>
        <param name="certificateName"><span data-ttu-id="726b2-494">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="726b2-494">The name of the certificate</span></span></param>
        <param name="certificateCollection"><span data-ttu-id="726b2-495">秘密キーで証明書のコレクション</span><span class="sxs-lookup"><span data-stu-id="726b2-495">The certificate collection with the private key</span></span></param>
        <param name="certificatePolicy"><span data-ttu-id="726b2-496">証明書の管理ポリシー</span><span class="sxs-lookup"><span data-stu-id="726b2-496">The management policy for the certificate</span></span></param>
        <param name="certificateAttributes"><span data-ttu-id="726b2-497">(省略可能) の証明書の属性</span><span class="sxs-lookup"><span data-stu-id="726b2-497">The attributes of the certificate (optional)</span></span></param>
        <param name="tags"><span data-ttu-id="726b2-498">キー/値ペアの形式でのアプリケーション固有のメタデータ</span><span class="sxs-lookup"><span data-stu-id="726b2-498">Application-specific metadata in the form of key-value pairs</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-499">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-499">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-500">証明書の新しいバージョンをインポートします。</span><span class="sxs-lookup"><span data-stu-id="726b2-500">Imports a new certificate version.</span></span> <span data-ttu-id="726b2-501">これが最初のバージョンである場合は、証明書リソースが作成されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-501">If this is the first version, the certificate resource is created.</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-502">資格情報コンテナーに証明書のバンドルをインポートします。</span><span class="sxs-lookup"><span data-stu-id="726b2-502">Imported certificate bundle to the vault.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; ImportCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string base64EncodedCertificate, string password = null, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; ImportCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string base64EncodedCertificate, string password, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportCertificateAsync (operations, vaultBaseUrl, certificateName, base64EncodedCertificate, password, certificatePolicy, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;ImportCertificateAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="base64EncodedCertificate" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-503">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-503">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-504">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-504">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="726b2-505">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-505">The name of the certificate.</span></span>
            </param>
        <param name="base64EncodedCertificate">
            <span data-ttu-id="726b2-506">インポートする証明書オブジェクトの表現を Base64 にエンコードされます。</span><span class="sxs-lookup"><span data-stu-id="726b2-506">Base64 encoded representation of the certificate object to import.</span></span> <span data-ttu-id="726b2-507">この証明書を秘密キーを含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="726b2-507">This certificate needs to contain the private key.</span></span>
            </param>
        <param name="password">
            <span data-ttu-id="726b2-508">Base64EncodedCertificate 内の秘密キーが暗号化されている場合、パスワードは暗号化に使用します。</span><span class="sxs-lookup"><span data-stu-id="726b2-508">If the private key in base64EncodedCertificate is encrypted, the password used for encryption.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="726b2-509">証明書の管理ポリシー。</span><span class="sxs-lookup"><span data-stu-id="726b2-509">The management policy for the certificate.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="726b2-510">(省略可能) の証明書の属性。</span><span class="sxs-lookup"><span data-stu-id="726b2-510">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="726b2-511">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="726b2-511">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-512">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-512">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-513">指定したキー資格情報コンテナーに証明書をインポートします。</span><span class="sxs-lookup"><span data-stu-id="726b2-513">Imports a certificate into a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-514">既存有効な証明書を Azure Key Vault には秘密キーを含むをインポートします。</span><span class="sxs-lookup"><span data-stu-id="726b2-514">Imports an existing valid certificate, containing a private key, into Azure Key Vault.</span></span> <span data-ttu-id="726b2-515">インポートする証明書は、PFX または PEM のいずれかの形式であることができます。</span><span class="sxs-lookup"><span data-stu-id="726b2-515">The certificate to be imported can be in either PFX or PEM format.</span></span> <span data-ttu-id="726b2-516">キーだけでなく x509 PEM ファイルを含める必要があります PEM 形式での証明書がある場合の証明書。</span><span class="sxs-lookup"><span data-stu-id="726b2-516">If the certificate is in PEM format the PEM file must contain the key as well as x509 certificates.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; ImportKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, Microsoft.Azure.KeyVault.Models.KeyBundle keyBundle, Nullable&lt;bool&gt; importToHardware = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; ImportKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, class Microsoft.Azure.KeyVault.Models.KeyBundle keyBundle, valuetype System.Nullable`1&lt;bool&gt; importToHardware, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.Models.KeyBundle,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.Models.KeyBundle * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportKeyAsync (operations, vaultBaseUrl, keyName, keyBundle, importToHardware, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;ImportKeyAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyBundle" Type="Microsoft.Azure.KeyVault.Models.KeyBundle" />
        <Parameter Name="importToHardware" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl"><span data-ttu-id="726b2-517">資格情報コンテナー名、https://myvault.vault.azure.net 例:</span><span class="sxs-lookup"><span data-stu-id="726b2-517">The vault name, e.g. https://myvault.vault.azure.net</span></span></param>
        <param name="keyName"><span data-ttu-id="726b2-518">キー名</span><span class="sxs-lookup"><span data-stu-id="726b2-518">The key name</span></span></param>
        <param name="keyBundle"> <span data-ttu-id="726b2-519">キーのバンドル</span><span class="sxs-lookup"><span data-stu-id="726b2-519">Key bundle</span></span> </param>
        <param name="importToHardware"><span data-ttu-id="726b2-520">ハードウェア キー (HSM) またはソフトウェア キーとしてインポートするかどうか</span><span class="sxs-lookup"><span data-stu-id="726b2-520">Whether to import as a hardware key (HSM) or software key</span></span> </param>
        <param name="cancellationToken"><span data-ttu-id="726b2-521">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-521">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-522">指定した資格情報コンテナーにキーをインポートします。</span><span class="sxs-lookup"><span data-stu-id="726b2-522">Imports a key into the specified vault</span></span>
            </summary>
        <returns> <span data-ttu-id="726b2-523">資格情報コンテナーにキーのバンドルをインポート</span><span class="sxs-lookup"><span data-stu-id="726b2-523">Imported key bundle to the vault</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; ImportKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, Nullable&lt;bool&gt; hsm = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; ImportKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, class Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, valuetype System.Nullable`1&lt;bool&gt; hsm, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Nullable{System.Boolean},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Nullable&lt;bool&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportKeyAsync (operations, vaultBaseUrl, keyName, key, hsm, keyAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;ImportKeyAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="key" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="hsm" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-524">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-524">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-525">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-525">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-526">インポートしたキーの名前です。</span><span class="sxs-lookup"><span data-stu-id="726b2-526">Name for the imported key.</span></span>
            </param>
        <param name="key">
            <span data-ttu-id="726b2-527">Json web key</span><span class="sxs-lookup"><span data-stu-id="726b2-527">The Json web key</span></span>
            </param>
        <param name="hsm">
            <span data-ttu-id="726b2-528">ハードウェア キー (HSM) またはソフトウェア キーとしてインポートするかどうか。</span><span class="sxs-lookup"><span data-stu-id="726b2-528">Whether to import as a hardware key (HSM) or software key.</span></span>
            </param>
        <param name="keyAttributes">
            <span data-ttu-id="726b2-529">キー管理の属性です。</span><span class="sxs-lookup"><span data-stu-id="726b2-529">The key management attributes.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="726b2-530">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="726b2-530">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-531">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-531">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-532">外部で作成されたキーをインポートする格納し、キー パラメーターを返し、属性をクライアントにします。</span><span class="sxs-lookup"><span data-stu-id="726b2-532">Imports an externally created key, stores it, and returns key parameters and attributes to the client.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-533">インポート キー操作は、すべてのキー タイプを Azure Key Vault にインポートするために使用可能性があります。</span><span class="sxs-lookup"><span data-stu-id="726b2-533">The import key operation may be used to import any key type into an Azure Key Vault.</span></span> <span data-ttu-id="726b2-534">名前付きのキーが既に存在する場合、Azure Key Vault には、キーの新しいバージョンが作成されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-534">If the named key already exists, Azure Key Vault creates a new version of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; MergeCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Collections.Generic.IList&lt;byte[]&gt; x509Certificates, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; MergeCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, class System.Collections.Generic.IList`1&lt;unsigned int8[]&gt; x509Certificates, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.MergeCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Collections.Generic.IList{System.Byte[]},Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MergeCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Collections.Generic.IList&lt;byte[]&gt; * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.MergeCertificateAsync (operations, vaultBaseUrl, certificateName, x509Certificates, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;MergeCertificateAsync&gt;d__78))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="x509Certificates" Type="System.Collections.Generic.IList&lt;System.Byte[]&gt;" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-535">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-535">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-536">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-536">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="726b2-537">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-537">The name of the certificate.</span></span>
            </param>
        <param name="x509Certificates">
            <span data-ttu-id="726b2-538">証明書または証明書チェーンをマージします。</span><span class="sxs-lookup"><span data-stu-id="726b2-538">The certificate or the certificate chain to merge.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="726b2-539">(省略可能) の証明書の属性。</span><span class="sxs-lookup"><span data-stu-id="726b2-539">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="726b2-540">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="726b2-540">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-541">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-541">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-542">既存のサーバーでキーのペアで、証明書または証明書チェーンをマージします。</span><span class="sxs-lookup"><span data-stu-id="726b2-542">Merges a certificate or a certificate chain with a key pair existing on the server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-543">MergeCertificate 操作では、証明書またはサービスで現在使用できるキーのペアで証明書チェーンのマージを実行します。</span><span class="sxs-lookup"><span data-stu-id="726b2-543">The MergeCertificate operation performs the merging of a certificate or certificate chain with a key pair currently available in the service.</span></span>
            <span data-ttu-id="726b2-544">認証:、証明書/更新アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-544">Authorization: requires the certificates/update permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; MergeCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Security.Cryptography.X509Certificates.X509Certificate2Collection x509Certificates, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; MergeCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, class System.Security.Cryptography.X509Certificates.X509Certificate2Collection x509Certificates, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.MergeCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Security.Cryptography.X509Certificates.X509Certificate2Collection,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MergeCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Security.Cryptography.X509Certificates.X509Certificate2Collection * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.MergeCertificateAsync (operations, vaultBaseUrl, certificateName, x509Certificates, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;MergeCertificateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="x509Certificates" Type="System.Security.Cryptography.X509Certificates.X509Certificate2Collection" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl"><span data-ttu-id="726b2-545">証明書を含む資格情報コンテナーの URL</span><span class="sxs-lookup"><span data-stu-id="726b2-545">The URL for the vault containing the certificate</span></span></param>
        <param name="certificateName"><span data-ttu-id="726b2-546">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="726b2-546">The name of the certificate</span></span></param>
        <param name="x509Certificates"><span data-ttu-id="726b2-547">証明書またはマージする certificte チェーン</span><span class="sxs-lookup"><span data-stu-id="726b2-547">The certificate or the certificte chain to merge</span></span></param>
        <param name="certificateAttributes"><span data-ttu-id="726b2-548">(省略可能) の証明書の属性</span><span class="sxs-lookup"><span data-stu-id="726b2-548">The attributes of the certificate (optional)</span></span></param>
        <param name="tags"><span data-ttu-id="726b2-549">キー/値ペアの形式でのアプリケーション固有のメタデータ</span><span class="sxs-lookup"><span data-stu-id="726b2-549">Application-specific metadata in the form of key-value pairs</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-550">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-550">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-551">既存のサーバーでキーのペアで、証明書または証明書チェーンをマージします。</span><span class="sxs-lookup"><span data-stu-id="726b2-551">Merges a certificate or a certificate chain with a key pair existing on the server.</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-552">マージされた証明書を含む応答メッセージです。</span><span class="sxs-lookup"><span data-stu-id="726b2-552">A response message containing the merged certificate.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedCertificateAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedCertificateAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId"><span data-ttu-id="726b2-553">削除から返された、削除された証明書の recoveryId します。</span><span class="sxs-lookup"><span data-stu-id="726b2-553">The recoveryId of the deleted certificate, returned from deletion.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-554">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-554">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-555">すぐに削除された証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-555">Purges the deleted certificate with immediate effect.</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-556">この要求の非同期実行を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="726b2-556">Task representing the asynchronous execution of this request.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedCertificateAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedCertificateAsync&gt;d__81))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-557">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-557">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-558">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-558">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="726b2-559">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="726b2-559">The name of the certificate</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-560">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-560">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-561">指定された削除済み証明書を完全に削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-561">Permanently deletes the specified deleted certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-562">PurgeDeletedCertificate 操作では、指定された証明書を回復する可能性の元に戻すことの削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="726b2-562">The PurgeDeletedCertificate operation performs an irreversible deletion of the specified certificate, without possibility for recovery.</span></span> <span data-ttu-id="726b2-563">操作は回復レベルで 'Purgeable' が指定されていない場合に使用できません。</span><span class="sxs-lookup"><span data-stu-id="726b2-563">The operation is not available if the recovery level does not specify 'Purgeable'.</span></span>
            <span data-ttu-id="726b2-564">明示的な '削除' 権限を許可する必要があります。</span><span class="sxs-lookup"><span data-stu-id="726b2-564">Requires the explicit granting of the 'purge' permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedKeyAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedKeyAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId"><span data-ttu-id="726b2-565">削除から削除された、キーの recoveryId が返されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-565">The recoveryId of the deleted key, returned from deletion.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-566">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-566">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-567">すぐに削除されたキーを削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-567">Purges the deleted key immediately.</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-568">この要求の非同期実行を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="726b2-568">Task representing the asynchronous execution of this request.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedKeyAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-569">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-569">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-570">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-570">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-571">キーの名前</span><span class="sxs-lookup"><span data-stu-id="726b2-571">The name of the key</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-572">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-572">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-573">指定したキーを完全に削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-573">Permanently deletes the specified key.</span></span> <span data-ttu-id="726b2-574">別名、キーを削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-574">aka purges the key.</span></span> <span data-ttu-id="726b2-575">認証:、キー/削除アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-575">Authorization: Requires the keys/purge permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedSecretAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedSecretAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId"><span data-ttu-id="726b2-576">削除されないように、削除されたシークレットの recoveryId が返されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-576">The recoveryId of the deleted secret, returned from deletion.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-577">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-577">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-578">すぐに削除されたシークレットを削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-578">Purges the deleted secret immediately.</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-579">この要求の非同期実行を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="726b2-579">Task representing the asynchronous execution of this request.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedSecretAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-580">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-580">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-581">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-581">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="726b2-582">シークレットの名前</span><span class="sxs-lookup"><span data-stu-id="726b2-582">The name of the secret</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-583">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-583">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-584">指定されたシークレットを完全に削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-584">Permanently deletes the specified secret.</span></span> <span data-ttu-id="726b2-585">別名、シークレットを削除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-585">aka purges the secret.</span></span>
            <span data-ttu-id="726b2-586">認証:、シークレット/削除アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-586">Authorization: requires the secrets/purge permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; RecoverDeletedCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; RecoverDeletedCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedCertificateAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedCertificateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId"><span data-ttu-id="726b2-587">削除から返された、削除された証明書の recoveryId します。</span><span class="sxs-lookup"><span data-stu-id="726b2-587">The recoveryId of the deleted certificate, returned from deletion.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-588">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-588">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-589">削除済みの証明書を回復します。</span><span class="sxs-lookup"><span data-stu-id="726b2-589">Recovers the deleted certificate.</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-590">回復された証明書を格納した応答メッセージ</span><span class="sxs-lookup"><span data-stu-id="726b2-590">A response message containing the recovered certificate</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; RecoverDeletedCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; RecoverDeletedCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedCertificateAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedCertificateAsync&gt;d__82))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-591">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-591">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-592">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-592">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="726b2-593">削除済みの証明書の名前</span><span class="sxs-lookup"><span data-stu-id="726b2-593">The name of the deleted certificate</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-594">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-594">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-595">現在のバージョンに戻す、削除された証明書を回復します。</span><span class="sxs-lookup"><span data-stu-id="726b2-595">Recovers the deleted certificate back to its current version under /certificates.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-596">RecoverDeletedCertificate 操作では、削除操作の取り消しを実行します。</span><span class="sxs-lookup"><span data-stu-id="726b2-596">The RecoverDeletedCertificate operation performs the reversal of the Delete operation.</span></span> <span data-ttu-id="726b2-597">操作は、ソフト削除の有効な資格情報コンテナーに適用し、間隔、保有期間 (削除済み証明書の属性で使用可能) 発行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="726b2-597">The operation is applicable in vaults enabled for soft-delete, and must be issued during the retention interval (available in the deleted certificate's attributes).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RecoverDeletedKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RecoverDeletedKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedKeyAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedKeyAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId"><span data-ttu-id="726b2-598">削除から削除された、キーの recoveryId が返されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-598">The recoveryId of the deleted key, returned from deletion.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-599">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-599">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-600">削除されたキーを回復します。</span><span class="sxs-lookup"><span data-stu-id="726b2-600">Recovers the deleted key.</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-601">回復キーを含む応答メッセージ</span><span class="sxs-lookup"><span data-stu-id="726b2-601">A response message containing the recovered key</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RecoverDeletedKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RecoverDeletedKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedKeyAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-602">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-602">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-603">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-603">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-604">削除されたキーの名前</span><span class="sxs-lookup"><span data-stu-id="726b2-604">The name of the deleted key</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-605">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-605">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-606">削除されたキーに戻します/keys 下にある現在のバージョンを回復します。</span><span class="sxs-lookup"><span data-stu-id="726b2-606">Recovers the deleted key back to its current version under /keys.</span></span>
            <span data-ttu-id="726b2-607">認証:、キー/回復のアクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-607">Authorization: Requires the keys/recover permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RecoverDeletedSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RecoverDeletedSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedSecretAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedSecretAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId"><span data-ttu-id="726b2-608">削除されないように、削除されたシークレットの recoveryId が返されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-608">The recoveryId of the deleted secret, returned from deletion.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-609">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-609">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-610">削除されたシークレットを復元します。</span><span class="sxs-lookup"><span data-stu-id="726b2-610">Recovers the deleted secret.</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-611">回復されたシークレットを含む応答メッセージ</span><span class="sxs-lookup"><span data-stu-id="726b2-611">A response message containing the recovered secret</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RecoverDeletedSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RecoverDeletedSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedSecretAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-612">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-612">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-613">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-613">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="726b2-614">削除されたシークレットの名前</span><span class="sxs-lookup"><span data-stu-id="726b2-614">The name of the deleted secret</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-615">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-615">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-616">/Secrets 下にある現在のバージョンに削除されたシークレット バックアップを復元します。</span><span class="sxs-lookup"><span data-stu-id="726b2-616">Recovers the deleted secret back to its current version under /secrets.</span></span>
            <span data-ttu-id="726b2-617">認証:、シークレット/回復のアクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-617">Authorization: requires the secrets/recover permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateStorageAccountKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt; RegenerateStorageAccountKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt; RegenerateStorageAccountKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RegenerateStorageAccountKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateStorageAccountKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RegenerateStorageAccountKeyAsync (operations, vaultBaseUrl, storageAccountName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RegenerateStorageAccountKeyAsync&gt;d__88))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-618">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-618">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-619">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-619">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="726b2-620">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-620">The name of the storage account.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-621">ストレージ アカウント キーの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-621">The storage account key name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-622">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-622">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-623">指定されたストレージ アカウントの指定したキー値を再生成します。</span><span class="sxs-lookup"><span data-stu-id="726b2-623">Regenerates the specified key value for the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RestoreKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, byte[] keyBundleBackup, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RestoreKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, unsigned int8[] keyBundleBackup, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RestoreKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestoreKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RestoreKeyAsync (operations, vaultBaseUrl, keyBundleBackup, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RestoreKeyAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyBundleBackup" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-624">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-624">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-625">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-625">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyBundleBackup">
            <span data-ttu-id="726b2-626">キーのバンドルに関連付けられているバックアップ blob です。</span><span class="sxs-lookup"><span data-stu-id="726b2-626">The backup blob associated with a key bundle.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-627">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-627">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-628">資格情報コンテナーにキーをバックアップを復元します。</span><span class="sxs-lookup"><span data-stu-id="726b2-628">Restores a backed up key to a vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-629">Azure Key Vault、キー、そのキー識別子、属性、およびアクセス制御ポリシーを復元するのには、以前にバックアップ キーをインポートします。</span><span class="sxs-lookup"><span data-stu-id="726b2-629">Imports a previously backed up key into Azure Key Vault, restoring the key, its key identifier, attributes and access control policies.</span></span> <span data-ttu-id="726b2-630">復元操作は、以前にバックアップ キーをインポートするために使用可能性があります。</span><span class="sxs-lookup"><span data-stu-id="726b2-630">The RESTORE operation may be used to import a previously backed up key.</span></span> <span data-ttu-id="726b2-631">キーの個別のバージョンを復元することはできません。</span><span class="sxs-lookup"><span data-stu-id="726b2-631">Individual versions of a key cannot be restored.</span></span> <span data-ttu-id="726b2-632">キーにはバックアップ時と同じキー名で全体として復元されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-632">The key is restored in its entirety with the same key name as it had when it was backed up.</span></span> <span data-ttu-id="726b2-633">キー名をターゲット Key Vault では使用できない場合、復元操作は拒否されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-633">If the key name is not available in the target Key Vault, the RESTORE operation will be rejected.</span></span> <span data-ttu-id="726b2-634">キー名は、復元中に保持されますが、中に、最終的なキー識別子は、別の資格情報コンテナーにキーを復元した場合に変更されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-634">While the key name is retained during restore, the final key identifier will change if the key is restored to a different vault.</span></span> <span data-ttu-id="726b2-635">復元では、すべてのバージョンを復元し、バージョン識別子を保持します。</span><span class="sxs-lookup"><span data-stu-id="726b2-635">Restore will restore all versions and preserve version identifiers.</span></span> <span data-ttu-id="726b2-636">復元操作のセキュリティの制約があります。 ターゲット Key Vault はソース Key Vault、ユーザーがターゲット Key Vault で復元権限を必要と同じ Microsoft Azure サブスクリプションで所有する必要があります。</span><span class="sxs-lookup"><span data-stu-id="726b2-636">The RESTORE operation is subject to security constraints: The target Key Vault must be owned by the same Microsoft Azure Subscription as the source Key Vault The user must have RESTORE permission in the target Key Vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RestoreSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, byte[] secretBundleBackup, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RestoreSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, unsigned int8[] secretBundleBackup, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RestoreSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestoreSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RestoreSecretAsync (operations, vaultBaseUrl, secretBundleBackup, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RestoreSecretAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretBundleBackup" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-637">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-637">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-638">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-638">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretBundleBackup">
            <span data-ttu-id="726b2-639">シークレットのバンドルに関連付けられているバックアップ blob です。</span><span class="sxs-lookup"><span data-stu-id="726b2-639">The backup blob associated with a secret bundle.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-640">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-640">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-641">資格情報コンテナーにシークレットをバックアップを復元します。</span><span class="sxs-lookup"><span data-stu-id="726b2-641">Restores a backed up secret to a vault.</span></span> <span data-ttu-id="726b2-642">認証:、シークレット/復元権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-642">Authorization: requires the secrets/restore permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetCertificateContactsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt; SetCertificateContactsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Microsoft.Azure.KeyVault.Models.Contacts contacts, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt; SetCertificateContactsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, class Microsoft.Azure.KeyVault.Models.Contacts contacts, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetCertificateContactsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,Microsoft.Azure.KeyVault.Models.Contacts,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetCertificateContactsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Microsoft.Azure.KeyVault.Models.Contacts * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetCertificateContactsAsync (operations, vaultBaseUrl, contacts, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SetCertificateContactsAsync&gt;d__60))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="contacts" Type="Microsoft.Azure.KeyVault.Models.Contacts" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-643">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-643">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-644">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-644">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="contacts">
            <span data-ttu-id="726b2-645">キー コンテナーの証明書の連絡先。</span><span class="sxs-lookup"><span data-stu-id="726b2-645">The contacts for the key vault certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-646">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-646">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-647">指定したキー資格情報コンテナーの証明書の連絡先を設定します。</span><span class="sxs-lookup"><span data-stu-id="726b2-647">Sets the certificate contacts for the specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-648">指定したキー資格情報コンテナーの証明書の連絡先を設定します。</span><span class="sxs-lookup"><span data-stu-id="726b2-648">Sets the certificate contacts for the specified key vault.</span></span> <span data-ttu-id="726b2-649">認証:、証明書/managecontacts 権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-649">Authorization: requires the certificates/managecontacts permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetCertificateIssuerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; SetCertificateIssuerAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, string provider, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; SetCertificateIssuerAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetCertificateIssuerAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetCertificateIssuerAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetCertificateIssuerAsync (operations, vaultBaseUrl, issuerName, provider, credentials, organizationDetails, attributes, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SetCertificateIssuerAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-650">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-650">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-651">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-651">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="726b2-652">発行者の名前です。</span><span class="sxs-lookup"><span data-stu-id="726b2-652">The name of the issuer.</span></span>
            </param>
        <param name="provider">
            <span data-ttu-id="726b2-653">発行元プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="726b2-653">The issuer provider.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="726b2-654">発行者のための資格情報。</span><span class="sxs-lookup"><span data-stu-id="726b2-654">The credentials to be used for the issuer.</span></span>
            </param>
        <param name="organizationDetails">
            <span data-ttu-id="726b2-655">発行元に提供される組織の詳細です。</span><span class="sxs-lookup"><span data-stu-id="726b2-655">Details of the organization as provided to the issuer.</span></span>
            </param>
        <param name="attributes">
            <span data-ttu-id="726b2-656">発行元のオブジェクトの属性。</span><span class="sxs-lookup"><span data-stu-id="726b2-656">Attributes of the issuer object.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-657">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-657">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-658">指定された証明書の発行者を設定します。</span><span class="sxs-lookup"><span data-stu-id="726b2-658">Sets the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-659">SetCertificateIssuer 操作を追加または指定された証明書の発行者を更新します。</span><span class="sxs-lookup"><span data-stu-id="726b2-659">The SetCertificateIssuer operation adds or updates the specified certificate issuer.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSasDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; SetSasDefinitionAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; SetSasDefinitionAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetSasDefinitionAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetSasDefinitionAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetSasDefinitionAsync (operations, vaultBaseUrl, storageAccountName, sasDefinitionName, parameters, sasDefinitionAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SetSasDefinitionAsync&gt;d__92))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-660">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-660">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-661">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-661">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="726b2-662">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-662">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="726b2-663">SAS の定義の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-663">The name of the SAS definition.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="726b2-664">Sas 定義は、キー/値ペアの形式でのメタデータを作成します。</span><span class="sxs-lookup"><span data-stu-id="726b2-664">Sas definition creation metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="sasDefinitionAttributes">
            <span data-ttu-id="726b2-665">SAS の定義の属性です。</span><span class="sxs-lookup"><span data-stu-id="726b2-665">The attributes of the SAS definition.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="726b2-666">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="726b2-666">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-667">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-667">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-668">作成するか、指定されたストレージ アカウントに対して新しい SAS 定義を更新します。</span><span class="sxs-lookup"><span data-stu-id="726b2-668">Creates or updates a new SAS definition for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; SetSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string value, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; SetSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string value, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetSecretAsync (operations, vaultBaseUrl, secretName, value, tags, contentType, secretAttributes, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SetSecretAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-669">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-669">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-670">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-670">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="726b2-671">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-671">The name of the secret.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="726b2-672">シークレットの値です。</span><span class="sxs-lookup"><span data-stu-id="726b2-672">The value of the secret.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="726b2-673">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="726b2-673">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="contentType">
            <span data-ttu-id="726b2-674">パスワードなどの秘密の値の型。</span><span class="sxs-lookup"><span data-stu-id="726b2-674">Type of the secret value such as a password.</span></span>
            </param>
        <param name="secretAttributes">
            <span data-ttu-id="726b2-675">シークレットの管理の属性です。</span><span class="sxs-lookup"><span data-stu-id="726b2-675">The secret management attributes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-676">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-676">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-677">指定された key vault のシークレットを設定します。</span><span class="sxs-lookup"><span data-stu-id="726b2-677">Sets a secret in a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-678">設定操作では、Azure Key Vault にシークレットを追加します。</span><span class="sxs-lookup"><span data-stu-id="726b2-678">The SET operation adds a secret to the Azure Key Vault.</span></span> <span data-ttu-id="726b2-679">名前付きのシークレットが既に存在する場合、Azure Key Vault はシークレットの新しいバージョンを作成します。</span><span class="sxs-lookup"><span data-stu-id="726b2-679">If the named secret already exists, Azure Key Vault creates a new version of that secret.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStorageAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt; SetStorageAccountAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt; SetStorageAccountAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetStorageAccountAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Boolean,System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetStorageAccountAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * bool * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetStorageAccountAsync (operations, vaultBaseUrl, storageAccountName, resourceId, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SetStorageAccountAsync&gt;d__86))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Boolean" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-680">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-680">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-681">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-681">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="726b2-682">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-682">The name of the storage account.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="726b2-683">ストレージ アカウントのリソース id です。</span><span class="sxs-lookup"><span data-stu-id="726b2-683">Storage account resource id.</span></span>
            </param>
        <param name="activeKeyName">
            <span data-ttu-id="726b2-684">現在アクティブなストレージ アカウント キーの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-684">Current active storage account key name.</span></span>
            </param>
        <param name="autoRegenerateKey">
            <span data-ttu-id="726b2-685">かどうか keyvault はユーザー用のストレージ アカウントを管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="726b2-685">whether keyvault should manage the storage account for the user.</span></span>
            </param>
        <param name="regenerationPeriod">
            <span data-ttu-id="726b2-686">キーの生成 ISO 8601 形式で指定されている期間。</span><span class="sxs-lookup"><span data-stu-id="726b2-686">The key regeneration time duration specified in ISO-8601 format.</span></span>
            </param>
        <param name="storageAccountAttributes">
            <span data-ttu-id="726b2-687">ストレージ アカウントの属性。</span><span class="sxs-lookup"><span data-stu-id="726b2-687">The attributes of the storage account.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="726b2-688">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="726b2-688">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-689">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-689">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-690">作成するか、新しいストレージ アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="726b2-690">Creates or updates a new storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; SignAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] digest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; SignAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] digest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SignAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SignAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SignAsync (operations, keyIdentifier, algorithm, digest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SignAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"> <span data-ttu-id="726b2-691">署名キーのグローバルのキー識別子</span><span class="sxs-lookup"><span data-stu-id="726b2-691">The global key identifier of the signing key</span></span> </param>
        <param name="algorithm"><span data-ttu-id="726b2-692">署名アルゴリズムです。</span><span class="sxs-lookup"><span data-stu-id="726b2-692">The signing algorithm.</span></span> <span data-ttu-id="726b2-693">可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-693">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span> </param>
        <param name="digest"><span data-ttu-id="726b2-694">署名するダイジェスト値</span><span class="sxs-lookup"><span data-stu-id="726b2-694">The digest value to sign</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-695">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-695">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-696">資格情報コンテナーで指定したキーを使用してダイジェストをから署名を作成します。</span><span class="sxs-lookup"><span data-stu-id="726b2-696">Creates a signature from a digest using the specified key in the vault</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-697">署名の値</span><span class="sxs-lookup"><span data-stu-id="726b2-697">The signature value</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; SignAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; SignAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SignAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SignAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SignAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SignAsync&gt;d__38))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-698">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-698">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-699">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-699">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-700">キー名。</span><span class="sxs-lookup"><span data-stu-id="726b2-700">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="726b2-701">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="726b2-701">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="726b2-702">署名/検証アルゴリズムの識別子です。</span><span class="sxs-lookup"><span data-stu-id="726b2-702">The signing/verification algorithm identifier.</span></span> <span data-ttu-id="726b2-703">可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-703">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span> <span data-ttu-id="726b2-704">使用可能な値が含まれます: 'PS256'、'PS384'、'PS512'、'RS256'、'RS384'、'RS512'、'RSNULL'、'ES256'、'ES384'、'ES512'、'ECDSA256'</span><span class="sxs-lookup"><span data-stu-id="726b2-704">Possible values include: 'PS256', 'PS384', 'PS512', 'RS256', 'RS384', 'RS512', 'RSNULL', 'ES256', 'ES384', 'ES512', 'ECDSA256'</span></span>
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-705">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-705">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-706">指定したキーを使用してダイジェストをから署名を作成します。</span><span class="sxs-lookup"><span data-stu-id="726b2-706">Creates a signature from a digest using the specified key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-707">サインイン操作は、非対称キーおよび対称キーをこの操作は、キーの秘密部分を使用するために、Azure Key Vault に格納されているに適用されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-707">The SIGN operation is applicable to asymmetric and symmetric keys stored in Azure Key Vault since this operation uses the private portion of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnwrapKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; UnwrapKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] wrappedKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; UnwrapKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] wrappedKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UnwrapKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UnwrapKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UnwrapKeyAsync (operations, keyIdentifier, algorithm, wrappedKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UnwrapKeyAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="wrappedKey" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"> <span data-ttu-id="726b2-708">ラップ/ラップ解除キーのグローバルのキー識別子</span><span class="sxs-lookup"><span data-stu-id="726b2-708">The global key identifier of the wrapping/unwrapping key</span></span> </param>
        <param name="algorithm"><span data-ttu-id="726b2-709">Unwrap アルゴリズムです。</span><span class="sxs-lookup"><span data-stu-id="726b2-709">The unwrap algorithm.</span></span> <span data-ttu-id="726b2-710">可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-710">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span></param>
        <param name="wrappedKey"><span data-ttu-id="726b2-711">ラップされた対称キー</span><span class="sxs-lookup"><span data-stu-id="726b2-711">The wrapped symmetric key</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-712">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-712">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-713">最初に、キー ラップに使用されている資格情報コンテナーに指定したキーを使用して対称キーのラップを解除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-713">Unwraps a symmetric key using the specified key in the vault that has initially been used for wrapping the key.</span></span>
                </summary>
        <returns><span data-ttu-id="726b2-714">ラップ解除された対称キー</span><span class="sxs-lookup"><span data-stu-id="726b2-714">The unwrapped symmetric key</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnwrapKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; UnwrapKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; UnwrapKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UnwrapKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UnwrapKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UnwrapKeyAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UnwrapKeyAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-715">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-715">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-716">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-716">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-717">キー名。</span><span class="sxs-lookup"><span data-stu-id="726b2-717">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="726b2-718">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="726b2-718">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="726b2-719">アルゴリズムの識別子です。</span><span class="sxs-lookup"><span data-stu-id="726b2-719">algorithm identifier.</span></span> <span data-ttu-id="726b2-720">使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。</span><span class="sxs-lookup"><span data-stu-id="726b2-720">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-721">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-721">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-722">そのキーをラップするために使用された最初に指定したキーを使用して対称キーのラップを解除します。</span><span class="sxs-lookup"><span data-stu-id="726b2-722">Unwraps a symmetric key using the specified key that was initially used for wrapping that key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-723">UNWRAP 操作は、対象キーの暗号化キーを使用して対称キーの復号化をサポートします。</span><span class="sxs-lookup"><span data-stu-id="726b2-723">The UNWRAP operation supports decryption of a symmetric key using the target key encryption key.</span></span> <span data-ttu-id="726b2-724">この操作は、WRAP 操作の逆です。</span><span class="sxs-lookup"><span data-stu-id="726b2-724">This operation is the reverse of the WRAP operation.</span></span> <span data-ttu-id="726b2-725">UNWRAP 操作は、非対称キーおよび対称キー、キーの秘密部分を使用しているので、Azure Key Vault に格納されているに適用されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-725">The UNWRAP operation applies to asymmetric and symmetric keys stored in Azure Key Vault since it uses the private portion of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; UpdateCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string certificateIdentifier, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; UpdateCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string certificateIdentifier, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateAsync (operations, certificateIdentifier, certificatePolicy, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateCertificateAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="certificateIdentifier" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="certificateIdentifier"><span data-ttu-id="726b2-726">証明書の URL です。</span><span class="sxs-lookup"><span data-stu-id="726b2-726">The URL for the certificate.</span></span></param>
        <param name="certificatePolicy"><span data-ttu-id="726b2-727">証明書の管理ポリシー。</span><span class="sxs-lookup"><span data-stu-id="726b2-727">The management policy for the certificate.</span></span></param>
        <param name="certificateAttributes"><span data-ttu-id="726b2-728">(省略可能) の証明書の属性</span><span class="sxs-lookup"><span data-stu-id="726b2-728">The attributes of the certificate (optional)</span></span></param>
        <param name="tags"><span data-ttu-id="726b2-729">キー/値ペアの形式でのアプリケーション固有のメタデータ</span><span class="sxs-lookup"><span data-stu-id="726b2-729">Application-specific metadata in the form of key-value pairs</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-730">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-730">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-731">証明書のバージョンを更新します。</span><span class="sxs-lookup"><span data-stu-id="726b2-731">Updates a certificate version.</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-732">更新された証明書。</span><span class="sxs-lookup"><span data-stu-id="726b2-732">The updated certificate.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; UpdateCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string certificateVersion, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; UpdateCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string certificateVersion, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateAsync (operations, vaultBaseUrl, certificateName, certificateVersion, certificatePolicy, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateCertificateAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVersion" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-733">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-733">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-734">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-734">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="726b2-735">指定されたキー コンテナーに証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-735">The name of the certificate in the given key vault.</span></span>
            </param>
        <param name="certificateVersion">
            <span data-ttu-id="726b2-736">証明書のバージョン。</span><span class="sxs-lookup"><span data-stu-id="726b2-736">The version of the certificate.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="726b2-737">証明書の管理ポリシー。</span><span class="sxs-lookup"><span data-stu-id="726b2-737">The management policy for the certificate.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="726b2-738">(省略可能) の証明書の属性。</span><span class="sxs-lookup"><span data-stu-id="726b2-738">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="726b2-739">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="726b2-739">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-740">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-740">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-741">特定の証明書に関連付けられている指定された属性を更新します。</span><span class="sxs-lookup"><span data-stu-id="726b2-741">Updates the specified attributes associated with the given certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-742">UpdateCertificate 操作は指定された証明書の指定した更新プログラムを適用します。要素だけが更新中は、証明書の属性に注意してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-742">The UpdateCertificate operation applies the specified update on the given certificate; note the only elements being updated are the certificate's attributes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateIssuerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; UpdateCertificateIssuerAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, string provider = null, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; UpdateCertificateIssuerAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateIssuerAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCertificateIssuerAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateIssuerAsync (operations, vaultBaseUrl, issuerName, provider, credentials, organizationDetails, attributes, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateCertificateIssuerAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-743">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-743">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-744">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-744">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="726b2-745">発行者の名前です。</span><span class="sxs-lookup"><span data-stu-id="726b2-745">The name of the issuer.</span></span>
            </param>
        <param name="provider">
            <span data-ttu-id="726b2-746">発行元プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="726b2-746">The issuer provider.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="726b2-747">発行者のための資格情報。</span><span class="sxs-lookup"><span data-stu-id="726b2-747">The credentials to be used for the issuer.</span></span>
            </param>
        <param name="organizationDetails">
            <span data-ttu-id="726b2-748">発行元に提供される組織の詳細です。</span><span class="sxs-lookup"><span data-stu-id="726b2-748">Details of the organization as provided to the issuer.</span></span>
            </param>
        <param name="attributes">
            <span data-ttu-id="726b2-749">発行元のオブジェクトの属性。</span><span class="sxs-lookup"><span data-stu-id="726b2-749">Attributes of the issuer object.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-750">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-750">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-751">指定された証明書の発行者を更新します。</span><span class="sxs-lookup"><span data-stu-id="726b2-751">Updates the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-752">UpdateCertificateIssuer 操作は、指定された証明書発行者のエンティティの更新プログラムを実行します。</span><span class="sxs-lookup"><span data-stu-id="726b2-752">The UpdateCertificateIssuer operation performs an update on the specified certificate issuer entity.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateOperationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; UpdateCertificateOperationAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, bool cancellationRequested, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; UpdateCertificateOperationAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, bool cancellationRequested, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateOperationAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCertificateOperationAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateOperationAsync (operations, vaultBaseUrl, certificateName, cancellationRequested, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateCertificateOperationAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationRequested" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-753">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-753">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-754">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-754">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="726b2-755">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-755">The name of the certificate.</span></span>
            </param>
        <param name="cancellationRequested">
            <span data-ttu-id="726b2-756">証明書の操作のキャンセルが要求されたかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="726b2-756">Indicates if cancellation was requested on the certificate operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-757">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-757">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-758">証明書の操作を更新します。</span><span class="sxs-lookup"><span data-stu-id="726b2-758">Updates a certificate operation.</span></span> <span data-ttu-id="726b2-759">認証:、証明書/更新アクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="726b2-759">Authorization: requires the certificates/update permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificatePolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt; UpdateCertificatePolicyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt; UpdateCertificatePolicyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificatePolicyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCertificatePolicyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificatePolicyAsync (operations, vaultBaseUrl, certificateName, certificatePolicy, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateCertificatePolicyAsync&gt;d__72))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-760">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-760">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-761">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-761">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="726b2-762">指定された資格情報コンテナー内の証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-762">The name of the certificate in the given vault.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="726b2-763">証明書のポリシーです。</span><span class="sxs-lookup"><span data-stu-id="726b2-763">The policy for the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-764">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-764">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-765">証明書のポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="726b2-765">Updates the policy for a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-766">証明書のポリシーで指定したメンバーを設定します。</span><span class="sxs-lookup"><span data-stu-id="726b2-766">Set specified members in the certificate policy.</span></span> <span data-ttu-id="726b2-767">Null として他のユーザーのままにします。</span><span class="sxs-lookup"><span data-stu-id="726b2-767">Leave others as null.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string[] keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes attributes = null, System.Collections.Generic.Dictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string[] keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes attributes, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String[],Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.Dictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string[] * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.Dictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync (operations, keyIdentifier, keyOps, attributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateKeyAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="keyOps" Type="System.String[]" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"><span data-ttu-id="726b2-768">キー識別子</span><span class="sxs-lookup"><span data-stu-id="726b2-768">The key identifier</span></span></param>
        <param name="keyOps"><span data-ttu-id="726b2-769">Json web キー操作。</span><span class="sxs-lookup"><span data-stu-id="726b2-769">Json web key operations.</span></span> <span data-ttu-id="726b2-770">詳細については、JsonWebKeyOperation を参照してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-770">For more information, see JsonWebKeyOperation.</span></span></param>
        <param name="attributes"><span data-ttu-id="726b2-771">キーの新しい属性。</span><span class="sxs-lookup"><span data-stu-id="726b2-771">The new attributes for the key.</span></span> <span data-ttu-id="726b2-772">キー属性の詳細については、KeyAttributes を参照してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-772">For more information on key attributes, see KeyAttributes.</span></span></param>
        <param name="tags"><span data-ttu-id="726b2-773">キー/値ペアの形式でのアプリケーション固有のメタデータ</span><span class="sxs-lookup"><span data-stu-id="726b2-773">Application-specific metadata in the form of key-value pairs</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-774">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-774">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-775">指定したキーに関連付けられているキー属性を更新します。</span><span class="sxs-lookup"><span data-stu-id="726b2-775">Updates the Key Attributes associated with the specified key</span></span>
            </summary>
        <returns> <span data-ttu-id="726b2-776">更新されたキー</span><span class="sxs-lookup"><span data-stu-id="726b2-776">The updated key</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string[] keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes attributes = null, System.Collections.Generic.Dictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string[] keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes attributes, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String[],Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.Dictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string[] * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.Dictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync (operations, vaultBaseUrl, keyName, keyOps, attributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateKeyAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyOps" Type="System.String[]" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl"><span data-ttu-id="726b2-777">資格情報コンテナー名、https://myvault.vault.azure.net 例:</span><span class="sxs-lookup"><span data-stu-id="726b2-777">The vault name, e.g. https://myvault.vault.azure.net</span></span></param>
        <param name="keyName"><span data-ttu-id="726b2-778">キー名</span><span class="sxs-lookup"><span data-stu-id="726b2-778">The key name</span></span></param>
        <param name="keyOps"><span data-ttu-id="726b2-779">Json web キー操作。</span><span class="sxs-lookup"><span data-stu-id="726b2-779">Json web key operations.</span></span> <span data-ttu-id="726b2-780">考えられるキーの操作の詳細については、JsonWebKeyOperation を参照してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-780">For more information on possible key operations, see JsonWebKeyOperation.</span></span></param>
        <param name="attributes"><span data-ttu-id="726b2-781">キーの新しい属性。</span><span class="sxs-lookup"><span data-stu-id="726b2-781">The new attributes for the key.</span></span> <span data-ttu-id="726b2-782">キー属性の詳細については、KeyAttributes を参照してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-782">For more information on key attributes, see KeyAttributes.</span></span></param>
        <param name="tags"><span data-ttu-id="726b2-783">キー/値ペアの形式でのアプリケーション固有のメタデータ</span><span class="sxs-lookup"><span data-stu-id="726b2-783">Application-specific metadata in the form of key-value pairs</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="726b2-784">指定したキーに関連付けられているキー属性を更新します。</span><span class="sxs-lookup"><span data-stu-id="726b2-784">Updates the Key Attributes associated with the specified key</span></span>
            </summary>
        <returns> <span data-ttu-id="726b2-785">更新されたキー</span><span class="sxs-lookup"><span data-stu-id="726b2-785">The updated key</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync (operations, vaultBaseUrl, keyName, keyVersion, keyOps, keyAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateKeyAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-786">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-786">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-787">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-787">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-788">更新するキーの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-788">The name of key to update.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="726b2-789">更新するキーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="726b2-789">The version of the key to update.</span></span>
            </param>
        <param name="keyOps">
            <span data-ttu-id="726b2-790">Json web キー操作。</span><span class="sxs-lookup"><span data-stu-id="726b2-790">Json web key operations.</span></span> <span data-ttu-id="726b2-791">考えられるキーの操作の詳細については、JsonWebKeyOperation を参照してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-791">For more information on possible key operations, see JsonWebKeyOperation.</span></span>
            </param>
        <param name="keyAttributes"></param>
        <param name="tags">
            <span data-ttu-id="726b2-792">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="726b2-792">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-793">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-793">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-794">キー操作の変更の更新は、格納されたキーの属性を指定し、任意のキーの型と Azure Key Vault に格納されているキーのバージョンに適用できます。</span><span class="sxs-lookup"><span data-stu-id="726b2-794">The update key operation changes specified attributes of a stored key and can be applied to any key type and key version stored in Azure Key Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-795">この操作を実行するために Key Vault にキーが既に存在しています。</span><span class="sxs-lookup"><span data-stu-id="726b2-795">In order to perform this operation, the key must already exist in the Key Vault.</span></span> <span data-ttu-id="726b2-796">注: キー自体の暗号化マテリアルは変更できません。</span><span class="sxs-lookup"><span data-stu-id="726b2-796">Note: The cryptographic material of a key itself cannot be changed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSasDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; UpdateSasDefinitionAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters = null, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; UpdateSasDefinitionAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSasDefinitionAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSasDefinitionAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSasDefinitionAsync (operations, vaultBaseUrl, storageAccountName, sasDefinitionName, parameters, sasDefinitionAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateSasDefinitionAsync&gt;d__93))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-797">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-797">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-798">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-798">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="726b2-799">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-799">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="726b2-800">SAS の定義の名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-800">The name of the SAS definition.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="726b2-801">Sas の定義は、キー/値ペアの形式でメタデータを更新します。</span><span class="sxs-lookup"><span data-stu-id="726b2-801">Sas definition update metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="sasDefinitionAttributes">
            <span data-ttu-id="726b2-802">SAS の定義の属性です。</span><span class="sxs-lookup"><span data-stu-id="726b2-802">The attributes of the SAS definition.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="726b2-803">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="726b2-803">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-804">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-804">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-805">特定の SAS 定義に関連付けられている指定された属性を更新します。</span><span class="sxs-lookup"><span data-stu-id="726b2-805">Updates the specified attributes associated with the given SAS definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; UpdateSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string secretIdentifier, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Collections.Generic.Dictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; UpdateSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string secretIdentifier, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.Dictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.Dictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSecretAsync (operations, secretIdentifier, contentType, secretAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateSecretAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="secretIdentifier" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="secretIdentifier"><span data-ttu-id="726b2-806">シークレットの URL</span><span class="sxs-lookup"><span data-stu-id="726b2-806">The URL of the secret</span></span></param>
        <param name="contentType"><span data-ttu-id="726b2-807">パスワードなどの秘密の値の型。</span><span class="sxs-lookup"><span data-stu-id="726b2-807">Type of the secret value such as password.</span></span></param>
        <param name="secretAttributes"><span data-ttu-id="726b2-808">シークレットの属性。</span><span class="sxs-lookup"><span data-stu-id="726b2-808">Attributes for the secret.</span></span> <span data-ttu-id="726b2-809">使用可能な属性の詳細については、SecretAttributes を参照してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-809">For more information on possible attributes, see SecretAttributes.</span></span></param>
        <param name="tags"><span data-ttu-id="726b2-810">キー/値ペアの形式でのアプリケーション固有のメタデータ</span><span class="sxs-lookup"><span data-stu-id="726b2-810">Application-specific metadata in the form of key-value pairs</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="726b2-811">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-811">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-812">指定されたシークレットに関連付けられている属性を更新します。</span><span class="sxs-lookup"><span data-stu-id="726b2-812">Updates the attributes associated with the specified secret</span></span>
            </summary>
        <returns><span data-ttu-id="726b2-813">更新されたシークレットを含む応答メッセージ</span><span class="sxs-lookup"><span data-stu-id="726b2-813">A response message containing the updated secret</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; UpdateSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string secretVersion, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; UpdateSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string secretVersion, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSecretAsync (operations, vaultBaseUrl, secretName, secretVersion, contentType, secretAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateSecretAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="secretVersion" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-814">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-814">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-815">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-815">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="726b2-816">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-816">The name of the secret.</span></span>
            </param>
        <param name="secretVersion">
            <span data-ttu-id="726b2-817">シークレットのバージョン。</span><span class="sxs-lookup"><span data-stu-id="726b2-817">The version of the secret.</span></span>
            </param>
        <param name="contentType">
            <span data-ttu-id="726b2-818">パスワードなどの秘密の値の型。</span><span class="sxs-lookup"><span data-stu-id="726b2-818">Type of the secret value such as a password.</span></span>
            </param>
        <param name="secretAttributes">
            <span data-ttu-id="726b2-819">シークレットの管理の属性です。</span><span class="sxs-lookup"><span data-stu-id="726b2-819">The secret management attributes.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="726b2-820">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="726b2-820">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-821">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-821">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-822">指定されたキー コンテナーに指定されたシークレットを使用して関連付けられている属性を更新します。</span><span class="sxs-lookup"><span data-stu-id="726b2-822">Updates the attributes associated with a specified secret in a given key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-823">更新操作は、既存の格納されているシークレットの指定された属性を変更します。</span><span class="sxs-lookup"><span data-stu-id="726b2-823">The UPDATE operation changes specified attributes of an existing stored secret.</span></span> <span data-ttu-id="726b2-824">要求で指定されていない属性のまま変更されません。</span><span class="sxs-lookup"><span data-stu-id="726b2-824">Attributes that are not specified in the request are left unchanged.</span></span> <span data-ttu-id="726b2-825">シークレット自体の値は変更できません。</span><span class="sxs-lookup"><span data-stu-id="726b2-825">The value of a secret itself cannot be changed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateStorageAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt; UpdateStorageAccountAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string activeKeyName = null, Nullable&lt;bool&gt; autoRegenerateKey = null, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt; UpdateStorageAccountAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string activeKeyName, valuetype System.Nullable`1&lt;bool&gt; autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateStorageAccountAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateStorageAccountAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateStorageAccountAsync (operations, vaultBaseUrl, storageAccountName, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateStorageAccountAsync&gt;d__87))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-826">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-826">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-827">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-827">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="726b2-828">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="726b2-828">The name of the storage account.</span></span>
            </param>
        <param name="activeKeyName">
            <span data-ttu-id="726b2-829">現在アクティブなストレージ アカウント キー名。</span><span class="sxs-lookup"><span data-stu-id="726b2-829">The current active storage account key name.</span></span>
            </param>
        <param name="autoRegenerateKey">
            <span data-ttu-id="726b2-830">かどうか keyvault はユーザー用のストレージ アカウントを管理する必要があります。</span><span class="sxs-lookup"><span data-stu-id="726b2-830">whether keyvault should manage the storage account for the user.</span></span>
            </param>
        <param name="regenerationPeriod">
            <span data-ttu-id="726b2-831">キーの生成 ISO 8601 形式で指定されている期間。</span><span class="sxs-lookup"><span data-stu-id="726b2-831">The key regeneration time duration specified in ISO-8601 format.</span></span>
            </param>
        <param name="storageAccountAttributes">
            <span data-ttu-id="726b2-832">ストレージ アカウントの属性。</span><span class="sxs-lookup"><span data-stu-id="726b2-832">The attributes of the storage account.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="726b2-833">キー/値ペアの形式でのアプリケーション固有のメタデータ。</span><span class="sxs-lookup"><span data-stu-id="726b2-833">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-834">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-834">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-835">特定のストレージ アカウントに関連付けられている指定された属性を更新します。</span><span class="sxs-lookup"><span data-stu-id="726b2-835">Updates the specified attributes associated with the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; VerifyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] digest, byte[] signature, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; VerifyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] digest, unsigned int8[] signature, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.VerifyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.VerifyAsync (operations, keyIdentifier, algorithm, digest, signature, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;VerifyAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"> <span data-ttu-id="726b2-836">署名に使用されるキーのグローバルのキー識別子</span><span class="sxs-lookup"><span data-stu-id="726b2-836">The global key identifier of the key used for signing</span></span> </param>
        <param name="algorithm"> <span data-ttu-id="726b2-837">署名/検証アルゴリズムです。</span><span class="sxs-lookup"><span data-stu-id="726b2-837">The signing/verification algorithm.</span></span> <span data-ttu-id="726b2-838">可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-838">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span></param>
        <param name="digest"> <span data-ttu-id="726b2-839">署名に使用されるダイジェスト</span><span class="sxs-lookup"><span data-stu-id="726b2-839">The digest used for signing</span></span> </param>
        <param name="signature"> <span data-ttu-id="726b2-840">検証対象の署名</span><span class="sxs-lookup"><span data-stu-id="726b2-840">The signature to be verified</span></span> </param>
        <param name="cancellationToken"><span data-ttu-id="726b2-841">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-841">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-842">指定したキーを使用して署名を検証します。</span><span class="sxs-lookup"><span data-stu-id="726b2-842">Verifies a signature using the specified key</span></span>
            </summary>
        <returns> <span data-ttu-id="726b2-843">署名検証済みの場合は false、それ以外の場合は true。</span><span class="sxs-lookup"><span data-stu-id="726b2-843">true if the signature is verified, false otherwise.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt; VerifyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] digest, byte[] signature, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt; VerifyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] digest, unsigned int8[] signature, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.VerifyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.VerifyAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, digest, signature, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;VerifyAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-844">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-844">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-845">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-845">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-846">キー名。</span><span class="sxs-lookup"><span data-stu-id="726b2-846">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="726b2-847">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="726b2-847">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="726b2-848">署名/検証アルゴリズムです。</span><span class="sxs-lookup"><span data-stu-id="726b2-848">The signing/verification algorithm.</span></span> <span data-ttu-id="726b2-849">可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-849">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span> <span data-ttu-id="726b2-850">使用可能な値が含まれます: 'PS256'、'PS384'、'PS512'、'RS256'、'RS384'、'RS512'、'RSNULL'、'ES256'、'ES384'、'ES512'、'ECDSA256'</span><span class="sxs-lookup"><span data-stu-id="726b2-850">Possible values include: 'PS256', 'PS384', 'PS512', 'RS256', 'RS384', 'RS512', 'RSNULL', 'ES256', 'ES384', 'ES512', 'ECDSA256'</span></span>
            </param>
        <param name="digest">
            <span data-ttu-id="726b2-851">ダイジェストの署名に使用します。</span><span class="sxs-lookup"><span data-stu-id="726b2-851">The digest used for signing.</span></span>
            </param>
        <param name="signature">
            <span data-ttu-id="726b2-852">検証対象の署名。</span><span class="sxs-lookup"><span data-stu-id="726b2-852">The signature to be verified.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-853">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-853">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-854">指定したキーを使用して署名を確認します。</span><span class="sxs-lookup"><span data-stu-id="726b2-854">Verifies a signature using a specified key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-855">検証処理は、Azure Key Vault に格納された対称キーを適用されます。</span><span class="sxs-lookup"><span data-stu-id="726b2-855">The VERIFY operation is applicable to symmetric keys stored in Azure Key Vault.</span></span> <span data-ttu-id="726b2-856">確認は不要な厳密にキーのパブリック部分を使用して署名の検証を実行できますが、この操作は、キー参照のみを持つ呼び出し元の便宜を図ってサポートので、Azure Key Vault に格納されている非対称キーのないと、キーのパブリックの部分です。</span><span class="sxs-lookup"><span data-stu-id="726b2-856">VERIFY is not strictly necessary for asymmetric keys stored in Azure Key Vault since signature verification can be performed using the public portion of the key but this operation is supported as a convenience for callers that only have a key-reference and not the public portion of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WrapKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; WrapKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] key, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; WrapKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] key, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.WrapKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member WrapKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.WrapKeyAsync (operations, keyIdentifier, algorithm, key, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;WrapKeyAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="key" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"> <span data-ttu-id="726b2-857">折り返しを使用するキーのグローバルのキー識別子</span><span class="sxs-lookup"><span data-stu-id="726b2-857">The global key identifier of the key used for wrapping</span></span> </param>
        <param name="algorithm"> <span data-ttu-id="726b2-858">ラップのアルゴリズム。</span><span class="sxs-lookup"><span data-stu-id="726b2-858">The wrap algorithm.</span></span> <span data-ttu-id="726b2-859">可能なアルゴリズムの種類の詳細については、JsonWebKeySignatureAlgorithm を参照してください。</span><span class="sxs-lookup"><span data-stu-id="726b2-859">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span></param>
        <param name="key"> <span data-ttu-id="726b2-860">対称キー</span><span class="sxs-lookup"><span data-stu-id="726b2-860">The symmetric key</span></span> </param>
        <param name="cancellationToken"><span data-ttu-id="726b2-861">省略可能なキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="726b2-861">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="726b2-862">指定したキーを使用して対称キーをラップします。</span><span class="sxs-lookup"><span data-stu-id="726b2-862">Wraps a symmetric key using the specified key</span></span>
            </summary>
        <returns> <span data-ttu-id="726b2-863">ラップされた対称キー</span><span class="sxs-lookup"><span data-stu-id="726b2-863">The wrapped symmetric key</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WrapKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; WrapKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; WrapKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.WrapKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member WrapKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.WrapKeyAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;WrapKeyAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="726b2-864">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="726b2-864">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="726b2-865">資格情報コンテナー名では、たとえば https://myvault.vault.azure.net します。</span><span class="sxs-lookup"><span data-stu-id="726b2-865">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="726b2-866">キー名。</span><span class="sxs-lookup"><span data-stu-id="726b2-866">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="726b2-867">キーのバージョン。</span><span class="sxs-lookup"><span data-stu-id="726b2-867">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="726b2-868">アルゴリズムの識別子です。</span><span class="sxs-lookup"><span data-stu-id="726b2-868">algorithm identifier.</span></span> <span data-ttu-id="726b2-869">使用可能な値が含まれます: ' RSA OAEP'、' RSA OAEP 256'、': rsa1_5 '。</span><span class="sxs-lookup"><span data-stu-id="726b2-869">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            <span data-ttu-id="726b2-870">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="726b2-870">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="726b2-871">指定したキーを使用して対称キーをラップします。</span><span class="sxs-lookup"><span data-stu-id="726b2-871">Wraps a symmetric key using a specified key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="726b2-872">WRAP 操作では、以前、Azure Key Vault に格納されているキーの暗号化キーを使用して対称キーの暗号化をサポートします。</span><span class="sxs-lookup"><span data-stu-id="726b2-872">The WRAP operation supports encryption of a symmetric key using a key encryption key that has previously been stored in an Azure Key Vault.</span></span> <span data-ttu-id="726b2-873">WRAP 操作は、キーの公開部分を使用して非対称キーで保護を実行できるので、Azure Key Vault に格納されている対称キーの厳密に必要だけです。</span><span class="sxs-lookup"><span data-stu-id="726b2-873">The WRAP operation is only strictly necessary for symmetric keys stored in Azure Key Vault since protection with an asymmetric key can be performed using the public portion of the key.</span></span> <span data-ttu-id="726b2-874">この操作は、キー参照であるが、パブリックのキー マテリアルにアクセスできない呼び出し元の便宜を図って非対称キーのサポートは。</span><span class="sxs-lookup"><span data-stu-id="726b2-874">This operation is supported for asymmetric keys as a convenience for callers that have a key-reference but do not have access to the public key material.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>