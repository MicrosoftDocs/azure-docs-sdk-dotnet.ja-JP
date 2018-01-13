<Type Name="IDocumentsOperations" FullName="Microsoft.Azure.Search.IDocumentsOperations">
  <TypeSignature Language="C#" Value="public interface IDocumentsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDocumentsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.IDocumentsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDocumentsOperations" />
  <TypeSignature Language="F#" Value="type IDocumentsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="931b5-101">インデックスのクエリを実行し、アップロード、マージ、およびドキュメントを削除するための操作を定義します。</span><span class="sxs-lookup"><span data-stu-id="931b5-101">Defines operations for querying an index and uploading, merging, and deleting documents.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Document-operations" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinueSearchWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt; ContinueSearchWithHttpMessagesAsync (Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt; ContinueSearchWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.ContinueSearchWithHttpMessagesAsync(Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContinueSearchWithHttpMessagesAsync : Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt;" Usage="iDocumentsOperations.ContinueSearchWithHttpMessagesAsync (continuationToken, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="continuationToken">
            <span data-ttu-id="931b5-102">インデックスから検索結果の次のページをフェッチするために必要な状態をカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="931b5-102">Encapsulates the state required to fetch the next page of search results from the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="931b5-103">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="931b5-103">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="931b5-104">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="931b5-104">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="931b5-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="931b5-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="931b5-106">Azure Search インデックスから検索結果の次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="931b5-106">Retrieves the next page of search results from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="931b5-107">クエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="931b5-107">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="931b5-108">ContinueSearch、ContinueSearchAsync、および ContinueSearchWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。</span><span class="sxs-lookup"><span data-stu-id="931b5-108">The non-generic overloads of the ContinueSearch, ContinueSearchAsync, and ContinueSearchWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="931b5-109">詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="931b5-109">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="931b5-110">Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。</span><span class="sxs-lookup"><span data-stu-id="931b5-110">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="931b5-111">参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="931b5-111">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="931b5-112">このメソッドが検索結果のページングを実装するのに役立つことはないことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="931b5-112">Note that this method is not meant to help you implement paging of search results.</span></span> <span data-ttu-id="931b5-113">ページングを使用して実装することができます、<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">上部</c>と<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c>パラメーターを<c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">検索</c>メソッドです。</span><span class="sxs-lookup"><span data-stu-id="931b5-113">You can implement paging using the <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">Top</c> and <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c> parameters to the <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Search</c> method.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueSearchWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;&gt; ContinueSearchWithHttpMessagesAsync&lt;T&gt; (Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt;&gt;&gt; ContinueSearchWithHttpMessagesAsync&lt;class T&gt;(class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.ContinueSearchWithHttpMessagesAsync``1(Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContinueSearchWithHttpMessagesAsync : Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T&gt;&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.ContinueSearchWithHttpMessagesAsync (continuationToken, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="931b5-114">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="931b5-114">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="931b5-115">この型のインスタンスは、インデックスからドキュメントとして取得できます。</span><span class="sxs-lookup"><span data-stu-id="931b5-115">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="continuationToken">
            <span data-ttu-id="931b5-116">インデックスから検索結果の次のページをフェッチするために必要な状態をカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="931b5-116">Encapsulates the state required to fetch the next page of search results from the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="931b5-117">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="931b5-117">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="931b5-118">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="931b5-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="931b5-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="931b5-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="931b5-120">Azure Search インデックスから検索結果の次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="931b5-120">Retrieves the next page of search results from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="931b5-121">クエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="931b5-121">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="931b5-122">Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロード、ContinueSearch、ContinueSearchAsync、および ContinueSearchWithHttpMessagesAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="931b5-122">The generic overloads of the ContinueSearch, ContinueSearchAsync, and ContinueSearchWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </para>
          <para>
            <span data-ttu-id="931b5-123">Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。</span><span class="sxs-lookup"><span data-stu-id="931b5-123">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="931b5-124">参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="931b5-124">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="931b5-125">このメソッドが検索結果のページングを実装するのに役立つことはないことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="931b5-125">Note that this method is not meant to help you implement paging of search results.</span></span> <span data-ttu-id="931b5-126">ページングを使用して実装することができます、<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">上部</c>と<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c>パラメーターを<c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">検索</c>メソッドです。</span><span class="sxs-lookup"><span data-stu-id="931b5-126">You can implement paging using the <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">Top</c> and <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c> parameters to the <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Search</c> method.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;long&gt;&gt; CountWithHttpMessagesAsync (Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;int64&gt;&gt; CountWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.CountWithHttpMessagesAsync(Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CountWithHttpMessagesAsync : Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;int64&gt;&gt;" Usage="iDocumentsOperations.CountWithHttpMessagesAsync (searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Int64&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="searchRequestOptions">
            <span data-ttu-id="931b5-127">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="931b5-127">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="931b5-128">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="931b5-128">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="931b5-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="931b5-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="931b5-130">Azure Search インデックスにドキュメントの数を照会します。</span><span class="sxs-lookup"><span data-stu-id="931b5-130">Queries the number of documents in the Azure Search index.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Document&gt;&gt; GetWithHttpMessagesAsync (string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.Document&gt;&gt; GetWithHttpMessagesAsync(string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Document&gt;&gt;" Usage="iDocumentsOperations.GetWithHttpMessagesAsync (key, selectedFields, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="key">
            <span data-ttu-id="931b5-131">取得するドキュメントのキー参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" />の有効なドキュメント キーを構築するための規則。</span><span class="sxs-lookup"><span data-stu-id="931b5-131">The key of the document to retrieve; See <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> for the rules for constructing valid document keys.</span></span>
            </param>
        <param name="selectedFields">
            <span data-ttu-id="931b5-132">ドキュメントを取得するフィールド名の一覧任意のフィールドを取得できませんが、返されるドキュメント表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="931b5-132">List of field names to retrieve for the document; Any field not retrieved will be missing from the returned document.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="931b5-133">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="931b5-133">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="931b5-134">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="931b5-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="931b5-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="931b5-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="931b5-136">Azure Search インデックスからドキュメントを取得します。</span><span class="sxs-lookup"><span data-stu-id="931b5-136">Retrieves a document from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            <span data-ttu-id="931b5-137">ドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="931b5-137">Response containing the document.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="931b5-138">Get、されます、および GetWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。</span><span class="sxs-lookup"><span data-stu-id="931b5-138">The non-generic overloads of the Get, GetAsync, and GetWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="931b5-139">このマッピングには、インデックスから正確な型情報の利点はないので、マッピングが常に正しくありません。</span><span class="sxs-lookup"><span data-stu-id="931b5-139">This mapping does not have the benefit of precise type information from the index, so the mapping is not always correct.</span></span> <span data-ttu-id="931b5-140">具体的には、次の場合の注意をして: <list type="bullet"> <item> <description>小数点が System.Int64 (c# の long) を逆シリアル化することがなく値の任意の数値。</description></item><item><description>System.Double ではなく、System.String 型としては、特別な倍精度浮動小数点値 NaN、無限などを逆シリアル化されます。</description></item><item><description>DateTimeOffset のように書式設定値を持つ任意の文字列フィールドがする正しく逆シリアル化できません。Edm.String フィールドではなく Edm.DateTimeOffset フィールドにこのような値を格納することをお勧めします。</description></item><item><description>Edm.DateTimeOffset フィールドは、System.DateTimeOffset、いない System.DateTime として逆シリアル化されます。</description></item></list></span><span class="sxs-lookup"><span data-stu-id="931b5-140">In particular, be aware of the following cases: <list type="bullet"><item><description> Any numeric value without a decimal point will be deserialized to System.Int64 (long in C#). </description></item><item><description> Special double-precision floating point values such as NaN and Infinity will be deserialized as type System.String rather than System.Double. </description></item><item><description> Any string field with a value formatted like a DateTimeOffset will be deserialized incorrectly. We recommend storing such values in Edm.DateTimeOffset fields rather than Edm.String fields. </description></item><item><description> Any Edm.DateTimeOffset field will be deserialized as a System.DateTimeOffset, not System.DateTime. </description></item></list></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;T&gt;&gt; GetWithHttpMessagesAsync&lt;T&gt; (string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;!!T&gt;&gt; GetWithHttpMessagesAsync&lt;class T&gt;(string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;'T&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.GetWithHttpMessagesAsync (key, selectedFields, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="931b5-141">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="931b5-141">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="931b5-142">この型のインスタンスは、インデックスからドキュメントとして取得できます。</span><span class="sxs-lookup"><span data-stu-id="931b5-142">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="key">
            <span data-ttu-id="931b5-143">取得するドキュメントのキー参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" />の有効なドキュメント キーを構築するための規則。</span><span class="sxs-lookup"><span data-stu-id="931b5-143">The key of the document to retrieve; See <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> for the rules for constructing valid document keys.</span></span>
            </param>
        <param name="selectedFields">
            <span data-ttu-id="931b5-144">ドキュメントを取得するフィールド名の一覧任意のフィールドを取得できませんでは、返されたオブジェクトの対応するプロパティ値として null または default があります。</span><span class="sxs-lookup"><span data-stu-id="931b5-144">List of field names to retrieve for the document; Any field not retrieved will have null or default as its corresponding property value in the returned object.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="931b5-145">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="931b5-145">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="931b5-146">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="931b5-146">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="931b5-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="931b5-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="931b5-148">Azure Search インデックスからドキュメントを取得します。</span><span class="sxs-lookup"><span data-stu-id="931b5-148">Retrieves a document from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            <span data-ttu-id="931b5-149">ドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="931b5-149">Response containing the document.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="931b5-150">Azure Search フィールド型を型パラメーターのコレクションを除くすべての Azure Search フィールドの種類こと、null 許容型を使用することをお勧め t です。 メモを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロード、Get、されます、および GetWithHttpMessagesAsyncT 型のプロパティの null 許容のプリミティブ型型マッピングのとおりです: <list type="table"> <listheader> <term>Azure Search フィールド型</term><description>.NET 型</description></listheader><item><term>Edm.String</term> <description>System.String (c# での文字列)</description></item><item><term>Collection(Edm.String)</term><description>IEnumerable&lt;System.String&gt; </description></item> <item> <term>Edm.Boolean</term><description>'system.nullable(of&lt;System.Boolean&gt; (bool? (C#))</description> </item> <item><term>Edm.Double</term><description>'system.nullable(of&lt;System.Double&gt; (二重? (C#))</description></item><item><term>Edm.Int32</term> <description>'System.nullable(of&lt;System.Int32&gt; (int ですか? (C#))</description></item><item><term>Edm.Int64</term><description>'system.nullable(of&lt;System.Int64&gt; (長い? (C#))</description></item><item><term>Edm.DateTimeOffset</term> <description> 'system.nullable(of&lt;System.DateTimeOffset&gt; (DateTimeOffset ですか? C# の場合) または 'system.nullable(of&lt;System.DateTime&gt; (DateTime? C# の場合)。両方の種類作業、DateTimeOffset の使用をお勧めします。ドキュメントを取得するときに、DateTime 値は常に (utc) になります。DateTime 値が次のように解釈されるドキュメントのインデックスを付ける場合: <list type="table"> <item> <term>UTC DateTime</term><description>として送信-インデックスには</description>。</item> <item><term>ローカル DateTime</term><description>インデックスに送信される前に UTC に変換します</description>。</item> <item><term>のタイム ゾーンが指定されていない DateTime</term><description>UTC と見なされ、として送信-インデックスには</description>。</item> </list> </description> </item> <item> <term>Edm.GeographyPoint</term><description><c cref="T:Microsoft.Spatial.GeographyPoint">Microsoft.Spatial.GeographyPoint</c></description></item></list></span><span class="sxs-lookup"><span data-stu-id="931b5-150">The generic overloads of the Get, GetAsync, and GetWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. Note that all Azure Search field types except collections are nullable, so we recommend using nullable primitive types for the properties of type T. The type mapping is as follows: <list type="table"><listheader><term>Azure Search field type</term><description>.NET type</description></listheader><item><term>Edm.String</term><description>System.String (string in C#)</description></item><item><term>Collection(Edm.String)</term><description>IEnumerable&lt;System.String&gt;</description></item><item><term>Edm.Boolean</term><description>System.Nullable&lt;System.Boolean&gt; (bool? in C#)</description></item><item><term>Edm.Double</term><description>System.Nullable&lt;System.Double&gt; (double? in C#)</description></item><item><term>Edm.Int32</term><description>System.Nullable&lt;System.Int32&gt; (int? in C#)</description></item><item><term>Edm.Int64</term><description>System.Nullable&lt;System.Int64&gt; (long? in C#)</description></item><item><term>Edm.DateTimeOffset</term><description> System.Nullable&lt;System.DateTimeOffset&gt; (DateTimeOffset? in C#) or System.Nullable&lt;System.DateTime&gt; (DateTime? in C#). Both types work, although we recommend using DateTimeOffset. When retrieving documents, DateTime values will always be in UTC. When indexing documents, DateTime values are interpreted as follows: <list type="table"><item><term>UTC DateTime</term><description>Sent as-is to the index.</description></item><item><term>Local DateTime</term><description>Converted to UTC before being sent to the index.</description></item><item><term>DateTime with unspecified time zone</term><description>Assumed to be UTC and sent as-is to the index.</description></item></list></description></item><item><term>Edm.GeographyPoint</term><description><c cref="T:Microsoft.Spatial.GeographyPoint">Microsoft.Spatial.GeographyPoint</c></description></item></list></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; IndexWithHttpMessagesAsync (Microsoft.Azure.Search.Models.IndexBatch batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; IndexWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.IndexBatch batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.IndexWithHttpMessagesAsync(Microsoft.Azure.Search.Models.IndexBatch,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member IndexWithHttpMessagesAsync : Microsoft.Azure.Search.Models.IndexBatch * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt;" Usage="iDocumentsOperations.IndexWithHttpMessagesAsync (batch, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="batch">
            <span data-ttu-id="931b5-151">インデックス操作のバッチです。</span><span class="sxs-lookup"><span data-stu-id="931b5-151">The batch of index actions.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="931b5-152">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="931b5-152">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="931b5-153">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="931b5-153">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="931b5-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="931b5-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="931b5-155">Azure Search インデックスには、アップロード、マージ、および削除操作のバッチを送信します。</span><span class="sxs-lookup"><span data-stu-id="931b5-155">Sends a batch of upload, merge, and/or delete actions to the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            <span data-ttu-id="931b5-156">バッチ内のすべてのアクションの操作の状態を含む応答。</span><span class="sxs-lookup"><span data-stu-id="931b5-156">Response containing the status of operations for all actions in the batch.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="931b5-157">インデックス、IndexAsync、および IndexWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。</span><span class="sxs-lookup"><span data-stu-id="931b5-157">The non-generic overloads of the Index, IndexAsync, and IndexWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="931b5-158">詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="931b5-158">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            <span data-ttu-id="931b5-159">インデックス作成操作の一部が失敗しましたが、その他のアクションが成功し、インデックスの状態が変更された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="931b5-159">Thrown when some of the indexing actions failed, but other actions succeeded and modified the state of the index.</span></span> <span data-ttu-id="931b5-160">これは、Search サービスは負荷が高いインデックス作成は場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="931b5-160">This can happen when the Search Service is under heavy indexing load.</span></span> <span data-ttu-id="931b5-161">明示的にこの例外をキャッチし、確認することが重要、 <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c>プロパティです。</span><span class="sxs-lookup"><span data-stu-id="931b5-161">It is important to explicitly catch this exception and check its <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> property.</span></span> <span data-ttu-id="931b5-162">このプロパティは、部分的な障害の後、インデックスの状態を確認します。 これにより、バッチ内の各インデックス アクションの状態を報告します。</span><span class="sxs-lookup"><span data-stu-id="931b5-162">This property reports the status of each indexing action in the batch, making it possible to determine the state of the index after a partial failure.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="IndexWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; IndexWithHttpMessagesAsync&lt;T&gt; (Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; IndexWithHttpMessagesAsync&lt;class T&gt;(class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.IndexWithHttpMessagesAsync``1(Microsoft.Azure.Search.Models.IndexBatch{``0},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member IndexWithHttpMessagesAsync : Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.IndexWithHttpMessagesAsync (batch, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="931b5-163">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="931b5-163">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="931b5-164">この型のインスタンスは、インデックス内のドキュメントとして格納できます。</span><span class="sxs-lookup"><span data-stu-id="931b5-164">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
        <param name="batch">
            <span data-ttu-id="931b5-165">インデックス操作のバッチです。</span><span class="sxs-lookup"><span data-stu-id="931b5-165">The batch of index actions.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="931b5-166">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="931b5-166">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="931b5-167">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="931b5-167">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="931b5-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="931b5-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="931b5-169">Azure Search インデックスには、アップロード、マージ、および削除操作のバッチを送信します。</span><span class="sxs-lookup"><span data-stu-id="931b5-169">Sends a batch of upload, merge, and/or delete actions to the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            <span data-ttu-id="931b5-170">バッチ内のすべてのアクションの操作の状態を含む応答。</span><span class="sxs-lookup"><span data-stu-id="931b5-170">Response containing the status of operations for all actions in the batch.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="931b5-171">Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、インデックス、IndexAsync、および IndexWithHttpMessagesAsync メソッドのジェネリック オーバー ロード参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="931b5-171">The generic overloads of the Index, IndexAsync, and IndexWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            <span data-ttu-id="931b5-172">インデックス作成操作の一部が失敗しましたが、その他のアクションが成功し、インデックスの状態が変更された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="931b5-172">Thrown when some of the indexing actions failed, but other actions succeeded and modified the state of the index.</span></span> <span data-ttu-id="931b5-173">これは、Search サービスは負荷が高いインデックス作成は場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="931b5-173">This can happen when the Search Service is under heavy indexing load.</span></span> <span data-ttu-id="931b5-174">明示的にこの例外をキャッチし、確認することが重要、 <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c>プロパティです。</span><span class="sxs-lookup"><span data-stu-id="931b5-174">It is important to explicitly catch this exception and check its <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> property.</span></span> <span data-ttu-id="931b5-175">このプロパティは、部分的な障害の後、インデックスの状態を確認します。 これにより、バッチ内の各インデックス アクションの状態を報告します。</span><span class="sxs-lookup"><span data-stu-id="931b5-175">This property reports the status of each indexing action in the batch, making it possible to determine the state of the index after a partial failure.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SearchWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt; SearchWithHttpMessagesAsync (string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt; SearchWithHttpMessagesAsync(string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SearchWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt;" Usage="iDocumentsOperations.SearchWithHttpMessagesAsync (searchText, searchParameters, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="searchText">
            <span data-ttu-id="931b5-176">フルテキスト検索クエリ式です。Null を使用して、または"\*"のすべてのドキュメントの一致するようにします。</span><span class="sxs-lookup"><span data-stu-id="931b5-176">A full-text search query expression; Use null or "\*" to match all documents.</span></span> <span data-ttu-id="931b5-177">参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" />検索クエリの構文についての詳細。</span><span class="sxs-lookup"><span data-stu-id="931b5-177">See <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> for more information about search query syntax.</span></span>
            </param>
        <param name="searchParameters">
            <span data-ttu-id="931b5-178">検索クエリを絞り込むパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="931b5-178">Parameters to further refine the search query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="931b5-179">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="931b5-179">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="931b5-180">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="931b5-180">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="931b5-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="931b5-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="931b5-182">Azure Search インデックス内のドキュメントを検索します。</span><span class="sxs-lookup"><span data-stu-id="931b5-182">Searches for documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="931b5-183">クエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="931b5-183">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="931b5-184">検索、SearchAsync、および SearchWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。</span><span class="sxs-lookup"><span data-stu-id="931b5-184">The non-generic overloads of the Search, SearchAsync, and SearchWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="931b5-185">詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="931b5-185">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="931b5-186">Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。</span><span class="sxs-lookup"><span data-stu-id="931b5-186">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="931b5-187">参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="931b5-187">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;&gt; SearchWithHttpMessagesAsync&lt;T&gt; (string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt;&gt;&gt; SearchWithHttpMessagesAsync&lt;class T&gt;(string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SearchWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T&gt;&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.SearchWithHttpMessagesAsync (searchText, searchParameters, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="931b5-188">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="931b5-188">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="931b5-189">この型のインスタンスは、インデックスからドキュメントとして取得できます。</span><span class="sxs-lookup"><span data-stu-id="931b5-189">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="searchText">
            <span data-ttu-id="931b5-190">フルテキスト検索クエリ式です。Null を使用して、または"\*"のすべてのドキュメントの一致するようにします。</span><span class="sxs-lookup"><span data-stu-id="931b5-190">A full-text search query expression; Use null or "\*" to match all documents.</span></span> <span data-ttu-id="931b5-191">参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" />検索クエリの構文についての詳細。</span><span class="sxs-lookup"><span data-stu-id="931b5-191">See <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> for more information about search query syntax.</span></span>
            </param>
        <param name="searchParameters">
            <span data-ttu-id="931b5-192">検索クエリを絞り込むパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="931b5-192">Parameters to further refine the search query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="931b5-193">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="931b5-193">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="931b5-194">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="931b5-194">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="931b5-195">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="931b5-195">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="931b5-196">Azure Search インデックス内のドキュメントを検索します。</span><span class="sxs-lookup"><span data-stu-id="931b5-196">Searches for documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="931b5-197">クエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="931b5-197">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="931b5-198">Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、検索、SearchAsync、および SearchWithHttpMessagesAsync メソッドのジェネリック オーバー ロード参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="931b5-198">The generic overloads of the Search, SearchAsync, and SearchWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </para>
          <para>
            <span data-ttu-id="931b5-199">Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。</span><span class="sxs-lookup"><span data-stu-id="931b5-199">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="931b5-200">参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="931b5-200">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuggestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;&gt; SuggestWithHttpMessagesAsync (string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;&gt; SuggestWithHttpMessagesAsync(string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.SuggestWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuggestWithHttpMessagesAsync : string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;&gt;" Usage="iDocumentsOperations.SuggestWithHttpMessagesAsync (searchText, suggesterName, suggestParameters, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="searchText">
            <span data-ttu-id="931b5-201">提案を基になる検索するテキスト。</span><span class="sxs-lookup"><span data-stu-id="931b5-201">The search text on which to base suggestions.</span></span>
            </param>
        <param name="suggesterName">
            <span data-ttu-id="931b5-202">インデックス定義の一部である suggesters コレクションで指定されている、suggester の名前。</span><span class="sxs-lookup"><span data-stu-id="931b5-202">The name of the suggester as specified in the suggesters collection that's part of the index definition.</span></span>
            </param>
        <param name="suggestParameters">
            <span data-ttu-id="931b5-203">提案クエリを絞り込むパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="931b5-203">Parameters to further refine the suggestion query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="931b5-204">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="931b5-204">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="931b5-205">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="931b5-205">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="931b5-206">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="931b5-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="931b5-207">入力テキストと Azure Search インデックスに一致するドキュメントに基づくクエリ用語をお勧めします。</span><span class="sxs-lookup"><span data-stu-id="931b5-207">Suggests query terms based on input text and matching documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            <span data-ttu-id="931b5-208">推奨されるテキストとクエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="931b5-208">Response containing the suggested text and documents matching the query.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="931b5-209">候補を表示する、SuggestAsync、および SuggestWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。</span><span class="sxs-lookup"><span data-stu-id="931b5-209">The non-generic overloads of the Suggest, SuggestAsync, and SuggestWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="931b5-210">詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="931b5-210">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuggestWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;&gt;&gt; SuggestWithHttpMessagesAsync&lt;T&gt; (string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSuggestResult`1&lt;!!T&gt;&gt;&gt; SuggestWithHttpMessagesAsync&lt;class T&gt;(string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.SuggestWithHttpMessagesAsync``1(System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuggestWithHttpMessagesAsync : string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;'T&gt;&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.SuggestWithHttpMessagesAsync (searchText, suggesterName, suggestParameters, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="931b5-211">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="931b5-211">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="931b5-212">この型のインスタンスは、インデックスからドキュメントとして取得できます。</span><span class="sxs-lookup"><span data-stu-id="931b5-212">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="searchText">
            <span data-ttu-id="931b5-213">提案を基になる検索するテキスト。</span><span class="sxs-lookup"><span data-stu-id="931b5-213">The search text on which to base suggestions.</span></span>
            </param>
        <param name="suggesterName">
            <span data-ttu-id="931b5-214">インデックス定義の一部である suggesters コレクションで指定されている、suggester の名前。</span><span class="sxs-lookup"><span data-stu-id="931b5-214">The name of the suggester as specified in the suggesters collection that's part of the index definition.</span></span>
            </param>
        <param name="suggestParameters">
            <span data-ttu-id="931b5-215">提案クエリを絞り込むパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="931b5-215">Parameters to further refine the suggestion query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="931b5-216">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="931b5-216">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="931b5-217">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="931b5-217">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="931b5-218">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="931b5-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="931b5-219">入力テキストと Azure Search インデックスに一致するドキュメントに基づくクエリ用語をお勧めします。</span><span class="sxs-lookup"><span data-stu-id="931b5-219">Suggests query terms based on input text and matching documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            <span data-ttu-id="931b5-220">推奨されるテキストとクエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="931b5-220">Response containing the suggested text and documents matching the query.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="931b5-221">Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロードの候補を表示する、SuggestAsync、および SuggestWithHttpMessagesAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="931b5-221">The generic overloads of the Suggest, SuggestAsync, and SuggestWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>