<Type Name="NodeHealthQueryDescription" FullName="System.Fabric.Description.NodeHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class NodeHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.NodeHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type NodeHealthQueryDescription = class" />
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
      <para><span data-ttu-id="d07dc-101">説明を取得するためのクエリ入力<see cref="T:System.Fabric.Health.NodeHealth" />です。</span><span class="sxs-lookup"><span data-stu-id="d07dc-101">Describes query input for getting <see cref="T:System.Fabric.Health.NodeHealth" />.</span></span> <span data-ttu-id="d07dc-102"><see cref="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.Fabric.Description.NodeHealthQueryDescription)" /> で使用されます。</span><span class="sxs-lookup"><span data-stu-id="d07dc-102">Used by <see cref="M:System.Fabric.FabricClient.HealthClient.GetNodeHealthAsync(System.Fabric.Description.NodeHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeHealthQueryDescription (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.NodeHealthQueryDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (nodeName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.NodeHealthQueryDescription : string -&gt; System.Fabric.Description.NodeHealthQueryDescription" Usage="new System.Fabric.Description.NodeHealthQueryDescription nodeName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="d07dc-103">ノード名。</span><span class="sxs-lookup"><span data-stu-id="d07dc-103">The node name.</span></span> <span data-ttu-id="d07dc-104">null または空にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="d07dc-104">Cannot be null or empty.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="d07dc-105"><see cref="T:System.Fabric.Description.NodeHealthQueryDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d07dc-105">Initializes a new instance of the <see cref="T:System.Fabric.Description.NodeHealthQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="d07dc-106">必須のパラメーターは、null または空にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="d07dc-106">A required parameter can't be null or empty.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.NodeHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.NodeHealthQueryDescription.EventsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthEventsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d07dc-107">取得または設定のコレクションを返すフィルター<see cref="T:System.Fabric.Health.HealthEvent" />ノードで報告します。</span><span class="sxs-lookup"><span data-stu-id="d07dc-107">Gets or sets the filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the node.</span></span> <span data-ttu-id="d07dc-108">フィルターに一致するイベントのみが返されます。</span><span class="sxs-lookup"><span data-stu-id="d07dc-108">Only events that match the filter will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="d07dc-109">正常性イベントを返すフィルター。</span><span class="sxs-lookup"><span data-stu-id="d07dc-109">The filter for the health event.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="d07dc-110">フィルターに一致するイベントのみが返されます。</span><span class="sxs-lookup"><span data-stu-id="d07dc-110">Only events that match the filter will be returned.</span></span> <span data-ttu-id="d07dc-111">すべてのイベントは、集計のノードの正常性状態の評価に使用されます。</span><span class="sxs-lookup"><span data-stu-id="d07dc-111">All events will be used to evaluate the node aggregated health state.</span></span>
            <span data-ttu-id="d07dc-112">フィルターが指定されていない場合は、すべてのイベントが返されます。</span><span class="sxs-lookup"><span data-stu-id="d07dc-112">If the filter is not specified, all events are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.NodeHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ClusterHealthPolicy with get, set" Usage="System.Fabric.Description.NodeHealthQueryDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="d07dc-113">取得または設定、<see cref="T:System.Fabric.Health.ClusterHealthPolicy" />ノードの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="d07dc-113">Gets or sets the <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> used to evaluate the node health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="d07dc-114"><see cref="T:System.Fabric.Health.ClusterHealthPolicy" />ノードの正常性を評価するために使用します。</span><span class="sxs-lookup"><span data-stu-id="d07dc-114">The <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> used to evaluate the node health.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="d07dc-115">正常性ストア マニフェストからクラスターの正常性ポリシーを使用して指定されていない場合 (場合が存在する) または既定の厳密な正常性ポリシー。</span><span class="sxs-lookup"><span data-stu-id="d07dc-115">If not specified, the health store uses the cluster health policy from the manifest (if exists) or the default, strict health policy.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.NodeHealthQueryDescription.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Description.NodeHealthQueryDescription.NodeName" />
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
          <para><span data-ttu-id="d07dc-116">ノード名を取得します。</span><span class="sxs-lookup"><span data-stu-id="d07dc-116">Gets the node name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="d07dc-117">ノード名。</span><span class="sxs-lookup"><span data-stu-id="d07dc-117">The node name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.NodeHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeHealthQueryDescription.ToString " />
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
            <span data-ttu-id="d07dc-118">正常性クエリの説明の文字列表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="d07dc-118">Gets a string representation of the health query description.</span></span>
            </summary>
        <returns><span data-ttu-id="d07dc-119">正常性クエリの説明の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="d07dc-119">A string representation of the health query description.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>