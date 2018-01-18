<Type Name="ServiceDescription" FullName="System.Fabric.Description.ServiceDescription">
  <TypeSignature Language="C#" Value="public abstract class ServiceDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceDescription" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceDescription" />
  <TypeSignature Language="F#" Value="type ServiceDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.StatelessServiceDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.StatefulServiceDescription))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para> <span data-ttu-id="88ecc-101">な ServiceDescription には、すべてのサービスを作成するために必要な情報が含まれます。</span><span class="sxs-lookup"><span data-stu-id="88ecc-101">A ServiceDescription contains all of the information necessary to create a service.</span></span> </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ServiceDescription (System.Fabric.Description.ServiceDescription other);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.Description.ServiceDescription other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceDescription.#ctor(System.Fabric.Description.ServiceDescription)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (other As ServiceDescription)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceDescription : System.Fabric.Description.ServiceDescription -&gt; System.Fabric.Description.ServiceDescription" Usage="new System.Fabric.Description.ServiceDescription other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.Description.ServiceDescription" />
      </Parameters>
      <Docs>
        <param name="other">
          <para><span data-ttu-id="88ecc-102">パラメーターのコピー元となるサービスの説明。</span><span class="sxs-lookup"><span data-stu-id="88ecc-102">The service description from which parameters are copied.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="88ecc-103">インスタンスを作成、<see cref="T:System.Fabric.Description.ServiceDescription" />から別のパラメーターを持つクラス<see cref="T:System.Fabric.Description.ServiceDescription" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="88ecc-103">Instantiates a <see cref="T:System.Fabric.Description.ServiceDescription" /> class with parameters from another <see cref="T:System.Fabric.Description.ServiceDescription" /> object.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ServiceDescription (System.Fabric.Description.ServiceDescriptionKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Description.ServiceDescriptionKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceDescription.#ctor(System.Fabric.Description.ServiceDescriptionKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (kind As ServiceDescriptionKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceDescription : System.Fabric.Description.ServiceDescriptionKind -&gt; System.Fabric.Description.ServiceDescription" Usage="new System.Fabric.Description.ServiceDescription kind" />
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
          <para><span data-ttu-id="88ecc-104">サービスの種類について説明します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-104">Describe the kind of service type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="88ecc-105">インスタンスを初期化<see cref="T:System.Fabric.Description.ServiceDescription" />サービスの種類を使用します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-105">Initialize an instance of <see cref="T:System.Fabric.Description.ServiceDescription" /> with service kind.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri with get, set" Usage="System.Fabric.Description.ServiceDescription.ApplicationName" />
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
          <para><span data-ttu-id="88ecc-106">取得またはアプリケーションの URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-106">Gets or sets the URI of the application.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="88ecc-107">アプリケーション名。</span><span class="sxs-lookup"><span data-stu-id="88ecc-107">The application name.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="88ecc-108">アプリケーションの一意の名前は、これはグループ サービスを一緒に管理用に使用します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-108">This is the unique name of an application and is used to group services together for management.</span></span> <span data-ttu-id="88ecc-109">スキームである必要があります"fabric:/"アプリケーション名は、サービス名のプレフィックスをする必要があります。</span><span class="sxs-lookup"><span data-stu-id="88ecc-109">The scheme must be "fabric:/" and the application name must be a prefix of the service name.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Correlations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceCorrelationDescription&gt; Correlations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ServiceCorrelationDescription&gt; Correlations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.Correlations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Correlations As IList(Of ServiceCorrelationDescription)" />
      <MemberSignature Language="F#" Value="member this.Correlations : System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceCorrelationDescription&gt;" Usage="System.Fabric.Description.ServiceDescription.Correlations" />
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
            <span data-ttu-id="88ecc-110">一覧を取得<see cref="T:System.Fabric.Description.ServiceCorrelationDescription" />他のサービスとこのサービスの相関関係を記述します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-110">Gets the list of <see cref="T:System.Fabric.Description.ServiceCorrelationDescription" />s that describe the correlations of this service with other services.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="88ecc-111">相関関係の説明の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-111">Returns the list of correlation descriptions.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMoveCost">
      <MemberSignature Language="C#" Value="public System.Fabric.MoveCost DefaultMoveCost { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.MoveCost DefaultMoveCost" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.DefaultMoveCost" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMoveCost As MoveCost" />
      <MemberSignature Language="F#" Value="member this.DefaultMoveCost : System.Fabric.MoveCost with get, set" Usage="System.Fabric.Description.ServiceDescription.DefaultMoveCost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.MoveCost</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> 
            <span data-ttu-id="88ecc-112">既定値の設定を取得または<see cref="T:System.Fabric.MoveCost" />サービスの値。</span><span class="sxs-lookup"><span data-stu-id="88ecc-112">Gets or sets the default <see cref="T:System.Fabric.MoveCost" /> value for the service.</span></span>
            </para>
        </summary>
        <value>
          <para> <span data-ttu-id="88ecc-113">既定値<see cref="T:System.Fabric.MoveCost" />サービス用設定される値。</span><span class="sxs-lookup"><span data-stu-id="88ecc-113">The default <see cref="T:System.Fabric.MoveCost" /> value that should be set to for the service.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializationData">
      <MemberSignature Language="C#" Value="public byte[] InitializationData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] InitializationData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.InitializationData" />
      <MemberSignature Language="VB.NET" Value="Public Property InitializationData As Byte()" />
      <MemberSignature Language="F#" Value="member this.InitializationData : byte[] with get, set" Usage="System.Fabric.Description.ServiceDescription.InitializationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="88ecc-114">取得または作成するときは、渡される初期化データをサービス インスタンスまたはレプリカに設定します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-114">Gets or sets the initialization data that will be passed to service instances or replicas when they are created.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="88ecc-115">初期化データを返します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-115">Returns the initialization data.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDefaultMoveCostSpecified">
      <MemberSignature Language="C#" Value="public bool IsDefaultMoveCostSpecified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDefaultMoveCostSpecified" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.IsDefaultMoveCostSpecified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDefaultMoveCostSpecified As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDefaultMoveCostSpecified : bool" Usage="System.Fabric.Description.ServiceDescription.IsDefaultMoveCostSpecified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> 
            <span data-ttu-id="88ecc-116">かどうか、既定値を取得<see cref="T:System.Fabric.MoveCost" />サービスが指定されています。</span><span class="sxs-lookup"><span data-stu-id="88ecc-116">Gets whether a default <see cref="T:System.Fabric.MoveCost" /> is specified for the service.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="88ecc-117">示すフラグかどうか、既定値<see cref="T:System.Fabric.MoveCost" />サービスが指定されています。</span><span class="sxs-lookup"><span data-stu-id="88ecc-117">A flag indicating whether a default <see cref="T:System.Fabric.MoveCost" /> is specified for the service.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServiceDescriptionKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServiceDescriptionKind Kind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As ServiceDescriptionKind" />
      <MemberSignature Language="F#" Value="member this.Kind : System.Fabric.Description.ServiceDescriptionKind" Usage="System.Fabric.Description.ServiceDescription.Kind" />
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
          <para><span data-ttu-id="88ecc-118">このサービスのサービスの種類 (たとえば、ステートフルなまたはステートレス) を取得します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-118">Gets the service kind (for example, Stateful or Stateless) of this service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="88ecc-119">サービスの種類。</span><span class="sxs-lookup"><span data-stu-id="88ecc-119">The service kind.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.ServiceLoadMetricDescription&gt; Metrics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.ServiceLoadMetricDescription&gt; Metrics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public Property Metrics As KeyedCollection(Of String, ServiceLoadMetricDescription)" />
      <MemberSignature Language="F#" Value="member this.Metrics : System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceLoadMetricDescription&gt; with get, set" Usage="System.Fabric.Description.ServiceDescription.Metrics" />
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
            <span data-ttu-id="88ecc-120">キー付きコレクションの取得または設定<see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" />s このサービスに対して定義されている負荷メトリックを記述します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-120">Gets or sets the keyed collection of <see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" />s that describe the load metrics defined for this service.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="88ecc-121">一連の負荷メトリックの説明を返します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-121">Returns the collection of load metric descriptions.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionSchemeDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.PartitionSchemeDescription PartitionSchemeDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.PartitionSchemeDescription PartitionSchemeDescription" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.PartitionSchemeDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionSchemeDescription As PartitionSchemeDescription" />
      <MemberSignature Language="F#" Value="member this.PartitionSchemeDescription : System.Fabric.Description.PartitionSchemeDescription with get, set" Usage="System.Fabric.Description.ServiceDescription.PartitionSchemeDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.PartitionSchemeDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="88ecc-122">取得またはこのサービスに使用するパーティション スキームの説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-122">Gets or sets the partition scheme description to be used for this service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="88ecc-123">サービスに使用するパーティション構成です。</span><span class="sxs-lookup"><span data-stu-id="88ecc-123">The partition scheme to be used for the service.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlacementConstraints">
      <MemberSignature Language="C#" Value="public string PlacementConstraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PlacementConstraints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.PlacementConstraints" />
      <MemberSignature Language="VB.NET" Value="Public Property PlacementConstraints As String" />
      <MemberSignature Language="F#" Value="member this.PlacementConstraints : string with get, set" Usage="System.Fabric.Description.ServiceDescription.PlacementConstraints" />
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
          <para> <span data-ttu-id="88ecc-124">取得またはこのサービスの配置に関する制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-124">Gets or sets the placement constraints for this service.</span></span></para>
        </summary>
        <value>
          <para> <span data-ttu-id="88ecc-125">配置に関する制約を返します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-125">Returns the placement constraints.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="88ecc-126">配置に関する制約は、サービスを特定のノード プロパティ (およびそれらのプロパティの値) は、配置を制御するために選択できるようにするブール型のステートメントです。</span><span class="sxs-lookup"><span data-stu-id="88ecc-126">Placement constraints are Boolean statements which allow services to select for particular node properties (and the values of those properties) in order to control where it is legal to place them.</span></span>  <span data-ttu-id="88ecc-127">ノードのプロパティは、通常、ノードのハードウェア機能に関連して、ノードに関するいくつか追加のメタデータを定義するキー値のペアです。</span><span class="sxs-lookup"><span data-stu-id="88ecc-127">Node properties are key value pairs that define some additional metadata about a node, usually related to the hardware capabilities of the node.</span></span>  <span data-ttu-id="88ecc-128">ノードのプロパティとして公開される可能性がハードウェアの特性には、"HasDisk"、"%memorysize"、"StorageSize"、"NumberOfCores"などがあります。サービスを展開するときに、管理者は、サービスに配慮してプロパティに加え、これらのプロパティの値の要件を定義する簡単なブール演算子を定義できます。</span><span class="sxs-lookup"><span data-stu-id="88ecc-128">Examples of hardware characteristics that could be exposed as node properties are “HasDisk”, “MemorySize”, “StorageSize”, “NumberOfCores” etc.  When deploying a service, an administrator can define the properties that the service cares about as well as simple Boolean operators which define requirements for the values of those properties.</span></span>  <span data-ttu-id="88ecc-129">例: (HasDisk = = true &amp; &amp; %memorysize&gt;= 2048)。</span><span class="sxs-lookup"><span data-stu-id="88ecc-129">Ex: (HasDisk==true &amp;&amp; MemorySize&gt;=2048).</span></span>  <span data-ttu-id="88ecc-130">実行時に Service Fabric 負荷分散はのみサービスに配置をサービスに必要なものと一致する値を持つプロパティを持つノード。</span><span class="sxs-lookup"><span data-stu-id="88ecc-130">During runtime, Service Fabric load balancing will only place services on nodes that have properties with values which match those required by the service.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PlacementPolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ServicePlacementPolicyDescription&gt; PlacementPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ServicePlacementPolicyDescription&gt; PlacementPolicies" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.PlacementPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PlacementPolicies As IList(Of ServicePlacementPolicyDescription)" />
      <MemberSignature Language="F#" Value="member this.PlacementPolicies : System.Collections.Generic.IList&lt;System.Fabric.Description.ServicePlacementPolicyDescription&gt;" Usage="System.Fabric.Description.ServiceDescription.PlacementPolicies" />
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
            <span data-ttu-id="88ecc-131">一覧を取得<see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" />をこのサービスの配置ポリシーをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-131">Gets the list of <see cref="T:System.Fabric.Description.ServicePlacementPolicyDescription" />s that describe the placement policies for this service.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="88ecc-132">配置ポリシーの説明の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-132">Returns the list of placement policy descriptions.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceDnsName">
      <MemberSignature Language="C#" Value="public string ServiceDnsName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceDnsName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.ServiceDnsName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceDnsName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceDnsName : string with get, set" Usage="System.Fabric.Description.ServiceDescription.ServiceDnsName" />
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
            <span data-ttu-id="88ecc-133">取得またはサービスの DNS 名を設定します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-133">Gets or sets the service DNS name.</span></span> <span data-ttu-id="88ecc-134">これを指定するとかどうか、サービスの代わりに DNS 名を介してアクセスできる<see cref="P:System.Fabric.Description.ServiceDescription.ServiceName" />です。</span><span class="sxs-lookup"><span data-stu-id="88ecc-134">If this is specified, then the service can be accessed via its DNS name instead of <see cref="P:System.Fabric.Description.ServiceDescription.ServiceName" />.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="88ecc-135">サービスの DNS 名または<c>null</c>サービスは、指定した DNS 名を持っていない場合。</span><span class="sxs-lookup"><span data-stu-id="88ecc-135">The DNS name of the service or <c>null</c> if the service doesn't have a DNS name specified.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri with get, set" Usage="System.Fabric.Description.ServiceDescription.ServiceName" />
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
          <para><span data-ttu-id="88ecc-136">取得またはこのサービスの URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-136">Gets or sets the URI of this service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="88ecc-137">サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="88ecc-137">The service name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationMode">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServicePackageActivationMode ServicePackageActivationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServicePackageActivationMode ServicePackageActivationMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.ServicePackageActivationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePackageActivationMode As ServicePackageActivationMode" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationMode : System.Fabric.Description.ServicePackageActivationMode with get, set" Usage="System.Fabric.Description.ServiceDescription.ServicePackageActivationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePackageActivationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> 
            <span data-ttu-id="88ecc-138">取得または設定、<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービス。</span><span class="sxs-lookup"><span data-stu-id="88ecc-138">Gets or sets the <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> of a service.</span></span>
            </para>
        </summary>
        <value>
          <para> 
            <span data-ttu-id="88ecc-139">A<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />を含むサービス パッケージのライセンス認証モードを表す列挙体、<see cref="P:System.Fabric.Description.ServiceDescription.ServiceTypeName" />がアクティブになるレプリカは、これによって説明されるサービスのインスタンスをホストして<see cref="T:System.Fabric.Description.ServiceDescription" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="88ecc-139">A <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> enumeration that represents activation mode of the service package that contains the <see cref="P:System.Fabric.Description.ServiceDescription.ServiceTypeName" /> and will be activated to host the replica(s) or instance(s) of the service described by this <see cref="T:System.Fabric.Description.ServiceDescription" /> object.</span></span> <span data-ttu-id="88ecc-140">参照してください<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="88ecc-140">Please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> for more details.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceDescription.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string with get, set" Usage="System.Fabric.Description.ServiceDescription.ServiceTypeName" />
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
          <para><span data-ttu-id="88ecc-141">取得またはサービス型の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="88ecc-141">Gets or sets the service type name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="88ecc-142">サービスの種類の名前。</span><span class="sxs-lookup"><span data-stu-id="88ecc-142">The name of the service type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>