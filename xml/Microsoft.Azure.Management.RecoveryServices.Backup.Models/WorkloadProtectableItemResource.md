<Type Name="WorkloadProtectableItemResource" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource">
  <TypeSignature Language="C#" Value="public class WorkloadProtectableItemResource : Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WorkloadProtectableItemResource extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource" />
  <TypeSignature Language="VB.NET" Value="Public Class WorkloadProtectableItemResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type WorkloadProtectableItemResource = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="5383a-101">バックアップ項目の基本クラス。</span><span class="sxs-lookup"><span data-stu-id="5383a-101">Base class for backup item.</span></span> <span data-ttu-id="5383a-102">ワークロードに固有のバックアップ アイテムは、このクラスから派生します。</span><span class="sxs-lookup"><span data-stu-id="5383a-102">Workload-specific backup items are derived from this class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WorkloadProtectableItemResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5383a-103">WorkloadProtectableItemResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5383a-103">Initializes a new instance of the WorkloadProtectableItemResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WorkloadProtectableItemResource (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string eTag = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string eTag, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional eTag As String = null, Optional properties As WorkloadProtectableItem = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource (id, name, type, location, tags, eTag, properties)" />
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
        <Parameter Name="properties" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="5383a-104">リソース Id は、リソースへの完全なパスを表します。</span><span class="sxs-lookup"><span data-stu-id="5383a-104">Resource Id represents the complete path to the resource.</span></span></param>
        <param name="name"><span data-ttu-id="5383a-105">リソースに関連付けられているリソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5383a-105">Resource name associated with the resource.</span></span></param>
        <param name="type"><span data-ttu-id="5383a-106">リソースの種類は Namespace/ResourceType/ResourceType/... 形式の完全なパスを表します</span><span class="sxs-lookup"><span data-stu-id="5383a-106">Resource type represents the complete path of the form Namespace/ResourceType/ResourceType/...</span></span></param>
        <param name="location"><span data-ttu-id="5383a-107">リソースの場所。</span><span class="sxs-lookup"><span data-stu-id="5383a-107">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="5383a-108">リソース タグ。</span><span class="sxs-lookup"><span data-stu-id="5383a-108">Resource tags.</span></span></param>
        <param name="eTag"><span data-ttu-id="5383a-109">省略可能な ETag です。</span><span class="sxs-lookup"><span data-stu-id="5383a-109">Optional ETag.</span></span></param>
        <param name="properties"><span data-ttu-id="5383a-110">WorkloadProtectableItemResource プロパティ</span><span class="sxs-lookup"><span data-stu-id="5383a-110">WorkloadProtectableItemResource properties</span></span></param>
        <summary>
            <span data-ttu-id="5383a-111">WorkloadProtectableItemResource クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5383a-111">Initializes a new instance of the WorkloadProtectableItemResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As WorkloadProtectableItem" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItemResource.Properties" />
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
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5383a-112">取得または設定 workloadProtectableItemResource プロパティ</span><span class="sxs-lookup"><span data-stu-id="5383a-112">Gets or sets workloadProtectableItemResource properties</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>