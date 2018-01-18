<Type Name="IIndexesOperations" FullName="Microsoft.Azure.Search.IIndexesOperations">
  <TypeSignature Language="C#" Value="public interface IIndexesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IIndexesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.IIndexesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IIndexesOperations" />
  <TypeSignature Language="F#" Value="type IIndexesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="41868-101">IndexesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="41868-101">IndexesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AnalyzeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.AnalyzeResult&gt;&gt; AnalyzeWithHttpMessagesAsync (string indexName, Microsoft.Azure.Search.Models.AnalyzeRequest request, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.AnalyzeResult&gt;&gt; AnalyzeWithHttpMessagesAsync(string indexName, class Microsoft.Azure.Search.Models.AnalyzeRequest request, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.AnalyzeWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.AnalyzeRequest,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AnalyzeWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.AnalyzeRequest * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.AnalyzeResult&gt;&gt;" Usage="iIndexesOperations.AnalyzeWithHttpMessagesAsync (indexName, request, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.AnalyzeResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="request" Type="Microsoft.Azure.Search.Models.AnalyzeRequest" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="indexName">
            <span data-ttu-id="41868-102">アナライザーのテスト対象のインデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="41868-102">The name of the index for which to test an analyzer.</span></span>
            </param>
        <param name="request">
            <span data-ttu-id="41868-103">テキストやアナライザー、分析コンポーネントをテストします。</span><span class="sxs-lookup"><span data-stu-id="41868-103">The text and analyzer or analysis components to test.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="41868-104">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="41868-104">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="41868-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="41868-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="41868-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="41868-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="41868-107">アナライザーがトークンにテキストを分割する方法を示しています。</span><span class="sxs-lookup"><span data-stu-id="41868-107">Shows how an analyzer breaks text into tokens.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/test-analyzer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="41868-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="41868-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="41868-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (Microsoft.Azure.Search.Models.Index index, Nullable&lt;bool&gt; allowIndexDowntime = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.Index&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.Index index, valuetype System.Nullable`1&lt;bool&gt; allowIndexDowntime, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.CreateOrUpdateWithHttpMessagesAsync(Microsoft.Azure.Search.Models.Index,System.Nullable{System.Boolean},Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : Microsoft.Azure.Search.Models.Index * Nullable&lt;bool&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt;" Usage="iIndexesOperations.CreateOrUpdateWithHttpMessagesAsync (index, allowIndexDowntime, searchRequestOptions, accessCondition, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="allowIndexDowntime" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="index">
            <span data-ttu-id="41868-111">インデックスを作成または更新の定義。</span><span class="sxs-lookup"><span data-stu-id="41868-111">The definition of the index to create or update.</span></span>
            </param>
        <param name="allowIndexDowntime">
            <span data-ttu-id="41868-112">で数秒以上のオフラインのインデックスを取得することにより、インデックスに追加する新しいアナライザー、されなければ、トークンのフィルターまたは char フィルターできます。</span><span class="sxs-lookup"><span data-stu-id="41868-112">Allows new analyzers, tokenizers, token filters, or char filters to be added to an index by taking the index offline for at least a few seconds.</span></span> <span data-ttu-id="41868-113">これにより、インデックスの作成とクエリの要求が失敗が一時的にさせます。</span><span class="sxs-lookup"><span data-stu-id="41868-113">This temporarily causes indexing and query requests to fail.</span></span> <span data-ttu-id="41868-114">インデックスを更新すると、インデックスのパフォーマンスと書き込み可用性が数分にわたり損なわれる場合があります。インデックスが非常に大きい場合、その時間も長くなります。</span><span class="sxs-lookup"><span data-stu-id="41868-114">Performance and write availability of the index can be impaired for several minutes after the index is updated, or longer for very large indexes.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="41868-115">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="41868-115">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="41868-116">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="41868-116">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="41868-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="41868-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="41868-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="41868-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="41868-119">新しい Azure Search インデックスを作成または、既に存在する場合、インデックスを更新します。</span><span class="sxs-lookup"><span data-stu-id="41868-119">Creates a new Azure Search index or updates an index if it already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string indexName, Microsoft.Azure.Search.Models.Index index, Nullable&lt;bool&gt; allowIndexDowntime = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.Index&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string indexName, class Microsoft.Azure.Search.Models.Index index, valuetype System.Nullable`1&lt;bool&gt; allowIndexDowntime, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.Index,System.Nullable{System.Boolean},Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.Index * Nullable&lt;bool&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt;" Usage="iIndexesOperations.CreateOrUpdateWithHttpMessagesAsync (indexName, index, allowIndexDowntime, searchRequestOptions, accessCondition, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="allowIndexDowntime" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="indexName">
            <span data-ttu-id="41868-120">インデックスを作成または更新の定義。</span><span class="sxs-lookup"><span data-stu-id="41868-120">The definition of the index to create or update.</span></span>
            </param>
        <param name="index">
            <span data-ttu-id="41868-121">インデックスを作成または更新の定義。</span><span class="sxs-lookup"><span data-stu-id="41868-121">The definition of the index to create or update.</span></span>
            </param>
        <param name="allowIndexDowntime">
            <span data-ttu-id="41868-122">で数秒以上のオフラインのインデックスを取得することにより、インデックスに追加する新しいアナライザー、されなければ、トークンのフィルターまたは char フィルターできます。</span><span class="sxs-lookup"><span data-stu-id="41868-122">Allows new analyzers, tokenizers, token filters, or char filters to be added to an index by taking the index offline for at least a few seconds.</span></span> <span data-ttu-id="41868-123">これにより、インデックスの作成とクエリの要求が失敗が一時的にさせます。</span><span class="sxs-lookup"><span data-stu-id="41868-123">This temporarily causes indexing and query requests to fail.</span></span> <span data-ttu-id="41868-124">インデックスを更新すると、インデックスのパフォーマンスと書き込み可用性が数分にわたり損なわれる場合があります。インデックスが非常に大きい場合、その時間も長くなります。</span><span class="sxs-lookup"><span data-stu-id="41868-124">Performance and write availability of the index can be impaired for several minutes after the index is updated, or longer for very large indexes.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="41868-125">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="41868-125">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="41868-126">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="41868-126">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="41868-127">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="41868-127">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="41868-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="41868-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="41868-129">新しい Azure Search インデックスを作成または、既に存在する場合、インデックスを更新します。</span><span class="sxs-lookup"><span data-stu-id="41868-129">Creates a new Azure Search index or updates an index if it already exists.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="41868-130">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-130">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="41868-131">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-131">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="41868-132">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-132">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt; CreateWithHttpMessagesAsync (Microsoft.Azure.Search.Models.Index index, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.Index&gt;&gt; CreateWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.Index index, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.CreateWithHttpMessagesAsync(Microsoft.Azure.Search.Models.Index,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : Microsoft.Azure.Search.Models.Index * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt;" Usage="iIndexesOperations.CreateWithHttpMessagesAsync (index, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="index">
            <span data-ttu-id="41868-133">作成するインデックスの定義。</span><span class="sxs-lookup"><span data-stu-id="41868-133">The definition of the index to create.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="41868-134">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="41868-134">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="41868-135">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="41868-135">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="41868-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="41868-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="41868-137">新しい Azure Search インデックスを作成します。</span><span class="sxs-lookup"><span data-stu-id="41868-137">Creates a new Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="41868-138">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-138">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="41868-139">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-139">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="41868-140">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-140">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.DeleteWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iIndexesOperations.DeleteWithHttpMessagesAsync (indexName, searchRequestOptions, accessCondition, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="indexName">
            <span data-ttu-id="41868-141">削除するインデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="41868-141">The name of the index to delete.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="41868-142">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="41868-142">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="41868-143">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="41868-143">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="41868-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="41868-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="41868-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="41868-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="41868-146">Azure Search インデックスとが含まれているすべてのドキュメントを削除します。</span><span class="sxs-lookup"><span data-stu-id="41868-146">Deletes an Azure Search index and all the documents it contains.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="41868-147">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="41868-148">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-148">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ExistsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt; ExistsWithHttpMessagesAsync (string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;bool&gt;&gt; ExistsWithHttpMessagesAsync(string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.ExistsWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt;" Usage="iIndexesOperations.ExistsWithHttpMessagesAsync (indexName, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="indexName">
            <span data-ttu-id="41868-149">インデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="41868-149">The name of the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="41868-150">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="41868-150">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="41868-151">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="41868-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="41868-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="41868-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="41868-153">Azure Search サービスに指定されたインデックスが存在するかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="41868-153">Determines whether or not the given index exists in the Azure Search service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="41868-154">値を含む応答<c>true</c>インデックスが存在する場合<c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="41868-154">A response with the value <c>true</c> if the index exists; <c>false</c> otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClient">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.ISearchIndexClient GetClient (string indexName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Search.ISearchIndexClient GetClient(string indexName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.GetClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClient (indexName As String) As ISearchIndexClient" />
      <MemberSignature Language="F#" Value="abstract member GetClient : string -&gt; Microsoft.Azure.Search.ISearchIndexClient" Usage="iIndexesOperations.GetClient indexName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.ISearchIndexClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="indexName"><span data-ttu-id="41868-155">インデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="41868-155">The name of the index.</span></span></param>
        <summary>
            <span data-ttu-id="41868-156">クエリを実行すると、指定したインデックスにドキュメントを管理するには、インデックスの新しいクライアントを作成します。</span><span class="sxs-lookup"><span data-stu-id="41868-156">Creates a new index client for querying and managing documents in a given index.</span></span>
            </summary>
        <returns><span data-ttu-id="41868-157">新しい<c cref="T:Microsoft.Azure.Search.SearchIndexClient">SearchIndexClient</c>インスタンス。</span><span class="sxs-lookup"><span data-stu-id="41868-157">A new <c cref="T:Microsoft.Azure.Search.SearchIndexClient">SearchIndexClient</c> instance.</span></span></returns>
        <remarks>
            <span data-ttu-id="41868-158">新しいクライアントは、インデックスへの完全な読み取り/書き込みアクセスで構成されます。</span><span class="sxs-lookup"><span data-stu-id="41868-158">The new client is configured with full read-write access to the index.</span></span> <span data-ttu-id="41868-159">直接作成する方法をお勧めのみを計画しているクエリ操作でクライアントを使用する場合、 <c cref="T:Microsoft.Azure.Search.SearchIndexClient">SearchIndexClient</c>インスタンスの代わりにします。</span><span class="sxs-lookup"><span data-stu-id="41868-159">If you are only planning to use the client for query operations, we recommend directly creating a <c cref="T:Microsoft.Azure.Search.SearchIndexClient">SearchIndexClient</c> instance instead.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatisticsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt;&gt; GetStatisticsWithHttpMessagesAsync (string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt;&gt; GetStatisticsWithHttpMessagesAsync(string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.GetStatisticsWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStatisticsWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt;&gt;" Usage="iIndexesOperations.GetStatisticsWithHttpMessagesAsync (indexName, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="indexName">
            <span data-ttu-id="41868-160">統計情報を取得する対象のインデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="41868-160">The name of the index for which to retrieve statistics.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="41868-161">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="41868-161">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="41868-162">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="41868-162">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="41868-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="41868-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="41868-164">ドキュメントの数と記憶域の使用状況を含む、指定したインデックスの統計を返します。</span><span class="sxs-lookup"><span data-stu-id="41868-164">Returns statistics for the given index, including a document count and storage usage.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Index-Statistics" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="41868-165">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-165">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="41868-166">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-166">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="41868-167">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-167">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt; GetWithHttpMessagesAsync (string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.Index&gt;&gt; GetWithHttpMessagesAsync(string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.GetWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt;" Usage="iIndexesOperations.GetWithHttpMessagesAsync (indexName, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="indexName">
            <span data-ttu-id="41868-168">取得するインデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="41868-168">The name of the index to retrieve.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="41868-169">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="41868-169">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="41868-170">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="41868-170">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="41868-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="41868-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="41868-172">Azure Search からインデックス定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="41868-172">Retrieves an index definition from Azure Search.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="41868-173">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-173">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="41868-174">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-174">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="41868-175">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-175">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.IndexListResult&gt;&gt; ListWithHttpMessagesAsync (string select = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.IndexListResult&gt;&gt; ListWithHttpMessagesAsync(string select, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.ListWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.IndexListResult&gt;&gt;" Usage="iIndexesOperations.ListWithHttpMessagesAsync (select, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.IndexListResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="select">
            <span data-ttu-id="41868-176">取得するインデックスの定義のプロパティを選択します。</span><span class="sxs-lookup"><span data-stu-id="41868-176">Selects which properties of the index definitions to retrieve.</span></span>
            <span data-ttu-id="41868-177">JSON プロパティ名のコンマ区切りリストとして指定または ' \*' のすべてのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="41868-177">Specified as a comma-separated list of JSON property names, or '\*' for all properties.</span></span> <span data-ttu-id="41868-178">既定値は、すべてのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="41868-178">The default is all properties.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="41868-179">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="41868-179">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="41868-180">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="41868-180">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="41868-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="41868-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="41868-182">Azure Search サービスの使用可能なすべてのインデックスを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="41868-182">Lists all indexes available for an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexes" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="41868-183">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-183">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="41868-184">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-184">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="41868-185">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="41868-185">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>