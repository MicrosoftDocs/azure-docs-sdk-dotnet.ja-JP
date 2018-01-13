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
            Cassandra データベースのコピー活動元。
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
            省略可能。 整合性レベルでは、Cassandra サーバーの数は、クライアント アプリケーションにデータを返す前に読み取り要求に応答する必要がありますを指定します。 Cassandra では、指定したデータの読み取り要求を満たすために Cassandra サーバー数を確認します。 いずれかを指定する必要があります<see cref="T:Microsoft.Azure.Management.DataFactories.Models.CassandraSourceReadConsistencyLevel" />です。
            既定値は、「1」です。
            小文字は区別されません。
            参照: http://docs.datastax.com/en/cassandra/2.0/cassandra/dml/dml_config_consistency_c.html です。
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
            省略可能。 SQL 92 クエリ式または Cassandra クエリ言語 (CQL) コマンドを指定する必要があります。
            CQL 参照: https://docs.datastax.com/en/cql/3.1/cql/cql_reference/cqlReferenceTOC.html です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>