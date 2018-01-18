<Type Name="CertificateBundle" FullName="Microsoft.Azure.KeyVault.Models.CertificateBundle">
  <TypeSignature Language="C#" Value="public class CertificateBundle" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateBundle extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.CertificateBundle" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateBundle" />
  <TypeSignature Language="F#" Value="type CertificateBundle = class" />
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
            <span data-ttu-id="0fd0b-101">証明書のバンドルは、(X509) 証明書とその属性で構成されます。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-101">A certificate bundle consists of a certificate (X509) plus its attributes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateBundle ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateBundle.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0fd0b-102">CertificateBundle クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-102">Initializes a new instance of the CertificateBundle class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateBundle (string id = null, string kid = null, string sid = null, byte[] x509Thumbprint = null, Microsoft.Azure.KeyVault.Models.CertificatePolicy policy = null, byte[] cer = null, string contentType = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes attributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string kid, string sid, unsigned int8[] x509Thumbprint, class Microsoft.Azure.KeyVault.Models.CertificatePolicy policy, unsigned int8[] cer, string contentType, class Microsoft.Azure.KeyVault.Models.CertificateAttributes attributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateBundle.#ctor(System.String,System.String,System.String,System.Byte[],Microsoft.Azure.KeyVault.Models.CertificatePolicy,System.Byte[],System.String,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional kid As String = null, Optional sid As String = null, Optional x509Thumbprint As Byte() = null, Optional policy As CertificatePolicy = null, Optional cer As Byte() = null, Optional contentType As String = null, Optional attributes As CertificateAttributes = null, Optional tags As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.CertificateBundle : string * string * string * byte[] * Microsoft.Azure.KeyVault.Models.CertificatePolicy * byte[] * string * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.KeyVault.Models.CertificateBundle" Usage="new Microsoft.Azure.KeyVault.Models.CertificateBundle (id, kid, sid, x509Thumbprint, policy, cer, contentType, attributes, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="kid" Type="System.String" />
        <Parameter Name="sid" Type="System.String" />
        <Parameter Name="x509Thumbprint" Type="System.Byte[]" />
        <Parameter Name="policy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="cer" Type="System.Byte[]" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="0fd0b-103">証明書の id です。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-103">The certificate id.</span></span></param>
        <param name="kid"><span data-ttu-id="0fd0b-104">キーの id です。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-104">The key id.</span></span></param>
        <param name="sid"><span data-ttu-id="0fd0b-105">シークレットの id です。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-105">The secret id.</span></span></param>
        <param name="x509Thumbprint"><span data-ttu-id="0fd0b-106">証明書の拇印です。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-106">Thumbprint of the certificate.</span></span></param>
        <param name="policy"><span data-ttu-id="0fd0b-107">管理ポリシー。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-107">The management policy.</span></span></param>
        <param name="cer"><span data-ttu-id="0fd0b-108">CER 内容の x509 証明書。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-108">CER contents of x509 certificate.</span></span></param>
        <param name="contentType"><span data-ttu-id="0fd0b-109">シークレットのコンテンツの種類。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-109">The content type of the secret.</span></span></param>
        <param name="attributes"><span data-ttu-id="0fd0b-110">証明書の属性です。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-110">The certificate attributes.</span></span></param>
        <param name="tags"><span data-ttu-id="0fd0b-111">キー/値ペアの形式でのアプリケーション固有のメタデータ</span><span class="sxs-lookup"><span data-stu-id="0fd0b-111">Application specific metadata in the form of key-value pairs</span></span></param>
        <summary>
            <span data-ttu-id="0fd0b-112">CertificateBundle クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-112">Initializes a new instance of the CertificateBundle class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Attributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.CertificateAttributes Attributes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.CertificateAttributes Attributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateBundle.Attributes" />
      <MemberSignature Language="VB.NET" Value="Public Property Attributes As CertificateAttributes" />
      <MemberSignature Language="F#" Value="member this.Attributes : Microsoft.Azure.KeyVault.Models.CertificateAttributes with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateBundle.Attributes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="attributes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.CertificateAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd0b-113">取得または証明書の属性を設定します。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-113">Gets or sets the certificate attributes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cer">
      <MemberSignature Language="C#" Value="public byte[] Cer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] Cer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateBundle.Cer" />
      <MemberSignature Language="VB.NET" Value="Public Property Cer As Byte()" />
      <MemberSignature Language="F#" Value="member this.Cer : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateBundle.Cer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd0b-114">取得または設定 CER 内容の x509 証明書。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-114">Gets or sets CER contents of x509 certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateIdentifier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.CertificateIdentifier CertificateIdentifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.CertificateIdentifier CertificateIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateBundle.CertificateIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CertificateIdentifier As CertificateIdentifier" />
      <MemberSignature Language="F#" Value="member this.CertificateIdentifier : Microsoft.Azure.KeyVault.CertificateIdentifier" Usage="Microsoft.Azure.KeyVault.Models.CertificateBundle.CertificateIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.CertificateIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd0b-115">これは、証明書の Id です。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-115">This is the Id of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateBundle.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateBundle.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="contentType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd0b-116">取得またはシークレットのコンテンツの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-116">Gets or sets the content type of the secret.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateBundle.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.KeyVault.Models.CertificateBundle.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd0b-117">証明書の id を取得します。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-117">Gets the certificate id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyIdentifier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.KeyIdentifier KeyIdentifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.KeyIdentifier KeyIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateBundle.KeyIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyIdentifier As KeyIdentifier" />
      <MemberSignature Language="F#" Value="member this.KeyIdentifier : Microsoft.Azure.KeyVault.KeyIdentifier" Usage="Microsoft.Azure.KeyVault.Models.CertificateBundle.KeyIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.KeyIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd0b-118">これは、証明書をバックアップするキーの Id です。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-118">This is the Id of the key backing the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kid">
      <MemberSignature Language="C#" Value="public string Kid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateBundle.Kid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kid As String" />
      <MemberSignature Language="F#" Value="member this.Kid : string" Usage="Microsoft.Azure.KeyVault.Models.CertificateBundle.Kid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd0b-119">キーの id を取得します。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-119">Gets the key id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Policy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.CertificatePolicy Policy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.CertificatePolicy Policy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateBundle.Policy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Policy As CertificatePolicy" />
      <MemberSignature Language="F#" Value="member this.Policy : Microsoft.Azure.KeyVault.Models.CertificatePolicy" Usage="Microsoft.Azure.KeyVault.Models.CertificateBundle.Policy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="policy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.CertificatePolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd0b-120">管理ポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-120">Gets the management policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretIdentifier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.SecretIdentifier SecretIdentifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.SecretIdentifier SecretIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateBundle.SecretIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecretIdentifier As SecretIdentifier" />
      <MemberSignature Language="F#" Value="member this.SecretIdentifier : Microsoft.Azure.KeyVault.SecretIdentifier" Usage="Microsoft.Azure.KeyVault.Models.CertificateBundle.SecretIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.SecretIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd0b-121">これは、シークレットをバックアップする証明書の Id です。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-121">This is the Id of the secret backing the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sid">
      <MemberSignature Language="C#" Value="public string Sid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateBundle.Sid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sid As String" />
      <MemberSignature Language="F#" Value="member this.Sid : string" Usage="Microsoft.Azure.KeyVault.Models.CertificateBundle.Sid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd0b-122">シークレットの id を取得します。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-122">Gets the secret id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateBundle.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.CertificateBundle.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd0b-123">取得またはキー/値ペアの形式でのアプリケーション固有のメタデータの設定</span><span class="sxs-lookup"><span data-stu-id="0fd0b-123">Gets or sets application specific metadata in the form of key-value pairs</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.CertificateBundle.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateBundle.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0fd0b-124">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-124">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0fd0b-125">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-125">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="X509Thumbprint">
      <MemberSignature Language="C#" Value="public byte[] X509Thumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] X509Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.CertificateBundle.X509Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property X509Thumbprint As Byte()" />
      <MemberSignature Language="F#" Value="member this.X509Thumbprint : byte[]" Usage="Microsoft.Azure.KeyVault.Models.CertificateBundle.X509Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="x5t")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fd0b-126">証明書の拇印を取得します。</span><span class="sxs-lookup"><span data-stu-id="0fd0b-126">Gets thumbprint of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>