<Type Name="IServicesOperations" FullName="Microsoft.Azure.Management.Search.IServicesOperations">
  <TypeSignature Language="C#" Value="public interface IServicesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServicesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.IServicesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServicesOperations" />
  <TypeSignature Language="F#" Value="type IServicesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="47291-101">ServicesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="47291-101">ServicesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckNameAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync (string name, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync(string name, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.IServicesOperations.CheckNameAvailabilityWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckNameAvailabilityWithHttpMessagesAsync : string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput&gt;&gt;" Usage="iServicesOperations.CheckNameAvailabilityWithHttpMessagesAsync (name, searchManagementRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
            <span data-ttu-id="47291-102">検証する検索サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="47291-102">The Search service name to validate.</span></span> <span data-ttu-id="47291-103">検索サービス名は、小文字、数字、ダッシュのみを含める必要があります、最初の 2 つ、または最後の 1 文字としてダッシュを使用することはできません、連続するダッシュ文字を含めることはできません、および 2 ~ 60 文字の長さの間である必要がありますをします。</span><span class="sxs-lookup"><span data-stu-id="47291-103">Search service names must only contain lowercase letters, digits or dashes, cannot use dash as the first two or last one characters, cannot contain consecutive dashes, and must be between 2 and 60 characters in length.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="47291-104">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="47291-104">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="47291-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="47291-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="47291-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="47291-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="47291-107">指定した検索サービス名が使用できるかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="47291-107">Checks whether or not the given Search service name is available for use.</span></span> <span data-ttu-id="47291-108">サービス URI の一部であるために、検索サービス名がグローバルに一意にする必要があります (https://&lt;名前&gt;。 &lt;name&gt;.search.windows.net)。</span><span class="sxs-lookup"><span data-stu-id="47291-108">Search service names must be globally unique since they are part of the service URI (https://&lt;name&gt;.search.windows.net).</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="47291-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="47291-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="47291-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="47291-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="47291-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="47291-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchService service, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchService service, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.IServicesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchService,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Search.Models.SearchService * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt;" Usage="iServicesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, searchServiceName, service, searchManagementRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="service" Type="Microsoft.Azure.Management.Search.Models.SearchService" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="47291-112">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="47291-112">The name of the resource group within the current subscription.</span></span>
            <span data-ttu-id="47291-113">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="47291-113">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="47291-114">Azure Search サービスを作成または更新の名前。</span><span class="sxs-lookup"><span data-stu-id="47291-114">The name of the Azure Search service to create or update.</span></span> <span data-ttu-id="47291-115">検索サービス名は、小文字、数字、ダッシュのみを含める必要があります、最初の 2 つ、または最後の 1 文字としてダッシュを使用することはできません、連続するダッシュ文字を含めることはできません、および 2 ~ 60 文字の長さの間である必要がありますをします。</span><span class="sxs-lookup"><span data-stu-id="47291-115">Search service names must only contain lowercase letters, digits or dashes, cannot use dash as the first two or last one characters, cannot contain consecutive dashes, and must be between 2 and 60 characters in length.</span></span> <span data-ttu-id="47291-116">サービス URI の一部であるために、検索サービス名がグローバルに一意にする必要があります (https://&lt;名前&gt;。 &lt;name&gt;.search.windows.net)。</span><span class="sxs-lookup"><span data-stu-id="47291-116">Search service names must be globally unique since they are part of the service URI (https://&lt;name&gt;.search.windows.net).</span></span> <span data-ttu-id="47291-117">サービスの作成後は、サービス名を変更できません。</span><span class="sxs-lookup"><span data-stu-id="47291-117">You cannot change the service name after the service is created.</span></span>
            </param>
        <param name="service">
            <span data-ttu-id="47291-118">Search サービスを作成または更新の定義。</span><span class="sxs-lookup"><span data-stu-id="47291-118">The definition of the Search service to create or update.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="47291-119">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="47291-119">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="47291-120">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="47291-120">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="47291-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="47291-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="47291-122">作成するか、特定のリソース グループ内の Search サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="47291-122">Creates or updates a Search service in the given resource group.</span></span>
            <span data-ttu-id="47291-123">Search サービスが既に存在する場合、すべてのプロパティが指定された値で更新されます。</span><span class="sxs-lookup"><span data-stu-id="47291-123">If the Search service already exists, all properties will be updated with the given values.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="47291-124">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="47291-124">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="47291-125">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="47291-125">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="47291-126">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="47291-126">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.IServicesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iServicesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, searchServiceName, searchManagementRequestOptions, customHeaders, cancellationToken)" />
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
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="47291-127">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="47291-127">The name of the resource group within the current subscription.</span></span>
            <span data-ttu-id="47291-128">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="47291-128">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="47291-129">指定されたリソース グループに関連付けられている Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="47291-129">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="47291-130">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="47291-130">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="47291-131">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="47291-131">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="47291-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="47291-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="47291-133">関連付けられているリソースと、特定のリソース グループ内の Search サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="47291-133">Deletes a Search service in the given resource group, along with its associated resources.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="47291-134">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="47291-134">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="47291-135">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="47291-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.IServicesOperations.GetWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt;" Usage="iServicesOperations.GetWithHttpMessagesAsync (resourceGroupName, searchServiceName, searchManagementRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt;</ReturnType>
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
            <span data-ttu-id="47291-136">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="47291-136">The name of the resource group within the current subscription.</span></span>
            <span data-ttu-id="47291-137">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="47291-137">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="47291-138">指定されたリソース グループに関連付けられている Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="47291-138">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="47291-139">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="47291-139">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="47291-140">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="47291-140">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="47291-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="47291-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="47291-142">指定したリソース グループ内の指定した名前で検索サービスを取得します。</span><span class="sxs-lookup"><span data-stu-id="47291-142">Gets the Search service with the given name in the given resource group.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="47291-143">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="47291-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="47291-144">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="47291-144">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="47291-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="47291-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.IServicesOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt;&gt;" Usage="iServicesOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, searchManagementRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="47291-146">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="47291-146">The name of the resource group within the current subscription.</span></span>
            <span data-ttu-id="47291-147">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="47291-147">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="47291-148">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="47291-148">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="47291-149">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="47291-149">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="47291-150">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="47291-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="47291-151">指定したリソース グループ内のすべての検索サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="47291-151">Gets a list of all Search services in the given resource group.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="47291-152">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="47291-152">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="47291-153">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="47291-153">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="47291-154">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="47291-154">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>