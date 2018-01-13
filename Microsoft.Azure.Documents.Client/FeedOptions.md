<Type Name="FeedOptions" FullName="Microsoft.Azure.Documents.Client.FeedOptions">
  <TypeSignature Language="C#" Value="public sealed class FeedOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FeedOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.FeedOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FeedOptions" />
  <TypeSignature Language="F#" Value="type FeedOptions = class" />
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
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Cosmos DB の Azure サービス内のフィード メソッド (列挙操作) に関連付けられているオプションを指定します。
            </summary>
    <remarks>
            クエリと ReadFeed 実行を管理するために使用します。 FeedOptions を使用して、ページ サイズ (MaxItemCount) を設定できます。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FeedOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.FeedOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
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
      <Parameters />
      <Docs>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> Azure Cosmos DB サービスのクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableRUPerMinuteUsage">
      <MemberSignature Language="C#" Value="public bool DisableRUPerMinuteUsage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DisableRUPerMinuteUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.DisableRUPerMinuteUsage" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableRUPerMinuteUsage As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableRUPerMinuteUsage : bool with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.DisableRUPerMinuteUsage" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、 <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.DisableRUPerMinuteUsage" /> Azure Cosmos DB サービスの現在のクエリのオプションです。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            要求単位 (Ru) の有効/無効にする disableRUPerMinuteUsage が使用される/を regular Ru/秒プロビジョニングされている場合、クエリを処理する分単位の容量がなくなった。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableCrossPartitionQuery">
      <MemberSignature Language="C#" Value="public bool EnableCrossPartitionQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableCrossPartitionQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.EnableCrossPartitionQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableCrossPartitionQuery As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableCrossPartitionQuery : bool with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.EnableCrossPartitionQuery" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスのクエリを実行する 1 つ以上の要求を送信するユーザーが有効にするかどうかを示す値を設定します。 複数の要求は、クエリが 1 つのパーティション キー値にスコープでない場合に必要です。
            </summary>
        <value>
            オプションは、クロス パーティションのクエリの実行が有効である場合は true です。それ以外の場合は false です。
            </value>
        <remarks>
          <para>
            このオプションは、ドキュメントおよびドキュメントの添付ファイルに対するクエリにのみ適用されます。
            </para>
        </remarks>
        <example>
          <code language="c#"><![CDATA[
            // Enable cross partition query.
            var queryable = client.CreateDocumentQuery<Book>(
                collectionLink, new FeedOptions { EnableCrossPartitionQuery = true }).Where(b => b.Price > 1000);
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="EnableLowPrecisionOrderBy">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableLowPrecisionOrderBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableLowPrecisionOrderBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.EnableLowPrecisionOrderBy" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableLowPrecisionOrderBy As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableLowPrecisionOrderBy : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.EnableLowPrecisionOrderBy" />
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
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または低精度の順番によって Azure Cosmos DB サービスを有効にするオプションを設定します。
            </summary>
        <value>
            低精度の order by 句を有効にするオプションです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableScanInQuery">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableScanInQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableScanInQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.EnableScanInQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableScanInQuery As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableScanInQuery : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.EnableScanInQuery" />
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
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定をインデックスとして処理できませんでした。 クエリに対するスキャンを有効にするオプションが、Azure Cosmos DB サービスで要求されたパスで除外されました。
            </summary>
        <value>
            オプションは、クエリでのスキャンが有効である場合は true です。それ以外の場合は false です。
            </value>
        <remarks>To be added.</remarks>
        <example>
          <code language="c#"><![CDATA[
            // Enable scan when Range index is not specified.
            var queryable = client.CreateDocumentQuery<Book>(
                collectionLink, new FeedOptions { EnableScanInQuery = true }).Where(b => b.Price > 1000);
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferedItemCount">
      <MemberSignature Language="C#" Value="public int MaxBufferedItemCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferedItemCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.MaxBufferedItemCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferedItemCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferedItemCount : int with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.MaxBufferedItemCount" />
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
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            バッファー内の中にクライアント側のことができる項目の最大数を取得または設定は、Azure Cosmos DB サービスのクエリの実行を並列です。 正の値のプロパティの値は、設定された値をバッファー内の項目の数を制限します。 0 より小さい値に設定されている場合、システムは自動的にバッファーする項目の数を決定します。
            </summary>
        <value>
            並列クエリの実行中にバッファーに格納できる項目の最大数。
            </value>
        <remarks>
            これは推奨はのみであり、場合によっては心変わりすることはできません。
            </remarks>
        <example>
          <code language="c#"><![CDATA[
            var queryable = client.CreateDocumentQuery<Book>(collectionLink, new FeedOptions { 
            MaximumBufferSize = 10, MaxDegreeOfParallelism = 2 });
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="MaxDegreeOfParallelism">
      <MemberSignature Language="C#" Value="public int MaxDegreeOfParallelism { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.MaxDegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDegreeOfParallelism As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDegreeOfParallelism : int with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.MaxDegreeOfParallelism" />
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
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスでの並列クエリの実行中にクライアント側を実行する同時実行操作の数を設定します。 プロパティに正の値を設定すると、同時実行操作の数が設定された値に制限されます。 0 未満に設定すると、同時実行操作の数はシステムによって自動的に設定されます。
            </summary>
        <value>
            並列実行時の同時実行操作の最大数。 既定値は 0 です。
            </value>
        <remarks>To be added.</remarks>
        <example>
          <code language="c#"><![CDATA[
            var queryable = client.CreateDocumentQuery<Book>(collectionLink, new FeedOptions { 
            MaxDegreeOfParallelism = 5});
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="MaxItemCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxItemCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxItemCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.MaxItemCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxItemCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxItemCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.MaxItemCount" />
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
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービス内の列挙操作で返される項目の最大数を設定します。
            </summary>
        <value>
            列挙操作で返される項目の最大数。
            </value>
        <remarks>
            クエリの改ページを使用します。
            動的なページ サイズの '-1' 使用されます。
            </remarks>
        <example>
          <code language="c#"><![CDATA[
            // Fetch query results 10 at a time.
            using (var queryable = client.CreateDocumentQuery<Book>(collectionLink, new FeedOptions { MaxItemCount = 10 }))
            {
                while (queryable.HasResults)
                {
                    FeedResponse<Book> response = await queryable.ExecuteNext<Book>();
                }
            }
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.PartitionKey PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.PartitionKey PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As PartitionKey" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : Microsoft.Azure.Documents.PartitionKey with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" />
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
        <ReturnType>Microsoft.Azure.Documents.PartitionKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、 <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" /> Azure Cosmos DB サービスの現在の要求に対するです。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            ドキュメントまたはパーティション分割コレクションでのフィードの添付ファイルを読み取るときにパーティション分割キーが必要です。 具体的にはパーティション キーが必要: <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadDocumentFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />、<see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadAttachmentFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />と<see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadConflictFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />です。  
            ドキュメントのみを含むパーティションで、<see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" />結果が返されます。
                </para>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <altmember cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />
        <example>
            次の例は、フィードを使用して、パーティション分割コレクションで、ドキュメントを読み取る方法を示しています。<see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" />です。
            この例でコレクションを作成、 <see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" /> '国' のプロパティのすべてのドキュメントにします。
            <code language="c#"><![CDATA[
            await client.ReadDocumentFeedAsync(
                collection.SelfLink, 
                new RequestOptions { PartitionKey = new PartitionKey("USA") } );
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyRangeId">
      <MemberSignature Language="C#" Value="public string PartitionKeyRangeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyRangeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKeyRangeId" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKeyRangeId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyRangeId : string with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.PartitionKeyRangeId" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または現在の要求のパーティション キーの範囲の id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            ReadFeed 要求は、これを使用する特定の範囲の要求を転送できます。
            これは、一括エクスポートのシナリオが発生した場合に便利です。
            </para>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <example>
            次の例では、パーティション キーの範囲「20」をパーティション分割コレクションでのフィード、ドキュメントを読み取る方法を示します。
            <code language="c#"><![CDATA[
            await client.ReadDocumentFeedAsync(
                collection.SelfLink, 
                new RequestOptions { PartitionKeyRangeId = "20" } );
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="PopulateQueryMetrics">
      <MemberSignature Language="C#" Value="public bool PopulateQueryMetrics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool PopulateQueryMetrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.PopulateQueryMetrics" />
      <MemberSignature Language="VB.NET" Value="Public Property PopulateQueryMetrics As Boolean" />
      <MemberSignature Language="F#" Value="member this.PopulateQueryMetrics : bool with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.PopulateQueryMetrics" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             取得または設定、 <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PopulateQueryMetrics" /> Cosmos DB の Azure サービスでドキュメントのクエリ要求のオプションを要求します。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            PopulateQueryMetrics は、クエリ要求のドキュメントでクエリの実行に関連する作業のメトリックの有効化/無効化に使用されます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestContinuation">
      <MemberSignature Language="C#" Value="public string RequestContinuation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestContinuation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.RequestContinuation" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestContinuation As String" />
      <MemberSignature Language="F#" Value="member this.RequestContinuation : string with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.RequestContinuation" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスの継続トークンの要求を設定します。
            </summary>
        <value>
            要求の継続トークンです。
            </value>
        <remarks>To be added.</remarks>
        <example>
          <code language="c#"><![CDATA[
            // Resume query execution using the continuation from the previous query
            var queryable = client.CreateDocumentQuery<Book>(collectionLink, new FeedOptions { RequestContinuation = prevQuery.ResponseContinuation });
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="ResponseContinuationTokenLimitInKb">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ResponseContinuationTokenLimitInKb { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ResponseContinuationTokenLimitInKb" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.ResponseContinuationTokenLimitInKb" />
      <MemberSignature Language="VB.NET" Value="Public Property ResponseContinuationTokenLimitInKb As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ResponseContinuationTokenLimitInKb : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.ResponseContinuationTokenLimitInKb" />
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
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             取得または設定、 <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.ResponseContinuationTokenLimitInKb" /> Cosmos DB の Azure サービスでドキュメントのクエリ要求のオプションを要求します。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            ResponseContinuationTokenLimitInKb を使用して、クエリの応答からの継続トークンの長さを制限できます。 有効な値は&gt;0 を = です。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.FeedOptions.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string with get, set" Usage="Microsoft.Azure.Documents.Client.FeedOptions.SessionToken" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスのセッションの整合性を使用するためのセッション トークンを設定します。
            </summary>
        <value>
            セッションで使用するためのセッション トークンです。
            </value>
        <remarks>
            複数 Microsoft.Azure.Documents.Client.DocumentClient インスタンス間で負荷分散するアプリケーション向けに便利です。 これで大文字と小文字、ラウンドト リップをアプリケーションには、エンド ユーザーからのトークンと Azure Cosmos DB にできるように、サーバー間でセッションを保持できます。
            </remarks>
        <example>
          <code language="c#"><![CDATA[
            var queryable = client.CreateDocumentQuery<Book>(
                collectionLink, new FeedOptions { SessionToken = lastSessionToken });
            ]]></code>
        </example>
      </Docs>
    </Member>
  </Members>
</Type>