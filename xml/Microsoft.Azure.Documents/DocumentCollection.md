<Type Name="DocumentCollection" FullName="Microsoft.Azure.Documents.DocumentCollection">
  <TypeSignature Language="C#" Value="public class DocumentCollection : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DocumentCollection extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.DocumentCollection" />
  <TypeSignature Language="VB.NET" Value="Public Class DocumentCollection&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DocumentCollection = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
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
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f9ad8-101">Cosmos DB の Azure サービスでドキュメントのコレクションを表します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-101">Represents a document collection in the Azure Cosmos DB service.</span></span> <span data-ttu-id="f9ad8-102">コレクションは、ドキュメントの名前付きの論理コンテナーです。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-102">A collection is a named logical container for documents.</span></span> 
            </summary>
    <remarks>
            <span data-ttu-id="f9ad8-103">データベースは、0 個以上の名前付きコレクションを含めることがあり、0 個以上の JSON ドキュメントの各コレクションで構成されます。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-103">A database may contain zero or more named collections and each collection consists of zero or more JSON documents.</span></span> <span data-ttu-id="f9ad8-104">スキーマ フリーである同じ構造またはフィールドを共有するコレクション内のドキュメントは必要ありません。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-104">Being schema-free, the documents in a collection do not need to share the same structure or fields.</span></span> <span data-ttu-id="f9ad8-105">コレクションは、アプリケーションのリソースにあるため、承認できます、マスター _ キーまたはリソース キーを使用します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-105">Since collections are application resources, they can be authorized using either the master key or resource keys.</span></span>
            <span data-ttu-id="f9ad8-106">参照してください<see>http://azure.microsoft.com/documentation/articles/documentdb-resources/#collections</see>コレクションの詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-106">Refer to <see>http://azure.microsoft.com/documentation/articles/documentdb-resources/#collections</see> for more details on collections.</span></span>
            </remarks>
    <altmember cref="T:Microsoft.Azure.Documents.IndexingPolicy" />
    <altmember cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />
    <altmember cref="T:Microsoft.Azure.Documents.Document" />
    <altmember cref="T:Microsoft.Azure.Documents.Database" />
    <altmember cref="T:Microsoft.Azure.Documents.Offer" />
    <example>
            <span data-ttu-id="f9ad8-107">次の例では、50000 単位あたりの要求のスループットを新しいパーティションのコレクションを作成します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-107">The example below creates a new partitioned collection with 50000 Request-per-Unit throughput.</span></span>
            <span data-ttu-id="f9ad8-108">パーティション キーは、このコレクション内のすべてのドキュメントに最初のレベル '国' プロパティです。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-108">The partition key is the first level 'country' property in all the documents within this collection.</span></span>
            <code language="c#"><![CDATA[
            DocumentCollection collection = await client.CreateDocumentCollectionAsync(
                databaseLink,
                new DocumentCollection 
                { 
                    Id = "MyCollection",
                    PartitionKey = new PartitionKeyDefinition
                    {
                        Paths = new Collection<string> { "/country" }
                    }
                }, 
                new RequestOptions { OfferThroughput = 50000} ).Result;
            ]]></code></example>
    <example>
            <span data-ttu-id="f9ad8-109">次の例では、10000 に設定されて OfferThroughput を新しいコレクションを作成します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-109">The example below creates a new collection with OfferThroughput set to 10000.</span></span>
            <code language="c#"><![CDATA[
            DocumentCollection collection = await client.CreateDocumentCollectionAsync(
                databaseLink,
                new DocumentCollection { Id = "MyCollection" }, 
                new RequestOptions { OfferThroughput = 10000} ).Result;
            ]]></code></example>
    <example>
            <span data-ttu-id="f9ad8-110">次の例では、カスタム インデックス作成ポリシーを使用して新しいコレクションを作成します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-110">The example below creates a new collection with a custom indexing policy.</span></span>
            <code language="c#"><![CDATA[
            DocumentCollection collectionSpec = new DocumentCollection { Id ="MyCollection" };
            collectionSpec.IndexingPolicy.Automatic = true;
            collectionSpec.IndexingPolicy.IndexingMode = IndexingMode.Consistent;
            collection = await client.CreateDocumentCollectionAsync(database.SelfLink, collectionSpec);
            ]]></code></example>
    <example>
            <span data-ttu-id="f9ad8-111">次の例では、Book という種類のこのコレクション内のドキュメントを作成します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-111">The example below creates a document of type Book inside this collection.</span></span>
            <code language="c#"><![CDATA[
            Document doc = await client.CreateDocumentAsync(collection.SelfLink, new Book { Title = "War and Peace" });
            ]]></code></example>
    <example>
            <span data-ttu-id="f9ad8-112">クエリによって、SelfLink を取得する Id のデータベースの次の例です。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-112">The example below queries for a Database by Id to retrieve the SelfLink.</span></span>
            <code language="c#"><![CDATA[
            using Microsoft.Azure.Documents.Linq;
            DocumentCollection collection = client.CreateDocumentCollectionQuery(databaseLink).Where(c => c.Id == "myColl").AsEnumerable().FirstOrDefault();
            string collectionLink = collection.SelfLink;
            ]]></code></example>
    <example>
            <span data-ttu-id="f9ad8-113">次の例では、このコレクションを削除します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-113">The example below deletes this collection.</span></span>
            <code language="c#"><![CDATA[
            await client.DeleteDocumentCollectionAsync(collection.SelfLink);
            ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.DocumentCollection.#ctor" />
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
            <span data-ttu-id="f9ad8-114">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> Azure Cosmos DB サービスのクラスです。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-114">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConflictsLink">
      <MemberSignature Language="C#" Value="public string ConflictsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConflictsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.ConflictsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConflictsLink As String" />
      <MemberSignature Language="F#" Value="member this.ConflictsLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.ConflictsLink" />
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
            <span data-ttu-id="f9ad8-115">Azure Cosmos DB サービスからコレクション内の競合の自己リンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-115">Gets the self-link for conflicts in a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f9ad8-116">自己リンクのコレクション内の競合をします。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-116">The self-link for conflicts in a collection.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultTimeToLive">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DefaultTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DefaultTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultTimeToLive As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DefaultTimeToLive : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="defaultTtl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9ad8-117">Azure Cosmos DB サービスからコレクション内のドキュメントを秒単位で有効期限の既定の時間を取得します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-117">Gets the default time to live in seconds for documents in a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f9ad8-118">これは、省略可能なプロパティです。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-118">It is an optional property.</span></span>
            <span data-ttu-id="f9ad8-119">有効な値はどちらかは 0 以外。 正の整数である必要があります '-1'、または<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-119">A valid value must be either a nonzero positive integer, '-1', or <c>null</c>.</span></span>
            <span data-ttu-id="f9ad8-120">既定では、DefaultTimeToLive はコレクションの有効期限が無効になって null の意味に設定されます。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-120">By default, DefaultTimeToLive is set to null meaning the time to live is turned off for the collection.</span></span>
            <span data-ttu-id="f9ad8-121">測定単位は秒です。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-121">The unit of measurement is seconds.</span></span> <span data-ttu-id="f9ad8-122">最大値は 2147483647 です。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-122">The maximum allowed value is 2147483647.</span></span>
            </value>
        <remarks>
          <para>
            <span data-ttu-id="f9ad8-123"><see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />有効期間の既定のポリシーとして、コレクション内のすべてのドキュメントに適用されます。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-123">The <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> will be applied to all the documents in the collection as the default time-to-live policy.</span></span>
            <span data-ttu-id="f9ad8-124">個々 のドキュメントは設定して、既定の有効期限ポリシーを上書きする可能性があります、<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />です。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-124">The individual document could override the default time-to-live policy by setting its <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />.</span></span>
            </para>
          <para>
            <span data-ttu-id="f9ad8-125">ときに、<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />は<c>null</c>に期限が無効にするコレクション。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-125">When the <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> is <c>null</c>, the time-to-live will be turned off for the collection.</span></span>
            <span data-ttu-id="f9ad8-126">すべてのドキュメントが決して期限切れになります。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-126">It means all the documents will never expire.</span></span> <span data-ttu-id="f9ad8-127">個々 のドキュメントの<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />無視されます。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-127">The individual document's <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> will be disregarded.</span></span>
            </para>
          <para>
            <span data-ttu-id="f9ad8-128">ときに、 <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> '-1' に期限がオンにするコレクションのです。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-128">When the <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> is '-1', the time-to-live will be turned on for the collection.</span></span>
            <span data-ttu-id="f9ad8-129">既定では、すべてのドキュメントが決して期限切れです。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-129">By default, all the documents will never expire.</span></span> <span data-ttu-id="f9ad8-130">個々 のドキュメントことがある特定の有効期間の値を設定してその<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />です。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-130">The individual document could be given a specific time-to-live value by setting its <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />.</span></span> <span data-ttu-id="f9ad8-131">ドキュメントの<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />されますが、有効であるし、バック グラウンドで期限切れのドキュメントは削除されます。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-131">The document's <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> will be honored, and the expired documents will be deleted in background.</span></span>
            </para>
          <para>
            <span data-ttu-id="f9ad8-132">ときに、 <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> 0 以外の正の整数に期限がオンにするコレクションのです。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-132">When the <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> is a nonzero positive integer, the time-to-live will be turned on for the collection.</span></span>
            <span data-ttu-id="f9ad8-133">有効期限 (秒) で、既定値は、すべてのドキュメントに適用されます。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-133">And a default time-to-live in seconds will be applied to all the documents.</span></span> <span data-ttu-id="f9ad8-134">ドキュメントが期限切れで、指定した後<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />後、その最終書き込み時刻の秒の値。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-134">A document will be expired after the specified <see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" /> value in seconds since its last write time.</span></span>
            <span data-ttu-id="f9ad8-135">個々 のドキュメントは設定して、既定の有効期限ポリシーを上書きする可能性があります、<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />です。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-135">The individual document could override the default time-to-live policy by setting its <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />.</span></span>
            <span data-ttu-id="f9ad8-136">参照してください、<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />詳細については、ドキュメントの最終的な有効期間ポリシーを評価します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-136">Please refer to the <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> for more details about evaluating the final time-to-live policy of a document.</span></span>
            </para>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.Document" />
        <example>
            <span data-ttu-id="f9ad8-137">有効期間を無効にコレクションの次の例です。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-137">The example below disables time-to-live on a collection.</span></span>
            <code language="c#"><![CDATA[
                collection.DefaultTimeToLive = null;
            ]]></code></example>
        <example>
            <span data-ttu-id="f9ad8-138">次の例を有効にする-有効期限コレクション。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-138">The example below enables time-to-live on a collection.</span></span> <span data-ttu-id="f9ad8-139">既定では、すべてのドキュメント有効期限はありません。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-139">By default, all the documents never expire.</span></span>
            <code language="c#"><![CDATA[
                collection.DefaultTimeToLive = -1;
            ]]></code></example>
        <example>
            <span data-ttu-id="f9ad8-140">次の例を有効にする-有効期限コレクション。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-140">The example below enables time-to-live on a collection.</span></span> <span data-ttu-id="f9ad8-141">既定では、ドキュメントの有効期限 1000 秒後にその最終書き込み時刻以降。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-141">By default, the document will expire after 1000 seconds since its last write time.</span></span>
            <code language="c#"><![CDATA[
            collection.DefaultTimeToLive = 1000;
                ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="DocumentsLink">
      <MemberSignature Language="C#" Value="public string DocumentsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DocumentsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.DocumentsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DocumentsLink As String" />
      <MemberSignature Language="F#" Value="member this.DocumentsLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.DocumentsLink" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_docs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9ad8-142">Azure Cosmos DB サービスからコレクション内のドキュメントの自己リンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-142">Gets the self-link for documents in a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f9ad8-143">コレクション内のドキュメントについては自己リンクは、します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-143">The self-link for documents in a collection.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.IndexingPolicy IndexingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.IndexingPolicy IndexingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.IndexingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexingPolicy As IndexingPolicy" />
      <MemberSignature Language="F#" Value="member this.IndexingPolicy : Microsoft.Azure.Documents.IndexingPolicy with get, set" Usage="Microsoft.Azure.Documents.DocumentCollection.IndexingPolicy" />
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
        <ReturnType>Microsoft.Azure.Documents.IndexingPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9ad8-144">取得、 <see cref="P:Microsoft.Azure.Documents.DocumentCollection.IndexingPolicy" /> Cosmos DB の Azure サービスから、コレクションに関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-144">Gets the <see cref="P:Microsoft.Azure.Documents.DocumentCollection.IndexingPolicy" /> associated with the collection from the Azure Cosmos DB service.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="f9ad8-145">コレクションに関連付けられているインデックス作成ポリシー。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-145">The indexing policy associated with the collection.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.PartitionKeyDefinition PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.PartitionKeyDefinition PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As PartitionKeyDefinition" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : Microsoft.Azure.Documents.PartitionKeyDefinition with get, set" Usage="Microsoft.Azure.Documents.DocumentCollection.PartitionKey" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="partitionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.PartitionKeyDefinition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9ad8-146">取得または設定<see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" />Cosmos DB の Azure サービス内のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-146">Gets or sets <see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" /> object in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
          <span data-ttu-id="f9ad8-147"><see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-147"><see cref="T:Microsoft.Azure.Documents.PartitionKeyDefinition" /> object.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredProceduresLink">
      <MemberSignature Language="C#" Value="public string StoredProceduresLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoredProceduresLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.StoredProceduresLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredProceduresLink As String" />
      <MemberSignature Language="F#" Value="member this.StoredProceduresLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.StoredProceduresLink" />
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_sprocs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9ad8-148">Azure Cosmos DB サービスからコレクション内のストアド プロシージャの自己リンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-148">Gets the self-link for stored procedures in a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f9ad8-149">コレクション内のストアド プロシージャには自己リンクは、します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-149">The self-link for stored procedures in a collection.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggersLink">
      <MemberSignature Language="C#" Value="public string TriggersLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TriggersLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.TriggersLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TriggersLink As String" />
      <MemberSignature Language="F#" Value="member this.TriggersLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.TriggersLink" />
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
            <span data-ttu-id="f9ad8-150">Azure Cosmos DB サービスからコレクション内のトリガーの自己リンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-150">Gets the self-link for triggers in a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f9ad8-151">コレクション内のトリガーは自己リンクは、します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-151">The self-link for triggers in a collection.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UniqueKeyPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.UniqueKeyPolicy UniqueKeyPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.UniqueKeyPolicy UniqueKeyPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.UniqueKeyPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property UniqueKeyPolicy As UniqueKeyPolicy" />
      <MemberSignature Language="F#" Value="member this.UniqueKeyPolicy : Microsoft.Azure.Documents.UniqueKeyPolicy with get, set" Usage="Microsoft.Azure.Documents.DocumentCollection.UniqueKeyPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uniqueKeyPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.UniqueKeyPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f9ad8-152">取得または設定、 <see cref="P:Microsoft.Azure.Documents.DocumentCollection.UniqueKeyPolicy" /> Azure Cosmos DB サービスのコレクション内のドキュメントの一意性を保証します。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-152">Gets or sets the <see cref="P:Microsoft.Azure.Documents.DocumentCollection.UniqueKeyPolicy" /> that guarantee uniqueness of documents in collection in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserDefinedFunctionsLink">
      <MemberSignature Language="C#" Value="public string UserDefinedFunctionsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserDefinedFunctionsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DocumentCollection.UserDefinedFunctionsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserDefinedFunctionsLink As String" />
      <MemberSignature Language="F#" Value="member this.UserDefinedFunctionsLink : string" Usage="Microsoft.Azure.Documents.DocumentCollection.UserDefinedFunctionsLink" />
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
            <span data-ttu-id="f9ad8-153">ユーザーの自己リンクを取得には、Azure Cosmos DB サービスからコレクション内の関数が定義されています。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-153">Gets the self-link for user defined functions in a collection from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f9ad8-154">コレクションで関数を定義するユーザーの自己リンクします。</span><span class="sxs-lookup"><span data-stu-id="f9ad8-154">The self-link for user defined functions in a collection.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>