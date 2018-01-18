<Type Name="Indexer" FullName="Microsoft.Azure.Search.Models.Indexer">
  <TypeSignature Language="C#" Value="public class Indexer : Microsoft.Azure.Search.Models.IResourceWithETag" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Indexer extends System.Object implements class Microsoft.Azure.Search.Models.IResourceWithETag" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.Indexer" />
  <TypeSignature Language="VB.NET" Value="Public Class Indexer&#xA;Implements IResourceWithETag" />
  <TypeSignature Language="F#" Value="type Indexer = class&#xA;    interface IResourceWithETag" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Search.Models.IResourceWithETag</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="6d999-101">Azure Search インデクサーを表します。</span><span class="sxs-lookup"><span data-stu-id="6d999-101">Represents an Azure Search indexer.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Indexer-operations" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Indexer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Indexer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6d999-102">Indexer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6d999-102">Initializes a new instance of the Indexer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Indexer (string name, string dataSourceName, string targetIndexName, string description = null, Microsoft.Azure.Search.Models.IndexingSchedule schedule = null, Microsoft.Azure.Search.Models.IndexingParameters parameters = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.FieldMapping&gt; fieldMappings = null, Nullable&lt;bool&gt; isDisabled = null, string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string dataSourceName, string targetIndexName, string description, class Microsoft.Azure.Search.Models.IndexingSchedule schedule, class Microsoft.Azure.Search.Models.IndexingParameters parameters, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.FieldMapping&gt; fieldMappings, valuetype System.Nullable`1&lt;bool&gt; isDisabled, string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Indexer.#ctor(System.String,System.String,System.String,System.String,Microsoft.Azure.Search.Models.IndexingSchedule,Microsoft.Azure.Search.Models.IndexingParameters,System.Collections.Generic.IList{Microsoft.Azure.Search.Models.FieldMapping},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, dataSourceName As String, targetIndexName As String, Optional description As String = null, Optional schedule As IndexingSchedule = null, Optional parameters As IndexingParameters = null, Optional fieldMappings As IList(Of FieldMapping) = null, Optional isDisabled As Nullable(Of Boolean) = null, Optional eTag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.Indexer : string * string * string * string * Microsoft.Azure.Search.Models.IndexingSchedule * Microsoft.Azure.Search.Models.IndexingParameters * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.FieldMapping&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Search.Models.Indexer" Usage="new Microsoft.Azure.Search.Models.Indexer (name, dataSourceName, targetIndexName, description, schedule, parameters, fieldMappings, isDisabled, eTag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="targetIndexName" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="schedule" Type="Microsoft.Azure.Search.Models.IndexingSchedule" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.IndexingParameters" />
        <Parameter Name="fieldMappings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.FieldMapping&gt;" />
        <Parameter Name="isDisabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="6d999-103">インデクサーの名前。</span><span class="sxs-lookup"><span data-stu-id="6d999-103">The name of the indexer.</span></span></param>
        <param name="dataSourceName"><span data-ttu-id="6d999-104">このインデクサーがデータを読み取り元となるデータ ソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="6d999-104">The name of the datasource from which this indexer reads data.</span></span></param>
        <param name="targetIndexName"><span data-ttu-id="6d999-105">このインデクサーがデータを書き込むインデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="6d999-105">The name of the index to which this indexer writes data.</span></span></param>
        <param name="description"><span data-ttu-id="6d999-106">インデクサーの説明です。</span><span class="sxs-lookup"><span data-stu-id="6d999-106">The description of the indexer.</span></span></param>
        <param name="schedule"><span data-ttu-id="6d999-107">このインデクサーのスケジュールです。</span><span class="sxs-lookup"><span data-stu-id="6d999-107">The schedule for this indexer.</span></span></param>
        <param name="parameters"><span data-ttu-id="6d999-108">インデクサー実行のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6d999-108">Parameters for indexer execution.</span></span></param>
        <param name="fieldMappings"><span data-ttu-id="6d999-109">インデックスのデータ ソースのフィールドと対応する対象のフィールド間のマッピングを定義します。</span><span class="sxs-lookup"><span data-stu-id="6d999-109">Defines mappings between fields in the data source and corresponding target fields in the index.</span></span></param>
        <param name="isDisabled"><span data-ttu-id="6d999-110">インデクサーは無効になっているかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="6d999-110">A value indicating whether the indexer is disabled.</span></span> <span data-ttu-id="6d999-111">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="6d999-111">Default is false.</span></span></param>
        <param name="eTag"><span data-ttu-id="6d999-112">インデクサーの ETag です。</span><span class="sxs-lookup"><span data-stu-id="6d999-112">The ETag of the Indexer.</span></span></param>
        <summary>
            <span data-ttu-id="6d999-113">Indexer クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6d999-113">Initializes a new instance of the Indexer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSourceName">
      <MemberSignature Language="C#" Value="public string DataSourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataSourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Indexer.DataSourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property DataSourceName As String" />
      <MemberSignature Language="F#" Value="member this.DataSourceName : string with get, set" Usage="Microsoft.Azure.Search.Models.Indexer.DataSourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataSourceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d999-114">取得またはこのインデクサーがデータを読み取り元となるデータ ソースの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="6d999-114">Gets or sets the name of the datasource from which this indexer reads data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Indexer.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Search.Models.Indexer.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d999-115">取得またはインデクサーの説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="6d999-115">Gets or sets the description of the indexer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Indexer.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Search.Models.Indexer.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="@odata.etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d999-116">取得またはインデクサーの ETag を設定します。</span><span class="sxs-lookup"><span data-stu-id="6d999-116">Gets or sets the ETag of the Indexer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FieldMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.FieldMapping&gt; FieldMappings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.FieldMapping&gt; FieldMappings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Indexer.FieldMappings" />
      <MemberSignature Language="VB.NET" Value="Public Property FieldMappings As IList(Of FieldMapping)" />
      <MemberSignature Language="F#" Value="member this.FieldMappings : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.FieldMapping&gt; with get, set" Usage="Microsoft.Azure.Search.Models.Indexer.FieldMappings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fieldMappings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.FieldMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d999-117">取得または設定は、インデックスのデータ ソースのフィールドと対応する対象のフィールド間のマッピングを定義します。</span><span class="sxs-lookup"><span data-stu-id="6d999-117">Gets or sets defines mappings between fields in the data source and corresponding target fields in the index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDisabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDisabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDisabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Indexer.IsDisabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDisabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDisabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.Indexer.IsDisabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="disabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d999-118">取得またはインデクサーが無効になっているかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="6d999-118">Gets or sets a value indicating whether the indexer is disabled.</span></span>
            <span data-ttu-id="6d999-119">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="6d999-119">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Indexer.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Search.Models.Indexer.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d999-120">取得またはインデクサーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="6d999-120">Gets or sets the name of the indexer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.IndexingParameters Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.IndexingParameters Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Indexer.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IndexingParameters" />
      <MemberSignature Language="F#" Value="member this.Parameters : Microsoft.Azure.Search.Models.IndexingParameters with get, set" Usage="Microsoft.Azure.Search.Models.Indexer.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d999-121">取得またはインデクサー実行のパラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="6d999-121">Gets or sets parameters for indexer execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.IndexingSchedule Schedule { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.IndexingSchedule Schedule" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Indexer.Schedule" />
      <MemberSignature Language="VB.NET" Value="Public Property Schedule As IndexingSchedule" />
      <MemberSignature Language="F#" Value="member this.Schedule : Microsoft.Azure.Search.Models.IndexingSchedule with get, set" Usage="Microsoft.Azure.Search.Models.Indexer.Schedule" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schedule")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexingSchedule</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d999-122">取得またはこのインデクサーのスケジュールを設定します。</span><span class="sxs-lookup"><span data-stu-id="6d999-122">Gets or sets the schedule for this indexer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetIndexName">
      <MemberSignature Language="C#" Value="public string TargetIndexName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetIndexName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.Indexer.TargetIndexName" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetIndexName As String" />
      <MemberSignature Language="F#" Value="member this.TargetIndexName : string with get, set" Usage="Microsoft.Azure.Search.Models.Indexer.TargetIndexName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetIndexName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d999-123">取得またはこのインデクサーがデータを書き込むインデックスの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="6d999-123">Gets or sets the name of the index to which this indexer writes data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.Indexer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="indexer.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6d999-124">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="6d999-124">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6d999-125">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6d999-125">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>