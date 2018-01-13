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
            フィルターのパラメーターは、並べ替え、ファセット、ページング、およびその他のクエリの動作を検索します。
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
            SearchParametersPayload クラスの新しいインスタンスを初期化します。
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
        <param name="count">結果の合計数を取得するかどうかを指定する値。 既定値は false です。 この値を true に設定すると、パフォーマンスに影響する場合があります。 返されるカウントは概数であることに注意してください。</param>
        <param name="facets">検索クエリに適用するファセットの式のリスト。 各ファセット式には、必要に応じて名前と値のペアのコンマ区切りのリストを続けて、フィールド名が含まれています。</param>
        <param name="filter">検索クエリに適用する OData $filter 式です。</param>
        <param name="highlight">使用するフィールド名のコンマ区切りリストには、重要なポイントがヒットします。 ヒット ハイライト機能は、検索可能フィールドのみを使用できます。</param>
        <param name="highlightPostTag">ヒットに付加される文字列タグが強調表示されます。 HighlightPreTag で設定する必要があります。 既定値は&amp;lt;/em&amp;gt;。</param>
        <param name="highlightPreTag">前にヒットに付加する文字列タグが強調表示されます。 HighlightPostTag で設定する必要があります。 既定値は&amp;lt; em&amp;gt;。</param>
        <param name="minimumCoverage">成功として報告されることをクエリするために検索クエリで対応する必要があります、インデックスの割合を示す 0 から 100 までの数値。 このパラメーターは、1 つだけのレプリカとサービスに対しても検索の可用性を確保するために便利で指定できます。 既定値は 100 です。</param>
        <param name="orderBy">結果の並べ替えに使用する OData $orderby 式のコンマ区切り一覧。 各式には、フィールド名または geo.distance() 関数への呼び出しのいずれかを指定できます。 各式の後に、昇順を示すために昇順と降順を示すために desc を指定できます。 既定値は昇順です。 結び付きは、ドキュメントの一致スコアによって切り離されます。 OrderBy が指定されていない場合、既定の並べ替え順序はドキュメントの一致スコアによって降順です。 あります最大 32 の Orderby 句。</param>
        <param name="queryType">取得または検索クエリの構文を指定する値を設定します。 既定値は 'simple' です。 クエリは Lucene のクエリ構文を使用する場合は、'full' を使用します。 使用可能な値が含まれます: 'simple'、'full'</param>
        <param name="scoringParameters">関数 (たとえば、referencePointParameter) 形式の名前: 値を使用してスコア付けに使用されるパラメーター値の一覧です。 たとえば、スコア付けプロファイル定義されている場合、関数 'mylocation' という名前のパラメーターとパラメーター文字列になります"mylocation:-122.2,44.8"(without the quotes) です。</param>
        <param name="scoringProfile">評価するスコア付けプロファイルの名前では、結果を並べ替えるために一致するドキュメントのスコアと一致します。</param>
        <param name="search">フルテキスト検索クエリ式です。Null を使用して、または"*"のすべてのドキュメントの一致するようにします。</param>
        <param name="searchFields">フルテキスト検索に含めるフィールド名のコンマ区切り一覧。</param>
        <param name="searchMode">一致すると、ドキュメントをカウントするために、検索語句の一部またはすべてを照合する必要があるかどうかを指定する値。 使用可能な値が含まれます 'any'、'all'。</param>
        <param name="select">コンマで区切られたフィールドの一覧を取得します。 指定しないと、スキーマで取得可能とマークされているすべてのフィールドが含まれます。</param>
        <param name="skip">スキップする検索結果の数。 この値は 100,000 より大きくすることはできません。 順番に、ドキュメントをスキャンする必要がありますが、この制限によりスキップを使用することはできない場合、は、範囲クエリを使用して、全順序キーとフィルターに OrderBy を代わりに使用を検討します。</param>
        <param name="top">取得する検索結果の数。 これは、検索結果のクライアント側のページングを実装する Skip と組み合わせて使用できます。 サーバー側のページングが原因には、結果が切り捨て、応答で結果の次のページを取得する ContinueSearch に渡すことが継続トークンが含まれます。 詳細については、DocumentSearchResponse.ContinuationToken を参照してください。</param>
        <summary>
            SearchParametersPayload クラスの新しいインスタンスを初期化します。
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
            取得または結果の合計数を取得するかどうかを示す値を設定します。 既定値は false です。 この値を true に設定すると、パフォーマンスに影響する場合があります。 返されるカウントは概数であることに注意してください。
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
            取得または検索クエリに適用するファセットの式の一覧を設定します。 各ファセット式には、必要に応じて名前と値のペアのコンマ区切りのリストを続けて、フィールド名が含まれています。
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
            取得または検索クエリに適用する OData $filter 式を設定します。
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
            取得またはヒット ハイライトに使用するフィールド名のコンマ区切り一覧を設定します。 ヒット ハイライト機能は、検索可能フィールドのみを使用できます。
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
            取得またはヒット ハイライトに追加される文字列タグを設定します。 HighlightPreTag で設定する必要があります。 既定値は&amp;amp; lt;/em&amp;amp; gt;。
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
            取得または先頭ヒット ハイライトに追加する文字列タグを設定します。 HighlightPostTag で設定する必要があります。 既定値は&amp;amp; lt; em&amp;amp; gt;。
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
            取得または成功として報告されることをクエリするために検索クエリで対応する必要があります、インデックスの割合を示す 0 から 100 までの数値を設定します。 このパラメーターは、1 つだけのレプリカとサービスに対しても検索の可用性を確保するために便利で指定できます。 既定値は 100 です。
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
            取得または結果の並べ替えに使用する OData $orderby 式のコンマ区切り一覧を設定します。 各式には、フィールド名または geo.distance() 関数への呼び出しのいずれかを指定できます。 各式の後に、昇順を示すために昇順と降順を示すために desc を指定できます。 既定値は昇順です。 結び付きは、ドキュメントの一致スコアによって切り離されます。 OrderBy が指定されていない場合、既定の並べ替え順序はドキュメントの一致スコアによって降順です。 あります最大 32 の Orderby 句。
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
            取得または検索クエリの構文を指定する値を設定します。
            既定値は 'simple' です。 クエリは Lucene のクエリ構文を使用する場合は、'full' を使用します。 使用可能な値が含まれます: 'simple'、'full'
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
            取得または関数 (たとえば、referencePointParameter) 形式の名前: 値を使用してスコア付けに使用されるパラメーター値の一覧を設定します。 たとえば、スコア付けプロファイル定義されている場合、関数 'mylocation' という名前のパラメーターとパラメーター文字列になります"mylocation:-122.2,44.8"(without the quotes) です。
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
            取得または結果を並べ替えるために一致するドキュメントの一致スコアを評価するスコア付けプロファイルの名前を設定します。
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
            フルテキスト検索クエリ式。 取得または設定Null を使用して、または"*"のすべてのドキュメントの一致するようにします。
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
            取得またはフルテキスト検索に含めるフィールド名のコンマ区切り一覧を設定します。
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
            取得または設定と一致すると、ドキュメントをカウントするために、検索語句の一部またはすべてを照合する必要があるかどうかを指定する値。 使用可能な値が含まれます 'any'、'all'。
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
            取得または設定、コンマで区切られたフィールドの一覧を取得します。 指定しないと、スキーマで取得可能とマークされているすべてのフィールドが含まれます。
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
            取得またはスキップに検索結果の数を設定します。 この値は 100,000 より大きくすることはできません。 順番に、ドキュメントをスキャンする必要がありますが、この制限によりスキップを使用することはできない場合、は、範囲クエリを使用して、全順序キーとフィルターに OrderBy を代わりに使用を検討します。
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
            取得または取得する検索結果の数を設定します。 これは、検索結果のクライアント側のページングを実装する Skip と組み合わせて使用できます。 サーバー側のページングが原因には、結果が切り捨て、応答で結果の次のページを取得する ContinueSearch に渡すことが継続トークンが含まれます。 詳細については、DocumentSearchResponse.ContinuationToken を参照してください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>