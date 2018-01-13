<Type Name="MonitoredRollingFabricUpgradePolicyDescription" FullName="System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription">
  <TypeSignature Language="C#" Value="public sealed class MonitoredRollingFabricUpgradePolicyDescription : System.Fabric.Description.MonitoredRollingUpgradePolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MonitoredRollingFabricUpgradePolicyDescription extends System.Fabric.Description.MonitoredRollingUpgradePolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MonitoredRollingFabricUpgradePolicyDescription&#xA;Inherits MonitoredRollingUpgradePolicyDescription" />
  <TypeSignature Language="F#" Value="type MonitoredRollingFabricUpgradePolicyDescription = class&#xA;    inherit MonitoredRollingUpgradePolicyDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.MonitoredRollingUpgradePolicyDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="113c9-101">クラスターのアップグレードを実行するときに使用する動作について説明します。</span><span class="sxs-lookup"><span data-stu-id="113c9-101">Describes the behavior to use when performing a cluster upgrade.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MonitoredRollingFabricUpgradePolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="113c9-102"><see cref="T:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="113c9-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.ApplicationHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationHealthPolicyMap As ApplicationHealthPolicyMap" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthPolicyMap : System.Fabric.Health.ApplicationHealthPolicyMap" Usage="System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.ApplicationHealthPolicyMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthPolicyMap</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="113c9-103">取得またはクラスターの正常性評価の一部としてアプリケーションのヘルスを評価するポリシーが使用されるアプリケーションの正常性を設定します。</span><span class="sxs-lookup"><span data-stu-id="113c9-103">Gets or sets the application health policies used to evaluate the applications health as part of the cluster health evaluation.</span></span> 
            </summary>
        <value><span data-ttu-id="113c9-104">アプリケーションの正常性ポリシーは、指定したアプリケーションの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="113c9-104">The application health policies used to evaluate the health of the specified applications.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="113c9-105">クラスターのアップグレード中に、クラスターの正常性を評価して、クラスターがまだ正常であるかどうかを決定します。</span><span class="sxs-lookup"><span data-stu-id="113c9-105">During cluster upgrade, the health of the cluster is evaluated to determine whether the cluster is still healthy.</span></span> <span data-ttu-id="113c9-106">クラスターの正常性評価の一部として、すべてのアプリケーションが評価され、クラスターの正常性で集計します。</span><span class="sxs-lookup"><span data-stu-id="113c9-106">As part of the cluster health evaluation, all applications are evaluated and aggregated in the cluster health.</span></span>
            <span data-ttu-id="113c9-107">アプリケーションの正常性ポリシー マップを使用して、クラスターの評価の一部としてアプリケーションを評価します。</span><span class="sxs-lookup"><span data-stu-id="113c9-107">The application health policy map is used to evaluate the applications as part of the cluster evaluation.</span></span>
            </para>
          <para>
            <span data-ttu-id="113c9-108">各エントリは、アプリケーションの名前をキーとして、および値を指定します、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />そのアプリケーションのアプリケーションのヘルスを評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="113c9-108">Each entry specifies as key the application name and as value an <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate the application health of that application.</span></span></para>
          <para>
            <span data-ttu-id="113c9-109">アプリケーションが、マップで指定されていない場合、アプリケーション マニフェストで検出された表す ApplicationHealthPolicy が評価のため使用されます。</span><span class="sxs-lookup"><span data-stu-id="113c9-109">If an application is not specified in the map, the ApplicationHealthPolicy found in the application manifest will be used for evaluation.</span></span> </para>
          <para>
            <span data-ttu-id="113c9-110">アップグレード中に、クラスターの正常性を評価するカスタム アプリケーションの正常性ポリシーにも使用<see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />または<see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="113c9-110">The custom application health policies are also used to evaluate cluster health during upgrade, through <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" /> or <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span></para>
          <para>
            <span data-ttu-id="113c9-111">マップは、既定では空です。</span><span class="sxs-lookup"><span data-stu-id="113c9-111">The map is empty by default.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDeltaHealthEvaluation">
      <MemberSignature Language="C#" Value="public bool EnableDeltaHealthEvaluation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableDeltaHealthEvaluation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.EnableDeltaHealthEvaluation" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDeltaHealthEvaluation As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableDeltaHealthEvaluation : bool with get, set" Usage="System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.EnableDeltaHealthEvaluation" />
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
          <para><span data-ttu-id="113c9-112">取得またはデルタ評価が有効になっているかどうかを示すフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="113c9-112">Gets or sets a flag indicating whether delta evaluation is enabled.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="113c9-113"><languageKeyword>true</languageKeyword>デルタの正常性評価を有効にするとします。<languageKeyword>false</languageKeyword>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="113c9-113"><languageKeyword>true</languageKeyword> when delta health evaluation is enabled; <languageKeyword>false</languageKeyword> otherwise.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="113c9-114">デルタの評価を有効にすると、クラスターの正常性評価の制限が許容されるは、正常性の面のパフォーマンスの低下がグローバルに、すべてのノードとごとに評価される各アップグレード ドメインの両方でことによって確認されます。</span><span class="sxs-lookup"><span data-stu-id="113c9-114">When delta evaluation is enabled, the cluster health evaluation ensures that the degradation of health respects tolerated limits, both globally, across all nodes, and per each upgrade domain that is evaluated.</span></span> <span data-ttu-id="113c9-115">指定された許容しきい値<see cref="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" />です。</span><span class="sxs-lookup"><span data-stu-id="113c9-115">The tolerated thresholds are specified in <see cref="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" />.</span></span></para>
          <para><span data-ttu-id="113c9-116">デルタの評価は既定では無効にします。</span><span class="sxs-lookup"><span data-stu-id="113c9-116">Delta evaluation is disabled by default.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ClusterHealthPolicy with get, set" Usage="System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="113c9-117">取得またはアップグレード中のクラスターに対してパフォーマンスの正常性がチェックするときに使用する正常性ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="113c9-117">Gets or sets the health policy to use when performing health checks against an upgrading cluster.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="113c9-118">正常性を実行するときに使用する正常性ポリシーは、アップグレード中のクラスターに対してを確認します。</span><span class="sxs-lookup"><span data-stu-id="113c9-118">The health policy to use when performing health checks against an upgrading cluster.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeHealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterUpgradeHealthPolicy UpgradeHealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterUpgradeHealthPolicy UpgradeHealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.UpgradeHealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeHealthPolicy As ClusterUpgradeHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.UpgradeHealthPolicy : System.Fabric.Health.ClusterUpgradeHealthPolicy with get, set" Usage="System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.UpgradeHealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterUpgradeHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="113c9-119">取得またはアップグレード中のクラスターに対してパフォーマンスの正常性をチェックするときに使用するデルタの正常性ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="113c9-119">Gets or sets the delta health policy to use when performing health checks against an upgrading cluster.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="113c9-120">正常性を実行するときに使用するデルタの正常性ポリシーは、アップグレード中のクラスターに対してを確認します。</span><span class="sxs-lookup"><span data-stu-id="113c9-120">The delta health policy to use when performing health checks against an upgrading cluster.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="113c9-121">アップグレードのヘルス ポリシーを使用するときに<see cref="P:System.Fabric.Description.FabricUpgradeUpdateDescription.EnableDeltaHealthEvaluation" />に設定されている<languageKeyword>true</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="113c9-121">The upgrade health policy is used when <see cref="P:System.Fabric.Description.FabricUpgradeUpdateDescription.EnableDeltaHealthEvaluation" /> is set to <languageKeyword>true</languageKeyword>.</span></span> <span data-ttu-id="113c9-122">デルタの評価は既定では無効にします。</span><span class="sxs-lookup"><span data-stu-id="113c9-122">Delta evaluation is disabled by default.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>