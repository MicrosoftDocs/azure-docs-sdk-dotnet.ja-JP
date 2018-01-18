<Type Name="ReplicaHealthStatesFilter" FullName="System.Fabric.Health.ReplicaHealthStatesFilter">
  <TypeSignature Language="C#" Value="public sealed class ReplicaHealthStatesFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicaHealthStatesFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ReplicaHealthStatesFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicaHealthStatesFilter" />
  <TypeSignature Language="F#" Value="type ReplicaHealthStatesFilter = class" />
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
      <para><span data-ttu-id="06011-101">フィルターを表す<see cref="T:System.Fabric.Health.ReplicaHealthState" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="06011-101">Represents the filter for <see cref="T:System.Fabric.Health.ReplicaHealthState" /> objects.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="06011-102">使用できるフィルター<see cref="T:System.Fabric.Description.PartitionHealthQueryDescription" />の一部として返される子どのレプリカを指定する<see cref="T:System.Fabric.Health.PartitionHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="06011-102">The filter can be used in <see cref="T:System.Fabric.Description.PartitionHealthQueryDescription" /> to specify which replica children should be returned as part of <see cref="T:System.Fabric.Health.PartitionHealth" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicaHealthStatesFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStatesFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="06011-103"><see cref="T:System.Fabric.Health.ReplicaHealthStatesFilter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="06011-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.ReplicaHealthStatesFilter" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public long HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthStatesFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As Long" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : int64 with get, set" Usage="System.Fabric.Health.ReplicaHealthStatesFilter.HealthStateFilter" />
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
          <para><span data-ttu-id="06011-104">推奨されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="06011-104">DEPRECATED.</span></span> <span data-ttu-id="06011-105">取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.ReplicaHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="06011-105">Gets or sets the filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ReplicaHealthState" /> entries in the collection.</span></span> <span data-ttu-id="06011-106">メンバーまたはのメンバーのビットごとの組み合わせから得られた値を表す<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="06011-106">Represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></para>
        </summary>
        <value>
          <para> <span data-ttu-id="06011-107">集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.ReplicaHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="06011-107">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ReplicaHealthState" /> entries in the collection.</span></span> <span data-ttu-id="06011-108">値は、メンバーまたはのメンバーのビットごとの組み合わせから取得<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="06011-108">The value comes from members or bitwise combination of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></para>
        </value>
        <remarks><span data-ttu-id="06011-109">このプロパティは今後使用しません。</span><span class="sxs-lookup"><span data-stu-id="06011-109">This property is obsolete.</span></span> <span data-ttu-id="06011-110">代わりに、<see cref="P:System.Fabric.Health.ReplicaHealthStatesFilter.HealthStateFilterValue" /> を使用してください。</span><span class="sxs-lookup"><span data-stu-id="06011-110">Use <see cref="P:System.Fabric.Health.ReplicaHealthStatesFilter.HealthStateFilterValue" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilterValue">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilterValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilterValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthStatesFilter.HealthStateFilterValue" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilterValue As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilterValue : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.ReplicaHealthStatesFilter.HealthStateFilterValue" />
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
            <span data-ttu-id="06011-111">取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.ReplicaHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="06011-111">Gets or sets the filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ReplicaHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="06011-112">集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.ReplicaHealthState" />エントリです。</span><span class="sxs-lookup"><span data-stu-id="06011-112">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ReplicaHealthState" /> entries.</span></span></value>
        <remarks><span data-ttu-id="06011-113">入力のコレクションは、必要な正常性状態を尊重エントリのみを返すフィルターされています。</span><span class="sxs-lookup"><span data-stu-id="06011-113">The input collection is filtered to return only entries that respect the desired health state.</span></span> <span data-ttu-id="06011-114">フィルターは、メンバーまたはのメンバーのビットごとの組み合わせから得られた値を表す<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="06011-114">The filter represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStatesFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="replicaHealthStatesFilter.ToString " />
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
            <span data-ttu-id="06011-115">フィルターの文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="06011-115">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="06011-116">フィルターの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="06011-116">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>