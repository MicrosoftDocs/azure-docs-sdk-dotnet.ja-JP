<Type Name="HealthEventsFilter" FullName="System.Fabric.Health.HealthEventsFilter">
  <TypeSignature Language="C#" Value="public sealed class HealthEventsFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HealthEventsFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthEventsFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HealthEventsFilter" />
  <TypeSignature Language="F#" Value="type HealthEventsFilter = class" />
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
      <para><span data-ttu-id="27de4-101">フィルターを表す<see cref="T:System.Fabric.Health.HealthEvent" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="27de4-101">Represents the filter for <see cref="T:System.Fabric.Health.HealthEvent" /> objects.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="27de4-102">フィルターは、エンティティのヘルスにどのイベントが返されるフィルターに正常性クエリで使用できます。</span><span class="sxs-lookup"><span data-stu-id="27de4-102">The filter can be used in health queries to filter which events are returned in entity health.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HealthEventsFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthEventsFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="27de4-103"><see cref="T:System.Fabric.Health.HealthEventsFilter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="27de4-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.HealthEventsFilter" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public long HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEventsFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As Long" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : int64 with get, set" Usage="System.Fabric.Health.HealthEventsFilter.HealthStateFilter" />
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
          <para><span data-ttu-id="27de4-104">DERECATED です。</span><span class="sxs-lookup"><span data-stu-id="27de4-104">DERECATED.</span></span> <span data-ttu-id="27de4-105">取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.HealthEvent" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="27de4-105">Gets or sets the filter for the aggregated health state of the <see cref="T:System.Fabric.Health.HealthEvent" /> entries in the collection.</span></span> <span data-ttu-id="27de4-106">メンバーまたはのメンバーのビットごとの組み合わせから得られた値を表す<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="27de4-106">Represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="27de4-107">集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.HealthEvent" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="27de4-107">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.HealthEvent" /> entries in the collection.</span></span></para>
        </value>
        <remarks><span data-ttu-id="27de4-108">このプロパティは今後使用しません。</span><span class="sxs-lookup"><span data-stu-id="27de4-108">This property is obsolete.</span></span> <span data-ttu-id="27de4-109">代わりに、<see cref="P:System.Fabric.Health.HealthEventsFilter.HealthStateFilterValue" /> を使用してください。</span><span class="sxs-lookup"><span data-stu-id="27de4-109">Use <see cref="P:System.Fabric.Health.HealthEventsFilter.HealthStateFilterValue" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilterValue">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilterValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilterValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEventsFilter.HealthStateFilterValue" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilterValue As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilterValue : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.HealthEventsFilter.HealthStateFilterValue" />
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
            <span data-ttu-id="27de4-110">取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.HealthEvent" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="27de4-110">Gets or sets the filter for the aggregated health state of the <see cref="T:System.Fabric.Health.HealthEvent" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="27de4-111">集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.HealthEvent" />エントリです。</span><span class="sxs-lookup"><span data-stu-id="27de4-111">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.HealthEvent" /> entries.</span></span></value>
        <remarks><span data-ttu-id="27de4-112">入力のコレクションは、必要な正常性状態を尊重エントリのみを返すフィルターされています。</span><span class="sxs-lookup"><span data-stu-id="27de4-112">The input collection is filtered to return only entries that respect the desired health state.</span></span> <span data-ttu-id="27de4-113">フィルターは、メンバーまたはのメンバーのビットごとの組み合わせから得られた値を表す<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="27de4-113">The filter represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthEventsFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="healthEventsFilter.ToString " />
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
            <span data-ttu-id="27de4-114">フィルターの文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="27de4-114">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="27de4-115">フィルターの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="27de4-115">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>