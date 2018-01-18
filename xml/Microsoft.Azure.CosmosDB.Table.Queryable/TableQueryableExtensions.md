<Type Name="TableQueryableExtensions" FullName="Microsoft.Azure.CosmosDB.Table.Queryable.TableQueryableExtensions">
  <TypeSignature Language="C#" Value="public static class TableQueryableExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed TableQueryableExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.Queryable.TableQueryableExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TableQueryableExtensions" />
  <TypeSignature Language="F#" Value="type TableQueryableExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9466e-101">型のオブジェクトの拡張メソッドのセットを提供<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />です。</span><span class="sxs-lookup"><span data-stu-id="9466e-101">Provides a set of extension methods for objects of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AsTableQuery&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; AsTableQuery&lt;TElement&gt; (this System.Linq.IQueryable&lt;TElement&gt; query);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; AsTableQuery&lt;TElement&gt;(class System.Linq.IQueryable`1&lt;!!TElement&gt; query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Queryable.TableQueryableExtensions.AsTableQuery``1(System.Linq.IQueryable{``0})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function AsTableQuery(Of TElement) (query As IQueryable(Of TElement)) As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="static member AsTableQuery : System.Linq.IQueryable&lt;'Element&gt; -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element&gt;" Usage="Microsoft.Azure.CosmosDB.Table.Queryable.TableQueryableExtensions.AsTableQuery query" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;TElement&gt;" RefType="this" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="9466e-102">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="9466e-102">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="9466e-103">実装するクエリ<see cref="T:System.Linq.IQueryable`1" />です。</span><span class="sxs-lookup"><span data-stu-id="9466e-103">A query that implements <see cref="T:System.Linq.IQueryable`1" />.</span></span></param>
        <summary>
            <span data-ttu-id="9466e-104">クエリとして返すことを指定します、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9466e-104">Specifies that a query be returned as a <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> object.</span></span>
            </summary>
        <returns><span data-ttu-id="9466e-105"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> 型のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9466e-105">An object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NotSupportedException" />
      </Docs>
    </Member>
    <Member MemberName="Resolve&lt;TElement,TResolved&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TResolved&gt; Resolve&lt;TElement,TResolved&gt; (this System.Linq.IQueryable&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResolved&gt; resolver);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TResolved&gt; Resolve&lt;TElement, TResolved&gt;(class System.Linq.IQueryable`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResolved&gt; resolver) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Queryable.TableQueryableExtensions.Resolve``2(System.Linq.IQueryable{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Resolve(Of TElement, TResolved) (query As IQueryable(Of TElement), resolver As EntityResolver(Of TResolved)) As TableQuery(Of TResolved)" />
      <MemberSignature Language="F#" Value="static member Resolve : System.Linq.IQueryable&lt;'Element&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Resolved&gt; -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Resolved&gt;" Usage="Microsoft.Azure.CosmosDB.Table.Queryable.TableQueryableExtensions.Resolve (query, resolver)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TResolved&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement" />
        <TypeParameter Name="TResolved" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;TElement&gt;" RefType="this" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResolved&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="9466e-106">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="9466e-106">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResolved"><span data-ttu-id="9466e-107">競合回避モジュールの型。</span><span class="sxs-lookup"><span data-stu-id="9466e-107">The type of the resolver.</span></span></typeparam>
        <param name="query"><span data-ttu-id="9466e-108">実装するクエリ<see cref="T:System.Linq.IQueryable`1" />です。</span><span class="sxs-lookup"><span data-stu-id="9466e-108">A query that implements <see cref="T:System.Linq.IQueryable`1" />.</span></span></param>
        <param name="resolver"><span data-ttu-id="9466e-109">エンティティ リゾルバーは型の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />します。</span><span class="sxs-lookup"><span data-stu-id="9466e-109">The entity resolver, of type <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />.</span></span></param>
        <summary>
            <span data-ttu-id="9466e-110">クエリのエンティティ リゾルバーを指定します。</span><span class="sxs-lookup"><span data-stu-id="9466e-110">Specifies an entity resolver for the query.</span></span>
            </summary>
        <returns><span data-ttu-id="9466e-111">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />と、指定された競合回避モジュール。</span><span class="sxs-lookup"><span data-stu-id="9466e-111">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> with the specified resolver.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NotSupportedException" />
      </Docs>
    </Member>
    <Member MemberName="WithContext&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; WithContext&lt;TElement&gt; (this System.Linq.IQueryable&lt;TElement&gt; query, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; WithContext&lt;TElement&gt;(class System.Linq.IQueryable`1&lt;!!TElement&gt; query, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Queryable.TableQueryableExtensions.WithContext``1(System.Linq.IQueryable{``0},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member WithContext : System.Linq.IQueryable&lt;'Element&gt; * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element&gt;" Usage="Microsoft.Azure.CosmosDB.Table.Queryable.TableQueryableExtensions.WithContext (query, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;TElement&gt;" RefType="this" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="9466e-112">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="9466e-112">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="9466e-113">実装するクエリ<see cref="T:System.Linq.IQueryable`1" />です。</span><span class="sxs-lookup"><span data-stu-id="9466e-113">A query that implements <see cref="T:System.Linq.IQueryable`1" />.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9466e-114"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9466e-114">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9466e-115">指定します、<see cref="T:Microsoft.Azure.Storage.OperationContext" />クエリにします。</span><span class="sxs-lookup"><span data-stu-id="9466e-115">Specifies an <see cref="T:Microsoft.Azure.Storage.OperationContext" /> for the query.</span></span>
            </summary>
        <returns><span data-ttu-id="9466e-116">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />指定された操作コンテキストを持つオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9466e-116">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> object with the specified operation context.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NotSupportedException" />
      </Docs>
    </Member>
    <Member MemberName="WithOptions&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; WithOptions&lt;TElement&gt; (this System.Linq.IQueryable&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableRequestOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; WithOptions&lt;TElement&gt;(class System.Linq.IQueryable`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.Queryable.TableQueryableExtensions.WithOptions``1(System.Linq.IQueryable{``0},Microsoft.Azure.CosmosDB.Table.TableRequestOptions)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function WithOptions(Of TElement) (query As IQueryable(Of TElement), options As TableRequestOptions) As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="static member WithOptions : System.Linq.IQueryable&lt;'Element&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element&gt;" Usage="Microsoft.Azure.CosmosDB.Table.Queryable.TableQueryableExtensions.WithOptions (query, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;TElement&gt;" RefType="this" />
        <Parameter Name="options" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="9466e-117">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="9466e-117">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="9466e-118">実装するクエリ<see cref="T:System.Linq.IQueryable`1" />です。</span><span class="sxs-lookup"><span data-stu-id="9466e-118">A query that implements <see cref="T:System.Linq.IQueryable`1" />.</span></span></param>
        <param name="options"><span data-ttu-id="9466e-119">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9466e-119">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <summary>
            <span data-ttu-id="9466e-120">セットを示す<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />クエリを実行するとします。</span><span class="sxs-lookup"><span data-stu-id="9466e-120">Specifies a set of <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> with which the query will be executed.</span></span>
            </summary>
        <returns><span data-ttu-id="9466e-121">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />指定された要求のオプション セットを持つオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9466e-121">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> object with the specified request options set.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NotSupportedException" />
      </Docs>
    </Member>
  </Members>
</Type>