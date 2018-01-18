<Type Name="FabricClient+FaultManagementClient" FullName="System.Fabric.FabricClient+FaultManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.FaultManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/FaultManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.FaultManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.FaultManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.FaultManagementClient = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="215e8-101">Service Fabric クラスター内の障害を導入する機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="215e8-101">Provides functionality to introduce faults in a Service Fabric cluster.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync partitionSelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="215e8-102">この選択されたパーティションで呼び出されるプライマリを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-102">Move primary will be called on this Selected Partition.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-103">新しいノードにプライマリ レプリカを選択したクラスターに移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-103">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-104">移動プライマリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-104">A task with move primary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-105">API では、選択したパーティションのプライマリ レプリカを使用して、新しいノードの場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-105">API uses the primary replica of the selected partition to move to new node location.</span></span>
            <span data-ttu-id="215e8-106">このオーバー ロードは、現在のノードの一覧から選択したランダム ノードを使用し、プライマリ レプリカがプライマリ レプリカを移動するための API の呼び出し時に存在しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-106">This overload uses random node selected from current node list, where primary replica does not exist at the time of API call for moving primary replica.</span></span>
            <span data-ttu-id="215e8-107">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-107">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-108">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-108">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-109">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-109">Invalid operation</span></span>
            - <span data-ttu-id="215e8-110">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-110">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-111">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-111">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-112">FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。</span><span class="sxs-lookup"><span data-stu-id="215e8-112">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="215e8-113">この選択されたパーティションで呼び出されるプライマリを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-113">Move primary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="215e8-114">移動を実行しようとするときに制約を無視するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-114">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-115">新しいノードにプライマリ レプリカを選択したクラスターに移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-115">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-116">移動プライマリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-116">A task with move primary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-117">API では、選択したパーティションのプライマリ レプリカを使用して、新しいノードの場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-117">API uses the primary replica of the selected partition to move to new node location.</span></span>
            <span data-ttu-id="215e8-118">このオーバー ロードは、現在のノードの一覧から選択したランダム ノードを使用し、プライマリ レプリカがプライマリ レプリカを移動するための API の呼び出し時に存在しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-118">This overload uses random node selected from current node list, where primary replica does not exist at the time of API call for moving primary replica.</span></span>
            <span data-ttu-id="215e8-119">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-119">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-120">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-120">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-121">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-121">Invalid operation</span></span>
            - <span data-ttu-id="215e8-122">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-122">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-123">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-123">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-124">FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。</span><span class="sxs-lookup"><span data-stu-id="215e8-124">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="215e8-125">この選択されたパーティションで呼び出されるプライマリを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-125">Move primary will be called on this Selected Partition.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-126">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-126">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-127">新しいノードにプライマリ レプリカを選択したクラスターに移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-127">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-128">移動プライマリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-128">A task with move primary result</span></span></returns>
        <remarks><span data-ttu-id="215e8-129">API では、選択したパーティションのプライマリ レプリカを使用して、新しいノードの場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-129">API uses the primary replica of the selected partition to move to new node location.</span></span>
            <span data-ttu-id="215e8-130">このオーバー ロードは、現在のノードの一覧から選択したランダム ノードを使用し、プライマリ レプリカがプライマリ レプリカを移動するための API の呼び出し時に存在しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-130">This overload uses random node selected from current node list, where primary replica does not exist at the time of API call for moving primary replica.</span></span>
            <span data-ttu-id="215e8-131">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-131">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-132">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-132">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-133">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-133">Invalid operation</span></span>
            - <span data-ttu-id="215e8-134">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-134">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-135">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-135">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-136">FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。</span><span class="sxs-lookup"><span data-stu-id="215e8-136">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-137">ノードの名前、プライマリ レプリカを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-137">Node name where primary replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-138">この選択されたパーティションで呼び出されるプライマリを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-138">Move primary will be called on this Selected Partition.</span></span> </param>
        <summary>
            <span data-ttu-id="215e8-139">新しいノードにプライマリ レプリカを選択したクラスターに移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-139">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-140">移動プライマリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-140">A task with move primary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-141">API では、選択したパーティションのプライマリ レプリカを使用して、ノード名で指定されたノードの新しい場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-141">API uses the primary replica of the selected partition to move to new node location specified by nodeName.</span></span>
            <span data-ttu-id="215e8-142">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-142">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-143">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-143">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-144">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-144">Invalid operation</span></span>
            - <span data-ttu-id="215e8-145">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-145">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-146">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-146">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-147">FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。</span><span class="sxs-lookup"><span data-stu-id="215e8-147">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="215e8-148">この選択されたパーティションで呼び出されるプライマリを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-148">Move primary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="215e8-149">移動を実行しようとするときに制約を無視するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-149">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-150">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-150">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-151">新しいノードにプライマリ レプリカを選択したクラスターに移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-151">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-152">移動プライマリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-152">A task with move primary result</span></span></returns>
        <remarks><span data-ttu-id="215e8-153">API では、選択したパーティションのプライマリ レプリカを使用して、新しいノードの場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-153">API uses the primary replica of the selected partition to move to new node location.</span></span>
            <span data-ttu-id="215e8-154">このオーバー ロードは、現在のノードの一覧から選択したランダム ノードを使用し、プライマリ レプリカがプライマリ レプリカを移動するための API の呼び出し時に存在しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-154">This overload uses random node selected from current node list, where primary replica does not exist at the time of API call for moving primary replica.</span></span>
            <span data-ttu-id="215e8-155">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-155">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-156">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-156">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-157">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-157">Invalid operation</span></span>
            - <span data-ttu-id="215e8-158">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-158">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-159">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-159">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-160">FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。</span><span class="sxs-lookup"><span data-stu-id="215e8-160">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="215e8-161">この選択されたパーティションで呼び出されるプライマリを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-161">Move primary will be called on this Selected Partition.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-162">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="215e8-162">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-163">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-163">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-164">新しいノードにプライマリ レプリカを選択したクラスターに移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-164">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-165">移動プライマリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-165">A task with move primary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-166">API では、選択したパーティションのプライマリ レプリカを使用して、新しいノードの場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-166">API uses the primary replica of the selected partition to move to new node location.</span></span>
            <span data-ttu-id="215e8-167">このオーバー ロードは、現在のノードの一覧から選択したランダム ノードを使用し、プライマリ レプリカがプライマリ レプリカを移動するための API の呼び出し時に存在しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-167">This overload uses random node selected from current node list, where primary replica does not exist at the time of API call for moving primary replica.</span></span>
            <span data-ttu-id="215e8-168">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-168">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span></remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-169">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-169">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-170">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-170">Invalid operation</span></span>
            - <span data-ttu-id="215e8-171">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-171">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-172">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-172">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-173">FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。</span><span class="sxs-lookup"><span data-stu-id="215e8-173">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-174">ノードの名前、プライマリ レプリカを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-174">Node name where primary replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-175">この選択されたパーティションで呼び出されるプライマリを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-175">Move primary will be called on this Selected Partition.</span></span> </param>
        <param name="ignoreConstraints"><span data-ttu-id="215e8-176">移動を実行しようとするときに制約を無視するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-176">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <summary>
             <span data-ttu-id="215e8-177">新しいノードにプライマリ レプリカを選択したクラスターに移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-177">Moves selected primary replica to new node in the cluster.</span></span>
             </summary>
        <returns><span data-ttu-id="215e8-178">移動プライマリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-178">A task with move primary result</span></span></returns>
        <remarks>
             <span data-ttu-id="215e8-179">API では、選択したパーティションのプライマリ レプリカを使用して、ノード名で指定されたノードの新しい場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-179">API uses the primary replica of the selected partition to move to new node location specified by nodeName.</span></span>
             <span data-ttu-id="215e8-180">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-180">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
             </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-181">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-181">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-182">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-182">Invalid operation</span></span>
             - <span data-ttu-id="215e8-183">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-183">If action called on stateless service.</span></span>
             - <span data-ttu-id="215e8-184">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-184">If not enough nodes available for action</span></span>
             </exception>
        <exception cref="T:System.Fabric.FabricException">
             <span data-ttu-id="215e8-185">FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。</span><span class="sxs-lookup"><span data-stu-id="215e8-185">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
             </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-186">ノードの名前、プライマリ レプリカを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-186">Node name where primary replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-187">この選択されたパーティションで呼び出されるプライマリを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-187">Move primary will be called on this Selected Partition.</span></span> </param>
        <param name="token"><span data-ttu-id="215e8-188">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-188">The cancellation token</span></span></param>
        <summary>
             <span data-ttu-id="215e8-189">新しいノードにプライマリ レプリカを選択したクラスターに移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-189">Moves selected primary replica to new node in the cluster.</span></span>
             </summary>
        <returns><span data-ttu-id="215e8-190">移動プライマリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-190">A task with move primary result</span></span></returns>
        <remarks>
             <span data-ttu-id="215e8-191">API では、選択したパーティションのプライマリ レプリカを使用して、ノード名で指定されたノードの新しい場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-191">API uses the primary replica of the selected partition to move to new node location specified by nodeName.</span></span>
             <span data-ttu-id="215e8-192">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-192">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
             </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-193">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-193">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-194">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-194">Invalid operation</span></span>
             - <span data-ttu-id="215e8-195">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-195">If action called on stateless service.</span></span>
             - <span data-ttu-id="215e8-196">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-196">If not enough nodes available for action</span></span>
             </exception>
        <exception cref="T:System.Fabric.FabricException">
             <span data-ttu-id="215e8-197">FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。</span><span class="sxs-lookup"><span data-stu-id="215e8-197">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
             </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MovePrimaryAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="215e8-198">この選択されたパーティションで呼び出されるプライマリを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-198">Move primary will be called on this Selected Partition.</span></span> </param>
        <param name="ignoreConstraints"><span data-ttu-id="215e8-199">移動を実行しようとするときに制約を無視するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-199">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-200">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="215e8-200">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-201">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-201">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-202">新しいノードにプライマリ レプリカを選択したクラスターに移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-202">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-203">移動プライマリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-203">A task with move primary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-204">API では、選択したパーティションのプライマリ レプリカを使用して、新しいノードの場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-204">API uses the primary replica of the selected partition to move to new node location.</span></span>
            <span data-ttu-id="215e8-205">このオーバー ロードは、現在のノードの一覧から選択したランダム ノードを使用し、プライマリ レプリカがプライマリ レプリカを移動するための API の呼び出し時に存在しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-205">This overload uses random node selected from current node list, where primary replica does not exist at the time of API call for moving primary replica.</span></span>
            <span data-ttu-id="215e8-206">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-206">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span></remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-207">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-207">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-208">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-208">Invalid operation</span></span>
            - <span data-ttu-id="215e8-209">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-209">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-210">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-210">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-211">FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。</span><span class="sxs-lookup"><span data-stu-id="215e8-211">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-212">ノードの名前、プライマリ レプリカを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-212">Node name where primary replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-213">この選択されたパーティションで呼び出されるプライマリを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-213">Move primary will be called on this Selected Partition.</span></span> </param>
        <param name="ignoreConstraints"><span data-ttu-id="215e8-214">移動を実行しようとするときに制約を無視するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-214">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-215">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-215">The cancellation token</span></span></param>
        <summary>
             <span data-ttu-id="215e8-216">新しいノードにプライマリ レプリカを選択したクラスターに移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-216">Moves selected primary replica to new node in the cluster.</span></span>
             </summary>
        <returns><span data-ttu-id="215e8-217">移動プライマリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-217">A task with move primary result</span></span></returns>
        <remarks>
             <span data-ttu-id="215e8-218">API では、選択したパーティションのプライマリ レプリカを使用して、ノード名で指定されたノードの新しい場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-218">API uses the primary replica of the selected partition to move to new node location specified by nodeName.</span></span>
             <span data-ttu-id="215e8-219">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-219">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
             </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-220">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-220">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-221">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-221">Invalid operation</span></span>
             - <span data-ttu-id="215e8-222">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-222">If action called on stateless service.</span></span>
             - <span data-ttu-id="215e8-223">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-223">If not enough nodes available for action</span></span>
             </exception>
        <exception cref="T:System.Fabric.FabricException">
             <span data-ttu-id="215e8-224">FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。</span><span class="sxs-lookup"><span data-stu-id="215e8-224">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
             </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MovePrimaryAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-225">ノードの名前、プライマリ レプリカを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-225">Node name where primary replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-226">この選択されたパーティションで呼び出されるプライマリを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-226">Move primary will be called on this Selected Partition.</span></span>
            <span data-ttu-id="215e8-227">API では、選択したパーティションのプライマリ レプリカを使用して、新しいノードの場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-227">API uses the primary replica of the selected partition to move to new node location.</span></span>
            </param>
        <param name="operationTimeout"><span data-ttu-id="215e8-228">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="215e8-228">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-229">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-229">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-230">新しいノードにプライマリ レプリカを選択したクラスターに移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-230">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-231">移動プライマリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-231">A task with move primary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-232">API では、選択したパーティションのプライマリ レプリカを使用して、ノード名で指定されたノードの新しい場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-232">API uses the primary replica of the selected partition to move to new node location specified by nodeName.</span></span>
            <span data-ttu-id="215e8-233">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-233">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-234">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-234">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-235">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-235">Invalid operation</span></span>
            - <span data-ttu-id="215e8-236">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-236">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-237">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-237">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-238">FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。</span><span class="sxs-lookup"><span data-stu-id="215e8-238">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MovePrimaryAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-239">ノードの名前、プライマリ レプリカを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-239">Node name where primary replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-240">この選択されたパーティションで呼び出されるプライマリを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-240">Move primary will be called on this Selected Partition.</span></span>
            <span data-ttu-id="215e8-241">API では、選択したパーティションのプライマリ レプリカを使用して、新しいノードの場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-241">API uses the primary replica of the selected partition to move to new node location.</span></span>
            </param>
        <param name="ignoreConstraints"><span data-ttu-id="215e8-242">移動を実行しようとするときに制約を無視するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-242">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-243">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="215e8-243">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-244">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-244">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-245">新しいノードにプライマリ レプリカを選択したクラスターに移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-245">Moves selected primary replica to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-246">移動プライマリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-246">A task with move primary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-247">API では、選択したパーティションのプライマリ レプリカを使用して、ノード名で指定されたノードの新しい場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-247">API uses the primary replica of the selected partition to move to new node location specified by nodeName.</span></span>
            <span data-ttu-id="215e8-248">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-248">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-249">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-249">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-250">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-250">Invalid operation</span></span>
            - <span data-ttu-id="215e8-251">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-251">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-252">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-252">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-253">FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。</span><span class="sxs-lookup"><span data-stu-id="215e8-253">FabricErrorCode.NotReady - If Primary replica is not ready for movement FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync partitionSelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="215e8-254">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-254">Move Secondary will be called on this Selected Partition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="215e8-255">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-255">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-256">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-256">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-257">API は、現在のセカンダリ ノードで指定されたパーティション セレクター構造内の選択したセカンダリ レプリカを使用します。</span><span class="sxs-lookup"><span data-stu-id="215e8-257">API uses the selected secondary replica inside partition selector structure specified by current secondary node.</span></span> <span data-ttu-id="215e8-258">この API のオーバー ロードは、選択したパーティションのランダムなセカンダリ レプリカの現在のセカンダリ ノードと選択したこのレプリカは、現在のノードの場所から新しいノードの場所に移動されますレプリカ移動のための新しいセカンダリ ノードにランダムに選択します。</span><span class="sxs-lookup"><span data-stu-id="215e8-258">This API overload randomly selects current secondary node for random secondary replica of the selected partition and new secondary node for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="215e8-259">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-259">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-260">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-260">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-261">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-261">Invalid operation</span></span>
            - <span data-ttu-id="215e8-262">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-262">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-263">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-263">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-264">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-264">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-265">FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合</span><span class="sxs-lookup"><span data-stu-id="215e8-265">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="215e8-266">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-266">Move Secondary will be called on this Selected Partition.</span></span> </param>
        <param name="ignoreConstraints"><span data-ttu-id="215e8-267">移動を実行しようとするときに制約を無視するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-267">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-268">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-268">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-269">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-269">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-270">API は、現在のセカンダリ ノードで指定されたパーティション セレクター構造内の選択したセカンダリ レプリカを使用します。</span><span class="sxs-lookup"><span data-stu-id="215e8-270">API uses the selected secondary replica inside partition selector structure specified by current secondary node.</span></span> <span data-ttu-id="215e8-271">この API のオーバー ロードは、選択したパーティションのランダムなセカンダリ レプリカの現在のセカンダリ ノードと選択したこのレプリカは、現在のノードの場所から新しいノードの場所に移動されますレプリカ移動のための新しいセカンダリ ノードにランダムに選択します。</span><span class="sxs-lookup"><span data-stu-id="215e8-271">This API overload randomly selects current secondary node for random secondary replica of the selected partition and new secondary node for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="215e8-272">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-272">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-273">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-273">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-274">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-274">Invalid operation</span></span>
            - <span data-ttu-id="215e8-275">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-275">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-276">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-276">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-277">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-277">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-278">FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合</span><span class="sxs-lookup"><span data-stu-id="215e8-278">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="215e8-279">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-279">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-280">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-280">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-281">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-281">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-282">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-282">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-283">この API のオーバー ロードは、選択したパーティションのランダムなセカンダリ レプリカの現在のセカンダリ ノードと選択したこのレプリカは、現在のノードの場所から新しいノードの場所に移動されますレプリカ移動のための新しいセカンダリ ノードにランダムに選択します。</span><span class="sxs-lookup"><span data-stu-id="215e8-283">This API overload randomly selects current secondary node for random secondary replica of the selected partition and new secondary node for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="215e8-284">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-284">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-285">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-285">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-286">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-286">Invalid operation</span></span>
            - <span data-ttu-id="215e8-287">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-287">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-288">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-288">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-289">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-289">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-290">FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - レプリカが移動される場合はセカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合</span><span class="sxs-lookup"><span data-stu-id="215e8-290">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the replica being moved is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__72))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="215e8-291">移動する場合に選択したレプリカが現在存在するノード名</span><span class="sxs-lookup"><span data-stu-id="215e8-291">node name where selected replica for move is currently present</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-292">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-292">Move Secondary will be called on this Selected Partition.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-293">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-293">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-294">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-294">A task with move secondary result</span></span></returns>
        <remarks><span data-ttu-id="215e8-295">API は、currentNodeName で指定されたパーティション セレクター構造内の選択したセカンダリ レプリカを使用します。</span><span class="sxs-lookup"><span data-stu-id="215e8-295">API uses the selected secondary replica inside partition selector structure specified by currentNodeName.</span></span> <span data-ttu-id="215e8-296">この API のオーバー ロードは、この選択したレプリカは現在のノードの場所から新しいノードの場所に移動するレプリカの移動のための新しいセカンダリ ノードをランダムに選択します。</span><span class="sxs-lookup"><span data-stu-id="215e8-296">This API overload randomly selects new secondary node for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="215e8-297">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-297">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-298">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-298">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-299">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-299">Invalid operation</span></span>
            - <span data-ttu-id="215e8-300">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-300">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-301">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-301">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-302">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-302">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-303">FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合</span><span class="sxs-lookup"><span data-stu-id="215e8-303">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="215e8-304">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-304">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="215e8-305">移動を実行しようとするときに制約を無視するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-305">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-306">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-306">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-307">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-307">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-308">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-308">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-309">この API のオーバー ロードは、選択したパーティションのランダムなセカンダリ レプリカの現在のセカンダリ ノードと選択したこのレプリカは、現在のノードの場所から新しいノードの場所に移動されますレプリカ移動のための新しいセカンダリ ノードにランダムに選択します。</span><span class="sxs-lookup"><span data-stu-id="215e8-309">This API overload randomly selects current secondary node for random secondary replica of the selected partition and new secondary node for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="215e8-310">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-310">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-311">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-311">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-312">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-312">Invalid operation</span></span>
            - <span data-ttu-id="215e8-313">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-313">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-314">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-314">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-315">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-315">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-316">FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - レプリカが移動される場合はセカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合</span><span class="sxs-lookup"><span data-stu-id="215e8-316">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the replica being moved is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__82))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="215e8-317">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-317">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-318">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="215e8-318">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-319">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-319">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-320">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-320">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-321">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-321">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-322">API は、指定されたパーティションのセレクターをランダムに選択したセカンダリ レプリカを使用します。</span><span class="sxs-lookup"><span data-stu-id="215e8-322">API uses the randomly selected secondary replica for specified partition selector.</span></span>
            <span data-ttu-id="215e8-323">この API のオーバー ロードは、この選択したレプリカは現在のノードの場所から新しいノードの場所に移動するレプリカの移動のための新しいセカンダリ ノード位置をランダムに選択します。</span><span class="sxs-lookup"><span data-stu-id="215e8-323">This API overload randomly selects new secondary node location for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="215e8-324">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-324">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-325">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-325">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-326">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-326">Invalid operation</span></span>
            - <span data-ttu-id="215e8-327">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-327">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-328">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-328">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-329">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-329">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-330">FabricErrorCode.AlreadyPrimaryReplica - に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのプライマリ レプリカが存在する場合の選択したパーティションのアクティブなセカンダリ レプリカに既に存在新しいノードFabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがセカンダリではない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-330">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - Active secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="215e8-331">移動する場合に選択したレプリカが現在存在するノード名</span><span class="sxs-lookup"><span data-stu-id="215e8-331">node name where selected replica for move is currently present</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-332">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-332">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="215e8-333">移動を実行しようとするときに制約を無視するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-333">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-334">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-334">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-335">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-335">A task with move secondary result</span></span></returns>
        <remarks><span data-ttu-id="215e8-336">API は、currentNodeName で指定されたパーティション セレクター構造内の選択したセカンダリ レプリカを使用します。</span><span class="sxs-lookup"><span data-stu-id="215e8-336">API uses the selected secondary replica inside partition selector structure specified by currentNodeName.</span></span> <span data-ttu-id="215e8-337">この API のオーバー ロードは、この選択したレプリカは現在のノードの場所から新しいノードの場所に移動するレプリカの移動のための新しいセカンダリ ノードをランダムに選択します。</span><span class="sxs-lookup"><span data-stu-id="215e8-337">This API overload randomly selects new secondary node for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="215e8-338">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-338">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-339">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-339">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-340">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-340">Invalid operation</span></span>
            - <span data-ttu-id="215e8-341">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-341">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-342">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-342">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-343">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-343">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-344">FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - レプリカが移動される場合はセカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合</span><span class="sxs-lookup"><span data-stu-id="215e8-344">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the replica being moved is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__74))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="215e8-345">移動する場合に選択したレプリカが現在存在するノード名</span><span class="sxs-lookup"><span data-stu-id="215e8-345">node name where selected replica for move is currently present</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-346">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-346">Move Secondary will be called on this Selected Partition.</span></span>
            </param>
        <param name="token"><span data-ttu-id="215e8-347">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-347">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-348">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-348">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-349">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-349">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-350">API は、currentNodeName で指定されたパーティション セレクター構造内の選択したセカンダリ レプリカを使用します。</span><span class="sxs-lookup"><span data-stu-id="215e8-350">API uses the selected secondary replica inside partition selector structure specified by currentNodeName.</span></span> <span data-ttu-id="215e8-351">この API のオーバー ロードは、この選択したレプリカは現在のノードの場所から新しいノードの場所に移動するレプリカの移動のための新しいセカンダリ ノードをランダムに選択します。</span><span class="sxs-lookup"><span data-stu-id="215e8-351">This API overload randomly selects new secondary node for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="215e8-352">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-352">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-353">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-353">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-354">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-354">Invalid operation</span></span>
            - <span data-ttu-id="215e8-355">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-355">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-356">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-356">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-357">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-357">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-358">FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合</span><span class="sxs-lookup"><span data-stu-id="215e8-358">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="215e8-359">移動する場合に選択したレプリカが現在存在するノード名</span><span class="sxs-lookup"><span data-stu-id="215e8-359">node name where selected replica for move is currently present</span></span></param>
        <param name="newNodeName"><span data-ttu-id="215e8-360">ノード名の選択されたレプリカを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-360">node name where selected replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-361">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-361">Move Secondary will be called on this Selected Partition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="215e8-362">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-362">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-363">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-363">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-364">API は、currentNodeName で指定された、選択したセカンダリ レプリカを使用および newNodeName で指定されたノードの新しい場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-364">API uses the selected secondary replica specified by currentNodeName and moves it to new node location specified by newNodeName.</span></span>
            <span data-ttu-id="215e8-365">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-365">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-366">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-366">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-367">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-367">Invalid operation</span></span>
            - <span data-ttu-id="215e8-368">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-368">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-369">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-369">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-370">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-370">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-371">FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合</span><span class="sxs-lookup"><span data-stu-id="215e8-371">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__81))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="215e8-372">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-372">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="215e8-373">移動を実行しようとするときに制約を無視するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-373">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-374">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="215e8-374">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-375">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-375">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-376">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-376">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-377">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-377">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-378">API は、指定されたパーティションのセレクターをランダムに選択したセカンダリ レプリカを使用します。</span><span class="sxs-lookup"><span data-stu-id="215e8-378">API uses the randomly selected secondary replica for specified partition selector.</span></span>
            <span data-ttu-id="215e8-379">この API のオーバー ロードは、この選択したレプリカは現在のノードの場所から新しいノードの場所に移動するレプリカの移動のための新しいセカンダリ ノード位置をランダムに選択します。</span><span class="sxs-lookup"><span data-stu-id="215e8-379">This API overload randomly selects new secondary node location for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="215e8-380">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-380">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-381">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-381">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-382">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-382">Invalid operation</span></span>
            - <span data-ttu-id="215e8-383">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-383">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-384">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-384">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-385">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-385">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-386">FabricErrorCode.AlreadyPrimaryReplica - に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのプライマリ レプリカが存在する場合の選択したパーティションのアクティブなセカンダリ レプリカに既に存在新しいノードFabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがセカンダリではない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-386">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - Active secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="215e8-387">移動する場合に選択したレプリカが現在存在するノード名</span><span class="sxs-lookup"><span data-stu-id="215e8-387">node name where selected replica for move is currently present</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-388">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-388">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="215e8-389">移動を実行しようとするときに制約を無視するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-389">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-390">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-390">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-391">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-391">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-392">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-392">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-393">API は、currentNodeName で指定されたパーティション セレクター構造内の選択したセカンダリ レプリカを使用します。</span><span class="sxs-lookup"><span data-stu-id="215e8-393">API uses the selected secondary replica inside partition selector structure specified by currentNodeName.</span></span> <span data-ttu-id="215e8-394">この API のオーバー ロードは、この選択したレプリカは現在のノードの場所から新しいノードの場所に移動するレプリカの移動のための新しいセカンダリ ノードをランダムに選択します。</span><span class="sxs-lookup"><span data-stu-id="215e8-394">This API overload randomly selects new secondary node for replica movement This selected replica will be moved to new node location from current node location.</span></span>
            <span data-ttu-id="215e8-395">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-395">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-396">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-396">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-397">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-397">Invalid operation</span></span>
            - <span data-ttu-id="215e8-398">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-398">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-399">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-399">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-400">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-400">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-401">FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合</span><span class="sxs-lookup"><span data-stu-id="215e8-401">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__80))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="215e8-402">移動する場合に選択したレプリカが現在存在するノード名</span><span class="sxs-lookup"><span data-stu-id="215e8-402">node name where selected replica for move is currently present</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-403">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-403">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-404">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="215e8-404">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-405">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-405">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-406">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-406">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-407">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-407">A task with move secondary result</span></span></returns>
        <remarks><span data-ttu-id="215e8-408">API は、currentNodeName で指定された、選択したセカンダリ レプリカを使用します。</span><span class="sxs-lookup"><span data-stu-id="215e8-408">API uses the selected secondary replica specified by currentNodeName.</span></span>
            <span data-ttu-id="215e8-409">この選択したレプリカは、ランダムに選択されたノードの新しい場所に移動されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-409">This selected replica will be moved to the randomly selected new node location.</span></span>
            <span data-ttu-id="215e8-410">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-410">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-411">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-411">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-412">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-412">Invalid operation</span></span>
            - <span data-ttu-id="215e8-413">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-413">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-414">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-414">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-415">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-415">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-416">FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合</span><span class="sxs-lookup"><span data-stu-id="215e8-416">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="215e8-417">移動する場合に選択したレプリカが現在存在するノード名</span><span class="sxs-lookup"><span data-stu-id="215e8-417">node name where selected replica for move is currently present</span></span></param>
        <param name="newNodeName"><span data-ttu-id="215e8-418">ノード名の選択されたレプリカを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-418">node name where selected replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-419">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-419">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="215e8-420">移動を実行しようとするときに制約を無視するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-420">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-421">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-421">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-422">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-422">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-423">API は、currentNodeName で指定された、選択したセカンダリ レプリカを使用および newNodeName で指定されたノードの新しい場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-423">API uses the selected secondary replica specified by currentNodeName and moves it to new node location specified by newNodeName.</span></span>
            <span data-ttu-id="215e8-424">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-424">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-425">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-425">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-426">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-426">Invalid operation</span></span>
            - <span data-ttu-id="215e8-427">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-427">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-428">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-428">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-429">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-429">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-430">FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合</span><span class="sxs-lookup"><span data-stu-id="215e8-430">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__78))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="215e8-431">移動する場合に選択したレプリカが現在存在するノード名</span><span class="sxs-lookup"><span data-stu-id="215e8-431">node name where selected replica for move is currently present</span></span></param>
        <param name="newNodeName"><span data-ttu-id="215e8-432">ノード名の選択されたレプリカを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-432">node name where selected replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-433">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-433">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-434">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-434">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-435">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-435">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-436">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-436">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-437">API は、currentNodeName で指定された、選択したセカンダリ レプリカを使用および newNodeName で指定されたノードの新しい場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-437">API uses the selected secondary replica specified by currentNodeName and moves it to new node location specified by newNodeName.</span></span>
            <span data-ttu-id="215e8-438">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-438">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-439">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-439">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-440">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-440">Invalid operation</span></span>
            - <span data-ttu-id="215e8-441">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-441">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-442">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-442">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-443">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-443">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-444">FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合</span><span class="sxs-lookup"><span data-stu-id="215e8-444">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__79))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="215e8-445">移動する場合に選択したレプリカが現在存在するノード名</span><span class="sxs-lookup"><span data-stu-id="215e8-445">node name where selected replica for move is currently present</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-446">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-446">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="215e8-447">移動を実行しようとするときに制約を無視するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-447">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-448">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="215e8-448">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-449">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-449">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-450">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-450">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-451">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-451">A task with move secondary result</span></span></returns>
        <remarks><span data-ttu-id="215e8-452">API は、currentNodeName で指定された、選択したセカンダリ レプリカを使用します。</span><span class="sxs-lookup"><span data-stu-id="215e8-452">API uses the selected secondary replica specified by currentNodeName.</span></span>
            <span data-ttu-id="215e8-453">この選択したレプリカは、ランダムに選択されたノードの新しい場所に移動されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-453">This selected replica will be moved to the randomly selected new node location.</span></span>
            <span data-ttu-id="215e8-454">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-454">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-455">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-455">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-456">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-456">Invalid operation</span></span>
            - <span data-ttu-id="215e8-457">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-457">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-458">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-458">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-459">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-459">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-460">FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合</span><span class="sxs-lookup"><span data-stu-id="215e8-460">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="215e8-461">移動する場合に選択したレプリカが現在存在するノード名</span><span class="sxs-lookup"><span data-stu-id="215e8-461">node name where selected replica for move is currently present</span></span></param>
        <param name="newNodeName"><span data-ttu-id="215e8-462">ノード名の選択されたレプリカを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-462">node name where selected replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-463">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-463">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="215e8-464">移動を実行しようとするときに制約を無視するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-464">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-465">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-465">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-466">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-466">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-467">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-467">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-468">API は、currentNodeName で指定された、選択したセカンダリ レプリカを使用および newNodeName で指定されたノードの新しい場所に移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-468">API uses the selected secondary replica specified by currentNodeName and moves it to new node location specified by newNodeName.</span></span>
            <span data-ttu-id="215e8-469">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-469">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-470">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-470">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-471">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-471">Invalid operation</span></span>
            - <span data-ttu-id="215e8-472">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-472">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-473">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-473">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-474">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-474">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-475">FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合</span><span class="sxs-lookup"><span data-stu-id="215e8-475">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - If active Secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary FabricErrorCode.ConstraintNotSatisfied - If the constraints for the new location of the replica would prohibit the move</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__84))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="215e8-476">移動する場合に選択したレプリカが現在存在するノード名</span><span class="sxs-lookup"><span data-stu-id="215e8-476">node name where selected replica for move is currently present</span></span></param>
        <param name="newNodeName"><span data-ttu-id="215e8-477">ノード名の選択されたレプリカを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-477">node name where selected replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-478">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-478">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-479">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="215e8-479">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-480">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-480">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-481">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-481">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-482">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-482">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-483">API は、currentNodeName 場所で指定されたパーティション セレクター構造内の選択したセカンダリ レプリカを使用します。</span><span class="sxs-lookup"><span data-stu-id="215e8-483">API uses the selected secondary replica inside partition selector structure specified by currentNodeName location.</span></span> <span data-ttu-id="215e8-484">この選択したレプリカは、現在のノードの場所から newNodeName 場所に移動されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-484">This selected replica will be moved to newNodeName location from current node location.</span></span>
            <span data-ttu-id="215e8-485">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-485">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-486">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-486">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-487">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-487">Invalid operation</span></span>
            - <span data-ttu-id="215e8-488">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-488">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-489">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-489">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-490">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-490">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-491">FabricErrorCode.AlreadyPrimaryReplica - に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのプライマリ レプリカが存在する場合の選択したパーティションのアクティブなセカンダリ レプリカに既に存在新しいノードFabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがセカンダリではない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-491">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - Active secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__83))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName"><span data-ttu-id="215e8-492">移動する場合に選択したレプリカが現在存在するノード名</span><span class="sxs-lookup"><span data-stu-id="215e8-492">node name where selected replica for move is currently present</span></span></param>
        <param name="newNodeName"><span data-ttu-id="215e8-493">ノード名の選択されたレプリカを移動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-493">node name where selected replica to be moved</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="215e8-494">移動セカンダリは、この選択したパーティションに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-494">Move Secondary will be called on this Selected Partition.</span></span></param>
        <param name="ignoreConstraints"><span data-ttu-id="215e8-495">移動を実行しようとするときに制約を無視するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-495">Whether or not to ignore constraints when attempting to execute the move.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-496">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="215e8-496">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-497">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-497">The cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-498">移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。</span><span class="sxs-lookup"><span data-stu-id="215e8-498">Moves selected secondary replica from current node to new node in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-499">移動セカンダリ結果のタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-499">A task with move secondary result</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-500">API は、currentNodeName 場所で指定されたパーティション セレクター構造内の選択したセカンダリ レプリカを使用します。</span><span class="sxs-lookup"><span data-stu-id="215e8-500">API uses the selected secondary replica inside partition selector structure specified by currentNodeName location.</span></span> <span data-ttu-id="215e8-501">この選択したレプリカは、現在のノードの場所から newNodeName 場所に移動されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-501">This selected replica will be moved to newNodeName location from current node location.</span></span>
            <span data-ttu-id="215e8-502">この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</span><span class="sxs-lookup"><span data-stu-id="215e8-502">This API is safe i.e. it will not cause quorum or data loss by itself unless additional faults or failures happen at the same time.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-503">再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="215e8-503">Retry is exhausted.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-504">操作が無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-504">Invalid operation</span></span>
            - <span data-ttu-id="215e8-505">アクションは、ステートレス サービスに対して呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-505">If action called on stateless service.</span></span>
            - <span data-ttu-id="215e8-506">アクティブなセカンダリ レプリカが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-506">If no active secondary replica exists</span></span>
            - <span data-ttu-id="215e8-507">十分な数のノードは処理で使用しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-507">If not enough nodes available for action</span></span>
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            <span data-ttu-id="215e8-508">FabricErrorCode.AlreadyPrimaryReplica - に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのプライマリ レプリカが存在する場合の選択したパーティションのアクティブなセカンダリ レプリカに既に存在新しいノードFabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがセカンダリではない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-508">FabricErrorCode.AlreadyPrimaryReplica - If Primary replica for selected partition already exist on new node FabricErrorCode.AlreadySecondaryReplica - Active secondary replica for selected partition already exist on new node FabricErrorCode.InvalidReplicaStateForReplicaOperation - If the target replica is not a secondary</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, bool forceRemove);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (replicaSelector, completionMode, forceRemove)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="215e8-509"><see cref="T:System.Fabric.ReplicaSelector" />レプリカを削除することを示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-509">The <see cref="T:System.Fabric.ReplicaSelector" /> which indicates the replica to be removed.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-510"><see cref="T:System.Fabric.CompletionMode" />レプリカの削除が完了するか、FM vie.w 外 DoNotVerify できません - レプリカを確認してください - 戻り値が終わったら、削除など、レプリカの削除をトリガーして返されるはまで待機するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-510">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the remove of the replica is complete or not DoNotVerify - Return after triggering the remove of the replica Verify - Return after the remove completes i.e. the replica is out of the FM vie.w</span></span></param>
        <param name="forceRemove"><span data-ttu-id="215e8-511">レプリカは強制的に削除されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-511">Will forcefully remove the replica</span></span></param>
        <summary>
            <span data-ttu-id="215e8-512">この API は、渡されたで指定されたレプリカ (ReportFault - 永続的であるのと同等) を削除で<see cref="T:System.Fabric.ReplicaSelector" />です。</span><span class="sxs-lookup"><span data-stu-id="215e8-512">This API will remove the replica (equivalent of ReportFault - Permanent) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-513">RemoveReplicaResult が実際に選択したレプリカに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="215e8-513">RemoveReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-514">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-514">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-515">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-515">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-516">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</span><span class="sxs-lookup"><span data-stu-id="215e8-516">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, bool forceRemove, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (replicaSelector, completionMode, forceRemove, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="215e8-517"><see cref="T:System.Fabric.ReplicaSelector" />レプリカを削除することを示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-517">The <see cref="T:System.Fabric.ReplicaSelector" /> which indicates the replica to be removed.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-518"><see cref="T:System.Fabric.CompletionMode" />レプリカの削除が完了するか、FM ビューから外れて DoNotVerify できません - レプリカを確認してください - 戻り値が終わったら、削除など、レプリカの削除をトリガーして返されるはまで待機するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-518">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the remove of the replica is complete or not DoNotVerify - Return after triggering the remove of the replica Verify - Return after the remove completes i.e. the replica is out of the FM view</span></span></param>
        <param name="forceRemove"><span data-ttu-id="215e8-519">レプリカは強制的に削除されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-519">Will forcefully remove the replica</span></span></param>
        <param name="token"><span data-ttu-id="215e8-520">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-520">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-521">この API は、渡されたで指定されたレプリカ (ReportFault - 永続的であるのと同等) を削除で<see cref="T:System.Fabric.ReplicaSelector" />です。</span><span class="sxs-lookup"><span data-stu-id="215e8-521">This API will remove the replica (equivalent of ReportFault - Permanent) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-522">RemoveReplicaResult が実際に選択したレプリカに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="215e8-522">RemoveReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-523">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-523">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-524">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-524">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-525">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</span><span class="sxs-lookup"><span data-stu-id="215e8-525">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, bool forceRemove, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (replicaSelector, completionMode, forceRemove, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="215e8-526"><see cref="T:System.Fabric.ReplicaSelector" />レプリカを削除することを示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-526">The <see cref="T:System.Fabric.ReplicaSelector" /> which indicates the replica to be removed.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-527"><see cref="T:System.Fabric.CompletionMode" />レプリカの削除が完了するか、FM ビューから外れて DoNotVerify できません - レプリカを確認してください - 戻り値が終わったら、削除など、レプリカの削除をトリガーして返されるはまで待機するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-527">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the remove of the replica is complete or not DoNotVerify - Return after triggering the remove of the replica Verify - Return after the remove completes i.e. the replica is out of the FM view.</span></span></param>
        <param name="forceRemove"><span data-ttu-id="215e8-528">レプリカが強制的に削除されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-528">Will forcefully remove the replica.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-529">レプリカを削除するを待機するタイムアウトを含む、操作の全体的なタイムアウト<see cref="T:System.Fabric.CompletionMode" />を確認してください</span><span class="sxs-lookup"><span data-stu-id="215e8-529">The overall timeout for the operation including the timeout to wait for replica to be removed if <see cref="T:System.Fabric.CompletionMode" /> is Verify</span></span></param>
        <param name="token"><span data-ttu-id="215e8-530">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-530">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-531">この API は、渡されたで指定されたレプリカ (ReportFault - 永続的であるのと同等) を削除で<see cref="T:System.Fabric.ReplicaSelector" />です。</span><span class="sxs-lookup"><span data-stu-id="215e8-531">This API will remove the replica (equivalent of ReportFault - Permanent) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-532">RemoveReplicaResult が実際に選択したレプリカに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="215e8-532">RemoveReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-533">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-533">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-534">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-534">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-535">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</span><span class="sxs-lookup"><span data-stu-id="215e8-535">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, bool forceRemove);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaId, completionMode, forceRemove)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-536">レプリカを移動するノード名<see cref="T:System.Fabric.ReplicaSelector" /></span><span class="sxs-lookup"><span data-stu-id="215e8-536">Node name where replica is to be moved <see cref="T:System.Fabric.ReplicaSelector" /></span></span></param>
        <param name="partitionId"><span data-ttu-id="215e8-537">パーティション、レプリカを削除する必要がある Id</span><span class="sxs-lookup"><span data-stu-id="215e8-537">Partition Id where the replica needs to be removed</span></span> </param>
        <param name="replicaId"><span data-ttu-id="215e8-538">削除する必要があるレプリカ Id</span><span class="sxs-lookup"><span data-stu-id="215e8-538">Replica Id that needs to be removed</span></span> </param>
        <param name="completionMode"><span data-ttu-id="215e8-539"><see cref="T:System.Fabric.CompletionMode" />いない DoNotVerify またはレプリカの再起動が完了するまで待機するかどうかを指定する - トリガーを確認してください - 戻り値の削除が完了した後、レプリカの再起動後に返されます</span><span class="sxs-lookup"><span data-stu-id="215e8-539">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the replica is complete or not DoNotVerify - Return after triggering the restart of the replica Verify - Return after the remove completes</span></span></param>
        <param name="forceRemove"><span data-ttu-id="215e8-540">レプリカは強制的に削除されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-540">Will forcefully remove the replica</span></span></param>
        <summary>
            <span data-ttu-id="215e8-541">この API は、渡されたで指定されたレプリカ (ReportFault - 永続的であるのと同等) を削除で<see cref="T:System.Fabric.ReplicaSelector" />です。</span><span class="sxs-lookup"><span data-stu-id="215e8-541">This API will remove the replica (equivalent of ReportFault - Permanent) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-542">RemoveReplicaResult が実際に選択したレプリカに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="215e8-542">RemoveReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-543">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-543">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-544">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-544">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-545">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</span><span class="sxs-lookup"><span data-stu-id="215e8-545">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, bool forceRemove, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaId, completionMode, forceRemove, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-546">レプリカを移動するノード名<see cref="T:System.Fabric.ReplicaSelector" /></span><span class="sxs-lookup"><span data-stu-id="215e8-546">Node name where replica is to be moved <see cref="T:System.Fabric.ReplicaSelector" /></span></span></param>
        <param name="partitionId"><span data-ttu-id="215e8-547">パーティション、レプリカを削除する必要がある Id</span><span class="sxs-lookup"><span data-stu-id="215e8-547">Partition Id where the replica needs to be removed</span></span> </param>
        <param name="replicaId"><span data-ttu-id="215e8-548">削除する必要があるレプリカ Id</span><span class="sxs-lookup"><span data-stu-id="215e8-548">Replica Id that needs to be removed</span></span> </param>
        <param name="completionMode"><span data-ttu-id="215e8-549"><see cref="T:System.Fabric.CompletionMode" />レプリカの削除が完了するか、FM ビューから外れて DoNotVerify できません - レプリカを確認してください - 戻り値が終わったら、削除など、レプリカの削除をトリガーして返されるはまで待機するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-549">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the remove of the replica is complete or not DoNotVerify - Return after triggering the remove of the replica Verify - Return after the remove completes i.e. the replica is out of the FM view.</span></span></param>
        <param name="forceRemove"><span data-ttu-id="215e8-550">レプリカは強制的に削除されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-550">Will forcefully remove the replica</span></span></param>
        <param name="token"><span data-ttu-id="215e8-551">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-551">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-552">この API は、渡されたで指定されたレプリカ (ReportFault - 永続的であるのと同等) を削除で<see cref="T:System.Fabric.ReplicaSelector" />です。</span><span class="sxs-lookup"><span data-stu-id="215e8-552">This API will remove the replica (equivalent of ReportFault - Permanent) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-553">RemoveReplicaResult が実際に選択したレプリカに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="215e8-553">RemoveReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-554">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-554">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-555">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-555">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-556">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</span><span class="sxs-lookup"><span data-stu-id="215e8-556">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, bool forceRemove, double operationTimeoutSec, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove, float64 operationTimeoutSec, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Boolean,System.Double,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * bool * double * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaId, completionMode, forceRemove, operationTimeoutSec, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="operationTimeoutSec" Type="System.Double" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-557">レプリカを移動するノード名<see cref="T:System.Fabric.ReplicaSelector" /></span><span class="sxs-lookup"><span data-stu-id="215e8-557">Node name where replica is to be moved <see cref="T:System.Fabric.ReplicaSelector" /></span></span></param>
        <param name="partitionId"><span data-ttu-id="215e8-558">パーティション、レプリカを削除する必要がある Id</span><span class="sxs-lookup"><span data-stu-id="215e8-558">Partition Id where the replica needs to be removed</span></span> </param>
        <param name="replicaId"><span data-ttu-id="215e8-559">削除する必要があるレプリカ Id</span><span class="sxs-lookup"><span data-stu-id="215e8-559">Replica Id that needs to be removed</span></span> </param>
        <param name="completionMode"><span data-ttu-id="215e8-560"><see cref="T:System.Fabric.CompletionMode" />いない DoNotVerify またはレプリカの再起動が完了するまで待機するかどうかを指定する - トリガーを確認してください - 戻り値の削除が完了した後、レプリカの再起動後に返されます</span><span class="sxs-lookup"><span data-stu-id="215e8-560">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the replica is complete or not DoNotVerify - Return after triggering the restart of the replica Verify - Return after the remove completes</span></span></param>
        <param name="forceRemove"><span data-ttu-id="215e8-561">レプリカが強制的に削除されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-561">Will forcefully remove the replica.</span></span></param>
        <param name="operationTimeoutSec"><span data-ttu-id="215e8-562">レプリカを削除するを待機するタイムアウトを含む操作は、秒単位で全体的タイムアウト<see cref="T:System.Fabric.CompletionMode" />を確認してください</span><span class="sxs-lookup"><span data-stu-id="215e8-562">The overall timeout in seconds for the operation, including the timeout to wait for replica to be removed if <see cref="T:System.Fabric.CompletionMode" /> is Verify</span></span></param>
        <param name="token"><span data-ttu-id="215e8-563">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-563">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-564">この API は、渡されたで指定されたレプリカ (ReportFault - 永続的であるのと同等) を削除で<see cref="T:System.Fabric.ReplicaSelector" />です。</span><span class="sxs-lookup"><span data-stu-id="215e8-564">This API will remove the replica (equivalent of ReportFault - Permanent) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-565">RemoveReplicaResult が実際に選択したレプリカに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="215e8-565">RemoveReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-566">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-566">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-567">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-567">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-568">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</span><span class="sxs-lookup"><span data-stu-id="215e8-568">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (Uri applicationName, System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(class System.Uri applicationName, class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.Uri,System.Fabric.ReplicaSelector,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : Uri * System.Fabric.ReplicaSelector * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (applicationName, replicaSelector, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="215e8-569">コード パッケージが所属するアプリケーションの名前</span><span class="sxs-lookup"><span data-stu-id="215e8-569">The name of the application to which the code package belongs</span></span></param>
        <param name="replicaSelector"><span data-ttu-id="215e8-570"><see cref="T:System.Fabric.ReplicaSelector" />識別、レプリカがホスト コード パッケージが再起動する必要があります。</span><span class="sxs-lookup"><span data-stu-id="215e8-570">The <see cref="T:System.Fabric.ReplicaSelector" /> which identifies the replica whose host code package needs to be restarted.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-571"><see cref="T:System.Fabric.CompletionMode" />か、コード パッケージの再起動が完了するまで待機するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-571">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-572">この API 呼び出しで指定されたレプリカをホストしているコード パッケージが再起動、<see cref="T:System.Fabric.ReplicaSelector" />指定されたアプリケーション名に属しているとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-572">This API call restarts the code package which hosts the replica specified by the <see cref="T:System.Fabric.ReplicaSelector" /> and belongs to the specified application name.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-573">RestartDeployedCodePackageResult が実際のコード パッケージが再起動し、選択されているレプリカに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="215e8-573">RestartDeployedCodePackageResult which gives information about the actual code package restarted and replica selected.</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-574"><see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。</span><span class="sxs-lookup"><span data-stu-id="215e8-574">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-575">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-575">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-576">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-576">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-577">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、指定されたパーティションが選択されている FabricErrorCode.CodePackageNotFound が存在しません - 選択したレプリカが FabricErrorCode.PartitionNotFound が見つからない場合、選択したコードパッケージが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="215e8-577">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist FabricErrorCode.CodePackageNotFound - If the selected code package was not found</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-578">コード パッケージが有効な実行中状態ではありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-578">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (Uri applicationName, System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(class System.Uri applicationName, class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.Uri,System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : Uri * System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (applicationName, replicaSelector, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="215e8-579">コードが belong.s をパッケージ化するアプリケーションの名前</span><span class="sxs-lookup"><span data-stu-id="215e8-579">The name of the application to which the code package belong.s</span></span></param>
        <param name="replicaSelector"><span data-ttu-id="215e8-580"><see cref="T:System.Fabric.ReplicaSelector" />識別、レプリカがホスト コード パッケージが再起動する必要があります。</span><span class="sxs-lookup"><span data-stu-id="215e8-580">The <see cref="T:System.Fabric.ReplicaSelector" /> which identifies the replica whose host code package needs to be restarted.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-581"><see cref="T:System.Fabric.CompletionMode" />か、コード パッケージの再起動が完了するまで待機するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-581">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-582">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-582">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-583">この API 呼び出しで指定されたレプリカをホストしているコード パッケージが再起動、<see cref="T:System.Fabric.ReplicaSelector" />指定されたアプリケーション名に属しているとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-583">This API call restarts the code package which hosts the replica specified by the <see cref="T:System.Fabric.ReplicaSelector" /> and belongs to the specified application name.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-584">RestartDeployedCodePackageResult が実際のコード パッケージが再起動し、選択されているレプリカに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="215e8-584">RestartDeployedCodePackageResult which gives information about the actual code package restarted and replica selected.</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-585"><see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。</span><span class="sxs-lookup"><span data-stu-id="215e8-585">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-586">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-586">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-587">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-587">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-588">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、指定されたパーティションが選択されている FabricErrorCode.CodePackageNotFound が存在しません - 選択したレプリカが FabricErrorCode.PartitionNotFound が見つからない場合、選択したコードパッケージが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="215e8-588">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist FabricErrorCode.CodePackageNotFound - If the selected code package was not found.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-589">コード パッケージが有効な実行中状態ではありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-589">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (Uri applicationName, System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(class System.Uri applicationName, class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.Uri,System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : Uri * System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (applicationName, replicaSelector, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="215e8-590">コード パッケージが所属するアプリケーションの名前</span><span class="sxs-lookup"><span data-stu-id="215e8-590">The name of the application to which the code package belongs</span></span></param>
        <param name="replicaSelector"><span data-ttu-id="215e8-591"><see cref="T:System.Fabric.ReplicaSelector" />識別、レプリカがホスト コード パッケージが再起動する必要があります。</span><span class="sxs-lookup"><span data-stu-id="215e8-591">The <see cref="T:System.Fabric.ReplicaSelector" /> which identifies the replica whose host code package needs to be restarted.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-592"><see cref="T:System.Fabric.CompletionMode" /> Not.n またはコード パッケージの再起動が完了するまで待機するかどうかを指定します</span><span class="sxs-lookup"><span data-stu-id="215e8-592">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.n</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-593">コード パッケージを再起動するまで待機するタイムアウトを含む、操作の全体的なタイムアウト<see cref="T:System.Fabric.CompletionMode" />を確認してください</span><span class="sxs-lookup"><span data-stu-id="215e8-593">The overall timeout for the operation including the timeout to wait for code package to restart if <see cref="T:System.Fabric.CompletionMode" /> is Verify</span></span></param>
        <param name="token"><span data-ttu-id="215e8-594">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="215e8-594">Cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-595">この API 呼び出しで指定されたレプリカをホストしているコード パッケージが再起動、<see cref="T:System.Fabric.ReplicaSelector" />指定されたアプリケーション名に属しているとします。</span><span class="sxs-lookup"><span data-stu-id="215e8-595">This API call restarts the code package which hosts the replica specified by the <see cref="T:System.Fabric.ReplicaSelector" /> and belongs to the specified application name.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-596">RestartDeployedCodePackageResult が実際のコード パッケージが再起動し、選択されているレプリカに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="215e8-596">RestartDeployedCodePackageResult which gives information about the actual code package restarted and replica selected.</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-597"><see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。</span><span class="sxs-lookup"><span data-stu-id="215e8-597">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-598">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-598">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-599">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-599">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-600">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、指定されたパーティションが選択されている FabricErrorCode.CodePackageNotFound が存在しません - 選択したレプリカが FabricErrorCode.PartitionNotFound が見つからない場合、選択したコードパッケージが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="215e8-600">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist FabricErrorCode.CodePackageNotFound - If the selected code package was not found</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-601">コード パッケージが有効な実行中状態ではありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-601">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.Int64,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * int64 * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, codePackageName, codePackageInstanceId, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-602">コード パッケージがホストされているノードです。</span><span class="sxs-lookup"><span data-stu-id="215e8-602">The node on which the code package is hosted.</span></span></param>
        <param name="applicationName"><span data-ttu-id="215e8-603">コード パッケージが所属するアプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="215e8-603">The name of the application to which the code package belongs.</span></span></param>
        <param name="serviceManifestName"><span data-ttu-id="215e8-604">コード パッケージが定義されているサービス マニフェストの名前。</span><span class="sxs-lookup"><span data-stu-id="215e8-604">The name of the service manifest where the code package is defined.</span></span></param>
        <param name="codePackageName"><span data-ttu-id="215e8-605">再起動するコード パッケージの名前</span><span class="sxs-lookup"><span data-stu-id="215e8-605">The name of the code package to be restarted</span></span></param>
        <param name="codePackageInstanceId"><span data-ttu-id="215e8-606">指定されていてと一致しませんし、再起動場合は処理されません、値は 0、比較を実行中のコード パッケージのコード パッケージ インスタンス id はスキップされます。</span><span class="sxs-lookup"><span data-stu-id="215e8-606">The code package instance id for the running code package which if specified and does not match then the restart is not processed If the value is 0 then the comparison is skipped.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-607"><see cref="T:System.Fabric.CompletionMode" />か、コード パッケージの再起動が完了するまで待機するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-607">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-608">この API 呼び出しでは、入力パラメーターで指定されたコード パッケージが再起動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-608">This API call restarts the code package as specified by the input parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-609">実際のコード パッケージについての情報」に進んで RestartDeployedCodePackageResult が再起動されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-609">RestartDeployedCodePackageResult which gives information about the actual code package restarted.</span></span> <span data-ttu-id="215e8-610">SelectedReplica はこのオーバー ロードでは None です。</span><span class="sxs-lookup"><span data-stu-id="215e8-610">SelectedReplica is None in this overload.</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-611"><see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。</span><span class="sxs-lookup"><span data-stu-id="215e8-611">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-612">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-612">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-613">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-613">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-614">これらは、ファブリック エラー FabricErrorCode.CodePackageNotFound - 選択したコード パッケージが見つかりませんでした FabricErrorCode.InstanceIdMismatch - 指定したインスタンス id が一致しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-614">These are the fabric failures FabricErrorCode.CodePackageNotFound - If the selected code package was not found FabricErrorCode.InstanceIdMismatch - If the specified instance id did not match</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-615">コード パッケージが有効な実行中状態ではありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-615">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.Int64,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * int64 * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, codePackageName, codePackageInstanceId, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-616">コード パッケージがホストされているノード</span><span class="sxs-lookup"><span data-stu-id="215e8-616">The node on which the code package is hosted</span></span></param>
        <param name="applicationName"><span data-ttu-id="215e8-617">コード パッケージが所属するアプリケーションの名前</span><span class="sxs-lookup"><span data-stu-id="215e8-617">The name of the application to which the code package belongs</span></span></param>
        <param name="serviceManifestName"><span data-ttu-id="215e8-618">コード パッケージが定義されているサービス マニフェストの名前</span><span class="sxs-lookup"><span data-stu-id="215e8-618">The name of the service manifest where the code package is defined</span></span></param>
        <param name="codePackageName"><span data-ttu-id="215e8-619">再起動するコード パッケージの名前</span><span class="sxs-lookup"><span data-stu-id="215e8-619">The name of the code package to be restarted</span></span></param>
        <param name="codePackageInstanceId"><span data-ttu-id="215e8-620">指定されていてと一致しませんし、再起動場合は処理されません、値は 0、比較を実行中のコード パッケージのコード パッケージ インスタンス id はスキップされます。</span><span class="sxs-lookup"><span data-stu-id="215e8-620">The code package instance id for the running code package which if specified and does not match then the restart is not processed If the value is 0 then the comparison is skipped</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-621"><see cref="T:System.Fabric.CompletionMode" />か、コード パッケージの再起動が完了するまで待機するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-621">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-622">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-622">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-623">この API 呼び出しでは、入力パラメーターで指定されたコード パッケージが再起動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-623">This API call restarts the code package as specified by the input parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-624">実際のコード パッケージについての情報」に進んで RestartDeployedCodePackageResult が再起動されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-624">RestartDeployedCodePackageResult which gives information about the actual code package restarted.</span></span> <span data-ttu-id="215e8-625">SelectedReplica はこのオーバー ロードでは None です。</span><span class="sxs-lookup"><span data-stu-id="215e8-625">SelectedReplica is None in this overload.</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-626"><see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。</span><span class="sxs-lookup"><span data-stu-id="215e8-626">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-627">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-627">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-628">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-628">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-629">これらは、ファブリック エラー FabricErrorCode.CodePackageNotFound - 選択したコード パッケージが見つかりませんでした FabricErrorCode.InstanceIdMismatch - 指定したインスタンス id が一致しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-629">These are the fabric failures FabricErrorCode.CodePackageNotFound - If the selected code package was not found FabricErrorCode.InstanceIdMismatch - If the specified instance id did not match</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-630">コード パッケージが有効な実行中状態ではありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-630">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.String,System.Int64,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * string * int64 * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, servicePackageActivationId, codePackageName, codePackageInstanceId, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-631">コード パッケージがホストされているノードです。</span><span class="sxs-lookup"><span data-stu-id="215e8-631">The node on which the code package is hosted.</span></span></param>
        <param name="applicationName"><span data-ttu-id="215e8-632">コード パッケージが所属するアプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="215e8-632">The name of the application to which the code package belongs.</span></span></param>
        <param name="serviceManifestName"><span data-ttu-id="215e8-633">コード パッケージが定義されているサービス マニフェストの名前。</span><span class="sxs-lookup"><span data-stu-id="215e8-633">The name of the service manifest where the code package is defined.</span></span></param>
        <param name="servicePackageActivationId">
          <para>
            <span data-ttu-id="215e8-634"><see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />コード パッケージが含まれている展開済みサービス パッケージのです。</span><span class="sxs-lookup"><span data-stu-id="215e8-634">The <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package which contains the code package.</span></span> <span data-ttu-id="215e8-635">使用して、展開済みサービス パッケージの ServicePackageActivationId を取得できます<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />クエリ。</span><span class="sxs-lookup"><span data-stu-id="215e8-635">You can get the ServicePackageActivationId of a deployed service package by using <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> query.</span></span> 
            </para>
          <para>
            <span data-ttu-id="215e8-636">場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />の作成時に指定された、サービスは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。</span><span class="sxs-lookup"><span data-stu-id="215e8-636">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service was <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it was not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="215e8-637">詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。</span><span class="sxs-lookup"><span data-stu-id="215e8-637">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </param>
        <param name="codePackageName"><span data-ttu-id="215e8-638">再起動するコード パッケージの名前</span><span class="sxs-lookup"><span data-stu-id="215e8-638">The name of the code package to be restarted</span></span></param>
        <param name="codePackageInstanceId"><span data-ttu-id="215e8-639">指定されていてと一致しませんし、再起動場合は処理されません、値は 0、比較を実行中のコード パッケージのコード パッケージ インスタンス id はスキップされます。</span><span class="sxs-lookup"><span data-stu-id="215e8-639">The code package instance id for the running code package which if specified and does not match then the restart is not processed If the value is 0 then the comparison is skipped.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-640"><see cref="T:System.Fabric.CompletionMode" />か、コード パッケージの再起動が完了するまで待機するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-640">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-641">この API 呼び出しでは、入力パラメーターで指定されたコード パッケージが再起動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-641">This API call restarts the code package as specified by the input parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-642">実際のコード パッケージについての情報」に進んで RestartDeployedCodePackageResult が再起動されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-642">RestartDeployedCodePackageResult which gives information about the actual code package restarted.</span></span> <span data-ttu-id="215e8-643">SelectedReplica はこのオーバー ロードでは None です。</span><span class="sxs-lookup"><span data-stu-id="215e8-643">SelectedReplica is None in this overload.</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-644"><see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。</span><span class="sxs-lookup"><span data-stu-id="215e8-644">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-645">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-645">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-646">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-646">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-647">これらは、ファブリック エラー FabricErrorCode.CodePackageNotFound - 選択したコード パッケージが見つかりませんでした FabricErrorCode.InstanceIdMismatch - 指定したインスタンス id が一致しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-647">These are the fabric failures FabricErrorCode.CodePackageNotFound - If the selected code package was not found FabricErrorCode.InstanceIdMismatch - If the specified instance id did not match</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-648">コード パッケージが有効な実行中状態ではありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-648">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.Int64,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * int64 * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, codePackageName, codePackageInstanceId, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-649">コード パッケージがホストされているノードです。</span><span class="sxs-lookup"><span data-stu-id="215e8-649">The node on which the code package is hosted.</span></span></param>
        <param name="applicationName"><span data-ttu-id="215e8-650">コード パッケージが所属するアプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="215e8-650">The name of the application to which the code package belongs.</span></span></param>
        <param name="serviceManifestName"><span data-ttu-id="215e8-651">コード パッケージが定義されているサービス マニフェストの名前。</span><span class="sxs-lookup"><span data-stu-id="215e8-651">The name of the service manifest where the code package is defined.</span></span></param>
        <param name="codePackageName"><span data-ttu-id="215e8-652">再起動するコード パッケージの名前</span><span class="sxs-lookup"><span data-stu-id="215e8-652">The name of the code package to be restarted</span></span></param>
        <param name="codePackageInstanceId"><span data-ttu-id="215e8-653">指定されていてと一致しませんし、再起動場合は処理されません、値は 0、比較を実行中のコード パッケージのコード パッケージ インスタンス id はスキップされます。</span><span class="sxs-lookup"><span data-stu-id="215e8-653">The code package instance id for the running code package which if specified and does not match then the restart is not processed If the value is 0 then the comparison is skipped.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-654"><see cref="T:System.Fabric.CompletionMode" />か、コード パッケージの再起動が完了するまで待機するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-654">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-655">コード パッケージを再起動するまで待機するタイムアウトを含む、操作の全体的なタイムアウト<see cref="T:System.Fabric.CompletionMode" />を確認してください</span><span class="sxs-lookup"><span data-stu-id="215e8-655">The overall timeout for the operation including the timeout to wait for code package to restart if <see cref="T:System.Fabric.CompletionMode" /> is Verify</span></span></param>
        <param name="token"><span data-ttu-id="215e8-656">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-656">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-657">この API 呼び出しでは、入力パラメーターで指定されたコード パッケージが再起動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-657">This API call restarts the code package as specified by the input parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-658">実際のコード パッケージについての情報」に進んで RestartDeployedCodePackageResult が再起動されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-658">RestartDeployedCodePackageResult which gives information about the actual code package restarted.</span></span> <span data-ttu-id="215e8-659">SelectedReplica はこのオーバー ロードでは None です。</span><span class="sxs-lookup"><span data-stu-id="215e8-659">SelectedReplica is None in this overload.</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-660"><see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。</span><span class="sxs-lookup"><span data-stu-id="215e8-660">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-661">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-661">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-662">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-662">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-663">これらは、ファブリック エラー FabricErrorCode.CodePackageNotFound - 選択したコード パッケージが見つかりませんでした FabricErrorCode.InstanceIdMismatch - 指定したインスタンス id が一致しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-663">These are the fabric failures FabricErrorCode.CodePackageNotFound - If the selected code package was not found FabricErrorCode.InstanceIdMismatch - If the specified instance id did not match</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-664">コード パッケージが有効な実行中状態ではありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-664">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.String,System.Int64,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * string * int64 * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, servicePackageActivationId, codePackageName, codePackageInstanceId, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-665">コード パッケージがホストされているノード</span><span class="sxs-lookup"><span data-stu-id="215e8-665">The node on which the code package is hosted</span></span></param>
        <param name="applicationName"><span data-ttu-id="215e8-666">コード パッケージが所属するアプリケーションの名前</span><span class="sxs-lookup"><span data-stu-id="215e8-666">The name of the application to which the code package belongs</span></span></param>
        <param name="serviceManifestName"><span data-ttu-id="215e8-667">コード パッケージが定義されているサービス マニフェストの名前</span><span class="sxs-lookup"><span data-stu-id="215e8-667">The name of the service manifest where the code package is defined</span></span></param>
        <param name="servicePackageActivationId">
          <para>
            <span data-ttu-id="215e8-668"><see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />コード パッケージが含まれている展開済みサービス パッケージのです。</span><span class="sxs-lookup"><span data-stu-id="215e8-668">The <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package which contains the code package.</span></span> <span data-ttu-id="215e8-669">使用して、展開済みサービス パッケージの ServicePackageActivationId を取得できます<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />クエリ。</span><span class="sxs-lookup"><span data-stu-id="215e8-669">You can get the ServicePackageActivationId of a deployed service package by using <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> query.</span></span> 
            </para>
          <para>
            <span data-ttu-id="215e8-670">場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />の作成時に指定された、サービスは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。</span><span class="sxs-lookup"><span data-stu-id="215e8-670">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service was <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it was not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="215e8-671">詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。</span><span class="sxs-lookup"><span data-stu-id="215e8-671">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </param>
        <param name="codePackageName"><span data-ttu-id="215e8-672">再起動するコード パッケージの名前</span><span class="sxs-lookup"><span data-stu-id="215e8-672">The name of the code package to be restarted</span></span></param>
        <param name="codePackageInstanceId"><span data-ttu-id="215e8-673">指定されていてと一致しませんし、再起動場合は処理されません、値は 0、比較を実行中のコード パッケージのコード パッケージ インスタンス id はスキップされます。</span><span class="sxs-lookup"><span data-stu-id="215e8-673">The code package instance id for the running code package which if specified and does not match then the restart is not processed If the value is 0 then the comparison is skipped</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-674"><see cref="T:System.Fabric.CompletionMode" />か、コード パッケージの再起動が完了するまで待機するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-674">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-675">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-675">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-676">この API 呼び出しでは、入力パラメーターで指定されたコード パッケージが再起動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-676">This API call restarts the code package as specified by the input parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-677">実際のコード パッケージについての情報」に進んで RestartDeployedCodePackageResult が再起動されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-677">RestartDeployedCodePackageResult which gives information about the actual code package restarted.</span></span> <span data-ttu-id="215e8-678">SelectedReplica はこのオーバー ロードでは None です。</span><span class="sxs-lookup"><span data-stu-id="215e8-678">SelectedReplica is None in this overload.</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-679"><see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。</span><span class="sxs-lookup"><span data-stu-id="215e8-679">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-680">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-680">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-681">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-681">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-682">これらは、ファブリック エラー FabricErrorCode.CodePackageNotFound - 選択したコード パッケージが見つかりませんでした FabricErrorCode.InstanceIdMismatch - 指定したインスタンス id が一致しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-682">These are the fabric failures FabricErrorCode.CodePackageNotFound - If the selected code package was not found FabricErrorCode.InstanceIdMismatch - If the specified instance id did not match</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-683">コード パッケージが有効な実行中状態ではありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-683">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.String,System.Int64,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * string * int64 * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, servicePackageActivationId, codePackageName, codePackageInstanceId, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-684">コード パッケージがホストされているノードです。</span><span class="sxs-lookup"><span data-stu-id="215e8-684">The node on which the code package is hosted.</span></span></param>
        <param name="applicationName"><span data-ttu-id="215e8-685">コード パッケージが所属するアプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="215e8-685">The name of the application to which the code package belongs.</span></span></param>
        <param name="serviceManifestName"><span data-ttu-id="215e8-686">コード パッケージが定義されているサービス マニフェストの名前。</span><span class="sxs-lookup"><span data-stu-id="215e8-686">The name of the service manifest where the code package is defined.</span></span></param>
        <param name="servicePackageActivationId">
          <para>
            <span data-ttu-id="215e8-687"><see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />コード パッケージが含まれている展開済みサービス パッケージのです。</span><span class="sxs-lookup"><span data-stu-id="215e8-687">The <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package which contains the code package.</span></span> <span data-ttu-id="215e8-688">使用して、展開済みサービス パッケージの ServicePackageActivationId を取得できます<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />クエリ。</span><span class="sxs-lookup"><span data-stu-id="215e8-688">You can get the ServicePackageActivationId of a deployed service package by using <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> query.</span></span> 
            </para>
          <para>
            <span data-ttu-id="215e8-689">場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />の作成時に指定された、サービスは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。</span><span class="sxs-lookup"><span data-stu-id="215e8-689">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service was <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it was not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="215e8-690">詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。</span><span class="sxs-lookup"><span data-stu-id="215e8-690">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </param>
        <param name="codePackageName"><span data-ttu-id="215e8-691">再起動するコード パッケージの名前</span><span class="sxs-lookup"><span data-stu-id="215e8-691">The name of the code package to be restarted</span></span></param>
        <param name="codePackageInstanceId"><span data-ttu-id="215e8-692">指定されていてと一致しませんし、再起動場合は処理されません、値は 0、比較を実行中のコード パッケージのコード パッケージ インスタンス id はスキップされます。</span><span class="sxs-lookup"><span data-stu-id="215e8-692">The code package instance id for the running code package which if specified and does not match then the restart is not processed If the value is 0 then the comparison is skipped.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-693"><see cref="T:System.Fabric.CompletionMode" />か、コード パッケージの再起動が完了するまで待機するかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-693">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the code package completes or not.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-694">コード パッケージを再起動するまで待機するタイムアウトを含む、操作の全体的なタイムアウト<see cref="T:System.Fabric.CompletionMode" />を確認してください</span><span class="sxs-lookup"><span data-stu-id="215e8-694">The overall timeout for the operation including the timeout to wait for code package to restart if <see cref="T:System.Fabric.CompletionMode" /> is Verify</span></span></param>
        <param name="token"><span data-ttu-id="215e8-695">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-695">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-696">この API 呼び出しでは、入力パラメーターで指定されたコード パッケージが再起動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-696">This API call restarts the code package as specified by the input parameters.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-697">実際のコード パッケージについての情報」に進んで RestartDeployedCodePackageResult が再起動されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-697">RestartDeployedCodePackageResult which gives information about the actual code package restarted.</span></span> <span data-ttu-id="215e8-698">SelectedReplica はこのオーバー ロードでは None です。</span><span class="sxs-lookup"><span data-stu-id="215e8-698">SelectedReplica is None in this overload.</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-699"><see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。</span><span class="sxs-lookup"><span data-stu-id="215e8-699">The <see cref="T:System.Fabric.CompletionMode" /> options are DoNotVerify - Return after triggering the restart of the code package Verify - Return after the restart completes i.e. the code package has come back up again.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-700">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-700">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-701">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-701">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-702">これらは、ファブリック エラー FabricErrorCode.CodePackageNotFound - 選択したコード パッケージが見つかりませんでした FabricErrorCode.InstanceIdMismatch - 指定したインスタンス id が一致しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-702">These are the fabric failures FabricErrorCode.CodePackageNotFound - If the selected code package was not found FabricErrorCode.InstanceIdMismatch - If the specified instance id did not match</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="215e8-703">コード パッケージが有効な実行中状態ではありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-703">The code package was not in a valid running state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (replicaSelector, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="215e8-704">このパラメーターは使用を特定のレプリカを選択します。</span><span class="sxs-lookup"><span data-stu-id="215e8-704">This parameter is used to choose a specific replica.</span></span>  <span data-ttu-id="215e8-705">このレプリカの対応するノードが再起動されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-705">This replica's corresponding node will be restarted.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-706">設定を確認してください、システムは確認をノードを再起動して、API があり、NodeStatus が稼働するまでは返されません。</span><span class="sxs-lookup"><span data-stu-id="215e8-706">If set to Verify, the system will check that the node restarted, and the API will not return until it has and NodeStatus is Up.</span></span>  <span data-ttu-id="215e8-707">かどうか DoNotVerify に設定すると、API を返します、ノードの再起動が開始されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-707">If set to DoNotVerify, the API returns once the node restart has been initiated.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-708">ノードをホストする Fabric.exe プロセスを再起動することによって、クラスター ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-708">Restarts a cluster node by restarting the Fabric.exe process that hosts the node.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-709">については、ターゲット ノードと選択したレプリカを表すタスク。</span><span class="sxs-lookup"><span data-stu-id="215e8-709">A task with information representing the target node, and the replica selected.</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-710">この API は、Service Fabric サービスのフェールオーバーの復旧パスをテストすると、クラスター内のノードの障害をシミュレートします。</span><span class="sxs-lookup"><span data-stu-id="215e8-710">This API simulates Service Fabric node failures in the cluster, which tests the fail-over recovery paths of your service.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-711"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-711">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>
              <span data-ttu-id="215e8-712">ErrorCode が無効な引数の場合は、ノード名が正しくありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-712">If the ErrorCode is InvalidArgument, nodeName is invalid.</span></span>
              <span data-ttu-id="215e8-713">ErrorCode が ReplicaDoesNotExist の場合は、選択したレプリカは見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="215e8-713">If the ErrorCode is ReplicaDoesNotExist, the selected replica was not found.</span></span>
              <span data-ttu-id="215e8-714">ErrorCode が PartitionNotFound の場合は、指定されたパーティションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-714">If the ErrorCode is PartitionNotFound, the specified partition does not exist.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-715">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="215e8-715">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-716">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="215e8-716">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (replicaSelector, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="215e8-717">このパラメーターは使用を特定のレプリカを選択します。</span><span class="sxs-lookup"><span data-stu-id="215e8-717">This parameter is used to choose a specific replica.</span></span>  <span data-ttu-id="215e8-718">このレプリカの対応するノードが再起動されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-718">This replica's corresponding node will be restarted.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-719">設定を確認してください、システムは確認をノードを再起動して、API があり、NodeStatus が稼働するまでは返されません。</span><span class="sxs-lookup"><span data-stu-id="215e8-719">If set to Verify, the system will check that the node restarted, and the API will not return until it has and NodeStatus is Up.</span></span>  <span data-ttu-id="215e8-720">かどうか DoNotVerify に設定すると、API を返します、ノードの再起動が開始されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-720">If set to DoNotVerify, the API returns once the node restart has been initiated.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-721">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="215e8-721">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-722">ノードをホストする Fabric.exe プロセスを再起動することによって、クラスター ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-722">Restarts a cluster node by restarting the Fabric.exe process that hosts the node.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-723">については、ターゲット ノードと選択したレプリカを表すタスク。</span><span class="sxs-lookup"><span data-stu-id="215e8-723">A task with information representing the target node, and the replica selected.</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-724">この API は、Service Fabric サービスのフェールオーバーの復旧パスをテストすると、クラスター内のノードの障害をシミュレートします。</span><span class="sxs-lookup"><span data-stu-id="215e8-724">This API simulates Service Fabric node failures in the cluster, which tests the fail-over recovery paths of your service.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-725"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-725">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>
              <span data-ttu-id="215e8-726">ErrorCode が無効な引数の場合は、ノード名が正しくありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-726">If the ErrorCode is InvalidArgument, nodeName is invalid.</span></span>
              <span data-ttu-id="215e8-727">ErrorCode が ReplicaDoesNotExist の場合は、選択したレプリカは見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="215e8-727">If the ErrorCode is ReplicaDoesNotExist, the selected replica was not found.</span></span>
              <span data-ttu-id="215e8-728">ErrorCode が PartitionNotFound の場合は、指定されたパーティションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-728">If the ErrorCode is PartitionNotFound, the specified partition does not exist.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-729">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="215e8-729">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-730">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="215e8-730">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (nodeName, nodeInstance, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-731">再起動するノードのノード名。</span><span class="sxs-lookup"><span data-stu-id="215e8-731">The node name of the node to restart.</span></span></param>
        <param name="nodeInstance">
          <para><span data-ttu-id="215e8-732">再起動するノードのノード インスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="215e8-732">The node instance ID of the node to restart.</span></span>
            <span data-ttu-id="215e8-733">いない、または、指定されて 0 に設定されている場合、値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-733">If not specified, or is set to 0, the value is ignored.</span></span>
            <span data-ttu-id="215e8-734">インスタンスは、-1 に設定されている場合、システムはこの値を内部的に決定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-734">If the instance is set to -1, the system will internally determine this value.</span></span>
            <span data-ttu-id="215e8-735">インスタンスには正の値がある場合は、アクティブなノード id と比較されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-735">If the instance has a positive value, it is compared with the active node ID.</span></span>
            <span data-ttu-id="215e8-736">Id が一致しない場合、プロセスは再開されませんし、エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="215e8-736">If the IDs do not match, the process is not restarted and an error occurs.</span></span>
            <span data-ttu-id="215e8-737">古いメッセージは、このエラーを発生できます。</span><span class="sxs-lookup"><span data-stu-id="215e8-737">A stale message can cause this error.</span></span>
            </para>
        </param>
        <param name="completionMode"><span data-ttu-id="215e8-738">設定を確認してください、システムは確認をノードを再起動して、API があり、NodeStatus が稼働するまでは返されません。</span><span class="sxs-lookup"><span data-stu-id="215e8-738">If set to Verify, the system will check that the node restarted, and the API will not return until it has and NodeStatus is Up.</span></span>  <span data-ttu-id="215e8-739">かどうか DoNotVerify に設定すると、API を返します、ノードの再起動が開始されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-739">If set to DoNotVerify, the API returns once the node restart has been initiated.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-740">ノードをホストする Fabric.exe プロセスを再起動することによって、クラスター ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-740">Restarts a cluster node by restarting the Fabric.exe process that hosts the node.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-741">については、ターゲット ノードを表すタスク。</span><span class="sxs-lookup"><span data-stu-id="215e8-741">A task with information representing the target node.</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-742">この API は、Service Fabric サービスのフェールオーバーの復旧パスをテストすると、クラスター内のノードの障害をシミュレートします。</span><span class="sxs-lookup"><span data-stu-id="215e8-742">This API simulates Service Fabric node failures in the cluster, which tests the fail-over recovery paths of your service.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-743"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-743">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>
              <span data-ttu-id="215e8-744">ErrorCode が NodeNotFound の場合は、nodeName またはノード インスタンスが無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-744">If the ErrorCode is NodeNotFound, nodeName or nodeInstance is invalid.</span></span>
              <span data-ttu-id="215e8-745">ErrorCode が InstanceIdMismatch の場合は、提供されるノード インスタンスが、現在実行中のインスタンスと一致しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-745">If the ErrorCode is InstanceIdMismatch, the nodeInstance provided does not match the currently running instance.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-746">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="215e8-746">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-747">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="215e8-747">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (replicaSelector, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="215e8-748">このパラメーターは使用を特定のレプリカを選択します。</span><span class="sxs-lookup"><span data-stu-id="215e8-748">This parameter is used to choose a specific replica.</span></span>
            <span data-ttu-id="215e8-749">レプリカが配置されているノードが再起動されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-749">The node where the replica is deployed will be restarted.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-750">設定を確認してください、システムは確認をノードを再起動して、API があり、NodeStatus が稼働するまでは返されません。</span><span class="sxs-lookup"><span data-stu-id="215e8-750">If set to Verify, the system will check that the node restarted, and the API will not return until it has and NodeStatus is Up.</span></span>  <span data-ttu-id="215e8-751">かどうか DoNotVerify に設定すると、API を返します、ノードの再起動が開始されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-751">If set to DoNotVerify, the API returns once the node restart has been initiated.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-752">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="215e8-752">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-753">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="215e8-753">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-754">ノードをホストする Fabric.exe プロセスを再起動することによって、クラスター ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-754">Restarts a cluster node by restarting the Fabric.exe process that hosts the node.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-755">については、ターゲット ノードと選択したレプリカを表すタスク。</span><span class="sxs-lookup"><span data-stu-id="215e8-755">A task with information representing the target node, and the replica selected.</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-756">この API は、Service Fabric サービスのフェールオーバーの復旧パスをテストすると、クラスター内のノードの障害をシミュレートします。</span><span class="sxs-lookup"><span data-stu-id="215e8-756">This API simulates Service Fabric node failures in the cluster, which tests the fail-over recovery paths of your service.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-757"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-757">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>
              <span data-ttu-id="215e8-758">ErrorCode が無効な引数の場合は、ノード名が正しくありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-758">If the ErrorCode is InvalidArgument, nodeName is invalid.</span></span>
              <span data-ttu-id="215e8-759">ErrorCode が ReplicaDoesNotExist の場合は、選択したレプリカは見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="215e8-759">If the ErrorCode is ReplicaDoesNotExist, the selected replica was not found.</span></span>
              <span data-ttu-id="215e8-760">ErrorCode が PartitionNotFound の場合は、指定されたパーティションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-760">If the ErrorCode is PartitionNotFound, the specified partition does not exist.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-761">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="215e8-761">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-762">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="215e8-762">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (nodeName, nodeInstance, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-763">再起動するノードのノード名。</span><span class="sxs-lookup"><span data-stu-id="215e8-763">The node name of the node to restart.</span></span></param>
        <param name="nodeInstance">
          <para><span data-ttu-id="215e8-764">再起動するノードのノード インスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="215e8-764">The node instance ID of the node to restart.</span></span>
            <span data-ttu-id="215e8-765">いない、または、指定されて 0 に設定されている場合、値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-765">If not specified, or is set to 0, the value is ignored.</span></span>
            <span data-ttu-id="215e8-766">インスタンスは、-1 に設定されている場合、システムはこの値を内部的に決定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-766">If the instance is set to -1, the system will internally determine this value.</span></span>
            <span data-ttu-id="215e8-767">インスタンスには正の値がある場合は、アクティブなインスタンス ID を持つ比較します。</span><span class="sxs-lookup"><span data-stu-id="215e8-767">If the instance has a positive value, it is compared with the active instance ID.</span></span>
            <span data-ttu-id="215e8-768">インスタンスが一致しない場合、プロセスは再開されませんし、エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="215e8-768">If the instances do not match, the process is not restarted and an error occurs.</span></span>
            <span data-ttu-id="215e8-769">古いメッセージは、このエラーを発生できます。</span><span class="sxs-lookup"><span data-stu-id="215e8-769">A stale message can cause this error.</span></span>
            </para>
        </param>
        <param name="completionMode"><span data-ttu-id="215e8-770">場合設定<see cref="F:System.Fabric.CompletionMode.Verify" />、システムことを確認、ノードを再起動し、API があり、NodeStatus が稼働するまでは返されません。</span><span class="sxs-lookup"><span data-stu-id="215e8-770">If set to <see cref="F:System.Fabric.CompletionMode.Verify" />, the system will check that the node restarted, and the API will not return until it has and NodeStatus is Up.</span></span>
            <span data-ttu-id="215e8-771">場合設定<see cref="F:System.Fabric.CompletionMode.DoNotVerify" />ノードの再起動が開始された後に、API が返されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-771">If set to <see cref="F:System.Fabric.CompletionMode.DoNotVerify" />, the API returns once the node restart has been initiated.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-772">この CancellationToken は、この操作を確認します。</span><span class="sxs-lookup"><span data-stu-id="215e8-772">The CancellationToken that this operation is observing.</span></span> <span data-ttu-id="215e8-773">取り消す必要がある操作の通知に使用されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-773">It is used to notify the operation that it should be canceled.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-774">ノードをホストする Fabric.exe プロセスを再起動することによって、クラスター ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-774">Restarts a cluster node by restarting the Fabric.exe process that hosts the node.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-775">については、ターゲット ノードを表すタスク。</span><span class="sxs-lookup"><span data-stu-id="215e8-775">A task with information representing the target node.</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-776">この API は、Service Fabric サービスのフェールオーバーの復旧パスをテストすると、クラスター内のノードの障害をシミュレートします。</span><span class="sxs-lookup"><span data-stu-id="215e8-776">This API simulates Service Fabric node failures in the cluster, which tests the fail-over recovery paths of your service.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-777"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-777">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  <span data-ttu-id="215e8-778">ErrorCode が NodeNotFound の場合は、ノード名が正しくありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-778">If the ErrorCode is NodeNotFound, nodeName is invalid.</span></span>
            <span data-ttu-id="215e8-779">ErrorCode が InstanceIdMismatch の場合、<paramref name="nodeInstance" />提供される、現在実行中のインスタンスと一致しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-779">If the ErrorCode is InstanceIdMismatch, the <paramref name="nodeInstance" /> provided does not match the currently running instance.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-780">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="215e8-780">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-781">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="215e8-781">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.String,System.Numerics.BigInteger,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestartNodeAsync (nodeName As String, nodeInstance As BigInteger, operationTimeout As TimeSpan, token As CancellationToken) As Task(Of RestartNodeResult)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : string * System.Numerics.BigInteger * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (nodeName, nodeInstance, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-782">再起動するノードのノード名。</span><span class="sxs-lookup"><span data-stu-id="215e8-782">The node name of the node to restart.</span></span></param>
        <param name="nodeInstance">
          <para><span data-ttu-id="215e8-783">再起動するノードのノード インスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="215e8-783">The node instance ID of the node to restart.</span></span>
            <span data-ttu-id="215e8-784">いない、または、指定されて 0 に設定されている場合、値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-784">If not specified, or is set to 0, the value is ignored.</span></span>
            <span data-ttu-id="215e8-785">インスタンスは、-1 に設定されている場合、システムはこの値を内部的に決定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-785">If the instance is set to -1, the system will internally determine this value.</span></span>
            <span data-ttu-id="215e8-786">インスタンスには正の値がある場合は、アクティブなノード id と比較されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-786">If the instance has a positive value, it is compared with the active node ID.</span></span>
            <span data-ttu-id="215e8-787">Id が一致しない場合、プロセスは再開されませんし、エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="215e8-787">If the IDs do not match, the process is not restarted and an error occurs.</span></span>
            <span data-ttu-id="215e8-788">古いメッセージは、このエラーを発生できます。</span><span class="sxs-lookup"><span data-stu-id="215e8-788">A stale message can cause this error.</span></span>
            </para>
        </param>
        <param name="operationTimeout"><span data-ttu-id="215e8-789">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="215e8-789">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-790">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="215e8-790">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-791">ノードをホストする Fabric.exe プロセスを再起動することによって、クラスター ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-791">Restarts a cluster node by restarting the Fabric.exe process that hosts the node.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-792">については、ターゲット ノードを表すタスク。</span><span class="sxs-lookup"><span data-stu-id="215e8-792">A task with information representing the target node.</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-793">この API は、Service Fabric サービスのフェールオーバーの復旧パスをテストすると、クラスター内のノードの障害をシミュレートします。</span><span class="sxs-lookup"><span data-stu-id="215e8-793">This API simulates Service Fabric node failures in the cluster, which tests the fail-over recovery paths of your service.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-794"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-794">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="215e8-795">ErrorCode が NodeNotFound の場合は、ノード名が正しくありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-795">If the ErrorCode is NodeNotFound, nodeName is invalid.</span></span>  
              <span data-ttu-id="215e8-796">ErrorCode が InstanceIdMismatch の場合は、提供されるノード インスタンスが、現在実行中のインスタンスと一致しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-796">If the ErrorCode is InstanceIdMismatch, the nodeInstance provided does not match the currently running instance.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-797">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="215e8-797">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-798">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="215e8-798">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (System.Fabric.ReplicaSelector replicaSelector, bool createFabricDump, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(class System.Fabric.ReplicaSelector replicaSelector, bool createFabricDump, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.Fabric.ReplicaSelector,System.Boolean,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : System.Fabric.ReplicaSelector * bool * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (replicaSelector, createFabricDump, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartNodeAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="createFabricDump" Type="System.Boolean" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="215e8-799">このパラメーターは使用を特定のレプリカを選択します。</span><span class="sxs-lookup"><span data-stu-id="215e8-799">This parameter is used to choose a specific replica.</span></span>  <span data-ttu-id="215e8-800">このレプリカの対応するノードが再起動されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-800">This replica's corresponding node will be restarted.</span></span></param>
        <param name="createFabricDump"> <span data-ttu-id="215e8-801">場合は true、システムに設定は、このノードの Fabric.exe のプロセスのダンプを作成します。</span><span class="sxs-lookup"><span data-stu-id="215e8-801">If set to true, the system will create the process dump for Fabric.exe on this node.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-802">設定を確認してください、システムは確認をノードを再起動して、API があり、NodeStatus が稼働するまでは返されません。</span><span class="sxs-lookup"><span data-stu-id="215e8-802">If set to Verify, the system will check that the node restarted, and the API will not return until it has and NodeStatus is Up.</span></span>  <span data-ttu-id="215e8-803">かどうか DoNotVerify に設定すると、API を返します、ノードの再起動が開始されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-803">If set to DoNotVerify, the API returns once the node restart has been initiated.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-804">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="215e8-804">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-805">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="215e8-805">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-806">ノードをホストする Fabric.exe プロセスを再起動することによって、クラスター ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-806">Restarts a cluster node by restarting the Fabric.exe process that hosts the node.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-807">については、ターゲット ノードと選択したレプリカを表すタスク。</span><span class="sxs-lookup"><span data-stu-id="215e8-807">A task with information representing the target node, and the replica selected.</span></span></returns>
        <remarks><span data-ttu-id="215e8-808">クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</span><span class="sxs-lookup"><span data-stu-id="215e8-808">A cluster node is a process, not an virtual or physical machine.</span></span>
            <span data-ttu-id="215e8-809">CreateFabricDump パラメーターが設定されている場合は、再起動時に、プロセスがクラッシュしましたおよびクラッシュ ダンプ フォルダーに配置されて、クラッシュ ダンプ DCA は、アップロードするように構成できます。</span><span class="sxs-lookup"><span data-stu-id="215e8-809">If the createFabricDump parameter is set, on restart the process is crashed and the crash dump is placed in the Crash Dumps folder which the DCA can be configured to upload.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-810"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-810">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>
              <span data-ttu-id="215e8-811">ErrorCode が無効な引数の場合は、ノード名が正しくありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-811">If the ErrorCode is InvalidArgument, nodeName is invalid.</span></span>
              <span data-ttu-id="215e8-812">ErrorCode が ReplicaDoesNotExist の場合は、選択したレプリカは見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="215e8-812">If the ErrorCode is ReplicaDoesNotExist, the selected replica was not found.</span></span>
              <span data-ttu-id="215e8-813">ErrorCode が PartitionNotFound の場合は、指定されたパーティションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-813">If the ErrorCode is PartitionNotFound, the specified partition does not exist.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-814">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="215e8-814">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-815">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="215e8-815">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, bool createFabricDump, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, bool createFabricDump, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.String,System.Numerics.BigInteger,System.Boolean,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : string * System.Numerics.BigInteger * bool * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (nodeName, nodeInstance, createFabricDump, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartNodeAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="createFabricDump" Type="System.Boolean" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-816">再起動するノードのノード名。</span><span class="sxs-lookup"><span data-stu-id="215e8-816">The node name of the node to restart.</span></span></param>
        <param name="nodeInstance">
          <para><span data-ttu-id="215e8-817">再起動するノードのノード インスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="215e8-817">The node instance ID of the node to restart.</span></span>
            <span data-ttu-id="215e8-818">いない、または、指定されて 0 に設定されている場合、値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-818">If not specified, or is set to 0, the value is ignored.</span></span>
            <span data-ttu-id="215e8-819">インスタンスは、-1 に設定されている場合、システムはこの値を内部的に決定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-819">If the instance is set to -1, the system will internally determine this value.</span></span>
            <span data-ttu-id="215e8-820">インスタンスには正の値がある場合は、アクティブなノード id と比較されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-820">If the instance has a positive value, it is compared with the active node ID.</span></span>
            <span data-ttu-id="215e8-821">Id が一致しない場合、プロセスは再開されませんし、エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="215e8-821">If the IDs do not match, the process is not restarted and an error occurs.</span></span>
            <span data-ttu-id="215e8-822">古いメッセージは、このエラーを発生できます。</span><span class="sxs-lookup"><span data-stu-id="215e8-822">A stale message can cause this error.</span></span>
            </para>
        </param>
        <param name="createFabricDump"> <span data-ttu-id="215e8-823">場合は true、システムに設定は、このノードの Fabric.exe のプロセスのダンプを作成します。</span><span class="sxs-lookup"><span data-stu-id="215e8-823">If set to true, the system will create the process dump for Fabric.exe on this node.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-824">設定を確認してください、システムは確認をノードを再起動して、API があり、NodeStatus が稼働するまでは返されません。</span><span class="sxs-lookup"><span data-stu-id="215e8-824">If set to Verify, the system will check that the node restarted, and the API will not return until it has and NodeStatus is Up.</span></span>  <span data-ttu-id="215e8-825">かどうか DoNotVerify に設定すると、API を返します、ノードの再起動が開始されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-825">If set to DoNotVerify, the API returns once the node restart has been initiated.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-826">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="215e8-826">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-827">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="215e8-827">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-828">ノードをホストする Fabric.exe プロセスを再起動することによって、クラスター ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-828">Restarts a cluster node by restarting the Fabric.exe process that hosts the node.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-829">については、ターゲット ノードを表すタスク。</span><span class="sxs-lookup"><span data-stu-id="215e8-829">A task with information representing the target node.</span></span></returns>
        <remarks>
            <span data-ttu-id="215e8-830">この API は、Service Fabric サービスのフェールオーバーの復旧パスをテストすると、クラスター内のノードの障害をシミュレートします。</span><span class="sxs-lookup"><span data-stu-id="215e8-830">This API simulates Service Fabric node failures in the cluster, which tests the fail-over recovery paths of your service.</span></span>
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-831"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-831">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="215e8-832">ErrorCode が NodeNotFound の場合は、ノード名が正しくありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-832">If the ErrorCode is NodeNotFound, nodeName is invalid.</span></span>  
              <span data-ttu-id="215e8-833">ErrorCode が InstanceIdMismatch の場合は、提供されるノード インスタンスが、現在実行中のインスタンスと一致しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-833">If the ErrorCode is InstanceIdMismatch, the nodeInstance provided does not match the currently running instance.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-834">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="215e8-834">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-835">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="215e8-835">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (replicaSelector, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="215e8-836"><see cref="T:System.Fabric.ReplicaSelector" />レプリカを再起動することを示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-836">The <see cref="T:System.Fabric.ReplicaSelector" /> which indicates the replica to be restarted.</span></span> <span data-ttu-id="215e8-837">この API は、永続化されたサービス レプリカでのみ呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="215e8-837">This API can only be called for persisted service replicas.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-838"><see cref="T:System.Fabric.CompletionMode" />いない DoNotVerify またはレプリカの再起動が完了するまで待機するかどうかを指定する - トリガーを確認してください - 戻り値の削除が完了した後、レプリカの再起動後に返されます</span><span class="sxs-lookup"><span data-stu-id="215e8-838">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the replica is complete or not DoNotVerify - Return after triggering the restart of the replica Verify - Return after the remove completes</span></span></param>
        <summary>
            <span data-ttu-id="215e8-839">この API に渡された指定されたレプリカ (ReportFault - 一時のと同等) が再起動で<see cref="T:System.Fabric.ReplicaSelector" />です。</span><span class="sxs-lookup"><span data-stu-id="215e8-839">This API will restart the replica (equivalent of ReportFault - Temporary) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-840">RestartReplicaResult が実際に選択したレプリカに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="215e8-840">RestartReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-841">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-841">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-842">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-842">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-843">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</span><span class="sxs-lookup"><span data-stu-id="215e8-843">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (replicaSelector, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="215e8-844"><see cref="T:System.Fabric.ReplicaSelector" />レプリカを再起動することを示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-844">The <see cref="T:System.Fabric.ReplicaSelector" /> which indicates the replica to be restarted.</span></span> <span data-ttu-id="215e8-845">この API は、永続化されたサービス レプリカでのみ呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="215e8-845">This API can only be called for persisted service replicas.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-846"><see cref="T:System.Fabric.CompletionMode" />いない DoNotVerify またはレプリカの再起動が完了するまで待機するかどうかを指定する - トリガーを確認してください - 戻り値の削除が完了した後、レプリカの再起動後に返されます</span><span class="sxs-lookup"><span data-stu-id="215e8-846">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the replica is complete or not DoNotVerify - Return after triggering the restart of the replica Verify - Return after the remove completes</span></span></param>
        <param name="token"><span data-ttu-id="215e8-847">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-847">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-848">この API は、渡された ReplicaSelector で指定されたレプリカ (ReportFault - 一時のと同等) を再起動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-848">This API will restart the replica (equivalent of ReportFault - Temporary) specified by the passed in ReplicaSelector.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-849">RestartReplicaResult が実際に選択したレプリカに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="215e8-849">RestartReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-850">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-850">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-851">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-851">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-852">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</span><span class="sxs-lookup"><span data-stu-id="215e8-852">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (replicaSelector, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><span data-ttu-id="215e8-853"><see cref="T:System.Fabric.ReplicaSelector" />レプリカを再起動することを示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-853">The <see cref="T:System.Fabric.ReplicaSelector" /> which indicates the replica to be restarted.</span></span> <span data-ttu-id="215e8-854">この API は、永続化されたサービス レプリカでのみ呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="215e8-854">This API can only be called for persisted service replicas.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-855"><see cref="T:System.Fabric.CompletionMode" />いない DoNotVerify またはレプリカの再起動が完了するまで待機するかどうかを指定する - トリガーを確認してください - 戻り値の削除が完了した後、レプリカの再起動後に返されます</span><span class="sxs-lookup"><span data-stu-id="215e8-855">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the replica is complete or not DoNotVerify - Return after triggering the restart of the replica Verify - Return after the remove completes</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-856">レプリカを場合に再起動するを待機するタイムアウトを含む、操作の全体的なタイムアウト<see cref="T:System.Fabric.CompletionMode" />を確認してください。</span><span class="sxs-lookup"><span data-stu-id="215e8-856">The overall timeout for the operation including the timeout to wait for replica to be restarted if <see cref="T:System.Fabric.CompletionMode" /> is Verify.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-857">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-857">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-858">この API に渡された指定されたレプリカ (ReportFault - 一時のと同等) が再起動で<see cref="T:System.Fabric.ReplicaSelector" />です。</span><span class="sxs-lookup"><span data-stu-id="215e8-858">This API will restart the replica (equivalent of ReportFault - Temporary) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-859">RestartReplicaResult が実際に選択したレプリカに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="215e8-859">RestartReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-860">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-860">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-861">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-861">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-862">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist - 選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-862">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaId, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-863">レプリカが再起動する必要があるノード名<see cref="T:System.Fabric.ReplicaSelector" /></span><span class="sxs-lookup"><span data-stu-id="215e8-863">Node name where replica needs to be restarted <see cref="T:System.Fabric.ReplicaSelector" /></span></span></param>
        <param name="partitionId"><span data-ttu-id="215e8-864">パーティション、レプリカが再起動する必要がある Id</span><span class="sxs-lookup"><span data-stu-id="215e8-864">Partition Id where the replica needs to be restarted</span></span> </param>
        <param name="replicaId"><span data-ttu-id="215e8-865">再起動する必要があるレプリカ Id</span><span class="sxs-lookup"><span data-stu-id="215e8-865">Replica Id that needs to be restarted</span></span> </param>
        <param name="completionMode"><span data-ttu-id="215e8-866"><see cref="T:System.Fabric.CompletionMode" />いない DoNotVerify またはレプリカの再起動が完了するまで待機するかどうかを指定する - トリガーを確認してください - 戻り値の削除が完了した後、レプリカの再起動後に返されます</span><span class="sxs-lookup"><span data-stu-id="215e8-866">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the replica is complete or not DoNotVerify - Return after triggering the restart of the replica Verify - Return after the remove completes</span></span></param>
        <summary>
            <span data-ttu-id="215e8-867">この API に渡された指定されたレプリカ (ReportFault - 一時のと同等) が再起動で<see cref="T:System.Fabric.ReplicaSelector" />です。</span><span class="sxs-lookup"><span data-stu-id="215e8-867">This API will restart the replica (equivalent of ReportFault - Temporary) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-868">RestartReplicaResult が実際に選択したレプリカに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="215e8-868">RestartReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-869">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-869">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-870">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-870">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-871">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</span><span class="sxs-lookup"><span data-stu-id="215e8-871">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaId, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-872">レプリカが再起動する必要があるノード名<see cref="T:System.Fabric.ReplicaSelector" /></span><span class="sxs-lookup"><span data-stu-id="215e8-872">Node name where replica needs to be restarted <see cref="T:System.Fabric.ReplicaSelector" /></span></span></param>
        <param name="partitionId"><span data-ttu-id="215e8-873">パーティション、レプリカが再起動する必要がある Id</span><span class="sxs-lookup"><span data-stu-id="215e8-873">Partition Id where the replica needs to be restarted</span></span> </param>
        <param name="replicaId"><span data-ttu-id="215e8-874">再起動する必要があるレプリカ Id</span><span class="sxs-lookup"><span data-stu-id="215e8-874">Replica Id that needs to be restarted</span></span> </param>
        <param name="completionMode"><span data-ttu-id="215e8-875"><see cref="T:System.Fabric.CompletionMode" />いない DoNotVerify またはレプリカの再起動が完了するまで待機するかどうかを指定する - トリガーを確認してください - 戻り値の削除が完了した後、レプリカの再起動後に返されます</span><span class="sxs-lookup"><span data-stu-id="215e8-875">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the replica is complete or not DoNotVerify - Return after triggering the restart of the replica Verify - Return after the remove completes</span></span></param>
        <param name="token"><span data-ttu-id="215e8-876">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-876">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-877">この API は、渡された ReplicaSelector で指定されたレプリカ (ReportFault - 一時のと同等) を再起動します。</span><span class="sxs-lookup"><span data-stu-id="215e8-877">This API will restart the replica (equivalent of ReportFault - Temporary) specified by the passed in ReplicaSelector.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-878">RestartReplicaResult が実際に選択したレプリカに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="215e8-878">RestartReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-879">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-879">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-880">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-880">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-881">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</span><span class="sxs-lookup"><span data-stu-id="215e8-881">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, double operationTimeoutSec, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, float64 operationTimeoutSec, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Double,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * double * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaId, completionMode, operationTimeoutSec, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeoutSec" Type="System.Double" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-882">レプリカが再起動する必要があるノード名<see cref="T:System.Fabric.ReplicaSelector" /></span><span class="sxs-lookup"><span data-stu-id="215e8-882">Node name where replica needs to be restarted <see cref="T:System.Fabric.ReplicaSelector" /></span></span></param>
        <param name="partitionId"><span data-ttu-id="215e8-883">パーティション、レプリカが再起動する必要がある Id</span><span class="sxs-lookup"><span data-stu-id="215e8-883">Partition Id where the replica needs to be restarted</span></span> </param>
        <param name="replicaId"><span data-ttu-id="215e8-884">再起動する必要があるレプリカ Id</span><span class="sxs-lookup"><span data-stu-id="215e8-884">Replica Id that needs to be restarted</span></span> </param>
        <param name="completionMode"><span data-ttu-id="215e8-885"><see cref="T:System.Fabric.CompletionMode" />いない DoNotVerify またはレプリカの再起動が完了するまで待機するかどうかを指定する - トリガーを確認してください - 戻り値の削除が完了した後、レプリカの再起動後に返されます</span><span class="sxs-lookup"><span data-stu-id="215e8-885">The <see cref="T:System.Fabric.CompletionMode" /> that specifies whether to wait until the restart of the replica is complete or not DoNotVerify - Return after triggering the restart of the replica Verify - Return after the remove completes</span></span></param>
        <param name="operationTimeoutSec"><span data-ttu-id="215e8-886">場合は再起動するレプリカを待機するタイムアウトを含む操作は、秒単位の全体的なタイムアウト<see cref="T:System.Fabric.CompletionMode" />を確認してください。</span><span class="sxs-lookup"><span data-stu-id="215e8-886">The overall timeout in seconds for the operation, including the timeout to wait for replica to be restarted if <see cref="T:System.Fabric.CompletionMode" /> is Verify.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-887">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="215e8-887">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="215e8-888">この API に渡された指定されたレプリカ (ReportFault - 一時のと同等) が再起動で<see cref="T:System.Fabric.ReplicaSelector" />です。</span><span class="sxs-lookup"><span data-stu-id="215e8-888">This API will restart the replica (equivalent of ReportFault - Temporary) specified by the passed in <see cref="T:System.Fabric.ReplicaSelector" />.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-889">RestartReplicaResult が実際に選択したレプリカに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="215e8-889">RestartReplicaResult which gives information about the actual selected replica.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-890">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="215e8-890">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-891">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="215e8-891">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-892">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist - 選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合</span><span class="sxs-lookup"><span data-stu-id="215e8-892">These are the fabric failures FabricErrorCode.ReplicaDoesNotExist - If the Selected replica was not found FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-893">開始するノードのノード名。</span><span class="sxs-lookup"><span data-stu-id="215e8-893">The node name of the node to start.</span></span></param>
        <param name="nodeInstance"><span data-ttu-id="215e8-894">停止する前に、ノードのノード インスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="215e8-894">The node instance ID of the node, before it was stopped.</span></span> <span data-ttu-id="215e8-895">これが指定されていない、または 0 に設定されている、これは無視されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-895">If this is not specified, or is set to 0, this is ignored.</span></span> <span data-ttu-id="215e8-896">これは、-1 に設定されている場合、システムはこの値を決定内部的にします。</span><span class="sxs-lookup"><span data-stu-id="215e8-896">If this is set to -1, the system will internally determine this value.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-897">設定を確認してください、システムがチェックするノードが開始されると、および状態になるまで、この API は返されません。</span><span class="sxs-lookup"><span data-stu-id="215e8-897">If set to Verify, the system will check that the node started, and the API will not return until it has.</span></span>  <span data-ttu-id="215e8-898">かどうか DoNotVerify に設定すると、API を返しますノードの開始が開始されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-898">If set to DoNotVerify, the API returns once the node start has been initiated.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-899">クラスター ノードを開始します。</span><span class="sxs-lookup"><span data-stu-id="215e8-899">Starts a cluster node.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-900">については、ターゲット ノードを表すタスク。</span><span class="sxs-lookup"><span data-stu-id="215e8-900">A task with information representing the target node.</span></span></returns>
        <remarks><span data-ttu-id="215e8-901">クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</span><span class="sxs-lookup"><span data-stu-id="215e8-901">A cluster node is a process, not an virtual or physical machine.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-902"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-902">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="215e8-903">ErrorCode が無効な引数の場合は、nodeName またはノード インスタンスが無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-903">If the ErrorCode is InvalidArgument, nodeName or nodeInstance is invalid.</span></span>  
              <span data-ttu-id="215e8-904">ErrorCode が InstanceIdMismatch の場合は、指定されたノード インスタンスは停止したノードのインスタンスを一致しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-904">If the ErrorCode is InstanceIdMismatch, the nodeInstance provided does not match the instance of the node that was stopped.</span></span>  
              <span data-ttu-id="215e8-905">ErrorCode が NodeHasNotStoppedYet の場合は、このノードで現在保留中の停止操作があります。</span><span class="sxs-lookup"><span data-stu-id="215e8-905">If the ErrorCode is NodeHasNotStoppedYet, there is a currently pending stop operation on this node.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-906">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="215e8-906">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-907">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="215e8-907">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-908">開始するノードのノード名。</span><span class="sxs-lookup"><span data-stu-id="215e8-908">The node name of the node to start.</span></span></param>
        <param name="nodeInstance"><span data-ttu-id="215e8-909">停止する前に、ノードのノード インスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="215e8-909">The node instance ID of the node, before it was stopped.</span></span>  <span data-ttu-id="215e8-910">これが指定されていない、または 0 に設定されている、これは無視されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-910">If this is not specified, or is set to 0, this is ignored.</span></span>  <span data-ttu-id="215e8-911">これは、-1 に設定されている場合、システムはこの値を決定内部的にします。</span><span class="sxs-lookup"><span data-stu-id="215e8-911">If this is set to -1, the system will internally determine this value.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-912">設定を確認してください、システムがチェックするノードが開始されると、および状態になるまで、この API は返されません。</span><span class="sxs-lookup"><span data-stu-id="215e8-912">If set to Verify, the system will check that the node started, and the API will not return until it has.</span></span>  <span data-ttu-id="215e8-913">かどうか DoNotVerify に設定すると、API を返しますノードの開始が開始されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-913">If set to DoNotVerify, the API returns once the node start has been initiated.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-914">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="215e8-914">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-915">クラスター ノードを開始します。</span><span class="sxs-lookup"><span data-stu-id="215e8-915">Starts a cluster node.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-916">については、ターゲット ノードを表すタスク。</span><span class="sxs-lookup"><span data-stu-id="215e8-916">A task with information representing the target node.</span></span></returns>
        <remarks><span data-ttu-id="215e8-917">クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</span><span class="sxs-lookup"><span data-stu-id="215e8-917">A cluster node is a process, not an virtual or physical machine.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-918"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-918">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="215e8-919">ErrorCode が無効な引数の場合は、nodeName またはノード インスタンスが無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-919">If the ErrorCode is InvalidArgument, nodeName or nodeInstance is invalid.</span></span>  
              <span data-ttu-id="215e8-920">ErrorCode が InstanceIdMismatch の場合は、指定されたノード インスタンスは停止したノードのインスタンスを一致しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-920">If the errorCode is InstanceIdMismatch, the nodeInstance provided does not match the instance of the node that was stopped.</span></span>  
              <span data-ttu-id="215e8-921">ErrorCode が NodeHasNotStoppedYet の場合は、このノードで現在保留中の停止操作があります。</span><span class="sxs-lookup"><span data-stu-id="215e8-921">If the ErrorCode is NodeHasNotStoppedYet, there is a currently pending stop operation on this node.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-922">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="215e8-922">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-923">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="215e8-923">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int clusterConnectionPort, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int32 clusterConnectionPort, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.String,System.Int32,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * string * int * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, ipAddressOrFQDN, clusterConnectionPort, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="ipAddressOrFQDN" Type="System.String" />
        <Parameter Name="clusterConnectionPort" Type="System.Int32" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-924">開始するノードのノード名。</span><span class="sxs-lookup"><span data-stu-id="215e8-924">The node name of the node to start.</span></span></param>
        <param name="nodeInstance"><span data-ttu-id="215e8-925">停止する前に、ノードのノード インスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="215e8-925">The node instance ID of the node, before it was stopped.</span></span>  <span data-ttu-id="215e8-926">これが指定されていない、または 0 に設定されている、これは無視されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-926">If this is not specified, or is set to 0, this is ignored.</span></span>  <span data-ttu-id="215e8-927">これは、-1 に設定されている場合、システムはこの値を決定内部的にします。</span><span class="sxs-lookup"><span data-stu-id="215e8-927">If this is set to -1, the system will internally determine this value.</span></span></param>
        <param name="ipAddressOrFQDN"><span data-ttu-id="215e8-928">IP アドレスまたはターゲット ノードの完全修飾ドメイン名 (FQDN) です。</span><span class="sxs-lookup"><span data-stu-id="215e8-928">The IP address or fully-qualified domain name (FQDN) of the target node.</span></span>  <span data-ttu-id="215e8-929">このパラメーターを指定すると場合、' ClusterConnectionPort"も指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="215e8-929">If this parameter is specified, 'ClusterConnectionPort" also must be specified.</span></span>  <span data-ttu-id="215e8-930">どちらも指定しないと場合、システムはこれらを内部的に決定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-930">If neither is specified, the system internally determines these.</span></span></param>
        <param name="clusterConnectionPort"><span data-ttu-id="215e8-931">ターゲット ノードのクラスター接続ポートです。</span><span class="sxs-lookup"><span data-stu-id="215e8-931">The cluster connection port of the target node.</span></span>  <span data-ttu-id="215e8-932">このパラメーターを指定すると場合、'ipAddressOrFQDN' も指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="215e8-932">If this parameter is specified, 'ipAddressOrFQDN' also must be specified.</span></span>  <span data-ttu-id="215e8-933">どちらも指定しないと場合、システムはこれらを内部的に決定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-933">If neither is specified, the system internally determines these.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-934">設定を確認してください、システムがチェックするノードが開始されると、および状態になるまで、この API は返されません。</span><span class="sxs-lookup"><span data-stu-id="215e8-934">If set to Verify, the system will check that the node started, and the API will not return until it has.</span></span>  <span data-ttu-id="215e8-935">かどうか DoNotVerify に設定すると、API を返しますノードの開始が開始されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-935">If set to DoNotVerify, the API returns once the node start has been initiated.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-936">クラスター ノードを開始します。</span><span class="sxs-lookup"><span data-stu-id="215e8-936">Starts a cluster node.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-937">については、ターゲット ノードを表すタスク。</span><span class="sxs-lookup"><span data-stu-id="215e8-937">A task with information representing the target node.</span></span></returns>
        <remarks><span data-ttu-id="215e8-938">クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</span><span class="sxs-lookup"><span data-stu-id="215e8-938">A cluster node is a process, not an virtual or physical machine.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-939"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-939">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="215e8-940">ErrorCode が無効な引数の場合は、nodeName またはノード インスタンスが無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-940">If the ErrorCode is InvalidArgument, nodeName or nodeInstance is invalid.</span></span>  
              <span data-ttu-id="215e8-941">ErrorCode が InstanceIdMismatch の場合は、指定されたノード インスタンスは停止したノードのインスタンスを一致しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-941">If the errorCode is InstanceIdMismatch, the nodeInstance provided does not match the instance of the node that was stopped.</span></span>  
              <span data-ttu-id="215e8-942">ErrorCode が NodeHasNotStoppedYet の場合は、このノードで現在保留中の停止操作があります。</span><span class="sxs-lookup"><span data-stu-id="215e8-942">If the ErrorCode is NodeHasNotStoppedYet, there is a currently pending stop operation on this node.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-943">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="215e8-943">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-944">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="215e8-944">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int clusterConnectionPort, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int32 clusterConnectionPort, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.String,System.Int32,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * string * int * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, ipAddressOrFQDN, clusterConnectionPort, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="ipAddressOrFQDN" Type="System.String" />
        <Parameter Name="clusterConnectionPort" Type="System.Int32" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-945">開始するノードのノード名。</span><span class="sxs-lookup"><span data-stu-id="215e8-945">The node name of the node to start.</span></span></param>
        <param name="nodeInstance"><span data-ttu-id="215e8-946">停止する前に、ノードのノード インスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="215e8-946">The node instance ID of the node, before it was stopped.</span></span>  <span data-ttu-id="215e8-947">これが指定されていない、または 0 に設定されている、これは無視されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-947">If this is not specified, or is set to 0, this is ignored.</span></span>  <span data-ttu-id="215e8-948">これは、-1 に設定されている場合、システムはこの値を決定内部的にします。</span><span class="sxs-lookup"><span data-stu-id="215e8-948">If this is set to -1, the system will internally determine this value.</span></span></param>
        <param name="ipAddressOrFQDN"><span data-ttu-id="215e8-949">IP アドレスまたはターゲット ノードの完全修飾ドメイン名 (FQDN) です。</span><span class="sxs-lookup"><span data-stu-id="215e8-949">The IP address or fully-qualified domain name (FQDN) of the target node.</span></span>  <span data-ttu-id="215e8-950">このパラメーターを指定すると場合、<paramref name="clusterConnectionPort" />も指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="215e8-950">If this parameter is specified, <paramref name="clusterConnectionPort" /> also must be specified.</span></span>  <span data-ttu-id="215e8-951">どちらも指定しないと場合、システムはこれらを内部的に決定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-951">If neither is specified, the system internally determines these.</span></span></param>
        <param name="clusterConnectionPort"><span data-ttu-id="215e8-952">ターゲット ノードのクラスター接続ポートです。</span><span class="sxs-lookup"><span data-stu-id="215e8-952">The cluster connection port of the target node.</span></span>  <span data-ttu-id="215e8-953">このパラメーターを指定すると場合、<paramref name="ipAddressOrFQDN" />も指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="215e8-953">If this parameter is specified, <paramref name="ipAddressOrFQDN" /> also must be specified.</span></span>  <span data-ttu-id="215e8-954">どちらも指定しないと場合、システムはこれらを内部的に決定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-954">If neither is specified, the system internally determines these.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-955">設定を確認してください、システムがチェックするノードが開始されると、および状態になるまで、この API は返されません。</span><span class="sxs-lookup"><span data-stu-id="215e8-955">If set to Verify, the system will check that the node started, and the API will not return until it has.</span></span>  <span data-ttu-id="215e8-956">かどうか DoNotVerify に設定すると、API を返しますノードの開始が開始されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-956">If set to DoNotVerify, the API returns once the node start has been initiated.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-957">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="215e8-957">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-958">クラスター ノードを開始します。</span><span class="sxs-lookup"><span data-stu-id="215e8-958">Starts a cluster node.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-959">については、ターゲット ノードを表すタスク。</span><span class="sxs-lookup"><span data-stu-id="215e8-959">A task with information representing the target node.</span></span></returns>
        <remarks><span data-ttu-id="215e8-960">クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</span><span class="sxs-lookup"><span data-stu-id="215e8-960">A cluster node is a process, not an virtual or physical machine.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-961"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-961">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="215e8-962">ErrorCode が無効な引数の場合は、nodeName またはノード インスタンスが無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-962">If the ErrorCode is InvalidArgument, nodeName or nodeInstance is invalid.</span></span>  
              <span data-ttu-id="215e8-963">ErrorCode が InstanceIdMismatch の場合は、指定されたノード インスタンスは停止したノードのインスタンスを一致しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-963">If the errorCode is InstanceIdMismatch, the nodeInstance provided does not match the instance of the node that was stopped.</span></span>  
              <span data-ttu-id="215e8-964">ErrorCode が NodeHasNotStoppedYet の場合は、このノードで現在保留中の停止操作があります。</span><span class="sxs-lookup"><span data-stu-id="215e8-964">If the ErrorCode is NodeHasNotStoppedYet, there is a currently pending stop operation on this node.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-965">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="215e8-965">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-966">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="215e8-966">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int clusterConnectionPort, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int32 clusterConnectionPort, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.String,System.Int32,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * string * int * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, ipAddressOrFQDN, clusterConnectionPort, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;StartNodeAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="ipAddressOrFQDN" Type="System.String" />
        <Parameter Name="clusterConnectionPort" Type="System.Int32" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-967">開始するノードのノード名。</span><span class="sxs-lookup"><span data-stu-id="215e8-967">The node name of the node to start.</span></span></param>
        <param name="nodeInstance"><span data-ttu-id="215e8-968">停止する前に、ノードのノード インスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="215e8-968">The node instance ID of the node, before it was stopped.</span></span>  <span data-ttu-id="215e8-969">これが指定されていない、または 0 に設定されている、これは無視されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-969">If this is not specified, or is set to 0, this is ignored.</span></span>  <span data-ttu-id="215e8-970">これは、-1 に設定されている場合、システムはこの値を決定内部的にします。</span><span class="sxs-lookup"><span data-stu-id="215e8-970">If this is set to -1, the system will internally determine this value.</span></span></param>
        <param name="ipAddressOrFQDN"><span data-ttu-id="215e8-971">IP アドレスまたはターゲット ノードの完全修飾ドメイン名 (FQDN) です。</span><span class="sxs-lookup"><span data-stu-id="215e8-971">The IP address or fully-qualified domain name (FQDN) of the target node.</span></span>  <span data-ttu-id="215e8-972">このパラメーターを指定すると場合、<paramref name="clusterConnectionPort" />も指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="215e8-972">If this parameter is specified, <paramref name="clusterConnectionPort" /> also must be specified.</span></span>  <span data-ttu-id="215e8-973">どちらも指定しないと場合、システムはこれらを内部的に決定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-973">If neither is specified, the system internally determines these.</span></span></param>
        <param name="clusterConnectionPort"><span data-ttu-id="215e8-974">ターゲット ノードのクラスター接続ポートです。</span><span class="sxs-lookup"><span data-stu-id="215e8-974">The cluster connection port of the target node.</span></span>  <span data-ttu-id="215e8-975">このパラメーターを指定すると場合、<paramref name="ipAddressOrFQDN" />も指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="215e8-975">If this parameter is specified, <paramref name="ipAddressOrFQDN" /> also must be specified.</span></span>  <span data-ttu-id="215e8-976">どちらも指定しないと場合、システムはこれらを内部的に決定します。</span><span class="sxs-lookup"><span data-stu-id="215e8-976">If neither is specified, the system internally determines these.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-977">設定を確認してください、システムがチェックするノードが開始されると、および状態になるまで、この API は返されません。</span><span class="sxs-lookup"><span data-stu-id="215e8-977">If set to Verify, the system will check that the node started, and the API will not return until it has.</span></span>  <span data-ttu-id="215e8-978">かどうか DoNotVerify に設定すると、API を返しますノードの開始が開始されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-978">If set to DoNotVerify, the API returns once the node start has been initiated.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-979">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="215e8-979">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-980">CancellationToken</span><span class="sxs-lookup"><span data-stu-id="215e8-980">The cancellationToken</span></span></param>
        <summary>
            <span data-ttu-id="215e8-981">クラスター ノードを開始します。</span><span class="sxs-lookup"><span data-stu-id="215e8-981">Starts a cluster node.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-982">については、ターゲット ノードを表すタスク。</span><span class="sxs-lookup"><span data-stu-id="215e8-982">A task with information representing the target node.</span></span></returns>
        <remarks><span data-ttu-id="215e8-983">クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</span><span class="sxs-lookup"><span data-stu-id="215e8-983">A cluster node is a process, not an virtual or physical machine.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-984"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-984">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="215e8-985">ErrorCode が無効な引数の場合は、nodeName またはノード インスタンスが無効です。</span><span class="sxs-lookup"><span data-stu-id="215e8-985">If the ErrorCode is InvalidArgument, nodeName or nodeInstance is invalid.</span></span>  
              <span data-ttu-id="215e8-986">ErrorCode が InstanceIdMismatch の場合は、指定されたノード インスタンスは停止したノードのインスタンスを一致しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-986">If the errorCode is InstanceIdMismatch, the nodeInstance provided does not match the instance of the node that was stopped.</span></span>  
              <span data-ttu-id="215e8-987">ErrorCode が NodeHasNotStoppedYet の場合は、このノードで現在保留中の停止操作があります。</span><span class="sxs-lookup"><span data-stu-id="215e8-987">If the ErrorCode is NodeHasNotStoppedYet, there is a currently pending stop operation on this node.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-988">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="215e8-988">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-989">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="215e8-989">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StopNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt; StopNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StopNodeResult&gt; StopNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StopNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.StopNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;" Usage="faultManagementClient.StopNodeAsync (nodeName, nodeInstance, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-990">停止するノードのノード名。</span><span class="sxs-lookup"><span data-stu-id="215e8-990">The node name of the node to stop.</span></span></param>
        <param name="nodeInstance"><span data-ttu-id="215e8-991">停止するノードのノード インスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="215e8-991">The node instance ID of the node to stop.</span></span>  <span data-ttu-id="215e8-992">これが指定されていない、または 0 に設定されている、これは無視されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-992">If this is not specified, or is set to 0, this is ignored.</span></span>  <span data-ttu-id="215e8-993">これは、-1 に設定されている場合、システムはこの値を決定内部的にします。</span><span class="sxs-lookup"><span data-stu-id="215e8-993">If this is set to -1, the system will internally determine this value.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-994">設定を確認してください、システムがチェックするノードが停止し、API は、状態になるまで返されません。</span><span class="sxs-lookup"><span data-stu-id="215e8-994">If set to Verify, the system will check that the node stopped, and the API will not return until it has.</span></span>  <span data-ttu-id="215e8-995">かどうか DoNotVerify に設定すると、API を返します、ノードの停止が開始されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-995">If set to DoNotVerify, the API returns once the node stop has been initiated.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-996">クラスター ノードを停止します。</span><span class="sxs-lookup"><span data-stu-id="215e8-996">Stops a cluster node.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-997">については、ターゲット ノードを表すタスク。</span><span class="sxs-lookup"><span data-stu-id="215e8-997">A task with information representing the target node.</span></span></returns>
        <remarks><span data-ttu-id="215e8-998">クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</span><span class="sxs-lookup"><span data-stu-id="215e8-998">A cluster node is a process, not an virtual or physical machine.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-999"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-999">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="215e8-1000">ErrorCode が無効な引数の場合は、ノード名が正しくありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-1000">If the ErrorCode is InvalidArgument, nodeName is invalid.</span></span>  
              <span data-ttu-id="215e8-1001">ErrorCode が InstanceIdMismatch の場合は、提供されるノード インスタンスが、現在実行中のインスタンスと一致しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-1001">If the ErrorCode is InstanceIdMismatch, the nodeInstance provided does not match the currently running instance.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-1002">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="215e8-1002">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-1003">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="215e8-1003">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StopNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt; StopNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StopNodeResult&gt; StopNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StopNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;" Usage="faultManagementClient.StopNodeAsync (nodeName, nodeInstance, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-1004">停止するノードのノード名。</span><span class="sxs-lookup"><span data-stu-id="215e8-1004">The node name of the node to stop.</span></span></param>
        <param name="nodeInstance"><span data-ttu-id="215e8-1005">停止するノードのノード インスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="215e8-1005">The node instance ID of the node to stop.</span></span>  <span data-ttu-id="215e8-1006">これが指定されていない、または 0 に設定されている、これは無視されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-1006">If this is not specified, or is set to 0, this is ignored.</span></span>  <span data-ttu-id="215e8-1007">これは、-1 に設定されている場合、システムはこの値を決定内部的にします。</span><span class="sxs-lookup"><span data-stu-id="215e8-1007">If this is set to -1, the system will internally determine this value.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-1008">設定を確認してください、システムがチェックするノードが停止し、API は、状態になるまで返されません。</span><span class="sxs-lookup"><span data-stu-id="215e8-1008">If set to Verify, the system will check that the node stopped, and the API will not return until it has.</span></span>  <span data-ttu-id="215e8-1009">かどうか DoNotVerify に設定すると、API を返します、ノードの停止が開始されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-1009">If set to DoNotVerify, the API returns once the node stop has been initiated.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-1010">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="215e8-1010">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-1011">クラスター ノードを停止します。</span><span class="sxs-lookup"><span data-stu-id="215e8-1011">Stops a cluster node.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-1012">については、ターゲット ノードを表すタスク。</span><span class="sxs-lookup"><span data-stu-id="215e8-1012">A task with information representing the target node.</span></span></returns>
        <remarks><span data-ttu-id="215e8-1013">クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</span><span class="sxs-lookup"><span data-stu-id="215e8-1013">A cluster node is a process, not an virtual or physical machine.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-1014"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-1014">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="215e8-1015">ErrorCode が無効な引数の場合は、ノード名が正しくありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-1015">If the ErrorCode is InvalidArgument, nodeName is invalid.</span></span>  
              <span data-ttu-id="215e8-1016">ErrorCode が InstanceIdMismatch の場合は、提供されるノード インスタンスが、現在実行中のインスタンスと一致しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-1016">If the ErrorCode is InstanceIdMismatch, the nodeInstance provided does not match the currently running instance.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-1017">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="215e8-1017">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-1018">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="215e8-1018">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StopNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt; StopNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StopNodeResult&gt; StopNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StopNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;" Usage="faultManagementClient.StopNodeAsync (nodeName, nodeInstance, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;StopNodeAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName"><span data-ttu-id="215e8-1019">停止するノードのノード名。</span><span class="sxs-lookup"><span data-stu-id="215e8-1019">The node name of the node to stop.</span></span></param>
        <param name="nodeInstance"><span data-ttu-id="215e8-1020">停止するノードのノード インスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="215e8-1020">The node instance ID of the node to stop.</span></span>  <span data-ttu-id="215e8-1021">これが指定されていない、または 0 に設定されている、これは無視されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-1021">If this is not specified, or is set to 0, this is ignored.</span></span>  <span data-ttu-id="215e8-1022">これは、-1 に設定されている場合、システムはこの値を決定内部的にします。</span><span class="sxs-lookup"><span data-stu-id="215e8-1022">If this is set to -1, the system will internally determine this value.</span></span></param>
        <param name="completionMode"><span data-ttu-id="215e8-1023">設定を確認してください、システムがチェックするノードが停止し、API は、状態になるまで返されません。</span><span class="sxs-lookup"><span data-stu-id="215e8-1023">If set to Verify, the system will check that the node stopped, and the API will not return until it has.</span></span>  <span data-ttu-id="215e8-1024">かどうか DoNotVerify に設定すると、API を返します、ノードの停止が開始されます。</span><span class="sxs-lookup"><span data-stu-id="215e8-1024">If set to DoNotVerify, the API returns once the node stop has been initiated.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="215e8-1025">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="215e8-1025">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="215e8-1026">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="215e8-1026">The cancellation token that is monitored for any request to cancel the operation.</span></span></param>
        <summary>
            <span data-ttu-id="215e8-1027">クラスター ノードを停止します。</span><span class="sxs-lookup"><span data-stu-id="215e8-1027">Stops a cluster node.</span></span>
            </summary>
        <returns><span data-ttu-id="215e8-1028">ターゲット ノードを表す情報とタスク</span><span class="sxs-lookup"><span data-stu-id="215e8-1028">A task with information representing the target node</span></span></returns>
        <remarks><span data-ttu-id="215e8-1029">クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</span><span class="sxs-lookup"><span data-stu-id="215e8-1029">A cluster node is a process, not an virtual or physical machine.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="215e8-1030"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="215e8-1030">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>  
              <span data-ttu-id="215e8-1031">ErrorCode が無効な引数の場合は、ノード名が正しくありません。</span><span class="sxs-lookup"><span data-stu-id="215e8-1031">If the ErrorCode is InvalidArgument, nodeName is invalid.</span></span>  
              <span data-ttu-id="215e8-1032">ErrorCode が InstanceIdMismatch の場合は、提供されるノード インスタンスが、現在実行中のインスタンスと一致しません。</span><span class="sxs-lookup"><span data-stu-id="215e8-1032">If the ErrorCode is InstanceIdMismatch, the nodeInstance provided does not match the currently running instance.</span></span>
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="215e8-1033">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="215e8-1033">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="215e8-1034">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="215e8-1034">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>