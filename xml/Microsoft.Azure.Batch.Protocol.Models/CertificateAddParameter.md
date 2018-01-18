<Type Name="CertificateAddParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter">
  <TypeSignature Language="C#" Value="public class CertificateAddParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateAddParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateAddParameter" />
  <TypeSignature Language="F#" Value="type CertificateAddParameter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c6087-101">インストールされていることを証明書を使用して、計算ノードをマシンに対する操作の認証に使用することができます。</span><span class="sxs-lookup"><span data-stu-id="c6087-101">A certificate that can be installed on compute nodes and can be used to authenticate operations on the machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateAddParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c6087-102">CertificateAddParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c6087-102">Initializes a new instance of the CertificateAddParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateAddParameter (string thumbprint, string thumbprintAlgorithm, string data, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateFormat&gt; certificateFormat = null, string password = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string thumbprint, string thumbprintAlgorithm, string data, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateFormat&gt; certificateFormat, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.#ctor(System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.CertificateFormat},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (thumbprint As String, thumbprintAlgorithm As String, data As String, Optional certificateFormat As Nullable(Of CertificateFormat) = null, Optional password As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter : string * string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateFormat&gt; * string -&gt; Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter (thumbprint, thumbprintAlgorithm, data, certificateFormat, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="data" Type="System.String" />
        <Parameter Name="certificateFormat" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateFormat&gt;" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="thumbprint"><span data-ttu-id="c6087-103">証明書の X.509 サムプリント。</span><span class="sxs-lookup"><span data-stu-id="c6087-103">The X.509 thumbprint of the certificate.</span></span>
            <span data-ttu-id="c6087-104">これは最大 40 の 16 進数字のシーケンス (スペースを含めることがありますが、これらが削除されます)。</span><span class="sxs-lookup"><span data-stu-id="c6087-104">This is a sequence of up to 40 hex digits (it may include spaces but these are removed).</span></span></param>
        <param name="thumbprintAlgorithm"><span data-ttu-id="c6087-105">サムプリントの取得に使用するアルゴリズムです。</span><span class="sxs-lookup"><span data-stu-id="c6087-105">The algorithm used to derive the thumbprint.</span></span> <span data-ttu-id="c6087-106">これには、sha1 があります。</span><span class="sxs-lookup"><span data-stu-id="c6087-106">This must be sha1.</span></span></param>
        <param name="data"><span data-ttu-id="c6087-107">証明書の base64 でエンコードされた内容。</span><span class="sxs-lookup"><span data-stu-id="c6087-107">The base64-encoded contents of the certificate.</span></span>
            <span data-ttu-id="c6087-108">最大サイズは、10 KB です。</span><span class="sxs-lookup"><span data-stu-id="c6087-108">The maximum size is 10KB.</span></span></param>
        <param name="certificateFormat"><span data-ttu-id="c6087-109">証明書のデータの形式です。</span><span class="sxs-lookup"><span data-stu-id="c6087-109">The format of the certificate data.</span></span></param>
        <param name="password"><span data-ttu-id="c6087-110">証明書の秘密キーにアクセスするパスワードです。</span><span class="sxs-lookup"><span data-stu-id="c6087-110">The password to access the certificate's private key.</span></span></param>
        <summary>
            <span data-ttu-id="c6087-111">CertificateAddParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c6087-111">Initializes a new instance of the CertificateAddParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateFormat">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateFormat&gt; CertificateFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateFormat&gt; CertificateFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.CertificateFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateFormat As Nullable(Of CertificateFormat)" />
      <MemberSignature Language="F#" Value="member this.CertificateFormat : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateFormat&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.CertificateFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateFormat&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6087-112">取得または証明書のデータの書式を設定します。</span><span class="sxs-lookup"><span data-stu-id="c6087-112">Gets or sets the format of the certificate data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c6087-113">使用可能な値が含まれます: 'pfx'、'cer'</span><span class="sxs-lookup"><span data-stu-id="c6087-113">Possible values include: 'pfx', 'cer'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public string Data { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Data" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.Data" />
      <MemberSignature Language="VB.NET" Value="Public Property Data As String" />
      <MemberSignature Language="F#" Value="member this.Data : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.Data" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="data")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6087-114">取得または証明書の base64 でエンコードされたコンテンツを設定します。</span><span class="sxs-lookup"><span data-stu-id="c6087-114">Gets or sets the base64-encoded contents of the certificate.</span></span> <span data-ttu-id="c6087-115">最大サイズは、10 KB です。</span><span class="sxs-lookup"><span data-stu-id="c6087-115">The maximum size is 10KB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6087-116">取得または証明書の秘密キーにアクセスするパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="c6087-116">Gets or sets the password to access the certificate's private key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c6087-117">証明書の形式が pfx である場合、この機能が必要です。</span><span class="sxs-lookup"><span data-stu-id="c6087-117">This is required if the certificate format is pfx.</span></span> <span data-ttu-id="c6087-118">証明書の形式が cer である場合は、これを省略する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c6087-118">It should be omitted if the certificate format is cer.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6087-119">取得または証明書の X.509 拇印を設定します。</span><span class="sxs-lookup"><span data-stu-id="c6087-119">Gets or sets the X.509 thumbprint of the certificate.</span></span> <span data-ttu-id="c6087-120">これは最大 40 の 16 進数字のシーケンス (スペースを含めることがありますが、これらが削除されます)。</span><span class="sxs-lookup"><span data-stu-id="c6087-120">This is a sequence of up to 40 hex digits (it may include spaces but these are removed).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintAlgorithm">
      <MemberSignature Language="C#" Value="public string ThumbprintAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.ThumbprintAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property ThumbprintAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintAlgorithm : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.ThumbprintAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="thumbprintAlgorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6087-121">取得または拇印の派生に使用するアルゴリズムを設定します。</span><span class="sxs-lookup"><span data-stu-id="c6087-121">Gets or sets the algorithm used to derive the thumbprint.</span></span> <span data-ttu-id="c6087-122">これには、sha1 があります。</span><span class="sxs-lookup"><span data-stu-id="c6087-122">This must be sha1.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificateAddParameter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c6087-123">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="c6087-123">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c6087-124">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c6087-124">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>