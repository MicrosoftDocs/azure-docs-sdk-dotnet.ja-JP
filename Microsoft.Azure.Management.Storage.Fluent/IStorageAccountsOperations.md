<Type Name="IStorageAccountsOperations" FullName="Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations">
  <TypeSignature Language="C#" Value="public interface IStorageAccountsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStorageAccountsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStorageAccountsOperations" />
  <TypeSignature Language="F#" Value="type IStorageAccountsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e5d8e-101">StorageAccountsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-101">StorageAccountsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;" Usage="iStorageAccountsOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, accountName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e5d8e-102">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-102">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e5d8e-103">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-103">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="e5d8e-104">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-104">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e5d8e-105">作成したアカウントを提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-105">The parameters to provide for the created account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e5d8e-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e5d8e-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5d8e-108">指定されたパラメーターで新しいストレージ アカウントを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-108">Asynchronously creates a new storage account with the specified parameters.</span></span> <span data-ttu-id="e5d8e-109">アカウントが既に作成されて、別のプロパティを持つ後続の作成要求が発行される場合は、アカウントのプロパティが更新されます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-109">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="e5d8e-110">アカウントが既に作成されていて、正確な同じ一連のプロパティとそれ以降の作成または更新要求が発行された、要求は成功します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-110">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e5d8e-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e5d8e-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e5d8e-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync (string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync(string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.CheckNameAvailabilityWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckNameAvailabilityWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt;&gt;" Usage="iStorageAccountsOperations.CheckNameAvailabilityWithHttpMessagesAsync (name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.CheckNameAvailabilityResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name"></param>
        <param name="customHeaders">
            <span data-ttu-id="e5d8e-114">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-114">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e5d8e-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5d8e-116">ストレージ アカウント名が有効で既に使用されていないことを確認します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-116">Checks that the storage account name is valid and is not already in use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e5d8e-117">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-117">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e5d8e-118">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-118">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e5d8e-119">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.CreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;" Usage="iStorageAccountsOperations.CreateWithHttpMessagesAsync (resourceGroupName, accountName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountCreateParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e5d8e-120">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-120">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e5d8e-121">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-121">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="e5d8e-122">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-122">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e5d8e-123">作成したアカウントを提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-123">The parameters to provide for the created account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e5d8e-124">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e5d8e-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5d8e-126">指定されたパラメーターで新しいストレージ アカウントを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-126">Asynchronously creates a new storage account with the specified parameters.</span></span> <span data-ttu-id="e5d8e-127">アカウントが既に作成されて、別のプロパティを持つ後続の作成要求が発行される場合は、アカウントのプロパティが更新されます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-127">If an account is already created and a subsequent create request is issued with different properties, the account properties will be updated.</span></span> <span data-ttu-id="e5d8e-128">アカウントが既に作成されていて、正確な同じ一連のプロパティとそれ以降の作成または更新要求が発行された、要求は成功します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-128">If an account is already created and a subsequent create or update request is issued with the exact same set of properties, the request will succeed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e5d8e-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e5d8e-130">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e5d8e-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iStorageAccountsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, accountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e5d8e-132">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-132">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e5d8e-133">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-133">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="e5d8e-134">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-134">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e5d8e-135">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-135">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e5d8e-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5d8e-137">Microsoft Azure でストレージ アカウントを削除します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-137">Deletes a storage account in Microsoft Azure.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e5d8e-138">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-138">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e5d8e-139">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-139">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertiesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; GetPropertiesWithHttpMessagesAsync (string resourceGroupName, string accountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; GetPropertiesWithHttpMessagesAsync(string resourceGroupName, string accountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.GetPropertiesWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPropertiesWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;" Usage="iStorageAccountsOperations.GetPropertiesWithHttpMessagesAsync (resourceGroupName, accountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e5d8e-140">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-140">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e5d8e-141">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-141">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="e5d8e-142">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-142">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e5d8e-143">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-143">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e5d8e-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5d8e-145">指定されたストレージ アカウントなどは、name、SKU 名、場所、およびアカウントの状態のプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-145">Returns the properties for the specified storage account including but not limited to name, SKU name, location, and account status.</span></span>
            <span data-ttu-id="e5d8e-146">ListKeys 操作は、記憶域のキーの取得を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-146">The ListKeys operation should be used to retrieve storage keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e5d8e-147">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e5d8e-148">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-148">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e5d8e-149">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e5d8e-150">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-150">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e5d8e-151">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e5d8e-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5d8e-153">指定したリソース グループで使用可能なすべてのストレージ アカウントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-153">Lists all the storage accounts available under the given resource group.</span></span> <span data-ttu-id="e5d8e-154">ストレージ キーが返されないことです。 注意してください。この ListKeys 操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-154">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e5d8e-155">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-155">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e5d8e-156">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-156">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e5d8e-157">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-157">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;&gt; ListKeysWithHttpMessagesAsync (string resourceGroupName, string accountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;&gt; ListKeysWithHttpMessagesAsync(string resourceGroupName, string accountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.ListKeysWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListKeysWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;&gt;" Usage="iStorageAccountsOperations.ListKeysWithHttpMessagesAsync (resourceGroupName, accountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e5d8e-158">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-158">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e5d8e-159">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-159">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="e5d8e-160">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-160">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e5d8e-161">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-161">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e5d8e-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5d8e-163">指定されたストレージ アカウントのアクセス キーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-163">Lists the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e5d8e-164">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-164">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e5d8e-165">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-165">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e5d8e-166">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-166">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="e5d8e-167">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-167">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e5d8e-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5d8e-169">サブスクリプションで使用可能なすべてのストレージ アカウントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-169">Lists all the storage accounts available under the subscription.</span></span>
            <span data-ttu-id="e5d8e-170">ストレージ キーが返されないことです。 注意してください。この ListKeys 操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-170">Note that storage keys are not returned; use the ListKeys operation for this.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e5d8e-171">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-171">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e5d8e-172">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-172">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e5d8e-173">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-173">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;&gt; RegenerateKeyWithHttpMessagesAsync (string resourceGroupName, string accountName, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;&gt; RegenerateKeyWithHttpMessagesAsync(string resourceGroupName, string accountName, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.RegenerateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;&gt;" Usage="iStorageAccountsOperations.RegenerateKeyWithHttpMessagesAsync (resourceGroupName, accountName, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountListKeysResultInner&gt;&gt;</ReturnType>
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
            <span data-ttu-id="e5d8e-174">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-174">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e5d8e-175">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-175">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="e5d8e-176">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-176">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="keyName"></param>
        <param name="customHeaders">
            <span data-ttu-id="e5d8e-177">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-177">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e5d8e-178">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5d8e-179">指定されたストレージ アカウントのアクセス キーの 1 つを再生成します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-179">Regenerates one of the access keys for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e5d8e-180">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-180">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e5d8e-181">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-181">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e5d8e-182">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-182">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string accountName, Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string accountName, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccountsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;" Usage="iStorageAccountsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, accountName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e5d8e-183">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-183">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="e5d8e-184">指定されたリソース グループ内にあるストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-184">The name of the storage account within the specified resource group.</span></span> <span data-ttu-id="e5d8e-185">ストレージ アカウント名の長さは 3 ～ 24 文字で、数字と小文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-185">Storage account names must be between 3 and 24 characters in length and use numbers and lower-case letters only.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e5d8e-186">更新されたアカウントを提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-186">The parameters to provide for the updated account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e5d8e-187">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-187">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e5d8e-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5d8e-189">更新操作は、SKU、暗号化、アクセス層、またはストレージ アカウント用のタグの更新を使用できます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-189">The update operation can be used to update the SKU, encryption, access tier, or tags for a storage account.</span></span> <span data-ttu-id="e5d8e-190">カスタム ドメインにアカウントをマップにも使用できます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-190">It can also be used to map the account to a custom domain.</span></span> <span data-ttu-id="e5d8e-191">ストレージ アカウントごとに 1 つのカスタム ドメインがサポートされます。カスタム ドメインの置換と変更はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-191">Only one custom domain is supported per storage account; the replacement/change of custom domain is not supported.</span></span> <span data-ttu-id="e5d8e-192">古いカスタム ドメインを置換するために古い値でなければなりませんクリア未登録の新しい値を設定する前に。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-192">In order to replace an old custom domain, the old value must be cleared/unregistered before a new value can be set.</span></span> <span data-ttu-id="e5d8e-193">複数のプロパティの更新はサポートされています。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-193">The update of multiple properties is supported.</span></span> <span data-ttu-id="e5d8e-194">この呼び出しでは、ストレージ アカウントのキーは変更されません。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-194">This call does not change the storage keys for the account.</span></span> <span data-ttu-id="e5d8e-195">ストレージ アカウント キーを変更する場合は、再生成のキー操作を使用します。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-195">If you want to change the storage account keys, use the regenerate keys operation.</span></span>
            <span data-ttu-id="e5d8e-196">作成後は、ストレージ アカウントの名前と場所を変更できません。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-196">The location and name of the storage account cannot be changed after creation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e5d8e-197">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-197">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e5d8e-198">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-198">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e5d8e-199">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e5d8e-199">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>