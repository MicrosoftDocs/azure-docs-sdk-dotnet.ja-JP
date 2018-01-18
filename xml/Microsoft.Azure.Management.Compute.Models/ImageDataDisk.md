<Type Name="ImageDataDisk" FullName="Microsoft.Azure.Management.Compute.Models.ImageDataDisk">
  <TypeSignature Language="C#" Value="public class ImageDataDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageDataDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ImageDataDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageDataDisk" />
  <TypeSignature Language="F#" Value="type ImageDataDisk = class" />
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
            <span data-ttu-id="bb4a5-101">データ ディスクをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-101">Describes a data disk.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageDataDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.#ctor" />
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
            <span data-ttu-id="bb4a5-102">ImageDataDisk クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-102">Initializes a new instance of the ImageDataDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageDataDisk (int lun, Microsoft.Azure.Management.Compute.Models.SubResource snapshot = null, Microsoft.Azure.Management.Compute.Models.SubResource managedDisk = null, string blobUri = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching = null, Nullable&lt;int&gt; diskSizeGB = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; storageAccountType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 lun, class Microsoft.Azure.Management.Compute.Models.SubResource snapshot, class Microsoft.Azure.Management.Compute.Models.SubResource managedDisk, string blobUri, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching, valuetype System.Nullable`1&lt;int32&gt; diskSizeGB, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.#ctor(System.Int32,Microsoft.Azure.Management.Compute.Models.SubResource,Microsoft.Azure.Management.Compute.Models.SubResource,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Models.CachingTypes},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.Compute.Models.StorageAccountTypes})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (lun As Integer, Optional snapshot As SubResource = null, Optional managedDisk As SubResource = null, Optional blobUri As String = null, Optional caching As Nullable(Of CachingTypes) = null, Optional diskSizeGB As Nullable(Of Integer) = null, Optional storageAccountType As Nullable(Of StorageAccountTypes) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ImageDataDisk : int * Microsoft.Azure.Management.Compute.Models.SubResource * Microsoft.Azure.Management.Compute.Models.SubResource * string * Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; -&gt; Microsoft.Azure.Management.Compute.Models.ImageDataDisk" Usage="new Microsoft.Azure.Management.Compute.Models.ImageDataDisk (lun, snapshot, managedDisk, blobUri, caching, diskSizeGB, storageAccountType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lun" Type="System.Int32" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
        <Parameter Name="managedDisk" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
        <Parameter Name="blobUri" Type="System.String" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt;" />
        <Parameter Name="diskSizeGB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="storageAccountType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt;" />
      </Parameters>
      <Docs>
        <param name="lun"><span data-ttu-id="bb4a5-103">データ ディスクの論理ユニットの数を指定します。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-103">Specifies the logical unit number of the data disk.</span></span> <span data-ttu-id="bb4a5-104">この値は、VM 内でのデータ ディスクを識別するために使用され、VM にアタッチされている各データ ディスクの一意なしたがってする必要があります。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-104">This value is used to identify data disks within the VM and therefore must be unique for each data disk attached to a VM.</span></span></param>
        <param name="snapshot"><span data-ttu-id="bb4a5-105">スナップショット。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-105">The snapshot.</span></span></param>
        <param name="managedDisk"><span data-ttu-id="bb4a5-106">ManagedDisk です。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-106">The managedDisk.</span></span></param>
        <param name="blobUri"><span data-ttu-id="bb4a5-107">バーチャル ハード_ディスク。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-107">The Virtual Hard Disk.</span></span></param>
        <param name="caching"><span data-ttu-id="bb4a5-108">キャッシュの要件を指定します。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-108">Specifies the caching requirements.</span></span>
            <span data-ttu-id="bb4a5-109">&lt;ブラジル&gt;&lt;br&gt;指定できる値は: &lt;br&gt;&lt;br&gt; **None** &lt;br&gt; &lt;ブラジル&gt; **ReadOnly** &lt;br&gt;&lt;br&gt; **ReadWrite** &lt;br&gt; &lt;br&gt;既定:**標準的な記憶域については None です。Premium storage の ReadOnly**です。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-109">&lt;br&gt;&lt;br&gt; Possible values are: &lt;br&gt;&lt;br&gt; **None** &lt;br&gt;&lt;br&gt; **ReadOnly** &lt;br&gt;&lt;br&gt; **ReadWrite** &lt;br&gt;&lt;br&gt; Default: **None for Standard storage. ReadOnly for Premium storage**.</span></span> <span data-ttu-id="bb4a5-110">使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-110">Possible values include: 'None', 'ReadOnly', 'ReadWrite'</span></span></param>
        <param name="diskSizeGB"><span data-ttu-id="bb4a5-111">空のデータ ディスクのサイズをギガバイト単位で指定します。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-111">Specifies the size of empty data disks in gigabytes.</span></span> <span data-ttu-id="bb4a5-112">この要素は、仮想マシンのイメージのディスクの名前の上書きを使用できます。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-112">This element can be used to overwrite the name of the disk in a virtual machine image.</span></span> <span data-ttu-id="bb4a5-113">&lt;ブラジル&gt;&lt;br&gt;この値は、1,023 GB より大きくすることはできません</span><span class="sxs-lookup"><span data-stu-id="bb4a5-113">&lt;br&gt;&lt;br&gt; This value cannot be larger than 1023 GB</span></span></param>
        <param name="storageAccountType"><span data-ttu-id="bb4a5-114">管理対象ディスクのストレージ アカウントの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-114">Specifies the storage account type for the managed disk.</span></span> <span data-ttu-id="bb4a5-115">指定できる値は: Standard_LRS またはが premium_lrs の場合。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-115">Possible values are: Standard_LRS or Premium_LRS.</span></span> <span data-ttu-id="bb4a5-116">使用可能な値が含まれます: 'Standard_LRS'、'Premium_LRS'</span><span class="sxs-lookup"><span data-stu-id="bb4a5-116">Possible values include: 'Standard_LRS', 'Premium_LRS'</span></span></param>
        <summary>
            <span data-ttu-id="bb4a5-117">ImageDataDisk クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-117">Initializes a new instance of the ImageDataDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobUri">
      <MemberSignature Language="C#" Value="public string BlobUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.BlobUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobUri As String" />
      <MemberSignature Language="F#" Value="member this.BlobUri : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageDataDisk.BlobUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb4a5-118">取得またはバーチャル ハード_ディスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-118">Gets or sets the Virtual Hard Disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingTypes)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageDataDisk.Caching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="caching")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb4a5-119">取得または設定は、キャッシュの要件を指定します。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-119">Gets or sets specifies the caching requirements.</span></span>
            <span data-ttu-id="bb4a5-120">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;指定できる値は: &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**None** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**ReadOnly** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**ReadWrite** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;既定値:**標準的な記憶域については None です。Premium storage の ReadOnly**です。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-120">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Possible values are: &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **None** &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **ReadOnly** &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **ReadWrite** &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Default: **None for Standard storage. ReadOnly for Premium storage**.</span></span> <span data-ttu-id="bb4a5-121">使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-121">Possible values include: 'None', 'ReadOnly', 'ReadWrite'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageDataDisk.DiskSizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskSizeGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb4a5-122">取得または設定は、空のデータ ディスクのサイズをギガバイト単位で指定します。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-122">Gets or sets specifies the size of empty data disks in gigabytes.</span></span>
            <span data-ttu-id="bb4a5-123">この要素は、仮想マシンのイメージのディスクの名前の上書きを使用できます。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-123">This element can be used to overwrite the name of the disk in a virtual machine image.</span></span> <span data-ttu-id="bb4a5-124">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;この値は、1,023 GB より大きくすることはできません。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-124">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; This value cannot be larger than 1023 GB</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lun">
      <MemberSignature Language="C#" Value="public int Lun { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Lun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.Lun" />
      <MemberSignature Language="VB.NET" Value="Public Property Lun As Integer" />
      <MemberSignature Language="F#" Value="member this.Lun : int with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageDataDisk.Lun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb4a5-125">取得または設定は、データ ディスクの論理ユニットの数を指定します。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-125">Gets or sets specifies the logical unit number of the data disk.</span></span>
            <span data-ttu-id="bb4a5-126">この値は、VM 内でのデータ ディスクを識別するために使用され、VM にアタッチされている各データ ディスクの一意なしたがってする必要があります。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-126">This value is used to identify data disks within the VM and therefore must be unique for each data disk attached to a VM.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource ManagedDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource ManagedDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.ManagedDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedDisk As SubResource" />
      <MemberSignature Language="F#" Value="member this.ManagedDisk : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageDataDisk.ManagedDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="managedDisk")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb4a5-127">取得または、managedDisk を設定します。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-127">Gets or sets the managedDisk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource Snapshot { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource Snapshot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.Snapshot" />
      <MemberSignature Language="VB.NET" Value="Public Property Snapshot As SubResource" />
      <MemberSignature Language="F#" Value="member this.Snapshot : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageDataDisk.Snapshot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="snapshot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb4a5-128">取得またはスナップショットを設定します。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-128">Gets or sets the snapshot.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; StorageAccountType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountType As Nullable(Of StorageAccountTypes)" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageDataDisk.StorageAccountType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bb4a5-129">取得または設定は、管理対象ディスクのストレージ アカウントの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-129">Gets or sets specifies the storage account type for the managed disk.</span></span> <span data-ttu-id="bb4a5-130">指定できる値は: Standard_LRS またはが premium_lrs の場合。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-130">Possible values are: Standard_LRS or Premium_LRS.</span></span> <span data-ttu-id="bb4a5-131">使用可能な値が含まれます: 'Standard_LRS'、'Premium_LRS'</span><span class="sxs-lookup"><span data-stu-id="bb4a5-131">Possible values include: 'Standard_LRS', 'Premium_LRS'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageDataDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="imageDataDisk.Validate " />
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
            <span data-ttu-id="bb4a5-132">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-132">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bb4a5-133">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bb4a5-133">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>