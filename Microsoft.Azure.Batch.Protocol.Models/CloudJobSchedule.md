<Type Name="CloudJobSchedule" FullName="Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule">
  <TypeSignature Language="C#" Value="public class CloudJobSchedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudJobSchedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudJobSchedule" />
  <TypeSignature Language="F#" Value="type CloudJobSchedule = class" />
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
            <span data-ttu-id="6ef88-101">定期的なジョブのジョブと各ジョブの作成に使用される仕様を実行するタイミングを指定することにより、ジョブ スケジュールです。</span><span class="sxs-lookup"><span data-stu-id="6ef88-101">A job schedule that allows recurring jobs by specifying when to run jobs and a specification used to create each job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudJobSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.#ctor" />
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
            <span data-ttu-id="6ef88-102">CloudJobSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-102">Initializes a new instance of the CloudJobSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudJobSchedule (string id = null, string displayName = null, string url = null, string eTag = null, Nullable&lt;DateTime&gt; lastModified = null, Nullable&lt;DateTime&gt; creationTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleState&gt; state = null, Nullable&lt;DateTime&gt; stateTransitionTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleState&gt; previousState = null, Nullable&lt;DateTime&gt; previousStateTransitionTime = null, Microsoft.Azure.Batch.Protocol.Models.Schedule schedule = null, Microsoft.Azure.Batch.Protocol.Models.JobSpecification jobSpecification = null, Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation executionInfo = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null, Microsoft.Azure.Batch.Protocol.Models.JobScheduleStatistics stats = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string displayName, string url, string eTag, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobScheduleState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; stateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobScheduleState&gt; previousState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; previousStateTransitionTime, class Microsoft.Azure.Batch.Protocol.Models.Schedule schedule, class Microsoft.Azure.Batch.Protocol.Models.JobSpecification jobSpecification, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation executionInfo, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleStatistics stats) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.JobScheduleState},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.JobScheduleState},System.Nullable{System.DateTime},Microsoft.Azure.Batch.Protocol.Models.Schedule,Microsoft.Azure.Batch.Protocol.Models.JobSpecification,Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem},Microsoft.Azure.Batch.Protocol.Models.JobScheduleStatistics)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule : string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleState&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Batch.Protocol.Models.Schedule * Microsoft.Azure.Batch.Protocol.Models.JobSpecification * Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; * Microsoft.Azure.Batch.Protocol.Models.JobScheduleStatistics -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule" Usage="new Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule (id, displayName, url, eTag, lastModified, creationTime, state, stateTransitionTime, previousState, previousStateTransitionTime, schedule, jobSpecification, executionInfo, metadata, stats)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleState&gt;" />
        <Parameter Name="stateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="previousState" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleState&gt;" />
        <Parameter Name="previousStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="schedule" Type="Microsoft.Azure.Batch.Protocol.Models.Schedule" />
        <Parameter Name="jobSpecification" Type="Microsoft.Azure.Batch.Protocol.Models.JobSpecification" />
        <Parameter Name="executionInfo" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
        <Parameter Name="stats" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleStatistics" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="6ef88-103">アカウント内でスケジュールを一意に識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="6ef88-103">A string that uniquely identifies the schedule within the account.</span></span></param>
        <param name="displayName"><span data-ttu-id="6ef88-104">スケジュールの表示名。</span><span class="sxs-lookup"><span data-stu-id="6ef88-104">The display name for the schedule.</span></span></param>
        <param name="url"><span data-ttu-id="6ef88-105">ジョブ スケジュールの URL です。</span><span class="sxs-lookup"><span data-stu-id="6ef88-105">The URL of the job schedule.</span></span></param>
        <param name="eTag"><span data-ttu-id="6ef88-106">ジョブ スケジュールの ETag です。</span><span class="sxs-lookup"><span data-stu-id="6ef88-106">The ETag of the job schedule.</span></span></param>
        <param name="lastModified"><span data-ttu-id="6ef88-107">最後には、ジョブ スケジュールの時刻が変更されました。</span><span class="sxs-lookup"><span data-stu-id="6ef88-107">The last modified time of the job schedule.</span></span></param>
        <param name="creationTime"><span data-ttu-id="6ef88-108">ジョブ スケジュールの作成時間。</span><span class="sxs-lookup"><span data-stu-id="6ef88-108">The creation time of the job schedule.</span></span></param>
        <param name="state"><span data-ttu-id="6ef88-109">ジョブ スケジュールの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="6ef88-109">The current state of the job schedule.</span></span></param>
        <param name="stateTransitionTime"><span data-ttu-id="6ef88-110">現在の状態、ジョブ スケジュールになった時刻。</span><span class="sxs-lookup"><span data-stu-id="6ef88-110">The time at which the job schedule entered the current state.</span></span></param>
        <param name="previousState"><span data-ttu-id="6ef88-111">ジョブ スケジュールの以前の状態。</span><span class="sxs-lookup"><span data-stu-id="6ef88-111">The previous state of the job schedule.</span></span></param>
        <param name="previousStateTransitionTime"><span data-ttu-id="6ef88-112">その前の状態、ジョブ スケジュールになった時刻。</span><span class="sxs-lookup"><span data-stu-id="6ef88-112">The time at which the job schedule entered its previous state.</span></span></param>
        <param name="schedule"><span data-ttu-id="6ef88-113">これに基づいてジョブを作成するスケジュールです。</span><span class="sxs-lookup"><span data-stu-id="6ef88-113">The schedule according to which jobs will be created.</span></span></param>
        <param name="jobSpecification"><span data-ttu-id="6ef88-114">このスケジュールを作成するジョブの詳細。</span><span class="sxs-lookup"><span data-stu-id="6ef88-114">The details of the jobs to be created on this schedule.</span></span></param>
        <param name="executionInfo"><span data-ttu-id="6ef88-115">されているし、このスケジュールで実行されるジョブに関する情報です。</span><span class="sxs-lookup"><span data-stu-id="6ef88-115">Information about jobs that have been and will be run under this schedule.</span></span></param>
        <param name="metadata"><span data-ttu-id="6ef88-116">メタデータとしてスケジュールに関連付けられている名前と値のペアの一覧。</span><span class="sxs-lookup"><span data-stu-id="6ef88-116">A list of name-value pairs associated with the schedule as metadata.</span></span></param>
        <param name="stats"><span data-ttu-id="6ef88-117">ジョブ スケジュールの有効期間リソース使用状況の統計。</span><span class="sxs-lookup"><span data-stu-id="6ef88-117">The lifetime resource usage statistics for the job schedule.</span></span></param>
        <summary>
            <span data-ttu-id="6ef88-118">CloudJobSchedule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-118">Initializes a new instance of the CloudJobSchedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ef88-119">取得またはジョブのスケジュールの作成時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-119">Gets or sets the creation time of the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ef88-120">取得またはスケジュールの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-120">Gets or sets the display name for the schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ef88-121">取得またはジョブ スケジュールの ETag を設定します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-121">Gets or sets the ETag of the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6ef88-122">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="6ef88-122">This is an opaque string.</span></span> <span data-ttu-id="6ef88-123">要求間で、ジョブ スケジュールが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="6ef88-123">You can use it to detect whether the job schedule has changed between requests.</span></span> <span data-ttu-id="6ef88-124">特には、変更が反映されるその他のユーザーが変更スケジュール間場合にのみを指定する、ジョブ スケジュールの更新要求で ETag を渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="6ef88-124">In particular, you can be pass the ETag with an Update Job Schedule request to specify that your changes should take effect only if nobody else has modified the schedule in the meantime.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation ExecutionInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation ExecutionInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.ExecutionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutionInfo As JobScheduleExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ExecutionInfo : Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.ExecutionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="executionInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ef88-125">取得または設定されているし、このスケジュールで実行されるジョブに関する情報。</span><span class="sxs-lookup"><span data-stu-id="6ef88-125">Gets or sets information about jobs that have been and will be run under this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="6ef88-126">取得またはアカウント内でスケジュールを一意に識別する文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-126">Gets or sets a string that uniquely identifies the schedule within the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6ef88-127">共通 id の GUID を使用するがします。</span><span class="sxs-lookup"><span data-stu-id="6ef88-127">It is common to use a GUID for the id.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobSpecification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobSpecification JobSpecification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobSpecification JobSpecification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.JobSpecification" />
      <MemberSignature Language="VB.NET" Value="Public Property JobSpecification As JobSpecification" />
      <MemberSignature Language="F#" Value="member this.JobSpecification : Microsoft.Azure.Batch.Protocol.Models.JobSpecification with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.JobSpecification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobSpecification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ef88-128">取得または、このスケジュールを作成するジョブの詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-128">Gets or sets the details of the jobs to be created on this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastModified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ef88-129">取得またはジョブ スケジュールの最終更新時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-129">Gets or sets the last modified time of the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6ef88-130">これは、前回のジョブの仕様または定期実行情報などのスケジュール レベル データが変更されました。</span><span class="sxs-lookup"><span data-stu-id="6ef88-130">This is the last time at which the schedule level data, such as the job specification or recurrence information, changed.</span></span> <span data-ttu-id="6ef88-131">新しいジョブを作成中など、ジョブ レベルの変更またはジョブの状態を変更すること考慮はされません。</span><span class="sxs-lookup"><span data-stu-id="6ef88-131">It does not factor in job-level changes such as new jobs being created or jobs changing state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ef88-132">取得またはメタデータとしてスケジュールに関連付けられている名前と値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-132">Gets or sets a list of name-value pairs associated with the schedule as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6ef88-133">バッチ サービスがメタデータに意味を割り当てませんこれは、ユーザー コードを使用するためだけです。</span><span class="sxs-lookup"><span data-stu-id="6ef88-133">The Batch service does not assign any meaning to metadata; it is solely for the use of user code.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleState&gt; PreviousState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobScheduleState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public Property PreviousState As Nullable(Of JobScheduleState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.PreviousState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="previousState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ef88-134">取得またはジョブ スケジュールの以前の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-134">Gets or sets the previous state of the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6ef88-135">このプロパティは、ジョブ スケジュールが初期のアクティブな状態にある場合です。</span><span class="sxs-lookup"><span data-stu-id="6ef88-135">This property is not present if the job schedule is in its initial active state.</span></span> <span data-ttu-id="6ef88-136">使用可能な値が含まれます: 'active'、'完了'、'disabled'、'終了'、'削除'</span><span class="sxs-lookup"><span data-stu-id="6ef88-136">Possible values include: 'active', 'completed', 'disabled', 'terminating', 'deleting'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.PreviousStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="previousStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ef88-137">取得またはジョブのスケジュールが以前の状態を入力する時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-137">Gets or sets the time at which the job schedule entered its previous state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6ef88-138">このプロパティは、ジョブ スケジュールが初期のアクティブな状態にある場合です。</span><span class="sxs-lookup"><span data-stu-id="6ef88-138">This property is not present if the job schedule is in its initial active state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.Schedule Schedule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.Schedule Schedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.Schedule" />
      <MemberSignature Language="VB.NET" Value="Public Property Schedule As Schedule" />
      <MemberSignature Language="F#" Value="member this.Schedule : Microsoft.Azure.Batch.Protocol.Models.Schedule with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.Schedule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schedule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.Schedule</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ef88-139">取得またはこれに基づいてジョブを作成するスケジュールを設定します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-139">Gets or sets the schedule according to which jobs will be created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleState&gt; State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobScheduleState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As Nullable(Of JobScheduleState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ef88-140">取得またはジョブのスケジュールの現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-140">Gets or sets the current state of the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6ef88-141">使用可能な値が含まれます: 'active'、'完了'、'disabled'、'終了'、'削除'</span><span class="sxs-lookup"><span data-stu-id="6ef88-141">Possible values include: 'active', 'completed', 'disabled', 'terminating', 'deleting'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ef88-142">取得または現在の状態、ジョブ スケジュールになった時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-142">Gets or sets the time at which the job schedule entered the current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stats">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobScheduleStatistics Stats { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobScheduleStatistics Stats" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.Stats" />
      <MemberSignature Language="VB.NET" Value="Public Property Stats As JobScheduleStatistics" />
      <MemberSignature Language="F#" Value="member this.Stats : Microsoft.Azure.Batch.Protocol.Models.JobScheduleStatistics with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.Stats" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stats")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ef88-143">取得またはジョブ スケジュールの有効期間リソース使用状況の統計を設定します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-143">Gets or sets the lifetime resource usage statistics for the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ef88-144">取得またはジョブ スケジュールの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-144">Gets or sets the URL of the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cloudJobSchedule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6ef88-145">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="6ef88-145">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ef88-146">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6ef88-146">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>