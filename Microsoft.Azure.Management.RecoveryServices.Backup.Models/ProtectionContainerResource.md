<Type Name="ProtectionContainerResource" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource">
  <TypeSignature Language="C#" Value="public class ProtectionContainerResource : Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProtectionContainerResource extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource" />
  <TypeSignature Language="VB.NET" Value="Public Class ProtectionContainerResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ProtectionContainerResource = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7bbf4-101">バックアップ アイテムのコンテナーの基本クラス。</span><span class="sxs-lookup"><span data-stu-id="7bbf4-101">Base class for container with backup items.</span></span> <span data-ttu-id="7bbf4-102">特定のワークロードを使用したコンテナーは、このクラスから派生します。</span><span class="sxs-lookup"><span data-stu-id="7bbf4-102">Containers with specific workloads are derived from this class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectionContainerResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7bbf4-103">ProtectionContainerResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7bbf4-103">Initializes a new instance of the ProtectionContainerResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectionContainerResource (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string eTag = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string eTag, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional eTag As String = null, Optional properties As ProtectionContainer = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource (id, name, type, location, tags, eTag, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="7bbf4-104">リソース Id は、リソースへの完全なパスを表します。</span><span class="sxs-lookup"><span data-stu-id="7bbf4-104">Resource Id represents the complete path to the resource.</span></span></param>
        <param name="name"><span data-ttu-id="7bbf4-105">リソースに関連付けられているリソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="7bbf4-105">Resource name associated with the resource.</span></span></param>
        <param name="type"><span data-ttu-id="7bbf4-106">リソースの種類は Namespace/ResourceType/ResourceType/... 形式の完全なパスを表します</span><span class="sxs-lookup"><span data-stu-id="7bbf4-106">Resource type represents the complete path of the form Namespace/ResourceType/ResourceType/...</span></span></param>
        <param name="location"><span data-ttu-id="7bbf4-107">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="7bbf4-107">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="7bbf4-108">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="7bbf4-108">Resource tags.</span></span></param>
        <param name="eTag"><span data-ttu-id="7bbf4-109">省略可能な ETag です。</span><span class="sxs-lookup"><span data-stu-id="7bbf4-109">Optional ETag.</span></span></param>
        <param name="properties"><span data-ttu-id="7bbf4-110">ProtectionContainerResource プロパティ</span><span class="sxs-lookup"><span data-stu-id="7bbf4-110">ProtectionContainerResource properties</span></span></param>
        <summary>
            <span data-ttu-id="7bbf4-111">ProtectionContainerResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7bbf4-111">Initializes a new instance of the ProtectionContainerResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As ProtectionContainer" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7bbf4-112">取得または設定 protectionContainerResource プロパティ</span><span class="sxs-lookup"><span data-stu-id="7bbf4-112">Gets or sets protectionContainerResource properties</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>