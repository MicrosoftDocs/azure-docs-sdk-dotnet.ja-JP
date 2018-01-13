<Type Name="SearchParameters" FullName="Microsoft.Azure.Search.Models.SearchParameters">
  <TypeSignature Language="C#" Value="public class SearchParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SearchParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchParameters" />
  <TypeSignature Language="F#" Value="type SearchParameters = class" />
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
            フィルターのパラメーターは、並べ替え、ファセット、ページング、およびその他のクエリの動作を検索します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SearchParameters.#ctor" />
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
            使用クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Facets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Facets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Facets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.Facets" />
      <MemberSignature Language="VB.NET" Value="Public Property Facets As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Facets : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.Facets" />
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
            取得または検索クエリに適用するファセットの式の一覧を設定します。 各ファセット式には、必要に応じて名前と値のペアのコンマ区切りのリストを続けて、フィールド名が含まれています。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Filter">
      <MemberSignature Language="C#" Value="public string Filter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Filter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.Filter" />
      <MemberSignature Language="VB.NET" Value="Public Property Filter As String" />
      <MemberSignature Language="F#" Value="member this.Filter : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.Filter" />
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
            取得または検索クエリに適用する OData $filter 式を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightFields">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; HighlightFields { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; HighlightFields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.HighlightFields" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightFields As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.HighlightFields : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.HighlightFields" />
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
            取得またはヒット ハイライトに使用するフィールド名の一覧を設定します。
            ヒット ハイライト機能は、検索可能フィールドのみを使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightPostTag">
      <MemberSignature Language="C#" Value="public string HighlightPostTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighlightPostTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.HighlightPostTag" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightPostTag As String" />
      <MemberSignature Language="F#" Value="member this.HighlightPostTag : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.HighlightPostTag" />
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
            取得またはヒット ハイライトに追加される文字列タグを設定します。 HighlightPreTag で設定する必要があります。 既定値は&amp;lt;/em&amp;gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HighlightPreTag">
      <MemberSignature Language="C#" Value="public string HighlightPreTag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HighlightPreTag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.HighlightPreTag" />
      <MemberSignature Language="VB.NET" Value="Public Property HighlightPreTag As String" />
      <MemberSignature Language="F#" Value="member this.HighlightPreTag : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.HighlightPreTag" />
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
            取得または先頭ヒット ハイライトに追加する文字列タグを設定します。
            HighlightPostTag で設定する必要があります。 既定値は&amp;lt; em&amp;gt;。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeTotalResultCount">
      <MemberSignature Language="C#" Value="public bool IncludeTotalResultCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncludeTotalResultCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.IncludeTotalResultCount" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludeTotalResultCount As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncludeTotalResultCount : bool with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.IncludeTotalResultCount" />
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
            取得または結果の合計数を取得するかどうかを示す値を設定します。 既定値は false です。 この値を true に設定すると、パフォーマンスに影響する場合があります。 返されるカウントは概数であることに注意してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumCoverage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MinimumCoverage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MinimumCoverage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.MinimumCoverage" />
      <MemberSignature Language="VB.NET" Value="Public Property MinimumCoverage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MinimumCoverage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.MinimumCoverage" />
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
            取得または成功として報告されることをクエリするために検索クエリで対応する必要があります、インデックスの割合を示す 0 から 100 までの数値を設定します。 このパラメーターは、1 つだけのレプリカとサービスに対しても検索の可用性を確保するために便利で指定できます。 既定値は 100 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderBy">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; OrderBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; OrderBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.OrderBy" />
      <MemberSignature Language="VB.NET" Value="Public Property OrderBy As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.OrderBy : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.OrderBy" />
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
            取得または結果の並べ替えに使用する OData $orderby 式の一覧を設定します。 各式には、フィールド名または geo.distance() 関数への呼び出しのいずれかを指定できます。 各式の後に、昇順を示すために昇順と降順を示すために desc を指定できます。 既定値は昇順です。 結び付きは、ドキュメントの一致スコアによって切り離されます。 OrderBy が指定されていない場合、既定の並べ替え順序はドキュメントの一致スコアによって降順です。 あります最大 32 の Orderby 句。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.QueryType QueryType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Search.Models.QueryType QueryType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.QueryType" />
      <MemberSignature Language="VB.NET" Value="Public Property QueryType As QueryType" />
      <MemberSignature Language="F#" Value="member this.QueryType : Microsoft.Azure.Search.Models.QueryType with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.QueryType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.QueryType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または検索クエリの構文を指定する値を設定します。
            既定値は 'simple' です。 クエリは Lucene のクエリ構文を使用する場合は、'full' を使用します。 このプロパティの使用可能な値が含まれます: 'simple'、'full' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScoringParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringParameter&gt; ScoringParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.ScoringParameter&gt; ScoringParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.ScoringParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property ScoringParameters As IList(Of ScoringParameter)" />
      <MemberSignature Language="F#" Value="member this.ScoringParameters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringParameter&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.ScoringParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringParameter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはスコア付け関数 (たとえば、referencePointParameter) で使用されるパラメーター値の一覧を設定します。 各パラメーターは、ScoringParameter オブジェクトにカプセル化された名前と値のペアです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScoringProfile">
      <MemberSignature Language="C#" Value="public string ScoringProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScoringProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.ScoringProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property ScoringProfile As String" />
      <MemberSignature Language="F#" Value="member this.ScoringProfile : string with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.ScoringProfile" />
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
            取得または結果を並べ替えるために一致するドキュメントの一致スコアを評価するスコア付けプロファイルの名前を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchFields">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SearchFields { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SearchFields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.SearchFields" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchFields As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SearchFields : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.SearchFields" />
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
            取得またはフルテキスト検索に含めるフィールド名の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.SearchMode SearchMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Search.Models.SearchMode SearchMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.SearchMode" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchMode As SearchMode" />
      <MemberSignature Language="F#" Value="member this.SearchMode : Microsoft.Azure.Search.Models.SearchMode with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.SearchMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SearchMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定と一致すると、ドキュメントをカウントするために、検索語句の一部またはすべてを照合する必要があるかどうかを指定する値。 このプロパティの使用可能な値が含まれます。 'any'、'all' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Select { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Select" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.Select" />
      <MemberSignature Language="VB.NET" Value="Public Property Select As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Select : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.Select" />
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
            取得または設定を取得するフィールドの一覧。 指定しないと、スキーマで取得可能とマークされているすべてのフィールドが含まれます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Skip">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Skip { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Skip" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.Skip" />
      <MemberSignature Language="VB.NET" Value="Public Property Skip As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Skip : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.Skip" />
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
            取得またはスキップに検索結果の数を設定します。 この値は 100,000 より大きくすることはできません。 順番に、ドキュメントをスキャンする必要がありますが、この制限によりスキップを使用することはできない場合、は、範囲クエリを使用して、全順序キーとフィルターに OrderBy を代わりに使用を検討します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Top">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Top { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Top" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SearchParameters.Top" />
      <MemberSignature Language="VB.NET" Value="Public Property Top As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Top : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SearchParameters.Top" />
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
            取得または取得する検索結果の数を設定します。 これは、検索結果のクライアント側のページングを実装する Skip と組み合わせて使用できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SearchParameters.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="searchParameters.ToString " />
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
            URL クエリ文字列の使用インスタンスに変換します。
            </summary>
        <returns>すべての検索パラメーターを含む URL クエリ文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>