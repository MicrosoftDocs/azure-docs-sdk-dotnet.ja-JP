<Type Name="VirtualMachineIdentity" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity">
  <TypeSignature Language="C#" Value="public class VirtualMachineIdentity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineIdentity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineIdentity" />
  <TypeSignature Language="F#" Value="type VirtualMachineIdentity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2e032-101">仮想マシンの id です。</span><span class="sxs-lookup"><span data-stu-id="2e032-101">Identity for the virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineIdentity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2e032-102">VirtualMachineIdentity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2e032-102">Initializes a new instance of the VirtualMachineIdentity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineIdentity (string principalId = null, string tenantId = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string principalId, string tenantId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Models.ResourceIdentityType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional principalId As String = null, Optional tenantId As String = null, Optional type As Nullable(Of ResourceIdentityType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity : string * string * Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity (principalId, tenantId, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="principalId" Type="System.String" />
        <Parameter Name="tenantId" Type="System.String" />
        <Parameter Name="type" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt;" />
      </Parameters>
      <Docs>
        <param name="principalId"><span data-ttu-id="2e032-103">バーチャル マシン id のプリンシパル id。</span><span class="sxs-lookup"><span data-stu-id="2e032-103">The principal id of virtual machine identity.</span></span></param>
        <param name="tenantId"><span data-ttu-id="2e032-104">仮想マシンに関連付けられているテナントの id です。</span><span class="sxs-lookup"><span data-stu-id="2e032-104">The tenant id associated with the virtual machine.</span></span></param>
        <param name="type"><span data-ttu-id="2e032-105">仮想マシンに使用される id の種類。</span><span class="sxs-lookup"><span data-stu-id="2e032-105">The type of identity used for the virtual machine.</span></span> <span data-ttu-id="2e032-106">現時点では、唯一サポートされている型は、'SystemAssigned' は、暗黙的に id を作成します。</span><span class="sxs-lookup"><span data-stu-id="2e032-106">Currently, the only supported type is 'SystemAssigned', which implicitly creates an identity.</span></span> <span data-ttu-id="2e032-107">使用可能な値が含まれます: 'SystemAssigned'</span><span class="sxs-lookup"><span data-stu-id="2e032-107">Possible values include: 'SystemAssigned'</span></span></param>
        <summary>
            <span data-ttu-id="2e032-108">VirtualMachineIdentity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2e032-108">Initializes a new instance of the VirtualMachineIdentity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrincipalId">
      <MemberSignature Language="C#" Value="public string PrincipalId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity.PrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrincipalId As String" />
      <MemberSignature Language="F#" Value="member this.PrincipalId : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity.PrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="2e032-109">バーチャル マシン id のプリンシパル id を取得します。</span><span class="sxs-lookup"><span data-stu-id="2e032-109">Gets the principal id of virtual machine identity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="2e032-110">仮想マシンに関連付けられているテナント id を取得します。</span><span class="sxs-lookup"><span data-stu-id="2e032-110">Gets the tenant id associated with the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As Nullable(Of ResourceIdentityType)" />
      <MemberSignature Language="F#" Value="member this.Type : Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.ResourceIdentityType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e032-111">取得または仮想マシンに使用される id の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="2e032-111">Gets or sets the type of identity used for the virtual machine.</span></span>
            <span data-ttu-id="2e032-112">現時点では、唯一サポートされている型は、'SystemAssigned' は、暗黙的に id を作成します。</span><span class="sxs-lookup"><span data-stu-id="2e032-112">Currently, the only supported type is 'SystemAssigned', which implicitly creates an identity.</span></span> <span data-ttu-id="2e032-113">使用可能な値が含まれます: 'SystemAssigned'</span><span class="sxs-lookup"><span data-stu-id="2e032-113">Possible values include: 'SystemAssigned'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>