<Type Name="DeployedApplicationHealthQueryDescription" FullName="System.Fabric.Description.DeployedApplicationHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.DeployedApplicationHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthQueryDescription = class" />
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
      <para><span data-ttu-id="8c170-101">説明を取得するためのクエリ入力<see cref="T:System.Fabric.Health.DeployedApplicationHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="8c170-101">Describes query input for getting <see cref="T:System.Fabric.Health.DeployedApplicationHealth" />.</span></span> <span data-ttu-id="8c170-102"><see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Fabric.Description.DeployedApplicationHealthQueryDescription)" /> で使用されます。</span><span class="sxs-lookup"><span data-stu-id="8c170-102">Used by <see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Fabric.Description.DeployedApplicationHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedApplicationHealthQueryDescription (Uri applicationName, string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedApplicationHealthQueryDescription.#ctor(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, nodeName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.DeployedApplicationHealthQueryDescription : Uri * string -&gt; System.Fabric.Description.DeployedApplicationHealthQueryDescription" Usage="new System.Fabric.Description.DeployedApplicationHealthQueryDescription (applicationName, nodeName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="8c170-103">アプリケーション名。</span><span class="sxs-lookup"><span data-stu-id="8c170-103">The application name.</span></span> <span data-ttu-id="8c170-104">null にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="8c170-104">Cannot be null.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="8c170-105">ノード名。</span><span class="sxs-lookup"><span data-stu-id="8c170-105">The node name.</span></span> <span data-ttu-id="8c170-106">null または空にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="8c170-106">Cannot be null or empty.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="8c170-107"><see cref="T:System.Fabric.Description.DeployedApplicationHealthQueryDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8c170-107">Initializes a new instance of the <see cref="T:System.Fabric.Description.DeployedApplicationHealthQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="8c170-108">必須のパラメーターを null にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="8c170-108">A required parameter can’t be null.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="8c170-109">必須のパラメーターを空にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="8c170-109">A required parameter can't be empty.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" />
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
          <para><span data-ttu-id="8c170-110">アプリケーションの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="8c170-110">Gets the name of the application.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8c170-111">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="8c170-111">The name of the application.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedServicePackagesFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedServicePackageHealthStatesFilter DeployedServicePackagesFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedServicePackageHealthStatesFilter DeployedServicePackagesFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.DeployedServicePackagesFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property DeployedServicePackagesFilter As DeployedServicePackageHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.DeployedServicePackagesFilter : System.Fabric.Health.DeployedServicePackageHealthStatesFilter with get, set" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.DeployedServicePackagesFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedServicePackageHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8c170-112">フィルター設定を取得または<see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" />子。</span><span class="sxs-lookup"><span data-stu-id="8c170-112">Gets or sets the filter for <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> children.</span></span> <span data-ttu-id="8c170-113">フィルターに一致する子のみが返されます。</span><span class="sxs-lookup"><span data-stu-id="8c170-113">Only children that match the filter will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8c170-114"><see cref="T:System.Fabric.Health.DeployedServicePackageHealthStatesFilter" />返された展開済みサービス パッケージをフィルター処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="8c170-114">The <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStatesFilter" /> used to filter returned deployed service packages.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="8c170-115">フィルターに一致する子のみが返されます。</span><span class="sxs-lookup"><span data-stu-id="8c170-115">Only children that match the filter will be returned.</span></span> <span data-ttu-id="8c170-116">すべての子は、展開されたアプリケーションで集計された正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="8c170-116">All children will be used to evaluate the deployed application aggregated health state.</span></span>
            <span data-ttu-id="8c170-117">フィルターが指定されていない場合は、展開済みアプリケーションの展開済みサービス パッケージのすべての子が返されます。</span><span class="sxs-lookup"><span data-stu-id="8c170-117">If the filter is not specified, all deployed service package children of the deployed application are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.EventsFilter" />
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
          <para><span data-ttu-id="8c170-118">取得または設定のコレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />配置したアプリケーションで報告します。</span><span class="sxs-lookup"><span data-stu-id="8c170-118">Gets or sets the filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the deployed application.</span></span> <span data-ttu-id="8c170-119">フィルターに一致するイベントのみが返されます。</span><span class="sxs-lookup"><span data-stu-id="8c170-119">Only events that match the filter will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8c170-120"><see cref="T:System.Fabric.Health.HealthEventsFilter" />返されるイベントをフィルター処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="8c170-120">The <see cref="T:System.Fabric.Health.HealthEventsFilter" /> used to filter returned events.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="8c170-121">フィルターに一致するイベントのみが返されます。</span><span class="sxs-lookup"><span data-stu-id="8c170-121">Only events that match the filter will be returned.</span></span> <span data-ttu-id="8c170-122">すべてのイベントは、アプリケーションで集計された正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="8c170-122">All events will be used to evaluate the application aggregated health state.</span></span>
            <span data-ttu-id="8c170-123">フィルターが指定されていない場合は、すべてのイベントが返されます。</span><span class="sxs-lookup"><span data-stu-id="8c170-123">If the filter is not specified, all events are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.HealthPolicy" />
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
          <para><span data-ttu-id="8c170-124">取得または設定、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />展開済みアプリケーションの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="8c170-124">Gets or sets the <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate the deployed application health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8c170-125"><see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="8c170-125">The <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate health.</span></span></para>
        </value>
        <remarks><span data-ttu-id="8c170-126">指定しない場合、正常性ストアは、アプリケーションの正常性ポリシーまたは親アプリケーション、展開されたアプリケーションを評価します。</span><span class="sxs-lookup"><span data-stu-id="8c170-126">If not specified, the health store uses the application health policy or the parent application to evaluate the deployed application.</span></span>
            <span data-ttu-id="8c170-127">アプリケーションの正常性ポリシーは、アプリケーション マニフェストで指定されます。</span><span class="sxs-lookup"><span data-stu-id="8c170-127">The application health policy is specified in the application manifest.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedApplicationHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedApplicationHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As DeployedApplicationHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.DeployedApplicationHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedApplicationHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8c170-128">取得または正常性の統計情報のフィルターを設定します。</span><span class="sxs-lookup"><span data-stu-id="8c170-128">Gets or sets the health statistics filter.</span></span>
            </summary>
        <value><span data-ttu-id="8c170-129">正常性の統計情報のフィルターです。</span><span class="sxs-lookup"><span data-stu-id="8c170-129">The health statistics filter.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="8c170-130">正常性の統計情報のフィルター コントロールかどうか、<see cref="T:System.Fabric.Health.DeployedApplicationHealth" />によって返される、クエリには、展開済みアプリケーション正常性の統計情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="8c170-130">The health statistics filter controls whether the <see cref="T:System.Fabric.Health.DeployedApplicationHealth" /> returned by the query contains the deployed application health statistics.</span></span> <span data-ttu-id="8c170-131">指定しない場合、統計情報が含まれます。</span><span class="sxs-lookup"><span data-stu-id="8c170-131">If not specified, the statistics are included.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.NodeName" />
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
          <para><span data-ttu-id="8c170-132">ノード名を取得します。</span><span class="sxs-lookup"><span data-stu-id="8c170-132">Gets the node name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8c170-133">ノード名。</span><span class="sxs-lookup"><span data-stu-id="8c170-133">The node name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedApplicationHealthQueryDescription.ToString " />
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
            <span data-ttu-id="8c170-134">正常性クエリの説明の文字列表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="8c170-134">Gets a string representation of the health query description.</span></span>
            </summary>
        <returns><span data-ttu-id="8c170-135">正常性クエリの説明の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="8c170-135">A string representation of the health query description.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>