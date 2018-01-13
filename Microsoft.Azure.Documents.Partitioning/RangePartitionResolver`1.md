<Type Name="RangePartitionResolver&lt;T&gt;" FullName="Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class RangePartitionResolver&lt;T&gt; : Microsoft.Azure.Documents.Client.IPartitionResolver where T : IComparable&lt;T&gt;, IEquatable&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RangePartitionResolver`1&lt;(class System.IComparable`1&lt;!T&gt;, class System.IEquatable`1&lt;!T&gt;) T&gt; extends System.Object implements class Microsoft.Azure.Documents.Client.IPartitionResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" />
  <TypeSignature Language="VB.NET" Value="Public Class RangePartitionResolver(Of T)&#xA;Implements IPartitionResolver" />
  <TypeSignature Language="F#" Value="type RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; = class&#xA;    interface IPartitionResolver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <InterfaceName>System.IComparable&lt;T&gt;</InterfaceName>
        <InterfaceName>System.IEquatable&lt;T&gt;</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IPartitionResolver</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for IPartitionResolver based classes is now obsolete. It's recommended that you use partitioned collections for higher storage and throughput.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <typeparam name="T"><span data-ttu-id="dd44f-101">範囲パーティション分割に使用する値の型。</span><span class="sxs-lookup"><span data-stu-id="dd44f-101">The type of value to use for range partitioning.</span></span></typeparam>
    <summary>
            <span data-ttu-id="dd44f-102">RangePartitionResolver では、自己リンクをコレクションに値の範囲のパーティションのマップを使用して Azure Cosmos DB サービスのパーティション分割を実装します。</span><span class="sxs-lookup"><span data-stu-id="dd44f-102">RangePartitionResolver implements partitioning in Azure Cosmos DB service by using a partition map of ranges of values to a collection self-link.</span></span>
            <span data-ttu-id="dd44f-103">これは、動作も、データの自然順序付けし、一般的な時系列データまたは文字列のアルファベット順の範囲をたとえば、値の範囲の使用時にクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="dd44f-103">This works well when the data is naturally ordered and commonly queried upon using ranges of values, e.g., for time series data or alphabetical ranges of strings.</span></span>
            </summary>
    <remarks>
      <para>
            <span data-ttu-id="dd44f-104">IPartitionResolver ベース クラスのサポートは廃止されました。</span><span class="sxs-lookup"><span data-stu-id="dd44f-104">Support for IPartitionResolver based classes is now obsolete.</span></span> <span data-ttu-id="dd44f-105">使用することをお勧め<a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">パーティション分割コレクション</a>の記憶域とスループットが向上します。</span><span class="sxs-lookup"><span data-stu-id="dd44f-105">It's recommended that you use <a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">Partitioned Collections</a> for higher storage and throughput.</span></span>
            </para>
      <para>
            <span data-ttu-id="dd44f-106">範囲パーティション分割では、パーティション キーが特定の範囲内にあるかどうかに基づいてパーティションが割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="dd44f-106">In range partitioning, partitions are assigned based on whether the partition key is within a certain range.</span></span> <span data-ttu-id="dd44f-107">RangePartitionResolver クラスには、間のマッピングを維持するのに役立ちます、<see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" />とコレクションの自己リンクします。</span><span class="sxs-lookup"><span data-stu-id="dd44f-107">The RangePartitionResolver class helps you maintain a mapping between a <see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" /> and collection self-link.</span></span>
            </para>
      <para>
        <span data-ttu-id="dd44f-108"><see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" />実装する任意の型の範囲を指定するための単純なクラス<see cref="T:System.IComparable`1" />と<see cref="T:System.IEquatable`1" />などの文字列または数値です。</span><span class="sxs-lookup"><span data-stu-id="dd44f-108"><see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" /> is a simple class for specifying ranges of any types that implement <see cref="T:System.IComparable`1" /> and <see cref="T:System.IEquatable`1" /> like strings or numbers.</span></span> <span data-ttu-id="dd44f-109">読み込み、作成しを任意の範囲内に渡すことができ、競合回避モジュールが twith、要求された範囲の交差するパーティションの範囲を識別することによってすべての候補コレクションを識別します。</span><span class="sxs-lookup"><span data-stu-id="dd44f-109">For reads and creates, you can pass in any arbitrary range, and the resolver identifies all the candidate collections by identifying the ranges of the partitions that intersect twith the requested range.</span></span>
            </para>
      <para>
            <span data-ttu-id="dd44f-110">範囲パーティション分割の特殊なケースは、範囲が単一不連続の値だけでルックアップがパーティション分割とも呼ばれます。</span><span class="sxs-lookup"><span data-stu-id="dd44f-110">A special case of range partitioning is when the range is just a single discrete value, sometimes called Lookup Partitioning.</span></span> <span data-ttu-id="dd44f-111">これは、地域や種類などの不連続の値によって、パーティション分割や、マルチ テナント アプリケーションで、テナントのパーティション分割のよく使用されます。</span><span class="sxs-lookup"><span data-stu-id="dd44f-111">This is commonly used for partitioning by discrete values like Region or Type or for partitioning tenants in a multi-tenant application.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RangePartitionResolver (Func&lt;object,object&gt; partitionKeyExtractor, System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,string&gt; partitionMap);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;object, object&gt; partitionKeyExtractor, class System.Collections.Generic.IDictionary`2&lt;class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt;, string&gt; partitionMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.#ctor(System.Func{System.Object,System.Object},System.Collections.Generic.IDictionary{Microsoft.Azure.Documents.Partitioning.Range{`0},System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKeyExtractor As Func(Of Object, Object), partitionMap As IDictionary(Of Range(Of T), String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; : Func&lt;obj, obj&gt; * System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;'T&gt;, string&gt; -&gt; Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt;" Usage="new Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt; (partitionKeyExtractor, partitionMap)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKeyExtractor" Type="System.Func&lt;System.Object,System.Object&gt;" />
        <Parameter Name="partitionMap" Type="System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="partitionKeyExtractor"><span data-ttu-id="dd44f-112">上のハッシュを実行するドキュメントのプロパティの名前です。</span><span class="sxs-lookup"><span data-stu-id="dd44f-112">The name of the property in the document to execute the hashing on.</span></span></param>
        <param name="partitionMap"><span data-ttu-id="dd44f-113">範囲からの要求をパーティション分割に使用されるコレクション リンクへのマップ。</span><span class="sxs-lookup"><span data-stu-id="dd44f-113">A map from range to collection-link that is used for partitioning requests.</span></span></param>
        <summary>
            <span data-ttu-id="dd44f-114">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" />指定して、サービスの Azure Cosmos db<paramref name="partitionKeyExtractor" />値。</span><span class="sxs-lookup"><span data-stu-id="dd44f-114">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" /> in the Azure Cosmos DB service using the specified <paramref name="partitionKeyExtractor" /> value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="dd44f-115">パラメーターのいずれかが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd44f-115">Thrown if one of the parameters is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RangePartitionResolver (string partitionKeyPropertyName, System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,string&gt; partitionMap);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKeyPropertyName, class System.Collections.Generic.IDictionary`2&lt;class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt;, string&gt; partitionMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.#ctor(System.String,System.Collections.Generic.IDictionary{Microsoft.Azure.Documents.Partitioning.Range{`0},System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKeyPropertyName As String, partitionMap As IDictionary(Of Range(Of T), String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; : string * System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;'T&gt;, string&gt; -&gt; Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt;" Usage="new Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt; (partitionKeyPropertyName, partitionMap)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKeyPropertyName" Type="System.String" />
        <Parameter Name="partitionMap" Type="System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="partitionKeyPropertyName"><span data-ttu-id="dd44f-116">上のハッシュを実行するドキュメントのプロパティの名前です。</span><span class="sxs-lookup"><span data-stu-id="dd44f-116">The name of the property in the document to execute the hashing on.</span></span></param>
        <param name="partitionMap"><span data-ttu-id="dd44f-117">範囲からの要求をパーティション分割に使用されるコレクション リンクへのマップ。</span><span class="sxs-lookup"><span data-stu-id="dd44f-117">A map from range to collection-link that is used for partitioning requests.</span></span></param>
        <summary>
            <span data-ttu-id="dd44f-118">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" />クラスを指定して、Azure Cosmos DB サービス <paramref name="partitionKeyPropertyName" />値。</span><span class="sxs-lookup"><span data-stu-id="dd44f-118">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> class in the Azure Cosmos DB service using the specified <paramref name="partitionKeyPropertyName" /> value.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="dd44f-119">1 つのプロパティ名に基づくパーティションを作成するときに使用します。</span><span class="sxs-lookup"><span data-stu-id="dd44f-119">Use when you want to partition based on a single property name.</span></span> <span data-ttu-id="dd44f-120">その他のパーティション分割スキームの場合、代わりに partitionKeyExtractor でコンス トラクターを使用します。</span><span class="sxs-lookup"><span data-stu-id="dd44f-120">For other partitioning schemes, use the constructor with partitionKeyExtractor instead.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="dd44f-121">パラメーターのいずれかが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd44f-121">Thrown if one of the parameters is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionKey">
      <MemberSignature Language="C#" Value="public virtual object GetPartitionKey (object document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object GetPartitionKey(object document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.GetPartitionKey(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPartitionKey (document As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetPartitionKey : obj -&gt; obj&#xA;override this.GetPartitionKey : obj -&gt; obj" Usage="rangePartitionResolver.GetPartitionKey document" />
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
        <param name="document"><span data-ttu-id="dd44f-122">ドキュメント オブジェクト</span><span class="sxs-lookup"><span data-stu-id="dd44f-122">A document object</span></span></param>
        <summary>
            <span data-ttu-id="dd44f-123">パーティション キーを指定して、指定されたドキュメントから抽出<see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" />プロパティまたは<see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" />Cosmos DB の Azure サービスでの優先順位で機能します。</span><span class="sxs-lookup"><span data-stu-id="dd44f-123">Extracts the partition key from the specified document using the specified <see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" /> property or <see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" /> function in order of preference in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="dd44f-124">パーティション キーとして使用されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="dd44f-124">object used as the partition key.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="dd44f-125">パーティション キーを抽出できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dd44f-125">Thrown if unable to extract the partition key.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyExtractor">
      <MemberSignature Language="C#" Value="public Func&lt;object,object&gt; PartitionKeyExtractor { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;object, object&gt; PartitionKeyExtractor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.PartitionKeyExtractor" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyExtractor As Func(Of Object, Object)" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyExtractor : Func&lt;obj, obj&gt;" Usage="Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt;.PartitionKeyExtractor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Object,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd44f-126">Azure Cosmos DB サービスの任意のオブジェクトから、パーティション キーを抽出する関数を取得します。</span><span class="sxs-lookup"><span data-stu-id="dd44f-126">Gets the function to extract the partition key from any object in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="dd44f-127">任意のオブジェクトから、パーティション キーを抽出する関数。</span><span class="sxs-lookup"><span data-stu-id="dd44f-127">The function to extract the partition key from any object.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyPropertyName">
      <MemberSignature Language="C#" Value="public string PartitionKeyPropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyPropertyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.PartitionKeyPropertyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyPropertyName As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyPropertyName : string" Usage="Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt;.PartitionKeyPropertyName" />
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
            <span data-ttu-id="dd44f-128">Cosmos DB の Azure サービスでのハッシュを実行するドキュメントのプロパティの名前です。</span><span class="sxs-lookup"><span data-stu-id="dd44f-128">The name of the property in the document to execute the hashing on in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionMap">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,string&gt; PartitionMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt;, string&gt; PartitionMap" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.PartitionMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionMap As IDictionary(Of Range(Of T), String)" />
      <MemberSignature Language="F#" Value="member this.PartitionMap : System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;'T&gt;, string&gt;" Usage="Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt;.PartitionMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd44f-129">範囲からの Azure Cosmos DB サービスのパーティション分割の要求で使用されるコレクション リンクへのマップを取得します。</span><span class="sxs-lookup"><span data-stu-id="dd44f-129">Gets the map from range to collection-link that is used for partitioning requests in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="dd44f-130">範囲からの要求をパーティション分割に使用されるコレクション リンクへのマップ。</span><span class="sxs-lookup"><span data-stu-id="dd44f-130">The map from range to collection-link that is used for partitioning requests.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveForCreate">
      <MemberSignature Language="C#" Value="public virtual string ResolveForCreate (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string ResolveForCreate(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.ResolveForCreate(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveForCreate (partitionKey As Object) As String" />
      <MemberSignature Language="F#" Value="abstract member ResolveForCreate : obj -&gt; string&#xA;override this.ResolveForCreate : obj -&gt; string" Usage="rangePartitionResolver.ResolveForCreate partitionKey" />
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
        <param name="partitionKey"><span data-ttu-id="dd44f-131">ターゲット コレクションの作成を決定するために使用するパーティション キー</span><span class="sxs-lookup"><span data-stu-id="dd44f-131">The partition key used to determine the target collection for create</span></span></param>
        <summary>
            <span data-ttu-id="dd44f-132">Azure Cosmos DB サービスの範囲パーティションのマップを使用してドキュメントを作成するためのパーティション キーを返します自己リンク正しいコレクションを指定します。</span><span class="sxs-lookup"><span data-stu-id="dd44f-132">Given a partition key, returns the correct collection self-link for creating a document using the range partition map in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="dd44f-133">ドキュメントの作成に使用するターゲット コレクションのリンクです。</span><span class="sxs-lookup"><span data-stu-id="dd44f-133">The target collection link that will be used for document creation.</span></span></returns>
        <remarks>
            <span data-ttu-id="dd44f-134">場合は、複数の範囲には、指定した partitionKey が一致すると、競合回避モジュールを返しますの一致する範囲のいずれか。</span><span class="sxs-lookup"><span data-stu-id="dd44f-134">If multiple ranges match the specified partitionKey, then the resolver returns one of the matching ranges.</span></span> <span data-ttu-id="dd44f-135">一致なしの範囲のかどうかは、メソッドをスロー、<see cref="T:System.InvalidOperationException" />です。</span><span class="sxs-lookup"><span data-stu-id="dd44f-135">If none of the ranges match, then the method throws a <see cref="T:System.InvalidOperationException" />.</span></span> <span data-ttu-id="dd44f-136">PartitionKey が null の場合は、すべてのコレクションが返されます。</span><span class="sxs-lookup"><span data-stu-id="dd44f-136">If partitionKey is null, then all collections are returned.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="dd44f-137">場合にスロー<paramref name="partitionKey" />が null です。</span><span class="sxs-lookup"><span data-stu-id="dd44f-137">Thrown if <paramref name="partitionKey" /> is null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="dd44f-138">場合にスローされます、<paramref name="partitionKey" />は無効な型の範囲の中に、指定されたパーティション キーが一致するものである場合またはします。</span><span class="sxs-lookup"><span data-stu-id="dd44f-138">Thrown if the <paramref name="partitionKey" /> is an invalid type or if none of the ranges match the specified partition key.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveForRead">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;string&gt; ResolveForRead (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; ResolveForRead(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.ResolveForRead(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveForRead (partitionKey As Object) As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="abstract member ResolveForRead : obj -&gt; seq&lt;string&gt;&#xA;override this.ResolveForRead : obj -&gt; seq&lt;string&gt;" Usage="rangePartitionResolver.ResolveForRead partitionKey" />
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
        <param name="partitionKey"><span data-ttu-id="dd44f-139">クエリのターゲット コレクションを決定するために使用するパーティション キー</span><span class="sxs-lookup"><span data-stu-id="dd44f-139">The partition key used to determine the target collections for query</span></span></param>
        <summary>
            <span data-ttu-id="dd44f-140">パーティション キーを返します範囲パーティション マップを使用して、Azure Cosmos DB サービスからの読み取りにコレクションへのリンクの一覧を指定します。</span><span class="sxs-lookup"><span data-stu-id="dd44f-140">Given a partition key, returns a list of collection links to read from using the range partition map in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="dd44f-141">ターゲット コレクションのリンクの一覧。</span><span class="sxs-lookup"><span data-stu-id="dd44f-141">The list of target collection links.</span></span></returns>
        <remarks>
            <span data-ttu-id="dd44f-142"><paramref name="partitionKey" />のインスタンスである必要があります<typeparamref name="T" />、<see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" />または<see cref="T:System.Collections.Generic.IEnumerable`1" />"。/&gt;.</span><span class="sxs-lookup"><span data-stu-id="dd44f-142">The <paramref name="partitionKey" /> must be an instance of <typeparamref name="T" />, <see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" /> or an <see cref="T:System.Collections.Generic.IEnumerable`1" />."/&gt;.</span></span> <span data-ttu-id="dd44f-143">このメソッドは、指定したと交差する範囲に対応するすべてのコレクションを返します<paramref name="partitionKey" />です。</span><span class="sxs-lookup"><span data-stu-id="dd44f-143">This method returns all the collections corresponding to the ranges that intersect with the specified <paramref name="partitionKey" />.</span></span>
            </remarks>
        <exception cref="T:System.InvalidOperationException">
            <span data-ttu-id="dd44f-144">場合にスローされます、<paramref name="partitionKey" />種類が無効です。</span><span class="sxs-lookup"><span data-stu-id="dd44f-144">Thrown if the <paramref name="partitionKey" /> is an invalid type.</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>