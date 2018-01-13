<Type Name="ElasticPoolUpdate" FullName="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate">
  <TypeSignature Language="C#" Value="public class ElasticPoolUpdate : Microsoft.Azure.Management.Sql.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ElasticPoolUpdate extends Microsoft.Azure.Management.Sql.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate" />
  <TypeSignature Language="VB.NET" Value="Public Class ElasticPoolUpdate&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ElasticPoolUpdate = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="25d9d-101">弾力性プールの更新プログラムを表します。</span><span class="sxs-lookup"><span data-stu-id="25d9d-101">Represents an elastic pool update.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="25d9d-102">ElasticPoolUpdate クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="25d9d-102">Initializes a new instance of the ElasticPoolUpdate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolUpdate (string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;DateTime&gt; creationDate = null, string state = null, string edition = null, Nullable&lt;int&gt; dtu = null, Nullable&lt;int&gt; databaseDtuMax = null, Nullable&lt;int&gt; databaseDtuMin = null, Nullable&lt;int&gt; storageMB = null, Nullable&lt;bool&gt; zoneRedundant = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationDate, string state, string edition, valuetype System.Nullable`1&lt;int32&gt; dtu, valuetype System.Nullable`1&lt;int32&gt; databaseDtuMax, valuetype System.Nullable`1&lt;int32&gt; databaseDtuMin, valuetype System.Nullable`1&lt;int32&gt; storageMB, valuetype System.Nullable`1&lt;bool&gt; zoneRedundant) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.#ctor(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional creationDate As Nullable(Of DateTime) = null, Optional state As String = null, Optional edition As String = null, Optional dtu As Nullable(Of Integer) = null, Optional databaseDtuMax As Nullable(Of Integer) = null, Optional databaseDtuMin As Nullable(Of Integer) = null, Optional storageMB As Nullable(Of Integer) = null, Optional zoneRedundant As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate" Usage="new Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate (id, name, type, tags, creationDate, state, edition, dtu, databaseDtuMax, databaseDtuMin, storageMB, zoneRedundant)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="creationDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="edition" Type="System.String" />
        <Parameter Name="dtu" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="databaseDtuMax" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="databaseDtuMin" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="storageMB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="zoneRedundant" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="25d9d-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="25d9d-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="25d9d-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="25d9d-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="25d9d-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="25d9d-105">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="25d9d-106">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="25d9d-106">Resource tags.</span></span></param>
        <param name="creationDate"><span data-ttu-id="25d9d-107">弾力性プール (ISO8601 形式) の作成日。</span><span class="sxs-lookup"><span data-stu-id="25d9d-107">The creation date of the elastic pool (ISO8601 format).</span></span></param>
        <param name="state"><span data-ttu-id="25d9d-108">弾力性プールの状態。</span><span class="sxs-lookup"><span data-stu-id="25d9d-108">The state of the elastic pool.</span></span> <span data-ttu-id="25d9d-109">使用可能な値が含まれます: '作成中'、'準備完了'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="25d9d-109">Possible values include: 'Creating', 'Ready', 'Disabled'</span></span></param>
        <param name="edition"><span data-ttu-id="25d9d-110">弾力性プールのエディションです。</span><span class="sxs-lookup"><span data-stu-id="25d9d-110">The edition of the elastic pool.</span></span> <span data-ttu-id="25d9d-111">使用可能な値が含まれます: 'Basic'、'Standard'、'Premium'</span><span class="sxs-lookup"><span data-stu-id="25d9d-111">Possible values include: 'Basic', 'Standard', 'Premium'</span></span></param>
        <param name="dtu"><span data-ttu-id="25d9d-112">合計は、データベースの弾力性プールの DTU を共有します。</span><span class="sxs-lookup"><span data-stu-id="25d9d-112">The total shared DTU for the database elastic pool.</span></span></param>
        <param name="databaseDtuMax"><span data-ttu-id="25d9d-113">任意の 1 つのデータベースが使用できる最大 DTU です。</span><span class="sxs-lookup"><span data-stu-id="25d9d-113">The maximum DTU any one database can consume.</span></span></param>
        <param name="databaseDtuMin"><span data-ttu-id="25d9d-114">最小の DTU のすべてのデータベースのことが保証されます。</span><span class="sxs-lookup"><span data-stu-id="25d9d-114">The minimum DTU all databases are guaranteed.</span></span></param>
        <param name="storageMB"><span data-ttu-id="25d9d-115">MB のデータベースの弾力性プールの記憶域の上限を取得します。</span><span class="sxs-lookup"><span data-stu-id="25d9d-115">Gets storage limit for the database elastic pool in MB.</span></span></param>
        <param name="zoneRedundant"><span data-ttu-id="25d9d-116">このデータベースの弾力性プールのゾーン冗長、つまりこのデータベースのレプリカがかどうかは、複数の可用性ゾーン間で分散行われます。</span><span class="sxs-lookup"><span data-stu-id="25d9d-116">Whether or not this database elastic pool is zone redundant, which means the replicas of this database will be spread across multiple availability zones.</span></span></param>
        <summary>
            <span data-ttu-id="25d9d-117">ElasticPoolUpdate クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="25d9d-117">Initializes a new instance of the ElasticPoolUpdate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.CreationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.CreationDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25d9d-118">弾力性プール (ISO8601 形式) の作成日を取得します。</span><span class="sxs-lookup"><span data-stu-id="25d9d-118">Gets the creation date of the elastic pool (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseDtuMax">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DatabaseDtuMax { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DatabaseDtuMax" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.DatabaseDtuMax" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseDtuMax As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DatabaseDtuMax : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.DatabaseDtuMax" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseDtuMax")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25d9d-119">取得または任意の 1 つのデータベースが使用できる最大の DTU を設定します。</span><span class="sxs-lookup"><span data-stu-id="25d9d-119">Gets or sets the maximum DTU any one database can consume.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseDtuMin">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DatabaseDtuMin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DatabaseDtuMin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.DatabaseDtuMin" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseDtuMin As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DatabaseDtuMin : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.DatabaseDtuMin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseDtuMin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25d9d-120">取得または設定の最小 DTU のすべてのデータベースのことが保証されます。</span><span class="sxs-lookup"><span data-stu-id="25d9d-120">Gets or sets the minimum DTU all databases are guaranteed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dtu">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Dtu { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Dtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.Dtu" />
      <MemberSignature Language="VB.NET" Value="Public Property Dtu As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Dtu : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.Dtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dtu")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25d9d-121">取得または合計のデータベースの弾力性プールの DTU の共有を設定します。</span><span class="sxs-lookup"><span data-stu-id="25d9d-121">Gets or sets the total shared DTU for the database elastic pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Edition">
      <MemberSignature Language="C#" Value="public string Edition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Edition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.Edition" />
      <MemberSignature Language="VB.NET" Value="Public Property Edition As String" />
      <MemberSignature Language="F#" Value="member this.Edition : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.Edition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.edition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25d9d-122">取得または弾力性プールのエディションを設定します。</span><span class="sxs-lookup"><span data-stu-id="25d9d-122">Gets or sets the edition of the elastic pool.</span></span> <span data-ttu-id="25d9d-123">使用可能な値が含まれます: 'Basic'、'Standard'、'Premium'</span><span class="sxs-lookup"><span data-stu-id="25d9d-123">Possible values include: 'Basic', 'Standard', 'Premium'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25d9d-124">弾力性プールの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="25d9d-124">Gets the state of the elastic pool.</span></span> <span data-ttu-id="25d9d-125">使用可能な値が含まれます: '作成中'、'準備完了'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="25d9d-125">Possible values include: 'Creating', 'Ready', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; StorageMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; StorageMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.StorageMB" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageMB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.StorageMB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.StorageMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageMB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25d9d-126">MB のデータベースの弾力性プールの記憶域の上限を取得します。</span><span class="sxs-lookup"><span data-stu-id="25d9d-126">Gets storage limit for the database elastic pool in MB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25d9d-127">取得またはリソース タグを設定します。</span><span class="sxs-lookup"><span data-stu-id="25d9d-127">Gets or sets resource tags.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ZoneRedundant">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ZoneRedundant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ZoneRedundant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.ZoneRedundant" />
      <MemberSignature Language="VB.NET" Value="Public Property ZoneRedundant As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ZoneRedundant : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolUpdate.ZoneRedundant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.zoneRedundant")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25d9d-128">取得またはこのデータベースの弾力性プールが複数の可用性ゾーン、ゾーン冗長、このデータベースのレプリカを意味に分散するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="25d9d-128">Gets or sets whether or not this database elastic pool is zone redundant, which means the replicas of this database will be spread across multiple availability zones.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>