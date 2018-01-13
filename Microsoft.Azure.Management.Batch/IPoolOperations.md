<Type Name="IPoolOperations" FullName="Microsoft.Azure.Management.Batch.IPoolOperations">
  <TypeSignature Language="C#" Value="public interface IPoolOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPoolOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.IPoolOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPoolOperations" />
  <TypeSignature Language="F#" Value="type IPoolOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7dbf4-101">PoolOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-101">PoolOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolCreateHeaders&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Pool, class Microsoft.Azure.Management.Batch.Models.PoolCreateHeaders&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool, Microsoft.Azure.Management.Batch.Models.PoolCreateHeaders&gt;&gt;" Usage="iPoolOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, accountName, poolName, parameters, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolCreateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7dbf4-102">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-102">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="7dbf4-103">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-103">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="7dbf4-104">プール名です。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-104">The pool name.</span></span> <span data-ttu-id="7dbf4-105">これは、アカウント内で一意でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-105">This must be unique within the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7dbf4-106">プールの作成に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-106">Additional parameters for pool creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="7dbf4-107">更新するプールのエンティティの状態 (ETag) のバージョン。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-107">The entity state (ETag) version of the pool to update.</span></span> <span data-ttu-id="7dbf4-108">値"\*"、プールが既に存在する場合にのみ、操作を適用するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-108">A value of "\*" can be used to apply the operation only if the pool already exists.</span></span> <span data-ttu-id="7dbf4-109">省略した場合、この操作常に使用されます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-109">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="7dbf4-110">設定 ' \*'、新しいプールを作成するが、既存のプールの更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-110">Set to '\*' to allow a new pool to be created, but to prevent updating an existing pool.</span></span> <span data-ttu-id="7dbf4-111">その他の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-111">Other values will be ignored.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7dbf4-112">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-112">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbf4-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbf4-114">指定されたアカウント内の新しいプールを作成します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-114">Creates a new pool inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7dbf4-115">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-115">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7dbf4-116">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-116">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7dbf4-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, string poolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, string poolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;&gt;" Usage="iPoolOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, accountName, poolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7dbf4-118">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-118">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="7dbf4-119">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-119">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="7dbf4-120">プール名です。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-120">The pool name.</span></span> <span data-ttu-id="7dbf4-121">これは、アカウント内で一意でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-121">This must be unique within the account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7dbf4-122">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-122">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbf4-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbf4-124">指定したプールを削除します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-124">Deletes the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7dbf4-125">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-125">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7dbf4-126">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-126">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolCreateHeaders&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Pool, class Microsoft.Azure.Management.Batch.Models.PoolCreateHeaders&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.CreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool, Microsoft.Azure.Management.Batch.Models.PoolCreateHeaders&gt;&gt;" Usage="iPoolOperations.CreateWithHttpMessagesAsync (resourceGroupName, accountName, poolName, parameters, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolCreateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7dbf4-127">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-127">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="7dbf4-128">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-128">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="7dbf4-129">プール名です。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-129">The pool name.</span></span> <span data-ttu-id="7dbf4-130">これは、アカウント内で一意でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-130">This must be unique within the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7dbf4-131">プールの作成に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-131">Additional parameters for pool creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="7dbf4-132">更新するプールのエンティティの状態 (ETag) のバージョン。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-132">The entity state (ETag) version of the pool to update.</span></span> <span data-ttu-id="7dbf4-133">値"\*"、プールが既に存在する場合にのみ、操作を適用するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-133">A value of "\*" can be used to apply the operation only if the pool already exists.</span></span> <span data-ttu-id="7dbf4-134">省略した場合、この操作常に使用されます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-134">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="7dbf4-135">設定 ' \*'、新しいプールを作成するが、既存のプールの更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-135">Set to '\*' to allow a new pool to be created, but to prevent updating an existing pool.</span></span> <span data-ttu-id="7dbf4-136">その他の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-136">Other values will be ignored.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7dbf4-137">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-137">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbf4-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbf4-139">指定されたアカウント内の新しいプールを作成します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-139">Creates a new pool inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7dbf4-140">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-140">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7dbf4-141">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-141">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7dbf4-142">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-142">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, string poolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, string poolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;&gt;" Usage="iPoolOperations.DeleteWithHttpMessagesAsync (resourceGroupName, accountName, poolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Management.Batch.Models.PoolDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7dbf4-143">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-143">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="7dbf4-144">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-144">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="7dbf4-145">プール名です。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-145">The pool name.</span></span> <span data-ttu-id="7dbf4-146">これは、アカウント内で一意でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-146">This must be unique within the account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7dbf4-147">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-147">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbf4-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbf4-149">指定したプールを削除します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-149">Deletes the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7dbf4-150">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-150">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7dbf4-151">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-151">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScaleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolDisableAutoScaleHeaders&gt;&gt; DisableAutoScaleWithHttpMessagesAsync (string resourceGroupName, string accountName, string poolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Pool, class Microsoft.Azure.Management.Batch.Models.PoolDisableAutoScaleHeaders&gt;&gt; DisableAutoScaleWithHttpMessagesAsync(string resourceGroupName, string accountName, string poolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.DisableAutoScaleWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableAutoScaleWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool, Microsoft.Azure.Management.Batch.Models.PoolDisableAutoScaleHeaders&gt;&gt;" Usage="iPoolOperations.DisableAutoScaleWithHttpMessagesAsync (resourceGroupName, accountName, poolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolDisableAutoScaleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7dbf4-152">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-152">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="7dbf4-153">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-153">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="7dbf4-154">プール名です。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-154">The pool name.</span></span> <span data-ttu-id="7dbf4-155">これは、アカウント内で一意でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-155">This must be unique within the account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7dbf4-156">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-156">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbf4-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbf4-158">プールの自動スケーリングを無効にします。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-158">Disables automatic scaling for a pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7dbf4-159">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-159">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7dbf4-160">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-160">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7dbf4-161">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-161">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string accountName, string poolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Pool, class Microsoft.Azure.Management.Batch.Models.PoolGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string accountName, string poolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool, Microsoft.Azure.Management.Batch.Models.PoolGetHeaders&gt;&gt;" Usage="iPoolOperations.GetWithHttpMessagesAsync (resourceGroupName, accountName, poolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7dbf4-162">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-162">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="7dbf4-163">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-163">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="7dbf4-164">プール名です。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-164">The pool name.</span></span> <span data-ttu-id="7dbf4-165">これは、アカウント内で一意でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-165">This must be unique within the account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7dbf4-166">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-166">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbf4-167">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbf4-168">指定したプールに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-168">Gets information about the specified pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7dbf4-169">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-169">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7dbf4-170">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-170">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7dbf4-171">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-171">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;&gt; ListByBatchAccountNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;&gt; ListByBatchAccountNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.ListByBatchAccountNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByBatchAccountNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;&gt;" Usage="iPoolOperations.ListByBatchAccountNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="7dbf4-172">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-172">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7dbf4-173">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-173">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbf4-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbf4-175">指定されたアカウント内のプールのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-175">Lists all of the pools in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7dbf4-176">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-176">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7dbf4-177">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-177">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7dbf4-178">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-178">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;&gt; ListByBatchAccountWithHttpMessagesAsync (string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, string select = null, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;&gt; ListByBatchAccountWithHttpMessagesAsync(string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, string select, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.ListByBatchAccountWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByBatchAccountWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;&gt;" Usage="iPoolOperations.ListByBatchAccountWithHttpMessagesAsync (resourceGroupName, accountName, maxresults, select, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Pool&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
             <span data-ttu-id="7dbf4-179">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-179">The name of the resource group that contains the Batch account.</span></span>
             </param>
        <param name="accountName">
             <span data-ttu-id="7dbf4-180">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-180">The name of the Batch account.</span></span>
             </param>
        <param name="maxresults">
             <span data-ttu-id="7dbf4-181">応答で返されるアイテムの最大数。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-181">The maximum number of items to return in the response.</span></span>
             </param>
        <param name="select">
             <span data-ttu-id="7dbf4-182">コンマ区切りのプロパティの一覧を返す必要があります。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-182">Comma separated list of properties that should be returned.</span></span> <span data-ttu-id="7dbf4-183">例:"のプロパティ/provisioningState"です。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-183">e.g. "properties/provisioningState".</span></span> <span data-ttu-id="7dbf4-184">のみの上位レベル のプロパティのプロパティ/選択に対して有効です。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-184">Only top level properties under properties/ are valid for selection.</span></span>
             </param>
        <param name="filter">
             <span data-ttu-id="7dbf4-185">OData フィルター式です。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-185">OData filter expression.</span></span> <span data-ttu-id="7dbf4-186">フィルター処理の有効なプロパティは次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-186">Valid properties for filtering are:</span></span>
            
             <span data-ttu-id="7dbf4-187">プロパティ/allocationState プロパティ/allocationStateTransitionTime プロパティ/creationTime プロパティ/provisioningState プロパティ/provisioningStateTransitionTime プロパティ/lastModified プロパティ/vmSize プロパティの名前/interNodeCommunication 自動スケールのプロパティ/scaleSettings/プロパティ/scaleSettings/fixedScale</span><span class="sxs-lookup"><span data-stu-id="7dbf4-187">name properties/allocationState properties/allocationStateTransitionTime properties/creationTime properties/provisioningState properties/provisioningStateTransitionTime properties/lastModified properties/vmSize properties/interNodeCommunication properties/scaleSettings/autoScale properties/scaleSettings/fixedScale</span></span>
             </param>
        <param name="customHeaders">
             <span data-ttu-id="7dbf4-188">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-188">The headers that will be added to request.</span></span>
             </param>
        <param name="cancellationToken">
             <span data-ttu-id="7dbf4-189">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-189">The cancellation token.</span></span>
             </param>
        <summary>
             <span data-ttu-id="7dbf4-190">指定されたアカウント内のプールのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-190">Lists all of the pools in the specified account.</span></span>
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
             <span data-ttu-id="7dbf4-191">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-191">Thrown when the operation returned an invalid status code</span></span>
             </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
             <span data-ttu-id="7dbf4-192">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-192">Thrown when unable to deserialize the response</span></span>
             </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
             <span data-ttu-id="7dbf4-193">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-193">Thrown when a required parameter is null</span></span>
             </exception>
      </Docs>
    </Member>
    <Member MemberName="StopResizeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders&gt;&gt; StopResizeWithHttpMessagesAsync (string resourceGroupName, string accountName, string poolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Pool, class Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders&gt;&gt; StopResizeWithHttpMessagesAsync(string resourceGroupName, string accountName, string poolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.StopResizeWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopResizeWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool, Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders&gt;&gt;" Usage="iPoolOperations.StopResizeWithHttpMessagesAsync (resourceGroupName, accountName, poolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolStopResizeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7dbf4-194">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-194">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="7dbf4-195">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-195">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="7dbf4-196">プール名です。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-196">The pool name.</span></span> <span data-ttu-id="7dbf4-197">これは、アカウント内で一意でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-197">This must be unique within the account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7dbf4-198">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-198">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbf4-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbf4-200">継続的な停止のサイズ変更、プールに操作します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-200">Stops an ongoing resize operation on the pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7dbf4-201">プール サイズ変更操作の前に以前の状態は元に戻りません。 行われるさらなる変更だけが停止され、プールが、現在の状態を維持します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-201">This does not restore the pool to its previous state before the resize operation: it only stops any further changes being made, and the pool maintains its current state.</span></span> <span data-ttu-id="7dbf4-202">停止後、プールが停止操作が完了するとではノードの数に安定します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-202">After stopping, the pool stabilizes at the number of nodes it was at when the stop operation was done.</span></span> <span data-ttu-id="7dbf4-203">プール割り当て状態は、停止操作中は停止してから、安定したに最初に変更します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-203">During the stop operation, the pool allocation state changes first to stopping and then to steady.</span></span> <span data-ttu-id="7dbf4-204">サイズ変更操作で、明示的なサイズ変更プール要求である必要はありません。この API は、作成時に、プールの初期サイズ設定を停止するようにも使用できます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-204">A resize operation need not be an explicit resize pool request; this API can also be used to halt the initial sizing of the pool when it is created.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7dbf4-205">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-205">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7dbf4-206">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-206">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7dbf4-207">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-207">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string accountName, string poolName, Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.Batch.Models.Pool, class Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string accountName, string poolName, class Microsoft.Azure.Management.Batch.Models.Pool parameters, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IPoolOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.Pool,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Batch.Models.Pool * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool, Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders&gt;&gt;" Usage="iPoolOperations.UpdateWithHttpMessagesAsync (resourceGroupName, accountName, poolName, parameters, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Batch.Models.Pool,Microsoft.Azure.Management.Batch.Models.PoolUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="poolName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.Pool" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7dbf4-208">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-208">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="7dbf4-209">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-209">The name of the Batch account.</span></span>
            </param>
        <param name="poolName">
            <span data-ttu-id="7dbf4-210">プール名です。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-210">The pool name.</span></span> <span data-ttu-id="7dbf4-211">これは、アカウント内で一意でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-211">This must be unique within the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7dbf4-212">更新する必要があるプールのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-212">Pool properties that should be updated.</span></span> <span data-ttu-id="7dbf4-213">指定されたプロパティが更新されます、指定されていない任意のプロパティは変更されません。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-213">Properties that are supplied will be updated, any property not supplied will be unchanged.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="7dbf4-214">更新するプールのエンティティの状態 (ETag) のバージョン。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-214">The entity state (ETag) version of the pool to update.</span></span> <span data-ttu-id="7dbf4-215">この値を省略するかに設定することができます"\*"を無条件で操作を適用します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-215">This value can be omitted or set to "\*" to apply the operation unconditionally.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7dbf4-216">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-216">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7dbf4-217">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7dbf4-218">既存のプールのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-218">Updates the properties of an existing pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7dbf4-219">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-219">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7dbf4-220">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-220">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7dbf4-221">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7dbf4-221">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>