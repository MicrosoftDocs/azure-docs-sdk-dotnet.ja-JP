<Type Name="PoolOperations" FullName="Microsoft.Azure.Batch.PoolOperations">
  <TypeSignature Language="C#" Value="public class PoolOperations : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolOperations extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PoolOperations" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolOperations&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type PoolOperations = class&#xA;    interface IInheritedBehaviors" />
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
            <span data-ttu-id="5b860-101">Azure Batch アカウントにプール関連の操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="5b860-101">Performs pool-related operations on an Azure Batch account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ChangeOSVersion">
      <MemberSignature Language="C#" Value="public void ChangeOSVersion (string poolId, string targetOSVersion, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ChangeOSVersion(string poolId, string targetOSVersion, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ChangeOSVersion(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ChangeOSVersion (poolId As String, targetOSVersion As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.ChangeOSVersion : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.ChangeOSVersion (poolId, targetOSVersion, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-102">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-102">The id of the pool.</span></span></param>
        <param name="targetOSVersion"><span data-ttu-id="5b860-103">プール内の仮想マシンにインストールされる Azure ゲスト OS バージョン。</span><span class="sxs-lookup"><span data-stu-id="5b860-103">The Azure Guest OS version to be installed on the virtual machines in the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-104">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-104">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-105">指定したプールのオペレーティング システムのバージョンを変更します。</span><span class="sxs-lookup"><span data-stu-id="5b860-105">Changes the operating system version of the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="5b860-106">OS バージョンの変更操作中には、バッチ サービスは、コンピューティング ノードの OS バージョンを変更するプールのノードを走査します。</span><span class="sxs-lookup"><span data-stu-id="5b860-106">During the change OS version operation, the Batch service traverses the nodes of the pool, changing the OS version of compute nodes.</span></span>  <span data-ttu-id="5b860-107">コンピューティング ノードを選択すると、そのノードで実行されているすべてのタスクがノードから削除され、後で (または、別の計算ノード) を再実行をキューに再登録します。</span><span class="sxs-lookup"><span data-stu-id="5b860-107">When a compute node is chosen, any tasks running on that node are removed from the node and requeued to be rerun later (or on a different compute node).</span></span>  <span data-ttu-id="5b860-108">バージョンの変更が完了するまで、ノードは使用できません。</span><span class="sxs-lookup"><span data-stu-id="5b860-108">The node will be unavailable until the version change is complete.</span></span></para>
          <para><span data-ttu-id="5b860-109">操作の結果は、ノードは、サービス、OS バージョンを変更して外すように、一時的に削減プールの容量にします。</span><span class="sxs-lookup"><span data-stu-id="5b860-109">The operation will result in temporarily reduced pool capacity as nodes are taken out of service to have their OS version changed.</span></span> <span data-ttu-id="5b860-110">サービスが、すべての変更を回避しようとしています。 バッチはコンピューティング ノードを同時とは限りません (特にでサイズの小さいプール); の実行そのため、操作の結果に、プールがタスクの実行を一時的に利用できなくなる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="5b860-110">Although the Batch service tries to avoid changing all compute nodes at the same time, it does not guarantee to do this (particularly on small pools); therefore, the operation may result in the pool being temporarily unavailable to run tasks.</span></span></para>
          <para><span data-ttu-id="5b860-111">OS バージョンの変更を要求すると、プールの状態に変わります<see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-111">When you request an OS version change, the pool state changes to <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />.</span></span>  <span data-ttu-id="5b860-112">すべてのコンピューティング ノードでは、バージョンの変更が完了したら、プールの状態に戻ります<see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-112">When all compute nodes have finished changing version, the pool state returns to <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />.</span></span></para>
          <para><span data-ttu-id="5b860-113">バージョンの変更が進行中、プールの中に<see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" />からノードを変更する OS バージョンを反映し、<see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" />ノードが変更しようとしている OS バージョンを反映します。</span><span class="sxs-lookup"><span data-stu-id="5b860-113">While the version change is in progress, the pool's <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" /> reflects the OS version that nodes are changing from, and <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" /> reflects the OS version that nodes are changing to.</span></span> <span data-ttu-id="5b860-114">変更が完了したら、CurrentOSVersion はすべてのノードで実行されている OS バージョンを反映するように更新されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-114">Once the change is complete, CurrentOSVersion is updated to reflect the OS version now running on all nodes.</span></span></para>
          <para><span data-ttu-id="5b860-115">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-115">This is a blocking operation.</span></span> <span data-ttu-id="5b860-116">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.ChangeOSVersionAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-116">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.ChangeOSVersionAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeOSVersionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ChangeOSVersionAsync (string poolId, string targetOSVersion, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ChangeOSVersionAsync(string poolId, string targetOSVersion, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ChangeOSVersionAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ChangeOSVersionAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.ChangeOSVersionAsync (poolId, targetOSVersion, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-117">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-117">The id of the pool.</span></span></param>
        <param name="targetOSVersion"><span data-ttu-id="5b860-118">プール内の仮想マシンにインストールされる Azure ゲスト OS バージョン。</span><span class="sxs-lookup"><span data-stu-id="5b860-118">The Azure Guest OS version to be installed on the virtual machines in the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-119">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-119">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-120">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-120">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-121">指定したプールのオペレーティング システムのバージョンを変更します。</span><span class="sxs-lookup"><span data-stu-id="5b860-121">Changes the operating system version of the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-122">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-122">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-123">OS バージョンの変更操作中には、バッチ サービスは、コンピューティング ノードの OS バージョンを変更するプールのノードを走査します。</span><span class="sxs-lookup"><span data-stu-id="5b860-123">During the change OS version operation, the Batch service traverses the nodes of the pool, changing the OS version of compute nodes.</span></span>  <span data-ttu-id="5b860-124">コンピューティング ノードを選択すると、そのノードで実行されているすべてのタスクがノードから削除され、後で (または、別の計算ノード) を再実行をキューに再登録します。</span><span class="sxs-lookup"><span data-stu-id="5b860-124">When a compute node is chosen, any tasks running on that node are removed from the node and requeued to be rerun later (or on a different compute node).</span></span>  <span data-ttu-id="5b860-125">バージョンの変更が完了するまで、ノードは使用できません。</span><span class="sxs-lookup"><span data-stu-id="5b860-125">The node will be unavailable until the version change is complete.</span></span></para>
          <para><span data-ttu-id="5b860-126">操作の結果は、ノードは、サービス、OS バージョンを変更して外すように、一時的に削減プールの容量にします。</span><span class="sxs-lookup"><span data-stu-id="5b860-126">The operation will result in temporarily reduced pool capacity as nodes are taken out of service to have their OS version changed.</span></span> <span data-ttu-id="5b860-127">サービスが、すべての変更を回避しようとしています。 バッチはコンピューティング ノードを同時とは限りません (特にでサイズの小さいプール); の実行そのため、操作の結果に、プールがタスクの実行を一時的に利用できなくなる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="5b860-127">Although the Batch service tries to avoid changing all compute nodes at the same time, it does not guarantee to do this (particularly on small pools); therefore, the operation may result in the pool being temporarily unavailable to run tasks.</span></span></para>
          <para><span data-ttu-id="5b860-128">OS バージョンの変更を要求すると、プールの状態に変わります<see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-128">When you request an OS version change, the pool state changes to <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Upgrading" />.</span></span>  <span data-ttu-id="5b860-129">すべてのコンピューティング ノードでは、バージョンの変更が完了したら、プールの状態に戻ります<see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-129">When all compute nodes have finished changing version, the pool state returns to <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Active" />.</span></span></para>
          <para><span data-ttu-id="5b860-130">バージョンの変更が進行中、プールの中に<see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" />からノードを変更する OS バージョンを反映し、<see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" />ノードが変更しようとしている OS バージョンを反映します。</span><span class="sxs-lookup"><span data-stu-id="5b860-130">While the version change is in progress, the pool's <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.CurrentOSVersion" /> reflects the OS version that nodes are changing from, and <see cref="P:Microsoft.Azure.Batch.CloudServiceConfiguration.TargetOSVersion" /> reflects the OS version that nodes are changing to.</span></span> <span data-ttu-id="5b860-131">変更が完了したら、CurrentOSVersion はすべてのノードで実行されている OS バージョンを反映するように更新されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-131">Once the change is complete, CurrentOSVersion is updated to reflect the OS version now running on all nodes.</span></span></para>
          <para><span data-ttu-id="5b860-132">バージョンの変更操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-132">The change version operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateComputeNodeUser">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNodeUser CreateComputeNodeUser (string poolId, string computeNodeId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.ComputeNodeUser CreateComputeNodeUser(string poolId, string computeNodeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.CreateComputeNodeUser(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateComputeNodeUser (poolId As String, computeNodeId As String) As ComputeNodeUser" />
      <MemberSignature Language="F#" Value="member this.CreateComputeNodeUser : string * string -&gt; Microsoft.Azure.Batch.ComputeNodeUser" Usage="poolOperations.CreateComputeNodeUser (poolId, computeNodeId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNodeUser</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-133">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-133">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-134">ユーザー アカウントを作成するコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-134">The id of the compute node where the user account will be created.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-135">作成、<see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" />を表す新しいコンピューティング ノード ユーザー アカウントに、Batch service にまだ存在しません。</span><span class="sxs-lookup"><span data-stu-id="5b860-135">Creates a <see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" /> representing a new compute node user account that does not yet exist in the Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-136">非結合<see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" />コンピューティング ノードに追加されていない新しいユーザー アカウントを表すです。</span><span class="sxs-lookup"><span data-stu-id="5b860-136">An unbound <see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" /> representing a new user account that has not been added to the compute node.</span></span></returns>
        <remarks><span data-ttu-id="5b860-137">新しいユーザーを追加するには、呼び出す<see cref="M:Microsoft.Azure.Batch.ComputeNodeUser.CommitAsync(Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-137">To add the new user, call <see cref="M:Microsoft.Azure.Batch.ComputeNodeUser.CommitAsync(Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudPool CreatePool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudPool CreatePool() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.CreatePool" />
      <MemberSignature Language="VB.NET" Value="Public Function CreatePool () As CloudPool" />
      <MemberSignature Language="F#" Value="member this.CreatePool : unit -&gt; Microsoft.Azure.Batch.CloudPool" Usage="poolOperations.CreatePool " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5b860-138">バインドが、バッチ サービスでのすべてのプールに整合性のリレーションシップはありません CloudPool のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="5b860-138">Creates an instance of CloudPool that is unbound and does not have a consistency relationship to any pool in the Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-139">A<see cref="T:Microsoft.Azure.Batch.CloudPool" />バッチ サービスに追加されていない新しいプールを表すです。</span><span class="sxs-lookup"><span data-stu-id="5b860-139">A <see cref="T:Microsoft.Azure.Batch.CloudPool" /> representing a new pool that has not been added to the Batch service.</span></span>
            <span data-ttu-id="5b860-140">Batch アカウントにプールを追加するには、呼び出す<see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-140">To add the pool to the Batch account, call <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudPool CreatePool (string poolId, string virtualMachineSize, Microsoft.Azure.Batch.CloudServiceConfiguration cloudServiceConfiguration, Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudPool CreatePool(string poolId, string virtualMachineSize, class Microsoft.Azure.Batch.CloudServiceConfiguration cloudServiceConfiguration, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.CreatePool(System.String,System.String,Microsoft.Azure.Batch.CloudServiceConfiguration,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="member this.CreatePool : string * string * Microsoft.Azure.Batch.CloudServiceConfiguration * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.CloudPool" Usage="poolOperations.CreatePool (poolId, virtualMachineSize, cloudServiceConfiguration, targetDedicatedComputeNodes, targetLowPriorityComputeNodes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="virtualMachineSize" Type="System.String" />
        <Parameter Name="cloudServiceConfiguration" Type="Microsoft.Azure.Batch.CloudServiceConfiguration" />
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-141">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-141">The id of the pool.</span></span></param>
        <param name="virtualMachineSize">
            <span data-ttu-id="5b860-142">プール内の仮想マシンのサイズ。</span><span class="sxs-lookup"><span data-stu-id="5b860-142">The size of virtual machines in the pool.</span></span>  <span data-ttu-id="5b860-143">サイズの https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/ を参照してください。</span><span class="sxs-lookup"><span data-stu-id="5b860-143">See https://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/ for sizes.</span></span> <span data-ttu-id="5b860-144">バッチには、ExtraSmall、A1V2 A2V2 を除くすべての Azure クラウド サービスの VM サイズがサポートしています。</span><span class="sxs-lookup"><span data-stu-id="5b860-144">Batch supports all Azure cloud service VM sizes except ExtraSmall, A1V2 and A2V2.</span></span></param>
        <param name="cloudServiceConfiguration"><span data-ttu-id="5b860-145"><see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />プールします。</span><span class="sxs-lookup"><span data-stu-id="5b860-145">The <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> for the pool.</span></span></param>
        <param name="targetDedicatedComputeNodes">
            <span data-ttu-id="5b860-146">専用の目的の数は、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="5b860-146">The desired number of dedicated compute nodes in the pool.</span></span>
            <span data-ttu-id="5b860-147">場合<paramref name="targetDedicatedComputeNodes" />と<paramref name="targetLowPriorityComputeNodes" />は省略すると、設定する必要あります、<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" />と<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="5b860-147">If <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> are omitted, you must set the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> and <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> properties.</span></span>
            </param>
        <param name="targetLowPriorityComputeNodes">
            <span data-ttu-id="5b860-148">目的の優先度の低い数は、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="5b860-148">The desired number of low-priority compute nodes in the pool.</span></span>
            <span data-ttu-id="5b860-149">場合<paramref name="targetDedicatedComputeNodes" />と<paramref name="targetLowPriorityComputeNodes" />は省略すると、設定する必要あります、<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" />と<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="5b860-149">If <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> are omitted, you must set the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> and <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> properties.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b860-150">バインドが、バッチ サービスでのすべてのプールに整合性のリレーションシップはありません CloudPool のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="5b860-150">Creates an instance of CloudPool that is unbound and does not have a consistency relationship to any pool in the Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-151">A<see cref="T:Microsoft.Azure.Batch.CloudPool" />バッチ サービスに追加されていない新しいプールを表すです。</span><span class="sxs-lookup"><span data-stu-id="5b860-151">A <see cref="T:Microsoft.Azure.Batch.CloudPool" /> representing a new pool that has not been added to the Batch service.</span></span>
            <span data-ttu-id="5b860-152">Batch アカウントにプールを追加するには、呼び出す<see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-152">To add the pool to the Batch account, call <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-153">Azure ゲスト OS ファミリの詳細については、https://azure.microsoft.com/documentation/articles/cloud-services-guestos-update-matrix/ を参照してください。</span><span class="sxs-lookup"><span data-stu-id="5b860-153">For information about Azure Guest OS families, see https://azure.microsoft.com/documentation/articles/cloud-services-guestos-update-matrix/</span></span> </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudPool CreatePool (string poolId, string virtualMachineSize, Microsoft.Azure.Batch.VirtualMachineConfiguration virtualMachineConfiguration, Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudPool CreatePool(string poolId, string virtualMachineSize, class Microsoft.Azure.Batch.VirtualMachineConfiguration virtualMachineConfiguration, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.CreatePool(System.String,System.String,Microsoft.Azure.Batch.VirtualMachineConfiguration,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="member this.CreatePool : string * string * Microsoft.Azure.Batch.VirtualMachineConfiguration * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.CloudPool" Usage="poolOperations.CreatePool (poolId, virtualMachineSize, virtualMachineConfiguration, targetDedicatedComputeNodes, targetLowPriorityComputeNodes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="virtualMachineSize" Type="System.String" />
        <Parameter Name="virtualMachineConfiguration" Type="Microsoft.Azure.Batch.VirtualMachineConfiguration" />
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-154">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-154">The id of the pool.</span></span></param>
        <param name="virtualMachineSize"><span data-ttu-id="5b860-155">プール内の仮想マシンのサイズ。</span><span class="sxs-lookup"><span data-stu-id="5b860-155">The size of virtual machines in the pool.</span></span> <span data-ttu-id="5b860-156">Windows サイズ https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/ と linux のサイズの https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ を参照してください。</span><span class="sxs-lookup"><span data-stu-id="5b860-156">See https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/ for windows sizes and https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/ for linux sizes.</span></span>
            </param>
        <param name="virtualMachineConfiguration"><span data-ttu-id="5b860-157"><see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />プールします。</span><span class="sxs-lookup"><span data-stu-id="5b860-157">The <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> for the pool.</span></span></param>
        <param name="targetDedicatedComputeNodes">
            <span data-ttu-id="5b860-158">専用の目的の数は、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="5b860-158">The desired number of dedicated compute nodes in the pool.</span></span>
            <span data-ttu-id="5b860-159">場合<paramref name="targetDedicatedComputeNodes" />と<paramref name="targetLowPriorityComputeNodes" />は省略すると、設定する必要あります、<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" />と<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="5b860-159">If <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> are omitted, you must set the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> and <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> properties.</span></span>
            </param>
        <param name="targetLowPriorityComputeNodes">
            <span data-ttu-id="5b860-160">目的の優先度の低い数は、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="5b860-160">The desired number of low-priority compute nodes in the pool.</span></span>
            <span data-ttu-id="5b860-161">場合<paramref name="targetDedicatedComputeNodes" />と<paramref name="targetLowPriorityComputeNodes" />は省略すると、設定する必要あります、<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" />と<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="5b860-161">If <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> are omitted, you must set the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> and <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleFormula" /> properties.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b860-162">バインドが、バッチ サービスでのすべてのプールに整合性のリレーションシップはありません CloudPool のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="5b860-162">Creates an instance of CloudPool that is unbound and does not have a consistency relationship to any pool in the Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-163">A<see cref="T:Microsoft.Azure.Batch.CloudPool" />バッチ サービスに追加されていない新しいプールを表すです。</span><span class="sxs-lookup"><span data-stu-id="5b860-163">A <see cref="T:Microsoft.Azure.Batch.CloudPool" /> representing a new pool that has not been added to the Batch service.</span></span>
            <span data-ttu-id="5b860-164">Batch アカウントにプールを追加するには、呼び出す<see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-164">To add the pool to the Batch account, call <see cref="M:Microsoft.Azure.Batch.CloudPool.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />
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
            <span data-ttu-id="5b860-165">取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.PoolOperations" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-165">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.PoolOperations" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="5b860-166">これらの動作は、子オブジェクトによって継承されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-166">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="5b860-167">変更は、コレクションの順序で適用されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-167">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="5b860-168">最後には、wins を記述します。</span><span class="sxs-lookup"><span data-stu-id="5b860-168">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteComputeNodeUser">
      <MemberSignature Language="C#" Value="public void DeleteComputeNodeUser (string poolId, string computeNodeId, string userName, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteComputeNodeUser(string poolId, string computeNodeId, string userName, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeleteComputeNodeUser(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteComputeNodeUser (poolId As String, computeNodeId As String, userName As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteComputeNodeUser : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DeleteComputeNodeUser (poolId, computeNodeId, userName, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-169">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-169">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-170">ユーザー アカウントを削除するコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-170">The id of the compute node from which you want to delete the user account.</span></span></param>
        <param name="userName"><span data-ttu-id="5b860-171">削除するユーザー アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="5b860-171">The name of the user account to be deleted.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-172">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-172">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-173">指定された計算ノードから指定されたユーザー アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-173">Deletes the specified user account from the specified compute node.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="5b860-174">内にある場合にのみ、コンピューティング ノードからのユーザー アカウントを削除することができます、<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" />または<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" />状態です。</span><span class="sxs-lookup"><span data-stu-id="5b860-174">You can delete a user account from a compute node only when it is in the <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> or <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> state.</span></span></para>
          <para><span data-ttu-id="5b860-175">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-175">This is a blocking operation.</span></span> <span data-ttu-id="5b860-176">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.DeleteComputeNodeUserAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-176">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.DeleteComputeNodeUserAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteComputeNodeUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteComputeNodeUserAsync (string poolId, string computeNodeId, string userName, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteComputeNodeUserAsync(string poolId, string computeNodeId, string userName, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeleteComputeNodeUserAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteComputeNodeUserAsync : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DeleteComputeNodeUserAsync (poolId, computeNodeId, userName, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-177">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-177">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-178">ユーザー アカウントを削除するコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-178">The id of the compute node from which you want to delete the user account.</span></span></param>
        <param name="userName"><span data-ttu-id="5b860-179">削除するユーザー アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="5b860-179">The name of the user account to be deleted.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-180">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-180">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-181">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-181">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-182">指定された計算ノードから指定されたユーザー アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-182">Deletes the specified user account from the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-183">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-183">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-184">内にある場合にのみ、コンピューティング ノードからのユーザー アカウントを削除することができます、<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" />または<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" />状態です。</span><span class="sxs-lookup"><span data-stu-id="5b860-184">You can delete a user account from a compute node only when it is in the <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> or <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> state.</span></span></para>
          <para><span data-ttu-id="5b860-185">削除操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-185">The delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNodeFile">
      <MemberSignature Language="C#" Value="public void DeleteNodeFile (string poolId, string computeNodeId, string filePath, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteNodeFile(string poolId, string computeNodeId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeleteNodeFile(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteNodeFile (poolId As String, computeNodeId As String, filePath As String, Optional recursive As Nullable(Of Boolean) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteNodeFile : string * string * string * Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DeleteNodeFile (poolId, computeNodeId, filePath, recursive, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-186">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-186">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-187">コンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-187">The id of the compute node.</span></span></param>
        <param name="filePath"><span data-ttu-id="5b860-188">削除するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="5b860-188">The path of the file to delete.</span></span></param>
        <param name="recursive">
            <span data-ttu-id="5b860-189">ファイル パスのパラメーターは、ファイルの代わりにディレクトリを表している場合にディレクトリを削除するには、省略可能な再帰的なパラメーターをすべてのファイルとサブディレクトリを設定できます。</span><span class="sxs-lookup"><span data-stu-id="5b860-189">If the file-path parameter represents a directory instead of a file, you can set the optional recursive parameter to true to delete the directory and all of the files and subdirectories in it.</span></span> <span data-ttu-id="5b860-190">再帰が false の場合、ディレクトリを空にする必要がありますか、削除は失敗します。</span><span class="sxs-lookup"><span data-stu-id="5b860-190">If recursive is false then the directory must be empty or deletion will fail.</span></span>
            </param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-191">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-191">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-192">指定された計算ノードから、指定したファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-192">Deletes the specified file from the specified compute node.</span></span>
            </summary>
        <remarks><span data-ttu-id="5b860-193">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-193">This is a blocking operation.</span></span>  <span data-ttu-id="5b860-194">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-194">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNodeFileAsync (string poolId, string computeNodeId, string filePath, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNodeFileAsync(string poolId, string computeNodeId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteNodeFileAsync : string * string * string * Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DeleteNodeFileAsync (poolId, computeNodeId, filePath, recursive, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-195">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-195">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-196">コンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-196">The id of the compute node.</span></span></param>
        <param name="filePath"><span data-ttu-id="5b860-197">削除するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="5b860-197">The path of the file to delete.</span></span></param>
        <param name="recursive">
            <span data-ttu-id="5b860-198">ファイル パスのパラメーターは、ファイルの代わりにディレクトリを表している場合にディレクトリを削除するには、省略可能な再帰的なパラメーターをすべてのファイルとサブディレクトリを設定できます。</span><span class="sxs-lookup"><span data-stu-id="5b860-198">If the file-path parameter represents a directory instead of a file, you can set the optional recursive parameter to true to delete the directory and all of the files and subdirectories in it.</span></span> <span data-ttu-id="5b860-199">再帰が false の場合、ディレクトリを空にする必要がありますか、削除は失敗します。</span><span class="sxs-lookup"><span data-stu-id="5b860-199">If recursive is false then the directory must be empty or deletion will fail.</span></span>
            </param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-200">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-200">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-201">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-201">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-202">指定された計算ノードから、指定したファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-202">Deletes the specified file from the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-203">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-203">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="5b860-204">削除操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-204">The delete operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletePool">
      <MemberSignature Language="C#" Value="public void DeletePool (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeletePool(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeletePool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeletePool (poolId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeletePool : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DeletePool (poolId, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-205">削除するプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-205">The id of the pool to delete.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-206">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-206">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-207">指定したプールを削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-207">Deletes the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="5b860-208">削除操作は、プールが削除されることを要求します。</span><span class="sxs-lookup"><span data-stu-id="5b860-208">The delete operation requests that the pool be deleted.</span></span>  <span data-ttu-id="5b860-209">要求は、プールに格納、<see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="5b860-209">The request puts the pool in the <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" /> state.</span></span>
            <span data-ttu-id="5b860-210">バッチ サービスは、実行中のタスクをキューに再登録し、さらにクライアント操作をしなくても実際のプールの削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="5b860-210">The Batch service will requeue any running tasks and perform the actual pool deletion without any further client action.</span></span></para>
          <remarks><span data-ttu-id="5b860-211">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-211">This is a blocking operation.</span></span> <span data-ttu-id="5b860-212">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.DeletePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-212">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.DeletePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletePoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeletePoolAsync (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeletePoolAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DeletePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeletePoolAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DeletePoolAsync (poolId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;DeletePoolAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-213">削除するプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-213">The id of the pool to delete.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-214">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-214">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-215">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-215">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-216">指定したプールを削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-216">Deletes the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-217">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5b860-217">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-218">削除操作は、プールが削除されることを要求します。</span><span class="sxs-lookup"><span data-stu-id="5b860-218">The delete operation requests that the pool be deleted.</span></span>  <span data-ttu-id="5b860-219">要求は、プールに格納、<see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" />状態です。</span><span class="sxs-lookup"><span data-stu-id="5b860-219">The request puts the pool in the <see cref="F:Microsoft.Azure.Batch.Common.PoolState.Deleting" /> state.</span></span>
            <span data-ttu-id="5b860-220">バッチ サービスは、実行中のタスクをキューに再登録し、さらにクライアント操作をしなくても実際のプールの削除を実行します。</span><span class="sxs-lookup"><span data-stu-id="5b860-220">The Batch service will requeue any running tasks and perform the actual pool deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="5b860-221">削除操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-221">The delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScale">
      <MemberSignature Language="C#" Value="public void DisableAutoScale (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableAutoScale(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DisableAutoScale(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DisableAutoScale (poolId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DisableAutoScale : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DisableAutoScale (poolId, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-222">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-222">The id of the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-223">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-223">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-224">指定したプールの自動スケーリングを無効にします。</span><span class="sxs-lookup"><span data-stu-id="5b860-224">Disables automatic scaling on the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="5b860-225">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-225">This is a blocking operation.</span></span> <span data-ttu-id="5b860-226">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.DisableAutoScaleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-226">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.DisableAutoScaleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableAutoScaleAsync (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableAutoScaleAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DisableAutoScaleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableAutoScaleAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DisableAutoScaleAsync (poolId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;DisableAutoScaleAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-227">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-227">The id of the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-228">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-228">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-229">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-229">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-230">指定したプールの自動スケーリングを無効にします。</span><span class="sxs-lookup"><span data-stu-id="5b860-230">Disables automatic scaling on the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-231">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-231">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-232">無効にする自動スケール操作が非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-232">The disable autoscale operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableComputeNodeScheduling">
      <MemberSignature Language="C#" Value="public void DisableComputeNodeScheduling (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableComputeNodeScheduling(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DisableComputeNodeScheduling(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DisableComputeNodeScheduling (poolId As String, computeNodeId As String, disableComputeNodeSchedulingOption As Nullable(Of DisableComputeNodeSchedulingOption), Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DisableComputeNodeScheduling : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.DisableComputeNodeScheduling (poolId, computeNodeId, disableComputeNodeSchedulingOption, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="disableComputeNodeSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-233">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-233">The id of the pool.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-234">コンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-234">The id of the compute node.</span></span></param>
        <param name="disableComputeNodeSchedulingOption"><span data-ttu-id="5b860-235">実行中のタスクを行うには新機能を指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-235">Specifies what to do with currently running tasks.</span></span> <span data-ttu-id="5b860-236">既定では、 <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-236">The default is <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-237">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-237">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-238">指定したコンピューティング ノードでタスクのスケジュール設定を無効にします。</span><span class="sxs-lookup"><span data-stu-id="5b860-238">Disables task scheduling on the specified compute node.</span></span>
            </summary>
        <remarks><span data-ttu-id="5b860-239">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-239">This is a blocking operation.</span></span> <span data-ttu-id="5b860-240">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.DisableComputeNodeSchedulingAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-240">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.DisableComputeNodeSchedulingAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableComputeNodeSchedulingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableComputeNodeSchedulingAsync (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableComputeNodeSchedulingAsync(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.DisableComputeNodeSchedulingAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableComputeNodeSchedulingAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.DisableComputeNodeSchedulingAsync (poolId, computeNodeId, disableComputeNodeSchedulingOption, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="disableComputeNodeSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-241">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-241">The id of the pool.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-242">コンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-242">The id of the compute node.</span></span></param>
        <param name="disableComputeNodeSchedulingOption"><span data-ttu-id="5b860-243">実行中のタスクを行うには新機能を指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-243">Specifies what to do with currently running tasks.</span></span> <span data-ttu-id="5b860-244">既定では、 <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-244">The default is <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-245">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-245">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-246">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-246">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-247">指定したコンピューティング ノードでタスクのスケジュール設定を無効にします。</span><span class="sxs-lookup"><span data-stu-id="5b860-247">Disables task scheduling on the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-248">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-248">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="5b860-249">この操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-249">This operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScale">
      <MemberSignature Language="C#" Value="public void EnableAutoScale (string poolId, string autoscaleFormula = null, Nullable&lt;TimeSpan&gt; autoscaleEvaluationInterval = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableAutoScale(string poolId, string autoscaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoscaleEvaluationInterval, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScale(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableAutoScale (poolId As String, Optional autoscaleFormula As String = null, Optional autoscaleEvaluationInterval As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScale : string * string * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.EnableAutoScale (poolId, autoscaleFormula, autoscaleEvaluationInterval, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="autoscaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-250">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-250">The id of the pool.</span></span></param>
        <param name="autoscaleFormula"><span data-ttu-id="5b860-251">プール内の計算ノードの必要な数の式。</span><span class="sxs-lookup"><span data-stu-id="5b860-251">The formula for the desired number of compute nodes in the pool.</span></span></param>
        <param name="autoscaleEvaluationInterval"><span data-ttu-id="5b860-252">自動スケールの数式に従ってプールのサイズを自動的に調整する時間間隔。</span><span class="sxs-lookup"><span data-stu-id="5b860-252">The time interval at which to automatically adjust the pool size according to the AutoScale formula.</span></span> <span data-ttu-id="5b860-253">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-253">The default value is 15 minutes.</span></span> <span data-ttu-id="5b860-254">最小値は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-254">The minimum allowed value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-255">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-255">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-256">指定したプールの自動スケーリングを有効にします。</span><span class="sxs-lookup"><span data-stu-id="5b860-256">Enables automatic scaling on the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="5b860-257">数式は、プールに適用される前に、有効性に対してチェックされます。</span><span class="sxs-lookup"><span data-stu-id="5b860-257">The formula is checked for validity before it is applied to the pool.</span></span> <span data-ttu-id="5b860-258">数式が有効でない場合、例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="5b860-258">If the formula is not valid, an exception occurs.</span></span></para>
          <para><span data-ttu-id="5b860-259">サイズ変更操作が、プールで進行中の場合は、プールで自動スケーリングを有効にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="5b860-259">You cannot enable automatic scaling on a pool if a resize operation is in progress on the pool.</span></span></para>
          <para><span data-ttu-id="5b860-260">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-260">This is a blocking operation.</span></span> <span data-ttu-id="5b860-261">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScaleAsync(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-261">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScaleAsync(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableAutoScaleAsync (string poolId, string autoscaleFormula = null, Nullable&lt;TimeSpan&gt; autoscaleEvaluationInterval = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableAutoScaleAsync(string poolId, string autoscaleFormula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoscaleEvaluationInterval, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScaleAsync(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableAutoScaleAsync : string * string * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.EnableAutoScaleAsync (poolId, autoscaleFormula, autoscaleEvaluationInterval, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;EnableAutoScaleAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="autoscaleEvaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-262">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-262">The id of the pool.</span></span></param>
        <param name="autoscaleFormula"><span data-ttu-id="5b860-263">プール内の計算ノードの必要な数の式。</span><span class="sxs-lookup"><span data-stu-id="5b860-263">The formula for the desired number of compute nodes in the pool.</span></span></param>
        <param name="autoscaleEvaluationInterval"><span data-ttu-id="5b860-264">自動スケールの数式に従ってプールのサイズを自動的に調整する時間間隔。</span><span class="sxs-lookup"><span data-stu-id="5b860-264">The time interval at which to automatically adjust the pool size according to the AutoScale formula.</span></span> <span data-ttu-id="5b860-265">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-265">The default value is 15 minutes.</span></span> <span data-ttu-id="5b860-266">最小値は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-266">The minimum allowed value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-267">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-267">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-268">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-268">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-269">指定したプールの自動スケーリングを有効にします。</span><span class="sxs-lookup"><span data-stu-id="5b860-269">Enables automatic scaling on the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-270">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-270">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-271">数式は、プールに適用される前に、有効性に対してチェックされます。</span><span class="sxs-lookup"><span data-stu-id="5b860-271">The formula is checked for validity before it is applied to the pool.</span></span> <span data-ttu-id="5b860-272">数式が有効でない場合、例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="5b860-272">If the formula is not valid, an exception occurs.</span></span></para>
          <para><span data-ttu-id="5b860-273">サイズ変更操作が、プールで進行中の場合は、プールで自動スケーリングを有効にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="5b860-273">You cannot enable automatic scaling on a pool if a resize operation is in progress on the pool.</span></span></para>
          <para><span data-ttu-id="5b860-274">有効にする自動スケール操作が非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-274">The enable autoscale operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableComputeNodeScheduling">
      <MemberSignature Language="C#" Value="public void EnableComputeNodeScheduling (string poolId, string computeNodeId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableComputeNodeScheduling(string poolId, string computeNodeId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EnableComputeNodeScheduling(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableComputeNodeScheduling (poolId As String, computeNodeId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableComputeNodeScheduling : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.EnableComputeNodeScheduling (poolId, computeNodeId, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-275">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-275">The id of the pool.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-276">コンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-276">The id of the compute node.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-277">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-277">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-278">指定したコンピューティング ノードでタスクのスケジュール設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="5b860-278">Enables task scheduling on the specified compute node.</span></span>
            </summary>
        <remarks><span data-ttu-id="5b860-279">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-279">This is a blocking operation.</span></span> <span data-ttu-id="5b860-280">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableComputeNodeScheduling(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-280">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableComputeNodeScheduling(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableComputeNodeSchedulingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableComputeNodeSchedulingAsync (string poolId, string computeNodeId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableComputeNodeSchedulingAsync(string poolId, string computeNodeId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EnableComputeNodeSchedulingAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableComputeNodeSchedulingAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.EnableComputeNodeSchedulingAsync (poolId, computeNodeId, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-281">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-281">The id of the pool.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-282">コンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-282">The id of the compute node.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-283">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-283">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-284">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-284">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-285">指定したコンピューティング ノードでタスクのスケジュール設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="5b860-285">Enables task scheduling on the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-286">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-286">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="5b860-287">この操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-287">This operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScale">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AutoScaleRun EvaluateAutoScale (string poolId, string autoscaleFormula, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.AutoScaleRun EvaluateAutoScale(string poolId, string autoscaleFormula, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EvaluateAutoScale(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function EvaluateAutoScale (poolId As String, autoscaleFormula As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As AutoScaleRun" />
      <MemberSignature Language="F#" Value="member this.EvaluateAutoScale : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.AutoScaleRun" Usage="poolOperations.EvaluateAutoScale (poolId, autoscaleFormula, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AutoScaleRun</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-288">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-288">The id of the pool.</span></span></param>
        <param name="autoscaleFormula"><span data-ttu-id="5b860-289">プールで評価される式です。</span><span class="sxs-lookup"><span data-stu-id="5b860-289">The formula to be evaluated on the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-290">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-290">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-291">指定したプール内の数式のスケーリングの自動評価結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="5b860-291">Gets the result of evaluating an automatic scaling formula on the specified pool.</span></span>  <span data-ttu-id="5b860-292">これは、自動スケール式を検証するため、主に、プールに、式を適用せず、結果を単純に返します。</span><span class="sxs-lookup"><span data-stu-id="5b860-292">This is primarily for validating an autoscale formula, as it simply returns the result without applying the formula to the pool.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-293">評価した結果、<paramref name="autoscaleFormula" />指定されたプールにします。</span><span class="sxs-lookup"><span data-stu-id="5b860-293">The result of evaluating the <paramref name="autoscaleFormula" /> on the specified pool.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-294">数式が検証され、その結果が計算されがプールには適用されません。</span><span class="sxs-lookup"><span data-stu-id="5b860-294">The formula is validated and its results calculated, but is not applied to the pool.</span></span>  <span data-ttu-id="5b860-295">適用するには、数式をプールを使用して<see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScale(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-295">To apply the formula to the pool, use <see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScale(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></para>
          <para><span data-ttu-id="5b860-296">このメソッドは、プールのすべての状態は変更されませんしは影響しません、<see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" />または<see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-296">This method does not change any state of the pool, and does not affect the <see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" /> or <see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />.</span></span></para>
          <para><span data-ttu-id="5b860-297">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-297">This is a blocking operation.</span></span> <span data-ttu-id="5b860-298">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.EvaluateAutoScaleAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-298">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.EvaluateAutoScaleAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScaleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt; EvaluateAutoScaleAsync (string poolId, string autoscaleFormula, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.AutoScaleRun&gt; EvaluateAutoScaleAsync(string poolId, string autoscaleFormula, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.EvaluateAutoScaleAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EvaluateAutoScaleAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt;" Usage="poolOperations.EvaluateAutoScaleAsync (poolId, autoscaleFormula, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;EvaluateAutoScaleAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.AutoScaleRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoscaleFormula" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-299">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-299">The id of the pool.</span></span></param>
        <param name="autoscaleFormula"><span data-ttu-id="5b860-300">プールで評価される式です。</span><span class="sxs-lookup"><span data-stu-id="5b860-300">The formula to be evaluated on the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-301">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-301">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-302">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-302">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-303">指定したプール内の数式のスケーリングの自動評価結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="5b860-303">Gets the result of evaluating an automatic scaling formula on the specified pool.</span></span>  <span data-ttu-id="5b860-304">これは、自動スケール式を検証するため、主に、プールに、式を適用せず、結果を単純に返します。</span><span class="sxs-lookup"><span data-stu-id="5b860-304">This is primarily for validating an autoscale formula, as it simply returns the result without applying the formula to the pool.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-305">評価した結果、<paramref name="autoscaleFormula" />指定されたプールにします。</span><span class="sxs-lookup"><span data-stu-id="5b860-305">The result of evaluating the <paramref name="autoscaleFormula" /> on the specified pool.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-306">数式が検証され、その結果が計算されがプールには適用されません。</span><span class="sxs-lookup"><span data-stu-id="5b860-306">The formula is validated and its results calculated, but is not applied to the pool.</span></span>  <span data-ttu-id="5b860-307">適用するには、数式をプールを使用して<see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScaleAsync(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-307">To apply the formula to the pool, use <see cref="M:Microsoft.Azure.Batch.PoolOperations.EnableAutoScaleAsync(System.String,System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="5b860-308">このメソッドは、プールのすべての状態は変更されませんしは影響しません、<see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" />または<see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-308">This method does not change any state of the pool, and does not affect the <see cref="P:Microsoft.Azure.Batch.CloudPool.LastModified" /> or <see cref="P:Microsoft.Azure.Batch.CloudPool.ETag" />.</span></span></para>
          <para><span data-ttu-id="5b860-309">評価操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-309">The evaluate operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolStatistics GetAllLifetimeStatistics (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.PoolStatistics GetAllLifetimeStatistics(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetAllLifetimeStatistics(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllLifetimeStatistics (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As PoolStatistics" />
      <MemberSignature Language="F#" Value="member this.GetAllLifetimeStatistics : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.PoolStatistics" Usage="poolOperations.GetAllLifetimeStatistics additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-310">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-310">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-311">現在のアカウント内のプールのすべての有効期間の概要統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="5b860-311">Gets lifetime summary statistics for all of the pools in the current account.</span></span>  
            <span data-ttu-id="5b860-312">統計情報は、存在していたアカウントを作成してから、アカウントの最後の更新時刻、統計のすべてのプール間で集計されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-312">Statistics are aggregated across all pools that have ever existed in the account, from account creation to the last update time of the statistics.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-313">集計されたプールの統計。</span><span class="sxs-lookup"><span data-stu-id="5b860-313">The aggregated pool statistics.</span></span></returns>
        <remarks><span data-ttu-id="5b860-314">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-314">This is a blocking operation.</span></span> <span data-ttu-id="5b860-315">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-315">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatisticsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.PoolStatistics&gt; GetAllLifetimeStatisticsAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.PoolStatistics&gt; GetAllLifetimeStatisticsAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetAllLifetimeStatisticsAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.PoolStatistics&gt;" Usage="poolOperations.GetAllLifetimeStatisticsAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;GetAllLifetimeStatisticsAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.PoolStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-316">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-316">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-317">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-317">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-318">現在のアカウント内のプールのすべての有効期間の概要統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="5b860-318">Gets lifetime summary statistics for all of the pools in the current account.</span></span>
            <span data-ttu-id="5b860-319">統計情報は、存在していたアカウントを作成してから、アカウントの最後の更新時刻、統計のすべてのプール間で集計されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-319">Statistics are aggregated across all pools that have ever existed in the account, from account creation to the last update time of the statistics.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-320">集計されたプールの統計。</span><span class="sxs-lookup"><span data-stu-id="5b860-320">The aggregated pool statistics.</span></span></returns>
        <remarks><span data-ttu-id="5b860-321">統計情報の取得操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-321">The get statistics operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetComputeNode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNode GetComputeNode (string poolId, string computeNodeId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.ComputeNode GetComputeNode(string poolId, string computeNodeId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetComputeNode(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetComputeNode : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.ComputeNode" Usage="poolOperations.GetComputeNode (poolId, computeNodeId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-322">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-322">The id of the pool.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-323">プールから取得するコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-323">The id of the compute node to get from the pool.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="5b860-324">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="5b860-324">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-325">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-325">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-326">指定された計算ノードを取得します。</span><span class="sxs-lookup"><span data-stu-id="5b860-326">Gets the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-327">A<see cref="T:Microsoft.Azure.Batch.ComputeNode" />指定された計算ノードに関する情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="5b860-327">A <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> containing information about the specified compute node.</span></span></returns>
        <remarks><span data-ttu-id="5b860-328">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-328">This is a blocking operation.</span></span> <span data-ttu-id="5b860-329">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetComputeNodeAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-329">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetComputeNodeAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetComputeNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt; GetComputeNodeAsync (string poolId, string computeNodeId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; GetComputeNodeAsync(string poolId, string computeNodeId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetComputeNodeAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetComputeNodeAsync : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt;" Usage="poolOperations.GetComputeNodeAsync (poolId, computeNodeId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.ComputeNode&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-330">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-330">The id of the pool.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-331">プールから取得するコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-331">The id of the compute node to get from the pool.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="5b860-332">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="5b860-332">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-333">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-333">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-334">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-334">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-335">指定された計算ノードを取得します。</span><span class="sxs-lookup"><span data-stu-id="5b860-335">Gets the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-336">A<see cref="T:Microsoft.Azure.Batch.ComputeNode" />指定された計算ノードに関する情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="5b860-336">A <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> containing information about the specified compute node.</span></span></returns>
        <remarks><span data-ttu-id="5b860-337">ノードの取得操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-337">The get node operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.NodeFile GetNodeFile (string poolId, string computeNodeId, string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.NodeFile GetNodeFile(string poolId, string computeNodeId, string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetNodeFile(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeFile (poolId As String, computeNodeId As String, filePath As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As NodeFile" />
      <MemberSignature Language="F#" Value="member this.GetNodeFile : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.NodeFile" Usage="poolOperations.GetNodeFile (poolId, computeNodeId, filePath, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-338">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-338">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-339">コンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-339">The id of the compute node.</span></span></param>
        <param name="filePath"><span data-ttu-id="5b860-340">取得するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="5b860-340">The path of the file to retrieve.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-341">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-341">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-342">コンピューティング ノード上のファイルに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="5b860-342">Gets information about a file on a compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-343">A<see cref="T:Microsoft.Azure.Batch.NodeFile" />ファイル、およびファイルをダウンロードして使用できるに関する情報を含む (を参照してください<see cref="M:Microsoft.Azure.Batch.NodeFile.CopyToStream(System.IO.Stream,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />)。</span><span class="sxs-lookup"><span data-stu-id="5b860-343">A <see cref="T:Microsoft.Azure.Batch.NodeFile" /> containing information about the file, and which can be used to download the file (see <see cref="M:Microsoft.Azure.Batch.NodeFile.CopyToStream(System.IO.Stream,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />).</span></span></returns>
        <remarks><span data-ttu-id="5b860-344">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-344">This is a blocking operation.</span></span> <span data-ttu-id="5b860-345">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-345">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync (string poolId, string computeNodeId, string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync(string poolId, string computeNodeId, string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeFileAsync : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="poolOperations.GetNodeFileAsync (poolId, computeNodeId, filePath, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-346">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-346">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-347">コンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-347">The id of the compute node.</span></span></param>
        <param name="filePath"><span data-ttu-id="5b860-348">取得するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="5b860-348">The path of the file to retrieve.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-349">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-349">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-350">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-350">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-351">コンピューティング ノード上のファイルに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="5b860-351">Gets information about a file on a compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-352">A<see cref="T:Microsoft.Azure.Batch.NodeFile" />ファイル、およびファイルをダウンロードして使用できるに関する情報を含む (を参照してください<see cref="M:Microsoft.Azure.Batch.NodeFile.CopyToStreamAsync(System.IO.Stream,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />)。</span><span class="sxs-lookup"><span data-stu-id="5b860-352">A <see cref="T:Microsoft.Azure.Batch.NodeFile" /> containing information about the file, and which can be used to download the file (see <see cref="M:Microsoft.Azure.Batch.NodeFile.CopyToStreamAsync(System.IO.Stream,Microsoft.Azure.Batch.GetFileRequestByteRange,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />).</span></span></returns>
        <remarks><span data-ttu-id="5b860-353">ファイルの取得操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-353">The get file operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPool">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudPool GetPool (string poolId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudPool GetPool(string poolId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetPool(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetPool : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.CloudPool" Usage="poolOperations.GetPool (poolId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-354">取得するプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-354">The id of the pool to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="5b860-355">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="5b860-355">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-356">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-356">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-357">指定した <see cref="T:Microsoft.Azure.Batch.CloudPool" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="5b860-357">Gets the specified <see cref="T:Microsoft.Azure.Batch.CloudPool" />.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-358">A<see cref="T:Microsoft.Azure.Batch.CloudPool" />指定した Azure Batch プールに関する情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="5b860-358">A <see cref="T:Microsoft.Azure.Batch.CloudPool" /> containing information about the specified Azure Batch pool.</span></span></returns>
        <remarks><span data-ttu-id="5b860-359">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-359">This is a blocking operation.</span></span> <span data-ttu-id="5b860-360">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetPoolAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-360">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetPoolAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudPool&gt; GetPoolAsync (string poolId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.CloudPool&gt; GetPoolAsync(string poolId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetPoolAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPoolAsync : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudPool&gt;" Usage="poolOperations.GetPoolAsync (poolId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;GetPoolAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-361">取得するプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-361">The id of the pool to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="5b860-362">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="5b860-362">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-363">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-363">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-364">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-364">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-365">指定した <see cref="T:Microsoft.Azure.Batch.CloudPool" /> を取得します。</span><span class="sxs-lookup"><span data-stu-id="5b860-365">Gets the specified <see cref="T:Microsoft.Azure.Batch.CloudPool" />.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-366">A<see cref="T:Microsoft.Azure.Batch.CloudPool" />指定した Azure Batch プールに関する情報を格納します。</span><span class="sxs-lookup"><span data-stu-id="5b860-366">A <see cref="T:Microsoft.Azure.Batch.CloudPool" /> containing information about the specified Azure Batch pool.</span></span></returns>
        <remarks><span data-ttu-id="5b860-367">プールの取得操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-367">The get pool operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFile">
      <MemberSignature Language="C#" Value="public void GetRDPFile (string poolId, string computeNodeId, System.IO.Stream rdpStream, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetRDPFile(string poolId, string computeNodeId, class System.IO.Stream rdpStream, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFile(System.String,System.String,System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetRDPFile (poolId As String, computeNodeId As String, rdpStream As Stream, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFile : string * string * System.IO.Stream * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.GetRDPFile (poolId, computeNodeId, rdpStream, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rdpStream" Type="System.IO.Stream" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-368">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-368">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-369">リモート デスクトップ ファイルを取得する対象のコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-369">The id of the compute node for which to get a Remote Desktop file.</span></span></param>
        <param name="rdpStream"><span data-ttu-id="5b860-370"><see cref="T:System.IO.Stream" />に RDP ファイルの内容を書き込まれます。</span><span class="sxs-lookup"><span data-stu-id="5b860-370">The <see cref="T:System.IO.Stream" /> into which the RDP file contents will be written.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-371">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-371">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-372">指定したノードのリモート デスクトップ プロトコル (RDP) ファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="5b860-372">Gets a Remote Desktop Protocol (RDP) file for the specified node.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="5b860-373">このメソッドが閉じない、<paramref name="rdpStream" />ストリーム、およびそれでは、書き込み終了後の位置はリセットされません。</span><span class="sxs-lookup"><span data-stu-id="5b860-373">This method does not close the <paramref name="rdpStream" /> stream, and it does not reset the position after writing.</span></span>
            <span data-ttu-id="5b860-374">呼び出し元の責任ストリームを閉じ、または必要な場合は、位置をリセットします。</span><span class="sxs-lookup"><span data-stu-id="5b860-374">It is the caller's responsibility to close the stream, or to reset the position if required.</span></span></para>
          <para><span data-ttu-id="5b860-375">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-375">This is a blocking operation.</span></span> <span data-ttu-id="5b860-376">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-376">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="5b860-377">プールが作成された場合にのみ、このメソッドを呼び出すことができます、<see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="5b860-377">This method can be invoked only if the pool is created with a <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> property.</span></span> <span data-ttu-id="5b860-378">このメソッドで作成されたプールで呼び出される場合<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />、Batch サービスが 409 (Conflict) を返します。</span><span class="sxs-lookup"><span data-stu-id="5b860-378">If this method is invoked on pools created with <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />, then Batch service returns 409 (Conflict).</span></span> <span data-ttu-id="5b860-379">指定されているのため<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />プロパティ、新しいメソッド<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b860-379">For pools with <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> property, the new method <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> must be used.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFile">
      <MemberSignature Language="C#" Value="public void GetRDPFile (string poolId, string computeNodeId, string rdpFileNameToCreate, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetRDPFile(string poolId, string computeNodeId, string rdpFileNameToCreate, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFile(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetRDPFile (poolId As String, computeNodeId As String, rdpFileNameToCreate As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFile : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.GetRDPFile (poolId, computeNodeId, rdpFileNameToCreate, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rdpFileNameToCreate" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-380">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-380">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-381">リモート デスクトップ ファイルを取得する対象のコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-381">The id of the compute node for which to get a Remote Desktop file.</span></span></param>
        <param name="rdpFileNameToCreate"><span data-ttu-id="5b860-382">RDP ファイルを作成するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="5b860-382">The file path at which to create the RDP file.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-383">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-383">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-384">指定したノードのリモート デスクトップ プロトコル ファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="5b860-384">Gets a Remote Desktop Protocol file for the specified node.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="5b860-385">ファイルを指定して場合<paramref name="rdpFileNameToCreate" />が既に存在するが上書きされます。</span><span class="sxs-lookup"><span data-stu-id="5b860-385">If the file specified by <paramref name="rdpFileNameToCreate" /> already exists, it is overwritten.</span></span></para>
          <para><span data-ttu-id="5b860-386">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-386">This is a blocking operation.</span></span> <span data-ttu-id="5b860-387">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-387">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="5b860-388">プールが作成された場合にのみ、このメソッドを呼び出すことができます、<see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="5b860-388">This method can be invoked only if the pool is created with a <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> property.</span></span> <span data-ttu-id="5b860-389">このメソッドで作成されたプールで呼び出される場合<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />、Batch サービスが 409 (Conflict) を返します。</span><span class="sxs-lookup"><span data-stu-id="5b860-389">If this method is invoked on pools created with <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />, then Batch service returns 409 (Conflict).</span></span> <span data-ttu-id="5b860-390">指定されているのため<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />プロパティ、新しいメソッド<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b860-390">For pools with <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> property, the new method <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> must be used.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task GetRDPFileAsync (string poolId, string computeNodeId, System.IO.Stream rdpStream, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task GetRDPFileAsync(string poolId, string computeNodeId, class System.IO.Stream rdpStream, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFileAsync : string * string * System.IO.Stream * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.GetRDPFileAsync (poolId, computeNodeId, rdpStream, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rdpStream" Type="System.IO.Stream" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-391">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-391">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-392">リモート デスクトップ ファイルを取得する対象のコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-392">The id of the compute node for which to get a Remote Desktop file.</span></span></param>
        <param name="rdpStream"><span data-ttu-id="5b860-393"><see cref="T:System.IO.Stream" />に RDP ファイルの内容を書き込まれます。</span><span class="sxs-lookup"><span data-stu-id="5b860-393">The <see cref="T:System.IO.Stream" /> into which the RDP file contents will be written.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-394">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-394">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-395">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-395">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-396">指定したノードのリモート デスクトップ プロトコル (RDP) ファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="5b860-396">Gets a Remote Desktop Protocol (RDP) file for the specified node.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-397">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-397">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-398">このメソッドが閉じない、<paramref name="rdpStream" />ストリーム、およびそれでは、書き込み終了後の位置はリセットされません。</span><span class="sxs-lookup"><span data-stu-id="5b860-398">This method does not close the <paramref name="rdpStream" /> stream, and it does not reset the position after writing.</span></span>
            <span data-ttu-id="5b860-399">呼び出し元の責任ストリームを閉じ、または必要な場合は、位置をリセットします。</span><span class="sxs-lookup"><span data-stu-id="5b860-399">It is the caller's responsibility to close the stream, or to reset the position if required.</span></span></para>
          <para><span data-ttu-id="5b860-400">RDP ファイルの取得操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-400">The get RDP file operation runs asynchronously.</span></span></para>
          <para><span data-ttu-id="5b860-401">プールが作成された場合にのみ、このメソッドを呼び出すことができます、<see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="5b860-401">This method can be invoked only if the pool is created with a <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> property.</span></span> <span data-ttu-id="5b860-402">このメソッドで作成されたプールで呼び出される場合<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />、Batch サービスが 409 (Conflict) を返します。</span><span class="sxs-lookup"><span data-stu-id="5b860-402">If this method is invoked on pools created with <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />, then Batch service returns 409 (Conflict).</span></span> <span data-ttu-id="5b860-403">指定されているのため<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />プロパティ、新しいメソッド<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b860-403">For pools with <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> property, the new method <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> must be used.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task GetRDPFileAsync (string poolId, string computeNodeId, string rdpFileNameToCreate, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task GetRDPFileAsync(string poolId, string computeNodeId, string rdpFileNameToCreate, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRDPFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFileAsync : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.GetRDPFileAsync (poolId, computeNodeId, rdpFileNameToCreate, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rdpFileNameToCreate" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-404">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-404">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-405">リモート デスクトップ ファイルを取得する対象のコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-405">The id of the compute node for which to get a Remote Desktop file.</span></span></param>
        <param name="rdpFileNameToCreate"><span data-ttu-id="5b860-406">RDP ファイルを作成するファイルのパス。</span><span class="sxs-lookup"><span data-stu-id="5b860-406">The file path at which to create the RDP file.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-407">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-407">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-408">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-408">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-409">指定したノードのリモート デスクトップ プロトコル ファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="5b860-409">Gets a Remote Desktop Protocol file for the specified node.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-410">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-410">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-411">ファイルを指定して場合<paramref name="rdpFileNameToCreate" />が既に存在するが上書きされます。</span><span class="sxs-lookup"><span data-stu-id="5b860-411">If the file specified by <paramref name="rdpFileNameToCreate" /> already exists, it is overwritten.</span></span></para>
          <para><span data-ttu-id="5b860-412">RDP ファイルの取得操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-412">The get RDP file operation runs asynchronously.</span></span></para>
          <para><span data-ttu-id="5b860-413">プールが作成された場合にのみ、このメソッドを呼び出すことができます、<see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="5b860-413">This method can be invoked only if the pool is created with a <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> property.</span></span> <span data-ttu-id="5b860-414">このメソッドで作成されたプールで呼び出される場合<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />、Batch サービスが 409 (Conflict) を返します。</span><span class="sxs-lookup"><span data-stu-id="5b860-414">If this method is invoked on pools created with <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />, then Batch service returns 409 (Conflict).</span></span> <span data-ttu-id="5b860-415">指定されているのため<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />プロパティ、新しいメソッド<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettingsAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b860-415">For pools with <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> property, the new method <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettingsAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> must be used.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteLoginSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.RemoteLoginSettings GetRemoteLoginSettings (string poolId, string computeNodeId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.RemoteLoginSettings GetRemoteLoginSettings(string poolId, string computeNodeId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettings(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRemoteLoginSettings (poolId As String, computeNodeId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As RemoteLoginSettings" />
      <MemberSignature Language="F#" Value="member this.GetRemoteLoginSettings : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.RemoteLoginSettings" Usage="poolOperations.GetRemoteLoginSettings (poolId, computeNodeId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.RemoteLoginSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-416">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-416">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-417">リモート デスクトップ ファイルを取得する対象のコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-417">The id of the compute node for which to get a Remote Desktop file.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-418">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-418">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-419">コンピューティング ノードへのリモート ログイン用に必要な設定を取得します。</span><span class="sxs-lookup"><span data-stu-id="5b860-419">Gets the settings required for remote login to a compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
          <para><span data-ttu-id="5b860-420">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-420">This is a blocking operation.</span></span> <span data-ttu-id="5b860-421">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettingsAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-421">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettingsAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="5b860-422">プールが作成された場合にのみ、このメソッドを呼び出すことができます、<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="5b860-422">This method can be invoked only if the pool is created with a <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> property.</span></span> <span data-ttu-id="5b860-423">このメソッドで作成されたプールで呼び出される場合<see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />、Batch サービスが 409 (Conflict) を返します。</span><span class="sxs-lookup"><span data-stu-id="5b860-423">If this method is invoked on pools created with <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />, then Batch service returns 409 (Conflict).</span></span> <span data-ttu-id="5b860-424">指定されているのため、 <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> GetRDPFileAsync/GetRDPFile のいずれかのプロパティを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b860-424">For pools with a <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> property, one of the GetRDPFileAsync/GetRDPFile methods must be used.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteLoginSettingsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt; GetRemoteLoginSettingsAsync (string poolId, string computeNodeId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.RemoteLoginSettings&gt; GetRemoteLoginSettingsAsync(string poolId, string computeNodeId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.GetRemoteLoginSettingsAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRemoteLoginSettingsAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt;" Usage="poolOperations.GetRemoteLoginSettingsAsync (poolId, computeNodeId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-425">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-425">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-426">リモート デスクトップ ファイルを取得する対象のコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-426">The id of the compute node for which to get a Remote Desktop file.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-427">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-427">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-428">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-428">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-429">コンピューティング ノードへのリモート ログイン用に必要な設定を取得します。</span><span class="sxs-lookup"><span data-stu-id="5b860-429">Gets the settings required for remote login to a compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-430">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-430">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-431">リモート ログインの設定の取得操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-431">The get remote login settings operation runs asynchronously.</span></span></para>
          <para><span data-ttu-id="5b860-432">プールが作成された場合にのみ、このメソッドを呼び出すことができます、<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="5b860-432">This method can be invoked only if the pool is created with a <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> property.</span></span> <span data-ttu-id="5b860-433">このメソッドで作成されたプールで呼び出される場合<see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />、Batch サービスが 409 (Conflict) を返します。</span><span class="sxs-lookup"><span data-stu-id="5b860-433">If this method is invoked on pools created with <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />, then Batch service returns 409 (Conflict).</span></span> <span data-ttu-id="5b860-434">指定されているのため、 <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> GetRDPFileAsync/GetRDPFile のいずれかのプロパティを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b860-434">For pools with a <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> property, one of the GetRDPFileAsync/GetRDPFile methods must be used.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListComputeNodes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; ListComputeNodes (string poolId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; ListComputeNodes(string poolId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListComputeNodes(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListComputeNodes : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" Usage="poolOperations.ListComputeNodes (poolId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-435">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-435">The id of the pool.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="5b860-436">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="5b860-436">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-437">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-437">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-438">列挙、<see cref="T:Microsoft.Azure.Batch.ComputeNode">コンピューティング ノード</see>の指定したプールします。</span><span class="sxs-lookup"><span data-stu-id="5b860-438">Enumerates the <see cref="T:Microsoft.Azure.Batch.ComputeNode">compute nodes</see> of the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-439"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />非同期的または同期的にコンピューティング ノードの列挙を使用できます。</span><span class="sxs-lookup"><span data-stu-id="5b860-439">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate compute nodes asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="5b860-440">このメソッドがすぐに戻るノードは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-440">This method returns immediately; the nodes are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="5b860-441">検索は非アトミックなです。ノードは、コレクションの列挙中にページで取得されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-441">Retrieval is non-atomic; nodes are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeAgentSkus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeAgentSku&gt; ListNodeAgentSkus (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.NodeAgentSku&gt; ListNodeAgentSkus(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListNodeAgentSkus(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListNodeAgentSkus : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeAgentSku&gt;" Usage="poolOperations.ListNodeAgentSkus (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeAgentSku&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="5b860-442">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="5b860-442">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-443">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-443">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-444">Batch Service によってサポートされているノード エージェント Sku 値を列挙します。</span><span class="sxs-lookup"><span data-stu-id="5b860-444">Enumerates the node agent Sku values supported by Batch Service.</span></span> 
            </summary>
        <returns><span data-ttu-id="5b860-445"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />ノード エージェント sku 値を非同期的または同期的に列挙を使用できます。</span><span class="sxs-lookup"><span data-stu-id="5b860-445">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate node agent sku values asynchronously or synchronously.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeFiles">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles (string poolId, string computeNodeId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListNodeFiles(System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListNodeFiles : string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="poolOperations.ListNodeFiles (poolId, computeNodeId, recursive, detailLevel, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-446">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-446">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-447">コンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-447">The id of the compute node.</span></span></param>
        <param name="recursive"><span data-ttu-id="5b860-448">True の場合、再帰的には、コンピューティング ノードのすべてのファイルを列挙します。</span><span class="sxs-lookup"><span data-stu-id="5b860-448">If true, recursively enumerates all files on the compute node.</span></span> <span data-ttu-id="5b860-449">False の場合は、コンピューティング ノードのルート ディレクトリ内のファイルのみを列挙します。</span><span class="sxs-lookup"><span data-stu-id="5b860-449">If false, enumerates only the files in the compute node root directory.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="5b860-450">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="5b860-450">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-451">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-451">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-452">指定された計算ノード上のファイルを列挙します。</span><span class="sxs-lookup"><span data-stu-id="5b860-452">Enumerates files on the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-453"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />ファイルを列挙する非同期的または同期的に使用できます。</span><span class="sxs-lookup"><span data-stu-id="5b860-453">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate files asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="5b860-454">このメソッドがすぐに戻るファイル データは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-454">This method returns immediately; the file data is retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="5b860-455">検索は非アトミックなです。ファイル データは、コレクションの列挙中にページで取得されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-455">Retrieval is non-atomic; file data is retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudPool&gt; ListPools (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudPool&gt; ListPools(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListPools : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudPool&gt;" Usage="poolOperations.ListPools (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="5b860-456">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="5b860-456">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-457">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-457">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-458">列挙、<see cref="T:Microsoft.Azure.Batch.CloudPool">プール</see>Batch アカウントにします。</span><span class="sxs-lookup"><span data-stu-id="5b860-458">Enumerates the <see cref="T:Microsoft.Azure.Batch.CloudPool">pools</see> in the Batch account.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-459"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を非同期的または同期的には、プールを列挙を使用できます。</span><span class="sxs-lookup"><span data-stu-id="5b860-459">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate pools asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="5b860-460">このメソッドがすぐに戻るプールは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-460">This method returns immediately; the pools are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="5b860-461">検索は非アトミックなです。プールは、コレクションの列挙中にページで取得されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-461">Retrieval is non-atomic; pools are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPoolUsageMetrics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.PoolUsageMetrics&gt; ListPoolUsageMetrics (Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.PoolUsageMetrics&gt; ListPoolUsageMetrics(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ListPoolUsageMetrics(System.Nullable{System.DateTime},System.Nullable{System.DateTime},Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListPoolUsageMetrics : Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.PoolUsageMetrics&gt;" Usage="poolOperations.ListPoolUsageMetrics (startTime, endTime, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.PoolUsageMetrics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="startTime"><span data-ttu-id="5b860-462">このエントリに含まれる集計範囲の開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="5b860-462">The start time of the aggregation interval covered by this entry.</span></span></param>
        <param name="endTime"><span data-ttu-id="5b860-463">このエントリの集計間隔の終了時刻です。</span><span class="sxs-lookup"><span data-stu-id="5b860-463">The end time of the aggregation interval for this entry.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="5b860-464">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</span><span class="sxs-lookup"><span data-stu-id="5b860-464">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-465">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-465">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-466">プールの使用状況メトリックを列挙します。</span><span class="sxs-lookup"><span data-stu-id="5b860-466">Enumerates pool usage metrics.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-467"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />メトリックを非同期的または同期的に列挙を使用できます。</span><span class="sxs-lookup"><span data-stu-id="5b860-467">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate metrics asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="5b860-468">このメソッドがすぐに戻るメトリック データは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-468">This method returns immediately; the metrics data is retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="5b860-469">検索は非アトミックなです。メトリック データは、コレクションの列挙中にページで取得されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-469">Retrieval is non-atomic; metrics data is retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Reboot">
      <MemberSignature Language="C#" Value="public void Reboot (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Reboot(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.Reboot(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reboot (poolId As String, computeNodeId As String, Optional rebootOption As Nullable(Of ComputeNodeRebootOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Reboot : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.Reboot (poolId, computeNodeId, rebootOption, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-470">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-470">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-471">再起動してコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-471">The id of the compute node to reboot.</span></span></param>
        <param name="rebootOption"><span data-ttu-id="5b860-472">ノードを再起動して、実行中のタスクの処理方法を指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-472">Specifies when to reboot the node and what to do with currently running tasks.</span></span> <span data-ttu-id="5b860-473">既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.Requeue" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-473">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.Requeue" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-474">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-474">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-475">指定された計算ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="5b860-475">Reboots the specified compute node.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="5b860-476">コンピューティング ノードを再起動するにあるときにのみ、<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" />または<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" />状態です。</span><span class="sxs-lookup"><span data-stu-id="5b860-476">You can reboot a compute node only when it is in the <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> or <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> state.</span></span></para>
          <para><span data-ttu-id="5b860-477">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-477">This is a blocking operation.</span></span> <span data-ttu-id="5b860-478">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.RebootAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-478">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.RebootAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RebootAsync (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RebootAsync(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RebootAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RebootAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RebootAsync (poolId, computeNodeId, rebootOption, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="rebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-479">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-479">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-480">再起動してコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-480">The id of the compute node to reboot.</span></span></param>
        <param name="rebootOption"><span data-ttu-id="5b860-481">ノードを再起動して、実行中のタスクの処理方法を指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-481">Specifies when to reboot the node and what to do with currently running tasks.</span></span> <span data-ttu-id="5b860-482">既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.Requeue" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-482">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeRebootOption.Requeue" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-483">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-483">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-484">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-484">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-485">指定された計算ノードを再起動します。</span><span class="sxs-lookup"><span data-stu-id="5b860-485">Reboots the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-486">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-486">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-487">コンピューティング ノードを再起動するにあるときにのみ、<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" />または<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" />状態です。</span><span class="sxs-lookup"><span data-stu-id="5b860-487">You can reboot a compute node only when it is in the <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> or <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> state.</span></span></para>
          <para><span data-ttu-id="5b860-488">再起動操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-488">The reboot operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Reimage">
      <MemberSignature Language="C#" Value="public void Reimage (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Reimage(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.Reimage(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reimage (poolId As String, computeNodeId As String, Optional reimageOption As Nullable(Of ComputeNodeReimageOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Reimage : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.Reimage (poolId, computeNodeId, reimageOption, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="reimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-489">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-489">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-490">再イメージ化にコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-490">The id of the compute node to reimage.</span></span></param>
        <param name="reimageOption"><span data-ttu-id="5b860-491">ノードを再イメージ化する場合と、実行中のタスクの処理方法を指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-491">Specifies when to reimage the node and what to do with currently running tasks.</span></span> <span data-ttu-id="5b860-492">既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Requeue" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-492">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Requeue" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-493">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-493">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-494">指定したコンピューティング ノードで、オペレーティング システムを再インストールします。</span><span class="sxs-lookup"><span data-stu-id="5b860-494">Reinstalls the operating system on the specified compute node.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="5b860-495">内にある場合にのみ、コンピューティング ノードを再イメージ化できる、<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" />または<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" />状態です。</span><span class="sxs-lookup"><span data-stu-id="5b860-495">You can reimage a compute node only when it is in the <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> or <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> state.</span></span></para>
          <para><span data-ttu-id="5b860-496">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-496">This is a blocking operation.</span></span> <span data-ttu-id="5b860-497">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.ReimageAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-497">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.ReimageAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReimageAsync (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ReimageAsync(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ReimageAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ReimageAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.ReimageAsync (poolId, computeNodeId, reimageOption, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="reimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-498">コンピューティング ノードを含むプールの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-498">The id of the pool that contains the compute node.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-499">再イメージ化にコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-499">The id of the compute node to reimage.</span></span></param>
        <param name="reimageOption"><span data-ttu-id="5b860-500">ノードを再イメージ化する場合と、実行中のタスクの処理方法を指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-500">Specifies when to reimage the node and what to do with currently running tasks.</span></span> <span data-ttu-id="5b860-501">既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Requeue" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-501">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Requeue" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-502">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-502">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-503">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-503">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-504">指定したコンピューティング ノードで、オペレーティング システムを再インストールします。</span><span class="sxs-lookup"><span data-stu-id="5b860-504">Reinstalls the operating system on the specified compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-505">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-505">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-506">内にある場合にのみ、コンピューティング ノードを再イメージ化できる、<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" />または<see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" />状態です。</span><span class="sxs-lookup"><span data-stu-id="5b860-506">You can reimage a compute node only when it is in the <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" /> or <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" /> state.</span></span></para>
          <para><span data-ttu-id="5b860-507">再イメージ化操作が非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-507">The reimage operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string poolId, Microsoft.Azure.Batch.ComputeNode computeNode, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string poolId, class Microsoft.Azure.Batch.ComputeNode computeNode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * Microsoft.Azure.Batch.ComputeNode * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.RemoveFromPool (poolId, computeNode, deallocationOption, resizeTimeout, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNode" Type="Microsoft.Azure.Batch.ComputeNode" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-508">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-508">The id of the pool.</span></span></param>
        <param name="computeNode"><span data-ttu-id="5b860-509"><see cref="T:Microsoft.Azure.Batch.ComputeNode" />をプールから削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-509">The <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="5b860-510">処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-510">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="5b860-511">既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-511">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="5b860-512">プールから計算ノードの削除のためのタイムアウトを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-512">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="5b860-513">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-513">The default value is 15 minutes.</span></span> <span data-ttu-id="5b860-514">最小値は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-514">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-515">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-515">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-516">指定したプールから指定された計算ノードを削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-516">Removes the specified compute node from the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="5b860-517">使用する方が効率的では、プールから複数のコンピューティング ノードを削除する必要がある場合、<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />オーバー ロードします。</span><span class="sxs-lookup"><span data-stu-id="5b860-517">If you need to remove multiple compute nodes from a pool, it is more efficient to use the <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> overload.</span></span></para>
          <para><span data-ttu-id="5b860-518">プールから削除できるのノードのみときに、<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は、プールの<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。</span><span class="sxs-lookup"><span data-stu-id="5b860-518">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="5b860-519">プールは既にサイズ変更、例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="5b860-519">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="5b860-520">プールからノードを削除すると、プールの AllocationState から変更を安定した<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-520">When you remove nodes from a pool, the pool's AllocationState changes from Steady to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="5b860-521">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-521">This is a blocking operation.</span></span> <span data-ttu-id="5b860-522">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-522">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (poolId As String, computeNodes As IEnumerable(Of ComputeNode), Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * seq&lt;Microsoft.Azure.Batch.ComputeNode&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.RemoveFromPool (poolId, computeNodes, deallocationOption, resizeTimeout, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodes" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-523">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-523">The id of the pool.</span></span></param>
        <param name="computeNodes"><span data-ttu-id="5b860-524"><see cref="T:Microsoft.Azure.Batch.ComputeNode">コンピューティング ノード</see>をプールから削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-524">The <see cref="T:Microsoft.Azure.Batch.ComputeNode">compute nodes</see> to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="5b860-525">処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-525">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="5b860-526">既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-526">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="5b860-527">プールから計算ノードの削除のためのタイムアウトを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-527">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="5b860-528">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-528">The default value is 15 minutes.</span></span> <span data-ttu-id="5b860-529">最小値は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-529">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-530">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-530">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-531">指定したプールから指定された計算ノードを削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-531">Removes the specified compute nodes from the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="5b860-532">プールから削除できるのノードのみときに、<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は、プールの<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。</span><span class="sxs-lookup"><span data-stu-id="5b860-532">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="5b860-533">プールは既にサイズ変更、例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="5b860-533">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="5b860-534">プールからノードを削除すると、プールの AllocationState から変更を安定した<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-534">When you remove nodes from a pool, the pool's AllocationState changes from Steady to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="5b860-535">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-535">This is a blocking operation.</span></span> <span data-ttu-id="5b860-536">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-536">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string poolId, System.Collections.Generic.IEnumerable&lt;string&gt; computeNodeIds, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string poolId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; computeNodeIds, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (poolId As String, computeNodeIds As IEnumerable(Of String), Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * seq&lt;string&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.RemoveFromPool (poolId, computeNodeIds, deallocationOption, resizeTimeout, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeIds" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-537">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-537">The id of the pool.</span></span></param>
        <param name="computeNodeIds"><span data-ttu-id="5b860-538">プールから削除するコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-538">The ids of the compute nodes to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="5b860-539">処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-539">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="5b860-540">既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-540">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="5b860-541">プールから計算ノードの削除のためのタイムアウトを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-541">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="5b860-542">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-542">The default value is 15 minutes.</span></span> <span data-ttu-id="5b860-543">最小値は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-543">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-544">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-544">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-545">指定したプールから指定された計算ノードを削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-545">Removes the specified compute nodes from the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="5b860-546">プールから削除できるのノードのみときに、<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は、プールの<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。</span><span class="sxs-lookup"><span data-stu-id="5b860-546">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="5b860-547">プールは既にサイズ変更、例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="5b860-547">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="5b860-548">プールからノードを削除すると、プールの AllocationState から変更を安定した<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-548">When you remove nodes from a pool, the pool's AllocationState changes from Steady to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="5b860-549">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-549">This is a blocking operation.</span></span> <span data-ttu-id="5b860-550">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-550">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (poolId As String, computeNodeId As String, Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.RemoveFromPool (poolId, computeNodeId, deallocationOption, resizeTimeout, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-551">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-551">The id of the pool.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-552">プールから削除するコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-552">The id of the compute node to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="5b860-553">処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-553">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="5b860-554">既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-554">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="5b860-555">プールから計算ノードの削除のためのタイムアウトを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-555">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="5b860-556">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-556">The default value is 15 minutes.</span></span> <span data-ttu-id="5b860-557">最小値は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-557">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-558">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-558">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-559">指定したプールから指定された計算ノードを削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-559">Removes the specified compute node from the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="5b860-560">使用する方が効率的では、プールから複数のコンピューティング ノードを削除する必要がある場合、<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />オーバー ロードします。</span><span class="sxs-lookup"><span data-stu-id="5b860-560">If you need to remove multiple compute nodes from a pool, it is more efficient to use the <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> overload.</span></span></para>
          <para><span data-ttu-id="5b860-561">プールから削除できるのノードのみときに、<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は、プールの<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。</span><span class="sxs-lookup"><span data-stu-id="5b860-561">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="5b860-562">プールは既にサイズ変更、例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="5b860-562">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="5b860-563">プールからノードを削除すると、プールの AllocationState から変更を安定した<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-563">When you remove nodes from a pool, the pool's AllocationState changes from Steady to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="5b860-564">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-564">This is a blocking operation.</span></span> <span data-ttu-id="5b860-565">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-565">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string poolId, Microsoft.Azure.Batch.ComputeNode computeNode, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string poolId, class Microsoft.Azure.Batch.ComputeNode computeNode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,Microsoft.Azure.Batch.ComputeNode,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * Microsoft.Azure.Batch.ComputeNode * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RemoveFromPoolAsync (poolId, computeNode, deallocationOption, resizeTimeout, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNode" Type="Microsoft.Azure.Batch.ComputeNode" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-566">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-566">The id of the pool.</span></span></param>
        <param name="computeNode"><span data-ttu-id="5b860-567"><see cref="T:Microsoft.Azure.Batch.ComputeNode" />をプールから削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-567">The <see cref="T:Microsoft.Azure.Batch.ComputeNode" /> to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="5b860-568">処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-568">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="5b860-569">既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-569">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="5b860-570">プールから計算ノードの削除のためのタイムアウトを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-570">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="5b860-571">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-571">The default value is 15 minutes.</span></span> <span data-ttu-id="5b860-572">最小値は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-572">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-573">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-573">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-574">指定したプールから指定された計算ノードを削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-574">Removes the specified compute node from the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-575">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-575">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-576">使用する方が効率的では、プールから複数のコンピューティング ノードを削除する必要がある場合、<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />オーバー ロードします。</span><span class="sxs-lookup"><span data-stu-id="5b860-576">If you need to remove multiple compute nodes from a pool, it is more efficient to use the <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> overload.</span></span></para>
          <para><span data-ttu-id="5b860-577">プールから削除できるのノードのみときに、<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は、プールの<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。</span><span class="sxs-lookup"><span data-stu-id="5b860-577">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="5b860-578">プールは既にサイズ変更、例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="5b860-578">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="5b860-579">プールからノードを削除すると、プールの AllocationState から変更を安定した<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-579">When you remove nodes from a pool, the pool's AllocationState changes from Steady to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="5b860-580">削除操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-580">The remove operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string poolId, string computeNodeId, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string poolId, string computeNodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveFromPoolAsync (poolId As String, computeNodeId As String, Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As Task" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * string * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RemoveFromPoolAsync (poolId, computeNodeId, deallocationOption, resizeTimeout, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeId" Type="System.String" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-581">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-581">The id of the pool.</span></span></param>
        <param name="computeNodeId"><span data-ttu-id="5b860-582">プールから削除するコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-582">The id of the compute node to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="5b860-583">処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-583">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="5b860-584">既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-584">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="5b860-585">プールから計算ノードの削除のためのタイムアウトを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-585">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="5b860-586">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-586">The default value is 15 minutes.</span></span> <span data-ttu-id="5b860-587">最小値は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-587">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-588">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-588">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-589">指定したプールから指定された計算ノードを削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-589">Removes the specified compute node from the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-590">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-590">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-591">使用する方が効率的では、プールから複数のコンピューティング ノードを削除する必要がある場合、<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />オーバー ロードします。</span><span class="sxs-lookup"><span data-stu-id="5b860-591">If you need to remove multiple compute nodes from a pool, it is more efficient to use the <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> overload.</span></span></para>
          <para><span data-ttu-id="5b860-592">プールから削除できるのノードのみときに、<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は、プールの<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。</span><span class="sxs-lookup"><span data-stu-id="5b860-592">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="5b860-593">プールは既にサイズ変更、例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="5b860-593">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="5b860-594">プールからノードを削除すると、プールの AllocationState から変更を安定した<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-594">When you remove nodes from a pool, the pool's AllocationState changes from Steady to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="5b860-595">削除操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-595">The remove operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.ComputeNode&gt; computeNodes, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.ComputeNode},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * seq&lt;Microsoft.Azure.Batch.ComputeNode&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RemoveFromPoolAsync (poolId, computeNodes, deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PoolOperations/&lt;RemoveFromPoolAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodes" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.ComputeNode&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-596">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-596">The id of the pool.</span></span></param>
        <param name="computeNodes"><span data-ttu-id="5b860-597"><see cref="T:Microsoft.Azure.Batch.ComputeNode">コンピューティング ノード</see>をプールから削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-597">The <see cref="T:Microsoft.Azure.Batch.ComputeNode">compute nodes</see> to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="5b860-598">処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-598">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="5b860-599">既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-599">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="5b860-600">プールから計算ノードの削除のためのタイムアウトを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-600">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="5b860-601">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-601">The default value is 15 minutes.</span></span> <span data-ttu-id="5b860-602">最小値は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-602">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-603">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-603">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-604">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-604">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-605">指定したプールから指定された計算ノードを削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-605">Removes the specified compute nodes from the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-606">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-606">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-607">プールから削除できるのノードのみときに、<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は、プールの<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。</span><span class="sxs-lookup"><span data-stu-id="5b860-607">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="5b860-608">プールは既にサイズ変更、例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="5b860-608">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="5b860-609">プールからノードを削除すると、プールの AllocationState から変更を安定した<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-609">When you remove nodes from a pool, the pool's AllocationState changes from Steady to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="5b860-610">削除操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-610">The remove operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (string poolId, System.Collections.Generic.IEnumerable&lt;string&gt; computeNodeIds, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;string&gt; computeNodeIds, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : string * seq&lt;string&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.RemoveFromPoolAsync (poolId, computeNodeIds, deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeIds" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-611">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-611">The id of the pool.</span></span></param>
        <param name="computeNodeIds"><span data-ttu-id="5b860-612">プールから削除するコンピューティング ノードの id。</span><span class="sxs-lookup"><span data-stu-id="5b860-612">The ids of the compute nodes to remove from the pool.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="5b860-613">処理する方法が既に実行中のタスクし、プールからそれらを実行してノードをいつ削除する場合がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-613">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="5b860-614">既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-614">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="5b860-615">プールから計算ノードの削除のためのタイムアウトを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-615">Specifies the timeout for removal of compute nodes from the pool.</span></span> <span data-ttu-id="5b860-616">既定値は、15 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-616">The default value is 15 minutes.</span></span> <span data-ttu-id="5b860-617">最小値は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-617">The minimum value is 5 minutes.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-618">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-618">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-619">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-619">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-620">指定したプールから指定された計算ノードを削除します。</span><span class="sxs-lookup"><span data-stu-id="5b860-620">Removes the specified compute nodes from the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-621">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-621">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-622">プールから削除できるのノードのみときに、<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は、プールの<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。</span><span class="sxs-lookup"><span data-stu-id="5b860-622">You can only remove nodes from a pool when the <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> of the pool is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span> <span data-ttu-id="5b860-623">プールは既にサイズ変更、例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="5b860-623">If the pool is already resizing, an exception occurs.</span></span></para>
          <para><span data-ttu-id="5b860-624">プールからノードを削除すると、プールの AllocationState から変更を安定した<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-624">When you remove nodes from a pool, the pool's AllocationState changes from Steady to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />.</span></span></para>
          <para><span data-ttu-id="5b860-625">削除操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-625">The remove operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizePool">
      <MemberSignature Language="C#" Value="public void ResizePool (string poolId, Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResizePool(string poolId, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ResizePool(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResizePool (poolId As String, Optional targetDedicatedComputeNodes As Nullable(Of Integer) = null, Optional targetLowPriorityComputeNodes As Nullable(Of Integer) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.ResizePool : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.ResizePool (poolId, targetDedicatedComputeNodes, targetLowPriorityComputeNodes, resizeTimeout, deallocationOption, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-626">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-626">The id of the pool.</span></span></param>
        <param name="targetDedicatedComputeNodes">
            <span data-ttu-id="5b860-627">専用の目的の数は、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="5b860-627">The desired number of dedicated compute nodes in the pool.</span></span>
            <span data-ttu-id="5b860-628">少なくとも 1 つの<paramref name="targetDedicatedComputeNodes" />と<paramref name="targetLowPriorityComputeNodes" />が必要です。</span><span class="sxs-lookup"><span data-stu-id="5b860-628">At least one of <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> is required.</span></span>
            </param>
        <param name="targetLowPriorityComputeNodes">
            <span data-ttu-id="5b860-629">目的の優先度の低い数は、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="5b860-629">The desired number of low-priority compute nodes in the pool.</span></span>
            <span data-ttu-id="5b860-630">少なくとも 1 つの<paramref name="targetDedicatedComputeNodes" />と<paramref name="targetLowPriorityComputeNodes" />が必要です。</span><span class="sxs-lookup"><span data-stu-id="5b860-630">At least one of <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> is required.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="5b860-631">プールにコンピューティング ノードの割り当てまたはプールから、コンピューティング ノードの削除のタイムアウトです。</span><span class="sxs-lookup"><span data-stu-id="5b860-631">The timeout for allocation of compute nodes to the pool or removal of compute nodes from the pool.</span></span> <span data-ttu-id="5b860-632">プールに達していない目標サイズこの時間以降後、サイズ変更は停止されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-632">If the pool has not reached the target size after this time, the resize is stopped.</span></span> <span data-ttu-id="5b860-633">既定では 15 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-633">The default is 15 minutes.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="5b860-634">プールのサイズが減少している場合は、処理する方法、既に実行中のタスクし、プールからそれらを実行してノードをいつ削除することがありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-634">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool, if the pool size is decreasing.</span></span> <span data-ttu-id="5b860-635">既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-635">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-636">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-636">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-637">指定したプールのサイズを変更します。</span><span class="sxs-lookup"><span data-stu-id="5b860-637">Resizes the specified pool.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="5b860-638">サイズ変更操作は、プールのサイズが変更できることを要求します。</span><span class="sxs-lookup"><span data-stu-id="5b860-638">The resize operation requests that the pool be resized.</span></span>  <span data-ttu-id="5b860-639">要求は、プールに格納、<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />割り当ての状態。</span><span class="sxs-lookup"><span data-stu-id="5b860-639">The request puts the pool in the <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" /> allocation state.</span></span>
            <span data-ttu-id="5b860-640">バッチ サービスは、さらにクライアント操作をしなくても、実際のサイズ変更を実行し、割り当て状態を設定<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />1 回を完了します。</span><span class="sxs-lookup"><span data-stu-id="5b860-640">The Batch service will perform the actual resize without any further client action, and set the allocation state to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> once complete.</span></span></para>
          <para>
            <span data-ttu-id="5b860-641">プールのサイズを変更することができますのみときにその<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。</span><span class="sxs-lookup"><span data-stu-id="5b860-641">You can only resize a pool when its <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span>
            <span data-ttu-id="5b860-642">自動スケーリング用に構成されているプールのサイズを変更することはできません (つまり、<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" />プールのプロパティが true)。</span><span class="sxs-lookup"><span data-stu-id="5b860-642">You cannot resize pools which are configured for automatic scaling (that is, the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> property of the pool is true).</span></span>
            <span data-ttu-id="5b860-643">プール サイズを小さくした場合、Batch service を削除するノードを選択します。</span><span class="sxs-lookup"><span data-stu-id="5b860-643">If you decrease the pool size, the Batch service chooses which nodes to remove.</span></span>  <span data-ttu-id="5b860-644">特定のノードを削除するには、呼び出す<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-644">To remove specific nodes, call <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPool(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span>
            </para>
          <para><span data-ttu-id="5b860-645">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-645">This is a blocking operation.</span></span> <span data-ttu-id="5b860-646">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.ResizePoolAsync(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-646">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.ResizePoolAsync(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizePoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResizePoolAsync (string poolId, Nullable&lt;int&gt; targetDedicatedComputeNodes = null, Nullable&lt;int&gt; targetLowPriorityComputeNodes = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ResizePoolAsync(string poolId, valuetype System.Nullable`1&lt;int32&gt; targetDedicatedComputeNodes, valuetype System.Nullable`1&lt;int32&gt; targetLowPriorityComputeNodes, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.ResizePoolAsync(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.TimeSpan},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResizePoolAsync : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.ResizePoolAsync (poolId, targetDedicatedComputeNodes, targetLowPriorityComputeNodes, resizeTimeout, deallocationOption, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetDedicatedComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetLowPriorityComputeNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-647">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-647">The id of the pool.</span></span></param>
        <param name="targetDedicatedComputeNodes">
            <span data-ttu-id="5b860-648">専用の目的の数は、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="5b860-648">The desired number of dedicated compute nodes in the pool.</span></span>
            <span data-ttu-id="5b860-649">少なくとも 1 つの<paramref name="targetDedicatedComputeNodes" />と<paramref name="targetLowPriorityComputeNodes" />が必要です。</span><span class="sxs-lookup"><span data-stu-id="5b860-649">At least one of <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> is required.</span></span>
            </param>
        <param name="targetLowPriorityComputeNodes">
            <span data-ttu-id="5b860-650">目的の優先度の低い数は、プール内のノードを計算します。</span><span class="sxs-lookup"><span data-stu-id="5b860-650">The desired number of low-priority compute nodes in the pool.</span></span>
            <span data-ttu-id="5b860-651">少なくとも 1 つの<paramref name="targetDedicatedComputeNodes" />と<paramref name="targetLowPriorityComputeNodes" />が必要です。</span><span class="sxs-lookup"><span data-stu-id="5b860-651">At least one of <paramref name="targetDedicatedComputeNodes" /> and <paramref name="targetLowPriorityComputeNodes" /> is required.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="5b860-652">プールにコンピューティング ノードの割り当てまたはプールから、コンピューティング ノードの削除のタイムアウトです。</span><span class="sxs-lookup"><span data-stu-id="5b860-652">The timeout for allocation of compute nodes to the pool or removal of compute nodes from the pool.</span></span> <span data-ttu-id="5b860-653">プールに達していない目標サイズこの時間以降後、サイズ変更は停止されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-653">If the pool has not reached the target size after this time, the resize is stopped.</span></span> <span data-ttu-id="5b860-654">既定では 15 分です。</span><span class="sxs-lookup"><span data-stu-id="5b860-654">The default is 15 minutes.</span></span></param>
        <param name="deallocationOption">
            <span data-ttu-id="5b860-655">プールのサイズが減少している場合は、処理する方法、既に実行中のタスクし、プールからそれらを実行してノードをいつ削除することがありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-655">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool, if the pool size is decreasing.</span></span> <span data-ttu-id="5b860-656">既定では、 <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-656">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-657">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-657">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-658">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-658">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-659">指定したプールのサイズを変更します。</span><span class="sxs-lookup"><span data-stu-id="5b860-659">Resizes the specified pool.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-660">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-660">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="5b860-661">サイズ変更操作は、プールのサイズが変更できることを要求します。</span><span class="sxs-lookup"><span data-stu-id="5b860-661">The resize operation requests that the pool be resized.</span></span>  <span data-ttu-id="5b860-662">要求は、プールに格納、<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" />割り当ての状態。</span><span class="sxs-lookup"><span data-stu-id="5b860-662">The request puts the pool in the <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Resizing" /> allocation state.</span></span>
            <span data-ttu-id="5b860-663">バッチ サービスは、さらにクライアント操作をしなくても、実際のサイズ変更を実行し、割り当て状態を設定<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />1 回を完了します。</span><span class="sxs-lookup"><span data-stu-id="5b860-663">The Batch service will perform the actual resize without any further client action, and set the allocation state to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" /> once complete.</span></span></para>
          <para>
            <span data-ttu-id="5b860-664">プールのサイズを変更することができますのみときにその<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />は<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />します。</span><span class="sxs-lookup"><span data-stu-id="5b860-664">You can only resize a pool when its <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> is <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span>
            <span data-ttu-id="5b860-665">自動スケーリング用に構成されているプールのサイズを変更することはできません (つまり、<see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" />プールのプロパティが true)。</span><span class="sxs-lookup"><span data-stu-id="5b860-665">You cannot resize pools which are configured for automatic scaling (that is, the <see cref="P:Microsoft.Azure.Batch.CloudPool.AutoScaleEnabled" /> property of the pool is true).</span></span>
            <span data-ttu-id="5b860-666">プール サイズを小さくした場合、Batch service を削除するノードを選択します。</span><span class="sxs-lookup"><span data-stu-id="5b860-666">If you decrease the pool size, the Batch service chooses which nodes to remove.</span></span>  <span data-ttu-id="5b860-667">特定のノードを削除するには、呼び出す<see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-667">To remove specific nodes, call <see cref="M:Microsoft.Azure.Batch.PoolOperations.RemoveFromPoolAsync(System.String,System.Collections.Generic.IEnumerable{System.String},System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span>
            </para>
          <para><span data-ttu-id="5b860-668">サイズ変更操作は非同期的に実行されます。</span><span class="sxs-lookup"><span data-stu-id="5b860-668">The resize operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResizePool">
      <MemberSignature Language="C#" Value="public void StopResizePool (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void StopResizePool(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.StopResizePool(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub StopResizePool (poolId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.StopResizePool : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="poolOperations.StopResizePool (poolId, additionalBehaviors)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-669">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-669">The id of the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-670">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-670">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-671">サイズ変更操作をプールを停止します。</span><span class="sxs-lookup"><span data-stu-id="5b860-671">Stops a pool resize operation.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-672">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-672">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="5b860-673">この操作は、プールで進行中のサイズ変更操作を停止します。</span><span class="sxs-lookup"><span data-stu-id="5b860-673">This operation stops an ongoing resize operation on the pool.</span></span>  <span data-ttu-id="5b860-674">プールのサイズは、停止操作が行われるときにノードの数に安定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-674">The pool size will stabilize at the number of nodes it is at when the stop operation is done.</span></span>  <span data-ttu-id="5b860-675">停止操作で、プール<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />最初に変更<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" />し<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-675">During the stop operation, the pool <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> changes first to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" /> and then to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span>
            </para>
          <para><span data-ttu-id="5b860-676">これは、ブロッキング操作です。</span><span class="sxs-lookup"><span data-stu-id="5b860-676">This is a blocking operation.</span></span> <span data-ttu-id="5b860-677">非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.PoolOperations.StopResizePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-677">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.PoolOperations.StopResizePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResizePoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopResizePoolAsync (string poolId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StopResizePoolAsync(string poolId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolOperations.StopResizePoolAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopResizePoolAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="poolOperations.StopResizePoolAsync (poolId, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="5b860-678">プールの ID。</span><span class="sxs-lookup"><span data-stu-id="5b860-678">The id of the pool.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="5b860-679">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-679">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.PoolOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5b860-680">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="5b860-680">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="5b860-681">サイズ変更操作をプールを停止します。</span><span class="sxs-lookup"><span data-stu-id="5b860-681">Stops a pool resize operation.</span></span>
            </summary>
        <returns><span data-ttu-id="5b860-682">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</span><span class="sxs-lookup"><span data-stu-id="5b860-682">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="5b860-683">この操作は、プールで進行中のサイズ変更操作を停止します。</span><span class="sxs-lookup"><span data-stu-id="5b860-683">This operation stops an ongoing resize operation on the pool.</span></span>  <span data-ttu-id="5b860-684">プールのサイズは、停止操作が行われるときにノードの数に安定します。</span><span class="sxs-lookup"><span data-stu-id="5b860-684">The pool size will stabilize at the number of nodes it is at when the stop operation is done.</span></span>  <span data-ttu-id="5b860-685">停止操作で、プール<see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" />最初に変更<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" />し<see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />です。</span><span class="sxs-lookup"><span data-stu-id="5b860-685">During the stop operation, the pool <see cref="P:Microsoft.Azure.Batch.CloudPool.AllocationState" /> changes first to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Stopping" /> and then to <see cref="F:Microsoft.Azure.Batch.Common.AllocationState.Steady" />.</span></span>
            </para>
          <para><span data-ttu-id="5b860-686">停止では、操作の実行が非同期的にサイズ変更します。</span><span class="sxs-lookup"><span data-stu-id="5b860-686">The stop resize operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>