<Type Name="IManagementLocksOperations" FullName="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations">
  <TypeSignature Language="C#" Value="public interface IManagementLocksOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IManagementLocksOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IManagementLocksOperations" />
  <TypeSignature Language="F#" Value="type IManagementLocksOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8e731-101">ManagementLocksOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="8e731-101">ManagementLocksOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAtResourceGroupLevelWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; CreateOrUpdateAtResourceGroupLevelWithHttpMessagesAsync (string resourceGroupName, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; CreateOrUpdateAtResourceGroupLevelWithHttpMessagesAsync(string resourceGroupName, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.CreateOrUpdateAtResourceGroupLevelWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAtResourceGroupLevelWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="iManagementLocksOperations.CreateOrUpdateAtResourceGroupLevelWithHttpMessagesAsync (resourceGroupName, lockName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8e731-102">ロックするリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-102">The name of the resource group to lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="8e731-103">ロックの名前です。</span><span class="sxs-lookup"><span data-stu-id="8e731-103">The lock name.</span></span> <span data-ttu-id="8e731-104">ロック名は 260 文字の最大値にできます。</span><span class="sxs-lookup"><span data-stu-id="8e731-104">The lock name can be a maximum of 260 characters.</span></span> <span data-ttu-id="8e731-105">含めることができない&lt;、 &gt; %、 &amp;、: \, ?、/、いずれかの制御文字またはします。</span><span class="sxs-lookup"><span data-stu-id="8e731-105">It cannot contain &lt;, &gt; %, &amp;, :, \, ?, /, or any control characters.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8e731-106">管理ロックのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8e731-106">The management lock parameters.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-109">作成するか、リソース グループ レベルの管理ロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="8e731-109">Creates or updates a management lock at the resource group level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e731-110">親スコープでロックを適用すると、すべての子リソースは同じロックを継承します。</span><span class="sxs-lookup"><span data-stu-id="8e731-110">When you apply a lock at a parent scope, all child resources inherit the same lock.</span></span> <span data-ttu-id="8e731-111">管理ロックを作成するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="8e731-111">To create management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="8e731-112">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="8e731-112">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-113">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-113">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e731-114">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-114">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-115">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-115">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtResourceLevelWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; CreateOrUpdateAtResourceLevelWithHttpMessagesAsync (string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; CreateOrUpdateAtResourceLevelWithHttpMessagesAsync(string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.CreateOrUpdateAtResourceLevelWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAtResourceLevelWithHttpMessagesAsync : string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="iManagementLocksOperations.CreateOrUpdateAtResourceLevelWithHttpMessagesAsync (resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8e731-116">ロック リソースを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-116">The name of the resource group containing the resource to lock.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="8e731-117">リソース プロバイダーの名前空間のリソースをロックします。</span><span class="sxs-lookup"><span data-stu-id="8e731-117">The resource provider namespace of the resource to lock.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="8e731-118">親のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="8e731-118">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="8e731-119">ロックするリソースのリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="8e731-119">The resource type of the resource to lock.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="8e731-120">ロックするリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-120">The name of the resource to lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="8e731-121">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-121">The name of lock.</span></span> <span data-ttu-id="8e731-122">ロック名は 260 文字の最大値にできます。</span><span class="sxs-lookup"><span data-stu-id="8e731-122">The lock name can be a maximum of 260 characters.</span></span>
            <span data-ttu-id="8e731-123">含めることができない&lt;、 &gt; %、 &amp;、: \, ?、/、いずれかの制御文字またはします。</span><span class="sxs-lookup"><span data-stu-id="8e731-123">It cannot contain &lt;, &gt; %, &amp;, :, \, ?, /, or any control characters.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8e731-124">作成または管理ロックを更新するためのパラメーター。</span><span class="sxs-lookup"><span data-stu-id="8e731-124">Parameters for creating or updating a  management lock.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-127">作成するか、リソース レベルまたはリソースの下の任意のレベルでの管理ロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="8e731-127">Creates or updates a management lock at the resource level or any level below the resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e731-128">親スコープでロックを適用すると、すべての子リソースは同じロックを継承します。</span><span class="sxs-lookup"><span data-stu-id="8e731-128">When you apply a lock at a parent scope, all child resources inherit the same lock.</span></span> <span data-ttu-id="8e731-129">管理ロックを作成するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="8e731-129">To create management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="8e731-130">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="8e731-130">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-131">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-131">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e731-132">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-132">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtSubscriptionLevelWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; CreateOrUpdateAtSubscriptionLevelWithHttpMessagesAsync (string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; CreateOrUpdateAtSubscriptionLevelWithHttpMessagesAsync(string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.CreateOrUpdateAtSubscriptionLevelWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAtSubscriptionLevelWithHttpMessagesAsync : string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="iManagementLocksOperations.CreateOrUpdateAtSubscriptionLevelWithHttpMessagesAsync (lockName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="lockName">
            <span data-ttu-id="8e731-134">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-134">The name of lock.</span></span> <span data-ttu-id="8e731-135">ロック名は 260 文字の最大値にできます。</span><span class="sxs-lookup"><span data-stu-id="8e731-135">The lock name can be a maximum of 260 characters.</span></span>
            <span data-ttu-id="8e731-136">含めることができない&lt;、 &gt; %、 &amp;、: \, ?、/、いずれかの制御文字またはします。</span><span class="sxs-lookup"><span data-stu-id="8e731-136">It cannot contain &lt;, &gt; %, &amp;, :, \, ?, /, or any control characters.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8e731-137">管理ロックのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8e731-137">The management lock parameters.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-138">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-138">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-140">作成するか、サブスクリプション レベルでの管理ロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="8e731-140">Creates or updates a management lock at the subscription level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e731-141">親スコープでロックを適用すると、すべての子リソースは同じロックを継承します。</span><span class="sxs-lookup"><span data-stu-id="8e731-141">When you apply a lock at a parent scope, all child resources inherit the same lock.</span></span> <span data-ttu-id="8e731-142">管理ロックを作成するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="8e731-142">To create management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="8e731-143">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="8e731-143">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-144">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-144">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e731-145">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-145">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-146">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-146">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateByScopeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; CreateOrUpdateByScopeWithHttpMessagesAsync (string scope, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; CreateOrUpdateByScopeWithHttpMessagesAsync(string scope, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.CreateOrUpdateByScopeWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateByScopeWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="iManagementLocksOperations.CreateOrUpdateByScopeWithHttpMessagesAsync (scope, lockName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="8e731-147">ロックのスコープです。</span><span class="sxs-lookup"><span data-stu-id="8e731-147">The scope for the lock.</span></span> <span data-ttu-id="8e731-148">割り当てのスコープを提供するときに使用して 'のサブスクリプション/{subscriptionid}' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' のリソース グループのサブスクリプションの場合と 'サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/providers/{resourceProviderNamespace}/{parentResourcePathIfPresent}/{resourcetype}/{resourcename}' のリソース。</span><span class="sxs-lookup"><span data-stu-id="8e731-148">When providing a scope for the assignment, use '/subscriptions/{subscriptionId}' for subscriptions, '/subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}' for resource groups, and '/subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{parentResourcePathIfPresent}/{resourceType}/{resourceName}' for resources.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="8e731-149">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-149">The name of lock.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8e731-150">作成または管理ロック パラメーターを更新します。</span><span class="sxs-lookup"><span data-stu-id="8e731-150">Create or update management lock parameters.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-151">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-153">作成またはスコープでの管理ロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="8e731-153">Create or update a management lock by scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-154">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e731-155">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtResourceGroupLevelWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteAtResourceGroupLevelWithHttpMessagesAsync (string resourceGroupName, string lockName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteAtResourceGroupLevelWithHttpMessagesAsync(string resourceGroupName, string lockName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.DeleteAtResourceGroupLevelWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAtResourceGroupLevelWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iManagementLocksOperations.DeleteAtResourceGroupLevelWithHttpMessagesAsync (resourceGroupName, lockName, customHeaders, cancellationToken)" />
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
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8e731-157">ロックを含むリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-157">The name of the resource group containing the lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="8e731-158">削除するロックの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-158">The name of lock to delete.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-159">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-159">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-161">リソース グループ レベルでの管理ロックを削除します。</span><span class="sxs-lookup"><span data-stu-id="8e731-161">Deletes a management lock at the resource group level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e731-162">管理ロックを削除するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="8e731-162">To delete management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="8e731-163">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="8e731-163">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-164">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-164">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-165">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-165">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtResourceLevelWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteAtResourceLevelWithHttpMessagesAsync (string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteAtResourceLevelWithHttpMessagesAsync(string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.DeleteAtResourceLevelWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAtResourceLevelWithHttpMessagesAsync : string * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iManagementLocksOperations.DeleteAtResourceLevelWithHttpMessagesAsync (resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName, customHeaders, cancellationToken)" />
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
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8e731-166">削除すると、ロック リソースを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-166">The name of the resource group containing the resource with the lock to delete.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="8e731-167">リソース プロバイダーの名前空間を削除するロックを持つリソースのです。</span><span class="sxs-lookup"><span data-stu-id="8e731-167">The resource provider namespace of the resource with the lock to delete.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="8e731-168">親のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="8e731-168">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="8e731-169">削除するロックを持つリソースのリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="8e731-169">The resource type of the resource with the lock to delete.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="8e731-170">ロックを削除すると、リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-170">The name of the resource with the lock to delete.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="8e731-171">削除するロックの名前です。</span><span class="sxs-lookup"><span data-stu-id="8e731-171">The name of the lock to delete.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-172">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-172">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-173">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-174">リソースまたはリソースの下の任意のレベルのロックの管理を削除します。</span><span class="sxs-lookup"><span data-stu-id="8e731-174">Deletes the management lock of a resource or any level below the resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e731-175">管理ロックを削除するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="8e731-175">To delete management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="8e731-176">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="8e731-176">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-177">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-177">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-178">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-178">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtSubscriptionLevelWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteAtSubscriptionLevelWithHttpMessagesAsync (string lockName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteAtSubscriptionLevelWithHttpMessagesAsync(string lockName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.DeleteAtSubscriptionLevelWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAtSubscriptionLevelWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iManagementLocksOperations.DeleteAtSubscriptionLevelWithHttpMessagesAsync (lockName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="lockName">
            <span data-ttu-id="8e731-179">削除するロックの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-179">The name of lock to delete.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-180">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-180">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-182">サブスクリプション レベルでの管理ロックを削除します。</span><span class="sxs-lookup"><span data-stu-id="8e731-182">Deletes the management lock at the subscription level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8e731-183">管理ロックを削除するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="8e731-183">To delete management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="8e731-184">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="8e731-184">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-185">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-185">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-186">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-186">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteByScopeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteByScopeWithHttpMessagesAsync (string scope, string lockName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteByScopeWithHttpMessagesAsync(string scope, string lockName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.DeleteByScopeWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteByScopeWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iManagementLocksOperations.DeleteByScopeWithHttpMessagesAsync (scope, lockName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="8e731-187">ロックのスコープです。</span><span class="sxs-lookup"><span data-stu-id="8e731-187">The scope for the lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="8e731-188">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-188">The name of lock.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-189">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-189">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-191">スコープでの管理ロックを削除します。</span><span class="sxs-lookup"><span data-stu-id="8e731-191">Delete a management lock by scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-192">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-192">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-193">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-193">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetAtResourceGroupLevelWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; GetAtResourceGroupLevelWithHttpMessagesAsync (string resourceGroupName, string lockName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; GetAtResourceGroupLevelWithHttpMessagesAsync(string resourceGroupName, string lockName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.GetAtResourceGroupLevelWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAtResourceGroupLevelWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="iManagementLocksOperations.GetAtResourceGroupLevelWithHttpMessagesAsync (resourceGroupName, lockName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8e731-194">ロックされているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-194">The name of the locked resource group.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="8e731-195">取得するロックの名前です。</span><span class="sxs-lookup"><span data-stu-id="8e731-195">The name of the lock to get.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-196">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-196">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-197">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-198">リソース グループ レベルでの管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="8e731-198">Gets a management lock at the resource group level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-199">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-199">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e731-200">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-200">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-201">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-201">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetAtResourceLevelWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; GetAtResourceLevelWithHttpMessagesAsync (string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; GetAtResourceLevelWithHttpMessagesAsync(string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.GetAtResourceLevelWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAtResourceLevelWithHttpMessagesAsync : string * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="iManagementLocksOperations.GetAtResourceLevelWithHttpMessagesAsync (resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8e731-202">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-202">The name of the resource group.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="8e731-203">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="8e731-203">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="8e731-204">SQL データベースと同様に、一部のサービスで必要な追加のパスのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8e731-204">An extra path parameter needed in some services, like SQL Databases.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="8e731-205">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="8e731-205">The type of the resource.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="8e731-206">リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-206">The name of the resource.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="8e731-207">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-207">The name of lock.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-208">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-208">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-209">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-210">リソースまたはリソースの下の任意のレベルの管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="8e731-210">Get the management lock of a resource or any level below resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-211">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-211">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e731-212">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-212">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-213">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-213">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetAtSubscriptionLevelWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; GetAtSubscriptionLevelWithHttpMessagesAsync (string lockName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; GetAtSubscriptionLevelWithHttpMessagesAsync(string lockName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.GetAtSubscriptionLevelWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAtSubscriptionLevelWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="iManagementLocksOperations.GetAtSubscriptionLevelWithHttpMessagesAsync (lockName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="lockName">
            <span data-ttu-id="8e731-214">取得するロックの名前です。</span><span class="sxs-lookup"><span data-stu-id="8e731-214">The name of the lock to get.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-215">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-215">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-216">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-216">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-217">サブスクリプション レベルでの管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="8e731-217">Gets a management lock at the subscription level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-218">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-218">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e731-219">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-219">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-220">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-220">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetByScopeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; GetByScopeWithHttpMessagesAsync (string scope, string lockName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; GetByScopeWithHttpMessagesAsync(string scope, string lockName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.GetByScopeWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByScopeWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="iManagementLocksOperations.GetByScopeWithHttpMessagesAsync (scope, lockName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="8e731-221">ロックのスコープです。</span><span class="sxs-lookup"><span data-stu-id="8e731-221">The scope for the lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="8e731-222">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-222">The name of lock.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-223">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-223">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-224">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-224">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-225">スコープでの管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="8e731-225">Get a management lock by scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-226">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-226">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e731-227">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-227">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-228">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-228">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceGroupLevelNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt; ListAtResourceGroupLevelNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt; ListAtResourceGroupLevelNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.ListAtResourceGroupLevelNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAtResourceGroupLevelNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt;" Usage="iManagementLocksOperations.ListAtResourceGroupLevelNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="8e731-229">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8e731-229">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-230">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-230">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-231">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-231">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-232">リソース グループのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="8e731-232">Gets all the management locks for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-233">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-233">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e731-234">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-234">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-235">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-235">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceGroupLevelWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt; ListAtResourceGroupLevelWithHttpMessagesAsync (string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt; ListAtResourceGroupLevelWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.ListAtResourceGroupLevelWithHttpMessagesAsync(System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAtResourceGroupLevelWithHttpMessagesAsync : string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt;" Usage="iManagementLocksOperations.ListAtResourceGroupLevelWithHttpMessagesAsync (resourceGroupName, odataQuery, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8e731-236">取得するロックを含むリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-236">The name of the resource group containing the locks to get.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="8e731-237">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="8e731-237">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-238">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-238">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-239">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-239">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-240">リソース グループのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="8e731-240">Gets all the management locks for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-241">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-241">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e731-242">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-242">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-243">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-243">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceLevelNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt; ListAtResourceLevelNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt; ListAtResourceLevelNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.ListAtResourceLevelNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAtResourceLevelNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt;" Usage="iManagementLocksOperations.ListAtResourceLevelNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="8e731-244">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8e731-244">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-245">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-245">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-246">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-246">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-247">リソースまたはリソースの下の任意のレベルのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="8e731-247">Gets all the management locks for a resource or any level below resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-248">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-248">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e731-249">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-249">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-250">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-250">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceLevelWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt; ListAtResourceLevelWithHttpMessagesAsync (string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt; ListAtResourceLevelWithHttpMessagesAsync(string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.ListAtResourceLevelWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAtResourceLevelWithHttpMessagesAsync : string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt;" Usage="iManagementLocksOperations.ListAtResourceLevelWithHttpMessagesAsync (resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, odataQuery, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8e731-251">ロックされたリソースを含むリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8e731-251">The name of the resource group containing the locked resource.</span></span> <span data-ttu-id="8e731-252">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="8e731-252">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="8e731-253">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="8e731-253">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="8e731-254">親のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="8e731-254">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="8e731-255">ロックされたリソースのリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="8e731-255">The resource type of the locked resource.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="8e731-256">ロックされたリソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="8e731-256">The name of the locked resource.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="8e731-257">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="8e731-257">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-258">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-258">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-259">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-259">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-260">リソースまたはリソースの下の任意のレベルのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="8e731-260">Gets all the management locks for a resource or any level below resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-261">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-261">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e731-262">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-262">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-263">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-263">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionLevelNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt; ListAtSubscriptionLevelNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt; ListAtSubscriptionLevelNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.ListAtSubscriptionLevelNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAtSubscriptionLevelNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt;" Usage="iManagementLocksOperations.ListAtSubscriptionLevelNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="8e731-264">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8e731-264">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-265">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-265">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-266">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-266">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-267">サブスクリプションのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="8e731-267">Gets all the management locks for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-268">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-268">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e731-269">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-269">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-270">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-270">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionLevelWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt; ListAtSubscriptionLevelWithHttpMessagesAsync (Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt; ListAtSubscriptionLevelWithHttpMessagesAsync(class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations.ListAtSubscriptionLevelWithHttpMessagesAsync(Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAtSubscriptionLevelWithHttpMessagesAsync : Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt;" Usage="iManagementLocksOperations.ListAtSubscriptionLevelWithHttpMessagesAsync (odataQuery, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="odataQuery">
            <span data-ttu-id="8e731-271">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="8e731-271">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8e731-272">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8e731-272">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8e731-273">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8e731-273">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8e731-274">サブスクリプションのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="8e731-274">Gets all the management locks for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8e731-275">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-275">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8e731-276">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-276">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8e731-277">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8e731-277">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>