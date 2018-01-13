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
            <span data-ttu-id="de3d2-101">Cassandra データベースのコピー活動元。</span><span class="sxs-lookup"><span data-stu-id="de3d2-101">A copy activity source for a Cassandra database.</span></span>
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
            <span data-ttu-id="de3d2-102">CassandraSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="de3d2-102">Initializes a new instance of the CassandraSource class.</span></span>
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
        <param name="additionalProperties"><span data-ttu-id="de3d2-103">メッセージから一致しないプロパティを逆シリアル化は、このコレクション</span><span class="sxs-lookup"><span data-stu-id="de3d2-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="sourceRetryCount"><span data-ttu-id="de3d2-104">ソースの再試行回数です。</span><span class="sxs-lookup"><span data-stu-id="de3d2-104">Source retry count.</span></span> <span data-ttu-id="de3d2-105">型: 整数 (または式に整数の resultType)。</span><span class="sxs-lookup"><span data-stu-id="de3d2-105">Type: integer (or Expression with resultType integer).</span></span></param>
        <param name="sourceRetryWait"><span data-ttu-id="de3d2-106">ソースの再試行の待機です。</span><span class="sxs-lookup"><span data-stu-id="de3d2-106">Source retry wait.</span></span> <span data-ttu-id="de3d2-107">型: 文字列 (または式の resultType 文字列)、パターン: ((\d+)\.)? (\d\d):(60|([0-5][0-9])): (60 |([0-5][0-9])) です。</span><span class="sxs-lookup"><span data-stu-id="de3d2-107">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="query"><span data-ttu-id="de3d2-108">データベースのクエリ。</span><span class="sxs-lookup"><span data-stu-id="de3d2-108">Database query.</span></span> <span data-ttu-id="de3d2-109">SQL 92 クエリ式または Cassandra クエリ言語 (CQL) コマンドを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="de3d2-109">Should be a SQL-92 query expression or Cassandra Query Language (CQL) command.</span></span> <span data-ttu-id="de3d2-110">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="de3d2-110">Type: string (or Expression with resultType string).</span></span></param>
        <param name="consistencyLevel"><span data-ttu-id="de3d2-111">整合性レベルでは、Cassandra サーバーの数は、クライアント アプリケーションにデータを返す前に読み取り要求に応答する必要がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="de3d2-111">The consistency level specifies how many Cassandra servers must respond to a read request before returning data to the client application.</span></span> <span data-ttu-id="de3d2-112">Cassandra では、指定したデータの読み取り要求を満たすために Cassandra サーバー数を確認します。</span><span class="sxs-lookup"><span data-stu-id="de3d2-112">Cassandra checks the specified number of Cassandra servers for data to satisfy the read request.</span></span> <span data-ttu-id="de3d2-113">CassandraSourceReadConsistencyLevels のいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="de3d2-113">Must be one of cassandraSourceReadConsistencyLevels.</span></span> <span data-ttu-id="de3d2-114">既定値は '1' です。</span><span class="sxs-lookup"><span data-stu-id="de3d2-114">The default value is 'ONE'.</span></span> <span data-ttu-id="de3d2-115">小文字は区別されません。</span><span class="sxs-lookup"><span data-stu-id="de3d2-115">It is case-insensitive.</span></span> <span data-ttu-id="de3d2-116">使用可能な値が含まれます: 'すべて'、'EACH_QUORUM'、'クォーラム'、'LOCAL_QUORUM'、'ONE'、'2'、'3'、'LOCAL_ONE'、'シリアル'、'LOCAL_SERIAL'</span><span class="sxs-lookup"><span data-stu-id="de3d2-116">Possible values include: 'ALL', 'EACH_QUORUM', 'QUORUM', 'LOCAL_QUORUM', 'ONE', 'TWO', 'THREE', 'LOCAL_ONE', 'SERIAL', 'LOCAL_SERIAL'</span></span></param>
        <summary>
            <span data-ttu-id="de3d2-117">CassandraSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="de3d2-117">Initializes a new instance of the CassandraSource class.</span></span>
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
            <span data-ttu-id="de3d2-118">取得または設定の一貫性レベルは、Cassandra サーバーの数は、クライアント アプリケーションにデータを返す前に読み取り要求に応答する必要がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="de3d2-118">Gets or sets the consistency level specifies how many Cassandra servers must respond to a read request before returning data to the client application.</span></span> <span data-ttu-id="de3d2-119">Cassandra では、指定したデータの読み取り要求を満たすために Cassandra サーバー数を確認します。</span><span class="sxs-lookup"><span data-stu-id="de3d2-119">Cassandra checks the specified number of Cassandra servers for data to satisfy the read request.</span></span> <span data-ttu-id="de3d2-120">CassandraSourceReadConsistencyLevels のいずれかを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="de3d2-120">Must be one of cassandraSourceReadConsistencyLevels.</span></span> <span data-ttu-id="de3d2-121">既定値は '1' です。</span><span class="sxs-lookup"><span data-stu-id="de3d2-121">The default value is 'ONE'.</span></span> <span data-ttu-id="de3d2-122">小文字は区別されません。</span><span class="sxs-lookup"><span data-stu-id="de3d2-122">It is case-insensitive.</span></span> <span data-ttu-id="de3d2-123">使用可能な値が含まれます: 'すべて'、'EACH_QUORUM'、'クォーラム'、'LOCAL_QUORUM'、'ONE'、'2'、'3'、'LOCAL_ONE'、'シリアル'、'LOCAL_SERIAL'</span><span class="sxs-lookup"><span data-stu-id="de3d2-123">Possible values include: 'ALL', 'EACH_QUORUM', 'QUORUM', 'LOCAL_QUORUM', 'ONE', 'TWO', 'THREE', 'LOCAL_ONE', 'SERIAL', 'LOCAL_SERIAL'</span></span>
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
            <span data-ttu-id="de3d2-124">取得またはデータベース クエリを設定します。</span><span class="sxs-lookup"><span data-stu-id="de3d2-124">Gets or sets database query.</span></span> <span data-ttu-id="de3d2-125">SQL 92 クエリ式または Cassandra クエリ言語 (CQL) コマンドを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="de3d2-125">Should be a SQL-92 query expression or Cassandra Query Language (CQL) command.</span></span> <span data-ttu-id="de3d2-126">型: 文字列 (または式の resultType 文字列)。</span><span class="sxs-lookup"><span data-stu-id="de3d2-126">Type: string (or Expression with resultType string).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>