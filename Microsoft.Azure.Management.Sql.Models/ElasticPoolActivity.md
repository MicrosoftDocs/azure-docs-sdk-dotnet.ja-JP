<Type Name="ElasticPoolActivity" FullName="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity">
  <TypeSignature Language="C#" Value="public class ElasticPoolActivity : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ElasticPoolActivity extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class ElasticPoolActivity&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type ElasticPoolActivity = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ea6c0-101">弾力性プールの利用状況を表します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-101">Represents the activity on an elastic pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-102">ElasticPoolActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-102">Initializes a new instance of the ElasticPoolActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolActivity (string id = null, string name = null, string type = null, string location = null, Nullable&lt;DateTime&gt; endTime = null, Nullable&lt;int&gt; errorCode = null, string errorMessage = null, Nullable&lt;int&gt; errorSeverity = null, string operation = null, Guid operationId = null, Nullable&lt;int&gt; percentComplete = null, Nullable&lt;int&gt; requestedDatabaseDtuMax = null, Nullable&lt;int&gt; requestedDatabaseDtuMin = null, Nullable&lt;int&gt; requestedDtu = null, string requestedElasticPoolName = null, Nullable&lt;long&gt; requestedStorageLimitInGB = null, string elasticPoolName = null, string serverName = null, Nullable&lt;DateTime&gt; startTime = null, string state = null, Nullable&lt;int&gt; requestedStorageLimitInMB = null, Nullable&lt;int&gt; requestedDatabaseDtuGuarantee = null, Nullable&lt;int&gt; requestedDatabaseDtuCap = null, Nullable&lt;int&gt; requestedDtuGuarantee = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, valuetype System.Nullable`1&lt;int32&gt; errorCode, string errorMessage, valuetype System.Nullable`1&lt;int32&gt; errorSeverity, string operation, valuetype System.Guid operationId, valuetype System.Nullable`1&lt;int32&gt; percentComplete, valuetype System.Nullable`1&lt;int32&gt; requestedDatabaseDtuMax, valuetype System.Nullable`1&lt;int32&gt; requestedDatabaseDtuMin, valuetype System.Nullable`1&lt;int32&gt; requestedDtu, string requestedElasticPoolName, valuetype System.Nullable`1&lt;int64&gt; requestedStorageLimitInGB, string elasticPoolName, string serverName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, string state, valuetype System.Nullable`1&lt;int32&gt; requestedStorageLimitInMB, valuetype System.Nullable`1&lt;int32&gt; requestedDatabaseDtuGuarantee, valuetype System.Nullable`1&lt;int32&gt; requestedDatabaseDtuCap, valuetype System.Nullable`1&lt;int32&gt; requestedDtuGuarantee) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.Int32},System.String,System.Nullable{System.Int32},System.String,System.Guid,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.Nullable{System.Int64},System.String,System.String,System.Nullable{System.DateTime},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional endTime As Nullable(Of DateTime) = null, Optional errorCode As Nullable(Of Integer) = null, Optional errorMessage As String = null, Optional errorSeverity As Nullable(Of Integer) = null, Optional operation As String = null, Optional operationId As Guid = null, Optional percentComplete As Nullable(Of Integer) = null, Optional requestedDatabaseDtuMax As Nullable(Of Integer) = null, Optional requestedDatabaseDtuMin As Nullable(Of Integer) = null, Optional requestedDtu As Nullable(Of Integer) = null, Optional requestedElasticPoolName As String = null, Optional requestedStorageLimitInGB As Nullable(Of Long) = null, Optional elasticPoolName As String = null, Optional serverName As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional state As String = null, Optional requestedStorageLimitInMB As Nullable(Of Integer) = null, Optional requestedDatabaseDtuGuarantee As Nullable(Of Integer) = null, Optional requestedDatabaseDtuCap As Nullable(Of Integer) = null, Optional requestedDtuGuarantee As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity : string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * string * Nullable&lt;int&gt; * string * Guid * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * Nullable&lt;int64&gt; * string * string * Nullable&lt;DateTime&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity" Usage="new Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity (id, name, type, location, endTime, errorCode, errorMessage, errorSeverity, operation, operationId, percentComplete, requestedDatabaseDtuMax, requestedDatabaseDtuMin, requestedDtu, requestedElasticPoolName, requestedStorageLimitInGB, elasticPoolName, serverName, startTime, state, requestedStorageLimitInMB, requestedDatabaseDtuGuarantee, requestedDatabaseDtuCap, requestedDtuGuarantee)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="errorCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="errorMessage" Type="System.String" />
        <Parameter Name="errorSeverity" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="percentComplete" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requestedDatabaseDtuMax" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requestedDatabaseDtuMin" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requestedDtu" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requestedElasticPoolName" Type="System.String" />
        <Parameter Name="requestedStorageLimitInGB" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="requestedStorageLimitInMB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requestedDatabaseDtuGuarantee" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requestedDatabaseDtuCap" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requestedDtuGuarantee" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="ea6c0-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="ea6c0-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="ea6c0-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="ea6c0-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="ea6c0-106">リソースが存在する地理的な場所</span><span class="sxs-lookup"><span data-stu-id="ea6c0-106">The geo-location where the resource lives</span></span></param>
        <param name="endTime"><span data-ttu-id="ea6c0-107">操作 (ISO8601 形式) を終了した時刻。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-107">The time the operation finished (ISO8601 format).</span></span></param>
        <param name="errorCode"><span data-ttu-id="ea6c0-108">使用可能な場合は、エラー コード。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-108">The error code if available.</span></span></param>
        <param name="errorMessage"><span data-ttu-id="ea6c0-109">使用可能な場合は、エラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-109">The error message if available.</span></span></param>
        <param name="errorSeverity"><span data-ttu-id="ea6c0-110">エラーの重大度使用可能な場合です。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-110">The error severity if available.</span></span></param>
        <param name="operation"><span data-ttu-id="ea6c0-111">操作の名前です。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-111">The operation name.</span></span></param>
        <param name="operationId"><span data-ttu-id="ea6c0-112">一意の操作 id。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-112">The unique operation ID.</span></span></param>
        <param name="percentComplete"><span data-ttu-id="ea6c0-113">使用可能な場合は、完了の割合。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-113">The percentage complete if available.</span></span></param>
        <param name="requestedDatabaseDtuMax"><span data-ttu-id="ea6c0-114">使用可能な場合、データベースごとの最大 DTU の要求。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-114">The requested max DTU per database if available.</span></span></param>
        <param name="requestedDatabaseDtuMin"><span data-ttu-id="ea6c0-115">使用可能な場合、データベースごとの要求された最小 DTU です。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-115">The requested min DTU per database if available.</span></span></param>
        <param name="requestedDtu"><span data-ttu-id="ea6c0-116">使用可能な場合、プールの DTU の要求。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-116">The requested DTU for the pool if available.</span></span></param>
        <param name="requestedElasticPoolName"><span data-ttu-id="ea6c0-117">要求された使用可能な場合は、弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-117">The requested name for the elastic pool if available.</span></span></param>
        <param name="requestedStorageLimitInGB"><span data-ttu-id="ea6c0-118">プール GB 利用可能な場合に要求記憶域の上限。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-118">The requested storage limit for the pool in GB if available.</span></span></param>
        <param name="elasticPoolName"><span data-ttu-id="ea6c0-119">弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-119">The name of the elastic pool.</span></span></param>
        <param name="serverName"><span data-ttu-id="ea6c0-120">弾力性プールがでは、サーバーの名前です。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-120">The name of the server the elastic pool is in.</span></span></param>
        <param name="startTime"><span data-ttu-id="ea6c0-121">操作 (ISO8601 形式) の開始時刻。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-121">The time the operation started (ISO8601 format).</span></span></param>
        <param name="state"><span data-ttu-id="ea6c0-122">操作の現在の状態。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-122">The current state of the operation.</span></span></param>
        <param name="requestedStorageLimitInMB"><span data-ttu-id="ea6c0-123">Mb 単位で要求記憶域の上限。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-123">The requested storage limit in MB.</span></span></param>
        <param name="requestedDatabaseDtuGuarantee"><span data-ttu-id="ea6c0-124">要求された各データベースの DTU 保証します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-124">The requested per database DTU guarantee.</span></span></param>
        <param name="requestedDatabaseDtuCap"><span data-ttu-id="ea6c0-125">要求されたデータベースの DTU 上限ごとです。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-125">The requested per database DTU cap.</span></span></param>
        <param name="requestedDtuGuarantee"><span data-ttu-id="ea6c0-126">要求した DTU 保証します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-126">The requested DTU guarantee.</span></span></param>
        <summary>
            <span data-ttu-id="ea6c0-127">ElasticPoolActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-127">Initializes a new instance of the ElasticPoolActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElasticPoolName">
      <MemberSignature Language="C#" Value="public string ElasticPoolName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.ElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.ElasticPoolName : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.ElasticPoolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.elasticPoolName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-128">弾力性プールの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-128">Gets the name of the elastic pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-129">操作 (ISO8601 形式) が終了した時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-129">Gets the time the operation finished (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errorCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-130">使用可能な場合は、エラー コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-130">Gets the error code if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errorMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-131">使用可能な場合は、エラー メッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-131">Gets the error message if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorSeverity">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ErrorSeverity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ErrorSeverity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.ErrorSeverity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorSeverity As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ErrorSeverity : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.ErrorSeverity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errorSeverity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-132">使用可能な場合は、エラーの重大度を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-132">Gets the error severity if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-133">取得またはリソースが存在する場所を地理的な場所に設定</span><span class="sxs-lookup"><span data-stu-id="ea6c0-133">Gets or sets the geo-location where the resource lives</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public string Operation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.Operation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operation As String" />
      <MemberSignature Language="F#" Value="member this.Operation : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-134">操作の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-134">Gets the operation name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public Guid OperationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid OperationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationId As Guid" />
      <MemberSignature Language="F#" Value="member this.OperationId : Guid" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.OperationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-135">一意の操作 ID を取得します</span><span class="sxs-lookup"><span data-stu-id="ea6c0-135">Gets the unique operation ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PercentComplete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PercentComplete As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.PercentComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.percentComplete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-136">パーセンテージを取得、完全な使用可能な場合です。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-136">Gets the percentage complete if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedDatabaseDtuCap">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RequestedDatabaseDtuCap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RequestedDatabaseDtuCap" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedDatabaseDtuCap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedDatabaseDtuCap As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RequestedDatabaseDtuCap : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedDatabaseDtuCap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedDatabaseDtuCap")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-137">データベースの DTU 上限あたりの要求を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-137">Gets the requested per database DTU cap.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedDatabaseDtuGuarantee">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RequestedDatabaseDtuGuarantee { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RequestedDatabaseDtuGuarantee" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedDatabaseDtuGuarantee" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedDatabaseDtuGuarantee As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RequestedDatabaseDtuGuarantee : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedDatabaseDtuGuarantee" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedDatabaseDtuGuarantee")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-138">データベースの DTU 保証あたりの要求を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-138">Gets the requested per database DTU guarantee.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedDatabaseDtuMax">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RequestedDatabaseDtuMax { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RequestedDatabaseDtuMax" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedDatabaseDtuMax" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedDatabaseDtuMax As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RequestedDatabaseDtuMax : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedDatabaseDtuMax" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedDatabaseDtuMax")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-139">使用可能な場合、データベースごとの最大 DTU の要求を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-139">Gets the requested max DTU per database if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedDatabaseDtuMin">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RequestedDatabaseDtuMin { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RequestedDatabaseDtuMin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedDatabaseDtuMin" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedDatabaseDtuMin As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RequestedDatabaseDtuMin : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedDatabaseDtuMin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedDatabaseDtuMin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-140">使用可能な場合は、データベースあたりの要求された最小 DTU を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-140">Gets the requested min DTU per database if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedDtu">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RequestedDtu { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RequestedDtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedDtu" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedDtu As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RequestedDtu : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedDtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedDtu")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-141">使用可能な場合、プールの DTU の要求を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-141">Gets the requested DTU for the pool if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedDtuGuarantee">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RequestedDtuGuarantee { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RequestedDtuGuarantee" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedDtuGuarantee" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedDtuGuarantee As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RequestedDtuGuarantee : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedDtuGuarantee" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedDtuGuarantee")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-142">要求した DTU 保証を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-142">Gets the requested DTU guarantee.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedElasticPoolName">
      <MemberSignature Language="C#" Value="public string RequestedElasticPoolName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.RequestedElasticPoolName : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedElasticPoolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedElasticPoolName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-143">使用可能な場合は、弾力性プールの要求された名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-143">Gets the requested name for the elastic pool if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedStorageLimitInGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; RequestedStorageLimitInGB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; RequestedStorageLimitInGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedStorageLimitInGB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedStorageLimitInGB As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RequestedStorageLimitInGB : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedStorageLimitInGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedStorageLimitInGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-144">GB 利用可能な場合に、プールの要求記憶域の上限を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-144">Gets the requested storage limit for the pool in GB if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedStorageLimitInMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RequestedStorageLimitInMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RequestedStorageLimitInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedStorageLimitInMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedStorageLimitInMB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RequestedStorageLimitInMB : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.RequestedStorageLimitInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedStorageLimitInMB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-145">要求記憶域の上限を mb 単位で取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-145">Gets the requested storage limit in MB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerName">
      <MemberSignature Language="C#" Value="public string ServerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.ServerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerName As String" />
      <MemberSignature Language="F#" Value="member this.ServerName : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.ServerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-146">弾力性プールが、サーバーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-146">Gets the name of the server the elastic pool is in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-147">操作 (ISO8601 形式) が開始された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-147">Gets the time the operation started (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolActivity.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea6c0-148">操作の現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="ea6c0-148">Gets the current state of the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>