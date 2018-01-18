<Type Name="JobSpecification" FullName="Microsoft.Azure.Batch.Protocol.Models.JobSpecification">
  <TypeSignature Language="C#" Value="public class JobSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class JobSpecification" />
  <TypeSignature Language="F#" Value="type JobSpecification = class" />
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
            <span data-ttu-id="b688f-101">スケジュールに従って作成するジョブの詳細を指定します。</span><span class="sxs-lookup"><span data-stu-id="b688f-101">Specifies details of the jobs to be created on a schedule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.#ctor" />
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
            <span data-ttu-id="b688f-102">JobSpecification クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b688f-102">Initializes a new instance of the JobSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobSpecification (Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, Nullable&lt;int&gt; priority = null, string displayName = null, Nullable&lt;bool&gt; usesTaskDependencies = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; onTaskFailure = null, Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.JobManagerTask jobManagerTask = null, Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask jobPreparationTask = null, Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask jobReleaseTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; commonEnvironmentSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, valuetype System.Nullable`1&lt;int32&gt; priority, string displayName, valuetype System.Nullable`1&lt;bool&gt; usesTaskDependencies, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; onTaskFailure, class Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.JobManagerTask jobManagerTask, class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask jobPreparationTask, class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask jobReleaseTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; commonEnvironmentSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.#ctor(Microsoft.Azure.Batch.Protocol.Models.PoolInformation,System.Nullable{System.Int32},System.String,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure},Microsoft.Azure.Batch.Protocol.Models.JobConstraints,Microsoft.Azure.Batch.Protocol.Models.JobManagerTask,Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask,Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobSpecification : Microsoft.Azure.Batch.Protocol.Models.PoolInformation * Nullable&lt;int&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; * Microsoft.Azure.Batch.Protocol.Models.JobConstraints * Microsoft.Azure.Batch.Protocol.Models.JobManagerTask * Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask * Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobSpecification" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobSpecification (poolInfo, priority, displayName, usesTaskDependencies, onAllTasksComplete, onTaskFailure, constraints, jobManagerTask, jobPreparationTask, jobReleaseTask, commonEnvironmentSettings, metadata)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="poolInfo" Type="Microsoft.Azure.Batch.Protocol.Models.PoolInformation" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="usesTaskDependencies" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="onAllTasksComplete" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;" />
        <Parameter Name="onTaskFailure" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.JobConstraints" />
        <Parameter Name="jobManagerTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask" />
        <Parameter Name="jobPreparationTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask" />
        <Parameter Name="jobReleaseTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask" />
        <Parameter Name="commonEnvironmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
      </Parameters>
      <Docs>
        <param name="poolInfo"><span data-ttu-id="b688f-103">バッチ サービスがこのスケジュールの下に作成されたジョブのタスクを実行するプールです。</span><span class="sxs-lookup"><span data-stu-id="b688f-103">The pool on which the Batch service runs the tasks of jobs created under this schedule.</span></span></param>
        <param name="priority"><span data-ttu-id="b688f-104">このスケジュールの下に作成されたジョブの優先順位。</span><span class="sxs-lookup"><span data-stu-id="b688f-104">The priority of jobs created under this schedule.</span></span></param>
        <param name="displayName"><span data-ttu-id="b688f-105">このスケジュールの下に作成されたジョブの表示名。</span><span class="sxs-lookup"><span data-stu-id="b688f-105">The display name for jobs created under this schedule.</span></span></param>
        <param name="usesTaskDependencies"><span data-ttu-id="b688f-106">かどうか、ジョブ内のタスクでは、互いに依存関係を定義できます。</span><span class="sxs-lookup"><span data-stu-id="b688f-106">Whether tasks in the job can define dependencies on each other.</span></span> <span data-ttu-id="b688f-107">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="b688f-107">The default is false.</span></span></param>
        <param name="onAllTasksComplete"><span data-ttu-id="b688f-108">アクション、バッチ サービスは、このスケジュールの下に作成されたジョブのすべてのタスクが完了した状態でとなります必要があります。</span><span class="sxs-lookup"><span data-stu-id="b688f-108">The action the Batch service should take when all tasks in a job created under this schedule are in the completed state.</span></span></param>
        <param name="onTaskFailure"><span data-ttu-id="b688f-109">アクション バッチ サービスがこのスケジュールの下に作成されたジョブのいずれかのタスクが失敗したときに行います。</span><span class="sxs-lookup"><span data-stu-id="b688f-109">The action the Batch service should take when any task fails in a job created under this schedule.</span></span> <span data-ttu-id="b688f-110">タスクが失敗した場合に失敗したと見なされるかどうかは、failureInfo です。</span><span class="sxs-lookup"><span data-stu-id="b688f-110">A task is considered to have failed if it have failed if has a failureInfo.</span></span> <span data-ttu-id="b688f-111">ゼロ以外の終了コードでの再試行回数を使い果たした後のタスクが完了した場合に、failureInfo が設定されているタスクを開始中にエラーがあった場合など、リソース ファイルのためダウンロードもエラー。</span><span class="sxs-lookup"><span data-stu-id="b688f-111">A failureInfo is set if the task completes with a non-zero exit code after exhausting its retry count, or if there was an error starting the task, for example due to a resource file download error.</span></span></param>
        <param name="constraints"><span data-ttu-id="b688f-112">このスケジュールの下に作成されたジョブの実行制約。</span><span class="sxs-lookup"><span data-stu-id="b688f-112">The execution constraints for jobs created under this schedule.</span></span></param>
        <param name="jobManagerTask"><span data-ttu-id="b688f-113">このスケジュールされたジョブが開始されたときに起動されるようにジョブ マネージャー タスクの詳細。</span><span class="sxs-lookup"><span data-stu-id="b688f-113">The details of a Job Manager task to be launched when a job is started under this schedule.</span></span></param>
        <param name="jobPreparationTask"><span data-ttu-id="b688f-114">このスケジュールの下に作成されたジョブのジョブの準備タスク。</span><span class="sxs-lookup"><span data-stu-id="b688f-114">The Job Preparation task for jobs created under this schedule.</span></span></param>
        <param name="jobReleaseTask"><span data-ttu-id="b688f-115">このスケジュールの下に作成されたジョブのジョブのリリース タスク。</span><span class="sxs-lookup"><span data-stu-id="b688f-115">The Job Release task for jobs created under this schedule.</span></span></param>
        <param name="commonEnvironmentSettings"><span data-ttu-id="b688f-116">一般的な環境変数設定の一覧。</span><span class="sxs-lookup"><span data-stu-id="b688f-116">A list of common environment variable settings.</span></span> <span data-ttu-id="b688f-117">これらの環境変数は、このスケジュール (ジョブ マネージャー、ジョブの準備およびジョブのリリース タスクを含む) の下に作成されたジョブのすべてのタスクに対して設定されます。</span><span class="sxs-lookup"><span data-stu-id="b688f-117">These environment variables are set for all tasks in jobs created under this schedule (including the Job Manager, Job Preparation and Job Release tasks).</span></span></param>
        <param name="metadata"><span data-ttu-id="b688f-118">メタデータとしてスケジュールで作成された各ジョブに関連付けられている名前と値のペアの一覧。</span><span class="sxs-lookup"><span data-stu-id="b688f-118">A list of name-value pairs associated with each job created under this schedule as metadata.</span></span></param>
        <summary>
            <span data-ttu-id="b688f-119">JobSpecification クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b688f-119">Initializes a new instance of the JobSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonEnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; CommonEnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; CommonEnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.CommonEnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonEnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.CommonEnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.CommonEnvironmentSettings" />
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
            <span data-ttu-id="b688f-120">取得または一般的な環境変数設定の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="b688f-120">Gets or sets a list of common environment variable settings.</span></span> <span data-ttu-id="b688f-121">これらの環境変数は、このスケジュール (ジョブ マネージャー、ジョブの準備およびジョブのリリース タスクを含む) の下に作成されたジョブのすべてのタスクに対して設定されます。</span><span class="sxs-lookup"><span data-stu-id="b688f-121">These environment variables are set for all tasks in jobs created under this schedule (including the Job Manager, Job Preparation and Job Release tasks).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b688f-122">個々 のタスクは、ここで指定した値が異なる同じ設定の名前を指定することで、環境設定を上書きできます。</span><span class="sxs-lookup"><span data-stu-id="b688f-122">Individual tasks can override an environment setting specified here by specifying the same setting name with a different value.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.JobConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.Constraints" />
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
            <span data-ttu-id="b688f-123">取得または、このスケジュールの下に作成されたジョブの実行の制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="b688f-123">Gets or sets the execution constraints for jobs created under this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.DisplayName" />
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
            <span data-ttu-id="b688f-124">取得または、このスケジュールの下に作成されたジョブの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="b688f-124">Gets or sets the display name for jobs created under this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b688f-125">名前は一意である必要はなく、最大で 1,024 の最大長の Unicode 文字を含めることができます。</span><span class="sxs-lookup"><span data-stu-id="b688f-125">The name need not be unique and can contain any Unicode characters up to a maximum length of 1024.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobManagerTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobManagerTask JobManagerTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobManagerTask JobManagerTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.JobManagerTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobManagerTask As JobManagerTask" />
      <MemberSignature Language="F#" Value="member this.JobManagerTask : Microsoft.Azure.Batch.Protocol.Models.JobManagerTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.JobManagerTask" />
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
            <span data-ttu-id="b688f-126">取得または このスケジュールされたジョブが開始されたときに起動されるようにジョブ マネージャー タスクの詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="b688f-126">Gets or sets the details of a Job Manager task to be launched when a job is started under this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b688f-127">ジョブがジョブ マネージャー タスクを指定しない場合、ユーザー必要があります明示的に追加のタスク タスク API を使用してジョブ。</span><span class="sxs-lookup"><span data-stu-id="b688f-127">If the job does not specify a Job Manager task, the user must explicitly add tasks to the job using the Task API.</span></span> <span data-ttu-id="b688f-128">ジョブでは、ジョブ マネージャー タスクを指定する場合、Batch service は、ジョブが作成され、ジョブ内の他のタスクをスケジュールする前に、ジョブ マネージャー タスクのスケジュールを設定しようと、ジョブ マネージャー タスクを作成します。</span><span class="sxs-lookup"><span data-stu-id="b688f-128">If the job does specify a Job Manager task, the Batch service creates the Job Manager task when the job is created, and will try to schedule the Job Manager task before scheduling other tasks in the job.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparationTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask JobPreparationTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask JobPreparationTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.JobPreparationTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparationTask As JobPreparationTask" />
      <MemberSignature Language="F#" Value="member this.JobPreparationTask : Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.JobPreparationTask" />
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
            <span data-ttu-id="b688f-129">取得または、このスケジュールの下に作成されたジョブのジョブの準備タスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="b688f-129">Gets or sets the Job Preparation task for jobs created under this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b688f-130">ジョブにジョブの準備タスクがある場合、Batch service はジョブの準備タスクをそのコンピューティング ノードでそのジョブのすべてのタスクを開始する前にコンピューティング ノードで実行します。</span><span class="sxs-lookup"><span data-stu-id="b688f-130">If a job has a Job Preparation task, the Batch service will run the Job Preparation task on a compute node before starting any tasks of that job on that compute node.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobReleaseTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask JobReleaseTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask JobReleaseTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.JobReleaseTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobReleaseTask As JobReleaseTask" />
      <MemberSignature Language="F#" Value="member this.JobReleaseTask : Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.JobReleaseTask" />
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
            <span data-ttu-id="b688f-131">取得または、このスケジュールの下に作成されたジョブのジョブのリリース タスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="b688f-131">Gets or sets the Job Release task for jobs created under this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b688f-132">ジョブのリリース タスクの主な目的は、コンピューティング ノードがジョブの準備タスクによって行われた変更を元に戻すにです。</span><span class="sxs-lookup"><span data-stu-id="b688f-132">The primary purpose of the Job Release task is to undo changes to compute nodes made by the Job Preparation task.</span></span> <span data-ttu-id="b688f-133">例の活動には、ローカルのファイルを削除するか、ジョブの準備の一環として開始されたサービスをシャット ダウンが含まれます。</span><span class="sxs-lookup"><span data-stu-id="b688f-133">Example activities include deleting local files, or shutting down services that were started as part of job preparation.</span></span> <span data-ttu-id="b688f-134">ジョブのジョブの準備タスクを指定せず、ジョブのリリース タスクを指定できません。</span><span class="sxs-lookup"><span data-stu-id="b688f-134">A Job Release task cannot be specified without also specifying a Job Preparation task for the job.</span></span> <span data-ttu-id="b688f-135">バッチ サービスは、ジョブの準備タスクを実行したコンピューティング ノードでジョブのリリース タスクを実行します。</span><span class="sxs-lookup"><span data-stu-id="b688f-135">The Batch service runs the Job Release task on the compute nodes that have run the Job Preparation task.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.Metadata" />
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
            <span data-ttu-id="b688f-136">取得またはメタデータとしてスケジュールで作成された各ジョブに関連付けられている名前と値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="b688f-136">Gets or sets a list of name-value pairs associated with each job created under this schedule as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b688f-137">バッチ サービスがメタデータに意味を割り当てませんこれは、ユーザー コードを使用するためだけです。</span><span class="sxs-lookup"><span data-stu-id="b688f-137">The Batch service does not assign any meaning to metadata; it is solely for the use of user code.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAllTasksComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.OnAllTasksComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property OnAllTasksComplete As Nullable(Of OnAllTasksComplete)" />
      <MemberSignature Language="F#" Value="member this.OnAllTasksComplete : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.OnAllTasksComplete" />
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
            <span data-ttu-id="b688f-138">取得または、バッチ サービスがこのスケジュールの下に作成されたジョブのすべてのタスクが完了した状態になるときに行うアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="b688f-138">Gets or sets the action the Batch service should take when all tasks in a job created under this schedule are in the completed state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b688f-139">ジョブにタスクが含まれていない場合、すべてのタスクと見なされる完全なに注意してください。</span><span class="sxs-lookup"><span data-stu-id="b688f-139">Note that if a job contains no tasks, then all tasks are considered complete.</span></span> <span data-ttu-id="b688f-140">このオプションは最も一般的であるためジョブ マネージャー タスクのジョブの自動終了せずジョブ マネージャーを使用する場合は、する最初に、onAllTasksComplete を noAction に設定されに設定する onAllTasksComplete terminateJob タスクの追加が完了したら ジョブのプロパティを更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b688f-140">This option is therefore most commonly used with a Job Manager task; if you want to use automatic job termination without a Job Manager, you should initially set onAllTasksComplete to noAction and update the job properties to set onAllTasksComplete to terminateJob once you have finished adding tasks.</span></span> <span data-ttu-id="b688f-141">既定値は noAction です。</span><span class="sxs-lookup"><span data-stu-id="b688f-141">The default is noAction.</span></span> <span data-ttu-id="b688f-142">使用可能な値が含まれます: 'noAction'、'terminateJob'</span><span class="sxs-lookup"><span data-stu-id="b688f-142">Possible values include: 'noAction', 'terminateJob'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTaskFailure">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; OnTaskFailure { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; OnTaskFailure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.OnTaskFailure" />
      <MemberSignature Language="VB.NET" Value="Public Property OnTaskFailure As Nullable(Of OnTaskFailure)" />
      <MemberSignature Language="F#" Value="member this.OnTaskFailure : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.OnTaskFailure" />
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
            <span data-ttu-id="b688f-143">取得またはバッチのいずれかのタスクがこのスケジュールの下に作成されたジョブに失敗したときにサービスが行うアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="b688f-143">Gets or sets the action the Batch service should take when any task fails in a job created under this schedule.</span></span> <span data-ttu-id="b688f-144">タスクが失敗した場合に失敗したと見なされるかどうかは、failureInfo です。</span><span class="sxs-lookup"><span data-stu-id="b688f-144">A task is considered to have failed if it have failed if has a failureInfo.</span></span> <span data-ttu-id="b688f-145">ゼロ以外の終了コードでの再試行回数を使い果たした後のタスクが完了した場合に、failureInfo が設定されているタスクを開始中にエラーがあった場合など、リソース ファイルのためダウンロードもエラー。</span><span class="sxs-lookup"><span data-stu-id="b688f-145">A failureInfo is set if the task completes with a non-zero exit code after exhausting its retry count, or if there was an error starting the task, for example due to a resource file download error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b688f-146">既定値は noAction です。</span><span class="sxs-lookup"><span data-stu-id="b688f-146">The default is noAction.</span></span> <span data-ttu-id="b688f-147">使用可能な値が含まれます: 'noAction'、'performExitOptionsJobAction'</span><span class="sxs-lookup"><span data-stu-id="b688f-147">Possible values include: 'noAction', 'performExitOptionsJobAction'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.PoolInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolInfo As PoolInformation" />
      <MemberSignature Language="F#" Value="member this.PoolInfo : Microsoft.Azure.Batch.Protocol.Models.PoolInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.PoolInfo" />
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
            <span data-ttu-id="b688f-148">取得またはバッチ サービスがこのスケジュールの下に作成されたジョブのタスクを実行するプールを設定します。</span><span class="sxs-lookup"><span data-stu-id="b688f-148">Gets or sets the pool on which the Batch service runs the tasks of jobs created under this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.Priority" />
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
            <span data-ttu-id="b688f-149">取得または、このスケジュールの下に作成されたジョブの優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="b688f-149">Gets or sets the priority of jobs created under this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b688f-150">優先順位の値の範囲は -1000 から 1000、-1000 が最も低い優先度と 1000 中優先順位が高いです。</span><span class="sxs-lookup"><span data-stu-id="b688f-150">Priority values can range from -1000 to 1000, with -1000 being the lowest priority and 1000 being the highest priority.</span></span> <span data-ttu-id="b688f-151">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="b688f-151">The default value is 0.</span></span> <span data-ttu-id="b688f-152">この優先順位は、すべてのジョブのジョブのスケジュールで、既定値として使用されます。</span><span class="sxs-lookup"><span data-stu-id="b688f-152">This priority is used as the default for all jobs under the job schedule.</span></span> <span data-ttu-id="b688f-153">更新ジョブの API を使用して、使用して作成した後は、ジョブの優先順位を更新できます。</span><span class="sxs-lookup"><span data-stu-id="b688f-153">You can update a job's priority after it has been created using by using the update job API.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UsesTaskDependencies">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsesTaskDependencies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsesTaskDependencies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.UsesTaskDependencies" />
      <MemberSignature Language="VB.NET" Value="Public Property UsesTaskDependencies As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsesTaskDependencies : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.UsesTaskDependencies" />
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
            <span data-ttu-id="b688f-154">取得または、ジョブ内のタスクは相互に依存関係を定義することができるかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="b688f-154">Gets or sets whether tasks in the job can define dependencies on each other.</span></span> <span data-ttu-id="b688f-155">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="b688f-155">The default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobSpecification.Validate " />
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
            <span data-ttu-id="b688f-156">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="b688f-156">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b688f-157">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b688f-157">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>