<Type Name="CloudJob" FullName="Microsoft.Azure.Batch.Protocol.Models.CloudJob">
  <TypeSignature Language="C#" Value="public class CloudJob" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudJob extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.CloudJob" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudJob" />
  <TypeSignature Language="F#" Value="type CloudJob = class" />
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
            <span data-ttu-id="ca311-101">Azure Batch のジョブの場合は。</span><span class="sxs-lookup"><span data-stu-id="ca311-101">An Azure Batch job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudJob ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudJob.#ctor" />
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
            <span data-ttu-id="ca311-102">CloudJob クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ca311-102">Initializes a new instance of the CloudJob class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudJob (string id = null, string displayName = null, Nullable&lt;bool&gt; usesTaskDependencies = null, string url = null, string eTag = null, Nullable&lt;DateTime&gt; lastModified = null, Nullable&lt;DateTime&gt; creationTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt; state = null, Nullable&lt;DateTime&gt; stateTransitionTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt; previousState = null, Nullable&lt;DateTime&gt; previousStateTransitionTime = null, Nullable&lt;int&gt; priority = null, Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.JobManagerTask jobManagerTask = null, Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask jobPreparationTask = null, Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask jobReleaseTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; commonEnvironmentSettings = null, Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; onTaskFailure = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null, Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation executionInfo = null, Microsoft.Azure.Batch.Protocol.Models.JobStatistics stats = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string displayName, valuetype System.Nullable`1&lt;bool&gt; usesTaskDependencies, string url, string eTag, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; stateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobState&gt; previousState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; previousStateTransitionTime, valuetype System.Nullable`1&lt;int32&gt; priority, class Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.JobManagerTask jobManagerTask, class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask jobPreparationTask, class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask jobReleaseTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; commonEnvironmentSettings, class Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; onTaskFailure, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata, class Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation executionInfo, class Microsoft.Azure.Batch.Protocol.Models.JobStatistics stats) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudJob.#ctor(System.String,System.String,System.Nullable{System.Boolean},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.JobState},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.JobState},System.Nullable{System.DateTime},System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.JobConstraints,Microsoft.Azure.Batch.Protocol.Models.JobManagerTask,Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask,Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},Microsoft.Azure.Batch.Protocol.Models.PoolInformation,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem},Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation,Microsoft.Azure.Batch.Protocol.Models.JobStatistics)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.CloudJob : string * string * Nullable&lt;bool&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.JobConstraints * Microsoft.Azure.Batch.Protocol.Models.JobManagerTask * Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask * Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Microsoft.Azure.Batch.Protocol.Models.PoolInformation * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; * Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation * Microsoft.Azure.Batch.Protocol.Models.JobStatistics -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudJob" Usage="new Microsoft.Azure.Batch.Protocol.Models.CloudJob (id, displayName, usesTaskDependencies, url, eTag, lastModified, creationTime, state, stateTransitionTime, previousState, previousStateTransitionTime, priority, constraints, jobManagerTask, jobPreparationTask, jobReleaseTask, commonEnvironmentSettings, poolInfo, onAllTasksComplete, onTaskFailure, metadata, executionInfo, stats)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="usesTaskDependencies" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt;" />
        <Parameter Name="stateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="previousState" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt;" />
        <Parameter Name="previousStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.JobConstraints" />
        <Parameter Name="jobManagerTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask" />
        <Parameter Name="jobPreparationTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask" />
        <Parameter Name="jobReleaseTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask" />
        <Parameter Name="commonEnvironmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="poolInfo" Type="Microsoft.Azure.Batch.Protocol.Models.PoolInformation" />
        <Parameter Name="onAllTasksComplete" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;" />
        <Parameter Name="onTaskFailure" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
        <Parameter Name="executionInfo" Type="Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation" />
        <Parameter Name="stats" Type="Microsoft.Azure.Batch.Protocol.Models.JobStatistics" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="ca311-103">アカウント内でジョブを一意に識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="ca311-103">A string that uniquely identifies the job within the account.</span></span></param>
        <param name="displayName"><span data-ttu-id="ca311-104">ジョブの表示名。</span><span class="sxs-lookup"><span data-stu-id="ca311-104">The display name for the job.</span></span></param>
        <param name="usesTaskDependencies"><span data-ttu-id="ca311-105">かどうか、ジョブ内のタスクでは、互いに依存関係を定義できます。</span><span class="sxs-lookup"><span data-stu-id="ca311-105">Whether tasks in the job can define dependencies on each other.</span></span> <span data-ttu-id="ca311-106">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="ca311-106">The default is false.</span></span></param>
        <param name="url"><span data-ttu-id="ca311-107">ジョブの URL です。</span><span class="sxs-lookup"><span data-stu-id="ca311-107">The URL of the job.</span></span></param>
        <param name="eTag"><span data-ttu-id="ca311-108">ジョブの ETag です。</span><span class="sxs-lookup"><span data-stu-id="ca311-108">The ETag of the job.</span></span></param>
        <param name="lastModified"><span data-ttu-id="ca311-109">最終更新ジョブの時刻。</span><span class="sxs-lookup"><span data-stu-id="ca311-109">The last modified time of the job.</span></span></param>
        <param name="creationTime"><span data-ttu-id="ca311-110">ジョブの作成時間。</span><span class="sxs-lookup"><span data-stu-id="ca311-110">The creation time of the job.</span></span></param>
        <param name="state"><span data-ttu-id="ca311-111">ジョブの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="ca311-111">The current state of the job.</span></span></param>
        <param name="stateTransitionTime"><span data-ttu-id="ca311-112">ジョブが現在の状態を入力する時刻。</span><span class="sxs-lookup"><span data-stu-id="ca311-112">The time at which the job entered its current state.</span></span></param>
        <param name="previousState"><span data-ttu-id="ca311-113">ジョブの以前の状態。</span><span class="sxs-lookup"><span data-stu-id="ca311-113">The previous state of the job.</span></span></param>
        <param name="previousStateTransitionTime"><span data-ttu-id="ca311-114">その前の状態、ジョブになった時刻。</span><span class="sxs-lookup"><span data-stu-id="ca311-114">The time at which the job entered its previous state.</span></span></param>
        <param name="priority"><span data-ttu-id="ca311-115">ジョブの優先度です。</span><span class="sxs-lookup"><span data-stu-id="ca311-115">The priority of the job.</span></span></param>
        <param name="constraints"><span data-ttu-id="ca311-116">ジョブの実行制約。</span><span class="sxs-lookup"><span data-stu-id="ca311-116">The execution constraints for the job.</span></span></param>
        <param name="jobManagerTask"><span data-ttu-id="ca311-117">ジョブが開始されたときに起動されるようにジョブ マネージャー タスクの詳細です。</span><span class="sxs-lookup"><span data-stu-id="ca311-117">Details of a Job Manager task to be launched when the job is started.</span></span></param>
        <param name="jobPreparationTask"><span data-ttu-id="ca311-118">ジョブの準備タスク。</span><span class="sxs-lookup"><span data-stu-id="ca311-118">The Job Preparation task.</span></span></param>
        <param name="jobReleaseTask"><span data-ttu-id="ca311-119">ジョブのリリース タスク。</span><span class="sxs-lookup"><span data-stu-id="ca311-119">The Job Release task.</span></span></param>
        <param name="commonEnvironmentSettings"><span data-ttu-id="ca311-120">一般的な環境変数設定の一覧。</span><span class="sxs-lookup"><span data-stu-id="ca311-120">The list of common environment variable settings.</span></span> <span data-ttu-id="ca311-121">これらの環境変数は、すべてのタスクのジョブ (ジョブ マネージャー、ジョブの準備およびジョブのリリース タスクを含む) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="ca311-121">These environment variables are set for all tasks in the job (including the Job Manager, Job Preparation and Job Release tasks).</span></span></param>
        <param name="poolInfo"><span data-ttu-id="ca311-122">ジョブに関連付けられたプールの設定。</span><span class="sxs-lookup"><span data-stu-id="ca311-122">The pool settings associated with the job.</span></span></param>
        <param name="onAllTasksComplete"><span data-ttu-id="ca311-123">アクション、バッチ サービスは必要があります、ジョブ内のすべてのタスクが完了した状態となります。</span><span class="sxs-lookup"><span data-stu-id="ca311-123">The action the Batch service should take when all tasks in the job are in the completed state.</span></span></param>
        <param name="onTaskFailure"><span data-ttu-id="ca311-124">アクション、ジョブ内の任意のタスクが失敗したときにバッチ サービスが行います。</span><span class="sxs-lookup"><span data-stu-id="ca311-124">The action the Batch service should take when any task in the job fails.</span></span></param>
        <param name="metadata"><span data-ttu-id="ca311-125">ジョブにメタデータとして関連付けられた名前と値のペアの一覧。</span><span class="sxs-lookup"><span data-stu-id="ca311-125">A list of name-value pairs associated with the job as metadata.</span></span></param>
        <param name="executionInfo"><span data-ttu-id="ca311-126">ジョブの実行情報。</span><span class="sxs-lookup"><span data-stu-id="ca311-126">The execution information for the job.</span></span></param>
        <param name="stats"><span data-ttu-id="ca311-127">ジョブの有効期間にわたってのリソース使用状況の統計。</span><span class="sxs-lookup"><span data-stu-id="ca311-127">Resource usage statistics for the entire lifetime of the job.</span></span></param>
        <summary>
            <span data-ttu-id="ca311-128">CloudJob クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ca311-128">Initializes a new instance of the CloudJob class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonEnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; CommonEnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; CommonEnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.CommonEnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonEnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.CommonEnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.CommonEnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commonEnvironmentSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca311-129">取得または一般的な環境変数設定の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-129">Gets or sets the list of common environment variable settings.</span></span>
            <span data-ttu-id="ca311-130">これらの環境変数は、すべてのタスクのジョブ (ジョブ マネージャー、ジョブの準備およびジョブのリリース タスクを含む) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="ca311-130">These environment variables are set for all tasks in the job (including the Job Manager, Job Preparation and Job Release tasks).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ca311-131">個々 のタスクは、ここで指定した値が異なる同じ設定の名前を指定することで、環境設定を上書きできます。</span><span class="sxs-lookup"><span data-stu-id="ca311-131">Individual tasks can override an environment setting specified here by specifying the same setting name with a different value.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.JobConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="constraints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca311-132">取得またはジョブの実行の制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-132">Gets or sets the execution constraints for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.CreationTime" />
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
            <span data-ttu-id="ca311-133">取得またはジョブの作成時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-133">Gets or sets the creation time of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.DisplayName" />
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
            <span data-ttu-id="ca311-134">取得またはジョブの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-134">Gets or sets the display name for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.ETag" />
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
            <span data-ttu-id="ca311-135">取得またはジョブの ETag を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-135">Gets or sets the ETag of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ca311-136">これは、不透明な文字列です。</span><span class="sxs-lookup"><span data-stu-id="ca311-136">This is an opaque string.</span></span> <span data-ttu-id="ca311-137">要求間で、ジョブが変更されたかどうかを検出するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="ca311-137">You can use it to detect whether the job has changed between requests.</span></span> <span data-ttu-id="ca311-138">特にには、変更が反映されるその他のユーザーが変更、ジョブ、その間場合にのみを指定するためのジョブを更新するときに、ETag を渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="ca311-138">In particular, you can be pass the ETag when updating a job to specify that your changes should take effect only if nobody else has modified the job in the meantime.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation ExecutionInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation ExecutionInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.ExecutionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutionInfo As JobExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ExecutionInfo : Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.ExecutionInfo" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca311-139">取得またはジョブの実行情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-139">Gets or sets the execution information for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.Id" />
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
            <span data-ttu-id="ca311-140">取得またはアカウント内でジョブを一意に識別する文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-140">Gets or sets a string that uniquely identifies the job within the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ca311-141">ID は大文字と小文字を区別 (つまり、大文字と小文字が異なるだけ、アカウント内の 2 つの Id はない必要があります)。</span><span class="sxs-lookup"><span data-stu-id="ca311-141">The ID is case-preserving and case-insensitive (that is, you may not have two IDs within an account that differ only by case).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobManagerTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobManagerTask JobManagerTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobManagerTask JobManagerTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.JobManagerTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobManagerTask As JobManagerTask" />
      <MemberSignature Language="F#" Value="member this.JobManagerTask : Microsoft.Azure.Batch.Protocol.Models.JobManagerTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.JobManagerTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobManagerTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobManagerTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca311-142">取得またはジョブが開始されたときに起動されるようにジョブ マネージャー タスクの詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-142">Gets or sets details of a Job Manager task to be launched when the job is started.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparationTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask JobPreparationTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask JobPreparationTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.JobPreparationTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparationTask As JobPreparationTask" />
      <MemberSignature Language="F#" Value="member this.JobPreparationTask : Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.JobPreparationTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobPreparationTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca311-143">取得またはジョブの準備タスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-143">Gets or sets the Job Preparation task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ca311-144">ジョブの準備タスクは、その他のタスク、ジョブの前に各ノードで実行する特別な作業です。</span><span class="sxs-lookup"><span data-stu-id="ca311-144">The Job Preparation task is a special task run on each node before any other task of the job.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobReleaseTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask JobReleaseTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask JobReleaseTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.JobReleaseTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobReleaseTask As JobReleaseTask" />
      <MemberSignature Language="F#" Value="member this.JobReleaseTask : Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.JobReleaseTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobReleaseTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca311-145">取得またはジョブのリリース タスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-145">Gets or sets the Job Release task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ca311-146">ジョブのリリース タスクは、特別なタスクがジョブの他のタスクを実行した各ノードで、ジョブの最後に実行します。</span><span class="sxs-lookup"><span data-stu-id="ca311-146">The Job Release task is a special task run at the end of the job on each node that has run any other task of the job.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.LastModified" />
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
            <span data-ttu-id="ca311-147">取得またはジョブの最終更新時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-147">Gets or sets the last modified time of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ca311-148">これは、前回のジョブの状態や、優先順位など、ジョブ レベル データが変更されました。</span><span class="sxs-lookup"><span data-stu-id="ca311-148">This is the last time at which the job level data, such as the job state or priority, changed.</span></span> <span data-ttu-id="ca311-149">新しいタスクや状態を変更するタスクを追加するなど、タスク レベルの変更には考慮されません。</span><span class="sxs-lookup"><span data-stu-id="ca311-149">It does not factor in task-level changes such as adding new tasks or tasks changing state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.Metadata" />
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
            <span data-ttu-id="ca311-150">取得またはメタデータとしてジョブに関連付けられている名前と値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-150">Gets or sets a list of name-value pairs associated with the job as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ca311-151">バッチ サービスがメタデータに意味を割り当てませんこれは、ユーザー コードを使用するためだけです。</span><span class="sxs-lookup"><span data-stu-id="ca311-151">The Batch service does not assign any meaning to metadata; it is solely for the use of user code.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAllTasksComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.OnAllTasksComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property OnAllTasksComplete As Nullable(Of OnAllTasksComplete)" />
      <MemberSignature Language="F#" Value="member this.OnAllTasksComplete : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.OnAllTasksComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="onAllTasksComplete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca311-152">取得またはバッチ ジョブ内のすべてのタスクが完了の状態でサービスが行うアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-152">Gets or sets the action the Batch service should take when all tasks in the job are in the completed state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ca311-153">noAction - 何もしません。</span><span class="sxs-lookup"><span data-stu-id="ca311-153">noAction - do nothing.</span></span> <span data-ttu-id="ca311-154">ジョブでは、終了または他のいくつかの方法で無効になっている場合を除きが消えない。</span><span class="sxs-lookup"><span data-stu-id="ca311-154">The job remains active unless terminated or disabled by some other means.</span></span> <span data-ttu-id="ca311-155">terminateJob - ジョブを終了します。</span><span class="sxs-lookup"><span data-stu-id="ca311-155">terminateJob - terminate the job.</span></span> <span data-ttu-id="ca311-156">ジョブの terminateReason は、'AllTasksComplete' に設定されます。</span><span class="sxs-lookup"><span data-stu-id="ca311-156">The job's terminateReason is set to 'AllTasksComplete'.</span></span> <span data-ttu-id="ca311-157">既定値は noAction です。</span><span class="sxs-lookup"><span data-stu-id="ca311-157">The default is noAction.</span></span> <span data-ttu-id="ca311-158">使用可能な値が含まれます: 'noAction'、'terminateJob'</span><span class="sxs-lookup"><span data-stu-id="ca311-158">Possible values include: 'noAction', 'terminateJob'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTaskFailure">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; OnTaskFailure { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; OnTaskFailure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.OnTaskFailure" />
      <MemberSignature Language="VB.NET" Value="Public Property OnTaskFailure As Nullable(Of OnTaskFailure)" />
      <MemberSignature Language="F#" Value="member this.OnTaskFailure : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.OnTaskFailure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="onTaskFailure")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca311-159">取得または、ジョブ内の任意のタスクが失敗したときに、バッチ サービスが実行するアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-159">Gets or sets the action the Batch service should take when any task in the job fails.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ca311-160">タスクが持つと見なされますが、failureInfo の障害が発生した場合。</span><span class="sxs-lookup"><span data-stu-id="ca311-160">A task is considered to have failed if has a failureInfo.</span></span> <span data-ttu-id="ca311-161">ゼロ以外の終了コードでの再試行回数を使い果たした後のタスクが完了した場合に、failureInfo が設定されているタスクを開始中にエラーがあった場合など、リソース ファイルのためダウンロードもエラー。</span><span class="sxs-lookup"><span data-stu-id="ca311-161">A failureInfo is set if the task completes with a non-zero exit code after exhausting its retry count, or if there was an error starting the task, for example due to a resource file download error.</span></span>
            <span data-ttu-id="ca311-162">noAction - 何もしません。</span><span class="sxs-lookup"><span data-stu-id="ca311-162">noAction - do nothing.</span></span> <span data-ttu-id="ca311-163">performExitOptionsJobAction - タスクの exitConditions コレクション内のタスクの終了条件に関連付けられているアクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="ca311-163">performExitOptionsJobAction - take the action associated with the task exit condition in the task's exitConditions collection.</span></span> <span data-ttu-id="ca311-164">(このまだあります何も行われているタスクが指定される場合。)既定値は noAction です。</span><span class="sxs-lookup"><span data-stu-id="ca311-164">(This may still result in no action being taken, if that is what the task specifies.) The default is noAction.</span></span> <span data-ttu-id="ca311-165">使用可能な値が含まれます: 'noAction'、'performExitOptionsJobAction'</span><span class="sxs-lookup"><span data-stu-id="ca311-165">Possible values include: 'noAction', 'performExitOptionsJobAction'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.PoolInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolInfo As PoolInformation" />
      <MemberSignature Language="F#" Value="member this.PoolInfo : Microsoft.Azure.Batch.Protocol.Models.PoolInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.PoolInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca311-166">取得またはジョブに関連付けられたプールの設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-166">Gets or sets the pool settings associated with the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt; PreviousState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public Property PreviousState As Nullable(Of JobState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.PreviousState" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca311-167">取得またはジョブの以前の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-167">Gets or sets the previous state of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ca311-168">ジョブが初期のアクティブな状態にある場合、このプロパティは設定されません。</span><span class="sxs-lookup"><span data-stu-id="ca311-168">This property is not set if the job is in its initial Active state.</span></span>
            <span data-ttu-id="ca311-169">使用可能な値が含まれます: 'active'、'無効'、'disabled'、'有効'、'終了'、'完了'、'削除'</span><span class="sxs-lookup"><span data-stu-id="ca311-169">Possible values include: 'active', 'disabling', 'disabled', 'enabling', 'terminating', 'completed', 'deleting'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.PreviousStateTransitionTime" />
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
            <span data-ttu-id="ca311-170">取得またはジョブを直前の状態が入力された時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-170">Gets or sets the time at which the job entered its previous state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ca311-171">ジョブが初期のアクティブな状態にある場合、このプロパティは設定されません。</span><span class="sxs-lookup"><span data-stu-id="ca311-171">This property is not set if the job is in its initial Active state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca311-172">取得またはジョブの優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-172">Gets or sets the priority of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ca311-173">優先順位の値の範囲は -1000 から 1000、-1000 が最も低い優先度と 1000 中優先順位が高いです。</span><span class="sxs-lookup"><span data-stu-id="ca311-173">Priority values can range from -1000 to 1000, with -1000 being the lowest priority and 1000 being the highest priority.</span></span> <span data-ttu-id="ca311-174">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="ca311-174">The default value is 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt; State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As Nullable(Of JobState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.State" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca311-175">取得またはジョブの現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-175">Gets or sets the current state of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ca311-176">使用可能な値が含まれます: 'active'、'無効'、'disabled'、'有効'、'終了'、'完了'、'削除'</span><span class="sxs-lookup"><span data-stu-id="ca311-176">Possible values include: 'active', 'disabling', 'disabled', 'enabling', 'terminating', 'completed', 'deleting'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.StateTransitionTime" />
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
            <span data-ttu-id="ca311-177">取得またはジョブが現在の状態を入力する時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-177">Gets or sets the time at which the job entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stats">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobStatistics Stats { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobStatistics Stats" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.Stats" />
      <MemberSignature Language="VB.NET" Value="Public Property Stats As JobStatistics" />
      <MemberSignature Language="F#" Value="member this.Stats : Microsoft.Azure.Batch.Protocol.Models.JobStatistics with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.Stats" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca311-178">取得またはジョブの有効期間全体のリソース使用状況の統計情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-178">Gets or sets resource usage statistics for the entire lifetime of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.Url" />
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
            <span data-ttu-id="ca311-179">取得またはジョブの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-179">Gets or sets the URL of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsesTaskDependencies">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsesTaskDependencies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsesTaskDependencies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.UsesTaskDependencies" />
      <MemberSignature Language="VB.NET" Value="Public Property UsesTaskDependencies As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsesTaskDependencies : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.UsesTaskDependencies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="usesTaskDependencies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca311-180">取得または、ジョブ内のタスクは相互に依存関係を定義することができるかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="ca311-180">Gets or sets whether tasks in the job can define dependencies on each other.</span></span> <span data-ttu-id="ca311-181">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="ca311-181">The default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudJob.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cloudJob.Validate " />
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
            <span data-ttu-id="ca311-182">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="ca311-182">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ca311-183">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ca311-183">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>