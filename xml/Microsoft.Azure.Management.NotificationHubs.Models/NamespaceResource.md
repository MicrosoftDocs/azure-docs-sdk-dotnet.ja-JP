<Type Name="NamespaceResource" FullName="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource">
  <TypeSignature Language="C#" Value="public class NamespaceResource : Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NamespaceResource extends Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource" />
  <TypeSignature Language="VB.NET" Value="Public Class NamespaceResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type NamespaceResource = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.NotificationHubs.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a8969-101">Namespace リソースの説明。</span><span class="sxs-lookup"><span data-stu-id="a8969-101">Description of a Namespace resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a8969-102">NamespaceResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a8969-102">Initializes a new instance of the NamespaceResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceResource (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.NotificationHubs.Models.Sku sku = null, string namespaceResourceName = null, string provisioningState = null, string region = null, string status = null, Nullable&lt;DateTime&gt; createdAt = null, string serviceBusEndpoint = null, string subscriptionId = null, string scaleUnit = null, Nullable&lt;bool&gt; enabled = null, Nullable&lt;bool&gt; critical = null, Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; namespaceType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.NotificationHubs.Models.Sku sku, string namespaceResourceName, string provisioningState, string region, string status, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, string serviceBusEndpoint, string subscriptionId, string scaleUnit, valuetype System.Nullable`1&lt;bool&gt; enabled, valuetype System.Nullable`1&lt;bool&gt; critical, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; namespaceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.NotificationHubs.Models.Sku,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.NotificationHubs.Models.Sku * string * string * string * string * Nullable&lt;DateTime&gt; * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource (location, id, name, type, tags, sku, namespaceResourceName, provisioningState, region, status, createdAt, serviceBusEndpoint, subscriptionId, scaleUnit, enabled, critical, namespaceType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.NotificationHubs.Models.Sku" />
        <Parameter Name="namespaceResourceName" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="region" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="serviceBusEndpoint" Type="System.String" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="scaleUnit" Type="System.String" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="critical" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="namespaceType" Type="System.Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="a8969-103">リソースの場所</span><span class="sxs-lookup"><span data-stu-id="a8969-103">Resource location</span></span></param>
        <param name="id"><span data-ttu-id="a8969-104">リソース Id</span><span class="sxs-lookup"><span data-stu-id="a8969-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="a8969-105">リソース名</span><span class="sxs-lookup"><span data-stu-id="a8969-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="a8969-106">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="a8969-106">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="a8969-107">リソース タグ</span><span class="sxs-lookup"><span data-stu-id="a8969-107">Resource tags</span></span></param>
        <param name="sku"><span data-ttu-id="a8969-108">作成された名前空間の sku</span><span class="sxs-lookup"><span data-stu-id="a8969-108">The sku of the created namespace</span></span></param>
        <param name="namespaceResourceName"><span data-ttu-id="a8969-109">名前空間の名前。</span><span class="sxs-lookup"><span data-stu-id="a8969-109">The name of the namespace.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="a8969-110">Namespace のプロビジョニング状態。</span><span class="sxs-lookup"><span data-stu-id="a8969-110">Provisioning state of the Namespace.</span></span></param>
        <param name="region"><span data-ttu-id="a8969-111">名前空間を作成する対象の地域を指定します。</span><span class="sxs-lookup"><span data-stu-id="a8969-111">Specifies the targeted region in which the namespace should be created.</span></span> <span data-ttu-id="a8969-112">次の値のいずれかのことができます: オーストラリア EastAustralia SoutheastCentral USEast USEast 米国 2West USNorth 中央 USSouth 中央 USEast AsiaSoutheast AsiaBrazil SouthJapan EastJapan WestNorth EuropeWest ヨーロッパ</span><span class="sxs-lookup"><span data-stu-id="a8969-112">It can be any of the following values: Australia EastAustralia SoutheastCentral USEast USEast US 2West USNorth Central USSouth Central USEast AsiaSoutheast AsiaBrazil SouthJapan EastJapan WestNorth EuropeWest Europe</span></span></param>
        <param name="status"><span data-ttu-id="a8969-113">名前空間の状態です。</span><span class="sxs-lookup"><span data-stu-id="a8969-113">Status of the namespace.</span></span> <span data-ttu-id="a8969-114">これらの値: 1 のいずれかのことができます = Created/Active2 = Creating3 Suspended4 を = = 削除しています</span><span class="sxs-lookup"><span data-stu-id="a8969-114">It can be any of these values:1 = Created/Active2 = Creating3 = Suspended4 = Deleting</span></span></param>
        <param name="createdAt"><span data-ttu-id="a8969-115">名前空間が作成された時刻。</span><span class="sxs-lookup"><span data-stu-id="a8969-115">The time the namespace was created.</span></span></param>
        <param name="serviceBusEndpoint"><span data-ttu-id="a8969-116">エンドポイントが NotificationHub 操作の実行に使用することができます。</span><span class="sxs-lookup"><span data-stu-id="a8969-116">Endpoint you can use to perform NotificationHub operations.</span></span></param>
        <param name="subscriptionId"><span data-ttu-id="a8969-117">名前空間に関連付けられている Azure サブスクリプションの Id。</span><span class="sxs-lookup"><span data-stu-id="a8969-117">The Id of the Azure subscription associated with the namespace.</span></span></param>
        <param name="scaleUnit"><span data-ttu-id="a8969-118">名前空間が作成される ScaleUnit</span><span class="sxs-lookup"><span data-stu-id="a8969-118">ScaleUnit where the namespace gets created</span></span></param>
        <param name="enabled"><span data-ttu-id="a8969-119">名前空間が現在有効かどうか。</span><span class="sxs-lookup"><span data-stu-id="a8969-119">Whether or not the namespace is currently enabled.</span></span></param>
        <param name="critical"><span data-ttu-id="a8969-120">かどうか、名前空間が"重大"に設定されます。</span><span class="sxs-lookup"><span data-stu-id="a8969-120">Whether or not the namespace is set as Critical.</span></span></param>
        <param name="namespaceType"><span data-ttu-id="a8969-121">名前空間の種類。</span><span class="sxs-lookup"><span data-stu-id="a8969-121">The namespace type.</span></span> <span data-ttu-id="a8969-122">使用可能な値が含まれます: 'メッセージング'、'NotificationHub'</span><span class="sxs-lookup"><span data-stu-id="a8969-122">Possible values include: 'Messaging', 'NotificationHub'</span></span></param>
        <summary>
            <span data-ttu-id="a8969-123">NamespaceResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a8969-123">Initializes a new instance of the NamespaceResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8969-124">取得または名前空間が作成された時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8969-124">Gets or sets the time the namespace was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Critical">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Critical { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Critical" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.Critical" />
      <MemberSignature Language="VB.NET" Value="Public Property Critical As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Critical : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.Critical" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.critical")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8969-125">取得または名前空間が"重大"として設定されているかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8969-125">Gets or sets whether or not the namespace is set as Critical.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8969-126">取得または名前空間が現在有効になっているかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8969-126">Gets or sets whether or not the namespace is currently enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NamespaceResourceName">
      <MemberSignature Language="C#" Value="public string NamespaceResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NamespaceResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.NamespaceResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property NamespaceResourceName As String" />
      <MemberSignature Language="F#" Value="member this.NamespaceResourceName : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.NamespaceResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8969-127">取得または名前空間の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8969-127">Gets or sets the name of the namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NamespaceType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; NamespaceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; NamespaceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.NamespaceType" />
      <MemberSignature Language="VB.NET" Value="Public Property NamespaceType As Nullable(Of NamespaceType)" />
      <MemberSignature Language="F#" Value="member this.NamespaceType : Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.NamespaceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.namespaceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8969-128">取得または名前空間の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8969-128">Gets or sets the namespace type.</span></span> <span data-ttu-id="a8969-129">使用可能な値が含まれます: 'メッセージング'、'NotificationHub'</span><span class="sxs-lookup"><span data-stu-id="a8969-129">Possible values include: 'Messaging', 'NotificationHub'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8969-130">取得または、Namespace のプロビジョニング状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8969-130">Gets or sets provisioning state of the Namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Region">
      <MemberSignature Language="C#" Value="public string Region { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Region" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.Region" />
      <MemberSignature Language="VB.NET" Value="Public Property Region As String" />
      <MemberSignature Language="F#" Value="member this.Region : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.Region" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.region")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8969-131">取得または設定は、名前空間を作成する対象の地域を指定します。</span><span class="sxs-lookup"><span data-stu-id="a8969-131">Gets or sets specifies the targeted region in which the namespace should be created.</span></span> <span data-ttu-id="a8969-132">次の値のいずれかのことができます: オーストラリア EastAustralia SoutheastCentral USEast USEast 米国 2West USNorth 中央 USSouth 中央 USEast AsiaSoutheast AsiaBrazil SouthJapan EastJapan WestNorth EuropeWest ヨーロッパ</span><span class="sxs-lookup"><span data-stu-id="a8969-132">It can be any of the following values: Australia EastAustralia SoutheastCentral USEast USEast US 2West USNorth Central USSouth Central USEast AsiaSoutheast AsiaBrazil SouthJapan EastJapan WestNorth EuropeWest Europe</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScaleUnit">
      <MemberSignature Language="C#" Value="public string ScaleUnit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScaleUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.ScaleUnit" />
      <MemberSignature Language="VB.NET" Value="Public Property ScaleUnit As String" />
      <MemberSignature Language="F#" Value="member this.ScaleUnit : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.ScaleUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scaleUnit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8969-133">取得または名前空間が作成される scaleUnit を設定</span><span class="sxs-lookup"><span data-stu-id="a8969-133">Gets or sets scaleUnit where the namespace gets created</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusEndpoint">
      <MemberSignature Language="C#" Value="public string ServiceBusEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.ServiceBusEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusEndpoint : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.ServiceBusEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceBusEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8969-134">取得または NotificationHub 操作の実行に使用できるエンドポイントを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8969-134">Gets or sets endpoint you can use to perform NotificationHub operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8969-135">取得または名前空間の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8969-135">Gets or sets status of the namespace.</span></span> <span data-ttu-id="a8969-136">これらの値: 1 のいずれかのことができます = Created/Active2 = Creating3 Suspended4 を = = 削除しています</span><span class="sxs-lookup"><span data-stu-id="a8969-136">It can be any of these values:1 = Created/Active2 = Creating3 = Suspended4 = Deleting</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceResource.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8969-137">取得または名前空間に関連付けられている Azure サブスクリプションの Id を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8969-137">Gets or sets the Id of the Azure subscription associated with the namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>