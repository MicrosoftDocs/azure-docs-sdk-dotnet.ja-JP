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
            インデックスのクエリを実行し、アップロード、マージ、およびドキュメントを削除するための操作。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="continuationToken">
            インデックスから検索結果の次のページをフェッチするために必要な状態をカプセル化します。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            Azure Search インデックスから検索結果の次のページを取得します。 
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            クエリに一致するドキュメントを含む応答。
            </returns>
        <remarks>
          <para>
            ContinueSearch、ContinueSearchAsync、および ContinueSearchWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。 詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。
            </para>
          <para>
            Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。
            参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。
            </para>
          <para>
            このメソッドが検索結果のページングを実装するのに役立つことはないことに注意してください。 ページングを使用して実装することができます、<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">上部</c>と<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c>パラメーターを<c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">検索</c>メソッドです。
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
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックスからドキュメントとして取得できます。
            </typeparam>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="continuationToken">
            インデックスから検索結果の次のページをフェッチするために必要な状態をカプセル化します。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            Azure Search インデックスから検索結果の次のページを取得します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            クエリに一致するドキュメントを含む応答。
            </returns>
        <remarks>
          <para>
            Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロード、ContinueSearch、ContinueSearchAsync、および ContinueSearchWithHttpMessagesAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。
            </para>
          <para>
            Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。
            参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。
            </para>
          <para>
            このメソッドが検索結果のページングを実装するのに役立つことはないことに注意してください。 ページングを使用して実装することができます、<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">上部</c>と<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c>パラメーターを<c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">検索</c>メソッドです。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="continuationToken">
            インデックスから検索結果の次のページをフェッチするために必要な状態をカプセル化します。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search インデックスから検索結果の次のページを取得します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            クエリに一致するドキュメントを含む応答。
            </returns>
        <remarks>
          <para>
            ContinueSearch、ContinueSearchAsync、および ContinueSearchWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。 詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。
            </para>
          <para>
            Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。
            参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。
            </para>
          <para>
            このメソッドが検索結果のページングを実装するのに役立つことはないことに注意してください。 ページングを使用して実装することができます、<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">上部</c>と<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c>パラメーターを<c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">検索</c>メソッドです。
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
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックスからドキュメントとして取得できます。
            </typeparam>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="continuationToken">
            インデックスから検索結果の次のページをフェッチするために必要な状態をカプセル化します。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search インデックスから検索結果の次のページを取得します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            クエリに一致するドキュメントを含む応答。
            </returns>
        <remarks>
          <para>
            Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロード、ContinueSearch、ContinueSearchAsync、および ContinueSearchWithHttpMessagesAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。
            </para>
          <para>
            Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。
            参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。
            </para>
          <para>
            このメソッドが検索結果のページングを実装するのに役立つことはないことに注意してください。 ページングを使用して実装することができます、<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">上部</c>と<c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c>パラメーターを<c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">検索</c>メソッドです。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            Azure Search インデックスにドキュメントの数を照会します。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search インデックスにドキュメントの数を照会します。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="key">
            取得するドキュメントのキー参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" />の有効なドキュメント キーを構築するための規則。
            </param>
        <param name="selectedFields">
            ドキュメントを取得するフィールド名の一覧任意のフィールドを取得できませんが、返されるドキュメント表示されなくなります。 既定では、取得可能なすべてのフィールドは結果に含まれます。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            Azure Search インデックスからドキュメントを取得します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            要求されたドキュメントです。
            </returns>
        <remarks>
            Get、されます、および GetWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。 詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。
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
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックスからドキュメントとして取得できます。
            </typeparam>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="key">
            取得するドキュメントのキー参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" />の有効なドキュメント キーを構築するための規則。
            </param>
        <param name="selectedFields">
            ドキュメントを取得するフィールド名の一覧任意のフィールドを取得できませんでは、返されたオブジェクトの対応するプロパティ値として null または default があります。 既定では、取得可能なすべてのフィールドは結果に含まれます。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            Azure Search インデックスからドキュメントを取得します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            要求されたドキュメントです。
            </returns>
        <remarks>
            Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロード、Get、されます、および GetWithHttpMessagesAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="key">
            取得するドキュメントのキー参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" />の有効なドキュメント キーを構築するための規則。
            </param>
        <param name="selectedFields">
            ドキュメントを取得するフィールド名の一覧任意のフィールドを取得できませんが、返されるドキュメント表示されなくなります。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search インデックスからドキュメントを取得します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            要求されたドキュメントです。
            </returns>
        <remarks>
            Get、されます、および GetWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。 詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。
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
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックスからドキュメントとして取得できます。
            </typeparam>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="key">
            取得するドキュメントのキー参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" />の有効なドキュメント キーを構築するための規則。
            </param>
        <param name="selectedFields">
            ドキュメントを取得するフィールド名の一覧任意のフィールドを取得できませんでは、返されたオブジェクトの対応するプロパティ値として null または default があります。 既定では、取得可能なすべてのフィールドは結果に含まれます。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search インデックスからドキュメントを取得します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            要求されたドキュメントです。
            </returns>
        <remarks>
            Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロード、Get、されます、および GetWithHttpMessagesAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="batch">
            インデックス操作のバッチです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            Azure Search インデックスには、アップロード、マージ、および削除操作のバッチを送信します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            バッチ内のすべてのアクションの操作の状態を含む応答。
            </returns>
        <remarks>
            インデックス、IndexAsync、および IndexWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。 詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            インデックス作成操作の一部が失敗しましたが、その他のアクションが成功し、インデックスの状態が変更された場合にスローされます。 これは、Search サービスは負荷が高いインデックス作成は場合に発生します。 明示的にこの例外をキャッチし、確認することが重要、 <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c>プロパティです。 このプロパティは、部分的な障害の後、インデックスの状態を確認します。 これにより、バッチ内の各インデックス アクションの状態を報告します。
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
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックス内のドキュメントとして格納できます。
            </typeparam>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="batch">
            インデックス操作のバッチです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            Azure Search インデックスには、アップロード、マージ、および削除操作のバッチを送信します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            バッチ内のすべてのアクションの操作の状態を含む応答。
            </returns>
        <remarks>
            Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロード、インデックスと IndexAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            インデックス作成操作の一部が失敗しましたが、その他のアクションが成功し、インデックスの状態が変更された場合にスローされます。 これは、Search サービスは負荷が高いインデックス作成は場合に発生します。 明示的にこの例外をキャッチし、確認することが重要、 <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c>プロパティです。 このプロパティは、部分的な障害の後、インデックスの状態を確認します。 これにより、バッチ内の各インデックス アクションの状態を報告します。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="batch">
            インデックス操作のバッチです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search インデックスには、アップロード、マージ、および削除操作のバッチを送信します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            バッチ内のすべてのアクションの操作の状態を含む応答。
            </returns>
        <remarks>
            インデックス、IndexAsync、および IndexWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。 詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            インデックス作成操作の一部が失敗しましたが、その他のアクションが成功し、インデックスの状態が変更された場合にスローされます。 これは、Search サービスは負荷が高いインデックス作成は場合に発生します。 明示的にこの例外をキャッチし、確認することが重要、 <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c>プロパティです。 このプロパティは、部分的な障害の後、インデックスの状態を確認します。 これにより、バッチ内の各インデックス アクションの状態を報告します。
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
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックス内のドキュメントとして格納できます。
            </typeparam>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="batch">
            インデックス操作のバッチです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search インデックスには、アップロード、マージ、および削除操作のバッチを送信します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            バッチ内のすべてのアクションの操作の状態を含む応答。
            </returns>
        <remarks>
            Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロード、インデックスと IndexAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            インデックス作成操作の一部が失敗しましたが、その他のアクションが成功し、インデックスの状態が変更された場合にスローされます。 これは、Search サービスは負荷が高いインデックス作成は場合に発生します。 明示的にこの例外をキャッチし、確認することが重要、 <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c>プロパティです。 このプロパティは、部分的な障害の後、インデックスの状態を確認します。 これにより、バッチ内の各インデックス アクションの状態を報告します。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="searchText">
            フルテキスト検索クエリ式です。Null を使用して、または"*"のすべてのドキュメントの一致するようにします。 参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" />検索クエリの構文についての詳細。
            </param>
        <param name="searchParameters">
            検索クエリを絞り込むパラメーターです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            Azure Search インデックス内のドキュメントを検索します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            クエリに一致するドキュメントを含む応答。
            </returns>
        <remarks>
          <para>
            検索、SearchAsync、および SearchWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。 詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。
            </para>
          <para>
            Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。
            参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。
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
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックスからドキュメントとして取得できます。
            </typeparam>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="searchText">
            フルテキスト検索クエリ式です。Null を使用して、または"*"のすべてのドキュメントの一致するようにします。 参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" />検索クエリの構文についての詳細。
            </param>
        <param name="searchParameters">
            検索クエリを絞り込むパラメーターです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            Azure Search インデックス内のドキュメントを検索します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            クエリに一致するドキュメントを含む応答。
            </returns>
        <remarks>
          <para>
            Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、検索、SearchAsync、および SearchWithHttpMessagesAsync メソッドのジェネリック オーバー ロード参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。
            </para>
          <para>
            Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。
            参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="searchText">
            フルテキスト検索クエリ式です。Null を使用して、または"*"のすべてのドキュメントの一致するようにします。 参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" />検索クエリの構文についての詳細。
            </param>
        <param name="searchParameters">
            検索クエリを絞り込むパラメーターです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search インデックス内のドキュメントを検索します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            クエリに一致するドキュメントを含む応答。
            </returns>
        <remarks>
          <para>
            検索、SearchAsync、および SearchWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。 詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。
            </para>
          <para>
            Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。
            参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。
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
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックスからドキュメントとして取得できます。
            </typeparam>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="searchText">
            フルテキスト検索クエリ式です。Null を使用して、または"*"のすべてのドキュメントの一致するようにします。 参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" />検索クエリの構文についての詳細。
            </param>
        <param name="searchParameters">
            検索クエリを絞り込むパラメーターです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search インデックス内のドキュメントを検索します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            クエリに一致するドキュメントを含む応答。
            </returns>
        <remarks>
          <para>
            Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、検索、SearchAsync、および SearchWithHttpMessagesAsync メソッドのジェネリック オーバー ロード参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。
            </para>
          <para>
            Azure Search では、1 つの応答ですべての結果を含めることはできません、返される応答によりより多くの結果を取得する ContinueSearch に渡すことが継続トークンが含まれます。
            参照してください<c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c>詳細についてはします。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="searchText">
            提案を基になる検索するテキスト。
            </param>
        <param name="suggesterName">
            インデックス定義の一部である suggesters コレクションで指定されている、suggester の名前。
            </param>
        <param name="suggestParameters">
            提案クエリを絞り込むパラメーターです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            入力テキストと Azure Search インデックスに一致するドキュメントに基づくクエリ用語をお勧めします。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            推奨されるテキストとクエリに一致するドキュメントを含む応答。
            </returns>
        <remarks>
            候補を表示する、SuggestAsync、および SuggestWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。 詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。
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
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックスからドキュメントとして取得できます。
            </typeparam>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="searchText">
            提案を基になる検索するテキスト。
            </param>
        <param name="suggesterName">
            インデックス定義の一部である suggesters コレクションで指定されている、suggester の名前。
            </param>
        <param name="suggestParameters">
            提案クエリを絞り込むパラメーターです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <summary>
            入力テキストと Azure Search インデックスに一致するドキュメントに基づくクエリ用語をお勧めします。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            推奨されるテキストとクエリに一致するドキュメントを含む応答。
            </returns>
        <remarks>
            Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロードの候補を表示する、SuggestAsync、および SuggestWithHttpMessagesAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。
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
            この拡張メソッドの操作のグループです。
            </param>
        <param name="searchText">
            提案を基になる検索するテキスト。
            </param>
        <param name="suggesterName">
            インデックス定義の一部である suggesters コレクションで指定されている、suggester の名前。
            </param>
        <param name="suggestParameters">
            提案クエリを絞り込むパラメーターです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            入力テキストと Azure Search インデックスに一致するドキュメントに基づくクエリ用語をお勧めします。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            推奨されるテキストとクエリに一致するドキュメントを含む応答。
            </returns>
        <remarks>
            候補を表示する、SuggestAsync、および SuggestWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。 詳細については、「 <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> 」を参照してください。
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
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックスからドキュメントとして取得できます。
            </typeparam>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="searchText">
            提案を基になる検索するテキスト。
            </param>
        <param name="suggesterName">
            インデックス定義の一部である suggesters コレクションで指定されている、suggester の名前。
            </param>
        <param name="suggestParameters">
            提案クエリを絞り込むパラメーターです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            入力テキストと Azure Search インデックスに一致するドキュメントに基づくクエリ用語をお勧めします。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            推奨されるテキストとクエリに一致するドキュメントを含む応答。
            </returns>
        <remarks>
            Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロードの候補を表示する、SuggestAsync、および SuggestWithHttpMessagesAsync参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>