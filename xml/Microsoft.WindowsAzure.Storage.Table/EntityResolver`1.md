<Type Name="EntityResolver&lt;T&gt;" FullName="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;T&gt;">
  <TypeSignature Language="C#" Value="public delegate T EntityResolver&lt;T&gt;(string partitionKey, string rowKey, DateTimeOffset timestamp, IDictionary&lt;string,EntityProperty&gt; properties, string etag);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed EntityResolver`1&lt;T&gt; extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function EntityResolver(Of T)(partitionKey As String, rowKey As String, timestamp As DateTimeOffset, properties As IDictionary(Of String, EntityProperty), etag As String) As T " />
  <TypeSignature Language="F#" Value="type EntityResolver&lt;'T&gt; = delegate of string * string * DateTimeOffset * IDictionary&lt;string, EntityProperty&gt; * string -&gt; 'T" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="partitionKey" Type="System.String" />
    <Parameter Name="rowKey" Type="System.String" />
    <Parameter Name="timestamp" Type="System.DateTimeOffset" />
    <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
    <Parameter Name="etag" Type="System.String" />
  </Parameters>
  <ReturnValue>
    <ReturnType>T</ReturnType>
  </ReturnValue>
  <Docs>
    <typeparam name="T"><span data-ttu-id="b111e-101">クエリ結果の射影先の型。</span><span class="sxs-lookup"><span data-stu-id="b111e-101">The type into which the query results are projected.</span></span></typeparam>
    <param name="partitionKey"><span data-ttu-id="b111e-102">エンティティのパーティション キーを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="b111e-102">A string containing the partition key for the entity.</span></span></param>
    <param name="rowKey"><span data-ttu-id="b111e-103">エンティティの行キーを含む文字列。</span><span class="sxs-lookup"><span data-stu-id="b111e-103">A string containing the row key for the entity.</span></span></param>
    <param name="timestamp"><span data-ttu-id="b111e-104">A<see cref="T:System.DateTimeOffset" />エンティティのタイムスタンプを表すです。</span><span class="sxs-lookup"><span data-stu-id="b111e-104">A <see cref="T:System.DateTimeOffset" /> containing the timestamp for the entity.</span></span></param>
    <param name="properties"><span data-ttu-id="b111e-105"><see cref="T:System.Collections.Generic.IDictionary`2" />エンティティのプロパティを含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b111e-105">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object containing the properties for the entity.</span></span></param>
    <param name="etag"><span data-ttu-id="b111e-106">ETag。</span><span class="sxs-lookup"><span data-stu-id="b111e-106">The ETag.</span></span></param>
    <summary>
            <span data-ttu-id="b111e-107">エンティティを解決するには、デリゲートを返します。</span><span class="sxs-lookup"><span data-stu-id="b111e-107">Returns a delegate for resolving entities.</span></span>
            </summary>
    <returns />
    <remarks>To be added.</remarks>
  </Docs>
</Type>