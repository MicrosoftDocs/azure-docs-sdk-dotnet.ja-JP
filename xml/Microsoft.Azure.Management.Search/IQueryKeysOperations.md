<Type Name="IQueryKeysOperations" FullName="Microsoft.Azure.Management.Search.IQueryKeysOperations">
  <TypeSignature Language="C#" Value="public interface IQueryKeysOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IQueryKeysOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.IQueryKeysOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IQueryKeysOperations" />
  <TypeSignature Language="F#" Value="type IQueryKeysOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c85e7-101">QueryKeysOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="c85e7-101">QueryKeysOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string searchServiceName, string name, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string searchServiceName, string name, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.IQueryKeysOperations.CreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;" Usage="iQueryKeysOperations.CreateWithHttpMessagesAsync (resourceGroupName, searchServiceName, name, searchManagementRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c85e7-102">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c85e7-102">The name of the resource group within the current subscription.</span></span>
            <span data-ttu-id="c85e7-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="c85e7-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="c85e7-104">指定されたリソース グループに関連付けられている Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="c85e7-104">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="c85e7-105">新しいクエリ API キーの名前。</span><span class="sxs-lookup"><span data-stu-id="c85e7-105">The name of the new query API key.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="c85e7-106">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="c85e7-106">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c85e7-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c85e7-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c85e7-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c85e7-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c85e7-109">指定した Search サービスの新しいクエリ キーを生成します。</span><span class="sxs-lookup"><span data-stu-id="c85e7-109">Generates a new query key for the specified Search service.</span></span> <span data-ttu-id="c85e7-110">サービスごとに最大で 50 個のクエリ キーを作成できます。</span><span class="sxs-lookup"><span data-stu-id="c85e7-110">You can create up to 50 query keys per service.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c85e7-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c85e7-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c85e7-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c85e7-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c85e7-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c85e7-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string searchServiceName, string key, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string searchServiceName, string key, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.IQueryKeysOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iQueryKeysOperations.DeleteWithHttpMessagesAsync (resourceGroupName, searchServiceName, key, searchManagementRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c85e7-114">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c85e7-114">The name of the resource group within the current subscription.</span></span>
            <span data-ttu-id="c85e7-115">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="c85e7-115">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="c85e7-116">指定されたリソース グループに関連付けられている Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="c85e7-116">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="key">
            <span data-ttu-id="c85e7-117">削除するクエリのキー。</span><span class="sxs-lookup"><span data-stu-id="c85e7-117">The query key to be deleted.</span></span> <span data-ttu-id="c85e7-118">クエリ キーは、名前ではなく、値によって識別されます。</span><span class="sxs-lookup"><span data-stu-id="c85e7-118">Query keys are identified by value, not by name.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="c85e7-119">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="c85e7-119">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c85e7-120">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c85e7-120">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c85e7-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c85e7-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c85e7-122">指定されたクエリ キーを削除します。</span><span class="sxs-lookup"><span data-stu-id="c85e7-122">Deletes the specified query key.</span></span> <span data-ttu-id="c85e7-123">管理者キーとは異なりクエリ キーは再生成されません。</span><span class="sxs-lookup"><span data-stu-id="c85e7-123">Unlike admin keys, query keys are not regenerated.</span></span> <span data-ttu-id="c85e7-124">クエリ キーを再生成するには、キーを削除して再作成します。</span><span class="sxs-lookup"><span data-stu-id="c85e7-124">The process for regenerating a query key is to delete and then recreate it.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c85e7-125">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c85e7-125">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c85e7-126">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c85e7-126">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListBySearchServiceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;&gt; ListBySearchServiceWithHttpMessagesAsync (string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;&gt; ListBySearchServiceWithHttpMessagesAsync(string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.IQueryKeysOperations.ListBySearchServiceWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBySearchServiceWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;&gt;" Usage="iQueryKeysOperations.ListBySearchServiceWithHttpMessagesAsync (resourceGroupName, searchServiceName, searchManagementRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c85e7-127">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c85e7-127">The name of the resource group within the current subscription.</span></span>
            <span data-ttu-id="c85e7-128">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="c85e7-128">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="c85e7-129">指定されたリソース グループに関連付けられている Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="c85e7-129">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="c85e7-130">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="c85e7-130">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c85e7-131">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c85e7-131">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c85e7-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c85e7-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c85e7-133">特定の Azure Search サービスのクエリ API キーの一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="c85e7-133">Returns the list of query API keys for the given Azure Search service.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c85e7-134">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c85e7-134">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c85e7-135">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c85e7-135">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c85e7-136">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c85e7-136">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>