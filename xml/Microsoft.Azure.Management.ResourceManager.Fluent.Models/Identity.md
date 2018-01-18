<Type Name="Identity" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity">
  <TypeSignature Language="C#" Value="public class Identity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Identity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity" />
  <TypeSignature Language="VB.NET" Value="Public Class Identity" />
  <TypeSignature Language="F#" Value="type Identity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c5b55-101">リソースの id です。</span><span class="sxs-lookup"><span data-stu-id="c5b55-101">Identity for the resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Identity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c5b55-102">Id クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c5b55-102">Initializes a new instance of the Identity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Identity (string principalId = null, string tenantId = null, Nullable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceIdentityType&gt; type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string principalId, string tenantId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceIdentityType&gt; type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceIdentityType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional principalId As String = null, Optional tenantId As String = null, Optional type As Nullable(Of ResourceIdentityType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity : string * string * Nullable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceIdentityType&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity (principalId, tenantId, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="principalId" Type="System.String" />
        <Parameter Name="tenantId" Type="System.String" />
        <Parameter Name="type" Type="System.Nullable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceIdentityType&gt;" />
      </Parameters>
      <Docs>
        <param name="principalId"><span data-ttu-id="c5b55-103">リソース id のプリンシパル id。</span><span class="sxs-lookup"><span data-stu-id="c5b55-103">The principal id of resource identity.</span></span></param>
        <param name="tenantId"><span data-ttu-id="c5b55-104">リソースのテナント id。</span><span class="sxs-lookup"><span data-stu-id="c5b55-104">The tenant id of resource.</span></span></param>
        <param name="type"><span data-ttu-id="c5b55-105">Id の種類。</span><span class="sxs-lookup"><span data-stu-id="c5b55-105">The identity type.</span></span> <span data-ttu-id="c5b55-106">使用可能な値が含まれます: 'SystemAssigned'</span><span class="sxs-lookup"><span data-stu-id="c5b55-106">Possible values include: 'SystemAssigned'</span></span></param>
        <summary>
            <span data-ttu-id="c5b55-107">Id クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c5b55-107">Initializes a new instance of the Identity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrincipalId">
      <MemberSignature Language="C#" Value="public string PrincipalId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity.PrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrincipalId As String" />
      <MemberSignature Language="F#" Value="member this.PrincipalId : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity.PrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="principalId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c5b55-108">リソース id のプリンシパル id を取得します。</span><span class="sxs-lookup"><span data-stu-id="c5b55-108">Gets the principal id of resource identity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="c5b55-109">リソースのテナント id を取得します。</span><span class="sxs-lookup"><span data-stu-id="c5b55-109">Gets the tenant id of resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceIdentityType&gt; Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceIdentityType&gt; Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As Nullable(Of ResourceIdentityType)" />
      <MemberSignature Language="F#" Value="member this.Type : Nullable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceIdentityType&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Models.Identity.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceIdentityType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c5b55-110">取得または id の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="c5b55-110">Gets or sets the identity type.</span></span> <span data-ttu-id="c5b55-111">使用可能な値が含まれます: 'SystemAssigned'</span><span class="sxs-lookup"><span data-stu-id="c5b55-111">Possible values include: 'SystemAssigned'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>