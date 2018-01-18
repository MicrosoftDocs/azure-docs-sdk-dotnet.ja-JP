<Type Name="IStatelessServicePartition" FullName="System.Fabric.IStatelessServicePartition">
  <TypeSignature Language="C#" Value="public interface IStatelessServicePartition : System.Fabric.IServicePartition" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatelessServicePartition implements class System.Fabric.IServicePartition" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatelessServicePartition" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatelessServicePartition&#xA;Implements IServicePartition" />
  <TypeSignature Language="F#" Value="type IStatelessServicePartition = interface&#xA;    interface IServicePartition" />
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
      <para><span data-ttu-id="ccd1e-101">ステートレス サービス インスタンスに関連付けられているパーティションを表します。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-101">Represents a partition that is associated with a stateless service instance.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="ccd1e-102">パラメーターとして、ステートレスなサービスを提供、<see cref="T:System.Fabric.IServicePartition" />です。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-102">Provided to a stateless service as a parameter to the <see cref="T:System.Fabric.IServicePartition" />.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ReportInstanceHealth">
      <MemberSignature Language="C#" Value="public void ReportInstanceHealth (System.Fabric.Health.HealthInformation healthInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportInstanceHealth(class System.Fabric.Health.HealthInformation healthInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServicePartition.ReportInstanceHealth(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportInstanceHealth (healthInfo As HealthInformation)" />
      <MemberSignature Language="F#" Value="abstract member ReportInstanceHealth : System.Fabric.Health.HealthInformation -&gt; unit" Usage="iStatelessServicePartition.ReportInstanceHealth healthInfo" />
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
        <param name="healthInfo"><span data-ttu-id="ccd1e-103"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-103">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property, and health state.</span></span></param>
        <summary>
            <span data-ttu-id="ccd1e-104">パーティションの現在のステートレスなサービス インスタンスの正常性に関する情報を報告します。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-104">Reports health information on the current stateless service instance of the partition.</span></span> 
            </summary>
        <returns />
        <remarks>
          <para><span data-ttu-id="ccd1e-105">正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-105">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="ccd1e-106">パーティションは、正常性ストアに、レポートを送信するのに内部ヘルス クライアントを使用します。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-106">The partition uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="ccd1e-107">使用してすぐに送信する送信オプションを指定できますが高優先度をレポート、<see cref="M:System.Fabric.IStatelessServicePartition.ReportInstanceHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />です。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-107">If the report has high priority, you can specify send options to send it immediately by using <see cref="M:System.Fabric.IStatelessServicePartition.ReportInstanceHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />.</span></span>
            </para>
          <para><span data-ttu-id="ccd1e-108">詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-108">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="ccd1e-109">これは、パーティション オブジェクトが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-109">This indicates that the partition object is closed.</span></span> <span data-ttu-id="ccd1e-110">レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-110">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReportInstanceHealth">
      <MemberSignature Language="C#" Value="public void ReportInstanceHealth (System.Fabric.Health.HealthInformation healthInfo, System.Fabric.Health.HealthReportSendOptions sendOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReportInstanceHealth(class System.Fabric.Health.HealthInformation healthInfo, class System.Fabric.Health.HealthReportSendOptions sendOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServicePartition.ReportInstanceHealth(System.Fabric.Health.HealthInformation,System.Fabric.Health.HealthReportSendOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReportInstanceHealth (healthInfo As HealthInformation, sendOptions As HealthReportSendOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReportInstanceHealth : System.Fabric.Health.HealthInformation * System.Fabric.Health.HealthReportSendOptions -&gt; unit" Usage="iStatelessServicePartition.ReportInstanceHealth (healthInfo, sendOptions)" />
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
        <param name="healthInfo"><span data-ttu-id="ccd1e-111"><see cref="T:System.Fabric.Health.HealthInformation" />ソース、プロパティ、および正常性の状態などの正常性レポート情報を説明します。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-111">The <see cref="T:System.Fabric.Health.HealthInformation" /> that describes the health report information, such as source, property and health state.</span></span></param>
        <param name="sendOptions">
          <para><span data-ttu-id="ccd1e-112"><see cref="T:System.Fabric.Health.HealthReportSendOptions" />レポートを送信する方法を制御します。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-112">The <see cref="T:System.Fabric.Health.HealthReportSendOptions" /> that controls how the report is sent.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="ccd1e-113">パーティションの現在のステートレスなサービス インスタンスの正常性に関する情報を報告します。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-113">Reports health information on the current stateless service instance of the partition.</span></span> 
            </summary>
        <returns />
        <remarks>
          <para><span data-ttu-id="ccd1e-114">正常性に関する情報は、送信元の ID、プロパティ、ヘルス状態およびその他の関連する詳細情報と同様に、レポートの詳細について説明します。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-114">The health information describes the report details, like the source ID, the property, the health state and other relevant details.</span></span>
            <span data-ttu-id="ccd1e-115">パーティションは、正常性ストアに、レポートを送信するのに内部ヘルス クライアントを使用します。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-115">The partition uses an internal health client to send the reports to the health store.</span></span>
            <span data-ttu-id="ccd1e-116">クライアントが構成されている期間あたりのレポートをバッチ処理によってヘルス マネージャーにメッセージを最適化 (既定: 30 秒)。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-116">The client optimizes messages to Health Manager by batching reports per a configured duration (Default: 30 seconds).</span></span>
            <span data-ttu-id="ccd1e-117">レポートに高優先順位がある場合は、直ちに送信する送信オプションを指定できます。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-117">If the report has high priority, you can specify send options to send it immediately.</span></span>
            </para>
          <para><span data-ttu-id="ccd1e-118">詳細について<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">正常性レポート</see>です。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-118">Read more about <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-report-health">health reporting</see>.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="ccd1e-119">これは、パーティション オブジェクトが閉じていることを示します。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-119">This indicates that the partition object is closed.</span></span> <span data-ttu-id="ccd1e-120">レプリカ/レプリケーター/インスタンスが閉じられたか、またはは閉じられます。</span><span class="sxs-lookup"><span data-stu-id="ccd1e-120">The replica/replicator/instance has either been closed or is about to be closed.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>