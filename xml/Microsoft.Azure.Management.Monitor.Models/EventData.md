<Type Name="EventData" FullName="Microsoft.Azure.Management.Monitor.Models.EventData">
  <TypeSignature Language="C#" Value="public class EventData" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventData extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Models.EventData" />
  <TypeSignature Language="VB.NET" Value="Public Class EventData" />
  <TypeSignature Language="F#" Value="type EventData = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="29b81-101">Azure のイベント ログ エントリが型 EventData です。</span><span class="sxs-lookup"><span data-stu-id="29b81-101">The Azure event log entries are of type EventData</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.EventData.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="29b81-102">EventData クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="29b81-102">Initializes a new instance of the EventData class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (Microsoft.Azure.Management.Monitor.Models.EventLevel level, DateTime eventTimestamp, DateTime submissionTimestamp, Microsoft.Azure.Management.Monitor.Models.SenderAuthorization authorization = null, System.Collections.Generic.IDictionary&lt;string,string&gt; claims = null, string caller = null, string description = null, string id = null, string eventDataId = null, string correlationId = null, Microsoft.Azure.Management.Monitor.Models.LocalizableString eventName = null, Microsoft.Azure.Management.Monitor.Models.LocalizableString category = null, Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo httpRequest = null, string resourceGroupName = null, Microsoft.Azure.Management.Monitor.Models.LocalizableString resourceProviderName = null, string resourceId = null, Microsoft.Azure.Management.Monitor.Models.LocalizableString resourceType = null, string operationId = null, Microsoft.Azure.Management.Monitor.Models.LocalizableString operationName = null, System.Collections.Generic.IDictionary&lt;string,string&gt; properties = null, Microsoft.Azure.Management.Monitor.Models.LocalizableString status = null, Microsoft.Azure.Management.Monitor.Models.LocalizableString subStatus = null, string subscriptionId = null, string tenantId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Monitor.Models.EventLevel level, valuetype System.DateTime eventTimestamp, valuetype System.DateTime submissionTimestamp, class Microsoft.Azure.Management.Monitor.Models.SenderAuthorization authorization, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; claims, string caller, string description, string id, string eventDataId, string correlationId, class Microsoft.Azure.Management.Monitor.Models.LocalizableString eventName, class Microsoft.Azure.Management.Monitor.Models.LocalizableString category, class Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo httpRequest, string resourceGroupName, class Microsoft.Azure.Management.Monitor.Models.LocalizableString resourceProviderName, string resourceId, class Microsoft.Azure.Management.Monitor.Models.LocalizableString resourceType, string operationId, class Microsoft.Azure.Management.Monitor.Models.LocalizableString operationName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties, class Microsoft.Azure.Management.Monitor.Models.LocalizableString status, class Microsoft.Azure.Management.Monitor.Models.LocalizableString subStatus, string subscriptionId, string tenantId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.EventData.#ctor(Microsoft.Azure.Management.Monitor.Models.EventLevel,System.DateTime,System.DateTime,Microsoft.Azure.Management.Monitor.Models.SenderAuthorization,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Monitor.Models.LocalizableString,Microsoft.Azure.Management.Monitor.Models.LocalizableString,Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo,System.String,Microsoft.Azure.Management.Monitor.Models.LocalizableString,System.String,Microsoft.Azure.Management.Monitor.Models.LocalizableString,System.String,Microsoft.Azure.Management.Monitor.Models.LocalizableString,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Monitor.Models.LocalizableString,Microsoft.Azure.Management.Monitor.Models.LocalizableString,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (level As EventLevel, eventTimestamp As DateTime, submissionTimestamp As DateTime, Optional authorization As SenderAuthorization = null, Optional claims As IDictionary(Of String, String) = null, Optional caller As String = null, Optional description As String = null, Optional id As String = null, Optional eventDataId As String = null, Optional correlationId As String = null, Optional eventName As LocalizableString = null, Optional category As LocalizableString = null, Optional httpRequest As HttpRequestInfo = null, Optional resourceGroupName As String = null, Optional resourceProviderName As LocalizableString = null, Optional resourceId As String = null, Optional resourceType As LocalizableString = null, Optional operationId As String = null, Optional operationName As LocalizableString = null, Optional properties As IDictionary(Of String, String) = null, Optional status As LocalizableString = null, Optional subStatus As LocalizableString = null, Optional subscriptionId As String = null, Optional tenantId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Models.EventData : Microsoft.Azure.Management.Monitor.Models.EventLevel * DateTime * DateTime * Microsoft.Azure.Management.Monitor.Models.SenderAuthorization * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * string * string * string * Microsoft.Azure.Management.Monitor.Models.LocalizableString * Microsoft.Azure.Management.Monitor.Models.LocalizableString * Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo * string * Microsoft.Azure.Management.Monitor.Models.LocalizableString * string * Microsoft.Azure.Management.Monitor.Models.LocalizableString * string * Microsoft.Azure.Management.Monitor.Models.LocalizableString * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Monitor.Models.LocalizableString * Microsoft.Azure.Management.Monitor.Models.LocalizableString * string * string -&gt; Microsoft.Azure.Management.Monitor.Models.EventData" Usage="new Microsoft.Azure.Management.Monitor.Models.EventData (level, eventTimestamp, submissionTimestamp, authorization, claims, caller, description, id, eventDataId, correlationId, eventName, category, httpRequest, resourceGroupName, resourceProviderName, resourceId, resourceType, operationId, operationName, properties, status, subStatus, subscriptionId, tenantId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="level" Type="Microsoft.Azure.Management.Monitor.Models.EventLevel" />
        <Parameter Name="eventTimestamp" Type="System.DateTime" />
        <Parameter Name="submissionTimestamp" Type="System.DateTime" />
        <Parameter Name="authorization" Type="Microsoft.Azure.Management.Monitor.Models.SenderAuthorization" />
        <Parameter Name="claims" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="caller" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="eventDataId" Type="System.String" />
        <Parameter Name="correlationId" Type="System.String" />
        <Parameter Name="eventName" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="category" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="httpRequest" Type="Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderName" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="resourceType" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="operationName" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="subStatus" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="tenantId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="level"><span data-ttu-id="29b81-103">イベント レベル。</span><span class="sxs-lookup"><span data-stu-id="29b81-103">the event level.</span></span> <span data-ttu-id="29b81-104">使用可能な値が含まれます: 'Critical'、'Error'、'Warning'、'情報'、'詳細'</span><span class="sxs-lookup"><span data-stu-id="29b81-104">Possible values include: 'Critical', 'Error', 'Warning', 'Informational', 'Verbose'</span></span></param>
        <param name="eventTimestamp"><span data-ttu-id="29b81-105">イベントがイベントに対応する要求を処理する Azure サービスによって生成されたときのタイムスタンプ。</span><span class="sxs-lookup"><span data-stu-id="29b81-105">the timestamp of when the event was generated by the Azure service processing the request corresponding the event.</span></span> <span data-ttu-id="29b81-106">ISO 8601 形式にします。</span><span class="sxs-lookup"><span data-stu-id="29b81-106">It in ISO 8601 format.</span></span></param>
        <param name="submissionTimestamp"><span data-ttu-id="29b81-107">イベントがこの API を使用してクエリを実行するために利用可能になったのタイムスタンプ。</span><span class="sxs-lookup"><span data-stu-id="29b81-107">the timestamp of when the event became available for querying via this API.</span></span> <span data-ttu-id="29b81-108">これは、ISO 8601 形式です。</span><span class="sxs-lookup"><span data-stu-id="29b81-108">It is in ISO 8601 format.</span></span> <span data-ttu-id="29b81-109">この値が、混同 eventTimestamp することはできません。</span><span class="sxs-lookup"><span data-stu-id="29b81-109">This value should not be confused eventTimestamp.</span></span> <span data-ttu-id="29b81-110">イベントの発生時刻とイベントは、Azure のログ記録インフラストラクチャに送信された時刻間に遅延がある場合があります。</span><span class="sxs-lookup"><span data-stu-id="29b81-110">As there might be a delay between the occurrence time of the event, and the time that the event is submitted to the Azure logging infrastructure.</span></span></param>
        <param name="authorization">To be added.</param>
        <param name="claims"><span data-ttu-id="29b81-111">ARM のアクセス許可を識別するキー値のペア。</span><span class="sxs-lookup"><span data-stu-id="29b81-111">key value pairs to identify ARM permissions.</span></span></param>
        <param name="caller"><span data-ttu-id="29b81-112">操作では、UPN 要求または SPN 要求の可用性に基づいてが実行したユーザーの電子メール アドレス。</span><span class="sxs-lookup"><span data-stu-id="29b81-112">the email address of the user who has performed the operation, the UPN claim or SPN claim based on availability.</span></span></param>
        <param name="description"><span data-ttu-id="29b81-113">イベントの説明です。</span><span class="sxs-lookup"><span data-stu-id="29b81-113">the description of the event.</span></span></param>
        <param name="id"><span data-ttu-id="29b81-114">RBAC の ARM で必要とは、このイベントの Id。</span><span class="sxs-lookup"><span data-stu-id="29b81-114">the Id of this event as required by ARM for RBAC.</span></span>
            <span data-ttu-id="29b81-115">EventDataID とタイムスタンプ情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="29b81-115">It contains the EventDataID and a timestamp information.</span></span></param>
        <param name="eventDataId"><span data-ttu-id="29b81-116">イベント データ id。これは、イベントの一意の識別子です。</span><span class="sxs-lookup"><span data-stu-id="29b81-116">the event data Id. This is a unique identifier for an event.</span></span></param>
        <param name="correlationId"><span data-ttu-id="29b81-117">関連付け Id、通常は GUID 文字列形式。</span><span class="sxs-lookup"><span data-stu-id="29b81-117">the correlation Id, usually a GUID in the string format.</span></span> <span data-ttu-id="29b81-118">相関 Id は、同じ uber 操作に属しているイベントの間で共有されます。</span><span class="sxs-lookup"><span data-stu-id="29b81-118">The correlation Id is shared among the events that belong to the same uber operation.</span></span></param>
        <param name="eventName"><span data-ttu-id="29b81-119">イベント名。</span><span class="sxs-lookup"><span data-stu-id="29b81-119">the event name.</span></span> <span data-ttu-id="29b81-120">この値は、OperationName と混同しないでください。</span><span class="sxs-lookup"><span data-stu-id="29b81-120">This value should not be confused with OperationName.</span></span> <span data-ttu-id="29b81-121">実際には、OperationName がエンドユーザーに説得力があります。</span><span class="sxs-lookup"><span data-stu-id="29b81-121">For practical purposes, OperationName might be more appealing to end users.</span></span></param>
        <param name="category"><span data-ttu-id="29b81-122">イベントのカテゴリ。</span><span class="sxs-lookup"><span data-stu-id="29b81-122">the event category.</span></span></param>
        <param name="httpRequest"><span data-ttu-id="29b81-123">HTTP 要求の情報です。</span><span class="sxs-lookup"><span data-stu-id="29b81-123">the HTTP request info.</span></span> <span data-ttu-id="29b81-124">通常、'clientRequestId'、'clientIpAddress' (イベントを開始したユーザーの IP アドレス) と 'method' が含まれます (HTTP メソッド PUT などの)。</span><span class="sxs-lookup"><span data-stu-id="29b81-124">Usually includes the 'clientRequestId', 'clientIpAddress' (IP address of the user who initiated the event) and 'method' (HTTP method e.g. PUT).</span></span></param>
        <param name="resourceGroupName"><span data-ttu-id="29b81-125">影響を受けるリソースのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="29b81-125">the resource group name of the impacted resource.</span></span></param>
        <param name="resourceProviderName"><span data-ttu-id="29b81-126">影響を受けるリソースのリソース プロバイダーの名前。</span><span class="sxs-lookup"><span data-stu-id="29b81-126">the resource provider name of the impacted resource.</span></span></param>
        <param name="resourceId"><span data-ttu-id="29b81-127">このイベントの原因となったリソースを一意に識別するリソースの uri。</span><span class="sxs-lookup"><span data-stu-id="29b81-127">the resource uri that uniquely identifies the resource that caused this event.</span></span></param>
        <param name="resourceType"><span data-ttu-id="29b81-128">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="29b81-128">the resource type</span></span></param>
        <param name="operationId"><span data-ttu-id="29b81-129">これは、通常、1 つの操作に対応するイベントの間で共有 GUID です。</span><span class="sxs-lookup"><span data-stu-id="29b81-129">It is usually a GUID shared among the events corresponding to single operation.</span></span> <span data-ttu-id="29b81-130">この値は、EventName と混同しないでください。</span><span class="sxs-lookup"><span data-stu-id="29b81-130">This value should not be confused with EventName.</span></span></param>
        <param name="operationName"><span data-ttu-id="29b81-131">操作の名前です。</span><span class="sxs-lookup"><span data-stu-id="29b81-131">the operation name.</span></span></param>
        <param name="properties"><span data-ttu-id="29b81-132">一連の&lt;キー、値&gt;ペア (ディクショナリでは通常&lt;String, String&gt;)、イベントに関する詳細情報を含むです。</span><span class="sxs-lookup"><span data-stu-id="29b81-132">the set of &lt;Key, Value&gt; pairs (usually a Dictionary&lt;String, String&gt;) that includes details about the event.</span></span></param>
        <param name="status"><span data-ttu-id="29b81-133">操作の状態を説明する文字列。</span><span class="sxs-lookup"><span data-stu-id="29b81-133">a string describing the status of the operation.</span></span> <span data-ttu-id="29b81-134">いくつかの一般的な値: 実行中、Succeeded、Failed、解決済み、開始します。</span><span class="sxs-lookup"><span data-stu-id="29b81-134">Some typical values are: Started, In progress, Succeeded, Failed, Resolved.</span></span></param>
        <param name="subStatus"><span data-ttu-id="29b81-135">イベントのサブ状態です。</span><span class="sxs-lookup"><span data-stu-id="29b81-135">the event sub status.</span></span> <span data-ttu-id="29b81-136">ほとんどの場合、含まれる場合、キャプチャ REST 呼び出しの HTTP ステータス コード。</span><span class="sxs-lookup"><span data-stu-id="29b81-136">Most of the time, when included, this captures the HTTP status code of the REST call.</span></span>
            <span data-ttu-id="29b81-137">一般的な値は、: [ok] (HTTP ステータス コード: 200)、作成した (HTTP ステータス コード: 201)、承認済み (HTTP ステータス コード: 202) No Content、(HTTP ステータス コード: 204)、不良 Request(HTTP Status Code: 400)、見つかりませんでした (HTTP ステータス コード: 404)、競合 (HTTP ステータス コード: 409)、内部サーバー エラー (HTTP ステータス コード: 500)、サービスを利用できません (HTTP ステータス コード: 503)、ゲートウェイ タイムアウト (HTTP ステータス コード: 504)</span><span class="sxs-lookup"><span data-stu-id="29b81-137">Common values are: OK (HTTP Status Code: 200), Created (HTTP Status Code: 201), Accepted (HTTP Status Code: 202), No Content (HTTP Status Code: 204), Bad Request(HTTP Status Code: 400), Not Found (HTTP Status Code: 404), Conflict (HTTP Status Code: 409), Internal Server Error (HTTP Status Code: 500), Service Unavailable (HTTP Status Code:503), Gateway Timeout (HTTP Status Code: 504)</span></span></param>
        <param name="subscriptionId"><span data-ttu-id="29b81-138">Azure のサブスクリプション Id 通常は GUID です。</span><span class="sxs-lookup"><span data-stu-id="29b81-138">the Azure subscription Id usually a GUID.</span></span></param>
        <param name="tenantId"><span data-ttu-id="29b81-139">Azure のテナント Id</span><span class="sxs-lookup"><span data-stu-id="29b81-139">the Azure tenant Id</span></span></param>
        <summary>
            <span data-ttu-id="29b81-140">EventData クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="29b81-140">Initializes a new instance of the EventData class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.SenderAuthorization Authorization { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.SenderAuthorization Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public Property Authorization As SenderAuthorization" />
      <MemberSignature Language="F#" Value="member this.Authorization : Microsoft.Azure.Management.Monitor.Models.SenderAuthorization with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authorization")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.SenderAuthorization</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caller">
      <MemberSignature Language="C#" Value="public string Caller { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Caller" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Caller" />
      <MemberSignature Language="VB.NET" Value="Public Property Caller As String" />
      <MemberSignature Language="F#" Value="member this.Caller : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Caller" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="caller")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-141">取得または、操作、UPN 要求または SPN 要求の可用性に基づいてが実行したユーザーの電子メール アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-141">Gets or sets the email address of the user who has performed the operation, the UPN claim or SPN claim based on availability.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Category">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString Category { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString Category" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Category" />
      <MemberSignature Language="VB.NET" Value="Public Property Category As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.Category : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Category" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="category")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-142">取得またはイベントのカテゴリを設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-142">Gets or sets the event category.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Claims">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Claims { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Claims" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Claims" />
      <MemberSignature Language="VB.NET" Value="Public Property Claims As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Claims : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Claims" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="claims")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-143">取得または ARM のアクセス許可を識別するキー値のペアを設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-143">Gets or sets key value pairs to identify ARM permissions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="correlationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-144">取得または相関 Id、通常は GUID 文字列形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-144">Gets or sets the correlation Id, usually a GUID in the string format.</span></span> <span data-ttu-id="29b81-145">相関 Id は、同じ uber 操作に属しているイベントの間で共有されます。</span><span class="sxs-lookup"><span data-stu-id="29b81-145">The correlation Id is shared among the events that belong to the same uber operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-146">取得またはイベントの説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-146">Gets or sets the description of the event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventDataId">
      <MemberSignature Language="C#" Value="public string EventDataId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventDataId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.EventDataId" />
      <MemberSignature Language="VB.NET" Value="Public Property EventDataId As String" />
      <MemberSignature Language="F#" Value="member this.EventDataId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.EventDataId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eventDataId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-147">取得または設定、イベント データ id。これは、イベントの一意の識別子です。</span><span class="sxs-lookup"><span data-stu-id="29b81-147">Gets or sets the event data Id. This is a unique identifier for an event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString EventName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString EventName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.EventName" />
      <MemberSignature Language="VB.NET" Value="Public Property EventName As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.EventName : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.EventName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eventName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-148">取得またはイベントの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-148">Gets or sets the event name.</span></span> <span data-ttu-id="29b81-149">この値は、OperationName と混同しないでください。</span><span class="sxs-lookup"><span data-stu-id="29b81-149">This value should not be confused with OperationName.</span></span> <span data-ttu-id="29b81-150">実際には、OperationName がエンドユーザーに説得力があります。</span><span class="sxs-lookup"><span data-stu-id="29b81-150">For practical purposes, OperationName might be more appealing to end users.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventTimestamp">
      <MemberSignature Language="C#" Value="public DateTime EventTimestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EventTimestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.EventTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property EventTimestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.EventTimestamp : DateTime with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.EventTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eventTimestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-151">取得またはイベントがイベントに対応する要求を処理する Azure サービスによって生成されたときのタイムスタンプを設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-151">Gets or sets the timestamp of when the event was generated by the Azure service processing the request corresponding the event.</span></span> <span data-ttu-id="29b81-152">ISO 8601 形式にします。</span><span class="sxs-lookup"><span data-stu-id="29b81-152">It in ISO 8601 format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpRequest">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo HttpRequest { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo HttpRequest" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.HttpRequest" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpRequest As HttpRequestInfo" />
      <MemberSignature Language="F#" Value="member this.HttpRequest : Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.HttpRequest" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="httpRequest")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-153">取得または HTTP の要求情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-153">Gets or sets the HTTP request info.</span></span> <span data-ttu-id="29b81-154">通常、'clientRequestId'、'clientIpAddress' (イベントを開始したユーザーの IP アドレス) と 'method' が含まれます (HTTP メソッド PUT などの)。</span><span class="sxs-lookup"><span data-stu-id="29b81-154">Usually includes the 'clientRequestId', 'clientIpAddress' (IP address of the user who initiated the event) and 'method' (HTTP method e.g. PUT).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
            <span data-ttu-id="29b81-155">取得または RBAC の ARM で必要に応じてこのイベントの Id を設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-155">Gets or sets the Id of this event as required by ARM for RBAC.</span></span> <span data-ttu-id="29b81-156">EventDataID とタイムスタンプ情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="29b81-156">It contains the EventDataID and a timestamp information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.EventLevel Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Models.EventLevel Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As EventLevel" />
      <MemberSignature Language="F#" Value="member this.Level : Microsoft.Azure.Management.Monitor.Models.EventLevel with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.EventLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-157">取得またはイベントのレベルを設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-157">Gets or sets the event level.</span></span> <span data-ttu-id="29b81-158">使用可能な値が含まれます: 'Critical'、'Error'、'Warning'、'情報'、'詳細'</span><span class="sxs-lookup"><span data-stu-id="29b81-158">Possible values include: 'Critical', 'Error', 'Warning', 'Informational', 'Verbose'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public string OperationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationId As String" />
      <MemberSignature Language="F#" Value="member this.OperationId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.OperationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-159">取得または設定は、通常、GUID は 1 回の操作に対応するイベント間で共有します。</span><span class="sxs-lookup"><span data-stu-id="29b81-159">Gets or sets it is usually a GUID shared among the events corresponding to single operation.</span></span> <span data-ttu-id="29b81-160">この値は、EventName と混同しないでください。</span><span class="sxs-lookup"><span data-stu-id="29b81-160">This value should not be confused with EventName.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString OperationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString OperationName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.OperationName" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationName As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.OperationName : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.OperationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operationName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-161">取得または操作名を設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-161">Gets or sets the operation name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-162">セットの取得または設定&amp;lt;キー、値&amp;gt; のペア (ディクショナリでは通常&amp;lt;String, String&amp;gt;) をイベントに関する詳細情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="29b81-162">Gets or sets the set of &amp;lt;Key, Value&amp;gt; pairs (usually a Dictionary&amp;lt;String, String&amp;gt;) that includes details about the event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroupName">
      <MemberSignature Language="C#" Value="public string ResourceGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.ResourceGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroupName : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.ResourceGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceGroupName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-163">取得または影響を受けるリソースのリソース グループ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-163">Gets or sets the resource group name of the impacted resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-164">取得またはこのイベントの原因となったリソースを一意に識別するリソースの uri を設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-164">Gets or sets the resource uri that uniquely identifies the resource that caused this event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceProviderName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString ResourceProviderName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString ResourceProviderName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.ResourceProviderName" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceProviderName As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.ResourceProviderName : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.ResourceProviderName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceProviderName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-165">取得または影響を受けるリソースのリソース プロバイダーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-165">Gets or sets the resource provider name of the impacted resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString ResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceType As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.ResourceType : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-166">取得または設定、リソースの種類</span><span class="sxs-lookup"><span data-stu-id="29b81-166">Gets or sets the resource type</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-167">取得または設定操作の状態を説明する文字列。</span><span class="sxs-lookup"><span data-stu-id="29b81-167">Gets or sets a string describing the status of the operation.</span></span> <span data-ttu-id="29b81-168">いくつかの一般的な値: 実行中、Succeeded、Failed、解決済み、開始します。</span><span class="sxs-lookup"><span data-stu-id="29b81-168">Some typical values are: Started, In progress, Succeeded, Failed, Resolved.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmissionTimestamp">
      <MemberSignature Language="C#" Value="public DateTime SubmissionTimestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime SubmissionTimestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.SubmissionTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property SubmissionTimestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.SubmissionTimestamp : DateTime with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.SubmissionTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="submissionTimestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-169">取得またはイベントがこの API を使用してクエリを実行するために利用可能になったときのタイムスタンプを設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-169">Gets or sets the timestamp of when the event became available for querying via this API.</span></span> <span data-ttu-id="29b81-170">これは、ISO 8601 形式です。</span><span class="sxs-lookup"><span data-stu-id="29b81-170">It is in ISO 8601 format.</span></span> <span data-ttu-id="29b81-171">この値が、混同 eventTimestamp することはできません。</span><span class="sxs-lookup"><span data-stu-id="29b81-171">This value should not be confused eventTimestamp.</span></span> <span data-ttu-id="29b81-172">イベントの発生時刻とイベントは、Azure のログ記録インフラストラクチャに送信された時刻間に遅延がある場合があります。</span><span class="sxs-lookup"><span data-stu-id="29b81-172">As there might be a delay between the occurrence time of the event, and the time that the event is submitted to the Azure logging infrastructure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-173">取得または、通常は GUID で Azure サブスクリプション Id を設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-173">Gets or sets the Azure subscription Id usually a GUID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString SubStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString SubStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.SubStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property SubStatus As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.SubStatus : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.SubStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-174">取得またはイベントのサブ状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="29b81-174">Gets or sets the event sub status.</span></span> <span data-ttu-id="29b81-175">ほとんどの場合、含まれる場合、キャプチャ REST 呼び出しの HTTP ステータス コード。</span><span class="sxs-lookup"><span data-stu-id="29b81-175">Most of the time, when included, this captures the HTTP status code of the REST call.</span></span> <span data-ttu-id="29b81-176">一般的な値は、: [ok] (HTTP ステータス コード: 200)、作成した (HTTP ステータス コード: 201)、承認済み (HTTP ステータス コード: 202) No Content、(HTTP ステータス コード: 204)、不良 Request(HTTP Status Code: 400)、見つかりませんでした (HTTP ステータス コード: 404)、競合 (HTTP ステータス コード: 409)、内部サーバー エラー (HTTP ステータス コード: 500)、サービスを利用できません (HTTP ステータス コード: 503)、ゲートウェイ タイムアウト (HTTP ステータス コード: 504)</span><span class="sxs-lookup"><span data-stu-id="29b81-176">Common values are: OK (HTTP Status Code: 200), Created (HTTP Status Code: 201), Accepted (HTTP Status Code: 202), No Content (HTTP Status Code: 204), Bad Request(HTTP Status Code: 400), Not Found (HTTP Status Code: 404), Conflict (HTTP Status Code: 409), Internal Server Error (HTTP Status Code: 500), Service Unavailable (HTTP Status Code:503), Gateway Timeout (HTTP Status Code: 504)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29b81-177">取得または設定、Azure テナント Id</span><span class="sxs-lookup"><span data-stu-id="29b81-177">Gets or sets the Azure tenant Id</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.EventData.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="eventData.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="29b81-178">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="29b81-178">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="29b81-179">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="29b81-179">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>