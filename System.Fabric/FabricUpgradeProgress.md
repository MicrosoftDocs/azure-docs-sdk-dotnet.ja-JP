<Type Name="FabricUpgradeProgress" FullName="System.Fabric.FabricUpgradeProgress">
  <TypeSignature Language="C#" Value="public sealed class FabricUpgradeProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FabricUpgradeProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricUpgradeProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricUpgradeProgress" />
  <TypeSignature Language="F#" Value="type FabricUpgradeProgress = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="ae683-101">Service Fabric アップグレードの進行状況をカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="ae683-101">Encapsulates the progress of a Service Fabric upgrade.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CurrentUpgradeDomainDuration">
      <MemberSignature Language="C#" Value="public TimeSpan CurrentUpgradeDomainDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan CurrentUpgradeDomainDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.CurrentUpgradeDomainDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentUpgradeDomainDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.CurrentUpgradeDomainDuration : TimeSpan" Usage="System.Fabric.FabricUpgradeProgress.CurrentUpgradeDomainDuration" />
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
          <para><span data-ttu-id="ae683-102">予測の所要時間は、現在のアップグレード ドメインの処理に費やされたを取得します。</span><span class="sxs-lookup"><span data-stu-id="ae683-102">Gets the estimated elapsed time spent processing the current Upgrade Domain.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ae683-103">推定経過時間では、現在のアップグレード ドメインの処理に費やされました。</span><span class="sxs-lookup"><span data-stu-id="ae683-103">The estimated elapsed time spent processing the current Upgrade Domain.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentUpgradeDomainProgress">
      <MemberSignature Language="C#" Value="public System.Fabric.UpgradeDomainProgress CurrentUpgradeDomainProgress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.UpgradeDomainProgress CurrentUpgradeDomainProgress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.CurrentUpgradeDomainProgress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentUpgradeDomainProgress As UpgradeDomainProgress" />
      <MemberSignature Language="F#" Value="member this.CurrentUpgradeDomainProgress : System.Fabric.UpgradeDomainProgress" Usage="System.Fabric.FabricUpgradeProgress.CurrentUpgradeDomainProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeDomainProgress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ae683-104">現在のアップグレード ドメイン内のノードの詳細なアップグレードの進行状況を示します。</span><span class="sxs-lookup"><span data-stu-id="ae683-104">Gives the detailed upgrade progress for nodes in the current upgrade domain.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ae683-105"><see cref="T:System.Fabric.UpgradeDomainProgress" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="ae683-105">Returns <see cref="T:System.Fabric.UpgradeDomainProgress" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureReason">
      <MemberSignature Language="C#" Value="public Nullable&lt;System.Fabric.UpgradeFailureReason&gt; FailureReason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Fabric.UpgradeFailureReason&gt; FailureReason" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.FailureReason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureReason As Nullable(Of UpgradeFailureReason)" />
      <MemberSignature Language="F#" Value="member this.FailureReason : Nullable&lt;System.Fabric.UpgradeFailureReason&gt;" Usage="System.Fabric.FabricUpgradeProgress.FailureReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Fabric.UpgradeFailureReason&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="ae683-106">アップグレードが失敗した場合は、アップグレードの失敗のカテゴリを取得します。</span><span class="sxs-lookup"><span data-stu-id="ae683-106">Gets the category of upgrade failure if the upgrade failed.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="ae683-107">アップグレードの失敗のカテゴリ。</span><span class="sxs-lookup"><span data-stu-id="ae683-107">The category of upgrade failure.</span></span> <span data-ttu-id="ae683-108"><see cref="T:System.Fabric.UpgradeFailureReason" /></span><span class="sxs-lookup"><span data-stu-id="ae683-108"><see cref="T:System.Fabric.UpgradeFailureReason" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureTimestampUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; FailureTimestampUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; FailureTimestampUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.FailureTimestampUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureTimestampUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.FailureTimestampUtc : Nullable&lt;DateTime&gt;" Usage="System.Fabric.FabricUpgradeProgress.FailureTimestampUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="ae683-109">アップグレードが失敗した時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="ae683-109">Gets the time at which the upgrade failed.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="ae683-110">時刻 (utc) のアップグレードが失敗しました。</span><span class="sxs-lookup"><span data-stu-id="ae683-110">The time at which the upgrade failed in UTC.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetChangedUpgradeDomains">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt; GetChangedUpgradeDomains (System.Fabric.FabricUpgradeProgress previousProgress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class System.Fabric.UpgradeDomainStatus&gt; GetChangedUpgradeDomains(class System.Fabric.FabricUpgradeProgress previousProgress) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricUpgradeProgress.GetChangedUpgradeDomains(System.Fabric.FabricUpgradeProgress)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetChangedUpgradeDomains (previousProgress As FabricUpgradeProgress) As ReadOnlyCollection(Of UpgradeDomainStatus)" />
      <MemberSignature Language="F#" Value="member this.GetChangedUpgradeDomains : System.Fabric.FabricUpgradeProgress -&gt; System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;" Usage="fabricUpgradeProgress.GetChangedUpgradeDomains previousProgress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousProgress" Type="System.Fabric.FabricUpgradeProgress" />
      </Parameters>
      <Docs>
        <param name="previousProgress">
          <para><span data-ttu-id="ae683-111">このアップグレード プロセスから以前の進行状況レポートです。</span><span class="sxs-lookup"><span data-stu-id="ae683-111">The previous progress report from this  upgrade process.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="ae683-112">変更されたアップグレード ドメインの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="ae683-112">Gets the list of changed upgrade domains.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="ae683-113">変更されたアップグレード ドメインの一覧。</span><span class="sxs-lookup"><span data-stu-id="ae683-113">The list of changed upgrade domains.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextUpgradeDomain">
      <MemberSignature Language="C#" Value="public string NextUpgradeDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextUpgradeDomain" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.NextUpgradeDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextUpgradeDomain As String" />
      <MemberSignature Language="F#" Value="member this.NextUpgradeDomain : string" Usage="System.Fabric.FabricUpgradeProgress.NextUpgradeDomain" />
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
          <para><span data-ttu-id="ae683-114">このアップグレードには、次のアップグレード ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="ae683-114">Gets the next upgrade domain for this  upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ae683-115">このアップグレードの次のアップグレード ドメイン。</span><span class="sxs-lookup"><span data-stu-id="ae683-115">The next upgrade domain for this  upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RollingUpgradeMode">
      <MemberSignature Language="C#" Value="public System.Fabric.RollingUpgradeMode RollingUpgradeMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.RollingUpgradeMode RollingUpgradeMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.RollingUpgradeMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RollingUpgradeMode As RollingUpgradeMode" />
      <MemberSignature Language="F#" Value="member this.RollingUpgradeMode : System.Fabric.RollingUpgradeMode" Usage="System.Fabric.FabricUpgradeProgress.RollingUpgradeMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RollingUpgradeMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ae683-116">このアップグレードのローリング アップグレードのモードを取得します。</span><span class="sxs-lookup"><span data-stu-id="ae683-116">Gets the rolling upgrade mode for this  upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ae683-117">このアップグレードのローリング アップグレード モードです。</span><span class="sxs-lookup"><span data-stu-id="ae683-117">The rolling upgrade mode for this  upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTimestampUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTimestampUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTimestampUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.StartTimestampUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTimestampUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTimestampUtc : Nullable&lt;DateTime&gt;" Usage="System.Fabric.FabricUpgradeProgress.StartTimestampUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="ae683-118">アップグレードが開始された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="ae683-118">Gets the time at which the upgrade started.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="ae683-119">Utc 形式でアップグレードが開始された時刻。</span><span class="sxs-lookup"><span data-stu-id="ae683-119">The time at which the upgrade started in UTC.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetCodeVersion">
      <MemberSignature Language="C#" Value="public string TargetCodeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetCodeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.TargetCodeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetCodeVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetCodeVersion : string" Usage="System.Fabric.FabricUpgradeProgress.TargetCodeVersion" />
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
          <para><span data-ttu-id="ae683-120">このアップグレードのターゲット コード バージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="ae683-120">Gets the target code version for this  upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ae683-121">このアップグレードのターゲット コード バージョンです。</span><span class="sxs-lookup"><span data-stu-id="ae683-121">The target code version for this  upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetConfigVersion">
      <MemberSignature Language="C#" Value="public string TargetConfigVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetConfigVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.TargetConfigVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetConfigVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetConfigVersion : string" Usage="System.Fabric.FabricUpgradeProgress.TargetConfigVersion" />
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
          <para><span data-ttu-id="ae683-122">このアップグレードのターゲットの構成バージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="ae683-122">Gets the target configuration version for this  upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ae683-123">このアップグレードのターゲットの構成のバージョン。</span><span class="sxs-lookup"><span data-stu-id="ae683-123">The target configuration version for this  upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricUpgradeProgress.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="fabricUpgradeProgress.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ae683-124">Fabric アップグレードの進行状況の文字列表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="ae683-124">Gets a string representation of the fabric upgrade progress.</span></span>
            </summary>
        <returns><span data-ttu-id="ae683-125"><see cref="T:System.Fabric.FabricUpgradeProgress" /> の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="ae683-125">A string representation of the <see cref="T:System.Fabric.FabricUpgradeProgress" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.FabricUpgradeProgress.UnhealthyEvaluations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ae683-126">データおよびクラスターの正常性を評価する正常性マネージャーによって使用されるアルゴリズムを記述する正常性評価を取得します。</span><span class="sxs-lookup"><span data-stu-id="ae683-126">Gets the health evaluations which describe the data and the algorithm used by health manager to evaluate cluster health.</span></span> <span data-ttu-id="ae683-127">正常性状態が設定されるクラスターの集計の場合のみ<see cref="F:System.Fabric.Health.HealthState.Error" />です。</span><span class="sxs-lookup"><span data-stu-id="ae683-127">Only populated when the cluster’s aggregated health state is  <see cref="F:System.Fabric.Health.HealthState.Error" />.</span></span> <span data-ttu-id="ae683-128">正常性評価のため、アップグレードがロールバック時に、正常性チェックが実行された時刻に稼働状態のスナップショット ビューを提供します。</span><span class="sxs-lookup"><span data-stu-id="ae683-128">When the upgrade rolls back because of health evaluation, it provides a snapshot view of the health at the time the health check was performed.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ae683-129">現在の集計された正常性状態を原因となった異常な評価。</span><span class="sxs-lookup"><span data-stu-id="ae683-129">The unhealthy evaluations that led to current aggregated health state.</span></span> <span data-ttu-id="ae683-130">次の種類の一覧の項目を指定できます: <see cref="T:System.Fabric.Health.ApplicationsHealthEvaluation" />、 <see cref="T:System.Fabric.Health.NodesHealthEvaluation" />、 <see cref="T:System.Fabric.Health.UpgradeDomainNodesHealthEvaluation" />、 <see cref="T:System.Fabric.Health.SystemApplicationHealthEvaluation" /> oror<see cref="T:System.Fabric.Health.EventHealthEvaluation" />です。</span><span class="sxs-lookup"><span data-stu-id="ae683-130">The items in the list can be of the following types: <see cref="T:System.Fabric.Health.ApplicationsHealthEvaluation" />, <see cref="T:System.Fabric.Health.NodesHealthEvaluation" />, <see cref="T:System.Fabric.Health.UpgradeDomainNodesHealthEvaluation" />, <see cref="T:System.Fabric.Health.SystemApplicationHealthEvaluation" /> oror <see cref="T:System.Fabric.Health.EventHealthEvaluation" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.FabricUpgradeDescription UpgradeDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.FabricUpgradeDescription UpgradeDescription" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.UpgradeDescription" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDescription As FabricUpgradeDescription" />
      <MemberSignature Language="F#" Value="member this.UpgradeDescription : System.Fabric.Description.FabricUpgradeDescription" Usage="System.Fabric.FabricUpgradeProgress.UpgradeDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.FabricUpgradeDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ae683-131">現在のアップグレードの動作を記述するアップグレード パラメーターの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="ae683-131">Gets the upgrade parameter details that describe the behavior of the current upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ae683-132">アップグレード パラメーターの詳細を現在のアップグレードの動作を記述します。</span><span class="sxs-lookup"><span data-stu-id="ae683-132">The upgrade parameter details that describe the behavior of the current upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainProgressAtFailure">
      <MemberSignature Language="C#" Value="public System.Fabric.UpgradeDomainProgress UpgradeDomainProgressAtFailure { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.UpgradeDomainProgress UpgradeDomainProgressAtFailure" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.UpgradeDomainProgressAtFailure" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomainProgressAtFailure As UpgradeDomainProgress" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainProgressAtFailure : System.Fabric.UpgradeDomainProgress" Usage="System.Fabric.FabricUpgradeProgress.UpgradeDomainProgressAtFailure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeDomainProgress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="ae683-133">アップグレードに失敗した時点で、システムがどのようなアクションを実行しているがの構造化された情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="ae683-133">Gets structured information about what actions were being performed by the system at the moment of upgrade failure.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="ae683-134">アップグレードの進行状況の詳細。</span><span class="sxs-lookup"><span data-stu-id="ae683-134">The upgrade progress details.</span></span> <span data-ttu-id="ae683-135"><see cref="T:System.Fabric.UpgradeDomainProgress" /></span><span class="sxs-lookup"><span data-stu-id="ae683-135"><see cref="T:System.Fabric.UpgradeDomainProgress" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomains">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt; UpgradeDomains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class System.Fabric.UpgradeDomainStatus&gt; UpgradeDomains" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.UpgradeDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomains As ReadOnlyCollection(Of UpgradeDomainStatus)" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomains : System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;" Usage="System.Fabric.FabricUpgradeProgress.UpgradeDomains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ae683-136">アップグレード ドメインの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="ae683-136">Gets the list of upgrade domains.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ae683-137">アップグレード ドメインの一覧。</span><span class="sxs-lookup"><span data-stu-id="ae683-137">The list of upgrade domains.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDuration">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.UpgradeDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeDuration : TimeSpan" Usage="System.Fabric.FabricUpgradeProgress.UpgradeDuration" />
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
          <para><span data-ttu-id="ae683-138">取得される予測所要時間は、現在の全体的な処理に費やされたをアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="ae683-138">Gets the estimated elapsed time spent processing the current overall upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ae683-139">推定経過時間では、現在の全体的なアップグレードの処理に費やされました。</span><span class="sxs-lookup"><span data-stu-id="ae683-139">The estimated elapsed time spent processing the current overall upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeState">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricUpgradeState UpgradeState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.FabricUpgradeState UpgradeState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.UpgradeState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeState As FabricUpgradeState" />
      <MemberSignature Language="F#" Value="member this.UpgradeState : System.Fabric.FabricUpgradeState" Usage="System.Fabric.FabricUpgradeProgress.UpgradeState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricUpgradeState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ae683-140">このアップグレードのアップグレードの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="ae683-140">Gets the upgrade state for this  upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ae683-141">このアップグレードのアップグレード状態です。</span><span class="sxs-lookup"><span data-stu-id="ae683-141">The upgrade state for this  upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>