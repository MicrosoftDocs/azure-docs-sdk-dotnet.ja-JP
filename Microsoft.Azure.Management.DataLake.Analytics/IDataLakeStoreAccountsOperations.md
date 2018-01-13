<Type Name="IDataLakeStoreAccountsOperations" FullName="Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations">
  <TypeSignature Language="C#" Value="public interface IDataLakeStoreAccountsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataLakeStoreAccountsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataLakeStoreAccountsOperations" />
  <TypeSignature Language="F#" Value="type IDataLakeStoreAccountsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="abd6b-101">DataLakeStoreAccountsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="abd6b-101">DataLakeStoreAccountsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; AddWithHttpMessagesAsync (string resourceGroupName, string accountName, string dataLakeStoreAccountName, Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters parameters = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; AddWithHttpMessagesAsync(string resourceGroupName, string accountName, string dataLakeStoreAccountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations.AddWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDataLakeStoreAccountsOperations.AddWithHttpMessagesAsync (resourceGroupName, accountName, dataLakeStoreAccountName, parameters, customHeaders, cancellationToken)" />
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
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.AddDataLakeStoreParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="abd6b-102">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="abd6b-102">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="abd6b-103">Data Lake Store アカウントを追加する、Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="abd6b-103">The name of the Data Lake Analytics account to which to add the Data Lake Store account.</span></span>
            </param>
        <param name="dataLakeStoreAccountName">
            <span data-ttu-id="abd6b-104">追加する Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="abd6b-104">The name of the Data Lake Store account to add.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="abd6b-105">Data Lake Store アカウントの詳細。</span><span class="sxs-lookup"><span data-stu-id="abd6b-105">The details of the Data Lake Store account.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="abd6b-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="abd6b-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="abd6b-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="abd6b-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="abd6b-108">含める追加の Data Lake Store アカウントに指定された Data Lake Analytics アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="abd6b-108">Updates the specified Data Lake Analytics account to include the additional Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="abd6b-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="abd6b-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="abd6b-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="abd6b-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, string dataLakeStoreAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, string dataLakeStoreAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDataLakeStoreAccountsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, accountName, dataLakeStoreAccountName, customHeaders, cancellationToken)" />
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
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="abd6b-111">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="abd6b-111">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="abd6b-112">Data Lake Store アカウントを削除する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="abd6b-112">The name of the Data Lake Analytics account from which to remove the Data Lake Store account.</span></span>
            </param>
        <param name="dataLakeStoreAccountName">
            <span data-ttu-id="abd6b-113">削除する Data Lake Store アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="abd6b-113">The name of the Data Lake Store account to remove</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="abd6b-114">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="abd6b-114">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="abd6b-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="abd6b-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="abd6b-116">指定された Data Lake Store アカウントを削除する指定された Data Lake Analytics アカウントを更新します。</span><span class="sxs-lookup"><span data-stu-id="abd6b-116">Updates the Data Lake Analytics account specified to remove the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="abd6b-117">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="abd6b-117">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="abd6b-118">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="abd6b-118">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string accountName, string dataLakeStoreAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string accountName, string dataLakeStoreAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;" Usage="iDataLakeStoreAccountsOperations.GetWithHttpMessagesAsync (resourceGroupName, accountName, dataLakeStoreAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="dataLakeStoreAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="abd6b-119">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="abd6b-119">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="abd6b-120">Data Lake Store アカウントの詳細を取得する対象の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="abd6b-120">The name of the Data Lake Analytics account from which to retrieve the Data Lake Store account details.</span></span>
            </param>
        <param name="dataLakeStoreAccountName">
            <span data-ttu-id="abd6b-121">取得する Data Lake Store アカウントの名前</span><span class="sxs-lookup"><span data-stu-id="abd6b-121">The name of the Data Lake Store account to retrieve</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="abd6b-122">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="abd6b-122">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="abd6b-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="abd6b-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="abd6b-124">指定された Data Lake Analytics アカウントの指定された Data Lake Store アカウントの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="abd6b-124">Gets the specified Data Lake Store account details in the specified Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="abd6b-125">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="abd6b-125">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="abd6b-126">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="abd6b-126">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="abd6b-127">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="abd6b-127">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;&gt; ListByAccountNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;&gt; ListByAccountNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations.ListByAccountNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByAccountNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;&gt;" Usage="iDataLakeStoreAccountsOperations.ListByAccountNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="abd6b-128">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="abd6b-128">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="abd6b-129">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="abd6b-129">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="abd6b-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="abd6b-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="abd6b-131">Data Lake Store アカウントが指定された Data Lake Analytics アカウントへのリンクの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="abd6b-131">Gets the first page of Data Lake Store accounts linked to the specified Data Lake Analytics account.</span></span> <span data-ttu-id="abd6b-132">応答には、存在する場合、次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="abd6b-132">The response includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="abd6b-133">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="abd6b-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="abd6b-134">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="abd6b-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="abd6b-135">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="abd6b-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;&gt; ListByAccountWithHttpMessagesAsync (string resourceGroupName, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;&gt; ListByAccountWithHttpMessagesAsync(string resourceGroupName, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations.ListByAccountWithHttpMessagesAsync(System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByAccountWithHttpMessagesAsync : string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;&gt;" Usage="iDataLakeStoreAccountsOperations.ListByAccountWithHttpMessagesAsync (resourceGroupName, accountName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="abd6b-136">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="abd6b-136">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="abd6b-137">名前、Data Lake Analytics アカウントの Data Lake Store アカウントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="abd6b-137">The name of the Data Lake Analytics account for which to list Data Lake Store accounts.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="abd6b-138">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="abd6b-138">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="abd6b-139">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="abd6b-139">OData Select statement.</span></span> <span data-ttu-id="abd6b-140">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="abd6b-140">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="abd6b-141">省略可能。</span><span class="sxs-lookup"><span data-stu-id="abd6b-141">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="abd6b-142">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="abd6b-142">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="abd6b-143">省略可能。</span><span class="sxs-lookup"><span data-stu-id="abd6b-143">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="abd6b-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="abd6b-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="abd6b-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="abd6b-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="abd6b-146">Data Lake Store アカウントが指定された Data Lake Analytics アカウントへのリンクの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="abd6b-146">Gets the first page of Data Lake Store accounts linked to the specified Data Lake Analytics account.</span></span> <span data-ttu-id="abd6b-147">応答には、存在する場合、次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="abd6b-147">The response includes a link to the next page, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="abd6b-148">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="abd6b-148">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="abd6b-149">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="abd6b-149">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="abd6b-150">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="abd6b-150">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>