<Type Name="IPartitionResolver" FullName="Microsoft.Azure.Documents.Client.IPartitionResolver">
  <TypeSignature Language="C#" Value="public interface IPartitionResolver" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPartitionResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.IPartitionResolver" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPartitionResolver" />
  <TypeSignature Language="F#" Value="type IPartitionResolver = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
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
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for IPartitionResolver is now obsolete. It's recommended that you use partitioned collections for higher storage and throughput.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="8ffea-101">これは、データベースのパーティションのリゾルバーを表します。</span><span class="sxs-lookup"><span data-stu-id="8ffea-101">This represents a partition resolver for a database.</span></span> <span data-ttu-id="8ffea-102">パーティション キー、Azure Cosmos DB サービスのパーティション キーに一致するリンクのコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="8ffea-102">Given a partition key, return the collection link(s) matching the partition key in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
      <para>
            <span data-ttu-id="8ffea-103">IPartitionResolver のサポートは廃止されました。</span><span class="sxs-lookup"><span data-stu-id="8ffea-103">Support for IPartitionResolver is now obsolete.</span></span> <span data-ttu-id="8ffea-104">使用することをお勧め<a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">パーティション分割コレクション</a>の記憶域とスループットが向上します。</span><span class="sxs-lookup"><span data-stu-id="8ffea-104">It's recommended that you use <a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">Partitioned Collections</a> for higher storage and throughput.</span></span>
            </para>
      <para>
            <span data-ttu-id="8ffea-105">DocumentClient を使用すると、作成し、データベースごとに IPartitionResolvers 実装を登録できます。</span><span class="sxs-lookup"><span data-stu-id="8ffea-105">DocumentClient allows you to create and register IPartitionResolvers implementations for each database.</span></span> <span data-ttu-id="8ffea-106">登録されると、コレクションではなくデータベースに対して直接ドキュメントの操作を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="8ffea-106">Once registered, you can perform document operations directly against a database instead of a collection.</span></span> <span data-ttu-id="8ffea-107">IPartitionResolvers には、ExtractPartitionKey、ResolveForCreate および ResolveForRead 3 つのメソッドがあります。</span><span class="sxs-lookup"><span data-stu-id="8ffea-107">IPartitionResolvers has just three methods ExtractPartitionKey, ResolveForCreate and ResolveForRead.</span></span>
            </para>
      <para>
            <span data-ttu-id="8ffea-108">LINQ クエリと ReadFeed 反復子を使用して、ResolveForRead 内部的には、要求のパーティション キーに一致するすべてのコレクションを反復処理します。</span><span class="sxs-lookup"><span data-stu-id="8ffea-108">LINQ queries and ReadFeed iterators use the ResolveForRead internally to iterate over all the collections that match the partition key for the request.</span></span> <span data-ttu-id="8ffea-109">同様に、ルーティングする ResolveForCreate が右のパーティションに作成操作の使用を作成します。</span><span class="sxs-lookup"><span data-stu-id="8ffea-109">Similarly, create operations use the ResolveForCreate to route creates to the right partition.</span></span> <span data-ttu-id="8ffea-110">置換のために必要な変更はありません、削除およびドキュメントを保持するコレクションへの参照が格納されているドキュメントを使用するための読み取り。</span><span class="sxs-lookup"><span data-stu-id="8ffea-110">There are no changes required for Replace, Delete and Read since they use the Document, which already contains the reference to the collection that holds the document.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetPartitionKey">
      <MemberSignature Language="C#" Value="public object GetPartitionKey (object document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object GetPartitionKey(object document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.IPartitionResolver.GetPartitionKey(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionKey (document As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetPartitionKey : obj -&gt; obj" Usage="iPartitionResolver.GetPartitionKey document" />
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
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="document"><span data-ttu-id="8ffea-111">ドキュメント オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8ffea-111">A document object.</span></span></param>
        <summary>
            <span data-ttu-id="8ffea-112">Cosmos DB の Azure サービス内のドキュメントからパーティション キーを抽出します。</span><span class="sxs-lookup"><span data-stu-id="8ffea-112">Extracts the partition key from a document in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="8ffea-113">ドキュメントのパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="8ffea-113">The partition key for the document.</span></span></returns>
        <remarks>
            <span data-ttu-id="8ffea-114">一般的な実装は、ドキュメント (ユーザー ID など) から 1 つのプロパティの値を取得またはバージョン ID などの複合プロパティを抽出デバイス #) またはに基づいて、ドキュメントの種類の例: カスタム ロジックを実装して、ユーザーの id の値を抽出するが、userMessages の userId を抽出します。</span><span class="sxs-lookup"><span data-stu-id="8ffea-114">Typical implementations will get the value of a single property from the document (e.g., user ID) or extract a compound property, for e.g., version ID, device #) or implement custom logic based on the type of the document, for e.g., extract value of id for users but extract userId for userMessages.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveForCreate">
      <MemberSignature Language="C#" Value="public string ResolveForCreate (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string ResolveForCreate(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.IPartitionResolver.ResolveForCreate(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveForCreate (partitionKey As Object) As String" />
      <MemberSignature Language="F#" Value="abstract member ResolveForCreate : obj -&gt; string" Usage="iPartitionResolver.ResolveForCreate partitionKey" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="partitionKey"><span data-ttu-id="8ffea-115">評価対象を決定するために使用するパーティション キーのコレクションは、操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="8ffea-115">The partition key used to determine the target collection for create operations.</span></span></param>
        <summary>
            <span data-ttu-id="8ffea-116">パーティション キーを指定するには、このコレクションを返します Cosmos DB の Azure サービスでドキュメントを作成するための自己リンクします。</span><span class="sxs-lookup"><span data-stu-id="8ffea-116">Given a partition key, this returns the collection self-link for creating a document in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="8ffea-117">指定されたパーティション キーでドキュメントを作成するコレクションに対しては自己リンクは、します。</span><span class="sxs-lookup"><span data-stu-id="8ffea-117">A self-link for the collection to create documents in for the specified partition key.</span></span></returns>
        <remarks>
            <span data-ttu-id="8ffea-118">戻り値は、有効なコレクションの自己リンク文字列、書式 db/db_rid/colls/col_rid をする必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ffea-118">The return value must be a valid collection self-link string in the format dbs/db_rid/colls/col_rid.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveForRead">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;string&gt; ResolveForRead (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; ResolveForRead(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.IPartitionResolver.ResolveForRead(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveForRead (partitionKey As Object) As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="abstract member ResolveForRead : obj -&gt; seq&lt;string&gt;" Usage="iPartitionResolver.ResolveForRead partitionKey" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="partitionKey"><span data-ttu-id="8ffea-119">読み取り、つまり、クエリまたは読み取りフィードのターゲット コレクションを決定するために使用するパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="8ffea-119">The partition key used to determine the target collections for reads, i.e., query or read-feed.</span></span></param>
        <summary>
            <span data-ttu-id="8ffea-120">指定されたパーティション キーが返されます。 コレクションの一覧は、自己からの読み取りにリンクします。</span><span class="sxs-lookup"><span data-stu-id="8ffea-120">Given a partition key, this returns a list of collection self-links to read from.</span></span>
            </summary>
        <returns><span data-ttu-id="8ffea-121">指定されたパーティション キーの読み取り要求を実行するには、コレクションの自己リンクします。</span><span class="sxs-lookup"><span data-stu-id="8ffea-121">The self-links for the collections to perform read requests for the specified partition key.</span></span></returns>
        <remarks>
            <span data-ttu-id="8ffea-122">戻り値は、形式 db/db_rid/colls/col_rid 内のコレクションの自己リンクした文字列の IEnumerable をする必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ffea-122">The return value must be an IEnumerable of collection self-link strings in the format dbs/db_rid/colls/col_rid.</span></span>
            <span data-ttu-id="8ffea-123">異なり ResolveForCreate、これは 1: n 異なるコレクションに時間の経過と共に作成される 1 つのパーティション キーとして、または Azure Cosmos DB サービスのコレクションの間のパーティション キーのデータ移行を実行しているためです。</span><span class="sxs-lookup"><span data-stu-id="8ffea-123">Unlike ResolveForCreate, this is a 1:N as a single partition key might be created in different collections over time or because you are performing data migration of partition key between collections in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>