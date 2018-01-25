<Type Name="IAtomicGroupStateReplicator" FullName="System.Fabric.IAtomicGroupStateReplicator">
  <TypeSignature Language="C#" Value="public interface IAtomicGroupStateReplicator" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAtomicGroupStateReplicator" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IAtomicGroupStateReplicator" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAtomicGroupStateReplicator" />
  <TypeSignature Language="F#" Value="type IAtomicGroupStateReplicator = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="b3448-101">分割不可能なグループのレプリケーション関連の機能を公開します。</span><span class="sxs-lookup"><span data-stu-id="b3448-101">Exposes replication-related functions for atomic groups.</span></span> </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="b3448-102"><see cref="T:System.Fabric.IAtomicGroupStateReplicator" />利用できるサービスがサービス グループのメンバーである場合です。</span><span class="sxs-lookup"><span data-stu-id="b3448-102">The <see cref="T:System.Fabric.IAtomicGroupStateReplicator" /> is available if the service is a member of a service group.</span></span> <span data-ttu-id="b3448-103">サービスを実装する必要があります<see cref="T:System.Fabric.IAtomicGroupStateProvider" />ステートフルであるとします。</span><span class="sxs-lookup"><span data-stu-id="b3448-103">The service must implement <see cref="T:System.Fabric.IAtomicGroupStateProvider" /> and be stateful.</span></span> <span data-ttu-id="b3448-104">作成するときに、<see cref="T:System.Fabric.FabricReplicator" />経由で<see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />、通常で渡す代わりに<see cref="T:System.Fabric.IStateProvider" />、サービスで渡すことができます、<see cref="T:System.Fabric.IAtomicGroupStateProvider" />代わりに実装します。</span><span class="sxs-lookup"><span data-stu-id="b3448-104">When creating a <see cref="T:System.Fabric.FabricReplicator" /> via <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />, instead of passing in a regular <see cref="T:System.Fabric.IStateProvider" />, the service can pass in the <see cref="T:System.Fabric.IAtomicGroupStateProvider" /> that it implements instead.</span></span> <span data-ttu-id="b3448-105">その結果、受信、<see cref="T:System.Fabric.IAtomicGroupStateReplicator" />です。</span><span class="sxs-lookup"><span data-stu-id="b3448-105">As a result, it receives a <see cref="T:System.Fabric.IAtomicGroupStateReplicator" />.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAtomicGroup">
      <MemberSignature Language="C#" Value="public long CreateAtomicGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 CreateAtomicGroup() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateReplicator.CreateAtomicGroup" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAtomicGroup () As Long" />
      <MemberSignature Language="F#" Value="abstract member CreateAtomicGroup : unit -&gt; int64" Usage="iAtomicGroupStateReplicator.CreateAtomicGroup " />
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
          <para><span data-ttu-id="b3448-106">新しい分割不可能なグループを作成し、分割不可能なグループの ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="b3448-106">Creates a new atomic group and obtains the ID of the atomic group.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="b3448-107">返します<see cref="T:System.Int64" />作成したアトミック グループの ID。</span><span class="sxs-lookup"><span data-stu-id="b3448-107">Returns <see cref="T:System.Int64" /> the ID of the created atomic group.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="b3448-108">分割不可能なグループは、サービス グループのメンバー間で一連の変更を調整するために使用されます。</span><span class="sxs-lookup"><span data-stu-id="b3448-108">Atomic groups are used to coordinate a set of changes across the members of a service group.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicateAtomicGroupCommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ReplicateAtomicGroupCommitAsync (long atomicGroupId, System.Threading.CancellationToken cancellationToken, out long commitSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ReplicateAtomicGroupCommitAsync(int64 atomicGroupId, valuetype System.Threading.CancellationToken cancellationToken, [out] int64&amp; commitSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateReplicator.ReplicateAtomicGroupCommitAsync(System.Int64,System.Threading.CancellationToken,System.Int64@)" />
      <MemberSignature Language="F#" Value="abstract member ReplicateAtomicGroupCommitAsync : int64 * System.Threading.CancellationToken *  -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iAtomicGroupStateReplicator.ReplicateAtomicGroupCommitAsync (atomicGroupId, cancellationToken, commitSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="commitSequenceNumber" Type="System.Int64&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para><span data-ttu-id="b3448-109">コミットするグループの ID。</span><span class="sxs-lookup"><span data-stu-id="b3448-109">The ID of the group to be committed.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="b3448-110"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b3448-110">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="b3448-111">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="b3448-111">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="b3448-112">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="b3448-112">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <param name="commitSequenceNumber">
          <para><span data-ttu-id="b3448-113">Out パラメーターとして、コミット操作の LSN です。</span><span class="sxs-lookup"><span data-stu-id="b3448-113">The LSN of the commit operation, as an out parameter.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b3448-114">アトミック グループの状態のレプリケーションを非同期にコミットします。</span><span class="sxs-lookup"><span data-stu-id="b3448-114">Asynchronously commits state replication for the atomic group.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="b3448-115">返します<see cref="T:System.Threading.Tasks.Task`1" />型の長い、コミット操作の LSN。</span><span class="sxs-lookup"><span data-stu-id="b3448-115">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type long, the LSN of the commit operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicateAtomicGroupOperationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ReplicateAtomicGroupOperationAsync (long atomicGroupId, System.Fabric.OperationData operationData, System.Threading.CancellationToken cancellationToken, out long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ReplicateAtomicGroupOperationAsync(int64 atomicGroupId, class System.Fabric.OperationData operationData, valuetype System.Threading.CancellationToken cancellationToken, [out] int64&amp; sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateReplicator.ReplicateAtomicGroupOperationAsync(System.Int64,System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />
      <MemberSignature Language="F#" Value="abstract member ReplicateAtomicGroupOperationAsync : int64 * System.Fabric.OperationData * System.Threading.CancellationToken *  -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iAtomicGroupStateReplicator.ReplicateAtomicGroupOperationAsync (atomicGroupId, operationData, cancellationToken, sequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="operationData" Type="System.Fabric.OperationData" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="sequenceNumber" Type="System.Int64&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para><span data-ttu-id="b3448-116">取得されるアトミック グループの ID<see cref="M:System.Fabric.IAtomicGroupStateReplicator.CreateAtomicGroup" />が含まれています、<see cref="T:System.Fabric.OperationData" />です。</span><span class="sxs-lookup"><span data-stu-id="b3448-116">The ID of the atomic group that is obtained from <see cref="M:System.Fabric.IAtomicGroupStateReplicator.CreateAtomicGroup" /> and includes the <see cref="T:System.Fabric.OperationData" />.</span></span></para>
        </param>
        <param name="operationData">
          <para><span data-ttu-id="b3448-117"><see cref="T:System.Fabric.OperationData" />をレプリケートします。</span><span class="sxs-lookup"><span data-stu-id="b3448-117">An <see cref="T:System.Fabric.OperationData" /> to be replicated.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="b3448-118">操作を観察し CancellationToken オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b3448-118">The CancellationToken object that the operation is observing.</span></span> <span data-ttu-id="b3448-119">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="b3448-119">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="b3448-120">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="b3448-120">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <param name="sequenceNumber">
          <para><span data-ttu-id="b3448-121">Out パラメーターとして、操作の LSN。</span><span class="sxs-lookup"><span data-stu-id="b3448-121">The LSN of the operation, as an out parameter.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b3448-122">一部の複製<see cref="T:System.Fabric.OperationData" />アトミック グループの一部として。</span><span class="sxs-lookup"><span data-stu-id="b3448-122">Replicates some <see cref="T:System.Fabric.OperationData" /> as a part of an atomic group.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="b3448-123">返します<see cref="T:System.Threading.Tasks.Task`1" />long 型で、レプリケートされたアトミック グループ操作の LSN。</span><span class="sxs-lookup"><span data-stu-id="b3448-123">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type long, the LSN of the replicated atomic group operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicateAtomicGroupRollbackAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ReplicateAtomicGroupRollbackAsync (long atomicGroupId, System.Threading.CancellationToken cancellationToken, out long rollbackSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ReplicateAtomicGroupRollbackAsync(int64 atomicGroupId, valuetype System.Threading.CancellationToken cancellationToken, [out] int64&amp; rollbackSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IAtomicGroupStateReplicator.ReplicateAtomicGroupRollbackAsync(System.Int64,System.Threading.CancellationToken,System.Int64@)" />
      <MemberSignature Language="F#" Value="abstract member ReplicateAtomicGroupRollbackAsync : int64 * System.Threading.CancellationToken *  -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iAtomicGroupStateReplicator.ReplicateAtomicGroupRollbackAsync (atomicGroupId, cancellationToken, rollbackSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="atomicGroupId" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="rollbackSequenceNumber" Type="System.Int64&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="atomicGroupId">
          <para><span data-ttu-id="b3448-124">ロールバックするアトミック グループの ID。</span><span class="sxs-lookup"><span data-stu-id="b3448-124">The ID of the atomic group to roll back.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="b3448-125"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b3448-125">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="b3448-126">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="b3448-126">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="b3448-127">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="b3448-127">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <param name="rollbackSequenceNumber">
          <para><span data-ttu-id="b3448-128">Out パラメーターとして、ロールバック操作の LSN。</span><span class="sxs-lookup"><span data-stu-id="b3448-128">The LSN of the rollback operation, as an out parameter.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b3448-129">非同期的にロールバック アトミック グループの状態のレプリケーション。</span><span class="sxs-lookup"><span data-stu-id="b3448-129">Asynchronously rolls-back state replication for the atomic group.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="b3448-130">返します<see cref="T:System.Threading.Tasks.Task`1" />long 型でロールバック操作の LSN。</span><span class="sxs-lookup"><span data-stu-id="b3448-130">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type long, the LSN of the rollback operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>