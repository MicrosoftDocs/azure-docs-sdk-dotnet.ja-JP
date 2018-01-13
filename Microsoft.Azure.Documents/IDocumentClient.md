<Type Name="IDocumentClient" FullName="Microsoft.Azure.Documents.IDocumentClient">
  <TypeSignature Language="C#" Value="public interface IDocumentClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDocumentClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.IDocumentClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDocumentClient" />
  <TypeSignature Language="F#" Value="type IDocumentClient = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            IDocumentClient インターフェイスは、Azure Cosmos DB サービスの .NET SDK の API のシグネチャをキャプチャします。
            参照してください<see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />実装の詳細。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthKey">
      <MemberSignature Language="C#" Value="public System.Security.SecureString AuthKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Security.SecureString AuthKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IDocumentClient.AuthKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuthKey As SecureString" />
      <MemberSignature Language="F#" Value="member this.AuthKey : System.Security.SecureString" Usage="Microsoft.Azure.Documents.IDocumentClient.AuthKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.SecureString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Cosmos DB の Azure サービスでクライアントによって使用される AuthKey を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Client.ConnectionPolicy ConnectionPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Client.ConnectionPolicy ConnectionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IDocumentClient.ConnectionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionPolicy As ConnectionPolicy" />
      <MemberSignature Language="F#" Value="member this.ConnectionPolicy : Microsoft.Azure.Documents.Client.ConnectionPolicy" Usage="Microsoft.Azure.Documents.IDocumentClient.ConnectionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Client.ConnectionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、 <see cref="T:Microsoft.Azure.Documents.Client.ConnectionPolicy" /> Cosmos DB の Azure サービスでクライアントによって使用されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsistencyLevel">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.ConsistencyLevel ConsistencyLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.ConsistencyLevel ConsistencyLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IDocumentClient.ConsistencyLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsistencyLevel As ConsistencyLevel" />
      <MemberSignature Language="F#" Value="member this.ConsistencyLevel : Microsoft.Azure.Documents.ConsistencyLevel" Usage="Microsoft.Azure.Documents.IDocumentClient.ConsistencyLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ConsistencyLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、構成された<see cref="T:Microsoft.Azure.Documents.ConsistencyLevel" />Cosmos DB の Azure サービス内のクライアントのです。 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; CreateAttachmentAsync (string documentLink, object attachment, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; CreateAttachmentAsync(string documentLink, object attachment, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAttachmentAsync (documentLink As String, attachment As Object, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentAsync : string * obj * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.CreateAttachmentAsync (documentLink, attachment, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="attachment" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">この新しい添付ファイルの親ドキュメントのリンク。 例:  db/db_rid/colls/col_rid/docs/doc_rid/ </param>
        <param name="attachment">添付ファイルのオブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Cosmos DB の Azure サービスに非同期操作として添付ファイルを作成します。
            </summary>
        <returns>
            <see cref="T:System.Threading.Tasks.Task" />サービス応答の非同期操作を表すオブジェクト。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; CreateAttachmentAsync (Uri documentUri, object attachment, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; CreateAttachmentAsync(class System.Uri documentUri, object attachment, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentAsync(System.Uri,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAttachmentAsync (documentUri As Uri, attachment As Object, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentAsync : Uri * obj * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.CreateAttachmentAsync (documentUri, attachment, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="attachment" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">添付ファイルを作成するドキュメントの URI。</param>
        <param name="attachment">添付ファイルのオブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Cosmos DB の Azure サービスに非同期操作として添付ファイルを作成します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; CreateAttachmentAsync (string documentLink, System.IO.Stream mediaStream, Microsoft.Azure.Documents.Client.MediaOptions options = null, Microsoft.Azure.Documents.Client.RequestOptions requestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; CreateAttachmentAsync(string documentLink, class System.IO.Stream mediaStream, class Microsoft.Azure.Documents.Client.MediaOptions options, class Microsoft.Azure.Documents.Client.RequestOptions requestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentAsync(System.String,System.IO.Stream,Microsoft.Azure.Documents.Client.MediaOptions,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentAsync : string * System.IO.Stream * Microsoft.Azure.Documents.Client.MediaOptions * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.CreateAttachmentAsync (documentLink, mediaStream, options, requestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="mediaStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.MediaOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">この新しい添付ファイルの親ドキュメントのリンク。 例:  db/db_rid/colls/col_rid/docs/doc_rid/ </param>
        <param name="mediaStream"><see cref="T:System.IO.Stream" />添付ファイルのメディアのです。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.MediaOptions" />要求します。</param>
        <param name="requestOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            用意されている内容と添付ファイルを作成<paramref name="mediaStream" />Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">いずれか<paramref name="documentLink" />または<paramref name="mediaStream" />が設定されていません。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; CreateAttachmentAsync (Uri documentUri, System.IO.Stream mediaStream, Microsoft.Azure.Documents.Client.MediaOptions options = null, Microsoft.Azure.Documents.Client.RequestOptions requestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; CreateAttachmentAsync(class System.Uri documentUri, class System.IO.Stream mediaStream, class Microsoft.Azure.Documents.Client.MediaOptions options, class Microsoft.Azure.Documents.Client.RequestOptions requestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentAsync(System.Uri,System.IO.Stream,Microsoft.Azure.Documents.Client.MediaOptions,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentAsync : Uri * System.IO.Stream * Microsoft.Azure.Documents.Client.MediaOptions * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.CreateAttachmentAsync (documentUri, mediaStream, options, requestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="mediaStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.MediaOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">添付ファイルを作成するドキュメントの URI。</param>
        <param name="mediaStream">添付ファイルのメディアのストリーム。</param>
        <param name="options">要求のメディア オプション。</param>
        <param name="requestOptions">要求の要求オプション。</param>
        <summary>
            Cosmos DB の Azure サービスに非同期操作として添付ファイルを作成します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Attachment&gt; CreateAttachmentQuery (string documentLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Attachment&gt; CreateAttachmentQuery(string documentLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Attachment&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentLink, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Attachment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">親のドキュメントへのリンク</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスでの添付ファイルのクエリを作成します。 IOrderedQueryable {添付} が返されます。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IOrderedQueryable {添付ファイル}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Attachment&gt; CreateAttachmentQuery (Uri documentUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Attachment&gt; CreateAttachmentQuery(class System.Uri documentUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Attachment&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentUri, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Attachment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">親のドキュメントの URI。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでの添付ファイルのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateAttachmentQuery (string documentLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateAttachmentQuery(string documentLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentLink, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">親のドキュメント リソースへのリンク。</param>
        <param name="querySpec">SQL 式を含む SqlQuerySpec インスタンス。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
             オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスでパラメーター化された値を持つ SQL ステートメントを使用して、クエリの添付ファイルを作成します。 IQueryable {ダイナミック} が返されます。
             パラメーター化された値を持つ SQL ステートメントを準備する方法の詳細についてを参照してください<see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />です。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateAttachmentQuery (string documentLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateAttachmentQuery(string documentLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentLink, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">親のドキュメントへのリンク。</param>
        <param name="sqlExpression">SQL ステートメント。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービス SQL ステートメントを使用して、クエリの添付ファイルを作成します。 IQueryable {ダイナミック} が返されます。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateAttachmentQuery (Uri documentUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateAttachmentQuery(class System.Uri documentUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentUri, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">親のドキュメントの URI。</param>
        <param name="querySpec">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでの添付ファイルのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateAttachmentQuery (Uri documentUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateAttachmentQuery(class System.Uri documentUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentUri, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">親のドキュメントの URI。</param>
        <param name="sqlExpression">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでの添付ファイルのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;T&gt; CreateAttachmentQuery&lt;T&gt; (string documentLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;!!T&gt; CreateAttachmentQuery&lt;T&gt;(string documentLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery``1(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentLink, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">照会するオブジェクトの型。</typeparam>
        <param name="documentLink">親のドキュメントのリンク。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスでの添付ファイルのクエリを作成します。
            </summary>
        <returns>クエリを評価できる IOrderedQueryable {t} です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;T&gt; CreateAttachmentQuery&lt;T&gt; (Uri documentUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;!!T&gt; CreateAttachmentQuery&lt;T&gt;(class System.Uri documentUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery``1(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentUri, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">照会するオブジェクトの型。</typeparam>
        <param name="documentUri">親のドキュメントの URI。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでの添付ファイルのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; CreateAttachmentQuery&lt;T&gt; (string documentLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!T&gt; CreateAttachmentQuery&lt;T&gt;(string documentLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery``1(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentLink, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="documentLink">親のドキュメントのリンク。</param>
        <param name="querySpec">SQL 式を含む SqlQuerySpec インスタンス。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
             オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスでパラメーター化された値を持つ SQL ステートメントを使用して、クエリの添付ファイルを作成します。
             パラメーター化された値を持つ SQL ステートメントを準備する方法の詳細についてを参照してください<see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />です。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IQueryable {t} です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; CreateAttachmentQuery&lt;T&gt; (string documentLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!T&gt; CreateAttachmentQuery&lt;T&gt;(string documentLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery``1(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentLink, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="documentLink">親のドキュメントのリンク。</param>
        <param name="sqlExpression">SQL ステートメント。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービス SQL ステートメントを使用して、クエリの添付ファイルを作成します。 
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IQueryable {t} です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; CreateAttachmentQuery&lt;T&gt; (Uri documentUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!T&gt; CreateAttachmentQuery&lt;T&gt;(class System.Uri documentUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery``1(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentUri, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="documentUri">親のドキュメントの URI。</param>
        <param name="querySpec">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでの添付ファイルのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAttachmentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; CreateAttachmentQuery&lt;T&gt; (Uri documentUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!T&gt; CreateAttachmentQuery&lt;T&gt;(class System.Uri documentUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateAttachmentQuery``1(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateAttachmentQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateAttachmentQuery (documentUri, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="documentUri">親のドキュメントの URI。</param>
        <param name="sqlExpression">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでの添付ファイルのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConflictQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Conflict&gt; CreateConflictQuery (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Conflict&gt; CreateConflictQuery(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateConflictQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateConflictQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Conflict&gt;" Usage="iDocumentClient.CreateConflictQuery (collectionLink, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Conflict&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親コレクションのリソースへのリンク。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスのコレクションでの競合のクエリを作成します。 「IOrderedQueryable {競合} が返されます。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IOrderedQueryable {競合}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConflictQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Conflict&gt; CreateConflictQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Conflict&gt; CreateConflictQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateConflictQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateConflictQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Conflict&gt;" Usage="iDocumentClient.CreateConflictQuery (documentCollectionUri, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Conflict&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでの競合についてクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConflictQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateConflictQuery (string collectionLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateConflictQuery(string collectionLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateConflictQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateConflictQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateConflictQuery (collectionLink, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親コレクションのリソースへのリンク。</param>
        <param name="querySpec">SQL 式を含む SqlQuerySpec インスタンス。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、パラメーター化された値を持つ Azure Cosmos DB サービスのコレクションでの競合のクエリを作成します。 IQueryable {ダイナミック} が返されます。
             パラメーター化された値を持つ SQL ステートメントを準備する方法の詳細についてを参照してください<see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />です。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConflictQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateConflictQuery (string collectionLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateConflictQuery(string collectionLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateConflictQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateConflictQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateConflictQuery (collectionLink, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親コレクションのリソースへのリンク。</param>
        <param name="sqlExpression">SQL ステートメント。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスのコレクションでの競合のクエリを作成します。 IQueryable {競合} が返されます。
            </summary>
        <returns>IQueryable {ダイナミック} を使用してクエリを評価できる、指定された SQL ステートメント。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConflictQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateConflictQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateConflictQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateConflictQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateConflictQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateConflictQuery (documentCollectionUri, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="querySpec">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでの競合についてクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConflictQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateConflictQuery (Uri documentCollectionUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateConflictQuery(class System.Uri documentCollectionUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateConflictQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateConflictQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateConflictQuery (documentCollectionUri, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="sqlExpression">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでの競合についてクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDatabaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt; CreateDatabaseAsync (Microsoft.Azure.Documents.Database database, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Database&gt;&gt; CreateDatabaseAsync(class Microsoft.Azure.Documents.Database database, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDatabaseAsync(Microsoft.Azure.Documents.Database,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDatabaseAsync : Microsoft.Azure.Documents.Database * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;" Usage="iDocumentClient.CreateDatabaseAsync (database, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="database" Type="Microsoft.Azure.Documents.Database" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="database">については、仕様、<see cref="T:Microsoft.Azure.Documents.Database" />を作成します。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Cosmos DB の Azure サービス内の非同期操作として、データベース リソースを作成します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Documents.Database" />サービス応答の非同期操作を表すタスク オブジェクト内で作成されました。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDatabaseQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Database&gt; CreateDatabaseQuery (Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Database&gt; CreateDatabaseQuery(class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDatabaseQuery(Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDatabaseQuery : Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Database&gt;" Usage="iDocumentClient.CreateDatabaseQuery feedOptions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Database&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスのアカウントでデータベースのリソースに対するクエリを作成します。 An IOrderedQueryable 返します {データベース&gt;です。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IOrderedQueryable {データベース}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDatabaseQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDatabaseQuery (Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDatabaseQuery(class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDatabaseQuery(Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDatabaseQuery : Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDatabaseQuery (querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="querySpec">SQL 式を含む SqlQuerySpec インスタンス。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスでパラメーター化された値を持つ SQL ステートメントを使用して、アカウントでデータベースのリソースに対するクエリを作成します。 IQueryable {ダイナミック} が返されます。
             パラメーター化された値を持つ SQL ステートメントを準備する方法の詳細についてを参照してください<see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />です。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDatabaseQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDatabaseQuery (string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDatabaseQuery(string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDatabaseQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDatabaseQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDatabaseQuery (sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="sqlExpression">SQL ステートメント。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービス SQL ステートメントを使用して、アカウントでデータベースのリソースに対するクエリを作成します。 IQueryable {ダイナミック} が返されます。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; CreateDocumentAsync (string collectionLink, object document, Microsoft.Azure.Documents.Client.RequestOptions options = null, bool disableAutomaticIdGeneration = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; CreateDocumentAsync(string collectionLink, object document, class Microsoft.Azure.Documents.Client.RequestOptions options, bool disableAutomaticIdGeneration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateDocumentAsync (collectionLink As String, document As Object, Optional options As RequestOptions = null, Optional disableAutomaticIdGeneration As Boolean = false) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentAsync : string * obj * Microsoft.Azure.Documents.Client.RequestOptions * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.CreateDocumentAsync (collectionLink, document, options, disableAutomaticIdGeneration)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="document" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
        <Parameter Name="disableAutomaticIdGeneration" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="collectionLink">リンク、<see cref="T:Microsoft.Azure.Documents.DocumentCollection" />でドキュメントを作成します。 例:  db db_rid/colls/coll_rid/ </param>
        <param name="document">作成するドキュメント オブジェクト。</param>
        <param name="options">(省略可能)要求のオプションを設定します。 例:  ドキュメントを作成するときに実行するトリガーを指定します。 <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /></param>
        <param name="disableAutomaticIdGeneration">(省略可能)これが True、システムの場合は、自動 id の生成を無効に id プロパティがドキュメントにない場合、例外がスローされます。</param>
        <summary>
            Cosmos DB の Azure サービス内の非同期操作として、ドキュメントを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; CreateDocumentAsync (Uri documentCollectionUri, object document, Microsoft.Azure.Documents.Client.RequestOptions options = null, bool disableAutomaticIdGeneration = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; CreateDocumentAsync(class System.Uri documentCollectionUri, object document, class Microsoft.Azure.Documents.Client.RequestOptions options, bool disableAutomaticIdGeneration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentAsync(System.Uri,System.Object,Microsoft.Azure.Documents.Client.RequestOptions,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateDocumentAsync (documentCollectionUri As Uri, document As Object, Optional options As RequestOptions = null, Optional disableAutomaticIdGeneration As Boolean = false) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentAsync : Uri * obj * Microsoft.Azure.Documents.Client.RequestOptions * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.CreateDocumentAsync (documentCollectionUri, document, options, disableAutomaticIdGeneration)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="document" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
        <Parameter Name="disableAutomaticIdGeneration" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">ドキュメントを作成するドキュメントのコレクションの URI。</param>
        <param name="document">ドキュメント オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <param name="disableAutomaticIdGeneration">自動 id の生成を無効にするフラグです。</param>
        <summary>
            Cosmos DB の Azure サービス内の非同期操作として、ドキュメントを作成します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; CreateDocumentCollectionAsync (string databaseLink, Microsoft.Azure.Documents.DocumentCollection documentCollection, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; CreateDocumentCollectionAsync(string databaseLink, class Microsoft.Azure.Documents.DocumentCollection documentCollection, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentCollectionAsync(System.String,Microsoft.Azure.Documents.DocumentCollection,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentCollectionAsync : string * Microsoft.Azure.Documents.DocumentCollection * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.CreateDocumentCollectionAsync (databaseLink, documentCollection, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="documentCollection" Type="Microsoft.Azure.Documents.DocumentCollection" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">内のコレクションを作成するデータベースのリンク。 例:  db/db_rid/</param>
        <param name="documentCollection"><see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />コレクションを作成するときに提供します。 例:  RequestOptions.OfferThroughput=400 です。 </param>
        <summary>
            Cosmos DB の Azure サービスに非同期操作として、コレクションを作成します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Documents.DocumentCollection" />に含まれているが作成された、<see cref="T:System.Threading.Tasks.Task" />サービス応答の非同期操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; CreateDocumentCollectionAsync (Uri databaseUri, Microsoft.Azure.Documents.DocumentCollection documentCollection, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; CreateDocumentCollectionAsync(class System.Uri databaseUri, class Microsoft.Azure.Documents.DocumentCollection documentCollection, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentCollectionAsync(System.Uri,Microsoft.Azure.Documents.DocumentCollection,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentCollectionAsync : Uri * Microsoft.Azure.Documents.DocumentCollection * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.CreateDocumentCollectionAsync (databaseUri, documentCollection, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="documentCollection" Type="Microsoft.Azure.Documents.DocumentCollection" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">内のコレクションを作成するデータベースの URI。</param>
        <param name="documentCollection"><see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Cosmos DB の Azure サービスに非同期操作として、コレクションを作成します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.DocumentCollection&gt; CreateDocumentCollectionQuery (string databaseLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt; CreateDocumentCollectionQuery(string databaseLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentCollectionQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentCollectionQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.DocumentCollection&gt;" Usage="iDocumentClient.CreateDocumentCollectionQuery (databaseLink, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.DocumentCollection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">親データベースのリソースへのリンク。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービス コレクションのクエリを作成します。 An IOrderedQueryable 返します {DocumentCollection&gt;です。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IOrderedQueryable {DocumentCollection}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.DocumentCollection&gt; CreateDocumentCollectionQuery (Uri databaseUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt; CreateDocumentCollectionQuery(class System.Uri databaseUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentCollectionQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentCollectionQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.DocumentCollection&gt;" Usage="iDocumentClient.CreateDocumentCollectionQuery (databaseUri, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.DocumentCollection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">親データベースの URI。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Azure Cosmos DB サービスのドキュメントのコレクションのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDocumentCollectionQuery (string databaseLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDocumentCollectionQuery(string databaseLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentCollectionQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentCollectionQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDocumentCollectionQuery (databaseLink, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">親データベースのリソースへのリンク。</param>
        <param name="querySpec">SQL 式を含む SqlQuerySpec インスタンス。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、パラメーター化された値を持つ SQL ステートメントを使用して Azure Cosmos DB データベース下のコレクションのクエリを作成します。 IQueryable {ダイナミック} が返されます。
             パラメーター化された値を持つ SQL ステートメントを準備する方法の詳細についてを参照してください<see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />です。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDocumentCollectionQuery (string databaseLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDocumentCollectionQuery(string databaseLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentCollectionQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentCollectionQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDocumentCollectionQuery (databaseLink, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">親データベースのリソースへのリンク。</param>
        <param name="sqlExpression">SQL ステートメント。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、SQL ステートメントを使用して Azure Cosmos DB データベース下のコレクションのクエリを作成します。   IQueryable {DocumentCollection} が返されます。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDocumentCollectionQuery (Uri databaseUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDocumentCollectionQuery(class System.Uri databaseUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentCollectionQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentCollectionQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDocumentCollectionQuery (databaseUri, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">データベースへの URI。</param>
        <param name="querySpec">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Azure Cosmos DB サービスのドキュメントのコレクションのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDocumentCollectionQuery (Uri databaseUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDocumentCollectionQuery(class System.Uri databaseUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentCollectionQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentCollectionQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDocumentCollectionQuery (databaseUri, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">データベースへの URI。</param>
        <param name="sqlExpression">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Azure Cosmos DB サービスのドキュメントのコレクションのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Document&gt; CreateDocumentQuery (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Document&gt; CreateDocumentQuery(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Document&gt;" Usage="iDocumentClient.CreateDocumentQuery (collectionLink, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Document&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親ドキュメント コレクションにリンクします。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスのコレクションの下のドキュメントのクエリを作成します。 IOrderedQueryable {ドキュメント} が返されます。
            </summary>
        <returns>クエリを評価できる IOrderedQueryable {ドキュメント}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Document&gt; CreateDocumentQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Document&gt; CreateDocumentQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Document&gt;" Usage="iDocumentClient.CreateDocumentQuery (documentCollectionUri, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Document&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">ドキュメントのコレクションの URI。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでドキュメントのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDocumentQuery (string collectionLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDocumentQuery(string collectionLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDocumentQuery (collectionLink, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親ドキュメント コレクションにリンクします。</param>
        <param name="querySpec">SQL 式を含む SqlQuerySpec インスタンス。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、パラメーター化された値を持つ SQL ステートメントを使用して、Azure Cosmos DB サービスのコレクションの下のドキュメントのクエリを作成します。 IQueryable {ダイナミック} が返されます。
            パラメーター化された値を持つ SQL ステートメントを準備する方法の詳細についてを参照してください<see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />です。
            </summary>
        <returns>IQueryable {動的&gt;クエリを評価することができます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDocumentQuery (string collectionLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDocumentQuery(string collectionLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDocumentQuery (collectionLink, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親ドキュメント コレクションにリンクします。</param>
        <param name="sqlExpression">SQL ステートメント。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、SQL ステートメントを使用して Azure Cosmos DB サービスのコレクションの下のドキュメントのクエリを作成します。 IQueryable {ダイナミック} が返されます。
            </summary>
        <returns>IQueryable {動的&gt;クエリを評価することができます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDocumentQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDocumentQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDocumentQuery (documentCollectionUri, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">ドキュメントのコレクションの URI。</param>
        <param name="querySpec">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでドキュメントのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateDocumentQuery (Uri documentCollectionUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateDocumentQuery(class System.Uri documentCollectionUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateDocumentQuery (documentCollectionUri, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">ドキュメントのコレクションの URI。</param>
        <param name="sqlExpression">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでドキュメントのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;T&gt; CreateDocumentQuery&lt;T&gt; (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;!!T&gt; CreateDocumentQuery&lt;T&gt;(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery``1(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateDocumentQuery (collectionLink, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">照会するオブジェクトの型。</typeparam>
        <param name="collectionLink">親コレクションのリソースへのリンク。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスのコレクションの下のドキュメントのクエリを作成します。
            </summary>
        <returns>クエリを評価できる IOrderedQueryable {t} です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;T&gt; CreateDocumentQuery&lt;T&gt; (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;!!T&gt; CreateDocumentQuery&lt;T&gt;(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery``1(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateDocumentQuery (documentCollectionUri, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">照会するオブジェクトの型。</typeparam>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでドキュメントのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; CreateDocumentQuery&lt;T&gt; (string collectionLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!T&gt; CreateDocumentQuery&lt;T&gt;(string collectionLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery``1(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateDocumentQuery (collectionLink, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">照会するオブジェクトの型。</typeparam>
        <param name="collectionLink">親ドキュメント コレクションにリンクします。</param>
        <param name="querySpec">SQL 式を含む SqlQuerySpec インスタンス。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、パラメーター化された値を持つ SQL ステートメントを使用して、Azure Cosmos DB サービスのコレクションの下のドキュメントのクエリを作成します。 IQueryable {t} を返します。
             パラメーター化された値を持つ SQL ステートメントを準備する方法の詳細についてを参照してください<see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />です。
            </summary>
        <returns>クエリを評価できる IQueryable {t} です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; CreateDocumentQuery&lt;T&gt; (string collectionLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!T&gt; CreateDocumentQuery&lt;T&gt;(string collectionLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery``1(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateDocumentQuery (collectionLink, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">照会するオブジェクトの型。</typeparam>
        <param name="collectionLink">親コレクションにリンクします。</param>
        <param name="sqlExpression">SQL ステートメント。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、SQL ステートメントを使用して Azure Cosmos DB サービスのコレクションの下のドキュメントのクエリを作成します。 IQueryable {t} を返します。
            </summary>
        <returns>クエリを評価できる IQueryable {t} です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; CreateDocumentQuery&lt;T&gt; (Uri documentCollectionUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!T&gt; CreateDocumentQuery&lt;T&gt;(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery``1(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateDocumentQuery (documentCollectionUri, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">照会するオブジェクトの型。</typeparam>
        <param name="documentCollectionUri">ドキュメントのコレクションの URI。</param>
        <param name="querySpec">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでドキュメントのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; CreateDocumentQuery&lt;T&gt; (Uri documentCollectionUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!!T&gt; CreateDocumentQuery&lt;T&gt;(class System.Uri documentCollectionUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateDocumentQuery``1(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateDocumentQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;'T&gt;" Usage="iDocumentClient.CreateDocumentQuery (documentCollectionUri, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">照会するオブジェクトの型。</typeparam>
        <param name="documentCollectionUri">ドキュメントのコレクションの URI。</param>
        <param name="sqlExpression">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでドキュメントのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOfferQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Offer&gt; CreateOfferQuery (Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Offer&gt; CreateOfferQuery(class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateOfferQuery(Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateOfferQuery : Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Offer&gt;" Usage="iDocumentClient.CreateOfferQuery feedOptions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Offer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB service アカウントでオファーに対してクエリを作成します。 IOrderedQueryable {オファー} が返されます。
            </summary>
        <returns>クエリを評価できる IOrderedQueryable {オファー}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOfferQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateOfferQuery (Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateOfferQuery(class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateOfferQuery(Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateOfferQuery : Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateOfferQuery (querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="querySpec">SQL 式を含む SqlQuerySpec インスタンス。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、パラメーター化された値を持つ SQL ステートメントを使用して Azure Cosmos DB service アカウントでオファーに対してクエリを作成します。 IQueryable {ダイナミック} が返されます。
            パラメーター化された値を持つ SQL ステートメントを準備する方法の詳細についてを参照してください<see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />です。
            </summary>
        <returns>クエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOfferQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateOfferQuery (string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateOfferQuery(string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateOfferQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateOfferQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateOfferQuery (sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="sqlExpression">SQL ステートメント。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、SQL ステートメントを使用して Azure Cosmos DB service アカウントでオファーに対してクエリを作成します。 これは、{動的} の IQueryable を返します。
            </summary>
        <returns>クエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; CreatePermissionAsync (string userLink, Microsoft.Azure.Documents.Permission permission, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; CreatePermissionAsync(string userLink, class Microsoft.Azure.Documents.Permission permission, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreatePermissionAsync(System.String,Microsoft.Azure.Documents.Permission,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreatePermissionAsync : string * Microsoft.Azure.Documents.Permission * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.CreatePermissionAsync (userLink, permission, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userLink" Type="System.String" />
        <Parameter Name="permission" Type="Microsoft.Azure.Documents.Permission" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userLink">アクセス許可を作成するユーザーのリンク。 例:  db db_rid/ユーザー/user_rid/ </param>
        <param name="permission"><see cref="T:Microsoft.Azure.Documents.Permission" /> オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            Cosmos DB の Azure サービス内の非同期操作として、ユーザー オブジェクトのアクセス許可を作成します。
            </summary>
        <returns>非同期操作が作成されたを含むサービスの応答を表すタスク オブジェクト<see cref="T:Microsoft.Azure.Documents.Permission" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; CreatePermissionAsync (Uri userUri, Microsoft.Azure.Documents.Permission permission, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; CreatePermissionAsync(class System.Uri userUri, class Microsoft.Azure.Documents.Permission permission, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreatePermissionAsync(System.Uri,Microsoft.Azure.Documents.Permission,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreatePermissionAsync : Uri * Microsoft.Azure.Documents.Permission * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.CreatePermissionAsync (userUri, permission, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="permission" Type="Microsoft.Azure.Documents.Permission" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">アクセス許可を作成するユーザーの URI。</param>
        <param name="permission"><see cref="T:Microsoft.Azure.Documents.Permission" /> オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Cosmos DB の Azure サービスに非同期操作としてのアクセス許可を作成します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Permission&gt; CreatePermissionQuery (string permissionsLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Permission&gt; CreatePermissionQuery(string permissionsLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreatePermissionQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreatePermissionQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Permission&gt;" Usage="iDocumentClient.CreatePermissionQuery (permissionsLink, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Permission&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissionsLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="permissionsLink">例: db/db_rid/ユーザー/user_rid/アクセス許可、ユーザー権限のパスのリンク/です。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスのユーザーのアクセス許可のクエリを作成します。 IOrderedQueryable {権限} が返されます。
            </summary>
        <returns>クエリを評価できる IOrderedQueryable {権限}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Permission&gt; CreatePermissionQuery (Uri userUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Permission&gt; CreatePermissionQuery(class System.Uri userUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreatePermissionQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreatePermissionQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Permission&gt;" Usage="iDocumentClient.CreatePermissionQuery (userUri, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Permission&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">親のユーザーの URI。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスにアクセス許可のクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreatePermissionQuery (string permissionsLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreatePermissionQuery(string permissionsLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreatePermissionQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreatePermissionQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreatePermissionQuery (permissionsLink, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissionsLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="permissionsLink">例: db/db_rid/ユーザー/user_rid/アクセス許可、ユーザー権限のパスのリンク/です。</param>
        <param name="querySpec">SQL 式を含む SqlQuerySpec インスタンス。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、パラメーター化された値を持つ SQL ステートメントを使用して、Azure Cosmos DB サービスのユーザーのアクセス許可のクエリを作成します。 IQueryable {ダイナミック} が返されます。
            パラメーター化された値を持つ SQL ステートメントを準備する方法の詳細についてを参照してください<see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />です。
            </summary>
        <returns>クエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreatePermissionQuery (string permissionsLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreatePermissionQuery(string permissionsLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreatePermissionQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreatePermissionQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreatePermissionQuery (permissionsLink, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissionsLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="permissionsLink">例: db/db_rid/ユーザー/user_rid/アクセス許可、ユーザー権限のパスのリンク/です。</param>
        <param name="sqlExpression">SQL ステートメント。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、SQL ステートメントを使用して Azure Cosmos DB サービスのユーザーのアクセス許可のクエリを作成します。 これは、{動的} の IQueryable を返します。
            </summary>
        <returns>クエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreatePermissionQuery (Uri userUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreatePermissionQuery(class System.Uri userUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreatePermissionQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreatePermissionQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreatePermissionQuery (userUri, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">親のユーザーの URI。</param>
        <param name="querySpec">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスにアクセス許可のクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreatePermissionQuery (Uri userUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreatePermissionQuery(class System.Uri userUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreatePermissionQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreatePermissionQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreatePermissionQuery (userUri, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">親のユーザーの URI。</param>
        <param name="sqlExpression">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスにアクセス許可のクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; CreateStoredProcedureAsync (string collectionLink, Microsoft.Azure.Documents.StoredProcedure storedProcedure, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; CreateStoredProcedureAsync(string collectionLink, class Microsoft.Azure.Documents.StoredProcedure storedProcedure, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateStoredProcedureAsync(System.String,Microsoft.Azure.Documents.StoredProcedure,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateStoredProcedureAsync : string * Microsoft.Azure.Documents.StoredProcedure * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.CreateStoredProcedureAsync (collectionLink, storedProcedure, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="storedProcedure" Type="Microsoft.Azure.Documents.StoredProcedure" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">ストアド プロシージャを作成するコレクションのリンク。 例:  db db_rid/colls/col_rid/</param>
        <param name="storedProcedure"><see cref="T:Microsoft.Azure.Documents.StoredProcedure" />オブジェクトを作成します。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            Cosmos DB の Azure サービス内の非同期操作として、ストアド プロシージャを作成します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Documents.StoredProcedure" />に含まれているが作成された、<see cref="T:System.Threading.Tasks.Task" />サービス応答の非同期操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; CreateStoredProcedureAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.StoredProcedure storedProcedure, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; CreateStoredProcedureAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.StoredProcedure storedProcedure, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateStoredProcedureAsync(System.Uri,Microsoft.Azure.Documents.StoredProcedure,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateStoredProcedureAsync : Uri * Microsoft.Azure.Documents.StoredProcedure * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.CreateStoredProcedureAsync (documentCollectionUri, storedProcedure, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="storedProcedure" Type="Microsoft.Azure.Documents.StoredProcedure" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">内のストアド プロシージャを作成するドキュメントのコレクションの URI。</param>
        <param name="storedProcedure"><see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Cosmos DB の Azure サービス内の非同期操作として、ストアド プロシージャを作成します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.StoredProcedure&gt; CreateStoredProcedureQuery (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt; CreateStoredProcedureQuery(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateStoredProcedureQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateStoredProcedureQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.StoredProcedure&gt;" Usage="iDocumentClient.CreateStoredProcedureQuery (collectionLink, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.StoredProcedure&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親コレクションのリソースへのリンク。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスのコレクションでのストアド プロシージャのクエリを作成します。 An IOrderedQueryable 返します {StoredProcedure&gt;です。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IOrderedQueryable {[storedprocedure]} です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.StoredProcedure&gt; CreateStoredProcedureQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt; CreateStoredProcedureQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateStoredProcedureQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateStoredProcedureQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.StoredProcedure&gt;" Usage="iDocumentClient.CreateStoredProcedureQuery (documentCollectionUri, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.StoredProcedure&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでストアド プロシージャのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateStoredProcedureQuery (string collectionLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateStoredProcedureQuery(string collectionLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateStoredProcedureQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateStoredProcedureQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateStoredProcedureQuery (collectionLink, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親コレクションのリソースへのリンク。</param>
        <param name="querySpec">SQL 式を含む SqlQuerySpec インスタンス。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、パラメーター化された値を持つ SQL ステートメントを使用して SQL ステートメントを使用して Azure Cosmos DB サービスのコレクションでのストアド プロシージャのクエリを作成します。 IQueryable {ダイナミック} が返されます。
             パラメーター化された値を持つ SQL ステートメントを準備する方法の詳細についてを参照してください<see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />です。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateStoredProcedureQuery (string collectionLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateStoredProcedureQuery(string collectionLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateStoredProcedureQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateStoredProcedureQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateStoredProcedureQuery (collectionLink, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親コレクションのリソースへのリンク。</param>
        <param name="sqlExpression">SQL ステートメント。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、SQL ステートメントを使用して Azure Cosmos DB サービスのコレクションでのストアド プロシージャのクエリを作成します。 IQueryable {ダイナミック} が返されます。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateStoredProcedureQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateStoredProcedureQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateStoredProcedureQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateStoredProcedureQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateStoredProcedureQuery (documentCollectionUri, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="querySpec">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでストアド プロシージャのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateStoredProcedureQuery (Uri documentCollectionUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateStoredProcedureQuery(class System.Uri documentCollectionUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateStoredProcedureQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateStoredProcedureQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateStoredProcedureQuery (documentCollectionUri, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="sqlExpression">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでストアド プロシージャのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; CreateTriggerAsync (string collectionLink, Microsoft.Azure.Documents.Trigger trigger, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; CreateTriggerAsync(string collectionLink, class Microsoft.Azure.Documents.Trigger trigger, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateTriggerAsync(System.String,Microsoft.Azure.Documents.Trigger,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateTriggerAsync : string * Microsoft.Azure.Documents.Trigger * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.CreateTriggerAsync (collectionLink, trigger, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="trigger" Type="Microsoft.Azure.Documents.Trigger" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">リンク、<see cref="T:Microsoft.Azure.Documents.DocumentCollection" />でトリガーを作成します。 例:  db db_rid/colls/col_rid/ </param>
        <param name="trigger"><see cref="T:Microsoft.Azure.Documents.Trigger" />オブジェクトを作成します。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            Cosmos DB の Azure サービス内の非同期操作として、トリガーを作成します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; CreateTriggerAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Trigger trigger, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; CreateTriggerAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Trigger trigger, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateTriggerAsync(System.Uri,Microsoft.Azure.Documents.Trigger,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateTriggerAsync : Uri * Microsoft.Azure.Documents.Trigger * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.CreateTriggerAsync (documentCollectionUri, trigger, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="trigger" Type="Microsoft.Azure.Documents.Trigger" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">トリガーを作成するドキュメントのコレクションの URI。</param>
        <param name="trigger"><see cref="T:Microsoft.Azure.Documents.Trigger" /> オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Cosmos DB の Azure サービス内の非同期操作として、トリガーを作成します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Trigger&gt; CreateTriggerQuery (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Trigger&gt; CreateTriggerQuery(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateTriggerQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateTriggerQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Trigger&gt;" Usage="iDocumentClient.CreateTriggerQuery (collectionLink, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Trigger&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親コレクションのリソースへのリンク。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスのコレクションでのトリガーのクエリを作成します。 An IOrderedQueryable 返します {トリガー&gt;です。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IOrderedQueryable {トリガー}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Trigger&gt; CreateTriggerQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.Trigger&gt; CreateTriggerQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateTriggerQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateTriggerQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Trigger&gt;" Usage="iDocumentClient.CreateTriggerQuery (documentCollectionUri, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.Trigger&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでのトリガーのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateTriggerQuery (string collectionLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateTriggerQuery(string collectionLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateTriggerQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateTriggerQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateTriggerQuery (collectionLink, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親コレクションのリソースへのリンク。</param>
        <param name="querySpec">SQL 式を含む SqlQuerySpec インスタンス。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、パラメーター化された値を持つ SQL ステートメントを使用して、Azure Cosmos DB サービスのコレクションでのトリガーのクエリを作成します。 IQueryable {ダイナミック} が返されます。
             パラメーター化された値を持つ SQL ステートメントを準備する方法の詳細についてを参照してください<see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />です。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IQueryable {トリガー}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateTriggerQuery (string collectionLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateTriggerQuery(string collectionLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateTriggerQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateTriggerQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateTriggerQuery (collectionLink, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親コレクションのリソースへのリンク。</param>
        <param name="sqlExpression">SQL ステートメント。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスのコレクションでのトリガーのクエリを作成します。 IQueryable {ダイナミック} が返されます。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateTriggerQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateTriggerQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateTriggerQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateTriggerQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateTriggerQuery (documentCollectionUri, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="querySpec">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでのトリガーのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateTriggerQuery (Uri documentCollectionUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateTriggerQuery(class System.Uri documentCollectionUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateTriggerQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateTriggerQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateTriggerQuery (documentCollectionUri, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="sqlExpression">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでのトリガーのクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; CreateUserAsync (string databaseLink, Microsoft.Azure.Documents.User user, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; CreateUserAsync(string databaseLink, class Microsoft.Azure.Documents.User user, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserAsync(System.String,Microsoft.Azure.Documents.User,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserAsync : string * Microsoft.Azure.Documents.User * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.CreateUserAsync (databaseLink, user, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="user" Type="Microsoft.Azure.Documents.User" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">ユーザーを作成するデータベースのリンク。 例:  db/db_rid/ </param>
        <param name="user"><see cref="T:Microsoft.Azure.Documents.User" />オブジェクトを作成します。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            Cosmos DB の Azure サービス内の非同期操作として、ユーザー オブジェクトを作成します。
            </summary>
        <returns>非同期操作が作成されたを含むサービスの応答を表すタスク オブジェクト<see cref="T:Microsoft.Azure.Documents.User" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; CreateUserAsync (Uri databaseUri, Microsoft.Azure.Documents.User user, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; CreateUserAsync(class System.Uri databaseUri, class Microsoft.Azure.Documents.User user, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserAsync(System.Uri,Microsoft.Azure.Documents.User,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserAsync : Uri * Microsoft.Azure.Documents.User * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.CreateUserAsync (databaseUri, user, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="user" Type="Microsoft.Azure.Documents.User" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">ユーザーを作成するデータベースの URI。</param>
        <param name="user"><see cref="T:Microsoft.Azure.Documents.User" /> オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Cosmos DB の Azure サービス内の非同期操作として、ユーザーを作成します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; CreateUserDefinedFunctionAsync (string collectionLink, Microsoft.Azure.Documents.UserDefinedFunction function, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; CreateUserDefinedFunctionAsync(string collectionLink, class Microsoft.Azure.Documents.UserDefinedFunction function, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserDefinedFunctionAsync(System.String,Microsoft.Azure.Documents.UserDefinedFunction,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateUserDefinedFunctionAsync (collectionLink As String, function As UserDefinedFunction, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member CreateUserDefinedFunctionAsync : string * Microsoft.Azure.Documents.UserDefinedFunction * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.CreateUserDefinedFunctionAsync (collectionLink, function, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Documents.UserDefinedFunction" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">リンク、<see cref="T:Microsoft.Azure.Documents.DocumentCollection" />ユーザーを作成するには、内の関数を定義します。 例:  db db_rid/colls/col_rid/ </param>
        <param name="function"><see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />オブジェクトを作成します。</param>
        <param name="options">(省略可能)どの<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            Cosmos DB の Azure サービス内の非同期操作として、ユーザー定義関数を作成します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; CreateUserDefinedFunctionAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.UserDefinedFunction function, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; CreateUserDefinedFunctionAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.UserDefinedFunction function, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserDefinedFunctionAsync(System.Uri,Microsoft.Azure.Documents.UserDefinedFunction,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateUserDefinedFunctionAsync (documentCollectionUri As Uri, function As UserDefinedFunction, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member CreateUserDefinedFunctionAsync : Uri * Microsoft.Azure.Documents.UserDefinedFunction * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.CreateUserDefinedFunctionAsync (documentCollectionUri, function, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="function" Type="Microsoft.Azure.Documents.UserDefinedFunction" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">ユーザーを作成するドキュメントのコレクションの URI には、内の関数が定義されています。</param>
        <param name="function"><see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Cosmos DB の Azure サービス内の非同期操作として、ユーザー定義関数を作成します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt; CreateUserDefinedFunctionQuery (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt; CreateUserDefinedFunctionQuery(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserDefinedFunctionQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserDefinedFunctionQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;" Usage="iDocumentClient.CreateUserDefinedFunctionQuery (collectionLink, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親コレクションのリソースへのリンク。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスのコレクションでの udf のクエリを作成します。 An IOrderedQueryable 返します {UserDefinedFunction&gt;です。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IOrderedQueryable {UserDefinedFunction}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt; CreateUserDefinedFunctionQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt; CreateUserDefinedFunctionQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserDefinedFunctionQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserDefinedFunctionQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;" Usage="iDocumentClient.CreateUserDefinedFunctionQuery (documentCollectionUri, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Azure Cosmos DB サービスのユーザー定義関数のクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateUserDefinedFunctionQuery (string collectionLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateUserDefinedFunctionQuery(string collectionLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserDefinedFunctionQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserDefinedFunctionQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateUserDefinedFunctionQuery (collectionLink, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親コレクションのリソースへのリンク。</param>
        <param name="querySpec">SQL 式を含む SqlQuerySpec インスタンス。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、パラメーター化された値を持つ Azure Cosmos DB サービスのコレクションでの udf のクエリを作成します。 IQueryable {ダイナミック} が返されます。
             パラメーター化された値を持つ SQL ステートメントを準備する方法の詳細についてを参照してください<see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />です。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>Https://msdn.microsoft.com/en-us/library/azure/dn782250.aspx と http://azure.microsoft.com/documentation/articles/documentdb-sql-query/ 構文と例についてを参照してください。</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />
        <altmember cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery" />
        <example>
            次の例の id でユーザー定義の関数のクエリの下。
            <code language="c#"><![CDATA[
            var query = new SqlQuerySpec("SELECT * FROM udfs u WHERE u.id = @id", new SqlParameterCollection(new SqlParameter[] { new SqlParameter { Name = "@id", Value = "sqrt" }}));
            UserDefinedFunction udf = client.CreateUserDefinedFunctionQuery(collectionLink, query).AsEnumerable().FirstOrDefault();
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateUserDefinedFunctionQuery (string collectionLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateUserDefinedFunctionQuery(string collectionLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserDefinedFunctionQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserDefinedFunctionQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateUserDefinedFunctionQuery (collectionLink, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親コレクションのリソースへのリンク。</param>
        <param name="sqlExpression">SQL ステートメント。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、SQL ステートメントを使用して Azure Cosmos DB サービスのコレクションでの udf のクエリを作成します。 IQueryable {ダイナミック} が返されます。
            </summary>
        <returns>指定された SQL ステートメントを使用してクエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateUserDefinedFunctionQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateUserDefinedFunctionQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserDefinedFunctionQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserDefinedFunctionQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateUserDefinedFunctionQuery (documentCollectionUri, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="querySpec">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Azure Cosmos DB サービスのユーザー定義関数のクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateUserDefinedFunctionQuery (Uri documentCollectionUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateUserDefinedFunctionQuery(class System.Uri documentCollectionUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserDefinedFunctionQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserDefinedFunctionQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateUserDefinedFunctionQuery (documentCollectionUri, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="sqlExpression">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Azure Cosmos DB サービスのユーザー定義関数のクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.User&gt; CreateUserQuery (string usersLink, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.User&gt; CreateUserQuery(string usersLink, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserQuery(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserQuery : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.User&gt;" Usage="iDocumentClient.CreateUserQuery (usersLink, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.User&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="usersLink" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="usersLink">例: db/db_rid/のユーザー、データベースのユーザーへのパス リンク/です。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスの下でのユーザーに対するクエリを作成します。 IOrderedQueryable {ユーザー} が返されます。
            </summary>
        <returns>クエリを評価できる IOrderedQueryable {ユーザー}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.User&gt; CreateUserQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IOrderedQueryable`1&lt;class Microsoft.Azure.Documents.User&gt; CreateUserQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserQuery(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserQuery : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.User&gt;" Usage="iDocumentClient.CreateUserQuery (documentCollectionUri, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IOrderedQueryable&lt;Microsoft.Azure.Documents.User&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでのユーザーに対するクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateUserQuery (string usersLink, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateUserQuery(string usersLink, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserQuery(System.String,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserQuery : string * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateUserQuery (usersLink, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="usersLink" Type="System.String" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="usersLink">例: db/db_rid/のユーザー、データベースのユーザーへのパス リンク/です。</param>
        <param name="querySpec">SQL 式を含む SqlQuerySpec インスタンス。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、パラメーター化された値を持つ SQL ステートメントを使用して Azure Cosmos DB データベースでのユーザーに対するクエリを作成します。 IQueryable {ダイナミック} が返されます。
            パラメーター化された値を持つ SQL ステートメントを準備する方法の詳細についてを参照してください<see cref="T:Microsoft.Azure.Documents.SqlQuerySpec" />です。
            </summary>
        <returns>IQueryable {動的&gt;クエリを評価することができます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateUserQuery (string usersLink, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateUserQuery(string usersLink, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserQuery(System.String,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserQuery : string * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateUserQuery (usersLink, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="usersLink" Type="System.String" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="usersLink">例: db/db_rid/のユーザー、データベースのユーザーへのパス リンク/です。</param>
        <param name="sqlExpression">SQL ステートメント。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /></param>
        <summary>
            オーバーロードされます。 このメソッドは、Azure Cosmos DB サービスの下でのユーザーに対するクエリを作成します。 IQueryable {動的} が返されます。
            </summary>
        <returns>クエリを評価できる IQueryable {ダイナミック}。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateUserQuery (Uri documentCollectionUri, Microsoft.Azure.Documents.SqlQuerySpec querySpec, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateUserQuery(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.SqlQuerySpec querySpec, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserQuery(System.Uri,Microsoft.Azure.Documents.SqlQuerySpec,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserQuery : Uri * Microsoft.Azure.Documents.SqlQuerySpec * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateUserQuery (documentCollectionUri, querySpec, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="querySpec" Type="Microsoft.Azure.Documents.SqlQuerySpec" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="querySpec">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでのユーザーに対するクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserQuery">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;dynamic&gt; CreateUserQuery (Uri documentCollectionUri, string sqlExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;object&gt; CreateUserQuery(class System.Uri documentCollectionUri, string sqlExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.CreateUserQuery(System.Uri,System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="F#" Value="abstract member CreateUserQuery : Uri * string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Linq.IQueryable&lt;obj&gt;" Usage="iDocumentClient.CreateUserQuery (documentCollectionUri, sqlExpression, feedOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="sqlExpression">Sql クエリです。</param>
        <param name="feedOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />フィード、クエリの結果を処理します。</param>
        <summary>
            Cosmos DB の Azure サービスでのユーザーに対するクエリを作成するメソッドです。
            </summary>
        <returns>クエリの結果セットです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; DeleteAttachmentAsync (string attachmentLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; DeleteAttachmentAsync(string attachmentLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteAttachmentAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAttachmentAsync (attachmentLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member DeleteAttachmentAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.DeleteAttachmentAsync (attachmentLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="attachmentLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="attachmentLink">リンク、<see cref="T:Microsoft.Azure.Documents.Attachment" />を削除します。 例:  db/db_rid/colls/col_rid/docs/doc_rid/添付ファイル/attachment_rid/ </param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            削除、 <see cref="T:Microsoft.Azure.Documents.Attachment" /> Cosmos DB の Azure サービス内の非同期操作として、データベースからです。
            </summary>
        <returns>A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />発行された要求に関する情報を含むです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; DeleteAttachmentAsync (Uri attachmentUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; DeleteAttachmentAsync(class System.Uri attachmentUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteAttachmentAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAttachmentAsync (attachmentUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member DeleteAttachmentAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.DeleteAttachmentAsync (attachmentUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="attachmentUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="attachmentUri">削除する添付ファイルの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として添付ファイルを削除します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteConflictAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt; DeleteConflictAsync (string conflictLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Conflict&gt;&gt; DeleteConflictAsync(string conflictLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteConflictAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteConflictAsync (conflictLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Conflict))" />
      <MemberSignature Language="F#" Value="abstract member DeleteConflictAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;" Usage="iDocumentClient.DeleteConflictAsync (conflictLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="conflictLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="conflictLink">リンク、<see cref="T:Microsoft.Azure.Documents.Conflict" />を削除します。 例:  db/db_rid/colls/coll_rid/競合/ </param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            削除、 <see cref="T:Microsoft.Azure.Documents.Conflict" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />発行された要求に関する情報を含むです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteConflictAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt; DeleteConflictAsync (Uri conflictUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Conflict&gt;&gt; DeleteConflictAsync(class System.Uri conflictUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteConflictAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteConflictAsync (conflictUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Conflict))" />
      <MemberSignature Language="F#" Value="abstract member DeleteConflictAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;" Usage="iDocumentClient.DeleteConflictAsync (conflictUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="conflictUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="conflictUri">削除競合の URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            競合を削除するには、Azure Cosmos DB サービスの非同期操作として。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDatabaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt; DeleteDatabaseAsync (string databaseLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Database&gt;&gt; DeleteDatabaseAsync(string databaseLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteDatabaseAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteDatabaseAsync (databaseLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Database))" />
      <MemberSignature Language="F#" Value="abstract member DeleteDatabaseAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;" Usage="iDocumentClient.DeleteDatabaseAsync (databaseLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">リンク、<see cref="T:Microsoft.Azure.Documents.Database" />を削除します。 例:  db/db_rid/ </param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            削除、 <see cref="T:Microsoft.Azure.Documents.Database" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />発行された要求に関する情報を含むです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDatabaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt; DeleteDatabaseAsync (Uri databaseUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Database&gt;&gt; DeleteDatabaseAsync(class System.Uri databaseUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteDatabaseAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteDatabaseAsync (databaseUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Database))" />
      <MemberSignature Language="F#" Value="abstract member DeleteDatabaseAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;" Usage="iDocumentClient.DeleteDatabaseAsync (databaseUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">削除するデータベースの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、データベースを削除します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; DeleteDocumentAsync (string documentLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; DeleteDocumentAsync(string documentLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteDocumentAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteDocumentAsync (documentLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member DeleteDocumentAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.DeleteDocumentAsync (documentLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">リンク、<see cref="T:Microsoft.Azure.Documents.Document" />を削除します。 例:  db/db_rid/colls/col_rid/docs/doc_rid/ </param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            削除、 <see cref="T:Microsoft.Azure.Documents.Document" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />発行された要求に関する情報を含むです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; DeleteDocumentAsync (Uri documentUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; DeleteDocumentAsync(class System.Uri documentUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteDocumentAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteDocumentAsync (documentUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member DeleteDocumentAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.DeleteDocumentAsync (documentUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">削除するドキュメントの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、ドキュメントを削除します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDocumentCollectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; DeleteDocumentCollectionAsync (string documentCollectionLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; DeleteDocumentCollectionAsync(string documentCollectionLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteDocumentCollectionAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteDocumentCollectionAsync (documentCollectionLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of DocumentCollection))" />
      <MemberSignature Language="F#" Value="abstract member DeleteDocumentCollectionAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.DeleteDocumentCollectionAsync (documentCollectionLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionLink">リンク、<see cref="T:Microsoft.Azure.Documents.Document" />を削除します。 例:  db db_rid/colls/col_rid/ </param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            削除、 <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />発行された要求に関する情報を含むです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteDocumentCollectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; DeleteDocumentCollectionAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; DeleteDocumentCollectionAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteDocumentCollectionAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteDocumentCollectionAsync (documentCollectionUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of DocumentCollection))" />
      <MemberSignature Language="F#" Value="abstract member DeleteDocumentCollectionAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.DeleteDocumentCollectionAsync (documentCollectionUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">削除するドキュメント コレクションの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、コレクションを削除します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletePermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; DeletePermissionAsync (string permissionLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; DeletePermissionAsync(string permissionLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeletePermissionAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeletePermissionAsync (permissionLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Permission))" />
      <MemberSignature Language="F#" Value="abstract member DeletePermissionAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.DeletePermissionAsync (permissionLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="permissionLink">リンク、<see cref="T:Microsoft.Azure.Documents.Permission" />を削除します。 例:  db/db_rid/ユーザー/user_rid/アクセス許可/permission_rid/ </param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            削除、 <see cref="T:Microsoft.Azure.Documents.Permission" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />発行された要求に関する情報を含むです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletePermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; DeletePermissionAsync (Uri permissionUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; DeletePermissionAsync(class System.Uri permissionUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeletePermissionAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeletePermissionAsync (permissionUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Permission))" />
      <MemberSignature Language="F#" Value="abstract member DeletePermissionAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.DeletePermissionAsync (permissionUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="permissionUri">削除する権限の URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作とアクセス許可を削除します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; DeleteStoredProcedureAsync (string storedProcedureLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; DeleteStoredProcedureAsync(string storedProcedureLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteStoredProcedureAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteStoredProcedureAsync (storedProcedureLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of StoredProcedure))" />
      <MemberSignature Language="F#" Value="abstract member DeleteStoredProcedureAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.DeleteStoredProcedureAsync (storedProcedureLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storedProcedureLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="storedProcedureLink">リンク、<see cref="T:Microsoft.Azure.Documents.StoredProcedure" />を削除します。 例:  db/db_rid/colls/col_rid/ストアド プロシージャ/sproc_rid/ </param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            削除、 <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />発行された要求に関する情報を含むです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; DeleteStoredProcedureAsync (Uri storedProcedureUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; DeleteStoredProcedureAsync(class System.Uri storedProcedureUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteStoredProcedureAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteStoredProcedureAsync (storedProcedureUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of StoredProcedure))" />
      <MemberSignature Language="F#" Value="abstract member DeleteStoredProcedureAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.DeleteStoredProcedureAsync (storedProcedureUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storedProcedureUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="storedProcedureUri">削除するストアド プロシージャの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、ストアド プロシージャを削除します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; DeleteTriggerAsync (string triggerLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; DeleteTriggerAsync(string triggerLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteTriggerAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteTriggerAsync (triggerLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Trigger))" />
      <MemberSignature Language="F#" Value="abstract member DeleteTriggerAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.DeleteTriggerAsync (triggerLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="triggerLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="triggerLink">リンク、<see cref="T:Microsoft.Azure.Documents.Trigger" />を削除します。 例:  db/db_rid/colls/col_rid/トリガー/trigger_rid/ </param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            削除、 <see cref="T:Microsoft.Azure.Documents.Trigger" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />発行された要求に関する情報を含むです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; DeleteTriggerAsync (Uri triggerUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; DeleteTriggerAsync(class System.Uri triggerUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteTriggerAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteTriggerAsync (triggerUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Trigger))" />
      <MemberSignature Language="F#" Value="abstract member DeleteTriggerAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.DeleteTriggerAsync (triggerUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="triggerUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="triggerUri">削除するトリガーの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            トリガーを削除するには、Azure Cosmos DB サービスの非同期操作として。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; DeleteUserAsync (string userLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; DeleteUserAsync(string userLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteUserAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteUserAsync (userLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of User))" />
      <MemberSignature Language="F#" Value="abstract member DeleteUserAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.DeleteUserAsync (userLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userLink">リンク、<see cref="T:Microsoft.Azure.Documents.User" />を削除します。 例:  db db_rid/ユーザー/user_rid/ </param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            削除、 <see cref="T:Microsoft.Azure.Documents.User" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />発行された要求に関する情報を含むです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; DeleteUserAsync (Uri userUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; DeleteUserAsync(class System.Uri userUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteUserAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteUserAsync (userUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of User))" />
      <MemberSignature Language="F#" Value="abstract member DeleteUserAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.DeleteUserAsync (userUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">削除するユーザーの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、ユーザーを削除します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; DeleteUserDefinedFunctionAsync (string functionLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; DeleteUserDefinedFunctionAsync(string functionLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteUserDefinedFunctionAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteUserDefinedFunctionAsync (functionLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member DeleteUserDefinedFunctionAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.DeleteUserDefinedFunctionAsync (functionLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="functionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="functionLink">リンク、<see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />を削除します。 例:  db/db_rid/colls/col_rid/udf/udf_rid/ </param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            削除、 <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />発行された要求に関する情報を含むです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; DeleteUserDefinedFunctionAsync (Uri functionUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; DeleteUserDefinedFunctionAsync(class System.Uri functionUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.DeleteUserDefinedFunctionAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteUserDefinedFunctionAsync (functionUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member DeleteUserDefinedFunctionAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.DeleteUserDefinedFunctionAsync (functionUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="functionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="functionUri">ユーザーの URI には、削除する関数が定義されています。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、ユーザー定義関数を削除します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteStoredProcedureAsync&lt;TValue&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;&gt; ExecuteStoredProcedureAsync&lt;TValue&gt; (string storedProcedureLink, params object[] procedureParams);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.StoredProcedureResponse`1&lt;!!TValue&gt;&gt; ExecuteStoredProcedureAsync&lt;TValue&gt;(string storedProcedureLink, object[] procedureParams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ExecuteStoredProcedureAsync``1(System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteStoredProcedureAsync(Of TValue) (storedProcedureLink As String, ParamArray procedureParams As Object()) As Task(Of StoredProcedureResponse(Of TValue))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteStoredProcedureAsync : string * obj[] -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;&gt;" Usage="iDocumentClient.ExecuteStoredProcedureAsync (storedProcedureLink, procedureParams)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TValue" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="storedProcedureLink" Type="System.String" />
        <Parameter Name="procedureParams" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="TValue">ストアド プロシージャの戻り値の型。</typeparam>
        <param name="storedProcedureLink">実行するストアド プロシージャへのリンク。</param>
        <param name="procedureParams">(省略可能)ストアド プロシージャのパラメーターを表す動的オブジェクトの配列。</param>
        <summary>
            Cosmos DB の Azure サービスでは、非同期操作として、コレクションに対してストアド プロシージャを実行します。
            </summary>
        <returns>すべての応答が含まれますが、非同期操作のサービスの応答を表すタスク オブジェクトは、ストアド プロシージャで設定します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">場合<paramref name="storedProcedureLink" />が設定されていません。</exception>
      </Docs>
    </Member>
    <Member MemberName="ExecuteStoredProcedureAsync&lt;TValue&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;&gt; ExecuteStoredProcedureAsync&lt;TValue&gt; (Uri storedProcedureUri, params object[] procedureParams);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.StoredProcedureResponse`1&lt;!!TValue&gt;&gt; ExecuteStoredProcedureAsync&lt;TValue&gt;(class System.Uri storedProcedureUri, object[] procedureParams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ExecuteStoredProcedureAsync``1(System.Uri,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteStoredProcedureAsync(Of TValue) (storedProcedureUri As Uri, ParamArray procedureParams As Object()) As Task(Of StoredProcedureResponse(Of TValue))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteStoredProcedureAsync : Uri * obj[] -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;&gt;" Usage="iDocumentClient.ExecuteStoredProcedureAsync (storedProcedureUri, procedureParams)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TValue" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="storedProcedureUri" Type="System.Uri" />
        <Parameter Name="procedureParams" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="TValue">ストアド プロシージャの戻り値の型。</typeparam>
        <param name="storedProcedureUri">実行するストアド プロシージャの URI。</param>
        <param name="procedureParams">ストアド プロシージャの実行のパラメーターです。</param>
        <summary>
            Cosmos DB の Azure サービスでは、非同期操作として、コレクションに対してストアド プロシージャを実行します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteStoredProcedureAsync&lt;TValue&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;&gt; ExecuteStoredProcedureAsync&lt;TValue&gt; (string storedProcedureLink, Microsoft.Azure.Documents.Client.RequestOptions options, params object[] procedureParams);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.StoredProcedureResponse`1&lt;!!TValue&gt;&gt; ExecuteStoredProcedureAsync&lt;TValue&gt;(string storedProcedureLink, class Microsoft.Azure.Documents.Client.RequestOptions options, object[] procedureParams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ExecuteStoredProcedureAsync``1(System.String,Microsoft.Azure.Documents.Client.RequestOptions,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteStoredProcedureAsync(Of TValue) (storedProcedureLink As String, options As RequestOptions, ParamArray procedureParams As Object()) As Task(Of StoredProcedureResponse(Of TValue))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteStoredProcedureAsync : string * Microsoft.Azure.Documents.Client.RequestOptions * obj[] -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;&gt;" Usage="iDocumentClient.ExecuteStoredProcedureAsync (storedProcedureLink, options, procedureParams)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TValue" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="storedProcedureLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
        <Parameter Name="procedureParams" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="TValue">ストアド プロシージャの戻り値の型。</typeparam>
        <param name="storedProcedureLink">実行するストアド プロシージャへのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <param name="procedureParams">(省略可能)ストアド プロシージャのパラメーターを表す動的オブジェクトの配列。</param>
        <summary>
            サービスでは Azure Cosmos DB、対象のパーティションを指定するには、非同期操作として、パーティションのコレクションに対してストアド プロシージャを実行します。
            </summary>
        <returns>すべての応答が含まれますが、非同期操作のサービスの応答を表すタスク オブジェクトは、ストアド プロシージャで設定します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">場合<paramref name="storedProcedureLink" />が設定されていません。</exception>
      </Docs>
    </Member>
    <Member MemberName="ExecuteStoredProcedureAsync&lt;TValue&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;&gt; ExecuteStoredProcedureAsync&lt;TValue&gt; (Uri storedProcedureUri, Microsoft.Azure.Documents.Client.RequestOptions options, params object[] procedureParams);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.StoredProcedureResponse`1&lt;!!TValue&gt;&gt; ExecuteStoredProcedureAsync&lt;TValue&gt;(class System.Uri storedProcedureUri, class Microsoft.Azure.Documents.Client.RequestOptions options, object[] procedureParams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ExecuteStoredProcedureAsync``1(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteStoredProcedureAsync(Of TValue) (storedProcedureUri As Uri, options As RequestOptions, ParamArray procedureParams As Object()) As Task(Of StoredProcedureResponse(Of TValue))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteStoredProcedureAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions * obj[] -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;'Value&gt;&gt;" Usage="iDocumentClient.ExecuteStoredProcedureAsync (storedProcedureUri, options, procedureParams)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.StoredProcedureResponse&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TValue" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="storedProcedureUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
        <Parameter Name="procedureParams" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <typeparam name="TValue">ストアド プロシージャの戻り値の型。</typeparam>
        <param name="storedProcedureUri">実行するストアド プロシージャの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <param name="procedureParams">ストアド プロシージャの実行のパラメーターです。</param>
        <summary>
            Cosmos DB の Azure サービスでは、非同期操作として、コレクションに対してストアド プロシージャを実行します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatabaseAccountAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.DatabaseAccount&gt; GetDatabaseAccountAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.DatabaseAccount&gt; GetDatabaseAccountAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.GetDatabaseAccountAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDatabaseAccountAsync () As Task(Of DatabaseAccount)" />
      <MemberSignature Language="F#" Value="abstract member GetDatabaseAccountAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.DatabaseAccount&gt;" Usage="iDocumentClient.GetDatabaseAccountAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.DatabaseAccount&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.DatabaseAccount" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="T:Microsoft.Azure.Documents.DatabaseAccount" />でラップ、<see cref="T:System.Threading.Tasks.Task" />オブジェクト。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; ReadAttachmentAsync (string attachmentLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; ReadAttachmentAsync(string attachmentLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadAttachmentAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAttachmentAsync (attachmentLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member ReadAttachmentAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.ReadAttachmentAsync (attachmentLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="attachmentLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="attachmentLink">添付ファイルを読み取るへのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.Attachment" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Attachment" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; ReadAttachmentAsync (Uri attachmentUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; ReadAttachmentAsync(class System.Uri attachmentUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadAttachmentAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAttachmentAsync (attachmentUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member ReadAttachmentAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.ReadAttachmentAsync (attachmentUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="attachmentUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="attachmentUri">読み取られる添付ファイル リソースへの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.Attachment" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Attachment" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAttachmentFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; ReadAttachmentFeedAsync (string documentLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; ReadAttachmentFeedAsync(string documentLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadAttachmentFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAttachmentFeedAsync (documentLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member ReadAttachmentFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.ReadAttachmentFeedAsync (documentLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">親のドキュメント リソースのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />この要求します。</param>
        <summary>
            フィード (シーケンス) を読み取ります<see cref="T:Microsoft.Azure.Documents.Attachment" />Cosmos DB の Azure サービス内の非同期操作としてドキュメントにします。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Attachment" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAttachmentFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; ReadAttachmentFeedAsync (Uri documentUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; ReadAttachmentFeedAsync(class System.Uri documentUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadAttachmentFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAttachmentFeedAsync (documentUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member ReadAttachmentFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.ReadAttachmentFeedAsync (documentUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">親のドキュメントの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、ドキュメントの添付ファイルのフィード (シーケンス) を読み取ります。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadConflictAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt; ReadConflictAsync (string conflictLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Conflict&gt;&gt; ReadConflictAsync(string conflictLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadConflictAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadConflictAsync (conflictLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Conflict))" />
      <MemberSignature Language="F#" Value="abstract member ReadConflictAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;" Usage="iDocumentClient.ReadConflictAsync (conflictLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="conflictLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="conflictLink">読み取られる競合へのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.Conflict" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Conflict" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadConflictAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt; ReadConflictAsync (Uri conflictUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Conflict&gt;&gt; ReadConflictAsync(class System.Uri conflictUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadConflictAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadConflictAsync (conflictUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Conflict))" />
      <MemberSignature Language="F#" Value="abstract member ReadConflictAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;" Usage="iDocumentClient.ReadConflictAsync (conflictUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="conflictUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="conflictUri">読み取られる競合リソースへの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.Conflict" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Conflict" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadConflictFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt; ReadConflictFeedAsync (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Conflict&gt;&gt; ReadConflictFeedAsync(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadConflictFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadConflictFeedAsync (collectionLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Conflict))" />
      <MemberSignature Language="F#" Value="abstract member ReadConflictFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;" Usage="iDocumentClient.ReadConflictFeedAsync (collectionLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親ドキュメント コレクション リソースのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />この要求します。</param>
        <summary>
            フィード (シーケンス) を読み取ります<see cref="T:Microsoft.Azure.Documents.Conflict" />Cosmos DB の Azure サービスで、非同期操作として、コレクションにします。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Conflict" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadConflictFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt; ReadConflictFeedAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Conflict&gt;&gt; ReadConflictFeedAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadConflictFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadConflictFeedAsync (documentCollectionUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Conflict))" />
      <MemberSignature Language="F#" Value="abstract member ReadConflictFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;" Usage="iDocumentClient.ReadConflictFeedAsync (documentCollectionUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Conflict&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、コレクションの競合のフィード (シーケンス) を読み取ります。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDatabaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt; ReadDatabaseAsync (string databaseLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Database&gt;&gt; ReadDatabaseAsync(string databaseLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDatabaseAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDatabaseAsync (databaseLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Database))" />
      <MemberSignature Language="F#" Value="abstract member ReadDatabaseAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;" Usage="iDocumentClient.ReadDatabaseAsync (databaseLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">読み取られるデータベース リソースのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.Database" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Database" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDatabaseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt; ReadDatabaseAsync (Uri databaseUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Database&gt;&gt; ReadDatabaseAsync(class System.Uri databaseUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDatabaseAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDatabaseAsync (databaseUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Database))" />
      <MemberSignature Language="F#" Value="abstract member ReadDatabaseAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;" Usage="iDocumentClient.ReadDatabaseAsync (databaseUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">読み取られるデータベース リソースへの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.Database" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Database" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDatabaseFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt; ReadDatabaseFeedAsync (Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Database&gt;&gt; ReadDatabaseFeedAsync(class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDatabaseFeedAsync(Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDatabaseFeedAsync (Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Database))" />
      <MemberSignature Language="F#" Value="abstract member ReadDatabaseFeedAsync : Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;" Usage="iDocumentClient.ReadDatabaseFeedAsync options" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />この要求します。</param>
        <summary>
            フィード (シーケンス) を読み取ります<see cref="T:Microsoft.Azure.Documents.Database" />Cosmos DB の Azure サービス内の非同期操作としてのデータベース アカウントにします。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Database" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; ReadDocumentAsync (string documentLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; ReadDocumentAsync(string documentLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDocumentAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDocumentAsync (documentLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member ReadDocumentAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.ReadDocumentAsync (documentLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">読み込まれるドキュメントのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.Document" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Document" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; ReadDocumentAsync (Uri documentUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; ReadDocumentAsync(class System.Uri documentUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDocumentAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDocumentAsync (documentUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member ReadDocumentAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.ReadDocumentAsync (documentUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">読み込まれるドキュメントのリソースへの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.Document" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Document" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDocumentCollectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReadDocumentCollectionAsync (string documentCollectionLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReadDocumentCollectionAsync(string documentCollectionLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDocumentCollectionAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDocumentCollectionAsync (documentCollectionLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of DocumentCollection))" />
      <MemberSignature Language="F#" Value="abstract member ReadDocumentCollectionAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.ReadDocumentCollectionAsync (documentCollectionLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionLink">読み取られる DocumentCollection のリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.DocumentCollection" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDocumentCollectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReadDocumentCollectionAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReadDocumentCollectionAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDocumentCollectionAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDocumentCollectionAsync (documentCollectionUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of DocumentCollection))" />
      <MemberSignature Language="F#" Value="abstract member ReadDocumentCollectionAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.ReadDocumentCollectionAsync (documentCollectionUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">読み取られる DocumentCollection リソースへの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.DocumentCollection" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDocumentCollectionFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReadDocumentCollectionFeedAsync (string databaseLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReadDocumentCollectionFeedAsync(string databaseLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDocumentCollectionFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDocumentCollectionFeedAsync (databaseLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of DocumentCollection))" />
      <MemberSignature Language="F#" Value="abstract member ReadDocumentCollectionFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.ReadDocumentCollectionFeedAsync (databaseLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">親データベースのリソースのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />この要求します。</param>
        <summary>
            フィード (シーケンス) を読み取ります<see cref="T:Microsoft.Azure.Documents.DocumentCollection" />Cosmos DB の Azure サービス内の非同期操作としてデータベースにします。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.DocumentCollection" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDocumentCollectionFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReadDocumentCollectionFeedAsync (Uri databaseUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReadDocumentCollectionFeedAsync(class System.Uri databaseUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDocumentCollectionFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDocumentCollectionFeedAsync (databaseUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of DocumentCollection))" />
      <MemberSignature Language="F#" Value="abstract member ReadDocumentCollectionFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.ReadDocumentCollectionFeedAsync (databaseUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">親データベースの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、データベース用のコレクションのフィード (シーケンス) を読み取ります。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDocumentFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;dynamic&gt;&gt; ReadDocumentFeedAsync (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;object&gt;&gt; ReadDocumentFeedAsync(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDocumentFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDocumentFeedAsync (collectionLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Object))" />
      <MemberSignature Language="F#" Value="abstract member ReadDocumentFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;obj&gt;&gt;" Usage="iDocumentClient.ReadDocumentFeedAsync (collectionLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親ドキュメント コレクション リソースのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />この要求します。</param>
        <summary>
            Azure Cosmos DB サービスの指定したコレクションのドキュメントのフィード (シーケンス) を読み取ります。 これにかかる時間を返します、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />動的オブジェクトの列挙した一覧を含むです。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />フィード内の項目を表す動的オブジェクトを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadDocumentFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;dynamic&gt;&gt; ReadDocumentFeedAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;object&gt;&gt; ReadDocumentFeedAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadDocumentFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadDocumentFeedAsync (documentCollectionUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Object))" />
      <MemberSignature Language="F#" Value="abstract member ReadDocumentFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;obj&gt;&gt;" Usage="iDocumentClient.ReadDocumentFeedAsync (documentCollectionUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、コレクションのドキュメントのフィード (シーケンス) を読み取ります。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEndpoint">
      <MemberSignature Language="C#" Value="public Uri ReadEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ReadEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IDocumentClient.ReadEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadEndpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.ReadEndpoint : Uri" Usage="Microsoft.Azure.Documents.IDocumentClient.ReadEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Cosmos DB の Azure サービスでに基づいて可用性と基本設定を選択された現在の読み取りエンドポイントを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadMediaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt; ReadMediaAsync (string mediaLink);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.MediaResponse&gt; ReadMediaAsync(string mediaLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadMediaAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadMediaAsync (mediaLink As String) As Task(Of MediaResponse)" />
      <MemberSignature Language="F#" Value="abstract member ReadMediaAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt;" Usage="iDocumentClient.ReadMediaAsync mediaLink" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mediaLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="mediaLink">読み取るメディアをリンクします。 例:  メディア/media_rid</param>
        <summary>
            Azure Cosmos DB サービスの指定した添付ファイルのコンテンツ (メディアも呼ばれる) を取得します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">場合<paramref name="mediaLink" />が設定されていません。</exception>
        <exception cref="T:System.ArgumentException">場合<paramref name="mediaLink" />/medias/{mediaId} の形式ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="ReadMediaMetadataAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt; ReadMediaMetadataAsync (string mediaLink);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.MediaResponse&gt; ReadMediaMetadataAsync(string mediaLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadMediaMetadataAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadMediaMetadataAsync (mediaLink As String) As Task(Of MediaResponse)" />
      <MemberSignature Language="F#" Value="abstract member ReadMediaMetadataAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt;" Usage="iDocumentClient.ReadMediaMetadataAsync mediaLink" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mediaLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="mediaLink">メタデータを読み取るメディアをリンクします。 例:  メディア/media_rid </param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として指定された添付ファイルのコンテンツ (メディアも呼ばれる) に関連付けられているメタデータを取得します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">場合<paramref name="mediaLink" />が設定されていません。</exception>
        <exception cref="T:System.ArgumentException">場合<paramref name="mediaLink" />/medias/{mediaId} の形式ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="ReadOfferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt; ReadOfferAsync (string offerLink);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Offer&gt;&gt; ReadOfferAsync(string offerLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadOfferAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadOfferAsync (offerLink As String) As Task(Of ResourceResponse(Of Offer))" />
      <MemberSignature Language="F#" Value="abstract member ReadOfferAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt;" Usage="iDocumentClient.ReadOfferAsync offerLink" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="offerLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="offerLink">読み取られるオファーへのリンク。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.Offer" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Offer" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadOffersFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt; ReadOffersFeedAsync (Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Offer&gt;&gt; ReadOffersFeedAsync(class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadOffersFeedAsync(Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadOffersFeedAsync (Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Offer))" />
      <MemberSignature Language="F#" Value="abstract member ReadOffersFeedAsync : Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt;" Usage="iDocumentClient.ReadOffersFeedAsync options" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />この要求します。</param>
        <summary>
            フィード (シーケンス) を読み取ります<see cref="T:Microsoft.Azure.Documents.Offer" />Cosmos DB の Azure サービス内の非同期操作としてのデータベース アカウントにします。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Offer" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadPermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; ReadPermissionAsync (string permissionLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; ReadPermissionAsync(string permissionLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadPermissionAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadPermissionAsync (permissionLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Permission))" />
      <MemberSignature Language="F#" Value="abstract member ReadPermissionAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.ReadPermissionAsync (permissionLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="permissionLink">読み取りアクセス許可のリソースのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.Permission" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Permission" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadPermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; ReadPermissionAsync (Uri permissionUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; ReadPermissionAsync(class System.Uri permissionUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadPermissionAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadPermissionAsync (permissionUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Permission))" />
      <MemberSignature Language="F#" Value="abstract member ReadPermissionAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.ReadPermissionAsync (permissionUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="permissionUri">読み取りアクセス許可のリソースへの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.Permission" /> Cosmos DB の Azure サービス内の非同期操作としてリソース。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Permission" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadPermissionFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; ReadPermissionFeedAsync (string userLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; ReadPermissionFeedAsync(string userLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadPermissionFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadPermissionFeedAsync (userLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Permission))" />
      <MemberSignature Language="F#" Value="abstract member ReadPermissionFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.ReadPermissionFeedAsync (userLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="userLink">親のユーザー リソースのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />この要求します。</param>
        <summary>
            フィード (シーケンス) を読み取ります<see cref="T:Microsoft.Azure.Documents.Permission" />Cosmos DB の Azure サービス内の非同期操作としてユーザーにします。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Permission" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadPermissionFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; ReadPermissionFeedAsync (Uri userUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; ReadPermissionFeedAsync(class System.Uri userUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadPermissionFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadPermissionFeedAsync (userUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Permission))" />
      <MemberSignature Language="F#" Value="abstract member ReadPermissionFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.ReadPermissionFeedAsync (userUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">親のユーザーの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、ユーザーのアクセス許可のフィード (シーケンス) を読み取ります。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReadStoredProcedureAsync (string storedProcedureLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReadStoredProcedureAsync(string storedProcedureLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadStoredProcedureAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadStoredProcedureAsync (storedProcedureLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of StoredProcedure))" />
      <MemberSignature Language="F#" Value="abstract member ReadStoredProcedureAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.ReadStoredProcedureAsync (storedProcedureLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storedProcedureLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="storedProcedureLink">読み取られるストアド プロシージャのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.StoredProcedure" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReadStoredProcedureAsync (Uri storedProcedureUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReadStoredProcedureAsync(class System.Uri storedProcedureUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadStoredProcedureAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadStoredProcedureAsync (storedProcedureUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of StoredProcedure))" />
      <MemberSignature Language="F#" Value="abstract member ReadStoredProcedureAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.ReadStoredProcedureAsync (storedProcedureUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storedProcedureUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="storedProcedureUri">読み取られるストアド プロシージャのリソースへの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.StoredProcedure" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStoredProcedureFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReadStoredProcedureFeedAsync (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReadStoredProcedureFeedAsync(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadStoredProcedureFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadStoredProcedureFeedAsync (collectionLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of StoredProcedure))" />
      <MemberSignature Language="F#" Value="abstract member ReadStoredProcedureFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.ReadStoredProcedureFeedAsync (collectionLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親ドキュメント コレクション リソースのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />この要求します。</param>
        <summary>
            フィード (シーケンス) を読み取ります<see cref="T:Microsoft.Azure.Documents.StoredProcedure" />Cosmos DB の Azure サービスで、非同期操作として、コレクションにします。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.StoredProcedure" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStoredProcedureFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReadStoredProcedureFeedAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReadStoredProcedureFeedAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadStoredProcedureFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadStoredProcedureFeedAsync (documentCollectionUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of StoredProcedure))" />
      <MemberSignature Language="F#" Value="abstract member ReadStoredProcedureFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.ReadStoredProcedureFeedAsync (documentCollectionUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、コレクションでストアド プロシージャをフィード (シーケンス) を読み取ります。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; ReadTriggerAsync (string triggerLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; ReadTriggerAsync(string triggerLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadTriggerAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadTriggerAsync (triggerLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Trigger))" />
      <MemberSignature Language="F#" Value="abstract member ReadTriggerAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.ReadTriggerAsync (triggerLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="triggerLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="triggerLink">読み取られるトリガーへのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.Trigger" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Trigger" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; ReadTriggerAsync (Uri triggerUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; ReadTriggerAsync(class System.Uri triggerUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadTriggerAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadTriggerAsync (triggerUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Trigger))" />
      <MemberSignature Language="F#" Value="abstract member ReadTriggerAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.ReadTriggerAsync (triggerUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="triggerUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="triggerUri">読み取られるトリガー リソースへの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.Trigger" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Trigger" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadTriggerFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; ReadTriggerFeedAsync (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; ReadTriggerFeedAsync(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadTriggerFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadTriggerFeedAsync (collectionLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Trigger))" />
      <MemberSignature Language="F#" Value="abstract member ReadTriggerFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.ReadTriggerFeedAsync (collectionLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親ドキュメント コレクション リソースのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />この要求します。</param>
        <summary>
            フィード (シーケンス) を読み取ります<see cref="T:Microsoft.Azure.Documents.Trigger" />Cosmos DB の Azure サービスで、非同期操作として、コレクションにします。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Trigger" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadTriggerFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; ReadTriggerFeedAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; ReadTriggerFeedAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadTriggerFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadTriggerFeedAsync (documentCollectionUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of Trigger))" />
      <MemberSignature Language="F#" Value="abstract member ReadTriggerFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.ReadTriggerFeedAsync (documentCollectionUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、コレクションのトリガーのフィード (シーケンス) を読み取ります。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; ReadUserAsync (string userLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; ReadUserAsync(string userLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadUserAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadUserAsync (userLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of User))" />
      <MemberSignature Language="F#" Value="abstract member ReadUserAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.ReadUserAsync (userLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userLink">読み取られるユーザー リソースへのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.User" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.User" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; ReadUserAsync (Uri userUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; ReadUserAsync(class System.Uri userUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadUserAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadUserAsync (userUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of User))" />
      <MemberSignature Language="F#" Value="abstract member ReadUserAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.ReadUserAsync (userUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">読み取られるユーザー リソースの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.User" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.User" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReadUserDefinedFunctionAsync (string functionLink, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReadUserDefinedFunctionAsync(string functionLink, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadUserDefinedFunctionAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadUserDefinedFunctionAsync (functionLink As String, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member ReadUserDefinedFunctionAsync : string * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.ReadUserDefinedFunctionAsync (functionLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="functionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="functionLink">読み取られるユーザー定義関数へのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReadUserDefinedFunctionAsync (Uri functionUri, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReadUserDefinedFunctionAsync(class System.Uri functionUri, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadUserDefinedFunctionAsync(System.Uri,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadUserDefinedFunctionAsync (functionUri As Uri, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member ReadUserDefinedFunctionAsync : Uri * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.ReadUserDefinedFunctionAsync (functionUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="functionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="functionUri">読み取られるユーザー定義関数リソースへの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            読み取り、 <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserDefinedFunctionFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReadUserDefinedFunctionFeedAsync (string collectionLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReadUserDefinedFunctionFeedAsync(string collectionLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadUserDefinedFunctionFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadUserDefinedFunctionFeedAsync (collectionLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member ReadUserDefinedFunctionFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.ReadUserDefinedFunctionFeedAsync (collectionLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">親ドキュメント コレクション リソースのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />この要求します。</param>
        <summary>
            フィード (シーケンス) を読み取ります<see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />Cosmos DB の Azure サービスで、非同期操作として、コレクションにします。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserDefinedFunctionFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReadUserDefinedFunctionFeedAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReadUserDefinedFunctionFeedAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadUserDefinedFunctionFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadUserDefinedFunctionFeedAsync (documentCollectionUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member ReadUserDefinedFunctionFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.ReadUserDefinedFunctionFeedAsync (documentCollectionUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">親ドキュメント コレクションの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、コレクションのユーザー定義関数のフィード (シーケンス) を読み取ります。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; ReadUserFeedAsync (string databaseLink, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; ReadUserFeedAsync(string databaseLink, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadUserFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadUserFeedAsync (databaseLink As String, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of User))" />
      <MemberSignature Language="F#" Value="abstract member ReadUserFeedAsync : string * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.ReadUserFeedAsync (databaseLink, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">親データベースのリソースのリンク。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />この要求します。</param>
        <summary>
            フィード (シーケンス) を読み取ります<see cref="T:Microsoft.Azure.Documents.User" />Cosmos DB の Azure サービス内の非同期操作としてデータベースにします。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.User" />読み取りリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserFeedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; ReadUserFeedAsync (Uri databaseUri, Microsoft.Azure.Documents.Client.FeedOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; ReadUserFeedAsync(class System.Uri databaseUri, class Microsoft.Azure.Documents.Client.FeedOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReadUserFeedAsync(System.Uri,Microsoft.Azure.Documents.Client.FeedOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadUserFeedAsync (databaseUri As Uri, Optional options As FeedOptions = null) As Task(Of FeedResponse(Of User))" />
      <MemberSignature Language="F#" Value="abstract member ReadUserFeedAsync : Uri * Microsoft.Azure.Documents.Client.FeedOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.ReadUserFeedAsync (databaseUri, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">親データベースの URI。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、データベースのユーザーのフィード (シーケンス) を読み取ります。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; ReplaceAttachmentAsync (Microsoft.Azure.Documents.Attachment attachment, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; ReplaceAttachmentAsync(class Microsoft.Azure.Documents.Attachment attachment, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceAttachmentAsync(Microsoft.Azure.Documents.Attachment,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceAttachmentAsync : Microsoft.Azure.Documents.Attachment * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.ReplaceAttachmentAsync (attachment, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="attachment" Type="Microsoft.Azure.Documents.Attachment" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="attachment">更新された<see cref="T:Microsoft.Azure.Documents.Attachment" />を持つ既存のリソースを置き換えます。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            置換、 <see cref="T:Microsoft.Azure.Documents.Attachment" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Attachment" />更新済みのリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; ReplaceAttachmentAsync (Uri attachmentUri, Microsoft.Azure.Documents.Attachment attachment, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; ReplaceAttachmentAsync(class System.Uri attachmentUri, class Microsoft.Azure.Documents.Attachment attachment, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceAttachmentAsync(System.Uri,Microsoft.Azure.Documents.Attachment,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceAttachmentAsync : Uri * Microsoft.Azure.Documents.Attachment * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.ReplaceAttachmentAsync (attachmentUri, attachment, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="attachmentUri" Type="System.Uri" />
        <Parameter Name="attachment" Type="Microsoft.Azure.Documents.Attachment" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="attachmentUri">更新する添付ファイルの URI。</param>
        <param name="attachment">添付ファイル リソースです。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として添付ファイルを置き換えます。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; ReplaceDocumentAsync (Microsoft.Azure.Documents.Document document, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; ReplaceDocumentAsync(class Microsoft.Azure.Documents.Document document, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceDocumentAsync(Microsoft.Azure.Documents.Document,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceDocumentAsync : Microsoft.Azure.Documents.Document * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.ReplaceDocumentAsync (document, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="Microsoft.Azure.Documents.Document" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="document">更新された<see cref="T:Microsoft.Azure.Documents.Document" />を持つ既存のリソースを置き換えます。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            置換、 <see cref="T:Microsoft.Azure.Documents.Document" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Document" />更新済みのリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; ReplaceDocumentAsync (string documentLink, object document, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; ReplaceDocumentAsync(string documentLink, object document, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceDocumentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReplaceDocumentAsync (documentLink As String, document As Object, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member ReplaceDocumentAsync : string * obj * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.ReplaceDocumentAsync (documentLink, document, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="document" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">更新するドキュメントのリンク。 例:  db/db_rid/colls/col_rid/docs/doc_rid/ </param>
        <param name="document">更新された<see cref="T:Microsoft.Azure.Documents.Document" />を持つ既存のリソースを置き換えます。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            置換、 <see cref="T:Microsoft.Azure.Documents.Document" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Document" />更新済みのリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; ReplaceDocumentAsync (Uri documentUri, object document, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; ReplaceDocumentAsync(class System.Uri documentUri, object document, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceDocumentAsync(System.Uri,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReplaceDocumentAsync (documentUri As Uri, document As Object, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member ReplaceDocumentAsync : Uri * obj * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.ReplaceDocumentAsync (documentUri, document, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="document" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">更新するドキュメントの URI。</param>
        <param name="document">更新されたドキュメントです。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、ドキュメントを置き換えます。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceDocumentCollectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReplaceDocumentCollectionAsync (Microsoft.Azure.Documents.DocumentCollection documentCollection, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReplaceDocumentCollectionAsync(class Microsoft.Azure.Documents.DocumentCollection documentCollection, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceDocumentCollectionAsync(Microsoft.Azure.Documents.DocumentCollection,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceDocumentCollectionAsync : Microsoft.Azure.Documents.DocumentCollection * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.ReplaceDocumentCollectionAsync (documentCollection, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollection" Type="Microsoft.Azure.Documents.DocumentCollection" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollection">更新されたドキュメントのコレクションです。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、ドキュメントのコレクションを置換します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceDocumentCollectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReplaceDocumentCollectionAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.DocumentCollection documentCollection, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.DocumentCollection&gt;&gt; ReplaceDocumentCollectionAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.DocumentCollection documentCollection, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceDocumentCollectionAsync(System.Uri,Microsoft.Azure.Documents.DocumentCollection,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceDocumentCollectionAsync : Uri * Microsoft.Azure.Documents.DocumentCollection * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;" Usage="iDocumentClient.ReplaceDocumentCollectionAsync (documentCollectionUri, documentCollection, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.DocumentCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="documentCollection" Type="Microsoft.Azure.Documents.DocumentCollection" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">更新するドキュメントのコレクションの URI。</param>
        <param name="documentCollection">更新されたドキュメントのコレクションです。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、ドキュメントのコレクションを置換します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceOfferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt; ReplaceOfferAsync (Microsoft.Azure.Documents.Offer offer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Offer&gt;&gt; ReplaceOfferAsync(class Microsoft.Azure.Documents.Offer offer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceOfferAsync(Microsoft.Azure.Documents.Offer)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceOfferAsync : Microsoft.Azure.Documents.Offer -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt;" Usage="iDocumentClient.ReplaceOfferAsync offer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Offer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="offer" Type="Microsoft.Azure.Documents.Offer" />
      </Parameters>
      <Docs>
        <param name="offer">更新された<see cref="T:Microsoft.Azure.Documents.Offer" />を持つ既存のリソースを置き換えます。</param>
        <summary>
            置換、 <see cref="T:Microsoft.Azure.Documents.Offer" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Offer" />更新済みのリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplacePermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; ReplacePermissionAsync (Microsoft.Azure.Documents.Permission permission, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; ReplacePermissionAsync(class Microsoft.Azure.Documents.Permission permission, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplacePermissionAsync(Microsoft.Azure.Documents.Permission,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplacePermissionAsync : Microsoft.Azure.Documents.Permission * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.ReplacePermissionAsync (permission, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permission" Type="Microsoft.Azure.Documents.Permission" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="permission">更新された<see cref="T:Microsoft.Azure.Documents.Permission" />を持つ既存のリソースを置き換えます。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            置換、 <see cref="T:Microsoft.Azure.Documents.Permission" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Permission" />更新済みのリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplacePermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; ReplacePermissionAsync (Uri permissionUri, Microsoft.Azure.Documents.Permission permission, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; ReplacePermissionAsync(class System.Uri permissionUri, class Microsoft.Azure.Documents.Permission permission, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplacePermissionAsync(System.Uri,Microsoft.Azure.Documents.Permission,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplacePermissionAsync : Uri * Microsoft.Azure.Documents.Permission * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.ReplacePermissionAsync (permissionUri, permission, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissionUri" Type="System.Uri" />
        <Parameter Name="permission" Type="Microsoft.Azure.Documents.Permission" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="permissionUri">更新する権限の URI。</param>
        <param name="permission">更新されたアクセス許可。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作とアクセス許可を置き換えます。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReplaceStoredProcedureAsync (Microsoft.Azure.Documents.StoredProcedure storedProcedure, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReplaceStoredProcedureAsync(class Microsoft.Azure.Documents.StoredProcedure storedProcedure, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceStoredProcedureAsync(Microsoft.Azure.Documents.StoredProcedure,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceStoredProcedureAsync : Microsoft.Azure.Documents.StoredProcedure * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.ReplaceStoredProcedureAsync (storedProcedure, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storedProcedure" Type="Microsoft.Azure.Documents.StoredProcedure" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="storedProcedure">更新された<see cref="T:Microsoft.Azure.Documents.StoredProcedure" />を持つ既存のリソースを置き換えます。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            置換、 <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.StoredProcedure" />更新済みのリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReplaceStoredProcedureAsync (Uri storedProcedureUri, Microsoft.Azure.Documents.StoredProcedure storedProcedure, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; ReplaceStoredProcedureAsync(class System.Uri storedProcedureUri, class Microsoft.Azure.Documents.StoredProcedure storedProcedure, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceStoredProcedureAsync(System.Uri,Microsoft.Azure.Documents.StoredProcedure,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceStoredProcedureAsync : Uri * Microsoft.Azure.Documents.StoredProcedure * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.ReplaceStoredProcedureAsync (storedProcedureUri, storedProcedure, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storedProcedureUri" Type="System.Uri" />
        <Parameter Name="storedProcedure" Type="Microsoft.Azure.Documents.StoredProcedure" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="storedProcedureUri">更新するストアド プロシージャの URI。</param>
        <param name="storedProcedure">更新されたストアド プロシージャです。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Cosmos DB の Azure サービス内の指定のストアド プロシージャを置き換えます。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; ReplaceTriggerAsync (Microsoft.Azure.Documents.Trigger trigger, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; ReplaceTriggerAsync(class Microsoft.Azure.Documents.Trigger trigger, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceTriggerAsync(Microsoft.Azure.Documents.Trigger,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceTriggerAsync : Microsoft.Azure.Documents.Trigger * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.ReplaceTriggerAsync (trigger, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trigger" Type="Microsoft.Azure.Documents.Trigger" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="trigger">更新された<see cref="T:Microsoft.Azure.Documents.Trigger" />を持つ既存のリソースを置き換えます。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            置換、 <see cref="T:Microsoft.Azure.Documents.Trigger" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.Trigger" />更新済みのリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; ReplaceTriggerAsync (Uri triggerUri, Microsoft.Azure.Documents.Trigger trigger, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; ReplaceTriggerAsync(class System.Uri triggerUri, class Microsoft.Azure.Documents.Trigger trigger, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceTriggerAsync(System.Uri,Microsoft.Azure.Documents.Trigger,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceTriggerAsync : Uri * Microsoft.Azure.Documents.Trigger * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.ReplaceTriggerAsync (triggerUri, trigger, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="triggerUri" Type="System.Uri" />
        <Parameter Name="trigger" Type="Microsoft.Azure.Documents.Trigger" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="triggerUri">更新するトリガーの URI。</param>
        <param name="trigger">更新されたトリガーです。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、トリガーを置換します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; ReplaceUserAsync (Microsoft.Azure.Documents.User user, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; ReplaceUserAsync(class Microsoft.Azure.Documents.User user, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceUserAsync(Microsoft.Azure.Documents.User,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceUserAsync : Microsoft.Azure.Documents.User * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.ReplaceUserAsync (user, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="user" Type="Microsoft.Azure.Documents.User" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="user">更新された<see cref="T:Microsoft.Azure.Documents.User" />を持つ既存のリソースを置き換えます。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            置換、 <see cref="T:Microsoft.Azure.Documents.User" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.User" />更新済みのリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; ReplaceUserAsync (Uri userUri, Microsoft.Azure.Documents.User user, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; ReplaceUserAsync(class System.Uri userUri, class Microsoft.Azure.Documents.User user, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceUserAsync(System.Uri,Microsoft.Azure.Documents.User,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceUserAsync : Uri * Microsoft.Azure.Documents.User * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.ReplaceUserAsync (userUri, user, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="user" Type="Microsoft.Azure.Documents.User" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">更新するユーザーの URI。</param>
        <param name="user">更新されたユーザー。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として、ユーザーに置換します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReplaceUserDefinedFunctionAsync (Microsoft.Azure.Documents.UserDefinedFunction function, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReplaceUserDefinedFunctionAsync(class Microsoft.Azure.Documents.UserDefinedFunction function, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceUserDefinedFunctionAsync(Microsoft.Azure.Documents.UserDefinedFunction,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReplaceUserDefinedFunctionAsync (function As UserDefinedFunction, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member ReplaceUserDefinedFunctionAsync : Microsoft.Azure.Documents.UserDefinedFunction * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.ReplaceUserDefinedFunctionAsync (function, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="function" Type="Microsoft.Azure.Documents.UserDefinedFunction" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="function">更新された<see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />を持つ既存のリソースを置き換えます。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            置換、 <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            A<see cref="N:System.Threading.Tasks" />を含む、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />ラップ、<see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />更新済みのリソース レコードを含むです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReplaceUserDefinedFunctionAsync (Uri userDefinedFunctionUri, Microsoft.Azure.Documents.UserDefinedFunction function, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; ReplaceUserDefinedFunctionAsync(class System.Uri userDefinedFunctionUri, class Microsoft.Azure.Documents.UserDefinedFunction function, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.ReplaceUserDefinedFunctionAsync(System.Uri,Microsoft.Azure.Documents.UserDefinedFunction,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReplaceUserDefinedFunctionAsync (userDefinedFunctionUri As Uri, function As UserDefinedFunction, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member ReplaceUserDefinedFunctionAsync : Uri * Microsoft.Azure.Documents.UserDefinedFunction * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.ReplaceUserDefinedFunctionAsync (userDefinedFunctionUri, function, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userDefinedFunctionUri" Type="System.Uri" />
        <Parameter Name="function" Type="Microsoft.Azure.Documents.UserDefinedFunction" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userDefinedFunctionUri">ユーザーの URI は、更新する関数を定義します。</param>
        <param name="function">更新されたユーザー定義関数です。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            ユーザーが置換では、Azure Cosmos DB サービスの非同期操作として関数が定義されます。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceEndpoint">
      <MemberSignature Language="C#" Value="public Uri ServiceEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IDocumentClient.ServiceEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceEndpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceEndpoint : Uri" Usage="Microsoft.Azure.Documents.IDocumentClient.ServiceEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure Cosmos DB サービスのサービス エンドポイントのエンドポイントの Uri を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Session">
      <MemberSignature Language="C#" Value="public object Session { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Session" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IDocumentClient.Session" />
      <MemberSignature Language="VB.NET" Value="Public Property Session As Object" />
      <MemberSignature Language="F#" Value="member this.Session : obj with get, set" Usage="Microsoft.Azure.Documents.IDocumentClient.Session" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、セッション整合性バージョンの Azure Cosmos DB サービスの追跡に使用されるセッション オブジェクトを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMediaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt; UpdateMediaAsync (string mediaLink, System.IO.Stream mediaStream, Microsoft.Azure.Documents.Client.MediaOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.MediaResponse&gt; UpdateMediaAsync(string mediaLink, class System.IO.Stream mediaStream, class Microsoft.Azure.Documents.Client.MediaOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpdateMediaAsync(System.String,System.IO.Stream,Microsoft.Azure.Documents.Client.MediaOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateMediaAsync (mediaLink As String, mediaStream As Stream, Optional options As MediaOptions = null) As Task(Of MediaResponse)" />
      <MemberSignature Language="F#" Value="abstract member UpdateMediaAsync : string * System.IO.Stream * Microsoft.Azure.Documents.Client.MediaOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt;" Usage="iDocumentClient.UpdateMediaAsync (mediaLink, mediaStream, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.MediaResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mediaLink" Type="System.String" />
        <Parameter Name="mediaStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.MediaOptions" />
      </Parameters>
      <Docs>
        <param name="mediaLink">更新するメディアをリンクします。 メディア/media_rid </param>
        <param name="mediaStream"><see cref="T:System.IO.Stream" />添付ファイルのメディアのです。</param>
        <param name="options">要求の <see cref="T:Microsoft.Azure.Documents.Client.MediaOptions" />。</param>
        <summary>
            Azure Cosmos DB サービスの非同期操作として指定されたメディアのコンテンツを置き換えます。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">いずれか<paramref name="mediaLink" />または<paramref name="mediaStream" />が設定されていません。</exception>
        <exception cref="T:System.ArgumentException">場合<paramref name="mediaLink" />/medias/{mediaId} の形式ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="UpsertAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; UpsertAttachmentAsync (string documentLink, object attachment, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; UpsertAttachmentAsync(string documentLink, object attachment, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertAttachmentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpsertAttachmentAsync (documentLink As String, attachment As Object, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member UpsertAttachmentAsync : string * obj * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.UpsertAttachmentAsync (documentLink, attachment, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="attachment" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">この新しい添付ファイルの親ドキュメントのリンク。 例:  db/db_rid/colls/col_rid/docs/doc_rid/ </param>
        <param name="attachment">添付ファイルのオブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            アップサート Cosmos DB の Azure サービス内の非同期操作として添付されます。
            </summary>
        <returns>
            <see cref="T:System.Threading.Tasks.Task" />サービス応答の非同期操作を表すオブジェクト。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; UpsertAttachmentAsync (Uri documentUri, object attachment, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; UpsertAttachmentAsync(class System.Uri documentUri, object attachment, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertAttachmentAsync(System.Uri,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpsertAttachmentAsync (documentUri As Uri, attachment As Object, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of Attachment))" />
      <MemberSignature Language="F#" Value="abstract member UpsertAttachmentAsync : Uri * obj * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.UpsertAttachmentAsync (documentUri, attachment, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="attachment" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">添付ファイルをアップサートするドキュメントの URI。</param>
        <param name="attachment"><see cref="T:Microsoft.Azure.Documents.Attachment" /> オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            アップサート Cosmos DB の Azure サービス内の非同期操作として添付されます。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; UpsertAttachmentAsync (string documentLink, System.IO.Stream mediaStream, Microsoft.Azure.Documents.Client.MediaOptions options = null, Microsoft.Azure.Documents.Client.RequestOptions requestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; UpsertAttachmentAsync(string documentLink, class System.IO.Stream mediaStream, class Microsoft.Azure.Documents.Client.MediaOptions options, class Microsoft.Azure.Documents.Client.RequestOptions requestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertAttachmentAsync(System.String,System.IO.Stream,Microsoft.Azure.Documents.Client.MediaOptions,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertAttachmentAsync : string * System.IO.Stream * Microsoft.Azure.Documents.Client.MediaOptions * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.UpsertAttachmentAsync (documentLink, mediaStream, options, requestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentLink" Type="System.String" />
        <Parameter Name="mediaStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.MediaOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentLink">この新しい添付ファイルの親ドキュメントのリンク。 例:  db/db_rid/colls/col_rid/docs/doc_rid/ </param>
        <param name="mediaStream"><see cref="T:System.IO.Stream" />添付ファイルのメディアのです。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.MediaOptions" />要求します。</param>
        <param name="requestOptions">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            アップサート、指定された内容と添付ファイル<paramref name="mediaStream" />Cosmos DB の Azure サービス内の非同期操作として。
            </summary>
        <returns>
            <see cref="T:System.Threading.Tasks.Task" />サービス応答の非同期操作を表すオブジェクト。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertAttachmentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt; UpsertAttachmentAsync (Uri documentUri, System.IO.Stream mediaStream, Microsoft.Azure.Documents.Client.MediaOptions options = null, Microsoft.Azure.Documents.Client.RequestOptions requestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Attachment&gt;&gt; UpsertAttachmentAsync(class System.Uri documentUri, class System.IO.Stream mediaStream, class Microsoft.Azure.Documents.Client.MediaOptions options, class Microsoft.Azure.Documents.Client.RequestOptions requestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertAttachmentAsync(System.Uri,System.IO.Stream,Microsoft.Azure.Documents.Client.MediaOptions,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertAttachmentAsync : Uri * System.IO.Stream * Microsoft.Azure.Documents.Client.MediaOptions * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;" Usage="iDocumentClient.UpsertAttachmentAsync (documentUri, mediaStream, options, requestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Attachment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentUri" Type="System.Uri" />
        <Parameter Name="mediaStream" Type="System.IO.Stream" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.MediaOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentUri">添付ファイルをアップサートするドキュメントの URI。</param>
        <param name="mediaStream">添付ファイルのメディアのストリーム。</param>
        <param name="options">要求の <see cref="T:Microsoft.Azure.Documents.Client.MediaOptions" />。</param>
        <param name="requestOptions">要求の <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />。</param>
        <summary>
            アップサート Cosmos DB の Azure サービス内の非同期操作として添付されます。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; UpsertDocumentAsync (string collectionLink, object document, Microsoft.Azure.Documents.Client.RequestOptions options = null, bool disableAutomaticIdGeneration = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; UpsertDocumentAsync(string collectionLink, object document, class Microsoft.Azure.Documents.Client.RequestOptions options, bool disableAutomaticIdGeneration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertDocumentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpsertDocumentAsync (collectionLink As String, document As Object, Optional options As RequestOptions = null, Optional disableAutomaticIdGeneration As Boolean = false) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member UpsertDocumentAsync : string * obj * Microsoft.Azure.Documents.Client.RequestOptions * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.UpsertDocumentAsync (collectionLink, document, options, disableAutomaticIdGeneration)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="document" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
        <Parameter Name="disableAutomaticIdGeneration" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="collectionLink">リンク、<see cref="T:Microsoft.Azure.Documents.DocumentCollection" />ドキュメントの upsert にします。 例:  db db_rid/colls/coll_rid/ </param>
        <param name="document">アップサートするドキュメント オブジェクト。</param>
        <param name="options">(省略可能)要求オプションを設定します。 例:  ドキュメントを作成するときに実行するトリガーを指定します。 <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /></param>
        <param name="disableAutomaticIdGeneration">(省略可能)これが True、システムの場合は、自動 id の生成を無効に id プロパティがドキュメントにない場合、例外がスローされます。</param>
        <summary>
            アップサート Cosmos DB の Azure サービス内の非同期操作としてドキュメント。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Documents.Document" />ことが upserted 内に含まれる、<see cref="T:System.Threading.Tasks.Task" />サービス応答の非同期操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertDocumentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt; UpsertDocumentAsync (Uri documentCollectionUri, object document, Microsoft.Azure.Documents.Client.RequestOptions options = null, bool disableAutomaticIdGeneration = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Document&gt;&gt; UpsertDocumentAsync(class System.Uri documentCollectionUri, object document, class Microsoft.Azure.Documents.Client.RequestOptions options, bool disableAutomaticIdGeneration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertDocumentAsync(System.Uri,System.Object,Microsoft.Azure.Documents.Client.RequestOptions,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpsertDocumentAsync (documentCollectionUri As Uri, document As Object, Optional options As RequestOptions = null, Optional disableAutomaticIdGeneration As Boolean = false) As Task(Of ResourceResponse(Of Document))" />
      <MemberSignature Language="F#" Value="abstract member UpsertDocumentAsync : Uri * obj * Microsoft.Azure.Documents.Client.RequestOptions * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;" Usage="iDocumentClient.UpsertDocumentAsync (documentCollectionUri, document, options, disableAutomaticIdGeneration)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="document" Type="System.Object" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
        <Parameter Name="disableAutomaticIdGeneration" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">ドキュメントの upsert をドキュメントのコレクションの URI にします。</param>
        <param name="document">ドキュメント オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <param name="disableAutomaticIdGeneration">自動 id の生成を無効にするフラグです。</param>
        <summary>
            アップサート Cosmos DB の Azure サービス内の非同期操作としてドキュメント。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertPermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; UpsertPermissionAsync (string userLink, Microsoft.Azure.Documents.Permission permission, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; UpsertPermissionAsync(string userLink, class Microsoft.Azure.Documents.Permission permission, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertPermissionAsync(System.String,Microsoft.Azure.Documents.Permission,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertPermissionAsync : string * Microsoft.Azure.Documents.Permission * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.UpsertPermissionAsync (userLink, permission, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userLink" Type="System.String" />
        <Parameter Name="permission" Type="Microsoft.Azure.Documents.Permission" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userLink">アップサート、アクセスを許可するユーザーのリンク用です。 例:  db db_rid/ユーザー/user_rid/ </param>
        <param name="permission"><see cref="T:Microsoft.Azure.Documents.Permission" /> オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            アップサート Cosmos DB の Azure サービス内の非同期操作として、ユーザー オブジェクトに対する権限。
            </summary>
        <returns>タスクを表すオブジェクトをサービス応答の非同期操作を含む、upserted<see cref="T:Microsoft.Azure.Documents.Permission" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertPermissionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt; UpsertPermissionAsync (Uri userUri, Microsoft.Azure.Documents.Permission permission, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Permission&gt;&gt; UpsertPermissionAsync(class System.Uri userUri, class Microsoft.Azure.Documents.Permission permission, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertPermissionAsync(System.Uri,Microsoft.Azure.Documents.Permission,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertPermissionAsync : Uri * Microsoft.Azure.Documents.Permission * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;" Usage="iDocumentClient.UpsertPermissionAsync (userUri, permission, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Permission&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userUri" Type="System.Uri" />
        <Parameter Name="permission" Type="Microsoft.Azure.Documents.Permission" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="userUri">アップサート、アクセス許可をユーザーの URI にします。</param>
        <param name="permission"><see cref="T:Microsoft.Azure.Documents.Permission" /> オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            アップサート Cosmos DB の Azure サービス内の非同期操作としてアクセスを許可します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; UpsertStoredProcedureAsync (string collectionLink, Microsoft.Azure.Documents.StoredProcedure storedProcedure, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; UpsertStoredProcedureAsync(string collectionLink, class Microsoft.Azure.Documents.StoredProcedure storedProcedure, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertStoredProcedureAsync(System.String,Microsoft.Azure.Documents.StoredProcedure,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertStoredProcedureAsync : string * Microsoft.Azure.Documents.StoredProcedure * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.UpsertStoredProcedureAsync (collectionLink, storedProcedure, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="storedProcedure" Type="Microsoft.Azure.Documents.StoredProcedure" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">Upsert ストアド プロシージャをコレクションのリンクにします。 例:  db db_rid/colls/col_rid/</param>
        <param name="storedProcedure"><see cref="T:Microsoft.Azure.Documents.StoredProcedure" />アップサートするオブジェクト。</param>
        <param name="options">(省略可能)どの<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            アップサート Cosmos DB の Azure サービス内の非同期操作としてストアド プロシージャです。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Documents.StoredProcedure" />ことが upserted 内に含まれる、<see cref="T:System.Threading.Tasks.Task" />サービス応答の非同期操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertStoredProcedureAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt; UpsertStoredProcedureAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.StoredProcedure storedProcedure, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.StoredProcedure&gt;&gt; UpsertStoredProcedureAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.StoredProcedure storedProcedure, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertStoredProcedureAsync(System.Uri,Microsoft.Azure.Documents.StoredProcedure,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertStoredProcedureAsync : Uri * Microsoft.Azure.Documents.StoredProcedure * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;" Usage="iDocumentClient.UpsertStoredProcedureAsync (documentCollectionUri, storedProcedure, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.StoredProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="storedProcedure" Type="Microsoft.Azure.Documents.StoredProcedure" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Upsert ストアド プロシージャにドキュメント コレクションの URI にします。</param>
        <param name="storedProcedure"><see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            アップサート Cosmos DB の Azure サービス内の非同期操作としてストアド プロシージャです。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; UpsertTriggerAsync (string collectionLink, Microsoft.Azure.Documents.Trigger trigger, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; UpsertTriggerAsync(string collectionLink, class Microsoft.Azure.Documents.Trigger trigger, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertTriggerAsync(System.String,Microsoft.Azure.Documents.Trigger,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertTriggerAsync : string * Microsoft.Azure.Documents.Trigger * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.UpsertTriggerAsync (collectionLink, trigger, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="trigger" Type="Microsoft.Azure.Documents.Trigger" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">リンク、 <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> upsert トリガーにします。 例:  db db_rid/colls/col_rid/ </param>
        <param name="trigger"><see cref="T:Microsoft.Azure.Documents.Trigger" />アップサートするオブジェクト。</param>
        <param name="options">(省略可能)どの<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            アップサート Cosmos DB の Azure サービス内の非同期操作としてトリガーします。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertTriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt; UpsertTriggerAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.Trigger trigger, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.Trigger&gt;&gt; UpsertTriggerAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.Trigger trigger, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertTriggerAsync(System.Uri,Microsoft.Azure.Documents.Trigger,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertTriggerAsync : Uri * Microsoft.Azure.Documents.Trigger * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;" Usage="iDocumentClient.UpsertTriggerAsync (documentCollectionUri, trigger, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.Trigger&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="trigger" Type="Microsoft.Azure.Documents.Trigger" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">Upsert トリガーにドキュメント コレクションの URI にします。</param>
        <param name="trigger"><see cref="T:Microsoft.Azure.Documents.Trigger" /> オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            アップサート Cosmos DB の Azure サービス内の非同期操作としてトリガーします。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; UpsertUserAsync (string databaseLink, Microsoft.Azure.Documents.User user, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; UpsertUserAsync(string databaseLink, class Microsoft.Azure.Documents.User user, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertUserAsync(System.String,Microsoft.Azure.Documents.User,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertUserAsync : string * Microsoft.Azure.Documents.User * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.UpsertUserAsync (databaseLink, user, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseLink" Type="System.String" />
        <Parameter Name="user" Type="Microsoft.Azure.Documents.User" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseLink">アップサート、ユーザーにデータベースのリンクにします。 例:  db/db_rid/ </param>
        <param name="user"><see cref="T:Microsoft.Azure.Documents.User" />アップサートするオブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            アップサート Cosmos DB の Azure サービス内の非同期操作として、ユーザー オブジェクトに対する権限。
            </summary>
        <returns>タスクを表すオブジェクトをサービス応答の非同期操作を含む、upserted<see cref="T:Microsoft.Azure.Documents.User" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt; UpsertUserAsync (Uri databaseUri, Microsoft.Azure.Documents.User user, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.User&gt;&gt; UpsertUserAsync(class System.Uri databaseUri, class Microsoft.Azure.Documents.User user, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertUserAsync(System.Uri,Microsoft.Azure.Documents.User,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="F#" Value="abstract member UpsertUserAsync : Uri * Microsoft.Azure.Documents.User * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;" Usage="iDocumentClient.UpsertUserAsync (databaseUri, user, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseUri" Type="System.Uri" />
        <Parameter Name="user" Type="Microsoft.Azure.Documents.User" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="databaseUri">アップサート、ユーザーにデータベースの URI にします。</param>
        <param name="user"><see cref="T:Microsoft.Azure.Documents.User" /> オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            アップサート Cosmos DB の Azure サービス内の非同期操作としてユーザー。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; UpsertUserDefinedFunctionAsync (string collectionLink, Microsoft.Azure.Documents.UserDefinedFunction function, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; UpsertUserDefinedFunctionAsync(string collectionLink, class Microsoft.Azure.Documents.UserDefinedFunction function, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertUserDefinedFunctionAsync(System.String,Microsoft.Azure.Documents.UserDefinedFunction,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpsertUserDefinedFunctionAsync (collectionLink As String, function As UserDefinedFunction, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member UpsertUserDefinedFunctionAsync : string * Microsoft.Azure.Documents.UserDefinedFunction * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.UpsertUserDefinedFunctionAsync (collectionLink, function, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collectionLink" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Documents.UserDefinedFunction" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="collectionLink">リンク、 <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> upsert にユーザーが内の関数を定義します。 例:  db db_rid/colls/col_rid/ </param>
        <param name="function"><see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />アップサートするオブジェクト。</param>
        <param name="options">(省略可能)どの<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この要求します。</param>
        <summary>
            アップサート、ユーザーは、Azure Cosmos DB サービス内の非同期操作として関数を定義します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpsertUserDefinedFunctionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; UpsertUserDefinedFunctionAsync (Uri documentCollectionUri, Microsoft.Azure.Documents.UserDefinedFunction function, Microsoft.Azure.Documents.Client.RequestOptions options = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.ResourceResponse`1&lt;class Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt; UpsertUserDefinedFunctionAsync(class System.Uri documentCollectionUri, class Microsoft.Azure.Documents.UserDefinedFunction function, class Microsoft.Azure.Documents.Client.RequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IDocumentClient.UpsertUserDefinedFunctionAsync(System.Uri,Microsoft.Azure.Documents.UserDefinedFunction,Microsoft.Azure.Documents.Client.RequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpsertUserDefinedFunctionAsync (documentCollectionUri As Uri, function As UserDefinedFunction, Optional options As RequestOptions = null) As Task(Of ResourceResponse(Of UserDefinedFunction))" />
      <MemberSignature Language="F#" Value="abstract member UpsertUserDefinedFunctionAsync : Uri * Microsoft.Azure.Documents.UserDefinedFunction * Microsoft.Azure.Documents.Client.RequestOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;" Usage="iDocumentClient.UpsertUserDefinedFunctionAsync (documentCollectionUri, function, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.ResourceResponse&lt;Microsoft.Azure.Documents.UserDefinedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentCollectionUri" Type="System.Uri" />
        <Parameter Name="function" Type="Microsoft.Azure.Documents.UserDefinedFunction" />
        <Parameter Name="options" Type="Microsoft.Azure.Documents.Client.RequestOptions" />
      </Parameters>
      <Docs>
        <param name="documentCollectionUri">アップサート、ユーザーにドキュメント コレクションの URI には、内の関数が定義されています。</param>
        <param name="function"><see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> オブジェクト。</param>
        <param name="options">(省略可能)<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />要求します。</param>
        <summary>
            アップサート、ユーザーは、Azure Cosmos DB サービス内の非同期操作として関数を定義します。
            </summary>
        <returns>サービスの応答の非同期操作を表すタスク オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEndpoint">
      <MemberSignature Language="C#" Value="public Uri WriteEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri WriteEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IDocumentClient.WriteEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteEndpoint As Uri" />
      <MemberSignature Language="F#" Value="member this.WriteEndpoint : Uri" Usage="Microsoft.Azure.Documents.IDocumentClient.WriteEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在の書き込みエンドポイントが Azure Cosmos DB サービスの選択に基づいて可用性および基本設定を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>