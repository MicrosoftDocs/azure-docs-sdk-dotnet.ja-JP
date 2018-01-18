<Type Name="ServiceTypeDescription" FullName="System.Fabric.Description.ServiceTypeDescription">
  <TypeSignature Language="C#" Value="public abstract class ServiceTypeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceTypeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceTypeDescription" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceTypeDescription" />
  <TypeSignature Language="F#" Value="type ServiceTypeDescription = class" />
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
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.StatelessServiceTypeDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Description.StatefulServiceTypeDescription))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="3401e-101">サービスの種類について説明します。</span><span class="sxs-lookup"><span data-stu-id="3401e-101">Describes the service type.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected internal ServiceTypeDescription (System.Fabric.Description.ServiceDescriptionKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Description.ServiceDescriptionKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceTypeDescription.#ctor(System.Fabric.Description.ServiceDescriptionKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Sub New (kind As ServiceDescriptionKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceTypeDescription : System.Fabric.Description.ServiceDescriptionKind -&gt; System.Fabric.Description.ServiceTypeDescription" Usage="new System.Fabric.Description.ServiceTypeDescription kind" />
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
          <para><span data-ttu-id="3401e-102">サービス説明の種類。</span><span class="sxs-lookup"><span data-stu-id="3401e-102">The service description kind.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="3401e-103">インスタンスを作成、<see cref="T:System.Fabric.Description.ServiceTypeDescription" />クラスを指定したサービス説明の種類。</span><span class="sxs-lookup"><span data-stu-id="3401e-103">Instantiates a <see cref="T:System.Fabric.Description.ServiceTypeDescription" /> class with specified service description kind.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected internal ServiceTypeDescription (System.Fabric.Description.ServiceTypeDescription other);" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.Description.ServiceTypeDescription other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceTypeDescription.#ctor(System.Fabric.Description.ServiceTypeDescription)" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Sub New (other As ServiceTypeDescription)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceTypeDescription : System.Fabric.Description.ServiceTypeDescription -&gt; System.Fabric.Description.ServiceTypeDescription" Usage="new System.Fabric.Description.ServiceTypeDescription other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.Description.ServiceTypeDescription" />
      </Parameters>
      <Docs>
        <param name="other">
          <para><span data-ttu-id="3401e-104">パラメーターのコピー元となるサービスの種類の説明。</span><span class="sxs-lookup"><span data-stu-id="3401e-104">The service type description from which parameters are copied.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="3401e-105">インスタンスを作成、<see cref="T:System.Fabric.Description.ServiceTypeDescription" />から別のパラメーターを持つクラス<see cref="T:System.Fabric.Description.ServiceTypeDescription" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="3401e-105">Instantiates a <see cref="T:System.Fabric.Description.ServiceTypeDescription" /> class with parameters from another <see cref="T:System.Fabric.Description.ServiceTypeDescription" /> object.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Extensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Extensions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Extensions" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceTypeDescription.Extensions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Extensions As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Extensions : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="System.Fabric.Description.ServiceTypeDescription.Extensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3401e-106">サービスの種類の拡張機能を取得します。</span><span class="sxs-lookup"><span data-stu-id="3401e-106">Gets the extensions for the service type.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3401e-107">サービスの拡張機能を入力します。</span><span class="sxs-lookup"><span data-stu-id="3401e-107">The extensions for the service type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Extensions_">
      <MemberSignature Language="C#" Value="protected internal System.Collections.Generic.IList&lt;System.Collections.Generic.KeyValuePair&lt;string,string&gt;&gt; Extensions_ { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;string, string&gt;&gt; Extensions_" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceTypeDescription.Extensions_" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Property Extensions_ As IList(Of KeyValuePair(Of String, String))" />
      <MemberSignature Language="F#" Value="member this.Extensions_ : System.Collections.Generic.IList&lt;System.Collections.Generic.KeyValuePair&lt;string, string&gt;&gt; with get, set" Usage="System.Fabric.Description.ServiceTypeDescription.Extensions_" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Collections.Generic.KeyValuePair&lt;System.String,System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3401e-108">内部使用のみ。</span><span class="sxs-lookup"><span data-stu-id="3401e-108">INTERNAL USE ONLY.</span></span> <span data-ttu-id="3401e-109">プロパティ"Extensions"のラッパーです。</span><span class="sxs-lookup"><span data-stu-id="3401e-109">Wrapper of property "Extensions".</span></span> <span data-ttu-id="3401e-110">シリアル化に必要です。</span><span class="sxs-lookup"><span data-stu-id="3401e-110">Needed for serialization.</span></span>
            </summary>
        <value>
            <span data-ttu-id="3401e-111">内部使用のみ。</span><span class="sxs-lookup"><span data-stu-id="3401e-111">INTERNAL USE ONLY.</span></span> <span data-ttu-id="3401e-112">プロパティ"Extensions"のラッパーです。</span><span class="sxs-lookup"><span data-stu-id="3401e-112">Wrapper of property "Extensions".</span></span> <span data-ttu-id="3401e-113">シリアル化に必要です。</span><span class="sxs-lookup"><span data-stu-id="3401e-113">Needed for serialization.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsStateful">
      <MemberSignature Language="C#" Value="protected internal bool IsStateful { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsStateful" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceTypeDescription.IsStateful" />
      <MemberSignature Language="VB.NET" Value="Protected Friend ReadOnly Property IsStateful As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsStateful : bool" Usage="System.Fabric.Description.ServiceTypeDescription.IsStateful" />
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
            <span data-ttu-id="3401e-114">サービスがステートフルであるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="3401e-114">Indicates whether the service is stateful.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="3401e-115">サービスがステートフルであるかどうかを示すフラグします。</span><span class="sxs-lookup"><span data-stu-id="3401e-115">Flag indicating whether the service is stateful.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="3401e-116">REST API とネイティブ コードが公開。</span><span class="sxs-lookup"><span data-stu-id="3401e-116">Exposed by REST API and native code.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadMetrics">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.ServiceLoadMetricDescription&gt; LoadMetrics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.ServiceLoadMetricDescription&gt; LoadMetrics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceTypeDescription.LoadMetrics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadMetrics As KeyedCollection(Of String, ServiceLoadMetricDescription)" />
      <MemberSignature Language="F#" Value="member this.LoadMetrics : System.Collections.ObjectModel.KeyedCollection&lt;string, System.Fabric.Description.ServiceLoadMetricDescription&gt;" Usage="System.Fabric.Description.ServiceTypeDescription.LoadMetrics" />
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
          <para><span data-ttu-id="3401e-117">負荷メトリックの種類は、サービスによって報告されるを取得します。</span><span class="sxs-lookup"><span data-stu-id="3401e-117">Gets the type of load metric is reported by the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3401e-118">負荷メトリックの種類は、サービスによって報告されます。</span><span class="sxs-lookup"><span data-stu-id="3401e-118">The type of load metric is reported by the service.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlacementConstraints">
      <MemberSignature Language="C#" Value="public string PlacementConstraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PlacementConstraints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceTypeDescription.PlacementConstraints" />
      <MemberSignature Language="VB.NET" Value="Public Property PlacementConstraints As String" />
      <MemberSignature Language="F#" Value="member this.PlacementConstraints : string with get, set" Usage="System.Fabric.Description.ServiceTypeDescription.PlacementConstraints" />
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
          <para><span data-ttu-id="3401e-119">取得または Service Fabric クラスター内のこのサービスをインスタンス化するときに使用される制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="3401e-119">Gets or sets the constraint to be used when instantiating this service in a Service Fabric cluster.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3401e-120">Service Fabric クラスター内のこのサービスをインスタンス化するときに使用する制約です。</span><span class="sxs-lookup"><span data-stu-id="3401e-120">The constraint to be used when instantiating this service in a Service Fabric cluster.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Policies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.List&lt;System.Fabric.Description.ServicePlacementPolicyDescription&gt; Policies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.List`1&lt;class System.Fabric.Description.ServicePlacementPolicyDescription&gt; Policies" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceTypeDescription.Policies" />
      <MemberSignature Language="VB.NET" Value="Public Property Policies As List(Of ServicePlacementPolicyDescription)" />
      <MemberSignature Language="F#" Value="member this.Policies : System.Collections.Generic.List&lt;System.Fabric.Description.ServicePlacementPolicyDescription&gt; with get, set" Usage="System.Fabric.Description.ServiceTypeDescription.Policies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;System.Fabric.Description.ServicePlacementPolicyDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3401e-121">サービスの種類のポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="3401e-121">Gets the policies of the service type.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3401e-122">サービスのポリシーを入力します。</span><span class="sxs-lookup"><span data-stu-id="3401e-122">The policies of the service type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadCommonProperties">
      <MemberSignature Language="C#" Value="protected internal void ReadCommonProperties (IntPtr serviceTypeName, IntPtr placementConstraints, IntPtr loadMetricsList, IntPtr descriptionExtensionList);" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig instance void ReadCommonProperties(native int serviceTypeName, native int placementConstraints, native int loadMetricsList, native int descriptionExtensionList) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceTypeDescription.ReadCommonProperties(System.IntPtr,System.IntPtr,System.IntPtr,System.IntPtr)" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Sub ReadCommonProperties (serviceTypeName As IntPtr, placementConstraints As IntPtr, loadMetricsList As IntPtr, descriptionExtensionList As IntPtr)" />
      <MemberSignature Language="F#" Value="member this.ReadCommonProperties : nativeint * nativeint * nativeint * nativeint -&gt; unit" Usage="serviceTypeDescription.ReadCommonProperties (serviceTypeName, placementConstraints, loadMetricsList, descriptionExtensionList)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.IntPtr" />
        <Parameter Name="placementConstraints" Type="System.IntPtr" />
        <Parameter Name="loadMetricsList" Type="System.IntPtr" />
        <Parameter Name="descriptionExtensionList" Type="System.IntPtr" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="3401e-123">サービスの種類の名前。</span><span class="sxs-lookup"><span data-stu-id="3401e-123">The name of the service type.</span></span></para>
        </param>
        <param name="placementConstraints">
          <para><span data-ttu-id="3401e-124">使用する制約です。</span><span class="sxs-lookup"><span data-stu-id="3401e-124">The constraints to be used.</span></span></para>
        </param>
        <param name="loadMetricsList">
          <para><span data-ttu-id="3401e-125">負荷メトリックの型。</span><span class="sxs-lookup"><span data-stu-id="3401e-125">The type of load metric.</span></span></para>
        </param>
        <param name="descriptionExtensionList">
          <para><span data-ttu-id="3401e-126">説明の拡張機能 ボックスの一覧です。</span><span class="sxs-lookup"><span data-stu-id="3401e-126">The description extension list.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="3401e-127">サービスの種類のプロパティを読み取ります。</span><span class="sxs-lookup"><span data-stu-id="3401e-127">Reads the properties of the service type.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ServiceDescriptionKind ServiceTypeKind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ServiceDescriptionKind ServiceTypeKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceTypeDescription.ServiceTypeKind" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceTypeKind As ServiceDescriptionKind" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeKind : System.Fabric.Description.ServiceDescriptionKind with get, set" Usage="System.Fabric.Description.ServiceTypeDescription.ServiceTypeKind" />
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
          <para><span data-ttu-id="3401e-128">取得またはサービス型の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="3401e-128">Gets or sets the kind of service type.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3401e-129">サービスの種類の種類。</span><span class="sxs-lookup"><span data-stu-id="3401e-129">The kind of service type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceTypeDescription.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string with get, set" Usage="System.Fabric.Description.ServiceTypeDescription.ServiceTypeName" />
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
          <para><span data-ttu-id="3401e-130">取得またはサービスの種類の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="3401e-130">Gets or sets the name of the service type.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3401e-131">サービスの種類の名前。</span><span class="sxs-lookup"><span data-stu-id="3401e-131">The name of the service type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>