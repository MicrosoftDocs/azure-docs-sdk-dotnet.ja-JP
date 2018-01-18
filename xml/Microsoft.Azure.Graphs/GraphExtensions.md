<Type Name="GraphExtensions" FullName="Microsoft.Azure.Graphs.GraphExtensions">
  <TypeSignature Language="C#" Value="public static class GraphExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed GraphExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.GraphExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module GraphExtensions" />
  <TypeSignature Language="F#" Value="type GraphExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
    <AssemblyVersion>1.14.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="beb81-101">このクラスの種類のグラフのクエリを作成するための拡張メソッドを提供する<see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" />です。</span><span class="sxs-lookup"><span data-stu-id="beb81-101">This class provides extension methods for creating Graph queries of type <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" />.</span></span>
            <span data-ttu-id="beb81-102">これらのクエリは、Azure DocumentDB コレクションに対して実行されます。</span><span class="sxs-lookup"><span data-stu-id="beb81-102">These queries will execute against Azure DocumentDB collection.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="beb81-103">クラスを拡張<see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />クラス データに対する高速グラフ走査および CRUD 操作を有効にするには、Azure DocumentDB コレクションで永続化します。</span><span class="sxs-lookup"><span data-stu-id="beb81-103">The class extends <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" /> class to enable you to express graph traversal and CRUD operations over data persisted in a Azure DocumentDB collection.</span></span> <span data-ttu-id="beb81-104">返された<see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" />オブジェクトが、実際のクエリの実行をラップして、これらのオブジェクトを列挙する強制的に実行される Azure DocumentDB クエリです。</span><span class="sxs-lookup"><span data-stu-id="beb81-104">The returned <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" /> objects wrap the actual query execution, and enumerating these objects forces Azure DocumentDB queries to be executed.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateGremlinQuery">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;dynamic&gt; CreateGremlinQuery (this Microsoft.Azure.Documents.Client.DocumentClient documentClient, Microsoft.Azure.Documents.DocumentCollection collection, string gremlinExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null, Microsoft.Azure.Graphs.GraphSONMode graphSONMode = Microsoft.Azure.Graphs.GraphSONMode.Compact);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Linq.IDocumentQuery`1&lt;object&gt; CreateGremlinQuery(class Microsoft.Azure.Documents.Client.DocumentClient documentClient, class Microsoft.Azure.Documents.DocumentCollection collection, string gremlinExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions, valuetype Microsoft.Azure.Graphs.GraphSONMode graphSONMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.GraphExtensions.CreateGremlinQuery(Microsoft.Azure.Documents.Client.DocumentClient,Microsoft.Azure.Documents.DocumentCollection,System.String,Microsoft.Azure.Documents.Client.FeedOptions,Microsoft.Azure.Graphs.GraphSONMode)" />
      <MemberSignature Language="F#" Value="static member CreateGremlinQuery : Microsoft.Azure.Documents.Client.DocumentClient * Microsoft.Azure.Documents.DocumentCollection * string * Microsoft.Azure.Documents.Client.FeedOptions * Microsoft.Azure.Graphs.GraphSONMode -&gt; Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;obj&gt;" Usage="Microsoft.Azure.Graphs.GraphExtensions.CreateGremlinQuery (documentClient, collection, gremlinExpression, feedOptions, graphSONMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documentClient" Type="Microsoft.Azure.Documents.Client.DocumentClient" RefType="this" />
        <Parameter Name="collection" Type="Microsoft.Azure.Documents.DocumentCollection" />
        <Parameter Name="gremlinExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
        <Parameter Name="graphSONMode" Type="Microsoft.Azure.Graphs.GraphSONMode" />
      </Parameters>
      <Docs>
        <param name="documentClient"><span data-ttu-id="beb81-105">クエリを実行する DocumentClient インスタンス。</span><span class="sxs-lookup"><span data-stu-id="beb81-105">The DocumentClient instance to execute the query.</span></span></param>
        <param name="collection"><span data-ttu-id="beb81-106">グラフのクエリを含む DocumentCollection です。</span><span class="sxs-lookup"><span data-stu-id="beb81-106">The DocumentCollection that contains the graph to query.</span></span></param>
        <param name="gremlinExpression"><span data-ttu-id="beb81-107">Gremlin 式です。</span><span class="sxs-lookup"><span data-stu-id="beb81-107">The Gremlin expression.</span></span></param>
        <param name="feedOptions"><span data-ttu-id="beb81-108">クエリ結果のフィードの処理のオプションです。</span><span class="sxs-lookup"><span data-stu-id="beb81-108">The options for processing the query result feed.</span></span> <span data-ttu-id="beb81-109">詳細については<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />します。</span><span class="sxs-lookup"><span data-stu-id="beb81-109">For details <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />.</span></span></param>
        <param name="graphSONMode"><span data-ttu-id="beb81-110">クエリの結果を返すときに使用する GraphSON モードです。</span><span class="sxs-lookup"><span data-stu-id="beb81-110">The GraphSON mode to use when returning the results of the query.</span></span></param>
        <summary>
            <span data-ttu-id="beb81-111">Azure CosmosDB コレクションに格納されているグラフ要素の作成/クエリ Gremlin 式を作成するメソッドです。</span><span class="sxs-lookup"><span data-stu-id="beb81-111">Method to create a Gremlin expression to create/query graph elements stored under an Azure CosmosDB collection.</span></span>
            </summary>
        <returns><span data-ttu-id="beb81-112"><see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" />クエリを評価することができます。</span><span class="sxs-lookup"><span data-stu-id="beb81-112">An <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" /> that can evaluate the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateGremlinQuery&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;T&gt; CreateGremlinQuery&lt;T&gt; (this Microsoft.Azure.Documents.Client.DocumentClient documentClient, Microsoft.Azure.Documents.DocumentCollection collection, string gremlinExpression, Microsoft.Azure.Documents.Client.FeedOptions feedOptions = null, Microsoft.Azure.Graphs.GraphSONMode graphSONMode = Microsoft.Azure.Graphs.GraphSONMode.Compact);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.Linq.IDocumentQuery`1&lt;!!T&gt; CreateGremlinQuery&lt;T&gt;(class Microsoft.Azure.Documents.Client.DocumentClient documentClient, class Microsoft.Azure.Documents.DocumentCollection collection, string gremlinExpression, class Microsoft.Azure.Documents.Client.FeedOptions feedOptions, valuetype Microsoft.Azure.Graphs.GraphSONMode graphSONMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.GraphExtensions.CreateGremlinQuery``1(Microsoft.Azure.Documents.Client.DocumentClient,Microsoft.Azure.Documents.DocumentCollection,System.String,Microsoft.Azure.Documents.Client.FeedOptions,Microsoft.Azure.Graphs.GraphSONMode)" />
      <MemberSignature Language="F#" Value="static member CreateGremlinQuery : Microsoft.Azure.Documents.Client.DocumentClient * Microsoft.Azure.Documents.DocumentCollection * string * Microsoft.Azure.Documents.Client.FeedOptions * Microsoft.Azure.Graphs.GraphSONMode -&gt; Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;'T&gt;" Usage="Microsoft.Azure.Graphs.GraphExtensions.CreateGremlinQuery (documentClient, collection, gremlinExpression, feedOptions, graphSONMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="documentClient" Type="Microsoft.Azure.Documents.Client.DocumentClient" RefType="this" />
        <Parameter Name="collection" Type="Microsoft.Azure.Documents.DocumentCollection" />
        <Parameter Name="gremlinExpression" Type="System.String" />
        <Parameter Name="feedOptions" Type="Microsoft.Azure.Documents.Client.FeedOptions" />
        <Parameter Name="graphSONMode" Type="Microsoft.Azure.Graphs.GraphSONMode" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="beb81-113">照会するオブジェクトの型。</span><span class="sxs-lookup"><span data-stu-id="beb81-113">Type of the object to query.</span></span></typeparam>
        <param name="documentClient"><span data-ttu-id="beb81-114">クエリを実行する DocumentClient インスタンス。</span><span class="sxs-lookup"><span data-stu-id="beb81-114">The DocumentClient instance to execute the query.</span></span></param>
        <param name="collection"><span data-ttu-id="beb81-115">グラフのクエリを含む DocumentCollection です。</span><span class="sxs-lookup"><span data-stu-id="beb81-115">The DocumentCollection that contains the graph to query.</span></span></param>
        <param name="gremlinExpression"><span data-ttu-id="beb81-116">Gremlin 式です。</span><span class="sxs-lookup"><span data-stu-id="beb81-116">The Gremlin expression.</span></span></param>
        <param name="feedOptions"><span data-ttu-id="beb81-117">クエリ結果のフィードの処理のオプションです。</span><span class="sxs-lookup"><span data-stu-id="beb81-117">The options for processing the query result feed.</span></span> <span data-ttu-id="beb81-118">詳細については<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />します。</span><span class="sxs-lookup"><span data-stu-id="beb81-118">For details <see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />.</span></span></param>
        <param name="graphSONMode"><span data-ttu-id="beb81-119">クエリの結果を返すときに使用する GraphSON モードです。</span><span class="sxs-lookup"><span data-stu-id="beb81-119">The GraphSON mode to use when returning the results of the query.</span></span></param>
        <summary>
            <span data-ttu-id="beb81-120">Azure CosmosDB コレクションに格納されているグラフ要素の作成/クエリ Gremlin 式を作成するメソッドです。</span><span class="sxs-lookup"><span data-stu-id="beb81-120">Method to create a Gremlin expression to create/query graph elements stored under an Azure CosmosDB collection.</span></span>
            </summary>
        <returns><span data-ttu-id="beb81-121"><see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" />クエリを評価することができます。</span><span class="sxs-lookup"><span data-stu-id="beb81-121">An <see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" /> that can evaluate the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>