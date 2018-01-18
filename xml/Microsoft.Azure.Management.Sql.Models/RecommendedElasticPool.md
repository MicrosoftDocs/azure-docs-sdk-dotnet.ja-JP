<Type Name="RecommendedElasticPool" FullName="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool">
  <TypeSignature Language="C#" Value="public class RecommendedElasticPool : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecommendedElasticPool extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool" />
  <TypeSignature Language="VB.NET" Value="Public Class RecommendedElasticPool&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type RecommendedElasticPool = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c712a-101">Recommented 弾力性プールを表します。</span><span class="sxs-lookup"><span data-stu-id="c712a-101">Represents a recommented elastic pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendedElasticPool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c712a-102">RecommendedElasticPool クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c712a-102">Initializes a new instance of the RecommendedElasticPool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendedElasticPool (string id = null, string name = null, string type = null, string databaseEdition = null, Nullable&lt;double&gt; dtu = null, Nullable&lt;double&gt; databaseDtuMin = null, Nullable&lt;double&gt; databaseDtuMax = null, Nullable&lt;double&gt; storageMB = null, Nullable&lt;DateTime&gt; observationPeriodStart = null, Nullable&lt;DateTime&gt; observationPeriodEnd = null, Nullable&lt;double&gt; maxObservedDtu = null, Nullable&lt;double&gt; maxObservedStorageMB = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.Database&gt; databases = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt; metrics = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string databaseEdition, valuetype System.Nullable`1&lt;float64&gt; dtu, valuetype System.Nullable`1&lt;float64&gt; databaseDtuMin, valuetype System.Nullable`1&lt;float64&gt; databaseDtuMax, valuetype System.Nullable`1&lt;float64&gt; storageMB, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; observationPeriodStart, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; observationPeriodEnd, valuetype System.Nullable`1&lt;float64&gt; maxObservedDtu, valuetype System.Nullable`1&lt;float64&gt; maxObservedStorageMB, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt; databases, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt; metrics) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Double},System.Nullable{System.Double},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.Database},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional databaseEdition As String = null, Optional dtu As Nullable(Of Double) = null, Optional databaseDtuMin As Nullable(Of Double) = null, Optional databaseDtuMax As Nullable(Of Double) = null, Optional storageMB As Nullable(Of Double) = null, Optional observationPeriodStart As Nullable(Of DateTime) = null, Optional observationPeriodEnd As Nullable(Of DateTime) = null, Optional maxObservedDtu As Nullable(Of Double) = null, Optional maxObservedStorageMB As Nullable(Of Double) = null, Optional databases As IList(Of Database) = null, Optional metrics As IList(Of RecommendedElasticPoolMetric) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool : string * string * string * string * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.Database&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt; -&gt; Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool" Usage="new Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool (id, name, type, databaseEdition, dtu, databaseDtuMin, databaseDtuMax, storageMB, observationPeriodStart, observationPeriodEnd, maxObservedDtu, maxObservedStorageMB, databases, metrics)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="databaseEdition" Type="System.String" />
        <Parameter Name="dtu" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="databaseDtuMin" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="databaseDtuMax" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="storageMB" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="observationPeriodStart" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="observationPeriodEnd" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="maxObservedDtu" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="maxObservedStorageMB" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="databases" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;" />
        <Parameter Name="metrics" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="c712a-103">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="c712a-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="c712a-104">リソース名。</span><span class="sxs-lookup"><span data-stu-id="c712a-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="c712a-105">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="c712a-105">Resource type.</span></span></param>
        <param name="databaseEdition"><span data-ttu-id="c712a-106">推奨エラスティック プールのエディションです。</span><span class="sxs-lookup"><span data-stu-id="c712a-106">The edition of the recommended elastic pool.</span></span> <span data-ttu-id="c712a-107">ElasticPoolEdition 列挙には、有効なすべてのエディションが含まれています。</span><span class="sxs-lookup"><span data-stu-id="c712a-107">The ElasticPoolEdition enumeration contains all the valid editions.</span></span> <span data-ttu-id="c712a-108">使用可能な値が含まれます: 'Basic'、'Standard'、'Premium'</span><span class="sxs-lookup"><span data-stu-id="c712a-108">Possible values include: 'Basic', 'Standard', 'Premium'</span></span></param>
        <param name="dtu"><span data-ttu-id="c712a-109">推奨エラスティック プールの DTU です。</span><span class="sxs-lookup"><span data-stu-id="c712a-109">The DTU for the recommended elastic pool.</span></span></param>
        <param name="databaseDtuMin"><span data-ttu-id="c712a-110">データベースの DTU の最小値。</span><span class="sxs-lookup"><span data-stu-id="c712a-110">The minimum DTU for the database.</span></span></param>
        <param name="databaseDtuMax"><span data-ttu-id="c712a-111">データベースの最大 DTU です。</span><span class="sxs-lookup"><span data-stu-id="c712a-111">The maximum DTU for the database.</span></span></param>
        <param name="storageMB"><span data-ttu-id="c712a-112">記憶域のサイズをメガバイト単位で取得します。</span><span class="sxs-lookup"><span data-stu-id="c712a-112">Gets storage size in megabytes.</span></span></param>
        <param name="observationPeriodStart"><span data-ttu-id="c712a-113">監視期間の開始 (ISO8601 形式)。</span><span class="sxs-lookup"><span data-stu-id="c712a-113">The observation period start (ISO8601 format).</span></span></param>
        <param name="observationPeriodEnd"><span data-ttu-id="c712a-114">監視期間の開始 (ISO8601 形式)。</span><span class="sxs-lookup"><span data-stu-id="c712a-114">The observation period start (ISO8601 format).</span></span></param>
        <param name="maxObservedDtu"><span data-ttu-id="c712a-115">観察された最大の DTU を取得します。</span><span class="sxs-lookup"><span data-stu-id="c712a-115">Gets maximum observed DTU.</span></span></param>
        <param name="maxObservedStorageMB"><span data-ttu-id="c712a-116">メガバイト単位で観察された最大のストレージを取得します。</span><span class="sxs-lookup"><span data-stu-id="c712a-116">Gets maximum observed storage in megabytes.</span></span></param>
        <param name="databases"><span data-ttu-id="c712a-117">このプール内のデータベースの一覧。</span><span class="sxs-lookup"><span data-stu-id="c712a-117">The list of databases in this pool.</span></span>
            <span data-ttu-id="c712a-118">展開されたプロパティ</span><span class="sxs-lookup"><span data-stu-id="c712a-118">Expanded property</span></span></param>
        <param name="metrics"><span data-ttu-id="c712a-119">サーバーに格納されていたデータベースの一覧。</span><span class="sxs-lookup"><span data-stu-id="c712a-119">The list of databases housed in the server.</span></span>
            <span data-ttu-id="c712a-120">展開されたプロパティ</span><span class="sxs-lookup"><span data-stu-id="c712a-120">Expanded property</span></span></param>
        <summary>
            <span data-ttu-id="c712a-121">RecommendedElasticPool クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c712a-121">Initializes a new instance of the RecommendedElasticPool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseDtuMax">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; DatabaseDtuMax { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; DatabaseDtuMax" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.DatabaseDtuMax" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseDtuMax As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.DatabaseDtuMax : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.DatabaseDtuMax" />
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
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c712a-122">取得またはデータベースの最大 DTU を設定します。</span><span class="sxs-lookup"><span data-stu-id="c712a-122">Gets or sets the maximum DTU for the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseDtuMin">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; DatabaseDtuMin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; DatabaseDtuMin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.DatabaseDtuMin" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseDtuMin As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.DatabaseDtuMin : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.DatabaseDtuMin" />
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
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c712a-123">取得またはデータベースの DTU の最小値を設定します。</span><span class="sxs-lookup"><span data-stu-id="c712a-123">Gets or sets the minimum DTU for the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseEdition">
      <MemberSignature Language="C#" Value="public string DatabaseEdition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseEdition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.DatabaseEdition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseEdition As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseEdition : string" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.DatabaseEdition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseEdition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c712a-124">推奨エラスティック プールのエディションを取得します。</span><span class="sxs-lookup"><span data-stu-id="c712a-124">Gets the edition of the recommended elastic pool.</span></span> <span data-ttu-id="c712a-125">ElasticPoolEdition 列挙には、有効なすべてのエディションが含まれています。</span><span class="sxs-lookup"><span data-stu-id="c712a-125">The ElasticPoolEdition enumeration contains all the valid editions.</span></span>
            <span data-ttu-id="c712a-126">使用可能な値が含まれます: 'Basic'、'Standard'、'Premium'</span><span class="sxs-lookup"><span data-stu-id="c712a-126">Possible values include: 'Basic', 'Standard', 'Premium'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Databases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.Database&gt; Databases { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt; Databases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.Databases" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Databases As IList(Of Database)" />
      <MemberSignature Language="F#" Value="member this.Databases : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.Databases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c712a-127">このプール内のデータベースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="c712a-127">Gets the list of databases in this pool.</span></span> <span data-ttu-id="c712a-128">展開されたプロパティ</span><span class="sxs-lookup"><span data-stu-id="c712a-128">Expanded property</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dtu">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Dtu { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Dtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.Dtu" />
      <MemberSignature Language="VB.NET" Value="Public Property Dtu As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Dtu : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.Dtu" />
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
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c712a-129">取得または推奨の弾力性プールの DTU を設定します。</span><span class="sxs-lookup"><span data-stu-id="c712a-129">Gets or sets the DTU for the recommended elastic pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxObservedDtu">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MaxObservedDtu { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MaxObservedDtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.MaxObservedDtu" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxObservedDtu As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MaxObservedDtu : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.MaxObservedDtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxObservedDtu")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c712a-130">観察された最大の DTU を取得します。</span><span class="sxs-lookup"><span data-stu-id="c712a-130">Gets maximum observed DTU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxObservedStorageMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MaxObservedStorageMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MaxObservedStorageMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.MaxObservedStorageMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxObservedStorageMB As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MaxObservedStorageMB : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.MaxObservedStorageMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxObservedStorageMB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c712a-131">メガバイト単位で観察された最大のストレージを取得します。</span><span class="sxs-lookup"><span data-stu-id="c712a-131">Gets maximum observed storage in megabytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt; Metrics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt; Metrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metrics As IList(Of RecommendedElasticPoolMetric)" />
      <MemberSignature Language="F#" Value="member this.Metrics : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.Metrics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metrics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c712a-132">サーバーに格納されていたデータベースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="c712a-132">Gets the list of databases housed in the server.</span></span> <span data-ttu-id="c712a-133">展開されたプロパティ</span><span class="sxs-lookup"><span data-stu-id="c712a-133">Expanded property</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObservationPeriodEnd">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ObservationPeriodEnd { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ObservationPeriodEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.ObservationPeriodEnd" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ObservationPeriodEnd As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ObservationPeriodEnd : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.ObservationPeriodEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.observationPeriodEnd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c712a-134">監視期間の開始 (ISO8601 形式) を取得します。</span><span class="sxs-lookup"><span data-stu-id="c712a-134">Gets the observation period start (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObservationPeriodStart">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ObservationPeriodStart { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ObservationPeriodStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.ObservationPeriodStart" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ObservationPeriodStart As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ObservationPeriodStart : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.ObservationPeriodStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.observationPeriodStart")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c712a-135">監視期間の開始 (ISO8601 形式) を取得します。</span><span class="sxs-lookup"><span data-stu-id="c712a-135">Gets the observation period start (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; StorageMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; StorageMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.StorageMB" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageMB As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.StorageMB : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPool.StorageMB" />
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
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c712a-136">記憶域のサイズをメガバイト単位で取得します。</span><span class="sxs-lookup"><span data-stu-id="c712a-136">Gets storage size in megabytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>