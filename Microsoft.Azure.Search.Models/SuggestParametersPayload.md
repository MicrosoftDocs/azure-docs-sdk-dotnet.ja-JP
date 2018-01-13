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
            フィルターのパラメーター、並べ替え、あいまい一致の場合、およびその他の提案は、動作をクエリします。
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
            SuggestParametersPayload クラスの新しいインスタンスを初期化します。
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
        <param name="filter">提案クエリに適用する OData $filter 式です。</param>
        <param name="fuzzy">提案クエリのあいまい一致を使用するかどうかを示す値。 既定値は false です。 設定した場合は true、クエリが検索候補を見つけます、検索テキストに置き換えられたまたは不足している文字がある場合でもです。 あいまい一致で検索候補を検索すると低速で多くのリソースを消費するため、一部のシナリオではエクスペリエンスがよくなりますが、パフォーマンスは低下します。</param>
        <param name="highlightPostTag">ヒットに付加される文字列タグが強調表示されます。 HighlightPreTag で設定する必要があります。 省略した場合、入力候補の語句の強調表示が無効です。</param>
        <param name="highlightPreTag">前にヒットに付加する文字列タグが強調表示されます。 HighlightPostTag で設定する必要があります。 省略した場合、入力候補の語句の強調表示が無効です。</param>
        <param name="minimumCoverage">成功として報告されることをクエリするために提案クエリによりカバーする必要があります、インデックスの割合を示す 0 から 100 までの数値。 このパラメーターは、1 つだけのレプリカとサービスに対しても検索の可用性を確保するために便利で指定できます。 既定値は 80 です。</param>
        <param name="orderBy">結果の並べ替えに使用する OData $orderby 式のコンマ区切り一覧。 各式には、フィールド名または geo.distance() 関数への呼び出しのいずれかを指定できます。 各式の後に、昇順を示すために昇順と降順を示すために desc を指定できます。 既定値は昇順です。 結び付きは、ドキュメントの一致スコアによって切り離されます。 OrderBy が指定されていない場合、既定の並べ替え順序はドキュメントの一致スコアによって降順です。 あります最大 32 の Orderby 句。</param>
        <param name="search">提案を基になる検索するテキスト。</param>
        <param name="searchFields">提案のクエリを実行する際に考慮するフィールド名のコンマ区切り一覧。</param>
        <param name="select">コンマで区切られたフィールドの一覧を取得します。 指定しないと、スキーマで取得可能とマークされているすべてのフィールドが含まれます。</param>
        <param name="suggesterName">インデックス定義の一部である suggesters コレクションで指定されている、suggester の名前。</param>
        <param name="top">取得する検索候補の数。 これには、1 ~ 100 の値があります。 既定では 5 です。</param>
        <summary>
            SuggestParametersPayload クラスの新しいインスタンスを初期化します。
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
            取得または提案クエリに適用する OData $filter 式を設定します。
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
            取得または提案クエリのあいまい一致を使用するかどうかを示す値を設定します。 既定値は false です。 設定した場合は true、クエリが検索候補を見つけます、検索テキストに置き換えられたまたは不足している文字がある場合でもです。 あいまい一致で検索候補を検索すると低速で多くのリソースを消費するため、一部のシナリオではエクスペリエンスがよくなりますが、パフォーマンスは低下します。
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
            取得またはヒット ハイライトに追加される文字列タグを設定します。 HighlightPreTag で設定する必要があります。 省略した場合、入力候補の語句の強調表示が無効です。
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
            取得または先頭ヒット ハイライトに追加する文字列タグを設定します。 HighlightPostTag で設定する必要があります。 省略した場合、入力候補の語句の強調表示が無効です。
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
            取得または成功として報告されることをクエリするために提案クエリによりカバーする必要があります、インデックスの割合を示す 0 から 100 までの数値を設定します。 このパラメーターは、1 つだけのレプリカとサービスに対しても検索の可用性を確保するために便利で指定できます。 既定値は 80 です。
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
            取得または結果の並べ替えに使用する OData $orderby 式のコンマ区切り一覧を設定します。 各式には、フィールド名または geo.distance() 関数への呼び出しのいずれかを指定できます。 各式の後に、昇順を示すために昇順と降順を示すために desc を指定できます。 既定値は昇順です。 結び付きは、ドキュメントの一致スコアによって切り離されます。 OrderBy が指定されていない場合、既定の並べ替え順序はドキュメントの一致スコアによって降順です。 あります最大 32 の Orderby 句。
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
            取得または提案を基になる検索テキストを設定します。
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
            取得または設定に関する推奨事項についてクエリを実行する際に考慮するフィールド名のコンマ区切り一覧。
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
            取得または設定、コンマで区切られたフィールドの一覧を取得します。 指定しないと、スキーマで取得可能とマークされているすべてのフィールドが含まれます。
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
            取得またはインデックスの定義の一部である suggesters コレクションで指定されている、suggester の名前を設定します。
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
            取得または設定を取得する候補の数。 これには、1 ~ 100 の値があります。 既定では 5 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>