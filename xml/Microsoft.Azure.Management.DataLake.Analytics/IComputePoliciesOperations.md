<Type Name="IComputePoliciesOperations" FullName="Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations">
  <TypeSignature Language="C#" Value="public interface IComputePoliciesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IComputePoliciesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IComputePoliciesOperations" />
  <TypeSignature Language="F#" Value="type IComputePoliciesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6cdf2-101">ComputePoliciesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-101">ComputePoliciesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string accountName, string computePolicyName, Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string accountName, string computePolicyName, class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;" Usage="iComputePoliciesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, accountName, computePolicyName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyCreateOrUpdateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6cdf2-102">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-102">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="6cdf2-103">Data Lake Analytics アカウントを追加または置き換えるコンピューティング ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-103">The name of the Data Lake Analytics account to add or replace the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="6cdf2-104">作成または更新するコンピューティング ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-104">The name of the compute policy to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6cdf2-105">作成またはコンピューティング ポリシーの更新に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-105">Parameters supplied to create or update the compute policy.</span></span> <span data-ttu-id="6cdf2-106">ジョブのプロパティごとの並列処理の次数の最大値、ジョブのプロパティ、またはその両方あたり最小優先度は存在しなければなりません。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-106">The max degree of parallelism per job property, min priority per job property, or both must be present.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6cdf2-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6cdf2-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6cdf2-109">作成するか、指定された計算ポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-109">Creates or updates the specified compute policy.</span></span> <span data-ttu-id="6cdf2-110">更新中に、指定した名前を持つコンピューティング ポリシーはこの新しいコンピューティング ポリシーに置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-110">During update, the compute policy with the specified name will be replaced with this new compute policy.</span></span> <span data-ttu-id="6cdf2-111">アカウント ポリシーをサポート、最大で 50</span><span class="sxs-lookup"><span data-stu-id="6cdf2-111">An account supports, at most, 50 policies</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6cdf2-112">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-112">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6cdf2-113">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-113">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6cdf2-114">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-114">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string accountName, string computePolicyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string accountName, string computePolicyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iComputePoliciesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, accountName, computePolicyName, customHeaders, cancellationToken)" />
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
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6cdf2-115">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-115">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="6cdf2-116">コンピューティングのポリシーを削除する Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-116">The name of the Data Lake Analytics account from which to delete the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="6cdf2-117">削除するコンピューティング ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-117">The name of the compute policy to delete.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6cdf2-118">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6cdf2-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6cdf2-120">指定された Data Lake Analytics アカウントから指定された計算のポリシーを削除します。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-120">Deletes the specified compute policy from the specified Data Lake Analytics account</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6cdf2-121">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-121">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6cdf2-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string accountName, string computePolicyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string accountName, string computePolicyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;" Usage="iComputePoliciesOperations.GetWithHttpMessagesAsync (resourceGroupName, accountName, computePolicyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6cdf2-123">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-123">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="6cdf2-124">コンピューティングのポリシーの取得元の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-124">The name of the Data Lake Analytics account from which to get the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="6cdf2-125">取得するコンピューティング ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-125">The name of the compute policy to retrieve.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6cdf2-126">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6cdf2-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6cdf2-128">指定された Data Lake Analytics 計算のポリシーを取得します。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-128">Gets the specified Data Lake Analytics compute policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6cdf2-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6cdf2-130">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6cdf2-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;&gt; ListByAccountNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;&gt; ListByAccountNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations.ListByAccountNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByAccountNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;&gt;" Usage="iComputePoliciesOperations.ListByAccountNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="6cdf2-132">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-132">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6cdf2-133">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-133">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6cdf2-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6cdf2-135">Data Lake Analytics の一覧は、指定された Data Lake Analytics アカウント内のポリシーを計算します。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-135">Lists the Data Lake Analytics compute policies within the specified Data Lake Analytics account.</span></span> <span data-ttu-id="6cdf2-136">アカウント ポリシーをサポート、最大で 50</span><span class="sxs-lookup"><span data-stu-id="6cdf2-136">An account supports, at most, 50 policies</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6cdf2-137">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-137">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6cdf2-138">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-138">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6cdf2-139">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-139">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;&gt; ListByAccountWithHttpMessagesAsync (string resourceGroupName, string accountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;&gt; ListByAccountWithHttpMessagesAsync(string resourceGroupName, string accountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations.ListByAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;&gt;" Usage="iComputePoliciesOperations.ListByAccountWithHttpMessagesAsync (resourceGroupName, accountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6cdf2-140">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-140">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="6cdf2-141">コンピューティングのポリシーの取得元の Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-141">The name of the Data Lake Analytics account from which to get the compute policies.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6cdf2-142">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-142">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6cdf2-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6cdf2-144">Data Lake Analytics の一覧は、指定された Data Lake Analytics アカウント内のポリシーを計算します。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-144">Lists the Data Lake Analytics compute policies within the specified Data Lake Analytics account.</span></span> <span data-ttu-id="6cdf2-145">アカウント ポリシーをサポート、最大で 50</span><span class="sxs-lookup"><span data-stu-id="6cdf2-145">An account supports, at most, 50 policies</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6cdf2-146">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-146">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6cdf2-147">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-147">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6cdf2-148">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-148">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string accountName, string computePolicyName, Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy parameters = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string accountName, string computePolicyName, class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;" Usage="iComputePoliciesOperations.UpdateWithHttpMessagesAsync (resourceGroupName, accountName, computePolicyName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="computePolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicy" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6cdf2-149">Data Lake Analytics アカウントが含まれている Azure リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-149">The name of the Azure resource group that contains the Data Lake Analytics account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="6cdf2-150">コンピューティング ポリシーを更新するために、Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-150">The name of the Data Lake Analytics account to which to update the compute policy.</span></span>
            </param>
        <param name="computePolicyName">
            <span data-ttu-id="6cdf2-151">更新するコンピューティング ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-151">The name of the compute policy to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6cdf2-152">コンピューティングのポリシーの更新に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-152">Parameters supplied to update the compute policy.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6cdf2-153">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-153">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6cdf2-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6cdf2-155">指定された計算のポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-155">Updates the specified compute policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6cdf2-156">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-156">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6cdf2-157">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-157">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6cdf2-158">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6cdf2-158">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>