<Type Name="IStateReplicator" FullName="System.Fabric.IStateReplicator">
  <TypeSignature Language="C#" Value="public interface IStateReplicator" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStateReplicator" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStateReplicator" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStateReplicator" />
  <TypeSignature Language="F#" Value="type IStateReplicator = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="d750e-101">レプリケーションに関連する関数を公開、<see cref="T:System.Fabric.FabricReplicator" />クラスによって使用されている<see cref="T:System.Fabric.IStateProvider" />を高可用性を保証する状態をレプリケートします。</span><span class="sxs-lookup"><span data-stu-id="d750e-101">Exposes replication-related functions of the <see cref="T:System.Fabric.FabricReplicator" /> class that are used by <see cref="T:System.Fabric.IStateProvider" /> to replicate state to ensure high availability.</span></span> </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetCopyStream">
      <MemberSignature Language="C#" Value="public System.Fabric.IOperationStream GetCopyStream ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IOperationStream GetCopyStream() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateReplicator.GetCopyStream" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCopyStream () As IOperationStream" />
      <MemberSignature Language="F#" Value="abstract member GetCopyStream : unit -&gt; System.Fabric.IOperationStream" Usage="iStateReplicator.GetCopyStream " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationStream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="d750e-102">取得では、ストリームをコピーします。</span><span class="sxs-lookup"><span data-stu-id="d750e-102">Gets copy stream.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="d750e-103">コピーを返します<see cref="T:System.Fabric.IOperationStream" />です。</span><span class="sxs-lookup"><span data-stu-id="d750e-103">Returns the copy <see cref="T:System.Fabric.IOperationStream" />.</span></span> </para>
        </returns>
        <remarks>
          <para><span data-ttu-id="d750e-104">返された CopyStream、<see cref="T:System.Fabric.IOperationStream" />を格納している<see cref="T:System.Fabric.OperationData" />を実装するオブジェクト<see cref="T:System.Fabric.IOperation" />です。</span><span class="sxs-lookup"><span data-stu-id="d750e-104">The returned CopyStream is an <see cref="T:System.Fabric.IOperationStream" /> that contains <see cref="T:System.Fabric.OperationData" /> objects that implement <see cref="T:System.Fabric.IOperation" />.</span></span> <span data-ttu-id="d750e-105"><see cref="T:System.Fabric.OperationData" />オブジェクトが、CopyState から取得した<see cref="T:System.Fabric.IOperationDataStream" />から、プライマリ レプリカを返す<see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />です。</span><span class="sxs-lookup"><span data-stu-id="d750e-105">The <see cref="T:System.Fabric.OperationData" /> objects are obtained from the CopyState <see cref="T:System.Fabric.IOperationDataStream" /> that the Primary replica returns from <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />.</span></span> <span data-ttu-id="d750e-106">レプリカが作成され、遅延を解消するのには、する必要があります、CopyStream を取得し、送信、適用、および承認を実装するオブジェクトのコピーを開始<see cref="T:System.Fabric.IOperation" />です。</span><span class="sxs-lookup"><span data-stu-id="d750e-106">When a replica is created and has to catch up, it should obtain the CopyStream and begin to send, apply, and acknowledge the Copy objects that implement <see cref="T:System.Fabric.IOperation" />.</span></span> <span data-ttu-id="d750e-107">並行して、レプリカは、対応する応答<see cref="M:System.Fabric.IStateProvider.GetCopyContext" />と<see cref="M:System.Fabric.IOperationDataStream.GetNextAsync(System.Threading.CancellationToken)" />呼び出しです。</span><span class="sxs-lookup"><span data-stu-id="d750e-107">In parallel, the replica responds to the corresponding <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> and <see cref="M:System.Fabric.IOperationDataStream.GetNextAsync(System.Threading.CancellationToken)" /> calls.</span></span> <span data-ttu-id="d750e-108">ストリームが空ときに、返された<see cref="T:System.Fabric.IOperation" />メソッドは null です。</span><span class="sxs-lookup"><span data-stu-id="d750e-108">The stream is empty when the returned <see cref="T:System.Fabric.IOperation" /> method is null.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="d750e-109"><see cref="T:System.Fabric.FabricTransientException" />再試行可能な例外です。</span><span class="sxs-lookup"><span data-stu-id="d750e-109"><see cref="T:System.Fabric.FabricTransientException" /> is a retriable exception.</span></span> <span data-ttu-id="d750e-110">次のいずれかが原因</span><span class="sxs-lookup"><span data-stu-id="d750e-110">It is caused by one of the following;</span></span></para>
          <para>
            <span data-ttu-id="d750e-111"><see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" />レプリケーターが保留中の再構成が返されます。</span><span class="sxs-lookup"><span data-stu-id="d750e-111"><see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" /> is returned when the replicator has a pending reconfiguration.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
            <span data-ttu-id="d750e-112"><see cref="T:System.Fabric.FabricObjectClosedException" />次のいずれかが原因は、</span><span class="sxs-lookup"><span data-stu-id="d750e-112"><see cref="T:System.Fabric.FabricObjectClosedException" /> is caused by one of the following;</span></span></para>
          <para>
            <span data-ttu-id="d750e-113"><see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" />レプリケーターが終了した場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="d750e-113"><see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" /> is returned when the replicator has been closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicationStream">
      <MemberSignature Language="C#" Value="public System.Fabric.IOperationStream GetReplicationStream ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IOperationStream GetReplicationStream() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateReplicator.GetReplicationStream" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicationStream () As IOperationStream" />
      <MemberSignature Language="F#" Value="abstract member GetReplicationStream : unit -&gt; System.Fabric.IOperationStream" Usage="iStateReplicator.GetReplicationStream " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationStream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="d750e-114">レプリケーション ストリームを取得します。</span><span class="sxs-lookup"><span data-stu-id="d750e-114">Gets replication stream.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="d750e-115">複製を返します<see cref="T:System.Fabric.IOperationStream" />です。</span><span class="sxs-lookup"><span data-stu-id="d750e-115">Returns the replication <see cref="T:System.Fabric.IOperationStream" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="d750e-116">ReplicationStream 実装<see cref="T:System.Fabric.IOperationStream" />です。</span><span class="sxs-lookup"><span data-stu-id="d750e-116">The ReplicationStream implements <see cref="T:System.Fabric.IOperationStream" />.</span></span> <span data-ttu-id="d750e-117">含まれています、ReplicationStream<see cref="T:System.Fabric.OperationData" />を実装するオブジェクト<see cref="T:System.Fabric.IOperation" />です。</span><span class="sxs-lookup"><span data-stu-id="d750e-117">The ReplicationStream contains <see cref="T:System.Fabric.OperationData" /> objects that implement <see cref="T:System.Fabric.IOperation" />.</span></span> <span data-ttu-id="d750e-118">オブジェクトが経由でプライマリ レプリカによって提供される<see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />です。</span><span class="sxs-lookup"><span data-stu-id="d750e-118">The objects are provided by the Primary replica via <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />.</span></span> <span data-ttu-id="d750e-119">一般に、セカンダリ レプリカを送信する必要があります<see cref="M:System.Fabric.IOperationStream.GetOperationAsync(System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d750e-119">Generally a Secondary replica should send <see cref="M:System.Fabric.IOperationStream.GetOperationAsync(System.Threading.CancellationToken)" />.</span></span> <span data-ttu-id="d750e-120">Service Fabric では、これを行うサービスは必要ありません、一般にサービスがすべて転送<see cref="T:System.Fabric.OperationData" />コピーからオブジェクトが最初に、ストリームし、レプリケーション ストリームからの操作を転送します。</span><span class="sxs-lookup"><span data-stu-id="d750e-120">Although Service Fabric does not require services to do so, generally services should transfer all <see cref="T:System.Fabric.OperationData" /> objects out of the copy stream first, and then transfer operations out of the replication stream.</span></span> <span data-ttu-id="d750e-121">同時に両方のコピーからの転送がサポートされていますが、増加状態を適用する際の複雑さは正しく更新し、高度なサービスにのみ推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d750e-121">The transfer from both copies in parallel is supported but increases the complexity of applying state updates correctly and is recommended only for advanced services.</span></span> <span data-ttu-id="d750e-122">ストリームが空ときに、返された<see cref="T:System.Fabric.IOperation" />メソッドは null です。</span><span class="sxs-lookup"><span data-stu-id="d750e-122">The stream is empty when the returned <see cref="T:System.Fabric.IOperation" /> method is null.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="d750e-123"><see cref="T:System.Fabric.FabricTransientException" />再試行可能な例外です。</span><span class="sxs-lookup"><span data-stu-id="d750e-123"><see cref="T:System.Fabric.FabricTransientException" /> is a retriable exception.</span></span> <span data-ttu-id="d750e-124">次のいずれかが原因</span><span class="sxs-lookup"><span data-stu-id="d750e-124">It is caused by one of the following;</span></span></para>
          <para>
            <span data-ttu-id="d750e-125"><see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" />レプリケーターが保留中の再構成が返されます。</span><span class="sxs-lookup"><span data-stu-id="d750e-125"><see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" /> is returned when the replicator has a pending reconfiguration.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
            <span data-ttu-id="d750e-126"><see cref="T:System.Fabric.FabricObjectClosedException" />次のいずれかが原因は、</span><span class="sxs-lookup"><span data-stu-id="d750e-126"><see cref="T:System.Fabric.FabricObjectClosedException" /> is caused by one of the following;</span></span></para>
          <para>
            <span data-ttu-id="d750e-127"><see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" />レプリケーターが終了した場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="d750e-127"><see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" /> is returned when the replicator has been closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReplicateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ReplicateAsync (System.Fabric.OperationData operationData, System.Threading.CancellationToken cancellationToken, out long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ReplicateAsync(class System.Fabric.OperationData operationData, valuetype System.Threading.CancellationToken cancellationToken, [out] int64&amp; sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />
      <MemberSignature Language="F#" Value="abstract member ReplicateAsync : System.Fabric.OperationData * System.Threading.CancellationToken *  -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iStateReplicator.ReplicateAsync (operationData, cancellationToken, sequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", Justification="Approved public API.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationData" Type="System.Fabric.OperationData" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="sequenceNumber" Type="System.Int64&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="operationData">
          <para><span data-ttu-id="d750e-128"><see cref="T:System.Fabric.OperationData" />プライマリ レプリカは、レプリケートする必要がある状態の変更を表すです。</span><span class="sxs-lookup"><span data-stu-id="d750e-128">The <see cref="T:System.Fabric.OperationData" /> that represents the state change that the Primary replica wants to replicate.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para> <span data-ttu-id="d750e-129">失われているレプリカの書き込みクォーラムです。</span><span class="sxs-lookup"><span data-stu-id="d750e-129">A write quorum of replicas that have been lost.</span></span> <span data-ttu-id="d750e-130">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="d750e-130">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="d750e-131">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="d750e-131">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <param name="sequenceNumber">
          <para><span data-ttu-id="d750e-132">Long、操作の LSN です。</span><span class="sxs-lookup"><span data-stu-id="d750e-132">Long, the LSN of the operation.</span></span> <span data-ttu-id="d750e-133">これは、タスクによって返される同じ値であることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="d750e-133">Note that this is the same value which is returned by the task.</span></span> <span data-ttu-id="d750e-134">Out パラメーターとして指定することは、ローカル記録するには、タスクが終了する場合はコミットの準備をするサービスに便利です。</span><span class="sxs-lookup"><span data-stu-id="d750e-134">Providing it as an out parameter is useful for services which want to prepare the local write to commit when the task finishes.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="d750e-135">セカンダリ レプリカにプライマリ レプリカから状態の変更をレプリケートし、それらの状態の変更が適用されているクォーラムの受信確認を受信します。</span><span class="sxs-lookup"><span data-stu-id="d750e-135">Replicates state changes from Primary replica to the Secondary replicas and receives a quorum acknowledgement that those state changes have been applied.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="d750e-136">返します<see cref="T:System.Threading.Tasks.Task`1" />long 型で、操作の LSN。</span><span class="sxs-lookup"><span data-stu-id="d750e-136">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type long, the LSN of the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="d750e-137">プライマリ レプリカでレプリケーションを実装するオブジェクトを生成する<see cref="T:System.Fabric.IOperation" />経由でレプリケーション ストリームから、セカンダリ レプリカを取得する<see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />が続きます<see cref="M:System.Fabric.IOperationStream.GetOperationAsync(System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="d750e-137">Replication at the Primary replica produces the objects that implement <see cref="T:System.Fabric.IOperation" /> that the Secondary replica obtains from the Replication Stream via <see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />, which is followed by <see cref="M:System.Fabric.IOperationStream.GetOperationAsync(System.Threading.CancellationToken)" />.</span></span> </para>
          <para><span data-ttu-id="d750e-138">プライマリ レプリカでは、状態の更新の処理に関連する多くの職務にします。</span><span class="sxs-lookup"><span data-stu-id="d750e-138">The Primary replica has many duties that are related to process state updates.</span></span> <span data-ttu-id="d750e-139">次の手順では、プライマリ レプリカがレプリケートされ、変更の確認に扱う必要があるイベントの全般的な順序を示します。</span><span class="sxs-lookup"><span data-stu-id="d750e-139">The following steps show the general sequence of events that a Primary replica must handle to replicate and acknowledge a change.</span></span> </para>
          <para><span data-ttu-id="d750e-140">パート 1: 着信要求の処理: 要求を受け取る: Write(x) – サービスが書き込み要求を受信する x。</span><span class="sxs-lookup"><span data-stu-id="d750e-140">Part 1: Handling incoming requests: Receive request: Write(x) – Service receives a write request, x.</span></span> <span data-ttu-id="d750e-141">CheckArguments –、サービスは、要求の引数をチェックします。</span><span class="sxs-lookup"><span data-stu-id="d750e-141">CheckArguments – The service checks the arguments of the request.</span></span> <span data-ttu-id="d750e-142">このチェックは、サービスの状態の一貫性を確保に役立ちます。</span><span class="sxs-lookup"><span data-stu-id="d750e-142">This check helps ensure the consistency of the service’s state.</span></span></para>
          <para><span data-ttu-id="d750e-143">現在の状態チェック – サービスは、操作が有効ではし、できますか、またはを実行するかを現在の状態を調べます。</span><span class="sxs-lookup"><span data-stu-id="d750e-143">Check current state – The service examines its current state to ensure that the operation is valid and can or should be performed.</span></span> <span data-ttu-id="d750e-144">このチェックでは、データの一貫性を確保できます。</span><span class="sxs-lookup"><span data-stu-id="d750e-144">This check also helps ensure data consistency.</span></span> <span data-ttu-id="d750e-145">サービス コードによって実行されます。</span><span class="sxs-lookup"><span data-stu-id="d750e-145">It is performed by the service code.</span></span></para>
          <para><span data-ttu-id="d750e-146">ロックの取得: サービスが同時に発生してから追加の操作を防ぐために必要なロックを取得する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d750e-146">Acquire Locks – The service should acquire the necessary locks to prevent additional operations from occurring at the same time.</span></span> <span data-ttu-id="d750e-147">この操作により、分離と一貫性を確保します。</span><span class="sxs-lookup"><span data-stu-id="d750e-147">This operation helps ensure isolation and consistency.</span></span></para>
          <para><span data-ttu-id="d750e-148">試行操作 (省略可能) – サービスがローカルで操作を試みることができます。</span><span class="sxs-lookup"><span data-stu-id="d750e-148">Attempt Operation (optional) – The service can attempt the operation locally.</span></span> <span data-ttu-id="d750e-149">この手順は、予約し領域の割り当てし、必要なすべての計算を実行します。</span><span class="sxs-lookup"><span data-stu-id="d750e-149">This step reserves and allocates space and performs all the necessary computations.</span></span> <span data-ttu-id="d750e-150">この手順では、結果の実際のコミットがすべて含まれています。</span><span class="sxs-lookup"><span data-stu-id="d750e-150">This step includes everything but the actual commit of the result.</span></span> <span data-ttu-id="d750e-151">この操作は、操作の持続性が向上し、以降の障害は非常に珍しい、します。</span><span class="sxs-lookup"><span data-stu-id="d750e-151">This operation improves the durability of the operation and makes later failures very unlikely.</span></span></para>
          <para><span data-ttu-id="d750e-152">OperationData – を製造、<see cref="T:System.Fabric.OperationData" />オブジェクトは、サービスに提示された Write(x) の表現。</span><span class="sxs-lookup"><span data-stu-id="d750e-152">Manufacture the OperationData – An <see cref="T:System.Fabric.OperationData" /> object is the representation of the Write(x) that was presented to the service.</span></span> <span data-ttu-id="d750e-153"><see cref="T:System.Fabric.OperationData" />オブジェクトには、セカンダリ レプリカにプライマリ レプリカから受信確認で転送する状態の変更が含まれています。</span><span class="sxs-lookup"><span data-stu-id="d750e-153">The <see cref="T:System.Fabric.OperationData" /> object contains the state change to be transferred with acknowledgement from the Primary replica to the Secondary replicas.</span></span> <span data-ttu-id="d750e-154">OperationData にサービスを挿入するデータを分割不可能な定義を更新、<see cref="T:System.Fabric.FabricReplicator" />のセカンダリ レプリカに転送します。</span><span class="sxs-lookup"><span data-stu-id="d750e-154">The data that the service places in the OperationData defines the atomic update that the <see cref="T:System.Fabric.FabricReplicator" /> transfers to the Secondary replicas.</span></span> <span data-ttu-id="d750e-155">作成することに注意してください、<see cref="T:System.Fabric.OperationData" />オブジェクトには、1 つまたは複数のバイト配列が必要です。</span><span class="sxs-lookup"><span data-stu-id="d750e-155">Note that creating of the <see cref="T:System.Fabric.OperationData" /> object requires one or more byte arrays.</span></span> <span data-ttu-id="d750e-156">決定自体と、状態の変化をシリアル化を介して FabricReplicator にこのバイト数のセットを提供する必要がありますサービス<see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />です。</span><span class="sxs-lookup"><span data-stu-id="d750e-156">The service must itself determine and serialize the change in state, and then provide this set of bytes to the FabricReplicator via <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />.</span></span> <span data-ttu-id="d750e-157">サービスでは、FabricReplicator に、操作を送信し、戻り値論理のシーケンス番号 (LSN) を受け取ります。</span><span class="sxs-lookup"><span data-stu-id="d750e-157">The service sends the operation to the FabricReplicator and receives a logical sequence number (LSN) in return.</span></span> <span data-ttu-id="d750e-158">LSN は、操作の id は、し、サービスと操作がすべての場所で同じ順序で常に適用されるように Service Fabric の両方を支援します。サービスは、インフライト操作の順序付きリストで、LSN と共に OperationData を記録する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d750e-158">The LSN is the identity for the operation and helps both the service and Service Fabric ensure that operations are always applied in the same order everywhere.The service should record the OperationData along with its LSN in an ordered list of in-flight operations.</span></span> <span data-ttu-id="d750e-159">これにより、操作が完了したら、一貫して適用できますが正しい順序で。</span><span class="sxs-lookup"><span data-stu-id="d750e-159">This ensures that when the operations are completed, they can be consistently applied in the correct order.</span></span></para>
          <para><span data-ttu-id="d750e-160">ロックを解除 - 処理または以降の要求の待機を続行します。</span><span class="sxs-lookup"><span data-stu-id="d750e-160">Release Locks - Continue processing or waiting for further requests.</span></span></para>
          <para><span data-ttu-id="d750e-161">パート 2: 要求を完了して、応答: プライマリ レプリカは、操作が適用されたことを示すコールバックを受信します。</span><span class="sxs-lookup"><span data-stu-id="d750e-161">Part 2: Completing requests and responding: The Primary replica receives a callback that indicates that the operation has been applied.</span></span> <span data-ttu-id="d750e-162">ReplicateAsync は完了です。</span><span class="sxs-lookup"><span data-stu-id="d750e-162">ReplicateAsync is completed.</span></span> <span data-ttu-id="d750e-163">このコールバックは、レプリカ セット内のレプリカのクォーラムによる操作が確認されていることを示します。</span><span class="sxs-lookup"><span data-stu-id="d750e-163">This callback indicates that the operation has been acknowledged by a quorum of the replicas in the replica set.</span></span> <span data-ttu-id="d750e-164">プライマリ レプリカがこのコールバックを受信すると、次の操作を実行にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="d750e-164">When the Primary replica receives this callback, it should perform the following actions:</span></span> </para>
          <para><span data-ttu-id="d750e-165">サービスのインフライトの一覧で ReplicateAsync から返される長い LSN で示されている、対応する操作を見つけて「QuorumAck は」としてマークします。</span><span class="sxs-lookup"><span data-stu-id="d750e-165">Find the corresponding operation that is indicated by the long LSN that is returned from ReplicateAsync in the service’s in-flight list and mark it as "QuorumAck’d".</span></span> </para>
          <para><span data-ttu-id="d750e-166">ここで、インフライトの一覧の最初の操作から開始して、移動、リストをローカル コミット操作で、[完了] に指定された受信者、QuorumAck のすべてのローカル状態と、対応する LSN の状態が変更された最初の不完全な操作になるまでマークに変更発生しました。</span><span class="sxs-lookup"><span data-stu-id="d750e-166">Now, starting at the first operation in the in-flight list, go through the list and locally commit all of the QuorumAck’d operations, finish any changes to the local state and mark the state changes with their corresponding LSN, until the first incomplete operation is encountered.</span></span> <span data-ttu-id="d750e-167">これにより、順序が保持されている (一貫性) とする操作が実際に適用されています。</span><span class="sxs-lookup"><span data-stu-id="d750e-167">This ensures that ordering is preserved (consistency) and that the operations are actually applied.</span></span> <span data-ttu-id="d750e-168">これは、以前の持続性と分離の準備の活用します。</span><span class="sxs-lookup"><span data-stu-id="d750e-168">This takes advantage of the previous durability and isolation preparations.</span></span> <span data-ttu-id="d750e-169">注: ほとんどのサービスは、そのためこの最後のコミット LSN 値をキャッシュするのには、その応答、<see cref="M:System.Fabric.IStateProvider.GetLastCommittedSequenceNumber" />最大 LSN のため、実際のストアのクエリは不要です。</span><span class="sxs-lookup"><span data-stu-id="d750e-169">Note: Most services should cache the last committed LSN value so that responses to the <see cref="M:System.Fabric.IStateProvider.GetLastCommittedSequenceNumber" /> do not require querying the actual store for the greatest LSN.</span></span> </para>
          <para><span data-ttu-id="d750e-170">操作は、プライマリ レプリカに正常にコミットされたときに、プライマリ レプリカことができますようになりました呼び出しを開始したクライアントに返信して、インフライトの一覧から、操作を削除します。</span><span class="sxs-lookup"><span data-stu-id="d750e-170">When an operation is successfully committed at the Primary replica, the Primary replica can now reply to the client that initiated the call and remove the operation from the in-flight list.</span></span> <span data-ttu-id="d750e-171">[次へ] の受信確認のクォーラム コールバックの待機を続行します。</span><span class="sxs-lookup"><span data-stu-id="d750e-171">Continue to wait for the next quorum-acknowledgment callback.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="d750e-172">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="d750e-172">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="d750e-173">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="d750e-173">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="d750e-174"><see cref="T:System.Fabric.FabricTransientException" />再試行可能な例外です。</span><span class="sxs-lookup"><span data-stu-id="d750e-174"><see cref="T:System.Fabric.FabricTransientException" /> is a retriable exception.</span></span> <span data-ttu-id="d750e-175">次のいずれかが原因</span><span class="sxs-lookup"><span data-stu-id="d750e-175">It is caused by one of the following;</span></span></para>
          <para>
            <span data-ttu-id="d750e-176"><see cref="F:System.Fabric.FabricErrorCode.NoWriteQuorum" />レプリケーターが書き込みクォーラムを現在持っていない場合が返されます.</span><span class="sxs-lookup"><span data-stu-id="d750e-176"><see cref="F:System.Fabric.FabricErrorCode.NoWriteQuorum" /> is returned when the replicator does not currently have write quorum..</span></span></para>
          <para>
            <span data-ttu-id="d750e-177"><see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" />レプリケーターが保留中の再構成が返されます。</span><span class="sxs-lookup"><span data-stu-id="d750e-177"><see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" /> is returned when the replicator has a pending reconfiguration.</span></span></para>
          <para>
            <span data-ttu-id="d750e-178"><see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" />レプリケーター キューがいっぱいになったときに返されます。</span><span class="sxs-lookup"><span data-stu-id="d750e-178"><see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" /> is returned when the replicator queue is full.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">
          <para>
            <span data-ttu-id="d750e-179"><see cref="T:System.Fabric.FabricNotPrimaryException" />次のいずれかが原因は、</span><span class="sxs-lookup"><span data-stu-id="d750e-179"><see cref="T:System.Fabric.FabricNotPrimaryException" /> is caused by one of the following;</span></span></para>
          <para>
            <span data-ttu-id="d750e-180"><see cref="F:System.Fabric.FabricErrorCode.NotPrimary" />レプリケーターが保留中の再構成が返されます。</span><span class="sxs-lookup"><span data-stu-id="d750e-180"><see cref="F:System.Fabric.FabricErrorCode.NotPrimary" /> is returned when the replicator has a pending reconfiguration.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
            <span data-ttu-id="d750e-181"><see cref="T:System.Fabric.FabricObjectClosedException" />次のいずれかが原因は、</span><span class="sxs-lookup"><span data-stu-id="d750e-181"><see cref="T:System.Fabric.FabricObjectClosedException" /> is caused by one of the following;</span></span></para>
          <para>
            <span data-ttu-id="d750e-182"><see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" />レプリケーターが終了した場合に返されます。</span><span class="sxs-lookup"><span data-stu-id="d750e-182"><see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" /> is returned when the replicator has been closed.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>
            <span data-ttu-id="d750e-183"><see cref="T:System.OperationCanceledException" />次のいずれかが原因は、</span><span class="sxs-lookup"><span data-stu-id="d750e-183"><see cref="T:System.OperationCanceledException" /> is caused by one of the following;</span></span></para>
          <para><span data-ttu-id="d750e-184">E_ABORT レプリケーターが転送レプリケーション操作をキャンセルするとします。</span><span class="sxs-lookup"><span data-stu-id="d750e-184">E_ABORT when replicator cancels an inflight replication operation.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateReplicatorSettings">
      <MemberSignature Language="C#" Value="public void UpdateReplicatorSettings (System.Fabric.ReplicatorSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UpdateReplicatorSettings(class System.Fabric.ReplicatorSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateReplicator.UpdateReplicatorSettings(System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateReplicatorSettings (settings As ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="abstract member UpdateReplicatorSettings : System.Fabric.ReplicatorSettings -&gt; unit" Usage="iStateReplicator.UpdateReplicatorSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para><span data-ttu-id="d750e-185">新しい<see cref="T:System.Fabric.ReplicatorSettings" />更新された資格情報を使用します。</span><span class="sxs-lookup"><span data-stu-id="d750e-185">The new <see cref="T:System.Fabric.ReplicatorSettings" /> with the updated credentials.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="d750e-186">実行時に複製物作成会社設定の変更を有効にします。</span><span class="sxs-lookup"><span data-stu-id="d750e-186">Enables modification of replicator settings during runtime.</span></span> <span data-ttu-id="d750e-187">変更できる唯一の設定は、セキュリティ資格情報です。</span><span class="sxs-lookup"><span data-stu-id="d750e-187">The only setting which can be modified is the security credentials.</span></span> </para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="d750e-188">次のいずれかによって発生します。</span><span class="sxs-lookup"><span data-stu-id="d750e-188">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="d750e-189">1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</span><span class="sxs-lookup"><span data-stu-id="d750e-189">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>