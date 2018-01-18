<Type Name="TenantIdDescription" FullName="Microsoft.Azure.Management.ResourceManager.Models.TenantIdDescription">
  <TypeSignature Language="C#" Value="public class TenantIdDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TenantIdDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.TenantIdDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class TenantIdDescription" />
  <TypeSignature Language="F#" Value="type TenantIdDescription = class" />
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
            <span data-ttu-id="107a2-101">テナント Id 情報です。</span><span class="sxs-lookup"><span data-stu-id="107a2-101">Tenant Id information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TenantIdDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.TenantIdDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="107a2-102">TenantIdDescription クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="107a2-102">Initializes a new instance of the TenantIdDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TenantIdDescription (string id = null, string tenantId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string tenantId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.TenantIdDescription.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional tenantId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.TenantIdDescription : string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.TenantIdDescription" Usage="new Microsoft.Azure.Management.ResourceManager.Models.TenantIdDescription (id, tenantId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="tenantId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="107a2-103">テナントの完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="107a2-103">The fully qualified ID of the tenant.</span></span> <span data-ttu-id="107a2-104">たとえば、/tenants/00000000-0000-0000-0000-000000000000 です。</span><span class="sxs-lookup"><span data-stu-id="107a2-104">For example, /tenants/00000000-0000-0000-0000-000000000000.</span></span></param>
        <param name="tenantId"><span data-ttu-id="107a2-105">テナント id。</span><span class="sxs-lookup"><span data-stu-id="107a2-105">The tenant ID.</span></span> <span data-ttu-id="107a2-106">たとえば、00000000-0000-0000-0000-000000000000 です。</span><span class="sxs-lookup"><span data-stu-id="107a2-106">For example, 00000000-0000-0000-0000-000000000000.</span></span></param>
        <summary>
            <span data-ttu-id="107a2-107">TenantIdDescription クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="107a2-107">Initializes a new instance of the TenantIdDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.TenantIdDescription.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.TenantIdDescription.Id" />
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
            <span data-ttu-id="107a2-108">テナントの完全修飾 ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="107a2-108">Gets the fully qualified ID of the tenant.</span></span> <span data-ttu-id="107a2-109">たとえば、/tenants/00000000-0000-0000-0000-000000000000 です。</span><span class="sxs-lookup"><span data-stu-id="107a2-109">For example, /tenants/00000000-0000-0000-0000-000000000000.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.TenantIdDescription.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.TenantIdDescription.TenantId" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="107a2-110">テナント ID を取得します</span><span class="sxs-lookup"><span data-stu-id="107a2-110">Gets the tenant ID.</span></span> <span data-ttu-id="107a2-111">たとえば、00000000-0000-0000-0000-000000000000 です。</span><span class="sxs-lookup"><span data-stu-id="107a2-111">For example, 00000000-0000-0000-0000-000000000000.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>