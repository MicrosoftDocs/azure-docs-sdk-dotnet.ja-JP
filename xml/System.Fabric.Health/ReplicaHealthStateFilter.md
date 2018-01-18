<Type Name="ReplicaHealthStateFilter" FullName="System.Fabric.Health.ReplicaHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class ReplicaHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicaHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ReplicaHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicaHealthStateFilter" />
  <TypeSignature Language="F#" Value="type ReplicaHealthStateFilter = class" />
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
            <span data-ttu-id="80f86-101">フィルター処理<see cref="T:System.Fabric.Health.ReplicaHealthState" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="80f86-101">Filter for <see cref="T:System.Fabric.Health.ReplicaHealthState" /> objects.</span></span>
            </summary>
    <remarks><span data-ttu-id="80f86-102">エンティティのヘルス状態のチャンク クエリでは、粒度が細かいにレプリカ フィルターの一覧を選択、クエリ結果に含める必要があるレプリカを指定できます。</span><span class="sxs-lookup"><span data-stu-id="80f86-102">The entity health state chunk queries can specify a list of replica filters to fine-grain select the replicas that should be included in the query result.</span></span>
            <span data-ttu-id="80f86-103">渡されるフィルターに関係なく、正常性状態を集計すべてのレプリカは、親の評価に使用されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="80f86-103">Note that all the replicas are used to evaluate parents aggregated health state, regardless of the filter passed in.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicaHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="80f86-104"><see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="80f86-104">Initializes a new instance of the <see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.ReplicaHealthStateFilter.HealthStateFilter" />
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
            <span data-ttu-id="80f86-105">取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.ReplicaHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="80f86-105">Gets or sets filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ReplicaHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="80f86-106">集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.ReplicaHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="80f86-106">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ReplicaHealthState" /> entries in the collection.</span></span></value>
        <remarks><span data-ttu-id="80f86-107">ヘルス状態フィルター値はメンバーまたはのメンバーのビットごとの組み合わせから取得<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="80f86-107">The health state filter value comes from members or bitwise combination of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span> <span data-ttu-id="80f86-108">フィルターの一致するように、レプリカの集計された正常性状態は、指定したヘルス状態のフィルターを一致しなければなりません。</span><span class="sxs-lookup"><span data-stu-id="80f86-108">For a replica to match the filter, its aggregated health state must match the specified health state filter.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaOrInstanceIdFilter">
      <MemberSignature Language="C#" Value="public long ReplicaOrInstanceIdFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaOrInstanceIdFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthStateFilter.ReplicaOrInstanceIdFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicaOrInstanceIdFilter As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaOrInstanceIdFilter : int64 with get, set" Usage="System.Fabric.Health.ReplicaHealthStateFilter.ReplicaOrInstanceIdFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="80f86-109">取得またはステートフル サービス レプリカ id またはステートレスなインスタンス id フィルターを設定します。</span><span class="sxs-lookup"><span data-stu-id="80f86-109">Gets or sets the stateful service replica id or the stateless instance id filter.</span></span>
            </summary>
        <value><span data-ttu-id="80f86-110">ステートフル サービス レプリカ id またはステートレスなインスタンス id フィルターします。</span><span class="sxs-lookup"><span data-stu-id="80f86-110">The stateful service replica id or the stateless instance id filter.</span></span></value>
        <remarks><span data-ttu-id="80f86-111">いない場合は、指定すると、親に一致するすべてのレプリカをフィルター処理 (もしあれば) し、指定したヘルス状態のフィルターはフィルターに一致します。</span><span class="sxs-lookup"><span data-stu-id="80f86-111">If not specified, all replicas that match the parent filters (if any) and the specified health state filter match the filter.</span></span>
            <span data-ttu-id="80f86-112">それ以外の場合、フィルターは、指定した id によって識別される、レプリカにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="80f86-112">Otherwise, the filter only applies to the replica identified by the given id.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="replicaHealthStateFilter.ToString " />
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
            <span data-ttu-id="80f86-113">フィルターの文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="80f86-113">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="80f86-114">フィルターの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="80f86-114">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>