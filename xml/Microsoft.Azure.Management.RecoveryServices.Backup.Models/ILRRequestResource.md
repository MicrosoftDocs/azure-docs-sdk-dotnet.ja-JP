<Type Name="ILRRequestResource" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource">
  <TypeSignature Language="C#" Value="public class ILRRequestResource : Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ILRRequestResource extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource" />
  <TypeSignature Language="VB.NET" Value="Public Class ILRRequestResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ILRRequestResource = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="2e484-101">API のファイルとフォルダーを復元するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="2e484-101">Parameters to restore file/folders API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ILRRequestResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2e484-102">ILRRequestResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2e484-102">Initializes a new instance of the ILRRequestResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ILRRequestResource (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string eTag = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequest properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string eTag, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequest properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequest)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional eTag As String = null, Optional properties As ILRRequest = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequest -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource (id, name, type, location, tags, eTag, properties)" />
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
        <Parameter Name="properties" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequest" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="2e484-103">リソース Id は、リソースへの完全なパスを表します。</span><span class="sxs-lookup"><span data-stu-id="2e484-103">Resource Id represents the complete path to the resource.</span></span></param>
        <param name="name"><span data-ttu-id="2e484-104">リソースに関連付けられているリソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="2e484-104">Resource name associated with the resource.</span></span></param>
        <param name="type"><span data-ttu-id="2e484-105">リソースの種類は Namespace/ResourceType/ResourceType/... 形式の完全なパスを表します</span><span class="sxs-lookup"><span data-stu-id="2e484-105">Resource type represents the complete path of the form Namespace/ResourceType/ResourceType/...</span></span></param>
        <param name="location"><span data-ttu-id="2e484-106">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="2e484-106">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="2e484-107">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="2e484-107">Resource tags.</span></span></param>
        <param name="eTag"><span data-ttu-id="2e484-108">省略可能な ETag です。</span><span class="sxs-lookup"><span data-stu-id="2e484-108">Optional ETag.</span></span></param>
        <param name="properties"><span data-ttu-id="2e484-109">ILRRequestResource プロパティ</span><span class="sxs-lookup"><span data-stu-id="2e484-109">ILRRequestResource properties</span></span></param>
        <summary>
            <span data-ttu-id="2e484-110">ILRRequestResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2e484-110">Initializes a new instance of the ILRRequestResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequest Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequest Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As ILRRequest" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequest with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequestResource.Properties" />
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
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ILRRequest</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2e484-111">取得または設定 iLRRequestResource プロパティ</span><span class="sxs-lookup"><span data-stu-id="2e484-111">Gets or sets iLRRequestResource properties</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>