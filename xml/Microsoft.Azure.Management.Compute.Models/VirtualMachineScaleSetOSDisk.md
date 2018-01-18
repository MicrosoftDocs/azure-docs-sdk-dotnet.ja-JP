<Type Name="VirtualMachineScaleSetOSDisk" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetOSDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetOSDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetOSDisk" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetOSDisk = class" />
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
            <span data-ttu-id="ce121-101">仮想マシン スケール セットのオペレーティング システム ディスクをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="ce121-101">Describes a virtual machine scale set operating system disk.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetOSDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.#ctor" />
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
            <span data-ttu-id="ce121-102">VirtualMachineScaleSetOSDisk クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ce121-102">Initializes a new instance of the VirtualMachineScaleSetOSDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetOSDisk (Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes createOption, string name = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching = null, Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; osType = null, Microsoft.Azure.Management.Compute.Models.VirtualHardDisk image = null, System.Collections.Generic.IList&lt;string&gt; vhdContainers = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters managedDisk = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes createOption, string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; caching, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; osType, class Microsoft.Azure.Management.Compute.Models.VirtualHardDisk image, class System.Collections.Generic.IList`1&lt;string&gt; vhdContainers, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters managedDisk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.#ctor(Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Models.CachingTypes},System.Nullable{Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes},Microsoft.Azure.Management.Compute.Models.VirtualHardDisk,System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createOption As DiskCreateOptionTypes, Optional name As String = null, Optional caching As Nullable(Of CachingTypes) = null, Optional osType As Nullable(Of OperatingSystemTypes) = null, Optional image As VirtualHardDisk = null, Optional vhdContainers As IList(Of String) = null, Optional managedDisk As VirtualMachineScaleSetManagedDiskParameters = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk : Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes * string * Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; * Microsoft.Azure.Management.Compute.Models.VirtualHardDisk * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk (createOption, name, caching, osType, image, vhdContainers, managedDisk)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createOption" Type="Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt;" />
        <Parameter Name="osType" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt;" />
        <Parameter Name="image" Type="Microsoft.Azure.Management.Compute.Models.VirtualHardDisk" />
        <Parameter Name="vhdContainers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="managedDisk" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters" />
      </Parameters>
      <Docs>
        <param name="createOption"><span data-ttu-id="ce121-103">スケール セット内の仮想マシンを作成する方法を指定します。&lt;br&gt;&lt;br&gt;は許可されている値だけ: **FromImage** \u2013 仮想マシンを作成するイメージを使用しているときに、この値を使用します。</span><span class="sxs-lookup"><span data-stu-id="ce121-103">Specifies how the virtual machines in the scale set should be created.&lt;br&gt;&lt;br&gt; The only allowed value is: **FromImage** \u2013 This value is used when you are using an image to create the virtual machine.</span></span> <span data-ttu-id="ce121-104">プラットフォーム イメージを使用している場合は、上記で説明した imageReference 要素を使用します。</span><span class="sxs-lookup"><span data-stu-id="ce121-104">If you are using a platform image, you also use the imageReference element described above.</span></span> <span data-ttu-id="ce121-105">Marketplace イメージを使用している場合は、前に説明した計画の要素を使用します。</span><span class="sxs-lookup"><span data-stu-id="ce121-105">If you are using a marketplace image, you  also use the plan element previously described.</span></span> <span data-ttu-id="ce121-106">使用可能な値が含まれます: 'FromImage'、'Empty'、'接続'</span><span class="sxs-lookup"><span data-stu-id="ce121-106">Possible values include: 'FromImage', 'Empty', 'Attach'</span></span></param>
        <param name="name"><span data-ttu-id="ce121-107">ディスクの名前。</span><span class="sxs-lookup"><span data-stu-id="ce121-107">The disk name.</span></span></param>
        <param name="caching"><span data-ttu-id="ce121-108">キャッシュの要件を指定します。</span><span class="sxs-lookup"><span data-stu-id="ce121-108">Specifies the caching requirements.</span></span>
            <span data-ttu-id="ce121-109">&lt;ブラジル&gt;&lt;br&gt;指定できる値は: &lt;br&gt;&lt;br&gt; **None** &lt;br&gt; &lt;ブラジル&gt; **ReadOnly** &lt;br&gt;&lt;br&gt; **ReadWrite** &lt;br&gt; &lt;br&gt;既定:**標準的な記憶域については None です。Premium storage の ReadOnly**です。</span><span class="sxs-lookup"><span data-stu-id="ce121-109">&lt;br&gt;&lt;br&gt; Possible values are: &lt;br&gt;&lt;br&gt; **None** &lt;br&gt;&lt;br&gt; **ReadOnly** &lt;br&gt;&lt;br&gt; **ReadWrite** &lt;br&gt;&lt;br&gt; Default: **None for Standard storage. ReadOnly for Premium storage**.</span></span> <span data-ttu-id="ce121-110">使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。</span><span class="sxs-lookup"><span data-stu-id="ce121-110">Possible values include: 'None', 'ReadOnly', 'ReadWrite'</span></span></param>
        <param name="osType"><span data-ttu-id="ce121-111">このプロパティでは、ユーザー イメージまたは特殊な VHD から VM を作成する場合に、ディスクに含まれている OS の種類を指定することができます。</span><span class="sxs-lookup"><span data-stu-id="ce121-111">This property allows you to specify the type of the OS that is included in the disk if creating a VM from user-image or a specialized VHD.</span></span> <span data-ttu-id="ce121-112">&lt;ブラジル&gt;&lt;br&gt;値を指定できます: &lt;br&gt;&lt;br&gt; **Windows** &lt;br&gt; &lt;br&gt; **Linux**です。</span><span class="sxs-lookup"><span data-stu-id="ce121-112">&lt;br&gt;&lt;br&gt; Possible values are: &lt;br&gt;&lt;br&gt; **Windows** &lt;br&gt;&lt;br&gt; **Linux**.</span></span> <span data-ttu-id="ce121-113">使用可能な値が含まれます 'Windows'、'Linux'。</span><span class="sxs-lookup"><span data-stu-id="ce121-113">Possible values include: 'Windows', 'Linux'</span></span></param>
        <param name="image"><span data-ttu-id="ce121-114">スケールのセットを基に、アンマネージ ユーザー イメージに関する情報を指定します。</span><span class="sxs-lookup"><span data-stu-id="ce121-114">Specifies information about the unmanaged user image to base the scale set on.</span></span></param>
        <param name="vhdContainers"><span data-ttu-id="ce121-115">スケール セットのオペレーティング システム ディスクを保存するために使用するコンテナーの url を指定します。</span><span class="sxs-lookup"><span data-stu-id="ce121-115">Specifies the container urls that are used to store operating system disks for the scale set.</span></span></param>
        <param name="managedDisk"><span data-ttu-id="ce121-116">管理対象ディスクのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ce121-116">The managed disk parameters.</span></span></param>
        <summary>
            <span data-ttu-id="ce121-117">VirtualMachineScaleSetOSDisk クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ce121-117">Initializes a new instance of the VirtualMachineScaleSetOSDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingTypes)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Compute.Models.CachingTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.Caching" />
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
            <span data-ttu-id="ce121-118">取得または設定は、キャッシュの要件を指定します。</span><span class="sxs-lookup"><span data-stu-id="ce121-118">Gets or sets specifies the caching requirements.</span></span>
            <span data-ttu-id="ce121-119">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;指定できる値は: &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**None** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**ReadOnly** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**ReadWrite** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;既定値:**標準的な記憶域については None です。Premium storage の ReadOnly**です。</span><span class="sxs-lookup"><span data-stu-id="ce121-119">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Possible values are: &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **None** &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **ReadOnly** &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **ReadWrite** &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Default: **None for Standard storage. ReadOnly for Premium storage**.</span></span> <span data-ttu-id="ce121-120">使用可能な値が含まれます 'None'、'ReadOnly'、'ReadWrite'。</span><span class="sxs-lookup"><span data-stu-id="ce121-120">Possible values include: 'None', 'ReadOnly', 'ReadWrite'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes CreateOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes CreateOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.CreateOption" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateOption As DiskCreateOptionTypes" />
      <MemberSignature Language="F#" Value="member this.CreateOption : Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.CreateOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.DiskCreateOptionTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce121-121">取得または設定は、スケール セット内の仮想マシンを作成する方法を指定します。&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;許可されている値だけ: **FromImage** \u2013 仮想マシンを作成するイメージを使用しているときに、この値を使用します。</span><span class="sxs-lookup"><span data-stu-id="ce121-121">Gets or sets specifies how the virtual machines in the scale set should be created.&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; The only allowed value is: **FromImage** \u2013 This value is used when you are using an image to create the virtual machine.</span></span> <span data-ttu-id="ce121-122">プラットフォーム イメージを使用している場合は、上記で説明した imageReference 要素を使用します。</span><span class="sxs-lookup"><span data-stu-id="ce121-122">If you are using a platform image, you also use the imageReference element described above.</span></span> <span data-ttu-id="ce121-123">Marketplace イメージを使用している場合は、前に説明した計画の要素を使用します。</span><span class="sxs-lookup"><span data-stu-id="ce121-123">If you are using a marketplace image, you  also use the plan element previously described.</span></span> <span data-ttu-id="ce121-124">使用可能な値が含まれます: 'FromImage'、'Empty'、'接続'</span><span class="sxs-lookup"><span data-stu-id="ce121-124">Possible values include: 'FromImage', 'Empty', 'Attach'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Image">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualHardDisk Image { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualHardDisk Image" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.Image" />
      <MemberSignature Language="VB.NET" Value="Public Property Image As VirtualHardDisk" />
      <MemberSignature Language="F#" Value="member this.Image : Microsoft.Azure.Management.Compute.Models.VirtualHardDisk with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.Image" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="image")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualHardDisk</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce121-125">取得または設定は、スケールのセットを基に、アンマネージ ユーザー イメージに関する情報を指定します。</span><span class="sxs-lookup"><span data-stu-id="ce121-125">Gets or sets specifies information about the unmanaged user image to base the scale set on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters ManagedDisk { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters ManagedDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.ManagedDisk" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagedDisk As VirtualMachineScaleSetManagedDiskParameters" />
      <MemberSignature Language="F#" Value="member this.ManagedDisk : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.ManagedDisk" />
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
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetManagedDiskParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce121-126">取得または管理対象ディスク パラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="ce121-126">Gets or sets the managed disk parameters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce121-127">取得またはディスクの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="ce121-127">Gets or sets the disk name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As Nullable(Of OperatingSystemTypes)" />
      <MemberSignature Language="F#" Value="member this.OsType : Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.OsType" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.OperatingSystemTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce121-128">取得または設定は、このプロパティを使用すると、ユーザー イメージまたは特殊な VHD から VM を作成する場合に、ディスクに含まれている OS の種類を指定できます。</span><span class="sxs-lookup"><span data-stu-id="ce121-128">Gets or sets this property allows you to specify the type of the OS that is included in the disk if creating a VM from user-image or a specialized VHD.</span></span> <span data-ttu-id="ce121-129">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;指定できる値は: &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**Windows** &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;**Linux**です。</span><span class="sxs-lookup"><span data-stu-id="ce121-129">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Possible values are: &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Windows** &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; **Linux**.</span></span> <span data-ttu-id="ce121-130">使用可能な値が含まれます 'Windows'、'Linux'。</span><span class="sxs-lookup"><span data-stu-id="ce121-130">Possible values include: 'Windows', 'Linux'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetOSDisk.Validate " />
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
            <span data-ttu-id="ce121-131">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="ce121-131">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce121-132">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce121-132">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VhdContainers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; VhdContainers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; VhdContainers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.VhdContainers" />
      <MemberSignature Language="VB.NET" Value="Public Property VhdContainers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.VhdContainers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSDisk.VhdContainers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vhdContainers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce121-133">取得または設定は、スケール セットのオペレーティング システム ディスクを保存するために使用するコンテナーの url を指定します。</span><span class="sxs-lookup"><span data-stu-id="ce121-133">Gets or sets specifies the container urls that are used to store operating system disks for the scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>