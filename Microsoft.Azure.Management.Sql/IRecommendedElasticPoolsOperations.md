<Type Name="IRecommendedElasticPoolsOperations" FullName="Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations">
  <TypeSignature Language="C#" Value="public interface IRecommendedElasticPoolsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRecommendedElasticPoolsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRecommendedElasticPoolsOperations" />
  <TypeSignature Language="F#" Value="type IRecommendedElasticPoolsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4728c-101">RecommendedElasticPoolsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="4728c-101">RecommendedElasticPoolsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string serverName, string recommendedElasticPoolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;&gt;" Usage="iRecommendedElasticPoolsOperations.GetWithHttpMessagesAsync (resourceGroupName, serverName, recommendedElasticPoolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4728c-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4728c-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4728c-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="4728c-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="4728c-104">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="4728c-104">The name of the server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="4728c-105">取得することをお勧め弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="4728c-105">The name of the recommended elastic pool to be retrieved.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4728c-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4728c-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4728c-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4728c-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4728c-108">推奨されるエラスティック プールを取得します。</span><span class="sxs-lookup"><span data-stu-id="4728c-108">Gets a recommented elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4728c-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4728c-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4728c-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4728c-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4728c-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4728c-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByServerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;&gt;&gt; ListByServerWithHttpMessagesAsync (string resourceGroupName, string serverName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;&gt;&gt; ListByServerWithHttpMessagesAsync(string resourceGroupName, string serverName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations.ListByServerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByServerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;&gt;&gt;" Usage="iRecommendedElasticPoolsOperations.ListByServerWithHttpMessagesAsync (resourceGroupName, serverName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4728c-112">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4728c-112">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4728c-113">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="4728c-113">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="4728c-114">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="4728c-114">The name of the server.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4728c-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4728c-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4728c-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4728c-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4728c-117">推奨されるエラスティック プールを返します。</span><span class="sxs-lookup"><span data-stu-id="4728c-117">Returns recommended elastic pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4728c-118">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4728c-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4728c-119">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4728c-119">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4728c-120">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4728c-120">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;&gt;&gt; ListMetricsWithHttpMessagesAsync (string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;&gt;&gt; ListMetricsWithHttpMessagesAsync(string resourceGroupName, string serverName, string recommendedElasticPoolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IRecommendedElasticPoolsOperations.ListMetricsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;&gt;&gt;" Usage="iRecommendedElasticPoolsOperations.ListMetricsWithHttpMessagesAsync (resourceGroupName, serverName, recommendedElasticPoolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4728c-121">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4728c-121">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4728c-122">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="4728c-122">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="4728c-123">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="4728c-123">The name of the server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="4728c-124">取得することをお勧め弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="4728c-124">The name of the recommended elastic pool to be retrieved.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4728c-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4728c-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4728c-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4728c-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4728c-127">推奨されるエラスティック プールのメトリックを返します。</span><span class="sxs-lookup"><span data-stu-id="4728c-127">Returns recommented elastic pool metrics.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4728c-128">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4728c-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4728c-129">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4728c-129">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4728c-130">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4728c-130">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>