<Type Name="IStorageAccountsOperations" FullName="Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations">
  <TypeSignature Language="C#" Value="public interface IStorageAccountsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStorageAccountsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStorageAccountsOperations" />
  <TypeSignature Language="F#" Value="type IStorageAccountsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b411c-101">StorageAccountsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="b411c-101">StorageAccountsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; AddWithHttpMessagesAsync (string resourceGroupName, string accountName, string storageAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; AddWithHttpMessagesAsync(string resourceGroupName, string accountName, string storageAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.AddWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iStorageAccountsOperations.AddWithHttpMessagesAsync (resourceGroupName, accountName, storageAccountName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.AddStorageAccountParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b411c-102">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-102">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="b411c-103">Azure ストレージ アカウントを追加する、Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-103">The name of the Data Lake Analytics account to which to add the Azure Storage account.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="b411c-104">追加する Azure ストレージ アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="b411c-104">The name of the Azure Storage account to add</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b411c-105">Azure ストレージ アカウントのアクセス キーと省略可能なサフィックスを含むパラメーター。</span><span class="sxs-lookup"><span data-stu-id="b411c-105">The parameters containing the access key and optional suffix for the Azure Storage Account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b411c-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b411c-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b411c-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b411c-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b411c-108">Azure ストレージ アカウントを追加する指定された Data Lake Analytics アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="b411c-108">Updates the specified Data Lake Analytics account to add an Azure Storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b411c-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b411c-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, string storageAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, string storageAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iStorageAccountsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, accountName, storageAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b411c-111">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-111">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="b411c-112">Azure ストレージ アカウントを削除する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-112">The name of the Data Lake Analytics account from which to remove the Azure Storage account.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="b411c-113">削除する Azure ストレージ アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="b411c-113">The name of the Azure Storage account to remove</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b411c-114">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b411c-114">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b411c-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b411c-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b411c-116">Azure ストレージ アカウントを削除する指定された Data Lake Analytics アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="b411c-116">Updates the specified Data Lake Analytics account to remove an Azure Storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b411c-117">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-117">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b411c-118">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-118">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetStorageContainerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt; GetStorageContainerWithHttpMessagesAsync (string resourceGroupName, string accountName, string storageAccountName, string containerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt; GetStorageContainerWithHttpMessagesAsync(string resourceGroupName, string accountName, string storageAccountName, string containerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.GetStorageContainerWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageContainerWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;" Usage="iStorageAccountsOperations.GetStorageContainerWithHttpMessagesAsync (resourceGroupName, accountName, storageAccountName, containerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b411c-119">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-119">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="b411c-120">Blob コンテナーを取得する対象の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-120">The name of the Data Lake Analytics account for which to retrieve blob container.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="b411c-121">Blob コンテナーを取得する対象の Azure ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-121">The name of the Azure storage account from which to retrieve the blob container.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="b411c-122">取得する Azure ストレージ コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="b411c-122">The name of the Azure storage container to retrieve</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b411c-123">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b411c-123">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b411c-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b411c-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b411c-125">指定された Data Lake Analytics と Azure ストレージ アカウントに関連付けられている指定された Azure ストレージ コンテナーを取得します。</span><span class="sxs-lookup"><span data-stu-id="b411c-125">Gets the specified Azure Storage container associated with the given Data Lake Analytics and Azure Storage accounts.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b411c-126">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-126">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b411c-127">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-127">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b411c-128">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-128">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string accountName, string storageAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string accountName, string storageAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;" Usage="iStorageAccountsOperations.GetWithHttpMessagesAsync (resourceGroupName, accountName, storageAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b411c-129">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-129">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="b411c-130">Azure ストレージ アカウントの詳細を取得する対象の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-130">The name of the Data Lake Analytics account from which to retrieve Azure storage account details.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="b411c-131">詳細を取得する対象の Azure ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-131">The name of the Azure Storage account for which to retrieve the details.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b411c-132">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b411c-132">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b411c-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b411c-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b411c-134">指定された Azure ストレージ アカウントが指定された Data Lake Analytics アカウントへのリンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="b411c-134">Gets the specified Azure Storage account linked to the given Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b411c-135">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-135">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b411c-136">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-136">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b411c-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;&gt; ListByAccountNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;&gt; ListByAccountNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.ListByAccountNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByAccountNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListByAccountNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="b411c-138">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="b411c-138">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b411c-139">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b411c-139">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b411c-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b411c-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b411c-141">指定された Data Lake Analytics アカウントに、リンクされている場合は、Azure ストレージ アカウントの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="b411c-141">Gets the first page of Azure Storage accounts, if any, linked to the specified Data Lake Analytics account.</span></span> <span data-ttu-id="b411c-142">応答には、存在する場合、次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="b411c-142">The response includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b411c-143">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b411c-144">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-144">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b411c-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;&gt; ListByAccountWithHttpMessagesAsync (string resourceGroupName, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;&gt; ListByAccountWithHttpMessagesAsync(string resourceGroupName, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.ListByAccountWithHttpMessagesAsync(System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByAccountWithHttpMessagesAsync : string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListByAccountWithHttpMessagesAsync (resourceGroupName, accountName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b411c-146">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-146">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="b411c-147">名前、Data Lake Analytics アカウントを Azure ストレージ アカウントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b411c-147">The name of the Data Lake Analytics account for which to list Azure Storage accounts.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="b411c-148">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="b411c-148">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="b411c-149">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="b411c-149">OData Select statement.</span></span> <span data-ttu-id="b411c-150">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="b411c-150">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="b411c-151">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b411c-151">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="b411c-152">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="b411c-152">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="b411c-153">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b411c-153">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b411c-154">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b411c-154">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b411c-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b411c-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b411c-156">指定された Data Lake Analytics アカウントに、リンクされている場合は、Azure ストレージ アカウントの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="b411c-156">Gets the first page of Azure Storage accounts, if any, linked to the specified Data Lake Analytics account.</span></span> <span data-ttu-id="b411c-157">応答には、存在する場合、次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="b411c-157">The response includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b411c-158">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-158">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b411c-159">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-159">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b411c-160">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-160">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListSasTokensNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;&gt; ListSasTokensNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;&gt; ListSasTokensNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.ListSasTokensNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSasTokensNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListSasTokensNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="b411c-161">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="b411c-161">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b411c-162">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b411c-162">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b411c-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b411c-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b411c-164">組み合わせに関連付けられた、指定された Data Lake Analytics と Azure ストレージ アカウントとコンテナーの SAS トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="b411c-164">Gets the SAS token associated with the specified Data Lake Analytics and Azure Storage account and container combination.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b411c-165">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-165">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b411c-166">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-166">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b411c-167">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-167">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListSasTokensWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;&gt; ListSasTokensWithHttpMessagesAsync (string resourceGroupName, string accountName, string storageAccountName, string containerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;&gt; ListSasTokensWithHttpMessagesAsync(string resourceGroupName, string accountName, string storageAccountName, string containerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.ListSasTokensWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSasTokensWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListSasTokensWithHttpMessagesAsync (resourceGroupName, accountName, storageAccountName, containerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SasTokenInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b411c-168">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-168">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="b411c-169">Azure ストレージ アカウントの SAS トークンの要求された Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-169">The name of the Data Lake Analytics account from which an Azure Storage account's SAS token is being requested.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="b411c-170">SAS トークンを要求する Azure のストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-170">The name of the Azure storage account for which the SAS token is being requested.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="b411c-171">SAS トークンを要求する対象の Azure ストレージ コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-171">The name of the Azure storage container for which the SAS token is being requested.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b411c-172">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b411c-172">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b411c-173">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b411c-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b411c-174">組み合わせに関連付けられた、指定された Data Lake Analytics と Azure ストレージ アカウントとコンテナーの SAS トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="b411c-174">Gets the SAS token associated with the specified Data Lake Analytics and Azure Storage account and container combination.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b411c-175">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-175">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b411c-176">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-176">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b411c-177">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-177">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListStorageContainersNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;&gt; ListStorageContainersNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;&gt; ListStorageContainersNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.ListStorageContainersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListStorageContainersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListStorageContainersNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="b411c-178">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="b411c-178">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b411c-179">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b411c-179">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b411c-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b411c-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b411c-181">指定された Data Lake Analytics と Azure ストレージ アカウントの組み合わせに関連付けられている場合は、Azure ストレージ コンテナーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b411c-181">Lists the Azure Storage containers, if any, associated with the specified Data Lake Analytics and Azure Storage account combination.</span></span> <span data-ttu-id="b411c-182">応答には、存在する場合、結果の次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="b411c-182">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b411c-183">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-183">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b411c-184">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-184">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b411c-185">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-185">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListStorageContainersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;&gt; ListStorageContainersWithHttpMessagesAsync (string resourceGroupName, string accountName, string storageAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;&gt; ListStorageContainersWithHttpMessagesAsync(string resourceGroupName, string accountName, string storageAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.ListStorageContainersWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListStorageContainersWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;&gt;" Usage="iStorageAccountsOperations.ListStorageContainersWithHttpMessagesAsync (resourceGroupName, accountName, storageAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageContainer&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b411c-186">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-186">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="b411c-187">名前 Data Lake Analytics アカウントを Azure Storage blob コンテナーの一覧にします。</span><span class="sxs-lookup"><span data-stu-id="b411c-187">The name of the Data Lake Analytics account for which to list Azure Storage blob containers.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="b411c-188">Blob コンテナーの一覧を表示する Azure のストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-188">The name of the Azure storage account from which to list blob containers.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b411c-189">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b411c-189">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b411c-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b411c-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b411c-191">指定された Data Lake Analytics と Azure ストレージ アカウントの組み合わせに関連付けられている場合は、Azure ストレージ コンテナーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b411c-191">Lists the Azure Storage containers, if any, associated with the specified Data Lake Analytics and Azure Storage account combination.</span></span> <span data-ttu-id="b411c-192">応答には、存在する場合、結果の次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="b411c-192">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b411c-193">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-193">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b411c-194">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-194">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b411c-195">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-195">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string accountName, string storageAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters parameters = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string accountName, string storageAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iStorageAccountsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, accountName, storageAccountName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateStorageAccountParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b411c-196">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b411c-196">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="b411c-197">内のストレージ アカウントを変更する Data Lake Analytics アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="b411c-197">The name of the Data Lake Analytics account to modify storage accounts in</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="b411c-198">Azure ストレージ アカウントを変更するには</span><span class="sxs-lookup"><span data-stu-id="b411c-198">The Azure Storage account to modify</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b411c-199">存在する場合に、アクセス キーと、ストレージ アカウントを更新するサフィックスを含むパラメーター。</span><span class="sxs-lookup"><span data-stu-id="b411c-199">The parameters containing the access key and suffix to update the storage account with, if any.</span></span> <span data-ttu-id="b411c-200">何も渡すことは、変更なしになります。</span><span class="sxs-lookup"><span data-stu-id="b411c-200">Passing nothing results in no change.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b411c-201">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b411c-201">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b411c-202">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b411c-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b411c-203">アクセス キーまたはサフィックスなど、Azure ストレージ blob アカウントの詳細を交換できる Data Lake Analytics アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="b411c-203">Updates the Data Lake Analytics account to replace Azure Storage blob account details, such as the access key and/or suffix.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b411c-204">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-204">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b411c-205">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b411c-205">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>