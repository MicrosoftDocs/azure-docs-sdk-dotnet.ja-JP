<Type Name="JobScheduleOperations" FullName="Microsoft.Azure.Batch.JobScheduleOperations">
  <TypeSignature Language="C#" Value="public class JobScheduleOperations : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobScheduleOperations extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobScheduleOperations" />
  <TypeSignature Language="VB.NET" Value="Public Class JobScheduleOperations&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type JobScheduleOperations = class&#xA;    interface IInheritedBehaviors" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="f4c7e-101">Azure Batch のジョブのスケジュールでの操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-101">Performs operations on Azure Batch job schedules.</span></span>
            </summary>
    <remarks>To be added.</remarks>
    <altmember cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />
  </Docs>
  <Members>
    <Member MemberName="CreateJobSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudJobSchedule CreateJobSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudJobSchedule CreateJobSchedule() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.CreateJobSchedule" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateJobSchedule () As CloudJobSchedule" />
      <MemberSignature Language="F#" Value="member this.CreateJobSchedule : unit -&gt; Microsoft.Azure.Batch.CloudJobSchedule" Usage="jobScheduleOperations.CreateJobSchedule " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudJobSchedule</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f4c7e-102">バインド解除されると、バッチ サービスで任意のジョブ スケジュールと整合性のリレーションシップを持たないを CloudJobSchedule のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-102">Creates an instance of CloudJobSchedule that is unbound and does not have a consistency relationship to any job schedule in the Batch Service.</span></span>
            </summary>
        <returns><span data-ttu-id="f4c7e-103">A <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> Batch service への送信されていないかされる新しいジョブ スケジュールを表すです。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-103">A <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> representing a new job schedule that has not been submitted to the Batch service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateJobSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudJobSchedule CreateJobSchedule (string jobScheduleId, Microsoft.Azure.Batch.Schedule schedule, Microsoft.Azure.Batch.JobSpecification jobSpecification);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudJobSchedule CreateJobSchedule(string jobScheduleId, class Microsoft.Azure.Batch.Schedule schedule, class Microsoft.Azure.Batch.JobSpecification jobSpecification) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.CreateJobSchedule(System.String,Microsoft.Azure.Batch.Schedule,Microsoft.Azure.Batch.JobSpecification)" />
      <MemberSignature Language="F#" Value="member this.CreateJobSchedule : string * Microsoft.Azure.Batch.Schedule * Microsoft.Azure.Batch.JobSpecification -&gt; Microsoft.Azure.Batch.CloudJobSchedule" Usage="jobScheduleOperations.CreateJobSchedule (jobScheduleId, schedule, jobSpecification)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudJobSchedule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="schedule" Type="Microsoft.Azure.Batch.Schedule" />
        <Parameter Name="jobSpecification" Type="Microsoft.Azure.Batch.JobSpecification" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="f4c7e-104">ジョブ スケジュールの id です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-104">The id of the job schedule.</span></span></param>
        <param name="schedule"><span data-ttu-id="f4c7e-105">ジョブを作成する場合を決定するスケジュール。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-105">The schedule that determines when jobs will be created.</span></span></param>
        <param name="jobSpecification"><span data-ttu-id="f4c7e-106"><see cref="T:Microsoft.Azure.Batch.JobSpecification" />に従って作成するジョブの詳細を含む、<paramref name="schedule" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-106">a <see cref="T:Microsoft.Azure.Batch.JobSpecification" /> containing details of the jobs to be created according to the <paramref name="schedule" />.</span></span></param>
        <summary>
            <span data-ttu-id="f4c7e-107">バインド解除されると、バッチ サービスで任意のジョブ スケジュールと整合性のリレーションシップを持たないを CloudJobSchedule のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-107">Creates an instance of CloudJobSchedule that is unbound and does not have a consistency relationship to any job schedule in the Batch Service.</span></span>
            </summary>
        <returns><span data-ttu-id="f4c7e-108">A <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> Batch service への送信されていないかされる新しいジョブ スケジュールを表すです。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-108">A <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> representing a new job schedule that has not been submitted to the Batch service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4c7e-109">取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.JobScheduleOperations" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-109">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.JobScheduleOperations" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="f4c7e-110">これらの動作は、子オブジェクトによって継承されます。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-110">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="f4c7e-111">変更は、コレクションの順序で適用されます。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-111">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="f4c7e-112">最後には、wins を記述します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-112">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteJobSchedule">
      <MemberSignature Language="C#" Value="public void DeleteJobSchedule (string jobScheduleId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteJobSchedule(string jobScheduleId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.DeleteJobSchedule(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteJobSchedule (jobScheduleId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteJobSchedule : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobScheduleOperations.DeleteJobSchedule (jobScheduleId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="f4c7e-113">ジョブ スケジュールの id です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-113">The id of the job schedule.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="f4c7e-114">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-114">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="f4c7e-115">指定されたジョブのスケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-115">Deletes the specified job schedule.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="f4c7e-116">削除操作は、ジョブのスケジュールが削除されることを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-116">The delete operation requests that the job schedule be deleted.</span></span>  <span data-ttu-id="f4c7e-117">要求は、スケジュールに格納、<see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-117">The request puts the schedule in the <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Deleting" /> state.</span></span>
            <span data-ttu-id="f4c7e-118">Batch service は既存のジョブとタスクは、アクティブなジョブを含め、スケジュールをすべて削除し、さらにクライアント操作をしなくても、実際のジョブ スケジュールの削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-118">The Batch service will delete any existing jobs and tasks under the schedule, including any active job, and perform the actual job schedule deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="f4c7e-119">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-119">This is a blocking operation.</span></span> <span data-ttu-id="f4c7e-120">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.DeleteJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-120">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.DeleteJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteJobScheduleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteJobScheduleAsync (string jobScheduleId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteJobScheduleAsync(string jobScheduleId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.DeleteJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteJobScheduleAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobScheduleOperations.DeleteJobScheduleAsync (jobScheduleId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobScheduleOperations/&lt;DeleteJobScheduleAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="f4c7e-121">ジョブ スケジュールの id です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-121">The id of the job schedule.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="f4c7e-122">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-122">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f4c7e-123">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-123">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f4c7e-124">指定されたジョブのスケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-124">Deletes the specified job schedule.</span></span>
            </summary>
        <returns><span data-ttu-id="f4c7e-125">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-125">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f4c7e-126">削除操作は、ジョブのスケジュールが削除されることを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-126">The delete operation requests that the job schedule be deleted.</span></span>  <span data-ttu-id="f4c7e-127">要求は、スケジュールに格納、<see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-127">The request puts the schedule in the <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Deleting" /> state.</span></span>
            <span data-ttu-id="f4c7e-128">Batch service は既存のジョブとタスクは、アクティブなジョブを含め、スケジュールをすべて削除し、さらにクライアント操作をしなくても、実際のジョブ スケジュールの削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-128">The Batch service will delete any existing jobs and tasks under the schedule, including any active job, and perform the actual job schedule deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="f4c7e-129">削除操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-129">The delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableJobSchedule">
      <MemberSignature Language="C#" Value="public void DisableJobSchedule (string jobScheduleId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableJobSchedule(string jobScheduleId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.DisableJobSchedule(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DisableJobSchedule (jobScheduleId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DisableJobSchedule : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobScheduleOperations.DisableJobSchedule (jobScheduleId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="f4c7e-130">ジョブ スケジュールの id です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-130">The id of the job schedule.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="f4c7e-131">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-131">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="f4c7e-132">指定されたジョブのスケジュールを無効にします。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-132">Disables the specified job schedule.</span></span>  <span data-ttu-id="f4c7e-133">無効になっているスケジュール、新しいジョブを作成しないでくださいけれども、後で再度有効ことがあります。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-133">Disabled schedules do not create new jobs, but may be re-enabled later.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="f4c7e-134">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-134">This is a blocking operation.</span></span> <span data-ttu-id="f4c7e-135">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.DisableJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-135">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.DisableJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="f4c7e-136">スケジュールを再度有効にするを呼び出す<see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.EnableJobSchedule(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-136">To re-enable the schedule, call <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.EnableJobSchedule(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableJobScheduleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableJobScheduleAsync (string jobScheduleId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableJobScheduleAsync(string jobScheduleId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.DisableJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableJobScheduleAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobScheduleOperations.DisableJobScheduleAsync (jobScheduleId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="f4c7e-137">ジョブ スケジュールの id です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-137">The id of the job schedule.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="f4c7e-138">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-138">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f4c7e-139">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-139">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f4c7e-140">指定されたジョブのスケジュールを無効にします。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-140">Disables the specified job schedule.</span></span>  <span data-ttu-id="f4c7e-141">無効になっているスケジュール、新しいジョブを作成しないでくださいけれども、後で再度有効ことがあります。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-141">Disabled schedules do not create new jobs, but may be re-enabled later.</span></span>
            </summary>
        <returns><span data-ttu-id="f4c7e-142">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-142">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f4c7e-143">無効化操作が非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-143">The disable operation runs asynchronously.</span></span></para>
          <para><span data-ttu-id="f4c7e-144">スケジュールを再度有効にするを呼び出す<see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.EnableJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-144">To re-enable the schedule, call <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.EnableJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableJobSchedule">
      <MemberSignature Language="C#" Value="public void EnableJobSchedule (string jobScheduleId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableJobSchedule(string jobScheduleId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.EnableJobSchedule(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableJobSchedule (jobScheduleId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableJobSchedule : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobScheduleOperations.EnableJobSchedule (jobScheduleId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="f4c7e-145">ジョブ スケジュールの id です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-145">The id of the job schedule.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="f4c7e-146">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-146">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="f4c7e-147">に従って作成されたジョブを許可する、指定したジョブのスケジュールを有効にその<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Schedule" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-147">Enables the specified job schedule, allowing jobs to be created according to its <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Schedule" />.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="f4c7e-148">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-148">This is a blocking operation.</span></span> <span data-ttu-id="f4c7e-149">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.EnableJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-149">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.EnableJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableJobScheduleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableJobScheduleAsync (string jobScheduleId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableJobScheduleAsync(string jobScheduleId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.EnableJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableJobScheduleAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobScheduleOperations.EnableJobScheduleAsync (jobScheduleId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="f4c7e-150">ジョブ スケジュールの id です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-150">The id of the job schedule.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="f4c7e-151">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-151">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f4c7e-152">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-152">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f4c7e-153">に従って作成されたジョブを許可する、指定したジョブのスケジュールを有効にその<see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Schedule" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-153">Enables the specified job schedule, allowing jobs to be created according to its <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Schedule" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f4c7e-154">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-154">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f4c7e-155">有効にする操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-155">The enable operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudJobSchedule GetJobSchedule (string jobScheduleId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudJobSchedule GetJobSchedule(string jobScheduleId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.GetJobSchedule(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetJobSchedule : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.CloudJobSchedule" Usage="jobScheduleOperations.GetJobSchedule (jobScheduleId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudJobSchedule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="f4c7e-156">取得するジョブのスケジュールの id。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-156">The id of the job schedule to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="f4c7e-157">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-157">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="f4c7e-158">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-158">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="f4c7e-159">指定した <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-159">Gets the specified <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f4c7e-160">A<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />指定された Azure Batch のジョブ スケジュールに関する情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-160">A <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> containing information about the specified Azure Batch job schedule.</span></span></returns>
        <remarks><span data-ttu-id="f4c7e-161">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-161">This is a blocking operation.</span></span> <span data-ttu-id="f4c7e-162">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.GetJobScheduleAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-162">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.GetJobScheduleAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobScheduleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudJobSchedule&gt; GetJobScheduleAsync (string jobScheduleId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.CloudJobSchedule&gt; GetJobScheduleAsync(string jobScheduleId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.GetJobScheduleAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetJobScheduleAsync : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudJobSchedule&gt;" Usage="jobScheduleOperations.GetJobScheduleAsync (jobScheduleId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobScheduleOperations/&lt;GetJobScheduleAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudJobSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="f4c7e-163">取得するジョブのスケジュールの id。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-163">The id of the job schedule to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="f4c7e-164">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-164">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="f4c7e-165">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-165">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f4c7e-166">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-166">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f4c7e-167">指定した <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-167">Gets the specified <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f4c7e-168">A<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />指定された Azure Batch のジョブ スケジュールに関する情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-168">A <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> containing information about the specified Azure Batch job schedule.</span></span></returns>
        <remarks><span data-ttu-id="f4c7e-169">ジョブ スケジュールの取得操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-169">The get job schedule operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt; ListJobs (string jobScheduleId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudJob&gt; ListJobs(string jobScheduleId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.ListJobs(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListJobs : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt;" Usage="jobScheduleOperations.ListJobs (jobScheduleId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="f4c7e-170">ジョブ スケジュールの id です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-170">The id of the job schedule.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="f4c7e-171">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-171">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="f4c7e-172">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-172">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="f4c7e-173">列挙、<see cref="T:Microsoft.Azure.Batch.CloudJob">ジョブ</see>指定されたジョブのスケジュールの下に作成します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-173">Enumerates the <see cref="T:Microsoft.Azure.Batch.CloudJob">jobs</see> created under the specified job schedule.</span></span>
            </summary>
        <returns><span data-ttu-id="f4c7e-174"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を非同期的または同期的に、ジョブを列挙を使用できます。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-174">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate jobs asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="f4c7e-175">このメソッドがすぐに戻るジョブは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-175">This method returns immediately; the jobs are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="f4c7e-176">検索は非アトミックなです。ジョブは、コレクションの列挙中にページで取得されます。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-176">Retrieval is non-atomic; jobs are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobSchedules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJobSchedule&gt; ListJobSchedules (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudJobSchedule&gt; ListJobSchedules(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.ListJobSchedules(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListJobSchedules : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJobSchedule&gt;" Usage="jobScheduleOperations.ListJobSchedules (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJobSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="f4c7e-177">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-177">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="f4c7e-178">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-178">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="f4c7e-179">列挙、<see cref="T:Microsoft.Azure.Batch.CloudJobSchedule">ジョブのスケジュール</see>Batch アカウントにします。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-179">Enumerates the <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule">job schedules</see> in the Batch account.</span></span>
            </summary>
        <returns><span data-ttu-id="f4c7e-180"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を非同期的または同期的に、ジョブのスケジュールを列挙を使用できます。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-180">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate job schedules asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="f4c7e-181">このメソッドがすぐに戻るジョブのスケジュールは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-181">This method returns immediately; the job schedules are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="f4c7e-182">検索は非アトミックなです。スケジュールは、コレクションの列挙中にページで取得されます。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-182">Retrieval is non-atomic; schedules are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateJobSchedule">
      <MemberSignature Language="C#" Value="public void TerminateJobSchedule (string jobScheduleId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TerminateJobSchedule(string jobScheduleId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.TerminateJobSchedule(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub TerminateJobSchedule (jobScheduleId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.TerminateJobSchedule : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobScheduleOperations.TerminateJobSchedule (jobScheduleId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="f4c7e-183">ジョブ スケジュールの id です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-183">The id of the job schedule.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="f4c7e-184">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-184">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="f4c7e-185">指定されたジョブのスケジュールを終了します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-185">Terminates the specified job schedule.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="f4c7e-186">終了操作は、ジョブのスケジュールが終了することを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-186">The terminate operation requests that the job schedule be terminated.</span></span>  <span data-ttu-id="f4c7e-187">要求は、スケジュールに格納、<see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Terminating" />状態です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-187">The request puts the schedule in the <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Terminating" /> state.</span></span>
            <span data-ttu-id="f4c7e-188">バッチ サービスは任意のアクティブなジョブ、終了するまで待機し、その他のクライアント操作しなくても、実際のジョブ スケジュールの終了を実行します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-188">The Batch service will wait for any active job to terminate, and perform the actual job schedule termination without any further client action.</span></span></para>
          <para><span data-ttu-id="f4c7e-189">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-189">This is a blocking operation.</span></span> <span data-ttu-id="f4c7e-190">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.TerminateJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-190">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.TerminateJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateJobScheduleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task TerminateJobScheduleAsync (string jobScheduleId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task TerminateJobScheduleAsync(string jobScheduleId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.TerminateJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.TerminateJobScheduleAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobScheduleOperations.TerminateJobScheduleAsync (jobScheduleId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobScheduleOperations/&lt;TerminateJobScheduleAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="f4c7e-191">ジョブ スケジュールの id です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-191">The id of the job schedule.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="f4c7e-192">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-192">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f4c7e-193">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-193">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f4c7e-194">指定されたジョブのスケジュールを終了します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-194">Terminates the specified job schedule.</span></span>
            </summary>
        <returns><span data-ttu-id="f4c7e-195">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-195">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f4c7e-196">終了操作は、ジョブのスケジュールが終了することを要求します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-196">The terminate operation requests that the job schedule be terminated.</span></span>  <span data-ttu-id="f4c7e-197">要求は、スケジュールに格納、<see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Terminating" />状態です。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-197">The request puts the schedule in the <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Terminating" /> state.</span></span>
            <span data-ttu-id="f4c7e-198">バッチ サービスは任意のアクティブなジョブ、終了するまで待機し、その他のクライアント操作しなくても、実際のジョブ スケジュールの終了を実行します。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-198">The Batch service will wait for any active job to terminate, and perform the actual job schedule termination without any further client action.</span></span></para>
          <para><span data-ttu-id="f4c7e-199">終了操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="f4c7e-199">The terminate operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>