<Type Name="Zone" FullName="Microsoft.Azure.Management.Dns.Models.Zone">
  <TypeSignature Language="C#" Value="public class Zone : Microsoft.Azure.Management.Dns.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Zone extends Microsoft.Azure.Management.Dns.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Models.Zone" />
  <TypeSignature Language="VB.NET" Value="Public Class Zone&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Zone = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Dns.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="83ee9-101">DNS ゾーンをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="83ee9-101">Describes a DNS zone.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Zone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Models.Zone.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="83ee9-102">ゾーンのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="83ee9-102">Initializes a new instance of the Zone class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Zone (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string etag = null, Nullable&lt;long&gt; maxNumberOfRecordSets = null, Nullable&lt;long&gt; numberOfRecordSets = null, System.Collections.Generic.IList&lt;string&gt; nameServers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string etag, valuetype System.Nullable`1&lt;int64&gt; maxNumberOfRecordSets, valuetype System.Nullable`1&lt;int64&gt; numberOfRecordSets, class System.Collections.Generic.IList`1&lt;string&gt; nameServers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Models.Zone.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional etag As String = null, Optional maxNumberOfRecordSets As Nullable(Of Long) = null, Optional numberOfRecordSets As Nullable(Of Long) = null, Optional nameServers As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Dns.Models.Zone : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Dns.Models.Zone" Usage="new Microsoft.Azure.Management.Dns.Models.Zone (location, id, name, type, tags, etag, maxNumberOfRecordSets, numberOfRecordSets, nameServers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="maxNumberOfRecordSets" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="numberOfRecordSets" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="nameServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="83ee9-103">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="83ee9-103">Resource location.</span></span></param>
        <param name="id"><span data-ttu-id="83ee9-104">リソースの ID</span><span class="sxs-lookup"><span data-stu-id="83ee9-104">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="83ee9-105">リソース名。</span><span class="sxs-lookup"><span data-stu-id="83ee9-105">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="83ee9-106">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="83ee9-106">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="83ee9-107">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="83ee9-107">Resource tags.</span></span></param>
        <param name="etag"><span data-ttu-id="83ee9-108">ゾーンの etag です。</span><span class="sxs-lookup"><span data-stu-id="83ee9-108">The etag of the zone.</span></span></param>
        <param name="maxNumberOfRecordSets"><span data-ttu-id="83ee9-109">この DNS ゾーンに作成できるレコードのセットの最大数。</span><span class="sxs-lookup"><span data-stu-id="83ee9-109">The maximum number of record sets that can be created in this DNS zone.</span></span>  <span data-ttu-id="83ee9-110">これは読み取り専用プロパティであり、この値を設定しようとするとは無視されます。</span><span class="sxs-lookup"><span data-stu-id="83ee9-110">This is a read-only property and any attempt to set this value will be ignored.</span></span></param>
        <param name="numberOfRecordSets"><span data-ttu-id="83ee9-111">現在のレコードの数は、この DNS ゾーンに設定します。</span><span class="sxs-lookup"><span data-stu-id="83ee9-111">The current number of record sets in this DNS zone.</span></span>  <span data-ttu-id="83ee9-112">これは読み取り専用プロパティであり、この値を設定しようとするとは無視されます。</span><span class="sxs-lookup"><span data-stu-id="83ee9-112">This is a read-only property and any attempt to set this value will be ignored.</span></span></param>
        <param name="nameServers"><span data-ttu-id="83ee9-113">この DNS ゾーンのネーム サーバー。</span><span class="sxs-lookup"><span data-stu-id="83ee9-113">The name servers for this DNS zone.</span></span> <span data-ttu-id="83ee9-114">これは読み取り専用プロパティであり、この値を設定しようとするとは無視されます。</span><span class="sxs-lookup"><span data-stu-id="83ee9-114">This is a read-only property and any attempt to set this value will be ignored.</span></span></param>
        <summary>
            <span data-ttu-id="83ee9-115">ゾーンのクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="83ee9-115">Initializes a new instance of the Zone class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Models.Zone.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Dns.Models.Zone.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83ee9-116">取得またはゾーンの etag を設定します。</span><span class="sxs-lookup"><span data-stu-id="83ee9-116">Gets or sets the etag of the zone.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxNumberOfRecordSets">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxNumberOfRecordSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxNumberOfRecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Models.Zone.MaxNumberOfRecordSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxNumberOfRecordSets As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxNumberOfRecordSets : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Dns.Models.Zone.MaxNumberOfRecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxNumberOfRecordSets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83ee9-117">この DNS ゾーンに作成できるレコードのセットの最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="83ee9-117">Gets the maximum number of record sets that can be created in this DNS zone.</span></span>  <span data-ttu-id="83ee9-118">これは読み取り専用プロパティであり、この値を設定しようとするとは無視されます。</span><span class="sxs-lookup"><span data-stu-id="83ee9-118">This is a read-only property and any attempt to set this value will be ignored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; NameServers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; NameServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Models.Zone.NameServers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NameServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NameServers : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Dns.Models.Zone.NameServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nameServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83ee9-119">この DNS ゾーンのネーム サーバーを取得します。</span><span class="sxs-lookup"><span data-stu-id="83ee9-119">Gets the name servers for this DNS zone.</span></span> <span data-ttu-id="83ee9-120">これは読み取り専用プロパティであり、この値を設定しようとするとは無視されます。</span><span class="sxs-lookup"><span data-stu-id="83ee9-120">This is a read-only property and any attempt to set this value will be ignored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfRecordSets">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; NumberOfRecordSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; NumberOfRecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Models.Zone.NumberOfRecordSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumberOfRecordSets As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.NumberOfRecordSets : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Dns.Models.Zone.NumberOfRecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberOfRecordSets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83ee9-121">この DNS ゾーン内の現在のレコード セットの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="83ee9-121">Gets the current number of record sets in this DNS zone.</span></span>  <span data-ttu-id="83ee9-122">これは読み取り専用プロパティであり、この値を設定しようとするとは無視されます。</span><span class="sxs-lookup"><span data-stu-id="83ee9-122">This is a read-only property and any attempt to set this value will be ignored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Models.Zone.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="zone.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="83ee9-123">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="83ee9-123">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="83ee9-124">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83ee9-124">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>