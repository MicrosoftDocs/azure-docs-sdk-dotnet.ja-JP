<Type Name="IStorageAccountsOperations" FullName="Microsoft.Azure.Management.Storage.IStorageAccountsOperations">
  <TypeSignature Language="C#" Value="public interface IStorageAccountsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStorageAccountsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.IStorageAccountsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStorageAccountsOperations" />
  <TypeSignature Language="F#" Value="type IStorageAccountsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="12351-101">StorageAccountsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="12351-101">StorageAccountsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.IStorageAccountsOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;" Usage="iStorageAccountsOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, accountName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12351-102">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-102">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="12351-103">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="12351-103">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="12351-104">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-104">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="12351-105">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="12351-105">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="12351-106">作成したアカウントを提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="12351-106">The parameters to provide for the created account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="12351-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="12351-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12351-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12351-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12351-109">指定されたパラメーターで新しいストレージ アカウントを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="12351-109">Asynchronously creates a new storage account with the specified parameters.</span></span> <span data-ttu-id="12351-110">アカウントが既に作成されて、別のプロパティを持つ後続の作成要求が発行される場合は、アカウントのプロパティが更新されます。</span><span class="sxs-lookup"><span data-stu-id="12351-110">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="12351-111">アカウントが既に作成されていて、正確な同じ一連のプロパティとそれ以降の作成または更新要求が発行された、要求は成功します。</span><span class="sxs-lookup"><span data-stu-id="12351-111">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="12351-112">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-112">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="12351-113">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-113">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="12351-114">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-114">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync (string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync(string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.IStorageAccountsOperations.CheckNameAvailabilityWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckNameAvailabilityWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult&gt;&gt;" Usage="iStorageAccountsOperations.CheckNameAvailabilityWithHttpMessagesAsync (name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.CheckNameAvailabilityResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
            <span data-ttu-id="12351-115">ストレージ アカウント名。</span><span class="sxs-lookup"><span data-stu-id="12351-115">The storage account name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="12351-116">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="12351-116">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12351-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12351-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12351-118">ストレージ アカウント名が有効で既に使用されていないことを確認します。</span><span class="sxs-lookup"><span data-stu-id="12351-118">Checks that the storage account name is valid and is not already in use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="12351-119">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-119">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="12351-120">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-120">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="12351-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.IStorageAccountsOperations.CreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;" Usage="iStorageAccountsOperations.CreateWithHttpMessagesAsync (resourceGroupName, accountName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12351-122">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-122">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="12351-123">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="12351-123">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="12351-124">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-124">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="12351-125">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="12351-125">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="12351-126">作成したアカウントを提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="12351-126">The parameters to provide for the created account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="12351-127">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="12351-127">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12351-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12351-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12351-129">指定されたパラメーターで新しいストレージ アカウントを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="12351-129">Asynchronously creates a new storage account with the specified parameters.</span></span> <span data-ttu-id="12351-130">アカウントが既に作成されて、別のプロパティを持つ後続の作成要求が発行される場合は、アカウントのプロパティが更新されます。</span><span class="sxs-lookup"><span data-stu-id="12351-130">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="12351-131">アカウントが既に作成されていて、正確な同じ一連のプロパティとそれ以降の作成または更新要求が発行された、要求は成功します。</span><span class="sxs-lookup"><span data-stu-id="12351-131">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="12351-132">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-132">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="12351-133">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-133">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="12351-134">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-134">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.IStorageAccountsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iStorageAccountsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, accountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12351-135">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-135">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="12351-136">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="12351-136">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="12351-137">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-137">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="12351-138">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="12351-138">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="12351-139">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="12351-139">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12351-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12351-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12351-141">Microsoft Azure でストレージ アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="12351-141">Deletes a storage account in Microsoft Azure.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="12351-142">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-142">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="12351-143">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-143">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; GetPropertiesWithHttpMessagesAsync (string resourceGroupName, string accountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; GetPropertiesWithHttpMessagesAsync(string resourceGroupName, string accountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.IStorageAccountsOperations.GetPropertiesWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPropertiesWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;" Usage="iStorageAccountsOperations.GetPropertiesWithHttpMessagesAsync (resourceGroupName, accountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12351-144">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-144">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="12351-145">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="12351-145">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="12351-146">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-146">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="12351-147">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="12351-147">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="12351-148">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="12351-148">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12351-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12351-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12351-150">指定されたストレージ アカウントなどは、name、SKU 名、場所、およびアカウントの状態のプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="12351-150">Returns the properties for the specified storage account including but not limited to name, SKU name, location, and account status.</span></span>
            <span data-ttu-id="12351-151">ListKeys 操作は、記憶域のキーの取得を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="12351-151">The ListKeys operation should be used to retrieve storage keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="12351-152">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-152">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="12351-153">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-153">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="12351-154">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-154">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAccountSASWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse&gt;&gt; ListAccountSASWithHttpMessagesAsync (string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.AccountSasParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse&gt;&gt; ListAccountSASWithHttpMessagesAsync(string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.AccountSasParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.IStorageAccountsOperations.ListAccountSASWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Storage.Models.AccountSasParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAccountSASWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Storage.Models.AccountSasParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse&gt;&gt;" Usage="iStorageAccountsOperations.ListAccountSASWithHttpMessagesAsync (resourceGroupName, accountName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.ListAccountSasResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.AccountSasParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12351-155">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-155">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="12351-156">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="12351-156">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="12351-157">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-157">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="12351-158">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="12351-158">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="12351-159">ストレージ アカウントの一覧の SAS の資格情報を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="12351-159">The parameters to provide to list SAS credentials for the storage account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="12351-160">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="12351-160">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12351-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12351-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12351-162">ストレージ アカウントの SAS の資格情報を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="12351-162">List SAS credentials of a storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="12351-163">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-163">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="12351-164">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-164">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="12351-165">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-165">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.IStorageAccountsOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12351-166">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-166">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="12351-167">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="12351-167">The name is case insensitive.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="12351-168">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="12351-168">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12351-169">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12351-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12351-170">指定したリソース グループで使用可能なすべてのストレージ アカウントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="12351-170">Lists all the storage accounts available under the given resource group.</span></span> <span data-ttu-id="12351-171">ストレージ キーが返されないことです。 注意してください。この ListKeys 操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="12351-171">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="12351-172">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-172">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="12351-173">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-173">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="12351-174">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-174">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;&gt; ListKeysWithHttpMessagesAsync (string resourceGroupName, string accountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;&gt; ListKeysWithHttpMessagesAsync(string resourceGroupName, string accountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.IStorageAccountsOperations.ListKeysWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListKeysWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;&gt;" Usage="iStorageAccountsOperations.ListKeysWithHttpMessagesAsync (resourceGroupName, accountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12351-175">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-175">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="12351-176">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="12351-176">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="12351-177">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-177">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="12351-178">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="12351-178">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="12351-179">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="12351-179">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12351-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12351-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12351-181">指定されたストレージ アカウントのアクセス キーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="12351-181">Lists the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="12351-182">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-182">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="12351-183">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-183">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="12351-184">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-184">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListServiceSASWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse&gt;&gt; ListServiceSASWithHttpMessagesAsync (string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.ServiceSasParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse&gt;&gt; ListServiceSASWithHttpMessagesAsync(string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.ServiceSasParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.IStorageAccountsOperations.ListServiceSASWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Storage.Models.ServiceSasParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListServiceSASWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Storage.Models.ServiceSasParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse&gt;&gt;" Usage="iStorageAccountsOperations.ListServiceSASWithHttpMessagesAsync (resourceGroupName, accountName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.ListServiceSasResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.ServiceSasParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12351-185">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-185">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="12351-186">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="12351-186">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="12351-187">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-187">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="12351-188">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="12351-188">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="12351-189">リスト サービスの SAS の資格情報を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="12351-189">The parameters to provide to list service SAS credentials.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="12351-190">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="12351-190">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12351-191">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12351-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12351-192">特定のリソースのサービスの SAS 資格情報を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="12351-192">List service SAS credentials of a specific resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="12351-193">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-193">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="12351-194">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-194">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="12351-195">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-195">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.IStorageAccountsOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="12351-196">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="12351-196">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12351-197">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12351-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12351-198">サブスクリプションで使用可能なすべてのストレージ アカウントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="12351-198">Lists all the storage accounts available under the subscription.</span></span>
            <span data-ttu-id="12351-199">ストレージ キーが返されないことです。 注意してください。この ListKeys 操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="12351-199">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="12351-200">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-200">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="12351-201">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-201">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="12351-202">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-202">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;&gt; RegenerateKeyWithHttpMessagesAsync (string resourceGroupName, string accountName, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;&gt; RegenerateKeyWithHttpMessagesAsync(string resourceGroupName, string accountName, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.IStorageAccountsOperations.RegenerateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;&gt;" Usage="iStorageAccountsOperations.RegenerateKeyWithHttpMessagesAsync (resourceGroupName, accountName, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccountListKeysResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12351-203">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-203">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="12351-204">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="12351-204">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="12351-205">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-205">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="12351-206">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="12351-206">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="12351-207">再生成された、可能な値を許可する記憶域のキーの名前は、key1、key2 です。</span><span class="sxs-lookup"><span data-stu-id="12351-207">The name of storage keys that want to be regenerated, possible vaules are key1, key2.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="12351-208">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="12351-208">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12351-209">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12351-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12351-210">指定されたストレージ アカウントのアクセス キーの 1 つを再生成します。</span><span class="sxs-lookup"><span data-stu-id="12351-210">Regenerates one of the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="12351-211">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-211">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="12351-212">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-212">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="12351-213">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-213">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.IStorageAccountsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;" Usage="iStorageAccountsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, accountName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Models.StorageAccount&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Models.StorageAccountUpdateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12351-214">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-214">The name of the resource group within the user's subscription.</span></span> <span data-ttu-id="12351-215">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="12351-215">The name is case insensitive.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="12351-216">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12351-216">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="12351-217">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="12351-217">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="12351-218">更新されたアカウントを提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="12351-218">The parameters to provide for the updated account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="12351-219">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="12351-219">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12351-220">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12351-220">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12351-221">更新操作は、SKU、暗号化、アクセス層、またはストレージ アカウント用のタグの更新を使用できます。</span><span class="sxs-lookup"><span data-stu-id="12351-221">The update operation can be used to update the SKU, encryption, access tier, or tags for a storage account.</span></span> <span data-ttu-id="12351-222">カスタム ドメインにアカウントをマップにも使用できます。</span><span class="sxs-lookup"><span data-stu-id="12351-222">It can also be used to map the account to a custom domain.</span></span> <span data-ttu-id="12351-223">ストレージ アカウントごとに 1 つのカスタム ドメインがサポートされます。カスタム ドメインの置換と変更はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="12351-223">Only one custom domain is supported per storage account; the replacement/change of custom domain is not supported.</span></span> <span data-ttu-id="12351-224">古いカスタム ドメインを置換するために古い値でなければなりませんクリア未登録の新しい値を設定する前に。</span><span class="sxs-lookup"><span data-stu-id="12351-224">In order to replace an old custom domain, the old value must be cleared/unregistered before a new value can be set.</span></span> <span data-ttu-id="12351-225">複数のプロパティの更新はサポートされています。</span><span class="sxs-lookup"><span data-stu-id="12351-225">The update of multiple properties is supported.</span></span> <span data-ttu-id="12351-226">この呼び出しでは、ストレージ アカウントのキーは変更されません。</span><span class="sxs-lookup"><span data-stu-id="12351-226">This call does not change the storage keys for the account.</span></span> <span data-ttu-id="12351-227">ストレージ アカウント キーを変更する場合は、再生成のキー操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="12351-227">If you want to change the storage account keys, use the regenerate keys operation.</span></span>
            <span data-ttu-id="12351-228">作成後は、ストレージ アカウントの名前と場所を変更できません。</span><span class="sxs-lookup"><span data-stu-id="12351-228">The location and name of the storage account cannot be changed after creation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="12351-229">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-229">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="12351-230">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-230">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="12351-231">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="12351-231">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>