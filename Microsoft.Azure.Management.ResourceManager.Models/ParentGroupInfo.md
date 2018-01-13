<Type Name="ParentGroupInfo" FullName="Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo">
  <TypeSignature Language="C#" Value="public class ParentGroupInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ParentGroupInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class ParentGroupInfo" />
  <TypeSignature Language="F#" Value="type ParentGroupInfo = class" />
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
            <span data-ttu-id="60406-101">(省略可能)親の管理グループの ID。</span><span class="sxs-lookup"><span data-stu-id="60406-101">(Optional) The ID of the parent management group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ParentGroupInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="60406-102">ParentGroupInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="60406-102">Initializes a new instance of the ParentGroupInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ParentGroupInfo (string parentId = null, string displayName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string parentId, string displayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional parentId As String = null, Optional displayName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo : string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo (parentId, displayName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="parentId" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentId"><span data-ttu-id="60406-103">親の管理グループの ID。</span><span class="sxs-lookup"><span data-stu-id="60406-103">The ID of the parent management group.</span></span> <span data-ttu-id="60406-104">例: </span><span class="sxs-lookup"><span data-stu-id="60406-104">E.g.</span></span>
            <span data-ttu-id="60406-105">/providers/Microsoft.Management/managementGroups/30000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="60406-105">/providers/Microsoft.Management/managementGroups/30000000-0000-0000-0000-000000000000</span></span></param>
        <param name="displayName"><span data-ttu-id="60406-106">管理グループのフレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="60406-106">The friendly name of the management group.</span></span></param>
        <summary>
            <span data-ttu-id="60406-107">ParentGroupInfo クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="60406-107">Initializes a new instance of the ParentGroupInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo.DisplayName" />
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
            <span data-ttu-id="60406-108">取得または管理グループのフレンドリ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="60406-108">Gets or sets the friendly name of the management group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParentId">
      <MemberSignature Language="C#" Value="public string ParentId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ParentId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo.ParentId" />
      <MemberSignature Language="VB.NET" Value="Public Property ParentId As String" />
      <MemberSignature Language="F#" Value="member this.ParentId : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ParentGroupInfo.ParentId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parentId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60406-109">取得または親の管理グループの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="60406-109">Gets or sets the ID of the parent management group.</span></span> <span data-ttu-id="60406-110">例: </span><span class="sxs-lookup"><span data-stu-id="60406-110">E.g.</span></span>
            <span data-ttu-id="60406-111">/providers/Microsoft.Management/managementGroups/30000000-0000-0000-0000-000000000000</span><span class="sxs-lookup"><span data-stu-id="60406-111">/providers/Microsoft.Management/managementGroups/30000000-0000-0000-0000-000000000000</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>