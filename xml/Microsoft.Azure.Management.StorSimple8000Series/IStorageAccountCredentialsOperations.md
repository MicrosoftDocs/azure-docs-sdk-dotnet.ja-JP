<Type Name="IStorageAccountCredentialsOperations" FullName="Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations">
  <TypeSignature Language="C#" Value="public interface IStorageAccountCredentialsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStorageAccountCredentialsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStorageAccountCredentialsOperations" />
  <TypeSignature Language="F#" Value="type IStorageAccountCredentialsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f1829-101">StorageAccountCredentialsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="f1829-101">StorageAccountCredentialsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string storageAccountCredentialName, Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string storageAccountCredentialName, class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt;" Usage="iStorageAccountCredentialsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (storageAccountCredentialName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountCredentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="storageAccountCredentialName">
            <span data-ttu-id="f1829-102">ストレージ アカウントの資格情報名。</span><span class="sxs-lookup"><span data-stu-id="f1829-102">The storage account credential name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f1829-103">ストレージ アカウントの資格情報を追加または更新します。</span><span class="sxs-lookup"><span data-stu-id="f1829-103">The storage account credential to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f1829-104">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f1829-104">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f1829-105">管理者名</span><span class="sxs-lookup"><span data-stu-id="f1829-105">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f1829-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f1829-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f1829-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f1829-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f1829-108">作成するか、ストレージ アカウントの資格情報を更新します。</span><span class="sxs-lookup"><span data-stu-id="f1829-108">Creates or updates the storage account credential.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f1829-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1829-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f1829-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1829-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f1829-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1829-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string storageAccountCredentialName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string storageAccountCredentialName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iStorageAccountCredentialsOperations.BeginDeleteWithHttpMessagesAsync (storageAccountCredentialName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountCredentialName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="storageAccountCredentialName">
            <span data-ttu-id="f1829-112">ストレージ アカウントの資格情報の名前。</span><span class="sxs-lookup"><span data-stu-id="f1829-112">The name of the storage account credential.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f1829-113">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f1829-113">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f1829-114">管理者名</span><span class="sxs-lookup"><span data-stu-id="f1829-114">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f1829-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f1829-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f1829-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f1829-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f1829-117">ストレージ アカウントの資格情報を削除します。</span><span class="sxs-lookup"><span data-stu-id="f1829-117">Deletes the storage account credential.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f1829-118">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1829-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f1829-119">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1829-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string storageAccountCredentialName, Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string storageAccountCredentialName, class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt;" Usage="iStorageAccountCredentialsOperations.CreateOrUpdateWithHttpMessagesAsync (storageAccountCredentialName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountCredentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="storageAccountCredentialName">
            <span data-ttu-id="f1829-120">ストレージ アカウントの資格情報名。</span><span class="sxs-lookup"><span data-stu-id="f1829-120">The storage account credential name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f1829-121">ストレージ アカウントの資格情報を追加または更新します。</span><span class="sxs-lookup"><span data-stu-id="f1829-121">The storage account credential to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f1829-122">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f1829-122">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f1829-123">管理者名</span><span class="sxs-lookup"><span data-stu-id="f1829-123">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f1829-124">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f1829-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f1829-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f1829-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f1829-126">作成するか、ストレージ アカウントの資格情報を更新します。</span><span class="sxs-lookup"><span data-stu-id="f1829-126">Creates or updates the storage account credential.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f1829-127">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1829-127">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f1829-128">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1829-128">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f1829-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1829-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string storageAccountCredentialName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string storageAccountCredentialName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iStorageAccountCredentialsOperations.DeleteWithHttpMessagesAsync (storageAccountCredentialName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountCredentialName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="storageAccountCredentialName">
            <span data-ttu-id="f1829-130">ストレージ アカウントの資格情報の名前。</span><span class="sxs-lookup"><span data-stu-id="f1829-130">The name of the storage account credential.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f1829-131">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f1829-131">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f1829-132">管理者名</span><span class="sxs-lookup"><span data-stu-id="f1829-132">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f1829-133">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f1829-133">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f1829-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f1829-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f1829-135">ストレージ アカウントの資格情報を削除します。</span><span class="sxs-lookup"><span data-stu-id="f1829-135">Deletes the storage account credential.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f1829-136">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1829-136">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f1829-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1829-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt; GetWithHttpMessagesAsync (string storageAccountCredentialName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt; GetWithHttpMessagesAsync(string storageAccountCredentialName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt;" Usage="iStorageAccountCredentialsOperations.GetWithHttpMessagesAsync (storageAccountCredentialName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountCredentialName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="storageAccountCredentialName">
            <span data-ttu-id="f1829-138">フェッチするストレージ アカウントの資格情報の名前。</span><span class="sxs-lookup"><span data-stu-id="f1829-138">The name of storage account credential to be fetched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="f1829-139">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f1829-139">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f1829-140">管理者名</span><span class="sxs-lookup"><span data-stu-id="f1829-140">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f1829-141">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f1829-141">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f1829-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f1829-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f1829-143">指定されたストレージ アカウントの資格情報名のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="f1829-143">Gets the properties of the specified storage account credential name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f1829-144">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1829-144">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f1829-145">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1829-145">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f1829-146">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1829-146">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt;&gt; ListByManagerWithHttpMessagesAsync (string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt;&gt; ListByManagerWithHttpMessagesAsync(string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IStorageAccountCredentialsOperations.ListByManagerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByManagerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt;&gt;" Usage="iStorageAccountCredentialsOperations.ListByManagerWithHttpMessagesAsync (resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f1829-147">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="f1829-147">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="f1829-148">管理者名</span><span class="sxs-lookup"><span data-stu-id="f1829-148">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f1829-149">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f1829-149">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f1829-150">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f1829-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f1829-151">マネージャー内のすべてのストレージ アカウントの資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f1829-151">Gets all the storage account credentials in a manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f1829-152">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1829-152">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f1829-153">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1829-153">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f1829-154">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f1829-154">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>