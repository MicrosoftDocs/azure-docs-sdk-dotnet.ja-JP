<Type Name="RsaKey" FullName="Microsoft.Azure.KeyVault.RsaKey">
  <TypeSignature Language="C#" Value="public class RsaKey : IDisposable, Microsoft.Azure.KeyVault.Core.IKey" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RsaKey extends System.Object implements class Microsoft.Azure.KeyVault.Core.IKey, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.RsaKey" />
  <TypeSignature Language="VB.NET" Value="Public Class RsaKey&#xA;Implements IDisposable, IKey" />
  <TypeSignature Language="F#" Value="type RsaKey = class&#xA;    interface IKey&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.KeyVault.Core.IKey</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="6c3ef-101">RSA キーです。</span><span class="sxs-lookup"><span data-stu-id="6c3ef-101">An RSA key.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RsaKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.RsaKey.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6c3ef-102">コンス トラクターは、GUID 識別子を 2048 ビットのキーを作成します。</span><span class="sxs-lookup"><span data-stu-id="6c3ef-102">Constructor, creates a 2048 bit key with a GUID identifier.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RsaKey (string kid);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string kid) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.RsaKey.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (kid As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.RsaKey : string -&gt; Microsoft.Azure.KeyVault.RsaKey" Usage="new Microsoft.Azure.KeyVault.RsaKey kid" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kid" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="kid"><span data-ttu-id="6c3ef-103">使用するキー識別子</span><span class="sxs-lookup"><span data-stu-id="6c3ef-103">The key identifier to use</span></span></param>
        <summary>
            <span data-ttu-id="6c3ef-104">コンス トラクターでは、2048 ビットの RSA キーを作成します。</span><span class="sxs-lookup"><span data-stu-id="6c3ef-104">Constructor, creates a 2048 bit RSA key.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RsaKey (string kid, int keySize);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string kid, int32 keySize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.RsaKey.#ctor(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (kid As String, keySize As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.RsaKey : string * int -&gt; Microsoft.Azure.KeyVault.RsaKey" Usage="new Microsoft.Azure.KeyVault.RsaKey (kid, keySize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kid" Type="System.String" />
        <Parameter Name="keySize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="kid"><span data-ttu-id="6c3ef-105">使用するキー識別子</span><span class="sxs-lookup"><span data-stu-id="6c3ef-105">The key identifier to use</span></span></param>
        <param name="keySize"><span data-ttu-id="6c3ef-106">キーのサイズ</span><span class="sxs-lookup"><span data-stu-id="6c3ef-106">The size of the key</span></span></param>
        <summary>
            <span data-ttu-id="6c3ef-107">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="6c3ef-107">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RsaKey (string kid, System.Security.Cryptography.RSA csp);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string kid, class System.Security.Cryptography.RSA csp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.RsaKey.#ctor(System.String,System.Security.Cryptography.RSA)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (kid As String, csp As RSA)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.RsaKey : string * System.Security.Cryptography.RSA -&gt; Microsoft.Azure.KeyVault.RsaKey" Usage="new Microsoft.Azure.KeyVault.RsaKey (kid, csp)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kid" Type="System.String" />
        <Parameter Name="csp" Type="System.Security.Cryptography.RSA" />
      </Parameters>
      <Docs>
        <param name="kid"><span data-ttu-id="6c3ef-108">使用するキー識別子</span><span class="sxs-lookup"><span data-stu-id="6c3ef-108">The key identifier to use</span></span></param>
        <param name="csp"><span data-ttu-id="6c3ef-109">キーの RSA オブジェクト</span><span class="sxs-lookup"><span data-stu-id="6c3ef-109">The RSA object for the key</span></span></param>
        <summary>
            <span data-ttu-id="6c3ef-110">コンストラクターです。</span><span class="sxs-lookup"><span data-stu-id="6c3ef-110">Constructor.</span></span>
            </summary>
        <remarks><span data-ttu-id="6c3ef-111">RSA オブジェクトは、IDisposable、このクラスは、RSA オブジェクトへの参照を保持するが、破棄しません、このコンス トラクターの呼び出し元がこのパラメーターの有効期間を担当します。</span><span class="sxs-lookup"><span data-stu-id="6c3ef-111">The RSA object is IDisposable, this class will hold a reference to the RSA object but will not dispose it, the caller of this constructor is responsible for the lifetime of this parameter.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RsaKey (string kid, System.Security.Cryptography.RSAParameters keyParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string kid, valuetype System.Security.Cryptography.RSAParameters keyParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.RsaKey.#ctor(System.String,System.Security.Cryptography.RSAParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (kid As String, keyParameters As RSAParameters)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.RsaKey : string * System.Security.Cryptography.RSAParameters -&gt; Microsoft.Azure.KeyVault.RsaKey" Usage="new Microsoft.Azure.KeyVault.RsaKey (kid, keyParameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kid" Type="System.String" />
        <Parameter Name="keyParameters" Type="System.Security.Cryptography.RSAParameters" />
      </Parameters>
      <Docs>
        <param name="kid"><span data-ttu-id="6c3ef-112">使用するキー識別子</span><span class="sxs-lookup"><span data-stu-id="6c3ef-112">The key identifier to use</span></span></param>
        <param name="keyParameters"><span data-ttu-id="6c3ef-113">キーの RSA パラメーター</span><span class="sxs-lookup"><span data-stu-id="6c3ef-113">The RSA parameters for the key</span></span></param>
        <summary>
            <span data-ttu-id="6c3ef-114">コンストラクター</span><span class="sxs-lookup"><span data-stu-id="6c3ef-114">Constructor</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; DecryptAsync (byte[] ciphertext, byte[] iv, byte[] authenticationData = null, byte[] authenticationTag = null, string algorithm = &quot;RSA-OAEP&quot;, System.Threading.CancellationToken token = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; DecryptAsync(unsigned int8[] ciphertext, unsigned int8[] iv, unsigned int8[] authenticationData, unsigned int8[] authenticationTag, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.RsaKey.DecryptAsync(System.Byte[],System.Byte[],System.Byte[],System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function DecryptAsync (ciphertext As Byte(), iv As Byte(), Optional authenticationData As Byte() = null, Optional authenticationTag As Byte() = null, Optional algorithm As String = &quot;RSA-OAEP&quot;, Optional token As CancellationToken = null) As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member DecryptAsync : byte[] * byte[] * byte[] * byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;&#xA;override this.DecryptAsync : byte[] * byte[] * byte[] * byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="rsaKey.DecryptAsync (ciphertext, iv, authenticationData, authenticationTag, algorithm, token)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.Core.IKey.DecryptAsync(System.Byte[],System.Byte[],System.Byte[],System.Byte[],System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
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
        <param name="ciphertext">To be added.</param>
        <param name="iv">To be added.</param>
        <param name="authenticationData">To be added.</param>
        <param name="authenticationTag">To be added.</param>
        <param name="algorithm">To be added.</param>
        <param name="token">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultEncryptionAlgorithm">
      <MemberSignature Language="C#" Value="public string DefaultEncryptionAlgorithm { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultEncryptionAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.RsaKey.DefaultEncryptionAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultEncryptionAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.DefaultEncryptionAlgorithm : string" Usage="Microsoft.Azure.KeyVault.RsaKey.DefaultEncryptionAlgorithm" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.KeyVault.Core.IKey.DefaultEncryptionAlgorithm</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultKeyWrapAlgorithm">
      <MemberSignature Language="C#" Value="public string DefaultKeyWrapAlgorithm { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultKeyWrapAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.RsaKey.DefaultKeyWrapAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultKeyWrapAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.DefaultKeyWrapAlgorithm : string" Usage="Microsoft.Azure.KeyVault.RsaKey.DefaultKeyWrapAlgorithm" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.KeyVault.Core.IKey.DefaultKeyWrapAlgorithm</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultSignatureAlgorithm">
      <MemberSignature Language="C#" Value="public string DefaultSignatureAlgorithm { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultSignatureAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.RsaKey.DefaultSignatureAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultSignatureAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.DefaultSignatureAlgorithm : string" Usage="Microsoft.Azure.KeyVault.RsaKey.DefaultSignatureAlgorithm" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.KeyVault.Core.IKey.DefaultSignatureAlgorithm</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.RsaKey.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="rsaKey.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.RsaKey.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="rsaKey.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Tuple&lt;byte[],byte[],string&gt;&gt; EncryptAsync (byte[] plaintext, byte[] iv = null, byte[] authenticationData = null, string algorithm = &quot;RSA-OAEP&quot;, System.Threading.CancellationToken token = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Tuple`3&lt;unsigned int8[], unsigned int8[], string&gt;&gt; EncryptAsync(unsigned int8[] plaintext, unsigned int8[] iv, unsigned int8[] authenticationData, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.RsaKey.EncryptAsync(System.Byte[],System.Byte[],System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function EncryptAsync (plaintext As Byte(), Optional iv As Byte() = null, Optional authenticationData As Byte() = null, Optional algorithm As String = &quot;RSA-OAEP&quot;, Optional token As CancellationToken = null) As Task(Of Tuple(Of Byte(), Byte(), String))" />
      <MemberSignature Language="F#" Value="abstract member EncryptAsync : byte[] * byte[] * byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[] * byte[] * string&gt;&#xA;override this.EncryptAsync : byte[] * byte[] * byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[] * byte[] * string&gt;" Usage="rsaKey.EncryptAsync (plaintext, iv, authenticationData, algorithm, token)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.Core.IKey.EncryptAsync(System.Byte[],System.Byte[],System.Byte[],System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
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
        <param name="plaintext">To be added.</param>
        <param name="iv">To be added.</param>
        <param name="authenticationData">To be added.</param>
        <param name="algorithm">To be added.</param>
        <param name="token">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeySize1024">
      <MemberSignature Language="C#" Value="public const int KeySize1024 = 1024;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int32 KeySize1024 = (1024)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.RsaKey.KeySize1024" />
      <MemberSignature Language="VB.NET" Value="Public Const KeySize1024 As Integer  = 1024" />
      <MemberSignature Language="F#" Value="val mutable KeySize1024 : int" Usage="Microsoft.Azure.KeyVault.RsaKey.KeySize1024" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <MemberValue>1024</MemberValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeySize2048">
      <MemberSignature Language="C#" Value="public const int KeySize2048 = 2048;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int32 KeySize2048 = (2048)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.KeyVault.RsaKey.KeySize2048" />
      <MemberSignature Language="VB.NET" Value="Public Const KeySize2048 As Integer  = 2048" />
      <MemberSignature Language="F#" Value="val mutable KeySize2048 : int" Usage="Microsoft.Azure.KeyVault.RsaKey.KeySize2048" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <MemberValue>2048</MemberValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kid">
      <MemberSignature Language="C#" Value="public string Kid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.RsaKey.Kid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kid As String" />
      <MemberSignature Language="F#" Value="member this.Kid : string" Usage="Microsoft.Azure.KeyVault.RsaKey.Kid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6c3ef-115">キー識別子</span><span class="sxs-lookup"><span data-stu-id="6c3ef-115">Key Identifier</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Tuple&lt;byte[],string&gt;&gt; SignAsync (byte[] digest, string algorithm, System.Threading.CancellationToken token = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Tuple`2&lt;unsigned int8[], string&gt;&gt; SignAsync(unsigned int8[] digest, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.RsaKey.SignAsync(System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function SignAsync (digest As Byte(), algorithm As String, Optional token As CancellationToken = null) As Task(Of Tuple(Of Byte(), String))" />
      <MemberSignature Language="F#" Value="abstract member SignAsync : byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[] * string&gt;&#xA;override this.SignAsync : byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[] * string&gt;" Usage="rsaKey.SignAsync (digest, algorithm, token)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.Core.IKey.SignAsync(System.Byte[],System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
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
        <param name="digest">To be added.</param>
        <param name="algorithm">To be added.</param>
        <param name="token">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnwrapKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; UnwrapKeyAsync (byte[] encryptedKey, string algorithm = &quot;RSA-OAEP&quot;, System.Threading.CancellationToken token = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; UnwrapKeyAsync(unsigned int8[] encryptedKey, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.RsaKey.UnwrapKeyAsync(System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function UnwrapKeyAsync (encryptedKey As Byte(), Optional algorithm As String = &quot;RSA-OAEP&quot;, Optional token As CancellationToken = null) As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member UnwrapKeyAsync : byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;&#xA;override this.UnwrapKeyAsync : byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="rsaKey.UnwrapKeyAsync (encryptedKey, algorithm, token)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.Core.IKey.UnwrapKeyAsync(System.Byte[],System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
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
        <param name="encryptedKey">To be added.</param>
        <param name="algorithm">To be added.</param>
        <param name="token">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; VerifyAsync (byte[] digest, byte[] signature, string algorithm, System.Threading.CancellationToken token = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; VerifyAsync(unsigned int8[] digest, unsigned int8[] signature, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.RsaKey.VerifyAsync(System.Byte[],System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function VerifyAsync (digest As Byte(), signature As Byte(), algorithm As String, Optional token As CancellationToken = null) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member VerifyAsync : byte[] * byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.VerifyAsync : byte[] * byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="rsaKey.VerifyAsync (digest, signature, algorithm, token)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.Core.IKey.VerifyAsync(System.Byte[],System.Byte[],System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
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
        <param name="digest">To be added.</param>
        <param name="signature">To be added.</param>
        <param name="algorithm">To be added.</param>
        <param name="token">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WrapKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Tuple&lt;byte[],string&gt;&gt; WrapKeyAsync (byte[] key, string algorithm = &quot;RSA-OAEP&quot;, System.Threading.CancellationToken token = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Tuple`2&lt;unsigned int8[], string&gt;&gt; WrapKeyAsync(unsigned int8[] key, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.RsaKey.WrapKeyAsync(System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function WrapKeyAsync (key As Byte(), Optional algorithm As String = &quot;RSA-OAEP&quot;, Optional token As CancellationToken = null) As Task(Of Tuple(Of Byte(), String))" />
      <MemberSignature Language="F#" Value="abstract member WrapKeyAsync : byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[] * string&gt;&#xA;override this.WrapKeyAsync : byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[] * string&gt;" Usage="rsaKey.WrapKeyAsync (key, algorithm, token)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.Core.IKey.WrapKeyAsync(System.Byte[],System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
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
        <param name="key">To be added.</param>
        <param name="algorithm">To be added.</param>
        <param name="token">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>