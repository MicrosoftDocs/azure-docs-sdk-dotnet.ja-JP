<Type Name="CassandraSource" FullName="Microsoft.Azure.Management.DataFactory.Models.CassandraSource">
  <TypeSignature Language="C#" Value="public class CassandraSource : Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CassandraSource extends Microsoft.Azure.Management.DataFactory.Models.CopySource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.CassandraSource" />
  <TypeSignature Language="VB.NET" Value="Public Class CassandraSource&#xA;Inherits CopySource" />
  <TypeSignature Language="F#" Value="type CassandraSource = class&#xA;    inherit CopySource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.CopySource</BaseTypeName>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CassandraSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CassandraSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CassandraSource (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object sourceRetryCount = null, object sourceRetryWait = null, object query = null, string consistencyLevel = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object sourceRetryCount, object sourceRetryWait, object query, string consistencyLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.CassandraSource.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Object,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional sourceRetryCount As Object = null, Optional sourceRetryWait As Object = null, Optional query As Object = null, Optional consistencyLevel As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.CassandraSource : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * obj * string -&gt; Microsoft.Azure.Management.DataFactory.Models.CassandraSource" Usage="new Microsoft.Azure.Management.DataFactory.Models.CassandraSource (additionalProperties, sourceRetryCount, sourceRetryWait, query, consistencyLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="sourceRetryCount" Type="System.Object" />
        <Parameter Name="sourceRetryWait" Type="System.Object" />
        <Parameter Name="query" Type="System.Object" />
        <Parameter Name="consistencyLevel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</param>
        <param name="sourceRetryCount">ソースの再試行回数です。 型: 整数 (または式に整数の resultType)。</param>
        <param name="sourceRetryWait">ソースの再試行の待機です。 型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</param>
        <param name="query">データベースのクエリ。 SQL 92 クエリ式または Cassandra クエリ言語 (CQL) コマンドを指定する必要があります。 型: 文字列 (または式の resultType 文字列)。</param>
        <param name="consistencyLevel">整合性レベルでは、Cassandra サーバーの数は、クライアント アプリケーションにデータを返す前に読み取り要求に応答する必要がありますを指定します。 Cassandra では、指定したデータの読み取り要求を満たすために Cassandra サーバー数を確認します。 CassandraSourceReadConsistencyLevels のいずれかを指定する必要があります。 既定値は '1' です。 小文字は区別されません。 使用可能な値が含まれます: 'すべて'、'EACH_QUORUM'、'クォーラム'、'LOCAL_QUORUM'、'ONE'、'2'、'3'、'LOCAL_ONE'、'シリアル'、'LOCAL_SERIAL'</param>
        <summary>
            CassandraSource クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsistencyLevel">
      <MemberSignature Language="C#" Value="public string ConsistencyLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsistencyLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CassandraSource.ConsistencyLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsistencyLevel As String" />
      <MemberSignature Language="F#" Value="member this.ConsistencyLevel : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CassandraSource.ConsistencyLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="consistencyLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の一貫性レベルは、Cassandra サーバーの数は、クライアント アプリケーションにデータを返す前に読み取り要求に応答する必要がありますを指定します。 Cassandra では、指定したデータの読み取り要求を満たすために Cassandra サーバー数を確認します。 CassandraSourceReadConsistencyLevels のいずれかを指定する必要があります。 既定値は '1' です。 小文字は区別されません。 使用可能な値が含まれます: 'すべて'、'EACH_QUORUM'、'クォーラム'、'LOCAL_QUORUM'、'ONE'、'2'、'3'、'LOCAL_ONE'、'シリアル'、'LOCAL_SERIAL'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public object Query { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Query" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.CassandraSource.Query" />
      <MemberSignature Language="VB.NET" Value="Public Property Query As Object" />
      <MemberSignature Language="F#" Value="member this.Query : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.CassandraSource.Query" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="query")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはデータベース クエリを設定します。 SQL 92 クエリ式または Cassandra クエリ言語 (CQL) コマンドを指定する必要があります。 型: 文字列 (または式の resultType 文字列)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>