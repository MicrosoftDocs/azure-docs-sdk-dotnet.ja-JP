<Type Name="RecommendedElasticPoolsOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecommendedElasticPoolsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecommendedElasticPoolsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecommendedElasticPoolsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecommendedElasticPoolsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c4cc0-101">RecommendedElasticPoolsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-101">Extension methods for RecommendedElasticPoolsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool Get (this Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool Get(class Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRecommendedElasticPoolsOperations, resourceGroupName As String, serverName As String, recommendedElasticPoolName As String) As RecommendedElasticPool" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool" Usage="Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.Get (operations, resourceGroupName, serverName, recommendedElasticPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c4cc0-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c4cc0-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c4cc0-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c4cc0-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-105">The name of the server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="c4cc0-106">取得することをお勧め弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-106">The name of the recommended elastic pool to be retrieved.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c4cc0-107">推奨されるエラスティック プールを取得します。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-107">Gets a recommented elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt; GetAsync (this Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt; GetAsync(class Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;" Usage="Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, recommendedElasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c4cc0-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c4cc0-109">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-109">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c4cc0-110">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-110">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c4cc0-111">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-111">The name of the server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="c4cc0-112">取得することをお勧め弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-112">The name of the recommended elastic pool to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c4cc0-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c4cc0-114">推奨されるエラスティック プールを取得します。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-114">Gets a recommented elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt; ListByServer (this Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt; ListByServer(class Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IRecommendedElasticPoolsOperations, resourceGroupName As String, serverName As String) As IEnumerable(Of RecommendedElasticPool)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;" Usage="Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c4cc0-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c4cc0-116">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-116">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c4cc0-117">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-117">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c4cc0-118">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-118">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c4cc0-119">推奨されるエラスティック プールを返します。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-119">Returns recommended elastic pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions/&lt;ListByServerAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c4cc0-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c4cc0-121">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-121">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c4cc0-122">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-122">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c4cc0-123">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-123">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c4cc0-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c4cc0-125">推奨されるエラスティック プールを返します。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-125">Returns recommended elastic pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt; ListMetrics (this Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt; ListMetrics(class Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.ListMetrics(Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetrics (operations As IRecommendedElasticPoolsOperations, resourceGroupName As String, serverName As String, recommendedElasticPoolName As String) As IEnumerable(Of RecommendedElasticPoolMetric)" />
      <MemberSignature Language="F#" Value="static member ListMetrics : Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;" Usage="Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.ListMetrics (operations, resourceGroupName, serverName, recommendedElasticPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c4cc0-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c4cc0-127">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-127">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c4cc0-128">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-128">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c4cc0-129">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-129">The name of the server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="c4cc0-130">取得することをお勧め弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-130">The name of the recommended elastic pool to be retrieved.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c4cc0-131">推奨されるエラスティック プールのメトリックを返します。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-131">Returns recommented elastic pool metrics.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations operations, string resourceGroupName, string serverName, string recommendedElasticPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions.ListMetricsAsync (operations, resourceGroupName, serverName, recommendedElasticPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.RecommendedElasticPoolsOperationsExtensions/&lt;ListMetricsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c4cc0-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c4cc0-133">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-133">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c4cc0-134">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-134">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c4cc0-135">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-135">The name of the server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="c4cc0-136">取得することをお勧め弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-136">The name of the recommended elastic pool to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c4cc0-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c4cc0-138">推奨されるエラスティック プールのメトリックを返します。</span><span class="sxs-lookup"><span data-stu-id="c4cc0-138">Returns recommented elastic pool metrics.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>