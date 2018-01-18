<Type Name="IStateProvider" FullName="System.Fabric.IStateProvider">
  <TypeSignature Language="C#" Value="public interface IStateProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStateProvider" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStateProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStateProvider" />
  <TypeSignature Language="F#" Value="type IStateProvider = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="d4e78-101">サービスが対話するために実装する必要がありますの動作を定義、<see cref="T:System.Fabric.FabricReplicator" />です。</span><span class="sxs-lookup"><span data-stu-id="d4e78-101">Defines the behavior that a service must implement to interact with the <see cref="T:System.Fabric.FabricReplicator" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetCopyContext">
      <MemberSignature Language="C#" Value="public System.Fabric.IOperationDataStream GetCopyContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IOperationDataStream GetCopyContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.GetCopyContext" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCopyContext () As IOperationDataStream" />
      <MemberSignature Language="F#" Value="abstract member GetCopyContext : unit -&gt; System.Fabric.IOperationDataStream" Usage="iStateProvider.GetCopyContext " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationDataStream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="d4e78-102">作成され、プライマリ レプリカにコンテキストを送信する開かれた後は、セカンダリ レプリカ上のコンテキストを取得します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-102">Obtains context on a secondary replica after it is created and opened to send context to the primary replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="d4e78-103"><see cref="T:System.Fabric.IOperationDataStream" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-103">Returns <see cref="T:System.Fabric.IOperationDataStream" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="d4e78-104">プライマリ レプリカがコンテキストを分析しを使用して状態を返送<see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />です。</span><span class="sxs-lookup"><span data-stu-id="d4e78-104">The primary replica analyzes the context and sends back state via <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />.</span></span></para>
          <para>
            <span data-ttu-id="d4e78-105"><see cref="M:System.Fabric.IStateProvider.GetCopyContext" />新しく作成された、アイドルなセカンダリ レプリカで呼び出され、非同期的に、プライマリ レプリカとの双方向メッセージ交換を確立するためのメカニズムを提供します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-105"><see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> is called on newly created, idle secondary replicas and provides a mechanism to asynchronously establish a bidirectional conversation with the primary replica.</span></span> <span data-ttu-id="d4e78-106">セカンダリ レプリカは、送信<see cref="T:System.Fabric.OperationData" />オブジェクトをプライマリ レプリカがセカンダリ レプリカでコンテキストを収集する場合の進行状況を判断できます。</span><span class="sxs-lookup"><span data-stu-id="d4e78-106">The secondary replica sends <see cref="T:System.Fabric.OperationData" /> objects with which the primary replica can determine the progress of collecting context on the secondary replica.</span></span> <span data-ttu-id="d4e78-107">プライマリ レプリカは、必要な状態に戻すを送信して応答します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-107">The primary replica responds by sending the required state back.</span></span>
                <span data-ttu-id="d4e78-108">参照してください<see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />交換の一方のプライマリ レプリカにします。</span><span class="sxs-lookup"><span data-stu-id="d4e78-108">See <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> at the primary replica for the other half of the exchange.</span></span> </para>
          <para><span data-ttu-id="d4e78-109">メモリ内のサービスでは、<see cref="M:System.Fabric.IStateProvider.GetCopyContext" />メソッドは呼び出されません、セカンダリ レプリカの状態は認識されている (空され、状態のすべてが必要)。</span><span class="sxs-lookup"><span data-stu-id="d4e78-109">For in-memory services, the <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> method is not called, as the state of the secondary replicas is known (they are empty and will require all of the state).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCopyState">
      <MemberSignature Language="C#" Value="public System.Fabric.IOperationDataStream GetCopyState (long upToSequenceNumber, System.Fabric.IOperationDataStream copyContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IOperationDataStream GetCopyState(int64 upToSequenceNumber, class System.Fabric.IOperationDataStream copyContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCopyState (upToSequenceNumber As Long, copyContext As IOperationDataStream) As IOperationDataStream" />
      <MemberSignature Language="F#" Value="abstract member GetCopyState : int64 * System.Fabric.IOperationDataStream -&gt; System.Fabric.IOperationDataStream" Usage="iStateProvider.GetCopyState (upToSequenceNumber, copyContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.NamingRules", "SA1305:FieldNamesMustNotUseHungarianNotation", Justification="Not Hungarian notation.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationDataStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upToSequenceNumber" Type="System.Int64" />
        <Parameter Name="copyContext" Type="System.Fabric.IOperationDataStream" />
      </Parameters>
      <Docs>
        <param name="upToSequenceNumber">
          <para><span data-ttu-id="d4e78-110">経由でコピー ストリーム内に配置する最大最後のシーケンス番号、<see cref="M:System.Fabric.IStateReplicator.GetCopyStream" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="d4e78-110">The maximum last sequence number that should be placed in the copy stream via the <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> method.</span></span>
            <span data-ttu-id="d4e78-111">この数より大きい Lsn が経由でレプリケーション ストリームの一部として、セカンダリ レプリカに配信される、<see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="d4e78-111">LSNs greater than this number are delivered to the secondary replica as a part of the replication stream via the <see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" /> method.</span></span></para>
        </param>
        <param name="copyContext">
          <para><span data-ttu-id="d4e78-112"><see cref="T:System.Fabric.IOperationDataStream" />を格納している、<see cref="T:System.Fabric.OperationData" />セカンダリ レプリカによって作成されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4e78-112">An <see cref="T:System.Fabric.IOperationDataStream" /> that contains the <see cref="T:System.Fabric.OperationData" /> objects that are created by the secondary replica.</span></span> </para>
        </param>
        <summary>
          <para><span data-ttu-id="d4e78-113">プライマリ レプリカのセカンダリ レプリカを作成する必要がある状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-113">Obtains state on a primary replica that is required to build a secondary replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="d4e78-114"><see cref="T:System.Fabric.IOperationDataStream" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-114">Returns <see cref="T:System.Fabric.IOperationDataStream" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="d4e78-115">同様に<see cref="M:System.Fabric.IStateProvider.GetCopyContext" />により、セカンダリ レプリカを使用して、プライマリ レプリカにコンテキストを送信する、 <see cref="T:System.Fabric.IOperationDataStream" />、<see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />により、プライマリ レプリカで応答する、<see cref="T:System.Fabric.IOperationDataStream" />です。</span><span class="sxs-lookup"><span data-stu-id="d4e78-115">Just as <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> enables the secondary replica to send context to the primary replica via an <see cref="T:System.Fabric.IOperationDataStream" />, <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> enables the primary replica to respond with an <see cref="T:System.Fabric.IOperationDataStream" />.</span></span> <span data-ttu-id="d4e78-116">ストリームには使用して、セカンダリ レプリカに配信されるオブジェクトが含まれています、<see cref="M:System.Fabric.IStateReplicator.GetCopyStream" />のメソッド、<see cref="T:System.Fabric.FabricReplicator" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="d4e78-116">The stream contains objects that are delivered to the secondary replica via the <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> method of the <see cref="T:System.Fabric.FabricReplicator" /> class.</span></span> <span data-ttu-id="d4e78-117">オブジェクトを実装<see cref="T:System.Fabric.IOperation" />し、指定されたデータが含まれています。</span><span class="sxs-lookup"><span data-stu-id="d4e78-117">The objects implement <see cref="T:System.Fabric.IOperation" /> and contain the specified data.</span></span> </para>
          <para> <span data-ttu-id="d4e78-118">プライマリ レプリカは、この呼び出しを受け取る、それを作成し、返す別<see cref="T:System.Fabric.IOperationDataStream" />を格納している<see cref="T:System.Fabric.OperationData" />です。</span><span class="sxs-lookup"><span data-stu-id="d4e78-118">When the primary replica receives this call, it should create and return another <see cref="T:System.Fabric.IOperationDataStream" /> that contains <see cref="T:System.Fabric.OperationData" />.</span></span> <span data-ttu-id="d4e78-119"><see cref="T:System.Fabric.OperationData" />セカンダリ レプリカが次々 に提供されているために必要なデータ/状態を表す<paramref name="upToSequenceNumber" />最大 LSN。</span><span class="sxs-lookup"><span data-stu-id="d4e78-119"><see cref="T:System.Fabric.OperationData" /> represents the data/state that the secondary replica requires to catch up to the provided <paramref name="upToSequenceNumber" /> maximum LSN.</span></span> <span data-ttu-id="d4e78-120">どの程度およびセカンダリ レプリカを経由で提供されるコンテキスト情報を使用して送信されるどの状態を持つを特定できる<see cref="M:System.Fabric.IStateProvider.GetCopyContext" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="d4e78-120">How much and which state has to be sent can be determined via the context information that the secondary replica provides via <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> method.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLastCommittedSequenceNumber">
      <MemberSignature Language="C#" Value="public long GetLastCommittedSequenceNumber ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 GetLastCommittedSequenceNumber() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.GetLastCommittedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLastCommittedSequenceNumber () As Long" />
      <MemberSignature Language="F#" Value="abstract member GetLastCommittedSequenceNumber : unit -&gt; int64" Usage="iStateProvider.GetLastCommittedSequenceNumber " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="d4e78-121">取得する最後のシーケンス番号、サービスがコミットされるとも呼ばれる論理シーケンス番号 (LSN)。</span><span class="sxs-lookup"><span data-stu-id="d4e78-121">Obtains the last sequence number that the service has committed, also known as Logical Sequence Number (LSN).</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="d4e78-122">最後のコミット シーケンス番号を返します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-122">Returns the last committed sequence number.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; OnDataLossAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; OnDataLossAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.OnDataLossAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDataLossAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iStateProvider.OnDataLossAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.MSInternal", "CA908:UseApprovedGenericsForPrecompiledAssemblies", Justification="Not precompiled assembly.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="d4e78-123"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4e78-123">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="d4e78-124">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-124">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="d4e78-125">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="d4e78-125">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="d4e78-126">このレプリカ セット内のレプリカのな書き込みクォーラムが失われていることと、そのためデータが失われる可能性がありますが発生したことを示します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-126">Indicates that a write quorum of replicas in this replica set has been lost, and that therefore data loss might have occurred.</span></span> <span data-ttu-id="d4e78-127">レプリカ セットは、プライマリ レプリカが含まれているレプリカの大部分で構成されます。</span><span class="sxs-lookup"><span data-stu-id="d4e78-127">The replica set consists of a majority of replicas, which includes the primary replica.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="d4e78-128">返します<see cref="T:System.Threading.Tasks.Task`1" />型の<see cref="T:System.Boolean" />、この通知の処理の一部として状態プロバイダーでの状態が変更されたかどうかを示す</span><span class="sxs-lookup"><span data-stu-id="d4e78-128">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type <see cref="T:System.Boolean" />, that indicates whether the state provider as part of processing this notification has changed its state</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="d4e78-129">Service Fabric ランタイムが、プライマリ レプリカが含まれており、レプリカのクォーラムの障害発生時に新しいプライマリ レプリカと、すぐに、新しいプライマリ レプリカでこのメソッドを呼び出します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-129">When the Service Fabric runtime observes the failure of a quorum of replicas, which includes the primary replica, it elects a new primary replica and immediately calls this method on the new primary replica.</span></span> <span data-ttu-id="d4e78-130">データ損失の可能性が通知をプライマリ レプリカは、外部データ ソースからの状態を復元することもできます。 またはが現在の状態で実行を続行できます。</span><span class="sxs-lookup"><span data-stu-id="d4e78-130">A primary replica that is informed of possible data loss can choose to restore its state from some external data source or can continue to run with the state that it currently has.</span></span> <span data-ttu-id="d4e78-131">サービスが、現在の状態で実行され続ける場合は、状態の変更が行われていないことを示す、このメソッドから false を返します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-131">If the service continues to run with its current state, it should return false from this method, which indicates that no state change has been made.</span></span> <span data-ttu-id="d4e78-132">復元または不完全な作業は、ロールバックなどの状態を変更した場合は true を返します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-132">If it has restored or altered its state, such as rolling back incomplete work, it should return true.</span></span> <span data-ttu-id="d4e78-133">True が返される場合はその他のレプリカの状態が不適切な想定されます。</span><span class="sxs-lookup"><span data-stu-id="d4e78-133">If true is returned, then the state in other replicas must be assumed to be incorrect.</span></span>
            <span data-ttu-id="d4e78-134">そのため、Service Fabric ランタイムでは、レプリカ セットから他のレプリカを削除し、それらを再作成します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-134">Therefore, the Service Fabric runtime removes the other replicas from the replica set and recreates them.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateEpochAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateEpochAsync (System.Fabric.Epoch epoch, long previousEpochLastSequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateEpochAsync(valuetype System.Fabric.Epoch epoch, int64 previousEpochLastSequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateEpochAsync : System.Fabric.Epoch * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStateProvider.UpdateEpochAsync (epoch, previousEpochLastSequenceNumber, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="previousEpochLastSequenceNumber" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para><span data-ttu-id="d4e78-135">新しい <see cref="T:System.Fabric.Epoch" />。</span><span class="sxs-lookup"><span data-stu-id="d4e78-135">The new <see cref="T:System.Fabric.Epoch" />.</span></span></para>
        </param>
        <param name="previousEpochLastSequenceNumber">
          <para> <span data-ttu-id="d4e78-136">以前のエポックの最大シーケンス番号 (LSN)。</span><span class="sxs-lookup"><span data-stu-id="d4e78-136">The maximum sequence number (LSN) in the previous epoch.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="d4e78-137"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d4e78-137">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="d4e78-138">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-138">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="d4e78-139">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="d4e78-139">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="d4e78-140">レプリカ セットの構成が変更の理由で変更または、プライマリ レプリカへの変更をしようとしましたが、レプリカを示します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-140">Indicates to a replica that the configuration of a replica set has changed due to a change or attempted change to the primary replica.</span></span> <span data-ttu-id="d4e78-141">変更は、エラーまたは以前のプライマリ レプリカの負荷分散のために発生します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-141">The change occurs due to failure or load balancing of the previous primary replica.</span></span> <span data-ttu-id="d4e78-142">エポックの変更は、特定のプライマリ レプリカによって送信された実際の構成の期間に操作を分割することによって、バリアとして機能します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-142">Epoch changes act as a barrier by segmenting operations into the exact configuration periods in which they were sent by a specific primary replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="d4e78-143"><see cref="T:System.Threading.Tasks.Task" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-143">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="d4e78-144">内の情報、<see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" />メソッドは、レプリカが受信した各エポックとそれらに含まれる最大の LSN の一覧、進行状況のベクトルを維持するためにサービスを有効にします。</span><span class="sxs-lookup"><span data-stu-id="d4e78-144">The information in the <see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" /> method enables the service to maintain a progress vector, which is a list of each epoch that the replica has received, and the maximum LSN that they contained.</span></span> </para>
          <para>
                <span data-ttu-id="d4e78-145">現在適用されている最大の LSN と進行状況のベクター データは、レプリカの状態を説明するコピー操作中に送信するセカンダリ レプリカに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="d4e78-145">The progress vector data along with the current applied maximum LSN is useful for a secondary replica to send during the copy operation to describe the state of the replica.</span></span></para>
          <para>
                <span data-ttu-id="d4e78-146">コピー操作中に、セカンダリ レプリカから受信した進行状況のベクトルを比較することにより、プライマリ レプリカをセカンダリ レプリカにどのような状態を送信する必要があります、セカンダリ レプリカが最新では、どうかを決定するかどうかと、セカンダリ レプリカfalse の進行状況が行われます。</span><span class="sxs-lookup"><span data-stu-id="d4e78-146">Comparing progress vectors that are received from secondary replicas during the copy operation enables primary replicas to determine whether the secondary replica is up-to-date, what state must be sent to the secondary replica, and whether the secondary replica has made false progress.</span></span> </para>
          <para><span data-ttu-id="d4e78-147">False の進行状況は、セカンダリ レプリカは、以前のエポックの LSN が、プライマリ レプリカは、その進行状況のベクター内にある LSN よりも大きかったレポートを意味します。</span><span class="sxs-lookup"><span data-stu-id="d4e78-147">False progress means that a secondary replica reports an LSN in a previous epoch was greater than the LSN that the primary replica has in its progress vector.</span></span> </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>