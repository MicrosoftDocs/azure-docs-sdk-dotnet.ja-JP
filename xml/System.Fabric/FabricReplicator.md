<Type Name="FabricReplicator" FullName="System.Fabric.FabricReplicator">
  <TypeSignature Language="C#" Value="public sealed class FabricReplicator : System.Fabric.IReplicator, System.Fabric.IReplicatorCatchupSpecificQuorum" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FabricReplicator extends System.Object implements class System.Fabric.IPrimaryReplicator, class System.Fabric.IReplicator, class System.Fabric.IReplicatorCatchupSpecificQuorum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricReplicator" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricReplicator&#xA;Implements IReplicator, IReplicatorCatchupSpecificQuorum" />
  <TypeSignature Language="F#" Value="type FabricReplicator = class&#xA;    interface IReplicator&#xA;    interface IPrimaryReplicator&#xA;    interface IReplicatorCatchupSpecificQuorum" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IReplicator</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Fabric.IReplicatorCatchupSpecificQuorum</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="23d70-101">高可用性と信頼性のレプリケート状態です。</span><span class="sxs-lookup"><span data-stu-id="23d70-101">Replicates state for high availability and reliability.</span></span> </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="23d70-102">既定の実装を提供、 <see cref="T:System.Fabric.IStateReplicator" />、 <see cref="T:System.Fabric.IReplicator" />、および<see cref="T:System.Fabric.IPrimaryReplicator" />インターフェイスの実装と共に、ユーザーのサービスが使用できる、<see cref="T:System.Fabric.IStateProvider" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="23d70-102">Provides the default implementation of the <see cref="T:System.Fabric.IStateReplicator" />, <see cref="T:System.Fabric.IReplicator" />, and <see cref="T:System.Fabric.IPrimaryReplicator" /> interfaces, which user services can use, along with their implementation of the <see cref="T:System.Fabric.IStateProvider" /> interface.</span></span></para>
      <para><span data-ttu-id="23d70-103">インスタンス、<see cref="T:System.Fabric.FabricReplicator" />クラスが経由で取得した、<see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="23d70-103">An instance of the <see cref="T:System.Fabric.FabricReplicator" /> class is obtained via the <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" /> method.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="InvalidAtomicGroupId">
      <MemberSignature Language="C#" Value="public const long InvalidAtomicGroupId = -1;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int64 InvalidAtomicGroupId = (-1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FabricReplicator.InvalidAtomicGroupId" />
      <MemberSignature Language="VB.NET" Value="Public Const InvalidAtomicGroupId As Long  = -1" />
      <MemberSignature Language="F#" Value="val mutable InvalidAtomicGroupId : int64" Usage="System.Fabric.FabricReplicator.InvalidAtomicGroupId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <MemberValue>-1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="23d70-104">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-104">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateReplicator">
      <MemberSignature Language="C#" Value="public System.Fabric.IStateReplicator StateReplicator { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.IStateReplicator StateReplicator" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricReplicator.StateReplicator" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateReplicator As IStateReplicator" />
      <MemberSignature Language="F#" Value="member this.StateReplicator : System.Fabric.IStateReplicator" Usage="System.Fabric.FabricReplicator.StateReplicator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IStateReplicator</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="23d70-105">取得、<see cref="T:System.Fabric.IStateReplicator" />を使用して状態を複製することができます</span><span class="sxs-lookup"><span data-stu-id="23d70-105">Gets the <see cref="T:System.Fabric.IStateReplicator" /> which can be used to replicate state</span></span></para>
        </summary>
        <value><span data-ttu-id="23d70-106">表す値、<see cref="T:System.Fabric.IStateReplicator" />を使用して状態を複製することができます</span><span class="sxs-lookup"><span data-stu-id="23d70-106">A value representing the <see cref="T:System.Fabric.IStateReplicator" /> which can be used to replicate state</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateReplicator2">
      <MemberSignature Language="C#" Value="public System.Fabric.IStateReplicator2 StateReplicator2 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.IStateReplicator2 StateReplicator2" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricReplicator.StateReplicator2" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateReplicator2 As IStateReplicator2" />
      <MemberSignature Language="F#" Value="member this.StateReplicator2 : System.Fabric.IStateReplicator2" Usage="System.Fabric.FabricReplicator.StateReplicator2" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IStateReplicator2</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="23d70-107">取得、<see cref="T:System.Fabric.IStateReplicator2" />を使用して状態を複製することができます</span><span class="sxs-lookup"><span data-stu-id="23d70-107">Gets the <see cref="T:System.Fabric.IStateReplicator2" /> which can be used to replicate state</span></span></para>
        </summary>
        <value><span data-ttu-id="23d70-108">表す値、<see cref="T:System.Fabric.IStateReplicator2" />を使用して状態を複製することができます</span><span class="sxs-lookup"><span data-stu-id="23d70-108">A value representing the <see cref="T:System.Fabric.IStateReplicator2" /> which can be used to replicate state</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IPrimaryReplicator.BuildReplicaAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IPrimaryReplicator.BuildReplicaAsync (System.Fabric.ReplicaInformation replicaInfo, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task System.Fabric.IPrimaryReplicator.BuildReplicaAsync(class System.Fabric.ReplicaInformation replicaInfo, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IPrimaryReplicator#BuildReplicaAsync(System.Fabric.ReplicaInformation,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IPrimaryReplicator.BuildReplicaAsync(System.Fabric.ReplicaInformation,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaInfo" Type="System.Fabric.ReplicaInformation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaInfo">
          <para><span data-ttu-id="23d70-109">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-109">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="23d70-110"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="23d70-110">The <see cref="T:System.Threading.CancellationToken" />  object that the operation is observing.</span></span> <span data-ttu-id="23d70-111">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="23d70-111">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="23d70-112">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="23d70-112">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary><span data-ttu-id="23d70-113">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-113">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="23d70-114">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="23d70-114">A task that represents the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IPrimaryReplicator.OnDataLossAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;bool&gt; IPrimaryReplicator.OnDataLossAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; System.Fabric.IPrimaryReplicator.OnDataLossAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IPrimaryReplicator#OnDataLossAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IPrimaryReplicator.OnDataLossAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="23d70-115"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="23d70-115">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="23d70-116">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="23d70-116">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="23d70-117">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="23d70-117">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary><span data-ttu-id="23d70-118">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-118">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="23d70-119">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="23d70-119">A task that represents the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IPrimaryReplicator.RemoveReplica">
      <MemberSignature Language="C#" Value="void IPrimaryReplicator.RemoveReplica (long replicaId);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Fabric.IPrimaryReplicator.RemoveReplica(int64 replicaId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IPrimaryReplicator#RemoveReplica(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Sub RemoveReplica (replicaId As Long) Implements IPrimaryReplicator.RemoveReplica" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IPrimaryReplicator.RemoveReplica(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="replicaId">
          <para><span data-ttu-id="23d70-120">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-120">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </param>
        <summary><span data-ttu-id="23d70-121">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-121">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <remarks>
          <para><span data-ttu-id="23d70-122">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-122">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IPrimaryReplicator.UpdateCatchUpReplicaSetConfiguration">
      <MemberSignature Language="C#" Value="void IPrimaryReplicator.UpdateCatchUpReplicaSetConfiguration (System.Fabric.ReplicaSetConfiguration currentConfiguration, System.Fabric.ReplicaSetConfiguration previousConfiguration);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Fabric.IPrimaryReplicator.UpdateCatchUpReplicaSetConfiguration(class System.Fabric.ReplicaSetConfiguration currentConfiguration, class System.Fabric.ReplicaSetConfiguration previousConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IPrimaryReplicator#UpdateCatchUpReplicaSetConfiguration(System.Fabric.ReplicaSetConfiguration,System.Fabric.ReplicaSetConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Sub UpdateCatchUpReplicaSetConfiguration (currentConfiguration As ReplicaSetConfiguration, previousConfiguration As ReplicaSetConfiguration) Implements IPrimaryReplicator.UpdateCatchUpReplicaSetConfiguration" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IPrimaryReplicator.UpdateCatchUpReplicaSetConfiguration(System.Fabric.ReplicaSetConfiguration,System.Fabric.ReplicaSetConfiguration)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentConfiguration" Type="System.Fabric.ReplicaSetConfiguration" />
        <Parameter Name="previousConfiguration" Type="System.Fabric.ReplicaSetConfiguration" />
      </Parameters>
      <Docs>
        <param name="currentConfiguration">
          <para><span data-ttu-id="23d70-123">内部使用のみ。</span><span class="sxs-lookup"><span data-stu-id="23d70-123">For Internal Use Only.</span></span></para>
        </param>
        <param name="previousConfiguration">
          <para><span data-ttu-id="23d70-124">内部使用のみ。</span><span class="sxs-lookup"><span data-stu-id="23d70-124">For Internal Use Only.</span></span></para>
        </param>
        <summary><span data-ttu-id="23d70-125">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-125">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IPrimaryReplicator.UpdateCurrentReplicaSetConfiguration">
      <MemberSignature Language="C#" Value="void IPrimaryReplicator.UpdateCurrentReplicaSetConfiguration (System.Fabric.ReplicaSetConfiguration currentConfiguration);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Fabric.IPrimaryReplicator.UpdateCurrentReplicaSetConfiguration(class System.Fabric.ReplicaSetConfiguration currentConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IPrimaryReplicator#UpdateCurrentReplicaSetConfiguration(System.Fabric.ReplicaSetConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Sub UpdateCurrentReplicaSetConfiguration (currentConfiguration As ReplicaSetConfiguration) Implements IPrimaryReplicator.UpdateCurrentReplicaSetConfiguration" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IPrimaryReplicator.UpdateCurrentReplicaSetConfiguration(System.Fabric.ReplicaSetConfiguration)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentConfiguration" Type="System.Fabric.ReplicaSetConfiguration" />
      </Parameters>
      <Docs>
        <param name="currentConfiguration">
          <para><span data-ttu-id="23d70-126">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-126">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </param>
        <summary><span data-ttu-id="23d70-127">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-127">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <remarks>
          <para><span data-ttu-id="23d70-128">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-128">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IPrimaryReplicator.WaitForCatchUpQuorumAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IPrimaryReplicator.WaitForCatchUpQuorumAsync (System.Fabric.ReplicaSetQuorumMode quorumMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task System.Fabric.IPrimaryReplicator.WaitForCatchUpQuorumAsync(valuetype System.Fabric.ReplicaSetQuorumMode quorumMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IPrimaryReplicator#WaitForCatchUpQuorumAsync(System.Fabric.ReplicaSetQuorumMode,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IPrimaryReplicator.WaitForCatchUpQuorumAsync(System.Fabric.ReplicaSetQuorumMode,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="quorumMode" Type="System.Fabric.ReplicaSetQuorumMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="quorumMode">
          <para><span data-ttu-id="23d70-129">内部使用のみ。</span><span class="sxs-lookup"><span data-stu-id="23d70-129">For Internal Use Only.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="23d70-130">操作を観察し CancellationToken オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="23d70-130">The CancellationToken object that the operation is observing.</span></span> <span data-ttu-id="23d70-131">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="23d70-131">It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="23d70-132">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="23d70-132">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary><span data-ttu-id="23d70-133">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-133">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="23d70-134">内部使用のみ。</span><span class="sxs-lookup"><span data-stu-id="23d70-134">For Internal Use Only.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IReplicator.Abort">
      <MemberSignature Language="C#" Value="void IReplicator.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Fabric.IReplicator.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IReplicator#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements IReplicator.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IReplicator.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="23d70-135">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-135">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <remarks />
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IReplicator.ChangeRoleAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReplicator.ChangeRoleAsync (System.Fabric.Epoch epoch, System.Fabric.ReplicaRole role, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task System.Fabric.IReplicator.ChangeRoleAsync(valuetype System.Fabric.Epoch epoch, valuetype System.Fabric.ReplicaRole role, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IReplicator#ChangeRoleAsync(System.Fabric.Epoch,System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IReplicator.ChangeRoleAsync(System.Fabric.Epoch,System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="role" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para><span data-ttu-id="23d70-136">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-136">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </param>
        <param name="role">
          <para><span data-ttu-id="23d70-137">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-137">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="23d70-138"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="23d70-138">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="23d70-139">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="23d70-139">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="23d70-140">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="23d70-140">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary><span data-ttu-id="23d70-141">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-141">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="23d70-142">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="23d70-142">A task that represents the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IReplicator.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReplicator.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task System.Fabric.IReplicator.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IReplicator#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IReplicator.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="23d70-143"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="23d70-143">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="23d70-144">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="23d70-144">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="23d70-145">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="23d70-145">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary><span data-ttu-id="23d70-146">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-146">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="23d70-147">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="23d70-147">A task that represents the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IReplicator.GetCatchUpCapability">
      <MemberSignature Language="C#" Value="long IReplicator.GetCatchUpCapability ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance int64 System.Fabric.IReplicator.GetCatchUpCapability() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IReplicator#GetCatchUpCapability" />
      <MemberSignature Language="VB.NET" Value="Function GetCatchUpCapability () As Long Implements IReplicator.GetCatchUpCapability" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IReplicator.GetCatchUpCapability</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="23d70-148">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-148">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="23d70-149">内部使用のみ。</span><span class="sxs-lookup"><span data-stu-id="23d70-149">For Internal Use Only.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IReplicator.GetCurrentProgress">
      <MemberSignature Language="C#" Value="long IReplicator.GetCurrentProgress ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance int64 System.Fabric.IReplicator.GetCurrentProgress() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IReplicator#GetCurrentProgress" />
      <MemberSignature Language="VB.NET" Value="Function GetCurrentProgress () As Long Implements IReplicator.GetCurrentProgress" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IReplicator.GetCurrentProgress</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="23d70-150">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-150">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="23d70-151">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-151">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IReplicator.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;string&gt; IReplicator.OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; System.Fabric.IReplicator.OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IReplicator#OpenAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IReplicator.OpenAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="23d70-152"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="23d70-152">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="23d70-153">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="23d70-153">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="23d70-154">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="23d70-154">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary><span data-ttu-id="23d70-155">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-155">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="23d70-156">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="23d70-156">A task that represents the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IReplicator.UpdateEpochAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReplicator.UpdateEpochAsync (System.Fabric.Epoch epoch, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task System.Fabric.IReplicator.UpdateEpochAsync(valuetype System.Fabric.Epoch epoch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricReplicator.System#Fabric#IReplicator#UpdateEpochAsync(System.Fabric.Epoch,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IReplicator.UpdateEpochAsync(System.Fabric.Epoch,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para><span data-ttu-id="23d70-157">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-157">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="23d70-158"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="23d70-158">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="23d70-159">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="23d70-159">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="23d70-160">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="23d70-160">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary><span data-ttu-id="23d70-161">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-161">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <returns>
          <para><span data-ttu-id="23d70-162">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-162">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnknownSequenceNumber">
      <MemberSignature Language="C#" Value="public const long UnknownSequenceNumber = -1;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int64 UnknownSequenceNumber = (-1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FabricReplicator.UnknownSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Const UnknownSequenceNumber As Long  = -1" />
      <MemberSignature Language="F#" Value="val mutable UnknownSequenceNumber : int64" Usage="System.Fabric.FabricReplicator.UnknownSequenceNumber" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <MemberValue>-1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="23d70-163">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="23d70-163">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>