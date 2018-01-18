<Type Name="ServiceHealthQueryDescription" FullName="System.Fabric.Description.ServiceHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type ServiceHealthQueryDescription = class" />
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
      <para><span data-ttu-id="44131-101">取得するためのクエリの入力を提供<see cref="T:System.Fabric.Health.ServiceHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="44131-101">Provides query input for getting <see cref="T:System.Fabric.Health.ServiceHealth" />.</span></span> <span data-ttu-id="44131-102"><see cref="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Fabric.Description.ServiceHealthQueryDescription)" /> で使用されます。</span><span class="sxs-lookup"><span data-stu-id="44131-102">Used by <see cref="M:System.Fabric.FabricClient.HealthClient.GetServiceHealthAsync(System.Fabric.Description.ServiceHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceHealthQueryDescription (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceHealthQueryDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serviceName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceHealthQueryDescription : Uri -&gt; System.Fabric.Description.ServiceHealthQueryDescription" Usage="new System.Fabric.Description.ServiceHealthQueryDescription serviceName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="44131-103">サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="44131-103">The service name.</span></span> <span data-ttu-id="44131-104">null にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="44131-104">Cannot be null.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="44131-105"><see cref="T:System.Fabric.Description.ServiceHealthQueryDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="44131-105">Initializes a new instance of the <see cref="T:System.Fabric.Description.ServiceHealthQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="44131-106">Null 値は、必須パラメーターに渡されました。</span><span class="sxs-lookup"><span data-stu-id="44131-106">A null value was passed in for a required parameter.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.ServiceHealthQueryDescription.EventsFilter" />
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
          <para><span data-ttu-id="44131-107">取得または設定のコレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />サービスに報告します。</span><span class="sxs-lookup"><span data-stu-id="44131-107">Gets or sets the filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the service.</span></span> <span data-ttu-id="44131-108">フィルターに一致するイベントのみが返されます。</span><span class="sxs-lookup"><span data-stu-id="44131-108">Only events that match the filter will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="44131-109"><see cref="T:System.Fabric.Health.HealthEventsFilter" />返されるイベントをフィルター処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="44131-109">The <see cref="T:System.Fabric.Health.HealthEventsFilter" /> used to filter returned events.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="44131-110">フィルターに一致するイベントのみが返されます。</span><span class="sxs-lookup"><span data-stu-id="44131-110">Only events that match the filter will be returned.</span></span> <span data-ttu-id="44131-111">すべてのイベントは、集計されたサービスのヘルス状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="44131-111">All events will be used to evaluate the service aggregated health state.</span></span>
            <span data-ttu-id="44131-112">フィルターが指定されていない場合は、すべてのイベントが返されます。</span><span class="sxs-lookup"><span data-stu-id="44131-112">If the filter is not specified, all events are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.ServiceHealthQueryDescription.HealthPolicy" />
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
          <para><span data-ttu-id="44131-113">取得または設定、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="44131-113">Gets or sets the <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="44131-114"><see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="44131-114">The <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate health.</span></span></para>
        </value>
        <remarks><span data-ttu-id="44131-115">指定されていない場合、正常性ストアは、サービスの正常性を評価する親アプリケーションのアプリケーションの正常性ポリシーを使用します。</span><span class="sxs-lookup"><span data-stu-id="44131-115">If not specified, the health store uses the application health policy of the parent application to evaluate the service health.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ServiceHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ServiceHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As ServiceHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.ServiceHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.ServiceHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ServiceHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44131-116">取得または正常性の統計情報のフィルターを設定します。</span><span class="sxs-lookup"><span data-stu-id="44131-116">Gets or sets the health statistics filter.</span></span>
            </summary>
        <value><span data-ttu-id="44131-117">正常性の統計情報のフィルターです。</span><span class="sxs-lookup"><span data-stu-id="44131-117">The health statistics filter.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="44131-118">正常性の統計情報のフィルター コントロールかどうか、<see cref="T:System.Fabric.Health.ServiceHealth" />によって返されるサービスの状態の統計がクエリに含まれています。</span><span class="sxs-lookup"><span data-stu-id="44131-118">The health statistics filter controls whether the <see cref="T:System.Fabric.Health.ServiceHealth" /> returned by the query contains the service health statistics.</span></span> <span data-ttu-id="44131-119">指定しない場合、統計情報が含まれます。</span><span class="sxs-lookup"><span data-stu-id="44131-119">If not specified, the statistics are included.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.PartitionHealthStatesFilter PartitionsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.PartitionHealthStatesFilter PartitionsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceHealthQueryDescription.PartitionsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionsFilter As PartitionHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.PartitionsFilter : System.Fabric.Health.PartitionHealthStatesFilter with get, set" Usage="System.Fabric.Description.ServiceHealthQueryDescription.PartitionsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.PartitionHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="44131-120">フィルター設定を取得または<see cref="T:System.Fabric.Health.PartitionHealthState" />子。</span><span class="sxs-lookup"><span data-stu-id="44131-120">Gets or sets the filter for <see cref="T:System.Fabric.Health.PartitionHealthState" /> children.</span></span> <span data-ttu-id="44131-121">フィルターに一致する子のみが返されます。</span><span class="sxs-lookup"><span data-stu-id="44131-121">Only children that match the filter will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="44131-122"><see cref="T:System.Fabric.Health.PartitionHealthStatesFilter" />返されるパーティションの正常性状態をフィルター処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="44131-122">The <see cref="T:System.Fabric.Health.PartitionHealthStatesFilter" /> used to filter returned partition health states.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="44131-123">フィルターに一致する子のみが返されます。</span><span class="sxs-lookup"><span data-stu-id="44131-123">Only children that match the filter will be returned.</span></span> <span data-ttu-id="44131-124">すべての子は、集計されたサービスのヘルス状態を評価する使用されます。</span><span class="sxs-lookup"><span data-stu-id="44131-124">All children will be used to evaluate the service aggregated health state.</span></span>
            <span data-ttu-id="44131-125">フィルターが指定されていない場合は、パーティションのすべての子が返されます。</span><span class="sxs-lookup"><span data-stu-id="44131-125">If the filter is not specified, all partition children are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceHealthQueryDescription.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Description.ServiceHealthQueryDescription.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="44131-126">取得、<see cref="T:System.Uri" />サービス名。</span><span class="sxs-lookup"><span data-stu-id="44131-126">Gets the <see cref="T:System.Uri" /> of the service name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="44131-127"><see cref="T:System.Uri" />サービス名。</span><span class="sxs-lookup"><span data-stu-id="44131-127">The <see cref="T:System.Uri" /> of the service name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceHealthQueryDescription.ToString " />
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
            <span data-ttu-id="44131-128">正常性クエリの説明の文字列表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="44131-128">Gets a string representation of the health query description.</span></span>
            </summary>
        <returns><span data-ttu-id="44131-129">正常性クエリの説明の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="44131-129">A string representation of the health query description.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>