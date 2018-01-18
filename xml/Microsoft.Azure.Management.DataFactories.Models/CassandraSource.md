<Type Name="CassandraSource" FullName="Microsoft.Azure.Management.DataFactories.Models.CassandraSource">
  <TypeSignature Language="C#" Value="public class CassandraSource : Microsoft.Azure.Management.DataFactories.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CassandraSource extends Microsoft.Azure.Management.DataFactories.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.CassandraSource" />
  <TypeSignature Language="VB.NET" Value="Public Class CassandraSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type CassandraSource = class&#xA;    inherit CopySource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.CopySource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="78f78-101">Cassandra データベースのコピー活動元。</span><span class="sxs-lookup"><span data-stu-id="78f78-101">A copy activity source for a Cassandra database.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CassandraSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.CassandraSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsistencyLevel">
      <MemberSignature Language="C#" Value="public string ConsistencyLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsistencyLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.CassandraSource.ConsistencyLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsistencyLevel As String" />
      <MemberSignature Language="F#" Value="member this.ConsistencyLevel : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSource.ConsistencyLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78f78-102">省略可能。</span><span class="sxs-lookup"><span data-stu-id="78f78-102">Optional.</span></span> <span data-ttu-id="78f78-103">整合性レベルでは、Cassandra サーバーの数は、クライアント アプリケーションにデータを返す前に読み取り要求に応答する必要がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="78f78-103">The consistency level specifies how many Cassandra servers must respond to a read request before returning data to the client application.</span></span> <span data-ttu-id="78f78-104">Cassandra では、指定したデータの読み取り要求を満たすために Cassandra サーバー数を確認します。</span><span class="sxs-lookup"><span data-stu-id="78f78-104">Cassandra checks the specified number of Cassandra servers for data to satisfy the read request.</span></span> <span data-ttu-id="78f78-105">いずれかを指定する必要があります<see cref="T:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="78f78-105">Must be one of <see cref="T:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel" />.</span></span>
            <span data-ttu-id="78f78-106">既定値は、「1」です。</span><span class="sxs-lookup"><span data-stu-id="78f78-106">The default value is "ONE".</span></span>
            <span data-ttu-id="78f78-107">小文字は区別されません。</span><span class="sxs-lookup"><span data-stu-id="78f78-107">It is case-insensitive.</span></span>
            <span data-ttu-id="78f78-108">参照: http://docs.datastax.com/en/cassandra/2.0/cassandra/dml/dml_config_consistency_c.html です。</span><span class="sxs-lookup"><span data-stu-id="78f78-108">Reference: http://docs.datastax.com/en/cassandra/2.0/cassandra/dml/dml_config_consistency_c.html.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public string Query { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Query" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.CassandraSource.Query" />
      <MemberSignature Language="VB.NET" Value="Public Property Query As String" />
      <MemberSignature Language="F#" Value="member this.Query : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.CassandraSource.Query" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="78f78-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="78f78-109">Optional.</span></span> <span data-ttu-id="78f78-110">SQL 92 クエリ式または Cassandra クエリ言語 (CQL) コマンドを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="78f78-110">Should be a SQL-92 query expression or Cassandra Query Language (CQL) command.</span></span>
            <span data-ttu-id="78f78-111">CQL 参照: https://docs.datastax.com/en/cql/3.1/cql/cql_reference/cqlReferenceTOC.html です。</span><span class="sxs-lookup"><span data-stu-id="78f78-111">CQL reference: https://docs.datastax.com/en/cql/3.1/cql/cql_reference/cqlReferenceTOC.html.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>