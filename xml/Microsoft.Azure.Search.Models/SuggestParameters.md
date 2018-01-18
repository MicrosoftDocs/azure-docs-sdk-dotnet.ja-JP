<Type Name="SuggestParameters" FullName="Microsoft.Azure.Search.Models.SuggestParameters">
  <TypeSignature Language="C#" Value="public class SuggestParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SuggestParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SuggestParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class SuggestParameters" />
  <TypeSignature Language="F#" Value="type SuggestParameters = class" />
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
            <span data-ttu-id="a8595-101">フィルターのパラメーター、並べ替え、あいまい一致の場合、およびその他の提案は、動作をクエリします。</span><span class="sxs-lookup"><span data-stu-id="a8595-101">Parameters for filtering, sorting, fuzzy matching, and other suggestions query behaviors.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SuggestParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SuggestParameters.#ctor" />
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
            <span data-ttu-id="a8595-102">SuggestParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a8595-102">Initializes a new instance of the SuggestParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public string Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As String" />
      <MemberSignature Language="F#" Value="member this.Filter : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.Filter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8595-103">取得または提案クエリに適用する OData $filter 式を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8595-103">Gets or sets the OData $filter expression to apply to the suggestions query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightPostTag">
      <MemberSignature Language="C#" Value="public string HighlightPostTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighlightPostTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.HighlightPostTag" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightPostTag As String" />
      <MemberSignature Language="F#" Value="member this.HighlightPostTag : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.HighlightPostTag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8595-104">取得またはヒット ハイライトに追加される文字列タグを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8595-104">Gets or sets a string tag that is appended to hit highlights.</span></span> <span data-ttu-id="a8595-105">HighlightPreTag で設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8595-105">Must be set with HighlightPreTag.</span></span> <span data-ttu-id="a8595-106">省略した場合、入力候補の語句の強調表示が無効です。</span><span class="sxs-lookup"><span data-stu-id="a8595-106">If omitted, hit highlighting of suggestions is disabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightPreTag">
      <MemberSignature Language="C#" Value="public string HighlightPreTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighlightPreTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.HighlightPreTag" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightPreTag As String" />
      <MemberSignature Language="F#" Value="member this.HighlightPreTag : string with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.HighlightPreTag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8595-107">取得または先頭ヒット ハイライトに追加する文字列タグを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8595-107">Gets or sets a string tag that is prepended to hit highlights.</span></span>
            <span data-ttu-id="a8595-108">HighlightPostTag で設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8595-108">Must be set with HighlightPostTag.</span></span> <span data-ttu-id="a8595-109">省略した場合、入力候補の語句の強調表示が無効です。</span><span class="sxs-lookup"><span data-stu-id="a8595-109">If omitted, hit highlighting of suggestions is disabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumCoverage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MinimumCoverage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MinimumCoverage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.MinimumCoverage" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumCoverage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MinimumCoverage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.MinimumCoverage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8595-110">取得または成功として報告されることをクエリするために提案クエリによりカバーする必要があります、インデックスの割合を示す 0 から 100 までの数値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8595-110">Gets or sets a number between 0 and 100 indicating the percentage of the index that must be covered by a suggestion query in order for the query to be reported as a success.</span></span> <span data-ttu-id="a8595-111">このパラメーターは、1 つだけのレプリカとサービスに対しても検索の可用性を確保するために便利で指定できます。</span><span class="sxs-lookup"><span data-stu-id="a8595-111">This parameter can be useful for ensuring search availability even for services with only one replica.</span></span> <span data-ttu-id="a8595-112">既定値は 80 です。</span><span class="sxs-lookup"><span data-stu-id="a8595-112">The default is 80.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderBy">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; OrderBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; OrderBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.OrderBy" />
      <MemberSignature Language="VB.NET" Value="Public Property OrderBy As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.OrderBy : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.OrderBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8595-113">取得または結果の並べ替えに使用する OData $orderby 式の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8595-113">Gets or sets the list of OData $orderby expressions by which to sort the results.</span></span> <span data-ttu-id="a8595-114">各式には、フィールド名または geo.distance() 関数への呼び出しのいずれかを指定できます。</span><span class="sxs-lookup"><span data-stu-id="a8595-114">Each expression can be either a field name or a call to the geo.distance() function.</span></span> <span data-ttu-id="a8595-115">各式の後に、昇順を示すために昇順と降順を示すために desc を指定できます。</span><span class="sxs-lookup"><span data-stu-id="a8595-115">Each expression can be followed by asc to indicate ascending, and desc to indicate descending.</span></span> <span data-ttu-id="a8595-116">既定値は昇順です。</span><span class="sxs-lookup"><span data-stu-id="a8595-116">The default is ascending order.</span></span> <span data-ttu-id="a8595-117">結び付きは、ドキュメントの一致スコアによって切り離されます。</span><span class="sxs-lookup"><span data-stu-id="a8595-117">Ties will be broken by the match scores of documents.</span></span> <span data-ttu-id="a8595-118">OrderBy が指定されていない場合、既定の並べ替え順序はドキュメントの一致スコアによって降順です。</span><span class="sxs-lookup"><span data-stu-id="a8595-118">If no OrderBy is specified, the default sort order is descending by document match score.</span></span> <span data-ttu-id="a8595-119">あります最大 32 の Orderby 句。</span><span class="sxs-lookup"><span data-stu-id="a8595-119">There can be at most 32 Orderby clauses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchFields">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SearchFields { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SearchFields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.SearchFields" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchFields As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SearchFields : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.SearchFields" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8595-120">取得または提案のクエリを実行する際に考慮するフィールド名の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8595-120">Gets or sets the list of field names to consider when querying for suggestions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Select { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Select" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.Select" />
      <MemberSignature Language="VB.NET" Value="Public Property Select As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Select : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.Select" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8595-121">取得または設定を取得するフィールドの一覧。</span><span class="sxs-lookup"><span data-stu-id="a8595-121">Gets or sets the list of fields to retrieve.</span></span> <span data-ttu-id="a8595-122">指定しないと、スキーマで取得可能とマークされているすべてのフィールドが含まれます。</span><span class="sxs-lookup"><span data-stu-id="a8595-122">If unspecified, all fields marked as retrievable in the schema are included.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Top">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Top { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Top" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.Top" />
      <MemberSignature Language="VB.NET" Value="Public Property Top As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Top : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.Top" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8595-123">取得または設定を取得する候補の数。</span><span class="sxs-lookup"><span data-stu-id="a8595-123">Gets or sets the number of suggestions to retrieve.</span></span> <span data-ttu-id="a8595-124">これには、1 ~ 100 の値があります。</span><span class="sxs-lookup"><span data-stu-id="a8595-124">This must be a value between 1 and 100.</span></span> <span data-ttu-id="a8595-125">既定では 5 です。</span><span class="sxs-lookup"><span data-stu-id="a8595-125">The default is to 5.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SuggestParameters.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="suggestParameters.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a8595-126">URL クエリ文字列 SuggestParameters インスタンスに変換します。</span><span class="sxs-lookup"><span data-stu-id="a8595-126">Converts the SuggestParameters instance to a URL query string.</span></span>
            </summary>
        <returns><span data-ttu-id="a8595-127">すべての提案パラメーターを含む URL クエリ文字列。</span><span class="sxs-lookup"><span data-stu-id="a8595-127">A URL query string containing all the suggestion parameters.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseFuzzyMatching">
      <MemberSignature Language="C#" Value="public bool UseFuzzyMatching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseFuzzyMatching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SuggestParameters.UseFuzzyMatching" />
      <MemberSignature Language="VB.NET" Value="Public Property UseFuzzyMatching As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseFuzzyMatching : bool with get, set" Usage="Microsoft.Azure.Search.Models.SuggestParameters.UseFuzzyMatching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8595-128">取得または提案クエリのあいまい一致を使用するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8595-128">Gets or sets a value indicating whether to use fuzzy matching for the suggestion query.</span></span> <span data-ttu-id="a8595-129">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="a8595-129">Default is false.</span></span> <span data-ttu-id="a8595-130">設定した場合は true、クエリが検索候補を見つけます、検索テキストに置き換えられたまたは不足している文字がある場合でもです。</span><span class="sxs-lookup"><span data-stu-id="a8595-130">when set to true, the query will find suggestions even if there's a substituted or missing character in the search text.</span></span> <span data-ttu-id="a8595-131">あいまい一致で検索候補を検索すると低速で多くのリソースを消費するため、一部のシナリオではエクスペリエンスがよくなりますが、パフォーマンスは低下します。</span><span class="sxs-lookup"><span data-stu-id="a8595-131">While this provides a better experience in some scenarios it comes at a performance cost as fuzzy suggestion searches are slower and consume more resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>