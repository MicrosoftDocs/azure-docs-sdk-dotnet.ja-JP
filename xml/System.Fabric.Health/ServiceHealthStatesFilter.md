<Type Name="ServiceHealthStatesFilter" FullName="System.Fabric.Health.ServiceHealthStatesFilter">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealthStatesFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealthStatesFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealthStatesFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealthStatesFilter" />
  <TypeSignature Language="F#" Value="type ServiceHealthStatesFilter = class" />
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
      <para><span data-ttu-id="2407d-101">フィルター処理を表します<see cref="T:System.Fabric.Health.ServiceHealthState" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2407d-101">Represents filter for <see cref="T:System.Fabric.Health.ServiceHealthState" /> objects.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="2407d-102">使用できるフィルター<see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" />を指定するサービスの子の一部として返される<see cref="T:System.Fabric.Health.ApplicationHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="2407d-102">The filter can be used in <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> to specify which service children should be returned as part of <see cref="T:System.Fabric.Health.ApplicationHealth" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceHealthStatesFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStatesFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="2407d-103"><see cref="T:System.Fabric.Health.ServiceHealthStatesFilter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2407d-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.ServiceHealthStatesFilter" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public long HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStatesFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As Long" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : int64 with get, set" Usage="System.Fabric.Health.ServiceHealthStatesFilter.HealthStateFilter" />
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
          <para><span data-ttu-id="2407d-104">推奨されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="2407d-104">DEPRECATED.</span></span> <span data-ttu-id="2407d-105">取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.ServiceHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="2407d-105">Gets or sets the filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ServiceHealthState" /> entries in the collection.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="2407d-106">フィルターの値です。</span><span class="sxs-lookup"><span data-stu-id="2407d-106">The value of the filter.</span></span> <span data-ttu-id="2407d-107">値は、メンバーまたはのメンバーのビットごとの組み合わせから取得<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="2407d-107">The value comes from members or bitwise combination of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></para>
        </value>
        <remarks><span data-ttu-id="2407d-108">このプロパティは今後使用しません。</span><span class="sxs-lookup"><span data-stu-id="2407d-108">This property is obsolete.</span></span> <span data-ttu-id="2407d-109">代わりに、<see cref="P:System.Fabric.Health.ApplicationHealthStatesFilter.HealthStateFilterValue" /> を使用してください。</span><span class="sxs-lookup"><span data-stu-id="2407d-109">Use <see cref="P:System.Fabric.Health.ApplicationHealthStatesFilter.HealthStateFilterValue" /> instead.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilterValue">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilterValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilterValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStatesFilter.HealthStateFilterValue" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilterValue As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilterValue : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.ServiceHealthStatesFilter.HealthStateFilterValue" />
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
            <span data-ttu-id="2407d-110">取得または設定の集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.ServiceHealthState" />コレクション内のエントリ。</span><span class="sxs-lookup"><span data-stu-id="2407d-110">Gets or sets the filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ServiceHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="2407d-111">集計された正常性状態のフィルター、<see cref="T:System.Fabric.Health.ServiceHealthState" />エントリです。</span><span class="sxs-lookup"><span data-stu-id="2407d-111">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ServiceHealthState" /> entries.</span></span></value>
        <remarks><span data-ttu-id="2407d-112">入力のコレクションは、必要な正常性状態を尊重エントリのみを返すフィルターされています。</span><span class="sxs-lookup"><span data-stu-id="2407d-112">The input collection is filtered to return only entries that respect the desired health state.</span></span> <span data-ttu-id="2407d-113">フィルターは、メンバーまたはのメンバーのビットごとの組み合わせから得られた値を表す<see cref="T:System.Fabric.Health.HealthStateFilter" />です。</span><span class="sxs-lookup"><span data-stu-id="2407d-113">The filter represents a value obtained from members or bitwise combinations of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStatesFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceHealthStatesFilter.ToString " />
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
            <span data-ttu-id="2407d-114">フィルターの文字列表現を返します。</span><span class="sxs-lookup"><span data-stu-id="2407d-114">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="2407d-115">フィルターの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="2407d-115">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>