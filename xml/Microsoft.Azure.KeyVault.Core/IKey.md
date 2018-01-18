<Type Name="IKey" FullName="Microsoft.Azure.KeyVault.Core.IKey">
  <TypeSignature Language="C#" Value="public interface IKey : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IKey implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Core.IKey" />
  <TypeSignature Language="VB.NET" Value="Public Interface IKey&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IKey = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="9c746-101">キーのためのインターフェイスします。</span><span class="sxs-lookup"><span data-stu-id="9c746-101">Interface for Keys</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DecryptAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; DecryptAsync (byte[] ciphertext, byte[] iv, byte[] authenticationData, byte[] authenticationTag, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; DecryptAsync(unsigned int8[] ciphertext, unsigned int8[] iv, unsigned int8[] authenticationData, unsigned int8[] authenticationTag, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.DecryptAsync(System.Byte[],System.Byte[],System.Byte[],System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function DecryptAsync (ciphertext As Byte(), iv As Byte(), authenticationData As Byte(), authenticationTag As Byte(), algorithm As String, token As CancellationToken) As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member DecryptAsync : byte[] * byte[] * byte[] * byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="iKey.DecryptAsync (ciphertext, iv, authenticationData, authenticationTag, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ciphertext" Type="System.Byte[]" />
        <Parameter Name="iv" Type="System.Byte[]" />
        <Parameter Name="authenticationData" Type="System.Byte[]" />
        <Parameter Name="authenticationTag" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="ciphertext"><span data-ttu-id="9c746-102">暗号化を解除する暗号テキスト</span><span class="sxs-lookup"><span data-stu-id="9c746-102">The cipher text to decrypt</span></span></param>
        <param name="iv"><span data-ttu-id="9c746-103">初期化ベクター</span><span class="sxs-lookup"><span data-stu-id="9c746-103">The initialization vector</span></span></param>
        <param name="authenticationData"><span data-ttu-id="9c746-104">認証データは、</span><span class="sxs-lookup"><span data-stu-id="9c746-104">The authentication data</span></span></param>
        <param name="authenticationTag">To be added.</param>
        <param name="algorithm"><span data-ttu-id="9c746-105">使用するアルゴリズム</span><span class="sxs-lookup"><span data-stu-id="9c746-105">The algorithm to use</span></span></param>
        <param name="token"><span data-ttu-id="9c746-106">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="9c746-106">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="9c746-107">指定した暗号テキストを復号化します。</span><span class="sxs-lookup"><span data-stu-id="9c746-107">Decrypts the specified cipher text.</span></span>
            </summary>
        <returns><span data-ttu-id="9c746-108">プレーン テキスト</span><span class="sxs-lookup"><span data-stu-id="9c746-108">The plain text</span></span></returns>
        <remarks><span data-ttu-id="9c746-109">アルゴリズムが指定されていない場合、実装では、既定のアルゴリズムを使用してください。</span><span class="sxs-lookup"><span data-stu-id="9c746-109">If algorithm is not specified, an implementation should use its default algorithm.</span></span>
            <span data-ttu-id="9c746-110">すべてのアルゴリズムは、要求、またはすべてのパラメーターをサポートします。</span><span class="sxs-lookup"><span data-stu-id="9c746-110">Not all algorithms require, or support, all parameters.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultEncryptionAlgorithm">
      <MemberSignature Language="C#" Value="public string DefaultEncryptionAlgorithm { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultEncryptionAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Core.IKey.DefaultEncryptionAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultEncryptionAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.DefaultEncryptionAlgorithm : string" Usage="Microsoft.Azure.KeyVault.Core.IKey.DefaultEncryptionAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c746-111">このキーの既定の暗号化アルゴリズム</span><span class="sxs-lookup"><span data-stu-id="9c746-111">The default encryption algorithm for this key</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultKeyWrapAlgorithm">
      <MemberSignature Language="C#" Value="public string DefaultKeyWrapAlgorithm { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultKeyWrapAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Core.IKey.DefaultKeyWrapAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultKeyWrapAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.DefaultKeyWrapAlgorithm : string" Usage="Microsoft.Azure.KeyVault.Core.IKey.DefaultKeyWrapAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c746-112">既定のキーは、このキーのアルゴリズムを折り返す</span><span class="sxs-lookup"><span data-stu-id="9c746-112">The default key wrap algorithm for this key</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultSignatureAlgorithm">
      <MemberSignature Language="C#" Value="public string DefaultSignatureAlgorithm { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultSignatureAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Core.IKey.DefaultSignatureAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultSignatureAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.DefaultSignatureAlgorithm : string" Usage="Microsoft.Azure.KeyVault.Core.IKey.DefaultSignatureAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c746-113">このキーの既定の署名アルゴリズム</span><span class="sxs-lookup"><span data-stu-id="9c746-113">The default signature algorithm for this key</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Tuple&lt;byte[],byte[],string&gt;&gt; EncryptAsync (byte[] plaintext, byte[] iv, byte[] authenticationData, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Tuple`3&lt;unsigned int8[], unsigned int8[], string&gt;&gt; EncryptAsync(unsigned int8[] plaintext, unsigned int8[] iv, unsigned int8[] authenticationData, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.EncryptAsync(System.Byte[],System.Byte[],System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function EncryptAsync (plaintext As Byte(), iv As Byte(), authenticationData As Byte(), algorithm As String, token As CancellationToken) As Task(Of Tuple(Of Byte(), Byte(), String))" />
      <MemberSignature Language="F#" Value="abstract member EncryptAsync : byte[] * byte[] * byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[] * byte[] * string&gt;" Usage="iKey.EncryptAsync (plaintext, iv, authenticationData, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Tuple&lt;System.Byte[],System.Byte[],System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="plaintext" Type="System.Byte[]" />
        <Parameter Name="iv" Type="System.Byte[]" />
        <Parameter Name="authenticationData" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="plaintext"><span data-ttu-id="9c746-114">プレーン テキストを暗号化するには</span><span class="sxs-lookup"><span data-stu-id="9c746-114">The plain text to encrypt</span></span></param>
        <param name="iv"><span data-ttu-id="9c746-115">初期化ベクター</span><span class="sxs-lookup"><span data-stu-id="9c746-115">The initialization vector</span></span></param>
        <param name="authenticationData"><span data-ttu-id="9c746-116">認証データは、</span><span class="sxs-lookup"><span data-stu-id="9c746-116">The authentication data</span></span></param>
        <param name="algorithm"><span data-ttu-id="9c746-117">使用するアルゴリズム</span><span class="sxs-lookup"><span data-stu-id="9c746-117">The algorithm to use</span></span></param>
        <param name="token"><span data-ttu-id="9c746-118">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="9c746-118">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="9c746-119">指定されたプレーン テキストを暗号化します。</span><span class="sxs-lookup"><span data-stu-id="9c746-119">Encrypts the specified plain text.</span></span>
            </summary>
        <returns><span data-ttu-id="9c746-120">暗号化テキスト、認証タグ (該当する場合)、使用するアルゴリズムで構成されるタプル</span><span class="sxs-lookup"><span data-stu-id="9c746-120">A Tuple consisting of the cipher text, the authentication tag (if applicable), the algorithm used</span></span></returns>
        <remarks><span data-ttu-id="9c746-121">アルゴリズムが指定されていない場合、実装では、既定のアルゴリズムを使用してください。</span><span class="sxs-lookup"><span data-stu-id="9c746-121">If the algorithm is not specified, an implementation should use its default algorithm.</span></span>
            <span data-ttu-id="9c746-122">すべて algorithyms が必要なまたはすべてのパラメーターをサポートします。</span><span class="sxs-lookup"><span data-stu-id="9c746-122">Not all algorithyms require, or support, all parameters.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Kid">
      <MemberSignature Language="C#" Value="public string Kid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Core.IKey.Kid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kid As String" />
      <MemberSignature Language="F#" Value="member this.Kid : string" Usage="Microsoft.Azure.KeyVault.Core.IKey.Kid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c746-123">キー識別子</span><span class="sxs-lookup"><span data-stu-id="9c746-123">The key identifier</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Tuple&lt;byte[],string&gt;&gt; SignAsync (byte[] digest, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Tuple`2&lt;unsigned int8[], string&gt;&gt; SignAsync(unsigned int8[] digest, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.SignAsync(System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function SignAsync (digest As Byte(), algorithm As String, token As CancellationToken) As Task(Of Tuple(Of Byte(), String))" />
      <MemberSignature Language="F#" Value="abstract member SignAsync : byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[] * string&gt;" Usage="iKey.SignAsync (digest, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Tuple&lt;System.Byte[],System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="digest"><span data-ttu-id="9c746-124">署名するダイジェスト</span><span class="sxs-lookup"><span data-stu-id="9c746-124">The digest to sign</span></span></param>
        <param name="algorithm"><span data-ttu-id="9c746-125">使用するアルゴリズム</span><span class="sxs-lookup"><span data-stu-id="9c746-125">The algorithm to use</span></span></param>
        <param name="token"><span data-ttu-id="9c746-126">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="9c746-126">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="9c746-127">指定したダイジェストに署名します。</span><span class="sxs-lookup"><span data-stu-id="9c746-127">Signs the specified digest.</span></span>
            </summary>
        <returns><span data-ttu-id="9c746-128">署名と使用するアルゴリズムで構成されるタプル</span><span class="sxs-lookup"><span data-stu-id="9c746-128">A Tuple consisting of the signature and the algorithm used</span></span></returns>
        <remarks><span data-ttu-id="9c746-129">実装する必要があります、既定のアルゴリズムを使用して、アルゴリズムが指定されていない場合</span><span class="sxs-lookup"><span data-stu-id="9c746-129">If the algorithm is not specified, an implementation should use its default algorithm</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="UnwrapKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; UnwrapKeyAsync (byte[] encryptedKey, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; UnwrapKeyAsync(unsigned int8[] encryptedKey, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.UnwrapKeyAsync(System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function UnwrapKeyAsync (encryptedKey As Byte(), algorithm As String, token As CancellationToken) As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member UnwrapKeyAsync : byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="iKey.UnwrapKeyAsync (encryptedKey, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encryptedKey" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="encryptedKey"><span data-ttu-id="9c746-130">暗号化されたキー マテリアル</span><span class="sxs-lookup"><span data-stu-id="9c746-130">The encrypted key material</span></span></param>
        <param name="algorithm"><span data-ttu-id="9c746-131">使用するアルゴリズム</span><span class="sxs-lookup"><span data-stu-id="9c746-131">The algorithm to use</span></span></param>
        <param name="token"><span data-ttu-id="9c746-132">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="9c746-132">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="9c746-133">指定されたキー マテリアルを復号化します。</span><span class="sxs-lookup"><span data-stu-id="9c746-133">Decrypts the specified key material.</span></span>
            </summary>
        <returns><span data-ttu-id="9c746-134">復号化されたキー マテリアル</span><span class="sxs-lookup"><span data-stu-id="9c746-134">The decrypted key material</span></span></returns>
        <remarks><span data-ttu-id="9c746-135">実装する必要があります、既定のアルゴリズムを使用して、アルゴリズムが指定されていない場合</span><span class="sxs-lookup"><span data-stu-id="9c746-135">If the algorithm is not specified, an implementation should use its default algorithm</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; VerifyAsync (byte[] digest, byte[] signature, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; VerifyAsync(unsigned int8[] digest, unsigned int8[] signature, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.VerifyAsync(System.Byte[],System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function VerifyAsync (digest As Byte(), signature As Byte(), algorithm As String, token As CancellationToken) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member VerifyAsync : byte[] * byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iKey.VerifyAsync (digest, signature, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="digest"><span data-ttu-id="9c746-136">ダイジェスト</span><span class="sxs-lookup"><span data-stu-id="9c746-136">The digest</span></span></param>
        <param name="signature"><span data-ttu-id="9c746-137">署名の値</span><span class="sxs-lookup"><span data-stu-id="9c746-137">The signature value</span></span></param>
        <param name="algorithm"><span data-ttu-id="9c746-138">使用するアルゴリズム</span><span class="sxs-lookup"><span data-stu-id="9c746-138">The algorithm to use</span></span></param>
        <param name="token"><span data-ttu-id="9c746-139">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="9c746-139">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="9c746-140">指定された署名値を確認します。</span><span class="sxs-lookup"><span data-stu-id="9c746-140">Verifies the specified signature value</span></span>
            </summary>
        <returns><span data-ttu-id="9c746-141">署名の確認に成功したかどうかを示すブール値</span><span class="sxs-lookup"><span data-stu-id="9c746-141">A bool indicating whether the signature was successfully verified</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WrapKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Tuple&lt;byte[],string&gt;&gt; WrapKeyAsync (byte[] key, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Tuple`2&lt;unsigned int8[], string&gt;&gt; WrapKeyAsync(unsigned int8[] key, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.WrapKeyAsync(System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function WrapKeyAsync (key As Byte(), algorithm As String, token As CancellationToken) As Task(Of Tuple(Of Byte(), String))" />
      <MemberSignature Language="F#" Value="abstract member WrapKeyAsync : byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[] * string&gt;" Usage="iKey.WrapKeyAsync (key, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Tuple&lt;System.Byte[],System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="9c746-142">暗号化キー マテリアル</span><span class="sxs-lookup"><span data-stu-id="9c746-142">The key material to encrypt</span></span></param>
        <param name="algorithm"><span data-ttu-id="9c746-143">使用するアルゴリズム</span><span class="sxs-lookup"><span data-stu-id="9c746-143">The algorithm to use</span></span></param>
        <param name="token"><span data-ttu-id="9c746-144">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="9c746-144">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="9c746-145">指定されたキー マテリアルを暗号化します。</span><span class="sxs-lookup"><span data-stu-id="9c746-145">Encrypts the specified key material.</span></span>
            </summary>
        <returns><span data-ttu-id="9c746-146">暗号化されたキーと使用するアルゴリズムで構成されるタプル</span><span class="sxs-lookup"><span data-stu-id="9c746-146">A Tuple consisting of the encrypted key and the algorithm used</span></span></returns>
        <remarks><span data-ttu-id="9c746-147">実装する必要があります、既定のアルゴリズムを使用して、アルゴリズムが指定されていない場合</span><span class="sxs-lookup"><span data-stu-id="9c746-147">If the algorithm is not specified, an implementation should use its default algorithm</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>