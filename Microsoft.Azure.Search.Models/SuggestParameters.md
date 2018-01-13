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
            フィルターのパラメーター、並べ替え、あいまい一致の場合、およびその他の提案は、動作をクエリします。
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
            SuggestParameters クラスの新しいインスタンスを初期化します。
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
            取得または提案クエリに適用する OData $filter 式を設定します。
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
            取得またはヒット ハイライトに追加される文字列タグを設定します。 HighlightPreTag で設定する必要があります。 省略した場合、入力候補の語句の強調表示が無効です。
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
            取得または先頭ヒット ハイライトに追加する文字列タグを設定します。
            HighlightPostTag で設定する必要があります。 省略した場合、入力候補の語句の強調表示が無効です。
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
            取得または成功として報告されることをクエリするために提案クエリによりカバーする必要があります、インデックスの割合を示す 0 から 100 までの数値を設定します。 このパラメーターは、1 つだけのレプリカとサービスに対しても検索の可用性を確保するために便利で指定できます。 既定値は 80 です。
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
            取得または結果の並べ替えに使用する OData $orderby 式の一覧を設定します。 各式には、フィールド名または geo.distance() 関数への呼び出しのいずれかを指定できます。 各式の後に、昇順を示すために昇順と降順を示すために desc を指定できます。 既定値は昇順です。 結び付きは、ドキュメントの一致スコアによって切り離されます。 OrderBy が指定されていない場合、既定の並べ替え順序はドキュメントの一致スコアによって降順です。 あります最大 32 の Orderby 句。
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
            取得または提案のクエリを実行する際に考慮するフィールド名の一覧を設定します。
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
            取得または設定を取得するフィールドの一覧。 指定しないと、スキーマで取得可能とマークされているすべてのフィールドが含まれます。
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
            取得または設定を取得する候補の数。 これには、1 ~ 100 の値があります。 既定では 5 です。
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
            URL クエリ文字列 SuggestParameters インスタンスに変換します。
            </summary>
        <returns>すべての提案パラメーターを含む URL クエリ文字列。</returns>
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
            取得または提案クエリのあいまい一致を使用するかどうかを示す値を設定します。 既定値は false です。 設定した場合は true、クエリが検索候補を見つけます、検索テキストに置き換えられたまたは不足している文字がある場合でもです。 あいまい一致で検索候補を検索すると低速で多くのリソースを消費するため、一部のシナリオではエクスペリエンスがよくなりますが、パフォーマンスは低下します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>