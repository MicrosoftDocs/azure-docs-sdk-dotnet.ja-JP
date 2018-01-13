<Type Name="RequestOptions" FullName="Microsoft.Azure.Documents.Client.RequestOptions">
  <TypeSignature Language="C#" Value="public sealed class RequestOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RequestOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.RequestOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RequestOptions" />
  <TypeSignature Language="F#" Value="type RequestOptions = class" />
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
            Cosmos DB の Azure サービスに発行された別の要求に対して指定できるオプションをカプセル化します。
            </summary>
    <remarks>
            これらのオプションの一部は、特定の操作にのみ有効です。 たとえば、 <para>PreTriggerInclude を使用することができますのみで作成、置換、および delete 操作を<see cref="T:Microsoft.Azure.Documents.Document" />または<see cref="T:Microsoft.Azure.Documents.Attachment" />です。</para><para>ETag、中に、置換 * や Delete * 操作では有効ではありませんへの影響、読み取り*、CreateQuery*または作成 * 操作します。</para></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.RequestOptions.#ctor" />
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
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessCondition">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Client.AccessCondition AccessCondition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Client.AccessCondition AccessCondition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.AccessCondition" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessCondition As AccessCondition" />
      <MemberSignature Language="F#" Value="member this.AccessCondition : Microsoft.Azure.Documents.Client.AccessCondition with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.AccessCondition" />
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
        <ReturnType>Microsoft.Azure.Documents.Client.AccessCondition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスの要求に関連付けられた条件 (ETag) を設定します。
            </summary>
        <value>
            要求に関連付けられている条件 (ETag) です。
            </value>
        <remarks>
            Delete * および置換 * メソッドで最もよく使用される<see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />など<see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReplaceDocumentAsync(Microsoft.Azure.Documents.Document,Microsoft.Azure.Documents.Client.RequestOptions)" />または<see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReplaceDocumentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" />メソッドなど、他の方法で使用できますが、<see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadDocumentAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />キャッシュのシナリオです。 
            </remarks>
        <see cref="T:Microsoft.Azure.Documents.Client.AccessCondition" />
        <example>
            次の例で RequestOptions を使用する方法を示しています<see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReplaceDocumentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" />のセットを指定する<see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.AccessCondition" />ドキュメントを更新するときに使用するには。
            <code language="c#"><![CDATA[
            // If ETag is current, then this will succeed. Otherwise the request will fail with HTTP 412 Precondition Failure
            await client.ReplaceDocumentAsync(
            readCopyOfBook.SelfLink, 
                new Book { Title = "Moby Dick", Price = 14.99 },
                new RequestOptions 
                { 
                AccessCondition = new AccessCondition 
                    { 
                    Condition = readCopyOfBook.ETag, 
                        Type = AccessConditionType.IfMatch 
                        } 
                    });
                 ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="ConsistencyLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Documents.ConsistencyLevel&gt; ConsistencyLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Documents.ConsistencyLevel&gt; ConsistencyLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.ConsistencyLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsistencyLevel As Nullable(Of ConsistencyLevel)" />
      <MemberSignature Language="F#" Value="member this.ConsistencyLevel : Nullable&lt;Microsoft.Azure.Documents.ConsistencyLevel&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.ConsistencyLevel" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Documents.ConsistencyLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスの要求に必要な整合性レベルを設定します。
            </summary>
        <value>
            要求に必要な一貫性レベルです。
            </value>
        <remarks>
            Azure の Cosmos DB には、4 つの異なる整合性レベルが提供しています。 Strong、Bounded Staleness、セッション、および Eventual - 最も弱いに最も強力な一貫性の順序で。
            <para>これは、データベース アカウント レベルでは、設定中に、Azure Cosmos DB には、個々 の要求の既定の一貫性レベルを緩和する、開発者ができるようにします。</para></remarks>
        <altmember cref="P:Microsoft.Azure.Documents.Client.RequestOptions.ConsistencyLevel" />
        <example>
            この例では、RequestOptions を使用して、この 1 回の読み取り操作の一貫性レベル Eventual を下げます。 
            <code language="c#"><![CDATA[
            Document doc = client.ReadDocumentAsync(documentLink, new RequestOptions { ConsistencyLevel = ConsistencyLevel.Eventual });
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="DisableRUPerMinuteUsage">
      <MemberSignature Language="C#" Value="public bool DisableRUPerMinuteUsage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DisableRUPerMinuteUsage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.DisableRUPerMinuteUsage" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableRUPerMinuteUsage As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableRUPerMinuteUsage : bool with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.DisableRUPerMinuteUsage" />
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
             取得または設定、 <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.DisableRUPerMinuteUsage" /> Azure Cosmos DB サービスの現在の要求に対するです。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            要求ユニット (Ru) の有効/無効にする disableRUPerMinuteUsage が使用される/regular Ru/秒プロビジョニングされている場合、要求の処理に分単位の容量がなくなった。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableScriptLogging">
      <MemberSignature Language="C#" Value="public bool EnableScriptLogging { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableScriptLogging" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableScriptLogging As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableScriptLogging : bool with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" />
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
             取得または設定、 <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" /> Azure Cosmos DB サービスの現在の要求に対するです。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            JavaScript のストアド プロシージャでのログ記録を有効/無効にする EnableScriptLogging を使用します。
            既定のスクリプトでは、ログ記録が無効です。
            ログは、応答ヘッダー (x-ms-documentdb-script-log-results) にアクセスできることができます。
            </para>
        </remarks>
        <altmember cref="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.ScriptLog" />
        <example>
            次の例は、使用してストアド プロシージャでのログ記録を有効にする方法を示しています。<see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" />です。
            <code language="c#"><![CDATA[
            var response = await client.ExecuteStoredProcedureAsync(
                document.SelfLink,
                new RequestOptions { EnableScriptLogging = true } );
            Console.WriteLine(response.ScriptLog);
            ]]></code>ログインは、ストアド プロシージャで、次を使用します。<code language="JavaScript"><![CDATA[
            console.log("This is trace log");
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="IndexingDirective">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Documents.IndexingDirective&gt; IndexingDirective { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Documents.IndexingDirective&gt; IndexingDirective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.IndexingDirective" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexingDirective As Nullable(Of IndexingDirective)" />
      <MemberSignature Language="F#" Value="member this.IndexingDirective : Nullable&lt;Microsoft.Azure.Documents.IndexingDirective&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.IndexingDirective" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Documents.IndexingDirective&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスの要求のインデックス処理ディレクティブ (Include または Exclude) を設定します。
            </summary>
        <value>
            要求で使用するインデックス作成のディレクティブ。
            </value>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.IndexingPolicy" />
        <altmember cref="P:Microsoft.Azure.Documents.Client.RequestOptions.IndexingDirective" />
        <example>
            次の例では、どのように明示的にインデックス自動インデックス作成がコレクション内のドキュメントをオフを示します。
            <code language="c#"><![CDATA[
            client.CreateDocumentAsync(defaultCollection.SelfLink,
            new { id = "AndersenFamily", isRegistered = true },
                new RequestOptions { IndexingDirective = IndexingDirective.Include });
                ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="OfferEnableRUPerMinuteThroughput">
      <MemberSignature Language="C#" Value="public bool OfferEnableRUPerMinuteThroughput { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool OfferEnableRUPerMinuteThroughput" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.OfferEnableRUPerMinuteThroughput" />
      <MemberSignature Language="VB.NET" Value="Public Property OfferEnableRUPerMinuteThroughput As Boolean" />
      <MemberSignature Language="F#" Value="member this.OfferEnableRUPerMinuteThroughput : bool with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.OfferEnableRUPerMinuteThroughput" />
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
            取得または設定、 <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.OfferEnableRUPerMinuteThroughput" /> Azure Cosmos DB サービスのコレクション
            </summary>
        <value>
            要求ユニット (RU) を表す/分のスループットが有効/無効、Cosmos DB の Azure サービス内のコレクションにします。
            </value>
        <remarks>
            このオプションはドキュメントのコレクションを作成するときにのみ有効です。
            </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <altmember cref="T:Microsoft.Azure.Documents.OfferV2" />
        <example>
            次の例では、1 分あたりの RU スループット オファーのコレクションを作成する方法を示します。
            <code language="c#"><![CDATA[
            await client.CreateDocumentCollectionAsync(
                database.SelfLink, 
                new DocumentCollection { Id = "newcoll" }, 
                new RequestOptions { OfferThroughput = 4000, OfferEnableRUPerMinuteThroughput  = true });
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="OfferThroughput">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; OfferThroughput { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; OfferThroughput" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.OfferThroughput" />
      <MemberSignature Language="VB.NET" Value="Public Property OfferThroughput As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.OfferThroughput : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.OfferThroughput" />
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
            取得または設定では、Azure Cosmos DB サービスにおける要求単位の測定値のコレクション用にプロビジョニング オファー スループット。
            </summary>
        <value>
            このプランにプロビジョニングされたスループットです。
            </value>
        <remarks>
            このオプションはドキュメントのコレクションを作成するときにのみ有効です。
            <para>詳細についてはプロビジョニング オファーのスループットに http://azure.microsoft.com/documentation/articles/documentdb-performance-levels/ を参照してください。</para></remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <altmember cref="T:Microsoft.Azure.Documents.OfferV2" />
        <example>
            次の例では、オファーのスループットのコレクションを作成する方法を示します。
            <code language="c#"><![CDATA[
            await client.CreateDocumentCollectionAsync(
                database.SelfLink, 
                new DocumentCollection { Id = "newcoll" }, 
                new RequestOptions { OfferThroughput = 50000 });
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="OfferType">
      <MemberSignature Language="C#" Value="public string OfferType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OfferType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.OfferType" />
      <MemberSignature Language="VB.NET" Value="Public Property OfferType As String" />
      <MemberSignature Language="F#" Value="member this.OfferType : string with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.OfferType" />
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
            取得または Azure Cosmos DB サービスのリソースのオファーの種類を設定します。
            </summary>
        <value>
            オファーの種類の値です。
            </value>
        <remarks>
            このオプションはドキュメントのコレクションを作成するときにのみ有効です。
            <para>有効なオファーの種類の一覧については http://azure.microsoft.comdocumentation/articles/documentdb-performance-levels/ を参照してください。</para></remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <altmember cref="T:Microsoft.Azure.Documents.Offer" />
        <example>
            次の例では、S2 オファーのコレクションを作成する方法を示します。
            <code language="c#"><![CDATA[
            await client.CreateDocumentCollectionAsync(
                database.SelfLink, 
                new DocumentCollection { Id = "newcoll" }, 
                new RequestOptions { OfferType = "S2" });
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.PartitionKey PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.PartitionKey PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As PartitionKey" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : Microsoft.Azure.Documents.PartitionKey with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.PartitionKey" />
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
            取得または設定、 <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.PartitionKey" /> Azure Cosmos DB サービスの現在の要求に対するです。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            パーティション キーを使用して、この要求のターゲット パーティションの識別。  読み取り時に設定し、すべてのドキュメント要求; に対する削除操作を必要があります。作成、読み取り、更新および削除の各操作のすべてのドキュメントの添付ファイル要求です。ストアド producedures で操作を実行します。
            
            ドキュメントに対する操作を作成し、更新、パーティション キーはオプションです。  存在しない場合、クライアント ライブラリは、ドキュメントからパーティション キーをサーバーに要求を送信する前に抽出されます。
            </para>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <altmember cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />
        <example>
            次の例を使用して、パーティション分割コレクション内のドキュメントを読み取る方法を示しています。<see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.PartitionKey" />です。
            この例でコレクションを作成、<see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />すべてのドキュメント内の 'id' プロパティのです。
            <code language="c#"><![CDATA[
            await client.ReadDocumentAsync(
                document.SelfLink, 
                new RequestOptions { PartitionKey = new PartitionKey(document.Id) } );
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="PopulateQuotaInfo">
      <MemberSignature Language="C#" Value="public bool PopulateQuotaInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool PopulateQuotaInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.PopulateQuotaInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property PopulateQuotaInfo As Boolean" />
      <MemberSignature Language="F#" Value="member this.PopulateQuotaInfo : bool with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.PopulateQuotaInfo" />
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
             取得または設定、<see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.PopulateQuotaInfo" />ドキュメント コレクションを読み取る Cosmos DB の Azure サービスに要求します。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            PopulateQuotaInfo は取得中のドキュメント コレクションの有効/無効にするために使用クォータ関連ドキュメント コレクションの統計情報の読み取り要求。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PostTriggerInclude">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; PostTriggerInclude { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; PostTriggerInclude" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.PostTriggerInclude" />
      <MemberSignature Language="VB.NET" Value="Public Property PostTriggerInclude As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PostTriggerInclude : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.PostTriggerInclude" />
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
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスの操作の後に呼び出されるトリガーを設定します。
            </summary>
        <value>
            操作の完了後に起動されるトリガー。
            </value>
        <remarks>
            ドキュメントの作成、置換、削除の方法で使用する場合にのみ有効です。
            現在 1 つだけ PreTrigger は操作ごとに許可します。
            </remarks>
        <see cref="T:Microsoft.Azure.Documents.Trigger" />
        <example>
            次の例では、対象ドキュメントを永続化の後に実行 PostTrigger RequestOptions を使用する方法を示します。
            <code language="c#"><![CDATA[
            client.CreateDocumentAsync(collection.SelfLink, 
            new { id = "AndersenFamily", isRegistered = true },
            new RequestOptions { PostTriggerInclude = new List<string> { "updateMetadata" } });
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="PreTriggerInclude">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; PreTriggerInclude { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; PreTriggerInclude" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.PreTriggerInclude" />
      <MemberSignature Language="VB.NET" Value="Public Property PreTriggerInclude As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PreTriggerInclude : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.PreTriggerInclude" />
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
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスの操作の前に呼び出されるトリガーを設定します。
            </summary>
        <value> 
            操作の前に起動されるトリガー。
            </value>
        <remarks>
            ドキュメントの作成、置換、削除の方法で使用する場合にのみ有効です。
            現在 1 つだけ PreTrigger は操作ごとに許可します。
            </remarks>
        <see cref="T:Microsoft.Azure.Documents.Trigger" />
        <see cref="T:System.Collections.Generic.IList`1" />
        <example>
            次の例では、対象ドキュメントを保存する前に実行する PreTrigger RequestOptions を使用する方法を示します。
            <code language="c#"><![CDATA[
            client.CreateDocumentAsync(collection.SelfLink, 
                new { id = "AndersenFamily", isRegistered = true },
                new RequestOptions { PreTriggerInclude = new List<string> { "validateDocumentContents" } });
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="ResourceTokenExpirySeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ResourceTokenExpirySeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ResourceTokenExpirySeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.ResourceTokenExpirySeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceTokenExpirySeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ResourceTokenExpirySeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.ResourceTokenExpirySeconds" />
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
            取得またはリソース トークンの有効期限を設定します。 際に使用される Azure Cosmos DB サービスの作成/更新/読み取りアクセスを許可します。
            </summary>
        <value>
            リソース トークンを秒単位で有効期限です。
            </value>
        <remarks>
            Azure Cosmos DB ユーザーとアクセス許可のインスタンスをインスタンス化する方法を使用するときに<see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />を取得するには、<see cref="P:Microsoft.Azure.Documents.Permission.Token" />リソースの<see cref="T:Microsoft.Azure.Documents.User" />にアクセスし、この、authKeyOrResourceToken のパラメーターに渡す必要がある<see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />コンス トラクター<para>トークンの有効期限が切れる前に経過時間の長さを設定する ResourceTokenExpirySeconds の RequestOption を使用できますこのトークンを要求するときにします。この値を 10 秒、5 時間 (または 18,000 秒) に既定値は、これは、値の範囲なしこと指定は 1 時間 (3,600 秒)。</para></remarks>
        <altmember cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />
        <altmember cref="T:Microsoft.Azure.Documents.Permission" />
        <altmember cref="T:Microsoft.Azure.Documents.User" />
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RequestOptions.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string with get, set" Usage="Microsoft.Azure.Documents.Client.RequestOptions.SessionToken" />
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
             取得または Azure Cosmos DB サービス内のセッションの整合性に使用するためのトークンを設定します。
             </summary>
        <value>
             セッションで使用するためのトークンです。
             </value>
        <remarks>
             1 つ、 <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.ConsistencyLevel" /> Azure Cosmos DB は、セッションのです。 実際には、これは、アカウントに適用される deault レベルです。 
             <para>セッションの整合性を使用するときに、Azure Cosmos DB への新しい各書き込み要求には新しい SessionToken が割り当てられます。
             DocumentClient はこのトークンを使用して内部的に読み取り/クエリ要求ごとに整合性レベルの設定が維持されるようにします。
             
              <para>一部のシナリオでは、考えてください。 このセッションを管理する必要があります。たとえば web アプリケーションは、複数のノード、各ノードが、それぞれのインスタンスの<see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />場合に、同じセッションに参加するこれらのノード (できるように、独自の書き込み一貫して全体で読み取る web 層)、SessionToken を送信する必要があります<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />の後続の読み取りをクライアント層の 1 つのノード上の書き込みアクションの cookie またはその他の機構を使用しており、web 層にそのトークンのフロー。
             これは、Azure ロード バランサーなどの要求間でセッション アフィニティが維持されないラウンド ロビンのロード バランサーを使用している場合  
             読み取りでした可能性があります。 そこで別のノードで、書き込み要求をセッションが作成されました。 
             </para><para>前述のように、Azure Cosmos DB SessionToken 間をフローしない場合を終了して、読み取りの一貫性のない結果を時間の期間。</para></para></remarks>
        <altmember cref="P:Microsoft.Azure.Documents.Client.RequestOptions.ConsistencyLevel" />
        <example>
             この例から SessionToken を取得する方法、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />させの別のインスタンスを使用して<see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />内<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この例では、クライアントの各インスタンスが別の AppDomain 内のコードから実行されていること、など別のノードに複数のノードの web アプリケーションの場合
             <code language="c#"><![CDATA[
             string sessionToken;
             string docSelfLink;
             
             using (DocumentClient client = new DocumentClient(new Uri(""), ""))
            {
             ResourceResponse<Document> response = client.CreateDocumentAsync(collection.SelfLink, new { id = "an id", value = "some value" }).Result;
             sessionToken = response.SessionToken;
                 Document created = response.Resource;
                 docSelfLink = created.SelfLink;
                 }
                 
             using (DocumentClient client = new DocumentClient(new Uri(""), ""))
                {
             ResourceResponse<Document> read = client.ReadDocumentAsync(docSelfLink, new RequestOptions { SessionToken = sessionToken }).Result; 
             }
                 ]]></code></example>
      </Docs>
    </Member>
  </Members>
</Type>