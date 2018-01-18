<Type Name="PartitionHealthQueryDescription" FullName="System.Fabric.Description.PartitionHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.PartitionHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type PartitionHealthQueryDescription = class" />
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
      <para><span data-ttu-id="57200-101">説明を取得するためのクエリ入力<see cref="T:System.Fabric.Health.PartitionHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="57200-101">Describes query input for getting <see cref="T:System.Fabric.Health.PartitionHealth" />.</span></span> <span data-ttu-id="57200-102"><see cref="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Fabric.Description.PartitionHealthQueryDescription)" /> で使用されます。</span><span class="sxs-lookup"><span data-stu-id="57200-102">Used by <see cref="M:System.Fabric.FabricClient.HealthClient.GetPartitionHealthAsync(System.Fabric.Description.PartitionHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionHealthQueryDescription (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.PartitionHealthQueryDescription.#ctor(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionId As Guid)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.PartitionHealthQueryDescription : Guid -&gt; System.Fabric.Description.PartitionHealthQueryDescription" Usage="new System.Fabric.Description.PartitionHealthQueryDescription partitionId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="57200-103">パーティションの識別子です。</span><span class="sxs-lookup"><span data-stu-id="57200-103">The partition identifier.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="57200-104"><see cref="T:System.Fabric.Description.PartitionHealthQueryDescription" /> クラスの新しいインスタンスを生成します。</span><span class="sxs-lookup"><span data-stu-id="57200-104">Instantiates a new instance of the <see cref="T:System.Fabric.Description.PartitionHealthQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PartitionHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.PartitionHealthQueryDescription.EventsFilter" />
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
          <para><span data-ttu-id="57200-105">取得または設定のコレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />パーティションに報告します。</span><span class="sxs-lookup"><span data-stu-id="57200-105">Gets or sets the filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the partition.</span></span> <span data-ttu-id="57200-106">フィルターに一致するイベントのみが返されます。</span><span class="sxs-lookup"><span data-stu-id="57200-106">Only events that match the filter will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="57200-107"><see cref="T:System.Fabric.Health.HealthEventsFilter" />返されるイベントをフィルター処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="57200-107">The <see cref="T:System.Fabric.Health.HealthEventsFilter" /> used to filter returned events.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="57200-108">フィルターに一致するイベントのみが返されます。</span><span class="sxs-lookup"><span data-stu-id="57200-108">Only events that match the filter will be returned.</span></span> <span data-ttu-id="57200-109">すべてのイベントは、パーティションの集計された正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="57200-109">All events will be used to evaluate the partition aggregated health state.</span></span>
            <span data-ttu-id="57200-110">フィルターが指定されていない場合は、すべてのイベントが返されます。</span><span class="sxs-lookup"><span data-stu-id="57200-110">If the filter is not specified, all events are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PartitionHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.PartitionHealthQueryDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="57200-111">取得または設定、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="57200-111">Gets or sets the <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="57200-112"><see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />パーティションの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="57200-112">The <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate partition health.</span></span></para>
        </value>
        <remarks><span data-ttu-id="57200-113">指定されていない場合、正常性ストアは、パーティションの正常性を評価する親アプリケーションのアプリケーションの正常性ポリシーを使用します。</span><span class="sxs-lookup"><span data-stu-id="57200-113">If not specified, the health store uses the application health policy of the parent application to evaluate the partition health.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.PartitionHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.PartitionHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PartitionHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As PartitionHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.PartitionHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.PartitionHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.PartitionHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="57200-114">取得または正常性の統計情報のフィルターを設定します。</span><span class="sxs-lookup"><span data-stu-id="57200-114">Gets or sets the health statistics filter.</span></span>
            </summary>
        <value><span data-ttu-id="57200-115">正常性の統計情報のフィルターです。</span><span class="sxs-lookup"><span data-stu-id="57200-115">The health statistics filter.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="57200-116">正常性の統計情報のフィルター コントロールかどうか、<see cref="T:System.Fabric.Health.PartitionHealth" />によって返される、クエリには、パーティションの正常性の統計情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="57200-116">The health statistics filter controls whether the <see cref="T:System.Fabric.Health.PartitionHealth" /> returned by the query contains the partition health statistics.</span></span> <span data-ttu-id="57200-117">指定しない場合、統計情報が含まれます。</span><span class="sxs-lookup"><span data-stu-id="57200-117">If not specified, the statistics are included.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PartitionHealthQueryDescription.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Description.PartitionHealthQueryDescription.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="57200-118">取得またはパーティションの識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="57200-118">Gets or sets the partition identifier.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="57200-119"><see cref="T:System.Guid" />パーティションの id を表すです。</span><span class="sxs-lookup"><span data-stu-id="57200-119">The <see cref="T:System.Guid" /> representing the partition identifier.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicasFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ReplicaHealthStatesFilter ReplicasFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ReplicaHealthStatesFilter ReplicasFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PartitionHealthQueryDescription.ReplicasFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicasFilter As ReplicaHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.ReplicasFilter : System.Fabric.Health.ReplicaHealthStatesFilter with get, set" Usage="System.Fabric.Description.PartitionHealthQueryDescription.ReplicasFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ReplicaHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="57200-120">フィルター設定を取得または<see cref="T:System.Fabric.Health.ReplicaHealthState" />子。</span><span class="sxs-lookup"><span data-stu-id="57200-120">Gets or sets the filter for <see cref="T:System.Fabric.Health.ReplicaHealthState" /> children.</span></span> <span data-ttu-id="57200-121">フィルターに一致する子のみが返されます。</span><span class="sxs-lookup"><span data-stu-id="57200-121">Only children that match the filter will be returned.</span></span> <span data-ttu-id="57200-122">すべての子は、パーティションの集計された正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="57200-122">All children will be used to evaluate the partition aggregated health state.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="57200-123"><see cref="T:System.Fabric.Health.ReplicaHealthStatesFilter" />返されたレプリカをフィルター処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="57200-123">The <see cref="T:System.Fabric.Health.ReplicaHealthStatesFilter" /> used to filter returned replicas.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="57200-124">フィルターに一致する子のみが返されます。</span><span class="sxs-lookup"><span data-stu-id="57200-124">Only children that match the filter will be returned.</span></span> <span data-ttu-id="57200-125">すべての子は、パーティションの集計された正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="57200-125">All children will be used to evaluate the partition aggregated health state.</span></span>
            <span data-ttu-id="57200-126">フィルターが指定されていない場合は、パーティションのすべての子が返されます。</span><span class="sxs-lookup"><span data-stu-id="57200-126">If the filter is not specified, all partition children are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.PartitionHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionHealthQueryDescription.ToString " />
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
            <span data-ttu-id="57200-127">正常性クエリの説明の文字列表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="57200-127">Gets a string representation of the health query description.</span></span>
            </summary>
        <returns><span data-ttu-id="57200-128">正常性クエリの説明の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="57200-128">A string representation of the health query description.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>