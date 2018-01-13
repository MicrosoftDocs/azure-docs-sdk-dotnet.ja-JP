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
            このクラスを変換する拡張メソッドを提供する、<see cref="T:System.Linq.IQueryable`1" />オブジェクトを<see cref="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" />オブジェクト。
            </summary>
    <remarks>
             <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />クラス Azure Cosmos DB 内のリソースを照会するための標準クエリ メソッドの実装を提供します。 これらのメソッドには、Azure Cosmos DB サービスの永続化すると、高速の走査、フィルター、およびデータに対する射影操作が有効にします。  IQueryable を拡張し、任意の直接クエリを実行しないメソッドとして定義されます。  代わりに、それらの機能は、基に指定されたリソースとクエリの式のクエリを作成するのにです。  実際のクエリの実行は、列挙型が実行される IQueryable オブジェクトに関連付けられている式ツリーを強制した場合に発生します。
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
        <typeparam name="T">照会するオブジェクトの型。</typeparam>
        <param name="query">変換するには、{T} の IQueryable。</param>
        <summary>
            Azure Cosmos DB サービスの改ページ調整と非同期実行をサポートする IDocumentQuery IQueryable に変換します。
            </summary>
        <returns>クエリを評価できる IDocumentQuery {t} です。</returns>
        <remarks>To be added.</remarks>
        <example>
            この例では、非同期的に AsDocumentQuery() インターフェイスを使用してクエリを実行する方法を示します。
            
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの平均を計算<see cref="T:System.Decimal" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの平均を計算<see cref="T:System.Double" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの平均を計算<see cref="T:System.Int32" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの平均を計算<see cref="T:System.Int64" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの平均を計算<see cref="T:System.Nullable`1" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの平均を計算<see cref="T:System.Nullable`1" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの平均を計算<see cref="T:System.Nullable`1" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの平均を計算<see cref="T:System.Nullable`1" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの平均を計算<see cref="T:System.Nullable`1" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの平均を計算<see cref="T:System.Single" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <typeparam name="TSource">source の要素の型。</typeparam>
        <param name="source">カウントする要素を格納しているシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンス内の要素の数を返します。
            </summary>
        <returns>入力シーケンス内の要素数。</returns>
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
        <typeparam name="TSource">source の要素の型。</typeparam>
        <param name="source">最大数を決定する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            ジェネリック型の最大値を返します<see cref="T:System.Linq.IQueryable`1" />です。
            </summary>
        <returns>シーケンスの最大値。</returns>
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
        <typeparam name="TSource">source の要素の型。</typeparam>
        <param name="source">最小値を決定する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            ジェネリック型の最小値を返します<see cref="T:System.Linq.IQueryable`1" />です。
            </summary>
        <returns>シーケンスの最小値。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの合計を計算<see cref="T:System.Decimal" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの合計を計算<see cref="T:System.Double" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの合計を計算<see cref="T:System.Int32" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの合計を計算<see cref="T:System.Int64" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの合計を計算<see cref="T:System.Nullable`1" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの合計を計算<see cref="T:System.Nullable`1" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの合計を計算<see cref="T:System.Nullable`1" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの合計を計算<see cref="T:System.Nullable`1" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの合計を計算<see cref="T:System.Nullable`1" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
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
        <param name="source">平均を計算する値のシーケンス。</param>
        <param name="cancellationToken">キャンセル トークン。</param>
        <summary>
            シーケンスの合計を計算<see cref="T:System.Single" />値。
            </summary>
        <returns>シーケンスの平均値です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>