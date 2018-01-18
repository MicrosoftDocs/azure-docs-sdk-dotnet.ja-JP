<Type Name="ApplicationHealthQueryDescription" FullName="System.Fabric.Description.ApplicationHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type ApplicationHealthQueryDescription = class" />
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
      <para><span data-ttu-id="ecbd6-101">アプリケーションの正常性を取得するためのクエリの入力を表します。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-101">Represents the query input for getting application health.</span></span> <span data-ttu-id="ecbd6-102"><see cref="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription)" /> で使用されます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-102">Used by <see cref="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationHealthQueryDescription (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationHealthQueryDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationHealthQueryDescription : Uri -&gt; System.Fabric.Description.ApplicationHealthQueryDescription" Usage="new System.Fabric.Description.ApplicationHealthQueryDescription applicationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="ecbd6-103">アプリケーション名。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-103">The application name.</span></span> <span data-ttu-id="ecbd6-104">ことはできません<languageKeyword>null</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-104">Cannot be <languageKeyword>null</languageKeyword>.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="ecbd6-105"><see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-105">Initializes a new instance of the <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="ecbd6-106">Null 値は、必須パラメーターに渡されました。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-106">A null value was passed in for a required parameter.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" />
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
          <para><span data-ttu-id="ecbd6-107">アプリケーションの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-107">Gets the name of the application.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ecbd6-108">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-108">The name of the application.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedApplicationsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedApplicationHealthStatesFilter DeployedApplicationsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedApplicationHealthStatesFilter DeployedApplicationsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.DeployedApplicationsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property DeployedApplicationsFilter As DeployedApplicationHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.DeployedApplicationsFilter : System.Fabric.Health.DeployedApplicationHealthStatesFilter with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.DeployedApplicationsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedApplicationHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ecbd6-109">フィルター設定を取得または<see cref="T:System.Fabric.Health.DeployedApplicationHealthState" />子。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-109">Gets or sets the filter for <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> children.</span></span> <span data-ttu-id="ecbd6-110">フィルターに一致する子のみが返されます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-110">Only children that match the filter will be returned.</span></span> <span data-ttu-id="ecbd6-111">すべての子は、アプリケーションで集計された正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-111">All children will be used to evaluate the application aggregated health state.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ecbd6-112">フィルター<see cref="T:System.Fabric.Health.DeployedApplicationHealthStatesFilter" />子。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-112">The filter for <see cref="T:System.Fabric.Health.DeployedApplicationHealthStatesFilter" /> children.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="ecbd6-113">フィルターに一致する子のみが返されます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-113">Only children that match the filter will be returned.</span></span> <span data-ttu-id="ecbd6-114">すべての子は、アプリケーションで集計された正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-114">All children will be used to evaluate the application aggregated health state.</span></span>
            <span data-ttu-id="ecbd6-115">フィルターが指定されていない場合は、アプリケーションの展開済みアプリケーションのすべての子が返されます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-115">If the filter is not specified, all deployed application children of the application are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.EventsFilter" />
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
          <para><span data-ttu-id="ecbd6-116">取得または設定のコレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />のアプリケーションに報告します。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-116">Gets or sets the filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the application.</span></span> <span data-ttu-id="ecbd6-117">フィルターに一致するイベントのみが返されます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-117">Only events that match the filter will be returned.</span></span> <span data-ttu-id="ecbd6-118">すべてのイベントは、アプリケーションで集計された正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-118">All events will be used to evaluate the application aggregated health state.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ecbd6-119">コレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />のアプリケーションに報告します。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-119">The filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the application.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="ecbd6-120">フィルターに一致するイベントのみが返されます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-120">Only events that match the filter will be returned.</span></span> <span data-ttu-id="ecbd6-121">すべてのイベントは、アプリケーションで集計された正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-121">All events will be used to evaluate the application aggregated health state.</span></span>
            <span data-ttu-id="ecbd6-122">フィルターが指定されていない場合は、すべてのイベントが返されます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-122">If the filter is not specified, all events are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.HealthPolicy" />
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
          <para><span data-ttu-id="ecbd6-123">取得または設定、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />アプリケーションの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-123">Gets or sets the <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate the application health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ecbd6-124"><see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />アプリケーションの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-124">The <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate application health.</span></span></para>
        </value>
        <remarks><span data-ttu-id="ecbd6-125">指定しない場合、正常性ストアは、アプリケーションを評価する、アプリケーション マニフェストで指定されたアプリケーションの正常性ポリシーを使用します。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-125">If not specified, the health store uses the application health policy specified in the application manifest to evaluate the application.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As ApplicationHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.ApplicationHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ecbd6-126">取得または正常性の統計情報のフィルターを設定します。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-126">Gets or sets the health statistics filter.</span></span>
            </summary>
        <value><span data-ttu-id="ecbd6-127">正常性の統計情報のフィルターです。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-127">The health statistics filter.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="ecbd6-128">正常性の統計情報のフィルター コントロールかどうか、<see cref="T:System.Fabric.Health.ApplicationHealth" />によって返される、クエリには、アプリケーションの正常性の統計情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-128">The health statistics filter controls whether the <see cref="T:System.Fabric.Health.ApplicationHealth" /> returned by the query contains the application health statistics.</span></span> <span data-ttu-id="ecbd6-129">指定しない場合、統計情報が含まれます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-129">If not specified, the statistics are included.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicesFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ServiceHealthStatesFilter ServicesFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ServiceHealthStatesFilter ServicesFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.ServicesFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicesFilter As ServiceHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.ServicesFilter : System.Fabric.Health.ServiceHealthStatesFilter with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.ServicesFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ServiceHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ecbd6-130">フィルター設定を取得または<see cref="T:System.Fabric.Health.ServiceHealthState" />子。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-130">Gets or sets the filter for <see cref="T:System.Fabric.Health.ServiceHealthState" /> children.</span></span> <span data-ttu-id="ecbd6-131">フィルターに一致する子のみが返されます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-131">Only children that match the filter will be returned.</span></span> <span data-ttu-id="ecbd6-132">すべての子は、アプリケーションで集計された正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-132">All children will be used to evaluate the application aggregated health state.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ecbd6-133">フィルター<see cref="T:System.Fabric.Health.ServiceHealthState" />子。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-133">The filter for <see cref="T:System.Fabric.Health.ServiceHealthState" /> children.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="ecbd6-134">フィルターに一致する子のみが返されます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-134">Only children that match the filter will be returned.</span></span> <span data-ttu-id="ecbd6-135">すべての子は、アプリケーションで集計された正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-135">All children will be used to evaluate the application aggregated health state.</span></span>
            <span data-ttu-id="ecbd6-136">フィルターが指定されていない場合は、アプリケーションのサービスのすべての子が返されます。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-136">If the filter is not specified, all service children of the application are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthQueryDescription.ToString " />
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
            <span data-ttu-id="ecbd6-137">正常性クエリの説明の文字列表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-137">Gets a string representation of the health query description.</span></span>
            </summary>
        <returns><span data-ttu-id="ecbd6-138">正常性クエリの説明の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="ecbd6-138">A string representation of the health query description.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>