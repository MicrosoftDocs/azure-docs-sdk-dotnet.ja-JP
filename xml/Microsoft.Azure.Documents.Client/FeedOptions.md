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
            <span data-ttu-id="9ff83-101">Cosmos DB の Azure サービス内のフィード メソッド (列挙操作) に関連付けられているオプションを指定します。</span><span class="sxs-lookup"><span data-stu-id="9ff83-101">Specifies the options associated with feed methods (enumeration operations) in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="9ff83-102">クエリと ReadFeed 実行を管理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="9ff83-102">Used to manage query and ReadFeed execution.</span></span> <span data-ttu-id="9ff83-103">FeedOptions を使用して、ページ サイズ (MaxItemCount) を設定できます。</span><span class="sxs-lookup"><span data-stu-id="9ff83-103">Can use FeedOptions to set page size (MaxItemCount)</span></span>
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
            <span data-ttu-id="9ff83-104">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> Azure Cosmos DB サービスのクラスです。</span><span class="sxs-lookup"><span data-stu-id="9ff83-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" /> class for the Azure Cosmos DB service.</span></span>
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
            <span data-ttu-id="9ff83-105">取得または設定、 <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.DisableRUPerMinuteUsage" /> Azure Cosmos DB サービスの現在のクエリのオプションです。</span><span class="sxs-lookup"><span data-stu-id="9ff83-105">Gets or sets the <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.DisableRUPerMinuteUsage" /> option for the current query in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            <span data-ttu-id="9ff83-106">要求単位 (Ru) の有効/無効にする disableRUPerMinuteUsage が使用される/を regular Ru/秒プロビジョニングされている場合、クエリを処理する分単位の容量がなくなった。</span><span class="sxs-lookup"><span data-stu-id="9ff83-106">DisableRUPerMinuteUsage is used to enable/disable Request Units(RUs)/minute capacity to serve the query if regular provisioned RUs/second is exhausted.</span></span>
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
            <span data-ttu-id="9ff83-107">取得または Azure Cosmos DB サービスのクエリを実行する 1 つ以上の要求を送信するユーザーが有効にするかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="9ff83-107">Gets or sets a value indicating whether users are enabled to send more than one request to execute the query in the Azure Cosmos DB service.</span></span> <span data-ttu-id="9ff83-108">複数の要求は、クエリが 1 つのパーティション キー値にスコープでない場合に必要です。</span><span class="sxs-lookup"><span data-stu-id="9ff83-108">More than one request is necessary if the query is not scoped to single partition key value.</span></span>
            </summary>
        <value>
            <span data-ttu-id="9ff83-109">オプションは、クロス パーティションのクエリの実行が有効である場合は true です。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="9ff83-109">Option is true if cross-partition query execution is enabled; otherwise, false.</span></span>
            </value>
        <remarks>
          <para>
            <span data-ttu-id="9ff83-110">このオプションは、ドキュメントおよびドキュメントの添付ファイルに対するクエリにのみ適用されます。</span><span class="sxs-lookup"><span data-stu-id="9ff83-110">This option only applies to queries on documents and document attachments.</span></span>
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
            <span data-ttu-id="9ff83-111">取得または低精度の順番によって Azure Cosmos DB サービスを有効にするオプションを設定します。</span><span class="sxs-lookup"><span data-stu-id="9ff83-111">Gets or sets the option to enable low precision order by in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="9ff83-112">低精度の order by 句を有効にするオプションです。</span><span class="sxs-lookup"><span data-stu-id="9ff83-112">The option to enable low-precision order by.</span></span>
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
            <span data-ttu-id="9ff83-113">取得または設定をインデックスとして処理できませんでした。 クエリに対するスキャンを有効にするオプションが、Azure Cosmos DB サービスで要求されたパスで除外されました。</span><span class="sxs-lookup"><span data-stu-id="9ff83-113">Gets or sets the option to enable scans on the queries which couldn't be served as indexing was opted out on the requested paths in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="9ff83-114">オプションは、クエリでのスキャンが有効である場合は true です。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="9ff83-114">Option is true if scan on queries is enabled; otherwise, false.</span></span>
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
            <span data-ttu-id="9ff83-115">バッファー内の中にクライアント側のことができる項目の最大数を取得または設定は、Azure Cosmos DB サービスのクエリの実行を並列です。</span><span class="sxs-lookup"><span data-stu-id="9ff83-115">Gets or sets the maximum number of items that can be buffered client side during parallel query execution in the Azure Cosmos DB service.</span></span> <span data-ttu-id="9ff83-116">正の値のプロパティの値は、設定された値をバッファー内の項目の数を制限します。</span><span class="sxs-lookup"><span data-stu-id="9ff83-116">A positive property value limits the number of buffered items to the set value.</span></span> <span data-ttu-id="9ff83-117">0 より小さい値に設定されている場合、システムは自動的にバッファーする項目の数を決定します。</span><span class="sxs-lookup"><span data-stu-id="9ff83-117">If it is set to less than 0, the system automatically decides the number of items to buffer.</span></span>
            </summary>
        <value>
            <span data-ttu-id="9ff83-118">並列クエリの実行中にバッファーに格納できる項目の最大数。</span><span class="sxs-lookup"><span data-stu-id="9ff83-118">The maximum count of items that can be buffered during parallel query execution.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="9ff83-119">これは推奨はのみであり、場合によっては心変わりすることはできません。</span><span class="sxs-lookup"><span data-stu-id="9ff83-119">This is only suggestive and cannot be abided by in certain cases.</span></span>
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
            <span data-ttu-id="9ff83-120">取得または Azure Cosmos DB サービスでの並列クエリの実行中にクライアント側を実行する同時実行操作の数を設定します。</span><span class="sxs-lookup"><span data-stu-id="9ff83-120">Gets or sets the number of concurrent operations run client side during parallel query execution in the Azure Cosmos DB service.</span></span> <span data-ttu-id="9ff83-121">プロパティに正の値を設定すると、同時実行操作の数が設定された値に制限されます。</span><span class="sxs-lookup"><span data-stu-id="9ff83-121">A positive property value limits the number of concurrent operations to the set value.</span></span> <span data-ttu-id="9ff83-122">0 未満に設定すると、同時実行操作の数はシステムによって自動的に設定されます。</span><span class="sxs-lookup"><span data-stu-id="9ff83-122">If it is set to less than 0, the system automatically decides the number of concurrent operations to run.</span></span>
            </summary>
        <value>
            <span data-ttu-id="9ff83-123">並列実行時の同時実行操作の最大数。</span><span class="sxs-lookup"><span data-stu-id="9ff83-123">The maximum number of concurrent operations during parallel execution.</span></span> <span data-ttu-id="9ff83-124">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="9ff83-124">Defaults to 0.</span></span>
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
            <span data-ttu-id="9ff83-125">取得または Azure Cosmos DB サービス内の列挙操作で返される項目の最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="9ff83-125">Gets or sets the maximum number of items to be returned in the enumeration operation in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="9ff83-126">列挙操作で返される項目の最大数。</span><span class="sxs-lookup"><span data-stu-id="9ff83-126">The maximum number of items to be returned in the enumeration operation.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="9ff83-127">クエリの改ページを使用します。</span><span class="sxs-lookup"><span data-stu-id="9ff83-127">Used for query pagination.</span></span>
            <span data-ttu-id="9ff83-128">動的なページ サイズの '-1' 使用されます。</span><span class="sxs-lookup"><span data-stu-id="9ff83-128">'-1' Used for dynamic page size.</span></span>
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
            <span data-ttu-id="9ff83-129">取得または設定、 <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" /> Azure Cosmos DB サービスの現在の要求に対するです。</span><span class="sxs-lookup"><span data-stu-id="9ff83-129">Gets or sets the <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" /> for the current request in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="9ff83-130">ドキュメントまたはパーティション分割コレクションでのフィードの添付ファイルを読み取るときにパーティション分割キーが必要です。</span><span class="sxs-lookup"><span data-stu-id="9ff83-130">Partition key is required when read documents or attachments feed in a partitioned collection.</span></span> <span data-ttu-id="9ff83-131">具体的にはパーティション キーが必要: <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadDocumentFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />、<see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadAttachmentFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />と<see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadConflictFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />です。</span><span class="sxs-lookup"><span data-stu-id="9ff83-131">Specifically Partition key is required for : <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadDocumentFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />, <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadAttachmentFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" /> and <see cref="M:Microsoft.Azure.Documents.Client.DocumentClient.ReadConflictFeedAsync(System.String,Microsoft.Azure.Documents.Client.FeedOptions)" />.</span></span>  
            <span data-ttu-id="9ff83-132">ドキュメントのみを含むパーティションで、<see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" />結果が返されます。</span><span class="sxs-lookup"><span data-stu-id="9ff83-132">Only documents in partitions containing the <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" /> is returned in the result.</span></span>
                </para>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <altmember cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />
        <example>
            <span data-ttu-id="9ff83-133">次の例は、フィードを使用して、パーティション分割コレクションで、ドキュメントを読み取る方法を示しています。<see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" />です。</span><span class="sxs-lookup"><span data-stu-id="9ff83-133">The following example shows how to read a document feed in a partitioned collection using <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PartitionKey" />.</span></span>
            <span data-ttu-id="9ff83-134">この例でコレクションを作成、 <see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" /> '国' のプロパティのすべてのドキュメントにします。</span><span class="sxs-lookup"><span data-stu-id="9ff83-134">The example assumes the collection is created with a <see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" /> on the 'country' property in all the documents.</span></span>
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
            <span data-ttu-id="9ff83-135">取得または現在の要求のパーティション キーの範囲の id を設定します。</span><span class="sxs-lookup"><span data-stu-id="9ff83-135">Gets or sets the partition key range id for the current request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="9ff83-136">ReadFeed 要求は、これを使用する特定の範囲の要求を転送できます。</span><span class="sxs-lookup"><span data-stu-id="9ff83-136">ReadFeed requests can use this to forward request to specific range.</span></span>
            <span data-ttu-id="9ff83-137">これは、一括エクスポートのシナリオが発生した場合に便利です。</span><span class="sxs-lookup"><span data-stu-id="9ff83-137">This is usefull in case of bulk export scenarios.</span></span>
            </para>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <example>
            <span data-ttu-id="9ff83-138">次の例では、パーティション キーの範囲「20」をパーティション分割コレクションでのフィード、ドキュメントを読み取る方法を示します。</span><span class="sxs-lookup"><span data-stu-id="9ff83-138">The following example shows how to read a document feed in a partitioned collection from partition key range "20".</span></span>
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
             <span data-ttu-id="9ff83-139">取得または設定、 <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PopulateQueryMetrics" /> Cosmos DB の Azure サービスでドキュメントのクエリ要求のオプションを要求します。</span><span class="sxs-lookup"><span data-stu-id="9ff83-139">Gets or sets the <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.PopulateQueryMetrics" /> request option for document query requests in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            <span data-ttu-id="9ff83-140">PopulateQueryMetrics は、クエリ要求のドキュメントでクエリの実行に関連する作業のメトリックの有効化/無効化に使用されます。</span><span class="sxs-lookup"><span data-stu-id="9ff83-140">PopulateQueryMetrics is used to enable/disable getting metrics relating to query execution on document query requests.</span></span>
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
            <span data-ttu-id="9ff83-141">取得または Azure Cosmos DB サービスの継続トークンの要求を設定します。</span><span class="sxs-lookup"><span data-stu-id="9ff83-141">Gets or sets the request continuation token in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="9ff83-142">要求の継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="9ff83-142">The request continuation token.</span></span>
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
             <span data-ttu-id="9ff83-143">取得または設定、 <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.ResponseContinuationTokenLimitInKb" /> Cosmos DB の Azure サービスでドキュメントのクエリ要求のオプションを要求します。</span><span class="sxs-lookup"><span data-stu-id="9ff83-143">Gets or sets the <see cref="P:Microsoft.Azure.Documents.Client.FeedOptions.ResponseContinuationTokenLimitInKb" /> request option for document query requests in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para> 
            <span data-ttu-id="9ff83-144">ResponseContinuationTokenLimitInKb を使用して、クエリの応答からの継続トークンの長さを制限できます。</span><span class="sxs-lookup"><span data-stu-id="9ff83-144">ResponseContinuationTokenLimitInKb is used to limit the length of continuation token in the query response.</span></span> <span data-ttu-id="9ff83-145">有効な値は&gt;0 を = です。</span><span class="sxs-lookup"><span data-stu-id="9ff83-145">Valid values are &gt;= 0.</span></span>
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
            <span data-ttu-id="9ff83-146">取得または Azure Cosmos DB サービスのセッションの整合性を使用するためのセッション トークンを設定します。</span><span class="sxs-lookup"><span data-stu-id="9ff83-146">Gets or sets the session token for use with session consistency in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="9ff83-147">セッションで使用するためのセッション トークンです。</span><span class="sxs-lookup"><span data-stu-id="9ff83-147">The session token for use with session consistency.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="9ff83-148">複数 Microsoft.Azure.Documents.Client.DocumentClient インスタンス間で負荷分散するアプリケーション向けに便利です。</span><span class="sxs-lookup"><span data-stu-id="9ff83-148">Useful for applications that are load balanced across multiple Microsoft.Azure.Documents.Client.DocumentClient instances.</span></span> <span data-ttu-id="9ff83-149">これで大文字と小文字、ラウンドト リップをアプリケーションには、エンド ユーザーからのトークンと Azure Cosmos DB にできるように、サーバー間でセッションを保持できます。</span><span class="sxs-lookup"><span data-stu-id="9ff83-149">In this case, round-trip the token from end user to the application and then back to Azure Cosmos DB so that a session can be preserved across servers.</span></span>
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