<Type Name="IResourcesOperations" FullName="Microsoft.Azure.Management.ResourceManager.IResourcesOperations">
  <TypeSignature Language="C#" Value="public interface IResourcesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IResourcesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.IResourcesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IResourcesOperations" />
  <TypeSignature Language="F#" Value="type IResourcesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cac2d-101">ResourcesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-101">ResourcesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateByIdWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; BeginCreateOrUpdateByIdWithHttpMessagesAsync (string resourceId, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; BeginCreateOrUpdateByIdWithHttpMessagesAsync(string resourceId, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.BeginCreateOrUpdateByIdWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateByIdWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;" Usage="iResourcesOperations.BeginCreateOrUpdateByIdWithHttpMessagesAsync (resourceId, apiVersion, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceId">
            <span data-ttu-id="cac2d-102">リソース名とリソースの種類を含む、リソースの完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-102">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="cac2d-103">形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}</span><span class="sxs-lookup"><span data-stu-id="cac2d-103">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="cac2d-104">操作に使用する API バージョン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-104">The API version to use for the operation.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cac2d-105">作成またはリソース パラメーターを更新します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-105">Create or update resource parameters.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-108">ID でリソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-108">Create a resource by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cac2d-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;" Usage="iResourcesOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cac2d-112">リソースのリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cac2d-112">The name of the resource group for the resource.</span></span> <span data-ttu-id="cac2d-113">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-113">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="cac2d-114">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-114">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="cac2d-115">親のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-115">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="cac2d-116">作成するリソースのリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="cac2d-116">The resource type of the resource to create.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cac2d-117">作成するリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="cac2d-117">The name of the resource to create.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="cac2d-118">操作に使用する API バージョン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-118">The API version to use for the operation.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cac2d-119">作成またはリソースを更新するためのパラメーター。</span><span class="sxs-lookup"><span data-stu-id="cac2d-119">Parameters for creating or updating the resource.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-120">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-120">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-122">リソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-122">Creates a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-123">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-123">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cac2d-124">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-124">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-125">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-125">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteByIdWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteByIdWithHttpMessagesAsync (string resourceId, string apiVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteByIdWithHttpMessagesAsync(string resourceId, string apiVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.BeginDeleteByIdWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteByIdWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iResourcesOperations.BeginDeleteByIdWithHttpMessagesAsync (resourceId, apiVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceId">
            <span data-ttu-id="cac2d-126">リソース名とリソースの種類を含む、リソースの完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-126">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="cac2d-127">形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}</span><span class="sxs-lookup"><span data-stu-id="cac2d-127">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="cac2d-128">操作に使用する API バージョン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-128">The API version to use for the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-129">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-129">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-131">ID でリソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-131">Deletes a resource by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-132">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-132">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iResourcesOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cac2d-134">削除するリソースが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cac2d-134">The name of the resource group that contains the resource to delete.</span></span> <span data-ttu-id="cac2d-135">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-135">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="cac2d-136">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-136">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="cac2d-137">親のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-137">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="cac2d-138">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="cac2d-138">The resource type.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cac2d-139">削除するリソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-139">The name of the resource to delete.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="cac2d-140">操作に使用する API バージョン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-140">The API version to use for the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-141">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-141">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-143">リソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-143">Deletes a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-144">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-144">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginMoveResourcesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginMoveResourcesWithHttpMessagesAsync (string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginMoveResourcesWithHttpMessagesAsync(string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.BeginMoveResourcesWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginMoveResourcesWithHttpMessagesAsync : string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iResourcesOperations.BeginMoveResourcesWithHttpMessagesAsync (sourceResourceGroupName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceResourceGroupName">
            <span data-ttu-id="cac2d-146">移動するリソースを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cac2d-146">The name of the resource group containing the resources to move.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cac2d-147">リソースの移動のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="cac2d-147">Parameters for moving resources.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-148">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-148">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-150">リソースを 1 つのリソース グループから別のリソース グループに移動します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-150">Moves resources from one resource group to another resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cac2d-151">移動するリソースは、同じソース リソース グループである必要があります。</span><span class="sxs-lookup"><span data-stu-id="cac2d-151">The resources to move must be in the same source resource group.</span></span>
            <span data-ttu-id="cac2d-152">ターゲット リソース グループは、別のサブスクリプションがあります。</span><span class="sxs-lookup"><span data-stu-id="cac2d-152">The target resource group may be in a different subscription.</span></span> <span data-ttu-id="cac2d-153">リソースを移動するときに、ソース グループと、対象グループの両方がロックされている操作の実行中です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-153">When moving resources, both the source group and the target group are locked for the duration of the operation.</span></span> <span data-ttu-id="cac2d-154">これらのグループに対する書き込み操作および削除操作は、移動が完了するまでブロックされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-154">Write and delete operations are blocked on the groups until the move completes.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-155">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-155">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginValidateMoveResourcesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginValidateMoveResourcesWithHttpMessagesAsync (string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginValidateMoveResourcesWithHttpMessagesAsync(string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.BeginValidateMoveResourcesWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginValidateMoveResourcesWithHttpMessagesAsync : string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iResourcesOperations.BeginValidateMoveResourcesWithHttpMessagesAsync (sourceResourceGroupName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceResourceGroupName">
            <span data-ttu-id="cac2d-157">検証するため、リソースを含む、リソース グループの名前に移動します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-157">The name of the resource group containing the resources to validate for move.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cac2d-158">リソースの移動のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="cac2d-158">Parameters for moving resources.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-159">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-159">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-161">リソースは、別のリソース グループを 1 つのリソース グループから移動できるかどうかを検証します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-161">Validates whether resources can be moved from one resource group to another resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cac2d-162">この操作は、指定したリソースをターゲットに移動できるかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-162">This operation checks whether the specified resources can be moved to the target.</span></span> <span data-ttu-id="cac2d-163">移動するリソースは、同じソース リソース グループである必要があります。</span><span class="sxs-lookup"><span data-stu-id="cac2d-163">The resources to move must be in the same source resource group.</span></span> <span data-ttu-id="cac2d-164">ターゲット リソース グループは、別のサブスクリプションがあります。</span><span class="sxs-lookup"><span data-stu-id="cac2d-164">The target resource group may be in a different subscription.</span></span> <span data-ttu-id="cac2d-165">検証が成功した場合は、HTTP 応答コード 204 (コンテンツなし) を返します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-165">If validation succeeds, it returns HTTP response code 204 (no content).</span></span> <span data-ttu-id="cac2d-166">検証に失敗した場合は、エラー メッセージを HTTP 応答コード 409 (Conflict) を返します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-166">If validation fails, it returns HTTP response code 409 (Conflict) with an error message.</span></span> <span data-ttu-id="cac2d-167">実行時間の長い操作の結果を確認する場所ヘッダーの値に URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-167">Retrieve the URL in the Location header value to check the result of the long-running operation.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-168">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-168">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-169">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-169">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceByIdWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt; CheckExistenceByIdWithHttpMessagesAsync (string resourceId, string apiVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;bool&gt;&gt; CheckExistenceByIdWithHttpMessagesAsync(string resourceId, string apiVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.CheckExistenceByIdWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckExistenceByIdWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt;" Usage="iResourcesOperations.CheckExistenceByIdWithHttpMessagesAsync (resourceId, apiVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceId">
            <span data-ttu-id="cac2d-170">リソース名とリソースの種類を含む、リソースの完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-170">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="cac2d-171">形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}</span><span class="sxs-lookup"><span data-stu-id="cac2d-171">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="cac2d-172">操作に使用する API バージョン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-172">The API version to use for the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-173">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-173">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-175">ID によってリソースが存在するかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-175">Checks by ID whether a resource exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-176">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-176">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-177">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-177">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt; CheckExistenceWithHttpMessagesAsync (string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;bool&gt;&gt; CheckExistenceWithHttpMessagesAsync(string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.CheckExistenceWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckExistenceWithHttpMessagesAsync : string * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt;" Usage="iResourcesOperations.CheckExistenceWithHttpMessagesAsync (resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cac2d-178">チェックするリソースを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cac2d-178">The name of the resource group containing the resource to check.</span></span>
            <span data-ttu-id="cac2d-179">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-179">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="cac2d-180">チェックするリソースのリソース プロバイダーです。</span><span class="sxs-lookup"><span data-stu-id="cac2d-180">The resource provider of the resource to check.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="cac2d-181">親のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-181">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="cac2d-182">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="cac2d-182">The resource type.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cac2d-183">存在するかどうかをチェックするリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="cac2d-183">The name of the resource to check whether it exists.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="cac2d-184">操作に使用する API バージョン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-184">The API version to use for the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-185">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-185">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-186">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-187">リソースが存在するかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-187">Checks whether a resource exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-188">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-188">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-189">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-189">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateByIdWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; CreateOrUpdateByIdWithHttpMessagesAsync (string resourceId, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; CreateOrUpdateByIdWithHttpMessagesAsync(string resourceId, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.CreateOrUpdateByIdWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateByIdWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;" Usage="iResourcesOperations.CreateOrUpdateByIdWithHttpMessagesAsync (resourceId, apiVersion, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceId">
            <span data-ttu-id="cac2d-190">リソース名とリソースの種類を含む、リソースの完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-190">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="cac2d-191">形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}</span><span class="sxs-lookup"><span data-stu-id="cac2d-191">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="cac2d-192">操作に使用する API バージョン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-192">The API version to use for the operation.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cac2d-193">作成またはリソース パラメーターを更新します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-193">Create or update resource parameters.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-194">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-194">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-195">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-195">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-196">ID でリソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-196">Create a resource by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-197">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-197">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cac2d-198">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-198">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-199">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-199">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;" Usage="iResourcesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cac2d-200">リソースのリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cac2d-200">The name of the resource group for the resource.</span></span> <span data-ttu-id="cac2d-201">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-201">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="cac2d-202">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-202">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="cac2d-203">親のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-203">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="cac2d-204">作成するリソースのリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="cac2d-204">The resource type of the resource to create.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cac2d-205">作成するリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="cac2d-205">The name of the resource to create.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="cac2d-206">操作に使用する API バージョン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-206">The API version to use for the operation.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cac2d-207">作成またはリソースを更新するためのパラメーター。</span><span class="sxs-lookup"><span data-stu-id="cac2d-207">Parameters for creating or updating the resource.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-208">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-208">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-209">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-210">リソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-210">Creates a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-211">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-211">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cac2d-212">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-212">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-213">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-213">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteByIdWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteByIdWithHttpMessagesAsync (string resourceId, string apiVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteByIdWithHttpMessagesAsync(string resourceId, string apiVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.DeleteByIdWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteByIdWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iResourcesOperations.DeleteByIdWithHttpMessagesAsync (resourceId, apiVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceId">
            <span data-ttu-id="cac2d-214">リソース名とリソースの種類を含む、リソースの完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-214">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="cac2d-215">形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}</span><span class="sxs-lookup"><span data-stu-id="cac2d-215">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="cac2d-216">操作に使用する API バージョン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-216">The API version to use for the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-217">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-217">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-218">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-219">ID でリソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-219">Deletes a resource by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-220">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-220">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-221">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-221">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iResourcesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cac2d-222">削除するリソースが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cac2d-222">The name of the resource group that contains the resource to delete.</span></span> <span data-ttu-id="cac2d-223">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-223">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="cac2d-224">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-224">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="cac2d-225">親のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-225">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="cac2d-226">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="cac2d-226">The resource type.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cac2d-227">削除するリソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-227">The name of the resource to delete.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="cac2d-228">操作に使用する API バージョン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-228">The API version to use for the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-229">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-229">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-230">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-230">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-231">リソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-231">Deletes a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-232">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-232">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-233">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-233">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetByIdWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; GetByIdWithHttpMessagesAsync (string resourceId, string apiVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; GetByIdWithHttpMessagesAsync(string resourceId, string apiVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.GetByIdWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByIdWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;" Usage="iResourcesOperations.GetByIdWithHttpMessagesAsync (resourceId, apiVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceId">
            <span data-ttu-id="cac2d-234">リソース名とリソースの種類を含む、リソースの完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-234">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="cac2d-235">形式を使用して subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name/}</span><span class="sxs-lookup"><span data-stu-id="cac2d-235">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="cac2d-236">操作に使用する API バージョン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-236">The API version to use for the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-237">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-237">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-238">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-239">ID でリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-239">Gets a resource by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-240">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-240">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cac2d-241">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-241">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-242">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-242">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;" Usage="iResourcesOperations.GetWithHttpMessagesAsync (resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cac2d-243">取得するリソースを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cac2d-243">The name of the resource group containing the resource to get.</span></span> <span data-ttu-id="cac2d-244">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-244">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="cac2d-245">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-245">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="cac2d-246">親のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-246">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="cac2d-247">リソースのリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="cac2d-247">The resource type of the resource.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cac2d-248">取得するリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="cac2d-248">The name of the resource to get.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="cac2d-249">操作に使用する API バージョン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-249">The API version to use for the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-250">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-250">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-251">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-251">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-252">リソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-252">Gets a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-253">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-253">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cac2d-254">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-254">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-255">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-255">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;&gt;" Usage="iResourcesOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="cac2d-256">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-256">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-257">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-257">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-258">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-258">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-259">リソース グループのすべてのリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-259">Get all the resources for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-260">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-260">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cac2d-261">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-261">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-262">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-262">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;&gt;" Usage="iResourcesOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, odataQuery, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cac2d-263">リソース グループにリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-263">The resource group with the resources to get.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="cac2d-264">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="cac2d-264">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-265">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-265">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-266">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-266">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-267">リソース グループのすべてのリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-267">Get all the resources for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-268">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-268">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cac2d-269">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-269">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-270">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-270">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;&gt;" Usage="iResourcesOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="cac2d-271">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-271">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-272">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-272">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-273">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-273">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-274">サブスクリプション内のすべてのリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-274">Get all the resources in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-275">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-275">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cac2d-276">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-276">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-277">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-277">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.ListWithHttpMessagesAsync(Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;&gt;" Usage="iResourcesOperations.ListWithHttpMessagesAsync (odataQuery, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="odataQuery">
            <span data-ttu-id="cac2d-278">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="cac2d-278">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-279">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-279">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-280">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-280">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-281">サブスクリプション内のすべてのリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-281">Get all the resources in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-282">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-282">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cac2d-283">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-283">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-284">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-284">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveResourcesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; MoveResourcesWithHttpMessagesAsync (string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; MoveResourcesWithHttpMessagesAsync(string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.MoveResourcesWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MoveResourcesWithHttpMessagesAsync : string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iResourcesOperations.MoveResourcesWithHttpMessagesAsync (sourceResourceGroupName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceResourceGroupName">
            <span data-ttu-id="cac2d-285">移動するリソースを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cac2d-285">The name of the resource group containing the resources to move.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cac2d-286">リソースの移動のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="cac2d-286">Parameters for moving resources.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-287">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-287">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-288">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-288">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-289">リソースを 1 つのリソース グループから別のリソース グループに移動します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-289">Moves resources from one resource group to another resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cac2d-290">移動するリソースは、同じソース リソース グループである必要があります。</span><span class="sxs-lookup"><span data-stu-id="cac2d-290">The resources to move must be in the same source resource group.</span></span>
            <span data-ttu-id="cac2d-291">ターゲット リソース グループは、別のサブスクリプションがあります。</span><span class="sxs-lookup"><span data-stu-id="cac2d-291">The target resource group may be in a different subscription.</span></span> <span data-ttu-id="cac2d-292">リソースを移動するときに、ソース グループと、対象グループの両方がロックされている操作の実行中です。</span><span class="sxs-lookup"><span data-stu-id="cac2d-292">When moving resources, both the source group and the target group are locked for the duration of the operation.</span></span> <span data-ttu-id="cac2d-293">これらのグループに対する書き込み操作および削除操作は、移動が完了するまでブロックされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-293">Write and delete operations are blocked on the groups until the move completes.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-294">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-294">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-295">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-295">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateMoveResourcesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ValidateMoveResourcesWithHttpMessagesAsync (string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ValidateMoveResourcesWithHttpMessagesAsync(string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IResourcesOperations.ValidateMoveResourcesWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ValidateMoveResourcesWithHttpMessagesAsync : string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iResourcesOperations.ValidateMoveResourcesWithHttpMessagesAsync (sourceResourceGroupName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceResourceGroupName">
            <span data-ttu-id="cac2d-296">検証するため、リソースを含む、リソース グループの名前に移動します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-296">The name of the resource group containing the resources to validate for move.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cac2d-297">リソースの移動のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="cac2d-297">Parameters for moving resources.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cac2d-298">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-298">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cac2d-299">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cac2d-299">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cac2d-300">リソースは、別のリソース グループを 1 つのリソース グループから移動できるかどうかを検証します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-300">Validates whether resources can be moved from one resource group to another resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cac2d-301">この操作は、指定したリソースをターゲットに移動できるかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-301">This operation checks whether the specified resources can be moved to the target.</span></span> <span data-ttu-id="cac2d-302">移動するリソースは、同じソース リソース グループである必要があります。</span><span class="sxs-lookup"><span data-stu-id="cac2d-302">The resources to move must be in the same source resource group.</span></span> <span data-ttu-id="cac2d-303">ターゲット リソース グループは、別のサブスクリプションがあります。</span><span class="sxs-lookup"><span data-stu-id="cac2d-303">The target resource group may be in a different subscription.</span></span> <span data-ttu-id="cac2d-304">検証が成功した場合は、HTTP 応答コード 204 (コンテンツなし) を返します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-304">If validation succeeds, it returns HTTP response code 204 (no content).</span></span> <span data-ttu-id="cac2d-305">検証に失敗した場合は、エラー メッセージを HTTP 応答コード 409 (Conflict) を返します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-305">If validation fails, it returns HTTP response code 409 (Conflict) with an error message.</span></span> <span data-ttu-id="cac2d-306">実行時間の長い操作の結果を確認する場所ヘッダーの値に URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="cac2d-306">Retrieve the URL in the Location header value to check the result of the long-running operation.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cac2d-307">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-307">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cac2d-308">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cac2d-308">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>