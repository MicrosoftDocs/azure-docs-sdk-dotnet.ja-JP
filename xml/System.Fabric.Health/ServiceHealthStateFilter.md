<Type Name="ServiceHealthStateFilter" FullName="System.Fabric.Health.ServiceHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealthStateFilter" />
  <TypeSignature Language="F#" Value="type ServiceHealthStateFilter = class" />
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
            <span data-ttu-id="078d8-101">フィルター処理<see cref="T:System.Fabric.Health.ServiceHealthState" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="078d8-101">Filter for <see cref="T:System.Fabric.Health.ServiceHealthState" /> objects.</span></span>
            </summary>
    <remarks><span data-ttu-id="078d8-102">エンティティのヘルス状態のチャンク クエリは、粒度が細かいするサービスのフィルターの一覧は、クエリ結果に含める必要があるサービスを選択して指定できます。</span><span class="sxs-lookup"><span data-stu-id="078d8-102">The entity health state chunk queries can specify a list of service filters to fine-grain select the services that should be included in the query result.</span></span>
            <span data-ttu-id="078d8-103">渡されるフィルターに関係なく、正常性状態を集計、サービスは、親の評価に使用されるすべてことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="078d8-103">Note that all the services are used to evaluate parents aggregated health state, regardless of the filter passed in.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="078d8-104"><see cref="T:System.Fabric.Health.ServiceHealthStateFilter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="078d8-104">Initializes a new instance of the <see cref="T:System.Fabric.Health.ServiceHealthStateFilter" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.ServiceHealthStateFilter.HealthStateFilter" />
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
            <span data-ttu-id="078d8-105">取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.ServiceHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="078d8-105">Gets or sets filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ServiceHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="078d8-106">集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.ServiceHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="078d8-106">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ServiceHealthState" /> entries in the collection.</span></span></value>
        <remarks><span data-ttu-id="078d8-107">ヘルス状態フィルター値はメンバーまたはのメンバーのビットごとの組み合わせから取得<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="078d8-107">The health state filter value comes from members or bitwise combination of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span> <span data-ttu-id="078d8-108">フィルターに一致するサービスの集計された正常性状態は、指定したヘルス状態のフィルターを一致しなければなりません。</span><span class="sxs-lookup"><span data-stu-id="078d8-108">For a service to match the filter, its aggregated health state must match the specified health state filter.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthStateFilter&gt; PartitionFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.PartitionHealthStateFilter&gt; PartitionFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateFilter.PartitionFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionFilters As IList(Of PartitionHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.PartitionFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthStateFilter&gt;" Usage="System.Fabric.Health.ServiceHealthStateFilter.PartitionFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="078d8-109">一覧を取得<see cref="T:System.Fabric.Health.PartitionHealthStateFilter" />パーティションの子の正常性状態に適用します。</span><span class="sxs-lookup"><span data-stu-id="078d8-109">Gets the list of <see cref="T:System.Fabric.Health.PartitionHealthStateFilter" /> to be applied to the partition children health states.</span></span>
            </summary>
        <value><span data-ttu-id="078d8-110">一連の<see cref="T:System.Fabric.Health.PartitionHealthStateFilter" />パーティションの子の正常性状態に適用します。</span><span class="sxs-lookup"><span data-stu-id="078d8-110">The list of <see cref="T:System.Fabric.Health.PartitionHealthStateFilter" /> to be applied to the partition children health states.</span></span></value>
        <remarks><span data-ttu-id="078d8-111">一覧には、1 つの既定のパーティションのフィルターや、クエリによって返される粒度が細かいエンティティに特定のパーティションのパーティションのフィルターを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="078d8-111">The list can contain one default partition filter and/or partition filters for specific partitions to fine-grain entities returned by the query.</span></span>
            <span data-ttu-id="078d8-112">フィルターに一致するすべてのパーティションの子は、サービスの子として返されます。</span><span class="sxs-lookup"><span data-stu-id="078d8-112">All partition children that match the filter will be returned as children of the service.</span></span>
            <span data-ttu-id="078d8-113">空の場合、既定では子は返されません。</span><span class="sxs-lookup"><span data-stu-id="078d8-113">If empty, the children are not returned by default.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceNameFilter">
      <MemberSignature Language="C#" Value="public Uri ServiceNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateFilter.ServiceNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceNameFilter As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceNameFilter : Uri with get, set" Usage="System.Fabric.Health.ServiceHealthStateFilter.ServiceNameFilter" />
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
            <span data-ttu-id="078d8-114">取得またはサービス名のフィルターを設定します。</span><span class="sxs-lookup"><span data-stu-id="078d8-114">Gets or sets the service name filter.</span></span>
            </summary>
        <value><span data-ttu-id="078d8-115">サービス名のフィルターです。</span><span class="sxs-lookup"><span data-stu-id="078d8-115">The service name filter.</span></span></value>
        <remarks><span data-ttu-id="078d8-116">指定しない場合、親フィルター (指定されている場合) と指定したヘルス状態のフィルターに一致するすべてのサービスは、フィルターに一致します。</span><span class="sxs-lookup"><span data-stu-id="078d8-116">If not specified, all services that match the parent filters (if any) and the specified health state filter match the filter.</span></span>
            <span data-ttu-id="078d8-117">それ以外の場合、フィルターは、指定されたサービスにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="078d8-117">Otherwise, the filter only applies to the specified service.</span></span> <span data-ttu-id="078d8-118">すべての他のメンバーのフィルター、ヘルス状態のフィルターと同様には、このサービスに適用されます。</span><span class="sxs-lookup"><span data-stu-id="078d8-118">All the other filter members, like health state filter, are applied to this service.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceHealthStateFilter.ToString " />
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
            <span data-ttu-id="078d8-119">フィルターの文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="078d8-119">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="078d8-120">フィルターの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="078d8-120">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>