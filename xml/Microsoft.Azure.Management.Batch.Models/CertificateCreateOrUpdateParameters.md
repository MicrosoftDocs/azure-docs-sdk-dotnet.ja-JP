<Type Name="CertificateCreateOrUpdateParameters" FullName="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters">
  <TypeSignature Language="C#" Value="public class CertificateCreateOrUpdateParameters : Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateCreateOrUpdateParameters extends Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateCreateOrUpdateParameters&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type CertificateCreateOrUpdateParameters = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Batch.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9ab90-101">証明書に関する情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="9ab90-101">Contains information about a certificate.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateCreateOrUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9ab90-102">CertificateCreateOrUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9ab90-102">Initializes a new instance of the CertificateCreateOrUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateCreateOrUpdateParameters (string data, string id = null, string name = null, string type = null, string etag = null, string thumbprintAlgorithm = null, string thumbprint = null, Microsoft.Azure.Management.Batch.Models.CertificateFormat format = Microsoft.Azure.Management.Batch.Models.CertificateFormat.Pfx, string password = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string data, string id, string name, string type, string etag, string thumbprintAlgorithm, string thumbprint, valuetype Microsoft.Azure.Management.Batch.Models.CertificateFormat format, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateFormat,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (data As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional etag As String = null, Optional thumbprintAlgorithm As String = null, Optional thumbprint As String = null, Optional format As CertificateFormat = Microsoft.Azure.Management.Batch.Models.CertificateFormat.Pfx, Optional password As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters : string * string * string * string * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateFormat * string -&gt; Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" Usage="new Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters (data, id, name, type, etag, thumbprintAlgorithm, thumbprint, format, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="data" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="format" Type="Microsoft.Azure.Management.Batch.Models.CertificateFormat" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="data"><span data-ttu-id="9ab90-103">証明書の base64 でエンコードされた内容。</span><span class="sxs-lookup"><span data-stu-id="9ab90-103">The base64-encoded contents of the certificate.</span></span></param>
        <param name="id"><span data-ttu-id="9ab90-104">リソースの ID。</span><span class="sxs-lookup"><span data-stu-id="9ab90-104">The ID of the resource.</span></span></param>
        <param name="name"><span data-ttu-id="9ab90-105">リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="9ab90-105">The name of the resource.</span></span></param>
        <param name="type"><span data-ttu-id="9ab90-106">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="9ab90-106">The type of the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="9ab90-107">同時実行ステートメントの使用、リソースの ETag。</span><span class="sxs-lookup"><span data-stu-id="9ab90-107">The ETag of the resource, used for concurrency statements.</span></span></param>
        <param name="thumbprintAlgorithm"><span data-ttu-id="9ab90-108">証明書のサムプリントのアルゴリズム</span><span class="sxs-lookup"><span data-stu-id="9ab90-108">The algorithm of the certificate thumbprint</span></span></param>
        <param name="thumbprint"><span data-ttu-id="9ab90-109">証明書の拇印</span><span class="sxs-lookup"><span data-stu-id="9ab90-109">The thumbprint of the certificate</span></span></param>
        <param name="format"><span data-ttu-id="9ab90-110">証明書の Cer または Pfx のいずれかの形式。</span><span class="sxs-lookup"><span data-stu-id="9ab90-110">The format of the certificate - either Pfx or Cer.</span></span> <span data-ttu-id="9ab90-111">省略した場合、既定値は Pfx にします。</span><span class="sxs-lookup"><span data-stu-id="9ab90-111">If omitted, the default is Pfx.</span></span> <span data-ttu-id="9ab90-112">使用可能な値が含まれます: 'Pfx'、'Cer'</span><span class="sxs-lookup"><span data-stu-id="9ab90-112">Possible values include: 'Pfx', 'Cer'</span></span></param>
        <param name="password"><span data-ttu-id="9ab90-113">証明書の秘密キーにアクセスするパスワードです。</span><span class="sxs-lookup"><span data-stu-id="9ab90-113">The password to access the certificate's private key.</span></span></param>
        <summary>
            <span data-ttu-id="9ab90-114">CertificateCreateOrUpdateParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9ab90-114">Initializes a new instance of the CertificateCreateOrUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public string Data { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Data" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Data" />
      <MemberSignature Language="VB.NET" Value="Public Property Data As String" />
      <MemberSignature Language="F#" Value="member this.Data : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.data")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9ab90-115">取得または証明書の base64 でエンコードされたコンテンツを設定します。</span><span class="sxs-lookup"><span data-stu-id="9ab90-115">Gets or sets the base64-encoded contents of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9ab90-116">最大サイズは、10 KB です。</span><span class="sxs-lookup"><span data-stu-id="9ab90-116">The maximum size is 10KB.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.CertificateFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.CertificateFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As CertificateFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Management.Batch.Models.CertificateFormat with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9ab90-117">取得または証明書の Cer または Pfx のいずれかの形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="9ab90-117">Gets or sets the format of the certificate - either Pfx or Cer.</span></span> <span data-ttu-id="9ab90-118">省略した場合、既定値は Pfx にします。</span><span class="sxs-lookup"><span data-stu-id="9ab90-118">If omitted, the default is Pfx.</span></span> <span data-ttu-id="9ab90-119">使用可能な値が含まれます: 'Pfx'、'Cer'</span><span class="sxs-lookup"><span data-stu-id="9ab90-119">Possible values include: 'Pfx', 'Cer'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9ab90-120">取得または証明書の秘密キーにアクセスするパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="9ab90-120">Gets or sets the password to access the certificate's private key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9ab90-121">証明書の形式が証明書の形式が cer である場合は省略する必要があります pfx である場合に必要です。</span><span class="sxs-lookup"><span data-stu-id="9ab90-121">This is required if the certificate format is pfx and must be omitted if the certificate format is cer.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9ab90-122">取得または設定、証明書の拇印</span><span class="sxs-lookup"><span data-stu-id="9ab90-122">Gets or sets the thumbprint of the certificate</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9ab90-123">これにより、名と拇印が一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9ab90-123">This must match the thumbprint from the name.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintAlgorithm">
      <MemberSignature Language="C#" Value="public string ThumbprintAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.ThumbprintAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property ThumbprintAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintAlgorithm : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.ThumbprintAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.thumbprintAlgorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9ab90-124">取得または設定、証明書のサムプリントのアルゴリズム</span><span class="sxs-lookup"><span data-stu-id="9ab90-124">Gets or sets the algorithm of the certificate thumbprint</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9ab90-125">これは、証明書名の最初の部分と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="9ab90-125">This must match the first portion of the certificate name.</span></span>
            <span data-ttu-id="9ab90-126">'SHA1' 現在必要です。</span><span class="sxs-lookup"><span data-stu-id="9ab90-126">Currently required to be 'SHA1'.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateCreateOrUpdateParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9ab90-127">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="9ab90-127">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9ab90-128">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9ab90-128">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>