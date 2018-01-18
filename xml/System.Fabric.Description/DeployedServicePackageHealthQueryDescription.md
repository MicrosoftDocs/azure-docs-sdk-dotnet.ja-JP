<Type Name="DeployedServicePackageHealthQueryDescription" FullName="System.Fabric.Description.DeployedServicePackageHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.DeployedServicePackageHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthQueryDescription = class" />
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
      <para><span data-ttu-id="5533a-101">説明を取得するクエリの入力<see cref="T:System.Fabric.Health.DeployedServicePackageHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="5533a-101">Describes the query input for getting <see cref="T:System.Fabric.Health.DeployedServicePackageHealth" />.</span></span> <span data-ttu-id="5533a-102"><see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Fabric.Description.DeployedServicePackageHealthQueryDescription)" /> で使用されます。</span><span class="sxs-lookup"><span data-stu-id="5533a-102">Used by <see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Fabric.Description.DeployedServicePackageHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthQueryDescription (Uri applicationName, string nodeName, string serviceManifestName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string nodeName, string serviceManifestName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.#ctor(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, nodeName As String, serviceManifestName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.DeployedServicePackageHealthQueryDescription : Uri * string * string -&gt; System.Fabric.Description.DeployedServicePackageHealthQueryDescription" Usage="new System.Fabric.Description.DeployedServicePackageHealthQueryDescription (applicationName, nodeName, serviceManifestName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="5533a-103">アプリケーション名。</span><span class="sxs-lookup"><span data-stu-id="5533a-103">The application name.</span></span> <span data-ttu-id="5533a-104">null にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="5533a-104">Cannot be null.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="5533a-105">ノード名。</span><span class="sxs-lookup"><span data-stu-id="5533a-105">The node name.</span></span> <span data-ttu-id="5533a-106">null または空にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="5533a-106">Cannot be null or empty.</span></span></para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="5533a-107">サービス マニフェスト名です。</span><span class="sxs-lookup"><span data-stu-id="5533a-107">The service manifest name.</span></span> <span data-ttu-id="5533a-108">null または空にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="5533a-108">Cannot be null or empty.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5533a-109">インスタンスを作成、<see cref="T:System.Fabric.Description.DeployedServicePackageHealthQueryDescription" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="5533a-109">Instantiates a <see cref="T:System.Fabric.Description.DeployedServicePackageHealthQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="5533a-110">必須のパラメーターを null にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="5533a-110">A required parameter can't be null.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="5533a-111">必須のパラメーターを空にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="5533a-111">A required parameter can't be empty.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthQueryDescription (Uri applicationName, string nodeName, string serviceManifestName, string servicePackageActivationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string nodeName, string serviceManifestName, string servicePackageActivationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.#ctor(System.Uri,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, nodeName As String, serviceManifestName As String, servicePackageActivationId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.DeployedServicePackageHealthQueryDescription : Uri * string * string * string -&gt; System.Fabric.Description.DeployedServicePackageHealthQueryDescription" Usage="new System.Fabric.Description.DeployedServicePackageHealthQueryDescription (applicationName, nodeName, serviceManifestName, servicePackageActivationId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="5533a-112">アプリケーション名。</span><span class="sxs-lookup"><span data-stu-id="5533a-112">The application name.</span></span> <span data-ttu-id="5533a-113">null にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="5533a-113">Cannot be null.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="5533a-114">ノード名。</span><span class="sxs-lookup"><span data-stu-id="5533a-114">The node name.</span></span> <span data-ttu-id="5533a-115">null または空にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="5533a-115">Cannot be null or empty.</span></span></para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="5533a-116">サービス マニフェスト名です。</span><span class="sxs-lookup"><span data-stu-id="5533a-116">The service manifest name.</span></span> <span data-ttu-id="5533a-117">null または空にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="5533a-117">Cannot be null or empty.</span></span></para>
        </param>
        <param name="servicePackageActivationId">
          <para>
            <span data-ttu-id="5533a-118"><see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />展開済みサービス パッケージのです。</span><span class="sxs-lookup"><span data-stu-id="5533a-118">The <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package.</span></span>
            <span data-ttu-id="5533a-119">使用して取得できます、展開済みサービス パッケージの ServicePackageActivationId<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />クエリ。</span><span class="sxs-lookup"><span data-stu-id="5533a-119">ServicePackageActivationId of a deployed service package can obtained by using <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> query.</span></span> 
            </para>
          <para>
            <span data-ttu-id="5533a-120">場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービスの作成時に指定した<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(が指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。</span><span class="sxs-lookup"><span data-stu-id="5533a-120">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service is <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it is not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="5533a-121">詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。</span><span class="sxs-lookup"><span data-stu-id="5533a-121">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </param>
        <summary>
          <para><span data-ttu-id="5533a-122">インスタンスを作成、<see cref="T:System.Fabric.Description.DeployedServicePackageHealthQueryDescription" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="5533a-122">Instantiates a <see cref="T:System.Fabric.Description.DeployedServicePackageHealthQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="5533a-123">必須のパラメーターを null にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="5533a-123">A required parameter can't be null.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="5533a-124">必須のパラメーターを空にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="5533a-124">A required parameter can't be empty.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" />
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
          <para><span data-ttu-id="5533a-125">アプリケーションの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="5533a-125">Gets the name of the application.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5533a-126">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="5533a-126">The name of the application.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.EventsFilter" />
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
          <para><span data-ttu-id="5533a-127">取得または設定のコレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />展開済みサービス パッケージに報告します。</span><span class="sxs-lookup"><span data-stu-id="5533a-127">Gets or sets the filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the deployed service package.</span></span> <span data-ttu-id="5533a-128">フィルターに一致するイベントのみが返されます。</span><span class="sxs-lookup"><span data-stu-id="5533a-128">Only events that match the filter will be returned.</span></span> <span data-ttu-id="5533a-129">すべてのイベントは、集計された正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="5533a-129">All events will be used to evaluate the aggregated health state.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5533a-130"><see cref="T:System.Fabric.Health.HealthEventsFilter" />返されるイベントをフィルター処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="5533a-130">The <see cref="T:System.Fabric.Health.HealthEventsFilter" /> used to filter returned events.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="5533a-131">フィルターに一致するイベントのみが返されます。</span><span class="sxs-lookup"><span data-stu-id="5533a-131">Only events that match the filter will be returned.</span></span> <span data-ttu-id="5533a-132">すべてのイベントは、エンティティで集計された正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="5533a-132">All events will be used to evaluate the entity aggregated health state.</span></span>
            <span data-ttu-id="5533a-133">フィルターが指定されていない場合は、すべてのイベントが返されます。</span><span class="sxs-lookup"><span data-stu-id="5533a-133">If the filter is not specified, all events are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.HealthPolicy" />
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
          <para><span data-ttu-id="5533a-134">取得または設定、<see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="5533a-134">Gets or sets the <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate the health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5533a-135"><see cref="T:System.Fabric.Health.ApplicationHealthPolicy" />正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="5533a-135">The <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate health.</span></span></para>
        </value>
        <remarks><span data-ttu-id="5533a-136">指定されていない場合、正常性ストアは、展開済みサービス パッケージの正常性を評価する親アプリケーションのアプリケーションの正常性ポリシーを使用します。</span><span class="sxs-lookup"><span data-stu-id="5533a-136">If not specified, the health store uses the application health policy of the parent application to evaluate the deployed service package health.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.NodeName" />
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
          <para><span data-ttu-id="5533a-137">ノード名を取得します。</span><span class="sxs-lookup"><span data-stu-id="5533a-137">Gets the node name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5533a-138"><see cref="T:System.String" />ノード名を表すです。</span><span class="sxs-lookup"><span data-stu-id="5533a-138">The <see cref="T:System.String" /> representing the node name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ServiceManifestName" />
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
          <para><span data-ttu-id="5533a-139">サービス マニフェスト名を取得します。</span><span class="sxs-lookup"><span data-stu-id="5533a-139">Gets the service manifest name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5533a-140"><see cref="T:System.String" />サービス マニフェスト名を表すです。</span><span class="sxs-lookup"><span data-stu-id="5533a-140">The <see cref="T:System.String" /> representing the service manifest name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ServicePackageActivationId" />
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
            <span data-ttu-id="5533a-141">サービス パッケージの ActivationId を取得します。</span><span class="sxs-lookup"><span data-stu-id="5533a-141">Gets the ActivationId of the service package.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="5533a-142"><see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />展開済みサービス パッケージのです。</span><span class="sxs-lookup"><span data-stu-id="5533a-142">The <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package.</span></span> <span data-ttu-id="5533a-143">使用して取得できます、展開済みサービス パッケージの ServicePackageActivationId<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />クエリ。</span><span class="sxs-lookup"><span data-stu-id="5533a-143">ServicePackageActivationId of a deployed service package can obtained by using <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> query.</span></span> 
            </para>
          <para>
            <span data-ttu-id="5533a-144">場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービスの作成時に指定した<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(が指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。</span><span class="sxs-lookup"><span data-stu-id="5533a-144">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service is <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it is not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="5533a-145">詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。</span><span class="sxs-lookup"><span data-stu-id="5533a-145">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span> 
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedServicePackageHealthQueryDescription.ToString " />
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
            <span data-ttu-id="5533a-146">正常性クエリの説明の文字列表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="5533a-146">Gets a string representation of the health query description.</span></span>
            </summary>
        <returns><span data-ttu-id="5533a-147">正常性クエリの説明の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="5533a-147">A string representation of the health query description.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>