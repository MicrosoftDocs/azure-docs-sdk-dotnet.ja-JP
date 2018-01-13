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
            型のオブジェクトの拡張メソッドのセットを提供<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />です。
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
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <param name="query">実装するクエリ<see cref="T:System.Linq.IQueryable`1" />です。</param>
        <summary>
            クエリとして返すことを指定します、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />オブジェクト。
            </summary>
        <returns><see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> 型のオブジェクト。</returns>
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
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <typeparam name="TResolved">競合回避モジュールの型。</typeparam>
        <param name="query">実装するクエリ<see cref="T:System.Linq.IQueryable`1" />です。</param>
        <param name="resolver">エンティティ リゾルバーは型の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />します。</param>
        <summary>
            クエリのエンティティ リゾルバーを指定します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />と、指定された競合回避モジュール。</returns>
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
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <param name="query">実装するクエリ<see cref="T:System.Linq.IQueryable`1" />です。</param>
        <param name="operationContext"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            指定します、<see cref="T:Microsoft.Azure.Storage.OperationContext" />クエリにします。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />指定された操作コンテキストを持つオブジェクト。</returns>
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
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <param name="query">実装するクエリ<see cref="T:System.Linq.IQueryable`1" />です。</param>
        <param name="options">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <summary>
            セットを示す<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />クエリを実行するとします。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />指定された要求のオプション セットを持つオブジェクト。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.NotSupportedException" />
      </Docs>
    </Member>
  </Members>
</Type>