<Type Name="IAppServiceEnvironmentsOperations" FullName="Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations">
  <TypeSignature Language="C#" Value="public interface IAppServiceEnvironmentsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAppServiceEnvironmentsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAppServiceEnvironmentsOperations" />
  <TypeSignature Language="F#" Value="type IAppServiceEnvironmentsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1d8b7-101">AppServiceEnvironmentsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-101">AppServiceEnvironmentsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateMultiRolePoolWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; BeginCreateOrUpdateMultiRolePoolWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; BeginCreateOrUpdateMultiRolePoolWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.BeginCreateOrUpdateMultiRolePoolWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateMultiRolePoolWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.BeginCreateOrUpdateMultiRolePoolWithHttpMessagesAsync (resourceGroupName, name, multiRolePoolEnvelope, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="multiRolePoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-102">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-102">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-103">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-103">Name of the App Service Environment.</span></span>
            </param>
        <param name="multiRolePoolEnvelope">
            <span data-ttu-id="1d8b7-104">マルチロール プールのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-104">Properties of the multi-role pool.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-107">作成またはマルチロール プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-107">Create or update a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-108">作成またはマルチロール プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-108">Create or update a multi-role pool.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource hostingEnvironmentEnvelope, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource hostingEnvironmentEnvelope, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, name, hostingEnvironmentEnvelope, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="hostingEnvironmentEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-112">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-112">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-113">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-113">Name of the App Service Environment.</span></span>
            </param>
        <param name="hostingEnvironmentEnvelope">
            <span data-ttu-id="1d8b7-114">App Service 環境の構成の詳細。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-114">Configuration details of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-117">作成または App Service 環境を更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-117">Create or update an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-118">作成または App Service 環境を更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-118">Create or update an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-119">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-119">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-120">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-120">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWorkerPoolWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; BeginCreateOrUpdateWorkerPoolWithHttpMessagesAsync (string resourceGroupName, string name, string workerPoolName, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; BeginCreateOrUpdateWorkerPoolWithHttpMessagesAsync(string resourceGroupName, string name, string workerPoolName, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.BeginCreateOrUpdateWorkerPoolWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWorkerPoolWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.BeginCreateOrUpdateWorkerPoolWithHttpMessagesAsync (resourceGroupName, name, workerPoolName, workerPoolEnvelope, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="workerPoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-122">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-122">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-123">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-123">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="1d8b7-124">ワーカー プールの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-124">Name of the worker pool.</span></span>
            </param>
        <param name="workerPoolEnvelope">
            <span data-ttu-id="1d8b7-125">ワーカー プールのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-125">Properties of the worker pool.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-126">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-128">作成またはワーカー プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-128">Create or update a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-129">作成またはワーカー プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-129">Create or update a worker pool.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-130">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-130">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-131">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-131">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-132">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-132">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string name, Nullable&lt;bool&gt; forceDelete = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; forceDelete, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAppServiceEnvironmentsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, name, forceDelete, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="forceDelete" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-133">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-133">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-134">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-134">Name of the App Service Environment.</span></span>
            </param>
        <param name="forceDelete">
            <span data-ttu-id="1d8b7-135">指定&lt;コード&gt;true&lt;/code&gt;を App Service 環境には、リソースが含まれている場合でも強制的に削除します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-135">Specify &lt;code&gt;true&lt;/code&gt; to force the deletion even if the App Service Environment contains resources.</span></span> <span data-ttu-id="1d8b7-136">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-136">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-137">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-137">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-139">App Service 環境を削除します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-139">Delete an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-140">App Service 環境を削除します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-140">Delete an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-141">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-141">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-142">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-142">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; BeginResumeNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; BeginResumeNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.BeginResumeNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginResumeNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.BeginResumeNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-143">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-143">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-146">App Service 環境を再開します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-146">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-147">App Service 環境を再開します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-147">Resume an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-148">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-148">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-149">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-149">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-150">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-150">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; BeginResumeWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; BeginResumeWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.BeginResumeWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginResumeWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.BeginResumeWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-151">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-151">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-152">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-152">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-153">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-153">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-155">App Service 環境を再開します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-155">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-156">App Service 環境を再開します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-156">Resume an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-157">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-157">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-158">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-158">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-159">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-159">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginSuspendNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; BeginSuspendNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; BeginSuspendNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.BeginSuspendNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginSuspendNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.BeginSuspendNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-160">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-160">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-161">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-161">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-163">App Service 環境を中断します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-163">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-164">App Service 環境を中断します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-164">Suspend an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-165">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-165">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-166">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-166">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-167">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-167">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginSuspendWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; BeginSuspendWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; BeginSuspendWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.BeginSuspendWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginSuspendWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.BeginSuspendWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-168">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-168">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-169">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-169">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-170">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-170">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-172">App Service 環境を中断します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-172">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-173">App Service 環境を中断します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-173">Suspend an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-174">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-174">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-175">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-175">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-176">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-176">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateMultiRolePoolWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; CreateOrUpdateMultiRolePoolWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; CreateOrUpdateMultiRolePoolWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.CreateOrUpdateMultiRolePoolWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateMultiRolePoolWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.CreateOrUpdateMultiRolePoolWithHttpMessagesAsync (resourceGroupName, name, multiRolePoolEnvelope, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="multiRolePoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-177">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-177">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-178">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-178">Name of the App Service Environment.</span></span>
            </param>
        <param name="multiRolePoolEnvelope">
            <span data-ttu-id="1d8b7-179">マルチロール プールのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-179">Properties of the multi-role pool.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-180">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-180">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-182">作成またはマルチロール プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-182">Create or update a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-183">作成またはマルチロール プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-183">Create or update a multi-role pool.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-184">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-184">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-185">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-185">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-186">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-186">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource hostingEnvironmentEnvelope, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource hostingEnvironmentEnvelope, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, name, hostingEnvironmentEnvelope, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="hostingEnvironmentEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-187">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-187">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-188">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-188">Name of the App Service Environment.</span></span>
            </param>
        <param name="hostingEnvironmentEnvelope">
            <span data-ttu-id="1d8b7-189">App Service 環境の構成の詳細。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-189">Configuration details of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-190">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-190">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-191">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-192">作成または App Service 環境を更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-192">Create or update an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-193">作成または App Service 環境を更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-193">Create or update an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-194">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-194">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-195">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-195">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-196">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-196">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWorkerPoolWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; CreateOrUpdateWorkerPoolWithHttpMessagesAsync (string resourceGroupName, string name, string workerPoolName, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; CreateOrUpdateWorkerPoolWithHttpMessagesAsync(string resourceGroupName, string name, string workerPoolName, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.CreateOrUpdateWorkerPoolWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWorkerPoolWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.CreateOrUpdateWorkerPoolWithHttpMessagesAsync (resourceGroupName, name, workerPoolName, workerPoolEnvelope, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="workerPoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-197">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-197">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-198">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-198">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="1d8b7-199">ワーカー プールの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-199">Name of the worker pool.</span></span>
            </param>
        <param name="workerPoolEnvelope">
            <span data-ttu-id="1d8b7-200">ワーカー プールのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-200">Properties of the worker pool.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-201">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-201">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-202">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-203">作成またはワーカー プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-203">Create or update a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-204">作成またはワーカー プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-204">Create or update a worker pool.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-205">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-205">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-206">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-206">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-207">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-207">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string name, Nullable&lt;bool&gt; forceDelete = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; forceDelete, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAppServiceEnvironmentsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, name, forceDelete, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="forceDelete" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-208">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-208">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-209">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-209">Name of the App Service Environment.</span></span>
            </param>
        <param name="forceDelete">
            <span data-ttu-id="1d8b7-210">指定&lt;コード&gt;true&lt;/code&gt;を App Service 環境には、リソースが含まれている場合でも強制的に削除します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-210">Specify &lt;code&gt;true&lt;/code&gt; to force the deletion even if the App Service Environment contains resources.</span></span> <span data-ttu-id="1d8b7-211">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-211">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-212">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-212">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-213">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-214">App Service 環境を削除します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-214">Delete an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-215">App Service 環境を削除します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-215">Delete an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-216">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-216">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-217">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-217">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDiagnosticsItemWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt;&gt; GetDiagnosticsItemWithHttpMessagesAsync (string resourceGroupName, string name, string diagnosticsName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt;&gt; GetDiagnosticsItemWithHttpMessagesAsync(string resourceGroupName, string name, string diagnosticsName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.GetDiagnosticsItemWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDiagnosticsItemWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.GetDiagnosticsItemWithHttpMessagesAsync (resourceGroupName, name, diagnosticsName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="diagnosticsName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-218">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-218">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-219">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-219">Name of the App Service Environment.</span></span>
            </param>
        <param name="diagnosticsName">
            <span data-ttu-id="1d8b7-220">診断の項目の名前。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-220">Name of the diagnostics item.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-221">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-221">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-222">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-223">App Service 環境の診断の項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-223">Get a diagnostics item for an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-224">App Service 環境の診断の項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-224">Get a diagnostics item for an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-225">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-225">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-226">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-226">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-227">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-227">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetMultiRolePoolWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; GetMultiRolePoolWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; GetMultiRolePoolWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.GetMultiRolePoolWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetMultiRolePoolWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.GetMultiRolePoolWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-228">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-228">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-229">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-229">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-230">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-230">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-231">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-231">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-232">マルチロール プールのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-232">Get properties of a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-233">マルチロール プールのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-233">Get properties of a multi-role pool.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-234">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-234">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-235">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-235">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-236">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-236">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.GetWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-237">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-237">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-238">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-238">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-239">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-239">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-240">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-240">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-241">App Service 環境のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-241">Get the properties of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-242">App Service 環境のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-242">Get the properties of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-243">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-243">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-244">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-244">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-245">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-245">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWorkerPoolWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; GetWorkerPoolWithHttpMessagesAsync (string resourceGroupName, string name, string workerPoolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; GetWorkerPoolWithHttpMessagesAsync(string resourceGroupName, string name, string workerPoolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.GetWorkerPoolWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWorkerPoolWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.GetWorkerPoolWithHttpMessagesAsync (resourceGroupName, name, workerPoolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-246">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-246">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-247">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-247">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="1d8b7-248">ワーカー プールの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-248">Name of the worker pool.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-249">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-249">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-250">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-250">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-251">ワーカー プールのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-251">Get properties of a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-252">ワーカー プールのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-252">Get properties of a worker pool.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-253">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-253">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-254">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-254">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-255">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-255">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAppServicePlansNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;&gt; ListAppServicePlansNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;&gt; ListAppServicePlansNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListAppServicePlansNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAppServicePlansNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListAppServicePlansNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-256">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-256">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-257">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-257">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-258">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-258">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-259">App Service Environment ですべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-259">Get all App Service plans in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-260">App Service Environment ですべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-260">Get all App Service plans in an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-261">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-261">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-262">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-262">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-263">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-263">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAppServicePlansWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;&gt; ListAppServicePlansWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;&gt; ListAppServicePlansWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListAppServicePlansWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAppServicePlansWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListAppServicePlansWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServicePlan&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-264">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-264">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-265">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-265">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-266">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-266">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-267">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-267">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-268">App Service Environment ですべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-268">Get all App Service plans in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-269">App Service Environment ですべての App Service プランを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-269">Get all App Service plans in an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-270">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-270">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-271">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-271">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-272">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-272">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-273">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-273">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-274">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-274">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-275">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-275">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-276">リソース グループ内のすべての App Service 環境を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-276">Get all App Service Environments in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-277">リソース グループ内のすべての App Service 環境を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-277">Get all App Service Environments in a resource group.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-278">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-278">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-279">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-279">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-280">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-280">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-281">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-281">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-282">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-282">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-283">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-283">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-284">リソース グループ内のすべての App Service 環境を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-284">Get all App Service Environments in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-285">リソース グループ内のすべての App Service 環境を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-285">Get all App Service Environments in a resource group.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-286">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-286">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-287">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-287">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-288">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-288">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListCapacitiesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;&gt;&gt; ListCapacitiesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;&gt;&gt; ListCapacitiesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListCapacitiesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListCapacitiesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListCapacitiesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-289">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-289">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-290">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-290">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-291">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-291">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-292">App Service 環境に使用される、使用可能なおよび合計ワーカー容量を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-292">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-293">App Service 環境に使用される、使用可能なおよび合計ワーカー容量を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-293">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-294">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-294">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-295">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-295">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-296">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-296">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListCapacitiesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;&gt;&gt; ListCapacitiesWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;&gt;&gt; ListCapacitiesWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListCapacitiesWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListCapacitiesWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListCapacitiesWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-297">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-297">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-298">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-298">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-299">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-299">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-300">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-300">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-301">App Service 環境に使用される、使用可能なおよび合計ワーカー容量を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-301">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-302">App Service 環境に使用される、使用可能なおよび合計ワーカー容量を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-302">Get the used, available, and total worker capacity an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-303">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-303">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-304">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-304">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-305">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-305">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListDiagnosticsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt;&gt;&gt; ListDiagnosticsWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt;&gt;&gt; ListDiagnosticsWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListDiagnosticsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListDiagnosticsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListDiagnosticsWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentDiagnostics&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-306">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-306">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-307">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-307">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-308">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-308">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-309">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-309">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-310">App Service 環境の診断情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-310">Get diagnostic information for an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-311">App Service 環境の診断情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-311">Get diagnostic information for an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-312">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-312">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-313">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-313">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-314">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-314">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.MetricDefinition&gt;&gt; ListMetricDefinitionsWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.MetricDefinition&gt;&gt; ListMetricDefinitionsWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMetricDefinitionsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricDefinitionsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.MetricDefinition&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMetricDefinitionsWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.MetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-315">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-315">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-316">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-316">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-317">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-317">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-318">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-318">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-319">App Service 環境のグローバルのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-319">Get global metric definitions of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-320">App Service 環境のグローバルのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-320">Get global metric definitions of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-321">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-321">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-322">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-322">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-323">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-323">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListMetricsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListMetricsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMetricsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMetricsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-324">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-324">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-325">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-325">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-326">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-326">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-327">App Service 環境のグローバルのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-327">Get global metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-328">App Service 環境のグローバルのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-328">Get global metrics of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-329">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-329">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-330">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-330">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-331">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-331">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListMetricsWithHttpMessagesAsync (string resourceGroupName, string name, Nullable&lt;bool&gt; details = null, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListMetricsWithHttpMessagesAsync(string resourceGroupName, string name, valuetype System.Nullable`1&lt;bool&gt; details, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMetricsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricsWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMetricsWithHttpMessagesAsync (resourceGroupName, name, details, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-332">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-332">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-333">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-333">Name of the App Service Environment.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="1d8b7-334">指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-334">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span>
            <span data-ttu-id="1d8b7-335">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-335">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="1d8b7-336">使用状況/メトリックのみ、フィルターで指定されたを返します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-336">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="1d8b7-337">フィルターは、odata 構文に準拠します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-337">Filter conforms to odata syntax.</span></span> <span data-ttu-id="1d8b7-338">例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-338">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-339">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-339">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-340">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-340">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-341">App Service 環境のグローバルのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-341">Get global metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-342">App Service 環境のグローバルのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-342">Get global metrics of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-343">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-343">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-344">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-344">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-345">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-345">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricDefinitionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt; ListMultiRoleMetricDefinitionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt; ListMultiRoleMetricDefinitionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMultiRoleMetricDefinitionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMultiRoleMetricDefinitionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMultiRoleMetricDefinitionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-346">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-346">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-347">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-347">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-348">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-348">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-349">App Service 環境のマルチロール プールのメトリック定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-349">Get metric definitions for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-350">App Service 環境のマルチロール プールのメトリック定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-350">Get metric definitions for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-351">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-351">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-352">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-352">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-353">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-353">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricDefinitionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt; ListMultiRoleMetricDefinitionsWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt; ListMultiRoleMetricDefinitionsWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMultiRoleMetricDefinitionsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMultiRoleMetricDefinitionsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMultiRoleMetricDefinitionsWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-354">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-354">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-355">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-355">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-356">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-356">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-357">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-357">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-358">App Service 環境のマルチロール プールのメトリック定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-358">Get metric definitions for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-359">App Service 環境のマルチロール プールのメトリック定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-359">Get metric definitions for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-360">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-360">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-361">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-361">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-362">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-362">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListMultiRoleMetricsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListMultiRoleMetricsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMultiRoleMetricsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMultiRoleMetricsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMultiRoleMetricsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-363">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-363">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-364">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-364">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-365">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-365">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-366">App Service 環境のマルチロール プールのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-366">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-367">App Service 環境のマルチロール プールのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-367">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-368">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-368">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-369">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-369">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-370">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-370">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleMetricsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListMultiRoleMetricsWithHttpMessagesAsync (string resourceGroupName, string name, string startTime = null, string endTime = null, string timeGrain = null, Nullable&lt;bool&gt; details = null, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListMultiRoleMetricsWithHttpMessagesAsync(string resourceGroupName, string name, string startTime, string endTime, string timeGrain, valuetype System.Nullable`1&lt;bool&gt; details, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMultiRoleMetricsWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMultiRoleMetricsWithHttpMessagesAsync : string * string * string * string * string * Nullable&lt;bool&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMultiRoleMetricsWithHttpMessagesAsync (resourceGroupName, name, startTime, endTime, timeGrain, details, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="timeGrain" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-371">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-371">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-372">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-372">Name of the App Service Environment.</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="1d8b7-373">メトリックのクエリの時間を開始しています。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-373">Beginning time of the metrics query.</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="1d8b7-374">メトリックのクエリの終了時刻です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-374">End time of the metrics query.</span></span>
            </param>
        <param name="timeGrain">
            <span data-ttu-id="1d8b7-375">メトリックのクエリの時間粒度。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-375">Time granularity of the metrics query.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="1d8b7-376">指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-376">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span>
            <span data-ttu-id="1d8b7-377">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-377">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="1d8b7-378">使用状況/メトリックのみ、フィルターで指定されたを返します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-378">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="1d8b7-379">フィルターは、odata 構文に準拠します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-379">Filter conforms to odata syntax.</span></span> <span data-ttu-id="1d8b7-380">例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-380">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-381">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-381">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-382">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-382">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-383">App Service 環境のマルチロール プールのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-383">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-384">App Service 環境のマルチロール プールのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-384">Get metrics for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-385">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-385">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-386">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-386">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-387">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-387">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricDefinitionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMultiRolePoolInstanceMetricDefinitionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMultiRolePoolInstanceMetricDefinitionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMultiRolePoolInstanceMetricDefinitionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-388">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-388">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-389">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-389">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-390">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-390">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-391">App Service 環境のマルチロール プールの特定のインスタンスのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-391">Get metric definitions for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-392">App Service 環境のマルチロール プールの特定のインスタンスのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-392">Get metric definitions for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-393">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-393">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-394">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-394">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-395">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-395">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricDefinitionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsWithHttpMessagesAsync (string resourceGroupName, string name, string instance, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt; ListMultiRolePoolInstanceMetricDefinitionsWithHttpMessagesAsync(string resourceGroupName, string name, string instance, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMultiRolePoolInstanceMetricDefinitionsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMultiRolePoolInstanceMetricDefinitionsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMultiRolePoolInstanceMetricDefinitionsWithHttpMessagesAsync (resourceGroupName, name, instance, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-396">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-396">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-397">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-397">Name of the App Service Environment.</span></span>
            </param>
        <param name="instance">
            <span data-ttu-id="1d8b7-398">マルチロール プール内のインスタンスの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-398">Name of the instance in the multi-role pool.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-399">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-399">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-400">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-400">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-401">App Service 環境のマルチロール プールの特定のインスタンスのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-401">Get metric definitions for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-402">App Service 環境のマルチロール プールの特定のインスタンスのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-402">Get metric definitions for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-403">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-403">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-404">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-404">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-405">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-405">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListMultiRolePoolInstanceMetricsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListMultiRolePoolInstanceMetricsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMultiRolePoolInstanceMetricsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMultiRolePoolInstanceMetricsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMultiRolePoolInstanceMetricsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-406">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-406">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-407">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-407">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-408">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-408">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-409">App Service 環境のマルチロール プールの特定のインスタンスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-409">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-410">App Service 環境のマルチロール プールの特定のインスタンスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-410">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-411">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-411">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-412">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-412">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-413">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-413">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolInstanceMetricsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListMultiRolePoolInstanceMetricsWithHttpMessagesAsync (string resourceGroupName, string name, string instance, Nullable&lt;bool&gt; details = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListMultiRolePoolInstanceMetricsWithHttpMessagesAsync(string resourceGroupName, string name, string instance, valuetype System.Nullable`1&lt;bool&gt; details, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMultiRolePoolInstanceMetricsWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMultiRolePoolInstanceMetricsWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMultiRolePoolInstanceMetricsWithHttpMessagesAsync (resourceGroupName, name, instance, details, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-414">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-414">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-415">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-415">Name of the App Service Environment.</span></span>
            </param>
        <param name="instance">
            <span data-ttu-id="1d8b7-416">マルチロール プール内のインスタンスの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-416">Name of the instance in the multi-role pool.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="1d8b7-417">指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-417">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span>
            <span data-ttu-id="1d8b7-418">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-418">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-419">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-419">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-420">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-420">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-421">App Service 環境のマルチロール プールの特定のインスタンスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-421">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-422">App Service 環境のマルチロール プールの特定のインスタンスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-422">Get metrics for a specific instance of a multi-role pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-423">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-423">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-424">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-424">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-425">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-425">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolSkusNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;&gt; ListMultiRolePoolSkusNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;&gt; ListMultiRolePoolSkusNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMultiRolePoolSkusNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMultiRolePoolSkusNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMultiRolePoolSkusNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-426">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-426">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-427">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-427">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-428">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-428">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-429">マルチロール プールを拡張するためには、利用可能な Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-429">Get available SKUs for scaling a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-430">マルチロール プールを拡張するためには、利用可能な Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-430">Get available SKUs for scaling a multi-role pool.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-431">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-431">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-432">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-432">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-433">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-433">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolSkusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;&gt; ListMultiRolePoolSkusWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;&gt; ListMultiRolePoolSkusWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMultiRolePoolSkusWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMultiRolePoolSkusWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMultiRolePoolSkusWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-434">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-434">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-435">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-435">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-436">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-436">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-437">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-437">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-438">マルチロール プールを拡張するためには、利用可能な Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-438">Get available SKUs for scaling a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-439">マルチロール プールを拡張するためには、利用可能な Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-439">Get available SKUs for scaling a multi-role pool.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-440">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-440">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-441">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-441">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-442">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-442">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;&gt; ListMultiRolePoolsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;&gt; ListMultiRolePoolsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMultiRolePoolsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMultiRolePoolsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMultiRolePoolsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-443">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-443">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-444">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-444">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-445">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-445">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-446">マルチロールすべてのプールを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-446">Get all multi-role pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-447">マルチロールすべてのプールを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-447">Get all multi-role pools.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-448">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-448">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-449">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-449">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-450">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-450">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRolePoolsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;&gt; ListMultiRolePoolsWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;&gt; ListMultiRolePoolsWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMultiRolePoolsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMultiRolePoolsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMultiRolePoolsWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-451">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-451">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-452">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-452">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-453">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-453">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-454">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-454">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-455">マルチロールすべてのプールを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-455">Get all multi-role pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-456">マルチロールすべてのプールを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-456">Get all multi-role pools.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-457">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-457">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-458">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-458">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-459">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-459">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleUsagesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;&gt; ListMultiRoleUsagesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;&gt; ListMultiRoleUsagesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMultiRoleUsagesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMultiRoleUsagesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMultiRoleUsagesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-460">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-460">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-461">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-461">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-462">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-462">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-463">App Service 環境のマルチロール プールの使用状況メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-463">Get usage metrics for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-464">App Service 環境のマルチロール プールの使用状況メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-464">Get usage metrics for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-465">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-465">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-466">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-466">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-467">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-467">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMultiRoleUsagesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;&gt; ListMultiRoleUsagesWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;&gt; ListMultiRoleUsagesWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListMultiRoleUsagesWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMultiRoleUsagesWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListMultiRoleUsagesWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-468">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-468">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-469">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-469">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-470">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-470">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-471">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-471">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-472">App Service 環境のマルチロール プールの使用状況メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-472">Get usage metrics for a multi-role pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-473">App Service 環境のマルチロール プールの使用状況メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-473">Get usage metrics for a multi-role pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-474">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-474">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-475">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-475">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-476">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-476">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-477">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-477">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-478">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-478">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-479">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-479">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-480">App Service 環境のすべてのサブスクリプションを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-480">Get all App Service Environments for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-481">App Service 環境のすべてのサブスクリプションを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-481">Get all App Service Environments for a subscription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-482">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-482">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-483">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-483">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-484">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-484">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListOperationsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Operation&gt;&gt;&gt; ListOperationsWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Operation&gt;&gt;&gt; ListOperationsWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListOperationsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListOperationsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Operation&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListOperationsWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Operation&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-485">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-485">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-486">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-486">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-487">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-487">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-488">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-488">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-489">App Service 環境の現在実行されているすべての操作を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-489">List all currently running operations on the App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-490">App Service 環境の現在実行されているすべての操作を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-490">List all currently running operations on the App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-491">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-491">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-492">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-492">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-493">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-493">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;&gt; ListUsagesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;&gt; ListUsagesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListUsagesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListUsagesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListUsagesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-494">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-494">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-495">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-495">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-496">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-496">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-497">App Service 環境のグローバルの使用状況メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-497">Get global usage metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-498">App Service 環境のグローバルの使用状況メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-498">Get global usage metrics of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-499">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-499">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-500">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-500">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-501">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-501">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;&gt; ListUsagesWithHttpMessagesAsync (string resourceGroupName, string name, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;&gt; ListUsagesWithHttpMessagesAsync(string resourceGroupName, string name, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListUsagesWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListUsagesWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListUsagesWithHttpMessagesAsync (resourceGroupName, name, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.CsmUsageQuota&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-502">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-502">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-503">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-503">Name of the App Service Environment.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="1d8b7-504">使用状況/メトリックのみ、フィルターで指定されたを返します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-504">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="1d8b7-505">フィルターは、odata 構文に準拠します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-505">Filter conforms to odata syntax.</span></span> <span data-ttu-id="1d8b7-506">例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-506">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-507">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-507">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-508">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-508">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-509">App Service 環境のグローバルの使用状況メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-509">Get global usage metrics of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-510">App Service 環境のグローバルの使用状況メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-510">Get global usage metrics of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-511">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-511">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-512">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-512">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-513">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-513">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListVipsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AddressResponse&gt;&gt; ListVipsWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.AddressResponse&gt;&gt; ListVipsWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListVipsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListVipsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AddressResponse&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListVipsWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AddressResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-514">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-514">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-515">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-515">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-516">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-516">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-517">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-517">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-518">App Service 環境に割り当てる IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-518">Get IP addresses assigned to an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-519">App Service 環境に割り当てる IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-519">Get IP addresses assigned to an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-520">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-520">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-521">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-521">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-522">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-522">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; ListWebAppsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; ListWebAppsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWebAppsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWebAppsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWebAppsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-523">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-523">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-524">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-524">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-525">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-525">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-526">App Service Environment ですべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-526">Get all apps in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-527">App Service Environment ですべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-527">Get all apps in an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-528">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-528">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-529">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-529">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-530">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-530">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWebAppsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; ListWebAppsWithHttpMessagesAsync (string resourceGroupName, string name, string propertiesToInclude = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; ListWebAppsWithHttpMessagesAsync(string resourceGroupName, string name, string propertiesToInclude, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWebAppsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWebAppsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWebAppsWithHttpMessagesAsync (resourceGroupName, name, propertiesToInclude, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="propertiesToInclude" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-531">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-531">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-532">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-532">Name of the App Service Environment.</span></span>
            </param>
        <param name="propertiesToInclude">
            <span data-ttu-id="1d8b7-533">コンマ区切りリストに含めるアプリのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-533">Comma separated list of app properties to include.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-534">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-534">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-535">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-535">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-536">App Service Environment ですべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-536">Get all apps in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-537">App Service Environment ですべてのアプリを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-537">Get all apps in an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-538">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-538">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-539">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-539">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-540">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-540">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricDefinitionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt; ListWebWorkerMetricDefinitionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt; ListWebWorkerMetricDefinitionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWebWorkerMetricDefinitionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWebWorkerMetricDefinitionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWebWorkerMetricDefinitionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-541">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-541">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-542">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-542">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-543">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-543">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-544">App Service 環境のワーカー プールのメトリック定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-544">Get metric definitions for a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-545">App Service 環境のワーカー プールのメトリック定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-545">Get metric definitions for a worker pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-546">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-546">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-547">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-547">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-548">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-548">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricDefinitionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt; ListWebWorkerMetricDefinitionsWithHttpMessagesAsync (string resourceGroupName, string name, string workerPoolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt; ListWebWorkerMetricDefinitionsWithHttpMessagesAsync(string resourceGroupName, string name, string workerPoolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWebWorkerMetricDefinitionsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWebWorkerMetricDefinitionsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWebWorkerMetricDefinitionsWithHttpMessagesAsync (resourceGroupName, name, workerPoolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-549">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-549">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-550">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-550">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="1d8b7-551">ワーカー プールの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-551">Name of the worker pool.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-552">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-552">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-553">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-553">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-554">App Service 環境のワーカー プールのメトリック定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-554">Get metric definitions for a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-555">App Service 環境のワーカー プールのメトリック定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-555">Get metric definitions for a worker pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-556">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-556">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-557">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-557">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-558">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-558">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListWebWorkerMetricsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListWebWorkerMetricsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWebWorkerMetricsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWebWorkerMetricsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWebWorkerMetricsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-559">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-559">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-560">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-560">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-561">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-561">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-562">AppServiceEnvironment (App Service Environment) のワーカー プールのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-562">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-563">AppServiceEnvironment (App Service Environment) のワーカー プールのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-563">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-564">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-564">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-565">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-565">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-566">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-566">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerMetricsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListWebWorkerMetricsWithHttpMessagesAsync (string resourceGroupName, string name, string workerPoolName, Nullable&lt;bool&gt; details = null, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListWebWorkerMetricsWithHttpMessagesAsync(string resourceGroupName, string name, string workerPoolName, valuetype System.Nullable`1&lt;bool&gt; details, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWebWorkerMetricsWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWebWorkerMetricsWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWebWorkerMetricsWithHttpMessagesAsync (resourceGroupName, name, workerPoolName, details, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-567">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-567">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-568">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-568">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="1d8b7-569">ワーカー プールの名前</span><span class="sxs-lookup"><span data-stu-id="1d8b7-569">Name of worker pool</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="1d8b7-570">指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-570">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span>
            <span data-ttu-id="1d8b7-571">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-571">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="1d8b7-572">使用状況/メトリックのみ、フィルターで指定されたを返します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-572">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="1d8b7-573">フィルターは、odata 構文に準拠します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-573">Filter conforms to odata syntax.</span></span> <span data-ttu-id="1d8b7-574">例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-574">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-575">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-575">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-576">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-576">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-577">AppServiceEnvironment (App Service Environment) のワーカー プールのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-577">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-578">AppServiceEnvironment (App Service Environment) のワーカー プールのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-578">Get metrics for a worker pool of a AppServiceEnvironment (App Service Environment).</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-579">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-579">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-580">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-580">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-581">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-581">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerUsagesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;&gt; ListWebWorkerUsagesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;&gt; ListWebWorkerUsagesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWebWorkerUsagesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWebWorkerUsagesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWebWorkerUsagesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-582">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-582">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-583">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-583">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-584">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-584">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-585">App Service 環境のワーカー プールの使用状況メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-585">Get usage metrics for a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-586">App Service 環境のワーカー プールの使用状況メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-586">Get usage metrics for a worker pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-587">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-587">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-588">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-588">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-589">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-589">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWebWorkerUsagesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;&gt; ListWebWorkerUsagesWithHttpMessagesAsync (string resourceGroupName, string name, string workerPoolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;&gt; ListWebWorkerUsagesWithHttpMessagesAsync(string resourceGroupName, string name, string workerPoolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWebWorkerUsagesWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWebWorkerUsagesWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWebWorkerUsagesWithHttpMessagesAsync (resourceGroupName, name, workerPoolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Usage&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-590">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-590">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-591">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-591">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="1d8b7-592">ワーカー プールの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-592">Name of the worker pool.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-593">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-593">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-594">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-594">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-595">App Service 環境のワーカー プールの使用状況メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-595">Get usage metrics for a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-596">App Service 環境のワーカー プールの使用状況メトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-596">Get usage metrics for a worker pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-597">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-597">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-598">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-598">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-599">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-599">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-600">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-600">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-601">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-601">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-602">App Service 環境のすべてのサブスクリプションを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-602">Get all App Service Environments for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-603">App Service 環境のすべてのサブスクリプションを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-603">Get all App Service Environments for a subscription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-604">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-604">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-605">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-605">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-606">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-606">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricDefinitionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWorkerPoolInstanceMetricDefinitionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWorkerPoolInstanceMetricDefinitionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWorkerPoolInstanceMetricDefinitionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-607">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-607">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-608">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-608">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-609">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-609">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-610">App Service 環境のワーカー プールの特定のインスタンスのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-610">Get metric definitions for a specific instance of a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-611">App Service 環境のワーカー プールの特定のインスタンスのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-611">Get metric definitions for a specific instance of a worker pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-612">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-612">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-613">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-613">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-614">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-614">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricDefinitionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsWithHttpMessagesAsync (string resourceGroupName, string name, string workerPoolName, string instance, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt; ListWorkerPoolInstanceMetricDefinitionsWithHttpMessagesAsync(string resourceGroupName, string name, string workerPoolName, string instance, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWorkerPoolInstanceMetricDefinitionsWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWorkerPoolInstanceMetricDefinitionsWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWorkerPoolInstanceMetricDefinitionsWithHttpMessagesAsync (resourceGroupName, name, workerPoolName, instance, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetricDefinition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-615">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-615">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-616">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-616">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="1d8b7-617">ワーカー プールの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-617">Name of the worker pool.</span></span>
            </param>
        <param name="instance">
            <span data-ttu-id="1d8b7-618">ワーカー プールのインスタンスの名前。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-618">Name of the instance in the worker pool.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-619">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-619">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-620">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-620">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-621">App Service 環境のワーカー プールの特定のインスタンスのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-621">Get metric definitions for a specific instance of a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-622">App Service 環境のワーカー プールの特定のインスタンスのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-622">Get metric definitions for a specific instance of a worker pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-623">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-623">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-624">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-624">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-625">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-625">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListWorkerPoolInstanceMetricsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListWorkerPoolInstanceMetricsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWorkerPoolInstanceMetricsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWorkerPoolInstanceMetricsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWorkerPoolInstanceMetricsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-626">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-626">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-627">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-627">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-628">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-628">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-629">App Service 環境のワーカー プールの特定のインスタンスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-629">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-630">App Service 環境のワーカー プールの特定のインスタンスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-630">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-631">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-631">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-632">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-632">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-633">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-633">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolInstanceMetricsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListWorkerPoolInstanceMetricsWithHttpMessagesAsync (string resourceGroupName, string name, string workerPoolName, string instance, Nullable&lt;bool&gt; details = null, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt; ListWorkerPoolInstanceMetricsWithHttpMessagesAsync(string resourceGroupName, string name, string workerPoolName, string instance, valuetype System.Nullable`1&lt;bool&gt; details, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWorkerPoolInstanceMetricsWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWorkerPoolInstanceMetricsWithHttpMessagesAsync : string * string * string * string * Nullable&lt;bool&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWorkerPoolInstanceMetricsWithHttpMessagesAsync (resourceGroupName, name, workerPoolName, instance, details, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.ResourceMetric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="instance" Type="System.String" />
        <Parameter Name="details" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-634">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-634">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-635">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-635">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="1d8b7-636">ワーカー プールの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-636">Name of the worker pool.</span></span>
            </param>
        <param name="instance">
            <span data-ttu-id="1d8b7-637">ワーカー プールのインスタンスの名前。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-637">Name of the instance in the worker pool.</span></span>
            </param>
        <param name="details">
            <span data-ttu-id="1d8b7-638">指定&lt;コード&gt;true&lt;/code&gt;にインスタンスの詳細を含めます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-638">Specify &lt;code&gt;true&lt;/code&gt; to include instance details.</span></span>
            <span data-ttu-id="1d8b7-639">既定値は&lt;コード&gt;false&lt;/code&gt;です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-639">The default is &lt;code&gt;false&lt;/code&gt;.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="1d8b7-640">使用状況/メトリックのみ、フィルターで指定されたを返します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-640">Return only usages/metrics specified in the filter.</span></span> <span data-ttu-id="1d8b7-641">フィルターは、odata 構文に準拠します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-641">Filter conforms to odata syntax.</span></span> <span data-ttu-id="1d8b7-642">例: $filter = (name.value eq 'Metric1' または name.value eq 'Metric2') と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [時間 |分 |1 日]'。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-642">Example: $filter=(name.value eq 'Metric1' or name.value eq 'Metric2') and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[Hour|Minute|Day]'.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-643">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-643">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-644">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-644">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-645">App Service 環境のワーカー プールの特定のインスタンスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-645">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-646">App Service 環境のワーカー プールの特定のインスタンスのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-646">Get metrics for a specific instance of a worker pool of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-647">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-647">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-648">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-648">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-649">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-649">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolSkusNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;&gt; ListWorkerPoolSkusNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;&gt; ListWorkerPoolSkusNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWorkerPoolSkusNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWorkerPoolSkusNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWorkerPoolSkusNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-650">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-650">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-651">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-651">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-652">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-652">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-653">ワーカー プールを拡張するためには、利用可能な Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-653">Get available SKUs for scaling a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-654">ワーカー プールを拡張するためには、利用可能な Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-654">Get available SKUs for scaling a worker pool.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-655">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-655">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-656">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-656">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-657">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-657">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolSkusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;&gt; ListWorkerPoolSkusWithHttpMessagesAsync (string resourceGroupName, string name, string workerPoolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;&gt; ListWorkerPoolSkusWithHttpMessagesAsync(string resourceGroupName, string name, string workerPoolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWorkerPoolSkusWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWorkerPoolSkusWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWorkerPoolSkusWithHttpMessagesAsync (resourceGroupName, name, workerPoolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-658">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-658">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-659">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-659">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="1d8b7-660">ワーカー プールの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-660">Name of the worker pool.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-661">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-661">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-662">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-662">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-663">ワーカー プールを拡張するためには、利用可能な Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-663">Get available SKUs for scaling a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-664">ワーカー プールを拡張するためには、利用可能な Sku を取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-664">Get available SKUs for scaling a worker pool.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-665">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-665">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-666">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-666">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-667">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-667">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;&gt; ListWorkerPoolsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;&gt; ListWorkerPoolsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWorkerPoolsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWorkerPoolsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWorkerPoolsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-668">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-668">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-669">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-669">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-670">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-670">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-671">App Service 環境のすべてのワーカー プールを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-671">Get all worker pools of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-672">App Service 環境のすべてのワーカー プールを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-672">Get all worker pools of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-673">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-673">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-674">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-674">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-675">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-675">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWorkerPoolsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;&gt; ListWorkerPoolsWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;&gt; ListWorkerPoolsWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ListWorkerPoolsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWorkerPoolsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ListWorkerPoolsWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-676">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-676">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-677">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-677">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-678">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-678">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-679">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-679">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-680">App Service 環境のすべてのワーカー プールを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-680">Get all worker pools of an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-681">App Service 環境のすべてのワーカー プールを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-681">Get all worker pools of an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-682">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-682">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-683">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-683">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-684">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-684">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RebootWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RebootWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RebootWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.RebootWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RebootWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iAppServiceEnvironmentsOperations.RebootWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-685">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-685">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-686">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-686">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-687">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-687">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-688">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-688">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-689">App Service 環境のすべてのマシンを再起動します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-689">Reboot all machines in an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-690">App Service 環境のすべてのマシンを再起動します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-690">Reboot all machines in an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-691">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-691">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-692">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-692">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResumeNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; ResumeNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; ResumeNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ResumeNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResumeNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ResumeNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-693">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-693">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-694">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-694">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-695">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-695">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-696">App Service 環境を再開します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-696">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-697">App Service 環境を再開します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-697">Resume an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-698">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-698">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-699">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-699">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-700">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-700">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResumeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; ResumeWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; ResumeWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.ResumeWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResumeWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.ResumeWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-701">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-701">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-702">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-702">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-703">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-703">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-704">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-704">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-705">App Service 環境を再開します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-705">Resume an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-706">App Service 環境を再開します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-706">Resume an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-707">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-707">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-708">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-708">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-709">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-709">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SuspendNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; SuspendNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; SuspendNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.SuspendNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuspendNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.SuspendNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d8b7-710">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-710">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-711">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-711">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-712">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-712">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-713">App Service 環境を中断します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-713">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-714">App Service 環境を中断します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-714">Suspend an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-715">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-715">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-716">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-716">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-717">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-717">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SuspendWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; SuspendWithHttpMessagesAsync (string resourceGroupName, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt; SuspendWithHttpMessagesAsync(string resourceGroupName, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.SuspendWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuspendWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.SuspendWithHttpMessagesAsync (resourceGroupName, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.Site&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-718">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-718">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-719">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-719">Name of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-720">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-720">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-721">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-721">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-722">App Service 環境を中断します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-722">Suspend an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-723">App Service 環境を中断します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-723">Suspend an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-724">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-724">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-725">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-725">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-726">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-726">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateMultiRolePoolWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; UpdateMultiRolePoolWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; UpdateMultiRolePoolWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource multiRolePoolEnvelope, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.UpdateMultiRolePoolWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateMultiRolePoolWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.UpdateMultiRolePoolWithHttpMessagesAsync (resourceGroupName, name, multiRolePoolEnvelope, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="multiRolePoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-727">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-727">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-728">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-728">Name of the App Service Environment.</span></span>
            </param>
        <param name="multiRolePoolEnvelope">
            <span data-ttu-id="1d8b7-729">マルチロール プールのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-729">Properties of the multi-role pool.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-730">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-730">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-731">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-731">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-732">作成またはマルチロール プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-732">Create or update a multi-role pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-733">作成またはマルチロール プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-733">Create or update a multi-role pool.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-734">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-734">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-735">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-735">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-736">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-736">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string name, Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource hostingEnvironmentEnvelope, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string name, class Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource hostingEnvironmentEnvelope, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, name, hostingEnvironmentEnvelope, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="hostingEnvironmentEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentPatchResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-737">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-737">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-738">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-738">Name of the App Service Environment.</span></span>
            </param>
        <param name="hostingEnvironmentEnvelope">
            <span data-ttu-id="1d8b7-739">App Service 環境の構成の詳細。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-739">Configuration details of the App Service Environment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-740">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-740">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-741">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-741">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-742">作成または App Service 環境を更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-742">Create or update an App Service Environment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-743">作成または App Service 環境を更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-743">Create or update an App Service Environment.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-744">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-744">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-745">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-745">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-746">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-746">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWorkerPoolWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; UpdateWorkerPoolWithHttpMessagesAsync (string resourceGroupName, string name, string workerPoolName, Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt; UpdateWorkerPoolWithHttpMessagesAsync(string resourceGroupName, string name, string workerPoolName, class Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource workerPoolEnvelope, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations.UpdateWorkerPoolWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWorkerPoolWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;" Usage="iAppServiceEnvironmentsOperations.UpdateWorkerPoolWithHttpMessagesAsync (resourceGroupName, name, workerPoolName, workerPoolEnvelope, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="workerPoolName" Type="System.String" />
        <Parameter Name="workerPoolEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.WorkerPoolResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d8b7-747">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-747">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="1d8b7-748">App Service 環境の名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-748">Name of the App Service Environment.</span></span>
            </param>
        <param name="workerPoolName">
            <span data-ttu-id="1d8b7-749">ワーカー プールの名前です。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-749">Name of the worker pool.</span></span>
            </param>
        <param name="workerPoolEnvelope">
            <span data-ttu-id="1d8b7-750">ワーカー プールのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-750">Properties of the worker pool.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d8b7-751">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-751">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d8b7-752">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-752">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d8b7-753">作成またはワーカー プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-753">Create or update a worker pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="1d8b7-754">作成またはワーカー プールを更新します。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-754">Create or update a worker pool.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d8b7-755">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-755">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d8b7-756">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-756">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d8b7-757">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d8b7-757">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>