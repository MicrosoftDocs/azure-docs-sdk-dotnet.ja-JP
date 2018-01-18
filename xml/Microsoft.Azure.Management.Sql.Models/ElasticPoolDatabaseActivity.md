<Type Name="ElasticPoolDatabaseActivity" FullName="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity">
  <TypeSignature Language="C#" Value="public class ElasticPoolDatabaseActivity : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ElasticPoolDatabaseActivity extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class ElasticPoolDatabaseActivity&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type ElasticPoolDatabaseActivity = class&#xA;    inherit ProxyResource" />
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
            <span data-ttu-id="f72ca-101">弾力性プールの利用状況を表します。</span><span class="sxs-lookup"><span data-stu-id="f72ca-101">Represents the activity on an elastic pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolDatabaseActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f72ca-102">ElasticPoolDatabaseActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f72ca-102">Initializes a new instance of the ElasticPoolDatabaseActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolDatabaseActivity (string id = null, string name = null, string type = null, string location = null, string databaseName = null, Nullable&lt;DateTime&gt; endTime = null, Nullable&lt;int&gt; errorCode = null, string errorMessage = null, Nullable&lt;int&gt; errorSeverity = null, string operation = null, Guid operationId = null, Nullable&lt;int&gt; percentComplete = null, string requestedElasticPoolName = null, string currentElasticPoolName = null, string currentServiceObjective = null, string requestedServiceObjective = null, string serverName = null, Nullable&lt;DateTime&gt; startTime = null, string state = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, string databaseName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, valuetype System.Nullable`1&lt;int32&gt; errorCode, string errorMessage, valuetype System.Nullable`1&lt;int32&gt; errorSeverity, string operation, valuetype System.Guid operationId, valuetype System.Nullable`1&lt;int32&gt; percentComplete, string requestedElasticPoolName, string currentElasticPoolName, string currentServiceObjective, string requestedServiceObjective, string serverName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, string state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.Int32},System.String,System.Nullable{System.Int32},System.String,System.Guid,System.Nullable{System.Int32},System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional databaseName As String = null, Optional endTime As Nullable(Of DateTime) = null, Optional errorCode As Nullable(Of Integer) = null, Optional errorMessage As String = null, Optional errorSeverity As Nullable(Of Integer) = null, Optional operation As String = null, Optional operationId As Guid = null, Optional percentComplete As Nullable(Of Integer) = null, Optional requestedElasticPoolName As String = null, Optional currentElasticPoolName As String = null, Optional currentServiceObjective As String = null, Optional requestedServiceObjective As String = null, Optional serverName As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional state As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity : string * string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * string * Nullable&lt;int&gt; * string * Guid * Nullable&lt;int&gt; * string * string * string * string * string * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity" Usage="new Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity (id, name, type, location, databaseName, endTime, errorCode, errorMessage, errorSeverity, operation, operationId, percentComplete, requestedElasticPoolName, currentElasticPoolName, currentServiceObjective, requestedServiceObjective, serverName, startTime, state)" />
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
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="errorCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="errorMessage" Type="System.String" />
        <Parameter Name="errorSeverity" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="percentComplete" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requestedElasticPoolName" Type="System.String" />
        <Parameter Name="currentElasticPoolName" Type="System.String" />
        <Parameter Name="currentServiceObjective" Type="System.String" />
        <Parameter Name="requestedServiceObjective" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="state" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="f72ca-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="f72ca-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="f72ca-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="f72ca-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="f72ca-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="f72ca-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="f72ca-106">リソースが存在する地理的な場所</span><span class="sxs-lookup"><span data-stu-id="f72ca-106">The geo-location where the resource lives</span></span></param>
        <param name="databaseName"><span data-ttu-id="f72ca-107">データベース名。</span><span class="sxs-lookup"><span data-stu-id="f72ca-107">The database name.</span></span></param>
        <param name="endTime"><span data-ttu-id="f72ca-108">操作 (ISO8601 形式) を終了した時刻。</span><span class="sxs-lookup"><span data-stu-id="f72ca-108">The time the operation finished (ISO8601 format).</span></span></param>
        <param name="errorCode"><span data-ttu-id="f72ca-109">使用可能な場合は、エラー コード。</span><span class="sxs-lookup"><span data-stu-id="f72ca-109">The error code if available.</span></span></param>
        <param name="errorMessage"><span data-ttu-id="f72ca-110">使用可能な場合は、エラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="f72ca-110">The error message if available.</span></span></param>
        <param name="errorSeverity"><span data-ttu-id="f72ca-111">エラーの重大度使用可能な場合です。</span><span class="sxs-lookup"><span data-stu-id="f72ca-111">The error severity if available.</span></span></param>
        <param name="operation"><span data-ttu-id="f72ca-112">操作の名前です。</span><span class="sxs-lookup"><span data-stu-id="f72ca-112">The operation name.</span></span></param>
        <param name="operationId"><span data-ttu-id="f72ca-113">一意の操作 id。</span><span class="sxs-lookup"><span data-stu-id="f72ca-113">The unique operation ID.</span></span></param>
        <param name="percentComplete"><span data-ttu-id="f72ca-114">使用可能な場合は、完了の割合。</span><span class="sxs-lookup"><span data-stu-id="f72ca-114">The percentage complete if available.</span></span></param>
        <param name="requestedElasticPoolName"><span data-ttu-id="f72ca-115">使用可能な場合は、弾力性プール データベースの名前をへ移動します。</span><span class="sxs-lookup"><span data-stu-id="f72ca-115">The name for the elastic pool the database is moving into if available.</span></span></param>
        <param name="currentElasticPoolName"><span data-ttu-id="f72ca-116">場合に、現在の弾力性プールの名前、データベースが使用できます。</span><span class="sxs-lookup"><span data-stu-id="f72ca-116">The name of the current elastic pool the database is in if available.</span></span></param>
        <param name="currentServiceObjective"><span data-ttu-id="f72ca-117">使用可能な場合は、現在のサービス目標の名前。</span><span class="sxs-lookup"><span data-stu-id="f72ca-117">The name of the current service objective if available.</span></span></param>
        <param name="requestedServiceObjective"><span data-ttu-id="f72ca-118">使用可能な場合は、要求されたサービス目標の名前。</span><span class="sxs-lookup"><span data-stu-id="f72ca-118">The name of the requested service objective if available.</span></span></param>
        <param name="serverName"><span data-ttu-id="f72ca-119">弾力性プールがでは、サーバーの名前です。</span><span class="sxs-lookup"><span data-stu-id="f72ca-119">The name of the server the elastic pool is in.</span></span></param>
        <param name="startTime"><span data-ttu-id="f72ca-120">操作 (ISO8601 形式) の開始時刻。</span><span class="sxs-lookup"><span data-stu-id="f72ca-120">The time the operation started (ISO8601 format).</span></span></param>
        <param name="state"><span data-ttu-id="f72ca-121">操作の現在の状態。</span><span class="sxs-lookup"><span data-stu-id="f72ca-121">The current state of the operation.</span></span></param>
        <summary>
            <span data-ttu-id="f72ca-122">ElasticPoolDatabaseActivity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f72ca-122">Initializes a new instance of the ElasticPoolDatabaseActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentElasticPoolName">
      <MemberSignature Language="C#" Value="public string CurrentElasticPoolName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.CurrentElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.CurrentElasticPoolName : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.CurrentElasticPoolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentElasticPoolName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f72ca-123">場合に、データベースは、現在のエラスティック プールの名前を取得使用できます。</span><span class="sxs-lookup"><span data-stu-id="f72ca-123">Gets the name of the current elastic pool the database is in if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentServiceObjective">
      <MemberSignature Language="C#" Value="public string CurrentServiceObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentServiceObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.CurrentServiceObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentServiceObjective As String" />
      <MemberSignature Language="F#" Value="member this.CurrentServiceObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.CurrentServiceObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentServiceObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f72ca-124">使用可能な場合は、現在のサービス目標の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="f72ca-124">Gets the name of the current service objective if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f72ca-125">データベース名を取得します。</span><span class="sxs-lookup"><span data-stu-id="f72ca-125">Gets the database name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.EndTime" />
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
            <span data-ttu-id="f72ca-126">操作 (ISO8601 形式) が終了した時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="f72ca-126">Gets the time the operation finished (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.ErrorCode" />
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
            <span data-ttu-id="f72ca-127">使用可能な場合は、エラー コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="f72ca-127">Gets the error code if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.ErrorMessage" />
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
            <span data-ttu-id="f72ca-128">使用可能な場合は、エラー メッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="f72ca-128">Gets the error message if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorSeverity">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ErrorSeverity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ErrorSeverity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.ErrorSeverity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorSeverity As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ErrorSeverity : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.ErrorSeverity" />
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
            <span data-ttu-id="f72ca-129">使用可能な場合は、エラーの重大度を取得します。</span><span class="sxs-lookup"><span data-stu-id="f72ca-129">Gets the error severity if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.Location" />
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
            <span data-ttu-id="f72ca-130">取得またはリソースが存在する場所を地理的な場所に設定</span><span class="sxs-lookup"><span data-stu-id="f72ca-130">Gets or sets the geo-location where the resource lives</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public string Operation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.Operation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operation As String" />
      <MemberSignature Language="F#" Value="member this.Operation : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.Operation" />
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
            <span data-ttu-id="f72ca-131">操作の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="f72ca-131">Gets the operation name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public Guid OperationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid OperationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationId As Guid" />
      <MemberSignature Language="F#" Value="member this.OperationId : Guid" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.OperationId" />
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
            <span data-ttu-id="f72ca-132">一意の操作 ID を取得します</span><span class="sxs-lookup"><span data-stu-id="f72ca-132">Gets the unique operation ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PercentComplete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PercentComplete As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.PercentComplete" />
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
            <span data-ttu-id="f72ca-133">パーセンテージを取得、完全な使用可能な場合です。</span><span class="sxs-lookup"><span data-stu-id="f72ca-133">Gets the percentage complete if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedElasticPoolName">
      <MemberSignature Language="C#" Value="public string RequestedElasticPoolName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.RequestedElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.RequestedElasticPoolName : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.RequestedElasticPoolName" />
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
            <span data-ttu-id="f72ca-134">データベースは、使用可能な場合に移行弾力性プールの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="f72ca-134">Gets the name for the elastic pool the database is moving into if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedServiceObjective">
      <MemberSignature Language="C#" Value="public string RequestedServiceObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedServiceObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.RequestedServiceObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedServiceObjective As String" />
      <MemberSignature Language="F#" Value="member this.RequestedServiceObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.RequestedServiceObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedServiceObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f72ca-135">使用可能な場合は、要求されたサービス目標の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="f72ca-135">Gets the name of the requested service objective if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerName">
      <MemberSignature Language="C#" Value="public string ServerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.ServerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerName As String" />
      <MemberSignature Language="F#" Value="member this.ServerName : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.ServerName" />
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
            <span data-ttu-id="f72ca-136">弾力性プールが、サーバーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="f72ca-136">Gets the name of the server the elastic pool is in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.StartTime" />
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
            <span data-ttu-id="f72ca-137">操作 (ISO8601 形式) が開始された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="f72ca-137">Gets the time the operation started (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.State" />
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
            <span data-ttu-id="f72ca-138">操作の現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f72ca-138">Gets the current state of the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>