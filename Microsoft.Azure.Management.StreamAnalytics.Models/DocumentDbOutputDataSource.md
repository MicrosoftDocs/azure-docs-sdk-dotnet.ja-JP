<Type Name="DocumentDbOutputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource">
  <TypeSignature Language="C#" Value="public class DocumentDbOutputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DocumentDbOutputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class DocumentDbOutputDataSource&#xA;Inherits OutputDataSource" />
  <TypeSignature Language="F#" Value="type DocumentDbOutputDataSource = class&#xA;    inherit OutputDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Storage/DocumentDB")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="22922-101">DocumentDB 出力のデータ ソースをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="22922-101">Describes a DocumentDB output data source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentDbOutputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="22922-102">DocumentDbOutputDataSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="22922-102">Initializes a new instance of the DocumentDbOutputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentDbOutputDataSource (string accountId = null, string accountKey = null, string database = null, string collectionNamePattern = null, string partitionKey = null, string documentId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountId, string accountKey, string database, string collectionNamePattern, string partitionKey, string documentId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional accountId As String = null, Optional accountKey As String = null, Optional database As String = null, Optional collectionNamePattern As String = null, Optional partitionKey As String = null, Optional documentId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource : string * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource (accountId, accountKey, database, collectionNamePattern, partitionKey, documentId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountId" Type="System.String" />
        <Parameter Name="accountKey" Type="System.String" />
        <Parameter Name="database" Type="System.String" />
        <Parameter Name="collectionNamePattern" Type="System.String" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="documentId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountId"><span data-ttu-id="22922-103">DocumentDB アカウントの名前または id。</span><span class="sxs-lookup"><span data-stu-id="22922-103">The DocumentDB account name or ID.</span></span> <span data-ttu-id="22922-104">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="22922-104">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="accountKey"><span data-ttu-id="22922-105">DocumentDB アカウントのアカウント キー。</span><span class="sxs-lookup"><span data-stu-id="22922-105">The account key for the DocumentDB account.</span></span> <span data-ttu-id="22922-106">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="22922-106">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="database"><span data-ttu-id="22922-107">DocumentDB データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="22922-107">The name of the DocumentDB database.</span></span>
            <span data-ttu-id="22922-108">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="22922-108">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="collectionNamePattern"><span data-ttu-id="22922-109">使用するコレクションのコレクション名のパターン。</span><span class="sxs-lookup"><span data-stu-id="22922-109">The collection name pattern for the collections to be used.</span></span> <span data-ttu-id="22922-110">コレクション名の形式は、オプションの {partition} トークンを使用して構成できます。この場合、パーティションは 0 から開始します。</span><span class="sxs-lookup"><span data-stu-id="22922-110">The collection name format can be constructed using the optional {partition} token, where partitions start from 0.</span></span> <span data-ttu-id="22922-111">詳細については https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output の DocumentDB セクションを参照してください。</span><span class="sxs-lookup"><span data-stu-id="22922-111">See the DocumentDB section of https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output for more information.</span></span> <span data-ttu-id="22922-112">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="22922-112">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="partitionKey"><span data-ttu-id="22922-113">コレクション全体で出力をパーティション分割するためのキーを指定するために使用される、出力イベント内のフィールドの名前。</span><span class="sxs-lookup"><span data-stu-id="22922-113">The name of the field in output events used to specify the key for partitioning output across collections.</span></span>
            <span data-ttu-id="22922-114">'CollectionNamePattern' {partition} トークンが含まれている場合、このプロパティを指定する必要です。</span><span class="sxs-lookup"><span data-stu-id="22922-114">If 'collectionNamePattern' contains the {partition} token, this property is required to be specified.</span></span></param>
        <param name="documentId"><span data-ttu-id="22922-115">挿入または更新操作の基準となるプライマリ キーを指定するために使用される、出力イベント内のフィールドの名前。</span><span class="sxs-lookup"><span data-stu-id="22922-115">The name of the field in output events used to specify the primary key which insert or update operations are based on.</span></span></param>
        <summary>
            <span data-ttu-id="22922-116">DocumentDbOutputDataSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="22922-116">Initializes a new instance of the DocumentDbOutputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountId">
      <MemberSignature Language="C#" Value="public string AccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.AccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountId As String" />
      <MemberSignature Language="F#" Value="member this.AccountId : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.AccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22922-117">DocumentDB アカウントの名前または id。 取得または設定</span><span class="sxs-lookup"><span data-stu-id="22922-117">Gets or sets the DocumentDB account name or ID.</span></span> <span data-ttu-id="22922-118">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="22922-118">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountKey">
      <MemberSignature Language="C#" Value="public string AccountKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.AccountKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountKey As String" />
      <MemberSignature Language="F#" Value="member this.AccountKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.AccountKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accountKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22922-119">取得または DocumentDB アカウントのアカウント キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="22922-119">Gets or sets the account key for the DocumentDB account.</span></span> <span data-ttu-id="22922-120">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="22922-120">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionNamePattern">
      <MemberSignature Language="C#" Value="public string CollectionNamePattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CollectionNamePattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.CollectionNamePattern" />
      <MemberSignature Language="VB.NET" Value="Public Property CollectionNamePattern As String" />
      <MemberSignature Language="F#" Value="member this.CollectionNamePattern : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.CollectionNamePattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.collectionNamePattern")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22922-121">取得または使用するコレクションのコレクション名のパターンを設定します。</span><span class="sxs-lookup"><span data-stu-id="22922-121">Gets or sets the collection name pattern for the collections to be used.</span></span> <span data-ttu-id="22922-122">コレクション名の形式は、オプションの {partition} トークンを使用して構成できます。この場合、パーティションは 0 から開始します。</span><span class="sxs-lookup"><span data-stu-id="22922-122">The collection name format can be constructed using the optional {partition} token, where partitions start from 0.</span></span> <span data-ttu-id="22922-123">詳細については https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output の DocumentDB セクションを参照してください。</span><span class="sxs-lookup"><span data-stu-id="22922-123">See the DocumentDB section of https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output for more information.</span></span> <span data-ttu-id="22922-124">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="22922-124">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Database">
      <MemberSignature Language="C#" Value="public string Database { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Database" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.Database" />
      <MemberSignature Language="VB.NET" Value="Public Property Database As String" />
      <MemberSignature Language="F#" Value="member this.Database : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.Database" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.database")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22922-125">取得または DocumentDB データベースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="22922-125">Gets or sets the name of the DocumentDB database.</span></span> <span data-ttu-id="22922-126">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="22922-126">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DocumentId">
      <MemberSignature Language="C#" Value="public string DocumentId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DocumentId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.DocumentId" />
      <MemberSignature Language="VB.NET" Value="Public Property DocumentId As String" />
      <MemberSignature Language="F#" Value="member this.DocumentId : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.DocumentId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.documentId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22922-127">取得または出力を挿入または更新操作を主キーを指定するために使用イベントがに基づいて、フィールドの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="22922-127">Gets or sets the name of the field in output events used to specify the primary key which insert or update operations are based on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.DocumentDbOutputDataSource.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partitionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22922-128">取得または出力をパーティション分割コレクション間でのキーを指定するために使用する出力イベント内のフィールドの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="22922-128">Gets or sets the name of the field in output events used to specify the key for partitioning output across collections.</span></span> <span data-ttu-id="22922-129">'CollectionNamePattern' {partition} トークンが含まれている場合、このプロパティを指定する必要です。</span><span class="sxs-lookup"><span data-stu-id="22922-129">If 'collectionNamePattern' contains the {partition} token, this property is required to be specified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>