<Type Name="IDocumentsOperations" FullName="Microsoft.Azure.Search.IDocumentsOperations">
  <TypeSignature Language="C#" Value="public interface IDocumentsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDocumentsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.IDocumentsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDocumentsOperations" />
  <TypeSignature Language="F#" Value="type IDocumentsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            インデックスのクエリを実行し、アップロード、マージ、およびドキュメントを削除するための操作を定義します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Document-operations" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinueSearchWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt; ContinueSearchWithHttpMessagesAsync (Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt; ContinueSearchWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.ContinueSearchWithHttpMessagesAsync(Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContinueSearchWithHttpMessagesAsync : Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt;" Usage="iDocumentsOperations.ContinueSearchWithHttpMessagesAsync (continuationToken, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="continuationToken">
            インデックスから検索結果の次のページをフェッチするために必要な状態をカプセル化します。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
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
    <Member MemberName="ContinueSearchWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;&gt; ContinueSearchWithHttpMessagesAsync&lt;T&gt; (Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt;&gt;&gt; ContinueSearchWithHttpMessagesAsync&lt;class T&gt;(class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.ContinueSearchWithHttpMessagesAsync``1(Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContinueSearchWithHttpMessagesAsync : Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T&gt;&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.ContinueSearchWithHttpMessagesAsync (continuationToken, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックスからドキュメントとして取得できます。
            </typeparam>
        <param name="continuationToken">
            インデックスから検索結果の次のページをフェッチするために必要な状態をカプセル化します。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
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
    <Member MemberName="CountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;long&gt;&gt; CountWithHttpMessagesAsync (Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;int64&gt;&gt; CountWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.CountWithHttpMessagesAsync(Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CountWithHttpMessagesAsync : Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;int64&gt;&gt;" Usage="iDocumentsOperations.CountWithHttpMessagesAsync (searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Int64&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
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
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Document&gt;&gt; GetWithHttpMessagesAsync (string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.Document&gt;&gt; GetWithHttpMessagesAsync(string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Document&gt;&gt;" Usage="iDocumentsOperations.GetWithHttpMessagesAsync (key, selectedFields, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="key">
            取得するドキュメントのキー参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" />の有効なドキュメント キーを構築するための規則。
            </param>
        <param name="selectedFields">
            ドキュメントを取得するフィールド名の一覧任意のフィールドを取得できませんが、返されるドキュメント表示されなくなります。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search インデックスからドキュメントを取得します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            ドキュメントを含む応答。
            </returns>
        <remarks>
            Get、されます、および GetWithHttpMessagesAsync メソッドの非ジェネリック オーバー ロードは、型をマップする JSON 応答のペイロード内の .NET 型に最善を尽くしますを確認します。 このマッピングには、インデックスから正確な型情報の利点はないので、マッピングが常に正しくありません。 具体的には、次の場合の注意をして: <list type="bullet"> <item> <description>小数点が System.Int64 (c# の long) を逆シリアル化することがなく値の任意の数値。</description></item><item><description>System.Double ではなく、System.String 型としては、特別な倍精度浮動小数点値 NaN、無限などを逆シリアル化されます。</description></item><item><description>DateTimeOffset のように書式設定値を持つ任意の文字列フィールドがする正しく逆シリアル化できません。Edm.String フィールドではなく Edm.DateTimeOffset フィールドにこのような値を格納することをお勧めします。</description></item><item><description>Edm.DateTimeOffset フィールドは、System.DateTimeOffset、いない System.DateTime として逆シリアル化されます。</description></item></list></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;T&gt;&gt; GetWithHttpMessagesAsync&lt;T&gt; (string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;!!T&gt;&gt; GetWithHttpMessagesAsync&lt;class T&gt;(string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;'T&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.GetWithHttpMessagesAsync (key, selectedFields, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックスからドキュメントとして取得できます。
            </typeparam>
        <param name="key">
            取得するドキュメントのキー参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" />の有効なドキュメント キーを構築するための規則。
            </param>
        <param name="selectedFields">
            ドキュメントを取得するフィールド名の一覧任意のフィールドを取得できませんでは、返されたオブジェクトの対応するプロパティ値として null または default があります。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search インデックスからドキュメントを取得します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            ドキュメントを含む応答。
            </returns>
        <remarks>
            Azure Search フィールド型を型パラメーターのコレクションを除くすべての Azure Search フィールドの種類こと、null 許容型を使用することをお勧め t です。 メモを使用して .NET 型のマッピングをサポートして、ジェネリック メソッドのオーバー ロード、Get、されます、および GetWithHttpMessagesAsyncT 型のプロパティの null 許容のプリミティブ型型マッピングのとおりです: <list type="table"> <listheader> <term>Azure Search フィールド型</term><description>.NET 型</description></listheader><item><term>Edm.String</term> <description>System.String (c# での文字列)</description></item><item><term>Collection(Edm.String)</term><description>IEnumerable&lt;System.String&gt; </description></item> <item> <term>Edm.Boolean</term><description>'system.nullable(of&lt;System.Boolean&gt; (bool? (C#))</description> </item> <item><term>Edm.Double</term><description>'system.nullable(of&lt;System.Double&gt; (二重? (C#))</description></item><item><term>Edm.Int32</term> <description>'System.nullable(of&lt;System.Int32&gt; (int ですか? (C#))</description></item><item><term>Edm.Int64</term><description>'system.nullable(of&lt;System.Int64&gt; (長い? (C#))</description></item><item><term>Edm.DateTimeOffset</term> <description> 'system.nullable(of&lt;System.DateTimeOffset&gt; (DateTimeOffset ですか? C# の場合) または 'system.nullable(of&lt;System.DateTime&gt; (DateTime? C# の場合)。両方の種類作業、DateTimeOffset の使用をお勧めします。ドキュメントを取得するときに、DateTime 値は常に (utc) になります。DateTime 値が次のように解釈されるドキュメントのインデックスを付ける場合: <list type="table"> <item> <term>UTC DateTime</term><description>として送信-インデックスには</description>。</item> <item><term>ローカル DateTime</term><description>インデックスに送信される前に UTC に変換します</description>。</item> <item><term>のタイム ゾーンが指定されていない DateTime</term><description>UTC と見なされ、として送信-インデックスには</description>。</item> </list> </description> </item> <item> <term>Edm.GeographyPoint</term><description><c cref="T:Microsoft.Spatial.GeographyPoint">Microsoft.Spatial.GeographyPoint</c></description></item></list></remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; IndexWithHttpMessagesAsync (Microsoft.Azure.Search.Models.IndexBatch batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; IndexWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.IndexBatch batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.IndexWithHttpMessagesAsync(Microsoft.Azure.Search.Models.IndexBatch,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member IndexWithHttpMessagesAsync : Microsoft.Azure.Search.Models.IndexBatch * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt;" Usage="iDocumentsOperations.IndexWithHttpMessagesAsync (batch, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="batch">
            インデックス操作のバッチです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
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
    <Member MemberName="IndexWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; IndexWithHttpMessagesAsync&lt;T&gt; (Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; IndexWithHttpMessagesAsync&lt;class T&gt;(class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.IndexWithHttpMessagesAsync``1(Microsoft.Azure.Search.Models.IndexBatch{``0},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member IndexWithHttpMessagesAsync : Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.IndexWithHttpMessagesAsync (batch, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックス内のドキュメントとして格納できます。
            </typeparam>
        <param name="batch">
            インデックス操作のバッチです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
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
            Azure Search フィールド型を t です。 型パラメーターを使用して .NET 型のマッピングをサポートして、インデックス、IndexAsync、および IndexWithHttpMessagesAsync メソッドのジェネリック オーバー ロード参照してください<see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />型マッピングの詳細についてはします。
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            インデックス作成操作の一部が失敗しましたが、その他のアクションが成功し、インデックスの状態が変更された場合にスローされます。 これは、Search サービスは負荷が高いインデックス作成は場合に発生します。 明示的にこの例外をキャッチし、確認することが重要、 <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c>プロパティです。 このプロパティは、部分的な障害の後、インデックスの状態を確認します。 これにより、バッチ内の各インデックス アクションの状態を報告します。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SearchWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt; SearchWithHttpMessagesAsync (string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt; SearchWithHttpMessagesAsync(string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SearchWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt;" Usage="iDocumentsOperations.SearchWithHttpMessagesAsync (searchText, searchParameters, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="searchText">
            フルテキスト検索クエリ式です。Null を使用して、または"*"のすべてのドキュメントの一致するようにします。 参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" />検索クエリの構文についての詳細。
            </param>
        <param name="searchParameters">
            検索クエリを絞り込むパラメーターです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
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
    <Member MemberName="SearchWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;&gt; SearchWithHttpMessagesAsync&lt;T&gt; (string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt;&gt;&gt; SearchWithHttpMessagesAsync&lt;class T&gt;(string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SearchWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T&gt;&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.SearchWithHttpMessagesAsync (searchText, searchParameters, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックスからドキュメントとして取得できます。
            </typeparam>
        <param name="searchText">
            フルテキスト検索クエリ式です。Null を使用して、または"*"のすべてのドキュメントの一致するようにします。 参照してください<see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" />検索クエリの構文についての詳細。
            </param>
        <param name="searchParameters">
            検索クエリを絞り込むパラメーターです。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
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
    <Member MemberName="SuggestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;&gt; SuggestWithHttpMessagesAsync (string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;&gt; SuggestWithHttpMessagesAsync(string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.SuggestWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuggestWithHttpMessagesAsync : string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;&gt;" Usage="iDocumentsOperations.SuggestWithHttpMessagesAsync (searchText, suggesterName, suggestParameters, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
        <param name="customHeaders">
            追加されるヘッダーを要求します。
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
    <Member MemberName="SuggestWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;&gt;&gt; SuggestWithHttpMessagesAsync&lt;T&gt; (string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSuggestResult`1&lt;!!T&gt;&gt;&gt; SuggestWithHttpMessagesAsync&lt;class T&gt;(string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.SuggestWithHttpMessagesAsync``1(System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuggestWithHttpMessagesAsync : string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;'T&gt;&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.SuggestWithHttpMessagesAsync (searchText, suggesterName, suggestParameters, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックスからドキュメントとして取得できます。
            </typeparam>
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
        <param name="customHeaders">
            追加されるヘッダーを要求します。
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