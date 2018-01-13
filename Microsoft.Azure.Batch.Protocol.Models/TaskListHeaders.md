<Type Name="TaskListHeaders" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders">
  <TypeSignature Language="C#" Value="public class TaskListHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskListHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskListHeaders" />
  <TypeSignature Language="F#" Value="type TaskListHeaders = class" />
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
            <span data-ttu-id="0c841-101">一覧表示操作のヘッダーを定義します。</span><span class="sxs-lookup"><span data-stu-id="0c841-101">Defines headers for List operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskListHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders.#ctor" />
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
            <span data-ttu-id="0c841-102">TaskListHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0c841-102">Initializes a new instance of the TaskListHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskListHeaders (Nullable&lt;Guid&gt; clientRequestId = null, Nullable&lt;Guid&gt; requestId = null, string eTag = null, Nullable&lt;DateTime&gt; lastModified = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; clientRequestId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; requestId, string eTag, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders.#ctor(System.Nullable{System.Guid},System.Nullable{System.Guid},System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientRequestId As Nullable(Of Guid) = null, Optional requestId As Nullable(Of Guid) = null, Optional eTag As String = null, Optional lastModified As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders : Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders (clientRequestId, requestId, eTag, lastModified)" />
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
      </Parameters>
      <Docs>
        <param name="clientRequestId"><span data-ttu-id="0c841-103">クライアント要求 id 要求時にクライアントによって指定します。</span><span class="sxs-lookup"><span data-stu-id="0c841-103">The client-request-id provided by the client during the request.</span></span> <span data-ttu-id="0c841-104">これが返されますの戻り値クライアント要求 id パラメーターを設定した場合にのみ true に設定します。</span><span class="sxs-lookup"><span data-stu-id="0c841-104">This will be returned only if the return-client-request-id parameter was set to true.</span></span></param>
        <param name="requestId"><span data-ttu-id="0c841-105">バッチ サービスに対して行った要求に対して一意の識別子。</span><span class="sxs-lookup"><span data-stu-id="0c841-105">A unique identifier for the request that was made to the Batch service.</span></span> <span data-ttu-id="0c841-106">要求の形式が正しいにもかかわらず要求が常に失敗する場合は、この値を使用して Microsoft にエラーを報告することができます。</span><span class="sxs-lookup"><span data-stu-id="0c841-106">If a request is consistently failing and you have verified that the request is properly formulated, you may use this value to report the error to Microsoft.</span></span> <span data-ttu-id="0c841-107">レポートでは、値を含める、この要求 ID のおおよその時間、要求が行われたことを対象となる要求が行われた、Batch アカウントおよびアカウントに配置する地域。</span><span class="sxs-lookup"><span data-stu-id="0c841-107">In your report, include the value of this request ID, the approximate time that the request was made, the Batch account against which the request was made, and the region that account resides in.</span></span></param>
        <param name="eTag"><span data-ttu-id="0c841-108">ETag HTTP 応答ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="0c841-108">The ETag HTTP response header.</span></span> <span data-ttu-id="0c841-109">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="0c841-109">This is an opaque string.</span></span> <span data-ttu-id="0c841-110">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="0c841-110">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="0c841-111">具体的には、いずれかの場合-変更のため、場合の未変更の状態のため、If-match または [なし]-If-match ヘッダーに ETag を渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="0c841-111">In particular, you can pass the ETag to one of the If-Modified-Since, If-Unmodified-Since, If-Match or If-None-Match headers.</span></span></param>
        <param name="lastModified"><span data-ttu-id="0c841-112">リソースの最終更新日時。</span><span class="sxs-lookup"><span data-stu-id="0c841-112">The time at which the resource was last modified.</span></span></param>
        <summary>
            <span data-ttu-id="0c841-113">TaskListHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0c841-113">Initializes a new instance of the TaskListHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders.ClientRequestId" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="0c841-114">取得または要求時に、クライアントによって提供される、クライアントの要求の id を設定します。</span><span class="sxs-lookup"><span data-stu-id="0c841-114">Gets or sets the client-request-id provided by the client during the request.</span></span> <span data-ttu-id="0c841-115">これが返されますの戻り値クライアント要求 id パラメーターを設定した場合にのみ true に設定します。</span><span class="sxs-lookup"><span data-stu-id="0c841-115">This will be returned only if the return-client-request-id parameter was set to true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders.ETag" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="0c841-116">取得または ETag HTTP 応答ヘッダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="0c841-116">Gets or sets the ETag HTTP response header.</span></span> <span data-ttu-id="0c841-117">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="0c841-117">This is an opaque string.</span></span> <span data-ttu-id="0c841-118">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="0c841-118">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="0c841-119">具体的には、いずれかの場合-変更のため、場合の未変更の状態のため、If-match または [なし]-If-match ヘッダーに ETag を渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="0c841-119">In particular, you can pass the ETag to one of the If-Modified-Since, If-Unmodified-Since, If-Match or If-None-Match headers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders.LastModified" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Last-Modified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0c841-120">取得またはリソースが最後に変更された時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="0c841-120">Gets or sets the time at which the resource was last modified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders.RequestId" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="0c841-121">取得または設定が、バッチ サービスに行われた要求の一意の識別子。</span><span class="sxs-lookup"><span data-stu-id="0c841-121">Gets or sets a unique identifier for the request that was made to the Batch service.</span></span> <span data-ttu-id="0c841-122">要求の形式が正しいにもかかわらず要求が常に失敗する場合は、この値を使用して Microsoft にエラーを報告することができます。</span><span class="sxs-lookup"><span data-stu-id="0c841-122">If a request is consistently failing and you have verified that the request is properly formulated, you may use this value to report the error to Microsoft.</span></span> <span data-ttu-id="0c841-123">レポートでは、値を含める、この要求 ID のおおよその時間、要求が行われたことを対象となる要求が行われた、Batch アカウントおよびアカウントに配置する地域。</span><span class="sxs-lookup"><span data-stu-id="0c841-123">In your report, include the value of this request ID, the approximate time that the request was made, the Batch account against which the request was made, and the region that account resides in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>