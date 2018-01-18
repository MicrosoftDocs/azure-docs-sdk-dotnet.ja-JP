<Type Name="ImageOSDisk" FullName="Microsoft.Azure.Management.Compute.Models.ImageOSDisk">
  <TypeSignature Language="C#" Value="public class ImageOSDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ImageOSDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ImageOSDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class ImageOSDisk" />
  <TypeSignature Language="F#" Value="type ImageOSDisk = class" />
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
            <span data-ttu-id="ea5ae-101">オペレーティング システム ディスクをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-101">Describes an Operating System disk.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageOSDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.#ctor" />
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
            <span data-ttu-id="ea5ae-102">ImageOSDisk クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-102">Initializes a new instance of the ImageOSDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ImageOSDisk (Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes osType, Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes osState, Microsoft.Azure.Management.Compute.Models.SubResource snapshot = null, Microsoft.Azure.Management.Compute.Models.SubResource managedDisk = null, string blobUri = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching = null, Nullable&lt;int&gt; diskSizeGB = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; storageAccountType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes osType, valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes osState, class Microsoft.Azure.Management.Compute.Models.SubResource snapshot, class Microsoft.Azure.Management.Compute.Models.SubResource managedDisk, string blobUri, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching, valuetype System.Nullable`1&lt;int32&gt; diskSizeGB, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.#ctor(Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes,Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes,Microsoft.Azure.Management.Compute.Models.SubResource,Microsoft.Azure.Management.Compute.Models.SubResource,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Models.CachingTypes},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.Compute.Models.StorageAccountTypes})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (osType As OperatingSystemTypes, osState As OperatingSystemStateTypes, Optional snapshot As SubResource = null, Optional managedDisk As SubResource = null, Optional blobUri As String = null, Optional caching As Nullable(Of CachingTypes) = null, Optional diskSizeGB As Nullable(Of Integer) = null, Optional storageAccountType As Nullable(Of StorageAccountTypes) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ImageOSDisk : Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes * Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes * Microsoft.Azure.Management.Compute.Models.SubResource * Microsoft.Azure.Management.Compute.Models.SubResource * string * Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; -&gt; Microsoft.Azure.Management.Compute.Models.ImageOSDisk" Usage="new Microsoft.Azure.Management.Compute.Models.ImageOSDisk (osType, osState, snapshot, managedDisk, blobUri, caching, diskSizeGB, storageAccountType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="osType" Type="Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
        <Parameter Name="managedDisk" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
        <Parameter Name="blobUri" Type="System.String" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt;" />
        <Parameter Name="diskSizeGB" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="storageAccountType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt;" />
      </Parameters>
      <Docs>
        <param name="osType"><span data-ttu-id="ea5ae-103">このプロパティでは、カスタム イメージから VM を作成する場合に、ディスクに含まれている OS の種類を指定することができます。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-103">This property allows you to specify the type of the OS that is included in the disk if creating a VM from a custom image.</span></span> <span data-ttu-id="ea5ae-104">&lt;ブラジル&gt;&lt;br&gt;値を指定できます: &lt;br&gt;&lt;br&gt; **Windows** &lt;br&gt; &lt;br&gt; **Linux**です。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-104">&lt;br&gt;&lt;br&gt; Possible values are: &lt;br&gt;&lt;br&gt; **Windows** &lt;br&gt;&lt;br&gt; **Linux**.</span></span>
            <span data-ttu-id="ea5ae-105">使用可能な値が含まれます 'Windows'、'Linux'。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-105">Possible values include: 'Windows', 'Linux'</span></span></param>
        <param name="osState"><span data-ttu-id="ea5ae-106">OS の状態。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-106">The OS State.</span></span> <span data-ttu-id="ea5ae-107">使用可能な値が含まれます: '汎用'、'特殊化'</span><span class="sxs-lookup"><span data-stu-id="ea5ae-107">Possible values include: 'Generalized', 'Specialized'</span></span></param>
        <param name="snapshot"><span data-ttu-id="ea5ae-108">スナップショット。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-108">The snapshot.</span></span></param>
        <param name="managedDisk"><span data-ttu-id="ea5ae-109">ManagedDisk です。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-109">The managedDisk.</span></span></param>
        <param name="blobUri"><span data-ttu-id="ea5ae-110">バーチャル ハード_ディスク。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-110">The Virtual Hard Disk.</span></span></param>
        <param name="caching"><span data-ttu-id="ea5ae-111">キャッシュの要件を指定します。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-111">Specifies the caching requirements.</span></span>
            <span data-ttu-id="ea5ae-112">&lt;ブラジル&gt;&lt;br&gt;指定できる値は: &lt;br&gt;&lt;br&gt; **None** &lt;br&gt; &lt;ブラジル&gt; **ReadOnly** &lt;br&gt;&lt;br&gt; **ReadWrite** &lt;br&gt; &lt;br&gt;既定:**標準的な記憶域については None です。Premium storage の ReadOnly**です。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-112">&lt;br&gt;&lt;br&gt; Possible values are: &lt;br&gt;&lt;br&gt; **None** &lt;br&gt;&lt;br&gt; **ReadOnly** &lt;br&gt;&lt;br&gt; **ReadWrite** &lt;br&gt;&lt;br&gt; Default: **None for Standard storage. ReadOnly for Premium storage**.</span></span> <span data-ttu-id="ea5ae-113">使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-113">Possible values include: 'None', 'ReadOnly', 'ReadWrite'</span></span></param>
        <param name="diskSizeGB"><span data-ttu-id="ea5ae-114">空のデータ ディスクのサイズをギガバイト単位で指定します。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-114">Specifies the size of empty data disks in gigabytes.</span></span> <span data-ttu-id="ea5ae-115">この要素は、仮想マシンのイメージのディスクの名前の上書きを使用できます。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-115">This element can be used to overwrite the name of the disk in a virtual machine image.</span></span> <span data-ttu-id="ea5ae-116">&lt;ブラジル&gt;&lt;br&gt;この値は、1,023 GB より大きくすることはできません</span><span class="sxs-lookup"><span data-stu-id="ea5ae-116">&lt;br&gt;&lt;br&gt; This value cannot be larger than 1023 GB</span></span></param>
        <param name="storageAccountType"><span data-ttu-id="ea5ae-117">管理対象ディスクのストレージ アカウントの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-117">Specifies the storage account type for the managed disk.</span></span> <span data-ttu-id="ea5ae-118">指定できる値は: Standard_LRS またはが premium_lrs の場合。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-118">Possible values are: Standard_LRS or Premium_LRS.</span></span> <span data-ttu-id="ea5ae-119">使用可能な値が含まれます: 'Standard_LRS'、'Premium_LRS'</span><span class="sxs-lookup"><span data-stu-id="ea5ae-119">Possible values include: 'Standard_LRS', 'Premium_LRS'</span></span></param>
        <summary>
            <span data-ttu-id="ea5ae-120">ImageOSDisk クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-120">Initializes a new instance of the ImageOSDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobUri">
      <MemberSignature Language="C#" Value="public string BlobUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.BlobUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobUri As String" />
      <MemberSignature Language="F#" Value="member this.BlobUri : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageOSDisk.BlobUri" />
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
            <span data-ttu-id="ea5ae-121">取得またはバーチャル ハード_ディスクを設定します。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-121">Gets or sets the Virtual Hard Disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingTypes)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageOSDisk.Caching" />
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
            <span data-ttu-id="ea5ae-122">取得または設定は、キャッシュの要件を指定します。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-122">Gets or sets specifies the caching requirements.</span></span>
            <span data-ttu-id="ea5ae-123">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;指定できる値は: &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**None** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**ReadOnly** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**ReadWrite** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;既定値:**標準的な記憶域については None です。Premium storage の ReadOnly**です。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-123">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Possible values are: &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **None** &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **ReadOnly** &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **ReadWrite** &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Default: **None for Standard storage. ReadOnly for Premium storage**.</span></span> <span data-ttu-id="ea5ae-124">使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-124">Possible values include: 'None', 'ReadOnly', 'ReadWrite'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskSizeGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiskSizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiskSizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.DiskSizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskSizeGB As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiskSizeGB : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageOSDisk.DiskSizeGB" />
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
            <span data-ttu-id="ea5ae-125">取得または設定は、空のデータ ディスクのサイズをギガバイト単位で指定します。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-125">Gets or sets specifies the size of empty data disks in gigabytes.</span></span>
            <span data-ttu-id="ea5ae-126">この要素は、仮想マシンのイメージのディスクの名前の上書きを使用できます。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-126">This element can be used to overwrite the name of the disk in a virtual machine image.</span></span> <span data-ttu-id="ea5ae-127">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;この値は、1,023 GB より大きくすることはできません。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-127">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; This value cannot be larger than 1023 GB</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource ManagedDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource ManagedDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.ManagedDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedDisk As SubResource" />
      <MemberSignature Language="F#" Value="member this.ManagedDisk : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageOSDisk.ManagedDisk" />
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
            <span data-ttu-id="ea5ae-128">取得または、managedDisk を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-128">Gets or sets the managedDisk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes OsState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes OsState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.OsState" />
      <MemberSignature Language="VB.NET" Value="Public Property OsState As OperatingSystemStateTypes" />
      <MemberSignature Language="F#" Value="member this.OsState : Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageOSDisk.OsState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperatingSystemStateTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea5ae-129">取得または OS の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-129">Gets or sets the OS State.</span></span> <span data-ttu-id="ea5ae-130">使用可能な値が含まれます: '汎用'、'特殊化'</span><span class="sxs-lookup"><span data-stu-id="ea5ae-130">Possible values include: 'Generalized', 'Specialized'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="member this.OsType : Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageOSDisk.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea5ae-131">取得または設定は、このプロパティを使用すると、カスタム イメージから VM を作成する場合に、ディスクに含まれている OS の種類を指定できます。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-131">Gets or sets this property allows you to specify the type of the OS that is included in the disk if creating a VM from a custom image.</span></span>
            <span data-ttu-id="ea5ae-132">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;指定できる値は: &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**Windows** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**Linux**です。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-132">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Possible values are: &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Windows** &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Linux**.</span></span> <span data-ttu-id="ea5ae-133">使用可能な値が含まれます 'Windows'、'Linux'。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-133">Possible values include: 'Windows', 'Linux'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource Snapshot { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource Snapshot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.Snapshot" />
      <MemberSignature Language="VB.NET" Value="Public Property Snapshot As SubResource" />
      <MemberSignature Language="F#" Value="member this.Snapshot : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageOSDisk.Snapshot" />
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
            <span data-ttu-id="ea5ae-134">取得またはスナップショットを設定します。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-134">Gets or sets the snapshot.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; StorageAccountType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; StorageAccountType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.StorageAccountType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountType As Nullable(Of StorageAccountTypes)" />
      <MemberSignature Language="F#" Value="member this.StorageAccountType : Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ImageOSDisk.StorageAccountType" />
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
            <span data-ttu-id="ea5ae-135">取得または設定は、管理対象ディスクのストレージ アカウントの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-135">Gets or sets specifies the storage account type for the managed disk.</span></span> <span data-ttu-id="ea5ae-136">指定できる値は: Standard_LRS またはが premium_lrs の場合。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-136">Possible values are: Standard_LRS or Premium_LRS.</span></span> <span data-ttu-id="ea5ae-137">使用可能な値が含まれます: 'Standard_LRS'、'Premium_LRS'</span><span class="sxs-lookup"><span data-stu-id="ea5ae-137">Possible values include: 'Standard_LRS', 'Premium_LRS'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ImageOSDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="imageOSDisk.Validate " />
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
            <span data-ttu-id="ea5ae-138">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-138">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ea5ae-139">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ea5ae-139">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>