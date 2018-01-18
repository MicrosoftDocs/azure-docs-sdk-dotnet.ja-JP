<Type Name="CheckAvailabilityParameters" FullName="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters">
  <TypeSignature Language="C#" Value="public class CheckAvailabilityParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckAvailabilityParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckAvailabilityParameters" />
  <TypeSignature Language="F#" Value="type CheckAvailabilityParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ed6be-101">Namespace および NotificationHubs 名前確認可用性に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ed6be-101">Parameters supplied to the Check Name Availability for Namespace and NotificationHubs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckAvailabilityParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ed6be-102">CheckAvailabilityParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ed6be-102">Initializes a new instance of the CheckAvailabilityParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckAvailabilityParameters (string name, string location, string id = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.NotificationHubs.Models.Sku sku = null, Nullable&lt;bool&gt; isAvailiable = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string location, string id, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.NotificationHubs.Models.Sku sku, valuetype System.Nullable`1&lt;bool&gt; isAvailiable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.NotificationHubs.Models.Sku,System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.NotificationHubs.Models.Sku * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters (name, location, id, type, tags, sku, isAvailiable)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.NotificationHubs.Models.Sku" />
        <Parameter Name="isAvailiable" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="ed6be-103">リソース名</span><span class="sxs-lookup"><span data-stu-id="ed6be-103">Resource name</span></span></param>
        <param name="location"><span data-ttu-id="ed6be-104">リソースの場所</span><span class="sxs-lookup"><span data-stu-id="ed6be-104">Resource location</span></span></param>
        <param name="id"><span data-ttu-id="ed6be-105">リソース Id</span><span class="sxs-lookup"><span data-stu-id="ed6be-105">Resource Id</span></span></param>
        <param name="type"><span data-ttu-id="ed6be-106">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="ed6be-106">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="ed6be-107">リソース タグ</span><span class="sxs-lookup"><span data-stu-id="ed6be-107">Resource tags</span></span></param>
        <param name="sku"><span data-ttu-id="ed6be-108">作成された名前空間の sku</span><span class="sxs-lookup"><span data-stu-id="ed6be-108">The sku of the created namespace</span></span></param>
        <param name="isAvailiable"><span data-ttu-id="ed6be-109">True の場合、名前があるし、新しい Namespace と NotificationHub の作成に使用できます。</span><span class="sxs-lookup"><span data-stu-id="ed6be-109">True if the name is available and can be used to create new Namespace/NotificationHub.</span></span> <span data-ttu-id="ed6be-110">それ以外の場合は false。</span><span class="sxs-lookup"><span data-stu-id="ed6be-110">Otherwise false.</span></span></param>
        <summary>
            <span data-ttu-id="ed6be-111">CheckAvailabilityParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ed6be-111">Initializes a new instance of the CheckAvailabilityParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ed6be-112">リソース Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="ed6be-112">Gets resource Id</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAvailiable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsAvailiable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsAvailiable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.IsAvailiable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAvailiable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsAvailiable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.IsAvailiable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isAvailiable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ed6be-113">取得または名前があるし、新しい Namespace と NotificationHub の作成に使用できる場合に true を設定します。</span><span class="sxs-lookup"><span data-stu-id="ed6be-113">Gets or sets true if the name is available and can be used to create new Namespace/NotificationHub.</span></span> <span data-ttu-id="ed6be-114">それ以外の場合は false。</span><span class="sxs-lookup"><span data-stu-id="ed6be-114">Otherwise false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ed6be-115">取得またはリソースの場所の設定</span><span class="sxs-lookup"><span data-stu-id="ed6be-115">Gets or sets resource location</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="ed6be-116">取得または設定リソース名</span><span class="sxs-lookup"><span data-stu-id="ed6be-116">Gets or sets resource name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.NotificationHubs.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.NotificationHubs.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.NotificationHubs.Models.Sku with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ed6be-117">取得または作成された名前空間の sku の設定</span><span class="sxs-lookup"><span data-stu-id="ed6be-117">Gets or sets the sku of the created namespace</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="ed6be-118">取得またはリソース タグを設定</span><span class="sxs-lookup"><span data-stu-id="ed6be-118">Gets or sets resource tags</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.NotificationHubs.Models.CheckAvailabilityParameters.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ed6be-119">リソースの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="ed6be-119">Gets resource type</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>