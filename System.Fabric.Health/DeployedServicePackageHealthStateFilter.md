<Type Name="DeployedServicePackageHealthStateFilter" FullName="System.Fabric.Health.DeployedServicePackageHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealthStateFilter" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthStateFilter = class" />
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
            <span data-ttu-id="f62e9-101">フィルター処理<see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f62e9-101">Filter for <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> objects.</span></span>
            </summary>
    <remarks><span data-ttu-id="f62e9-102">正常性の状態のチャンクのクエリでは、粒度が細かいに展開済みサービス パッケージ フィルターの一覧クエリ結果に含める必要がある展開済みサービス パッケージの選択を指定できます。</span><span class="sxs-lookup"><span data-stu-id="f62e9-102">The health state chunk queries can specify a list of deployed service package filters to fine-grain select the deployed service packages that should be included in the query result.</span></span>
            <span data-ttu-id="f62e9-103">渡されるフィルターに関係なく、正常性状態を集計すべて展開済みサービス パッケージが親の評価に使用されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="f62e9-103">Note that all the deployed service packages are used to evaluate parents aggregated health state, regardless of the filter passed in.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f62e9-104"><see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f62e9-104">Initializes a new instance of the <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStateFilter.HealthStateFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStateFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f62e9-105">取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="f62e9-105">Gets or sets filter for the aggregated health state of the <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="f62e9-106">集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="f62e9-106">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> entries in the collection.</span></span></value>
        <remarks><span data-ttu-id="f62e9-107">ヘルス状態フィルター値はメンバーまたはのメンバーのビットごとの組み合わせから取得<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="f62e9-107">The health state filter value comes from members or bitwise combination of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span> <span data-ttu-id="f62e9-108">展開済みサービス パッケージ フィルターに一致するには、集計された正常性状態は、指定したヘルス状態のフィルターで一致しなければなりません。</span><span class="sxs-lookup"><span data-stu-id="f62e9-108">For a deployed service package to match the filter, its aggregated health state must match the specified health state filter.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestNameFilter">
      <MemberSignature Language="C#" Value="public string ServiceManifestNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateFilter.ServiceManifestNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceManifestNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestNameFilter : string with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStateFilter.ServiceManifestNameFilter" />
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
            <span data-ttu-id="f62e9-109">取得またはサービス マニフェスト名のフィルターを設定します。</span><span class="sxs-lookup"><span data-stu-id="f62e9-109">Gets or sets the service manifest name filter.</span></span>
            </summary>
        <value><span data-ttu-id="f62e9-110">サービス マニフェスト名のフィルターです。</span><span class="sxs-lookup"><span data-stu-id="f62e9-110">The service manifest name filter.</span></span></value>
        <remarks><span data-ttu-id="f62e9-111">いない場合は、すべてが指定すると、(存在する場合)、親フィルターに一致するサービス パッケージを配置し、指定したヘルス状態のフィルターはフィルターに一致します。</span><span class="sxs-lookup"><span data-stu-id="f62e9-111">If not specified, all deployed service packages that match the parent filters (if any) and the specified health state filters match the filter.</span></span>
            <span data-ttu-id="f62e9-112">それ以外の場合、フィルターは、指定したサービス マニフェスト名を展開済みサービス パッケージにのみ適用され、それと一致するヘルス状態のフィルター。</span><span class="sxs-lookup"><span data-stu-id="f62e9-112">Otherwise, the filter only applies to the deployed service package for the specified service manifest name and the health state filter will be matched against it.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationIdFilter">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationIdFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationIdFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateFilter.ServicePackageActivationIdFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePackageActivationIdFilter As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationIdFilter : string with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStateFilter.ServicePackageActivationIdFilter" />
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
            <span data-ttu-id="f62e9-113">取得またはサービス パッケージ ActivationId フィルターを設定します。</span><span class="sxs-lookup"><span data-stu-id="f62e9-113">Gets or sets the service package ActivationId filter.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="f62e9-114"><see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />展開済みサービスのパッケージを使用して取得できます<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />クエリ。</span><span class="sxs-lookup"><span data-stu-id="f62e9-114">The <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package can be obtained by using <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> query.</span></span> 
             </para>
          <para>
            <span data-ttu-id="f62e9-115">場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />の作成時に指定された、サービスは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。</span><span class="sxs-lookup"><span data-stu-id="f62e9-115">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service was <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it was not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="f62e9-116">詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。</span><span class="sxs-lookup"><span data-stu-id="f62e9-116">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedServicePackageHealthStateFilter.ToString " />
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
            <span data-ttu-id="f62e9-117">フィルターの文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="f62e9-117">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="f62e9-118">フィルターの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="f62e9-118">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>