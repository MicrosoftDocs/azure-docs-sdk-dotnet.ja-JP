<Type Name="JobOperations" FullName="Microsoft.Azure.Batch.JobOperations">
  <TypeSignature Language="C#" Value="public class JobOperations : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobOperations extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Class JobOperations&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type JobOperations = class&#xA;    interface IInheritedBehaviors" />
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
            <span data-ttu-id="d3988-101">Azure Batch のジョブで操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="d3988-101">Performs operations on Azure Batch jobs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
    <altmember cref="T:Microsoft.Azure.Batch.CloudJob" />
  </Docs>
  <Members>
    <Member MemberName="AddTask">
      <MemberSignature Language="C#" Value="public System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt; AddTask (string jobId, Microsoft.Azure.Batch.CloudTask taskToAdd, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt; AddTask(string jobId, class Microsoft.Azure.Batch.CloudTask taskToAdd, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,Microsoft.Azure.Batch.CloudTask,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddTask (jobId As String, taskToAdd As CloudTask, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As ConcurrentDictionary(Of Type, IFileStagingArtifact)" />
      <MemberSignature Language="F#" Value="member this.AddTask : string * Microsoft.Azure.Batch.CloudTask * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;" Usage="jobOperations.AddTask (jobId, taskToAdd, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskToAdd" Type="Microsoft.Azure.Batch.CloudTask" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-102">タスクを追加するジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-102">The id of the job to which to add the task.</span></span></param>
        <param name="taskToAdd"><span data-ttu-id="d3988-103">追加する <see cref="T:Microsoft.Azure.Batch.CloudTask" />。</span><span class="sxs-lookup"><span data-stu-id="d3988-103">The <see cref="T:Microsoft.Azure.Batch.CloudTask" /> to add.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-104">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-104">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-105">ジョブを 1 つのタスクを追加します。</span><span class="sxs-lookup"><span data-stu-id="d3988-105">Adds a single task to a job.</span></span>  <span data-ttu-id="d3988-106">複数のタスクを追加する<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>です。</span><span class="sxs-lookup"><span data-stu-id="d3988-106">To add multiple tasks, use <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-107">ステージング処理ファイルに関する情報のコレクション (を参照してください<see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />)。</span><span class="sxs-lookup"><span data-stu-id="d3988-107">A collection of information about the file staging process (see <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).</span></span>
            <span data-ttu-id="d3988-108">詳細については、「<see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="d3988-108">For more information see <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="d3988-109">このメソッドを呼び出すたびには、バッチ サービスへの要求が発生します。</span><span class="sxs-lookup"><span data-stu-id="d3988-109">Each call to this method incurs a request to the Batch service.</span></span> <span data-ttu-id="d3988-110">したがって、このメソッドを使用して、複数のタスクが一括を使用するよりも効率の低いを追加するメソッドを追加し、HTTP 接続の制限が発生することができます。</span><span class="sxs-lookup"><span data-stu-id="d3988-110">Therefore, using this method to add multiple tasks is less efficient than using a bulk add method, and can incur HTTP connection restrictions.</span></span>
            <span data-ttu-id="d3988-111">場合は、これらの操作の多くの並列で実行し、クライアント側のタイムアウトが表示される、http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx を参照してくださいか使用してください、複数のタスクAddTask のオーバー ロードします。</span><span class="sxs-lookup"><span data-stu-id="d3988-111">If you are performing many of these operations in parallel and are seeing client side timeouts, please see http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx or use the multiple-task overload of AddTask.</span></span></para>
          <para><span data-ttu-id="d3988-112">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="d3988-112">This is a blocking operation.</span></span> <span data-ttu-id="d3988-113">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-113">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddTask">
      <MemberSignature Language="C#" Value="public void AddTask (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions = null, System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts = null, Nullable&lt;TimeSpan&gt; timeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddTask(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, class Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions, class System.Collections.Concurrent.ConcurrentBag`1&lt;class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddTask (jobId As String, tasksToAdd As IEnumerable(Of CloudTask), Optional parallelOptions As BatchClientParallelOptions = null, Optional fileStagingArtifacts As ConcurrentBag(Of ConcurrentDictionary(Of Type, IFileStagingArtifact)) = null, Optional timeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.AddTask : string * seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.BatchClientParallelOptions * System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.AddTask (jobId, tasksToAdd, parallelOptions, fileStagingArtifacts, timeout, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="tasksToAdd" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="parallelOptions" Type="Microsoft.Azure.Batch.BatchClientParallelOptions" />
        <Parameter Name="fileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt;" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-114">タスクを追加するジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-114">The id of the job to which to add the tasks.</span></span></param>
        <param name="tasksToAdd"><span data-ttu-id="d3988-115"><see cref="T:Microsoft.Azure.Batch.CloudTask" />S を追加します。</span><span class="sxs-lookup"><span data-stu-id="d3988-115">The <see cref="T:Microsoft.Azure.Batch.CloudTask" />s to add.</span></span></param>
        <param name="parallelOptions">
            <span data-ttu-id="d3988-116">バッチ サービスに発行された同時の並列 AddTaskCollection 要求の数を制御します。</span><span class="sxs-lookup"><span data-stu-id="d3988-116">Controls the number of simultaneous parallel AddTaskCollection requests issued to the Batch service.</span></span>  <span data-ttu-id="d3988-117">各 AddTaskCollection 要求が最大で含まれている<see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />その中のタスクです。</span><span class="sxs-lookup"><span data-stu-id="d3988-117">Each AddTaskCollection request contains at most <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" /> tasks in it.</span></span>
            <span data-ttu-id="d3988-118">また、操作のキャンセル トークンを制御します。</span><span class="sxs-lookup"><span data-stu-id="d3988-118">Also controls the cancellation token for the operation.</span></span>
            <span data-ttu-id="d3988-119">既定値が使用される省略すると、(を参照してください<see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />)。</span><span class="sxs-lookup"><span data-stu-id="d3988-119">If omitted, the default is used (see <see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />.)</span></span>
            </param>
        <param name="fileStagingArtifacts"><span data-ttu-id="d3988-120">ステージング処理ファイルに関する情報を受信する、省略可能なコレクション (を参照してください<see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />)。</span><span class="sxs-lookup"><span data-stu-id="d3988-120">An optional collection to receive information about the file staging process (see <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).</span></span>
            <span data-ttu-id="d3988-121">エントリを追加、 <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" /> Batch service に送信するグループ化されたタスクのセットごとにします。</span><span class="sxs-lookup"><span data-stu-id="d3988-121">An entry is added to the <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" /> for each set of tasks grouped for submission to the Batch service.</span></span>
            <span data-ttu-id="d3988-122">単一タスクとは異なりを追加、ファイルのステージング処理をカスタマイズする、このパラメーターを使用することはできません。</span><span class="sxs-lookup"><span data-stu-id="d3988-122">Unlike single-task adds, you cannot use this parameter to customize the file staging process.</span></span>
            <span data-ttu-id="d3988-123">各エントリの形式に関する詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-123">For more information about the format of each entry, see <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="d3988-124">操作がタイムアウトするまでの時間。</span><span class="sxs-lookup"><span data-stu-id="d3988-124">The amount of time after which the operation times out.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-125">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-125">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-126">ジョブにタスクを追加します。</span><span class="sxs-lookup"><span data-stu-id="d3988-126">Adds tasks to a job.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="d3988-127">これは、ブロッキング操作です。非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-127">This is a blocking operation; for a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></para>
          <para><span data-ttu-id="d3988-128">このメソッドは、アトミックです。つまり、メソッドがタスクの追加を開始し、失敗する可能性です。</span><span class="sxs-lookup"><span data-stu-id="d3988-128">This method is not atomic; that is, it is possible for the method to start adding tasks and then fail.</span></span> <span data-ttu-id="d3988-129">追加するタスクのコレクションに分割されるサイズのチャンク多くて<see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />、各チャンクに対して AddTaskCollection 要求が実行されたとします。</span><span class="sxs-lookup"><span data-stu-id="d3988-129">The collection of tasks to add is broken down into chunks of size at most <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />, and an AddTaskCollection request is issued for each chunk.</span></span>  <span data-ttu-id="d3988-130">に従って並列で要求を発行することがあります、<paramref name="parallelOptions" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-130">Requests may be issued in parallel according to the <paramref name="parallelOptions" />.</span></span></para>
          <para><span data-ttu-id="d3988-131">Batch service への多数の同時要求の発行と、HTTP 接続の制限が発生することができます。</span><span class="sxs-lookup"><span data-stu-id="d3988-131">Issuing a large number of simultaneous requests to the Batch service can incur HTTP connection restrictions.</span></span>
            <span data-ttu-id="d3988-132">これらの操作の多くを並列で実行中 (または、parallelOptions で大きな MaxDegreeOfParallelism を指定した) 場合とは、クライアント側のタイムアウト、http://msdn.microsoft.com/en-us/library/ を参照してくださいsystem.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx です。</span><span class="sxs-lookup"><span data-stu-id="d3988-132">If you are performing many of these operations in parallel (or have specified a large MaxDegreeOfParallelism in the parallelOptions) and are seeing client side timeouts, please see http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx .</span></span></para>
          <para><span data-ttu-id="d3988-133">エラーが発生した場合、操作の進行状況は、によって決まります<see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" />動作します。</span><span class="sxs-lookup"><span data-stu-id="d3988-133">The progress of the operation in the face of errors is determined by <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" /> behavior.</span></span>
            <span data-ttu-id="d3988-134">通常、クライアントは、通常の状況で動作する、既定値を使用してバッチとして、この動作を指定する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="d3988-134">You do not normally need to specify this behavior, as the Batch client uses a default which works in normal circumstances.</span></span>
            <span data-ttu-id="d3988-135">この動作をカスタマイズする場合、AddTaskCollectionResultHandler 内の指定、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />または<paramref name="additionalBehaviors" />コレクション。</span><span class="sxs-lookup"><span data-stu-id="d3988-135">If you do want to customize this behavior, specify an AddTaskCollectionResultHandler in the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> or <paramref name="additionalBehaviors" /> collections.</span></span></para>
        </remarks>
        <exception cref="T:Microsoft.Azure.Batch.ParallelOperationsException"><span data-ttu-id="d3988-136">Batch service への 1 つまたは複数の要求が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3988-136">Thrown if one or more requests to the Batch service fail.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AddTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddTaskAsync (string jobId, Microsoft.Azure.Batch.CloudTask taskToAdd, System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt; allFileStagingArtifacts = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddTaskAsync(string jobId, class Microsoft.Azure.Batch.CloudTask taskToAdd, class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt; allFileStagingArtifacts, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.AddTaskAsync : string * Microsoft.Azure.Batch.CloudTask * System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.AddTaskAsync (jobId, taskToAdd, allFileStagingArtifacts, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskToAdd" Type="Microsoft.Azure.Batch.CloudTask" />
        <Parameter Name="allFileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-137">タスクを追加するジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-137">The id of the job to which to add the task.</span></span></param>
        <param name="taskToAdd"><span data-ttu-id="d3988-138">追加する <see cref="T:Microsoft.Azure.Batch.CloudTask" />。</span><span class="sxs-lookup"><span data-stu-id="d3988-138">The <see cref="T:Microsoft.Azure.Batch.CloudTask" /> to add.</span></span></param>
        <param name="allFileStagingArtifacts"><span data-ttu-id="d3988-139">オプションのコレクションをカスタマイズし、ステージング処理ファイルに関する情報を受け取ります (を参照してください<see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />)。</span><span class="sxs-lookup"><span data-stu-id="d3988-139">An optional collection to customize and receive information about the file staging process (see <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).</span></span>
            <span data-ttu-id="d3988-140">詳細については、「<see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="d3988-140">For more information see <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-141">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-141">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d3988-142">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="d3988-142">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-143">ジョブを 1 つのタスクを追加します。</span><span class="sxs-lookup"><span data-stu-id="d3988-143">Adds a single task to a job.</span></span>  <span data-ttu-id="d3988-144">複数のタスクを追加する<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>です。</span><span class="sxs-lookup"><span data-stu-id="d3988-144">To add multiple tasks, use <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-145">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d3988-145">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="d3988-146">このメソッドを呼び出すたびには、バッチ サービスへの要求が発生します。</span><span class="sxs-lookup"><span data-stu-id="d3988-146">Each call to this method incurs a request to the Batch service.</span></span> <span data-ttu-id="d3988-147">したがって、このメソッドを使用して、複数のタスクが一括を使用するよりも効率の低いを追加するメソッドを追加し、HTTP 接続の制限が発生することができます。</span><span class="sxs-lookup"><span data-stu-id="d3988-147">Therefore, using this method to add multiple tasks is less efficient than using a bulk add method, and can incur HTTP connection restrictions.</span></span>
            <span data-ttu-id="d3988-148">場合は、これらの操作の多くの並列で実行し、クライアント側のタイムアウトが表示される、http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx を参照してくださいか使用してください、複数のタスクAddTaskAsync のオーバー ロードします。</span><span class="sxs-lookup"><span data-stu-id="d3988-148">If you are performing many of these operations in parallel and are seeing client side timeouts, please see http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx or use the multiple-task overload of AddTaskAsync.</span></span></para>
          <para><span data-ttu-id="d3988-149">タスクの追加操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-149">The add task operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddTaskAsync (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions = null, System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts = null, Nullable&lt;TimeSpan&gt; timeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddTaskAsync(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, class Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions, class System.Collections.Concurrent.ConcurrentBag`1&lt;class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddTaskAsync (jobId As String, tasksToAdd As IEnumerable(Of CloudTask), Optional parallelOptions As BatchClientParallelOptions = null, Optional fileStagingArtifacts As ConcurrentBag(Of ConcurrentDictionary(Of Type, IFileStagingArtifact)) = null, Optional timeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As Task" />
      <MemberSignature Language="F#" Value="member this.AddTaskAsync : string * seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.BatchClientParallelOptions * System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="jobOperations.AddTaskAsync (jobId, tasksToAdd, parallelOptions, fileStagingArtifacts, timeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;AddTaskAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="tasksToAdd" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="parallelOptions" Type="Microsoft.Azure.Batch.BatchClientParallelOptions" />
        <Parameter Name="fileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt;" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-150">タスクを追加するジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-150">The id of the job to which to add the tasks.</span></span></param>
        <param name="tasksToAdd"><span data-ttu-id="d3988-151"><see cref="T:Microsoft.Azure.Batch.CloudTask" />S を追加します。</span><span class="sxs-lookup"><span data-stu-id="d3988-151">The <see cref="T:Microsoft.Azure.Batch.CloudTask" />s to add.</span></span></param>
        <param name="parallelOptions">
            <span data-ttu-id="d3988-152">バッチ サービスに発行された同時の並列 AddTaskCollection 要求の数を制御します。</span><span class="sxs-lookup"><span data-stu-id="d3988-152">Controls the number of simultaneous parallel AddTaskCollection requests issued to the Batch service.</span></span>  <span data-ttu-id="d3988-153">各 AddTaskCollection 要求が最大で含まれている<see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />その中のタスクです。</span><span class="sxs-lookup"><span data-stu-id="d3988-153">Each AddTaskCollection request contains at most <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" /> tasks in it.</span></span>
            <span data-ttu-id="d3988-154">また、操作のキャンセル トークンを制御します。</span><span class="sxs-lookup"><span data-stu-id="d3988-154">Also controls the cancellation token for the operation.</span></span>
            <span data-ttu-id="d3988-155">既定値が使用される省略すると、(を参照してください<see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />)。</span><span class="sxs-lookup"><span data-stu-id="d3988-155">If omitted, the default is used (see <see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />.)</span></span>
            </param>
        <param name="fileStagingArtifacts"><span data-ttu-id="d3988-156">ステージング処理ファイルに関する情報を受信する、省略可能なコレクション (を参照してください<see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />)。</span><span class="sxs-lookup"><span data-stu-id="d3988-156">An optional collection to receive information about the file staging process (see <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).</span></span>
            <span data-ttu-id="d3988-157">エントリを追加、 <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" /> Batch service に送信するグループ化されたタスクのセットごとにします。</span><span class="sxs-lookup"><span data-stu-id="d3988-157">An entry is added to the <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" /> for each set of tasks grouped for submission to the Batch service.</span></span>
            <span data-ttu-id="d3988-158">単一タスクとは異なりを追加、ファイルのステージング処理をカスタマイズする、このパラメーターを使用することはできません。</span><span class="sxs-lookup"><span data-stu-id="d3988-158">Unlike single-task adds, you cannot use this parameter to customize the file staging process.</span></span>
            <span data-ttu-id="d3988-159">各エントリの形式に関する詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-159">For more information about the format of each entry, see <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="d3988-160">操作がタイムアウトするまでの時間。</span><span class="sxs-lookup"><span data-stu-id="d3988-160">The amount of time after which the operation times out.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-161">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-161">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-162">ジョブにタスクを追加します。</span><span class="sxs-lookup"><span data-stu-id="d3988-162">Adds tasks to a job.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-163">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d3988-163">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="d3988-164">タスクの追加操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-164">The add task operation runs asynchronously.</span></span></para>
          <para><span data-ttu-id="d3988-165">このメソッドは、アトミックです。つまり、メソッドがタスクの追加を開始し、失敗する可能性です。</span><span class="sxs-lookup"><span data-stu-id="d3988-165">This method is not atomic; that is, it is possible for the method to start adding tasks and then fail.</span></span> <span data-ttu-id="d3988-166">追加するタスクのコレクションに分割されるサイズのチャンク多くて<see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />、各チャンクに対して AddTaskCollection 要求が実行されたとします。</span><span class="sxs-lookup"><span data-stu-id="d3988-166">The collection of tasks to add is broken down into chunks of size at most <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />, and an AddTaskCollection request is issued for each chunk.</span></span>  <span data-ttu-id="d3988-167">に従って並列で要求を発行することがあります、<paramref name="parallelOptions" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-167">Requests may be issued in parallel according to the <paramref name="parallelOptions" />.</span></span></para>
          <para><span data-ttu-id="d3988-168">Batch service への多数の同時要求の発行と、HTTP 接続の制限が発生することができます。</span><span class="sxs-lookup"><span data-stu-id="d3988-168">Issuing a large number of simultaneous requests to the Batch service can incur HTTP connection restrictions.</span></span>
            <span data-ttu-id="d3988-169">これらの操作の多くを並列で実行中 (または、parallelOptions で大きな MaxDegreeOfParallelism を指定した) 場合とは、クライアント側のタイムアウト、http://msdn.microsoft.com/en-us/library/ を参照してくださいsystem.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx です。</span><span class="sxs-lookup"><span data-stu-id="d3988-169">If you are performing many of these operations in parallel (or have specified a large MaxDegreeOfParallelism in the parallelOptions) and are seeing client side timeouts, please see http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx .</span></span></para>
          <para><span data-ttu-id="d3988-170">エラーが発生した場合、操作の進行状況は、によって決まります<see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" />動作します。</span><span class="sxs-lookup"><span data-stu-id="d3988-170">The progress of the operation in the face of errors is determined by <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" /> behavior.</span></span>
            <span data-ttu-id="d3988-171">通常、クライアントは、通常の状況で動作する、既定値を使用してバッチとして、この動作を指定する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="d3988-171">You do not normally need to specify this behavior, as the Batch client uses a default which works in normal circumstances.</span></span>
            <span data-ttu-id="d3988-172">この動作をカスタマイズする場合、AddTaskCollectionResultHandler 内の指定、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />または<paramref name="additionalBehaviors" />コレクション。</span><span class="sxs-lookup"><span data-stu-id="d3988-172">If you do want to customize this behavior, specify an AddTaskCollectionResultHandler in the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> or <paramref name="additionalBehaviors" /> collections.</span></span></para>
        </remarks>
        <exception cref="T:Microsoft.Azure.Batch.ParallelOperationsException"><span data-ttu-id="d3988-173">Batch service への 1 つまたは複数の要求が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3988-173">Thrown if one or more requests to the Batch service fail.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateJob">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudJob CreateJob ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudJob CreateJob() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.CreateJob" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateJob () As CloudJob" />
      <MemberSignature Language="F#" Value="member this.CreateJob : unit -&gt; Microsoft.Azure.Batch.CloudJob" Usage="jobOperations.CreateJob " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudJob</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d3988-174">バインドが、バッチ サービスで任意のジョブを整合性のリレーションシップを持たない CloudJob のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="d3988-174">Creates an instance of CloudJob that is unbound and does not have a consistency relationship to any job in the Batch Service.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-175">A <see cref="T:Microsoft.Azure.Batch.CloudJob" /> Batch service への送信されていないかの新しいジョブを表すです。</span><span class="sxs-lookup"><span data-stu-id="d3988-175">A <see cref="T:Microsoft.Azure.Batch.CloudJob" /> representing a new job that has not been submitted to the Batch service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateJob">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudJob CreateJob (string jobId, Microsoft.Azure.Batch.PoolInformation poolInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudJob CreateJob(string jobId, class Microsoft.Azure.Batch.PoolInformation poolInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.CreateJob(System.String,Microsoft.Azure.Batch.PoolInformation)" />
      <MemberSignature Language="F#" Value="member this.CreateJob : string * Microsoft.Azure.Batch.PoolInformation -&gt; Microsoft.Azure.Batch.CloudJob" Usage="jobOperations.CreateJob (jobId, poolInformation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="poolInformation" Type="Microsoft.Azure.Batch.PoolInformation" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-176">ジョブの Id。</span><span class="sxs-lookup"><span data-stu-id="d3988-176">The Id of the job.</span></span></param>
        <param name="poolInformation"><span data-ttu-id="d3988-177">プールの情報、ジョブが実行されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-177">The information about the pool the job will run on.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-178">バインドが、バッチ サービスで任意のジョブを整合性のリレーションシップを持たない CloudJob のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="d3988-178">Creates an instance of CloudJob that is unbound and does not have a consistency relationship to any job in the Batch Service.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-179">A <see cref="T:Microsoft.Azure.Batch.CloudJob" /> Batch service への送信されていないかの新しいジョブを表すです。</span><span class="sxs-lookup"><span data-stu-id="d3988-179">A <see cref="T:Microsoft.Azure.Batch.CloudJob" /> representing a new job that has not been submitted to the Batch service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />
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
            <span data-ttu-id="d3988-180">取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.JobOperations" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-180">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.JobOperations" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="d3988-181">これらの動作は、子オブジェクトによって継承されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-181">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="d3988-182">変更は、コレクションの順序で適用されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-182">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="d3988-183">最後には、wins を記述します。</span><span class="sxs-lookup"><span data-stu-id="d3988-183">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteJob">
      <MemberSignature Language="C#" Value="public void DeleteJob (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteJob(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteJob(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteJob (jobId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteJob : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.DeleteJob (jobId, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-184">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-184">The id of the job.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-185">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-185">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-186">指定したジョブを削除します。</span><span class="sxs-lookup"><span data-stu-id="d3988-186">Deletes the specified job.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="d3988-187">削除操作は、ジョブを削除することを要求します。</span><span class="sxs-lookup"><span data-stu-id="d3988-187">The delete operation requests that the job be deleted.</span></span>  <span data-ttu-id="d3988-188">要求、ジョブを格納する、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="d3988-188">The request puts the job in the <see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" /> state.</span></span>
            <span data-ttu-id="d3988-189">バッチ サービスは、実行中のタスクを停止し、さらにクライアント操作をしなくても、実際のジョブの削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="d3988-189">The Batch service will stop any running tasks and perform the actual job deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="d3988-190">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="d3988-190">This is a blocking operation.</span></span> <span data-ttu-id="d3988-191">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.DeleteJobAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-191">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobOperations.DeleteJobAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteJobAsync (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteJobAsync(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteJobAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteJobAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.DeleteJobAsync (jobId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;DeleteJobAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-192">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-192">The id of the job.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-193">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-193">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d3988-194">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="d3988-194">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-195">指定したジョブを削除します。</span><span class="sxs-lookup"><span data-stu-id="d3988-195">Deletes the specified job.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-196">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="d3988-196">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="d3988-197">削除操作は、ジョブを削除することを要求します。</span><span class="sxs-lookup"><span data-stu-id="d3988-197">The delete operation requests that the job be deleted.</span></span>  <span data-ttu-id="d3988-198">要求、ジョブを格納する、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="d3988-198">The request puts the job in the <see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" /> state.</span></span>
            <span data-ttu-id="d3988-199">バッチ サービスは、実行中のタスクを停止し、さらにクライアント操作をしなくても、実際のジョブの削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="d3988-199">The Batch service will stop any running tasks and perform the actual job deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="d3988-200">削除操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-200">The delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNodeFile">
      <MemberSignature Language="C#" Value="public void DeleteNodeFile (string jobId, string taskId, string filePath, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteNodeFile(string jobId, string taskId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteNodeFile(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteNodeFile (jobId As String, taskId As String, filePath As String, Optional recursive As Nullable(Of Boolean) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteNodeFile : string * string * string * Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.DeleteNodeFile (jobId, taskId, filePath, recursive, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-201">タスクを含むジョブの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-201">The id of the job containing the task.</span></span></param>
        <param name="taskId"><span data-ttu-id="d3988-202">タスクの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-202">The id of the task.</span></span></param>
        <param name="filePath"><span data-ttu-id="d3988-203">削除するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="d3988-203">The path of the file to delete.</span></span></param>
        <param name="recursive">
            <span data-ttu-id="d3988-204">ファイル パスのパラメーターは、ファイルの代わりにディレクトリを表している場合にディレクトリを削除するには、省略可能な再帰的なパラメーターをすべてのファイルとサブディレクトリを設定できます。</span><span class="sxs-lookup"><span data-stu-id="d3988-204">If the file-path parameter represents a directory instead of a file, you can set the optional recursive parameter to true to delete the directory and all of the files and subdirectories in it.</span></span> <span data-ttu-id="d3988-205">再帰が false の場合、ディレクトリを空にする必要がありますか、削除は失敗します。</span><span class="sxs-lookup"><span data-stu-id="d3988-205">If recursive is false then the directory must be empty or deletion will fail.</span></span>
            </param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-206">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-206">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-207">コンピューティング ノードでこのタスクのディレクトリから指定されたファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="d3988-207">Deletes the specified file from the task's directory on its compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-208">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="d3988-208">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="d3988-209">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="d3988-209">This is a blocking operation.</span></span>  <span data-ttu-id="d3988-210">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-210">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNodeFileAsync (string jobId, string taskId, string filePath, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNodeFileAsync(string jobId, string taskId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteNodeFileAsync : string * string * string * Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.DeleteNodeFileAsync (jobId, taskId, filePath, recursive, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;DeleteNodeFileAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-211">タスクを含むジョブの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-211">The id of the job containing the task.</span></span></param>
        <param name="taskId"><span data-ttu-id="d3988-212">タスクの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-212">The id of the task.</span></span></param>
        <param name="filePath"><span data-ttu-id="d3988-213">削除するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="d3988-213">The path of the file to delete.</span></span></param>
        <param name="recursive">
            <span data-ttu-id="d3988-214">ファイル パスのパラメーターは、ファイルの代わりにディレクトリを表している場合にディレクトリを削除するには、省略可能な再帰的なパラメーターをすべてのファイルとサブディレクトリを設定できます。</span><span class="sxs-lookup"><span data-stu-id="d3988-214">If the file-path parameter represents a directory instead of a file, you can set the optional recursive parameter to true to delete the directory and all of the files and subdirectories in it.</span></span> <span data-ttu-id="d3988-215">再帰が false の場合、ディレクトリを空にする必要がありますか、削除は失敗します。</span><span class="sxs-lookup"><span data-stu-id="d3988-215">If recursive is false then the directory must be empty or deletion will fail.</span></span>
            </param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-216">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-216">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d3988-217">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="d3988-217">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-218">コンピューティング ノードでこのタスクのディレクトリから指定されたファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="d3988-218">Deletes the specified file from the task's directory on its compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-219">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="d3988-219">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="d3988-220">削除操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-220">The delete operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteTask">
      <MemberSignature Language="C#" Value="public void DeleteTask (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteTask(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteTask(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteTask (jobId As String, taskId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteTask : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.DeleteTask (jobId, taskId, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-221">タスクを含むジョブの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-221">The id of the job containing the task.</span></span></param>
        <param name="taskId"><span data-ttu-id="d3988-222">タスクの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-222">The id of the task.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-223">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-223">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-224">指定したタスクを削除します。</span><span class="sxs-lookup"><span data-stu-id="d3988-224">Deletes the specified task.</span></span>
            </summary>
        <remarks><span data-ttu-id="d3988-225">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="d3988-225">This is a blocking operation.</span></span>  <span data-ttu-id="d3988-226">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.DeleteTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-226">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobOperations.DeleteTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteTaskAsync (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteTaskAsync(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteTaskAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.DeleteTaskAsync (jobId, taskId, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-227">タスクを含むジョブの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-227">The id of the job containing the task.</span></span></param>
        <param name="taskId"><span data-ttu-id="d3988-228">タスクの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-228">The id of the task.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-229">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-229">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d3988-230">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="d3988-230">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-231">指定したタスクを削除します。</span><span class="sxs-lookup"><span data-stu-id="d3988-231">Deletes the specified task.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-232">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="d3988-232">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="d3988-233">削除操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-233">The delete operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableJob">
      <MemberSignature Language="C#" Value="public void DisableJob (string jobId, Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableJob(string jobId, valuetype Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DisableJob(System.String,Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.DisableJob : string * Microsoft.Azure.Batch.Common.DisableJobOption * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.DisableJob (jobId, disableJobOption, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="disableJobOption" Type="Microsoft.Azure.Batch.Common.DisableJobOption" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-234">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-234">The id of the job.</span></span></param>
        <param name="disableJobOption"><span data-ttu-id="d3988-235">ジョブに関連付けられているアクティブなタスクを行うには新機能を指定します。</span><span class="sxs-lookup"><span data-stu-id="d3988-235">Specifies what to do with active tasks associated with the job.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-236">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-236">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-237">指定したジョブを無効にします。</span><span class="sxs-lookup"><span data-stu-id="d3988-237">Disables the specified job.</span></span>  <span data-ttu-id="d3988-238">無効なジョブは、新しいタスクを実行しないでくださいが、後で再度有効ことがあります。</span><span class="sxs-lookup"><span data-stu-id="d3988-238">Disabled jobs do not run new tasks, but may be re-enabled later.</span></span>
            </summary>
        <remarks><span data-ttu-id="d3988-239">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="d3988-239">This is a blocking operation.</span></span> <span data-ttu-id="d3988-240">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.DisableJobAsync(System.String,Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-240">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobOperations.DisableJobAsync(System.String,Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableJobAsync (string jobId, Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableJobAsync(string jobId, valuetype Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DisableJobAsync(System.String,Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableJobAsync : string * Microsoft.Azure.Batch.Common.DisableJobOption * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.DisableJobAsync (jobId, disableJobOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;DisableJobAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="disableJobOption" Type="Microsoft.Azure.Batch.Common.DisableJobOption" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-241">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-241">The id of the job.</span></span></param>
        <param name="disableJobOption"><span data-ttu-id="d3988-242">ジョブに関連付けられているアクティブなタスクを行うには新機能を指定します。</span><span class="sxs-lookup"><span data-stu-id="d3988-242">Specifies what to do with active tasks associated with the job.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-243">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-243">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d3988-244">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="d3988-244">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-245">指定したジョブを無効にします。</span><span class="sxs-lookup"><span data-stu-id="d3988-245">Disables the specified job.</span></span>  <span data-ttu-id="d3988-246">無効なジョブは、新しいタスクを実行しないでくださいが、後で再度有効ことがあります。</span><span class="sxs-lookup"><span data-stu-id="d3988-246">Disabled jobs do not run new tasks, but may be re-enabled later.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-247">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="d3988-247">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="d3988-248">無効化操作が非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-248">The disable operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableJob">
      <MemberSignature Language="C#" Value="public void EnableJob (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableJob(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.EnableJob(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableJob (jobId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableJob : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.EnableJob (jobId, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-249">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-249">The id of the job.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-250">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-250">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-251">新しいタスクの実行を許可する、指定されたジョブを有効にします。</span><span class="sxs-lookup"><span data-stu-id="d3988-251">Enables the specified job, allowing new tasks to run.</span></span>
            </summary>
        <remarks><span data-ttu-id="d3988-252">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="d3988-252">This is a blocking operation.</span></span> <span data-ttu-id="d3988-253">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.EnableJobAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-253">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobOperations.EnableJobAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableJobAsync (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableJobAsync(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.EnableJobAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableJobAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.EnableJobAsync (jobId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;EnableJobAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-254">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-254">The id of the job.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-255">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-255">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d3988-256">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="d3988-256">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-257">新しいタスクの実行を許可する、指定されたジョブを有効にします。</span><span class="sxs-lookup"><span data-stu-id="d3988-257">Enables the specified job, allowing new tasks to run.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-258">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="d3988-258">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="d3988-259">有効にする操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-259">The enable operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobStatistics GetAllLifetimeStatistics (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.JobStatistics GetAllLifetimeStatistics(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetAllLifetimeStatistics(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllLifetimeStatistics (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As JobStatistics" />
      <MemberSignature Language="F#" Value="member this.GetAllLifetimeStatistics : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.JobStatistics" Usage="jobOperations.GetAllLifetimeStatistics additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-260">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-260">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-261">ジョブの現在のアカウント内のすべての有効期間の概要統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="d3988-261">Gets lifetime summary statistics for all of the jobs in the current account.</span></span>  
            <span data-ttu-id="d3988-262">統計情報は、存在していたアカウントを作成してから、アカウントの最後の更新時刻、統計のすべてのジョブで集計されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-262">Statistics are aggregated across all jobs that have ever existed in the account, from account creation to the last update time of the statistics.</span></span> 
            </summary>
        <returns><span data-ttu-id="d3988-263">集計されたジョブの統計。</span><span class="sxs-lookup"><span data-stu-id="d3988-263">The aggregated job statistics.</span></span></returns>
        <remarks><span data-ttu-id="d3988-264">これは、ブロッキング操作です。非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-264">This is a blocking operation; for a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatisticsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.JobStatistics&gt; GetAllLifetimeStatisticsAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.JobStatistics&gt; GetAllLifetimeStatisticsAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetAllLifetimeStatisticsAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.JobStatistics&gt;" Usage="jobOperations.GetAllLifetimeStatisticsAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;GetAllLifetimeStatisticsAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.JobStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-265">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-265">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d3988-266">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="d3988-266">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-267">ジョブの現在のアカウント内のすべての有効期間の概要統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="d3988-267">Gets lifetime summary statistics for all of the jobs in the current account.</span></span>  
            <span data-ttu-id="d3988-268">統計情報は、存在していたアカウントを作成してから、アカウントの最後の更新時刻、統計のすべてのジョブで集計されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-268">Statistics are aggregated across all jobs that have ever existed in the account, from account creation to the last update time of the statistics.</span></span> 
            </summary>
        <returns><span data-ttu-id="d3988-269">集計されたジョブの統計。</span><span class="sxs-lookup"><span data-stu-id="d3988-269">The aggregated job statistics.</span></span></returns>
        <remarks><span data-ttu-id="d3988-270">統計情報の取得操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-270">The get statistics operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJob">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudJob GetJob (string jobId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudJob GetJob(string jobId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetJob(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetJob : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.CloudJob" Usage="jobOperations.GetJob (jobId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-271">取得するジョブの id です。</span><span class="sxs-lookup"><span data-stu-id="d3988-271">The id of the job to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="d3988-272">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="d3988-272">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-273">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-273">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-274">指定した <see cref="T:Microsoft.Azure.Batch.CloudJob" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="d3988-274">Gets the specified <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-275">A<see cref="T:Microsoft.Azure.Batch.CloudJob" />指定した Azure Batch のジョブに関する情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="d3988-275">A <see cref="T:Microsoft.Azure.Batch.CloudJob" /> containing information about the specified Azure Batch job.</span></span></returns>
        <remarks><span data-ttu-id="d3988-276">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="d3988-276">This is a blocking operation.</span></span> <span data-ttu-id="d3988-277">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.GetJobAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-277">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobOperations.GetJobAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudJob&gt; GetJobAsync (string jobId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.CloudJob&gt; GetJobAsync(string jobId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetJobAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetJobAsync : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudJob&gt;" Usage="jobOperations.GetJobAsync (jobId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;GetJobAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-278">取得するジョブの id です。</span><span class="sxs-lookup"><span data-stu-id="d3988-278">The id of the job to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="d3988-279">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="d3988-279">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-280">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-280">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d3988-281">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="d3988-281">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-282">指定した <see cref="T:Microsoft.Azure.Batch.CloudJob" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="d3988-282">Gets the specified <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-283">A<see cref="T:Microsoft.Azure.Batch.CloudJob" />指定した Azure Batch のジョブに関する情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="d3988-283">A <see cref="T:Microsoft.Azure.Batch.CloudJob" /> containing information about the specified Azure Batch job.</span></span></returns>
        <remarks><span data-ttu-id="d3988-284">Get job 操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-284">The get job operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobTaskCounts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskCounts GetJobTaskCounts (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.TaskCounts GetJobTaskCounts(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetJobTaskCounts(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetJobTaskCounts (jobId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As TaskCounts" />
      <MemberSignature Language="F#" Value="member this.GetJobTaskCounts : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.TaskCounts" Usage="jobOperations.GetJobTaskCounts (jobId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskCounts</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-285">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-285">The id of the job.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-286">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-286">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-287">指定されたジョブのタスクの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="d3988-287">Gets the task counts for the specified job.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-288">A<see cref="T:Microsoft.Azure.Batch.TaskCounts" />ジョブのカウントをタスクを含むオブジェクトします。</span><span class="sxs-lookup"><span data-stu-id="d3988-288">A <see cref="T:Microsoft.Azure.Batch.TaskCounts" /> object containing the task counts for the job.</span></span></returns>
        <remarks><span data-ttu-id="d3988-289">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="d3988-289">This is a blocking operation.</span></span> <span data-ttu-id="d3988-290">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.GetJobTaskCountsAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-290">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobOperations.GetJobTaskCountsAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobTaskCountsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt; GetJobTaskCountsAsync (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.TaskCounts&gt; GetJobTaskCountsAsync(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetJobTaskCountsAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetJobTaskCountsAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt;" Usage="jobOperations.GetJobTaskCountsAsync (jobId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;GetJobTaskCountsAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-291">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-291">The id of the job.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-292">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-292">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d3988-293">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="d3988-293">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-294">指定されたジョブのタスクの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="d3988-294">Gets the task counts for the specified job.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-295">A<see cref="T:Microsoft.Azure.Batch.TaskCounts" />ジョブのカウントをタスクを含むオブジェクトします。</span><span class="sxs-lookup"><span data-stu-id="d3988-295">A <see cref="T:Microsoft.Azure.Batch.TaskCounts" /> object containing the task counts for the job.</span></span></returns>
        <remarks><span data-ttu-id="d3988-296">ジョブのタスクの取得は、非同期的に操作の実行をカウントします。</span><span class="sxs-lookup"><span data-stu-id="d3988-296">The get job task counts operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.NodeFile GetNodeFile (string jobId, string taskId, string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.NodeFile GetNodeFile(string jobId, string taskId, string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetNodeFile(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeFile (jobId As String, taskId As String, filePath As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As NodeFile" />
      <MemberSignature Language="F#" Value="member this.GetNodeFile : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.NodeFile" Usage="jobOperations.GetNodeFile (jobId, taskId, filePath, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.NodeFile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-297">タスクを含むジョブの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-297">The id of the job containing the task.</span></span></param>
        <param name="taskId"><span data-ttu-id="d3988-298">タスクの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-298">The id of the task.</span></span></param>
        <param name="filePath"><span data-ttu-id="d3988-299">取得するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="d3988-299">The path of the file to retrieve.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-300">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-300">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-301">指定された取得<see cref="T:Microsoft.Azure.Batch.NodeFile" />コンピューティング ノードで、指定したタスクのディレクトリからです。</span><span class="sxs-lookup"><span data-stu-id="d3988-301">Gets the specified <see cref="T:Microsoft.Azure.Batch.NodeFile" /> from the specified task's directory on its compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-302">A<see cref="T:Microsoft.Azure.Batch.NodeFile" />を表す、指定したファイルです。</span><span class="sxs-lookup"><span data-stu-id="d3988-302">A <see cref="T:Microsoft.Azure.Batch.NodeFile" /> representing the specified file.</span></span></returns>
        <remarks><span data-ttu-id="d3988-303">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="d3988-303">This is a blocking operation.</span></span>  <span data-ttu-id="d3988-304">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-304">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync (string jobId, string taskId, string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync(string jobId, string taskId, string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeFileAsync : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="jobOperations.GetNodeFileAsync (jobId, taskId, filePath, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-305">タスクを含むジョブの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-305">The id of the job containing the task.</span></span></param>
        <param name="taskId"><span data-ttu-id="d3988-306">タスクの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-306">The id of the task.</span></span></param>
        <param name="filePath"><span data-ttu-id="d3988-307">取得するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="d3988-307">The path of the file to retrieve.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-308">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-308">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d3988-309">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="d3988-309">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-310">指定された取得<see cref="T:Microsoft.Azure.Batch.NodeFile" />コンピューティング ノードで、指定したタスクのディレクトリからです。</span><span class="sxs-lookup"><span data-stu-id="d3988-310">Gets the specified <see cref="T:Microsoft.Azure.Batch.NodeFile" /> from the specified task's directory on its compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-311">A<see cref="T:Microsoft.Azure.Batch.NodeFile" />を表す、指定したファイルです。</span><span class="sxs-lookup"><span data-stu-id="d3988-311">A <see cref="T:Microsoft.Azure.Batch.NodeFile" /> representing the specified file.</span></span></returns>
        <remarks><span data-ttu-id="d3988-312">ファイルの取得操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-312">The get file operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudTask GetTask (string jobId, string taskId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudTask GetTask(string jobId, string taskId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetTask(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetTask : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.CloudTask" Usage="jobOperations.GetTask (jobId, taskId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudTask</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-313">タスクを取得するジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-313">The id of the job from which to get the task.</span></span></param>
        <param name="taskId"><span data-ttu-id="d3988-314">取得するためのタスクの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-314">The id of the task to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="d3988-315">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="d3988-315">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-316">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-316">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-317">指定した <see cref="T:Microsoft.Azure.Batch.CloudTask" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="d3988-317">Gets the specified <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-318">A<see cref="T:Microsoft.Azure.Batch.CloudTask" />指定した Azure Batch のタスクに関する情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="d3988-318">A <see cref="T:Microsoft.Azure.Batch.CloudTask" /> containing information about the specified Azure Batch task.</span></span></returns>
        <remarks><span data-ttu-id="d3988-319">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="d3988-319">This is a blocking operation.</span></span> <span data-ttu-id="d3988-320">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.GetTaskAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-320">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobOperations.GetTaskAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt; GetTaskAsync (string jobId, string taskId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; GetTaskAsync(string jobId, string taskId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetTaskAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTaskAsync : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt;" Usage="jobOperations.GetTaskAsync (jobId, taskId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-321">タスクを取得するジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-321">The id of the job from which to get the task.</span></span></param>
        <param name="taskId"><span data-ttu-id="d3988-322">取得するためのタスクの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-322">The id of the task to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="d3988-323">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="d3988-323">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-324">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-324">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d3988-325">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="d3988-325">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-326">指定した <see cref="T:Microsoft.Azure.Batch.CloudTask" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="d3988-326">Gets the specified <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-327">A<see cref="T:Microsoft.Azure.Batch.CloudTask" />指定した Azure Batch のタスクに関する情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="d3988-327">A <see cref="T:Microsoft.Azure.Batch.CloudTask" /> containing information about the specified Azure Batch task.</span></span></returns>
        <remarks><span data-ttu-id="d3988-328">タスクの取得操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-328">The get task operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobPreparationAndReleaseTaskStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation&gt; ListJobPreparationAndReleaseTaskStatus (string jobId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation&gt; ListJobPreparationAndReleaseTaskStatus(string jobId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ListJobPreparationAndReleaseTaskStatus(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListJobPreparationAndReleaseTaskStatus : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation&gt;" Usage="jobOperations.ListJobPreparationAndReleaseTaskStatus (jobId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-329">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-329">The id of the job.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="d3988-330">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="d3988-330">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-331">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-331">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-332">状態を列挙します<see cref="P:Microsoft.Azure.Batch.CloudJob.JobPreparationTask" />と<see cref="P:Microsoft.Azure.Batch.CloudJob.JobReleaseTask" />指定されたジョブのタスクです。</span><span class="sxs-lookup"><span data-stu-id="d3988-332">Enumerates the status of <see cref="P:Microsoft.Azure.Batch.CloudJob.JobPreparationTask" /> and <see cref="P:Microsoft.Azure.Batch.CloudJob.JobReleaseTask" /> tasks for the specified job.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-333"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を非同期的または同期的にステータスの列挙を使用できます。</span><span class="sxs-lookup"><span data-stu-id="d3988-333">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate statuses asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="d3988-334">このメソッドがすぐに戻るこれらの状態は、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-334">This method returns immediately; the statuses are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="d3988-335">検索は非アトミックなです。状態は、コレクションの列挙中にページで取得されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-335">Retrieval is non-atomic; statuses are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt; ListJobs (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudJob&gt; ListJobs(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ListJobs(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListJobs : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt;" Usage="jobOperations.ListJobs (detailLevel, additionalBehaviors)" />
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
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="d3988-336">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="d3988-336">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-337">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-337">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-338">列挙、<see cref="T:Microsoft.Azure.Batch.CloudJob">ジョブ</see>Batch アカウントにします。</span><span class="sxs-lookup"><span data-stu-id="d3988-338">Enumerates the <see cref="T:Microsoft.Azure.Batch.CloudJob">jobs</see> in the Batch account.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-339"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を非同期的または同期的に、ジョブを列挙を使用できます。</span><span class="sxs-lookup"><span data-stu-id="d3988-339">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate jobs asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="d3988-340">このメソッドがすぐに戻るジョブは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-340">This method returns immediately; the jobs are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="d3988-341">検索は非アトミックなです。ジョブは、コレクションの列挙中にページで取得されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-341">Retrieval is non-atomic; jobs are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeFiles">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles (string jobId, string taskId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles(string jobId, string taskId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ListNodeFiles(System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListNodeFiles : string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="jobOperations.ListNodeFiles (jobId, taskId, recursive, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-342">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-342">The id of the job.</span></span></param>
        <param name="taskId"><span data-ttu-id="d3988-343">タスクの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-343">The id of the task.</span></span></param>
        <param name="recursive"><span data-ttu-id="d3988-344">True の場合は、タスクのすべてのファイルの再帰的な一覧を実行します。</span><span class="sxs-lookup"><span data-stu-id="d3988-344">If true, performs a recursive list of all files of the task.</span></span> <span data-ttu-id="d3988-345">False の場合は、タスクのルート ディレクトリにファイルのみを返します。</span><span class="sxs-lookup"><span data-stu-id="d3988-345">If false, returns only the files in the root task directory.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="d3988-346">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="d3988-346">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-347">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-347">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-348">列挙、 <see cref="T:Microsoft.Azure.Batch.NodeFile">NodeFiles</see>コンピューティング ノードで、指定したタスクのディレクトリにします。</span><span class="sxs-lookup"><span data-stu-id="d3988-348">Enumerates the <see cref="T:Microsoft.Azure.Batch.NodeFile">NodeFiles</see> in the specified task's directory on its compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-349"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />ファイルを列挙する非同期的または同期的に使用できます。</span><span class="sxs-lookup"><span data-stu-id="d3988-349">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate files asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="d3988-350">このメソッドがすぐに戻るファイル データは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-350">This method returns immediately; the file data is retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="d3988-351">検索は非アトミックなです。ファイル データは、コレクションの列挙中にページで取得されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-351">Retrieval is non-atomic; file data is retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSubtasks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.SubtaskInformation&gt; ListSubtasks (string jobId, string taskId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.SubtaskInformation&gt; ListSubtasks(string jobId, string taskId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ListSubtasks(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListSubtasks : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.SubtaskInformation&gt;" Usage="jobOperations.ListSubtasks (jobId, taskId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.SubtaskInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-352">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-352">The id of the job.</span></span></param>
        <param name="taskId"><span data-ttu-id="d3988-353">取得するためのタスクの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-353">The id of the task to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="d3988-354">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="d3988-354">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-355">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-355">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-356">列挙、<see cref="T:Microsoft.Azure.Batch.SubtaskInformation">サブタスクについて</see>指定したタスク。</span><span class="sxs-lookup"><span data-stu-id="d3988-356">Enumerates the <see cref="T:Microsoft.Azure.Batch.SubtaskInformation">subtask information</see> of the specified task.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-357"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />サブタスクを非同期的または同期的に列挙を使用できます。</span><span class="sxs-lookup"><span data-stu-id="d3988-357">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate subtasks asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="d3988-358">このメソッドがすぐに戻るタスクは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-358">This method returns immediately; the tasks are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="d3988-359">検索は非アトミックなです。タスクは、コレクションの列挙中にページで取得されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-359">Retrieval is non-atomic; tasks are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTasks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; ListTasks (string jobId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; ListTasks(string jobId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ListTasks(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListTasks : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" Usage="jobOperations.ListTasks (jobId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-360">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-360">The id of the job.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="d3988-361">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="d3988-361">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-362">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-362">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-363">列挙、<see cref="T:Microsoft.Azure.Batch.CloudTask">タスク</see>の指定されたジョブです。</span><span class="sxs-lookup"><span data-stu-id="d3988-363">Enumerates the <see cref="T:Microsoft.Azure.Batch.CloudTask">tasks</see> of the specified job.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-364"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を使用して非同期的または同期的にタスクの列挙をことができます。</span><span class="sxs-lookup"><span data-stu-id="d3988-364">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate tasks asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="d3988-365">このメソッドがすぐに戻るタスクは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-365">This method returns immediately; the tasks are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="d3988-366">検索は非アトミックなです。タスクは、コレクションの列挙中にページで取得されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-366">Retrieval is non-atomic; tasks are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReactivateTask">
      <MemberSignature Language="C#" Value="public void ReactivateTask (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ReactivateTask(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ReactivateTask(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReactivateTask (jobId As String, taskId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.ReactivateTask : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.ReactivateTask (jobId, taskId, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-367">タスクを含むジョブの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-367">The id of the job containing the task.</span></span></param>
        <param name="taskId"><span data-ttu-id="d3988-368">タスクの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-368">The id of the task.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-369">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-369">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-370">許可することで、再試行カウントが使い果たされた場合でも、もう一度実行するタスクを再アクティブ化します。</span><span class="sxs-lookup"><span data-stu-id="d3988-370">Reactivates a task, allowing it to run again even if its retry count has been exhausted.</span></span>
            </summary>
        <remarks>
          <para>
            <span data-ttu-id="d3988-371">再アクティブ化では、タスクがその最大再試行回数まで再試行の対象となります。</span><span class="sxs-lookup"><span data-stu-id="d3988-371">Reactivation makes a task eligible to be retried again up to its maximum retry count.</span></span>
            </para>
          <para>
            <span data-ttu-id="d3988-372">この操作は完了していない、または正常に (終了コード 0) の以前に完了したタスクを失敗します。</span><span class="sxs-lookup"><span data-stu-id="d3988-372">This operation will fail for tasks that are not completed or that previously completed successfully (with an exit code of 0).</span></span>
            </para>
          <para>
            <span data-ttu-id="d3988-373">さらは失敗しますが、ジョブの場合、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" />または<see cref="F:Microsoft.Azure.Batch.Common.JobState.Terminating" />または<see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="d3988-373">Additionally, this will fail if the job is in the <see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" /> or <see cref="F:Microsoft.Azure.Batch.Common.JobState.Terminating" /> or <see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" /> state.</span></span>
            <span data-ttu-id="d3988-374">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="d3988-374">This is a blocking operation.</span></span> <span data-ttu-id="d3988-375">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.ReactivateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-375">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobOperations.ReactivateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReactivateTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReactivateTaskAsync (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ReactivateTaskAsync(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ReactivateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ReactivateTaskAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.ReactivateTaskAsync (jobId, taskId, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-376">タスクを含むジョブの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-376">The id of the job containing the task.</span></span></param>
        <param name="taskId"><span data-ttu-id="d3988-377">タスクの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-377">The id of the task.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-378">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-378">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d3988-379">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="d3988-379">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-380">許可することで、再試行カウントが使い果たされた場合でも、もう一度実行するタスクを再アクティブ化します。</span><span class="sxs-lookup"><span data-stu-id="d3988-380">Reactivates a task, allowing it to run again even if its retry count has been exhausted.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-381">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="d3988-381">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="d3988-382">再アクティブ化では、タスクがその最大再試行回数まで再試行の対象となります。</span><span class="sxs-lookup"><span data-stu-id="d3988-382">Reactivation makes a task eligible to be retried again up to its maximum retry count.</span></span>
            </para>
          <para>
            <span data-ttu-id="d3988-383">さらは失敗しますが、ジョブの場合、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" />または<see cref="F:Microsoft.Azure.Batch.Common.JobState.Terminating" />または<see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="d3988-383">Additionally, this will fail if the job is in the <see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" /> or <see cref="F:Microsoft.Azure.Batch.Common.JobState.Terminating" /> or <see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" /> state.</span></span>
            <span data-ttu-id="d3988-384">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="d3988-384">This is a blocking operation.</span></span> <span data-ttu-id="d3988-385">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.ReactivateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-385">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobOperations.ReactivateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span>
            </para>
          <para>
            <span data-ttu-id="d3988-386">再アクティブ化操作が非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-386">The reactivate operation runs asynchronously.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateJob">
      <MemberSignature Language="C#" Value="public void TerminateJob (string jobId, string terminateReason = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TerminateJob(string jobId, string terminateReason, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.TerminateJob(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub TerminateJob (jobId As String, Optional terminateReason As String = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.TerminateJob : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.TerminateJob (jobId, terminateReason, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-387">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-387">The id of the job.</span></span></param>
        <param name="terminateReason"><span data-ttu-id="d3988-388">ジョブのとして表示するテキスト<see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-388">The text you want to appear as the job's <see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-389">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-389">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-390">完了としてマークして、指定されたジョブを終了します。</span><span class="sxs-lookup"><span data-stu-id="d3988-390">Terminates the specified job, marking it as completed.</span></span>
            </summary>
        <remarks><span data-ttu-id="d3988-391">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="d3988-391">This is a blocking operation.</span></span> <span data-ttu-id="d3988-392">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.TerminateJobAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-392">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobOperations.TerminateJobAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task TerminateJobAsync (string jobId, string terminateReason = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task TerminateJobAsync(string jobId, string terminateReason, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.TerminateJobAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.TerminateJobAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.TerminateJobAsync (jobId, terminateReason, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;TerminateJobAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-393">ジョブの id。</span><span class="sxs-lookup"><span data-stu-id="d3988-393">The id of the job.</span></span></param>
        <param name="terminateReason"><span data-ttu-id="d3988-394">ジョブのとして表示するテキスト<see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-394">The text you want to appear as the job's <see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-395">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-395">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d3988-396">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="d3988-396">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-397">完了としてマークして、指定されたジョブを終了します。</span><span class="sxs-lookup"><span data-stu-id="d3988-397">Terminates the specified job, marking it as completed.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-398">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d3988-398">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="d3988-399">終了操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-399">The terminate operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateTask">
      <MemberSignature Language="C#" Value="public void TerminateTask (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TerminateTask(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.TerminateTask(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub TerminateTask (jobId As String, taskId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.TerminateTask : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.TerminateTask (jobId, taskId, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-400">タスクを含むジョブの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-400">The id of the job containing the task.</span></span></param>
        <param name="taskId"><span data-ttu-id="d3988-401">タスクの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-401">The id of the task.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-402">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-402">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-403">指定したタスクを終了します。</span><span class="sxs-lookup"><span data-stu-id="d3988-403">Terminates the specified task.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-404">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="d3988-404">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="d3988-405">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="d3988-405">This is a blocking operation.</span></span>  <span data-ttu-id="d3988-406">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.TerminateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-406">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobOperations.TerminateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task TerminateTaskAsync (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task TerminateTaskAsync(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.TerminateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.TerminateTaskAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.TerminateTaskAsync (jobId, taskId, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="d3988-407">タスクを含むジョブの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-407">The id of the job containing the task.</span></span></param>
        <param name="taskId"><span data-ttu-id="d3988-408">タスクの ID です。</span><span class="sxs-lookup"><span data-stu-id="d3988-408">The id of the task.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="d3988-409">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="d3988-409">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d3988-410">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="d3988-410">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d3988-411">指定したタスクを終了します。</span><span class="sxs-lookup"><span data-stu-id="d3988-411">Terminates the specified task.</span></span>
            </summary>
        <returns><span data-ttu-id="d3988-412">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="d3988-412">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="d3988-413">終了操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="d3988-413">The terminate operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>