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
            <span data-ttu-id="6228b-101">Cosmos DB の Azure サービスに発行された別の要求に対して指定できるオプションをカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="6228b-101">Encapsulates options that can be specified for different requests issued to the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="6228b-102">これらのオプションの一部は、特定の操作にのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="6228b-102">Some of these options are valid for specific operations only.</span></span> <span data-ttu-id="6228b-103">たとえば、 <para>PreTriggerInclude を使用することができますのみで作成、置換、および delete 操作を<see cref="T:Microsoft.Azure.Documents.Document" />または<see cref="T:Microsoft.Azure.Documents.Attachment" />です。</para><para>ETag、中に、置換 \* や Delete \* 操作では有効ではありませんへの影響、読み取り*、CreateQuery*または作成 \* 操作します。</para></span><span class="sxs-lookup"><span data-stu-id="6228b-103">For example, <para>PreTriggerInclude can be used only on create, replace and delete operations on a <see cref="T:Microsoft.Azure.Documents.Document" /> or <see cref="T:Microsoft.Azure.Documents.Attachment" />. </para><para>ETag, while valid on Replace\* and Delete\* operations, would have no impact on a Read*, CreateQuery* or Create\* operations.</para></span></span></remarks>
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
            <span data-ttu-id="6228b-104">取得または Azure Cosmos DB サービスの要求に関連付けられた条件 (ETag) を設定します。</span><span class="sxs-lookup"><span data-stu-id="6228b-104">Gets or sets the condition (ETag) associated with the request in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6228b-105">要求に関連付けられている条件 (ETag) です。</span><span class="sxs-lookup"><span data-stu-id="6228b-105">The condition (ETag) associated with the request.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6228b-106">Delete * および置換 * メソッドで最もよく使用される<see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />など<see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReplaceDocumentAsync(Microsoft.Azure.Documents.Document,Microsoft.Azure.Documents.Client.RequestOptions)" />または<see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReplaceDocumentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" />メソッドなど、他の方法で使用できますが、<see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadDocumentAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" />キャッシュのシナリオです。</span><span class="sxs-lookup"><span data-stu-id="6228b-106">Most commonly used with the Delete* and Replace* methods of <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> such as <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReplaceDocumentAsync(Microsoft.Azure.Documents.Document,Microsoft.Azure.Documents.Client.RequestOptions)" /> or <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReplaceDocumentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" /> methods, but can be used with other methods like <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadDocumentAsync(System.String,Microsoft.Azure.Documents.Client.RequestOptions)" /> for caching scenarios.</span></span> 
            </remarks>
        <see cref="T:Microsoft.Azure.Documents.Client.AccessCondition" />
        <example>
            <span data-ttu-id="6228b-107">次の例で RequestOptions を使用する方法を示しています<see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReplaceDocumentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" />のセットを指定する<see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.AccessCondition" />ドキュメントを更新するときに使用するには。</span><span class="sxs-lookup"><span data-stu-id="6228b-107">The following example shows how to use RequestOptions with <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReplaceDocumentAsync(System.String,System.Object,Microsoft.Azure.Documents.Client.RequestOptions)" /> to specify the set of <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.AccessCondition" /> to be used when updating a document</span></span>
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
            <span data-ttu-id="6228b-108">取得または Azure Cosmos DB サービスの要求に必要な整合性レベルを設定します。</span><span class="sxs-lookup"><span data-stu-id="6228b-108">Gets or sets the consistency level required for the request in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6228b-109">要求に必要な一貫性レベルです。</span><span class="sxs-lookup"><span data-stu-id="6228b-109">The consistency level required for the request.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6228b-110">Azure の Cosmos DB には、4 つの異なる整合性レベルが提供しています。</span><span class="sxs-lookup"><span data-stu-id="6228b-110">Azure Cosmos DB offers 4 different consistency levels.</span></span> <span data-ttu-id="6228b-111">Strong、Bounded Staleness、セッション、および Eventual - 最も弱いに最も強力な一貫性の順序で。</span><span class="sxs-lookup"><span data-stu-id="6228b-111">Strong, Bounded Staleness, Session and Eventual - in order of strongest to weakest consistency.</span></span>
            <span data-ttu-id="6228b-112"><para>これは、データベース アカウント レベルでは、設定中に、Azure Cosmos DB には、個々 の要求の既定の一貫性レベルを緩和する、開発者ができるようにします。</para></span><span class="sxs-lookup"><span data-stu-id="6228b-112"><para> While this is set at a database account level, Azure Cosmos DB allows a developer to weaken the default consistency level for each individual request. </para></span></span></remarks>
        <altmember cref="P:Microsoft.Azure.Documents.Client.RequestOptions.ConsistencyLevel" />
        <example>
            <span data-ttu-id="6228b-113">この例では、RequestOptions を使用して、この 1 回の読み取り操作の一貫性レベル Eventual を下げます。</span><span class="sxs-lookup"><span data-stu-id="6228b-113">This example uses RequestOptions to lower the consistency level to Eventual for this single Read operation.</span></span> 
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
             <span data-ttu-id="6228b-114">取得または設定、 <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.DisableRUPerMinuteUsage" /> Azure Cosmos DB サービスの現在の要求に対するです。</span><span class="sxs-lookup"><span data-stu-id="6228b-114">Gets or sets the <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.DisableRUPerMinuteUsage" /> for the current request in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            <span data-ttu-id="6228b-115">要求ユニット (Ru) の有効/無効にする disableRUPerMinuteUsage が使用される/regular Ru/秒プロビジョニングされている場合、要求の処理に分単位の容量がなくなった。</span><span class="sxs-lookup"><span data-stu-id="6228b-115">DisableRUPerMinuteUsage is used to enable/disable Request Units(RUs)/minute capacity to serve the request if regular provisioned RUs/second is exhausted.</span></span>
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
             <span data-ttu-id="6228b-116">取得または設定、 <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" /> Azure Cosmos DB サービスの現在の要求に対するです。</span><span class="sxs-lookup"><span data-stu-id="6228b-116">Gets or sets the <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" /> for the current request in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="6228b-117">JavaScript のストアド プロシージャでのログ記録を有効/無効にする EnableScriptLogging を使用します。</span><span class="sxs-lookup"><span data-stu-id="6228b-117">EnableScriptLogging is used to enable/disable logging in JavaScript stored procedures.</span></span>
            <span data-ttu-id="6228b-118">既定のスクリプトでは、ログ記録が無効です。</span><span class="sxs-lookup"><span data-stu-id="6228b-118">By default script logging is disabled.</span></span>
            <span data-ttu-id="6228b-119">ログは、応答ヘッダー (x-ms-documentdb-script-log-results) にアクセスできることができます。</span><span class="sxs-lookup"><span data-stu-id="6228b-119">The log can also be accessible in response header (x-ms-documentdb-script-log-results).</span></span>
            </para>
        </remarks>
        <altmember cref="P:Microsoft.Azure.Documents.Client.StoredProcedureResponse`1.ScriptLog" />
        <example>
            <span data-ttu-id="6228b-120">次の例は、使用してストアド プロシージャでのログ記録を有効にする方法を示しています。<see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" />です。</span><span class="sxs-lookup"><span data-stu-id="6228b-120">The following example shows how to enable logging in stored procedures using <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.EnableScriptLogging" />.</span></span>
            <span data-ttu-id="6228b-121"><code language="c#"><![CDATA[
            var response = await client.ExecuteStoredProcedureAsync(
                document.SelfLink,
                new RequestOptions { EnableScriptLogging = true } );
            Console.WriteLine(response.ScriptLog);
            ]]></code>ログインは、ストアド プロシージャで、次を使用します。<code language="JavaScript"><![CDATA[
            console.log("This is trace log");
            ]]></code></span><span class="sxs-lookup"><span data-stu-id="6228b-121"><code language="c#"><![CDATA[
            var response = await client.ExecuteStoredProcedureAsync(
            document.SelfLink,
new RequestOptions { EnableScriptLogging = true } );
Console.WriteLine(response.ScriptLog);
]]></code> To log, use the following in store procedure: <code language="JavaScript"><![CDATA[
console.log("This is trace log");
]]></code></span></span></example>
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
            <span data-ttu-id="6228b-122">取得または Azure Cosmos DB サービスの要求のインデックス処理ディレクティブ (Include または Exclude) を設定します。</span><span class="sxs-lookup"><span data-stu-id="6228b-122">Gets or sets the indexing directive (Include or Exclude) for the request in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6228b-123">要求で使用するインデックス作成のディレクティブ。</span><span class="sxs-lookup"><span data-stu-id="6228b-123">The indexing directive to use with a request.</span></span>
            </value>
        <remarks>To be added.</remarks>
        <altmember cref="T:Microsoft.Azure.Documents.IndexingPolicy" />
        <altmember cref="P:Microsoft.Azure.Documents.Client.RequestOptions.IndexingDirective" />
        <example>
            <span data-ttu-id="6228b-124">次の例では、どのように明示的にインデックス自動インデックス作成がコレクション内のドキュメントをオフを示します。</span><span class="sxs-lookup"><span data-stu-id="6228b-124">The following example shows how to explicitly index a document in a collection with automatic indexing turned off.</span></span>
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
            <span data-ttu-id="6228b-125">取得または設定、 <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.OfferEnableRUPerMinuteThroughput" /> Azure Cosmos DB サービスのコレクション</span><span class="sxs-lookup"><span data-stu-id="6228b-125">Gets or sets the <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.OfferEnableRUPerMinuteThroughput" /> for a collection in the Azure Cosmos DB service</span></span>
            </summary>
        <value>
            <span data-ttu-id="6228b-126">要求ユニット (RU) を表す/分のスループットが有効/無効、Cosmos DB の Azure サービス内のコレクションにします。</span><span class="sxs-lookup"><span data-stu-id="6228b-126">Represents Request Units(RU)/Minute throughput is enabled/disabled for a collection in the Azure Cosmos DB service.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6228b-127">このオプションはドキュメントのコレクションを作成するときにのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="6228b-127">This option is only valid when creating a document collection.</span></span>
            </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <altmember cref="T:Microsoft.Azure.Documents.OfferV2" />
        <example>
            <span data-ttu-id="6228b-128">次の例では、1 分あたりの RU スループット オファーのコレクションを作成する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="6228b-128">The followng example shows how to create a collection with RU/Minute throughput offer.</span></span>
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
            <span data-ttu-id="6228b-129">取得または設定では、Azure Cosmos DB サービスにおける要求単位の測定値のコレクション用にプロビジョニング オファー スループット。</span><span class="sxs-lookup"><span data-stu-id="6228b-129">Gets or sets the offer throughput provisioned for a collection in measurement of Requests-per-Unit in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6228b-130">このプランにプロビジョニングされたスループットです。</span><span class="sxs-lookup"><span data-stu-id="6228b-130">The provisioned throughtput for this offer.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6228b-131">このオプションはドキュメントのコレクションを作成するときにのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="6228b-131">This option is only valid when creating a document collection.</span></span>
            <span data-ttu-id="6228b-132"><para>詳細についてはプロビジョニング オファーのスループットに http://azure.microsoft.com/documentation/articles/documentdb-performance-levels/ を参照してください。</para></span><span class="sxs-lookup"><span data-stu-id="6228b-132"><para> Refer to http://azure.microsoft.com/documentation/articles/documentdb-performance-levels/ for details on provision offer throughput. </para></span></span></remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <altmember cref="T:Microsoft.Azure.Documents.OfferV2" />
        <example>
            <span data-ttu-id="6228b-133">次の例では、オファーのスループットのコレクションを作成する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="6228b-133">The followng example shows how to create a collection with offer throughtput.</span></span>
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
            <span data-ttu-id="6228b-134">取得または Azure Cosmos DB サービスのリソースのオファーの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="6228b-134">Gets or sets the offer type for the resource in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6228b-135">オファーの種類の値です。</span><span class="sxs-lookup"><span data-stu-id="6228b-135">The offer type value.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6228b-136">このオプションはドキュメントのコレクションを作成するときにのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="6228b-136">This option is only valid when creating a document collection.</span></span>
            <span data-ttu-id="6228b-137"><para>有効なオファーの種類の一覧については http://azure.microsoft.comdocumentation/articles/documentdb-performance-levels/ を参照してください。</para></span><span class="sxs-lookup"><span data-stu-id="6228b-137"><para> Refer to http://azure.microsoft.comdocumentation/articles/documentdb-performance-levels/ for the list of valid offer types. </para></span></span></remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <altmember cref="T:Microsoft.Azure.Documents.Offer" />
        <example>
            <span data-ttu-id="6228b-138">次の例では、S2 オファーのコレクションを作成する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="6228b-138">The followng example shows how to create a collection with the S2 offer.</span></span>
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
            <span data-ttu-id="6228b-139">取得または設定、 <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.PartitionKey" /> Azure Cosmos DB サービスの現在の要求に対するです。</span><span class="sxs-lookup"><span data-stu-id="6228b-139">Gets or sets the <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.PartitionKey" /> for the current request in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="6228b-140">パーティション キーを使用して、この要求のターゲット パーティションの識別。</span><span class="sxs-lookup"><span data-stu-id="6228b-140">Partition key is used to identify the target partition for this request.</span></span>  <span data-ttu-id="6228b-141">読み取り時に設定し、すべてのドキュメント要求; に対する削除操作を必要があります。作成、読み取り、更新および削除の各操作のすべてのドキュメントの添付ファイル要求です。ストアド producedures で操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="6228b-141">It must be set on read and delete operations for all document requests; create, read, update and delete operations for all document attachment requests; and execute operation on stored producedures.</span></span>
            
            <span data-ttu-id="6228b-142">ドキュメントに対する操作を作成し、更新、パーティション キーはオプションです。</span><span class="sxs-lookup"><span data-stu-id="6228b-142">For create and update operations on documents, the partition key is optional.</span></span>  <span data-ttu-id="6228b-143">存在しない場合、クライアント ライブラリは、ドキュメントからパーティション キーをサーバーに要求を送信する前に抽出されます。</span><span class="sxs-lookup"><span data-stu-id="6228b-143">When absent, the client library will extract the partition key from the document before sending the request to the server.</span></span>
            </para>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <altmember cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />
        <example>
            <span data-ttu-id="6228b-144">次の例を使用して、パーティション分割コレクション内のドキュメントを読み取る方法を示しています。<see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.PartitionKey" />です。</span><span class="sxs-lookup"><span data-stu-id="6228b-144">The following example shows how to read a document in a partitioned collection using <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.PartitionKey" />.</span></span>
            <span data-ttu-id="6228b-145">この例でコレクションを作成、<see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />すべてのドキュメント内の 'id' プロパティのです。</span><span class="sxs-lookup"><span data-stu-id="6228b-145">The example assumes the collection is created with a <see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" /> of the 'id' property in all the documents.</span></span>
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
             <span data-ttu-id="6228b-146">取得または設定、<see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.PopulateQuotaInfo" />ドキュメント コレクションを読み取る Cosmos DB の Azure サービスに要求します。</span><span class="sxs-lookup"><span data-stu-id="6228b-146">Gets or sets the <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.PopulateQuotaInfo" /> for document collection read requests in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            <span data-ttu-id="6228b-147">PopulateQuotaInfo は取得中のドキュメント コレクションの有効/無効にするために使用クォータ関連ドキュメント コレクションの統計情報の読み取り要求。</span><span class="sxs-lookup"><span data-stu-id="6228b-147">PopulateQuotaInfo is used to enable/disable getting document collection quota related stats for document collection read requests.</span></span>
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
            <span data-ttu-id="6228b-148">取得または Azure Cosmos DB サービスの操作の後に呼び出されるトリガーを設定します。</span><span class="sxs-lookup"><span data-stu-id="6228b-148">Gets or sets the trigger to be invoked after the operation in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6228b-149">操作の完了後に起動されるトリガー。</span><span class="sxs-lookup"><span data-stu-id="6228b-149">The trigger to be invoked after the operation.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6228b-150">ドキュメントの作成、置換、削除の方法で使用する場合にのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="6228b-150">Only valid when used with Create, Replace and Delete methods for documents.</span></span>
            <span data-ttu-id="6228b-151">現在 1 つだけ PreTrigger は操作ごとに許可します。</span><span class="sxs-lookup"><span data-stu-id="6228b-151">Currently only one PreTrigger is permitted per operation.</span></span>
            </remarks>
        <see cref="T:Microsoft.Azure.Documents.Trigger" />
        <example>
            <span data-ttu-id="6228b-152">次の例では、対象ドキュメントを永続化の後に実行 PostTrigger RequestOptions を使用する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="6228b-152">The following example shows how to use RequestOptions to include a PostTrigger to execute after persisting the document.</span></span>
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
            <span data-ttu-id="6228b-153">取得または Azure Cosmos DB サービスの操作の前に呼び出されるトリガーを設定します。</span><span class="sxs-lookup"><span data-stu-id="6228b-153">Gets or sets the trigger to be invoked before the operation in the Azure Cosmos DB service.</span></span>
            </summary>
        <value> 
            <span data-ttu-id="6228b-154">操作の前に起動されるトリガー。</span><span class="sxs-lookup"><span data-stu-id="6228b-154">The trigger to be invoked before the operation.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6228b-155">ドキュメントの作成、置換、削除の方法で使用する場合にのみ有効です。</span><span class="sxs-lookup"><span data-stu-id="6228b-155">Only valid when used with Create, Replace and Delete methods for documents.</span></span>
            <span data-ttu-id="6228b-156">現在 1 つだけ PreTrigger は操作ごとに許可します。</span><span class="sxs-lookup"><span data-stu-id="6228b-156">Currently only one PreTrigger is permitted per operation.</span></span>
            </remarks>
        <see cref="T:Microsoft.Azure.Documents.Trigger" />
        <see cref="T:System.Collections.Generic.IList`1" />
        <example>
            <span data-ttu-id="6228b-157">次の例では、対象ドキュメントを保存する前に実行する PreTrigger RequestOptions を使用する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="6228b-157">The following example shows how to use RequestOptions to include a PreTrigger to execute before persisting the document.</span></span>
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
            <span data-ttu-id="6228b-158">取得またはリソース トークンの有効期限を設定します。</span><span class="sxs-lookup"><span data-stu-id="6228b-158">Gets or sets the expiry time for resource token.</span></span> <span data-ttu-id="6228b-159">際に使用される Azure Cosmos DB サービスの作成/更新/読み取りアクセスを許可します。</span><span class="sxs-lookup"><span data-stu-id="6228b-159">Used when creating/updating/reading permissions in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="6228b-160">リソース トークンを秒単位で有効期限です。</span><span class="sxs-lookup"><span data-stu-id="6228b-160">The expiry time in seconds for the resource token.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="6228b-161">Azure Cosmos DB ユーザーとアクセス許可のインスタンスをインスタンス化する方法を使用するときに<see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />を取得するには、<see cref="P:Microsoft.Azure.Documents.Permission.Token" />リソースの<see cref="T:Microsoft.Azure.Documents.User" />にアクセスし、この、authKeyOrResourceToken のパラメーターに渡す必要がある<see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />コンス トラクター<para>トークンの有効期限が切れる前に経過時間の長さを設定する ResourceTokenExpirySeconds の RequestOption を使用できますこのトークンを要求するときにします。この値を 10 秒、5 時間 (または 18,000 秒) に既定値は、これは、値の範囲なしこと指定は 1 時間 (3,600 秒)。</para></span><span class="sxs-lookup"><span data-stu-id="6228b-161">When working with Azure Cosmos DB Users and Permissions, the way to instantiate an instance of <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> is to get the <see cref="P:Microsoft.Azure.Documents.Permission.Token" /> for the resource the <see cref="T:Microsoft.Azure.Documents.User" /> wants to access and pass this to the authKeyOrResourceToken parameter of <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> constructor <para> When requesting this Token, a RequestOption for ResourceTokenExpirySeconds can be used to set the length of time to elapse before the token expires. This value can range from 10 seconds, to 5 hours (or 18,000 seconds) The default value for this, should none be supplied is 1 hour (or 3,600 seconds). </para></span></span></remarks>
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
             <span data-ttu-id="6228b-162">取得または Azure Cosmos DB サービス内のセッションの整合性に使用するためのトークンを設定します。</span><span class="sxs-lookup"><span data-stu-id="6228b-162">Gets or sets the token for use with session consistency in the Azure Cosmos DB service.</span></span>
             </summary>
        <value>
             <span data-ttu-id="6228b-163">セッションで使用するためのトークンです。</span><span class="sxs-lookup"><span data-stu-id="6228b-163">The token for use with session consistency.</span></span>
             </value>
        <remarks>
             <span data-ttu-id="6228b-164">1 つ、 <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.ConsistencyLevel" /> Azure Cosmos DB は、セッションのです。</span><span class="sxs-lookup"><span data-stu-id="6228b-164">One of the <see cref="P:Microsoft.Azure.Documents.Client.RequestOptions.ConsistencyLevel" /> for Azure Cosmos DB is Session.</span></span> <span data-ttu-id="6228b-165">実際には、これは、アカウントに適用される deault レベルです。</span><span class="sxs-lookup"><span data-stu-id="6228b-165">In fact, this is the deault level applied to accounts.</span></span> 
             <span data-ttu-id="6228b-166"><para>セッションの整合性を使用するときに、Azure Cosmos DB への新しい各書き込み要求には新しい SessionToken が割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="6228b-166"><para> When working with Session consistency, each new write request to Azure Cosmos DB is assigned a new SessionToken.</span></span>
             <span data-ttu-id="6228b-167">DocumentClient はこのトークンを使用して内部的に読み取り/クエリ要求ごとに整合性レベルの設定が維持されるようにします。</span><span class="sxs-lookup"><span data-stu-id="6228b-167">The DocumentClient will use this token internally with each read/query request to ensure that the set consistency level is maintained.</span></span>
             
              <span data-ttu-id="6228b-168"><para>一部のシナリオでは、考えてください。 このセッションを管理する必要があります。たとえば web アプリケーションは、複数のノード、各ノードが、それぞれのインスタンスの<see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />場合に、同じセッションに参加するこれらのノード (できるように、独自の書き込み一貫して全体で読み取る web 層)、SessionToken を送信する必要があります<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />の後続の読み取りをクライアント層の 1 つのノード上の書き込みアクションの cookie またはその他の機構を使用しており、web 層にそのトークンのフロー。</span><span class="sxs-lookup"><span data-stu-id="6228b-168"><para> In some scenarios you need to manage this Session yourself; Consider a web application with multiple nodes, each node will have its own instance of <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> If you wanted these nodes to participate in the same session (to be able read your own writes consistently across web tiers) you would have to send the SessionToken from <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> of the write action on one node to the client tier, using a cookie or some other mechanism, and have that token flow back to the web tier for subsequent reads.</span></span>
             <span data-ttu-id="6228b-169">これは、Azure ロード バランサーなどの要求間でセッション アフィニティが維持されないラウンド ロビンのロード バランサーを使用している場合</span><span class="sxs-lookup"><span data-stu-id="6228b-169">If you are using a round-robin load balancer which does not maintain session affinity between requests, such as the Azure Load Balancer,</span></span>  
             <span data-ttu-id="6228b-170">読み取りでした可能性があります。 そこで別のノードで、書き込み要求をセッションが作成されました。</span><span class="sxs-lookup"><span data-stu-id="6228b-170">the read could potentially land on a different node to the write request, where the session was created.</span></span> 
             <span data-ttu-id="6228b-171"></para><para>前述のように、Azure Cosmos DB SessionToken 間をフローしない場合を終了して、読み取りの一貫性のない結果を時間の期間。</para></para></span><span class="sxs-lookup"><span data-stu-id="6228b-171"></para><para> If you do not flow the Azure Cosmos DB SessionToken across as described above you could end up with inconsistent read results for a period of time. </para></para></span></span></remarks>
        <altmember cref="P:Microsoft.Azure.Documents.Client.RequestOptions.ConsistencyLevel" />
        <example>
             <span data-ttu-id="6228b-172">この例から SessionToken を取得する方法、<see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" />させの別のインスタンスを使用して<see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />内<see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" />この例では、クライアントの各インスタンスが別の AppDomain 内のコードから実行されていること、など別のノードに複数のノードの web アプリケーションの場合</span><span class="sxs-lookup"><span data-stu-id="6228b-172">This example shows how you can retrieve the SessionToken from a <see cref="T:Microsoft.Azure.Documents.Client.ResourceResponse`1" /> and then use it on a different instance of <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> within <see cref="T:Microsoft.Azure.Documents.Client.RequestOptions" /> This example assumes that the each instance of the client is running from code within a different AppDomain, such as on different nodes in the case of multiple node web application</span></span>
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