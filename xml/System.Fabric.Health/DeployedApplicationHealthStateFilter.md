<Type Name="DeployedApplicationHealthStateFilter" FullName="System.Fabric.Health.DeployedApplicationHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedApplicationHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealthStateFilter" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthStateFilter = class" />
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
            <span data-ttu-id="ae93b-101">フィルター処理<see cref="T:System.Fabric.Health.DeployedApplicationHealthState" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ae93b-101">Filter for <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> objects.</span></span>
            </summary>
    <remarks><span data-ttu-id="ae93b-102">正常性の状態のチャンクのクエリでは、粒度が細かいに展開済みアプリケーション フィルターの一覧クエリ結果に含める必要がある配置済みアプリケーションの選択を指定できます。</span><span class="sxs-lookup"><span data-stu-id="ae93b-102">The health state chunk queries can specify a list of deployed application filters to fine-grain select the deployed applications that should be included in the query result.</span></span>
            <span data-ttu-id="ae93b-103">渡されるフィルターに関係なく、正常性状態を集計すべて配置されているアプリケーションは、親の評価に使用されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="ae93b-103">Note that all the deployed applications are used to evaluate parents' aggregated health state, regardless of the filter passed in.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedApplicationHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ae93b-104"><see cref="T:System.Fabric.Health.DeployedApplicationHealthStateFilter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ae93b-104">Initializes a new instance of the <see cref="T:System.Fabric.Health.DeployedApplicationHealthStateFilter" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedServicePackageFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthStateFilter&gt; DeployedServicePackageFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.DeployedServicePackageHealthStateFilter&gt; DeployedServicePackageFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateFilter.DeployedServicePackageFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedServicePackageFilters As IList(Of DeployedServicePackageHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.DeployedServicePackageFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthStateFilter&gt;" Usage="System.Fabric.Health.DeployedApplicationHealthStateFilter.DeployedServicePackageFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedServicePackageHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ae93b-105">一覧を取得<see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" />をデプロイ済みサービス パッケージのヘルス状態に適用できます。</span><span class="sxs-lookup"><span data-stu-id="ae93b-105">Gets the list of <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" /> to be applied to the deployed service package health states.</span></span>
            </summary>
        <value><span data-ttu-id="ae93b-106">一連の<see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" />をデプロイ済みサービス パッケージのヘルス状態に適用できます。</span><span class="sxs-lookup"><span data-stu-id="ae93b-106">The list of <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" /> to be applied to the deployed service package health states.</span></span></value>
        <remarks><span data-ttu-id="ae93b-107">すべては、フィルターに一致するパッケージは、展開されたアプリケーションの子として返されるサービスを配置します。</span><span class="sxs-lookup"><span data-stu-id="ae93b-107">All deployed service packages that match the filter will be returned as children of the deployed application.</span></span>
            <span data-ttu-id="ae93b-108">空の場合、既定では子は返されません。</span><span class="sxs-lookup"><span data-stu-id="ae93b-108">If empty, the children are not returned by default.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.DeployedApplicationHealthStateFilter.HealthStateFilter" />
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
            <span data-ttu-id="ae93b-109">取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.DeployedApplicationHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="ae93b-109">Gets or sets filter for the aggregated health state of the <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="ae93b-110">集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.DeployedApplicationHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="ae93b-110">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> entries in the collection.</span></span></value>
        <remarks><span data-ttu-id="ae93b-111">ヘルス状態フィルター値はメンバーまたはのメンバーのビットごとの組み合わせから取得<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="ae93b-111">The health state filter value comes from members or bitwise combination of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span> <span data-ttu-id="ae93b-112">フィルターの一致するように配置されたアプリケーション、集計された正常性状態は、指定したヘルス状態のフィルターを一致しなければなりません。</span><span class="sxs-lookup"><span data-stu-id="ae93b-112">For a deployed application to match the filter, its aggregated health state must match the specified health state filter.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeNameFilter">
      <MemberSignature Language="C#" Value="public string NodeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedApplicationHealthStateFilter.NodeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.NodeNameFilter : string with get, set" Usage="System.Fabric.Health.DeployedApplicationHealthStateFilter.NodeNameFilter" />
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
            <span data-ttu-id="ae93b-113">取得またはノード名のフィルターを設定します。</span><span class="sxs-lookup"><span data-stu-id="ae93b-113">Gets or sets the node name filter.</span></span>
            </summary>
        <value><span data-ttu-id="ae93b-114">ノード名のフィルターです。</span><span class="sxs-lookup"><span data-stu-id="ae93b-114">The node name filter.</span></span></value>
        <remarks><span data-ttu-id="ae93b-115">以外の場合 (ある場合)、親フィルターに一致する指定すると、展開済みのすべてのアプリケーションが考慮され、その他のメンバーのフィルター選択、ヘルス状態のフィルターと同様に一致しました。</span><span class="sxs-lookup"><span data-stu-id="ae93b-115">If not specified, all deployed applications that match the parent filters (if any) are taken into consideration and matched against the other filter members, like health state filter.</span></span>
            <span data-ttu-id="ae93b-116">それ以外の場合、フィルターは、指定したノードにデプロイされたアプリケーションにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="ae93b-116">Otherwise, the filter only applies to applications deployed on the specified node.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedApplicationHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedApplicationHealthStateFilter.ToString " />
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
            <span data-ttu-id="ae93b-117">フィルターの文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="ae93b-117">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="ae93b-118">フィルターの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="ae93b-118">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>