<Type Name="IServicePartition" FullName="System.Fabric.IServicePartition">
  <TypeSignature Language="C#" Value="public interface IServicePartition" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServicePartition" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServicePartition" />
  <TypeSignature Language="F#" Value="type IServicePartition = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1201:ElementsMustAppearInTheCorrectOrder", Justification="Preserve order of public interface member from V1.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="56442-101">パーティションに属しを実行時に、システムとの対話をサービスのメソッドを提供に関する情報をサービスを提供します。</span><span class="sxs-lookup"><span data-stu-id="56442-101">Provides information to the service about the partition to which it belongs and provides methods for the service to interact with the system during runtime.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PartitionInfo">
      <MemberSignature Language="C#" Value="public System.Fabric.ServicePartitionInformation PartitionInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ServicePartitionInformation PartitionInfo" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.IServicePartition.PartitionInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionInfo As ServicePartitionInformation" />
      <MemberSignature Language="F#" Value="member this.PartitionInfo : System.Fabric.ServicePartitionInformation" Usage="System.Fabric.IServicePartition.PartitionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ServicePartitionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="56442-102">アクセスできるように、<see cref="T:System.Fabric.ServicePartitionInformation" />パーティションの種類および ID を格納する、サービスの</span><span class="sxs-lookup"><span data-stu-id="56442-102">Provides access to the <see cref="T:System.Fabric.ServicePartitionInformation" /> of the service, which contains the partition type and ID.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="56442-103"><see cref="T:System.Fabric.ServicePartitionInformation" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="56442-103">Returns <see cref="T:System.Fabric.ServicePartitionInformation" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="56442-104">これは、パーティション オブジェクトが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="56442-104">This indicates that the partition object is closed.</span></span> <span data-ttu-id="56442-105">レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</span><span class="sxs-lookup"><span data-stu-id="56442-105">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportFault">
      <MemberSignature Language="C#" Value="public void ReportFault (System.Fabric.FaultType faultType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportFault(valuetype System.Fabric.FaultType faultType) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" />
      <MemberSignature Language="F#" Value="abstract member ReportFault : System.Fabric.FaultType -&gt; unit" Usage="iServicePartition.ReportFault faultType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="faultType" Type="System.Fabric.FaultType" />
      </Parameters>
      <Docs>
        <param name="faultType">
          <para><span data-ttu-id="56442-106"><see cref="T:System.Fabric.FaultType" />サービスで検出されました。</span><span class="sxs-lookup"><span data-stu-id="56442-106">The <see cref="T:System.Fabric.FaultType" /> that the service has encountered.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="56442-107">ランタイムにはエラーを報告するレプリカを有効にする元となることできません回復しする必要がありますを再起動または削除、エラーが発生することを示します。</span><span class="sxs-lookup"><span data-stu-id="56442-107">Enables the replica to report a fault to the runtime and indicates that it has encountered an error from which it cannot recover and must either be restarted or removed.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="56442-108">エラーは通常、サービス コードには、回復できない問題が発生したときに報告されます。</span><span class="sxs-lookup"><span data-stu-id="56442-108">A fault is typically reported when the service code encounters an issue from which it cannot recover.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="56442-109">これは、パーティション オブジェクトが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="56442-109">This indicates that the partition object is closed.</span></span> <span data-ttu-id="56442-110">レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</span><span class="sxs-lookup"><span data-stu-id="56442-110">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportLoad">
      <MemberSignature Language="C#" Value="public void ReportLoad (System.Collections.Generic.IEnumerable&lt;System.Fabric.LoadMetric&gt; metrics);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportLoad(class System.Collections.Generic.IEnumerable`1&lt;class System.Fabric.LoadMetric&gt; metrics) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportLoad (metrics As IEnumerable(Of LoadMetric))" />
      <MemberSignature Language="F#" Value="abstract member ReportLoad : seq&lt;System.Fabric.LoadMetric&gt; -&gt; unit" Usage="iServicePartition.ReportLoad metrics" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metrics" Type="System.Collections.Generic.IEnumerable&lt;System.Fabric.LoadMetric&gt;" />
      </Parameters>
      <Docs>
        <param name="metrics">
          <para><span data-ttu-id="56442-111">コレクション<see cref="T:System.Fabric.LoadMetric" />の負荷を報告します。</span><span class="sxs-lookup"><span data-stu-id="56442-111">A collection of <see cref="T:System.Fabric.LoadMetric" /> to report the load for.</span></span> </para>
        </param>
        <summary>
          <para><span data-ttu-id="56442-112">負荷分散のメトリックのセットの負荷を報告します。</span><span class="sxs-lookup"><span data-stu-id="56442-112">Reports the load for a set of load balancing metrics.</span></span> <span data-ttu-id="56442-113">いつでも、負荷を報告することができます、<see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />メソッドの 1 つまたは複数のプロパティを提供し、<see cref="T:System.Fabric.LoadMetric" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="56442-113">The load can be reported at any time via the <see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" /> method and provides one or more properties of the <see cref="T:System.Fabric.LoadMetric" /> method.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="56442-114">用意されているものに対応する、報告されたメトリック、<see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" />の一部として、<see cref="T:System.Fabric.Description.ServiceDescription" />サービスの作成に使用されます。</span><span class="sxs-lookup"><span data-stu-id="56442-114">The reported metrics should correspond to those that are provided in the <see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" /> as a part of the <see cref="T:System.Fabric.Description.ServiceDescription" /> that is used to create the service.</span></span> <span data-ttu-id="56442-115">説明には存在しない負荷メトリックは無視されます。</span><span class="sxs-lookup"><span data-stu-id="56442-115">Load metrics that are not present in the description are ignored.</span></span> <span data-ttu-id="56442-116">カスタム メトリックを報告機能では、サービスを分散させる追加のカスタム情報を基にした Service Fabric を使用します。</span><span class="sxs-lookup"><span data-stu-id="56442-116">Reporting custom metrics allows Service Fabric to balance services that are based on additional custom information.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="56442-117">これは、パーティション オブジェクトが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="56442-117">This indicates that the partition object is closed.</span></span> <span data-ttu-id="56442-118">レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</span><span class="sxs-lookup"><span data-stu-id="56442-118">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportMoveCost">
      <MemberSignature Language="C#" Value="public void ReportMoveCost (System.Fabric.MoveCost moveCost);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportMoveCost(valuetype System.Fabric.MoveCost moveCost) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportMoveCost(System.Fabric.MoveCost)" />
      <MemberSignature Language="F#" Value="abstract member ReportMoveCost : System.Fabric.MoveCost -&gt; unit" Usage="iServicePartition.ReportMoveCost moveCost" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="moveCost" Type="System.Fabric.MoveCost" />
      </Parameters>
      <Docs>
        <param name="moveCost">
          <para><span data-ttu-id="56442-119">報告<see cref="T:System.Fabric.MoveCost" />です。</span><span class="sxs-lookup"><span data-stu-id="56442-119">The reported <see cref="T:System.Fabric.MoveCost" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="56442-120">レプリカの移動コストを報告します。</span><span class="sxs-lookup"><span data-stu-id="56442-120">Reports the move cost for a replica.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="56442-121">サービスは、このメソッドを使用してレプリカの移動コストをレポートできます。</span><span class="sxs-lookup"><span data-stu-id="56442-121">Services can report move cost of a replica using this method.</span></span> <span data-ttu-id="56442-122">サービス ファブリック リソース残高は、クラスター内の最適なバランスを検索するときに、読み込み情報と、各レプリカの移動コストの両方を調べます。</span><span class="sxs-lookup"><span data-stu-id="56442-122">While the Service Fabric Resource Balances searches for the best balance in the cluster, it examines both load information and move cost of each replica.</span></span> <span data-ttu-id="56442-123">リソースの残高は分散を実現するために低コストでレプリカを移動たいとします。</span><span class="sxs-lookup"><span data-stu-id="56442-123">Resource balances will prefer to move replicas with lower cost in order to achieve balance.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="56442-124">これは、パーティション オブジェクトが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="56442-124">This indicates that the partition object is closed.</span></span> <span data-ttu-id="56442-125">レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</span><span class="sxs-lookup"><span data-stu-id="56442-125">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportPartitionHealth">
      <MemberSignature Language="C#" Value="public void ReportPartitionHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportPartitionHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportPartitionHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportPartitionHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportPartitionHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iServicePartition.ReportPartitionHealth healthInfo" />
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
        <param name="healthInfo"><span data-ttu-id="56442-126"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="56442-126">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property, and health state.</span></span></param>
        <summary>
            <span data-ttu-id="56442-127">現在のパーティションの正常性を報告します。</span><span class="sxs-lookup"><span data-stu-id="56442-127">Reports current partition health.</span></span> 
            </summary>
        <returns />
        <remarks>
          <para><span data-ttu-id="56442-128">正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。</span><span class="sxs-lookup"><span data-stu-id="56442-128">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="56442-129">パーティションは、正常性ストアに、レポートを送信するのに内部ヘルス クライアントを使用します。</span><span class="sxs-lookup"><span data-stu-id="56442-129">The partition uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="56442-130">クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。</span><span class="sxs-lookup"><span data-stu-id="56442-130">The client optimizes messages to Health Manager by batching reports per a configured duration (Default: 30 seconds).</span></span>
            <span data-ttu-id="56442-131">使用してすぐに送信する送信オプションを指定できますが高優先度をレポート、<see cref="M:System.Fabric.IServicePartition.ReportPartitionHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />です。</span><span class="sxs-lookup"><span data-stu-id="56442-131">If the report has high priority, you can specify send options to send it immediately by using <see cref="M:System.Fabric.IServicePartition.ReportPartitionHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />.</span></span>
            </para>
          <para><span data-ttu-id="56442-132">詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</span><span class="sxs-lookup"><span data-stu-id="56442-132">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="56442-133">これは、パーティション オブジェクトが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="56442-133">This indicates that the partition object is closed.</span></span> <span data-ttu-id="56442-134">レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</span><span class="sxs-lookup"><span data-stu-id="56442-134">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportPartitionHealth">
      <MemberSignature Language="C#" Value="public void ReportPartitionHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportPartitionHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IServicePartition.ReportPartitionHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportPartitionHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportPartitionHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iServicePartition.ReportPartitionHealth (healthInfo, sendOptions)" />
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
        <param name="healthInfo"><span data-ttu-id="56442-135"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="56442-135">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property, and health state.</span></span></param>
        <param name="sendOptions">
          <para><span data-ttu-id="56442-136"><see cref="T:System.Fabric.Health.HealthReportSendOptions" />パーティション レポートを送信する方法を制御します。</span><span class="sxs-lookup"><span data-stu-id="56442-136">The <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> that controls how the partition report is sent.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="56442-137">現在のパーティションの正常性を報告します。</span><span class="sxs-lookup"><span data-stu-id="56442-137">Reports current partition health.</span></span> 
            </summary>
        <returns />
        <remarks>
          <para><span data-ttu-id="56442-138">正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。</span><span class="sxs-lookup"><span data-stu-id="56442-138">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="56442-139">パーティションは、正常性ストアに、レポートを送信するのに内部ヘルス クライアントを使用します。</span><span class="sxs-lookup"><span data-stu-id="56442-139">The partition uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="56442-140">クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。</span><span class="sxs-lookup"><span data-stu-id="56442-140">The client optimizes messages to Health Manager by batching reports per a configured duration (Default: 30 seconds).</span></span>
            <span data-ttu-id="56442-141">レポートに高優先順位がある場合は、直ちに送信する送信オプションを指定できます。</span><span class="sxs-lookup"><span data-stu-id="56442-141">If the report has high priority, you can specify send options to send it immediately.</span></span>
            </para>
          <para><span data-ttu-id="56442-142">詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</span><span class="sxs-lookup"><span data-stu-id="56442-142">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="56442-143">これは、パーティション オブジェクトが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="56442-143">This indicates that the partition object is closed.</span></span> <span data-ttu-id="56442-144">レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</span><span class="sxs-lookup"><span data-stu-id="56442-144">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>