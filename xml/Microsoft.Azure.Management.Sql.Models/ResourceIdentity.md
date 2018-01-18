<Type Name="ResourceIdentity" FullName="Microsoft.Azure.Management.Sql.Models.ResourceIdentity">
  <TypeSignature Language="C#" Value="public class ResourceIdentity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceIdentity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ResourceIdentity" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceIdentity" />
  <TypeSignature Language="F#" Value="type ResourceIdentity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a2086-101">Azure Active Directory id のリソースを構成します。</span><span class="sxs-lookup"><span data-stu-id="a2086-101">Azure Active Directory identity configuration for a resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceIdentity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ResourceIdentity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a2086-102">ResourceIdentity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a2086-102">Initializes a new instance of the ResourceIdentity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceIdentity (Nullable&lt;Guid&gt; principalId = null, string type = null, Nullable&lt;Guid&gt; tenantId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; principalId, string type, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; tenantId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ResourceIdentity.#ctor(System.Nullable{System.Guid},System.String,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional principalId As Nullable(Of Guid) = null, Optional type As String = null, Optional tenantId As Nullable(Of Guid) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ResourceIdentity : Nullable&lt;Guid&gt; * string * Nullable&lt;Guid&gt; -&gt; Microsoft.Azure.Management.Sql.Models.ResourceIdentity" Usage="new Microsoft.Azure.Management.Sql.Models.ResourceIdentity (principalId, type, tenantId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="principalId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tenantId" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="principalId"><span data-ttu-id="a2086-103">Azure Active Directory のプリンシパル id。</span><span class="sxs-lookup"><span data-stu-id="a2086-103">The Azure Active Directory principal id.</span></span></param>
        <param name="type"><span data-ttu-id="a2086-104">Id の種類。</span><span class="sxs-lookup"><span data-stu-id="a2086-104">The identity type.</span></span> <span data-ttu-id="a2086-105">これを自動的に作成し、Azure Active Directory のプリンシパルのリソースを割り当てるために 'SystemAssigned' に設定します。</span><span class="sxs-lookup"><span data-stu-id="a2086-105">Set this to 'SystemAssigned' in order to automatically create and assign an Azure Active Directory principal for the resource.</span></span> <span data-ttu-id="a2086-106">使用可能な値が含まれます: 'SystemAssigned'</span><span class="sxs-lookup"><span data-stu-id="a2086-106">Possible values include: 'SystemAssigned'</span></span></param>
        <param name="tenantId"><span data-ttu-id="a2086-107">Azure Active Directory テナント id です。</span><span class="sxs-lookup"><span data-stu-id="a2086-107">The Azure Active Directory tenant id.</span></span></param>
        <summary>
            <span data-ttu-id="a2086-108">ResourceIdentity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a2086-108">Initializes a new instance of the ResourceIdentity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrincipalId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; PrincipalId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; PrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ResourceIdentity.PrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrincipalId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.PrincipalId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ResourceIdentity.PrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="principalId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2086-109">Azure Active Directory のプリンシパル id を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2086-109">Gets the Azure Active Directory principal id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; TenantId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ResourceIdentity.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TenantId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.TenantId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ResourceIdentity.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
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
            <span data-ttu-id="a2086-110">Azure Active Directory テナント id を取得します。</span><span class="sxs-lookup"><span data-stu-id="a2086-110">Gets the Azure Active Directory tenant id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ResourceIdentity.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ResourceIdentity.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
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
            <span data-ttu-id="a2086-111">取得または id の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="a2086-111">Gets or sets the identity type.</span></span> <span data-ttu-id="a2086-112">これを自動的に作成し、Azure Active Directory のプリンシパルのリソースを割り当てるために 'SystemAssigned' に設定します。</span><span class="sxs-lookup"><span data-stu-id="a2086-112">Set this to 'SystemAssigned' in order to automatically create and assign an Azure Active Directory principal for the resource.</span></span> <span data-ttu-id="a2086-113">使用可能な値が含まれます: 'SystemAssigned'</span><span class="sxs-lookup"><span data-stu-id="a2086-113">Possible values include: 'SystemAssigned'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>