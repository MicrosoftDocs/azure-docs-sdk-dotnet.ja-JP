<Type Name="ApplicationUpdateDescription" FullName="System.Fabric.Description.ApplicationUpdateDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationUpdateDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationUpdateDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationUpdateDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationUpdateDescription" />
  <TypeSignature Language="F#" Value="type ApplicationUpdateDescription = class" />
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
            <span data-ttu-id="9312f-101">使用して更新されるアプリケーション容量の更新について説明します<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" /></span><span class="sxs-lookup"><span data-stu-id="9312f-101">Describes an update of application capacity that will be updated using <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" /></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationUpdateDescription (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationUpdateDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationUpdateDescription : Uri -&gt; System.Fabric.Description.ApplicationUpdateDescription" Usage="new System.Fabric.Description.ApplicationUpdateDescription applicationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="9312f-102">アプリケーション インスタンス名の URI。</span><span class="sxs-lookup"><span data-stu-id="9312f-102">URI of the application instance name.</span></span></param>
        <summary>
            <span data-ttu-id="9312f-103"><see cref="T:System.Fabric.Description.ApplicationUpdateDescription" /> の新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="9312f-103">Creates a new instance of <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationUpdateDescription (Uri applicationName, bool removeApplicationCapacity, long minimumNodes, long maximumNodes, System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt; metrics);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, bool removeApplicationCapacity, int64 minimumNodes, int64 maximumNodes, class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ApplicationMetricDescription&gt; metrics) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationUpdateDescription.#ctor(System.Uri,System.Boolean,System.Int64,System.Int64,System.Collections.Generic.IList{System.Fabric.Description.ApplicationMetricDescription})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, removeApplicationCapacity As Boolean, minimumNodes As Long, maximumNodes As Long, metrics As IList(Of ApplicationMetricDescription))" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationUpdateDescription : Uri * bool * int64 * int64 * System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt; -&gt; System.Fabric.Description.ApplicationUpdateDescription" Usage="new System.Fabric.Description.ApplicationUpdateDescription (applicationName, removeApplicationCapacity, minimumNodes, maximumNodes, metrics)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="removeApplicationCapacity" Type="System.Boolean" />
        <Parameter Name="minimumNodes" Type="System.Int64" />
        <Parameter Name="maximumNodes" Type="System.Int64" />
        <Parameter Name="metrics" Type="System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt;" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="9312f-104">アプリケーション インスタンス名の URI。</span><span class="sxs-lookup"><span data-stu-id="9312f-104">URI of the application instance name.</span></span></param>
        <param name="removeApplicationCapacity">
            <span data-ttu-id="9312f-105">アプリケーションの性能を削除するかどうかを示します (を参照してください<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.RemoveApplicationCapacity" />)。</span><span class="sxs-lookup"><span data-stu-id="9312f-105">Indicates if application capacity should be removed (see <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.RemoveApplicationCapacity" />).</span></span>
            </param>
        <param name="minimumNodes">
            <span data-ttu-id="9312f-106">ノードの最小数 (を参照してください<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />)。</span><span class="sxs-lookup"><span data-stu-id="9312f-106">Minimum number of nodes (see <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />).</span></span>
            </param>
        <param name="maximumNodes">
            <span data-ttu-id="9312f-107">ノードの最大数 (を参照してください<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />)</span><span class="sxs-lookup"><span data-stu-id="9312f-107">Maximum number of nodes (see <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />)</span></span>
            </param>
        <param name="metrics">
            <span data-ttu-id="9312f-108">アプリケーションの容量メトリック (を参照してください<see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" />)</span><span class="sxs-lookup"><span data-stu-id="9312f-108">Application capacity metrics (see <see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" />)</span></span>
            </param>
        <summary>
            <span data-ttu-id="9312f-109">新しいインスタンスを作成<see cref="T:System.Fabric.Description.ApplicationUpdateDescription" />アプリケーション容量パラメーターを使用します。</span><span class="sxs-lookup"><span data-stu-id="9312f-109">Creates a new instance of <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" /> with application capacity parameters.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpdateDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri with get, set" Usage="System.Fabric.Description.ApplicationUpdateDescription.ApplicationName" />
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
          <para><span data-ttu-id="9312f-110">取得またはアプリケーション インスタンスの URI 名を設定します。</span><span class="sxs-lookup"><span data-stu-id="9312f-110">Gets or sets the URI name of the application instance.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="9312f-111">アプリケーション名。</span><span class="sxs-lookup"><span data-stu-id="9312f-111">The application name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaximumNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaximumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumNodes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaximumNodes : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9312f-112">取得または、このアプリケーションをインスタンス化するノードの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="9312f-112">Gets or sets the maximum number of nodes where this application can be instantiated.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="9312f-113">スパンするこのアプリケーションが許可されているノードの数。</span><span class="sxs-lookup"><span data-stu-id="9312f-113">Number of nodes this application is allowed to span.</span></span> <span data-ttu-id="9312f-114">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="9312f-114">Default value is zero.</span></span>
            <span data-ttu-id="9312f-115">ゼロになった場合は、クラスター内のノードの数にかかわらずアプリケーションを配置することができます。</span><span class="sxs-lookup"><span data-stu-id="9312f-115">If it is zero, Application can be placed on any number of nodes in the cluster.</span></span>
            <span data-ttu-id="9312f-116">アプリケーションを更新するときにこのパラメーターが指定されていない場合は、ノードの最大数は変更されません。</span><span class="sxs-lookup"><span data-stu-id="9312f-116">If this parameter is not specified when updating an application, then the maximum number of nodes remains unchanged.</span></span>
            </para>
          <para>
            <span data-ttu-id="9312f-117">このパラメーターがより小さい場合<see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />、<see cref="T:System.ArgumentException" />場合にスローされます<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" />と呼びます。</span><span class="sxs-lookup"><span data-stu-id="9312f-117">If this parameter is smaller than <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" /> an <see cref="T:System.ArgumentException" /> will be thrown when <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" /> is called.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt; Metrics;" />
      <MemberSignature Language="ILAsm" Value=".field public class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ApplicationMetricDescription&gt; Metrics" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public Metrics As IList(Of ApplicationMetricDescription) " />
      <MemberSignature Language="F#" Value="val mutable Metrics : System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt;" Usage="System.Fabric.Description.ApplicationUpdateDescription.Metrics" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.ApplicationMetricDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9312f-118">取得またはアプリケーションの性能が定義されているメトリックのリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="9312f-118">Gets or sets the list of metrics for which the application capacity is defined.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9312f-119">アプリケーションの容量のメトリックを指定します。</span><span class="sxs-lookup"><span data-stu-id="9312f-119">Specifies the metric Capacity of the Application.</span></span> <span data-ttu-id="9312f-120">各メトリックを使用するための容量が指定された<see cref="T:System.Fabric.Description.ApplicationMetricDescription" />です。</span><span class="sxs-lookup"><span data-stu-id="9312f-120">Capacity is specified for each metric using <see cref="T:System.Fabric.Description.ApplicationMetricDescription" />.</span></span>
            <span data-ttu-id="9312f-121">このパラメーターが設定されていない場合、アプリケーションの容量メトリックは変更されませんアプリケーションを更新する場合。</span><span class="sxs-lookup"><span data-stu-id="9312f-121">If this parameter is not set, then application capacity metrics will remain unchanged when updating application.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MinimumNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MinimumNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumNodes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MinimumNodes : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9312f-122">取得またはノードの最小数を設定します。</span><span class="sxs-lookup"><span data-stu-id="9312f-122">Gets or sets the minimum number of nodes.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="9312f-123">Service Fabric が、クラスター内のこのアプリケーションを配置する容量を予約、ノードの数。</span><span class="sxs-lookup"><span data-stu-id="9312f-123">Number of nodes where Service Fabric will reserve Capacity in the cluster for this Application to be placed.</span></span>
            <span data-ttu-id="9312f-124">ある意味ではありませんこれらすべてのノード上のレプリカを保持するアプリケーションが保証されるに注意してください。</span><span class="sxs-lookup"><span data-stu-id="9312f-124">Note that this does not mean that the Application is guaranteed to have replicas on all those nodes.</span></span>
            </para>
          <para>
            <span data-ttu-id="9312f-125">このパラメーターが 0 に設定されている場合は、容量は予約されません。</span><span class="sxs-lookup"><span data-stu-id="9312f-125">If this parameter is set to zero, no capacity will be reserved.</span></span> <span data-ttu-id="9312f-126">アプリケーションを更新するときに、このパラメーターが設定されていない場合は、ノードの最小数は変更されません。</span><span class="sxs-lookup"><span data-stu-id="9312f-126">If this parameter is not set when updating application then the minimum number of nodes remains unchanged.</span></span>
            </para>
          <para>
            <span data-ttu-id="9312f-127">このパラメーターがより大きい場合<see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" />両方のパラメーターが指定されている場合、<see cref="T:System.ArgumentException" />場合にスローされます<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" />と呼びます。</span><span class="sxs-lookup"><span data-stu-id="9312f-127">If this parameters is greater than <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" /> and if both parameters are specified then an <see cref="T:System.ArgumentException" /> will be thrown when <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" /> is called.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveApplicationCapacity">
      <MemberSignature Language="C#" Value="public bool RemoveApplicationCapacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RemoveApplicationCapacity" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpdateDescription.RemoveApplicationCapacity" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoveApplicationCapacity As Boolean" />
      <MemberSignature Language="F#" Value="member this.RemoveApplicationCapacity : bool with get, set" Usage="System.Fabric.Description.ApplicationUpdateDescription.RemoveApplicationCapacity" />
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
            <span data-ttu-id="9312f-128">取得または RemoveApplicationCapacity フラグを設定します。</span><span class="sxs-lookup"><span data-stu-id="9312f-128">Gets or sets the RemoveApplicationCapacity flag.</span></span>
            </summary>
        <value>
            <span data-ttu-id="9312f-129">このアプリケーションのアプリケーションの容量に関連するすべてのパラメーターをオフにするために使用します。</span><span class="sxs-lookup"><span data-stu-id="9312f-129">Used to clear all parameters related to Application Capacity for this application.</span></span>
            <span data-ttu-id="9312f-130">その他のアプリケーションの性能パラメーターと共に、このパラメーターを指定することはできません。</span><span class="sxs-lookup"><span data-stu-id="9312f-130">It is not possible to specify this parameter together with other Application Capacity parameters.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>