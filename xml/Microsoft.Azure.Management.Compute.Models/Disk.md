<Type Name="Disk" FullName="Microsoft.Azure.Management.Compute.Models.Disk">
  <TypeSignature Language="C#" Value="public class Disk : Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Disk extends Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.Disk" />
  <TypeSignature Language="VB.NET" Value="Public Class Disk&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Disk = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9e973-101">ディスク リソースです。</span><span class="sxs-lookup"><span data-stu-id="9e973-101">Disk resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Disk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Disk.#ctor" />
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
            <span data-ttu-id="9e973-102">ディスク クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9e973-102">Initializes a new instance of the Disk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Disk (string location, Microsoft.Azure.Management.Compute.Models.CreationData creationData, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string managedBy = null, Microsoft.Azure.Management.Compute.Models.DiskSku sku = null, System.Collections.Generic.IList&lt;string&gt; zones = null, Nullable&lt;DateTime&gt; timeCreated = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; osType = null, Nullable&lt;int&gt; diskSizeGB = null, Microsoft.Azure.Management.Compute.Models.EncryptionSettings encryptionSettings = null, string provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class Microsoft.Azure.Management.Compute.Models.CreationData creationData, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string managedBy, class Microsoft.Azure.Management.Compute.Models.DiskSku sku, class System.Collections.Generic.IList`1&lt;string&gt; zones, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timeCreated, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; osType, valuetype System.Nullable`1&lt;int32&gt; diskSizeGB, class Microsoft.Azure.Management.Compute.Models.EncryptionSettings encryptionSettings, string provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Disk.#ctor(System.String,Microsoft.Azure.Management.Compute.Models.CreationData,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.Compute.Models.DiskSku,System.Collections.Generic.IList{System.String},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes},System.Nullable{System.Int32},Microsoft.Azure.Management.Compute.Models.EncryptionSettings,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.Disk : string * Microsoft.Azure.Management.Compute.Models.CreationData * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.Compute.Models.DiskSku * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Compute.Models.EncryptionSettings * string -&gt; Microsoft.Azure.Management.Compute.Models.Disk" Usage="new Microsoft.Azure.Management.Compute.Models.Disk (location, creationData, id, name, type, tags, managedBy, sku, zones, timeCreated, osType, diskSizeGB, encryptionSettings, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="creationData" Type="Microsoft.Azure.Management.Compute.Models.CreationData" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="managedBy" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Compute.Models.DiskSku" />
        <Parameter Name="zones" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="timeCreated" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="osType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt;" />
        <Parameter Name="diskSizeGB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="encryptionSettings" Type="Microsoft.Azure.Management.Compute.Models.EncryptionSettings" />
        <Parameter Name="provisioningState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="9e973-103">リソースの場所</span><span class="sxs-lookup"><span data-stu-id="9e973-103">Resource location</span></span></param>
        <param name="creationData"><span data-ttu-id="9e973-104">ディスクのソース情報です。</span><span class="sxs-lookup"><span data-stu-id="9e973-104">Disk source information.</span></span> <span data-ttu-id="9e973-105">ディスクが作成された後、CreationData 情報を変更できません。</span><span class="sxs-lookup"><span data-stu-id="9e973-105">CreationData information cannot be changed after the disk has been created.</span></span></param>
        <param name="id"><span data-ttu-id="9e973-106">リソース Id</span><span class="sxs-lookup"><span data-stu-id="9e973-106">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="9e973-107">リソース名</span><span class="sxs-lookup"><span data-stu-id="9e973-107">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="9e973-108">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="9e973-108">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="9e973-109">リソース タグ</span><span class="sxs-lookup"><span data-stu-id="9e973-109">Resource tags</span></span></param>
        <param name="managedBy"><span data-ttu-id="9e973-110">ディスクが接続されている VM の ID を含む相対 URI。</span><span class="sxs-lookup"><span data-stu-id="9e973-110">A relative URI containing the ID of the VM that has the disk attached.</span></span></param>
        <param name="sku">To be added.</param>
        <param name="zones"><span data-ttu-id="9e973-111">ディスクの論理ゾーンの一覧です。</span><span class="sxs-lookup"><span data-stu-id="9e973-111">The Logical zone list for Disk.</span></span></param>
        <param name="timeCreated"><span data-ttu-id="9e973-112">ディスクが作成された時刻。</span><span class="sxs-lookup"><span data-stu-id="9e973-112">The time when the disk was created.</span></span></param>
        <param name="osType"><span data-ttu-id="9e973-113">オペレーティング システムの種類。</span><span class="sxs-lookup"><span data-stu-id="9e973-113">The Operating System type.</span></span> <span data-ttu-id="9e973-114">使用可能な値が含まれます 'Windows'、'Linux'。</span><span class="sxs-lookup"><span data-stu-id="9e973-114">Possible values include: 'Windows', 'Linux'</span></span></param>
        <param name="diskSizeGB"><span data-ttu-id="9e973-115">CreationData.createOption が空の場合は、このフィールドは必須およびを作成する VHD のサイズを示します。</span><span class="sxs-lookup"><span data-stu-id="9e973-115">If creationData.createOption is Empty, this field is mandatory and it indicates the size of the VHD to create.</span></span> <span data-ttu-id="9e973-116">このフィールドが更新プログラムやその他のオプションを使用した作成用に存在する場合は、サイズ変更を示します。</span><span class="sxs-lookup"><span data-stu-id="9e973-116">If this field is present for updates or creation with other options, it indicates a resize.</span></span> <span data-ttu-id="9e973-117">サイズ変更はディスクが実行中の VM にアタッチされていないと、ディスクのサイズを増やすことができますのみ場合のみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="9e973-117">Resizes are only allowed if the disk is not attached to a running VM, and can only increase the disk's size.</span></span></param>
        <param name="encryptionSettings"><span data-ttu-id="9e973-118">ディスクまたはスナップショットの暗号化の設定</span><span class="sxs-lookup"><span data-stu-id="9e973-118">Encryption settings for disk or snapshot</span></span></param>
        <param name="provisioningState"><span data-ttu-id="9e973-119">プロビジョニングの状態のディスク。</span><span class="sxs-lookup"><span data-stu-id="9e973-119">The disk provisioning state.</span></span></param>
        <summary>
            <span data-ttu-id="9e973-120">ディスク クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9e973-120">Initializes a new instance of the Disk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationData">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.CreationData CreationData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.CreationData CreationData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Disk.CreationData" />
      <MemberSignature Language="VB.NET" Value="Public Property CreationData As CreationData" />
      <MemberSignature Language="F#" Value="member this.CreationData : Microsoft.Azure.Management.Compute.Models.CreationData with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Disk.CreationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.CreationData</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e973-121">取得またはソースのディスク情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="9e973-121">Gets or sets disk source information.</span></span> <span data-ttu-id="9e973-122">ディスクが作成された後、CreationData 情報を変更できません。</span><span class="sxs-lookup"><span data-stu-id="9e973-122">CreationData information cannot be changed after the disk has been created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Disk.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Disk.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="9e973-123">取得または設定 creationData.createOption が空では、このフィールドは必須および作成する VHD のサイズを示す場合。</span><span class="sxs-lookup"><span data-stu-id="9e973-123">Gets or sets if creationData.createOption is Empty, this field is mandatory and it indicates the size of the VHD to create.</span></span> <span data-ttu-id="9e973-124">このフィールドが更新プログラムやその他のオプションを使用した作成用に存在する場合は、サイズ変更を示します。</span><span class="sxs-lookup"><span data-stu-id="9e973-124">If this field is present for updates or creation with other options, it indicates a resize.</span></span> <span data-ttu-id="9e973-125">サイズ変更はディスクが実行中の VM にアタッチされていないと、ディスクのサイズを増やすことができますのみ場合のみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="9e973-125">Resizes are only allowed if the disk is not attached to a running VM, and can only increase the disk's size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.EncryptionSettings EncryptionSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.EncryptionSettings EncryptionSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Disk.EncryptionSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionSettings As EncryptionSettings" />
      <MemberSignature Language="F#" Value="member this.EncryptionSettings : Microsoft.Azure.Management.Compute.Models.EncryptionSettings with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Disk.EncryptionSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.EncryptionSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e973-126">取得または設定のディスクまたはスナップショットの暗号化の設定</span><span class="sxs-lookup"><span data-stu-id="9e973-126">Gets or sets encryption settings for disk or snapshot</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedBy">
      <MemberSignature Language="C#" Value="public string ManagedBy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ManagedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Disk.ManagedBy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ManagedBy As String" />
      <MemberSignature Language="F#" Value="member this.ManagedBy : string" Usage="Microsoft.Azure.Management.Compute.Models.Disk.ManagedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
        <summary>
            <span data-ttu-id="9e973-127">ディスクが接続されている VM の ID を含む相対 URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="9e973-127">Gets a relative URI containing the ID of the VM that has the disk attached.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Disk.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As Nullable(Of OperatingSystemTypes)" />
      <MemberSignature Language="F#" Value="member this.OsType : Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Disk.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e973-128">取得またはオペレーティング システムの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="9e973-128">Gets or sets the Operating System type.</span></span> <span data-ttu-id="9e973-129">使用可能な値が含まれます 'Windows'、'Linux'。</span><span class="sxs-lookup"><span data-stu-id="9e973-129">Possible values include: 'Windows', 'Linux'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Disk.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Compute.Models.Disk.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="9e973-130">プロビジョニングの状態、ディスクを取得します。</span><span class="sxs-lookup"><span data-stu-id="9e973-130">Gets the disk provisioning state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.DiskSku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.DiskSku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Disk.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As DiskSku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Models.DiskSku with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Disk.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.DiskSku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeCreated">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; TimeCreated { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; TimeCreated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Disk.TimeCreated" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeCreated As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.TimeCreated : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Compute.Models.Disk.TimeCreated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="9e973-131">ディスクの作成日時を取得します。</span><span class="sxs-lookup"><span data-stu-id="9e973-131">Gets the time when the disk was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.Disk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="disk.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9e973-132">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="9e973-132">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9e973-133">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9e973-133">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Zones">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Zones { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Zones" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.Disk.Zones" />
      <MemberSignature Language="VB.NET" Value="Public Property Zones As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Zones : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.Disk.Zones" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
        <summary>
            <span data-ttu-id="9e973-134">取得またはディスクの論理ゾーンの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="9e973-134">Gets or sets the Logical zone list for Disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>