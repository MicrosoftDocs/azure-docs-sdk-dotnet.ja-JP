<Type Name="ITransaction" FullName="Microsoft.ServiceFabric.Data.ITransaction">
  <TypeSignature Language="C#" Value="public interface ITransaction : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITransaction implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.ITransaction" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITransaction&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ITransaction = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="cbefc-101">一連の操作は、作業の 1 つの論理単位として実行されます。</span><span class="sxs-lookup"><span data-stu-id="cbefc-101">A sequence of operations performed as a single logical unit of work.</span></span>
             </summary>
    <remarks>
             <span data-ttu-id="cbefc-102">トランザクションは、次の ACID プロパティを示す必要があります。</span><span class="sxs-lookup"><span data-stu-id="cbefc-102">A transaction must exhibit the following ACID properties.</span></span> <span data-ttu-id="cbefc-103">(を参照してください: https://technet.microsoft.com/en-us/library/ms190612)<list type="bullet"> <item> <description>原子性、トランザクションは作業のアトミック単位である必要がありますすべてそのデータ変更が実行される場合、または、どれもが使用されます。</description></item><item><description>整合性 - が完了したら、トランザクション残す必要がありますすべてのデータ一貫性のある状態にします。すべての内部データ構造は、トランザクション終了時に正しくなければなりません。</description></item><item><description>分離 - 同時実行トランザクションによって加えられた変更は、他の同時実行トランザクションによって加えられた変更から分離する必要があります。内の操作を使用する分離レベル、<see cref="T:Microsoft.ServiceFabric.Data.ITransaction" />によって決定されます、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />操作を実行します。</description></item><item><description>-の持続性トランザクションが完了すると、その影響が完全に内でシステムです。システム障害が発生しても変更は永続化します。</description></item></list><para>この型の任意のインスタンス メンバーは、スレッド セーフである保証はされません。これにより、トランザクション、同時実行の単位: ユーザーは、特定の時点の時間、インフライトの複数のトランザクションを持つことができますが、特定のトランザクションの各 API 呼び出す必要があります、一度に 1 つです。すべて<see cref="T:IReliableCollection{T}" />トランザクションと、タスクがある必要がありますの戻り値をそのまま使用する Api は、一度に 1 つを待機します。</para><para>正しい使用法の例を次に示します。</span><span class="sxs-lookup"><span data-stu-id="cbefc-103">(see: https://technet.microsoft.com/en-us/library/ms190612) <list type="bullet"><item><description> Atomicity - A transaction must be an atomic unit of work; either all of its data modifications are performed, or none of them is performed. </description></item><item><description> Consistency - When completed, a transaction must leave all data in a consistent state. All internal data structures must be correct at the end of the transaction. </description></item><item><description> Isolation - Modifications made by concurrent transactions must be isolated from the modifications made by any other concurrent transactions. The isolation level used for an operation within an <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" /> is determined by the <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> performing the operation. </description></item><item><description> Durability - After a transaction has completed, its effects are permanently in place in the system. The modifications persist even in the event of a system failure. </description></item></list><para> Any instance member of this type is not guaranteed to be thread safe. This makes transactions the unit of concurrency: Users can have multiple transactions in-flight at any given point of time, but for a given transaction each API must be called one at a time. All <see cref="T:IReliableCollection{T}" /> APIs that accept a transaction and return a Task must be awaited one at a time. </para><para> Following is an example of a correct usage.</span></span>
             <span data-ttu-id="cbefc-104"><code><![CDATA[
                         
                         while (true)
                     {
                         cancellationToken.ThrowIfCancellationRequested();
                         
                     try
                         {
                         using (var tx = this.StateManager.CreateTransaction())
                         {
                         await concurrentQueue.EnqueueAsync(tx, 12L, cancellationToken);
                     await tx.CommitAsync();
                         
                         return;
                     }
             }
             catch (TransactionFaultedException e)
             {
             // This indicates that the transaction was internally faulted by the system. One possible cause for this is that the transaction was long running
             // and blocked a checkpoint. Increasing the "ReliableStateManagerReplicatorSettings.CheckpointThresholdInMB" will help reduce the chances of running into this exception
             Console.WriteLine("Transaction was internally faulted, retrying the transaction: " + e);
             }
                 catch (FabricNotPrimaryException e)
                 {
                     // Gracefully exit RunAsync as the new primary should have RunAsync invoked on it and continue work.
             // If instead enqueue was being executed as part of a client request, the client would be signaled to re-resolve.
                     Console.WriteLine("Replica is not primary, exiting RunAsync: " + e);
                     return;
                         }
                         catch (FabricNotReadableException e)
                             {
                             // Retry until the queue is readable or a different exception is thrown.
            Console.WriteLine("Queue is not readable, retrying the transaction: " + e);
                             }
                         catch (FabricObjectClosedException e)
                     {
                     // Gracefully exit RunAsync as this is happening due to replica close.
                     // If instead enqueue was being executed as part of a client request, the client would be signaled to re-resolve.
                         Console.WriteLine("Replica is closing, exiting RunAsync: " + e);
                         return;
                         }
                     catch (TimeoutException e)
                     {
                     Console.WriteLine("Encountered TimeoutException during EnqueueAsync, retrying the transaction: " + e);
                         }
                         
                         // Delay and retry.
                         await Task.Delay(TimeSpan.FromMilliseconds(100), cancellationToken);
                     }
                     ]]></code></para><para>未定義の動作に不適切な使用例を次に示します。</span><span class="sxs-lookup"><span data-stu-id="cbefc-104"><code><![CDATA[
                     
                         while (true)
                         {
                     cancellationToken.ThrowIfCancellationRequested();
                     
                     try
                         {
                         using (var tx = this.StateManager.CreateTransaction())
                         {
                         await concurrentQueue.EnqueueAsync(tx, 12L, cancellationToken);
                     await tx.CommitAsync();
                     
                     return;
                         }
                     }
            catch (TransactionFaultedException e)
                     {
                     // This indicates that the transaction was internally faulted by the system. One possible cause for this is that the transaction was long running
                 // and blocked a checkpoint. Increasing the "ReliableStateManagerReplicatorSettings.CheckpointThresholdInMB" will help reduce the chances of running into this exception
             Console.WriteLine("Transaction was internally faulted, retrying the transaction: " + e);
             }
             catch (FabricNotPrimaryException e)
             {
             // Gracefully exit RunAsync as the new primary should have RunAsync invoked on it and continue work.
                 // If instead enqueue was being executed as part of a client request, the client would be signaled to re-resolve.
                 Console.WriteLine("Replica is not primary, exiting RunAsync: " + e);
                 return;
             }
                 catch (FabricNotReadableException e)
                 {
             // Retry until the queue is readable or a different exception is thrown.
             Console.WriteLine("Queue is not readable, retrying the transaction: " + e);
}
catch (FabricObjectClosedException e)
{
// Gracefully exit RunAsync as this is happening due to replica close.
// If instead enqueue was being executed as part of a client request, the client would be signaled to re-resolve.
Console.WriteLine("Replica is closing, exiting RunAsync: " + e);
return;
}
catch (TimeoutException e)
{
Console.WriteLine("Encountered TimeoutException during EnqueueAsync, retrying the transaction: " + e);
}

// Delay and retry.
await Task.Delay(TimeSpan.FromMilliseconds(100), cancellationToken);
}
]]></code></para><para> The following is an example of incorrect usage that has undefined behavior.</span></span>
<code><![CDATA[
using (var txn = this.StateManager.CreateTransaction())
{
List<Task> taskList = new List<Task>();
taskList.Add(concurrentQueue.DequeueAsync(txn, cancellationToken));
taskList.Add(concurrentQueue.DequeueAsync(txn, cancellationToken));

await Task.WhenAll(taskList);
await txn.CommitAsync();
}
]]></code></para></remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ITransaction.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iTransaction.Abort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cbefc-105">中止 (ロールバック) トランザクション。</span><span class="sxs-lookup"><span data-stu-id="cbefc-105">Abort (rolls back) the transaction.</span></span>
            </summary>
        <remarks>
          <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="cbefc-106">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="cbefc-106">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="cbefc-107">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="cbefc-107">Retry the operation on a new transaction</span></span></exception>
          <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="cbefc-108">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cbefc-108">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="cbefc-109">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="cbefc-109">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="cbefc-110">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="cbefc-110">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
          <exception cref="T:System.Fabric.FabricNotPrimaryException">
            <span data-ttu-id="cbefc-111">トランザクションには、更新プログラムが含まれています。<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と<see cref="T:System.Fabric.ReplicaRole" />プライマリではありません。</span><span class="sxs-lookup"><span data-stu-id="cbefc-111">The transaction includes updates to <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> and the <see cref="T:System.Fabric.ReplicaRole" /> is not Primary.</span></span>
            <span data-ttu-id="cbefc-112">プライマリ レプリカのみでは、書き込みの状態が与えられます。</span><span class="sxs-lookup"><span data-stu-id="cbefc-112">Only Primary replicas are given write status.</span></span>
            </exception>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CommitAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ITransaction.CommitAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CommitAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CommitAsync : unit -&gt; System.Threading.Tasks.Task" Usage="iTransaction.CommitAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cbefc-113">トランザクションをコミットします。</span><span class="sxs-lookup"><span data-stu-id="cbefc-113">Commit the transaction.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cbefc-114">非同期コミット操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="cbefc-114">A task that represents the asynchronous commit operation.</span></span> 
            </returns>
        <remarks>
            <span data-ttu-id="cbefc-115">すべての変更が永続化された、レプリケートされるため、コミットされていると、トランザクションを中止できません。</span><span class="sxs-lookup"><span data-stu-id="cbefc-115">You cannot abort a transaction once it has been committed, because all modifications have been persisted and replicated.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="cbefc-116">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="cbefc-116">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="cbefc-117">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="cbefc-117">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="cbefc-118">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cbefc-118">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="cbefc-119">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="cbefc-119">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="cbefc-120">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="cbefc-120">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">
            <span data-ttu-id="cbefc-121">トランザクションには、更新プログラムが含まれています。<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と<see cref="T:System.Fabric.ReplicaRole" />プライマリではありません。</span><span class="sxs-lookup"><span data-stu-id="cbefc-121">The transaction includes updates to <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> and the <see cref="T:System.Fabric.ReplicaRole" /> is not Primary.</span></span>
            <span data-ttu-id="cbefc-122">プライマリ レプリカのみでは、書き込みの状態が与えられます。</span><span class="sxs-lookup"><span data-stu-id="cbefc-122">Only Primary replicas are given write status.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CommitSequenceNumber">
      <MemberSignature Language="C#" Value="public long CommitSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CommitSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ITransaction.CommitSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CommitSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.CommitSequenceNumber : int64" Usage="Microsoft.ServiceFabric.Data.ITransaction.CommitSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cbefc-123">コミット操作のシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="cbefc-123">Sequence number for the commit operation.</span></span>
            </summary>
        <value>
            <span data-ttu-id="cbefc-124">シーケンス番号をトランザクションがコミットされました。</span><span class="sxs-lookup"><span data-stu-id="cbefc-124">The sequence number at which the the transaction was committed.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVisibilitySequenceNumberAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; GetVisibilitySequenceNumberAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; GetVisibilitySequenceNumberAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ITransaction.GetVisibilitySequenceNumberAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVisibilitySequenceNumberAsync () As Task(Of Long)" />
      <MemberSignature Language="F#" Value="abstract member GetVisibilitySequenceNumberAsync : unit -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iTransaction.GetVisibilitySequenceNumberAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cbefc-125">可視性のシーケンス番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbefc-125">Gets the visibility sequence number.</span></span>
            </summary>
        <returns><span data-ttu-id="cbefc-126">可視性のシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="cbefc-126">The visibility sequence number.</span></span></returns>
        <remarks>
          <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="cbefc-127">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="cbefc-127">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="cbefc-128">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="cbefc-128">Retry the operation on a new transaction</span></span></exception>
          <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="cbefc-129">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cbefc-129">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="cbefc-130">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="cbefc-130">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="cbefc-131">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="cbefc-131">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TransactionId">
      <MemberSignature Language="C#" Value="public long TransactionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TransactionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ITransaction.TransactionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransactionId As Long" />
      <MemberSignature Language="F#" Value="member this.TransactionId : int64" Usage="Microsoft.ServiceFabric.Data.ITransaction.TransactionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cbefc-132">トランザクションを識別する値を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbefc-132">Gets a value identifying the transaction.</span></span>
            </summary>
        <value><span data-ttu-id="cbefc-133">トランザクション id。</span><span class="sxs-lookup"><span data-stu-id="cbefc-133">The transaction id.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>