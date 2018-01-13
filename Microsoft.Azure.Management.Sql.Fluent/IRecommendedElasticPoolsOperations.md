<Type Name="IRecommendedElasticPoolsOperations" FullName="Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations">
  <TypeSignature Language="C#" Value="public interface IRecommendedElasticPoolsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRecommendedElasticPoolsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRecommendedElasticPoolsOperations" />
  <TypeSignature Language="F#" Value="type IRecommendedElasticPoolsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9b7a6-101">RecommendedElasticPoolsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-101">RecommendedElasticPoolsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetDatabasesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; GetDatabasesWithHttpMessagesAsync (string resourceGroupName, string serverName, string recommendedElasticPoolName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; GetDatabasesWithHttpMessagesAsync(string resourceGroupName, string serverName, string recommendedElasticPoolName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations.GetDatabasesWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDatabasesWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;" Usage="iRecommendedElasticPoolsOperations.GetDatabasesWithHttpMessagesAsync (resourceGroupName, serverName, recommendedElasticPoolName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9b7a6-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9b7a6-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="9b7a6-104">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-104">The name of the Azure SQL server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="9b7a6-105">取得するには、Azure SQL 弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-105">The name of the Azure SQL Elastic Pool to be retrieved.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="9b7a6-106">取得する Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-106">The name of the Azure SQL database to be retrieved.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9b7a6-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b7a6-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b7a6-109">Azure SQL 推奨弾力性プール内で Azure SQL データベースに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-109">Gets information about an Azure SQL database inside of an Azure SQL Recommended Elastic Pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9b7a6-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9b7a6-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9b7a6-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string serverName, string recommendedElasticPoolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;&gt;" Usage="iRecommendedElasticPoolsOperations.GetWithHttpMessagesAsync (resourceGroupName, serverName, recommendedElasticPoolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;&gt;</ReturnType>
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
            <span data-ttu-id="9b7a6-113">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-113">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9b7a6-114">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-114">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="9b7a6-115">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-115">The name of the Azure SQL server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="9b7a6-116">Azure SQL 推奨弾力性プールを取得するの名前。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-116">The name of the Azure SQL Recommended Elastic Pool to be retrieved.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9b7a6-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b7a6-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b7a6-119">Azure SQL 推奨エラスティック プールに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-119">Gets information about an Azure SQL Recommended Elastic Pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9b7a6-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9b7a6-121">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9b7a6-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListDatabasesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;&gt; ListDatabasesWithHttpMessagesAsync (string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;&gt; ListDatabasesWithHttpMessagesAsync(string resourceGroupName, string serverName, string recommendedElasticPoolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations.ListDatabasesWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListDatabasesWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;&gt;" Usage="iRecommendedElasticPoolsOperations.ListDatabasesWithHttpMessagesAsync (resourceGroupName, serverName, recommendedElasticPoolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;&gt;</ReturnType>
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
            <span data-ttu-id="9b7a6-123">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-123">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9b7a6-124">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-124">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="9b7a6-125">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-125">The name of the Azure SQL server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="9b7a6-126">Azure SQL 推奨弾力性プールを取得するの名前。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-126">The name of the Azure SQL Recommended Elastic Pool to be retrieved.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9b7a6-127">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-127">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b7a6-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b7a6-129">Azure SQL 推奨弾力性プール内での Azure SQL データベースに関する情報を返します。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-129">Returns information about an Azure SQL database inside of an Azure SQL Recommended Elastic Pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9b7a6-130">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-130">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9b7a6-131">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-131">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9b7a6-132">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-132">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt;&gt;&gt; ListMetricsWithHttpMessagesAsync (string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt;&gt;&gt; ListMetricsWithHttpMessagesAsync(string resourceGroupName, string serverName, string recommendedElasticPoolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations.ListMetricsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt;&gt;&gt;" Usage="iRecommendedElasticPoolsOperations.ListMetricsWithHttpMessagesAsync (resourceGroupName, serverName, recommendedElasticPoolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolMetric&gt;&gt;&gt;</ReturnType>
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
            <span data-ttu-id="9b7a6-133">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-133">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9b7a6-134">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-134">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="9b7a6-135">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-135">The name of the Azure SQL server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="9b7a6-136">Azure SQL 推奨弾力性プールを取得するの名前。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-136">The name of the Azure SQL Recommended Elastic Pool to be retrieved.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9b7a6-137">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-137">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b7a6-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b7a6-139">弾力性プールの推奨されるメトリックに関する情報を返します。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-139">Returns information about an recommended elastic pool metrics.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9b7a6-140">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-140">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9b7a6-141">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-141">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9b7a6-142">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-142">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, string serverName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, string serverName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IRecommendedElasticPoolsOperations.ListWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;&gt;&gt;" Usage="iRecommendedElasticPoolsOperations.ListWithHttpMessagesAsync (resourceGroupName, serverName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RecommendedElasticPoolInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9b7a6-143">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-143">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9b7a6-144">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-144">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="9b7a6-145">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-145">The name of the Azure SQL server.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9b7a6-146">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-146">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b7a6-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b7a6-148">Azure SQL 推奨の弾力性プールに関する情報を返します。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-148">Returns information about Azure SQL Recommended Elastic Pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9b7a6-149">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-149">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9b7a6-150">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-150">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9b7a6-151">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b7a6-151">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>