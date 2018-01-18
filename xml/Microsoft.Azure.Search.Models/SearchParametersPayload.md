<Type Name="SearchParametersPayload" FullName="Microsoft.Azure.Search.Models.SearchParametersPayload">
  <TypeSignature Language="C#" Value="public class SearchParametersPayload" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchParametersPayload extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SearchParametersPayload" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchParametersPayload" />
  <TypeSignature Language="F#" Value="type SearchParametersPayload = class" />
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
            <span data-ttu-id="46a25-101">フィルターのパラメーターは、並べ替え、ファセット、ページング、およびその他のクエリの動作を検索します。</span><span class="sxs-lookup"><span data-stu-id="46a25-101">Parameters for filtering, sorting, faceting, paging, and other search query behaviors.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchParametersPayload ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SearchParametersPayload.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="46a25-102">SearchParametersPayload クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="46a25-102">Initializes a new instance of the SearchParametersPayload class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchParametersPayload (Nullable&lt;bool&gt; count = null, System.Collections.Generic.IList&lt;string&gt; facets = null, string filter = null, string highlight = null, string highlightPostTag = null, string highlightPreTag = null, Nullable&lt;double&gt; minimumCoverage = null, string orderBy = null, Nullable&lt;Microsoft.Azure.Search.Models.QueryType&gt; queryType = null, System.Collections.Generic.IList&lt;string&gt; scoringParameters = null, string scoringProfile = null, string search = null, string searchFields = null, Nullable&lt;Microsoft.Azure.Search.Models.SearchMode&gt; searchMode = null, string select = null, Nullable&lt;int&gt; skip = null, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.IList`1&lt;string&gt; facets, string filter, string highlight, string highlightPostTag, string highlightPreTag, valuetype System.Nullable`1&lt;float64&gt; minimumCoverage, string orderBy, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.QueryType&gt; queryType, class System.Collections.Generic.IList`1&lt;string&gt; scoringParameters, string scoringProfile, string search, string searchFields, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.SearchMode&gt; searchMode, string select, valuetype System.Nullable`1&lt;int32&gt; skip, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SearchParametersPayload.#ctor(System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String},System.String,System.String,System.String,System.String,System.Nullable{System.Double},System.String,System.Nullable{Microsoft.Azure.Search.Models.QueryType},System.Collections.Generic.IList{System.String},System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Search.Models.SearchMode},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional count As Nullable(Of Boolean) = null, Optional facets As IList(Of String) = null, Optional filter As String = null, Optional highlight As String = null, Optional highlightPostTag As String = null, Optional highlightPreTag As String = null, Optional minimumCoverage As Nullable(Of Double) = null, Optional orderBy As String = null, Optional queryType As Nullable(Of QueryType) = null, Optional scoringParameters As IList(Of String) = null, Optional scoringProfile As String = null, Optional search As String = null, Optional searchFields As String = null, Optional searchMode As Nullable(Of SearchMode) = null, Optional select As String = null, Optional skip As Nullable(Of Integer) = null, Optional top As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.SearchParametersPayload : Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string * string * string * Nullable&lt;double&gt; * string * Nullable&lt;Microsoft.Azure.Search.Models.QueryType&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string * string * Nullable&lt;Microsoft.Azure.Search.Models.SearchMode&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.SearchParametersPayload" Usage="new Microsoft.Azure.Search.Models.SearchParametersPayload (count, facets, filter, highlight, highlightPostTag, highlightPreTag, minimumCoverage, orderBy, queryType, scoringParameters, scoringProfile, search, searchFields, searchMode, select, skip, top)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="facets" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="highlight" Type="System.String" />
        <Parameter Name="highlightPostTag" Type="System.String" />
        <Parameter Name="highlightPreTag" Type="System.String" />
        <Parameter Name="minimumCoverage" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="orderBy" Type="System.String" />
        <Parameter Name="queryType" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.QueryType&gt;" />
        <Parameter Name="scoringParameters" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="scoringProfile" Type="System.String" />
        <Parameter Name="search" Type="System.String" />
        <Parameter Name="searchFields" Type="System.String" />
        <Parameter Name="searchMode" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.SearchMode&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="skip" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="count"><span data-ttu-id="46a25-103">結果の合計数を取得するかどうかを指定する値。</span><span class="sxs-lookup"><span data-stu-id="46a25-103">A value that specifies whether to fetch the total count of results.</span></span> <span data-ttu-id="46a25-104">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="46a25-104">Default is false.</span></span> <span data-ttu-id="46a25-105">この値を true に設定すると、パフォーマンスに影響する場合があります。</span><span class="sxs-lookup"><span data-stu-id="46a25-105">Setting this value to true may have a performance impact.</span></span> <span data-ttu-id="46a25-106">返されるカウントは概数であることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46a25-106">Note that the count returned is an approximation.</span></span></param>
        <param name="facets"><span data-ttu-id="46a25-107">検索クエリに適用するファセットの式のリスト。</span><span class="sxs-lookup"><span data-stu-id="46a25-107">The list of facet expressions to apply to the search query.</span></span> <span data-ttu-id="46a25-108">各ファセット式には、必要に応じて名前と値のペアのコンマ区切りのリストを続けて、フィールド名が含まれています。</span><span class="sxs-lookup"><span data-stu-id="46a25-108">Each facet expression contains a field name, optionally followed by a comma-separated list of name:value pairs.</span></span></param>
        <param name="filter"><span data-ttu-id="46a25-109">検索クエリに適用する OData $filter 式です。</span><span class="sxs-lookup"><span data-stu-id="46a25-109">The OData $filter expression to apply to the search query.</span></span></param>
        <param name="highlight"><span data-ttu-id="46a25-110">使用するフィールド名のコンマ区切りリストには、重要なポイントがヒットします。</span><span class="sxs-lookup"><span data-stu-id="46a25-110">The comma-separated list of field names to use for hit highlights.</span></span> <span data-ttu-id="46a25-111">ヒット ハイライト機能は、検索可能フィールドのみを使用できます。</span><span class="sxs-lookup"><span data-stu-id="46a25-111">Only searchable fields can be used for hit highlighting.</span></span></param>
        <param name="highlightPostTag"><span data-ttu-id="46a25-112">ヒットに付加される文字列タグが強調表示されます。</span><span class="sxs-lookup"><span data-stu-id="46a25-112">A string tag that is appended to hit highlights.</span></span> <span data-ttu-id="46a25-113">HighlightPreTag で設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="46a25-113">Must be set with HighlightPreTag.</span></span> <span data-ttu-id="46a25-114">既定値は&amp;lt;/em&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="46a25-114">Default is &amp;lt;/em&amp;gt;.</span></span></param>
        <param name="highlightPreTag"><span data-ttu-id="46a25-115">前にヒットに付加する文字列タグが強調表示されます。</span><span class="sxs-lookup"><span data-stu-id="46a25-115">A string tag that is prepended to hit highlights.</span></span> <span data-ttu-id="46a25-116">HighlightPostTag で設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="46a25-116">Must be set with HighlightPostTag.</span></span> <span data-ttu-id="46a25-117">既定値は&amp;lt; em&amp;gt;。</span><span class="sxs-lookup"><span data-stu-id="46a25-117">Default is &amp;lt;em&amp;gt;.</span></span></param>
        <param name="minimumCoverage"><span data-ttu-id="46a25-118">成功として報告されることをクエリするために検索クエリで対応する必要があります、インデックスの割合を示す 0 から 100 までの数値。</span><span class="sxs-lookup"><span data-stu-id="46a25-118">A number between 0 and 100 indicating the percentage of the index that must be covered by a search query in order for the query to be reported as a success.</span></span> <span data-ttu-id="46a25-119">このパラメーターは、1 つだけのレプリカとサービスに対しても検索の可用性を確保するために便利で指定できます。</span><span class="sxs-lookup"><span data-stu-id="46a25-119">This parameter can be useful for ensuring search availability even for services with only one replica.</span></span> <span data-ttu-id="46a25-120">既定値は 100 です。</span><span class="sxs-lookup"><span data-stu-id="46a25-120">The default is 100.</span></span></param>
        <param name="orderBy"><span data-ttu-id="46a25-121">結果の並べ替えに使用する OData $orderby 式のコンマ区切り一覧。</span><span class="sxs-lookup"><span data-stu-id="46a25-121">The comma-separated list of OData $orderby expressions by which to sort the results.</span></span> <span data-ttu-id="46a25-122">各式には、フィールド名または geo.distance() 関数への呼び出しのいずれかを指定できます。</span><span class="sxs-lookup"><span data-stu-id="46a25-122">Each expression can be either a field name or a call to the geo.distance() function.</span></span> <span data-ttu-id="46a25-123">各式の後に、昇順を示すために昇順と降順を示すために desc を指定できます。</span><span class="sxs-lookup"><span data-stu-id="46a25-123">Each expression can be followed by asc to indicate ascending, and desc to indicate descending.</span></span> <span data-ttu-id="46a25-124">既定値は昇順です。</span><span class="sxs-lookup"><span data-stu-id="46a25-124">The default is ascending order.</span></span> <span data-ttu-id="46a25-125">結び付きは、ドキュメントの一致スコアによって切り離されます。</span><span class="sxs-lookup"><span data-stu-id="46a25-125">Ties will be broken by the match scores of documents.</span></span> <span data-ttu-id="46a25-126">OrderBy が指定されていない場合、既定の並べ替え順序はドキュメントの一致スコアによって降順です。</span><span class="sxs-lookup"><span data-stu-id="46a25-126">If no OrderBy is specified, the default sort order is descending by document match score.</span></span> <span data-ttu-id="46a25-127">あります最大 32 の Orderby 句。</span><span class="sxs-lookup"><span data-stu-id="46a25-127">There can be at most 32 Orderby clauses.</span></span></param>
        <param name="queryType"><span data-ttu-id="46a25-128">取得または検索クエリの構文を指定する値を設定します。</span><span class="sxs-lookup"><span data-stu-id="46a25-128">Gets or sets a value that specifies the syntax of the search query.</span></span> <span data-ttu-id="46a25-129">既定値は 'simple' です。</span><span class="sxs-lookup"><span data-stu-id="46a25-129">The default is 'simple'.</span></span> <span data-ttu-id="46a25-130">クエリは Lucene のクエリ構文を使用する場合は、'full' を使用します。</span><span class="sxs-lookup"><span data-stu-id="46a25-130">Use 'full' if your query uses the Lucene query syntax.</span></span> <span data-ttu-id="46a25-131">使用可能な値が含まれます: 'simple'、'full'</span><span class="sxs-lookup"><span data-stu-id="46a25-131">Possible values include: 'simple', 'full'</span></span></param>
        <param name="scoringParameters"><span data-ttu-id="46a25-132">関数 (たとえば、referencePointParameter) 形式の名前: 値を使用してスコア付けに使用されるパラメーター値の一覧です。</span><span class="sxs-lookup"><span data-stu-id="46a25-132">The list of parameter values to be used in scoring functions (for example, referencePointParameter) using the format name:value.</span></span> <span data-ttu-id="46a25-133">たとえば、スコア付けプロファイル定義されている場合、関数 'mylocation' という名前のパラメーターとパラメーター文字列になります"mylocation:-122.2,44.8"(without the quotes) です。</span><span class="sxs-lookup"><span data-stu-id="46a25-133">For example, if the scoring profile defines a function with a parameter called 'mylocation' the parameter string would be "mylocation:-122.2,44.8"(without the quotes).</span></span></param>
        <param name="scoringProfile"><span data-ttu-id="46a25-134">評価するスコア付けプロファイルの名前では、結果を並べ替えるために一致するドキュメントのスコアと一致します。</span><span class="sxs-lookup"><span data-stu-id="46a25-134">The name of a scoring profile to evaluate match scores for matching documents in order to sort the results.</span></span></param>
        <param name="search"><span data-ttu-id="46a25-135">フルテキスト検索クエリ式です。Null を使用して、または"\*"のすべてのドキュメントの一致するようにします。</span><span class="sxs-lookup"><span data-stu-id="46a25-135">A full-text search query expression; Use null or "\*" to match all documents.</span></span></param>
        <param name="searchFields"><span data-ttu-id="46a25-136">フルテキスト検索に含めるフィールド名のコンマ区切り一覧。</span><span class="sxs-lookup"><span data-stu-id="46a25-136">The comma-separated list of field names to include in the full-text search.</span></span></param>
        <param name="searchMode"><span data-ttu-id="46a25-137">一致すると、ドキュメントをカウントするために、検索語句の一部またはすべてを照合する必要があるかどうかを指定する値。</span><span class="sxs-lookup"><span data-stu-id="46a25-137">A value that specifies whether any or all of the search terms must be matched in order to count the document as a match.</span></span> <span data-ttu-id="46a25-138">使用可能な値が含まれます 'any'、'all'。</span><span class="sxs-lookup"><span data-stu-id="46a25-138">Possible values include: 'any', 'all'</span></span></param>
        <param name="select"><span data-ttu-id="46a25-139">コンマで区切られたフィールドの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="46a25-139">The comma-separated list of fields to retrieve.</span></span> <span data-ttu-id="46a25-140">指定しないと、スキーマで取得可能とマークされているすべてのフィールドが含まれます。</span><span class="sxs-lookup"><span data-stu-id="46a25-140">If unspecified, all fields marked as retrievable in the schema are included.</span></span></param>
        <param name="skip"><span data-ttu-id="46a25-141">スキップする検索結果の数。</span><span class="sxs-lookup"><span data-stu-id="46a25-141">The number of search results to skip.</span></span> <span data-ttu-id="46a25-142">この値は 100,000 より大きくすることはできません。</span><span class="sxs-lookup"><span data-stu-id="46a25-142">This value cannot be greater than 100,000.</span></span> <span data-ttu-id="46a25-143">順番に、ドキュメントをスキャンする必要がありますが、この制限によりスキップを使用することはできない場合、は、範囲クエリを使用して、全順序キーとフィルターに OrderBy を代わりに使用を検討します。</span><span class="sxs-lookup"><span data-stu-id="46a25-143">If you need to scan documents in sequence, but cannot use Skip due to this limitation, consider using OrderBy on a totally-ordered key and Filter with a range query instead.</span></span></param>
        <param name="top"><span data-ttu-id="46a25-144">取得する検索結果の数。</span><span class="sxs-lookup"><span data-stu-id="46a25-144">The number of search results to retrieve.</span></span> <span data-ttu-id="46a25-145">これは、検索結果のクライアント側のページングを実装する Skip と組み合わせて使用できます。</span><span class="sxs-lookup"><span data-stu-id="46a25-145">This can be used in conjunction with Skip to implement client-side paging of search results.</span></span> <span data-ttu-id="46a25-146">サーバー側のページングが原因には、結果が切り捨て、応答で結果の次のページを取得する ContinueSearch に渡すことが継続トークンが含まれます。</span><span class="sxs-lookup"><span data-stu-id="46a25-146">If results are truncated due to server-side paging, the response will include a continuation token that can be passed to ContinueSearch to retrieve the next page of results.</span></span> <span data-ttu-id="46a25-147">詳細については、DocumentSearchResponse.ContinuationToken を参照してください。</span><span class="sxs-lookup"><span data-stu-id="46a25-147">See DocumentSearchResponse.ContinuationToken for more information.</span></span></param>
        <summary>
            <span data-ttu-id="46a25-148">SearchParametersPayload クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="46a25-148">Initializes a new instance of the SearchParametersPayload class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-149">取得または結果の合計数を取得するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="46a25-149">Gets or sets a value that specifies whether to fetch the total count of results.</span></span> <span data-ttu-id="46a25-150">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="46a25-150">Default is false.</span></span> <span data-ttu-id="46a25-151">この値を true に設定すると、パフォーマンスに影響する場合があります。</span><span class="sxs-lookup"><span data-stu-id="46a25-151">Setting this value to true may have a performance impact.</span></span> <span data-ttu-id="46a25-152">返されるカウントは概数であることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="46a25-152">Note that the count returned is an approximation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Facets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Facets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Facets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.Facets" />
      <MemberSignature Language="VB.NET" Value="Public Property Facets As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Facets : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.Facets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="facets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-153">取得または検索クエリに適用するファセットの式の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="46a25-153">Gets or sets the list of facet expressions to apply to the search query.</span></span> <span data-ttu-id="46a25-154">各ファセット式には、必要に応じて名前と値のペアのコンマ区切りのリストを続けて、フィールド名が含まれています。</span><span class="sxs-lookup"><span data-stu-id="46a25-154">Each facet expression contains a field name, optionally followed by a comma-separated list of name:value pairs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public string Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As String" />
      <MemberSignature Language="F#" Value="member this.Filter : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.Filter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-155">取得または検索クエリに適用する OData $filter 式を設定します。</span><span class="sxs-lookup"><span data-stu-id="46a25-155">Gets or sets the OData $filter expression to apply to the search query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Highlight">
      <MemberSignature Language="C#" Value="public string Highlight { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Highlight" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.Highlight" />
      <MemberSignature Language="VB.NET" Value="Public Property Highlight As String" />
      <MemberSignature Language="F#" Value="member this.Highlight : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.Highlight" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="highlight")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-156">取得またはヒット ハイライトに使用するフィールド名のコンマ区切り一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="46a25-156">Gets or sets the comma-separated list of field names to use for hit highlights.</span></span> <span data-ttu-id="46a25-157">ヒット ハイライト機能は、検索可能フィールドのみを使用できます。</span><span class="sxs-lookup"><span data-stu-id="46a25-157">Only searchable fields can be used for hit highlighting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightPostTag">
      <MemberSignature Language="C#" Value="public string HighlightPostTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighlightPostTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.HighlightPostTag" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightPostTag As String" />
      <MemberSignature Language="F#" Value="member this.HighlightPostTag : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.HighlightPostTag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="highlightPostTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-158">取得またはヒット ハイライトに追加される文字列タグを設定します。</span><span class="sxs-lookup"><span data-stu-id="46a25-158">Gets or sets a string tag that is appended to hit highlights.</span></span> <span data-ttu-id="46a25-159">HighlightPreTag で設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="46a25-159">Must be set with HighlightPreTag.</span></span> <span data-ttu-id="46a25-160">既定値は&amp;amp; lt;/em&amp;amp; gt;。</span><span class="sxs-lookup"><span data-stu-id="46a25-160">Default is &amp;amp;lt;/em&amp;amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightPreTag">
      <MemberSignature Language="C#" Value="public string HighlightPreTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighlightPreTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.HighlightPreTag" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightPreTag As String" />
      <MemberSignature Language="F#" Value="member this.HighlightPreTag : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.HighlightPreTag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="highlightPreTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-161">取得または先頭ヒット ハイライトに追加する文字列タグを設定します。</span><span class="sxs-lookup"><span data-stu-id="46a25-161">Gets or sets a string tag that is prepended to hit highlights.</span></span> <span data-ttu-id="46a25-162">HighlightPostTag で設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="46a25-162">Must be set with HighlightPostTag.</span></span> <span data-ttu-id="46a25-163">既定値は&amp;amp; lt; em&amp;amp; gt;。</span><span class="sxs-lookup"><span data-stu-id="46a25-163">Default is &amp;amp;lt;em&amp;amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumCoverage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MinimumCoverage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MinimumCoverage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.MinimumCoverage" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumCoverage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MinimumCoverage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.MinimumCoverage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minimumCoverage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-164">取得または成功として報告されることをクエリするために検索クエリで対応する必要があります、インデックスの割合を示す 0 から 100 までの数値を設定します。</span><span class="sxs-lookup"><span data-stu-id="46a25-164">Gets or sets a number between 0 and 100 indicating the percentage of the index that must be covered by a search query in order for the query to be reported as a success.</span></span> <span data-ttu-id="46a25-165">このパラメーターは、1 つだけのレプリカとサービスに対しても検索の可用性を確保するために便利で指定できます。</span><span class="sxs-lookup"><span data-stu-id="46a25-165">This parameter can be useful for ensuring search availability even for services with only one replica.</span></span> <span data-ttu-id="46a25-166">既定値は 100 です。</span><span class="sxs-lookup"><span data-stu-id="46a25-166">The default is 100.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderBy">
      <MemberSignature Language="C#" Value="public string OrderBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OrderBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.OrderBy" />
      <MemberSignature Language="VB.NET" Value="Public Property OrderBy As String" />
      <MemberSignature Language="F#" Value="member this.OrderBy : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.OrderBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="orderby")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-167">取得または結果の並べ替えに使用する OData $orderby 式のコンマ区切り一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="46a25-167">Gets or sets the comma-separated list of OData $orderby expressions by which to sort the results.</span></span> <span data-ttu-id="46a25-168">各式には、フィールド名または geo.distance() 関数への呼び出しのいずれかを指定できます。</span><span class="sxs-lookup"><span data-stu-id="46a25-168">Each expression can be either a field name or a call to the geo.distance() function.</span></span> <span data-ttu-id="46a25-169">各式の後に、昇順を示すために昇順と降順を示すために desc を指定できます。</span><span class="sxs-lookup"><span data-stu-id="46a25-169">Each expression can be followed by asc to indicate ascending, and desc to indicate descending.</span></span> <span data-ttu-id="46a25-170">既定値は昇順です。</span><span class="sxs-lookup"><span data-stu-id="46a25-170">The default is ascending order.</span></span> <span data-ttu-id="46a25-171">結び付きは、ドキュメントの一致スコアによって切り離されます。</span><span class="sxs-lookup"><span data-stu-id="46a25-171">Ties will be broken by the match scores of documents.</span></span> <span data-ttu-id="46a25-172">OrderBy が指定されていない場合、既定の並べ替え順序はドキュメントの一致スコアによって降順です。</span><span class="sxs-lookup"><span data-stu-id="46a25-172">If no OrderBy is specified, the default sort order is descending by document match score.</span></span> <span data-ttu-id="46a25-173">あります最大 32 の Orderby 句。</span><span class="sxs-lookup"><span data-stu-id="46a25-173">There can be at most 32 Orderby clauses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.QueryType&gt; QueryType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.QueryType&gt; QueryType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.QueryType" />
      <MemberSignature Language="VB.NET" Value="Public Property QueryType As Nullable(Of QueryType)" />
      <MemberSignature Language="F#" Value="member this.QueryType : Nullable&lt;Microsoft.Azure.Search.Models.QueryType&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.QueryType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="queryType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.QueryType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-174">取得または検索クエリの構文を指定する値を設定します。</span><span class="sxs-lookup"><span data-stu-id="46a25-174">Gets or sets a value that specifies the syntax of the search query.</span></span>
            <span data-ttu-id="46a25-175">既定値は 'simple' です。</span><span class="sxs-lookup"><span data-stu-id="46a25-175">The default is 'simple'.</span></span> <span data-ttu-id="46a25-176">クエリは Lucene のクエリ構文を使用する場合は、'full' を使用します。</span><span class="sxs-lookup"><span data-stu-id="46a25-176">Use 'full' if your query uses the Lucene query syntax.</span></span> <span data-ttu-id="46a25-177">使用可能な値が含まれます: 'simple'、'full'</span><span class="sxs-lookup"><span data-stu-id="46a25-177">Possible values include: 'simple', 'full'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScoringParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ScoringParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ScoringParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.ScoringParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property ScoringParameters As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ScoringParameters : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.ScoringParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scoringParameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-178">取得または関数 (たとえば、referencePointParameter) 形式の名前: 値を使用してスコア付けに使用されるパラメーター値の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="46a25-178">Gets or sets the list of parameter values to be used in scoring functions (for example, referencePointParameter) using the format name:value.</span></span> <span data-ttu-id="46a25-179">たとえば、スコア付けプロファイル定義されている場合、関数 'mylocation' という名前のパラメーターとパラメーター文字列になります"mylocation:-122.2,44.8"(without the quotes) です。</span><span class="sxs-lookup"><span data-stu-id="46a25-179">For example, if the scoring profile defines a function with a parameter called 'mylocation' the parameter string would be "mylocation:-122.2,44.8"(without the quotes).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScoringProfile">
      <MemberSignature Language="C#" Value="public string ScoringProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScoringProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.ScoringProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property ScoringProfile As String" />
      <MemberSignature Language="F#" Value="member this.ScoringProfile : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.ScoringProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scoringProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-180">取得または結果を並べ替えるために一致するドキュメントの一致スコアを評価するスコア付けプロファイルの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="46a25-180">Gets or sets the name of a scoring profile to evaluate match scores for matching documents in order to sort the results.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Search">
      <MemberSignature Language="C#" Value="public string Search { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Search" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.Search" />
      <MemberSignature Language="VB.NET" Value="Public Property Search As String" />
      <MemberSignature Language="F#" Value="member this.Search : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.Search" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="search")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-181">フルテキスト検索クエリ式。 取得または設定Null を使用して、または"\*"のすべてのドキュメントの一致するようにします。</span><span class="sxs-lookup"><span data-stu-id="46a25-181">Gets or sets a full-text search query expression; Use null or "\*" to match all documents.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchFields">
      <MemberSignature Language="C#" Value="public string SearchFields { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SearchFields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.SearchFields" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchFields As String" />
      <MemberSignature Language="F#" Value="member this.SearchFields : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.SearchFields" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="searchFields")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-182">取得またはフルテキスト検索に含めるフィールド名のコンマ区切り一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="46a25-182">Gets or sets the comma-separated list of field names to include in the full-text search.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.SearchMode&gt; SearchMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.SearchMode&gt; SearchMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.SearchMode" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchMode As Nullable(Of SearchMode)" />
      <MemberSignature Language="F#" Value="member this.SearchMode : Nullable&lt;Microsoft.Azure.Search.Models.SearchMode&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.SearchMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="searchMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.SearchMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-183">取得または設定と一致すると、ドキュメントをカウントするために、検索語句の一部またはすべてを照合する必要があるかどうかを指定する値。</span><span class="sxs-lookup"><span data-stu-id="46a25-183">Gets or sets a value that specifies whether any or all of the search terms must be matched in order to count the document as a match.</span></span> <span data-ttu-id="46a25-184">使用可能な値が含まれます 'any'、'all'。</span><span class="sxs-lookup"><span data-stu-id="46a25-184">Possible values include: 'any', 'all'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public string Select { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Select" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.Select" />
      <MemberSignature Language="VB.NET" Value="Public Property Select As String" />
      <MemberSignature Language="F#" Value="member this.Select : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.Select" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="select")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-185">取得または設定、コンマで区切られたフィールドの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="46a25-185">Gets or sets the comma-separated list of fields to retrieve.</span></span> <span data-ttu-id="46a25-186">指定しないと、スキーマで取得可能とマークされているすべてのフィールドが含まれます。</span><span class="sxs-lookup"><span data-stu-id="46a25-186">If unspecified, all fields marked as retrievable in the schema are included.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Skip">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Skip { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Skip" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.Skip" />
      <MemberSignature Language="VB.NET" Value="Public Property Skip As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Skip : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.Skip" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="skip")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-187">取得またはスキップに検索結果の数を設定します。</span><span class="sxs-lookup"><span data-stu-id="46a25-187">Gets or sets the number of search results to skip.</span></span> <span data-ttu-id="46a25-188">この値は 100,000 より大きくすることはできません。</span><span class="sxs-lookup"><span data-stu-id="46a25-188">This value cannot be greater than 100,000.</span></span> <span data-ttu-id="46a25-189">順番に、ドキュメントをスキャンする必要がありますが、この制限によりスキップを使用することはできない場合、は、範囲クエリを使用して、全順序キーとフィルターに OrderBy を代わりに使用を検討します。</span><span class="sxs-lookup"><span data-stu-id="46a25-189">If you need to scan documents in sequence, but cannot use Skip due to this limitation, consider using OrderBy on a totally-ordered key and Filter with a range query instead.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Top">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Top { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Top" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParametersPayload.Top" />
      <MemberSignature Language="VB.NET" Value="Public Property Top As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Top : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParametersPayload.Top" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="top")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="46a25-190">取得または取得する検索結果の数を設定します。</span><span class="sxs-lookup"><span data-stu-id="46a25-190">Gets or sets the number of search results to retrieve.</span></span> <span data-ttu-id="46a25-191">これは、検索結果のクライアント側のページングを実装する Skip と組み合わせて使用できます。</span><span class="sxs-lookup"><span data-stu-id="46a25-191">This can be used in conjunction with Skip to implement client-side paging of search results.</span></span> <span data-ttu-id="46a25-192">サーバー側のページングが原因には、結果が切り捨て、応答で結果の次のページを取得する ContinueSearch に渡すことが継続トークンが含まれます。</span><span class="sxs-lookup"><span data-stu-id="46a25-192">If results are truncated due to server-side paging, the response will include a continuation token that can be passed to ContinueSearch to retrieve the next page of results.</span></span> <span data-ttu-id="46a25-193">詳細については、DocumentSearchResponse.ContinuationToken を参照してください。</span><span class="sxs-lookup"><span data-stu-id="46a25-193">See DocumentSearchResponse.ContinuationToken for more information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>