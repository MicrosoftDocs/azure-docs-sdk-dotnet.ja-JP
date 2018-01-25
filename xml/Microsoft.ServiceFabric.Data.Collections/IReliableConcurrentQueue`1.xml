<Type Name="IReliableConcurrentQueue&lt;T&gt;" FullName="Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IReliableConcurrentQueue&lt;T&gt; : Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableConcurrentQueue`1&lt;T&gt; implements class Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableConcurrentQueue(Of T)&#xA;Implements IReliableState" />
  <TypeSignature Language="F#" Value="type IReliableConcurrentQueue&lt;'T&gt; = interface&#xA;    interface IReliableState" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">
            <span data-ttu-id="159ee-101">スリム信頼性の高いキューに格納されている値の型。</span><span class="sxs-lookup"><span data-stu-id="159ee-101">The type of the values contained in the reliable queue slim.</span></span>
            </typeparam>
    <summary>
      <para>
            <span data-ttu-id="159ee-102">信頼性の高いベスト エフォート先入れ先出しの順序を永続化された、レプリケートされた値のコレクションを表します。</span><span class="sxs-lookup"><span data-stu-id="159ee-102">Represents a reliable collection of persisted, replicated values with best-effort first-in first-out ordering.</span></span>
            </para>
    </summary>
    <remarks>
      <para>
            <span data-ttu-id="159ee-103">代わりとして用意されています<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />ワークロードの厳密な順序付けが行われていない必要な場合として、順序付けの制約を緩和すること同時実行が大幅に向上できます。</span><span class="sxs-lookup"><span data-stu-id="159ee-103">Intended as an alternative to <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" /> for workloads where strict ordering is not required, as by relaxing the ordering constraint, concurrency can be greatly improved.</span></span>  <span data-ttu-id="159ee-104"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />1 つずつ、最大同時コンシューマーとプロデューサーを制限するときに<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />このような制限はありません。</span><span class="sxs-lookup"><span data-stu-id="159ee-104"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" /> restricts concurrent consumers and producers to a maximum of one each, while <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> imposes no such restriction.</span></span>
            </para>
      <para>
        <span data-ttu-id="159ee-105"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />その他の信頼できるデータ構造体として同じトランザクション分離のセマンティクスを提供していません。</span><span class="sxs-lookup"><span data-stu-id="159ee-105"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> does not offer the same transaction isolation semantics as the other reliable data structures.</span></span>  <span data-ttu-id="159ee-106">個々 の操作とプロパティを参照してください (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />、<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />と<see cref="P:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.Count" />) どのような分離の詳細については、存在する場合、それらを提供します。</span><span class="sxs-lookup"><span data-stu-id="159ee-106">See the individual operations and properties (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />, <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> and <see cref="P:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.Count" />) for details on what isolation, if any, they provide.</span></span>
            </para>
      <para>
            <span data-ttu-id="159ee-107">値をキューで比較的短時間になることが必要つまりの送信 (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />) 率は、受信以上になると (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />) 率。</span><span class="sxs-lookup"><span data-stu-id="159ee-107">It is expected that values will be relatively short-lived in the queue; in other words, that the egress (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />) rate is equal to or greater than the ingress (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />) rate.</span></span>  <span data-ttu-id="159ee-108">この期待値を違反すると、システムのパフォーマンスが悪化する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="159ee-108">Violating this expectation may worsen system performance.</span></span>  <span data-ttu-id="159ee-109">容量に達した後に受信キューに入れますを調整する計画的なキュー容量に制約は、このプロパティを維持するために役立ちます。</span><span class="sxs-lookup"><span data-stu-id="159ee-109">A planned queue capacity constraint which will throttle incoming Enqueues once the capacity is reached will help in maintaining this property.</span></span>
            <span data-ttu-id="159ee-110">プロパティを使用する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="159ee-110">property.</span></span>
            </para>
      <para>
            <span data-ttu-id="159ee-111">ように、要素の順序が厳密に限りませんが、キュー内の 2 つの値の順序について想定する必要がありますは行われません。</span><span class="sxs-lookup"><span data-stu-id="159ee-111">As the ordering of elements is not strictly guaranteed, assumptions about the ordering of any two values in the queue MUST NOT be made.</span></span>  <span data-ttu-id="159ee-112">ベスト エフォート先入れ先出しの順序付けは、提供公平性です。値が、キューに費やす時間は、障害発生率を関連付ける必要があります (エラー変わることがあります、キューの順序) およびデキュー レートがエンキュー率ではありません。</span><span class="sxs-lookup"><span data-stu-id="159ee-112">The best-effort first-in first-out ordering is provided for fairness; the time that an value spends in the queue should be related to the failure rate (failures may alter the queue's ordering) and the dequeue rate, but not the enqueue rate.</span></span>
            </para>
      <para>
        <span data-ttu-id="159ee-113"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />ただし、ピーク操作を提供しません結合して<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />と<see cref="M:Microsoft.ServiceFabric.Data.ITransaction.Abort" />同じセマンティクスを実現できます。</span><span class="sxs-lookup"><span data-stu-id="159ee-113"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> does not offer a Peek operation, however by combining <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> and <see cref="M:Microsoft.ServiceFabric.Data.ITransaction.Abort" /> the same semantic can be achieved.</span></span>  <span data-ttu-id="159ee-114">参照してください<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />追加の詳細と例です。</span><span class="sxs-lookup"><span data-stu-id="159ee-114">See <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> for additional details and an example.</span></span>
            </para>
      <para>
            <span data-ttu-id="159ee-115">このキューに格納されている値は、キューでの操作のコンテキスト外変換します。</span><span class="sxs-lookup"><span data-stu-id="159ee-115">Values stored in this queue MUST NOT be mutated outside the context of an operation on the queue.</span></span> <span data-ttu-id="159ee-116">強くお勧めする<typeparamref name="T" />偶発的なデータの破損を回避するために変更できません。</span><span class="sxs-lookup"><span data-stu-id="159ee-116">It is highly recommended to make <typeparamref name="T" /> immutable in order to avoid accidental data corruption.</span></span>
            </para>
      <para>
            <span data-ttu-id="159ee-117">トランザクションは、同時実行の単位: ユーザーは、時間の特定の時点インフライトの複数のトランザクションを持つことができますが、特定のトランザクションの各 API 呼び出す必要があります、一度に 1 つです。</span><span class="sxs-lookup"><span data-stu-id="159ee-117">Transaction is the unit of concurrency: Users can have multiple transactions in-flight at any given point of time but for a given transaction each API must be called one at a time.</span></span>
            <span data-ttu-id="159ee-118">すべての信頼性の高いコレクション Api をトランザクションでは、タスクを返すには、待機中の 1 つずつをする必要があります。</span><span class="sxs-lookup"><span data-stu-id="159ee-118">So all Reliable Collection APIs that take in a transaction and return a Task, must be awaited one at a time.</span></span>
            <seealso cref="T:Microsoft.ServiceFabric.Data.ITransaction" /></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public long Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Long" />
      <MemberSignature Language="F#" Value="member this.Count : int64" Usage="Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue&lt;'T&gt;.Count" />
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
          <para>
             <span data-ttu-id="159ee-119">値の数を取得、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />です。</span><span class="sxs-lookup"><span data-stu-id="159ee-119">Gets the number of values in the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />.</span></span>
             </para>
        </summary>
        <value><span data-ttu-id="159ee-120">値の数、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />です。</span><span class="sxs-lookup"><span data-stu-id="159ee-120">The number of values in  the <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />.</span></span></value>
        <remarks>
          <para>
             <span data-ttu-id="159ee-121">この数に現在表示されている値の数を表します<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />です。</span><span class="sxs-lookup"><span data-stu-id="159ee-121">This count represents the number of values currently visible to <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />.</span></span>  <span data-ttu-id="159ee-122">コミットされていないキューに登録でが、コミットされていない Dequeues はカウントを減らし、カウントは向上しません。</span><span class="sxs-lookup"><span data-stu-id="159ee-122">Uncommitted Enqueues will not increase the count, however uncommitted Dequeues will decrease the count.</span></span>
             </para>
          <para>
             <span data-ttu-id="159ee-123">この API は、トランザクション パラメーターを受け取らないに注意してください。</span><span class="sxs-lookup"><span data-stu-id="159ee-123">Note that this API does not take a transaction parameter.</span></span>  <span data-ttu-id="159ee-124">以降の効果<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />は他のトランザクションから分離されません、カウントすることもできません他のトランザクションから分離します。</span><span class="sxs-lookup"><span data-stu-id="159ee-124">Since the effects of <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> are not isolated from other transactions, the count also cannot be isolated from other transactions.</span></span>  
             </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException"><span data-ttu-id="159ee-125">レプリカを現在読み取れません。</span><span class="sxs-lookup"><span data-stu-id="159ee-125">The replica is currently not readable.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="159ee-126"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />ランタイムによって終了されました。</span><span class="sxs-lookup"><span data-stu-id="159ee-126">The <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> was closed by the runtime.</span></span></exception>
        <example>
             <span data-ttu-id="159ee-127">この例では、キャンセル トークンが取り消されるまで、無限、キューの数を監視する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="159ee-127">This example shows how to monitor the queue's count infinitely, until the cancellation token is canceled.</span></span>
             <code><![CDATA[
             protected override async Task RunAsync(CancellationToken cancellationToken)
             {
                 var concurrentQueue = await this.StateManager.GetOrAddAsync<IReliableConcurrentQueue<long>>(new Uri("fabric:/concurrentQueue"));
            
                 // Assumption: values are being enqueued/dequeued in another place (e.g. the communication listener).
                 var observer = Task.Run(
                     async () =>
                         {
                             while (true)
                             {
                                 cancellationToken.ThrowIfCancellationRequested();
            
                                 try
                                 {
                                     Console.WriteLine("Count: " + concurrentQueue.Count);
                                 }
                                 catch (FabricNotReadableException e)
                                 {
                                     // Retry until the queue is readable or a different exception is thrown.
                                     Console.WriteLine("Queue is not readable, retrying the observation: " + e);
                                 }
                                 catch (FabricObjectClosedException e)
                                 {
                                     // Gracefully exit as this is happening due to replica close.
                                     Console.WriteLine("Replica is closing, stopping observer: " + e);
                                     return;
                                 }
                                 
                                 await Task.Delay(TimeSpan.FromMilliseconds(100), cancellationToken);
                             }
                         },
                     cancellationToken);
             }
             ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="EnqueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnqueueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, T value, System.Threading.CancellationToken cancellationToken = null, Nullable&lt;TimeSpan&gt; timeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task EnqueueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !T value, valuetype System.Threading.CancellationToken cancellationToken, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="F#" Value="abstract member EnqueueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'T * System.Threading.CancellationToken * Nullable&lt;TimeSpan&gt; -&gt; System.Threading.Tasks.Task" Usage="iReliableConcurrentQueue.EnqueueAsync (tx, value, cancellationToken, timeout)" />
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
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="159ee-128">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="159ee-128">Transaction to associate this operation with.</span></span></param>
        <param name="value"><span data-ttu-id="159ee-129">キューの末尾に追加する値。</span><span class="sxs-lookup"><span data-stu-id="159ee-129">The value to add to the end of the queue.</span></span> <span data-ttu-id="159ee-130">参照型の場合は、値を null にできます。</span><span class="sxs-lookup"><span data-stu-id="159ee-130">The value can be null for reference types.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="159ee-131">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="159ee-131">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="159ee-132">既定では、 <see cref="P:System.Threading.CancellationToken.None" />です。</span><span class="sxs-lookup"><span data-stu-id="159ee-132">The default is <see cref="P:System.Threading.CancellationToken.None" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="159ee-133">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="159ee-133">The amount of time to wait for the operation to complete before throwing a TimeoutException.</span></span> <span data-ttu-id="159ee-134">既定値は null です。</span><span class="sxs-lookup"><span data-stu-id="159ee-134">The default is null.</span></span>  <span data-ttu-id="159ee-135">Null が渡された場合は、既定のタイムアウトが使用されます。</span><span class="sxs-lookup"><span data-stu-id="159ee-135">If null is passed, a default timeout will be used.</span></span></param>
        <summary>
          <para>
             <span data-ttu-id="159ee-136">ステージの値がキューにエンキューします。</span><span class="sxs-lookup"><span data-stu-id="159ee-136">Stage the enqueue of a value into the queue.</span></span>
             </para>
        </summary>
        <returns><span data-ttu-id="159ee-137">非同期のエンキュー操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="159ee-137">Task that represents the asynchronous enqueue operation.</span></span></returns>
        <remarks>
             <span data-ttu-id="159ee-138">A<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />操作は、対象の任意の値を返すことはできません、<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />まだコミットされていません。</span><span class="sxs-lookup"><span data-stu-id="159ee-138">A <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> operation cannot return any value for which its <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> has not yet been committed.</span></span>
             <span data-ttu-id="159ee-139">これで、値がエンキュー; トランザクションが含まれますその結果、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />読み取り、書き込みをサポートしていません。</span><span class="sxs-lookup"><span data-stu-id="159ee-139">This includes the transaction in which the value was enqueued; as a consequence, <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> does not support Read-Your-Writes.</span></span>
             </remarks>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="159ee-140">レプリカは不要になった<cref name="ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="159ee-140">The replica is no longer in <cref name="ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException"><span data-ttu-id="159ee-141">レプリカを現在読み取れません。</span><span class="sxs-lookup"><span data-stu-id="159ee-141">The replica is currently not readable.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="159ee-142"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />ランタイムによって終了されました。</span><span class="sxs-lookup"><span data-stu-id="159ee-142">The <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> was closed by the runtime.</span></span></exception>
        <exception cref="T:System.Fabric.FabricTransientException"><span data-ttu-id="159ee-143">レプリカは、一時的なエラーを説明しました。</span><span class="sxs-lookup"><span data-stu-id="159ee-143">The replica saw a transient failure.</span></span> <span data-ttu-id="159ee-144">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="159ee-144">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="159ee-145">レプリカは、上記で定義された型以外の非再試行可能エラーを説明しました。</span><span class="sxs-lookup"><span data-stu-id="159ee-145">The replica saw a non retriable failure other than the types defined above.</span></span> <span data-ttu-id="159ee-146">クリーンアップと rethrow 例外</span><span class="sxs-lookup"><span data-stu-id="159ee-146">Cleanup and rethrow the exception</span></span></exception>
        <exception cref="T:System.TimeoutException">
             <span data-ttu-id="159ee-147">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="159ee-147">The operation was unable to be completed within the given timeout.</span></span>  <span data-ttu-id="159ee-148">トランザクションを中止するかし、再試行する、新しいトランザクションを作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="159ee-148">The transaction should be aborted and a new transaction should be created to retry.</span></span>
             </exception>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="159ee-149"><paramref name="tx" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="159ee-149"><paramref name="tx" /> is null.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="159ee-150">使用して、操作が取り消されました<paramref name="cancellationToken" />です。</span><span class="sxs-lookup"><span data-stu-id="159ee-150">The operation was canceled via <paramref name="cancellationToken" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="159ee-151">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="159ee-151">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="159ee-152">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="159ee-152">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
             <span data-ttu-id="159ee-153">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="159ee-153">Thrown when a method call is invalid for the object's current state.</span></span>
             <span data-ttu-id="159ee-154">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="159ee-154">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
             <span data-ttu-id="159ee-155">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="159ee-155">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
             </exception>
        <example>
             <span data-ttu-id="159ee-156">この例を使用する方法を示しています。<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />エンキュー再試行の値にします。</span><span class="sxs-lookup"><span data-stu-id="159ee-156">This example shows how to use <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> to enqueue a value with retry.</span></span>
             <code><![CDATA[
             protected override async Task RunAsync(CancellationToken cancellationToken)
             {
                 var concurrentQueue = await this.StateManager.GetOrAddAsync<IReliableConcurrentQueue<long>>(new Uri("fabric:/concurrentQueue"));
            
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
                     catch (FabricTransientException e)
                     {
                         // Retry until the queue is writable or a different exception is thrown.
                         Console.WriteLine("Queue is currently not writable, retrying the transaction: " + e);
                     }
            
                     // Delay and retry.
                     await Task.Delay(TimeSpan.FromMilliseconds(100), cancellationToken);
                 }
             }
             ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="TryDequeueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryDequeueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, System.Threading.CancellationToken cancellationToken = null, Nullable&lt;TimeSpan&gt; timeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryDequeueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, valuetype System.Threading.CancellationToken cancellationToken, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="F#" Value="abstract member TryDequeueAsync : Microsoft.ServiceFabric.Data.ITransaction * System.Threading.CancellationToken * Nullable&lt;TimeSpan&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableConcurrentQueue.TryDequeueAsync (tx, cancellationToken, timeout)" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="tx"><span data-ttu-id="159ee-157">使用してこの操作を関連付けるトランザクションです。</span><span class="sxs-lookup"><span data-stu-id="159ee-157">Transaction to associate this operation with.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="159ee-158">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="159ee-158">The token to monitor for cancellation requests.</span></span> <span data-ttu-id="159ee-159">既定では、 <see cref="P:System.Threading.CancellationToken.None" />です。</span><span class="sxs-lookup"><span data-stu-id="159ee-159">The default is <see cref="P:System.Threading.CancellationToken.None" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="159ee-160">操作が完了するまで待機する時間の量。</span><span class="sxs-lookup"><span data-stu-id="159ee-160">The amount of time to wait for the operation to complete.</span></span> <span data-ttu-id="159ee-161">既定値は null です。</span><span class="sxs-lookup"><span data-stu-id="159ee-161">The default is null.</span></span>  <span data-ttu-id="159ee-162">Null が渡された場合は、既定のタイムアウトが使用されます。</span><span class="sxs-lookup"><span data-stu-id="159ee-162">If null is passed, a default timeout will be used.</span></span></param>
        <summary>
          <para>
            <span data-ttu-id="159ee-163">仮キューからの値をデキューします。</span><span class="sxs-lookup"><span data-stu-id="159ee-163">Tentatively dequeue a value from the queue.</span></span> <span data-ttu-id="159ee-164">キューが空の場合は、使用可能になるアイテム dequeue 操作は待機します。</span><span class="sxs-lookup"><span data-stu-id="159ee-164">If the queue is empty, the dequeue operation will wait for an item to become available.</span></span>
            </para>
        </summary>
        <returns>
            <span data-ttu-id="159ee-165">表す非同期のタスクには、操作がキューから削除します。</span><span class="sxs-lookup"><span data-stu-id="159ee-165">A task that represents the asynchronous dequeue operation.</span></span> <span data-ttu-id="159ee-166">タスクの結果は T 型の ConditionalValue場合は、値は、許容時間内デキューされました、返す、ConditionalValue false として HasValue、それ以外の場合、返さ true として HasValue と型 T のキューから取り出されたアイテムとして値を持つ ConditionalValue</span><span class="sxs-lookup"><span data-stu-id="159ee-166">The task's result is a ConditionalValue of type T. If a value was dequeued within the given time, return a ConditionalValue with HasValue as false, else it returns a ConditionalValue with HasValue as true and the Value as the dequeued item of Type T</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="159ee-167">中に<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />対象の値を返すことができますのみ、対応する<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />コミットされ、<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />操作が互いから分離されていません。</span><span class="sxs-lookup"><span data-stu-id="159ee-167">While <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> can only return values for which the corresponding <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> was committed, <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> operations are not isolated from one another.</span></span>  <span data-ttu-id="159ee-168">トランザクションには、値がデキュー、他のトランザクション、キューから削除できませんがその他の値をキューからブロックされていません。</span><span class="sxs-lookup"><span data-stu-id="159ee-168">Once a transaction has dequeued a value, other transactions cannot dequeue it, but are not blocked from dequeuing other values.</span></span>
            </para>
          <para>
            <span data-ttu-id="159ee-169">ときに、トランザクション、または 1 つまたは複数を含むトランザクション<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />操作が中止されて、デキューされる値を任意の順序でキューの先頭に追加されます。</span><span class="sxs-lookup"><span data-stu-id="159ee-169">When a transaction or transactions including one or more <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> operations aborts, the dequeued values will be added back at the head of the queue in an arbitrary order.</span></span>  <span data-ttu-id="159ee-170">これにより、これらの値がデキューのため、すぐに再度厳密順序を適用することがなく、データ構造の公平性を向上させるよう (で許可される同時実行を減らすことが必要<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />)。</span><span class="sxs-lookup"><span data-stu-id="159ee-170">This will ensure that these values will be dequeued again soon, improving the fairness of the data structure, but without enforcing strict ordering (which would require reducing the allowed concurrency, as in <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />).</span></span>
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotPrimaryException"><span data-ttu-id="159ee-171">レプリカは不要になった<cref name="ReplicaRole.Primary" />です。</span><span class="sxs-lookup"><span data-stu-id="159ee-171">The replica is no longer in <cref name="ReplicaRole.Primary" />.</span></span></exception>
        <exception cref="T:System.Fabric.FabricNotReadableException"><span data-ttu-id="159ee-172">レプリカを現在読み取れません。</span><span class="sxs-lookup"><span data-stu-id="159ee-172">The replica is currently not readable.</span></span></exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><span data-ttu-id="159ee-173"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />ランタイムによって終了されました。</span><span class="sxs-lookup"><span data-stu-id="159ee-173">The <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" /> was closed by the runtime.</span></span></exception>
        <exception cref="T:System.Fabric.FabricTransientException"><span data-ttu-id="159ee-174">レプリカは、一時的なエラーを説明しました。</span><span class="sxs-lookup"><span data-stu-id="159ee-174">The replica saw a transient failure.</span></span> <span data-ttu-id="159ee-175">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="159ee-175">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="159ee-176">レプリカは、上記で定義された型以外の非再試行可能エラーを説明しました。</span><span class="sxs-lookup"><span data-stu-id="159ee-176">The replica saw a non retriable failure other than the types defined above.</span></span> <span data-ttu-id="159ee-177">クリーンアップと rethrow 例外</span><span class="sxs-lookup"><span data-stu-id="159ee-177">Cleanup and rethrow the exception</span></span></exception>
        <exception cref="T:System.TimeoutException">
            <span data-ttu-id="159ee-178">操作は、指定したタイムアウト時間内に完了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="159ee-178">The operation was unable to be completed within the given timeout.</span></span>  <span data-ttu-id="159ee-179">トランザクションを中止するかし、再試行する、新しいトランザクションを作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="159ee-179">The transaction should be aborted and a new transaction should be created to retry.</span></span>
            </exception>
        <exception cref="T:System.ArgumentNullException">
          <span data-ttu-id="159ee-180"><paramref name="tx" /> が null です。</span><span class="sxs-lookup"><span data-stu-id="159ee-180"><paramref name="tx" /> is null.</span></span> <span data-ttu-id="159ee-181">この例外を処理しません。</span><span class="sxs-lookup"><span data-stu-id="159ee-181">Do not handle this exception.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="159ee-182">使用して、操作が取り消されました<paramref name="cancellationToken" />です。</span><span class="sxs-lookup"><span data-stu-id="159ee-182">The operation was canceled via <paramref name="cancellationToken" />.</span></span></exception>
        <exception cref="T:System.Fabric.TransactionFaultedException"><span data-ttu-id="159ee-183">トランザクションは、システムによって内部で途中終了されました。</span><span class="sxs-lookup"><span data-stu-id="159ee-183">The transaction has been internally faulted by the system.</span></span> <span data-ttu-id="159ee-184">新しいトランザクションで操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="159ee-184">Retry the operation on a new transaction</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="159ee-185">メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="159ee-185">Thrown when a method call is invalid for the object's current state.</span></span>
            <span data-ttu-id="159ee-186">例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。</span><span class="sxs-lookup"><span data-stu-id="159ee-186">Example, transaction used is already terminated: committed or aborted by the user.</span></span>
            <span data-ttu-id="159ee-187">この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。</span><span class="sxs-lookup"><span data-stu-id="159ee-187">If this exception is thrown, it is highly likely that there is a bug in the service code of the use of transactions.</span></span>
            </exception>
        <example>
            <span data-ttu-id="159ee-188">この例では、デキューし、キャンセル トークンが取り消されるまで、再試行で無限にログインする方法を示します。</span><span class="sxs-lookup"><span data-stu-id="159ee-188">This example shows how to dequeue and log infinitely with retry, until the cancellation token is canceled.</span></span>  
            <code><![CDATA[
            protected override async Task RunAsync(CancellationToken cancellationToken)
            {
                var concurrentQueue = await this.StateManager.GetOrAddAsync<IReliableConcurrentQueue<long>>(new Uri("fabric:/concurrentQueue"));
            
                // Assumption: values are being enqueued by another source (e.g. the communication listener).
                while (true)
                {
                    cancellationToken.ThrowIfCancellationRequested();
            
                    try
                    {
                        using (var tx = this.StateManager.CreateTransaction())
                        {
                            var dequeueOutput = await concurrentQueue.TryDequeueAsync(tx, cancellationToken, TimeSpan.FromMilliseconds(100));
                            await tx.CommitAsync();
            
                            if (dequeueOutput.HasValue)
                            {
                                Console.WriteLine("Dequeue # " + dequeueOutput);
                            }
                            else
                            {
                                Console.WriteLine("Could not dequeue in the given time");
                            }
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
                        // If instead dequeue was being executed as part of a client request, the client would be signaled to re-resolve.
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
                        // If instead dequeue was being executed as part of a client request, the client would be signaled to re-resolve.
                        Console.WriteLine("Replica is closing, exiting RunAsync: " + e);
                        return;
                    }
                    catch (TimeoutException e)
                    {
                        Console.WriteLine("Encountered TimeoutException during DequeueAsync, retrying the transaction: " + e);
                    }
                    catch (FabricTransientException e)
                    {
                        // Retry until the queue is writable or a different exception is thrown.
                        Console.WriteLine("Queue is currently not writable, retrying the transaction: " + e);
                    }
            
                    // Delay and retry.
                    await Task.Delay(TimeSpan.FromMilliseconds(100), cancellationToken);
                }
            }
            ]]></code></example>
      </Docs>
    </Member>
  </Members>
</Type>