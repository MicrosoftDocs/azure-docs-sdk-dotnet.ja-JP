<Type Name="DocumentsOperationsExtensions" FullName="Microsoft.Azure.Search.DocumentsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DocumentsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DocumentsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.DocumentsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DocumentsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DocumentsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3effa-101">インデックスのクエリを実行し、アップロード、マージ、およびドキュメントを削除するための操作。</span><span class="sxs-lookup"><span data-stu-id="3effa-101">Operations for querying an index and uploading, merging, and deleting documents.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Document-operations" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinueSearch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSearchResult ContinueSearch (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSearchResult ContinueSearch(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearch(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member ContinueSearch : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSearchResult" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearch (operations, continuationToken, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSearchResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3effa-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-102">The operations group for this extension method.</span></span>
            </param>
        <param name="continuationToken">
            <span data-ttu-id="3effa-103">インデックスから検索結果の次のページをフェッチするために必要な状態をカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="3effa-103">Encapsulates the state required to fetch the next page of search results from the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-104">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-104">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-105">Azure Search インデックスから検索結果の次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="3effa-105">Retrieves the next page of search results from the Azure Search index.</span></span> 
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="3effa-106">クエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="3effa-106">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="3effa-107">ContinueSearch、ContinueSearchAsync、および ContinueSearchWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。</span><span class="sxs-lookup"><span data-stu-id="3effa-107">The non-generic overloads of the ContinueSearch, ContinueSearchAsync, and ContinueSearchWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="3effa-108">詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3effa-108">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="3effa-109">Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。</span><span class="sxs-lookup"><span data-stu-id="3effa-109">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="3effa-110">参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-110">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="3effa-111">このメソッドが検索結果のページングを実装するのに役立つことはないことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="3effa-111">Note that this method is not meant to help you implement paging of search results.</span></span> <span data-ttu-id="3effa-112">ページングを使用して実装することができます、<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">上部</c>と<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c>パラメーターを<c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">検索</c>メソッドです。</span><span class="sxs-lookup"><span data-stu-id="3effa-112">You can implement paging using the <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">Top</c> and <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c> parameters to the <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Search</c> method.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueSearch&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt; ContinueSearch&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt; ContinueSearch&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearch``1(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member ContinueSearch : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearch (operations, continuationToken, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="3effa-113">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="3effa-113">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="3effa-114">この型のインスタンスは、インデックスからドキュメントとして取得できます。</span><span class="sxs-lookup"><span data-stu-id="3effa-114">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="3effa-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-115">The operations group for this extension method.</span></span>
            </param>
        <param name="continuationToken">
            <span data-ttu-id="3effa-116">インデックスから検索結果の次のページをフェッチするために必要な状態をカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="3effa-116">Encapsulates the state required to fetch the next page of search results from the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-117">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-117">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-118">Azure Search インデックスから検索結果の次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="3effa-118">Retrieves the next page of search results from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="3effa-119">クエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="3effa-119">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="3effa-120">Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロード、ContinueSearch、ContinueSearchAsync、および ContinueSearchWithHttpMessagesAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-120">The generic overloads of the ContinueSearch, ContinueSearchAsync, and ContinueSearchWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </para>
          <para>
            <span data-ttu-id="3effa-121">Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。</span><span class="sxs-lookup"><span data-stu-id="3effa-121">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="3effa-122">参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-122">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="3effa-123">このメソッドが検索結果のページングを実装するのに役立つことはないことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="3effa-123">Note that this method is not meant to help you implement paging of search results.</span></span> <span data-ttu-id="3effa-124">ページングを使用して実装することができます、<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">上部</c>と<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c>パラメーターを<c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">検索</c>メソッドです。</span><span class="sxs-lookup"><span data-stu-id="3effa-124">You can implement paging using the <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">Top</c> and <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c> parameters to the <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Search</c> method.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueSearchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt; ContinueSearchAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult&gt; ContinueSearchAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearchAsync(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ContinueSearchAsync : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearchAsync (operations, continuationToken, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;ContinueSearchAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3effa-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-125">The operations group for this extension method.</span></span>
            </param>
        <param name="continuationToken">
            <span data-ttu-id="3effa-126">インデックスから検索結果の次のページをフェッチするために必要な状態をカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="3effa-126">Encapsulates the state required to fetch the next page of search results from the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-127">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-127">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3effa-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3effa-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-129">Azure Search インデックスから検索結果の次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="3effa-129">Retrieves the next page of search results from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="3effa-130">クエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="3effa-130">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="3effa-131">ContinueSearch、ContinueSearchAsync、および ContinueSearchWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。</span><span class="sxs-lookup"><span data-stu-id="3effa-131">The non-generic overloads of the ContinueSearch, ContinueSearchAsync, and ContinueSearchWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="3effa-132">詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3effa-132">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="3effa-133">Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。</span><span class="sxs-lookup"><span data-stu-id="3effa-133">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="3effa-134">参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-134">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="3effa-135">このメソッドが検索結果のページングを実装するのに役立つことはないことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="3effa-135">Note that this method is not meant to help you implement paging of search results.</span></span> <span data-ttu-id="3effa-136">ページングを使用して実装することができます、<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">上部</c>と<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c>パラメーターを<c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">検索</c>メソッドです。</span><span class="sxs-lookup"><span data-stu-id="3effa-136">You can implement paging using the <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">Top</c> and <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c> parameters to the <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Search</c> method.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueSearchAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt; ContinueSearchAsync&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt;&gt; ContinueSearchAsync&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearchAsync``1(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ContinueSearchAsync : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T&gt;&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearchAsync (operations, continuationToken, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;ContinueSearchAsync&gt;d__5`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="3effa-137">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="3effa-137">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="3effa-138">この型のインスタンスは、インデックスからドキュメントとして取得できます。</span><span class="sxs-lookup"><span data-stu-id="3effa-138">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="3effa-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-139">The operations group for this extension method.</span></span>
            </param>
        <param name="continuationToken">
            <span data-ttu-id="3effa-140">インデックスから検索結果の次のページをフェッチするために必要な状態をカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="3effa-140">Encapsulates the state required to fetch the next page of search results from the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-141">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-141">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3effa-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3effa-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-143">Azure Search インデックスから検索結果の次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="3effa-143">Retrieves the next page of search results from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="3effa-144">クエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="3effa-144">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="3effa-145">Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロード、ContinueSearch、ContinueSearchAsync、および ContinueSearchWithHttpMessagesAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-145">The generic overloads of the ContinueSearch, ContinueSearchAsync, and ContinueSearchWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </para>
          <para>
            <span data-ttu-id="3effa-146">Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。</span><span class="sxs-lookup"><span data-stu-id="3effa-146">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="3effa-147">参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-147">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="3effa-148">このメソッドが検索結果のページングを実装するのに役立つことはないことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="3effa-148">Note that this method is not meant to help you implement paging of search results.</span></span> <span data-ttu-id="3effa-149">ページングを使用して実装することができます、<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">上部</c>と<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c>パラメーターを<c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">検索</c>メソッドです。</span><span class="sxs-lookup"><span data-stu-id="3effa-149">You can implement paging using the <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">Top</c> and <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c> parameters to the <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Search</c> method.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public static long Count (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig int64 Count(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Count(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Count : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; int64" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Count (operations, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3effa-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-150">The operations group for this extension method.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-151">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-151">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-152">Azure Search インデックスにドキュメントの数を照会します。</span><span class="sxs-lookup"><span data-stu-id="3effa-152">Queries the number of documents in the Azure Search index.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;long&gt; CountAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;int64&gt; CountAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.CountAsync(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CountAsync : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.CountAsync (operations, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;CountAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3effa-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-153">The operations group for this extension method.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-154">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-154">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3effa-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3effa-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-156">Azure Search インデックスにドキュメントの数を照会します。</span><span class="sxs-lookup"><span data-stu-id="3effa-156">Queries the number of documents in the Azure Search index.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Document Get (this Microsoft.Azure.Search.IDocumentsOperations operations, string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Document Get(class Microsoft.Azure.Search.IDocumentsOperations operations, string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Get(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Search.IDocumentsOperations * string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.Document" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Get (operations, key, selectedFields, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Document</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3effa-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-157">The operations group for this extension method.</span></span>
            </param>
        <param name="key">
            <span data-ttu-id="3effa-158">取得するドキュメントのキー参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" />の有効なドキュメント キーを構築するための規則。</span><span class="sxs-lookup"><span data-stu-id="3effa-158">The key of the document to retrieve; See <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> for the rules for constructing valid document keys.</span></span>
            </param>
        <param name="selectedFields">
            <span data-ttu-id="3effa-159">ドキュメントを取得するフィールド名の一覧任意のフィールドを取得できませんが、返されるドキュメント表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="3effa-159">List of field names to retrieve for the document; Any field not retrieved will be missing from the returned document.</span></span> <span data-ttu-id="3effa-160">既定では、取得可能なすべてのフィールドは結果に含まれます。</span><span class="sxs-lookup"><span data-stu-id="3effa-160">All retrievable fields are included in the result by default.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-161">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-161">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-162">Azure Search インデックスからドキュメントを取得します。</span><span class="sxs-lookup"><span data-stu-id="3effa-162">Retrieves a document from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            <span data-ttu-id="3effa-163">要求されたドキュメントです。</span><span class="sxs-lookup"><span data-stu-id="3effa-163">The requested document.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="3effa-164">Get、されます、および GetWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。</span><span class="sxs-lookup"><span data-stu-id="3effa-164">The non-generic overloads of the Get, GetAsync, and GetWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="3effa-165">詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3effa-165">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T Get&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T Get&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Get``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Search.IDocumentsOperations * string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; 'T (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Get (operations, key, selectedFields, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="3effa-166">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="3effa-166">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="3effa-167">この型のインスタンスは、インデックスからドキュメントとして取得できます。</span><span class="sxs-lookup"><span data-stu-id="3effa-167">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="3effa-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-168">The operations group for this extension method.</span></span>
            </param>
        <param name="key">
            <span data-ttu-id="3effa-169">取得するドキュメントのキー参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" />の有効なドキュメント キーを構築するための規則。</span><span class="sxs-lookup"><span data-stu-id="3effa-169">The key of the document to retrieve; See <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> for the rules for constructing valid document keys.</span></span>
            </param>
        <param name="selectedFields">
            <span data-ttu-id="3effa-170">ドキュメントを取得するフィールド名の一覧任意のフィールドを取得できませんでは、返されたオブジェクトの対応するプロパティ値として null または default があります。</span><span class="sxs-lookup"><span data-stu-id="3effa-170">List of field names to retrieve for the document; Any field not retrieved will have null or default as its corresponding property value in the returned object.</span></span> <span data-ttu-id="3effa-171">既定では、取得可能なすべてのフィールドは結果に含まれます。</span><span class="sxs-lookup"><span data-stu-id="3effa-171">All retrievable fields are included in the result by default.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-172">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-172">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-173">Azure Search インデックスからドキュメントを取得します。</span><span class="sxs-lookup"><span data-stu-id="3effa-173">Retrieves a document from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            <span data-ttu-id="3effa-174">要求されたドキュメントです。</span><span class="sxs-lookup"><span data-stu-id="3effa-174">The requested document.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="3effa-175">Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロード、Get、されます、および GetWithHttpMessagesAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-175">The generic overloads of the Get, GetAsync, and GetWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Document&gt; GetAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Document&gt; GetAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.GetAsync(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Search.IDocumentsOperations * string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Document&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.GetAsync (operations, key, selectedFields, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Document&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3effa-176">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-176">The operations group for this extension method.</span></span>
            </param>
        <param name="key">
            <span data-ttu-id="3effa-177">取得するドキュメントのキー参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" />の有効なドキュメント キーを構築するための規則。</span><span class="sxs-lookup"><span data-stu-id="3effa-177">The key of the document to retrieve; See <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> for the rules for constructing valid document keys.</span></span>
            </param>
        <param name="selectedFields">
            <span data-ttu-id="3effa-178">ドキュメントを取得するフィールド名の一覧任意のフィールドを取得できませんが、返されるドキュメント表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="3effa-178">List of field names to retrieve for the document; Any field not retrieved will be missing from the returned document.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-179">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-179">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3effa-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3effa-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-181">Azure Search インデックスからドキュメントを取得します。</span><span class="sxs-lookup"><span data-stu-id="3effa-181">Retrieves a document from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            <span data-ttu-id="3effa-182">要求されたドキュメントです。</span><span class="sxs-lookup"><span data-stu-id="3effa-182">The requested document.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="3effa-183">Get、されます、および GetWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。</span><span class="sxs-lookup"><span data-stu-id="3effa-183">The non-generic overloads of the Get, GetAsync, and GetWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="3effa-184">詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3effa-184">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;T&gt; GetAsync&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;!!T&gt; GetAsync&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.GetAsync``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Search.IDocumentsOperations * string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.GetAsync (operations, key, selectedFields, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;GetAsync&gt;d__9`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="3effa-185">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="3effa-185">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="3effa-186">この型のインスタンスは、インデックスからドキュメントとして取得できます。</span><span class="sxs-lookup"><span data-stu-id="3effa-186">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="3effa-187">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-187">The operations group for this extension method.</span></span>
            </param>
        <param name="key">
            <span data-ttu-id="3effa-188">取得するドキュメントのキー参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" />の有効なドキュメント キーを構築するための規則。</span><span class="sxs-lookup"><span data-stu-id="3effa-188">The key of the document to retrieve; See <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> for the rules for constructing valid document keys.</span></span>
            </param>
        <param name="selectedFields">
            <span data-ttu-id="3effa-189">ドキュメントを取得するフィールド名の一覧任意のフィールドを取得できませんでは、返されたオブジェクトの対応するプロパティ値として null または default があります。</span><span class="sxs-lookup"><span data-stu-id="3effa-189">List of field names to retrieve for the document; Any field not retrieved will have null or default as its corresponding property value in the returned object.</span></span> <span data-ttu-id="3effa-190">既定では、取得可能なすべてのフィールドは結果に含まれます。</span><span class="sxs-lookup"><span data-stu-id="3effa-190">All retrievable fields are included in the result by default.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-191">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-191">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3effa-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3effa-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-193">Azure Search インデックスからドキュメントを取得します。</span><span class="sxs-lookup"><span data-stu-id="3effa-193">Retrieves a document from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            <span data-ttu-id="3effa-194">要求されたドキュメントです。</span><span class="sxs-lookup"><span data-stu-id="3effa-194">The requested document.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="3effa-195">Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロード、Get、されます、および GetWithHttpMessagesAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-195">The generic overloads of the Get, GetAsync, and GetWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Index">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentIndexResult Index (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.IndexBatch batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentIndexResult Index(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.IndexBatch batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Index(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.IndexBatch,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Index : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.IndexBatch * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentIndexResult" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Index (operations, batch, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentIndexResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3effa-196">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-196">The operations group for this extension method.</span></span>
            </param>
        <param name="batch">
            <span data-ttu-id="3effa-197">インデックス操作のバッチです。</span><span class="sxs-lookup"><span data-stu-id="3effa-197">The batch of index actions.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-198">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-198">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-199">Azure Search インデックスには、アップロード、マージ、および削除操作のバッチを送信します。</span><span class="sxs-lookup"><span data-stu-id="3effa-199">Sends a batch of upload, merge, and/or delete actions to the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            <span data-ttu-id="3effa-200">バッチ内のすべてのアクションの操作の状態を含む応答。</span><span class="sxs-lookup"><span data-stu-id="3effa-200">Response containing the status of operations for all actions in the batch.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="3effa-201">インデックス、IndexAsync、および IndexWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。</span><span class="sxs-lookup"><span data-stu-id="3effa-201">The non-generic overloads of the Index, IndexAsync, and IndexWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="3effa-202">詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3effa-202">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            <span data-ttu-id="3effa-203">インデックス作成操作の一部が失敗しましたが、その他のアクションが成功し、インデックスの状態が変更された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="3effa-203">Thrown when some of the indexing actions failed, but other actions succeeded and modified the state of the index.</span></span> <span data-ttu-id="3effa-204">これは、Search サービスは負荷が高いインデックス作成は場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="3effa-204">This can happen when the Search Service is under heavy indexing load.</span></span> <span data-ttu-id="3effa-205">明示的にこの例外をキャッチし、確認することが重要、 <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c>プロパティです。</span><span class="sxs-lookup"><span data-stu-id="3effa-205">It is important to explicitly catch this exception and check its <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> property.</span></span> <span data-ttu-id="3effa-206">このプロパティは、部分的な障害の後、インデックスの状態を確認します。 これにより、バッチ内の各インデックス アクションの状態を報告します。</span><span class="sxs-lookup"><span data-stu-id="3effa-206">This property reports the status of each indexing action in the batch, making it possible to determine the state of the index after a partial failure.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Index&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentIndexResult Index&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentIndexResult Index&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Index``1(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.IndexBatch{``0},Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Index : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentIndexResult (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Index (operations, batch, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentIndexResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="3effa-207">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="3effa-207">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="3effa-208">この型のインスタンスは、インデックス内のドキュメントとして格納できます。</span><span class="sxs-lookup"><span data-stu-id="3effa-208">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="3effa-209">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-209">The operations group for this extension method.</span></span>
            </param>
        <param name="batch">
            <span data-ttu-id="3effa-210">インデックス操作のバッチです。</span><span class="sxs-lookup"><span data-stu-id="3effa-210">The batch of index actions.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-211">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-211">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-212">Azure Search インデックスには、アップロード、マージ、および削除操作のバッチを送信します。</span><span class="sxs-lookup"><span data-stu-id="3effa-212">Sends a batch of upload, merge, and/or delete actions to the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            <span data-ttu-id="3effa-213">バッチ内のすべてのアクションの操作の状態を含む応答。</span><span class="sxs-lookup"><span data-stu-id="3effa-213">Response containing the status of operations for all actions in the batch.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="3effa-214">Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロード、インデックスと IndexAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-214">The generic overloads of the Index and IndexAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            <span data-ttu-id="3effa-215">インデックス作成操作の一部が失敗しましたが、その他のアクションが成功し、インデックスの状態が変更された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="3effa-215">Thrown when some of the indexing actions failed, but other actions succeeded and modified the state of the index.</span></span> <span data-ttu-id="3effa-216">これは、Search サービスは負荷が高いインデックス作成は場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="3effa-216">This can happen when the Search Service is under heavy indexing load.</span></span> <span data-ttu-id="3effa-217">明示的にこの例外をキャッチし、確認することが重要、 <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c>プロパティです。</span><span class="sxs-lookup"><span data-stu-id="3effa-217">It is important to explicitly catch this exception and check its <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> property.</span></span> <span data-ttu-id="3effa-218">このプロパティは、部分的な障害の後、インデックスの状態を確認します。 これにより、バッチ内の各インデックス アクションの状態を報告します。</span><span class="sxs-lookup"><span data-stu-id="3effa-218">This property reports the status of each indexing action in the batch, making it possible to determine the state of the index after a partial failure.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="IndexAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt; IndexAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.IndexBatch batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentIndexResult&gt; IndexAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.IndexBatch batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.IndexAsync(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.IndexBatch,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member IndexAsync : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.IndexBatch * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.IndexAsync (operations, batch, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;IndexAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3effa-219">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-219">The operations group for this extension method.</span></span>
            </param>
        <param name="batch">
            <span data-ttu-id="3effa-220">インデックス操作のバッチです。</span><span class="sxs-lookup"><span data-stu-id="3effa-220">The batch of index actions.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-221">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-221">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3effa-222">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3effa-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-223">Azure Search インデックスには、アップロード、マージ、および削除操作のバッチを送信します。</span><span class="sxs-lookup"><span data-stu-id="3effa-223">Sends a batch of upload, merge, and/or delete actions to the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            <span data-ttu-id="3effa-224">バッチ内のすべてのアクションの操作の状態を含む応答。</span><span class="sxs-lookup"><span data-stu-id="3effa-224">Response containing the status of operations for all actions in the batch.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="3effa-225">インデックス、IndexAsync、および IndexWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。</span><span class="sxs-lookup"><span data-stu-id="3effa-225">The non-generic overloads of the Index, IndexAsync, and IndexWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="3effa-226">詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3effa-226">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            <span data-ttu-id="3effa-227">インデックス作成操作の一部が失敗しましたが、その他のアクションが成功し、インデックスの状態が変更された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="3effa-227">Thrown when some of the indexing actions failed, but other actions succeeded and modified the state of the index.</span></span> <span data-ttu-id="3effa-228">これは、Search サービスは負荷が高いインデックス作成は場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="3effa-228">This can happen when the Search Service is under heavy indexing load.</span></span> <span data-ttu-id="3effa-229">明示的にこの例外をキャッチし、確認することが重要、 <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c>プロパティです。</span><span class="sxs-lookup"><span data-stu-id="3effa-229">It is important to explicitly catch this exception and check its <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> property.</span></span> <span data-ttu-id="3effa-230">このプロパティは、部分的な障害の後、インデックスの状態を確認します。 これにより、バッチ内の各インデックス アクションの状態を報告します。</span><span class="sxs-lookup"><span data-stu-id="3effa-230">This property reports the status of each indexing action in the batch, making it possible to determine the state of the index after a partial failure.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="IndexAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt; IndexAsync&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentIndexResult&gt; IndexAsync&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.IndexAsync``1(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.IndexBatch{``0},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member IndexAsync : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.IndexAsync (operations, batch, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;IndexAsync&gt;d__13`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="3effa-231">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="3effa-231">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="3effa-232">この型のインスタンスは、インデックス内のドキュメントとして格納できます。</span><span class="sxs-lookup"><span data-stu-id="3effa-232">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="3effa-233">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-233">The operations group for this extension method.</span></span>
            </param>
        <param name="batch">
            <span data-ttu-id="3effa-234">インデックス操作のバッチです。</span><span class="sxs-lookup"><span data-stu-id="3effa-234">The batch of index actions.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-235">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-235">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3effa-236">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3effa-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-237">Azure Search インデックスには、アップロード、マージ、および削除操作のバッチを送信します。</span><span class="sxs-lookup"><span data-stu-id="3effa-237">Sends a batch of upload, merge, and/or delete actions to the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            <span data-ttu-id="3effa-238">バッチ内のすべてのアクションの操作の状態を含む応答。</span><span class="sxs-lookup"><span data-stu-id="3effa-238">Response containing the status of operations for all actions in the batch.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="3effa-239">Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロード、インデックスと IndexAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-239">The generic overloads of the Index and IndexAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            <span data-ttu-id="3effa-240">インデックス作成操作の一部が失敗しましたが、その他のアクションが成功し、インデックスの状態が変更された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="3effa-240">Thrown when some of the indexing actions failed, but other actions succeeded and modified the state of the index.</span></span> <span data-ttu-id="3effa-241">これは、Search サービスは負荷が高いインデックス作成は場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="3effa-241">This can happen when the Search Service is under heavy indexing load.</span></span> <span data-ttu-id="3effa-242">明示的にこの例外をキャッチし、確認することが重要、 <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c>プロパティです。</span><span class="sxs-lookup"><span data-stu-id="3effa-242">It is important to explicitly catch this exception and check its <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> property.</span></span> <span data-ttu-id="3effa-243">このプロパティは、部分的な障害の後、インデックスの状態を確認します。 これにより、バッチ内の各インデックス アクションの状態を報告します。</span><span class="sxs-lookup"><span data-stu-id="3effa-243">This property reports the status of each indexing action in the batch, making it possible to determine the state of the index after a partial failure.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Search">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSearchResult Search (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSearchResult Search(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Search(Microsoft.Azure.Search.IDocumentsOperations,System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Search : Microsoft.Azure.Search.IDocumentsOperations * string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSearchResult" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Search (operations, searchText, searchParameters, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSearchResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3effa-244">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-244">The operations group for this extension method.</span></span>
            </param>
        <param name="searchText">
            <span data-ttu-id="3effa-245">フルテキスト検索クエリ式です。Null を使用して、または"\*"のすべてのドキュメントの一致するようにします。</span><span class="sxs-lookup"><span data-stu-id="3effa-245">A full-text search query expression; Use null or "\*" to match all documents.</span></span> <span data-ttu-id="3effa-246">参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" />検索クエリの構文についての詳細。</span><span class="sxs-lookup"><span data-stu-id="3effa-246">See <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> for more information about search query syntax.</span></span>
            </param>
        <param name="searchParameters">
            <span data-ttu-id="3effa-247">検索クエリを絞り込むパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="3effa-247">Parameters to further refine the search query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-248">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-248">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-249">Azure Search インデックス内のドキュメントを検索します。</span><span class="sxs-lookup"><span data-stu-id="3effa-249">Searches for documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="3effa-250">クエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="3effa-250">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="3effa-251">検索、SearchAsync、および SearchWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。</span><span class="sxs-lookup"><span data-stu-id="3effa-251">The non-generic overloads of the Search, SearchAsync, and SearchWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="3effa-252">詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3effa-252">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="3effa-253">Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。</span><span class="sxs-lookup"><span data-stu-id="3effa-253">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="3effa-254">参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-254">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Search&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt; Search&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt; Search&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Search``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Search : Microsoft.Azure.Search.IDocumentsOperations * string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Search (operations, searchText, searchParameters, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="3effa-255">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="3effa-255">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="3effa-256">この型のインスタンスは、インデックスからドキュメントとして取得できます。</span><span class="sxs-lookup"><span data-stu-id="3effa-256">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="3effa-257">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-257">The operations group for this extension method.</span></span>
            </param>
        <param name="searchText">
            <span data-ttu-id="3effa-258">フルテキスト検索クエリ式です。Null を使用して、または"\*"のすべてのドキュメントの一致するようにします。</span><span class="sxs-lookup"><span data-stu-id="3effa-258">A full-text search query expression; Use null or "\*" to match all documents.</span></span> <span data-ttu-id="3effa-259">参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" />検索クエリの構文についての詳細。</span><span class="sxs-lookup"><span data-stu-id="3effa-259">See <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> for more information about search query syntax.</span></span>
            </param>
        <param name="searchParameters">
            <span data-ttu-id="3effa-260">検索クエリを絞り込むパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="3effa-260">Parameters to further refine the search query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-261">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-261">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-262">Azure Search インデックス内のドキュメントを検索します。</span><span class="sxs-lookup"><span data-stu-id="3effa-262">Searches for documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="3effa-263">クエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="3effa-263">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="3effa-264">Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、検索、SearchAsync、および SearchWithHttpMessagesAsync メソッドのジェネリック オーバー ロード参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-264">The generic overloads of the Search, SearchAsync, and SearchWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </para>
          <para>
            <span data-ttu-id="3effa-265">Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。</span><span class="sxs-lookup"><span data-stu-id="3effa-265">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="3effa-266">参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-266">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt; SearchAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult&gt; SearchAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.SearchAsync(Microsoft.Azure.Search.IDocumentsOperations,System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SearchAsync : Microsoft.Azure.Search.IDocumentsOperations * string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.SearchAsync (operations, searchText, searchParameters, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;SearchAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3effa-267">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-267">The operations group for this extension method.</span></span>
            </param>
        <param name="searchText">
            <span data-ttu-id="3effa-268">フルテキスト検索クエリ式です。Null を使用して、または"\*"のすべてのドキュメントの一致するようにします。</span><span class="sxs-lookup"><span data-stu-id="3effa-268">A full-text search query expression; Use null or "\*" to match all documents.</span></span> <span data-ttu-id="3effa-269">参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" />検索クエリの構文についての詳細。</span><span class="sxs-lookup"><span data-stu-id="3effa-269">See <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> for more information about search query syntax.</span></span>
            </param>
        <param name="searchParameters">
            <span data-ttu-id="3effa-270">検索クエリを絞り込むパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="3effa-270">Parameters to further refine the search query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-271">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-271">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3effa-272">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3effa-272">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-273">Azure Search インデックス内のドキュメントを検索します。</span><span class="sxs-lookup"><span data-stu-id="3effa-273">Searches for documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="3effa-274">クエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="3effa-274">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="3effa-275">検索、SearchAsync、および SearchWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。</span><span class="sxs-lookup"><span data-stu-id="3effa-275">The non-generic overloads of the Search, SearchAsync, and SearchWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="3effa-276">詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3effa-276">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="3effa-277">Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。</span><span class="sxs-lookup"><span data-stu-id="3effa-277">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="3effa-278">参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-278">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt; SearchAsync&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt;&gt; SearchAsync&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.SearchAsync``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SearchAsync : Microsoft.Azure.Search.IDocumentsOperations * string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T&gt;&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.SearchAsync (operations, searchText, searchParameters, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;SearchAsync&gt;d__17`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="3effa-279">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="3effa-279">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="3effa-280">この型のインスタンスは、インデックスからドキュメントとして取得できます。</span><span class="sxs-lookup"><span data-stu-id="3effa-280">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="3effa-281">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-281">The operations group for this extension method.</span></span>
            </param>
        <param name="searchText">
            <span data-ttu-id="3effa-282">フルテキスト検索クエリ式です。Null を使用して、または"\*"のすべてのドキュメントの一致するようにします。</span><span class="sxs-lookup"><span data-stu-id="3effa-282">A full-text search query expression; Use null or "\*" to match all documents.</span></span> <span data-ttu-id="3effa-283">参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" />検索クエリの構文についての詳細。</span><span class="sxs-lookup"><span data-stu-id="3effa-283">See <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> for more information about search query syntax.</span></span>
            </param>
        <param name="searchParameters">
            <span data-ttu-id="3effa-284">検索クエリを絞り込むパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="3effa-284">Parameters to further refine the search query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-285">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-285">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3effa-286">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3effa-286">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-287">Azure Search インデックス内のドキュメントを検索します。</span><span class="sxs-lookup"><span data-stu-id="3effa-287">Searches for documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="3effa-288">クエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="3effa-288">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="3effa-289">Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、検索、SearchAsync、および SearchWithHttpMessagesAsync メソッドのジェネリック オーバー ロード参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-289">The generic overloads of the Search, SearchAsync, and SearchWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </para>
          <para>
            <span data-ttu-id="3effa-290">Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。</span><span class="sxs-lookup"><span data-stu-id="3effa-290">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="3effa-291">参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-291">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Suggest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSuggestResult Suggest (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSuggestResult Suggest(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Suggest(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Suggest : Microsoft.Azure.Search.IDocumentsOperations * string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSuggestResult" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Suggest (operations, searchText, suggesterName, suggestParameters, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSuggestResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3effa-292">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-292">The operations group for this extension method.</span></span>
            </param>
        <param name="searchText">
            <span data-ttu-id="3effa-293">提案を基になる検索するテキスト。</span><span class="sxs-lookup"><span data-stu-id="3effa-293">The search text on which to base suggestions.</span></span>
            </param>
        <param name="suggesterName">
            <span data-ttu-id="3effa-294">インデックス定義の一部である suggesters コレクションで指定されている、suggester の名前。</span><span class="sxs-lookup"><span data-stu-id="3effa-294">The name of the suggester as specified in the suggesters collection that's part of the index definition.</span></span>
            </param>
        <param name="suggestParameters">
            <span data-ttu-id="3effa-295">提案クエリを絞り込むパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="3effa-295">Parameters to further refine the suggestion query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-296">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-296">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-297">入力テキストと Azure Search インデックスに一致するドキュメントに基づくクエリ用語をお勧めします。</span><span class="sxs-lookup"><span data-stu-id="3effa-297">Suggests query terms based on input text and matching documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            <span data-ttu-id="3effa-298">推奨されるテキストとクエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="3effa-298">Response containing the suggested text and documents matching the query.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="3effa-299">候補を表示する、SuggestAsync、および SuggestWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。</span><span class="sxs-lookup"><span data-stu-id="3effa-299">The non-generic overloads of the Suggest, SuggestAsync, and SuggestWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="3effa-300">詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3effa-300">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Suggest&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt; Suggest&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSuggestResult`1&lt;!!T&gt; Suggest&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Suggest``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Suggest : Microsoft.Azure.Search.IDocumentsOperations * string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Suggest (operations, searchText, suggesterName, suggestParameters, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="3effa-301">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="3effa-301">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="3effa-302">この型のインスタンスは、インデックスからドキュメントとして取得できます。</span><span class="sxs-lookup"><span data-stu-id="3effa-302">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="3effa-303">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-303">The operations group for this extension method.</span></span>
            </param>
        <param name="searchText">
            <span data-ttu-id="3effa-304">提案を基になる検索するテキスト。</span><span class="sxs-lookup"><span data-stu-id="3effa-304">The search text on which to base suggestions.</span></span>
            </param>
        <param name="suggesterName">
            <span data-ttu-id="3effa-305">インデックス定義の一部である suggesters コレクションで指定されている、suggester の名前。</span><span class="sxs-lookup"><span data-stu-id="3effa-305">The name of the suggester as specified in the suggesters collection that's part of the index definition.</span></span>
            </param>
        <param name="suggestParameters">
            <span data-ttu-id="3effa-306">提案クエリを絞り込むパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="3effa-306">Parameters to further refine the suggestion query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-307">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-307">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-308">入力テキストと Azure Search インデックスに一致するドキュメントに基づくクエリ用語をお勧めします。</span><span class="sxs-lookup"><span data-stu-id="3effa-308">Suggests query terms based on input text and matching documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            <span data-ttu-id="3effa-309">推奨されるテキストとクエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="3effa-309">Response containing the suggested text and documents matching the query.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="3effa-310">Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロードの候補を表示する、SuggestAsync、および SuggestWithHttpMessagesAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-310">The generic overloads of the Suggest, SuggestAsync, and SuggestWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuggestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt; SuggestAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSuggestResult&gt; SuggestAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.SuggestAsync(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SuggestAsync : Microsoft.Azure.Search.IDocumentsOperations * string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.SuggestAsync (operations, searchText, suggesterName, suggestParameters, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;SuggestAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3effa-311">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-311">The operations group for this extension method.</span></span>
            </param>
        <param name="searchText">
            <span data-ttu-id="3effa-312">提案を基になる検索するテキスト。</span><span class="sxs-lookup"><span data-stu-id="3effa-312">The search text on which to base suggestions.</span></span>
            </param>
        <param name="suggesterName">
            <span data-ttu-id="3effa-313">インデックス定義の一部である suggesters コレクションで指定されている、suggester の名前。</span><span class="sxs-lookup"><span data-stu-id="3effa-313">The name of the suggester as specified in the suggesters collection that's part of the index definition.</span></span>
            </param>
        <param name="suggestParameters">
            <span data-ttu-id="3effa-314">提案クエリを絞り込むパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="3effa-314">Parameters to further refine the suggestion query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-315">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-315">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3effa-316">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3effa-316">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-317">入力テキストと Azure Search インデックスに一致するドキュメントに基づくクエリ用語をお勧めします。</span><span class="sxs-lookup"><span data-stu-id="3effa-317">Suggests query terms based on input text and matching documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            <span data-ttu-id="3effa-318">推奨されるテキストとクエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="3effa-318">Response containing the suggested text and documents matching the query.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="3effa-319">候補を表示する、SuggestAsync、および SuggestWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。</span><span class="sxs-lookup"><span data-stu-id="3effa-319">The non-generic overloads of the Suggest, SuggestAsync, and SuggestWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="3effa-320">詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3effa-320">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuggestAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;&gt; SuggestAsync&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSuggestResult`1&lt;!!T&gt;&gt; SuggestAsync&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.SuggestAsync``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SuggestAsync : Microsoft.Azure.Search.IDocumentsOperations * string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;'T&gt;&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.SuggestAsync (operations, searchText, suggesterName, suggestParameters, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;SuggestAsync&gt;d__21`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="3effa-321">インデックス スキーマにマップされる CLR 型。</span><span class="sxs-lookup"><span data-stu-id="3effa-321">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="3effa-322">この型のインスタンスは、インデックスからドキュメントとして取得できます。</span><span class="sxs-lookup"><span data-stu-id="3effa-322">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="3effa-323">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3effa-323">The operations group for this extension method.</span></span>
            </param>
        <param name="searchText">
            <span data-ttu-id="3effa-324">提案を基になる検索するテキスト。</span><span class="sxs-lookup"><span data-stu-id="3effa-324">The search text on which to base suggestions.</span></span>
            </param>
        <param name="suggesterName">
            <span data-ttu-id="3effa-325">インデックス定義の一部である suggesters コレクションで指定されている、suggester の名前。</span><span class="sxs-lookup"><span data-stu-id="3effa-325">The name of the suggester as specified in the suggesters collection that's part of the index definition.</span></span>
            </param>
        <param name="suggestParameters">
            <span data-ttu-id="3effa-326">提案クエリを絞り込むパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="3effa-326">Parameters to further refine the suggestion query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="3effa-327">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="3effa-327">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3effa-328">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3effa-328">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3effa-329">入力テキストと Azure Search インデックスに一致するドキュメントに基づくクエリ用語をお勧めします。</span><span class="sxs-lookup"><span data-stu-id="3effa-329">Suggests query terms based on input text and matching documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            <span data-ttu-id="3effa-330">推奨されるテキストとクエリに一致するドキュメントを含む応答。</span><span class="sxs-lookup"><span data-stu-id="3effa-330">Response containing the suggested text and documents matching the query.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="3effa-331">Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロードの候補を表示する、SuggestAsync、および SuggestWithHttpMessagesAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="3effa-331">The generic overloads of the Suggest, SuggestAsync, and SuggestWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>