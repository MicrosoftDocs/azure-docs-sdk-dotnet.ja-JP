<Type Name="ManagementGroupRecursiveChildInfo" FullName="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo">
  <TypeSignature Language="C#" Value="public class ManagementGroupRecursiveChildInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagementGroupRecursiveChildInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagementGroupRecursiveChildInfo" />
  <TypeSignature Language="F#" Value="type ManagementGroupRecursiveChildInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="42ace-101">管理グループの一意の識別子 (ID)。</span><span class="sxs-lookup"><span data-stu-id="42ace-101">The unique identifier (ID) of a management group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementGroupRecursiveChildInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="42ace-102">ManagementGroupRecursiveChildInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="42ace-102">Initializes a new instance of the ManagementGroupRecursiveChildInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementGroupRecursiveChildInfo (string childType = null, string childId = null, string displayName = null, Nullable&lt;Guid&gt; tenantId = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo&gt; children = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string childType, string childId, string displayName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; tenantId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo&gt; children) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo.#ctor(System.String,System.String,System.String,System.Nullable{System.Guid},System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional childType As String = null, Optional childId As String = null, Optional displayName As String = null, Optional tenantId As Nullable(Of Guid) = null, Optional children As IList(Of ManagementGroupRecursiveChildInfo) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo : string * string * string * Nullable&lt;Guid&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo (childType, childId, displayName, tenantId, children)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="childType" Type="System.String" />
        <Parameter Name="childId" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="tenantId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="children" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo&gt;" />
      </Parameters>
      <Docs>
        <param name="childType"><span data-ttu-id="42ace-103">管理グループの再帰的なお子様の情報</span><span class="sxs-lookup"><span data-stu-id="42ace-103">Managment Group Recursive Child Info</span></span></param>
        <param name="childId"><span data-ttu-id="42ace-104">管理グループ (サブスクリプション) の子リソースの ID。</span><span class="sxs-lookup"><span data-stu-id="42ace-104">The ID of the child resource (management group or subscription).</span></span> <span data-ttu-id="42ace-105">例: </span><span class="sxs-lookup"><span data-stu-id="42ace-105">E.g.</span></span>
            <span data-ttu-id="42ace-106">/providers/Microsoft.Management/managementGroups/40000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="42ace-106">/providers/Microsoft.Management/managementGroups/40000000-0000-0000-0000-000000000000</span></span></param>
        <param name="displayName"><span data-ttu-id="42ace-107">子リソースのフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="42ace-107">The friendly name of the child resource.</span></span></param>
        <param name="tenantId"><span data-ttu-id="42ace-108">(省略可能)子リソースに関連付けられている AAD テナント ID です。</span><span class="sxs-lookup"><span data-stu-id="42ace-108">(Optional) The AAD Tenant ID associated with the child resource.</span></span></param>
        <param name="children"><span data-ttu-id="42ace-109">子の一覧です。</span><span class="sxs-lookup"><span data-stu-id="42ace-109">The list of children.</span></span></param>
        <summary>
            <span data-ttu-id="42ace-110">ManagementGroupRecursiveChildInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="42ace-110">Initializes a new instance of the ManagementGroupRecursiveChildInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChildId">
      <MemberSignature Language="C#" Value="public string ChildId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ChildId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo.ChildId" />
      <MemberSignature Language="VB.NET" Value="Public Property ChildId As String" />
      <MemberSignature Language="F#" Value="member this.ChildId : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo.ChildId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="childId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="42ace-111">取得または管理グループ (サブスクリプション) の子リソースの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="42ace-111">Gets or sets the ID of the child resource (management group or subscription).</span></span> <span data-ttu-id="42ace-112">例: </span><span class="sxs-lookup"><span data-stu-id="42ace-112">E.g.</span></span>
            <span data-ttu-id="42ace-113">/providers/Microsoft.Management/managementGroups/40000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="42ace-113">/providers/Microsoft.Management/managementGroups/40000000-0000-0000-0000-000000000000</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Children">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo&gt; Children { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo&gt; Children" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo.Children" />
      <MemberSignature Language="VB.NET" Value="Public Property Children As IList(Of ManagementGroupRecursiveChildInfo)" />
      <MemberSignature Language="F#" Value="member this.Children : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo.Children" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="children")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="42ace-114">取得または子のリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="42ace-114">Gets or sets the list of children.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChildType">
      <MemberSignature Language="C#" Value="public string ChildType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ChildType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo.ChildType" />
      <MemberSignature Language="VB.NET" Value="Public Property ChildType As String" />
      <MemberSignature Language="F#" Value="member this.ChildType : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo.ChildType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="childType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="42ace-115">取得または設定の管理グループの再帰的なお子様の情報</span><span class="sxs-lookup"><span data-stu-id="42ace-115">Gets or sets managment Group Recursive Child Info</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="42ace-116">使用可能な値が含まれます: '登録', 'Department'、'Account', 'Subscription'</span><span class="sxs-lookup"><span data-stu-id="42ace-116">Possible values include: 'Enrollment', 'Department', 'Account', 'Subscription'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="42ace-117">取得または子リソースのフレンドリ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="42ace-117">Gets or sets the friendly name of the child resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; TenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.TenantId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupRecursiveChildInfo.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="42ace-118">取得または (省略可能)、AAD テナントに関連付けられた ID 子リソースを設定します。</span><span class="sxs-lookup"><span data-stu-id="42ace-118">Gets or sets (Optional) The AAD Tenant ID associated with the child resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>