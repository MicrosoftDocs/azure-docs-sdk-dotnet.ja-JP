<Type Name="SuggestParametersPayload" FullName="Microsoft.Azure.Search.Models.SuggestParametersPayload">
  <TypeSignature Language="C#" Value="public class SuggestParametersPayload" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SuggestParametersPayload extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SuggestParametersPayload" />
  <TypeSignature Language="VB.NET" Value="Public Class SuggestParametersPayload" />
  <TypeSignature Language="F#" Value="type SuggestParametersPayload = class" />
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
            <span data-ttu-id="583d9-101">フィルターのパラメーター、並べ替え、あいまい一致の場合、およびその他の提案は、動作をクエリします。</span><span class="sxs-lookup"><span data-stu-id="583d9-101">Parameters for filtering, sorting, fuzzy matching, and other suggestions query behaviors.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SuggestParametersPayload ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SuggestParametersPayload.#ctor" />
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
            <span data-ttu-id="583d9-102">SuggestParametersPayload クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="583d9-102">Initializes a new instance of the SuggestParametersPayload class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SuggestParametersPayload (string filter = null, Nullable&lt;bool&gt; fuzzy = null, string highlightPostTag = null, string highlightPreTag = null, Nullable&lt;double&gt; minimumCoverage = null, string orderBy = null, string search = null, string searchFields = null, string select = null, string suggesterName = null, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string filter, valuetype System.Nullable`1&lt;bool&gt; fuzzy, string highlightPostTag, string highlightPreTag, valuetype System.Nullable`1&lt;float64&gt; minimumCoverage, string orderBy, string search, string searchFields, string select, string suggesterName, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SuggestParametersPayload.#ctor(System.String,System.Nullable{System.Boolean},System.String,System.String,System.Nullable{System.Double},System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional filter As String = null, Optional fuzzy As Nullable(Of Boolean) = null, Optional highlightPostTag As String = null, Optional highlightPreTag As String = null, Optional minimumCoverage As Nullable(Of Double) = null, Optional orderBy As String = null, Optional search As String = null, Optional searchFields As String = null, Optional select As String = null, Optional suggesterName As String = null, Optional top As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.SuggestParametersPayload : string * Nullable&lt;bool&gt; * string * string * Nullable&lt;double&gt; * string * string * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.SuggestParametersPayload" Usage="new Microsoft.Azure.Search.Models.SuggestParametersPayload (filter, fuzzy, highlightPostTag, highlightPreTag, minimumCoverage, orderBy, search, searchFields, select, suggesterName, top)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="fuzzy" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="highlightPostTag" Type="System.String" />
        <Parameter Name="highlightPreTag" Type="System.String" />
        <Parameter Name="minimumCoverage" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="orderBy" Type="System.String" />
        <Parameter Name="search" Type="System.String" />
        <Parameter Name="searchFields" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="filter"><span data-ttu-id="583d9-103">提案クエリに適用する OData $filter 式です。</span><span class="sxs-lookup"><span data-stu-id="583d9-103">The OData $filter expression to apply to the suggestions query.</span></span></param>
        <param name="fuzzy"><span data-ttu-id="583d9-104">提案クエリのあいまい一致を使用するかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="583d9-104">A value indicating whether to use fuzzy matching for the suggestion query.</span></span> <span data-ttu-id="583d9-105">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="583d9-105">Default is false.</span></span> <span data-ttu-id="583d9-106">設定した場合は true、クエリが検索候補を見つけます、検索テキストに置き換えられたまたは不足している文字がある場合でもです。</span><span class="sxs-lookup"><span data-stu-id="583d9-106">when set to true, the query will find suggestions even if there's a substituted or missing character in the search text.</span></span> <span data-ttu-id="583d9-107">あいまい一致で検索候補を検索すると低速で多くのリソースを消費するため、一部のシナリオではエクスペリエンスがよくなりますが、パフォーマンスは低下します。</span><span class="sxs-lookup"><span data-stu-id="583d9-107">While this provides a better experience in some scenarios it comes at a performance cost as fuzzy suggestion searches are slower and consume more resources.</span></span></param>
        <param name="highlightPostTag"><span data-ttu-id="583d9-108">ヒットに付加される文字列タグが強調表示されます。</span><span class="sxs-lookup"><span data-stu-id="583d9-108">A string tag that is appended to hit highlights.</span></span> <span data-ttu-id="583d9-109">HighlightPreTag で設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="583d9-109">Must be set with HighlightPreTag.</span></span> <span data-ttu-id="583d9-110">省略した場合、入力候補の語句の強調表示が無効です。</span><span class="sxs-lookup"><span data-stu-id="583d9-110">If omitted, hit highlighting of suggestions is disabled.</span></span></param>
        <param name="highlightPreTag"><span data-ttu-id="583d9-111">前にヒットに付加する文字列タグが強調表示されます。</span><span class="sxs-lookup"><span data-stu-id="583d9-111">A string tag that is prepended to hit highlights.</span></span> <span data-ttu-id="583d9-112">HighlightPostTag で設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="583d9-112">Must be set with HighlightPostTag.</span></span> <span data-ttu-id="583d9-113">省略した場合、入力候補の語句の強調表示が無効です。</span><span class="sxs-lookup"><span data-stu-id="583d9-113">If omitted, hit highlighting of suggestions is disabled.</span></span></param>
        <param name="minimumCoverage"><span data-ttu-id="583d9-114">成功として報告されることをクエリするために提案クエリによりカバーする必要があります、インデックスの割合を示す 0 から 100 までの数値。</span><span class="sxs-lookup"><span data-stu-id="583d9-114">A number between 0 and 100 indicating the percentage of the index that must be covered by a suggestion query in order for the query to be reported as a success.</span></span> <span data-ttu-id="583d9-115">このパラメーターは、1 つだけのレプリカとサービスに対しても検索の可用性を確保するために便利で指定できます。</span><span class="sxs-lookup"><span data-stu-id="583d9-115">This parameter can be useful for ensuring search availability even for services with only one replica.</span></span> <span data-ttu-id="583d9-116">既定値は 80 です。</span><span class="sxs-lookup"><span data-stu-id="583d9-116">The default is 80.</span></span></param>
        <param name="orderBy"><span data-ttu-id="583d9-117">結果の並べ替えに使用する OData $orderby 式のコンマ区切り一覧。</span><span class="sxs-lookup"><span data-stu-id="583d9-117">The comma-separated list of OData $orderby expressions by which to sort the results.</span></span> <span data-ttu-id="583d9-118">各式には、フィールド名または geo.distance() 関数への呼び出しのいずれかを指定できます。</span><span class="sxs-lookup"><span data-stu-id="583d9-118">Each expression can be either a field name or a call to the geo.distance() function.</span></span> <span data-ttu-id="583d9-119">各式の後に、昇順を示すために昇順と降順を示すために desc を指定できます。</span><span class="sxs-lookup"><span data-stu-id="583d9-119">Each expression can be followed by asc to indicate ascending, and desc to indicate descending.</span></span> <span data-ttu-id="583d9-120">既定値は昇順です。</span><span class="sxs-lookup"><span data-stu-id="583d9-120">The default is ascending order.</span></span> <span data-ttu-id="583d9-121">結び付きは、ドキュメントの一致スコアによって切り離されます。</span><span class="sxs-lookup"><span data-stu-id="583d9-121">Ties will be broken by the match scores of documents.</span></span> <span data-ttu-id="583d9-122">OrderBy が指定されていない場合、既定の並べ替え順序はドキュメントの一致スコアによって降順です。</span><span class="sxs-lookup"><span data-stu-id="583d9-122">If no OrderBy is specified, the default sort order is descending by document match score.</span></span> <span data-ttu-id="583d9-123">あります最大 32 の Orderby 句。</span><span class="sxs-lookup"><span data-stu-id="583d9-123">There can be at most 32 Orderby clauses.</span></span></param>
        <param name="search"><span data-ttu-id="583d9-124">提案を基になる検索するテキスト。</span><span class="sxs-lookup"><span data-stu-id="583d9-124">The search text on which to base suggestions.</span></span></param>
        <param name="searchFields"><span data-ttu-id="583d9-125">提案のクエリを実行する際に考慮するフィールド名のコンマ区切り一覧。</span><span class="sxs-lookup"><span data-stu-id="583d9-125">The comma-separated list of field names to consider when querying for suggestions.</span></span></param>
        <param name="select"><span data-ttu-id="583d9-126">コンマで区切られたフィールドの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="583d9-126">The comma-separated list of fields to retrieve.</span></span> <span data-ttu-id="583d9-127">指定しないと、スキーマで取得可能とマークされているすべてのフィールドが含まれます。</span><span class="sxs-lookup"><span data-stu-id="583d9-127">If unspecified, all fields marked as retrievable in the schema are included.</span></span></param>
        <param name="suggesterName"><span data-ttu-id="583d9-128">インデックス定義の一部である suggesters コレクションで指定されている、suggester の名前。</span><span class="sxs-lookup"><span data-stu-id="583d9-128">The name of the suggester as specified in the suggesters collection that's part of the index definition.</span></span></param>
        <param name="top"><span data-ttu-id="583d9-129">取得する検索候補の数。</span><span class="sxs-lookup"><span data-stu-id="583d9-129">The number of suggestions to retrieve.</span></span> <span data-ttu-id="583d9-130">これには、1 ~ 100 の値があります。</span><span class="sxs-lookup"><span data-stu-id="583d9-130">This must be a value between 1 and 100.</span></span> <span data-ttu-id="583d9-131">既定では 5 です。</span><span class="sxs-lookup"><span data-stu-id="583d9-131">The default is to 5.</span></span></param>
        <summary>
            <span data-ttu-id="583d9-132">SuggestParametersPayload クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="583d9-132">Initializes a new instance of the SuggestParametersPayload class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public string Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As String" />
      <MemberSignature Language="F#" Value="member this.Filter : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.Filter" />
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
            <span data-ttu-id="583d9-133">取得または提案クエリに適用する OData $filter 式を設定します。</span><span class="sxs-lookup"><span data-stu-id="583d9-133">Gets or sets the OData $filter expression to apply to the suggestions query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fuzzy">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Fuzzy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Fuzzy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.Fuzzy" />
      <MemberSignature Language="VB.NET" Value="Public Property Fuzzy As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Fuzzy : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.Fuzzy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fuzzy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="583d9-134">取得または提案クエリのあいまい一致を使用するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="583d9-134">Gets or sets a value indicating whether to use fuzzy matching for the suggestion query.</span></span> <span data-ttu-id="583d9-135">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="583d9-135">Default is false.</span></span> <span data-ttu-id="583d9-136">設定した場合は true、クエリが検索候補を見つけます、検索テキストに置き換えられたまたは不足している文字がある場合でもです。</span><span class="sxs-lookup"><span data-stu-id="583d9-136">when set to true, the query will find suggestions even if there's a substituted or missing character in the search text.</span></span> <span data-ttu-id="583d9-137">あいまい一致で検索候補を検索すると低速で多くのリソースを消費するため、一部のシナリオではエクスペリエンスがよくなりますが、パフォーマンスは低下します。</span><span class="sxs-lookup"><span data-stu-id="583d9-137">While this provides a better experience in some scenarios it comes at a performance cost as fuzzy suggestion searches are slower and consume more resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightPostTag">
      <MemberSignature Language="C#" Value="public string HighlightPostTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighlightPostTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.HighlightPostTag" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightPostTag As String" />
      <MemberSignature Language="F#" Value="member this.HighlightPostTag : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.HighlightPostTag" />
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
            <span data-ttu-id="583d9-138">取得またはヒット ハイライトに追加される文字列タグを設定します。</span><span class="sxs-lookup"><span data-stu-id="583d9-138">Gets or sets a string tag that is appended to hit highlights.</span></span> <span data-ttu-id="583d9-139">HighlightPreTag で設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="583d9-139">Must be set with HighlightPreTag.</span></span> <span data-ttu-id="583d9-140">省略した場合、入力候補の語句の強調表示が無効です。</span><span class="sxs-lookup"><span data-stu-id="583d9-140">If omitted, hit highlighting of suggestions is disabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightPreTag">
      <MemberSignature Language="C#" Value="public string HighlightPreTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighlightPreTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.HighlightPreTag" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightPreTag As String" />
      <MemberSignature Language="F#" Value="member this.HighlightPreTag : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.HighlightPreTag" />
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
            <span data-ttu-id="583d9-141">取得または先頭ヒット ハイライトに追加する文字列タグを設定します。</span><span class="sxs-lookup"><span data-stu-id="583d9-141">Gets or sets a string tag that is prepended to hit highlights.</span></span> <span data-ttu-id="583d9-142">HighlightPostTag で設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="583d9-142">Must be set with HighlightPostTag.</span></span> <span data-ttu-id="583d9-143">省略した場合、入力候補の語句の強調表示が無効です。</span><span class="sxs-lookup"><span data-stu-id="583d9-143">If omitted, hit highlighting of suggestions is disabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumCoverage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MinimumCoverage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MinimumCoverage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.MinimumCoverage" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumCoverage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MinimumCoverage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.MinimumCoverage" />
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
            <span data-ttu-id="583d9-144">取得または成功として報告されることをクエリするために提案クエリによりカバーする必要があります、インデックスの割合を示す 0 から 100 までの数値を設定します。</span><span class="sxs-lookup"><span data-stu-id="583d9-144">Gets or sets a number between 0 and 100 indicating the percentage of the index that must be covered by a suggestion query in order for the query to be reported as a success.</span></span> <span data-ttu-id="583d9-145">このパラメーターは、1 つだけのレプリカとサービスに対しても検索の可用性を確保するために便利で指定できます。</span><span class="sxs-lookup"><span data-stu-id="583d9-145">This parameter can be useful for ensuring search availability even for services with only one replica.</span></span> <span data-ttu-id="583d9-146">既定値は 80 です。</span><span class="sxs-lookup"><span data-stu-id="583d9-146">The default is 80.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderBy">
      <MemberSignature Language="C#" Value="public string OrderBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OrderBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.OrderBy" />
      <MemberSignature Language="VB.NET" Value="Public Property OrderBy As String" />
      <MemberSignature Language="F#" Value="member this.OrderBy : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.OrderBy" />
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
            <span data-ttu-id="583d9-147">取得または結果の並べ替えに使用する OData $orderby 式のコンマ区切り一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="583d9-147">Gets or sets the comma-separated list of OData $orderby expressions by which to sort the results.</span></span> <span data-ttu-id="583d9-148">各式には、フィールド名または geo.distance() 関数への呼び出しのいずれかを指定できます。</span><span class="sxs-lookup"><span data-stu-id="583d9-148">Each expression can be either a field name or a call to the geo.distance() function.</span></span> <span data-ttu-id="583d9-149">各式の後に、昇順を示すために昇順と降順を示すために desc を指定できます。</span><span class="sxs-lookup"><span data-stu-id="583d9-149">Each expression can be followed by asc to indicate ascending, and desc to indicate descending.</span></span> <span data-ttu-id="583d9-150">既定値は昇順です。</span><span class="sxs-lookup"><span data-stu-id="583d9-150">The default is ascending order.</span></span> <span data-ttu-id="583d9-151">結び付きは、ドキュメントの一致スコアによって切り離されます。</span><span class="sxs-lookup"><span data-stu-id="583d9-151">Ties will be broken by the match scores of documents.</span></span> <span data-ttu-id="583d9-152">OrderBy が指定されていない場合、既定の並べ替え順序はドキュメントの一致スコアによって降順です。</span><span class="sxs-lookup"><span data-stu-id="583d9-152">If no OrderBy is specified, the default sort order is descending by document match score.</span></span> <span data-ttu-id="583d9-153">あります最大 32 の Orderby 句。</span><span class="sxs-lookup"><span data-stu-id="583d9-153">There can be at most 32 Orderby clauses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Search">
      <MemberSignature Language="C#" Value="public string Search { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Search" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.Search" />
      <MemberSignature Language="VB.NET" Value="Public Property Search As String" />
      <MemberSignature Language="F#" Value="member this.Search : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.Search" />
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
            <span data-ttu-id="583d9-154">取得または提案を基になる検索テキストを設定します。</span><span class="sxs-lookup"><span data-stu-id="583d9-154">Gets or sets the search text on which to base suggestions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchFields">
      <MemberSignature Language="C#" Value="public string SearchFields { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SearchFields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.SearchFields" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchFields As String" />
      <MemberSignature Language="F#" Value="member this.SearchFields : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.SearchFields" />
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
            <span data-ttu-id="583d9-155">取得または設定に関する推奨事項についてクエリを実行する際に考慮するフィールド名のコンマ区切り一覧。</span><span class="sxs-lookup"><span data-stu-id="583d9-155">Gets or sets the comma-separated list of field names to consider when querying for suggestions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public string Select { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Select" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.Select" />
      <MemberSignature Language="VB.NET" Value="Public Property Select As String" />
      <MemberSignature Language="F#" Value="member this.Select : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.Select" />
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
            <span data-ttu-id="583d9-156">取得または設定、コンマで区切られたフィールドの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="583d9-156">Gets or sets the comma-separated list of fields to retrieve.</span></span> <span data-ttu-id="583d9-157">指定しないと、スキーマで取得可能とマークされているすべてのフィールドが含まれます。</span><span class="sxs-lookup"><span data-stu-id="583d9-157">If unspecified, all fields marked as retrievable in the schema are included.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuggesterName">
      <MemberSignature Language="C#" Value="public string SuggesterName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SuggesterName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.SuggesterName" />
      <MemberSignature Language="VB.NET" Value="Public Property SuggesterName As String" />
      <MemberSignature Language="F#" Value="member this.SuggesterName : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.SuggesterName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="suggesterName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="583d9-158">取得またはインデックスの定義の一部である suggesters コレクションで指定されている、suggester の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="583d9-158">Gets or sets the name of the suggester as specified in the suggesters collection that's part of the index definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Top">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Top { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Top" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParametersPayload.Top" />
      <MemberSignature Language="VB.NET" Value="Public Property Top As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Top : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParametersPayload.Top" />
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
            <span data-ttu-id="583d9-159">取得または設定を取得する候補の数。</span><span class="sxs-lookup"><span data-stu-id="583d9-159">Gets or sets the number of suggestions to retrieve.</span></span> <span data-ttu-id="583d9-160">これには、1 ~ 100 の値があります。</span><span class="sxs-lookup"><span data-stu-id="583d9-160">This must be a value between 1 and 100.</span></span> <span data-ttu-id="583d9-161">既定では 5 です。</span><span class="sxs-lookup"><span data-stu-id="583d9-161">The default is to 5.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>