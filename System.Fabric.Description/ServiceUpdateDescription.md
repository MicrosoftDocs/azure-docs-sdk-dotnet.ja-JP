<Type Name="ServiceUpdateDescription" FullName="System.Fabric.Description.ServiceUpdateDescription">
  <TypeSignature Language="C#" Value="public abstract class ServiceUpdateDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceUpdateDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceUpdateDescription" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceUpdateDescription" />
  <TypeSignature Language="F#" Value="type ServiceUpdateDescription = class" />
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
      <para><span data-ttu-id="f3bff-101">変更、<see cref="T:System.Fabric.Description.ServiceDescription" />の既存のサービスです。</span><span class="sxs-lookup"><span data-stu-id="f3bff-101">Modifies the <see cref="T:System.Fabric.Description.ServiceDescription" /> of an existing service.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ServiceUpdateDescription (System.Fabric.Description.ServiceDescriptionKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Description.ServiceDescriptionKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceUpdateDescription.#ctor(System.Fabric.Description.ServiceDescriptionKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (kind As ServiceDescriptionKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceUpdateDescription : System.Fabric.Description.ServiceDescriptionKind -&gt; System.Fabric.Description.ServiceUpdateDescription" Usage="new System.Fabric.Description.ServiceUpdateDescription kind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="System.Fabric.Description.ServiceDescriptionKind" />
      </Parameters>
      <Docs>
        <param name="kind">
          <para><span data-ttu-id="f3bff-102">種類を指定するかどうかこの<see cref="T:System.Fabric.Description.ServiceUpdateDescription" />は、<see cref="T:System.Fabric.Description.StatelessServiceUpdateDescription" />または<see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" /></span><span class="sxs-lookup"><span data-stu-id="f3bff-102">The kind specifies whether this <see cref="T:System.Fabric.Description.ServiceUpdateDescription" /> is a <see cref="T:System.Fabric.Description.StatelessServiceUpdateDescription" /> or <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" /></span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f3bff-103"><see cref="T:System.Fabric.Description.ServiceUpdateDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f3bff-103">Initializes a new instance of the <see cref="T:System.Fabric.Description.ServiceUpdateDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Correlations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceCorrelationDescription&gt; Correlations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ServiceCorrelationDescription&gt; Correlations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceUpdateDescription.Correlations" />
      <MemberSignature Language="VB.NET" Value="Public Property Correlations As IList(Of ServiceCorrelationDescription)" />
      <MemberSignature Language="F#" Value="member this.Correlations : System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceCorrelationDescription&gt; with get, set" Usage="System.Fabric.Description.ServiceUpdateDescription.Correlations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceCorrelationDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="f3bff-104">サービスの相関関係の一覧。</span><span class="sxs-lookup"><span data-stu-id="f3bff-104">A list of service correlations.</span></span> <see cref="T:System.Fabric.Description.ServiceCorrelationDescription" /></para>
        </summary>
        <value>
          <para><span data-ttu-id="f3bff-105">相関関係のプロパティを取得/設定 _correlations、IList フィールドの値。</span><span class="sxs-lookup"><span data-stu-id="f3bff-105">Correlations property gets/sets the value of the IList field, _correlations.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMoveCost">
      <MemberSignature Language="C#" Value="public Nullable&lt;System.Fabric.MoveCost&gt; DefaultMoveCost { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Fabric.MoveCost&gt; DefaultMoveCost" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceUpdateDescription.DefaultMoveCost" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMoveCost As Nullable(Of MoveCost)" />
      <MemberSignature Language="F#" Value="member this.DefaultMoveCost : Nullable&lt;System.Fabric.MoveCost&gt; with get, set" Usage="System.Fabric.Description.ServiceUpdateDescription.DefaultMoveCost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Fabric.MoveCost&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="f3bff-106">既定値は、コストを移動します。</span><span class="sxs-lookup"><span data-stu-id="f3bff-106">The default move cost.</span></span> <span data-ttu-id="f3bff-107"><see cref="T:System.Fabric.MoveCost" />指定しない場合、値になります<see cref="F:System.Fabric.Interop.NativeTypes.FABRIC_MOVE_COST.FABRIC_MOVE_COST_LOW" /></span><span class="sxs-lookup"><span data-stu-id="f3bff-107"><see cref="T:System.Fabric.MoveCost" /> If not provided, the value will be <see cref="F:System.Fabric.Interop.NativeTypes.FABRIC_MOVE_COST.FABRIC_MOVE_COST_LOW" /></span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f3bff-108">DefaultMoveCost プロパティを取得/設定 _defaultMoveCost MoveCost フィールドの値。</span><span class="sxs-lookup"><span data-stu-id="f3bff-108">DefaultMoveCost property gets/sets the value of the MoveCost field, _defaultMoveCost.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServiceDescriptionKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServiceDescriptionKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceUpdateDescription.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As ServiceDescriptionKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.Description.ServiceDescriptionKind" Usage="System.Fabric.Description.ServiceUpdateDescription.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServiceDescriptionKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f3bff-109">取得または設定するかどうか、<see cref="T:System.Fabric.Description.ServiceUpdateDescription" />オブジェクトが、<see cref="T:System.Fabric.Description.StatelessServiceUpdateDescription" />または<see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" />です。</span><span class="sxs-lookup"><span data-stu-id="f3bff-109">Gets or sets whether the <see cref="T:System.Fabric.Description.ServiceUpdateDescription" /> object is a <see cref="T:System.Fabric.Description.StatelessServiceUpdateDescription" /> or <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f3bff-110">更新プログラムの説明の種類。</span><span class="sxs-lookup"><span data-stu-id="f3bff-110">The kind of update description.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.ServiceLoadMetricDescription&gt; Metrics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.ServiceLoadMetricDescription&gt; Metrics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceUpdateDescription.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public Property Metrics As KeyedCollection(Of String, ServiceLoadMetricDescription)" />
      <MemberSignature Language="F#" Value="member this.Metrics : System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceLoadMetricDescription&gt; with get, set" Usage="System.Fabric.Description.ServiceUpdateDescription.Metrics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.KeyedCollection&lt;System.String,System.Fabric.Description.ServiceLoadMetricDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="f3bff-111">サービス メトリックの説明をサービスのメトリック名のマップ。</span><span class="sxs-lookup"><span data-stu-id="f3bff-111">A map of service metric name to service metric description.</span></span> <see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" /></para>
        </summary>
        <value>
          <para><span data-ttu-id="f3bff-112">メトリックのプロパティを取得/設定 _metrics KeyedCollection フィールドの値。</span><span class="sxs-lookup"><span data-stu-id="f3bff-112">Metrics property gets/sets the value of the KeyedCollection field, _metrics.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlacementConstraints">
      <MemberSignature Language="C#" Value="public string PlacementConstraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PlacementConstraints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceUpdateDescription.PlacementConstraints" />
      <MemberSignature Language="VB.NET" Value="Public Property PlacementConstraints As String" />
      <MemberSignature Language="F#" Value="member this.PlacementConstraints : string with get, set" Usage="System.Fabric.Description.ServiceUpdateDescription.PlacementConstraints" />
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
          <para>
            <span data-ttu-id="f3bff-113">このサービスの配置制約。</span><span class="sxs-lookup"><span data-stu-id="f3bff-113">The placement constraints for this service.</span></span> <span data-ttu-id="f3bff-114">配置制約は、いくつかのノード上に配置されているレプリカを制限します。</span><span class="sxs-lookup"><span data-stu-id="f3bff-114">A placement constraint restrict the replica being placed on some nodes.</span></span>
            <span data-ttu-id="f3bff-115">配置に関する制約は、各配置制約の結合されたロジックです。</span><span class="sxs-lookup"><span data-stu-id="f3bff-115">Placement constraints is a combined logic of each placement constraint.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="f3bff-116">PlacementConstraints プロパティを取得/設定 placementConstraints、文字列フィールドの値。</span><span class="sxs-lookup"><span data-stu-id="f3bff-116">PlacementConstraints property gets/sets the value of the string field, placementConstraints.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
        <example> <span data-ttu-id="f3bff-117">nodeName node1 を = = | |nodeType databaseNode を = =</span><span class="sxs-lookup"><span data-stu-id="f3bff-117">nodeName == node1 || nodeType == databaseNode</span></span> </example>
      </Docs>
    </Member>
    <Member MemberName="PlacementPolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ServicePlacementPolicyDescription&gt; PlacementPolicies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ServicePlacementPolicyDescription&gt; PlacementPolicies" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceUpdateDescription.PlacementPolicies" />
      <MemberSignature Language="VB.NET" Value="Public Property PlacementPolicies As IList(Of ServicePlacementPolicyDescription)" />
      <MemberSignature Language="F#" Value="member this.PlacementPolicies : System.Collections.Generic.IList&lt;System.Fabric.Description.ServicePlacementPolicyDescription&gt; with get, set" Usage="System.Fabric.Description.ServiceUpdateDescription.PlacementPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.ServicePlacementPolicyDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="f3bff-118">サービス配置ポリシーの一覧。</span><span class="sxs-lookup"><span data-stu-id="f3bff-118">A list of service placement policies.</span></span> <see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" /></para>
        </summary>
        <value>
          <para><span data-ttu-id="f3bff-119">PlacementPolicies プロパティを取得/設定 _placementPolicies、IList フィールドの値。</span><span class="sxs-lookup"><span data-stu-id="f3bff-119">PlacementPolicies property gets/sets the value of the IList field, _placementPolicies.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>