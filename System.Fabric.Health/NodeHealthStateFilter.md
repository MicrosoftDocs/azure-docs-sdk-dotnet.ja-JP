<Type Name="NodeHealthStateFilter" FullName="System.Fabric.Health.NodeHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class NodeHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.NodeHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeHealthStateFilter" />
  <TypeSignature Language="F#" Value="type NodeHealthStateFilter = class" />
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
            <span data-ttu-id="29ddf-101">フィルター処理<see cref="T:System.Fabric.Health.NodeHealthState" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="29ddf-101">Filter for <see cref="T:System.Fabric.Health.NodeHealthState" /> objects.</span></span>
            </summary>
    <remarks><span data-ttu-id="29ddf-102">クラスターの正常性の状態のチャンク クエリは、粒度が細かいするノードのフィルターの一覧は、クエリ結果に含める必要があるノードを選択して指定できます。</span><span class="sxs-lookup"><span data-stu-id="29ddf-102">The cluster health state chunk queries can specify a list of node filters to fine-grain select the nodes that should be included in the query result.</span></span>
            <span data-ttu-id="29ddf-103">渡されるすべてのノードがフィルターに関係なく、集計されたクラスターの正常性状態の評価に使用されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="29ddf-103">Note that all the nodes are used to evaluate cluster aggregated health state, regardless of the filter passed in.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.NodeHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="29ddf-104"><see cref="T:System.Fabric.Health.NodeHealthStateFilter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="29ddf-104">Initializes a new instance of the <see cref="T:System.Fabric.Health.NodeHealthStateFilter" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodeHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.NodeHealthStateFilter.HealthStateFilter" />
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
            <span data-ttu-id="29ddf-105">取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.NodeHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="29ddf-105">Gets or sets filter for the aggregated health state of the <see cref="T:System.Fabric.Health.NodeHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="29ddf-106">集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.NodeHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="29ddf-106">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.NodeHealthState" /> entries in the collection.</span></span></value>
        <remarks><span data-ttu-id="29ddf-107">ヘルス状態フィルター値はメンバーまたはのメンバーのビットごとの組み合わせから取得<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="29ddf-107">The health state filter value comes from members or bitwise combination of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span> <span data-ttu-id="29ddf-108">フィルターに一致するノードは、集計された正常性状態は、指定したヘルス状態のフィルターを一致しなければなりません。</span><span class="sxs-lookup"><span data-stu-id="29ddf-108">For a node to match the filter, its aggregated health state must match the specified health state filter.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeNameFilter">
      <MemberSignature Language="C#" Value="public string NodeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodeHealthStateFilter.NodeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.NodeNameFilter : string with get, set" Usage="System.Fabric.Health.NodeHealthStateFilter.NodeNameFilter" />
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
            <span data-ttu-id="29ddf-109">取得またはノード名のフィルターを設定します。</span><span class="sxs-lookup"><span data-stu-id="29ddf-109">Gets or sets the node name filter.</span></span>
            </summary>
        <value><span data-ttu-id="29ddf-110">ノード名のフィルターです。</span><span class="sxs-lookup"><span data-stu-id="29ddf-110">The node name filter.</span></span></value>
        <remarks><span data-ttu-id="29ddf-111">指定しない場合、(存在する場合)、親フィルターに一致するすべてのノードが考慮され、ヘルス状態のフィルターと同様に、他のフィルター メンバーと照合します。</span><span class="sxs-lookup"><span data-stu-id="29ddf-111">If not specified, all nodes that match the parent filters (if any) are taken into consideration and matched against the other filter members, like health state filter.</span></span>
            <span data-ttu-id="29ddf-112">それ以外の場合、フィルターは、指定したノードにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="29ddf-112">Otherwise, the filter only applies to the specfied node.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.NodeHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeHealthStateFilter.ToString " />
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
            <span data-ttu-id="29ddf-113">フィルターの文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="29ddf-113">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="29ddf-114">フィルターの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="29ddf-114">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>