<Type Name="DeployedStatefulServiceReplicaDetail" FullName="System.Fabric.Query.DeployedStatefulServiceReplicaDetail">
  <TypeSignature Language="C#" Value="public sealed class DeployedStatefulServiceReplicaDetail : System.Fabric.Query.DeployedServiceReplicaDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedStatefulServiceReplicaDetail extends System.Fabric.Query.DeployedServiceReplicaDetail" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedStatefulServiceReplicaDetail" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedStatefulServiceReplicaDetail&#xA;Inherits DeployedServiceReplicaDetail" />
  <TypeSignature Language="F#" Value="type DeployedStatefulServiceReplicaDetail = class&#xA;    inherit DeployedServiceReplicaDetail" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.DeployedServiceReplicaDetail</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="95bb4-101">コード パッケージで実行して、ステートフルなレプリカに関する情報を表します。</span><span class="sxs-lookup"><span data-stu-id="95bb4-101">Represents the information about a stateful replica running in a code package.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedStatefulServiceReplicaDetail ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="95bb4-102"><see cref="T:System.Fabric.Query.DeployedStatefulServiceReplicaDetail" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="95bb4-102">Initializes a new instance of the <see cref="T:System.Fabric.Query.DeployedStatefulServiceReplicaDetail" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentReplicatorOperation">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicatorOperationName CurrentReplicatorOperation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ReplicatorOperationName CurrentReplicatorOperation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.CurrentReplicatorOperation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentReplicatorOperation As ReplicatorOperationName" />
      <MemberSignature Language="F#" Value="member this.CurrentReplicatorOperation : System.Fabric.Query.ReplicatorOperationName" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.CurrentReplicatorOperation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="95bb4-103">レプリケーターで実行されている現在の Api を取得します。</span><span class="sxs-lookup"><span data-stu-id="95bb4-103">Gets the current APIs running on the replicator.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="95bb4-104">レプリケーターで実行されている現在の Api。</span><span class="sxs-lookup"><span data-stu-id="95bb4-104">The current APIs running on the replicator.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedServiceReplica">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.DeployedStatefulServiceReplica DeployedServiceReplica { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.DeployedStatefulServiceReplica DeployedServiceReplica" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.DeployedServiceReplica" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedServiceReplica As DeployedStatefulServiceReplica" />
      <MemberSignature Language="F#" Value="member this.DeployedServiceReplica : System.Fabric.Query.DeployedStatefulServiceReplica" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.DeployedServiceReplica" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.DeployedStatefulServiceReplica</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="95bb4-105">レプリカのロール、ホスト プロセス Id、再構成に関する情報と同様に、展開済みサービス レプリカの追加の詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="95bb4-105">Gets additonal details about the deployed service replica like replica role, host processId, information about reconfiguration.</span></span></para>
          <value><span data-ttu-id="95bb4-106">レプリカの詳細です。</span><span class="sxs-lookup"><span data-stu-id="95bb4-106">Replica Detail.</span></span></value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionAccessStatus ReadStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PartitionAccessStatus ReadStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReadStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadStatus As PartitionAccessStatus" />
      <MemberSignature Language="F#" Value="member this.ReadStatus : System.Fabric.PartitionAccessStatus" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReadStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="95bb4-107">現在のこのレプリカの状態の読み取りを取得します。</span><span class="sxs-lookup"><span data-stu-id="95bb4-107">Gets the current read status for this replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="95bb4-108">現在では、このレプリカの状態を読み取る。</span><span class="sxs-lookup"><span data-stu-id="95bb4-108">The current read status for this replica.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaId">
      <MemberSignature Language="C#" Value="public long ReplicaId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicaId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaId : int64" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicaId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="95bb4-109">このレプリカのレプリカの ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="95bb4-109">Gets the replica ID of this replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="95bb4-110">レプリカ ID</span><span class="sxs-lookup"><span data-stu-id="95bb4-110">The replica ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicaStatus ReplicaStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ReplicaStatus ReplicaStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicaStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaStatus As ReplicaStatus" />
      <MemberSignature Language="F#" Value="member this.ReplicaStatus : System.Fabric.Query.ReplicaStatus" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicaStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicaStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95bb4-111">現在のレプリカの状態を示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="95bb4-111">Gets a value indicating the status of the current replica.</span></span>
            </summary>
        <value><span data-ttu-id="95bb4-112">レプリカの状態。</span><span class="sxs-lookup"><span data-stu-id="95bb4-112">The replica status.</span></span></value>
        <remarks><span data-ttu-id="95bb4-113">現時点では、のみのレプリカ型<see cref="T:System.Fabric.KeyValueStoreReplica" />クエリ ステータスの詳細が生成されます。</span><span class="sxs-lookup"><span data-stu-id="95bb4-113">Currently, only replicas of type <see cref="T:System.Fabric.KeyValueStoreReplica" /> will produce query status details.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicatorStatus ReplicatorStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ReplicatorStatus ReplicatorStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicatorStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicatorStatus As ReplicatorStatus" />
      <MemberSignature Language="F#" Value="member this.ReplicatorStatus : System.Fabric.Query.ReplicatorStatus" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicatorStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="95bb4-114">Service Fabric レプリケーター、レプリカが使用されている場合は、レプリケーターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="95bb4-114">Gets the information about the replicator if the replica is using the Service Fabric Replicator</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="95bb4-115">レプリケーター状態です。</span><span class="sxs-lookup"><span data-stu-id="95bb4-115">The replicator status.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionAccessStatus WriteStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PartitionAccessStatus WriteStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.WriteStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteStatus As PartitionAccessStatus" />
      <MemberSignature Language="F#" Value="member this.WriteStatus : System.Fabric.PartitionAccessStatus" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.WriteStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="95bb4-116">レプリカの現在の書き込みの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="95bb4-116">Gets the current write status of the replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="95bb4-117">現在では、レプリカの状態を記述します。</span><span class="sxs-lookup"><span data-stu-id="95bb4-117">The current write status of the replica.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>