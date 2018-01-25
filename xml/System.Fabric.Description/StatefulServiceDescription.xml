<Type Name="StatefulServiceDescription" FullName="System.Fabric.Description.StatefulServiceDescription">
  <TypeSignature Language="C#" Value="public sealed class StatefulServiceDescription : System.Fabric.Description.ServiceDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatefulServiceDescription extends System.Fabric.Description.ServiceDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.StatefulServiceDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatefulServiceDescription&#xA;Inherits ServiceDescription" />
  <TypeSignature Language="F#" Value="type StatefulServiceDescription = class&#xA;    inherit ServiceDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServiceDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="b7dd3-101">拡張を表す<see cref="T:System.Fabric.Description.ServiceDescription" />ステートフルなサービスを作成するために必要な追加情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-101">Represents the extend <see cref="T:System.Fabric.Description.ServiceDescription" /> to provide additional information necessary to create stateful services.</span></span></para>
    </summary>
    <remarks>
      <para />
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatefulServiceDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatefulServiceDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="b7dd3-102"><see cref="T:System.Fabric.Description.StatefulServiceDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.StatefulServiceDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasPersistedState">
      <MemberSignature Language="C#" Value="public bool HasPersistedState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasPersistedState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.HasPersistedState" />
      <MemberSignature Language="VB.NET" Value="Public Property HasPersistedState As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasPersistedState : bool with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.HasPersistedState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b7dd3-103">取得またはこのインスタンスの状態が永続化するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-103">Gets or sets a value indicating whether this instance has persisted state.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="b7dd3-104"><languageKeyword>true</languageKeyword>状態、それ以外のインスタンスが永続化する場合<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-104"><languageKeyword>true</languageKeyword> if the instance has persisted state; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b7dd3-105">ときに、<see cref="T:System.Fabric.FabricReplicator" />でセカンダリ レプリカが永続的なサービスの操作を受け取り、その受信確認を送信できるプライマリ前に、データが保持されていることを確認するサービスを待つ必要があります。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-105">When a <see cref="T:System.Fabric.FabricReplicator" /> at a secondary replica receives an operation for a persistent service, it must wait for the service to acknowledge that the data has been persisted before it can send that acknowledgment back to the primary.</span></span> <span data-ttu-id="b7dd3-106">非永続的なサービスでは、操作受信を確認できますすぐに受信したときにします。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-106">For non-persistent services, the operation can be acknowledged immediately upon receipt.</span></span></para>
          <para><span data-ttu-id="b7dd3-107">永続的なサービスのレプリカが失敗した場合、Service Fabric すぐには考慮されませんそのレプリカを損失としてそのレプリカの永続的な状態がまだ存在するため。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-107">When a persistent service replica fails, the Service Fabric will not immediately consider that replica as lost because the persistent state for that replica still exists.</span></span> <span data-ttu-id="b7dd3-108">レプリカを復旧した場合を再作成できます永続化された状態を使用します。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-108">If the replica is recovered, it can be recreated using the persisted state.</span></span> <span data-ttu-id="b7dd3-109">これに対し、代替レプリカをすぐにビルドを開始してがありますコストと、不要なエラーは一時的な場合は特にです。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-109">In contrast, beginning to build a replacement replica immediately may be costly and unnecessary, especially when the failures are transient.</span></span> <span data-ttu-id="b7dd3-110">Service Fabric が待機を最初から新しい (置換) レプリカを構築する前に回復する永続的なレプリカを構成するのには、使用、<see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />パラメーター。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-110">To configure how long Service Fabric should wait for the persistent replica to recover before building a new (replacement) replica from scratch, use the <see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" /> parameter.</span></span> <span data-ttu-id="b7dd3-111">非永続的なサービスの (を持つ<see cref="P:System.Fabric.Description.StatefulServiceDescription.HasPersistedState" />'éý' <languageKeyword>false</languageKeyword>)、Service Fabric の新しいレプリカの作成はすぐに開始 (から、回復する永続的な状態が存在しないためと同じようローカルな復旧を待機中にポイントがありません).</span><span class="sxs-lookup"><span data-stu-id="b7dd3-111">For non-persistent services (those with <see cref="P:System.Fabric.Description.StatefulServiceDescription.HasPersistedState" /> set to <languageKeyword>false</languageKeyword>), Service Fabric will immediately begin creating a new replica (since there is no persistent state to recover from, and hence no point in waiting for local recovery).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MinReplicaSetSize">
      <MemberSignature Language="C#" Value="public int MinReplicaSetSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MinReplicaSetSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MinReplicaSetSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MinReplicaSetSize : int with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b7dd3-112">取得またはこのサービスに許可されている最小のレプリカ セットのサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-112">Gets or sets the minimum allowed replica set size for this service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b7dd3-113">最小値には、このサービスのレプリカ セットのサイズが許可されています。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-113">The minimum allowed replica set size for this service.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b7dd3-114">Service Fabric が、特定のパーティションのレプリカ セットのビューで保持するレプリカの最小数を定義します。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-114">Defines the minimum number of replicas that Service Fabric will keep in its view of the Replica Set for a given partition.</span></span> <span data-ttu-id="b7dd3-115">たとえば場合、<see cref="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" />は 5 (5) 通常 (失敗) なし、そこに設定されて、レプリカ セットのビューに 5 つのレプリカになります。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-115">For example, if the <see cref="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" /> is set to five (5) then normally (without failures) there will be five replicas in the view of the replica set.</span></span> <span data-ttu-id="b7dd3-116">ただし、この数は障害中に低下します。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-116">However this number will decrease during failures.</span></span> <span data-ttu-id="b7dd3-117"><see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />ビューでは、レプリカの最小数を定義たとえば場合、 <see cref="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" /> 5 と<see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />、3 つは、3 つの同時障害 (を実行している残りの 2 つのレプリカでその結果、) 必要がありますがある場合でもレプリカ セット (を 2 とダウン) のビューに 3 つのレプリカです。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-117">The <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /> defines the minimum number of replicas in the view, so for example if the <see cref="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" /> is five and the <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /> is three, then even if there are three concurrent failures (resulting  in only two remaining replicas running) will still have three replicas in its view of the replica set (two up and one down).</span></span> <span data-ttu-id="b7dd3-118">以降</span><span class="sxs-lookup"><span data-stu-id="b7dd3-118">Since</span></span>  
            <span data-ttu-id="b7dd3-119">クォーラムの過半数は、このビューで保持されるレプリカの数のマジョリティのクォーラムを使用して、<see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />は最小レベルのすべての操作の信頼性: 前の例では、ターゲット = 5 と Min = 3, 3 つの同時障害には、2 つの残りのレプリカ (および 1 つのダウン)、および 3 のマジョリティ クォーラム (、 <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />) は 2 です。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-119">uses majority quorum of the number of replicas maintained in this view, majority quorum of the <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /> is minimum level of reliability of any operation: in the prior example, with Target = 5 and Min = 3, with 3 concurrent failures, there are two remaining up replicas (and one down), and the majority quorum of 3 (the <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />) is 2.</span></span> <span data-ttu-id="b7dd3-120">つまり、プライマリ、引き続き操作をレプリケートすること、および、進捗 (パーティション) を設定する残りのセカンダリ レプリカがレプリカの順序で操作を適用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-120">This means that the primary will continue to be able to replicate operations AND that the remaining secondary replica MUST apply the operation in order for the replica set (partition) to make progress.</span></span> <span data-ttu-id="b7dd3-121">レプリカの合計数を下回るマジョリティ クォーラムのかどうか、<see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />以降に書き込みを禁止する、します。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-121">If the total number of replicas drops below the majority quorum of the <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" /> then further writes will be disallowed.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="QuorumLossWaitDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; QuorumLossWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; QuorumLossWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.QuorumLossWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property QuorumLossWaitDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.QuorumLossWaitDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.QuorumLossWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b7dd3-122">取得またはクォーラム損失の状態になるパーティションが許可されている、秒単位で最大の期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-122">Gets or sets the maximum duration, in seconds, for which a partition is allowed to be in a state of quorum loss.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b7dd3-123">この待機時間として、<see cref="T:System.TimeSpan" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-123">The wait duration as a <see cref="T:System.TimeSpan" /> object.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b7dd3-124">場合は、パーティションは、この期間が過ぎた後クォーラムが失われるは、パーティションが失われると下向きのレプリカを考慮してクォーラム損失から回復しました。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-124">If the partition is still in quorum loss after this duration, the partition is recovered from quorum loss by considering the down replicas as lost.</span></span> <span data-ttu-id="b7dd3-125">この場合、データ損失が発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-125">Note that this can potentially incur data loss.</span></span> <span data-ttu-id="b7dd3-126">既定値は無限大と、この値を変更するには使用しないでです。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-126">The default value is Infinity and it is not recommended to change this value.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaRestartWaitDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ReplicaRestartWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ReplicaRestartWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicaRestartWaitDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ReplicaRestartWaitDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b7dd3-127">取得または設定中は、レプリカがダウンしたときに、新しいレプリカが作成されたときまでの秒。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-127">Gets or sets the duration, in seconds, between when a replica goes down and when a new replica is created.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b7dd3-128">期間は、<see cref="T:System.TimeSpan" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-128">The duration as a <see cref="T:System.TimeSpan" /> object.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b7dd3-129">永続的なレプリカがダウンした場合は、このタイマーが開始されます。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-129">When a persistent replica goes down, this timer starts.</span></span>  <span data-ttu-id="b7dd3-130">有効期限が切れるときに、Service Fabric は、クラスター内の任意のノードでの新しいレプリカを作成します。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-130">When it expires Service Fabric will create a new replica on any node in the cluster.</span></span> <span data-ttu-id="b7dd3-131">この構成では、不要な状態のコピーを減らします。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-131">This configuration is to reduce unnecessary state copies.</span></span> <span data-ttu-id="b7dd3-132">永続化されたレプリカがダウンしたときの待ち時間に戻るには、<see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />コピーが必要とする新しいレプリカを作成する前に (秒)。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-132">When a persisted replica goes down, the system waits for it to come back up for <see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" /> seconds before creating a new replica which will require a copy.</span></span> <span data-ttu-id="b7dd3-133">注まだ、紛失、レプリカがダウンしているのとは見なされません。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-133">Note that a replica that is down is not considered lost, yet.</span></span></para>
          <para><span data-ttu-id="b7dd3-134">既定値は、300 (秒) です。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-134">The default value is 300 (seconds).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StandByReplicaKeepDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; StandByReplicaKeepDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; StandByReplicaKeepDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.StandByReplicaKeepDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property StandByReplicaKeepDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StandByReplicaKeepDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.StandByReplicaKeepDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b7dd3-135">取得または削除されるまでの StandBy レプリカを保持する期間の定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-135">Gets or sets the definition on how long StandBy replicas should be maintained before being removed.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b7dd3-136">削除されるまでの StandBy レプリカを保持する期間を定義します。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-136">The definition on how long StandBy replicas should be maintained before being removed.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b7dd3-137">レプリカをよりも長い間ダウンすると場合があります、<see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />です。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-137">Sometimes a replica will be down for longer than the <see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />.</span></span> <span data-ttu-id="b7dd3-138">このような場合に置き換える新しいレプリカがビルドされます。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-138">In these cases a new replica will be built to replace it.</span></span> <span data-ttu-id="b7dd3-139">場合がありますただし、障害は永続的なと永続的なレプリカを復旧最終的にします。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-139">Sometimes however the loss is not permanent and the persistent replica is eventually recovered.</span></span> <span data-ttu-id="b7dd3-140">これは、スタンバイ状態のレプリカを構成します。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-140">This now constitutes a StandBy replica.</span></span> <span data-ttu-id="b7dd3-141">スタンバイのレプリカは、場合はその後のエラーまたはリソースが既に存在して、回復を短縮するために使用できる永続的な状態であるため、アクションを分散優先的に使用されます。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-141">StandBy replicas will preferentially be used in the case of subsequent failures or resource balancing actions, since they represent persistent state that already exists and which can be used to expedite recovery.</span></span> <span data-ttu-id="b7dd3-142"><see cref="P:System.Fabric.Description.StatefulServiceDescription.StandByReplicaKeepDuration" />削除される前にこのような StandBy レプリカを保持する期間を定義します。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-142">The <see cref="P:System.Fabric.Description.StatefulServiceDescription.StandByReplicaKeepDuration" /> defines how long such StandBy replicas should be maintained before being removed.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetReplicaSetSize">
      <MemberSignature Language="C#" Value="public int TargetReplicaSetSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 TargetReplicaSetSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetReplicaSetSize As Integer" />
      <MemberSignature Language="F#" Value="member this.TargetReplicaSetSize : int with get, set" Usage="System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> <span data-ttu-id="b7dd3-143">取得またはレプリカ セットのターゲット サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-143">Gets or sets the target size of the replica set.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b7dd3-144">レプリカのターゲット サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-144">The target size of the replica set.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b7dd3-145">システムを作成し、このサービスの各パーティションを保持するレプリカの数。</span><span class="sxs-lookup"><span data-stu-id="b7dd3-145">The number of replicas that the system creates and maintains for each partition of this service.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>