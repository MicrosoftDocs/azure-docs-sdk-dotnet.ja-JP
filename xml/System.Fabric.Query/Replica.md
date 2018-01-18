<Type Name="Replica" FullName="System.Fabric.Query.Replica">
  <TypeSignature Language="C#" Value="public abstract class Replica" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Replica extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.Replica" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Replica" />
  <TypeSignature Language="F#" Value="type Replica = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.StatelessServiceInstance))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.StatefulServiceReplica))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="76c1c-101">クエリのレプリカを表します。</span><span class="sxs-lookup"><span data-stu-id="76c1c-101">Represents a query replica.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Replica (System.Fabric.Query.ServiceKind serviceKind, long id, System.Fabric.Query.ServiceReplicaStatus replicaStatus, System.Fabric.Health.HealthState healthState, string replicaAddress, string nodeName, TimeSpan lastInBuildDuration);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Query.ServiceKind serviceKind, int64 id, valuetype System.Fabric.Query.ServiceReplicaStatus replicaStatus, valuetype System.Fabric.Health.HealthState healthState, string replicaAddress, string nodeName, valuetype System.TimeSpan lastInBuildDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.Replica.#ctor(System.Fabric.Query.ServiceKind,System.Int64,System.Fabric.Query.ServiceReplicaStatus,System.Fabric.Health.HealthState,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Query.Replica : System.Fabric.Query.ServiceKind * int64 * System.Fabric.Query.ServiceReplicaStatus * System.Fabric.Health.HealthState * string * string * TimeSpan -&gt; System.Fabric.Query.Replica" Usage="new System.Fabric.Query.Replica (serviceKind, id, replicaStatus, healthState, replicaAddress, nodeName, lastInBuildDuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceKind" Type="System.Fabric.Query.ServiceKind" />
        <Parameter Name="id" Type="System.Int64" />
        <Parameter Name="replicaStatus" Type="System.Fabric.Query.ServiceReplicaStatus" />
        <Parameter Name="healthState" Type="System.Fabric.Health.HealthState" />
        <Parameter Name="replicaAddress" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="lastInBuildDuration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceKind">
          <para><span data-ttu-id="76c1c-102">レプリカの種類</span><span class="sxs-lookup"><span data-stu-id="76c1c-102">The type of the replica</span></span></para>
        </param>
        <param name="id">
          <para><span data-ttu-id="76c1c-103">レプリカ ID</span><span class="sxs-lookup"><span data-stu-id="76c1c-103">The replica ID</span></span></para>
        </param>
        <param name="replicaStatus">
          <para><span data-ttu-id="76c1c-104">状態のレプリカで初期化されます。</span><span class="sxs-lookup"><span data-stu-id="76c1c-104">The status replica will be initialized with.</span></span></para>
        </param>
        <param name="healthState">
          <para><span data-ttu-id="76c1c-105">ヘルス状態のレプリカで初期化されます。</span><span class="sxs-lookup"><span data-stu-id="76c1c-105">The health state replica will be initialized with</span></span></para>
        </param>
        <param name="replicaAddress">
          <para><span data-ttu-id="76c1c-106">アドレスのレプリカで初期化されます。</span><span class="sxs-lookup"><span data-stu-id="76c1c-106">The address replica will be initialized with.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="76c1c-107">ノード名のレプリカで初期化されます。</span><span class="sxs-lookup"><span data-stu-id="76c1c-107">The node name replica will be initialized with</span></span></para>
        </param>
        <param name="lastInBuildDuration">
          <para><span data-ttu-id="76c1c-108">ビルド時間レプリカ内の最後で初期化されます。</span><span class="sxs-lookup"><span data-stu-id="76c1c-108">The last in build duration replica will be initialized with.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="76c1c-109">レプリカを初期化します。</span><span class="sxs-lookup"><span data-stu-id="76c1c-109">Initializes a replica</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Query.Replica.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="76c1c-110">レプリカの正常性状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="76c1c-110">Gets the health state of the replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="76c1c-111">レプリカの正常性状態。</span><span class="sxs-lookup"><span data-stu-id="76c1c-111">The health state of the replica.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public long Id { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Id" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As Long" />
      <MemberSignature Language="F#" Value="member this.Id : int64 with get, set" Usage="System.Fabric.Query.Replica.Id" />
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
          <para><span data-ttu-id="76c1c-112">レプリカの識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="76c1c-112">Gets the replica identifier.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="76c1c-113">レプリカの識別子です。</span><span class="sxs-lookup"><span data-stu-id="76c1c-113">The replica identifier.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastInBuildDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LastInBuildDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LastInBuildDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.LastInBuildDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastInBuildDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LastInBuildDuration : TimeSpan" Usage="System.Fabric.Query.Replica.LastInBuildDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="76c1c-114">最後にビルドを取得期間。</span><span class="sxs-lookup"><span data-stu-id="76c1c-114">Gets last in build duration.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="76c1c-115">ビルドの期間内の最後。</span><span class="sxs-lookup"><span data-stu-id="76c1c-115">The last in build duration.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastInBuildDurationInSeconds">
      <MemberSignature Language="C#" Value="protected internal long LastInBuildDurationInSeconds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastInBuildDurationInSeconds" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.LastInBuildDurationInSeconds" />
      <MemberSignature Language="VB.NET" Value="Protected Friend ReadOnly Property LastInBuildDurationInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.LastInBuildDurationInSeconds : int64" Usage="System.Fabric.Query.Replica.LastInBuildDurationInSeconds" />
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
            <span data-ttu-id="76c1c-116">ビルド時間を秒単位の最後に取得します。</span><span class="sxs-lookup"><span data-stu-id="76c1c-116">Gets last in build duration in seconds.</span></span>
            </summary>
        <value><span data-ttu-id="76c1c-117">最後のビルド時間の秒単位にします。</span><span class="sxs-lookup"><span data-stu-id="76c1c-117">Last in build duration in seconds.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Query.Replica.NodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="76c1c-118">レプリカが実行されているノード名を取得します。</span><span class="sxs-lookup"><span data-stu-id="76c1c-118">Gets the node name the replica is running on.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="76c1c-119">ノード名、レプリカがで実行されています。</span><span class="sxs-lookup"><span data-stu-id="76c1c-119">The node name the replica is running on.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaAddress">
      <MemberSignature Language="C#" Value="public string ReplicaAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicaAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.ReplicaAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicaAddress : string" Usage="System.Fabric.Query.Replica.ReplicaAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="76c1c-120">レプリカがリッスン アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="76c1c-120">Gets the address the replica is listening on.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="76c1c-121">アドレス、レプリカがリッスンします。</span><span class="sxs-lookup"><span data-stu-id="76c1c-121">The address the replica is listening on.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceReplicaStatus ReplicaStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceReplicaStatus ReplicaStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.ReplicaStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaStatus As ServiceReplicaStatus" />
      <MemberSignature Language="F#" Value="member this.ReplicaStatus : System.Fabric.Query.ServiceReplicaStatus" Usage="System.Fabric.Query.Replica.ReplicaStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="76c1c-122">レプリカの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="76c1c-122">Gets the status of the replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="76c1c-123">レプリカの状態です。</span><span class="sxs-lookup"><span data-stu-id="76c1c-123">The status of the replica.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceKind ServiceKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceKind ServiceKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.ServiceKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceKind As ServiceKind" />
      <MemberSignature Language="F#" Value="member this.ServiceKind : System.Fabric.Query.ServiceKind" Usage="System.Fabric.Query.Replica.ServiceKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76c1c-124">サービスの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="76c1c-124">Gets the service kind.</span></span>
            </summary>
        <value><span data-ttu-id="76c1c-125">サービスの種類。</span><span class="sxs-lookup"><span data-stu-id="76c1c-125">The service kind.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>