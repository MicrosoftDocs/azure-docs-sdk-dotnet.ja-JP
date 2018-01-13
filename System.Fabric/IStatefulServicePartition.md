<Type Name="IStatefulServicePartition" FullName="System.Fabric.IStatefulServicePartition">
  <TypeSignature Language="C#" Value="public interface IStatefulServicePartition : System.Fabric.IServicePartition" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatefulServicePartition implements class System.Fabric.IServicePartition" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatefulServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatefulServicePartition&#xA;Implements IServicePartition" />
  <TypeSignature Language="F#" Value="type IStatefulServicePartition = interface&#xA;    interface IServicePartition" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IServicePartition</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="cd099-101">ステートフル サービス レプリカに関連付けられているパーティションを表します。</span><span class="sxs-lookup"><span data-stu-id="cd099-101">Represents a partition that is associated with a stateful service replica.</span></span> </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="cd099-102"><see cref="T:System.Fabric.IServicePartition" /> の派生クラスです。</span><span class="sxs-lookup"><span data-stu-id="cd099-102">Derived from <see cref="T:System.Fabric.IServicePartition" />.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateReplicator">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricReplicator CreateReplicator (System.Fabric.IStateProvider stateProvider, System.Fabric.ReplicatorSettings replicatorSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.FabricReplicator CreateReplicator(class System.Fabric.IStateProvider stateProvider, class System.Fabric.ReplicatorSettings replicatorSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="abstract member CreateReplicator : System.Fabric.IStateProvider * System.Fabric.ReplicatorSettings -&gt; System.Fabric.FabricReplicator" Usage="iStatefulServicePartition.CreateReplicator (stateProvider, replicatorSettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricReplicator</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateProvider" Type="System.Fabric.IStateProvider" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="stateProvider">
          <para><span data-ttu-id="cd099-103"><see cref="T:System.Fabric.IStateProvider" />いる、返された<see cref="T:System.Fabric.FabricReplicator" />関連付けする必要があります。</span><span class="sxs-lookup"><span data-stu-id="cd099-103">The <see cref="T:System.Fabric.IStateProvider" /> with which the returned <see cref="T:System.Fabric.FabricReplicator" /> should be associated.</span></span> <span data-ttu-id="cd099-104">これは、多くの場合、同じオブジェクトを実装する<see cref="T:System.Fabric.IStatefulServiceReplica" />、特定のサービスを異なる方法で考慮することがありますが、します。</span><span class="sxs-lookup"><span data-stu-id="cd099-104">This is often the same object that implements <see cref="T:System.Fabric.IStatefulServiceReplica" />, but certain services might be factored differently.</span></span> </para>
        </param>
        <param name="replicatorSettings">
          <para><span data-ttu-id="cd099-105"><see cref="T:System.Fabric.ReplicatorSettings" />いる、返された<see cref="T:System.Fabric.FabricReplicator" />構成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="cd099-105">The <see cref="T:System.Fabric.ReplicatorSettings" /> with which the returned <see cref="T:System.Fabric.FabricReplicator" /> should be configured.</span></span> </para>
        </param>
        <summary>
          <para><span data-ttu-id="cd099-106">作成、<see cref="T:System.Fabric.FabricReplicator" />指定された設定で、レプリカに返します。</span><span class="sxs-lookup"><span data-stu-id="cd099-106">Creates a <see cref="T:System.Fabric.FabricReplicator" /> with the specified settings and returns it to the replica.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="cd099-107"><see cref="T:System.Fabric.FabricReplicator" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="cd099-107">Returns <see cref="T:System.Fabric.FabricReplicator" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="cd099-108">このメソッドは、作成に使用する必要があります、<see cref="T:System.Fabric.FabricReplicator" />サービスとして、<see cref="T:System.Fabric.IStateReplicator" />ステートフルなサービスを実装する<see cref="T:System.Fabric.IStateProvider" />です。</span><span class="sxs-lookup"><span data-stu-id="cd099-108">This method should be used to create a <see cref="T:System.Fabric.FabricReplicator" /> to service as the <see cref="T:System.Fabric.IStateReplicator" /> for a stateful service that implements <see cref="T:System.Fabric.IStateProvider" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionAccessStatus ReadStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PartitionAccessStatus ReadStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IStatefulServicePartition.ReadStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadStatus As PartitionAccessStatus" />
      <MemberSignature Language="F#" Value="member this.ReadStatus : System.Fabric.PartitionAccessStatus" Usage="System.Fabric.IStatefulServicePartition.ReadStatus" />
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
          <para><span data-ttu-id="cd099-109">読み取り操作に関して、レプリカの準備の確認に使用されます。</span><span class="sxs-lookup"><span data-stu-id="cd099-109">Used to check the readiness of the replica in regard to read operations.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="cd099-110"><see cref="T:System.Fabric.PartitionAccessStatus" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="cd099-110">Returns <see cref="T:System.Fabric.PartitionAccessStatus" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="cd099-111"><see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />レプリカが読み取り操作は、顧客の要求を処理する前に確認する必要があります。</span><span class="sxs-lookup"><span data-stu-id="cd099-111">The <see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" /> should be checked before the replica is servicing a customer request that is a read operation.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="cd099-112">これは、パーティション オブジェクトが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="cd099-112">This indicates that the partition object is closed.</span></span> <span data-ttu-id="cd099-113">レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</span><span class="sxs-lookup"><span data-stu-id="cd099-113">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportReplicaHealth">
      <MemberSignature Language="C#" Value="public void ReportReplicaHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportReplicaHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServicePartition.ReportReplicaHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportReplicaHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportReplicaHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iStatefulServicePartition.ReportReplicaHealth healthInfo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="healthInfo"><span data-ttu-id="cd099-114"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="cd099-114">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property, and health state.</span></span></param>
        <summary>
            <span data-ttu-id="cd099-115">パーティションの現在のステートフル サービス レプリカの正常性を報告します。</span><span class="sxs-lookup"><span data-stu-id="cd099-115">Reports health on the current stateful service replica of the partition.</span></span>
            </summary>
        <returns />
        <remarks>
          <para><span data-ttu-id="cd099-116">正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。</span><span class="sxs-lookup"><span data-stu-id="cd099-116">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="cd099-117">パーティションは、正常性ストアに、レポートを送信するのに内部ヘルス クライアントを使用します。</span><span class="sxs-lookup"><span data-stu-id="cd099-117">The partition uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="cd099-118">クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。</span><span class="sxs-lookup"><span data-stu-id="cd099-118">The client optimizes messages to Health Manager by batching reports per a configured duration (Default: 30 seconds).</span></span>
            <span data-ttu-id="cd099-119">使用してすぐに送信する送信オプションを指定できますが高優先度をレポート、<see cref="M:System.Fabric.IStatefulServicePartition.ReportReplicaHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />です。</span><span class="sxs-lookup"><span data-stu-id="cd099-119">If the report has high priority, you can specify send options to send it immediately by using <see cref="M:System.Fabric.IStatefulServicePartition.ReportReplicaHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />.</span></span>
            </para>
          <para><span data-ttu-id="cd099-120">詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</span><span class="sxs-lookup"><span data-stu-id="cd099-120">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="cd099-121">これは、パーティション オブジェクトが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="cd099-121">This indicates that the partition object is closed.</span></span> <span data-ttu-id="cd099-122">レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</span><span class="sxs-lookup"><span data-stu-id="cd099-122">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportReplicaHealth">
      <MemberSignature Language="C#" Value="public void ReportReplicaHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportReplicaHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatefulServicePartition.ReportReplicaHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportReplicaHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportReplicaHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iStatefulServicePartition.ReportReplicaHealth (healthInfo, sendOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="healthInfo" Type="System.Fabric.Health.HealthInformation" />
        <Parameter Name="sendOptions" Type="System.Fabric.Health.HealthReportSendOptions" />
      </Parameters>
      <Docs>
        <param name="healthInfo"><span data-ttu-id="cd099-123"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="cd099-123">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property, and health state.</span></span></param>
        <param name="sendOptions">
          <para><span data-ttu-id="cd099-124"><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</span><span class="sxs-lookup"><span data-stu-id="cd099-124">The <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> that controls how the report is sent.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="cd099-125">パーティションの現在のステートフル サービス レプリカの正常性を報告します。</span><span class="sxs-lookup"><span data-stu-id="cd099-125">Reports health on the current stateful service replica of the partition.</span></span>
            </summary>
        <returns />
        <remarks>
          <para><span data-ttu-id="cd099-126">正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。</span><span class="sxs-lookup"><span data-stu-id="cd099-126">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="cd099-127">内部的には、パーティションは、正常性ストアに、レポートを送信するのに内部ヘルス クライアントを使用します。</span><span class="sxs-lookup"><span data-stu-id="cd099-127">Internally, the partition uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="cd099-128">クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。</span><span class="sxs-lookup"><span data-stu-id="cd099-128">The client optimizes messages to Health Manager by batching reports per a configured duration (Default: 30 seconds).</span></span>
            <span data-ttu-id="cd099-129">レポートに高優先順位がある場合は、直ちに送信する送信オプションを指定できます。</span><span class="sxs-lookup"><span data-stu-id="cd099-129">If the report has high priority, you can specify send options to send it immediately.</span></span>
            </para>
          <para><span data-ttu-id="cd099-130">詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</span><span class="sxs-lookup"><span data-stu-id="cd099-130">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="cd099-131">これは、パーティション オブジェクトが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="cd099-131">This indicates that the partition object is closed.</span></span> <span data-ttu-id="cd099-132">レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</span><span class="sxs-lookup"><span data-stu-id="cd099-132">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="WriteStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionAccessStatus WriteStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PartitionAccessStatus WriteStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IStatefulServicePartition.WriteStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteStatus As PartitionAccessStatus" />
      <MemberSignature Language="F#" Value="member this.WriteStatus : System.Fabric.PartitionAccessStatus" Usage="System.Fabric.IStatefulServicePartition.WriteStatus" />
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
          <para><span data-ttu-id="cd099-133">書き込み操作についてそのパーティションの準備の確認に使用されます。</span><span class="sxs-lookup"><span data-stu-id="cd099-133">Used to check the readiness of the partition in regard to write operations.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="cd099-134"><see cref="T:System.Fabric.PartitionAccessStatus" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="cd099-134">Returns <see cref="T:System.Fabric.PartitionAccessStatus" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="cd099-135"><see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" />レプリカは、書き込み操作は、顧客の要求をサービスする前に確認する必要があります。</span><span class="sxs-lookup"><span data-stu-id="cd099-135">The <see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" /> should be checked before the replica services a customer request that is a write operation.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="cd099-136">これは、パーティション オブジェクトが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="cd099-136">This indicates that the partition object is closed.</span></span> <span data-ttu-id="cd099-137">レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</span><span class="sxs-lookup"><span data-stu-id="cd099-137">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>