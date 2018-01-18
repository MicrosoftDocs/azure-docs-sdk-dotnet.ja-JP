<Type Name="JobAddParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter">
  <TypeSignature Language="C#" Value="public class JobAddParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobAddParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class JobAddParameter" />
  <TypeSignature Language="F#" Value="type JobAddParameter = class" />
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
            <span data-ttu-id="c8a63-101">追加するために Azure Batch のジョブです。</span><span class="sxs-lookup"><span data-stu-id="c8a63-101">An Azure Batch job to add.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobAddParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.#ctor" />
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
            <span data-ttu-id="c8a63-102">JobAddParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-102">Initializes a new instance of the JobAddParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobAddParameter (string id, Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, string displayName = null, Nullable&lt;int&gt; priority = null, Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.JobManagerTask jobManagerTask = null, Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask jobPreparationTask = null, Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask jobReleaseTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; commonEnvironmentSettings = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; onTaskFailure = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null, Nullable&lt;bool&gt; usesTaskDependencies = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, string displayName, valuetype System.Nullable`1&lt;int32&gt; priority, class Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.JobManagerTask jobManagerTask, class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask jobPreparationTask, class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask jobReleaseTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; commonEnvironmentSettings, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; onTaskFailure, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata, valuetype System.Nullable`1&lt;bool&gt; usesTaskDependencies) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolInformation,System.String,System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.JobConstraints,Microsoft.Azure.Batch.Protocol.Models.JobManagerTask,Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask,Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem},System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobAddParameter : string * Microsoft.Azure.Batch.Protocol.Models.PoolInformation * string * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.JobConstraints * Microsoft.Azure.Batch.Protocol.Models.JobManagerTask * Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask * Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobAddParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobAddParameter (id, poolInfo, displayName, priority, constraints, jobManagerTask, jobPreparationTask, jobReleaseTask, commonEnvironmentSettings, onAllTasksComplete, onTaskFailure, metadata, usesTaskDependencies)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="poolInfo" Type="Microsoft.Azure.Batch.Protocol.Models.PoolInformation" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.JobConstraints" />
        <Parameter Name="jobManagerTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask" />
        <Parameter Name="jobPreparationTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask" />
        <Parameter Name="jobReleaseTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask" />
        <Parameter Name="commonEnvironmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="onAllTasksComplete" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;" />
        <Parameter Name="onTaskFailure" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
        <Parameter Name="usesTaskDependencies" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="c8a63-103">アカウント内でジョブを一意に識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="c8a63-103">A string that uniquely identifies the job within the account.</span></span></param>
        <param name="poolInfo"><span data-ttu-id="c8a63-104">バッチ サービスがジョブのタスクを実行するプールです。</span><span class="sxs-lookup"><span data-stu-id="c8a63-104">The pool on which the Batch service runs the job's tasks.</span></span></param>
        <param name="displayName"><span data-ttu-id="c8a63-105">ジョブの表示名。</span><span class="sxs-lookup"><span data-stu-id="c8a63-105">The display name for the job.</span></span></param>
        <param name="priority"><span data-ttu-id="c8a63-106">ジョブの優先度です。</span><span class="sxs-lookup"><span data-stu-id="c8a63-106">The priority of the job.</span></span></param>
        <param name="constraints"><span data-ttu-id="c8a63-107">ジョブの実行制約。</span><span class="sxs-lookup"><span data-stu-id="c8a63-107">The execution constraints for the job.</span></span></param>
        <param name="jobManagerTask"><span data-ttu-id="c8a63-108">ジョブが開始されたときに起動されるようにジョブ マネージャー タスクの詳細です。</span><span class="sxs-lookup"><span data-stu-id="c8a63-108">Details of a Job Manager task to be launched when the job is started.</span></span></param>
        <param name="jobPreparationTask"><span data-ttu-id="c8a63-109">ジョブの準備タスク。</span><span class="sxs-lookup"><span data-stu-id="c8a63-109">The Job Preparation task.</span></span></param>
        <param name="jobReleaseTask"><span data-ttu-id="c8a63-110">ジョブのリリース タスク。</span><span class="sxs-lookup"><span data-stu-id="c8a63-110">The Job Release task.</span></span></param>
        <param name="commonEnvironmentSettings"><span data-ttu-id="c8a63-111">一般的な環境変数設定の一覧。</span><span class="sxs-lookup"><span data-stu-id="c8a63-111">The list of common environment variable settings.</span></span> <span data-ttu-id="c8a63-112">これらの環境変数は、すべてのタスクのジョブ (ジョブ マネージャー、ジョブの準備およびジョブのリリース タスクを含む) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="c8a63-112">These environment variables are set for all tasks in the job (including the Job Manager, Job Preparation and Job Release tasks).</span></span></param>
        <param name="onAllTasksComplete"><span data-ttu-id="c8a63-113">アクション、バッチ サービスは必要があります、ジョブ内のすべてのタスクが完了した状態となります。</span><span class="sxs-lookup"><span data-stu-id="c8a63-113">The action the Batch service should take when all tasks in the job are in the completed state.</span></span></param>
        <param name="onTaskFailure"><span data-ttu-id="c8a63-114">アクション、ジョブ内の任意のタスクが失敗したときにバッチ サービスが行います。</span><span class="sxs-lookup"><span data-stu-id="c8a63-114">The action the Batch service should take when any task in the job fails.</span></span></param>
        <param name="metadata"><span data-ttu-id="c8a63-115">ジョブにメタデータとして関連付けられた名前と値のペアの一覧。</span><span class="sxs-lookup"><span data-stu-id="c8a63-115">A list of name-value pairs associated with the job as metadata.</span></span></param>
        <param name="usesTaskDependencies"><span data-ttu-id="c8a63-116">かどうか、ジョブ内のタスクでは、互いに依存関係を定義できます。</span><span class="sxs-lookup"><span data-stu-id="c8a63-116">Whether tasks in the job can define dependencies on each other.</span></span> <span data-ttu-id="c8a63-117">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="c8a63-117">The default is false.</span></span></param>
        <summary>
            <span data-ttu-id="c8a63-118">JobAddParameter クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-118">Initializes a new instance of the JobAddParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonEnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; CommonEnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; CommonEnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.CommonEnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonEnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.CommonEnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.CommonEnvironmentSettings" />
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
            <span data-ttu-id="c8a63-119">取得または一般的な環境変数設定の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-119">Gets or sets the list of common environment variable settings.</span></span>
            <span data-ttu-id="c8a63-120">これらの環境変数は、すべてのタスクのジョブ (ジョブ マネージャー、ジョブの準備およびジョブのリリース タスクを含む) に設定されます。</span><span class="sxs-lookup"><span data-stu-id="c8a63-120">These environment variables are set for all tasks in the job (including the Job Manager, Job Preparation and Job Release tasks).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a63-121">個々 のタスクは、ここで指定した値が異なる同じ設定の名前を指定することで、環境設定を上書きできます。</span><span class="sxs-lookup"><span data-stu-id="c8a63-121">Individual tasks can override an environment setting specified here by specifying the same setting name with a different value.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.JobConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Constraints" />
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
            <span data-ttu-id="c8a63-122">取得またはジョブの実行の制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-122">Gets or sets the execution constraints for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.DisplayName" />
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
            <span data-ttu-id="c8a63-123">取得またはジョブの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-123">Gets or sets the display name for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a63-124">表示名は一意でない必要があり、最大で 1,024 の最大長の Unicode 文字を含めることができます。</span><span class="sxs-lookup"><span data-stu-id="c8a63-124">The display name need not be unique and can contain any Unicode characters up to a maximum length of 1024.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Id" />
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
            <span data-ttu-id="c8a63-125">取得またはアカウント内でジョブを一意に識別する文字列を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-125">Gets or sets a string that uniquely identifies the job within the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a63-126">ID は、ハイフン、アンダー スコアを含む、英数字の任意の組み合わせを含めることができ、64 を超える文字を含めることはできません。</span><span class="sxs-lookup"><span data-stu-id="c8a63-126">The ID can contain any combination of alphanumeric characters including hyphens and underscores, and cannot contain more than 64 characters.</span></span> <span data-ttu-id="c8a63-127">ID は大文字と小文字を区別 (つまり、大文字と小文字が異なるだけ、アカウント内の 2 つの Id はない必要があります)。</span><span class="sxs-lookup"><span data-stu-id="c8a63-127">The ID is case-preserving and case-insensitive (that is, you may not have two IDs within an account that differ only by case).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobManagerTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobManagerTask JobManagerTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobManagerTask JobManagerTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobManagerTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobManagerTask As JobManagerTask" />
      <MemberSignature Language="F#" Value="member this.JobManagerTask : Microsoft.Azure.Batch.Protocol.Models.JobManagerTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobManagerTask" />
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
            <span data-ttu-id="c8a63-128">取得またはジョブが開始されたときに起動されるようにジョブ マネージャー タスクの詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-128">Gets or sets details of a Job Manager task to be launched when the job is started.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a63-129">ジョブがジョブ マネージャー タスクを指定しない場合、ユーザー必要があります明示的に追加のタスク ジョブ。</span><span class="sxs-lookup"><span data-stu-id="c8a63-129">If the job does not specify a Job Manager task, the user must explicitly add tasks to the job.</span></span> <span data-ttu-id="c8a63-130">ジョブでは、ジョブ マネージャー タスクを指定する場合、Batch service は、ジョブが作成され、ジョブ内の他のタスクをスケジュールする前に、ジョブ マネージャー タスクのスケジュールを設定しようと、ジョブ マネージャー タスクを作成します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-130">If the job does specify a Job Manager task, the Batch service creates the Job Manager task when the job is created, and will try to schedule the Job Manager task before scheduling other tasks in the job.</span></span> <span data-ttu-id="c8a63-131">ジョブ マネージャー タスクの一般的な目的はなどによってどのような追加タスクが実行を決定する、作業完了の確認など、コントロールやモニターのジョブ実行します。(ただし、ジョブ マネージャー タスクがこれらのアクティビティに制限されていません - 総合的タスク、システムであり、ジョブに必要な任意のアクションを実行します。)たとえば、ジョブ マネージャー タスク可能性がありますをパラメーターとして指定されたファイルをダウンロード、そのファイルの内容を分析およびその内容に基づく追加タスクを送信します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-131">The Job Manager task's typical purpose is to control and/or monitor job execution, for example by deciding what additional tasks to run, determining when the work is complete, etc. (However, a Job Manager task is not restricted to these activities - it is a fully-fledged task in the system and perform whatever actions are required for the job.) For example, a Job Manager task might download a file specified as a parameter, analyze the contents of that file and submit additional tasks based on those contents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparationTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask JobPreparationTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask JobPreparationTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobPreparationTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparationTask As JobPreparationTask" />
      <MemberSignature Language="F#" Value="member this.JobPreparationTask : Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobPreparationTask" />
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
            <span data-ttu-id="c8a63-132">取得またはジョブの準備タスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-132">Gets or sets the Job Preparation task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a63-133">ジョブにジョブの準備タスクがある場合、Batch service はジョブの準備タスクをそのコンピューティング ノードでそのジョブのすべてのタスクを開始する前にコンピューティング ノードで実行します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-133">If a job has a Job Preparation task, the Batch service will run the Job Preparation task on a compute node before starting any tasks of that job on that compute node.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobReleaseTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask JobReleaseTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask JobReleaseTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobReleaseTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobReleaseTask As JobReleaseTask" />
      <MemberSignature Language="F#" Value="member this.JobReleaseTask : Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobReleaseTask" />
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
            <span data-ttu-id="c8a63-134">取得またはジョブのリリース タスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-134">Gets or sets the Job Release task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a63-135">ジョブのジョブの準備タスクを指定せず、ジョブのリリース タスクを指定できません。</span><span class="sxs-lookup"><span data-stu-id="c8a63-135">A Job Release task cannot be specified without also specifying a Job Preparation task for the job.</span></span> <span data-ttu-id="c8a63-136">バッチ サービスは、ジョブの準備タスクを実行したコンピューティング ノードでジョブのリリース タスクを実行します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-136">The Batch service runs the Job Release task on the compute nodes that have run the Job Preparation task.</span></span> <span data-ttu-id="c8a63-137">ジョブのリリース タスクの主な目的は、コンピューティング ノードがジョブの準備タスクによって行われた変更を元に戻すにです。</span><span class="sxs-lookup"><span data-stu-id="c8a63-137">The primary purpose of the Job Release task is to undo changes to compute nodes made by the Job Preparation task.</span></span> <span data-ttu-id="c8a63-138">例の活動には、ローカルのファイルを削除するか、ジョブの準備の一環として開始されたサービスをシャット ダウンが含まれます。</span><span class="sxs-lookup"><span data-stu-id="c8a63-138">Example activities include deleting local files, or shutting down services that were started as part of job preparation.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Metadata" />
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
            <span data-ttu-id="c8a63-139">取得またはメタデータとしてジョブに関連付けられている名前と値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-139">Gets or sets a list of name-value pairs associated with the job as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a63-140">バッチ サービスがメタデータに意味を割り当てませんこれは、ユーザー コードを使用するためだけです。</span><span class="sxs-lookup"><span data-stu-id="c8a63-140">The Batch service does not assign any meaning to metadata; it is solely for the use of user code.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAllTasksComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.OnAllTasksComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property OnAllTasksComplete As Nullable(Of OnAllTasksComplete)" />
      <MemberSignature Language="F#" Value="member this.OnAllTasksComplete : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.OnAllTasksComplete" />
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
            <span data-ttu-id="c8a63-141">取得またはバッチ ジョブ内のすべてのタスクが完了の状態でサービスが行うアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-141">Gets or sets the action the Batch service should take when all tasks in the job are in the completed state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a63-142">ジョブにタスクが含まれていない場合、すべてのタスクと見なされる完全なに注意してください。</span><span class="sxs-lookup"><span data-stu-id="c8a63-142">Note that if a job contains no tasks, then all tasks are considered complete.</span></span> <span data-ttu-id="c8a63-143">このオプションは最も一般的であるためジョブ マネージャー タスクのジョブの自動終了せずジョブ マネージャーを使用する場合は、する最初に、onAllTasksComplete を noAction に設定されに設定する onAllTasksComplete terminateJob タスクの追加が完了したら ジョブのプロパティを更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c8a63-143">This option is therefore most commonly used with a Job Manager task; if you want to use automatic job termination without a Job Manager, you should initially set onAllTasksComplete to noAction and update the job properties to set onAllTasksComplete to terminateJob once you have finished adding tasks.</span></span> <span data-ttu-id="c8a63-144">既定値は noAction です。</span><span class="sxs-lookup"><span data-stu-id="c8a63-144">The default is noAction.</span></span> <span data-ttu-id="c8a63-145">使用可能な値が含まれます: 'noAction'、'terminateJob'</span><span class="sxs-lookup"><span data-stu-id="c8a63-145">Possible values include: 'noAction', 'terminateJob'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTaskFailure">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; OnTaskFailure { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; OnTaskFailure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.OnTaskFailure" />
      <MemberSignature Language="VB.NET" Value="Public Property OnTaskFailure As Nullable(Of OnTaskFailure)" />
      <MemberSignature Language="F#" Value="member this.OnTaskFailure : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.OnTaskFailure" />
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
            <span data-ttu-id="c8a63-146">取得または、ジョブ内の任意のタスクが失敗したときに、バッチ サービスが実行するアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-146">Gets or sets the action the Batch service should take when any task in the job fails.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a63-147">タスクが持つと見なされますが、failureInfo の障害が発生した場合。</span><span class="sxs-lookup"><span data-stu-id="c8a63-147">A task is considered to have failed if has a failureInfo.</span></span> <span data-ttu-id="c8a63-148">ゼロ以外の終了コードでの再試行回数を使い果たした後のタスクが完了した場合に、failureInfo が設定されているタスクを開始中にエラーがあった場合など、リソース ファイルのためダウンロードもエラー。</span><span class="sxs-lookup"><span data-stu-id="c8a63-148">A failureInfo is set if the task completes with a non-zero exit code after exhausting its retry count, or if there was an error starting the task, for example due to a resource file download error.</span></span> <span data-ttu-id="c8a63-149">既定値は noAction です。</span><span class="sxs-lookup"><span data-stu-id="c8a63-149">The default is noAction.</span></span> <span data-ttu-id="c8a63-150">使用可能な値が含まれます: 'noAction'、'performExitOptionsJobAction'</span><span class="sxs-lookup"><span data-stu-id="c8a63-150">Possible values include: 'noAction', 'performExitOptionsJobAction'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.PoolInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolInfo As PoolInformation" />
      <MemberSignature Language="F#" Value="member this.PoolInfo : Microsoft.Azure.Batch.Protocol.Models.PoolInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.PoolInfo" />
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
            <span data-ttu-id="c8a63-151">取得またはバッチ サービスがジョブのタスクを実行するプールを設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-151">Gets or sets the pool on which the Batch service runs the job's tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Priority" />
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
            <span data-ttu-id="c8a63-152">取得またはジョブの優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-152">Gets or sets the priority of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8a63-153">優先順位の値の範囲は -1000 から 1000、-1000 が最も低い優先度と 1000 中優先順位が高いです。</span><span class="sxs-lookup"><span data-stu-id="c8a63-153">Priority values can range from -1000 to 1000, with -1000 being the lowest priority and 1000 being the highest priority.</span></span> <span data-ttu-id="c8a63-154">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="c8a63-154">The default value is 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UsesTaskDependencies">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsesTaskDependencies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsesTaskDependencies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.UsesTaskDependencies" />
      <MemberSignature Language="VB.NET" Value="Public Property UsesTaskDependencies As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsesTaskDependencies : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.UsesTaskDependencies" />
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
            <span data-ttu-id="c8a63-155">取得または、ジョブ内のタスクは相互に依存関係を定義することができるかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-155">Gets or sets whether tasks in the job can define dependencies on each other.</span></span> <span data-ttu-id="c8a63-156">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="c8a63-156">The default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobAddParameter.Validate " />
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
            <span data-ttu-id="c8a63-157">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="c8a63-157">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c8a63-158">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c8a63-158">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>