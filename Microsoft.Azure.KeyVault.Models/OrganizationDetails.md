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
            証明書の発行者の構成の詳細です。
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
            OrganizationDetails クラスの新しいインスタンスを初期化します。
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
        <param name="id">組織の id です。</param>
        <param name="adminDetails">組織の管理者の詳細です。</param>
        <summary>
            OrganizationDetails クラスの新しいインスタンスを初期化します。
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
            取得または組織の管理者の詳細を設定します。
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
            取得または組織の id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>