<Type Name="VaultCertificate" FullName="Microsoft.Azure.Management.Compute.Models.VaultCertificate">
  <TypeSignature Language="C#" Value="public class VaultCertificate" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VaultCertificate extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VaultCertificate" />
  <TypeSignature Language="VB.NET" Value="Public Class VaultCertificate" />
  <TypeSignature Language="F#" Value="type VaultCertificate = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="56440-101">Key Vault に単一の証明書参照を記述し、VM に証明書がある必要があります。</span><span class="sxs-lookup"><span data-stu-id="56440-101">Describes a single certificate reference in a Key Vault, and where the certificate should reside on the VM.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultCertificate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VaultCertificate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="56440-102">VaultCertificate クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="56440-102">Initializes a new instance of the VaultCertificate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultCertificate (string certificateUrl = null, string certificateStore = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string certificateUrl, string certificateStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VaultCertificate.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional certificateUrl As String = null, Optional certificateStore As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VaultCertificate : string * string -&gt; Microsoft.Azure.Management.Compute.Models.VaultCertificate" Usage="new Microsoft.Azure.Management.Compute.Models.VaultCertificate (certificateUrl, certificateStore)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="certificateUrl" Type="System.String" />
        <Parameter Name="certificateStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="certificateUrl"><span data-ttu-id="56440-103">これは、シークレットとして Key Vault にアップロードされている証明書の URL です。</span><span class="sxs-lookup"><span data-stu-id="56440-103">This is the URL of a certificate that has been uploaded to Key Vault as a secret.</span></span> <span data-ttu-id="56440-104">参照してください、シークレットを Key Vault に追加すると、 [key vault にキーまたはシークレットを追加](https://docs.microsoft.com/azure/key-vault/key-vault-get-started/#add)です。</span><span class="sxs-lookup"><span data-stu-id="56440-104">For adding a secret to the Key Vault, see [Add a key or secret to the key vault](https://docs.microsoft.com/azure/key-vault/key-vault-get-started/#add).</span></span>
            <span data-ttu-id="56440-105">証明書の要件は、ユーザーがオブジェクトの次の JSON の Base64 エンコードが utf-8 でエンコードされたこのケースでは、: &lt;br&gt;&lt;br&gt; {&lt;br&gt; "data":"&lt;Base64 でエンコードされた証明&gt;"、&lt;br&gt; "dataType":"pfx"&lt;br&gt; "password":"&lt;pfx ファイル パスワード&gt;"&lt;br&gt;}</span><span class="sxs-lookup"><span data-stu-id="56440-105">In this case, your certificate needs to be It is the Base64 encoding of the following JSON Object which is encoded in UTF-8: &lt;br&gt;&lt;br&gt; {&lt;br&gt; "data":"&lt;Base64-encoded-certificate&gt;",&lt;br&gt; "dataType":"pfx",&lt;br&gt; "password":"&lt;pfx-file-password&gt;"&lt;br&gt;}</span></span></param>
        <param name="certificateStore"><span data-ttu-id="56440-106">Windows vm の場合は、証明書の追加先となる仮想マシンで、証明書ストアを指定します。</span><span class="sxs-lookup"><span data-stu-id="56440-106">For Windows VMs, specifies the certificate store on the Virtual Machine to which the certificate should be added.</span></span> <span data-ttu-id="56440-107">指定された証明書ストアは、LocalMachine アカウントでは暗黙的にします。</span><span class="sxs-lookup"><span data-stu-id="56440-107">The specified certificate store is implicitly in the LocalMachine account.</span></span> <span data-ttu-id="56440-108">&lt;ブラジル&gt;&lt;br&gt;Linux Vm の場合は、証明書ファイルがディレクトリに配置/var/lib/waagent、ファイル名を持つ&lt;UppercaseThumbprint&gt;.crt の X509 証明書のファイルと&lt;UppercaseThumbpring&gt;.prv 秘密キーにします。</span><span class="sxs-lookup"><span data-stu-id="56440-108">&lt;br&gt;&lt;br&gt;For Linux VMs, the certificate file is placed under the /var/lib/waagent directory, with the file name &lt;UppercaseThumbprint&gt;.crt for the X509 certificate file and &lt;UppercaseThumbpring&gt;.prv for private key.</span></span> <span data-ttu-id="56440-109">これらのファイルの両方が、.pem 形式です。</span><span class="sxs-lookup"><span data-stu-id="56440-109">Both of these files are .pem formatted.</span></span></param>
        <summary>
            <span data-ttu-id="56440-110">VaultCertificate クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="56440-110">Initializes a new instance of the VaultCertificate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateStore">
      <MemberSignature Language="C#" Value="public string CertificateStore { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateStore" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VaultCertificate.CertificateStore" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateStore As String" />
      <MemberSignature Language="F#" Value="member this.CertificateStore : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VaultCertificate.CertificateStore" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateStore")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="56440-111">取得、または Windows vm の設定、証明書の追加先となる仮想マシンで、証明書ストアを指定します。</span><span class="sxs-lookup"><span data-stu-id="56440-111">Gets or sets for Windows VMs, specifies the certificate store on the Virtual Machine to which the certificate should be added.</span></span> <span data-ttu-id="56440-112">指定された証明書ストアは、LocalMachine アカウントでは暗黙的にします。</span><span class="sxs-lookup"><span data-stu-id="56440-112">The specified certificate store is implicitly in the LocalMachine account.</span></span> <span data-ttu-id="56440-113">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Linux vm の場合は、証明書ファイルがディレクトリに配置/var/lib/waagent、ファイル名を持つ&amp;lt;UppercaseThumbprint&amp;gt;。crt の X509 証明書ファイルと&amp;lt;UppercaseThumbpring&amp;gt;。秘密キーの prv です。</span><span class="sxs-lookup"><span data-stu-id="56440-113">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt;For Linux VMs, the certificate file is placed under the /var/lib/waagent directory, with the file name &amp;lt;UppercaseThumbprint&amp;gt;.crt for the X509 certificate file and &amp;lt;UppercaseThumbpring&amp;gt;.prv for private key.</span></span> <span data-ttu-id="56440-114">これらのファイルの両方が、.pem 形式です。</span><span class="sxs-lookup"><span data-stu-id="56440-114">Both of these files are .pem formatted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateUrl">
      <MemberSignature Language="C#" Value="public string CertificateUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VaultCertificate.CertificateUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateUrl As String" />
      <MemberSignature Language="F#" Value="member this.CertificateUrl : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VaultCertificate.CertificateUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="56440-115">取得または設定は、シークレットとして Key Vault にアップロードされている証明書の URL になります。</span><span class="sxs-lookup"><span data-stu-id="56440-115">Gets or sets this is the URL of a certificate that has been uploaded to Key Vault as a secret.</span></span> <span data-ttu-id="56440-116">参照してください、シークレットを Key Vault に追加すると、 [key vault にキーまたはシークレットを追加](https://docs.microsoft.com/azure/key-vault/key-vault-get-started/#add)です。</span><span class="sxs-lookup"><span data-stu-id="56440-116">For adding a secret to the Key Vault, see [Add a key or secret to the key vault](https://docs.microsoft.com/azure/key-vault/key-vault-get-started/#add).</span></span>
            <span data-ttu-id="56440-117">証明書の要件は、ユーザーがオブジェクトの次の JSON の Base64 エンコードが utf-8 でエンコードされたこのケースでは、: &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;{&amp;lt; br&amp;gt;"data":"&amp;lt;Base64 でエンコードされた証明&amp;gt;"、&amp;lt; br&amp;gt;"dataType":"pfx"&amp;lt; br&amp;gt;"password":"&amp;lt; pfx ファイル パスワード&amp;gt;"&amp;lt; br&amp;gt;}</span><span class="sxs-lookup"><span data-stu-id="56440-117">In this case, your certificate needs to be It is the Base64 encoding of the following JSON Object which is encoded in UTF-8: &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; {&amp;lt;br&amp;gt; "data":"&amp;lt;Base64-encoded-certificate&amp;gt;",&amp;lt;br&amp;gt; "dataType":"pfx",&amp;lt;br&amp;gt; "password":"&amp;lt;pfx-file-password&amp;gt;"&amp;lt;br&amp;gt;}</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>