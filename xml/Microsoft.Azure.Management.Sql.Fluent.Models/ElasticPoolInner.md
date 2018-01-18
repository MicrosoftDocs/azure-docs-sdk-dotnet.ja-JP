<Type Name="ElasticPoolInner" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner">
  <TypeSignature Language="C#" Value="public class ElasticPoolInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ElasticPoolInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ElasticPoolInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ElasticPoolInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e59b9-101">Azure SQL Database の弾力性プールを表します。</span><span class="sxs-lookup"><span data-stu-id="e59b9-101">Represents an Azure SQL Database elastic pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e59b9-102">ElasticPoolInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e59b9-102">Initializes a new instance of the ElasticPoolInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;DateTime&gt; creationDate = null, string state = null, string edition = null, Nullable&lt;int&gt; dtu = null, Nullable&lt;int&gt; databaseDtuMax = null, Nullable&lt;int&gt; databaseDtuMin = null, Nullable&lt;int&gt; storageMB = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationDate, string state, string edition, valuetype System.Nullable`1&lt;int32&gt; dtu, valuetype System.Nullable`1&lt;int32&gt; databaseDtuMax, valuetype System.Nullable`1&lt;int32&gt; databaseDtuMin, valuetype System.Nullable`1&lt;int32&gt; storageMB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional creationDate As Nullable(Of DateTime) = null, Optional state As String = null, Optional edition As String = null, Optional dtu As Nullable(Of Integer) = null, Optional databaseDtuMax As Nullable(Of Integer) = null, Optional databaseDtuMin As Nullable(Of Integer) = null, Optional storageMB As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner (location, id, name, type, tags, creationDate, state, edition, dtu, databaseDtuMax, databaseDtuMin, storageMB)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
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
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="creationDate"><span data-ttu-id="e59b9-103">Azure SQL 弾力性プール (ISO8601 形式) の作成日。</span><span class="sxs-lookup"><span data-stu-id="e59b9-103">The creation date of the Azure SQL Elastic Pool (ISO8601 format).</span></span></param>
        <param name="state"><span data-ttu-id="e59b9-104">Azure SQL 弾力性プールの状態。</span><span class="sxs-lookup"><span data-stu-id="e59b9-104">The state of the Azure SQL Elastic Pool.</span></span>
            <span data-ttu-id="e59b9-105">使用可能な値が含まれます: '作成中'、'準備完了'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="e59b9-105">Possible values include: 'Creating', 'Ready', 'Disabled'</span></span></param>
        <param name="edition"><span data-ttu-id="e59b9-106">Azure SQL 弾力性プールのエディションです。</span><span class="sxs-lookup"><span data-stu-id="e59b9-106">The edition of the Azure SQL Elastic Pool.</span></span>
            <span data-ttu-id="e59b9-107">使用可能な値が含まれます: 'Basic'、'Standard'、'Premium'</span><span class="sxs-lookup"><span data-stu-id="e59b9-107">Possible values include: 'Basic', 'Standard', 'Premium'</span></span></param>
        <param name="dtu"><span data-ttu-id="e59b9-108">合計では、SQL Azure データベースの弾力性プールの DTU が共有されます。</span><span class="sxs-lookup"><span data-stu-id="e59b9-108">The total shared DTU for the SQL Azure Database Elastic Pool.</span></span></param>
        <param name="databaseDtuMax"><span data-ttu-id="e59b9-109">最大の DTU の 1 つの SQL Azure データベースを使用できます。</span><span class="sxs-lookup"><span data-stu-id="e59b9-109">The maximum DTU any one SQL Azure Database can consume.</span></span></param>
        <param name="databaseDtuMin"><span data-ttu-id="e59b9-110">最小の DTU のすべての SQL Azure データベースのことが保証されます。</span><span class="sxs-lookup"><span data-stu-id="e59b9-110">The minimum DTU all SQL Azure Databases are guaranteed.</span></span></param>
        <param name="storageMB"><span data-ttu-id="e59b9-111">Mb SQL Azure データベース弾力性プール記憶域の上限を取得します。</span><span class="sxs-lookup"><span data-stu-id="e59b9-111">Gets storage limit for the SQL Azure Database Elastic Pool in MB.</span></span></param>
        <summary>
            <span data-ttu-id="e59b9-112">ElasticPoolInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e59b9-112">Initializes a new instance of the ElasticPoolInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner.CreationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner.CreationDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e59b9-113">Azure SQL 弾力性プール (ISO8601 形式) の作成日を取得します。</span><span class="sxs-lookup"><span data-stu-id="e59b9-113">Gets the creation date of the Azure SQL Elastic Pool (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseDtuMax">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DatabaseDtuMax { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DatabaseDtuMax" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner.DatabaseDtuMax" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseDtuMax As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DatabaseDtuMax : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner.DatabaseDtuMax" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e59b9-114">取得または 1 つの SQL Azure データベースが使用できる最大の DTU を設定します。</span><span class="sxs-lookup"><span data-stu-id="e59b9-114">Gets or sets the maximum DTU any one SQL Azure Database can consume.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseDtuMin">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DatabaseDtuMin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DatabaseDtuMin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner.DatabaseDtuMin" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseDtuMin As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DatabaseDtuMin : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner.DatabaseDtuMin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e59b9-115">取得または設定の最小 DTU のすべての SQL Azure データベースのことが保証されます。</span><span class="sxs-lookup"><span data-stu-id="e59b9-115">Gets or sets the minimum DTU all SQL Azure Databases are guaranteed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dtu">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Dtu { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Dtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner.Dtu" />
      <MemberSignature Language="VB.NET" Value="Public Property Dtu As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Dtu : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner.Dtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e59b9-116">取得または SQL Azure データベースの弾力性プールの合計の DTU の共有を設定します。</span><span class="sxs-lookup"><span data-stu-id="e59b9-116">Gets or sets the total shared DTU for the SQL Azure Database Elastic Pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Edition">
      <MemberSignature Language="C#" Value="public string Edition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Edition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner.Edition" />
      <MemberSignature Language="VB.NET" Value="Public Property Edition As String" />
      <MemberSignature Language="F#" Value="member this.Edition : string with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner.Edition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e59b9-117">取得または Azure SQL 弾力性プールのエディションを設定します。</span><span class="sxs-lookup"><span data-stu-id="e59b9-117">Gets or sets the edition of the Azure SQL Elastic Pool.</span></span> <span data-ttu-id="e59b9-118">使用可能な値が含まれます: 'Basic'、'Standard'、'Premium'</span><span class="sxs-lookup"><span data-stu-id="e59b9-118">Possible values include: 'Basic', 'Standard', 'Premium'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e59b9-119">Azure SQL 弾力性プールの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="e59b9-119">Gets the state of the Azure SQL Elastic Pool.</span></span> <span data-ttu-id="e59b9-120">使用可能な値が含まれます: '作成中'、'準備完了'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="e59b9-120">Possible values include: 'Creating', 'Ready', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageMB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; StorageMB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; StorageMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner.StorageMB" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageMB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.StorageMB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ElasticPoolInner.StorageMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="e59b9-121">Mb SQL Azure データベース弾力性プール記憶域の上限を取得します。</span><span class="sxs-lookup"><span data-stu-id="e59b9-121">Gets storage limit for the SQL Azure Database Elastic Pool in MB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>