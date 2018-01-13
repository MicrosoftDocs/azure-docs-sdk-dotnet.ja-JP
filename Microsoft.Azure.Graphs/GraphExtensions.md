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
            このクラスの種類のグラフのクエリを作成するための拡張メソッドを提供する<see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" />です。
            これらのクエリは、Azure DocumentDB コレクションに対して実行されます。
            </summary>
    <remarks>
            クラスを拡張<see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />クラス データに対する高速グラフ走査および CRUD 操作を有効にするには、Azure DocumentDB コレクションで永続化します。 返された<see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" />オブジェクトが、実際のクエリの実行をラップして、これらのオブジェクトを列挙する強制的に実行される Azure DocumentDB クエリです。
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
        <param name="documentClient">クエリを実行する DocumentClient インスタンス。</param>
        <param name="collection">グラフのクエリを含む DocumentCollection です。</param>
        <param name="gremlinExpression">Gremlin 式です。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />します。</param>
        <param name="graphSONMode">クエリの結果を返すときに使用する GraphSON モードです。</param>
        <summary>
            Azure CosmosDB コレクションに格納されているグラフ要素の作成/クエリ Gremlin 式を作成するメソッドです。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" />クエリを評価することができます。</returns>
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
        <typeparam name="T">照会するオブジェクトの型。</typeparam>
        <param name="documentClient">クエリを実行する DocumentClient インスタンス。</param>
        <param name="collection">グラフのクエリを含む DocumentCollection です。</param>
        <param name="gremlinExpression">Gremlin 式です。</param>
        <param name="feedOptions">クエリ結果のフィードの処理のオプションです。 詳細については<see cref="T:Microsoft.Azure.Documents.Client.FeedOptions" />します。</param>
        <param name="graphSONMode">クエリの結果を返すときに使用する GraphSON モードです。</param>
        <summary>
            Azure CosmosDB コレクションに格納されているグラフ要素の作成/クエリ Gremlin 式を作成するメソッドです。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" />クエリを評価することができます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>