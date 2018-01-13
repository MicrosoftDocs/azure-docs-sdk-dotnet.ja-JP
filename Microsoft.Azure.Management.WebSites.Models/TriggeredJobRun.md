<Type Name="TriggeredJobRun" FullName="Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun">
  <TypeSignature Language="C#" Value="public class TriggeredJobRun : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TriggeredJobRun extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun" />
  <TypeSignature Language="VB.NET" Value="Public Class TriggeredJobRun&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type TriggeredJobRun = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="87307-101">トリガーされた Web ジョブは、情報を実行します。</span><span class="sxs-lookup"><span data-stu-id="87307-101">Triggered Web Job Run Information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TriggeredJobRun ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="87307-102">TriggeredJobRun クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="87307-102">Initializes a new instance of the TriggeredJobRun class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TriggeredJobRun (string id = null, string name = null, string kind = null, string type = null, string triggeredJobRunId = null, string triggeredJobRunName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.TriggeredWebJobStatus&gt; status = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, string duration = null, string outputUrl = null, string errorUrl = null, string url = null, string jobName = null, string trigger = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string triggeredJobRunId, string triggeredJobRunName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.TriggeredWebJobStatus&gt; status, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string duration, string outputUrl, string errorUrl, string url, string jobName, string trigger) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.TriggeredWebJobStatus},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional triggeredJobRunId As String = null, Optional triggeredJobRunName As String = null, Optional status As Nullable(Of TriggeredWebJobStatus) = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional duration As String = null, Optional outputUrl As String = null, Optional errorUrl As String = null, Optional url As String = null, Optional jobName As String = null, Optional trigger As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun : string * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.TriggeredWebJobStatus&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun" Usage="new Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun (id, name, kind, type, triggeredJobRunId, triggeredJobRunName, status, startTime, endTime, duration, outputUrl, errorUrl, url, jobName, trigger)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="triggeredJobRunId" Type="System.String" />
        <Parameter Name="triggeredJobRunName" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.TriggeredWebJobStatus&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="duration" Type="System.String" />
        <Parameter Name="outputUrl" Type="System.String" />
        <Parameter Name="errorUrl" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="trigger" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="87307-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="87307-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="87307-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="87307-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="87307-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="87307-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="87307-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="87307-106">Resource type.</span></span></param>
        <param name="triggeredJobRunId"><span data-ttu-id="87307-107">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="87307-107">Job ID.</span></span></param>
        <param name="triggeredJobRunName"><span data-ttu-id="87307-108">ジョブ名です。</span><span class="sxs-lookup"><span data-stu-id="87307-108">Job name.</span></span></param>
        <param name="status"><span data-ttu-id="87307-109">ジョブの状態。</span><span class="sxs-lookup"><span data-stu-id="87307-109">Job status.</span></span> <span data-ttu-id="87307-110">使用可能な値が含まれます: 'は Success'、'失敗'、'Error'</span><span class="sxs-lookup"><span data-stu-id="87307-110">Possible values include: 'Success', 'Failed', 'Error'</span></span></param>
        <param name="startTime"><span data-ttu-id="87307-111">開始時刻。</span><span class="sxs-lookup"><span data-stu-id="87307-111">Start time.</span></span></param>
        <param name="endTime"><span data-ttu-id="87307-112">終了時刻です。</span><span class="sxs-lookup"><span data-stu-id="87307-112">End time.</span></span></param>
        <param name="duration"><span data-ttu-id="87307-113">ジョブの期間です。</span><span class="sxs-lookup"><span data-stu-id="87307-113">Job duration.</span></span></param>
        <param name="outputUrl"><span data-ttu-id="87307-114">出力 URL です。</span><span class="sxs-lookup"><span data-stu-id="87307-114">Output URL.</span></span></param>
        <param name="errorUrl"><span data-ttu-id="87307-115">エラー URL です。</span><span class="sxs-lookup"><span data-stu-id="87307-115">Error URL.</span></span></param>
        <param name="url"><span data-ttu-id="87307-116">ジョブの URL です。</span><span class="sxs-lookup"><span data-stu-id="87307-116">Job URL.</span></span></param>
        <param name="jobName"><span data-ttu-id="87307-117">ジョブ名です。</span><span class="sxs-lookup"><span data-stu-id="87307-117">Job name.</span></span></param>
        <param name="trigger"><span data-ttu-id="87307-118">ジョブ トリガーします。</span><span class="sxs-lookup"><span data-stu-id="87307-118">Job trigger.</span></span></param>
        <summary>
            <span data-ttu-id="87307-119">TriggeredJobRun クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="87307-119">Initializes a new instance of the TriggeredJobRun class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Duration">
      <MemberSignature Language="C#" Value="public string Duration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Duration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.Duration" />
      <MemberSignature Language="VB.NET" Value="Public Property Duration As String" />
      <MemberSignature Language="F#" Value="member this.Duration : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.Duration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.duration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87307-120">取得またはジョブ期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="87307-120">Gets or sets job duration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
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
            <span data-ttu-id="87307-121">取得または終了時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="87307-121">Gets or sets end time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorUrl">
      <MemberSignature Language="C#" Value="public string ErrorUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.ErrorUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorUrl As String" />
      <MemberSignature Language="F#" Value="member this.ErrorUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.ErrorUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errorUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87307-122">取得またはエラー URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="87307-122">Gets or sets error URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobName">
      <MemberSignature Language="C#" Value="public string JobName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.JobName" />
      <MemberSignature Language="VB.NET" Value="Public Property JobName As String" />
      <MemberSignature Language="F#" Value="member this.JobName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.JobName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.jobName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87307-123">取得またはジョブの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="87307-123">Gets or sets job name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputUrl">
      <MemberSignature Language="C#" Value="public string OutputUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutputUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.OutputUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputUrl As String" />
      <MemberSignature Language="F#" Value="member this.OutputUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.OutputUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87307-124">取得または出力 URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="87307-124">Gets or sets output URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
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
            <span data-ttu-id="87307-125">取得または開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="87307-125">Gets or sets start time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.TriggeredWebJobStatus&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.TriggeredWebJobStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of TriggeredWebJobStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.TriggeredWebJobStatus&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.TriggeredWebJobStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87307-126">取得またはジョブの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="87307-126">Gets or sets job status.</span></span> <span data-ttu-id="87307-127">使用可能な値が含まれます: 'は Success'、'失敗'、'Error'</span><span class="sxs-lookup"><span data-stu-id="87307-127">Possible values include: 'Success', 'Failed', 'Error'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Trigger">
      <MemberSignature Language="C#" Value="public string Trigger { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Trigger" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.Trigger" />
      <MemberSignature Language="VB.NET" Value="Public Property Trigger As String" />
      <MemberSignature Language="F#" Value="member this.Trigger : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.Trigger" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.trigger")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87307-128">取得またはジョブ トリガーを設定します。</span><span class="sxs-lookup"><span data-stu-id="87307-128">Gets or sets job trigger.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggeredJobRunId">
      <MemberSignature Language="C#" Value="public string TriggeredJobRunId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TriggeredJobRunId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.TriggeredJobRunId" />
      <MemberSignature Language="VB.NET" Value="Public Property TriggeredJobRunId As String" />
      <MemberSignature Language="F#" Value="member this.TriggeredJobRunId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.TriggeredJobRunId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87307-129">取得またはジョブ ID を設定します</span><span class="sxs-lookup"><span data-stu-id="87307-129">Gets or sets job ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggeredJobRunName">
      <MemberSignature Language="C#" Value="public string TriggeredJobRunName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TriggeredJobRunName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.TriggeredJobRunName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggeredJobRunName As String" />
      <MemberSignature Language="F#" Value="member this.TriggeredJobRunName : string" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.TriggeredJobRunName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87307-130">ジョブの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="87307-130">Gets job name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.TriggeredJobRun.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87307-131">取得またはジョブの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="87307-131">Gets or sets job URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>