<Type Name="ElasticPoolActivityInner" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner">
  <TypeSignature Language="C#" Value="public class ElasticPoolActivityInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ElasticPoolActivityInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ElasticPoolActivityInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ElasticPoolActivityInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e2f59-101">Azure SQL 弾力性プールの利用状況を表します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-101">Represents the activity on an Azure SQL Elastic Pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolActivityInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e2f59-102">ElasticPoolActivityInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-102">Initializes a new instance of the ElasticPoolActivityInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolActivityInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;DateTime&gt; endTime = null, Nullable&lt;int&gt; errorCode = null, string errorMessage = null, Nullable&lt;int&gt; errorSeverity = null, string operation = null, string operationId = null, Nullable&lt;int&gt; percentComplete = null, Nullable&lt;int&gt; requestedDatabaseDtuMax = null, Nullable&lt;int&gt; requestedDatabaseDtuMin = null, Nullable&lt;int&gt; requestedDtu = null, string requestedElasticPoolName = null, Nullable&lt;long&gt; requestedStorageLimitInGB = null, string elasticPoolName = null, string serverName = null, Nullable&lt;DateTime&gt; startTime = null, string state = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, valuetype System.Nullable`1&lt;int32&gt; errorCode, string errorMessage, valuetype System.Nullable`1&lt;int32&gt; errorSeverity, string operation, string operationId, valuetype System.Nullable`1&lt;int32&gt; percentComplete, valuetype System.Nullable`1&lt;int32&gt; requestedDatabaseDtuMax, valuetype System.Nullable`1&lt;int32&gt; requestedDatabaseDtuMin, valuetype System.Nullable`1&lt;int32&gt; requestedDtu, string requestedElasticPoolName, valuetype System.Nullable`1&lt;int64&gt; requestedStorageLimitInGB, string elasticPoolName, string serverName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, string state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.DateTime},System.Nullable{System.Int32},System.String,System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.Nullable{System.Int64},System.String,System.String,System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional endTime As Nullable(Of DateTime) = null, Optional errorCode As Nullable(Of Integer) = null, Optional errorMessage As String = null, Optional errorSeverity As Nullable(Of Integer) = null, Optional operation As String = null, Optional operationId As String = null, Optional percentComplete As Nullable(Of Integer) = null, Optional requestedDatabaseDtuMax As Nullable(Of Integer) = null, Optional requestedDatabaseDtuMin As Nullable(Of Integer) = null, Optional requestedDtu As Nullable(Of Integer) = null, Optional requestedElasticPoolName As String = null, Optional requestedStorageLimitInGB As Nullable(Of Long) = null, Optional elasticPoolName As String = null, Optional serverName As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional state As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * string * Nullable&lt;int&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * Nullable&lt;int64&gt; * string * string * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner (location, id, name, type, tags, endTime, errorCode, errorMessage, errorSeverity, operation, operationId, percentComplete, requestedDatabaseDtuMax, requestedDatabaseDtuMin, requestedDtu, requestedElasticPoolName, requestedStorageLimitInGB, elasticPoolName, serverName, startTime, state)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="errorCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="errorMessage" Type="System.String" />
        <Parameter Name="errorSeverity" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
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
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="endTime"><span data-ttu-id="e2f59-103">操作 (ISO8601 形式) を終了した時刻。</span><span class="sxs-lookup"><span data-stu-id="e2f59-103">The time the operation finished (ISO8601 format).</span></span></param>
        <param name="errorCode"><span data-ttu-id="e2f59-104">使用可能な場合は、エラー コード。</span><span class="sxs-lookup"><span data-stu-id="e2f59-104">The error code if available.</span></span></param>
        <param name="errorMessage"><span data-ttu-id="e2f59-105">使用可能な場合は、エラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e2f59-105">The error message if available.</span></span></param>
        <param name="errorSeverity"><span data-ttu-id="e2f59-106">エラーの重大度使用可能な場合です。</span><span class="sxs-lookup"><span data-stu-id="e2f59-106">The error severity if available.</span></span></param>
        <param name="operation"><span data-ttu-id="e2f59-107">操作の名前です。</span><span class="sxs-lookup"><span data-stu-id="e2f59-107">The operation name.</span></span></param>
        <param name="operationId"><span data-ttu-id="e2f59-108">一意の操作 id。</span><span class="sxs-lookup"><span data-stu-id="e2f59-108">The unique operation ID.</span></span></param>
        <param name="percentComplete"><span data-ttu-id="e2f59-109">使用可能な場合は、完了の割合。</span><span class="sxs-lookup"><span data-stu-id="e2f59-109">The percentage complete if available.</span></span></param>
        <param name="requestedDatabaseDtuMax"><span data-ttu-id="e2f59-110">使用可能な場合、データベースごとの最大 DTU の要求。</span><span class="sxs-lookup"><span data-stu-id="e2f59-110">The requested max DTU per database if available.</span></span></param>
        <param name="requestedDatabaseDtuMin"><span data-ttu-id="e2f59-111">使用可能な場合、データベースごとの要求された最小 DTU です。</span><span class="sxs-lookup"><span data-stu-id="e2f59-111">The requested min DTU per database if available.</span></span></param>
        <param name="requestedDtu"><span data-ttu-id="e2f59-112">使用可能な場合、プールの DTU の要求。</span><span class="sxs-lookup"><span data-stu-id="e2f59-112">The requested DTU for the pool if available.</span></span></param>
        <param name="requestedElasticPoolName"><span data-ttu-id="e2f59-113">要求された使用可能な場合は、弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="e2f59-113">The requested name for the Elastic Pool if available.</span></span></param>
        <param name="requestedStorageLimitInGB"><span data-ttu-id="e2f59-114">プール GB 利用可能な場合に要求記憶域の上限。</span><span class="sxs-lookup"><span data-stu-id="e2f59-114">The requested storage limit for the pool in GB if available.</span></span></param>
        <param name="elasticPoolName"><span data-ttu-id="e2f59-115">弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="e2f59-115">The name of the Elastic Pool.</span></span></param>
        <param name="serverName"><span data-ttu-id="e2f59-116">Azure SQL サーバー、弾力性プールの名前です。</span><span class="sxs-lookup"><span data-stu-id="e2f59-116">The name of the Azure SQL server the Elastic Pool is in.</span></span></param>
        <param name="startTime"><span data-ttu-id="e2f59-117">操作 (ISO8601 形式) の開始時刻。</span><span class="sxs-lookup"><span data-stu-id="e2f59-117">The time the operation started (ISO8601 format).</span></span></param>
        <param name="state"><span data-ttu-id="e2f59-118">操作の現在の状態。</span><span class="sxs-lookup"><span data-stu-id="e2f59-118">The current state of the operation.</span></span></param>
        <summary>
            <span data-ttu-id="e2f59-119">ElasticPoolActivityInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-119">Initializes a new instance of the ElasticPoolActivityInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElasticPoolName">
      <MemberSignature Language="C#" Value="public string ElasticPoolName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.ElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.ElasticPoolName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.ElasticPoolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2f59-120">弾力性プールの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-120">Gets the name of the Elastic Pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2f59-121">操作 (ISO8601 形式) が終了した時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-121">Gets the time the operation finished (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2f59-122">使用可能な場合は、エラー コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-122">Gets the error code if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2f59-123">使用可能な場合は、エラー メッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-123">Gets the error message if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorSeverity">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ErrorSeverity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ErrorSeverity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.ErrorSeverity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorSeverity As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ErrorSeverity : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.ErrorSeverity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2f59-124">使用可能な場合は、エラーの重大度を取得します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-124">Gets the error severity if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public string Operation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.Operation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operation As String" />
      <MemberSignature Language="F#" Value="member this.Operation : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2f59-125">操作の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-125">Gets the operation name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public string OperationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationId As String" />
      <MemberSignature Language="F#" Value="member this.OperationId : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.OperationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e2f59-126">一意の操作 ID を取得します</span><span class="sxs-lookup"><span data-stu-id="e2f59-126">Gets the unique operation ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PercentComplete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PercentComplete As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.PercentComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2f59-127">パーセンテージを取得、完全な使用可能な場合です。</span><span class="sxs-lookup"><span data-stu-id="e2f59-127">Gets the percentage complete if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedDatabaseDtuMax">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RequestedDatabaseDtuMax { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RequestedDatabaseDtuMax" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.RequestedDatabaseDtuMax" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedDatabaseDtuMax As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RequestedDatabaseDtuMax : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.RequestedDatabaseDtuMax" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2f59-128">使用可能な場合、データベースごとの最大 DTU の要求を取得します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-128">Gets the requested max DTU per database if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedDatabaseDtuMin">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RequestedDatabaseDtuMin { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RequestedDatabaseDtuMin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.RequestedDatabaseDtuMin" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedDatabaseDtuMin As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RequestedDatabaseDtuMin : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.RequestedDatabaseDtuMin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2f59-129">使用可能な場合は、データベースあたりの要求された最小 DTU を取得します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-129">Gets the requested min DTU per database if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedDtu">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RequestedDtu { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RequestedDtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.RequestedDtu" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedDtu As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RequestedDtu : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.RequestedDtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2f59-130">使用可能な場合、プールの DTU の要求を取得します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-130">Gets the requested DTU for the pool if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedElasticPoolName">
      <MemberSignature Language="C#" Value="public string RequestedElasticPoolName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.RequestedElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.RequestedElasticPoolName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.RequestedElasticPoolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2f59-131">使用可能な場合は、弾力性プールの要求された名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-131">Gets the requested name for the Elastic Pool if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedStorageLimitInGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; RequestedStorageLimitInGB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; RequestedStorageLimitInGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.RequestedStorageLimitInGB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedStorageLimitInGB As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RequestedStorageLimitInGB : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.RequestedStorageLimitInGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2f59-132">GB 利用可能な場合に、プールの要求記憶域の上限を取得します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-132">Gets the requested storage limit for the pool in GB if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerName">
      <MemberSignature Language="C#" Value="public string ServerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.ServerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerName As String" />
      <MemberSignature Language="F#" Value="member this.ServerName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.ServerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2f59-133">弾力性プールが、Azure SQL サーバーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-133">Gets the name of the Azure SQL server the Elastic Pool is in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2f59-134">操作 (ISO8601 形式) が開始された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-134">Gets the time the operation started (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolActivityInner.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e2f59-135">操作の現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="e2f59-135">Gets the current state of the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>