<Type Name="ManagementGroupWithChildren" FullName="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren">
  <TypeSignature Language="C#" Value="public class ManagementGroupWithChildren" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagementGroupWithChildren extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagementGroupWithChildren" />
  <TypeSignature Language="F#" Value="type ManagementGroupWithChildren = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="1758f-101">管理グループの詳細。</span><span class="sxs-lookup"><span data-stu-id="1758f-101">The management group details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementGroupWithChildren ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1758f-102">ManagementGroupWithChildren クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1758f-102">Initializes a new instance of the ManagementGroupWithChildren class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementGroupWithChildren (string id = null, string type = null, Nullable&lt;Guid&gt; name = null, Nullable&lt;Guid&gt; tenantId = null, string displayName = null, Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties details = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupChildInfo&gt; children = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string type, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; name, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; tenantId, string displayName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties details, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupChildInfo&gt; children) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren.#ctor(System.String,System.String,System.Nullable{System.Guid},System.Nullable{System.Guid},System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupChildInfo})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional type As String = null, Optional name As Nullable(Of Guid) = null, Optional tenantId As Nullable(Of Guid) = null, Optional displayName As String = null, Optional details As ManagementGroupDetailsProperties = null, Optional children As IList(Of ManagementGroupChildInfo) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren : string * string * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupChildInfo&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren (id, type, name, tenantId, displayName, details, children)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="name" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="tenantId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="details" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties" />
        <Parameter Name="children" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupChildInfo&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="1758f-103">管理グループの ID。</span><span class="sxs-lookup"><span data-stu-id="1758f-103">The ID of the management group.</span></span> <span data-ttu-id="1758f-104">例: </span><span class="sxs-lookup"><span data-stu-id="1758f-104">E.g.</span></span>
            <span data-ttu-id="1758f-105">/providers/Microsoft.Management/managementGroups/20000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="1758f-105">/providers/Microsoft.Management/managementGroups/20000000-0000-0000-0000-000000000000</span></span></param>
        <param name="type"><span data-ttu-id="1758f-106">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="1758f-106">The type of the resource.</span></span> <span data-ttu-id="1758f-107">例: </span><span class="sxs-lookup"><span data-stu-id="1758f-107">E.g.</span></span>
            <span data-ttu-id="1758f-108">/providers/Microsoft.Management/managementGroups</span><span class="sxs-lookup"><span data-stu-id="1758f-108">/providers/Microsoft.Management/managementGroups</span></span></param>
        <param name="name"><span data-ttu-id="1758f-109">管理グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1758f-109">The name of the management group.</span></span> <span data-ttu-id="1758f-110">例: </span><span class="sxs-lookup"><span data-stu-id="1758f-110">E.g.</span></span>
            <span data-ttu-id="1758f-111">20000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="1758f-111">20000000-0000-0000-0000-000000000000</span></span></param>
        <param name="tenantId"><span data-ttu-id="1758f-112">管理グループに関連付けられている AAD テナント ID です。</span><span class="sxs-lookup"><span data-stu-id="1758f-112">The AAD Tenant ID associated with the management group.</span></span> <span data-ttu-id="1758f-113">例: </span><span class="sxs-lookup"><span data-stu-id="1758f-113">E.g.</span></span> <span data-ttu-id="1758f-114">10000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="1758f-114">10000000-0000-0000-0000-000000000000</span></span></param>
        <param name="displayName"><span data-ttu-id="1758f-115">管理グループのフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="1758f-115">The friendly name of the management group.</span></span></param>
        <param name="details"><span data-ttu-id="1758f-116">詳細</span><span class="sxs-lookup"><span data-stu-id="1758f-116">Details</span></span></param>
        <param name="children"><span data-ttu-id="1758f-117">子の一覧です。</span><span class="sxs-lookup"><span data-stu-id="1758f-117">The list of children.</span></span></param>
        <summary>
            <span data-ttu-id="1758f-118">ManagementGroupWithChildren クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1758f-118">Initializes a new instance of the ManagementGroupWithChildren class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Children">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupChildInfo&gt; Children { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupChildInfo&gt; Children" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren.Children" />
      <MemberSignature Language="VB.NET" Value="Public Property Children As IList(Of ManagementGroupChildInfo)" />
      <MemberSignature Language="F#" Value="member this.Children : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupChildInfo&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren.Children" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.children")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupChildInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1758f-119">取得または子のリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="1758f-119">Gets or sets the list of children.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As ManagementGroupDetailsProperties" />
      <MemberSignature Language="F#" Value="member this.Details : Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1758f-120">取得または設定の詳細</span><span class="sxs-lookup"><span data-stu-id="1758f-120">Gets or sets details</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1758f-121">取得または管理グループのフレンドリ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="1758f-121">Gets or sets the friendly name of the management group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="1758f-122">管理グループの ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="1758f-122">Gets the ID of the management group.</span></span> <span data-ttu-id="1758f-123">例: </span><span class="sxs-lookup"><span data-stu-id="1758f-123">E.g.</span></span>
            <span data-ttu-id="1758f-124">/providers/Microsoft.Management/managementGroups/20000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="1758f-124">/providers/Microsoft.Management/managementGroups/20000000-0000-0000-0000-000000000000</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.Name : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1758f-125">管理グループの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="1758f-125">Gets the name of the management group.</span></span> <span data-ttu-id="1758f-126">例: </span><span class="sxs-lookup"><span data-stu-id="1758f-126">E.g.</span></span>
            <span data-ttu-id="1758f-127">20000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="1758f-127">20000000-0000-0000-0000-000000000000</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; TenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.TenantId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1758f-128">取得または管理グループに関連付けられている AAD テナント ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="1758f-128">Gets or sets the AAD Tenant ID associated with the management group.</span></span> <span data-ttu-id="1758f-129">例: </span><span class="sxs-lookup"><span data-stu-id="1758f-129">E.g.</span></span> <span data-ttu-id="1758f-130">10000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="1758f-130">10000000-0000-0000-0000-000000000000</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithChildren.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="1758f-131">リソースの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="1758f-131">Gets the type of the resource.</span></span> <span data-ttu-id="1758f-132">例: </span><span class="sxs-lookup"><span data-stu-id="1758f-132">E.g.</span></span>
            <span data-ttu-id="1758f-133">/providers/Microsoft.Management/managementGroups</span><span class="sxs-lookup"><span data-stu-id="1758f-133">/providers/Microsoft.Management/managementGroups</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>