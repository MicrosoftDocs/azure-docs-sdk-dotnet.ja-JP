<Type Name="FileGetFromComputeNodeOptions" FullName="Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions">
  <TypeSignature Language="C#" Value="public class FileGetFromComputeNodeOptions : Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileGetFromComputeNodeOptions extends System.Object implements class Microsoft.Azure.Batch.Protocol.Models.IOptions, class Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class FileGetFromComputeNodeOptions&#xA;Implements ITimeoutOptions" />
  <TypeSignature Language="F#" Value="type FileGetFromComputeNodeOptions = class&#xA;    interface ITimeoutOptions&#xA;    interface IOptions" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="c84ff-101">GetFromComputeNode 操作に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c84ff-101">Additional parameters for GetFromComputeNode operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileGetFromComputeNodeOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions.#ctor" />
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
            <span data-ttu-id="c84ff-102">FileGetFromComputeNodeOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c84ff-102">Initializes a new instance of the FileGetFromComputeNodeOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileGetFromComputeNodeOptions (Nullable&lt;int&gt; timeout = null, Nullable&lt;Guid&gt; clientRequestId = null, Nullable&lt;bool&gt; returnClientRequestId = null, Nullable&lt;DateTime&gt; ocpDate = null, string ocpRange = null, Nullable&lt;DateTime&gt; ifModifiedSince = null, Nullable&lt;DateTime&gt; ifUnmodifiedSince = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; clientRequestId, valuetype System.Nullable`1&lt;bool&gt; returnClientRequestId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ocpDate, string ocpRange, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ifModifiedSince, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ifUnmodifiedSince) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions.#ctor(System.Nullable{System.Int32},System.Nullable{System.Guid},System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timeout As Nullable(Of Integer) = null, Optional clientRequestId As Nullable(Of Guid) = null, Optional returnClientRequestId As Nullable(Of Boolean) = null, Optional ocpDate As Nullable(Of DateTime) = null, Optional ocpRange As String = null, Optional ifModifiedSince As Nullable(Of DateTime) = null, Optional ifUnmodifiedSince As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions : Nullable&lt;int&gt; * Nullable&lt;Guid&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions" Usage="new Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions (timeout, clientRequestId, returnClientRequestId, ocpDate, ocpRange, ifModifiedSince, ifUnmodifiedSince)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="clientRequestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="returnClientRequestId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ocpDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ocpRange" Type="System.String" />
        <Parameter Name="ifModifiedSince" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ifUnmodifiedSince" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="c84ff-103">最大時間を秒単位で、要求の処理に、サーバーが費やすことができます。</span><span class="sxs-lookup"><span data-stu-id="c84ff-103">The maximum time that the server can spend processing the request, in seconds.</span></span> <span data-ttu-id="c84ff-104">既定値は 30 秒です。</span><span class="sxs-lookup"><span data-stu-id="c84ff-104">The default is 30 seconds.</span></span></param>
        <param name="clientRequestId"><span data-ttu-id="c84ff-105">例: 9C4D50EE 2 次元 56、中かっこなどの装飾なしの GUID の形式で、呼び出し元によって生成された要求 id-4 CD 3-8152-34347DC9F2B0 です。</span><span class="sxs-lookup"><span data-stu-id="c84ff-105">The caller-generated request identity, in the form of a GUID with no decoration such as curly braces, e.g. 9C4D50EE-2D56-4CD3-8152-34347DC9F2B0.</span></span></param>
        <param name="returnClientRequestId"><span data-ttu-id="c84ff-106">サーバーが応答でクライアント要求 id を返すかどうか。</span><span class="sxs-lookup"><span data-stu-id="c84ff-106">Whether the server should return the client-request-id in the response.</span></span></param>
        <param name="ocpDate"><span data-ttu-id="c84ff-107">要求が発行された時刻。</span><span class="sxs-lookup"><span data-stu-id="c84ff-107">The time the request was issued.</span></span> <span data-ttu-id="c84ff-108">クライアント ライブラリ通常この設定を現在のシステム クロック時間。これを明示的に設定、REST API を直接呼び出す場合。</span><span class="sxs-lookup"><span data-stu-id="c84ff-108">Client libraries typically set this to the current system clock time; set it explicitly if you are calling the REST API directly.</span></span></param>
        <param name="ocpRange"><span data-ttu-id="c84ff-109">取得するバイトの範囲です。</span><span class="sxs-lookup"><span data-stu-id="c84ff-109">The byte range to be retrieved.</span></span> <span data-ttu-id="c84ff-110">既定では、ファイル全体を取得します。</span><span class="sxs-lookup"><span data-stu-id="c84ff-110">The default is to retrieve the entire file.</span></span> <span data-ttu-id="c84ff-111">形式はバイト startRange endRange を = です。</span><span class="sxs-lookup"><span data-stu-id="c84ff-111">The format is bytes=startRange-endRange.</span></span></param>
        <param name="ifModifiedSince"><span data-ttu-id="c84ff-112">クライアントに既知のリソースの最終更新時刻を示すタイムスタンプです。</span><span class="sxs-lookup"><span data-stu-id="c84ff-112">A timestamp indicating the last modified time of the resource known to the client.</span></span> <span data-ttu-id="c84ff-113">指定した時刻以降、サービス上のリソースが変更された場合にのみ、操作が実行されます。</span><span class="sxs-lookup"><span data-stu-id="c84ff-113">The operation will be performed only if the resource on the service has been modified since the specified time.</span></span></param>
        <param name="ifUnmodifiedSince"><span data-ttu-id="c84ff-114">クライアントに既知のリソースの最終更新時刻を示すタイムスタンプです。</span><span class="sxs-lookup"><span data-stu-id="c84ff-114">A timestamp indicating the last modified time of the resource known to the client.</span></span> <span data-ttu-id="c84ff-115">指定した時刻以降、サービス上のリソースが変更されていない場合にのみ、操作が実行されます。</span><span class="sxs-lookup"><span data-stu-id="c84ff-115">The operation will be performed only if the resource on the service has not been modified since the specified time.</span></span></param>
        <summary>
            <span data-ttu-id="c84ff-116">FileGetFromComputeNodeOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c84ff-116">Initializes a new instance of the FileGetFromComputeNodeOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions.ClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c84ff-117">例: 9C4D50EE 2 次元 56、中かっこなどの装飾なしの GUID の形式では呼び出し元によって生成された要求 id が設定を取得または -4 CD 3-8152-34347DC9F2B0 です。</span><span class="sxs-lookup"><span data-stu-id="c84ff-117">Gets or sets the caller-generated request identity, in the form of a GUID with no decoration such as curly braces, e.g. 9C4D50EE-2D56-4CD3-8152-34347DC9F2B0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfModifiedSince">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; IfModifiedSince { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; IfModifiedSince" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions.IfModifiedSince" />
      <MemberSignature Language="VB.NET" Value="Public Property IfModifiedSince As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.IfModifiedSince : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions.IfModifiedSince" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c84ff-118">取得またはクライアントに既知のリソースの最終更新時刻を示すタイムスタンプを設定します。</span><span class="sxs-lookup"><span data-stu-id="c84ff-118">Gets or sets a timestamp indicating the last modified time of the resource known to the client.</span></span> <span data-ttu-id="c84ff-119">指定した時刻以降、サービス上のリソースが変更された場合にのみ、操作が実行されます。</span><span class="sxs-lookup"><span data-stu-id="c84ff-119">The operation will be performed only if the resource on the service has been modified since the specified time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfUnmodifiedSince">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; IfUnmodifiedSince { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; IfUnmodifiedSince" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions.IfUnmodifiedSince" />
      <MemberSignature Language="VB.NET" Value="Public Property IfUnmodifiedSince As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.IfUnmodifiedSince : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions.IfUnmodifiedSince" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c84ff-120">取得またはクライアントに既知のリソースの最終更新時刻を示すタイムスタンプを設定します。</span><span class="sxs-lookup"><span data-stu-id="c84ff-120">Gets or sets a timestamp indicating the last modified time of the resource known to the client.</span></span> <span data-ttu-id="c84ff-121">指定した時刻以降、サービス上のリソースが変更されていない場合にのみ、操作が実行されます。</span><span class="sxs-lookup"><span data-stu-id="c84ff-121">The operation will be performed only if the resource on the service has not been modified since the specified time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OcpDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OcpDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions.OcpDate" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OcpDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions.OcpDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c84ff-122">取得または要求が発行された時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="c84ff-122">Gets or sets the time the request was issued.</span></span> <span data-ttu-id="c84ff-123">クライアント ライブラリ通常この設定を現在のシステム クロック時間。これを明示的に設定、REST API を直接呼び出す場合。</span><span class="sxs-lookup"><span data-stu-id="c84ff-123">Client libraries typically set this to the current system clock time; set it explicitly if you are calling the REST API directly.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpRange">
      <MemberSignature Language="C#" Value="public string OcpRange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OcpRange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions.OcpRange" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpRange As String" />
      <MemberSignature Language="F#" Value="member this.OcpRange : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions.OcpRange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c84ff-124">取得または取得するバイトの範囲を設定します。</span><span class="sxs-lookup"><span data-stu-id="c84ff-124">Gets or sets the byte range to be retrieved.</span></span> <span data-ttu-id="c84ff-125">既定では、ファイル全体を取得します。</span><span class="sxs-lookup"><span data-stu-id="c84ff-125">The default is to retrieve the entire file.</span></span> <span data-ttu-id="c84ff-126">形式はバイト startRange endRange を = です。</span><span class="sxs-lookup"><span data-stu-id="c84ff-126">The format is bytes=startRange-endRange.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReturnClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReturnClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions.ReturnClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReturnClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReturnClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions.ReturnClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ReturnClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c84ff-127">取得またはサーバーが応答でクライアント要求 id を返すかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="c84ff-127">Gets or sets whether the server should return the client-request-id in the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Timeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Timeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions.Timeout" />
      <MemberSignature Language="VB.NET" Value="Public Property Timeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Timeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromComputeNodeOptions.Timeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions.Timeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c84ff-128">取得または設定の最大時間 (秒)、要求の処理に、サーバーが費やすことができます。</span><span class="sxs-lookup"><span data-stu-id="c84ff-128">Gets or sets the maximum time that the server can spend processing the request, in seconds.</span></span> <span data-ttu-id="c84ff-129">既定値は 30 秒です。</span><span class="sxs-lookup"><span data-stu-id="c84ff-129">The default is 30 seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>