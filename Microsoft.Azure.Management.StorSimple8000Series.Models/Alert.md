<Type Name="Alert" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert">
  <TypeSignature Language="C#" Value="public class Alert : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Alert extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert" />
  <TypeSignature Language="VB.NET" Value="Public Class Alert&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type Alert = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="7a3ff-101">警告。</span><span class="sxs-lookup"><span data-stu-id="7a3ff-101">The alert.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Alert ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7a3ff-102">アラートのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7a3ff-102">Initializes a new instance of the Alert class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Alert (string title, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope scope, string alertType, DateTime appearedAtTime, DateTime appearedAtSourceTime, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource source, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity severity, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus status, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Nullable&lt;DateTime&gt; clearedAtTime = null, Nullable&lt;DateTime&gt; clearedAtSourceTime = null, string recommendation = null, string resolutionReason = null, Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails errorDetails = null, System.Collections.Generic.IDictionary&lt;string,string&gt; detailedInformation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string title, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope scope, string alertType, valuetype System.DateTime appearedAtTime, valuetype System.DateTime appearedAtSourceTime, class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource source, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity severity, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus status, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; clearedAtTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; clearedAtSourceTime, string recommendation, string resolutionReason, class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails errorDetails, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; detailedInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.#ctor(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope,System.String,System.DateTime,System.DateTime,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (title As String, scope As AlertScope, alertType As String, appearedAtTime As DateTime, appearedAtSourceTime As DateTime, source As AlertSource, severity As AlertSeverity, status As AlertStatus, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null, Optional clearedAtTime As Nullable(Of DateTime) = null, Optional clearedAtSourceTime As Nullable(Of DateTime) = null, Optional recommendation As String = null, Optional resolutionReason As String = null, Optional errorDetails As AlertErrorDetails = null, Optional detailedInformation As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.Alert : string * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope * string * DateTime * DateTime * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Alert" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.Alert (title, scope, alertType, appearedAtTime, appearedAtSourceTime, source, severity, status, id, name, type, kind, clearedAtTime, clearedAtSourceTime, recommendation, resolutionReason, errorDetails, detailedInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="title" Type="System.String" />
        <Parameter Name="scope" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope" />
        <Parameter Name="alertType" Type="System.String" />
        <Parameter Name="appearedAtTime" Type="System.DateTime" />
        <Parameter Name="appearedAtSourceTime" Type="System.DateTime" />
        <Parameter Name="source" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource" />
        <Parameter Name="severity" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="clearedAtTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="clearedAtSourceTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="recommendation" Type="System.String" />
        <Parameter Name="resolutionReason" Type="System.String" />
        <Parameter Name="errorDetails" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails" />
        <Parameter Name="detailedInformation" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="title"><span data-ttu-id="7a3ff-103">警告のタイトル</span><span class="sxs-lookup"><span data-stu-id="7a3ff-103">The title of the alert</span></span></param>
        <param name="scope"><span data-ttu-id="7a3ff-104">アラートのスコープです。</span><span class="sxs-lookup"><span data-stu-id="7a3ff-104">The scope of the alert.</span></span> <span data-ttu-id="7a3ff-105">使用可能な値が含まれます: 'Resource'、'デバイス'</span><span class="sxs-lookup"><span data-stu-id="7a3ff-105">Possible values include: 'Resource', 'Device'</span></span></param>
        <param name="alertType"><span data-ttu-id="7a3ff-106">アラートの種類</span><span class="sxs-lookup"><span data-stu-id="7a3ff-106">The type of the alert</span></span></param>
        <param name="appearedAtTime"><span data-ttu-id="7a3ff-107">アラートが発生した UTC 時刻</span><span class="sxs-lookup"><span data-stu-id="7a3ff-107">The UTC time at which the alert was raised</span></span></param>
        <param name="appearedAtSourceTime"><span data-ttu-id="7a3ff-108">アラートが発生した、元の時刻</span><span class="sxs-lookup"><span data-stu-id="7a3ff-108">The source time at which the alert was raised</span></span></param>
        <param name="source"><span data-ttu-id="7a3ff-109">アラートが発生したソース</span><span class="sxs-lookup"><span data-stu-id="7a3ff-109">The source at which the alert was raised</span></span></param>
        <param name="severity"><span data-ttu-id="7a3ff-110">アラートの重大度。</span><span class="sxs-lookup"><span data-stu-id="7a3ff-110">The severity of the alert.</span></span> <span data-ttu-id="7a3ff-111">使用可能な値が含まれます: '情報'、'警告'、'重大'</span><span class="sxs-lookup"><span data-stu-id="7a3ff-111">Possible values include: 'Informational', 'Warning', 'Critical'</span></span></param>
        <param name="status"><span data-ttu-id="7a3ff-112">警告の現在の状態。</span><span class="sxs-lookup"><span data-stu-id="7a3ff-112">The current status of the alert.</span></span> <span data-ttu-id="7a3ff-113">使用可能な値が含まれます: 'Active'、'オフ'</span><span class="sxs-lookup"><span data-stu-id="7a3ff-113">Possible values include: 'Active', 'Cleared'</span></span></param>
        <param name="id"><span data-ttu-id="7a3ff-114">オブジェクトを一意に識別するパス ID です。</span><span class="sxs-lookup"><span data-stu-id="7a3ff-114">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="7a3ff-115">オブジェクトの名前。</span><span class="sxs-lookup"><span data-stu-id="7a3ff-115">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="7a3ff-116">オブジェクトの階層型です。</span><span class="sxs-lookup"><span data-stu-id="7a3ff-116">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="7a3ff-117">オブジェクトの種類。</span><span class="sxs-lookup"><span data-stu-id="7a3ff-117">The Kind of the object.</span></span> <span data-ttu-id="7a3ff-118">現在は Series8000 はサポートされています。</span><span class="sxs-lookup"><span data-stu-id="7a3ff-118">Currently only Series8000 is supported.</span></span> <span data-ttu-id="7a3ff-119">使用可能な値が含まれます: 'Series8000'</span><span class="sxs-lookup"><span data-stu-id="7a3ff-119">Possible values include: 'Series8000'</span></span></param>
        <param name="clearedAtTime"><span data-ttu-id="7a3ff-120">UTC 時刻に警告が消去されました</span><span class="sxs-lookup"><span data-stu-id="7a3ff-120">The UTC time at which the alert was cleared</span></span></param>
        <param name="clearedAtSourceTime"><span data-ttu-id="7a3ff-121">元の時刻、警告が消去されました</span><span class="sxs-lookup"><span data-stu-id="7a3ff-121">The source time at which the alert was cleared</span></span></param>
        <param name="recommendation"><span data-ttu-id="7a3ff-122">アラートの発生した問題の推奨される操作</span><span class="sxs-lookup"><span data-stu-id="7a3ff-122">The recommended action for the issue raised in the alert</span></span></param>
        <param name="resolutionReason"><span data-ttu-id="7a3ff-123">アラートの解決理由</span><span class="sxs-lookup"><span data-stu-id="7a3ff-123">The reason for resolving the alert</span></span></param>
        <param name="errorDetails"><span data-ttu-id="7a3ff-124">アラートが発生したエラーの詳細</span><span class="sxs-lookup"><span data-stu-id="7a3ff-124">The details of the error for which the alert was raised</span></span></param>
        <param name="detailedInformation"><span data-ttu-id="7a3ff-125">アラートの詳細について</span><span class="sxs-lookup"><span data-stu-id="7a3ff-125">More details about the alert</span></span></param>
        <summary>
            <span data-ttu-id="7a3ff-126">アラートのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7a3ff-126">Initializes a new instance of the Alert class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlertType">
      <MemberSignature Language="C#" Value="public string AlertType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AlertType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AlertType" />
      <MemberSignature Language="VB.NET" Value="Public Property AlertType As String" />
      <MemberSignature Language="F#" Value="member this.AlertType : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AlertType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.alertType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a3ff-127">取得または設定、アラートの種類</span><span class="sxs-lookup"><span data-stu-id="7a3ff-127">Gets or sets the type of the alert</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppearedAtSourceTime">
      <MemberSignature Language="C#" Value="public DateTime AppearedAtSourceTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AppearedAtSourceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AppearedAtSourceTime" />
      <MemberSignature Language="VB.NET" Value="Public Property AppearedAtSourceTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.AppearedAtSourceTime : DateTime with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AppearedAtSourceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appearedAtSourceTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a3ff-128">取得またはアラートが発生した、元の時刻の設定</span><span class="sxs-lookup"><span data-stu-id="7a3ff-128">Gets or sets the source time at which the alert was raised</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppearedAtTime">
      <MemberSignature Language="C#" Value="public DateTime AppearedAtTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AppearedAtTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AppearedAtTime" />
      <MemberSignature Language="VB.NET" Value="Public Property AppearedAtTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.AppearedAtTime : DateTime with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.AppearedAtTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.appearedAtTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a3ff-129">取得またはアラートが発生した UTC 時刻の設定</span><span class="sxs-lookup"><span data-stu-id="7a3ff-129">Gets or sets the UTC time at which the alert was raised</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearedAtSourceTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ClearedAtSourceTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ClearedAtSourceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ClearedAtSourceTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ClearedAtSourceTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ClearedAtSourceTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ClearedAtSourceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clearedAtSourceTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a3ff-130">取得または設定、元の時刻、警告が消去されました</span><span class="sxs-lookup"><span data-stu-id="7a3ff-130">Gets or sets the source time at which the alert was cleared</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearedAtTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ClearedAtTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ClearedAtTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ClearedAtTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ClearedAtTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ClearedAtTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ClearedAtTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clearedAtTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a3ff-131">取得または設定の UTC 時刻に警告が消去されました</span><span class="sxs-lookup"><span data-stu-id="7a3ff-131">Gets or sets the UTC time at which the alert was cleared</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetailedInformation">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; DetailedInformation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; DetailedInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.DetailedInformation" />
      <MemberSignature Language="VB.NET" Value="Public Property DetailedInformation As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.DetailedInformation : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.DetailedInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.detailedInformation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a3ff-132">取得または設定、アラートに関する詳細</span><span class="sxs-lookup"><span data-stu-id="7a3ff-132">Gets or sets more details about the alert</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails ErrorDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails ErrorDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ErrorDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorDetails As AlertErrorDetails" />
      <MemberSignature Language="F#" Value="member this.ErrorDetails : Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ErrorDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errorDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertErrorDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a3ff-133">取得または設定のアラートが発生したエラーの詳細</span><span class="sxs-lookup"><span data-stu-id="7a3ff-133">Gets or sets the details of the error for which the alert was raised</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recommendation">
      <MemberSignature Language="C#" Value="public string Recommendation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Recommendation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Recommendation" />
      <MemberSignature Language="VB.NET" Value="Public Property Recommendation As String" />
      <MemberSignature Language="F#" Value="member this.Recommendation : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Recommendation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recommendation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a3ff-134">取得または設定、アラートの発生した問題の推奨される操作</span><span class="sxs-lookup"><span data-stu-id="7a3ff-134">Gets or sets the recommended action for the issue raised in the alert</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolutionReason">
      <MemberSignature Language="C#" Value="public string ResolutionReason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResolutionReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ResolutionReason" />
      <MemberSignature Language="VB.NET" Value="Public Property ResolutionReason As String" />
      <MemberSignature Language="F#" Value="member this.ResolutionReason : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.ResolutionReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resolutionReason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a3ff-135">取得または設定、アラートの解決理由</span><span class="sxs-lookup"><span data-stu-id="7a3ff-135">Gets or sets the reason for resolving the alert</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scope">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope Scope { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope Scope" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Scope" />
      <MemberSignature Language="VB.NET" Value="Public Property Scope As AlertScope" />
      <MemberSignature Language="F#" Value="member this.Scope : Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Scope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scope")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a3ff-136">取得またはアラートのスコープを設定します。</span><span class="sxs-lookup"><span data-stu-id="7a3ff-136">Gets or sets the scope of the alert.</span></span> <span data-ttu-id="7a3ff-137">使用可能な値が含まれます: 'Resource'、'デバイス'</span><span class="sxs-lookup"><span data-stu-id="7a3ff-137">Possible values include: 'Resource', 'Device'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Severity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity Severity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity Severity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Severity" />
      <MemberSignature Language="VB.NET" Value="Public Property Severity As AlertSeverity" />
      <MemberSignature Language="F#" Value="member this.Severity : Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Severity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.severity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSeverity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a3ff-138">取得またはアラートの重要度を設定します。</span><span class="sxs-lookup"><span data-stu-id="7a3ff-138">Gets or sets the severity of the alert.</span></span> <span data-ttu-id="7a3ff-139">使用可能な値が含まれます: '情報'、'警告'、'重大'</span><span class="sxs-lookup"><span data-stu-id="7a3ff-139">Possible values include: 'Informational', 'Warning', 'Critical'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As AlertSource" />
      <MemberSignature Language="F#" Value="member this.Source : Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertSource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a3ff-140">アラートが発生したソース取得または設定</span><span class="sxs-lookup"><span data-stu-id="7a3ff-140">Gets or sets the source at which the alert was raised</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As AlertStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AlertStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a3ff-141">取得または警告の現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="7a3ff-141">Gets or sets the current status of the alert.</span></span> <span data-ttu-id="7a3ff-142">使用可能な値が含まれます: 'Active'、'オフ'</span><span class="sxs-lookup"><span data-stu-id="7a3ff-142">Possible values include: 'Active', 'Cleared'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Title">
      <MemberSignature Language="C#" Value="public string Title { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Title" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Title" />
      <MemberSignature Language="VB.NET" Value="Public Property Title As String" />
      <MemberSignature Language="F#" Value="member this.Title : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Title" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.title")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7a3ff-143">取得または警告のタイトルを設定</span><span class="sxs-lookup"><span data-stu-id="7a3ff-143">Gets or sets the title of the alert</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Alert.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="alert.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7a3ff-144">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="7a3ff-144">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7a3ff-145">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7a3ff-145">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>