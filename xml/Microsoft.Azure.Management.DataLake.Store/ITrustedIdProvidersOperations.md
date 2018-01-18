<Type Name="ITrustedIdProvidersOperations" FullName="Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations">
  <TypeSignature Language="C#" Value="public interface ITrustedIdProvidersOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITrustedIdProvidersOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITrustedIdProvidersOperations" />
  <TypeSignature Language="F#" Value="type ITrustedIdProvidersOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1d971-101">TrustedIdProvidersOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="1d971-101">TrustedIdProvidersOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string accountName, string trustedIdProviderName, Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string accountName, string trustedIdProviderName, class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;" Usage="iTrustedIdProvidersOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, accountName, trustedIdProviderName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d971-102">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1d971-102">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1d971-103">Data Lake Store アカウントを追加または置き換える信頼できる id プロバイダーの名前。</span><span class="sxs-lookup"><span data-stu-id="1d971-103">The name of the Data Lake Store account to add or replace the trusted identity provider.</span></span>
            </param>
        <param name="trustedIdProviderName">
            <span data-ttu-id="1d971-104">信頼できる id プロバイダーの名前。</span><span class="sxs-lookup"><span data-stu-id="1d971-104">The name of the trusted identity provider.</span></span> <span data-ttu-id="1d971-105">これは、アカウント内のプロバイダーの差別化を使用されます。</span><span class="sxs-lookup"><span data-stu-id="1d971-105">This is used for differentiation of providers in the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1d971-106">信頼できる id プロバイダーを作成または指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="1d971-106">Parameters supplied to create or replace the trusted identity provider.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d971-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d971-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d971-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d971-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d971-109">作成するか、指定された信頼できる id プロバイダーを更新します。</span><span class="sxs-lookup"><span data-stu-id="1d971-109">Creates or updates the specified trusted identity provider.</span></span> <span data-ttu-id="1d971-110">この新しいプロバイダーを更新中に、信頼できる id プロバイダー、指定した名前は置き換えられます</span><span class="sxs-lookup"><span data-stu-id="1d971-110">During update, the trusted identity provider with the specified name will be replaced with this new provider</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d971-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d971-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d971-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, string trustedIdProviderName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, string trustedIdProviderName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iTrustedIdProvidersOperations.DeleteWithHttpMessagesAsync (resourceGroupName, accountName, trustedIdProviderName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d971-114">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1d971-114">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1d971-115">信頼できる id プロバイダーを削除する Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1d971-115">The name of the Data Lake Store account from which to delete the trusted identity provider.</span></span>
            </param>
        <param name="trustedIdProviderName">
            <span data-ttu-id="1d971-116">削除する信頼できる id プロバイダーの名前。</span><span class="sxs-lookup"><span data-stu-id="1d971-116">The name of the trusted identity provider to delete.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d971-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d971-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d971-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d971-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d971-119">指定された Data Lake Store アカウントから指定された信頼できる id プロバイダーを削除します。</span><span class="sxs-lookup"><span data-stu-id="1d971-119">Deletes the specified trusted identity provider from the specified Data Lake Store account</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d971-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d971-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string accountName, string trustedIdProviderName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string accountName, string trustedIdProviderName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;" Usage="iTrustedIdProvidersOperations.GetWithHttpMessagesAsync (resourceGroupName, accountName, trustedIdProviderName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d971-122">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1d971-122">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1d971-123">信頼できる id プロバイダーの取得元の Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1d971-123">The name of the Data Lake Store account from which to get the trusted identity provider.</span></span>
            </param>
        <param name="trustedIdProviderName">
            <span data-ttu-id="1d971-124">取得する信頼できる id プロバイダーの名前。</span><span class="sxs-lookup"><span data-stu-id="1d971-124">The name of the trusted identity provider to retrieve.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d971-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d971-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d971-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d971-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d971-127">指定された Data Lake Store 信頼できる id プロバイダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="1d971-127">Gets the specified Data Lake Store trusted identity provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d971-128">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d971-129">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-129">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d971-130">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-130">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;&gt; ListByAccountNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;&gt; ListByAccountNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations.ListByAccountNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByAccountNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;&gt;" Usage="iTrustedIdProvidersOperations.ListByAccountNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="1d971-131">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1d971-131">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d971-132">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d971-132">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d971-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d971-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d971-134">指定された Data Lake Store アカウント内で信頼できる Data Lake Store id プロバイダーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1d971-134">Lists the Data Lake Store trusted identity providers within the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d971-135">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-135">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d971-136">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-136">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d971-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;&gt; ListByAccountWithHttpMessagesAsync (string resourceGroupName, string accountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;&gt; ListByAccountWithHttpMessagesAsync(string resourceGroupName, string accountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations.ListByAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;&gt;" Usage="iTrustedIdProvidersOperations.ListByAccountWithHttpMessagesAsync (resourceGroupName, accountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d971-138">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1d971-138">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1d971-139">信頼できる id プロバイダーの取得元の Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1d971-139">The name of the Data Lake Store account from which to get the trusted identity providers.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d971-140">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d971-140">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d971-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d971-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d971-142">指定された Data Lake Store アカウント内で信頼できる Data Lake Store id プロバイダーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="1d971-142">Lists the Data Lake Store trusted identity providers within the specified Data Lake Store account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d971-143">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d971-144">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-144">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d971-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string accountName, string trustedIdProviderName, Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters parameters = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string accountName, string trustedIdProviderName, class Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.ITrustedIdProvidersOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;" Usage="iTrustedIdProvidersOperations.UpdateWithHttpMessagesAsync (resourceGroupName, accountName, trustedIdProviderName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Store.Models.TrustedIdProvider&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="trustedIdProviderName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Store.Models.UpdateTrustedIdProviderParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1d971-146">Data Lake Store アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1d971-146">The name of the Azure resource group that contains the Data Lake Store account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="1d971-147">信頼できる id プロバイダーを更新するために、Data Lake Store アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="1d971-147">The name of the Data Lake Store account to which to update the trusted identity provider.</span></span>
            </param>
        <param name="trustedIdProviderName">
            <span data-ttu-id="1d971-148">信頼できる id プロバイダーの名前。</span><span class="sxs-lookup"><span data-stu-id="1d971-148">The name of the trusted identity provider.</span></span> <span data-ttu-id="1d971-149">これは、アカウント内のプロバイダーの差別化を使用されます。</span><span class="sxs-lookup"><span data-stu-id="1d971-149">This is used for differentiation of providers in the account.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1d971-150">信頼できる id プロバイダーを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="1d971-150">Parameters supplied to update the trusted identity provider.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1d971-151">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1d971-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1d971-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1d971-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d971-153">指定された信頼できる id プロバイダーを更新します。</span><span class="sxs-lookup"><span data-stu-id="1d971-153">Updates the specified trusted identity provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1d971-154">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1d971-155">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1d971-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1d971-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>