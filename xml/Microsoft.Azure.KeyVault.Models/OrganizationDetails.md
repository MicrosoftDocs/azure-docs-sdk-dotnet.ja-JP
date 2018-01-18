<Type Name="OrganizationDetails" FullName="Microsoft.Azure.KeyVault.Models.OrganizationDetails">
  <TypeSignature Language="C#" Value="public class OrganizationDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OrganizationDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class OrganizationDetails" />
  <TypeSignature Language="F#" Value="type OrganizationDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="35395-101">証明書の発行者の構成の詳細です。</span><span class="sxs-lookup"><span data-stu-id="35395-101">Details of the organization of the certificate issuer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OrganizationDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.OrganizationDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="35395-102">OrganizationDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="35395-102">Initializes a new instance of the OrganizationDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OrganizationDetails (string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.KeyVault.Models.AdministratorDetails&gt; adminDetails = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.KeyVault.Models.AdministratorDetails&gt; adminDetails) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.OrganizationDetails.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.KeyVault.Models.AdministratorDetails})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional adminDetails As IList(Of AdministratorDetails) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.OrganizationDetails : string * System.Collections.Generic.IList&lt;Microsoft.Azure.KeyVault.Models.AdministratorDetails&gt; -&gt; Microsoft.Azure.KeyVault.Models.OrganizationDetails" Usage="new Microsoft.Azure.KeyVault.Models.OrganizationDetails (id, adminDetails)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="adminDetails" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.KeyVault.Models.AdministratorDetails&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="35395-103">組織の id です。</span><span class="sxs-lookup"><span data-stu-id="35395-103">Id of the organization.</span></span></param>
        <param name="adminDetails"><span data-ttu-id="35395-104">組織の管理者の詳細です。</span><span class="sxs-lookup"><span data-stu-id="35395-104">Details of the organization administrator.</span></span></param>
        <summary>
            <span data-ttu-id="35395-105">OrganizationDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="35395-105">Initializes a new instance of the OrganizationDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminDetails">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.KeyVault.Models.AdministratorDetails&gt; AdminDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.KeyVault.Models.AdministratorDetails&gt; AdminDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.OrganizationDetails.AdminDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminDetails As IList(Of AdministratorDetails)" />
      <MemberSignature Language="F#" Value="member this.AdminDetails : System.Collections.Generic.IList&lt;Microsoft.Azure.KeyVault.Models.AdministratorDetails&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.OrganizationDetails.AdminDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="admin_details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.KeyVault.Models.AdministratorDetails&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="35395-106">取得または組織の管理者の詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="35395-106">Gets or sets details of the organization administrator.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.OrganizationDetails.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.OrganizationDetails.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
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
            <span data-ttu-id="35395-107">取得または組織の id を設定します。</span><span class="sxs-lookup"><span data-stu-id="35395-107">Gets or sets id of the organization.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>