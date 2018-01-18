<Type Name="PartitionHealthStateFilter" FullName="System.Fabric.Health.PartitionHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealthStateFilter" />
  <TypeSignature Language="F#" Value="type PartitionHealthStateFilter = class" />
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
            <span data-ttu-id="17f29-101">フィルター処理<see cref="T:System.Fabric.Health.PartitionHealthState" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="17f29-101">Filter for <see cref="T:System.Fabric.Health.PartitionHealthState" /> objects.</span></span>
            </summary>
    <remarks><span data-ttu-id="17f29-102">正常性の状態のチャンク クエリは、粒度が細かいパーティション フィルターの一覧は、クエリ結果に含める必要があるパーティションを選択して指定できます。</span><span class="sxs-lookup"><span data-stu-id="17f29-102">The health state chunk queries can specify a list of partition filters to fine-grain select the partitions that should be included in the query result.</span></span>
            <span data-ttu-id="17f29-103">渡されるフィルターに関係なく、正常性状態を集計すべてのパーティションが親の評価に使用されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="17f29-103">Note that all the partitions are used to evaluate parents' aggregated health state, regardless of the filter passed in.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="17f29-104"><see cref="T:System.Fabric.Health.PartitionHealthStateFilter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="17f29-104">Initializes a new instance of the <see cref="T:System.Fabric.Health.PartitionHealthStateFilter" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.PartitionHealthStateFilter.HealthStateFilter" />
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
            <span data-ttu-id="17f29-105">取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.PartitionHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="17f29-105">Gets or sets filter for the aggregated health state of the <see cref="T:System.Fabric.Health.PartitionHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="17f29-106">集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.PartitionHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="17f29-106">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.PartitionHealthState" /> entries in the collection.</span></span></value>
        <remarks><span data-ttu-id="17f29-107">ヘルス状態フィルター値はメンバーまたはのメンバーのビットごとの組み合わせから取得<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="17f29-107">The health state filter value comes from members or bitwise combination of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span> <span data-ttu-id="17f29-108">フィルターに一致するパーティションの集計された正常性状態は、指定したヘルス状態のフィルターを一致しなければなりません。</span><span class="sxs-lookup"><span data-stu-id="17f29-108">For a partition to match the filter, its aggregated health state must match the specified health state filter.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionIdFilter">
      <MemberSignature Language="C#" Value="public Guid PartitionIdFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionIdFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateFilter.PartitionIdFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionIdFilter As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionIdFilter : Guid with get, set" Usage="System.Fabric.Health.PartitionHealthStateFilter.PartitionIdFilter" />
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
            <span data-ttu-id="17f29-109">取得または、パーティション id フィルターを設定します。</span><span class="sxs-lookup"><span data-stu-id="17f29-109">Gets or sets the partition id filter.</span></span>
            </summary>
        <value><span data-ttu-id="17f29-110">パーティション id フィルターです。</span><span class="sxs-lookup"><span data-stu-id="17f29-110">The partition id filter.</span></span></value>
        <remarks><span data-ttu-id="17f29-111">いない場合は、指定すると、親に一致するすべてのパーティションをフィルター処理 (もしあれば) し、指定したヘルス状態のフィルターはフィルターに一致します。</span><span class="sxs-lookup"><span data-stu-id="17f29-111">If not specified, all partitions that match the parent filters (if any) and the specified health state filter match the filter.</span></span>
            <span data-ttu-id="17f29-112">それ以外の場合、フィルターは、パーティション id によって識別されるパーティションにのみ適用されます。すべての他のメンバーのフィルター、ヘルス状態のフィルターおよびレプリカ フィルターと同様には、このパーティションに適用されます。</span><span class="sxs-lookup"><span data-stu-id="17f29-112">Otherwise, the filter only applies to the partition identified by the partition id. All the other filter members, like health state filter and replicas filter, are applied to this partition.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthStateFilter&gt; ReplicaFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ReplicaHealthStateFilter&gt; ReplicaFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateFilter.ReplicaFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaFilters As IList(Of ReplicaHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.ReplicaFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthStateFilter&gt;" Usage="System.Fabric.Health.PartitionHealthStateFilter.ReplicaFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17f29-113">一覧を取得<see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" />をレプリカの子の正常性状態に適用できます。</span><span class="sxs-lookup"><span data-stu-id="17f29-113">Gets the list of <see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" /> to be applied to the replica children health states.</span></span>
            </summary>
        <value><span data-ttu-id="17f29-114">一連の<see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" />をレプリカの子の正常性状態に適用できます。</span><span class="sxs-lookup"><span data-stu-id="17f29-114">The list of <see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" /> to be applied to the replica children health states.</span></span></value>
        <remarks><span data-ttu-id="17f29-115">フィルターに一致するすべてのレプリカ子は、パーティションの子として返されます。</span><span class="sxs-lookup"><span data-stu-id="17f29-115">All replica children that match the filter will be returned as children of the partition.</span></span>
            <span data-ttu-id="17f29-116">空の場合、既定では子は返されません。</span><span class="sxs-lookup"><span data-stu-id="17f29-116">If empty, the children are not returned by default.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionHealthStateFilter.ToString " />
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
            <span data-ttu-id="17f29-117">フィルターの文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="17f29-117">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="17f29-118">フィルターの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="17f29-118">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>