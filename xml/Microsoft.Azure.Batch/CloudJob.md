<Type Name="CloudJob" FullName="Microsoft.Azure.Batch.CloudJob">
  <TypeSignature Language="C#" Value="public class CloudJob : Microsoft.Azure.Batch.IInheritedBehaviors, Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudJob extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors, class Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.CloudJob" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudJob&#xA;Implements IInheritedBehaviors, IRefreshable" />
  <TypeSignature Language="F#" Value="type CloudJob = class&#xA;    interface IRefreshable&#xA;    interface ITransportObjectProvider&lt;JobAddParameter&gt;&#xA;    interface IInheritedBehaviors&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IRefreshable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="b875e-101">Azure Batch のジョブの場合は。</span><span class="sxs-lookup"><span data-stu-id="b875e-101">An Azure Batch job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddTask">
      <MemberSignature Language="C#" Value="public System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt; AddTask (Microsoft.Azure.Batch.CloudTask taskToAdd, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt; AddTask(class Microsoft.Azure.Batch.CloudTask taskToAdd, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.AddTask(Microsoft.Azure.Batch.CloudTask,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddTask (taskToAdd As CloudTask, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As ConcurrentDictionary(Of Type, IFileStagingArtifact)" />
      <MemberSignature Language="F#" Value="member this.AddTask : Microsoft.Azure.Batch.CloudTask * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;" Usage="cloudJob.AddTask (taskToAdd, additionalBehaviors)" />
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
        <Parameter Name="taskToAdd" Type="Microsoft.Azure.Batch.CloudTask" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="taskToAdd"><span data-ttu-id="b875e-102">追加する <see cref="T:Microsoft.Azure.Batch.CloudTask" />。</span><span class="sxs-lookup"><span data-stu-id="b875e-102">The <see cref="T:Microsoft.Azure.Batch.CloudTask" /> to add.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-103">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-103">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-104">これを 1 つのタスクを追加<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-104">Adds a single task to this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>  <span data-ttu-id="b875e-105">複数のタスクを追加する<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>です。</span><span class="sxs-lookup"><span data-stu-id="b875e-105">To add multiple tasks, use <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>.</span></span>
            </summary>
        <returns><span data-ttu-id="b875e-106">ステージング処理ファイルに関する情報のコレクション (を参照してください<see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />)。</span><span class="sxs-lookup"><span data-stu-id="b875e-106">A collection of information about the file staging process (see <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).</span></span>
            <span data-ttu-id="b875e-107">詳細については、「<see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="b875e-107">For more information see <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="b875e-108">このメソッドを呼び出すたびには、バッチ サービスへの要求が発生します。</span><span class="sxs-lookup"><span data-stu-id="b875e-108">Each call to this method incurs a request to the Batch service.</span></span> <span data-ttu-id="b875e-109">したがって、このメソッドを使用して、複数のタスクが一括を使用するよりも効率の低いを追加するメソッドを追加し、HTTP 接続の制限が発生することができます。</span><span class="sxs-lookup"><span data-stu-id="b875e-109">Therefore, using this method to add multiple tasks is less efficient than using a bulk add method, and can incur HTTP connection restrictions.</span></span>
            <span data-ttu-id="b875e-110">並列でこれらの操作の多くを実行して、クライアント側のタイムアウトが表示される場合 (、 <see cref="T:System.Threading.Tasks.TaskCanceledException" />)、http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx を参照してくださいか使用してください<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="b875e-110">If you are performing many of these operations in parallel and are seeing client side timeouts (a <see cref="T:System.Threading.Tasks.TaskCanceledException" />), please see http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx or use <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span>
            </para>
          <para><span data-ttu-id="b875e-111">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="b875e-111">This is a blocking operation.</span></span> <span data-ttu-id="b875e-112">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-112">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddTask">
      <MemberSignature Language="C#" Value="public void AddTask (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions = null, System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts = null, Nullable&lt;TimeSpan&gt; timeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddTask(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, class Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions, class System.Collections.Concurrent.ConcurrentBag`1&lt;class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.AddTask(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddTask (tasksToAdd As IEnumerable(Of CloudTask), Optional parallelOptions As BatchClientParallelOptions = null, Optional fileStagingArtifacts As ConcurrentBag(Of ConcurrentDictionary(Of Type, IFileStagingArtifact)) = null, Optional timeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.AddTask : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.BatchClientParallelOptions * System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.AddTask (tasksToAdd, parallelOptions, fileStagingArtifacts, timeout, additionalBehaviors)" />
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
        <Parameter Name="tasksToAdd" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="parallelOptions" Type="Microsoft.Azure.Batch.BatchClientParallelOptions" />
        <Parameter Name="fileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt;" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="tasksToAdd"><span data-ttu-id="b875e-113"><see cref="T:Microsoft.Azure.Batch.CloudTask" />S を追加します。</span><span class="sxs-lookup"><span data-stu-id="b875e-113">The <see cref="T:Microsoft.Azure.Batch.CloudTask" />s to add.</span></span></param>
        <param name="parallelOptions">
            <span data-ttu-id="b875e-114">バッチ サービスに発行された同時の並列 AddTaskCollection 要求の数を制御します。</span><span class="sxs-lookup"><span data-stu-id="b875e-114">Controls the number of simultaneous parallel AddTaskCollection requests issued to the Batch service.</span></span>  <span data-ttu-id="b875e-115">各 AddTaskCollection 要求が最大で含まれている<see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />その中のタスクです。</span><span class="sxs-lookup"><span data-stu-id="b875e-115">Each AddTaskCollection request contains at most <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" /> tasks in it.</span></span>
            <span data-ttu-id="b875e-116">また、操作のキャンセル トークンを制御します。</span><span class="sxs-lookup"><span data-stu-id="b875e-116">Also controls the cancellation token for the operation.</span></span>
            <span data-ttu-id="b875e-117">既定値が使用される省略すると、(を参照してください<see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />)。</span><span class="sxs-lookup"><span data-stu-id="b875e-117">If omitted, the default is used (see <see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />.)</span></span>
            </param>
        <param name="fileStagingArtifacts"><span data-ttu-id="b875e-118">ステージング処理ファイルに関する情報を受信する、省略可能なコレクション (を参照してください<see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />)。</span><span class="sxs-lookup"><span data-stu-id="b875e-118">An optional collection to receive information about the file staging process (see <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).</span></span>
            <span data-ttu-id="b875e-119">エントリを追加、 <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" /> Batch service に送信するグループ化されたタスクのセットごとにします。</span><span class="sxs-lookup"><span data-stu-id="b875e-119">An entry is added to the <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" /> for each set of tasks grouped for submission to the Batch service.</span></span>
            <span data-ttu-id="b875e-120">単一タスクとは異なりを追加、ファイルのステージング処理をカスタマイズする、このパラメーターを使用することはできません。</span><span class="sxs-lookup"><span data-stu-id="b875e-120">Unlike single-task adds, you cannot use this parameter to customize the file staging process.</span></span>
            <span data-ttu-id="b875e-121">各エントリの形式に関する詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-121">For more information about the format of each entry, see <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="b875e-122">操作がタイムアウトするまでの時間。</span><span class="sxs-lookup"><span data-stu-id="b875e-122">The amount of time after which the operation times out.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-123">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-123">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-124">ジョブにタスクを追加します。</span><span class="sxs-lookup"><span data-stu-id="b875e-124">Adds tasks to a job.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="b875e-125">これは、ブロッキング操作です。非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-125">This is a blocking operation; for a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></para>
          <para><span data-ttu-id="b875e-126">このメソッドは、アトミックです。つまり、メソッドがタスクの追加を開始し、失敗する可能性です。</span><span class="sxs-lookup"><span data-stu-id="b875e-126">This method is not atomic; that is, it is possible for the method to start adding tasks and then fail.</span></span> <span data-ttu-id="b875e-127">追加するタスクのコレクションに分割されるサイズのチャンク多くて<see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />、各チャンクに対して AddTaskCollection 要求が実行されたとします。</span><span class="sxs-lookup"><span data-stu-id="b875e-127">The collection of tasks to add is broken down into chunks of size at most <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />, and an AddTaskCollection request is issued for each chunk.</span></span>  <span data-ttu-id="b875e-128">に従って並列で要求を発行することがあります、<paramref name="parallelOptions" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-128">Requests may be issued in parallel according to the <paramref name="parallelOptions" />.</span></span></para>
          <para><span data-ttu-id="b875e-129">Batch service への多数の同時要求の発行と、HTTP 接続の制限が発生することができます。</span><span class="sxs-lookup"><span data-stu-id="b875e-129">Issuing a large number of simultaneous requests to the Batch service can incur HTTP connection restrictions.</span></span>
            <span data-ttu-id="b875e-130">これらの操作の多くを並列で実行中 (または、parallelOptions で大きな MaxDegreeOfParallelism を指定した) 場合、クライアント側のタイムアウトが表示される (、 <see cref="T:System.Threading.Tasks.TaskCanceledException" />)、http://msdn.microsoft.com/en-us/library/ を参照してくださいsystem.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx です。</span><span class="sxs-lookup"><span data-stu-id="b875e-130">If you are performing many of these operations in parallel (or have specified a large MaxDegreeOfParallelism in the parallelOptions) and are seeing client side timeouts (a <see cref="T:System.Threading.Tasks.TaskCanceledException" />), please see http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx .</span></span></para>
          <para><span data-ttu-id="b875e-131">エラーが発生した場合、操作の進行状況は、によって決まります<see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" />動作します。</span><span class="sxs-lookup"><span data-stu-id="b875e-131">The progress of the operation in the face of errors is determined by <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" /> behavior.</span></span>
            <span data-ttu-id="b875e-132">通常、クライアントは、通常の状況で動作する、既定値を使用してバッチとして、この動作を指定する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="b875e-132">You do not normally need to specify this behavior, as the Batch client uses a default which works in normal circumstances.</span></span>
            <span data-ttu-id="b875e-133">この動作をカスタマイズする場合、AddTaskCollectionResultHandler 内の指定、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />または<paramref name="additionalBehaviors" />コレクション。</span><span class="sxs-lookup"><span data-stu-id="b875e-133">If you do want to customize this behavior, specify an AddTaskCollectionResultHandler in the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" /> or <paramref name="additionalBehaviors" /> collections.</span></span></para>
        </remarks>
        <exception cref="T:Microsoft.Azure.Batch.ParallelOperationsException"><span data-ttu-id="b875e-134">Batch service への 1 つまたは複数の要求が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b875e-134">Thrown if one or more requests to the Batch service fail.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AddTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddTaskAsync (Microsoft.Azure.Batch.CloudTask taskToAdd, System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt; allFileStagingArtifacts = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddTaskAsync(class Microsoft.Azure.Batch.CloudTask taskToAdd, class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt; allFileStagingArtifacts, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.AddTaskAsync : Microsoft.Azure.Batch.CloudTask * System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.AddTaskAsync (taskToAdd, allFileStagingArtifacts, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;AddTaskAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskToAdd" Type="Microsoft.Azure.Batch.CloudTask" />
        <Parameter Name="allFileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="taskToAdd"><span data-ttu-id="b875e-135">追加する <see cref="T:Microsoft.Azure.Batch.CloudTask" />。</span><span class="sxs-lookup"><span data-stu-id="b875e-135">The <see cref="T:Microsoft.Azure.Batch.CloudTask" /> to add.</span></span></param>
        <param name="allFileStagingArtifacts"><span data-ttu-id="b875e-136">オプションのコレクションをカスタマイズし、ステージング処理ファイルに関する情報を受け取ります (を参照してください<see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />)。</span><span class="sxs-lookup"><span data-stu-id="b875e-136">An optional collection to customize and receive information about the file staging process (see <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).</span></span>
            <span data-ttu-id="b875e-137">詳細については、「<see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="b875e-137">For more information see <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-138">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-138">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b875e-139">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="b875e-139">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-140">これを 1 つのタスクを追加<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-140">Adds a single task to this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>  <span data-ttu-id="b875e-141">複数のタスクを追加する<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>です。</span><span class="sxs-lookup"><span data-stu-id="b875e-141">To add multiple tasks, use <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>.</span></span>
            </summary>
        <returns><span data-ttu-id="b875e-142">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="b875e-142">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="b875e-143">このメソッドを呼び出すたびには、バッチ サービスへの要求が発生します。</span><span class="sxs-lookup"><span data-stu-id="b875e-143">Each call to this method incurs a request to the Batch service.</span></span> <span data-ttu-id="b875e-144">したがって、このメソッドを使用して、複数のタスクが一括を使用するよりも効率の低いを追加するメソッドを追加し、HTTP 接続の制限が発生することができます。</span><span class="sxs-lookup"><span data-stu-id="b875e-144">Therefore, using this method to add multiple tasks is less efficient than using a bulk add method, and can incur HTTP connection restrictions.</span></span>
            <span data-ttu-id="b875e-145">並列でこれらの操作の多くを実行して、クライアント側のタイムアウトが表示される場合 (、 <see cref="T:System.Threading.Tasks.TaskCanceledException" />)、http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx を参照してくださいか使用してください<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="b875e-145">If you are performing many of these operations in parallel and are seeing client side timeouts (a <see cref="T:System.Threading.Tasks.TaskCanceledException" />), please see http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx or use <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span>
            </para>
          <para><span data-ttu-id="b875e-146">タスクの追加操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-146">The add task operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddTaskAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions = null, System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts = null, Nullable&lt;TimeSpan&gt; timeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddTaskAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, class Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions, class System.Collections.Concurrent.ConcurrentBag`1&lt;class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddTaskAsync (tasksToAdd As IEnumerable(Of CloudTask), Optional parallelOptions As BatchClientParallelOptions = null, Optional fileStagingArtifacts As ConcurrentBag(Of ConcurrentDictionary(Of Type, IFileStagingArtifact)) = null, Optional timeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As Task" />
      <MemberSignature Language="F#" Value="member this.AddTaskAsync : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.BatchClientParallelOptions * System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="cloudJob.AddTaskAsync (tasksToAdd, parallelOptions, fileStagingArtifacts, timeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;AddTaskAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasksToAdd" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="parallelOptions" Type="Microsoft.Azure.Batch.BatchClientParallelOptions" />
        <Parameter Name="fileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt;" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="tasksToAdd"><span data-ttu-id="b875e-147"><see cref="T:Microsoft.Azure.Batch.CloudTask" />S を追加します。</span><span class="sxs-lookup"><span data-stu-id="b875e-147">The <see cref="T:Microsoft.Azure.Batch.CloudTask" />s to add.</span></span></param>
        <param name="parallelOptions">
            <span data-ttu-id="b875e-148">バッチ サービスに発行された同時の並列 AddTaskCollection 要求の数を制御します。</span><span class="sxs-lookup"><span data-stu-id="b875e-148">Controls the number of simultaneous parallel AddTaskCollection requests issued to the Batch service.</span></span>  <span data-ttu-id="b875e-149">各 AddTaskCollection 要求が最大で含まれている<see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />その中のタスクです。</span><span class="sxs-lookup"><span data-stu-id="b875e-149">Each AddTaskCollection request contains at most <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" /> tasks in it.</span></span>
            <span data-ttu-id="b875e-150">また、操作のキャンセル トークンを制御します。</span><span class="sxs-lookup"><span data-stu-id="b875e-150">Also controls the cancellation token for the operation.</span></span>
            <span data-ttu-id="b875e-151">既定値が使用される省略すると、(を参照してください<see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />)。</span><span class="sxs-lookup"><span data-stu-id="b875e-151">If omitted, the default is used (see <see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />.)</span></span>
            </param>
        <param name="fileStagingArtifacts"><span data-ttu-id="b875e-152">ステージング処理ファイルに関する情報を受信する、省略可能なコレクション (を参照してください<see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />)。</span><span class="sxs-lookup"><span data-stu-id="b875e-152">An optional collection to receive information about the file staging process (see <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).</span></span>
            <span data-ttu-id="b875e-153">エントリを追加、 <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" /> Batch service に送信するグループ化されたタスクのセットごとにします。</span><span class="sxs-lookup"><span data-stu-id="b875e-153">An entry is added to the <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" /> for each set of tasks grouped for submission to the Batch service.</span></span>
            <span data-ttu-id="b875e-154">単一タスクとは異なりを追加、ファイルのステージング処理をカスタマイズする、このパラメーターを使用することはできません。</span><span class="sxs-lookup"><span data-stu-id="b875e-154">Unlike single-task adds, you cannot use this parameter to customize the file staging process.</span></span>
            <span data-ttu-id="b875e-155">各エントリの形式に関する詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-155">For more information about the format of each entry, see <see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="b875e-156">操作がタイムアウトするまでの時間。</span><span class="sxs-lookup"><span data-stu-id="b875e-156">The amount of time after which the operation times out.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-157">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-157">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-158">ジョブにタスクを追加します。</span><span class="sxs-lookup"><span data-stu-id="b875e-158">Adds tasks to a job.</span></span>
            </summary>
        <returns><span data-ttu-id="b875e-159">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b875e-159">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="b875e-160">タスクの追加操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-160">The add task operation runs asynchronously.</span></span></para>
          <para><span data-ttu-id="b875e-161">このメソッドは、アトミックです。つまり、メソッドがタスクの追加を開始し、失敗する可能性です。</span><span class="sxs-lookup"><span data-stu-id="b875e-161">This method is not atomic; that is, it is possible for the method to start adding tasks and then fail.</span></span> <span data-ttu-id="b875e-162">追加するタスクのコレクションに分割されるサイズのチャンク多くて<see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />、各チャンクに対して AddTaskCollection 要求が実行されたとします。</span><span class="sxs-lookup"><span data-stu-id="b875e-162">The collection of tasks to add is broken down into chunks of size at most <see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />, and an AddTaskCollection request is issued for each chunk.</span></span>  <span data-ttu-id="b875e-163">に従って並列で要求を発行することがあります、<paramref name="parallelOptions" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-163">Requests may be issued in parallel according to the <paramref name="parallelOptions" />.</span></span></para>
          <para><span data-ttu-id="b875e-164">Batch service への多数の同時要求の発行と、HTTP 接続の制限が発生することができます。</span><span class="sxs-lookup"><span data-stu-id="b875e-164">Issuing a large number of simultaneous requests to the Batch service can incur HTTP connection restrictions.</span></span>
            <span data-ttu-id="b875e-165">これらの操作の多くを並列で実行中 (または、parallelOptions で大きな MaxDegreeOfParallelism を指定した) 場合、クライアント側のタイムアウトが表示される (、 <see cref="T:System.Threading.Tasks.TaskCanceledException" />)、http://msdn.microsoft.com/en-us/library/ を参照してくださいsystem.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx です。</span><span class="sxs-lookup"><span data-stu-id="b875e-165">If you are performing many of these operations in parallel (or have specified a large MaxDegreeOfParallelism in the parallelOptions) and are seeing client side timeouts (a <see cref="T:System.Threading.Tasks.TaskCanceledException" />), please see http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx .</span></span></para>
          <para><span data-ttu-id="b875e-166">エラーが発生した場合、操作の進行状況は、によって決まります<see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" />動作します。</span><span class="sxs-lookup"><span data-stu-id="b875e-166">The progress of the operation in the face of errors is determined by <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" /> behavior.</span></span>
            <span data-ttu-id="b875e-167">通常、クライアントは、通常の状況で動作する、既定値を使用してバッチとして、この動作を指定する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="b875e-167">You do not normally need to specify this behavior, as the Batch client uses a default which works in normal circumstances.</span></span>
            <span data-ttu-id="b875e-168">この動作をカスタマイズする場合、AddTaskCollectionResultHandler 内の指定、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />または<paramref name="additionalBehaviors" />コレクション。</span><span class="sxs-lookup"><span data-stu-id="b875e-168">If you do want to customize this behavior, specify an AddTaskCollectionResultHandler in the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" /> or <paramref name="additionalBehaviors" /> collections.</span></span></para>
        </remarks>
        <exception cref="T:Microsoft.Azure.Batch.ParallelOperationsException"><span data-ttu-id="b875e-169">Batch service への 1 つまたは複数の要求が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b875e-169">Thrown if one or more requests to the Batch service fail.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="public void Commit (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Commit(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Commit (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Commit : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Commit additionalBehaviors" />
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
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-170">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-170">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-171">このコミット<see cref="T:Microsoft.Azure.Batch.CloudJob" />Azure Batch のサービスにします。</span><span class="sxs-lookup"><span data-stu-id="b875e-171">Commits this <see cref="T:Microsoft.Azure.Batch.CloudJob" /> to the Azure Batch service.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="b875e-172">場合、<see cref="T:Microsoft.Azure.Batch.CloudJob" />既に存在する、バッチ サービスでは、そのプロパティがこのプロパティで置き換えられます<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-172">If the <see cref="T:Microsoft.Azure.Batch.CloudJob" /> already exists on the Batch service, its properties are replaced by the properties of this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span></para>
          <para><span data-ttu-id="b875e-173">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="b875e-173">This is a blocking operation.</span></span> <span data-ttu-id="b875e-174">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-174">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.CommitAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;CommitAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-175">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-175">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b875e-176">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="b875e-176">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-177">このコミット<see cref="T:Microsoft.Azure.Batch.CloudJob" />Azure Batch のサービスにします。</span><span class="sxs-lookup"><span data-stu-id="b875e-177">Commits this <see cref="T:Microsoft.Azure.Batch.CloudJob" /> to the Azure Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="b875e-178">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="b875e-178">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="b875e-179">場合、<see cref="T:Microsoft.Azure.Batch.CloudJob" />既に存在する、バッチ サービスでは、そのプロパティがこのプロパティで置き換えられます<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-179">If the <see cref="T:Microsoft.Azure.Batch.CloudJob" /> already exists on the Batch service, its properties are replaced by the properties of this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span></para>
          <para><span data-ttu-id="b875e-180">コミット操作が非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-180">The commit operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitChanges">
      <MemberSignature Language="C#" Value="public void CommitChanges (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CommitChanges(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.CommitChanges(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CommitChanges (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.CommitChanges : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.CommitChanges additionalBehaviors" />
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
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-181">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-181">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-182">これをすべて保留中の変更をコミット<see cref="T:Microsoft.Azure.Batch.CloudJob" />Azure Batch のサービスにします。</span><span class="sxs-lookup"><span data-stu-id="b875e-182">Commits all pending changes to this <see cref="T:Microsoft.Azure.Batch.CloudJob" /> to the Azure Batch service.</span></span>
            </summary>
        <remarks>
          <para>
            <span data-ttu-id="b875e-183">既存の更新<see cref="T:Microsoft.Azure.Batch.CloudJob" />のこのプロパティをそのプロパティを置き換えることで、バッチ サービスで<see cref="T:Microsoft.Azure.Batch.CloudJob" />が変更されました。</span><span class="sxs-lookup"><span data-stu-id="b875e-183">Updates an existing <see cref="T:Microsoft.Azure.Batch.CloudJob" /> on the Batch service by replacing its properties with the properties of this <see cref="T:Microsoft.Azure.Batch.CloudJob" /> which have been changed.</span></span>
            <span data-ttu-id="b875e-184">変更されていないプロパティは無視されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-184">Unchanged properties are ignored.</span></span>
            <span data-ttu-id="b875e-185">このエンティティの前回のすべての変更は、バッチ サービスから取得されました (のいずれかによって<see cref="M:Microsoft.Azure.Batch.CloudJob.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />、 <see cref="M:Microsoft.Azure.Batch.JobOperations.GetJob(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />、または<see cref="M:Microsoft.Azure.Batch.JobOperations.ListJobs(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) 適用されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-185">All changes since the last time this entity was retrieved from the Batch service (either via <see cref="M:Microsoft.Azure.Batch.CloudJob.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, <see cref="M:Microsoft.Azure.Batch.JobOperations.GetJob(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, or <see cref="M:Microsoft.Azure.Batch.JobOperations.ListJobs(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) are applied.</span></span>
            <span data-ttu-id="b875e-186">Null が明示的に設定されているプロパティでは、バッチ サービスは、プロパティを null に設定する部分的な更新をサポートしていないため、例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="b875e-186">Properties which are explicitly set to null will cause an exception because the Batch service does not support partial updates which set a property to null.</span></span>
            <span data-ttu-id="b875e-187">プロパティを null に設定する必要がある場合を使用して<see cref="M:Microsoft.Azure.Batch.CloudJob.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-187">If you need to set a property to null, use <see cref="M:Microsoft.Azure.Batch.CloudJob.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span>
            </para>
          <para><span data-ttu-id="b875e-188">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="b875e-188">This is a blocking operation.</span></span> <span data-ttu-id="b875e-189">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.CommitChangesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-189">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.CommitChangesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitChangesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitChangesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitChangesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.CommitChangesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitChangesAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.CommitChangesAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;CommitChangesAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-190">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-190">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b875e-191">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="b875e-191">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-192">これをすべて保留中の変更をコミット<see cref="T:Microsoft.Azure.Batch.CloudJob" />Azure Batch のサービスにします。</span><span class="sxs-lookup"><span data-stu-id="b875e-192">Commits all pending changes to this <see cref="T:Microsoft.Azure.Batch.CloudJob" /> to the Azure Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="b875e-193">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="b875e-193">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="b875e-194">既存の更新<see cref="T:Microsoft.Azure.Batch.CloudJob" />のこのプロパティをそのプロパティを置き換えることで、バッチ サービスで<see cref="T:Microsoft.Azure.Batch.CloudJob" />が変更されました。</span><span class="sxs-lookup"><span data-stu-id="b875e-194">Updates an existing <see cref="T:Microsoft.Azure.Batch.CloudJob" /> on the Batch service by replacing its properties with the properties of this <see cref="T:Microsoft.Azure.Batch.CloudJob" /> which have been changed.</span></span>
            <span data-ttu-id="b875e-195">変更されていないプロパティは無視されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-195">Unchanged properties are ignored.</span></span>
            <span data-ttu-id="b875e-196">このエンティティの前回のすべての変更は、バッチ サービスから取得されました (のいずれかによって<see cref="M:Microsoft.Azure.Batch.CloudJob.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />、 <see cref="M:Microsoft.Azure.Batch.JobOperations.GetJob(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />、または<see cref="M:Microsoft.Azure.Batch.JobOperations.ListJobs(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) 適用されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-196">All changes since the last time this entity was retrieved from the Batch service (either via <see cref="M:Microsoft.Azure.Batch.CloudJob.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, <see cref="M:Microsoft.Azure.Batch.JobOperations.GetJob(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />, or <see cref="M:Microsoft.Azure.Batch.JobOperations.ListJobs(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) are applied.</span></span>
            <span data-ttu-id="b875e-197">Null が明示的に設定されているプロパティでは、バッチ サービスは、プロパティを null に設定する部分的な更新をサポートしていないため、例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="b875e-197">Properties which are explicitly set to null will cause an exception because the Batch service does not support partial updates which set a property to null.</span></span>
            <span data-ttu-id="b875e-198">プロパティを null に設定する必要がある場合を使用して<see cref="M:Microsoft.Azure.Batch.CloudJob.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-198">If you need to set a property to null, use <see cref="M:Microsoft.Azure.Batch.CloudJob.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span>
            </para>
          <para><span data-ttu-id="b875e-199">この操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-199">This operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonEnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt; CommonEnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.EnvironmentSetting&gt; CommonEnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.CommonEnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonEnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.CommonEnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.CommonEnvironmentSettings" />
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
            <span data-ttu-id="b875e-200">取得または一般的な環境変数設定の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="b875e-200">Gets or sets a list of common environment variable settings.</span></span> <span data-ttu-id="b875e-201">これらの環境変数がすべてのタスクの設定は<see cref="T:Microsoft.Azure.Batch.CloudJob" />(ジョブ マネージャー、ジョブの準備およびジョブのリリース タスクを含む)。</span><span class="sxs-lookup"><span data-stu-id="b875e-201">These environment variables are set for all tasks in this <see cref="T:Microsoft.Azure.Batch.CloudJob" /> (including the Job Manager, Job Preparation and Job Release tasks).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.JobConstraints with get, set" Usage="Microsoft.Azure.Batch.CloudJob.Constraints" />
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
            <span data-ttu-id="b875e-202">取得またはジョブの実行の制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="b875e-202">Gets or sets the execution constraints for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudJob.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b875e-203">ジョブの作成時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="b875e-203">Gets the creation time of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />
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
            <span data-ttu-id="b875e-204">取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-204">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="b875e-205">これらの動作は、子オブジェクトによって継承されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-205">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="b875e-206">変更は、コレクションの順序で適用されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-206">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="b875e-207">最後には、wins を記述します。</span><span class="sxs-lookup"><span data-stu-id="b875e-207">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Delete(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Delete : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Delete additionalBehaviors" />
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
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-208">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-208">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-209">この <see cref="T:Microsoft.Azure.Batch.CloudJob" /> を削除します。</span><span class="sxs-lookup"><span data-stu-id="b875e-209">Deletes this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="b875e-210">削除操作は、ジョブを削除することを要求します。</span><span class="sxs-lookup"><span data-stu-id="b875e-210">The delete operation requests that the job be deleted.</span></span>  <span data-ttu-id="b875e-211">要求、ジョブを格納する、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="b875e-211">The request puts the job in the <see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" /> state.</span></span>
            <span data-ttu-id="b875e-212">バッチ サービスは、実行中のタスクを停止し、さらにクライアント操作をしなくても、実際のジョブの削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="b875e-212">The Batch service will stop any running tasks and perform the actual job deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="b875e-213">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="b875e-213">This is a blocking operation.</span></span> <span data-ttu-id="b875e-214">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-214">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.DeleteAsync (additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-215">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-215">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b875e-216">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="b875e-216">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-217">この <see cref="T:Microsoft.Azure.Batch.CloudJob" /> を削除します。</span><span class="sxs-lookup"><span data-stu-id="b875e-217">Deletes this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <returns><span data-ttu-id="b875e-218">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="b875e-218">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="b875e-219">削除操作は、ジョブを削除することを要求します。</span><span class="sxs-lookup"><span data-stu-id="b875e-219">The delete operation requests that the job be deleted.</span></span>  <span data-ttu-id="b875e-220">要求、ジョブを格納する、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="b875e-220">The request puts the job in the <see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" /> state.</span></span>
            <span data-ttu-id="b875e-221">バッチ サービスは、実行中のタスクを停止し、さらにクライアント操作をしなくても、実際のジョブの削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="b875e-221">The Batch service will stop any running tasks and perform the actual job deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="b875e-222">削除操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-222">The delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Disable">
      <MemberSignature Language="C#" Value="public void Disable (Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Disable(valuetype Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Disable(Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.Disable : Microsoft.Azure.Batch.Common.DisableJobOption * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Disable (disableJobOption, additionalBehaviors)" />
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
        <Parameter Name="disableJobOption" Type="Microsoft.Azure.Batch.Common.DisableJobOption" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="disableJobOption"><span data-ttu-id="b875e-223">ジョブに関連付けられているアクティブなタスクを行うには新機能を指定します。</span><span class="sxs-lookup"><span data-stu-id="b875e-223">Specifies what to do with active tasks associated with the job.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-224">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-224">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-225">これを無効に<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-225">Disables this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>  <span data-ttu-id="b875e-226">無効なジョブは、新しいタスクを実行しないでくださいが、後で再度有効ことがあります。</span><span class="sxs-lookup"><span data-stu-id="b875e-226">Disabled jobs do not run new tasks, but may be re-enabled later.</span></span>
            </summary>
        <remarks><span data-ttu-id="b875e-227">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="b875e-227">This is a blocking operation.</span></span> <span data-ttu-id="b875e-228">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.DisableAsync(Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-228">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.DisableAsync(Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableAsync (Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableAsync(valuetype Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.DisableAsync(Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableAsync : Microsoft.Azure.Batch.Common.DisableJobOption * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.DisableAsync (disableJobOption, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="disableJobOption" Type="Microsoft.Azure.Batch.Common.DisableJobOption" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="disableJobOption"><span data-ttu-id="b875e-229">ジョブに関連付けられているアクティブなタスクを行うには新機能を指定します。</span><span class="sxs-lookup"><span data-stu-id="b875e-229">Specifies what to do with active tasks associated with the job.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-230">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-230">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b875e-231">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="b875e-231">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-232">これを無効に<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-232">Disables this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>  <span data-ttu-id="b875e-233">無効なジョブは、新しいタスクを実行しないでくださいが、後で再度有効ことがあります。</span><span class="sxs-lookup"><span data-stu-id="b875e-233">Disabled jobs do not run new tasks, but may be re-enabled later.</span></span>
            </summary>
        <returns><span data-ttu-id="b875e-234">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="b875e-234">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="b875e-235">無効化操作が非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-235">The disable operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.CloudJob.DisplayName" />
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
            <span data-ttu-id="b875e-236">取得またはジョブの表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="b875e-236">Gets or sets the display name of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enable">
      <MemberSignature Language="C#" Value="public void Enable (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Enable(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Enable(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Enable (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Enable : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Enable additionalBehaviors" />
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
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-237">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-237">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-238">これにより、 <see cref="T:Microsoft.Azure.Batch.CloudJob" />、新しいタスクの実行を許可します。</span><span class="sxs-lookup"><span data-stu-id="b875e-238">Enables this <see cref="T:Microsoft.Azure.Batch.CloudJob" />, allowing new tasks to run.</span></span>
            </summary>
        <remarks><span data-ttu-id="b875e-239">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="b875e-239">This is a blocking operation.</span></span> <span data-ttu-id="b875e-240">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.EnableAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-240">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.EnableAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.EnableAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.EnableAsync (additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-241">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-241">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b875e-242">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="b875e-242">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-243">これにより、 <see cref="T:Microsoft.Azure.Batch.CloudJob" />、新しいタスクの実行を許可します。</span><span class="sxs-lookup"><span data-stu-id="b875e-243">Enables this <see cref="T:Microsoft.Azure.Batch.CloudJob" />, allowing new tasks to run.</span></span>
            </summary>
        <returns><span data-ttu-id="b875e-244">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="b875e-244">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="b875e-245">有効にする操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-245">The enable operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.Batch.CloudJob.ETag" />
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
            <span data-ttu-id="b875e-246">ジョブの ETag を取得します。</span><span class="sxs-lookup"><span data-stu-id="b875e-246">Gets the ETag for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobExecutionInformation ExecutionInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobExecutionInformation ExecutionInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.ExecutionInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExecutionInformation As JobExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ExecutionInformation : Microsoft.Azure.Batch.JobExecutionInformation" Usage="Microsoft.Azure.Batch.CloudJob.ExecutionInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b875e-247">ジョブの実行情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="b875e-247">Gets the execution information for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudTask GetTask (string taskId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudTask GetTask(string taskId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.GetTask(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetTask : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.CloudTask" Usage="cloudJob.GetTask (taskId, detailLevel, additionalBehaviors)" />
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
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="taskId"><span data-ttu-id="b875e-248">取得するためのタスクの id。</span><span class="sxs-lookup"><span data-stu-id="b875e-248">The id of the task to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="b875e-249">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="b875e-249">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-250">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-250">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-251">指定した <see cref="T:Microsoft.Azure.Batch.CloudTask" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="b875e-251">Gets the specified <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span></span>
            </summary>
        <returns><span data-ttu-id="b875e-252">A<see cref="T:Microsoft.Azure.Batch.CloudTask" />指定した Azure Batch のタスクに関する情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="b875e-252">A <see cref="T:Microsoft.Azure.Batch.CloudTask" /> containing information about the specified Azure Batch task.</span></span></returns>
        <remarks><span data-ttu-id="b875e-253">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="b875e-253">This is a blocking operation.</span></span> <span data-ttu-id="b875e-254">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.GetTaskAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-254">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.GetTaskAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt; GetTaskAsync (string taskId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; GetTaskAsync(string taskId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.GetTaskAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTaskAsync : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt;" Usage="cloudJob.GetTaskAsync (taskId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;GetTaskAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="taskId"><span data-ttu-id="b875e-255">取得するためのタスクの id。</span><span class="sxs-lookup"><span data-stu-id="b875e-255">The id of the task to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="b875e-256">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="b875e-256">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-257">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-257">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b875e-258">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="b875e-258">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-259">指定した <see cref="T:Microsoft.Azure.Batch.CloudTask" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="b875e-259">Gets the specified <see cref="T:Microsoft.Azure.Batch.CloudTask" />.</span></span>
            </summary>
        <returns><span data-ttu-id="b875e-260">A<see cref="T:Microsoft.Azure.Batch.CloudTask" />指定した Azure Batch のタスクに関する情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="b875e-260">A <see cref="T:Microsoft.Azure.Batch.CloudTask" /> containing information about the specified Azure Batch task.</span></span></returns>
        <remarks><span data-ttu-id="b875e-261">タスクの取得操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-261">The get task operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskCounts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskCounts GetTaskCounts (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.TaskCounts GetTaskCounts(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.GetTaskCounts(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTaskCounts (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As TaskCounts" />
      <MemberSignature Language="F#" Value="member this.GetTaskCounts : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.TaskCounts" Usage="cloudJob.GetTaskCounts additionalBehaviors" />
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
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-262">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-262">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-263">ジョブのタスクの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="b875e-263">Gets the task counts for the job.</span></span>
            </summary>
        <returns><span data-ttu-id="b875e-264">A<see cref="T:Microsoft.Azure.Batch.TaskCounts" />オブジェクトのタスクを含むジョブのカウント</span><span class="sxs-lookup"><span data-stu-id="b875e-264">A <see cref="T:Microsoft.Azure.Batch.TaskCounts" /> object containing the task counts for the job</span></span></returns>
        <remarks><span data-ttu-id="b875e-265">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="b875e-265">This is a blocking operation.</span></span> <span data-ttu-id="b875e-266">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.GetTaskCountsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-266">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.GetTaskCountsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskCountsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt; GetTaskCountsAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.TaskCounts&gt; GetTaskCountsAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.GetTaskCountsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTaskCountsAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt;" Usage="cloudJob.GetTaskCountsAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;GetTaskCountsAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-267">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-267">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b875e-268">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="b875e-268">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-269">ジョブのタスクの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="b875e-269">Gets the task counts for the job.</span></span>
            </summary>
        <returns><span data-ttu-id="b875e-270">A<see cref="T:Microsoft.Azure.Batch.TaskCounts" />ジョブのカウントをタスクを含むオブジェクトします。</span><span class="sxs-lookup"><span data-stu-id="b875e-270">A <see cref="T:Microsoft.Azure.Batch.TaskCounts" /> object containing the task counts for the job.</span></span></returns>
        <remarks><span data-ttu-id="b875e-271">ジョブのタスクの取得は、非同期的に操作の実行をカウントします。</span><span class="sxs-lookup"><span data-stu-id="b875e-271">The get job task counts operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.CloudJob.Id" />
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
            <span data-ttu-id="b875e-272">取得またはジョブの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="b875e-272">Gets or sets the id of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobManagerTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobManagerTask JobManagerTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobManagerTask JobManagerTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.JobManagerTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobManagerTask As JobManagerTask" />
      <MemberSignature Language="F#" Value="member this.JobManagerTask : Microsoft.Azure.Batch.JobManagerTask with get, set" Usage="Microsoft.Azure.Batch.CloudJob.JobManagerTask" />
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
            <span data-ttu-id="b875e-273">取得または、ジョブ マネージャー タスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="b875e-273">Gets or sets the Job Manager task.</span></span> <span data-ttu-id="b875e-274">ジョブ マネージャー タスクが起動されるときに、<see cref="T:Microsoft.Azure.Batch.CloudJob" />が開始します。</span><span class="sxs-lookup"><span data-stu-id="b875e-274">The Job Manager task is launched when the <see cref="T:Microsoft.Azure.Batch.CloudJob" /> is started.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparationTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobPreparationTask JobPreparationTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobPreparationTask JobPreparationTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.JobPreparationTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparationTask As JobPreparationTask" />
      <MemberSignature Language="F#" Value="member this.JobPreparationTask : Microsoft.Azure.Batch.JobPreparationTask with get, set" Usage="Microsoft.Azure.Batch.CloudJob.JobPreparationTask" />
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
            <span data-ttu-id="b875e-275">取得またはジョブの準備タスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="b875e-275">Gets or sets the Job Preparation task.</span></span> <span data-ttu-id="b875e-276">バッチ サービスは、そのコンピューティング ノードでそのジョブのすべてのタスクを開始する前に、コンピューティング ノードでジョブの準備タスクが実行されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-276">The Batch service will run the Job Preparation task on a compute node before starting any tasks of that job on that compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobReleaseTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobReleaseTask JobReleaseTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobReleaseTask JobReleaseTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.JobReleaseTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobReleaseTask As JobReleaseTask" />
      <MemberSignature Language="F#" Value="member this.JobReleaseTask : Microsoft.Azure.Batch.JobReleaseTask with get, set" Usage="Microsoft.Azure.Batch.CloudJob.JobReleaseTask" />
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
            <span data-ttu-id="b875e-277">取得またはジョブのリリース タスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="b875e-277">Gets or sets the Job Release task.</span></span> <span data-ttu-id="b875e-278">バッチ サービスは、ジョブのいずれかのタスクが実行される各コンピューティング ノードで、ジョブの終了時に、ジョブのリリース タスクを実行します。</span><span class="sxs-lookup"><span data-stu-id="b875e-278">The Batch service runs the Job Release task when the job ends, on each compute node where any task of the job has run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudJob.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b875e-279">ジョブの最終更新時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="b875e-279">Gets the last modified time of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTasks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; ListTasks (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; ListTasks(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.ListTasks(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListTasks : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" Usage="cloudJob.ListTasks (detailLevel, additionalBehaviors)" />
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
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="b875e-280">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="b875e-280">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-281">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-281">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-282">列挙、<see cref="T:Microsoft.Azure.Batch.CloudTask">タスク</see>この<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-282">Enumerates the <see cref="T:Microsoft.Azure.Batch.CloudTask">tasks</see> of this <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <returns><span data-ttu-id="b875e-283"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を使用して非同期的または同期的にタスクの列挙をことができます。</span><span class="sxs-lookup"><span data-stu-id="b875e-283">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate tasks asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="b875e-284">このメソッドがすぐに戻るタスクは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-284">This method returns immediately; the tasks are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="b875e-285">検索は非アトミックなです。タスクは、コレクションの列挙中にページで取得されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-285">Retrieval is non-atomic; tasks are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.Metadata" />
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
            <span data-ttu-id="b875e-286">取得またはメタデータとしてジョブに関連付けられている名前と値のペアの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="b875e-286">Gets or sets a list of name-value pairs associated with the job as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAllTasksComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt; OnAllTasksComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt; OnAllTasksComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.OnAllTasksComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property OnAllTasksComplete As Nullable(Of OnAllTasksComplete)" />
      <MemberSignature Language="F#" Value="member this.OnAllTasksComplete : Nullable&lt;Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.OnAllTasksComplete" />
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
            <span data-ttu-id="b875e-287">取得またはアクション、ジョブ内のすべてのタスクがあるときにサービスが実行するバッチの設定、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" />状態です。</span><span class="sxs-lookup"><span data-stu-id="b875e-287">Gets or sets the action the Batch service should take when all tasks in the job are in the <see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" /> state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTaskFailure">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.OnTaskFailure&gt; OnTaskFailure { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.OnTaskFailure&gt; OnTaskFailure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.OnTaskFailure" />
      <MemberSignature Language="VB.NET" Value="Public Property OnTaskFailure As Nullable(Of OnTaskFailure)" />
      <MemberSignature Language="F#" Value="member this.OnTaskFailure : Nullable&lt;Microsoft.Azure.Batch.Common.OnTaskFailure&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.OnTaskFailure" />
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
            <span data-ttu-id="b875e-288">取得または、ジョブ内の任意のタスクが失敗したときに、バッチ サービスが実行するアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="b875e-288">Gets or sets the action the Batch service should take when any task in the job fails.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b875e-289">タスクは、ゼロ以外の終了コードが完了し、再試行カウントが不足する場合は、またはスケジュール設定エラーが発生した場合に失敗したと見なされます。</span><span class="sxs-lookup"><span data-stu-id="b875e-289">A task is considered to have failed if it completes with a non-zero exit code and has exhausted its retry count, or if it had a scheduling error.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolInformation PoolInformation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.PoolInformation PoolInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.PoolInformation" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolInformation As PoolInformation" />
      <MemberSignature Language="F#" Value="member this.PoolInformation : Microsoft.Azure.Batch.PoolInformation with get, set" Usage="Microsoft.Azure.Batch.CloudJob.PoolInformation" />
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
            <span data-ttu-id="b875e-290">取得またはバッチ サービスがジョブのタスクを実行するプールを設定します。</span><span class="sxs-lookup"><span data-stu-id="b875e-290">Gets or sets the pool on which the Batch service runs the job's tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt; PreviousState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.JobState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousState As Nullable(Of JobState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt;" Usage="Microsoft.Azure.Batch.CloudJob.PreviousState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b875e-291">ジョブの以前の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="b875e-291">Gets the previous state of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b875e-292">ジョブが場合は、初期の<see cref="F:Microsoft.Azure.Batch.Common.JobState.Active" />状態、PreviousState プロパティが定義されていません。</span><span class="sxs-lookup"><span data-stu-id="b875e-292">If the job is in its initial <see cref="F:Microsoft.Azure.Batch.Common.JobState.Active" /> state, the PreviousState property is not defined.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudJob.PreviousStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b875e-293">ジョブを直前の状態が入力された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="b875e-293">Gets the time at which the job entered its previous state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b875e-294">ジョブが場合は、初期の<see cref="F:Microsoft.Azure.Batch.Common.JobState.Active" />状態、PreviousStateTransitionTime プロパティが定義されていません。</span><span class="sxs-lookup"><span data-stu-id="b875e-294">If the job is in its initial <see cref="F:Microsoft.Azure.Batch.Common.JobState.Active" /> state, the PreviousStateTransitionTime property is not defined.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.Priority" />
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
            <span data-ttu-id="b875e-295">取得またはジョブの優先順位を設定します。</span><span class="sxs-lookup"><span data-stu-id="b875e-295">Gets or sets the priority of the job.</span></span> <span data-ttu-id="b875e-296">優先順位の値の範囲は -1000 から 1000、-1000 が最も低い優先度と 1000 中優先順位が高いです。</span><span class="sxs-lookup"><span data-stu-id="b875e-296">Priority values can range from -1000 to 1000, with -1000 being the lowest priority and 1000 being the highest priority.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b875e-297">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="b875e-297">The default value is 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public void Refresh (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Refresh(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="abstract member Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit&#xA;override this.Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Refresh (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="b875e-298">最新の更新の詳細レベルです。</span><span class="sxs-lookup"><span data-stu-id="b875e-298">The detail level for the refresh.</span></span>  <span data-ttu-id="b875e-299">詳細レベルを省略する場合、<see cref="P:Microsoft.Azure.Batch.CloudJob.Id" />プロパティを指定すると、更新は失敗します。</span><span class="sxs-lookup"><span data-stu-id="b875e-299">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.CloudJob.Id" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-300">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-300">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-301">現在の更新<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-301">Refreshes the current <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.RefreshAsync (detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;RefreshAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="b875e-302">最新の更新の詳細レベルです。</span><span class="sxs-lookup"><span data-stu-id="b875e-302">The detail level for the refresh.</span></span>  <span data-ttu-id="b875e-303">詳細レベルを省略する場合、<see cref="P:Microsoft.Azure.Batch.CloudJob.Id" />プロパティを指定すると、更新は失敗します。</span><span class="sxs-lookup"><span data-stu-id="b875e-303">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.CloudJob.Id" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-304">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-304">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b875e-305">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="b875e-305">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-306">現在の更新<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-306">Refreshes the current <see cref="T:Microsoft.Azure.Batch.CloudJob" />.</span></span>
            </summary>
        <returns><span data-ttu-id="b875e-307">A<see cref="T:System.Threading.Tasks.Task" />非同期更新操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="b875e-307">A <see cref="T:System.Threading.Tasks.Task" /> representing the asynchronous refresh operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.JobState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of JobState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt;" Usage="Microsoft.Azure.Batch.CloudJob.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b875e-308">ジョブの現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="b875e-308">Gets the current state of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudJob.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b875e-309">ジョブが現在の状態を入力する時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="b875e-309">Gets the time at which the job entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobStatistics Statistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobStatistics Statistics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Statistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Statistics As JobStatistics" />
      <MemberSignature Language="F#" Value="member this.Statistics : Microsoft.Azure.Batch.JobStatistics" Usage="Microsoft.Azure.Batch.CloudJob.Statistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b875e-310">ジョブの有効期間全体のリソース使用状況の統計を取得します。</span><span class="sxs-lookup"><span data-stu-id="b875e-310">Gets resource usage statistics for the entire lifetime of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b875e-311">場合にのみ、このプロパティが設定されます、<see cref="T:Microsoft.Azure.Batch.CloudJob" />で取得した、 <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" /> 'stats' 属性を含むそれ以外の場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="b875e-311">This property is populated only if the <see cref="T:Microsoft.Azure.Batch.CloudJob" /> was retrieved with an <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" /> including the 'stats' attribute; otherwise it is null.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="public void Terminate (string terminateReason = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Terminate(string terminateReason, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Terminate(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Terminate (Optional terminateReason As String = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Terminate : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Terminate (terminateReason, additionalBehaviors)" />
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
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="terminateReason"><span data-ttu-id="b875e-312">ジョブのとして表示するテキスト<see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-312">The text you want to appear as the job's <see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-313">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-313">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-314">これが終了<see cref="T:Microsoft.Azure.Batch.CloudJob" />、完了済みとしてマークすることです。</span><span class="sxs-lookup"><span data-stu-id="b875e-314">Terminates this <see cref="T:Microsoft.Azure.Batch.CloudJob" />, marking it as completed.</span></span>
            </summary>
        <remarks><span data-ttu-id="b875e-315">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="b875e-315">This is a blocking operation.</span></span> <span data-ttu-id="b875e-316">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.TerminateAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-316">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CloudJob.TerminateAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task TerminateAsync (string terminateReason = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task TerminateAsync(string terminateReason, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.TerminateAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.TerminateAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.TerminateAsync (terminateReason, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="terminateReason"><span data-ttu-id="b875e-317">ジョブのとして表示するテキスト<see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-317">The text you want to appear as the job's <see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="b875e-318">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="b875e-318">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="b875e-319">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="b875e-319">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="b875e-320">これが終了<see cref="T:Microsoft.Azure.Batch.CloudJob" />、完了済みとしてマークすることです。</span><span class="sxs-lookup"><span data-stu-id="b875e-320">Terminates this <see cref="T:Microsoft.Azure.Batch.CloudJob" />, marking it as completed.</span></span>
            </summary>
        <returns><span data-ttu-id="b875e-321">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b875e-321">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="b875e-322">終了操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="b875e-322">The terminate operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.CloudJob.Url" />
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
            <span data-ttu-id="b875e-323">ジョブの URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="b875e-323">Gets the URL of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsesTaskDependencies">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsesTaskDependencies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsesTaskDependencies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.UsesTaskDependencies" />
      <MemberSignature Language="VB.NET" Value="Public Property UsesTaskDependencies As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsesTaskDependencies : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.UsesTaskDependencies" />
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
            <span data-ttu-id="b875e-324">取得または、ジョブ内のタスクは相互に依存関係を定義することができるかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="b875e-324">Gets or sets whether tasks in the job can define dependencies on each other.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b875e-325">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="b875e-325">The default value is false.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>