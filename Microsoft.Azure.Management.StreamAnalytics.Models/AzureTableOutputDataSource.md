<Type Name="AzureTableOutputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource">
  <TypeSignature Language="C#" Value="public class AzureTableOutputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureTableOutputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureTableOutputDataSource&#xA;Inherits OutputDataSource" />
  <TypeSignature Language="F#" Value="type AzureTableOutputDataSource = class&#xA;    inherit OutputDataSource" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Storage/Table")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3fc72-101">Azure Table 出力のデータ ソースをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="3fc72-101">Describes an Azure Table output data source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableOutputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3fc72-102">AzureTableOutputDataSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3fc72-102">Initializes a new instance of the AzureTableOutputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableOutputDataSource (string accountName = null, string accountKey = null, string table = null, string partitionKey = null, string rowKey = null, System.Collections.Generic.IList&lt;string&gt; columnsToRemove = null, Nullable&lt;int&gt; batchSize = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string accountKey, string table, string partitionKey, string rowKey, class System.Collections.Generic.IList`1&lt;string&gt; columnsToRemove, valuetype System.Nullable`1&lt;int32&gt; batchSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional accountName As String = null, Optional accountKey As String = null, Optional table As String = null, Optional partitionKey As String = null, Optional rowKey As String = null, Optional columnsToRemove As IList(Of String) = null, Optional batchSize As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource : string * string * string * string * string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource (accountName, accountKey, table, partitionKey, rowKey, columnsToRemove, batchSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="accountKey" Type="System.String" />
        <Parameter Name="table" Type="System.String" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
        <Parameter Name="columnsToRemove" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="batchSize" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="3fc72-103">Azure ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="3fc72-103">The name of the Azure Storage account.</span></span>
            <span data-ttu-id="3fc72-104">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="3fc72-104">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="accountKey"><span data-ttu-id="3fc72-105">Azure ストレージ アカウントのアカウント キー。</span><span class="sxs-lookup"><span data-stu-id="3fc72-105">The account key for the Azure Storage account.</span></span> <span data-ttu-id="3fc72-106">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="3fc72-106">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="table"><span data-ttu-id="3fc72-107">Azure テーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="3fc72-107">The name of the Azure Table.</span></span> <span data-ttu-id="3fc72-108">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="3fc72-108">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="partitionKey"><span data-ttu-id="3fc72-109">この要素は、Azure テーブルのパーティション キーとして使用されるクエリの SELECT ステートメントからの列の名前を示します。</span><span class="sxs-lookup"><span data-stu-id="3fc72-109">This element indicates the name of a column from the SELECT statement in the query that will be used as the partition key for the Azure Table.</span></span> <span data-ttu-id="3fc72-110">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="3fc72-110">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="rowKey"><span data-ttu-id="3fc72-111">この要素は、Azure テーブルの行キーとして使用されるクエリの SELECT ステートメントからの列の名前を示します。</span><span class="sxs-lookup"><span data-stu-id="3fc72-111">This element indicates the name of a column from the SELECT statement in the query that will be used as the row key for the Azure Table.</span></span> <span data-ttu-id="3fc72-112">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="3fc72-112">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="columnsToRemove"><span data-ttu-id="3fc72-113">指定した場合、配列内の各項目は、出力イベント エンティティから (存在する場合) を削除する列の名前です。</span><span class="sxs-lookup"><span data-stu-id="3fc72-113">If specified, each item in the array is the name of a column to remove (if present) from output event entities.</span></span></param>
        <param name="batchSize"><span data-ttu-id="3fc72-114">一度に、Azure テーブルに書き込む行の数。</span><span class="sxs-lookup"><span data-stu-id="3fc72-114">The number of rows to write to the Azure Table at a time.</span></span></param>
        <summary>
            <span data-ttu-id="3fc72-115">AzureTableOutputDataSource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3fc72-115">Initializes a new instance of the AzureTableOutputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountKey">
      <MemberSignature Language="C#" Value="public string AccountKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource.AccountKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountKey As String" />
      <MemberSignature Language="F#" Value="member this.AccountKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource.AccountKey" />
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
            <span data-ttu-id="3fc72-116">取得または Azure ストレージ アカウントのアカウント キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="3fc72-116">Gets or sets the account key for the Azure Storage account.</span></span>
            <span data-ttu-id="3fc72-117">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="3fc72-117">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accountName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fc72-118">取得または Azure ストレージ アカウントの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="3fc72-118">Gets or sets the name of the Azure Storage account.</span></span> <span data-ttu-id="3fc72-119">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="3fc72-119">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BatchSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BatchSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource.BatchSize" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BatchSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource.BatchSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.batchSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fc72-120">取得または設定時に、Azure テーブルに書き込む行の数。</span><span class="sxs-lookup"><span data-stu-id="3fc72-120">Gets or sets the number of rows to write to the Azure Table at a time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ColumnsToRemove">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ColumnsToRemove { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ColumnsToRemove" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource.ColumnsToRemove" />
      <MemberSignature Language="VB.NET" Value="Public Property ColumnsToRemove As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ColumnsToRemove : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource.ColumnsToRemove" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.columnsToRemove")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fc72-121">取得または設定の指定した場合、配列内の各項目は、出力イベント エンティティから (存在する場合) を削除する列の名前。</span><span class="sxs-lookup"><span data-stu-id="3fc72-121">Gets or sets if specified, each item in the array is the name of a column to remove (if present) from output event entities.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource.PartitionKey" />
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
            <span data-ttu-id="3fc72-122">取得または設定、この要素は、Azure テーブルのパーティション キーとして使用されるクエリの SELECT ステートメントからの列の名前を示します。</span><span class="sxs-lookup"><span data-stu-id="3fc72-122">Gets or sets this element indicates the name of a column from the SELECT statement in the query that will be used as the partition key for the Azure Table.</span></span> <span data-ttu-id="3fc72-123">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="3fc72-123">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public string RowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource.RowKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.rowKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fc72-124">取得または設定、この要素は、Azure テーブルの行キーとして使用されるクエリの SELECT ステートメントからの列の名前を示します。</span><span class="sxs-lookup"><span data-stu-id="3fc72-124">Gets or sets this element indicates the name of a column from the SELECT statement in the query that will be used as the row key for the Azure Table.</span></span> <span data-ttu-id="3fc72-125">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="3fc72-125">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Table">
      <MemberSignature Language="C#" Value="public string Table { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Table" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource.Table" />
      <MemberSignature Language="VB.NET" Value="Public Property Table As String" />
      <MemberSignature Language="F#" Value="member this.Table : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.AzureTableOutputDataSource.Table" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.table")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3fc72-126">取得または Azure テーブルの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="3fc72-126">Gets or sets the name of the Azure Table.</span></span> <span data-ttu-id="3fc72-127">PUT (CreateOrReplace) 要求に必要です。</span><span class="sxs-lookup"><span data-stu-id="3fc72-127">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>