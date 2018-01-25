<Type Name="IReliableQueue&lt;T&gt;" FullName="Microsoft.ServiceFabric.Data.Collections.IReliableQueue&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IReliableQueue&lt;T&gt; : Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableQueue`1&lt;T&gt; implements class Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1&lt;!T&gt;, class Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableQueue(Of T)&#xA;Implements IReliableCollection(Of T)" />
  <TypeSignature Language="F#" Value="type IReliableQueue&lt;'T&gt; = interface&#xA;    interface IReliableCollection&lt;'T&gt;&#xA;    interface IReliableState" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;T&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T"><span data-ttu-id="36c69-101">信頼性の高いキューに格納されている要素の型。</span><span class="sxs-lookup"><span data-stu-id="36c69-101">The type of the elements contained in the reliable queue.</span></span></typeparam>
    <summary>
            <span data-ttu-id="36c69-102">信頼性の高い、先入れ先出しのコレクションを表します永続化され、レプリケートされるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="36c69-102">Represents a reliable first-in, first-out collection of objects that are persisted and replicated.</span></span>
            </summary>
    <remarks>
      <para>
            <span data-ttu-id="36c69-103">このキューに格納されている値は、キューでの操作のコンテキスト外変換します。</span><span class="sxs-lookup"><span data-stu-id="36c69-103">Values stored in this queue MUST NOT be mutated outside the context of an operation on the queue.</span></span> <span data-ttu-id="36c69-104">強くお勧めする<typeparamref name="T" />偶発的なデータの破損を回避するために変更できません。</span><span class="sxs-lookup"><span data-stu-id="36c69-104">It is highly recommended to make <typeparamref name="T" /> immutable in order to avoid accidental data corruption.</span></span>
            </para>
      <para>
            <span data-ttu-id="36c69-105">トランザクションは、同時実行の単位: ユーザーは、時間の特定の時点インフライトの複数のトランザクションを持つことができますが、特定のトランザクションの各 API 呼び出す必要があります、一度に 1 つです。</span><span class="sxs-lookup"><span data-stu-id="36c69-105">Transaction is the unit of concurrency: Users can have multiple transactions in-flight at any given point of time but for a given transaction each API must be called one at a time.</span></span>
            <span data-ttu-id="36c69-106">すべての信頼性の高いコレクション Api をトランザクションでは、タスクを返すには、待機中の 1 つずつをする必要があります。</span><span class="sxs-lookup"><span data-stu-id="36c69-106">So all Reliable Collection APIs that take in a transaction and return a Task, must be awaited one at a time.</span></span>
            <seealso cref="T:Microsoft.ServiceFabric.Data.ITransaction" /></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;T&gt;&gt; CreateEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction tx);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;!T&gt;&gt; CreateEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction tx) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.CreateEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEnumerableAsync (tx As ITransaction) As Task(Of IAsyncEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="abstract member CreateEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;'T&gt;&gt;" Usage="iReliableQueue.CreateEnumerableAsync tx" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="36c69-107">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="36c69-107">Transaction to associate this operation with.</span></span></param>
        <summary>
            <span data-ttu-id="36c69-108">経由で列挙可能な非同期を作成、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />です。</span><span class="sxs-lookup"><span data-stu-id="36c69-108">Creates an async enumerable over the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />.</span></span>
            </summary>
        <returns><span data-ttu-id="36c69-109">すべての値を表す IEnumerable です。</span><span class="sxs-lookup"><span data-stu-id="36c69-109">IEnumerable that represents all the values.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="36c69-110">例外には、ことを示します、<cref name="IReliableQueue{T}" />時点で読み取りを処理できません。</span><span class="sxs-lookup"><span data-stu-id="36c69-110">Exception indicates that the <cref name="IReliableQueue{T}" /> cannot serve reads at the moment.</span></span>
            <span data-ttu-id="36c69-111"><cref name="FabricNotReadableException" />すべてのページでスローされる可能性<cref name="ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="36c69-111"><cref name="FabricNotReadableException" /> can be thrown in all <cref name="ReplicaRole" />s.</span></span>
            <span data-ttu-id="36c69-112">1 つの例でスローされたため、<cref name="ReplicaRole.Primary" />が失われること<cref name="IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="36c69-112">One example for it being thrown in the <cref name="ReplicaRole.Primary" /> is loss of <cref name="IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="36c69-113">1 つの例でスローされたため、<cref name="ReplicaRole.ActiveSecondary" />は、信頼性の高いキューの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="36c69-113">One example for it being thrown in the <cref name="ReplicaRole.ActiveSecondary" /> is that Reliable Queue's state is not yet consistent.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnqueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnqueueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, T item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task EnqueueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !T item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnqueueAsync (tx As ITransaction, item As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member EnqueueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'T -&gt; System.Threading.Tasks.Task" Usage="iReliableQueue.EnqueueAsync (tx, item)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="item" Type="T" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="36c69-114">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="36c69-114">Transaction to associate this operation with.</span></span></param>
        <param name="item"><span data-ttu-id="36c69-115">キューの末尾に追加するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="36c69-115">The object to add to the end of the queue.</span></span> <span data-ttu-id="36c69-116">参照型の場合は、値を null にできます。</span><span class="sxs-lookup"><span data-stu-id="36c69-116">The value can be null for reference types.</span></span></param>
        <summary>
            <span data-ttu-id="36c69-117">信頼性の高いキューの末尾にオブジェクトを追加します。</span><span class="sxs-lookup"><span data-stu-id="36c69-117">Adds an object to the end of the reliable queue.</span></span>
            </summary>
        <returns><span data-ttu-id="36c69-118">非同期のエンキュー操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="36c69-118">Task that represents the asynchronous enqueue operation.</span></span></returns>
        <remarks><span data-ttu-id="36c69-119">再試行可能な例外は、このメソッドによってスローされた場合は、トランザクションを破棄する勧め<paramref name="tx" />し、新しいトランザクションでもう一度やり直してください。</span><span class="sxs-lookup"><span data-stu-id="36c69-119">If a retriable exception is thrown by this method, it is recommended to dispose the transaction <paramref name="tx" /> and try again with a new transaction.</span></span></remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="36c69-120"><paramref name="tx" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="36c69-120"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="36c69-121">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="36c69-121">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="36c69-122">ときにスローされる例外、<cref name="IReliableQueue{T}" />に含まれていない<cref name="ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="36c69-122">The exception that is thrown when the <cref name="IReliableQueue{T}" /> is not in <cref name="ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="36c69-123">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-123">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="36c69-124">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="36c69-124">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="36c69-125">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="36c69-125">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="36c69-126">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-126">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="36c69-127">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="36c69-127">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnqueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnqueueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, T item, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task EnqueueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !T item, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnqueueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'T * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReliableQueue.EnqueueAsync (tx, item, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="item" Type="T" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="36c69-128">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="36c69-128">Transaction to associate this operation with.</span></span></param>
        <param name="item"><span data-ttu-id="36c69-129">キューの末尾に追加するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="36c69-129">The object to add to the end of the queue.</span></span> <span data-ttu-id="36c69-130">参照型の場合は、値を null にできます。</span><span class="sxs-lookup"><span data-stu-id="36c69-130">The value can be null for reference types.</span></span></param>
        <param name="timeout"><span data-ttu-id="36c69-131">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="36c69-131">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="36c69-132">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="36c69-132">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="36c69-133">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="36c69-133">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="36c69-134">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="36c69-134">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="36c69-135">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="36c69-135">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="36c69-136">信頼性の高いキューの末尾にオブジェクトを追加します。</span><span class="sxs-lookup"><span data-stu-id="36c69-136">Adds an object to the end of the reliable queue.</span></span>
            </summary>
        <returns><span data-ttu-id="36c69-137">非同期のエンキュー操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="36c69-137">Task that represents the asynchronous enqueue operation.</span></span></returns>
        <remarks><span data-ttu-id="36c69-138">再試行可能な例外は、このメソッドによってスローされた場合は、トランザクションを破棄する勧め<paramref name="tx" />し、新しいトランザクションでもう一度やり直してください。</span><span class="sxs-lookup"><span data-stu-id="36c69-138">If a retriable exception is thrown by this method, it is recommended to dispose the transaction <paramref name="tx" /> and try again with a new transaction.</span></span></remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="36c69-139"><paramref name="tx" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="36c69-139"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="36c69-140"><paramref name="timeout" /> が負の値です。</span><span class="sxs-lookup"><span data-stu-id="36c69-140"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="36c69-141">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="36c69-141">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="36c69-142">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-142">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="36c69-143">ときにスローされる例外、<cref name="IReliableQueue{T}" />に含まれていない<cref name="ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="36c69-143">The exception that is thrown when the <cref name="IReliableQueue{T}" /> is not in <cref name="ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="36c69-144">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-144">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="36c69-145">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="36c69-145">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="36c69-146">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="36c69-146">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="36c69-147">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-147">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="36c69-148">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="36c69-148">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryDequeueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryDequeueAsync (Microsoft.ServiceFabric.Data.ITransaction tx);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryDequeueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryDequeueAsync (tx As ITransaction) As Task(Of ConditionalValue(Of T))" />
      <MemberSignature Language="F#" Value="abstract member TryDequeueAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryDequeueAsync tx" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="36c69-149">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="36c69-149">Transaction to associate this operation with.</span></span></param>
        <summary>
            <span data-ttu-id="36c69-150">削除して、信頼性の高いキューの先頭にオブジェクトを取得しようとします。</span><span class="sxs-lookup"><span data-stu-id="36c69-150">Tries to remove and return the object at the beginning of the reliable queue.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36c69-151">表す非同期のタスクには、操作がキューから削除します。</span><span class="sxs-lookup"><span data-stu-id="36c69-151">Task that represents the asynchronous dequeue operation.</span></span> <span data-ttu-id="36c69-152">タスクの結果の組は、その場合、オブジェクトが削除されたかどうかを示すオブジェクトを使用して、します。</span><span class="sxs-lookup"><span data-stu-id="36c69-152">The task result is a tuple indicating whether an object was removed and if so, the object.</span></span>
            </returns>
        <remarks><span data-ttu-id="36c69-153">再試行可能な例外は、このメソッドによってスローされた場合は、トランザクションを破棄する勧め<paramref name="tx" />し、新しいトランザクションでもう一度やり直してください。</span><span class="sxs-lookup"><span data-stu-id="36c69-153">If a retriable exception is thrown by this method, it is recommended to dispose the transaction <paramref name="tx" /> and try again with a new transaction.</span></span></remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="36c69-154"><paramref name="tx" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="36c69-154"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="36c69-155">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="36c69-155">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="36c69-156">ときにスローされる例外、<cref name="IReliableQueue{T}" />に含まれていない<cref name="ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="36c69-156">The exception that is thrown when the <cref name="IReliableQueue{T}" /> is not in <cref name="ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="36c69-157">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-157">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="36c69-158">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="36c69-158">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="36c69-159">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="36c69-159">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="36c69-160">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-160">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="36c69-161">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="36c69-161">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryDequeueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryDequeueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryDequeueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryDequeueAsync : Microsoft.ServiceFabric.Data.ITransaction * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryDequeueAsync (tx, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="36c69-162">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="36c69-162">Transaction to associate this operation with.</span></span></param>
        <param name="timeout"><span data-ttu-id="36c69-163">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="36c69-163">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="36c69-164">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="36c69-164">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="36c69-165">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="36c69-165">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="36c69-166">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="36c69-166">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="36c69-167">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="36c69-167">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="36c69-168">削除して、信頼性の高いキューの先頭にオブジェクトを取得しようとします。</span><span class="sxs-lookup"><span data-stu-id="36c69-168">Tries to remove and return the object at the beginning of the reliable queue.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36c69-169">表す非同期のタスクには、操作がキューから削除します。</span><span class="sxs-lookup"><span data-stu-id="36c69-169">Task that represents the asynchronous dequeue operation.</span></span> <span data-ttu-id="36c69-170">タスクの結果の組は、その場合、オブジェクトが削除されたかどうかを示すオブジェクトを使用して、します。</span><span class="sxs-lookup"><span data-stu-id="36c69-170">The task result is a tuple indicating whether an object was removed and if so, the object.</span></span>
            </returns>
        <remarks><span data-ttu-id="36c69-171">再試行可能な例外は、このメソッドによってスローされた場合は、トランザクションを破棄する勧め<paramref name="tx" />し、新しいトランザクションでもう一度やり直してください。</span><span class="sxs-lookup"><span data-stu-id="36c69-171">If a retriable exception is thrown by this method, it is recommended to dispose the transaction <paramref name="tx" /> and try again with a new transaction.</span></span></remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="36c69-172"><paramref name="tx" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="36c69-172"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="36c69-173"><paramref name="timeout" /> が負の値です。</span><span class="sxs-lookup"><span data-stu-id="36c69-173"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="36c69-174">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="36c69-174">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="36c69-175">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-175">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="36c69-176">ときにスローされる例外、<cref name="IReliableQueue{T}" />に含まれていない<cref name="ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="36c69-176">The exception that is thrown when the <cref name="IReliableQueue{T}" /> is not in <cref name="ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="36c69-177">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-177">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="36c69-178">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="36c69-178">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="36c69-179">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="36c69-179">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="36c69-180">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-180">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="36c69-181">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="36c69-181">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryPeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryPeekAsync (Microsoft.ServiceFabric.Data.ITransaction tx);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryPeekAsync(class Microsoft.ServiceFabric.Data.ITransaction tx) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryPeekAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryPeekAsync (tx As ITransaction) As Task(Of ConditionalValue(Of T))" />
      <MemberSignature Language="F#" Value="abstract member TryPeekAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryPeekAsync tx" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="36c69-182">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="36c69-182">Transaction to associate this operation with.</span></span></param>
        <summary>
            <span data-ttu-id="36c69-183">削除することがなく、信頼性の高いキューの先頭からオブジェクトを返すしようとしています。</span><span class="sxs-lookup"><span data-stu-id="36c69-183">Tries to return an object from the beginning of the reliable queue without removing it.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36c69-184">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="36c69-184">Task that represents the asynchronous peek operation.</span></span> <span data-ttu-id="36c69-185">タスクの結果の組は、その場合、キューの先頭にオブジェクトが見つかったかどうかを示すオブジェクトを使用して、します。</span><span class="sxs-lookup"><span data-stu-id="36c69-185">The task result is a tuple indicating whether an object was found at the beginning of the queue and if so, the object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="36c69-186"><paramref name="tx" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="36c69-186"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="36c69-187">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="36c69-187">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="36c69-188">例外には、ことを示します、<cref name="IReliableQueue{T}" />時点で読み取りを処理できません。</span><span class="sxs-lookup"><span data-stu-id="36c69-188">Exception indicates that the <cref name="IReliableQueue{T}" /> cannot serve reads at the moment.</span></span>
            <span data-ttu-id="36c69-189"><cref name="FabricNotReadableException" />すべてのページでスローされる可能性<cref name="ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="36c69-189"><cref name="FabricNotReadableException" /> can be thrown in all <cref name="ReplicaRole" />s.</span></span>
            <span data-ttu-id="36c69-190">1 つの例でスローされたため、<cref name="ReplicaRole.Primary" />が失われること<cref name="IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="36c69-190">One example for it being thrown in the <cref name="ReplicaRole.Primary" /> is loss of <cref name="IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="36c69-191">1 つの例でスローされたため、<cref name="ReplicaRole.ActiveSecondary" />は、信頼性の高いキューの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="36c69-191">One example for it being thrown in the <cref name="ReplicaRole.ActiveSecondary" /> is that Reliable Queue's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="36c69-192">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-192">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="36c69-193">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="36c69-193">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="36c69-194">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="36c69-194">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="36c69-195">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-195">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="36c69-196">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="36c69-196">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryPeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryPeekAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryPeekAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryPeekAsync(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Collections.LockMode)" />
      <MemberSignature Language="F#" Value="abstract member TryPeekAsync : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Collections.LockMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryPeekAsync (tx, lockMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="36c69-197">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="36c69-197">Transaction to associate this operation with.</span></span></param>
        <param name="lockMode"><span data-ttu-id="36c69-198">この読み取り操作に使用するロックの種類です。</span><span class="sxs-lookup"><span data-stu-id="36c69-198">Type of locking to use for this read operation.</span></span></param>
        <summary>
            <span data-ttu-id="36c69-199">削除することがなく、信頼性の高いキューの先頭からオブジェクトを返すしようとしています。</span><span class="sxs-lookup"><span data-stu-id="36c69-199">Tries to return an object from the beginning of the reliable queue without removing it.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36c69-200">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="36c69-200">Task that represents the asynchronous peek operation.</span></span> <span data-ttu-id="36c69-201">タスクの結果の組は、その場合、キューの先頭にオブジェクトが見つかったかどうかを示すオブジェクトを使用して、します。</span><span class="sxs-lookup"><span data-stu-id="36c69-201">The task result is a tuple indicating whether an object was found at the beginning of the queue and if so, the object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="36c69-202"><paramref name="tx" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="36c69-202"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="36c69-203">既定のタイムアウト以内に完了する操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="36c69-203">The operation failed to complete within the default timeout.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="36c69-204">例外には、ことを示します、<cref name="IReliableQueue{T}" />時点で読み取りを処理できません。</span><span class="sxs-lookup"><span data-stu-id="36c69-204">Exception indicates that the <cref name="IReliableQueue{T}" /> cannot serve reads at the moment.</span></span>
            <span data-ttu-id="36c69-205"><cref name="FabricNotReadableException" />すべてのページでスローされる可能性<cref name="ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="36c69-205"><cref name="FabricNotReadableException" /> can be thrown in all <cref name="ReplicaRole" />s.</span></span>
            <span data-ttu-id="36c69-206">1 つの例でスローされたため、<cref name="ReplicaRole.Primary" />が失われること<cref name="IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="36c69-206">One example for it being thrown in the <cref name="ReplicaRole.Primary" /> is loss of <cref name="IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="36c69-207">1 つの例でスローされたため、<cref name="ReplicaRole.ActiveSecondary" />は、信頼性の高いキューの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="36c69-207">One example for it being thrown in the <cref name="ReplicaRole.ActiveSecondary" /> is that Reliable Queue's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="36c69-208">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-208">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="36c69-209">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="36c69-209">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="36c69-210">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="36c69-210">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="36c69-211">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-211">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="36c69-212">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="36c69-212">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryPeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryPeekAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryPeekAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryPeekAsync(Microsoft.ServiceFabric.Data.ITransaction,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryPeekAsync : Microsoft.ServiceFabric.Data.ITransaction * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryPeekAsync (tx, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="36c69-213">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="36c69-213">Transaction to associate this operation with.</span></span></param>
        <param name="timeout"><span data-ttu-id="36c69-214">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="36c69-214">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="36c69-215">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="36c69-215">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="36c69-216">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="36c69-216">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="36c69-217">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="36c69-217">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="36c69-218">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="36c69-218">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="36c69-219">削除することがなく、信頼性の高いキューの先頭からオブジェクトを返すしようとしています。</span><span class="sxs-lookup"><span data-stu-id="36c69-219">Tries to return an object from the beginning of the reliable queue without removing it.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36c69-220">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="36c69-220">Task that represents the asynchronous peek operation.</span></span> <span data-ttu-id="36c69-221">タスクの結果の組は、その場合、キューの先頭にオブジェクトが見つかったかどうかを示すオブジェクトを使用して、します。</span><span class="sxs-lookup"><span data-stu-id="36c69-221">The task result is a tuple indicating whether an object was found at the beginning of the queue and if so, the object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="36c69-222"><paramref name="tx" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="36c69-222"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="36c69-223"><paramref name="timeout" /> が負の値です。</span><span class="sxs-lookup"><span data-stu-id="36c69-223"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="36c69-224">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="36c69-224">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="36c69-225">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-225">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="36c69-226">例外には、ことを示します、<cref name="IReliableQueue{T}" />時点で読み取りを処理できません。</span><span class="sxs-lookup"><span data-stu-id="36c69-226">Exception indicates that the <cref name="IReliableQueue{T}" /> cannot serve reads at the moment.</span></span>
            <span data-ttu-id="36c69-227"><cref name="FabricNotReadableException" />すべてのページでスローされる可能性<cref name="ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="36c69-227"><cref name="FabricNotReadableException" /> can be thrown in all <cref name="ReplicaRole" />s.</span></span>
            <span data-ttu-id="36c69-228">1 つの例でスローされたため、<cref name="ReplicaRole.Primary" />が失われること<cref name="IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="36c69-228">One example for it being thrown in the <cref name="ReplicaRole.Primary" /> is loss of <cref name="IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="36c69-229">1 つの例でスローされたため、<cref name="ReplicaRole.ActiveSecondary" />は、信頼性の高いキューの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="36c69-229">One example for it being thrown in the <cref name="ReplicaRole.ActiveSecondary" /> is that Reliable Queue's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="36c69-230">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-230">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="36c69-231">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="36c69-231">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="36c69-232">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="36c69-232">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="36c69-233">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-233">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="36c69-234">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="36c69-234">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryPeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryPeekAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryPeekAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryPeekAsync(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Collections.LockMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryPeekAsync : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Collections.LockMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryPeekAsync (tx, lockMode, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="36c69-235">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="36c69-235">Transaction to associate this operation with.</span></span></param>
        <param name="lockMode"><span data-ttu-id="36c69-236">この読み取り操作に使用するロックの種類です。</span><span class="sxs-lookup"><span data-stu-id="36c69-236">Type of locking to use for this read operation.</span></span></param>
        <param name="timeout"><span data-ttu-id="36c69-237">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="36c69-237">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="36c69-238">主にデッドロックを防ぐために使用します。</span><span class="sxs-lookup"><span data-stu-id="36c69-238">Primarily used to prevent deadlocks.</span></span> <span data-ttu-id="36c69-239">既定では 4 秒です。</span><span class="sxs-lookup"><span data-stu-id="36c69-239">The default is 4 seconds.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="36c69-240">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="36c69-240">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="36c69-241">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="36c69-241">The default is None.</span></span></param>
        <summary>
            <span data-ttu-id="36c69-242">削除することがなく、信頼性の高いキューの先頭からオブジェクトを返すしようとしています。</span><span class="sxs-lookup"><span data-stu-id="36c69-242">Tries to return an object from the beginning of the reliable queue without removing it.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36c69-243">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="36c69-243">Task that represents the asynchronous peek operation.</span></span> <span data-ttu-id="36c69-244">タスクの結果の組は、その場合、キューの先頭にオブジェクトが見つかったかどうかを示すオブジェクトを使用して、します。</span><span class="sxs-lookup"><span data-stu-id="36c69-244">The task result is a tuple indicating whether an object was found at the beginning of the queue and if so, the object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="36c69-245"><paramref name="tx" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="36c69-245"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="36c69-246"><paramref name="timeout" /> が負の値です。</span><span class="sxs-lookup"><span data-stu-id="36c69-246"><paramref name="timeout" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="36c69-247">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="36c69-247">The operation failed to complete within the given timeout.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="36c69-248">操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-248">The operation was canceled.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            <span data-ttu-id="36c69-249">例外には、ことを示します、<cref name="IReliableQueue{T}" />時点で読み取りを処理できません。</span><span class="sxs-lookup"><span data-stu-id="36c69-249">Exception indicates that the <cref name="IReliableQueue{T}" /> cannot serve reads at the moment.</span></span>
            <span data-ttu-id="36c69-250"><cref name="FabricNotReadableException" />すべてのページでスローされる可能性<cref name="ReplicaRole" />s。</span><span class="sxs-lookup"><span data-stu-id="36c69-250"><cref name="FabricNotReadableException" /> can be thrown in all <cref name="ReplicaRole" />s.</span></span>
            <span data-ttu-id="36c69-251">1 つの例でスローされたため、<cref name="ReplicaRole.Primary" />が失われること<cref name="IStatefulServicePartition.ReadStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="36c69-251">One example for it being thrown in the <cref name="ReplicaRole.Primary" /> is loss of <cref name="IStatefulServicePartition.ReadStatus" />.</span></span>
            <span data-ttu-id="36c69-252">1 つの例でスローされたため、<cref name="ReplicaRole.ActiveSecondary" />は、信頼性の高いキューの状態があるまだ一貫性のあります。</span><span class="sxs-lookup"><span data-stu-id="36c69-252">One example for it being thrown in the <cref name="ReplicaRole.ActiveSecondary" /> is that Reliable Queue's state is not yet consistent.</span></span>
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="36c69-253">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-253">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="36c69-254">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="36c69-254">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="36c69-255">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="36c69-255">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="36c69-256">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="36c69-256">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="36c69-257">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="36c69-257">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>