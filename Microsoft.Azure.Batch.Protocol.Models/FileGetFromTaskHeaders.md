<Type Name="FileGetFromTaskHeaders" FullName="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders">
  <TypeSignature Language="C#" Value="public class FileGetFromTaskHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileGetFromTaskHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class FileGetFromTaskHeaders" />
  <TypeSignature Language="F#" Value="type FileGetFromTaskHeaders = class&#xA;    interface IProtocolNodeFile" />
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
            <span data-ttu-id="3da46-101">GetFromTask 操作のヘッダーを定義します。</span><span class="sxs-lookup"><span data-stu-id="3da46-101">Defines headers for GetFromTask operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileGetFromTaskHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.#ctor" />
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
            <span data-ttu-id="3da46-102">FileGetFromTaskHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3da46-102">Initializes a new instance of the FileGetFromTaskHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileGetFromTaskHeaders (Nullable&lt;Guid&gt; clientRequestId = null, Nullable&lt;Guid&gt; requestId = null, string eTag = null, Nullable&lt;DateTime&gt; lastModified = null, Nullable&lt;DateTime&gt; ocpCreationTime = null, Nullable&lt;bool&gt; ocpBatchFileIsdirectory = null, string ocpBatchFileUrl = null, string ocpBatchFileMode = null, string contentType = null, Nullable&lt;long&gt; contentLength = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; clientRequestId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; requestId, string eTag, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ocpCreationTime, valuetype System.Nullable`1&lt;bool&gt; ocpBatchFileIsdirectory, string ocpBatchFileUrl, string ocpBatchFileMode, string contentType, valuetype System.Nullable`1&lt;int64&gt; contentLength) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.#ctor(System.Nullable{System.Guid},System.Nullable{System.Guid},System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Boolean},System.String,System.String,System.String,System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientRequestId As Nullable(Of Guid) = null, Optional requestId As Nullable(Of Guid) = null, Optional eTag As String = null, Optional lastModified As Nullable(Of DateTime) = null, Optional ocpCreationTime As Nullable(Of DateTime) = null, Optional ocpBatchFileIsdirectory As Nullable(Of Boolean) = null, Optional ocpBatchFileUrl As String = null, Optional ocpBatchFileMode As String = null, Optional contentType As String = null, Optional contentLength As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders : Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;bool&gt; * string * string * string * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders" Usage="new Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders (clientRequestId, requestId, eTag, lastModified, ocpCreationTime, ocpBatchFileIsdirectory, ocpBatchFileUrl, ocpBatchFileMode, contentType, contentLength)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientRequestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="requestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ocpCreationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ocpBatchFileIsdirectory" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ocpBatchFileUrl" Type="System.String" />
        <Parameter Name="ocpBatchFileMode" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="contentLength" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="clientRequestId"><span data-ttu-id="3da46-103">クライアント要求 id 要求時にクライアントによって指定します。</span><span class="sxs-lookup"><span data-stu-id="3da46-103">The client-request-id provided by the client during the request.</span></span> <span data-ttu-id="3da46-104">これが返されますの戻り値クライアント要求 id パラメーターを設定した場合にのみ true に設定します。</span><span class="sxs-lookup"><span data-stu-id="3da46-104">This will be returned only if the return-client-request-id parameter was set to true.</span></span></param>
        <param name="requestId"><span data-ttu-id="3da46-105">バッチ サービスに対して行った要求に対して一意の識別子。</span><span class="sxs-lookup"><span data-stu-id="3da46-105">A unique identifier for the request that was made to the Batch service.</span></span> <span data-ttu-id="3da46-106">要求の形式が正しいにもかかわらず要求が常に失敗する場合は、この値を使用して Microsoft にエラーを報告することができます。</span><span class="sxs-lookup"><span data-stu-id="3da46-106">If a request is consistently failing and you have verified that the request is properly formulated, you may use this value to report the error to Microsoft.</span></span> <span data-ttu-id="3da46-107">レポートでは、値を含める、この要求 ID のおおよその時間、要求が行われたことを対象となる要求が行われた、Batch アカウントおよびアカウントに配置する地域。</span><span class="sxs-lookup"><span data-stu-id="3da46-107">In your report, include the value of this request ID, the approximate time that the request was made, the Batch account against which the request was made, and the region that account resides in.</span></span></param>
        <param name="eTag"><span data-ttu-id="3da46-108">ETag HTTP 応答ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="3da46-108">The ETag HTTP response header.</span></span> <span data-ttu-id="3da46-109">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="3da46-109">This is an opaque string.</span></span> <span data-ttu-id="3da46-110">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="3da46-110">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="3da46-111">具体的には、いずれかの場合-変更のため、場合の未変更の状態のため、If-match または [なし]-If-match ヘッダーに ETag を渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="3da46-111">In particular, you can pass the ETag to one of the If-Modified-Since, If-Unmodified-Since, If-Match or If-None-Match headers.</span></span></param>
        <param name="lastModified"><span data-ttu-id="3da46-112">リソースの最終更新日時。</span><span class="sxs-lookup"><span data-stu-id="3da46-112">The time at which the resource was last modified.</span></span></param>
        <param name="ocpCreationTime"><span data-ttu-id="3da46-113">ファイルの作成時刻。</span><span class="sxs-lookup"><span data-stu-id="3da46-113">The file creation time.</span></span></param>
        <param name="ocpBatchFileIsdirectory"><span data-ttu-id="3da46-114">かどうか、オブジェクトは、ディレクトリを表します。</span><span class="sxs-lookup"><span data-stu-id="3da46-114">Whether the object represents a directory.</span></span></param>
        <param name="ocpBatchFileUrl"><span data-ttu-id="3da46-115">ファイルの URL です。</span><span class="sxs-lookup"><span data-stu-id="3da46-115">The URL of the file.</span></span></param>
        <param name="ocpBatchFileMode"><span data-ttu-id="3da46-116">8 進数形式でファイル モード属性です。</span><span class="sxs-lookup"><span data-stu-id="3da46-116">The file mode attribute in octal format.</span></span></param>
        <param name="contentType"><span data-ttu-id="3da46-117">ファイルのコンテンツの種類。</span><span class="sxs-lookup"><span data-stu-id="3da46-117">The content type of the file.</span></span></param>
        <param name="contentLength"><span data-ttu-id="3da46-118">ファイルの長さ。</span><span class="sxs-lookup"><span data-stu-id="3da46-118">The length of the file.</span></span></param>
        <summary>
            <span data-ttu-id="3da46-119">FileGetFromTaskHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3da46-119">Initializes a new instance of the FileGetFromTaskHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.ClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.ClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="client-request-id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3da46-120">取得または要求時に、クライアントによって提供される、クライアントの要求の id を設定します。</span><span class="sxs-lookup"><span data-stu-id="3da46-120">Gets or sets the client-request-id provided by the client during the request.</span></span> <span data-ttu-id="3da46-121">これが返されますの戻り値クライアント要求 id パラメーターを設定した場合にのみ true に設定します。</span><span class="sxs-lookup"><span data-stu-id="3da46-121">This will be returned only if the return-client-request-id parameter was set to true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLength">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ContentLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ContentLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.ContentLength" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentLength As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ContentLength : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.ContentLength" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.ContentLength</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Content-Length")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3da46-122">取得またはファイルの長さを設定します。</span><span class="sxs-lookup"><span data-stu-id="3da46-122">Gets or sets the length of the file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.ContentType" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.ContentType</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Content-Type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3da46-123">取得またはファイルのコンテンツの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="3da46-123">Gets or sets the content type of the file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.ETag" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.ETag</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ETag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3da46-124">取得または ETag HTTP 応答ヘッダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="3da46-124">Gets or sets the ETag HTTP response header.</span></span> <span data-ttu-id="3da46-125">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="3da46-125">This is an opaque string.</span></span> <span data-ttu-id="3da46-126">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="3da46-126">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="3da46-127">具体的には、いずれかの場合-変更のため、場合の未変更の状態のため、If-match または [なし]-If-match ヘッダーに ETag を渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="3da46-127">In particular, you can pass the ETag to one of the If-Modified-Since, If-Unmodified-Since, If-Match or If-None-Match headers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.LastModified" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.LastModified</InterfaceMember>
      </Implements>
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Last-Modified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3da46-128">取得またはリソースが最後に変更された時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="3da46-128">Gets or sets the time at which the resource was last modified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpBatchFileIsdirectory">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OcpBatchFileIsdirectory { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OcpBatchFileIsdirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.OcpBatchFileIsdirectory" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpBatchFileIsdirectory As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OcpBatchFileIsdirectory : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.OcpBatchFileIsdirectory" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.OcpBatchFileIsdirectory</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ocp-batch-file-isdirectory")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3da46-129">取得またはオブジェクトがディレクトリを表すかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="3da46-129">Gets or sets whether the object represents a directory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpBatchFileMode">
      <MemberSignature Language="C#" Value="public string OcpBatchFileMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OcpBatchFileMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.OcpBatchFileMode" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpBatchFileMode As String" />
      <MemberSignature Language="F#" Value="member this.OcpBatchFileMode : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.OcpBatchFileMode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.OcpBatchFileMode</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ocp-batch-file-mode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3da46-130">取得または 8 進数形式でファイル モード属性を設定します。</span><span class="sxs-lookup"><span data-stu-id="3da46-130">Gets or sets the file mode attribute in octal format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpBatchFileUrl">
      <MemberSignature Language="C#" Value="public string OcpBatchFileUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OcpBatchFileUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.OcpBatchFileUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpBatchFileUrl As String" />
      <MemberSignature Language="F#" Value="member this.OcpBatchFileUrl : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.OcpBatchFileUrl" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.OcpBatchFileUrl</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ocp-batch-file-url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3da46-131">取得またはファイルの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="3da46-131">Gets or sets the URL of the file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpCreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OcpCreationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OcpCreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.OcpCreationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpCreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OcpCreationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.OcpCreationTime" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.OcpCreationTime</InterfaceMember>
      </Implements>
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ocp-creation-time")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3da46-132">取得またはファイル作成時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="3da46-132">Gets or sets the file creation time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetFromTaskHeaders.RequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IProtocolNodeFile.RequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="request-id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3da46-133">取得または設定が、バッチ サービスに行われた要求の一意の識別子。</span><span class="sxs-lookup"><span data-stu-id="3da46-133">Gets or sets a unique identifier for the request that was made to the Batch service.</span></span> <span data-ttu-id="3da46-134">要求の形式が正しいにもかかわらず要求が常に失敗する場合は、この値を使用して Microsoft にエラーを報告することができます。</span><span class="sxs-lookup"><span data-stu-id="3da46-134">If a request is consistently failing and you have verified that the request is properly formulated, you may use this value to report the error to Microsoft.</span></span> <span data-ttu-id="3da46-135">レポートでは、値を含める、この要求 ID のおおよその時間、要求が行われたことを対象となる要求が行われた、Batch アカウントおよびアカウントに配置する地域。</span><span class="sxs-lookup"><span data-stu-id="3da46-135">In your report, include the value of this request ID, the approximate time that the request was made, the Batch account against which the request was made, and the region that account resides in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>