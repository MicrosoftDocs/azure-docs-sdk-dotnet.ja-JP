<Type Name="JobSpecification" FullName="Microsoft.Azure.Batch.JobSpecification">
  <TypeSignature Language="C#" Value="public class JobSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class JobSpecification" />
  <TypeSignature Language="F#" Value="type JobSpecification = class&#xA;    interface ITransportObjectProvider&lt;JobSpecification&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="f6baf-101"><see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.JobSpecification" />の<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />です。</span><span class="sxs-lookup"><span data-stu-id="f6baf-101">The <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.JobSpecification" /> of a <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobSpecification (Microsoft.Azure.Batch.PoolInformation poolInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.PoolInformation poolInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobSpecification.#ctor(Microsoft.Azure.Batch.PoolInformation)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.JobSpecification : Microsoft.Azure.Batch.PoolInformation -&gt; Microsoft.Azure.Batch.JobSpecification" Usage="new Microsoft.Azure.Batch.JobSpecification poolInformation" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="poolInformation" Type="Microsoft.Azure.Batch.PoolInformation" />
      </Parameters>
      <Docs>
        <param name="poolInformation"><span data-ttu-id="f6baf-102">バッチ サービスが実行されているタスクに作成されたジョブをこれを使用して、プール<see cref="T:Microsoft.Azure.Batch.JobSpecification" />です。</span><span class="sxs-lookup"><span data-stu-id="f6baf-102">The pool on which the Batch service runs the tasks of jobs created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span></span></param>
        <summary>
            <span data-ttu-id="f6baf-103"><see cref="T:Microsoft.Azure.Batch.JobSpecification" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f6baf-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.JobSpecification" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonEnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt; CommonEnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.EnvironmentSetting&gt; CommonEnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.CommonEnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonEnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.CommonEnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.CommonEnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6baf-104">取得または一般的な環境変数設定の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="f6baf-104">Gets or sets a list of common environment variable settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f6baf-105">これらの環境変数をこの下で作成されたジョブのすべてのタスクの設定は<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />(ジョブ マネージャー、ジョブの準備およびジョブのリリース タスクを含む)。</span><span class="sxs-lookup"><span data-stu-id="f6baf-105">These environment variables are set for all tasks in jobs created under this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> (including the Job Manager, Job Preparation and Job Release tasks).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.JobConstraints with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6baf-106">これを使用して作成されたジョブの実行の制約を取得または<see cref="T:Microsoft.Azure.Batch.JobSpecification" />です。</span><span class="sxs-lookup"><span data-stu-id="f6baf-106">Gets or sets the execution constraints for jobs created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6baf-107">これを使用して作成されたすべてのジョブの表示名を取得または<see cref="T:Microsoft.Azure.Batch.JobSpecification" />です。</span><span class="sxs-lookup"><span data-stu-id="f6baf-107">Gets or sets a display name for all jobs created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobManagerTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobManagerTask JobManagerTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobManagerTask JobManagerTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.JobManagerTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobManagerTask As JobManagerTask" />
      <MemberSignature Language="F#" Value="member this.JobManagerTask : Microsoft.Azure.Batch.JobManagerTask with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.JobManagerTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobManagerTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6baf-108">これを使用して、ジョブが作成されるときに起動されるようにジョブ マネージャー タスクの詳細を取得または<see cref="T:Microsoft.Azure.Batch.JobSpecification" />です。</span><span class="sxs-lookup"><span data-stu-id="f6baf-108">Gets or sets details of a Job Manager task to be launched when a job is created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparationTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobPreparationTask JobPreparationTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobPreparationTask JobPreparationTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.JobPreparationTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparationTask As JobPreparationTask" />
      <MemberSignature Language="F#" Value="member this.JobPreparationTask : Microsoft.Azure.Batch.JobPreparationTask with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.JobPreparationTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobPreparationTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6baf-109">これを使用して作成されたジョブのジョブの準備タスクの設定を取得または<see cref="T:Microsoft.Azure.Batch.JobSpecification" />です。</span><span class="sxs-lookup"><span data-stu-id="f6baf-109">Gets or sets the Job Preparation task for jobs created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f6baf-110">バッチ サービスは、そのコンピューティング ノードでそのジョブのすべてのタスクを開始する前に、コンピューティング ノードでジョブの準備タスクが実行されます。</span><span class="sxs-lookup"><span data-stu-id="f6baf-110">The Batch service will run the Job Preparation task on a compute node before starting any tasks of that job on that compute node.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobReleaseTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobReleaseTask JobReleaseTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobReleaseTask JobReleaseTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.JobReleaseTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobReleaseTask As JobReleaseTask" />
      <MemberSignature Language="F#" Value="member this.JobReleaseTask : Microsoft.Azure.Batch.JobReleaseTask with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.JobReleaseTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobReleaseTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6baf-111">これを使用して作成されたジョブのジョブのリリース タスクの設定を取得または<see cref="T:Microsoft.Azure.Batch.JobSpecification" />です。</span><span class="sxs-lookup"><span data-stu-id="f6baf-111">Gets or sets the Job Release task for jobs created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f6baf-112">バッチ サービスは、ジョブのいずれかのタスクが実行される各コンピューティング ノードで、ジョブの終了時に、ジョブのリリース タスクを実行します。</span><span class="sxs-lookup"><span data-stu-id="f6baf-112">The Batch service runs the Job Release task when the job ends, on each compute node where any task of the job has run.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6baf-113">これを使用して作成されたジョブに関連付けられている名前と値のペアの一覧を取得または<see cref="T:Microsoft.Azure.Batch.JobSpecification" />メタデータとして。</span><span class="sxs-lookup"><span data-stu-id="f6baf-113">Gets or sets a list of name-value pairs associated with jobs created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" /> as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAllTasksComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt; OnAllTasksComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt; OnAllTasksComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.OnAllTasksComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property OnAllTasksComplete As Nullable(Of OnAllTasksComplete)" />
      <MemberSignature Language="F#" Value="member this.OnAllTasksComplete : Nullable&lt;Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt; with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.OnAllTasksComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6baf-114">取得またはアクション、ジョブ内のすべてのタスクがあるときにサービスが実行するバッチの設定、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" />状態です。</span><span class="sxs-lookup"><span data-stu-id="f6baf-114">Gets or sets the action the Batch service should take when all tasks in the job are in the <see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" /> state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTaskFailure">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.OnTaskFailure&gt; OnTaskFailure { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.OnTaskFailure&gt; OnTaskFailure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.OnTaskFailure" />
      <MemberSignature Language="VB.NET" Value="Public Property OnTaskFailure As Nullable(Of OnTaskFailure)" />
      <MemberSignature Language="F#" Value="member this.OnTaskFailure : Nullable&lt;Microsoft.Azure.Batch.Common.OnTaskFailure&gt; with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.OnTaskFailure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.OnTaskFailure&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6baf-115">取得または、ジョブ内の任意のタスクが失敗したときに、バッチ サービスが実行するアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="f6baf-115">Gets or sets the action the Batch service should take when any task in the job fails.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f6baf-116">タスクは、ゼロ以外の終了コードが完了し、再試行カウントが不足する場合は、またはスケジュール設定エラーが発生した場合に失敗したと見なされます。</span><span class="sxs-lookup"><span data-stu-id="f6baf-116">A task is considered to have failed if it completes with a non-zero exit code and has exhausted its retry count, or if it had a scheduling error.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolInformation PoolInformation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.PoolInformation PoolInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.PoolInformation" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolInformation As PoolInformation" />
      <MemberSignature Language="F#" Value="member this.PoolInformation : Microsoft.Azure.Batch.PoolInformation with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.PoolInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6baf-117">バッチ サービスが実行されているタスクに作成されたジョブをこれを使用して、プールの設定を取得または<see cref="T:Microsoft.Azure.Batch.JobSpecification" />です。</span><span class="sxs-lookup"><span data-stu-id="f6baf-117">Gets or sets the pool on which the Batch service runs the tasks of jobs created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6baf-118">これを使用して作成されたジョブの優先順位の設定を取得または<see cref="T:Microsoft.Azure.Batch.JobSpecification" />です。</span><span class="sxs-lookup"><span data-stu-id="f6baf-118">Gets or sets the priority of jobs created via this <see cref="T:Microsoft.Azure.Batch.JobSpecification" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
             <span data-ttu-id="f6baf-119">優先順位の値の範囲は -1000 から 1000、-1000 が最も低い優先度と 1000 中優先順位が高いです。</span><span class="sxs-lookup"><span data-stu-id="f6baf-119">Priority values can range from -1000 to 1000, with -1000 being the lowest priority and 1000 being the highest priority.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UsesTaskDependencies">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsesTaskDependencies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsesTaskDependencies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobSpecification.UsesTaskDependencies" />
      <MemberSignature Language="VB.NET" Value="Public Property UsesTaskDependencies As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsesTaskDependencies : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.JobSpecification.UsesTaskDependencies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f6baf-120">このジョブにタスクを作成するかどうかの設定を取得または<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />互いに依存関係を定義することができます。</span><span class="sxs-lookup"><span data-stu-id="f6baf-120">Gets or sets whether tasks in jobs created under this <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> can define dependencies on each other.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f6baf-121">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="f6baf-121">The default value is false.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>