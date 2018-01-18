<Type Name="PoolUpgradeOSHeaders" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders">
  <TypeSignature Language="C#" Value="public class PoolUpgradeOSHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolUpgradeOSHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolUpgradeOSHeaders" />
  <TypeSignature Language="F#" Value="type PoolUpgradeOSHeaders = class" />
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
            <span data-ttu-id="94f0e-101">UpgradeOS 操作のヘッダーを定義します。</span><span class="sxs-lookup"><span data-stu-id="94f0e-101">Defines headers for UpgradeOS operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolUpgradeOSHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders.#ctor" />
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
            <span data-ttu-id="94f0e-102">PoolUpgradeOSHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="94f0e-102">Initializes a new instance of the PoolUpgradeOSHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolUpgradeOSHeaders (Nullable&lt;Guid&gt; clientRequestId = null, Nullable&lt;Guid&gt; requestId = null, string eTag = null, Nullable&lt;DateTime&gt; lastModified = null, string dataServiceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; clientRequestId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; requestId, string eTag, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, string dataServiceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders.#ctor(System.Nullable{System.Guid},System.Nullable{System.Guid},System.String,System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientRequestId As Nullable(Of Guid) = null, Optional requestId As Nullable(Of Guid) = null, Optional eTag As String = null, Optional lastModified As Nullable(Of DateTime) = null, Optional dataServiceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders : Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * string * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders (clientRequestId, requestId, eTag, lastModified, dataServiceId)" />
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
        <Parameter Name="dataServiceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientRequestId"><span data-ttu-id="94f0e-103">クライアント要求 id 要求時にクライアントによって指定します。</span><span class="sxs-lookup"><span data-stu-id="94f0e-103">The client-request-id provided by the client during the request.</span></span> <span data-ttu-id="94f0e-104">これが返されますの戻り値クライアント要求 id パラメーターを設定した場合にのみ true に設定します。</span><span class="sxs-lookup"><span data-stu-id="94f0e-104">This will be returned only if the return-client-request-id parameter was set to true.</span></span></param>
        <param name="requestId"><span data-ttu-id="94f0e-105">バッチ サービスに対して行った要求に対して一意の識別子。</span><span class="sxs-lookup"><span data-stu-id="94f0e-105">A unique identifier for the request that was made to the Batch service.</span></span> <span data-ttu-id="94f0e-106">要求の形式が正しいにもかかわらず要求が常に失敗する場合は、この値を使用して Microsoft にエラーを報告することができます。</span><span class="sxs-lookup"><span data-stu-id="94f0e-106">If a request is consistently failing and you have verified that the request is properly formulated, you may use this value to report the error to Microsoft.</span></span> <span data-ttu-id="94f0e-107">レポートでは、値を含める、この要求 ID のおおよその時間、要求が行われたことを対象となる要求が行われた、Batch アカウントおよびアカウントに配置する地域。</span><span class="sxs-lookup"><span data-stu-id="94f0e-107">In your report, include the value of this request ID, the approximate time that the request was made, the Batch account against which the request was made, and the region that account resides in.</span></span></param>
        <param name="eTag"><span data-ttu-id="94f0e-108">ETag HTTP 応答ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="94f0e-108">The ETag HTTP response header.</span></span> <span data-ttu-id="94f0e-109">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="94f0e-109">This is an opaque string.</span></span> <span data-ttu-id="94f0e-110">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="94f0e-110">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="94f0e-111">具体的には、いずれかの場合-変更のため、場合の未変更の状態のため、If-match または [なし]-If-match ヘッダーに ETag を渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="94f0e-111">In particular, you can pass the ETag to one of the If-Modified-Since, If-Unmodified-Since, If-Match or If-None-Match headers.</span></span></param>
        <param name="lastModified"><span data-ttu-id="94f0e-112">リソースの最終更新日時。</span><span class="sxs-lookup"><span data-stu-id="94f0e-112">The time at which the resource was last modified.</span></span></param>
        <param name="dataServiceId"><span data-ttu-id="94f0e-113">要求が適用されるリソースの OData の ID です。</span><span class="sxs-lookup"><span data-stu-id="94f0e-113">The OData ID of the resource to which the request applied.</span></span></param>
        <summary>
            <span data-ttu-id="94f0e-114">PoolUpgradeOSHeaders クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="94f0e-114">Initializes a new instance of the PoolUpgradeOSHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders.ClientRequestId" />
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
            <span data-ttu-id="94f0e-115">取得または要求時に、クライアントによって提供される、クライアントの要求の id を設定します。</span><span class="sxs-lookup"><span data-stu-id="94f0e-115">Gets or sets the client-request-id provided by the client during the request.</span></span> <span data-ttu-id="94f0e-116">これが返されますの戻り値クライアント要求 id パラメーターを設定した場合にのみ true に設定します。</span><span class="sxs-lookup"><span data-stu-id="94f0e-116">This will be returned only if the return-client-request-id parameter was set to true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataServiceId">
      <MemberSignature Language="C#" Value="public string DataServiceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataServiceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders.DataServiceId" />
      <MemberSignature Language="VB.NET" Value="Public Property DataServiceId As String" />
      <MemberSignature Language="F#" Value="member this.DataServiceId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders.DataServiceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="DataServiceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94f0e-117">取得または要求が適用されるリソースの OData の ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="94f0e-117">Gets or sets the OData ID of the resource to which the request applied.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders.ETag" />
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
            <span data-ttu-id="94f0e-118">取得または ETag HTTP 応答ヘッダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="94f0e-118">Gets or sets the ETag HTTP response header.</span></span> <span data-ttu-id="94f0e-119">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="94f0e-119">This is an opaque string.</span></span> <span data-ttu-id="94f0e-120">要求間でリソースが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="94f0e-120">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="94f0e-121">具体的には、いずれかの場合-変更のため、場合の未変更の状態のため、If-match または [なし]-If-match ヘッダーに ETag を渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="94f0e-121">In particular, you can pass the ETag to one of the If-Modified-Since, If-Unmodified-Since, If-Match or If-None-Match headers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders.LastModified" />
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
            <span data-ttu-id="94f0e-122">取得またはリソースが最後に変更された時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="94f0e-122">Gets or sets the time at which the resource was last modified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders.RequestId" />
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
            <span data-ttu-id="94f0e-123">取得または設定が、バッチ サービスに行われた要求の一意の識別子。</span><span class="sxs-lookup"><span data-stu-id="94f0e-123">Gets or sets a unique identifier for the request that was made to the Batch service.</span></span> <span data-ttu-id="94f0e-124">要求の形式が正しいにもかかわらず要求が常に失敗する場合は、この値を使用して Microsoft にエラーを報告することができます。</span><span class="sxs-lookup"><span data-stu-id="94f0e-124">If a request is consistently failing and you have verified that the request is properly formulated, you may use this value to report the error to Microsoft.</span></span> <span data-ttu-id="94f0e-125">レポートでは、値を含める、この要求 ID のおおよその時間、要求が行われたことを対象となる要求が行われた、Batch アカウントおよびアカウントに配置する地域。</span><span class="sxs-lookup"><span data-stu-id="94f0e-125">In your report, include the value of this request ID, the approximate time that the request was made, the Batch account against which the request was made, and the region that account resides in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>