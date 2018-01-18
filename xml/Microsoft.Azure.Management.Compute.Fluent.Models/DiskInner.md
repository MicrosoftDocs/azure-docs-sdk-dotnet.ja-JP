<Type Name="DiskInner" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner">
  <TypeSignature Language="C#" Value="public class DiskInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DiskInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner" />
  <TypeSignature Language="VB.NET" Value="Public Class DiskInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DiskInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e8f1b-101">ディスク リソースです。</span><span class="sxs-lookup"><span data-stu-id="e8f1b-101">Disk resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiskInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e8f1b-102">DiskInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e8f1b-102">Initializes a new instance of the DiskInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiskInner (Microsoft.Azure.Management.Compute.Fluent.Models.CreationData creationData, string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string managedBy = null, Microsoft.Azure.Management.Compute.Fluent.Models.DiskSku sku = null, System.Collections.Generic.IList&lt;string&gt; zones = null, Nullable&lt;DateTime&gt; timeCreated = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; osType = null, Nullable&lt;int&gt; diskSizeGB = null, Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings encryptionSettings = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Fluent.Models.CreationData creationData, string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string managedBy, class Microsoft.Azure.Management.Compute.Fluent.Models.DiskSku sku, class System.Collections.Generic.IList`1&lt;string&gt; zones, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timeCreated, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; osType, valuetype System.Nullable`1&lt;int32&gt; diskSizeGB, class Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings encryptionSettings, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.CreationData,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.Compute.Fluent.Models.DiskSku,System.Collections.Generic.IList{System.String},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes},System.Nullable{System.Int32},Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner : Microsoft.Azure.Management.Compute.Fluent.Models.CreationData * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.Compute.Fluent.Models.DiskSku * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner (creationData, location, id, name, type, tags, managedBy, sku, zones, timeCreated, osType, diskSizeGB, encryptionSettings, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="creationData" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CreationData" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="managedBy" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskSku" />
        <Parameter Name="zones" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="timeCreated" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="osType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt;" />
        <Parameter Name="diskSizeGB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="encryptionSettings" Type="Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="creationData">To be added.</param>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="managedBy">To be added.</param>
        <param name="sku">To be added.</param>
        <param name="zones">To be added.</param>
        <param name="timeCreated">To be added.</param>
        <param name="osType">To be added.</param>
        <param name="diskSizeGB">To be added.</param>
        <param name="encryptionSettings">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationData">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.CreationData CreationData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.CreationData CreationData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.CreationData" />
      <MemberSignature Language="VB.NET" Value="Public Property CreationData As CreationData" />
      <MemberSignature Language="F#" Value="member this.CreationData : Microsoft.Azure.Management.Compute.Fluent.Models.CreationData with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.CreationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.CreationData</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8f1b-103">取得またはソースのディスク情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="e8f1b-103">Gets or sets disk source information.</span></span> <span data-ttu-id="e8f1b-104">ディスクが作成された後、CreationData 情報を変更できません。</span><span class="sxs-lookup"><span data-stu-id="e8f1b-104">CreationData information cannot be changed after the disk has been created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.diskSizeGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8f1b-105">取得または設定 creationData.createOption が空では、このフィールドは必須および作成する VHD のサイズを示す場合。</span><span class="sxs-lookup"><span data-stu-id="e8f1b-105">Gets or sets if creationData.createOption is Empty, this field is mandatory and it indicates the size of the VHD to create.</span></span> <span data-ttu-id="e8f1b-106">このフィールドが更新プログラムやその他のオプションを使用した作成用に存在する場合は、サイズ変更を示します。</span><span class="sxs-lookup"><span data-stu-id="e8f1b-106">If this field is present for updates or creation with other options, it indicates a resize.</span></span> <span data-ttu-id="e8f1b-107">サイズ変更はディスクが実行中の VM にアタッチされていないと、ディスクのサイズを増やすことができますのみ場合のみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="e8f1b-107">Resizes are only allowed if the disk is not attached to a running VM, and can only increase the disk's size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings EncryptionSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings EncryptionSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.EncryptionSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionSettings As EncryptionSettings" />
      <MemberSignature Language="F#" Value="member this.EncryptionSettings : Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.EncryptionSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8f1b-108">取得または設定のディスクまたはスナップショットの暗号化の設定</span><span class="sxs-lookup"><span data-stu-id="e8f1b-108">Gets or sets encryption settings for disk or snapshot</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedBy">
      <MemberSignature Language="C#" Value="public string ManagedBy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ManagedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.ManagedBy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ManagedBy As String" />
      <MemberSignature Language="F#" Value="member this.ManagedBy : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.ManagedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="managedBy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As Nullable(Of OperatingSystemTypes)" />
      <MemberSignature Language="F#" Value="member this.OsType : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8f1b-109">取得またはオペレーティング システムの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="e8f1b-109">Gets or sets the Operating System type.</span></span> <span data-ttu-id="e8f1b-110">使用可能な値が含まれます 'Windows'、'Linux'。</span><span class="sxs-lookup"><span data-stu-id="e8f1b-110">Possible values include: 'Windows', 'Linux'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8f1b-111">プロビジョニングの状態、ディスクを取得します。</span><span class="sxs-lookup"><span data-stu-id="e8f1b-111">Gets the disk provisioning state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiskSku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.DiskSku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As DiskSku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Fluent.Models.DiskSku with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.DiskSku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeCreated">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; TimeCreated { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; TimeCreated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.TimeCreated" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeCreated As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.TimeCreated : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.TimeCreated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeCreated")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e8f1b-112">ディスクの作成日時を取得します。</span><span class="sxs-lookup"><span data-stu-id="e8f1b-112">Gets the time when the disk was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="diskInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e8f1b-113">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="e8f1b-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e8f1b-114">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e8f1b-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Zones">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Zones { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Zones" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.Zones" />
      <MemberSignature Language="VB.NET" Value="Public Property Zones As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Zones : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DiskInner.Zones" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="zones")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>