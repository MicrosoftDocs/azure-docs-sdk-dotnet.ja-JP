<Type Name="ClusterHealthQueryDescription" FullName="System.Fabric.Description.ClusterHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ClusterHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ClusterHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type ClusterHealthQueryDescription = class" />
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
      <para><span data-ttu-id="79a93-101">取得するためのクエリの入力を提供<see cref="T:System.Fabric.Health.ClusterHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="79a93-101">Provides query input for getting <see cref="T:System.Fabric.Health.ClusterHealth" />.</span></span> <span data-ttu-id="79a93-102"><see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" /> で使用されます。</span><span class="sxs-lookup"><span data-stu-id="79a93-102">Used by <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ClusterHealthQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="79a93-103"><see cref="T:System.Fabric.Description.ClusterHealthQueryDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="79a93-103">Initializes a new instance of the <see cref="T:System.Fabric.Description.ClusterHealthQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.ApplicationHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationHealthPolicyMap As ApplicationHealthPolicyMap" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthPolicyMap : System.Fabric.Health.ApplicationHealthPolicyMap" Usage="System.Fabric.Description.ClusterHealthQueryDescription.ApplicationHealthPolicyMap" />
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
          <para><span data-ttu-id="79a93-104">クラスターからのアプリケーションの正常性を評価するために使用するアプリケーションの正常性ポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="79a93-104">Gets the application health policies used to evaluate the health of the applications from the cluster.</span></span> <span data-ttu-id="79a93-105">各エントリは、アプリケーションの名前をキーとして、および値を指定します、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />アプリケーションの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="79a93-105">Each entry specifies as key the application name and as value an <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate the application health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="79a93-106">アプリケーションの正常性ポリシーは、クラスターからのアプリケーションの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="79a93-106">The application health policies used to evaluate the health of the applications from the cluster.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="79a93-107">マップでは、アプリケーションが指定されていない場合、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />見つかった評価のためのアプリケーションでマニフェストが使用されます。</span><span class="sxs-lookup"><span data-stu-id="79a93-107">If an application is not specified in the map, the <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> found in its application manifest will be used for evaluation.</span></span> <span data-ttu-id="79a93-108">マップは、既定では空です。</span><span class="sxs-lookup"><span data-stu-id="79a93-108">The map is empty by default.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthStatesFilter ApplicationsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthStatesFilter ApplicationsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.ApplicationsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationsFilter As ApplicationHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.ApplicationsFilter : System.Fabric.Health.ApplicationHealthStatesFilter with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.ApplicationsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="79a93-109">フィルター設定を取得または<see cref="T:System.Fabric.Health.ApplicationHealthState" />子。</span><span class="sxs-lookup"><span data-stu-id="79a93-109">Gets or sets the filter for <see cref="T:System.Fabric.Health.ApplicationHealthState" /> children.</span></span> <span data-ttu-id="79a93-110">フィルターに一致する子のみが返されます。</span><span class="sxs-lookup"><span data-stu-id="79a93-110">Only children that match the filter will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="79a93-111">フィルター<see cref="T:System.Fabric.Health.ApplicationHealthState" />子。</span><span class="sxs-lookup"><span data-stu-id="79a93-111">The filter for <see cref="T:System.Fabric.Health.ApplicationHealthState" /> children.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="79a93-112">フィルターに一致するアプリケーションのみが返されます。</span><span class="sxs-lookup"><span data-stu-id="79a93-112">Only applications that match the filter will be returned.</span></span> <span data-ttu-id="79a93-113">すべてのアプリケーションは、集計されたクラスターの正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="79a93-113">All applications will be used to evaluate the cluster aggregated health state.</span></span>
            <span data-ttu-id="79a93-114">フィルターが指定されていない場合は、クラスターのすべてのアプリケーションが返されます。</span><span class="sxs-lookup"><span data-stu-id="79a93-114">If the filter is not specified, all cluster applications are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.EventsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthEventsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="79a93-115">取得または設定のコレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />クラスターに報告します。</span><span class="sxs-lookup"><span data-stu-id="79a93-115">Gets or sets the filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the cluster.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="79a93-116">コレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />クラスターに報告します。</span><span class="sxs-lookup"><span data-stu-id="79a93-116">The filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the cluster.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="79a93-117">フィルターに一致するイベントのみが返されます。</span><span class="sxs-lookup"><span data-stu-id="79a93-117">Only events that match the filter will be returned.</span></span> <span data-ttu-id="79a93-118">すべてのイベントは、集計されたクラスターの正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="79a93-118">All events will be used to evaluate the cluster aggregated health state.</span></span>
            <span data-ttu-id="79a93-119">フィルターが指定されていない場合は、すべてのイベントが返されます。</span><span class="sxs-lookup"><span data-stu-id="79a93-119">If the filter is not specified, all events are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ClusterHealthPolicy with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.HealthPolicy" />
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
          <para><span data-ttu-id="79a93-120">取得または設定、<see cref="T:System.Fabric.Health.ClusterHealthPolicy" />クラスターの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="79a93-120">Gets or sets the <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> used to evaluate the cluster health.</span></span> <span data-ttu-id="79a93-121">ポリシーは、クラスターおよびノードの集計された正常性状態に報告されるイベントの集計された正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="79a93-121">The policy will be used to evaluate the aggregated health state of the events reported on cluster as well as the aggregated health states of the nodes.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="79a93-122"><see cref="T:System.Fabric.Health.ClusterHealthPolicy" />クラスターの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="79a93-122">The <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> used to evaluate the cluster health.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As ClusterHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.ClusterHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79a93-123">取得または正常性の統計情報のフィルターを設定します。</span><span class="sxs-lookup"><span data-stu-id="79a93-123">Gets or sets the health statistics filter.</span></span>
            </summary>
        <value><span data-ttu-id="79a93-124">正常性の統計情報のフィルターです。</span><span class="sxs-lookup"><span data-stu-id="79a93-124">The health statistics filter.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="79a93-125">正常性の統計情報のフィルター コントロールかどうか、<see cref="T:System.Fabric.Health.ClusterHealth" />によって返される、クエリには、クラスターの状態の統計が含まれています。</span><span class="sxs-lookup"><span data-stu-id="79a93-125">The health statistics filter controls whether the <see cref="T:System.Fabric.Health.ClusterHealth" /> returned by the query contains the cluster health statistics.</span></span> <span data-ttu-id="79a93-126">指定しない場合、統計情報が含まれます。</span><span class="sxs-lookup"><span data-stu-id="79a93-126">If not specified, the statistics are included.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodesFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.NodeHealthStatesFilter NodesFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.NodeHealthStatesFilter NodesFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.NodesFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property NodesFilter As NodeHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.NodesFilter : System.Fabric.Health.NodeHealthStatesFilter with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.NodesFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.NodeHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="79a93-127">フィルター設定を取得または<see cref="T:System.Fabric.Health.NodeHealthState" />子。</span><span class="sxs-lookup"><span data-stu-id="79a93-127">Gets or sets the filter for <see cref="T:System.Fabric.Health.NodeHealthState" /> children.</span></span> <span data-ttu-id="79a93-128">フィルターに一致する子のみが返されます。</span><span class="sxs-lookup"><span data-stu-id="79a93-128">Only children that match the filter will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="79a93-129">フィルター<see cref="T:System.Fabric.Health.NodeHealthState" />子。</span><span class="sxs-lookup"><span data-stu-id="79a93-129">The filter for <see cref="T:System.Fabric.Health.NodeHealthState" /> children.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="79a93-130">フィルターに一致するノードだけが返されます。</span><span class="sxs-lookup"><span data-stu-id="79a93-130">Only nodes that match the filter will be returned.</span></span> <span data-ttu-id="79a93-131">すべてのノードは、集計されたクラスターの正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="79a93-131">All nodes will be used to evaluate the cluster aggregated health state.</span></span>
            <span data-ttu-id="79a93-132">フィルターが指定されていない場合は、すべてのクラスター ノードが返されます。</span><span class="sxs-lookup"><span data-stu-id="79a93-132">If the filter is not specified, all cluster nodes are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ClusterHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterHealthQueryDescription.ToString " />
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
            <span data-ttu-id="79a93-133">正常性クエリの説明の文字列表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="79a93-133">Gets a string representation of the health query description.</span></span>
            </summary>
        <returns><span data-ttu-id="79a93-134">正常性クエリの説明の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="79a93-134">A string representation of the health query description.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>