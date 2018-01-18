<Type Name="FabricUpgradeUpdateDescription" FullName="System.Fabric.Description.FabricUpgradeUpdateDescription">
  <TypeSignature Language="C#" Value="public sealed class FabricUpgradeUpdateDescription : System.Fabric.Description.UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FabricUpgradeUpdateDescription extends System.Fabric.Description.UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.FabricUpgradeUpdateDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricUpgradeUpdateDescription&#xA;Inherits UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="F#" Value="type FabricUpgradeUpdateDescription = class&#xA;    inherit UpgradeUpdateDescriptionBase" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.UpgradeUpdateDescriptionBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="68cbf-101">クラスターのアップグレードの動作を記述するアップグレード パラメーターを変更するために使用します。</span><span class="sxs-lookup"><span data-stu-id="68cbf-101">Used to modify the upgrade parameters describing the behavior cluster upgrades.</span></span>
            <span data-ttu-id="68cbf-102">以下を参照してください。<see cref="M:System.Fabric.FabricClient.ClusterManagementClient.UpdateFabricUpgradeAsync(System.Fabric.Description.FabricUpgradeUpdateDescription)" /></span><span class="sxs-lookup"><span data-stu-id="68cbf-102">See <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.UpdateFabricUpgradeAsync(System.Fabric.Description.FabricUpgradeUpdateDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricUpgradeUpdateDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.FabricUpgradeUpdateDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="68cbf-103"><see cref="T:System.Fabric.Description.FabricUpgradeUpdateDescription" /> クラスのインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="68cbf-103">Creates an instance of the <see cref="T:System.Fabric.Description.FabricUpgradeUpdateDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.FabricUpgradeUpdateDescription.ApplicationHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationHealthPolicyMap As ApplicationHealthPolicyMap" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthPolicyMap : System.Fabric.Health.ApplicationHealthPolicyMap with get, set" Usage="System.Fabric.Description.FabricUpgradeUpdateDescription.ApplicationHealthPolicyMap" />
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
            <span data-ttu-id="68cbf-104">取得またはクラスターの正常性評価の一部としてアプリケーションのヘルスを評価するポリシーが使用されるアプリケーションの正常性を設定します。</span><span class="sxs-lookup"><span data-stu-id="68cbf-104">Gets or sets the application health policies used to evaluate the applications health as part of the cluster health evaluation.</span></span> 
            </summary>
        <value><span data-ttu-id="68cbf-105">アプリケーションの正常性ポリシーは、指定したアプリケーションの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="68cbf-105">The application health policies used to evaluate the health of the specified applications.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="68cbf-106">クラスターのアップグレード中に、クラスターの正常性を評価して、クラスターがまだ正常であるかどうかを決定します。</span><span class="sxs-lookup"><span data-stu-id="68cbf-106">During cluster upgrade, the health of the cluster is evaluated to determine whether the cluster is still healthy.</span></span> <span data-ttu-id="68cbf-107">クラスターの正常性評価の一部として、すべてのアプリケーションが評価され、クラスターの正常性で集計します。</span><span class="sxs-lookup"><span data-stu-id="68cbf-107">As part of the cluster health evaluation, all applications are evaluated and aggregated in the cluster health.</span></span>
            <span data-ttu-id="68cbf-108">アプリケーションの正常性ポリシー マップを使用して、クラスターの評価の一部としてアプリケーションを評価します。</span><span class="sxs-lookup"><span data-stu-id="68cbf-108">The application health policy map is used to evaluate the applications as part of the cluster evaluation.</span></span>
            </para>
          <para>
            <span data-ttu-id="68cbf-109">各エントリは、アプリケーションの名前をキーとして、および値を指定します、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />そのアプリケーションのアプリケーションのヘルスを評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="68cbf-109">Each entry specifies as key the application name and as value an <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate the application health of that application.</span></span>
            </para>
          <para>
            <span data-ttu-id="68cbf-110">アプリケーションが、マップで指定されていない場合、アプリケーション マニフェストで検出された表す ApplicationHealthPolicy が評価のため使用されます。</span><span class="sxs-lookup"><span data-stu-id="68cbf-110">If an application is not specified in the map, the ApplicationHealthPolicy found in the application manifest will be used for evaluation.</span></span> </para>
          <para>
            <span data-ttu-id="68cbf-111">アップグレード中に、クラスターの正常性を評価するカスタム アプリケーションの正常性ポリシーにも使用<see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />または<see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="68cbf-111">The custom application health policies are also used to evaluate cluster health during upgrade, through <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" /> or <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span>
            </para>
          <para>
            <span data-ttu-id="68cbf-112">マップは、既定では、以前にアプリケーションの正常性ポリシーを設定する、更新プログラムを適用しないことが null です。</span><span class="sxs-lookup"><span data-stu-id="68cbf-112">The map is null by default, which means that the update doesn't apply to previously set application health policies.</span></span>
            <span data-ttu-id="68cbf-113">アプリケーションの正常性ポリシーを更新するには、マップを作成し、必要なアプリケーションのエントリを追加します。</span><span class="sxs-lookup"><span data-stu-id="68cbf-113">To update the application health policies, first create the map then add entries for desired applications.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDeltaHealthEvaluation">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableDeltaHealthEvaluation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableDeltaHealthEvaluation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.FabricUpgradeUpdateDescription.EnableDeltaHealthEvaluation" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDeltaHealthEvaluation As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableDeltaHealthEvaluation : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.Description.FabricUpgradeUpdateDescription.EnableDeltaHealthEvaluation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="68cbf-114">取得またはデルタ評価が有効になっているかどうかを示すフラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="68cbf-114">Gets or sets a flag indicating whether delta evaluation is enabled.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="68cbf-115"><languageKeyword>true</languageKeyword>デルタの正常性評価を有効にするとします。<languageKeyword>false</languageKeyword>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="68cbf-115"><languageKeyword>true</languageKeyword> when delta health evaluation is enabled; <languageKeyword>false</languageKeyword> otherwise.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="68cbf-116">デルタの評価を有効にすると、クラスターの正常性評価の制限が許容されるは、正常性の面のパフォーマンスの低下がグローバルに、すべてのノードとごとに評価される各アップグレード ドメインの両方でことによって確認されます。</span><span class="sxs-lookup"><span data-stu-id="68cbf-116">When delta evaluation is enabled, the cluster health evaluation ensures that the degradation of health respects tolerated limits, both globally, across all nodes, and per each upgrade domain that is evaluated.</span></span> <span data-ttu-id="68cbf-117">指定された許容しきい値<see cref="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" />です。</span><span class="sxs-lookup"><span data-stu-id="68cbf-117">The tolerated thresholds are specified in <see cref="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" />.</span></span></para>
          <para><span data-ttu-id="68cbf-118">デルタの評価は既定では無効にします。</span><span class="sxs-lookup"><span data-stu-id="68cbf-118">Delta evaluation is disabled by default.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.FabricUpgradeUpdateDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ClusterHealthPolicy with get, set" Usage="System.Fabric.Description.FabricUpgradeUpdateDescription.HealthPolicy" />
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
          <para><span data-ttu-id="68cbf-119"><see cref="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.HealthPolicy" /> を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="68cbf-119">Gets or sets the <see cref="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.HealthPolicy" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="68cbf-120">クラスターの正常性ポリシーはアップグレード中にクラスターの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="68cbf-120">The cluster health policy used to evaluate cluster health during upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeHealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterUpgradeHealthPolicy UpgradeHealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterUpgradeHealthPolicy UpgradeHealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.FabricUpgradeUpdateDescription.UpgradeHealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeHealthPolicy As ClusterUpgradeHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.UpgradeHealthPolicy : System.Fabric.Health.ClusterUpgradeHealthPolicy with get, set" Usage="System.Fabric.Description.FabricUpgradeUpdateDescription.UpgradeHealthPolicy" />
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
          <para><span data-ttu-id="68cbf-121"><see cref="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.UpgradeHealthPolicy" /> を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="68cbf-121">Gets or sets the <see cref="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.UpgradeHealthPolicy" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="68cbf-122">クラスターのアップグレードのヘルス ポリシーはアップグレード中にクラスターの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="68cbf-122">The cluster upgrade health policy used to evaluate cluster health during upgrade.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="68cbf-123">アップグレードのヘルス ポリシーを使用するときに<see cref="P:System.Fabric.Description.FabricUpgradeUpdateDescription.EnableDeltaHealthEvaluation" />に設定されている<languageKeyword>true</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="68cbf-123">The upgrade health policy is used when <see cref="P:System.Fabric.Description.FabricUpgradeUpdateDescription.EnableDeltaHealthEvaluation" /> is set to <languageKeyword>true</languageKeyword>.</span></span> <span data-ttu-id="68cbf-124">デルタの評価は既定では無効です。</span><span class="sxs-lookup"><span data-stu-id="68cbf-124">The delta evaluation is disabled by default.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>