<Type Name="ProcessThreadInfo" FullName="Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo">
  <TypeSignature Language="C#" Value="public class ProcessThreadInfo : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProcessThreadInfo extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class ProcessThreadInfo&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type ProcessThreadInfo = class&#xA;    inherit ProxyOnlyResource" />
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
            <span data-ttu-id="e7f3d-101">プロセス スレッドの情報です。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-101">Process Thread Information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProcessThreadInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e7f3d-102">ProcessThreadInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-102">Initializes a new instance of the ProcessThreadInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProcessThreadInfo (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;int&gt; processThreadInfoId = null, string href = null, string process = null, string startAddress = null, Nullable&lt;int&gt; currentPriority = null, string priorityLevel = null, Nullable&lt;int&gt; basePriority = null, Nullable&lt;DateTime&gt; startTime = null, string totalProcessorTime = null, string userProcessorTime = null, string priviledgedProcessorTime = null, string state = null, string waitReason = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;int32&gt; processThreadInfoId, string href, string process, string startAddress, valuetype System.Nullable`1&lt;int32&gt; currentPriority, string priorityLevel, valuetype System.Nullable`1&lt;int32&gt; basePriority, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, string totalProcessorTime, string userProcessorTime, string priviledgedProcessorTime, string state, string waitReason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.String,System.Nullable{System.Int32},System.String,System.Nullable{System.Int32},System.Nullable{System.DateTime},System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional processThreadInfoId As Nullable(Of Integer) = null, Optional href As String = null, Optional process As String = null, Optional startAddress As String = null, Optional currentPriority As Nullable(Of Integer) = null, Optional priorityLevel As String = null, Optional basePriority As Nullable(Of Integer) = null, Optional startTime As Nullable(Of DateTime) = null, Optional totalProcessorTime As String = null, Optional userProcessorTime As String = null, Optional priviledgedProcessorTime As String = null, Optional state As String = null, Optional waitReason As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo : string * string * string * string * Nullable&lt;int&gt; * string * string * string * Nullable&lt;int&gt; * string * Nullable&lt;int&gt; * Nullable&lt;DateTime&gt; * string * string * string * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo" Usage="new Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo (id, name, kind, type, processThreadInfoId, href, process, startAddress, currentPriority, priorityLevel, basePriority, startTime, totalProcessorTime, userProcessorTime, priviledgedProcessorTime, state, waitReason)" />
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
        <Parameter Name="processThreadInfoId" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="href" Type="System.String" />
        <Parameter Name="process" Type="System.String" />
        <Parameter Name="startAddress" Type="System.String" />
        <Parameter Name="currentPriority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="priorityLevel" Type="System.String" />
        <Parameter Name="basePriority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="totalProcessorTime" Type="System.String" />
        <Parameter Name="userProcessorTime" Type="System.String" />
        <Parameter Name="priviledgedProcessorTime" Type="System.String" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="waitReason" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="e7f3d-103">リソース id です。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="e7f3d-104">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="e7f3d-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="e7f3d-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-106">Resource type.</span></span></param>
        <param name="processThreadInfoId"><span data-ttu-id="e7f3d-107">展開の ARM 識別子です。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-107">ARM Identifier for deployment.</span></span></param>
        <param name="href"><span data-ttu-id="e7f3d-108">HRef の URI。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-108">HRef URI.</span></span></param>
        <param name="process"><span data-ttu-id="e7f3d-109">プロセス URI。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-109">Process URI.</span></span></param>
        <param name="startAddress"><span data-ttu-id="e7f3d-110">開始アドレス。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-110">Start address.</span></span></param>
        <param name="currentPriority"><span data-ttu-id="e7f3d-111">現在のスレッド優先度です。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-111">Current thread priority.</span></span></param>
        <param name="priorityLevel"><span data-ttu-id="e7f3d-112">スレッドの優先度レベル。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-112">Thread priority level.</span></span></param>
        <param name="basePriority"><span data-ttu-id="e7f3d-113">基本の優先度です。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-113">Base priority.</span></span></param>
        <param name="startTime"><span data-ttu-id="e7f3d-114">開始時刻。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-114">Start time.</span></span></param>
        <param name="totalProcessorTime"><span data-ttu-id="e7f3d-115">合計プロセッサ時間。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-115">Total processor time.</span></span></param>
        <param name="userProcessorTime"><span data-ttu-id="e7f3d-116">ユーザー プロセッサ時間。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-116">User processor time.</span></span></param>
        <param name="priviledgedProcessorTime"><span data-ttu-id="e7f3d-117">特権プロセッサ時間。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-117">Priviledged processor time.</span></span></param>
        <param name="state"><span data-ttu-id="e7f3d-118">スレッドの状態。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-118">Thread state.</span></span></param>
        <param name="waitReason"><span data-ttu-id="e7f3d-119">理由を待機します。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-119">Wait reason.</span></span></param>
        <summary>
            <span data-ttu-id="e7f3d-120">ProcessThreadInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-120">Initializes a new instance of the ProcessThreadInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BasePriority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BasePriority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BasePriority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.BasePriority" />
      <MemberSignature Language="VB.NET" Value="Public Property BasePriority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BasePriority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.BasePriority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.basePriority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e7f3d-121">取得または基本優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-121">Gets or sets base priority.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentPriority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentPriority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentPriority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.CurrentPriority" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentPriority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentPriority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.CurrentPriority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentPriority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e7f3d-122">取得または現在のスレッド優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-122">Gets or sets current thread priority.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Href">
      <MemberSignature Language="C#" Value="public string Href { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Href" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.Href" />
      <MemberSignature Language="VB.NET" Value="Public Property Href As String" />
      <MemberSignature Language="F#" Value="member this.Href : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.Href" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.href")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e7f3d-123">取得または hRef URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-123">Gets or sets hRef URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PriorityLevel">
      <MemberSignature Language="C#" Value="public string PriorityLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PriorityLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.PriorityLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property PriorityLevel As String" />
      <MemberSignature Language="F#" Value="member this.PriorityLevel : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.PriorityLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.priorityLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e7f3d-124">取得またはスレッドの優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-124">Gets or sets thread priority level.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PriviledgedProcessorTime">
      <MemberSignature Language="C#" Value="public string PriviledgedProcessorTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PriviledgedProcessorTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.PriviledgedProcessorTime" />
      <MemberSignature Language="VB.NET" Value="Public Property PriviledgedProcessorTime As String" />
      <MemberSignature Language="F#" Value="member this.PriviledgedProcessorTime : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.PriviledgedProcessorTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.priviledgedProcessorTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e7f3d-125">取得または特権プロセッサ時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-125">Gets or sets priviledged processor time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Process">
      <MemberSignature Language="C#" Value="public string Process { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Process" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.Process" />
      <MemberSignature Language="VB.NET" Value="Public Property Process As String" />
      <MemberSignature Language="F#" Value="member this.Process : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.Process" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.process")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e7f3d-126">取得またはプロセス URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-126">Gets or sets process URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessThreadInfoId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ProcessThreadInfoId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ProcessThreadInfoId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.ProcessThreadInfoId" />
      <MemberSignature Language="VB.NET" Value="Public Property ProcessThreadInfoId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ProcessThreadInfoId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.ProcessThreadInfoId" />
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
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e7f3d-127">取得または展開の ARM 識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-127">Gets or sets ARM Identifier for deployment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAddress">
      <MemberSignature Language="C#" Value="public string StartAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.StartAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property StartAddress As String" />
      <MemberSignature Language="F#" Value="member this.StartAddress : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.StartAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e7f3d-128">取得または開始アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-128">Gets or sets start address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.StartTime" />
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
            <span data-ttu-id="e7f3d-129">取得または開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-129">Gets or sets start time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
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
            <span data-ttu-id="e7f3d-130">取得またはスレッドの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-130">Gets or sets thread state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalProcessorTime">
      <MemberSignature Language="C#" Value="public string TotalProcessorTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TotalProcessorTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.TotalProcessorTime" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalProcessorTime As String" />
      <MemberSignature Language="F#" Value="member this.TotalProcessorTime : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.TotalProcessorTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.totalProcessorTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e7f3d-131">取得またはプロセッサの合計時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-131">Gets or sets total processor time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserProcessorTime">
      <MemberSignature Language="C#" Value="public string UserProcessorTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserProcessorTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.UserProcessorTime" />
      <MemberSignature Language="VB.NET" Value="Public Property UserProcessorTime As String" />
      <MemberSignature Language="F#" Value="member this.UserProcessorTime : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.UserProcessorTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.userProcessorTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e7f3d-132">取得またはユーザー プロセッサ時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-132">Gets or sets user processor time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitReason">
      <MemberSignature Language="C#" Value="public string WaitReason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WaitReason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.WaitReason" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitReason As String" />
      <MemberSignature Language="F#" Value="member this.WaitReason : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.ProcessThreadInfo.WaitReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.waitReason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e7f3d-133">取得または設定は、理由を待機します。</span><span class="sxs-lookup"><span data-stu-id="e7f3d-133">Gets or sets wait reason.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>