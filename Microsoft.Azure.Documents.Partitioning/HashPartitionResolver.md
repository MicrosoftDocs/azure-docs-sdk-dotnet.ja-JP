<Type Name="HashPartitionResolver" FullName="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver">
  <TypeSignature Language="C#" Value="public class HashPartitionResolver : IDisposable, Microsoft.Azure.Documents.Client.IPartitionResolver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HashPartitionResolver extends System.Object implements class Microsoft.Azure.Documents.Client.IPartitionResolver, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" />
  <TypeSignature Language="VB.NET" Value="Public Class HashPartitionResolver&#xA;Implements IDisposable, IPartitionResolver" />
  <TypeSignature Language="F#" Value="type HashPartitionResolver = class&#xA;    interface IPartitionResolver&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IPartitionResolver</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for IPartitionResolver based classes is now obsolete. It's recommended that you use partitioned collections for higher storage and throughput.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="96781-101">HashPartitionResolver は、要求およびデータを Azure Cosmos DB サービスのパーティションの数の間で均等に分散することができます、ハッシュ関数の値に基づくパーティション分割を実装します。</span><span class="sxs-lookup"><span data-stu-id="96781-101">HashPartitionResolver implements partitioning based on the value of a hash function, allowing you to evenly distribute requests and data across a number of partitions in the Azure Cosmos DB service.</span></span> 
            </summary>
    <remarks>
      <para>
            <span data-ttu-id="96781-102">IPartitionResolver ベース クラスのサポートは廃止されました。</span><span class="sxs-lookup"><span data-stu-id="96781-102">Support for IPartitionResolver based classes is now obsolete.</span></span> <span data-ttu-id="96781-103">使用することをお勧め<a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">パーティション分割コレクション</a>の記憶域とスループットが向上します。</span><span class="sxs-lookup"><span data-stu-id="96781-103">It's recommended that you use <a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">Partitioned Collections</a> for higher storage and throughput.</span></span>
            </para>
      <para>
            <span data-ttu-id="96781-104">HashPartitionResolver クラスでは、経由で指定されたハッシュ関数で、一貫したハッシュ リングを内部的に実装、<see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="96781-104">The HashPartitionResolver class internally implements a consistent hash ring over the hash function specified in the <see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" /> interface.</span></span> <span data-ttu-id="96781-105">既定では、HashPartitionResolver が MD5 ハッシュ関数には、このことができますにスワップ アウトする別のハッシュ実装。</span><span class="sxs-lookup"><span data-stu-id="96781-105">By default, the HashPartitionResolver provides an MD5 hash function, but this can be swapped out with a different hashing implementation.</span></span> <span data-ttu-id="96781-106">一貫したハッシュ リングは、コレクション間でドキュメントのより均一な分布を実現するためにコレクションごとに 16 のレプリカを作成します。</span><span class="sxs-lookup"><span data-stu-id="96781-106">The consistent hash ring creates 16 replicas for each collection in order to achieve a more uniform distribution of documents across collections.</span></span>
            </para>
      <para>
            <span data-ttu-id="96781-107">ハッシュ パーティション分割は、コレクション間でデータを均等に割り当てがあるために、パーティション キーは基数の大きな時にパーティション分割に最も適しています。</span><span class="sxs-lookup"><span data-stu-id="96781-107">The hash partitioning is most suitable for partitioning when the partition key has a high cardinality because it will distribute the data evenly across collections.</span></span> <span data-ttu-id="96781-108">通常ハッシュ パーティション分割は、id プロパティを使用しています。</span><span class="sxs-lookup"><span data-stu-id="96781-108">Typically hash partitioning uses the id property.</span></span> <span data-ttu-id="96781-109">ハッシュ パーティション分割の一般的なユース ケースは、生成またはから多数の個別のクライアントまたはユーザー プロファイル、カタログ アイテム、および遠隔測定データを格納するために使用されたデータです。</span><span class="sxs-lookup"><span data-stu-id="96781-109">A common use cases for hash partitioning is data produced or consumed from a large number of distinct clients or for storing user profiles, catalog items, and telemetry data.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HashPartitionResolver (Func&lt;object,string&gt; partitionKeyExtractor, System.Collections.Generic.IEnumerable&lt;string&gt; collectionLinks, int numberOfVirtualNodesPerCollection = 128, Microsoft.Azure.Documents.Partitioning.IHashGenerator hashGenerator = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;object, string&gt; partitionKeyExtractor, class System.Collections.Generic.IEnumerable`1&lt;string&gt; collectionLinks, int32 numberOfVirtualNodesPerCollection, class Microsoft.Azure.Documents.Partitioning.IHashGenerator hashGenerator) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.#ctor(System.Func{System.Object,System.String},System.Collections.Generic.IEnumerable{System.String},System.Int32,Microsoft.Azure.Documents.Partitioning.IHashGenerator)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKeyExtractor As Func(Of Object, String), collectionLinks As IEnumerable(Of String), Optional numberOfVirtualNodesPerCollection As Integer = 128, Optional hashGenerator As IHashGenerator = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.HashPartitionResolver : Func&lt;obj, string&gt; * seq&lt;string&gt; * int * Microsoft.Azure.Documents.Partitioning.IHashGenerator -&gt; Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" Usage="new Microsoft.Azure.Documents.Partitioning.HashPartitionResolver (partitionKeyExtractor, collectionLinks, numberOfVirtualNodesPerCollection, hashGenerator)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKeyExtractor" Type="System.Func&lt;System.Object,System.String&gt;" />
        <Parameter Name="collectionLinks" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="numberOfVirtualNodesPerCollection" Type="System.Int32" />
        <Parameter Name="hashGenerator" Type="Microsoft.Azure.Documents.Partitioning.IHashGenerator" />
      </Parameters>
      <Docs>
        <param name="partitionKeyExtractor"><span data-ttu-id="96781-110">ドキュメントからの partitionKey を抽出する関数</span><span class="sxs-lookup"><span data-stu-id="96781-110">A function to extract the partitionKey from the document</span></span></param>
        <param name="collectionLinks"><span data-ttu-id="96781-111">ハッシュに使用されるコレクションへのリンクの一覧。</span><span class="sxs-lookup"><span data-stu-id="96781-111">The list of collection links used for hashing.</span></span></param>
        <param name="numberOfVirtualNodesPerCollection"><span data-ttu-id="96781-112">Conisistent ハッシュ リング内のコレクションあたりの仮想ノードの数。</span><span class="sxs-lookup"><span data-stu-id="96781-112">The number of virtual nodes per collection in the conisistent hash ring.</span></span></param>
        <param name="hashGenerator"><span data-ttu-id="96781-113"><see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" />一貫したハッシュで使用します。</span><span class="sxs-lookup"><span data-stu-id="96781-113">The <see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" /> to use in consistent hashing.</span></span> <span data-ttu-id="96781-114">Null の場合は、既定の MD5 ハッシュ ジェネレーターが使用されます。</span><span class="sxs-lookup"><span data-stu-id="96781-114">If null, the default MD5 hash generator is used.</span></span></param>
        <summary>
            <span data-ttu-id="96781-115">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" />指定して、サービスの Azure Cosmos db<paramref name="partitionKeyExtractor" />値。</span><span class="sxs-lookup"><span data-stu-id="96781-115">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" /> in the Azure Cosmos DB service using the specified <paramref name="partitionKeyExtractor" /> value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HashPartitionResolver (string partitionKeyPropertyName, System.Collections.Generic.IEnumerable&lt;string&gt; collectionLinks, int numberOfVirtualNodesPerCollection = 128, Microsoft.Azure.Documents.Partitioning.IHashGenerator hashGenerator = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKeyPropertyName, class System.Collections.Generic.IEnumerable`1&lt;string&gt; collectionLinks, int32 numberOfVirtualNodesPerCollection, class Microsoft.Azure.Documents.Partitioning.IHashGenerator hashGenerator) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.#ctor(System.String,System.Collections.Generic.IEnumerable{System.String},System.Int32,Microsoft.Azure.Documents.Partitioning.IHashGenerator)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKeyPropertyName As String, collectionLinks As IEnumerable(Of String), Optional numberOfVirtualNodesPerCollection As Integer = 128, Optional hashGenerator As IHashGenerator = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.HashPartitionResolver : string * seq&lt;string&gt; * int * Microsoft.Azure.Documents.Partitioning.IHashGenerator -&gt; Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" Usage="new Microsoft.Azure.Documents.Partitioning.HashPartitionResolver (partitionKeyPropertyName, collectionLinks, numberOfVirtualNodesPerCollection, hashGenerator)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKeyPropertyName" Type="System.String" />
        <Parameter Name="collectionLinks" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="numberOfVirtualNodesPerCollection" Type="System.Int32" />
        <Parameter Name="hashGenerator" Type="Microsoft.Azure.Documents.Partitioning.IHashGenerator" />
      </Parameters>
      <Docs>
        <param name="partitionKeyPropertyName"><span data-ttu-id="96781-116">上のハッシュを実行するドキュメントのプロパティの名前です。</span><span class="sxs-lookup"><span data-stu-id="96781-116">The name of the property in the document to execute the hashing on.</span></span></param>
        <param name="collectionLinks"><span data-ttu-id="96781-117">ハッシュに使用されるコレクションへのリンクの一覧。</span><span class="sxs-lookup"><span data-stu-id="96781-117">The list of collection links used for hashing.</span></span></param>
        <param name="numberOfVirtualNodesPerCollection"><span data-ttu-id="96781-118">Conisistent ハッシュ リング内のコレクションあたりの仮想ノードの数。</span><span class="sxs-lookup"><span data-stu-id="96781-118">The number of virtual nodes per collection in the conisistent hash ring.</span></span></param>
        <param name="hashGenerator"><span data-ttu-id="96781-119"><see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" />一貫したハッシュで使用します。</span><span class="sxs-lookup"><span data-stu-id="96781-119">The <see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" /> to use in consistent hashing.</span></span> <span data-ttu-id="96781-120">Null の場合は、既定の MD5 ハッシュ ジェネレーターが使用されます。</span><span class="sxs-lookup"><span data-stu-id="96781-120">If null, the default MD5 hash generator is used.</span></span></param>
        <summary>
            <span data-ttu-id="96781-121">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" />指定して、サービスの Azure Cosmos db<paramref name="partitionKeyPropertyName" />値。</span><span class="sxs-lookup"><span data-stu-id="96781-121">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" /> in the Azure Cosmos DB service using the specified <paramref name="partitionKeyPropertyName" /> value.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="96781-122">1 つのプロパティ名に基づくパーティションを作成するときに使用します。</span><span class="sxs-lookup"><span data-stu-id="96781-122">Use when you want to partition based on a single property name.</span></span> <span data-ttu-id="96781-123">その他のパーティション分割スキームの場合、代わりに partitionKeyExtractor でコンス トラクターを使用します。</span><span class="sxs-lookup"><span data-stu-id="96781-123">For other partitioning schemes, use the constructor with partitionKeyExtractor instead.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionLinks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;string&gt; CollectionLinks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; CollectionLinks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.CollectionLinks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionLinks As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="member this.CollectionLinks : seq&lt;string&gt;" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.CollectionLinks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96781-124">Azure Cosmos DB サービスのハッシュに使用されるコレクションへのリンクの IEnumerable を取得します。</span><span class="sxs-lookup"><span data-stu-id="96781-124">Gets the IEnumerable of collection links used for hashing in the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="96781-125">ハッシュに使用されるコレクションへのリンクの IEnumerable です。</span><span class="sxs-lookup"><span data-stu-id="96781-125">The IEnumerable of collection links used for hashing.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="hashPartitionResolver.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="96781-126">Cosmos DB の Azure サービスでの競合回避モジュールを破棄します。</span><span class="sxs-lookup"><span data-stu-id="96781-126">Disposes the resolver in the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Finalize">
      <MemberSignature Language="C#" Value="~HashPartitionResolver ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Finalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.Finalize" />
      <MemberSignature Language="VB.NET" Value="Finalize ()" />
      <MemberSignature Language="F#" Value="override this.Finalize : unit -&gt; unit" Usage="hashPartitionResolver.Finalize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="96781-127">クラスのデストラクターです。</span><span class="sxs-lookup"><span data-stu-id="96781-127">Class destructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionKey">
      <MemberSignature Language="C#" Value="public virtual object GetPartitionKey (object document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object GetPartitionKey(object document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.GetPartitionKey(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPartitionKey (document As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetPartitionKey : obj -&gt; obj&#xA;override this.GetPartitionKey : obj -&gt; obj" Usage="hashPartitionResolver.GetPartitionKey document" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Documents.Client.IPartitionResolver.GetPartitionKey(System.Object)</InterfaceMember>
      </Implements>
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
        <param name="document"><span data-ttu-id="96781-128">ドキュメント オブジェクト</span><span class="sxs-lookup"><span data-stu-id="96781-128">A document object</span></span></param>
        <summary>
            <span data-ttu-id="96781-129">パーティション キーを指定して、指定されたドキュメントから抽出<see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" />プロパティまたは<see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" />Cosmos DB の Azure サービスでの優先順位で機能します。</span><span class="sxs-lookup"><span data-stu-id="96781-129">Extracts the partition key from the specified document using the specified <see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" /> property or <see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" /> function in order of preference in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="96781-130">パーティション キーとして使用されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="96781-130">object used as the partition key.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="96781-131">パーティション キーを抽出できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="96781-131">Thrown if unable to extract the partition key.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="HashGenerator">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Partitioning.IHashGenerator HashGenerator { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Partitioning.IHashGenerator HashGenerator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.HashGenerator" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HashGenerator As IHashGenerator" />
      <MemberSignature Language="F#" Value="member this.HashGenerator : Microsoft.Azure.Documents.Partitioning.IHashGenerator" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.HashGenerator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Partitioning.IHashGenerator</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96781-132">一貫したハッシュで使用される HashGenerator を取得します。</span><span class="sxs-lookup"><span data-stu-id="96781-132">Gets the HashGenerator used in consistent hashing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfVirtualNodesPerCollection">
      <MemberSignature Language="C#" Value="public int NumberOfVirtualNodesPerCollection { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 NumberOfVirtualNodesPerCollection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.NumberOfVirtualNodesPerCollection" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumberOfVirtualNodesPerCollection As Integer" />
      <MemberSignature Language="F#" Value="member this.NumberOfVirtualNodesPerCollection : int" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.NumberOfVirtualNodesPerCollection" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="96781-133">Conisistent ハッシュにコレクションごとの仮想ノードの数は、Azure Cosmos DB サービス リングします。</span><span class="sxs-lookup"><span data-stu-id="96781-133">The number of virtual nodes per collection in the conisistent hash ring in the Azure Cosmos DB service.</span></span> <span data-ttu-id="96781-134">これは、ドキュメントの歪み度のセキュリティ侵害で制御コレクション vs 一貫したハッシュ遅延します。</span><span class="sxs-lookup"><span data-stu-id="96781-134">This controls the compromise of skewness of documents accross collections vs the consistent hashing latency.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyExtractor">
      <MemberSignature Language="C#" Value="public Func&lt;object,string&gt; PartitionKeyExtractor { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;object, string&gt; PartitionKeyExtractor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyExtractor As Func(Of Object, String)" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyExtractor : Func&lt;obj, string&gt;" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Object,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96781-135">Cosmos DB の Azure サービス内のオブジェクトから、パーティション キーを抽出する関数を取得します。</span><span class="sxs-lookup"><span data-stu-id="96781-135">Gets the function to extract the partition key from an object in the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="96781-136">オブジェクトから、パーティション キーを抽出する関数。</span><span class="sxs-lookup"><span data-stu-id="96781-136">The function to extract the partition key from an object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyPropertyName">
      <MemberSignature Language="C#" Value="public string PartitionKeyPropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyPropertyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyPropertyName As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyPropertyName : string" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="96781-137">Cosmos DB の Azure サービスでのハッシュを実行するドキュメントでプロパティの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="96781-137">Gets the name of the property in the document to execute the hashing on in the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="96781-138">上のハッシュを実行するドキュメントのプロパティの名前です。</span><span class="sxs-lookup"><span data-stu-id="96781-138">The name of the property in the document to execute the hashing on.</span></span></value>
        <remarks>
            <span data-ttu-id="96781-139">HashPartitionResolver - 2 つのモードをサポートしている 1 つを使用して PartitionKeyPropertyName と、その他の PartitionKeyExtractor を使用しています。</span><span class="sxs-lookup"><span data-stu-id="96781-139">HashPartitionResolver supports two modes - one using PartitionKeyPropertyName and the other using PartitionKeyExtractor.</span></span>
            <span data-ttu-id="96781-140">PartitionKeyPropertyName がリフレクションでは、c# を使用してプロパティ名では、JSON 表現ではありませんを使用して抽出されます。</span><span class="sxs-lookup"><span data-stu-id="96781-140">PartitionKeyPropertyName is extracted using Reflection, so use the C# property name, not the JSON representation.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveForCreate">
      <MemberSignature Language="C#" Value="public virtual string ResolveForCreate (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string ResolveForCreate(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.ResolveForCreate(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveForCreate (partitionKey As Object) As String" />
      <MemberSignature Language="F#" Value="abstract member ResolveForCreate : obj -&gt; string&#xA;override this.ResolveForCreate : obj -&gt; string" Usage="hashPartitionResolver.ResolveForCreate partitionKey" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Documents.Client.IPartitionResolver.ResolveForCreate(System.Object)</InterfaceMember>
      </Implements>
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
        <param name="partitionKey"><span data-ttu-id="96781-141">ターゲット コレクションを決定するために使用するパーティション キーを作成します。</span><span class="sxs-lookup"><span data-stu-id="96781-141">The partition key used to determine the target collection for creates.</span></span></param>
        <summary>
            <span data-ttu-id="96781-142">パーティション キーを返しますが、コレクションの自己リンク指定 Cosmos DB の Azure サービスでドキュメントを作成します。</span><span class="sxs-lookup"><span data-stu-id="96781-142">Given a partition key, returns the collection self-link for creating a document in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="96781-143">ドキュメントの作成に使用するターゲット コレクションのリンクです。</span><span class="sxs-lookup"><span data-stu-id="96781-143">The target collection link that will be used for document creation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="96781-144">スローされた場合、指定した<paramref name="partitionKey" />が null です。</span><span class="sxs-lookup"><span data-stu-id="96781-144">Thrown if the specified <paramref name="partitionKey" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveForRead">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;string&gt; ResolveForRead (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; ResolveForRead(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.ResolveForRead(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveForRead (partitionKey As Object) As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="abstract member ResolveForRead : obj -&gt; seq&lt;string&gt;&#xA;override this.ResolveForRead : obj -&gt; seq&lt;string&gt;" Usage="hashPartitionResolver.ResolveForRead partitionKey" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Documents.Client.IPartitionResolver.ResolveForRead(System.Object)</InterfaceMember>
      </Implements>
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
        <param name="partitionKey"><span data-ttu-id="96781-145">読み取り対象のコレクションを決定するために使用するパーティション キーです。</span><span class="sxs-lookup"><span data-stu-id="96781-145">The partition key used to determine the target collections for reading.</span></span> <span data-ttu-id="96781-146">文字列である必要があります。</span><span class="sxs-lookup"><span data-stu-id="96781-146">Must be a string.</span></span></param>
        <summary>
            <span data-ttu-id="96781-147">パーティション キーを返します Cosmos DB の Azure サービスでそのハッシュを使用してから参照するコレクションにリンクの一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="96781-147">Given a partition key, returns a list of collection links to read from using its hash in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="96781-148">ターゲット コレクションのリンクの一覧。</span><span class="sxs-lookup"><span data-stu-id="96781-148">The list of target collection links.</span></span></returns>
        <remarks>
            <span data-ttu-id="96781-149">PartitionKey が null の場合は、すべてのコレクションが返されます。</span><span class="sxs-lookup"><span data-stu-id="96781-149">If partitionKey is null, then all collections are returned.</span></span> <span data-ttu-id="96781-150">HashPartitionResolver partitionKeys として文字列のみをサポートします。</span><span class="sxs-lookup"><span data-stu-id="96781-150">The HashPartitionResolver supports only strings as partitionKeys.</span></span>
            <span data-ttu-id="96781-151">その他の種類には、文字列に変換する ToString() または JsonConvert.SerializeObject() を使用します。</span><span class="sxs-lookup"><span data-stu-id="96781-151">For other types, use ToString() or JsonConvert.SerializeObject() to convert to string.</span></span>
            </remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="96781-152">パーティション キーが文字列ではない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="96781-152">Thrown if the partition key is not a string.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>