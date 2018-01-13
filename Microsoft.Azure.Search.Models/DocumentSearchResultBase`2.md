<Type Name="DocumentSearchResultBase&lt;TResult,TDoc&gt;" FullName="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;TResult,TDoc&gt;">
  <TypeSignature Language="C#" Value="public class DocumentSearchResultBase&lt;TResult,TDoc&gt; where TResult : SearchResultBase&lt;TDoc&gt; where TDoc : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DocumentSearchResultBase`2&lt;(class Microsoft.Azure.Search.Models.SearchResultBase`1&lt;!TDoc&gt;) TResult, class TDoc&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2" />
  <TypeSignature Language="VB.NET" Value="Public Class DocumentSearchResultBase(Of TResult, TDoc)" />
  <TypeSignature Language="F#" Value="type DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TResult">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.Search.Models.SearchResultBase&lt;TDoc&gt;</BaseTypeName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="TDoc">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TResult">
            検索応答内のドキュメントをカプセル化するモデル クラスの型。
            </typeparam>
    <typeparam name="TDoc">
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックスからドキュメントとして取得できます。
            </typeparam>
    <summary>
            Azure Search インデックスから検索を含む応答の結果します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentSearchResultBase ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.SearchContinuationToken ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.SearchContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As SearchContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.Azure.Search.Models.SearchContinuationToken with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SearchContinuationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            検索結果の取得を続行するために使用する継続トークンを取得します。 これは、機能は、Azure Search は、1 つの応答を含む検索要求を実行できない場合に必要です。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            Azure Search は、1 つの検索応答で要求されたすべてのドキュメントを返すことができませんしない限り、このプロパティは null になります。 実装に固有のさまざまな理由により、変更される可能性が発生することができます。
            堅牢なクライアントでは、返されたドキュメントが予想よりも少なく、ドキュメントの取得を継続するために継続トークンが含まれている場合を処理する準備が常にできている必要があります。 このプロパティが null でない場合は、その値を渡すことができます、 <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.ContinueSearchWithHttpMessagesAsync(Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">ContinueSearchAsync</c>複数の検索結果を取得します。
            </para>
          <para>
            このプロパティは、検索結果のページングを実装するのに役立つものでないことに注意してください。 ページングを使用して実装することができます、<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">上部</c>と<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c>パラメーターを検索します。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            検索操作で見つからないか、またはカウントが要求されていない場合は null は、結果の合計数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            存在する場合、数がこの応答に結果の数より大きくなる可能性があります。 これは、使用する場合に発生することができます、<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">上部</c>または<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c>パラメーター、または Azure Search は、1 つの検索応答で要求されたすべてのドキュメントを返すことはできません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Coverage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Coverage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Coverage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.Coverage" />
      <MemberSignature Language="VB.NET" Value="Public Property Coverage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Coverage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.Coverage" />
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
            インデックスがあるが、クエリに含まれているか MinimumCoverage 設定されていない場合は、null の割合を示す値を取得、<c cref="T:Microsoft.Azure.Search.Models.SearchParameters">使用</c>です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Facets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.FacetResults Facets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.FacetResults Facets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.Facets" />
      <MemberSignature Language="VB.NET" Value="Public Property Facets As FacetResults" />
      <MemberSignature Language="F#" Value="member this.Facets : Microsoft.Azure.Search.Models.FacetResults with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.Facets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.FacetResults</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファセットを取得、クエリの結果、検索操作、または null のクエリに任意のファセットの式が含まれていない場合。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;TResult&gt; Results { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;!TResult&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.Results" />
      <MemberSignature Language="VB.NET" Value="Public Property Results As IList(Of TResult)" />
      <MemberSignature Language="F#" Value="member this.Results : System.Collections.Generic.IList&lt;'Result (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt;)&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クエリによって返される結果のシーケンスを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>