<Type Name="NodeHealthStatesFilter" FullName="System.Fabric.Health.NodeHealthStatesFilter">
  <TypeSignature Language="C#" Value="public sealed class NodeHealthStatesFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeHealthStatesFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.NodeHealthStatesFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeHealthStatesFilter" />
  <TypeSignature Language="F#" Value="type NodeHealthStatesFilter = class" />
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
      <para><span data-ttu-id="d3c68-101">フィルターを表す<see cref="T:System.Fabric.Health.NodeHealthState" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d3c68-101">Represents the filter for <see cref="T:System.Fabric.Health.NodeHealthState" /> objects.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="d3c68-102">使用できるフィルター<see cref="T:System.Fabric.Description.ClusterHealthQueryDescription" />の一部として返される、クラスターの子ノードを指定する<see cref="T:System.Fabric.Health.ClusterHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="d3c68-102">The filter can be used in <see cref="T:System.Fabric.Description.ClusterHealthQueryDescription" /> to specify which node children of the cluster should be returned as part of <see cref="T:System.Fabric.Health.ClusterHealth" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeHealthStatesFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.NodeHealthStatesFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="d3c68-103"><see cref="T:System.Fabric.Health.NodeHealthStatesFilter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d3c68-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.NodeHealthStatesFilter" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public long HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodeHealthStatesFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As Long" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : int64 with get, set" Usage="System.Fabric.Health.NodeHealthStatesFilter.HealthStateFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This property is obsolete. Use HealthStateFilterValue instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d3c68-104">推奨されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="d3c68-104">DEPRECATED.</span></span> <span data-ttu-id="d3c68-105">取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.NodeHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="d3c68-105">Gets or sets the filter for the aggregated health state of the <see cref="T:System.Fabric.Health.NodeHealthState" /> entries in the collection.</span></span> <span data-ttu-id="d3c68-106">メンバーまたはのメンバーのビットごとの組み合わせから得られた値を表す<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="d3c68-106">Represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="d3c68-107">集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.NodeHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="d3c68-107">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.NodeHealthState" /> entries in the collection.</span></span> <span data-ttu-id="d3c68-108">メンバーまたはのメンバーのビットごとの組み合わせから得られた値を表す<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="d3c68-108">Represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></para>
        </value>
        <remarks><span data-ttu-id="d3c68-109">このプロパティは今後使用しません。</span><span class="sxs-lookup"><span data-stu-id="d3c68-109">This property is obsolete.</span></span> <span data-ttu-id="d3c68-110">代わりに、<see cref="P:System.Fabric.Health.NodeHealthStatesFilter.HealthStateFilterValue" /> を使用してください。</span><span class="sxs-lookup"><span data-stu-id="d3c68-110">Use <see cref="P:System.Fabric.Health.NodeHealthStatesFilter.HealthStateFilterValue" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilterValue">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilterValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilterValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodeHealthStatesFilter.HealthStateFilterValue" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilterValue As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilterValue : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.NodeHealthStatesFilter.HealthStateFilterValue" />
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
            <span data-ttu-id="d3c68-111">取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.NodeHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="d3c68-111">Gets or sets the filter for the aggregated health state of the <see cref="T:System.Fabric.Health.NodeHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="d3c68-112">集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.NodeHealthState" />エントリです。</span><span class="sxs-lookup"><span data-stu-id="d3c68-112">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.NodeHealthState" /> entries.</span></span></value>
        <remarks><span data-ttu-id="d3c68-113">入力のコレクションは、必要な正常性状態を尊重エントリのみを返すフィルターされています。</span><span class="sxs-lookup"><span data-stu-id="d3c68-113">The input collection is filtered to return only entries that respect the desired health state.</span></span> <span data-ttu-id="d3c68-114">フィルターは、メンバーまたはのメンバーのビットごとの組み合わせから得られた値を表す<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="d3c68-114">The filter represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.NodeHealthStatesFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeHealthStatesFilter.ToString " />
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
            <span data-ttu-id="d3c68-115">フィルターの文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="d3c68-115">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="d3c68-116">フィルターの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="d3c68-116">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>