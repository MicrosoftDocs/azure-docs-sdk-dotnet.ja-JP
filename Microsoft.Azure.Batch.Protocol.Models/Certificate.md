<Type Name="Certificate" FullName="Microsoft.Azure.Batch.Protocol.Models.Certificate">
  <TypeSignature Language="C#" Value="public class Certificate" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Certificate extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.Certificate" />
  <TypeSignature Language="VB.NET" Value="Public Class Certificate" />
  <TypeSignature Language="F#" Value="type Certificate = class" />
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
            <span data-ttu-id="372a7-101">インストールされていることを証明書を使用して、計算ノードをマシンに対する操作の認証に使用することができます。</span><span class="sxs-lookup"><span data-stu-id="372a7-101">A certificate that can be installed on compute nodes and can be used to authenticate operations on the machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Certificate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.Certificate.#ctor" />
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
            <span data-ttu-id="372a7-102">証明書のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="372a7-102">Initializes a new instance of the Certificate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Certificate (string thumbprint = null, string thumbprintAlgorithm = null, string url = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; state = null, Nullable&lt;DateTime&gt; stateTransitionTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; previousState = null, Nullable&lt;DateTime&gt; previousStateTransitionTime = null, string publicData = null, Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError deleteCertificateError = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string thumbprint, string thumbprintAlgorithm, string url, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; stateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; previousState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; previousStateTransitionTime, string publicData, class Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError deleteCertificateError) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.Certificate.#ctor(System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.CertificateState},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.CertificateState},System.Nullable{System.DateTime},System.String,Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.Certificate : string * string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError -&gt; Microsoft.Azure.Batch.Protocol.Models.Certificate" Usage="new Microsoft.Azure.Batch.Protocol.Models.Certificate (thumbprint, thumbprintAlgorithm, url, state, stateTransitionTime, previousState, previousStateTransitionTime, publicData, deleteCertificateError)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt;" />
        <Parameter Name="stateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="previousState" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt;" />
        <Parameter Name="previousStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="publicData" Type="System.String" />
        <Parameter Name="deleteCertificateError" Type="Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError" />
      </Parameters>
      <Docs>
        <param name="thumbprint"><span data-ttu-id="372a7-103">証明書の X.509 サムプリント。</span><span class="sxs-lookup"><span data-stu-id="372a7-103">The X.509 thumbprint of the certificate.</span></span>
            <span data-ttu-id="372a7-104">これは、最大 40 の 16 進数字のシーケンスです。</span><span class="sxs-lookup"><span data-stu-id="372a7-104">This is a sequence of up to 40 hex digits.</span></span></param>
        <param name="thumbprintAlgorithm"><span data-ttu-id="372a7-105">サムプリントの取得に使用するアルゴリズムです。</span><span class="sxs-lookup"><span data-stu-id="372a7-105">The algorithm used to derive the thumbprint.</span></span></param>
        <param name="url"><span data-ttu-id="372a7-106">証明書の URL です。</span><span class="sxs-lookup"><span data-stu-id="372a7-106">The URL of the certificate.</span></span></param>
        <param name="state"><span data-ttu-id="372a7-107">証明書の現在の状態。</span><span class="sxs-lookup"><span data-stu-id="372a7-107">The current state of the certificate.</span></span></param>
        <param name="stateTransitionTime"><span data-ttu-id="372a7-108">証明書が、現在の状態を入力する時刻。</span><span class="sxs-lookup"><span data-stu-id="372a7-108">The time at which the certificate entered its current state.</span></span></param>
        <param name="previousState"><span data-ttu-id="372a7-109">証明書の以前の状態。</span><span class="sxs-lookup"><span data-stu-id="372a7-109">The previous state of the certificate.</span></span></param>
        <param name="previousStateTransitionTime"><span data-ttu-id="372a7-110">証明書が以前の状態を入力する時刻。</span><span class="sxs-lookup"><span data-stu-id="372a7-110">The time at which the certificate entered its previous state.</span></span></param>
        <param name="publicData"><span data-ttu-id="372a7-111">Base 64 でエンコードされた .cer ファイルとして証明書のパブリックの部分です。</span><span class="sxs-lookup"><span data-stu-id="372a7-111">The public part of the certificate as a base-64 encoded .cer file.</span></span></param>
        <param name="deleteCertificateError"><span data-ttu-id="372a7-112">この証明書を削除するのには、前回の試行で発生したエラー。</span><span class="sxs-lookup"><span data-stu-id="372a7-112">The error that occurred on the last attempt to delete this certificate.</span></span></param>
        <summary>
            <span data-ttu-id="372a7-113">証明書のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="372a7-113">Initializes a new instance of the Certificate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError DeleteCertificateError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError DeleteCertificateError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.DeleteCertificateError" />
      <MemberSignature Language="VB.NET" Value="Public Property DeleteCertificateError As DeleteCertificateError" />
      <MemberSignature Language="F#" Value="member this.DeleteCertificateError : Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.DeleteCertificateError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deleteCertificateError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="372a7-114">取得またはこの証明書を削除する最後の試行で発生したエラーを設定します。</span><span class="sxs-lookup"><span data-stu-id="372a7-114">Gets or sets the error that occurred on the last attempt to delete this certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="372a7-115">証明書が DeleteFailed 状態である場合にのみ、このプロパティが設定されます。</span><span class="sxs-lookup"><span data-stu-id="372a7-115">This property is set only if the certificate is in the DeleteFailed state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; PreviousState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public Property PreviousState As Nullable(Of CertificateState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.PreviousState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="previousState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="372a7-116">取得または証明書の以前の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="372a7-116">Gets or sets the previous state of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="372a7-117">証明書が初期のアクティブな状態にある場合、このプロパティは設定されません。</span><span class="sxs-lookup"><span data-stu-id="372a7-117">This property is not set if the certificate is in its initial active state.</span></span> <span data-ttu-id="372a7-118">使用可能な値が含まれます: 'active'、'削除'、'deleteFailed'</span><span class="sxs-lookup"><span data-stu-id="372a7-118">Possible values include: 'active', 'deleting', 'deleteFailed'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.PreviousStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="previousStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="372a7-119">取得または証明書が以前の状態を入力する時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="372a7-119">Gets or sets the time at which the certificate entered its previous state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="372a7-120">証明書が初期のアクティブな状態にある場合、このプロパティは設定されません。</span><span class="sxs-lookup"><span data-stu-id="372a7-120">This property is not set if the certificate is in its initial Active state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicData">
      <MemberSignature Language="C#" Value="public string PublicData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.PublicData" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicData As String" />
      <MemberSignature Language="F#" Value="member this.PublicData : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.PublicData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="publicData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="372a7-121">取得または base 64 でエンコードされた .cer ファイルとして証明書のパブリックの部分を設定します。</span><span class="sxs-lookup"><span data-stu-id="372a7-121">Gets or sets the public part of the certificate as a base-64 encoded .cer file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As Nullable(Of CertificateState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="372a7-122">取得または証明書の現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="372a7-122">Gets or sets the current state of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="372a7-123">使用可能な値が含まれます: 'active'、'削除'、'deleteFailed'</span><span class="sxs-lookup"><span data-stu-id="372a7-123">Possible values include: 'active', 'deleting', 'deleteFailed'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="372a7-124">取得または証明書が、現在の状態を入力するされた時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="372a7-124">Gets or sets the time at which the certificate entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.Thumbprint" />
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
            <span data-ttu-id="372a7-125">取得または証明書の X.509 拇印を設定します。</span><span class="sxs-lookup"><span data-stu-id="372a7-125">Gets or sets the X.509 thumbprint of the certificate.</span></span> <span data-ttu-id="372a7-126">これは、最大 40 の 16 進数字のシーケンスです。</span><span class="sxs-lookup"><span data-stu-id="372a7-126">This is a sequence of up to 40 hex digits.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintAlgorithm">
      <MemberSignature Language="C#" Value="public string ThumbprintAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.ThumbprintAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property ThumbprintAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintAlgorithm : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.ThumbprintAlgorithm" />
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
            <span data-ttu-id="372a7-127">取得または拇印の派生に使用するアルゴリズムを設定します。</span><span class="sxs-lookup"><span data-stu-id="372a7-127">Gets or sets the algorithm used to derive the thumbprint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="372a7-128">取得または証明書の URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="372a7-128">Gets or sets the URL of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>