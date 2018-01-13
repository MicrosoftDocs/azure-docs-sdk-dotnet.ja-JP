<Type Name="FileGetPropertiesFromComputeNodeOptions" FullName="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions">
  <TypeSignature Language="C#" Value="public class FileGetPropertiesFromComputeNodeOptions : Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileGetPropertiesFromComputeNodeOptions extends System.Object implements class Microsoft.Azure.Batch.Protocol.Models.IOptions, class Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class FileGetPropertiesFromComputeNodeOptions&#xA;Implements ITimeoutOptions" />
  <TypeSignature Language="F#" Value="type FileGetPropertiesFromComputeNodeOptions = class&#xA;    interface ITimeoutOptions&#xA;    interface IOptions" />
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
            <span data-ttu-id="33258-101">GetPropertiesFromComputeNode 操作に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="33258-101">Additional parameters for GetPropertiesFromComputeNode operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileGetPropertiesFromComputeNodeOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.#ctor" />
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
            <span data-ttu-id="33258-102">FileGetPropertiesFromComputeNodeOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="33258-102">Initializes a new instance of the FileGetPropertiesFromComputeNodeOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileGetPropertiesFromComputeNodeOptions (Nullable&lt;int&gt; timeout = null, Nullable&lt;Guid&gt; clientRequestId = null, Nullable&lt;bool&gt; returnClientRequestId = null, Nullable&lt;DateTime&gt; ocpDate = null, Nullable&lt;DateTime&gt; ifModifiedSince = null, Nullable&lt;DateTime&gt; ifUnmodifiedSince = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; clientRequestId, valuetype System.Nullable`1&lt;bool&gt; returnClientRequestId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ocpDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ifModifiedSince, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ifUnmodifiedSince) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.#ctor(System.Nullable{System.Int32},System.Nullable{System.Guid},System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timeout As Nullable(Of Integer) = null, Optional clientRequestId As Nullable(Of Guid) = null, Optional returnClientRequestId As Nullable(Of Boolean) = null, Optional ocpDate As Nullable(Of DateTime) = null, Optional ifModifiedSince As Nullable(Of DateTime) = null, Optional ifUnmodifiedSince As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions : Nullable&lt;int&gt; * Nullable&lt;Guid&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions" Usage="new Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions (timeout, clientRequestId, returnClientRequestId, ocpDate, ifModifiedSince, ifUnmodifiedSince)" />
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
        <Parameter Name="ifModifiedSince" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ifUnmodifiedSince" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="33258-103">最大時間を秒単位で、要求の処理に、サーバーが費やすことができます。</span><span class="sxs-lookup"><span data-stu-id="33258-103">The maximum time that the server can spend processing the request, in seconds.</span></span> <span data-ttu-id="33258-104">既定値は 30 秒です。</span><span class="sxs-lookup"><span data-stu-id="33258-104">The default is 30 seconds.</span></span></param>
        <param name="clientRequestId"><span data-ttu-id="33258-105">例: 9C4D50EE 2 次元 56、中かっこなどの装飾なしの GUID の形式で、呼び出し元によって生成された要求 id-4 CD 3-8152-34347DC9F2B0 です。</span><span class="sxs-lookup"><span data-stu-id="33258-105">The caller-generated request identity, in the form of a GUID with no decoration such as curly braces, e.g. 9C4D50EE-2D56-4CD3-8152-34347DC9F2B0.</span></span></param>
        <param name="returnClientRequestId"><span data-ttu-id="33258-106">サーバーが応答でクライアント要求 id を返すかどうか。</span><span class="sxs-lookup"><span data-stu-id="33258-106">Whether the server should return the client-request-id in the response.</span></span></param>
        <param name="ocpDate"><span data-ttu-id="33258-107">要求が発行された時刻。</span><span class="sxs-lookup"><span data-stu-id="33258-107">The time the request was issued.</span></span> <span data-ttu-id="33258-108">クライアント ライブラリ通常この設定を現在のシステム クロック時間。これを明示的に設定、REST API を直接呼び出す場合。</span><span class="sxs-lookup"><span data-stu-id="33258-108">Client libraries typically set this to the current system clock time; set it explicitly if you are calling the REST API directly.</span></span></param>
        <param name="ifModifiedSince"><span data-ttu-id="33258-109">クライアントに既知のリソースの最終更新時刻を示すタイムスタンプです。</span><span class="sxs-lookup"><span data-stu-id="33258-109">A timestamp indicating the last modified time of the resource known to the client.</span></span> <span data-ttu-id="33258-110">指定した時刻以降、サービス上のリソースが変更された場合にのみ、操作が実行されます。</span><span class="sxs-lookup"><span data-stu-id="33258-110">The operation will be performed only if the resource on the service has been modified since the specified time.</span></span></param>
        <param name="ifUnmodifiedSince"><span data-ttu-id="33258-111">クライアントに既知のリソースの最終更新時刻を示すタイムスタンプです。</span><span class="sxs-lookup"><span data-stu-id="33258-111">A timestamp indicating the last modified time of the resource known to the client.</span></span> <span data-ttu-id="33258-112">指定した時刻以降、サービス上のリソースが変更されていない場合にのみ、操作が実行されます。</span><span class="sxs-lookup"><span data-stu-id="33258-112">The operation will be performed only if the resource on the service has not been modified since the specified time.</span></span></param>
        <summary>
            <span data-ttu-id="33258-113">FileGetPropertiesFromComputeNodeOptions クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="33258-113">Initializes a new instance of the FileGetPropertiesFromComputeNodeOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.ClientRequestId" />
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
            <span data-ttu-id="33258-114">例: 9C4D50EE 2 次元 56、中かっこなどの装飾なしの GUID の形式では呼び出し元によって生成された要求 id が設定を取得または -4 CD 3-8152-34347DC9F2B0 です。</span><span class="sxs-lookup"><span data-stu-id="33258-114">Gets or sets the caller-generated request identity, in the form of a GUID with no decoration such as curly braces, e.g. 9C4D50EE-2D56-4CD3-8152-34347DC9F2B0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfModifiedSince">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; IfModifiedSince { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; IfModifiedSince" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.IfModifiedSince" />
      <MemberSignature Language="VB.NET" Value="Public Property IfModifiedSince As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.IfModifiedSince : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.IfModifiedSince" />
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
            <span data-ttu-id="33258-115">取得またはクライアントに既知のリソースの最終更新時刻を示すタイムスタンプを設定します。</span><span class="sxs-lookup"><span data-stu-id="33258-115">Gets or sets a timestamp indicating the last modified time of the resource known to the client.</span></span> <span data-ttu-id="33258-116">指定した時刻以降、サービス上のリソースが変更された場合にのみ、操作が実行されます。</span><span class="sxs-lookup"><span data-stu-id="33258-116">The operation will be performed only if the resource on the service has been modified since the specified time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfUnmodifiedSince">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; IfUnmodifiedSince { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; IfUnmodifiedSince" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.IfUnmodifiedSince" />
      <MemberSignature Language="VB.NET" Value="Public Property IfUnmodifiedSince As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.IfUnmodifiedSince : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.IfUnmodifiedSince" />
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
            <span data-ttu-id="33258-117">取得またはクライアントに既知のリソースの最終更新時刻を示すタイムスタンプを設定します。</span><span class="sxs-lookup"><span data-stu-id="33258-117">Gets or sets a timestamp indicating the last modified time of the resource known to the client.</span></span> <span data-ttu-id="33258-118">指定した時刻以降、サービス上のリソースが変更されていない場合にのみ、操作が実行されます。</span><span class="sxs-lookup"><span data-stu-id="33258-118">The operation will be performed only if the resource on the service has not been modified since the specified time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OcpDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OcpDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.OcpDate" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OcpDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.OcpDate" />
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
            <span data-ttu-id="33258-119">取得または要求が発行された時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="33258-119">Gets or sets the time the request was issued.</span></span> <span data-ttu-id="33258-120">クライアント ライブラリ通常この設定を現在のシステム クロック時間。これを明示的に設定、REST API を直接呼び出す場合。</span><span class="sxs-lookup"><span data-stu-id="33258-120">Client libraries typically set this to the current system clock time; set it explicitly if you are calling the REST API directly.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReturnClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReturnClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.ReturnClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReturnClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReturnClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.ReturnClientRequestId" />
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
            <span data-ttu-id="33258-121">取得またはサーバーが応答でクライアント要求 id を返すかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="33258-121">Gets or sets whether the server should return the client-request-id in the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Timeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Timeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.Timeout" />
      <MemberSignature Language="VB.NET" Value="Public Property Timeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Timeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.FileGetPropertiesFromComputeNodeOptions.Timeout" />
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
            <span data-ttu-id="33258-122">取得または設定の最大時間 (秒)、要求の処理に、サーバーが費やすことができます。</span><span class="sxs-lookup"><span data-stu-id="33258-122">Gets or sets the maximum time that the server can spend processing the request, in seconds.</span></span> <span data-ttu-id="33258-123">既定値は 30 秒です。</span><span class="sxs-lookup"><span data-stu-id="33258-123">The default is 30 seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>