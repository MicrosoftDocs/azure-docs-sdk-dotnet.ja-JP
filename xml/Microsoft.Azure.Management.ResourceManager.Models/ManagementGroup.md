<Type Name="ManagementGroup" FullName="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup">
  <TypeSignature Language="C#" Value="public class ManagementGroup" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagementGroup extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagementGroup" />
  <TypeSignature Language="F#" Value="type ManagementGroup = class" />
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
            <span data-ttu-id="de593-101">管理グループの詳細。</span><span class="sxs-lookup"><span data-stu-id="de593-101">The management group details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="de593-102">ManagementGroup クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="de593-102">Initializes a new instance of the ManagementGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementGroup (string id = null, string type = null, Nullable&lt;Guid&gt; name = null, Nullable&lt;Guid&gt; tenantId = null, string displayName = null, Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties details = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string type, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; name, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; tenantId, string displayName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties details) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.#ctor(System.String,System.String,System.Nullable{System.Guid},System.Nullable{System.Guid},System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional type As String = null, Optional name As Nullable(Of Guid) = null, Optional tenantId As Nullable(Of Guid) = null, Optional displayName As String = null, Optional details As ManagementGroupDetailsProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup : string * string * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup (id, type, name, tenantId, displayName, details)" />
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
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="de593-103">管理グループの ID。</span><span class="sxs-lookup"><span data-stu-id="de593-103">The ID of the management group.</span></span> <span data-ttu-id="de593-104">例: </span><span class="sxs-lookup"><span data-stu-id="de593-104">E.g.</span></span>
            <span data-ttu-id="de593-105">/providers/Microsoft.Management/managementGroups/20000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="de593-105">/providers/Microsoft.Management/managementGroups/20000000-0000-0000-0000-000000000000</span></span></param>
        <param name="type"><span data-ttu-id="de593-106">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="de593-106">The type of the resource.</span></span> <span data-ttu-id="de593-107">例: </span><span class="sxs-lookup"><span data-stu-id="de593-107">E.g.</span></span>
            <span data-ttu-id="de593-108">/providers/Microsoft.Management/managementGroups</span><span class="sxs-lookup"><span data-stu-id="de593-108">/providers/Microsoft.Management/managementGroups</span></span></param>
        <param name="name"><span data-ttu-id="de593-109">管理グループの名前。</span><span class="sxs-lookup"><span data-stu-id="de593-109">The name of the management group.</span></span> <span data-ttu-id="de593-110">例: </span><span class="sxs-lookup"><span data-stu-id="de593-110">E.g.</span></span>
            <span data-ttu-id="de593-111">20000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="de593-111">20000000-0000-0000-0000-000000000000</span></span></param>
        <param name="tenantId"><span data-ttu-id="de593-112">管理グループに関連付けられている AAD テナント ID です。</span><span class="sxs-lookup"><span data-stu-id="de593-112">The AAD Tenant ID associated with the management group.</span></span> <span data-ttu-id="de593-113">例: </span><span class="sxs-lookup"><span data-stu-id="de593-113">E.g.</span></span> <span data-ttu-id="de593-114">10000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="de593-114">10000000-0000-0000-0000-000000000000</span></span></param>
        <param name="displayName"><span data-ttu-id="de593-115">管理グループのフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="de593-115">The friendly name of the management group.</span></span></param>
        <param name="details"><span data-ttu-id="de593-116">詳細</span><span class="sxs-lookup"><span data-stu-id="de593-116">Details</span></span></param>
        <summary>
            <span data-ttu-id="de593-117">ManagementGroup クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="de593-117">Initializes a new instance of the ManagementGroup class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties Details { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.Details" />
      <MemberSignature Language="VB.NET" Value="Public Property Details As ManagementGroupDetailsProperties" />
      <MemberSignature Language="F#" Value="member this.Details : Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupDetailsProperties with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.Details" />
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
            <span data-ttu-id="de593-118">取得または設定の詳細</span><span class="sxs-lookup"><span data-stu-id="de593-118">Gets or sets details</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.DisplayName" />
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
            <span data-ttu-id="de593-119">取得または管理グループのフレンドリ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="de593-119">Gets or sets the friendly name of the management group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.Id" />
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
            <span data-ttu-id="de593-120">管理グループの ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="de593-120">Gets the ID of the management group.</span></span> <span data-ttu-id="de593-121">例: </span><span class="sxs-lookup"><span data-stu-id="de593-121">E.g.</span></span>
            <span data-ttu-id="de593-122">/providers/Microsoft.Management/managementGroups/20000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="de593-122">/providers/Microsoft.Management/managementGroups/20000000-0000-0000-0000-000000000000</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.Name : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.Name" />
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
            <span data-ttu-id="de593-123">管理グループの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="de593-123">Gets the name of the management group.</span></span> <span data-ttu-id="de593-124">例: </span><span class="sxs-lookup"><span data-stu-id="de593-124">E.g.</span></span>
            <span data-ttu-id="de593-125">20000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="de593-125">20000000-0000-0000-0000-000000000000</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; TenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.TenantId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.TenantId" />
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
            <span data-ttu-id="de593-126">取得または管理グループに関連付けられている AAD テナント ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="de593-126">Gets or sets the AAD Tenant ID associated with the management group.</span></span> <span data-ttu-id="de593-127">例: </span><span class="sxs-lookup"><span data-stu-id="de593-127">E.g.</span></span> <span data-ttu-id="de593-128">10000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="de593-128">10000000-0000-0000-0000-000000000000</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroup.Type" />
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
            <span data-ttu-id="de593-129">リソースの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="de593-129">Gets the type of the resource.</span></span> <span data-ttu-id="de593-130">例: </span><span class="sxs-lookup"><span data-stu-id="de593-130">E.g.</span></span>
            <span data-ttu-id="de593-131">/providers/Microsoft.Management/managementGroups</span><span class="sxs-lookup"><span data-stu-id="de593-131">/providers/Microsoft.Management/managementGroups</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>