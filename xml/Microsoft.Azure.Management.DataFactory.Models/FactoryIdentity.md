<Type Name="FactoryIdentity" FullName="Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity">
  <TypeSignature Language="C#" Value="public class FactoryIdentity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi FactoryIdentity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity" />
  <TypeSignature Language="VB.NET" Value="Public Class FactoryIdentity" />
  <TypeSignature Language="F#" Value="type FactoryIdentity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="559a1-101">工場出荷時のリソースの id プロパティ。</span><span class="sxs-lookup"><span data-stu-id="559a1-101">Identity properties of the factory resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FactoryIdentity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="559a1-102">FactoryIdentity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="559a1-102">Initializes a new instance of the FactoryIdentity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FactoryIdentity (Nullable&lt;Guid&gt; principalId = null, Nullable&lt;Guid&gt; tenantId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; principalId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; tenantId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity.#ctor(System.Nullable{System.Guid},System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional principalId As Nullable(Of Guid) = null, Optional tenantId As Nullable(Of Guid) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity : Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity" Usage="new Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity (principalId, tenantId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="principalId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="tenantId" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="principalId"><span data-ttu-id="559a1-103">Id のプリンシパル id。</span><span class="sxs-lookup"><span data-stu-id="559a1-103">The principal id of the identity.</span></span></param>
        <param name="tenantId"><span data-ttu-id="559a1-104">Id のクライアントのテナント id です。</span><span class="sxs-lookup"><span data-stu-id="559a1-104">The client tenant id of the identity.</span></span></param>
        <summary>
            <span data-ttu-id="559a1-105">FactoryIdentity クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="559a1-105">Initializes a new instance of the FactoryIdentity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrincipalId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; PrincipalId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; PrincipalId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity.PrincipalId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrincipalId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.PrincipalId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity.PrincipalId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="559a1-106">Id のプリンシパル id を取得します。</span><span class="sxs-lookup"><span data-stu-id="559a1-106">Gets the principal id of the identity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; TenantId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TenantId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.TenantId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="559a1-107">Id のクライアントのテナント id を取得します。</span><span class="sxs-lookup"><span data-stu-id="559a1-107">Gets the client tenant id of the identity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public static string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity.Type" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.DataFactory.Models.FactoryIdentity.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="559a1-108">Id の種類。</span><span class="sxs-lookup"><span data-stu-id="559a1-108">The identity type.</span></span> <span data-ttu-id="559a1-109">現在、唯一サポートされている型は 'SystemAssigned' です。</span><span class="sxs-lookup"><span data-stu-id="559a1-109">Currently the only supported type is 'SystemAssigned'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>