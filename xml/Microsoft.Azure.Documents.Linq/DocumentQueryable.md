<Type Name="DocumentQueryable" FullName="Microsoft.Azure.Documents.Linq.DocumentQueryable">
  <TypeSignature Language="C#" Value="public static class DocumentQueryable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DocumentQueryable extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Linq.DocumentQueryable" />
  <TypeSignature Language="VB.NET" Value="Public Module DocumentQueryable" />
  <TypeSignature Language="F#" Value="type DocumentQueryable = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
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
            <span data-ttu-id="fc3c8-101">このクラスを変換する拡張メソッドを提供する、<see cref="T:System.Linq.IQueryable`1" />オブジェクトを<see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-101">This class provides extension methods for converting a <see cref="T:System.Linq.IQueryable`1" /> object to a <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" /> object.</span></span>
            </summary>
    <remarks>
             <span data-ttu-id="fc3c8-102"><see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />クラス Azure Cosmos DB 内のリソースを照会するための標準クエリ メソッドの実装を提供します。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-102">The <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> class provides implementation of standard query methods for querying resources in Azure Cosmos DB.</span></span> <span data-ttu-id="fc3c8-103">これらのメソッドには、Azure Cosmos DB サービスの永続化すると、高速の走査、フィルター、およびデータに対する射影操作が有効にします。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-103">These methods enable you to express traversal, filter, and projection operations over data persisted in the Azure Cosmos DB service.</span></span>  <span data-ttu-id="fc3c8-104">IQueryable を拡張し、任意の直接クエリを実行しないメソッドとして定義されます。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-104">They are defined as methods that extend IQueryable, and do not perform any querying directly.</span></span>  <span data-ttu-id="fc3c8-105">代わりに、それらの機能は、基に指定されたリソースとクエリの式のクエリを作成するのにです。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-105">Instead, their functionality is to create queries based the resource and query expression provided.</span></span>  <span data-ttu-id="fc3c8-106">実際のクエリの実行は、列挙型が実行される IQueryable オブジェクトに関連付けられている式ツリーを強制した場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-106">The actual query execution occurs when enumeration forces the expression tree associated with an IQueryable object to be executed.</span></span>
             </remarks>
    <altmember cref="T:Microsoft.Azure.Documents.IDocumentClient" />
    <altmember cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />
  </Docs>
  <Members>
    <Member MemberName="AsDocumentQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;T&gt; AsDocumentQuery&lt;T&gt; (this System.Linq.IQueryable&lt;T&gt; query);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Linq.IDocumentQuery`1&lt;!!T&gt; AsDocumentQuery&lt;T&gt;(class System.Linq.IQueryable`1&lt;!!T&gt; query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.AsDocumentQuery``1(System.Linq.IQueryable{``0})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function AsDocumentQuery(Of T) (query As IQueryable(Of T)) As IDocumentQuery(Of T)" />
      <MemberSignature Language="F#" Value="static member AsDocumentQuery : System.Linq.IQueryable&lt;'T&gt; -&gt; Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;'T&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.AsDocumentQuery query" />
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
        <ReturnType>Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;T&gt;" RefType="this" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="fc3c8-107">照会するオブジェクトの型。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-107">the type of object to query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="fc3c8-108">変換するには、{T} の IQueryable。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-108">the IQueryable{T} to be converted.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-109">Azure Cosmos DB サービスの改ページ調整と非同期実行をサポートする IDocumentQuery IQueryable に変換します。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-109">Converts an IQueryable to IDocumentQuery which supports pagination and asynchronous execution in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-110">クエリを評価できる IDocumentQuery {t} です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-110">An IDocumentQuery{T} that can evaluate the query.</span></span></returns>
        <remarks>To be added.</remarks>
        <example>
            <span data-ttu-id="fc3c8-111">この例では、非同期的に AsDocumentQuery() インターフェイスを使用してクエリを実行する方法を示します。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-111">This example shows how to run a query asynchronously using the AsDocumentQuery() interface.</span></span>
            
            <code language="c#"><![CDATA[
            using (var queryable = client.CreateDocumentQuery<Book>(
                collectionLink,
                new FeedOptions { MaxItemCount = 10 })
                .Where(b => b.Title == "War and Peace")
                .AsDocumentQuery())
            {
                while (queryable.HasMoreResults) 
                {
                    foreach(Book b in await queryable.ExecuteNextAsync<Book>())
                    {
                        // Iterate through books
                    }
                }
            }
            ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="AverageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;decimal&gt; AverageAsync (this System.Linq.IQueryable&lt;decimal&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;valuetype System.Decimal&gt; AverageAsync(class System.Linq.IQueryable`1&lt;valuetype System.Decimal&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync(System.Linq.IQueryable{System.Decimal},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AverageAsync : System.Linq.IQueryable&lt;decimal&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;decimal&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Decimal&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Decimal&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-112">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-112">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-113">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-114">シーケンスの平均を計算<see cref="T:System.Decimal" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-114">Computes the average of a sequence of <see cref="T:System.Decimal" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-115">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-115">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;double&gt; AverageAsync (this System.Linq.IQueryable&lt;double&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;float64&gt; AverageAsync(class System.Linq.IQueryable`1&lt;float64&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync(System.Linq.IQueryable{System.Double},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AverageAsync : System.Linq.IQueryable&lt;double&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;double&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Double&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-116">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-116">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-117">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-118">シーケンスの平均を計算<see cref="T:System.Double" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-118">Computes the average of a sequence of <see cref="T:System.Double" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-119">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-119">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;double&gt; AverageAsync (this System.Linq.IQueryable&lt;int&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;float64&gt; AverageAsync(class System.Linq.IQueryable`1&lt;int32&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync(System.Linq.IQueryable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AverageAsync : System.Linq.IQueryable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;double&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Int32&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-120">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-120">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-121">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-122">シーケンスの平均を計算<see cref="T:System.Int32" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-122">Computes the average of a sequence of <see cref="T:System.Int32" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-123">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-123">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;double&gt; AverageAsync (this System.Linq.IQueryable&lt;long&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;float64&gt; AverageAsync(class System.Linq.IQueryable`1&lt;int64&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync(System.Linq.IQueryable{System.Int64},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AverageAsync : System.Linq.IQueryable&lt;int64&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;double&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Int64&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-124">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-124">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-125">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-126">シーケンスの平均を計算<see cref="T:System.Int64" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-126">Computes the average of a sequence of <see cref="T:System.Int64" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-127">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-127">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Nullable&lt;decimal&gt;&gt; AverageAsync (this System.Linq.IQueryable&lt;Nullable&lt;decimal&gt;&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;valuetype System.Nullable`1&lt;valuetype System.Decimal&gt;&gt; AverageAsync(class System.Linq.IQueryable`1&lt;valuetype System.Nullable`1&lt;valuetype System.Decimal&gt;&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync(System.Linq.IQueryable{System.Nullable{System.Decimal}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AverageAsync : System.Linq.IQueryable&lt;Nullable&lt;decimal&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Nullable&lt;decimal&gt;&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Nullable&lt;System.Decimal&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Nullable&lt;System.Decimal&gt;&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-128">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-128">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-129">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-130">シーケンスの平均を計算<see cref="T:System.Nullable`1" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-130">Computes the average of a sequence of <see cref="T:System.Nullable`1" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-131">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-131">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Nullable&lt;double&gt;&gt; AverageAsync (this System.Linq.IQueryable&lt;Nullable&lt;double&gt;&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;valuetype System.Nullable`1&lt;float64&gt;&gt; AverageAsync(class System.Linq.IQueryable`1&lt;valuetype System.Nullable`1&lt;float64&gt;&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync(System.Linq.IQueryable{System.Nullable{System.Double}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AverageAsync : System.Linq.IQueryable&lt;Nullable&lt;double&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Nullable&lt;double&gt;&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Nullable&lt;System.Double&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Nullable&lt;System.Double&gt;&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-132">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-132">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-133">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-134">シーケンスの平均を計算<see cref="T:System.Nullable`1" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-134">Computes the average of a sequence of <see cref="T:System.Nullable`1" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-135">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-135">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Nullable&lt;double&gt;&gt; AverageAsync (this System.Linq.IQueryable&lt;Nullable&lt;int&gt;&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;valuetype System.Nullable`1&lt;float64&gt;&gt; AverageAsync(class System.Linq.IQueryable`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync(System.Linq.IQueryable{System.Nullable{System.Int32}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AverageAsync : System.Linq.IQueryable&lt;Nullable&lt;int&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Nullable&lt;double&gt;&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Nullable&lt;System.Double&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Nullable&lt;System.Int32&gt;&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-136">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-136">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-137">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-138">シーケンスの平均を計算<see cref="T:System.Nullable`1" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-138">Computes the average of a sequence of <see cref="T:System.Nullable`1" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-139">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-139">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Nullable&lt;double&gt;&gt; AverageAsync (this System.Linq.IQueryable&lt;Nullable&lt;long&gt;&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;valuetype System.Nullable`1&lt;float64&gt;&gt; AverageAsync(class System.Linq.IQueryable`1&lt;valuetype System.Nullable`1&lt;int64&gt;&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync(System.Linq.IQueryable{System.Nullable{System.Int64}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AverageAsync : System.Linq.IQueryable&lt;Nullable&lt;int64&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Nullable&lt;double&gt;&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Nullable&lt;System.Double&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Nullable&lt;System.Int64&gt;&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-140">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-140">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-141">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-142">シーケンスの平均を計算<see cref="T:System.Nullable`1" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-142">Computes the average of a sequence of <see cref="T:System.Nullable`1" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-143">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-143">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Nullable&lt;float&gt;&gt; AverageAsync (this System.Linq.IQueryable&lt;Nullable&lt;float&gt;&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;valuetype System.Nullable`1&lt;float32&gt;&gt; AverageAsync(class System.Linq.IQueryable`1&lt;valuetype System.Nullable`1&lt;float32&gt;&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync(System.Linq.IQueryable{System.Nullable{System.Single}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AverageAsync : System.Linq.IQueryable&lt;Nullable&lt;single&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Nullable&lt;single&gt;&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Nullable&lt;System.Single&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Nullable&lt;System.Single&gt;&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-144">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-144">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-145">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-146">シーケンスの平均を計算<see cref="T:System.Nullable`1" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-146">Computes the average of a sequence of <see cref="T:System.Nullable`1" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-147">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-147">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AverageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;float&gt; AverageAsync (this System.Linq.IQueryable&lt;float&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;float32&gt; AverageAsync(class System.Linq.IQueryable`1&lt;float32&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync(System.Linq.IQueryable{System.Single},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AverageAsync : System.Linq.IQueryable&lt;single&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;single&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.AverageAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Single&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Single&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-148">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-148">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-149">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-150">シーケンスの平均を計算<see cref="T:System.Single" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-150">Computes the average of a sequence of <see cref="T:System.Single" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-151">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-151">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CountAsync&lt;TSource&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;int&gt; CountAsync&lt;TSource&gt; (this System.Linq.IQueryable&lt;TSource&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;int32&gt; CountAsync&lt;TSource&gt;(class System.Linq.IQueryable`1&lt;!!TSource&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.CountAsync``1(System.Linq.IQueryable{``0},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CountAsync : System.Linq.IQueryable&lt;'Source&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.CountAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TSource" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;TSource&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TSource"><span data-ttu-id="fc3c8-152">source の要素の型。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-152">The type of the elements of source.</span></span></typeparam>
        <param name="source"><span data-ttu-id="fc3c8-153">カウントする要素を格納しているシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-153">The sequence that contains the elements to be counted.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-154">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-155">シーケンス内の要素の数を返します。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-155">Returns the number of elements in a sequence.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-156">入力シーケンス内の要素数。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-156">The number of elements in the input sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAsync&lt;TSource&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;TSource&gt; MaxAsync&lt;TSource&gt; (this System.Linq.IQueryable&lt;TSource&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;!!TSource&gt; MaxAsync&lt;TSource&gt;(class System.Linq.IQueryable`1&lt;!!TSource&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.MaxAsync``1(System.Linq.IQueryable{``0},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MaxAsync : System.Linq.IQueryable&lt;'Source&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'Source&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.MaxAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;TSource&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TSource" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;TSource&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TSource"><span data-ttu-id="fc3c8-157">source の要素の型。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-157">The type of the elements of source.</span></span></typeparam>
        <param name="source"><span data-ttu-id="fc3c8-158">最大数を決定する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-158">A sequence of values to determine the maximum of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-159">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-160">ジェネリック型の最大値を返します<see cref="T:System.Linq.IQueryable`1" />です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-160">Returns the maximum value in a generic <see cref="T:System.Linq.IQueryable`1" />.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-161">シーケンスの最大値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-161">The maximum value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinAsync&lt;TSource&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;TSource&gt; MinAsync&lt;TSource&gt; (this System.Linq.IQueryable&lt;TSource&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;!!TSource&gt; MinAsync&lt;TSource&gt;(class System.Linq.IQueryable`1&lt;!!TSource&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.MinAsync``1(System.Linq.IQueryable{``0},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MinAsync : System.Linq.IQueryable&lt;'Source&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'Source&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.MinAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;TSource&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TSource" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;TSource&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TSource"><span data-ttu-id="fc3c8-162">source の要素の型。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-162">The type of the elements of source.</span></span></typeparam>
        <param name="source"><span data-ttu-id="fc3c8-163">最小値を決定する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-163">A sequence of values to determine the minimum of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-164">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-165">ジェネリック型の最小値を返します<see cref="T:System.Linq.IQueryable`1" />です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-165">Returns the minimum value in a generic <see cref="T:System.Linq.IQueryable`1" />.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-166">シーケンスの最小値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-166">The minimum value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SumAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;decimal&gt; SumAsync (this System.Linq.IQueryable&lt;decimal&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;valuetype System.Decimal&gt; SumAsync(class System.Linq.IQueryable`1&lt;valuetype System.Decimal&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync(System.Linq.IQueryable{System.Decimal},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SumAsync : System.Linq.IQueryable&lt;decimal&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;decimal&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Decimal&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Decimal&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-167">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-167">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-168">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-169">シーケンスの合計を計算<see cref="T:System.Decimal" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-169">Computes the sum of a sequence of <see cref="T:System.Decimal" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-170">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-170">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SumAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;double&gt; SumAsync (this System.Linq.IQueryable&lt;double&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;float64&gt; SumAsync(class System.Linq.IQueryable`1&lt;float64&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync(System.Linq.IQueryable{System.Double},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SumAsync : System.Linq.IQueryable&lt;double&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;double&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Double&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-171">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-171">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-172">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-172">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-173">シーケンスの合計を計算<see cref="T:System.Double" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-173">Computes the sum of a sequence of <see cref="T:System.Double" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-174">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-174">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SumAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;int&gt; SumAsync (this System.Linq.IQueryable&lt;int&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;int32&gt; SumAsync(class System.Linq.IQueryable`1&lt;int32&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync(System.Linq.IQueryable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SumAsync : System.Linq.IQueryable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Int32&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-175">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-175">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-176">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-176">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-177">シーケンスの合計を計算<see cref="T:System.Int32" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-177">Computes the sum of a sequence of <see cref="T:System.Int32" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-178">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-178">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SumAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;long&gt; SumAsync (this System.Linq.IQueryable&lt;long&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;int64&gt; SumAsync(class System.Linq.IQueryable`1&lt;int64&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync(System.Linq.IQueryable{System.Int64},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SumAsync : System.Linq.IQueryable&lt;int64&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Int64&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-179">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-179">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-180">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-181">シーケンスの合計を計算<see cref="T:System.Int64" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-181">Computes the sum of a sequence of <see cref="T:System.Int64" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-182">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-182">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SumAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Nullable&lt;decimal&gt;&gt; SumAsync (this System.Linq.IQueryable&lt;Nullable&lt;decimal&gt;&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;valuetype System.Nullable`1&lt;valuetype System.Decimal&gt;&gt; SumAsync(class System.Linq.IQueryable`1&lt;valuetype System.Nullable`1&lt;valuetype System.Decimal&gt;&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync(System.Linq.IQueryable{System.Nullable{System.Decimal}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SumAsync : System.Linq.IQueryable&lt;Nullable&lt;decimal&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Nullable&lt;decimal&gt;&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Nullable&lt;System.Decimal&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Nullable&lt;System.Decimal&gt;&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-183">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-183">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-184">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-184">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-185">シーケンスの合計を計算<see cref="T:System.Nullable`1" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-185">Computes the sum of a sequence of <see cref="T:System.Nullable`1" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-186">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-186">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SumAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Nullable&lt;double&gt;&gt; SumAsync (this System.Linq.IQueryable&lt;Nullable&lt;double&gt;&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;valuetype System.Nullable`1&lt;float64&gt;&gt; SumAsync(class System.Linq.IQueryable`1&lt;valuetype System.Nullable`1&lt;float64&gt;&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync(System.Linq.IQueryable{System.Nullable{System.Double}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SumAsync : System.Linq.IQueryable&lt;Nullable&lt;double&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Nullable&lt;double&gt;&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Nullable&lt;System.Double&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Nullable&lt;System.Double&gt;&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-187">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-187">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-188">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-189">シーケンスの合計を計算<see cref="T:System.Nullable`1" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-189">Computes the sum of a sequence of <see cref="T:System.Nullable`1" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-190">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-190">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SumAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Nullable&lt;int&gt;&gt; SumAsync (this System.Linq.IQueryable&lt;Nullable&lt;int&gt;&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; SumAsync(class System.Linq.IQueryable`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync(System.Linq.IQueryable{System.Nullable{System.Int32}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SumAsync : System.Linq.IQueryable&lt;Nullable&lt;int&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Nullable&lt;int&gt;&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Nullable&lt;System.Int32&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Nullable&lt;System.Int32&gt;&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-191">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-191">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-192">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-193">シーケンスの合計を計算<see cref="T:System.Nullable`1" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-193">Computes the sum of a sequence of <see cref="T:System.Nullable`1" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-194">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-194">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SumAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Nullable&lt;long&gt;&gt; SumAsync (this System.Linq.IQueryable&lt;Nullable&lt;long&gt;&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;valuetype System.Nullable`1&lt;int64&gt;&gt; SumAsync(class System.Linq.IQueryable`1&lt;valuetype System.Nullable`1&lt;int64&gt;&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync(System.Linq.IQueryable{System.Nullable{System.Int64}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SumAsync : System.Linq.IQueryable&lt;Nullable&lt;int64&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Nullable&lt;int64&gt;&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Nullable&lt;System.Int64&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Nullable&lt;System.Int64&gt;&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-195">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-195">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-196">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-197">シーケンスの合計を計算<see cref="T:System.Nullable`1" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-197">Computes the sum of a sequence of <see cref="T:System.Nullable`1" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-198">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-198">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SumAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Nullable&lt;float&gt;&gt; SumAsync (this System.Linq.IQueryable&lt;Nullable&lt;float&gt;&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;valuetype System.Nullable`1&lt;float32&gt;&gt; SumAsync(class System.Linq.IQueryable`1&lt;valuetype System.Nullable`1&lt;float32&gt;&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync(System.Linq.IQueryable{System.Nullable{System.Single}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SumAsync : System.Linq.IQueryable&lt;Nullable&lt;single&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Nullable&lt;single&gt;&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Nullable&lt;System.Single&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Nullable&lt;System.Single&gt;&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-199">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-199">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-200">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-200">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-201">シーケンスの合計を計算<see cref="T:System.Nullable`1" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-201">Computes the sum of a sequence of <see cref="T:System.Nullable`1" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-202">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-202">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SumAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;float&gt; SumAsync (this System.Linq.IQueryable&lt;float&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;float32&gt; SumAsync(class System.Linq.IQueryable`1&lt;float32&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync(System.Linq.IQueryable{System.Single},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SumAsync : System.Linq.IQueryable&lt;single&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;single&gt;" Usage="Microsoft.Azure.Documents.Linq.DocumentQueryable.SumAsync (source, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Single&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Linq.IQueryable&lt;System.Single&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source"><span data-ttu-id="fc3c8-203">平均を計算する値のシーケンス。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-203">A sequence of values to calculate the average of.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fc3c8-204">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-204">The cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="fc3c8-205">シーケンスの合計を計算<see cref="T:System.Single" />値。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-205">Computes the sum of a sequence of <see cref="T:System.Single" /> values.</span></span>
            </summary>
        <returns><span data-ttu-id="fc3c8-206">シーケンスの平均値です。</span><span class="sxs-lookup"><span data-stu-id="fc3c8-206">The average value in the sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>