<Type Name="IIndexesOperations" FullName="Microsoft.Azure.Search.IIndexesOperations">
  <TypeSignature Language="C#" Value="public interface IIndexesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IIndexesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.IIndexesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IIndexesOperations" />
  <TypeSignature Language="F#" Value="type IIndexesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            IndexesOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AnalyzeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.AnalyzeResult&gt;&gt; AnalyzeWithHttpMessagesAsync (string indexName, Microsoft.Azure.Search.Models.AnalyzeRequest request, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.AnalyzeResult&gt;&gt; AnalyzeWithHttpMessagesAsync(string indexName, class Microsoft.Azure.Search.Models.AnalyzeRequest request, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.AnalyzeWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.AnalyzeRequest,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AnalyzeWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.AnalyzeRequest * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.AnalyzeResult&gt;&gt;" Usage="iIndexesOperations.AnalyzeWithHttpMessagesAsync (indexName, request, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.AnalyzeResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="request" Type="Microsoft.Azure.Search.Models.AnalyzeRequest" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="indexName">
            アナライザーのテスト対象のインデックスの名前。
            </param>
        <param name="request">
            テキストやアナライザー、分析コンポーネントをテストします。
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
            アナライザーがトークンにテキストを分割する方法を示しています。
            <see href="https://docs.microsoft.com/rest/api/searchservice/test-analyzer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (Microsoft.Azure.Search.Models.Index index, Nullable&lt;bool&gt; allowIndexDowntime = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.Index&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.Index index, valuetype System.Nullable`1&lt;bool&gt; allowIndexDowntime, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.CreateOrUpdateWithHttpMessagesAsync(Microsoft.Azure.Search.Models.Index,System.Nullable{System.Boolean},Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : Microsoft.Azure.Search.Models.Index * Nullable&lt;bool&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt;" Usage="iIndexesOperations.CreateOrUpdateWithHttpMessagesAsync (index, allowIndexDowntime, searchRequestOptions, accessCondition, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="allowIndexDowntime" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="index">
            インデックスを作成または更新の定義。
            </param>
        <param name="allowIndexDowntime">
            で数秒以上のオフラインのインデックスを取得することにより、インデックスに追加する新しいアナライザー、されなければ、トークンのフィルターまたは char フィルターできます。 これにより、インデックスの作成とクエリの要求が失敗が一時的にさせます。 インデックスを更新すると、インデックスのパフォーマンスと書き込み可用性が数分にわたり損なわれる場合があります。インデックスが非常に大きい場合、その時間も長くなります。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="accessCondition">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しい Azure Search インデックスを作成または、既に存在する場合、インデックスを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string indexName, Microsoft.Azure.Search.Models.Index index, Nullable&lt;bool&gt; allowIndexDowntime = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.Index&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string indexName, class Microsoft.Azure.Search.Models.Index index, valuetype System.Nullable`1&lt;bool&gt; allowIndexDowntime, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.Index,System.Nullable{System.Boolean},Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.Index * Nullable&lt;bool&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt;" Usage="iIndexesOperations.CreateOrUpdateWithHttpMessagesAsync (indexName, index, allowIndexDowntime, searchRequestOptions, accessCondition, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="allowIndexDowntime" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="indexName">
            インデックスを作成または更新の定義。
            </param>
        <param name="index">
            インデックスを作成または更新の定義。
            </param>
        <param name="allowIndexDowntime">
            で数秒以上のオフラインのインデックスを取得することにより、インデックスに追加する新しいアナライザー、されなければ、トークンのフィルターまたは char フィルターできます。 これにより、インデックスの作成とクエリの要求が失敗が一時的にさせます。 インデックスを更新すると、インデックスのパフォーマンスと書き込み可用性が数分にわたり損なわれる場合があります。インデックスが非常に大きい場合、その時間も長くなります。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="accessCondition">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しい Azure Search インデックスを作成または、既に存在する場合、インデックスを更新します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt; CreateWithHttpMessagesAsync (Microsoft.Azure.Search.Models.Index index, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.Index&gt;&gt; CreateWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.Index index, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.CreateWithHttpMessagesAsync(Microsoft.Azure.Search.Models.Index,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : Microsoft.Azure.Search.Models.Index * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt;" Usage="iIndexesOperations.CreateWithHttpMessagesAsync (index, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="index">
            作成するインデックスの定義。
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
            新しい Azure Search インデックスを作成します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.DeleteWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iIndexesOperations.DeleteWithHttpMessagesAsync (indexName, searchRequestOptions, accessCondition, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="indexName">
            削除するインデックスの名前。
            </param>
        <param name="searchRequestOptions">
            操作の追加パラメーター
            </param>
        <param name="accessCondition">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Azure Search インデックスとが含まれているすべてのドキュメントを削除します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ExistsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt; ExistsWithHttpMessagesAsync (string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;bool&gt;&gt; ExistsWithHttpMessagesAsync(string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.ExistsWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt;" Usage="iIndexesOperations.ExistsWithHttpMessagesAsync (indexName, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="indexName">
            インデックスの名前。
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
            Azure Search サービスに指定されたインデックスが存在するかどうかを判断します。
            </summary>
        <returns>
            値を含む応答<c>true</c>インデックスが存在する場合<c>false</c>それ以外の場合。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClient">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.ISearchIndexClient GetClient (string indexName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Search.ISearchIndexClient GetClient(string indexName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.GetClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClient (indexName As String) As ISearchIndexClient" />
      <MemberSignature Language="F#" Value="abstract member GetClient : string -&gt; Microsoft.Azure.Search.ISearchIndexClient" Usage="iIndexesOperations.GetClient indexName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.ISearchIndexClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="indexName">インデックスの名前。</param>
        <summary>
            クエリを実行すると、指定したインデックスにドキュメントを管理するには、インデックスの新しいクライアントを作成します。
            </summary>
        <returns>新しい<c cref="T:Microsoft.Azure.Search.SearchIndexClient">SearchIndexClient</c>インスタンス。</returns>
        <remarks>
            新しいクライアントは、インデックスへの完全な読み取り/書き込みアクセスで構成されます。 直接作成する方法をお勧めのみを計画しているクエリ操作でクライアントを使用する場合、 <c cref="T:Microsoft.Azure.Search.SearchIndexClient">SearchIndexClient</c>インスタンスの代わりにします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatisticsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt;&gt; GetStatisticsWithHttpMessagesAsync (string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt;&gt; GetStatisticsWithHttpMessagesAsync(string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.GetStatisticsWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStatisticsWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt;&gt;" Usage="iIndexesOperations.GetStatisticsWithHttpMessagesAsync (indexName, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="indexName">
            統計情報を取得する対象のインデックスの名前。
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
            ドキュメントの数と記憶域の使用状況を含む、指定したインデックスの統計を返します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Index-Statistics" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt; GetWithHttpMessagesAsync (string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.Index&gt;&gt; GetWithHttpMessagesAsync(string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.GetWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt;" Usage="iIndexesOperations.GetWithHttpMessagesAsync (indexName, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Index&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="indexName">
            取得するインデックスの名前。
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
            Azure Search からインデックス定義を取得します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.IndexListResult&gt;&gt; ListWithHttpMessagesAsync (string select = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.IndexListResult&gt;&gt; ListWithHttpMessagesAsync(string select, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IIndexesOperations.ListWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.IndexListResult&gt;&gt;" Usage="iIndexesOperations.ListWithHttpMessagesAsync (select, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.IndexListResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="select">
            取得するインデックスの定義のプロパティを選択します。
            JSON プロパティ名のコンマ区切りリストとして指定または ' *' のすべてのプロパティです。 既定値は、すべてのプロパティです。
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
            Azure Search サービスの使用可能なすべてのインデックスを一覧表示します。
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexes" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>