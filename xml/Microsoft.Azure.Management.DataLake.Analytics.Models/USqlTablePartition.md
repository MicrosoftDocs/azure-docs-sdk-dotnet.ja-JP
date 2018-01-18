<Type Name="USqlTablePartition" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition">
  <TypeSignature Language="C#" Value="public class USqlTablePartition : Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlTablePartition extends Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlTablePartition&#xA;Inherits CatalogItem" />
  <TypeSignature Language="F#" Value="type USqlTablePartition = class&#xA;    inherit CatalogItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7f7e9-101">Data Lake Analytics カタログ U-SQL テーブル パーティション アイテムです。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-101">A Data Lake Analytics catalog U-SQL table partition item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlTablePartition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7f7e9-102">USqlTablePartition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-102">Initializes a new instance of the USqlTablePartition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlTablePartition (string computeAccountName = null, Nullable&lt;Guid&gt; version = null, string databaseName = null, string schemaName = null, string name = null, Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName parentName = null, Nullable&lt;int&gt; indexId = null, System.Collections.Generic.IList&lt;string&gt; label = null, Nullable&lt;DateTimeOffset&gt; createDate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computeAccountName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; version, string databaseName, string schemaName, string name, class Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName parentName, valuetype System.Nullable`1&lt;int32&gt; indexId, class System.Collections.Generic.IList`1&lt;string&gt; label, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; createDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.#ctor(System.String,System.Nullable{System.Guid},System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional computeAccountName As String = null, Optional version As Nullable(Of Guid) = null, Optional databaseName As String = null, Optional schemaName As String = null, Optional name As String = null, Optional parentName As DdlName = null, Optional indexId As Nullable(Of Integer) = null, Optional label As IList(Of String) = null, Optional createDate As Nullable(Of DateTimeOffset) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition : string * Nullable&lt;Guid&gt; * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition (computeAccountName, version, databaseName, schemaName, name, parentName, indexId, label, createDate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="computeAccountName" Type="System.String" />
        <Parameter Name="version" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parentName" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName" />
        <Parameter Name="indexId" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="label" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="createDate" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="computeAccountName"><span data-ttu-id="7f7e9-103">Data Lake Analytics アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-103">the name of the Data Lake Analytics account.</span></span></param>
        <param name="version"><span data-ttu-id="7f7e9-104">カタログ アイテムのバージョン。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-104">the version of the catalog item.</span></span></param>
        <param name="databaseName"><span data-ttu-id="7f7e9-105">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-105">the name of the database.</span></span></param>
        <param name="schemaName"><span data-ttu-id="7f7e9-106">このテーブルのパーティションとデータベースに関連付けられているスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-106">the name of the schema associated with this table partition and database.</span></span></param>
        <param name="name"><span data-ttu-id="7f7e9-107">テーブルのパーティションの名前。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-107">the name of the table partition.</span></span></param>
        <param name="parentName"><span data-ttu-id="7f7e9-108">パーティションの親の Ddl オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-108">the Ddl object of the partition's parent.</span></span></param>
        <param name="indexId"><span data-ttu-id="7f7e9-109">このパーティションのインデックス ID です。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-109">the index ID for this partition.</span></span></param>
        <param name="label"><span data-ttu-id="7f7e9-110">このパーティションに関連付けられているラベルの一覧です。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-110">the list of labels associated with this partition.</span></span></param>
        <param name="createDate"><span data-ttu-id="7f7e9-111">パーティションの作成日時</span><span class="sxs-lookup"><span data-stu-id="7f7e9-111">the creation time of the partition</span></span></param>
        <summary>
            <span data-ttu-id="7f7e9-112">USqlTablePartition クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-112">Initializes a new instance of the USqlTablePartition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; CreateDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; CreateDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.CreateDate" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateDate As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.CreateDate : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.CreateDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f7e9-113">取得またはパーティションの作成時の設定</span><span class="sxs-lookup"><span data-stu-id="7f7e9-113">Gets or sets the creation time of the partition</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="databaseName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f7e9-114">取得またはデータベースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-114">Gets or sets the name of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IndexId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IndexId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.IndexId" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IndexId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.IndexId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="indexId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f7e9-115">取得またはこのパーティションのインデックス ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-115">Gets or sets the index ID for this partition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Label : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="label")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f7e9-116">取得またはこのパーティションに関連付けられているラベルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-116">Gets or sets the list of labels associated with this partition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="partitionName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f7e9-117">取得またはテーブルのパーティションの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-117">Gets or sets the name of the table partition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParentName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName ParentName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName ParentName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.ParentName" />
      <MemberSignature Language="VB.NET" Value="Public Property ParentName As DdlName" />
      <MemberSignature Language="F#" Value="member this.ParentName : Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.ParentName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parentName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f7e9-118">取得またはパーティションの親の Ddl オブジェクトを設定します。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-118">Gets or sets the Ddl object of the partition's parent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchemaName">
      <MemberSignature Language="C#" Value="public string SchemaName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SchemaName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.SchemaName" />
      <MemberSignature Language="VB.NET" Value="Public Property SchemaName As String" />
      <MemberSignature Language="F#" Value="member this.SchemaName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.SchemaName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schemaName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7f7e9-119">取得またはこのテーブルのパーティションとデータベースに関連付けられているスキーマの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="7f7e9-119">Gets or sets the name of the schema associated with this table partition and database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>