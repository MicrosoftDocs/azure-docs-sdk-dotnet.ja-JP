<Type Name="VirtualMachine" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachine">
  <TypeSignature Language="C#" Value="public class VirtualMachine : Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachine extends Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachine" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachine&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualMachine = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="f4304-101">仮想マシンについて説明します。</span><span class="sxs-lookup"><span data-stu-id="f4304-101">Describes a Virtual Machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachine ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachine.#ctor" />
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
            <span data-ttu-id="f4304-102">VirtualMachine クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f4304-102">Initializes a new instance of the VirtualMachine class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachine (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Compute.Models.Plan plan = null, Microsoft.Azure.Management.Compute.Models.HardwareProfile hardwareProfile = null, Microsoft.Azure.Management.Compute.Models.StorageProfile storageProfile = null, Microsoft.Azure.Management.Compute.Models.OSProfile osProfile = null, Microsoft.Azure.Management.Compute.Models.NetworkProfile networkProfile = null, Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile diagnosticsProfile = null, Microsoft.Azure.Management.Compute.Models.SubResource availabilitySet = null, string provisioningState = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView instanceView = null, string licenseType = null, string vmId = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; resources = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity identity = null, System.Collections.Generic.IList&lt;string&gt; zones = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Compute.Models.Plan plan, class Microsoft.Azure.Management.Compute.Models.HardwareProfile hardwareProfile, class Microsoft.Azure.Management.Compute.Models.StorageProfile storageProfile, class Microsoft.Azure.Management.Compute.Models.OSProfile osProfile, class Microsoft.Azure.Management.Compute.Models.NetworkProfile networkProfile, class Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile diagnosticsProfile, class Microsoft.Azure.Management.Compute.Models.SubResource availabilitySet, string provisioningState, class Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView instanceView, string licenseType, string vmId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; resources, class Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity identity, class System.Collections.Generic.IList`1&lt;string&gt; zones) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachine.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Compute.Models.Plan,Microsoft.Azure.Management.Compute.Models.HardwareProfile,Microsoft.Azure.Management.Compute.Models.StorageProfile,Microsoft.Azure.Management.Compute.Models.OSProfile,Microsoft.Azure.Management.Compute.Models.NetworkProfile,Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile,Microsoft.Azure.Management.Compute.Models.SubResource,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension},Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachine : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Compute.Models.Plan * Microsoft.Azure.Management.Compute.Models.HardwareProfile * Microsoft.Azure.Management.Compute.Models.StorageProfile * Microsoft.Azure.Management.Compute.Models.OSProfile * Microsoft.Azure.Management.Compute.Models.NetworkProfile * Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile * Microsoft.Azure.Management.Compute.Models.SubResource * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; * Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachine" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachine (location, id, name, type, tags, plan, hardwareProfile, storageProfile, osProfile, networkProfile, diagnosticsProfile, availabilitySet, provisioningState, instanceView, licenseType, vmId, resources, identity, zones)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="plan" Type="Microsoft.Azure.Management.Compute.Models.Plan" />
        <Parameter Name="hardwareProfile" Type="Microsoft.Azure.Management.Compute.Models.HardwareProfile" />
        <Parameter Name="storageProfile" Type="Microsoft.Azure.Management.Compute.Models.StorageProfile" />
        <Parameter Name="osProfile" Type="Microsoft.Azure.Management.Compute.Models.OSProfile" />
        <Parameter Name="networkProfile" Type="Microsoft.Azure.Management.Compute.Models.NetworkProfile" />
        <Parameter Name="diagnosticsProfile" Type="Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile" />
        <Parameter Name="availabilitySet" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="instanceView" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView" />
        <Parameter Name="licenseType" Type="System.String" />
        <Parameter Name="vmId" Type="System.String" />
        <Parameter Name="resources" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity" />
        <Parameter Name="zones" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="f4304-103">リソースの場所</span><span class="sxs-lookup"><span data-stu-id="f4304-103">Resource location</span></span></param>
        <param name="id"><span data-ttu-id="f4304-104">リソース Id</span><span class="sxs-lookup"><span data-stu-id="f4304-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="f4304-105">リソース名</span><span class="sxs-lookup"><span data-stu-id="f4304-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="f4304-106">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="f4304-106">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="f4304-107">リソース タグ</span><span class="sxs-lookup"><span data-stu-id="f4304-107">Resource tags</span></span></param>
        <param name="plan"><span data-ttu-id="f4304-108">仮想マシンの作成に使用する marketplace イメージに関する情報を指定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-108">Specifies information about the marketplace image used to create the virtual machine.</span></span> <span data-ttu-id="f4304-109">この要素は marketplace イメージのみ使用されます。</span><span class="sxs-lookup"><span data-stu-id="f4304-109">This element is only used for marketplace images.</span></span> <span data-ttu-id="f4304-110">API から marketplace イメージを使用することができます、前に、画像がプログラムでの使用を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f4304-110">Before you can use a marketplace image from an API, you must enable the image for programmatic use.</span></span>  <span data-ttu-id="f4304-111">Azure ポータルで、検索、marketplace イメージを使用して、をクリックする**はじめに - をプログラムでは、展開する&gt;**です。</span><span class="sxs-lookup"><span data-stu-id="f4304-111">In the Azure portal, find the marketplace image that you want to use and then click **Want to deploy programmatically, Get Started -&gt;**.</span></span>
            <span data-ttu-id="f4304-112">必要な情報を入力し、クリックして**保存**です。</span><span class="sxs-lookup"><span data-stu-id="f4304-112">Enter any required information and then click **Save**.</span></span></param>
        <param name="hardwareProfile"><span data-ttu-id="f4304-113">仮想マシンのハードウェアの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-113">Specifies the hardware settings for the virtual machine.</span></span></param>
        <param name="storageProfile"><span data-ttu-id="f4304-114">仮想マシンのディスクの記憶域の設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-114">Specifies the storage settings for the virtual machine disks.</span></span></param>
        <param name="osProfile"><span data-ttu-id="f4304-115">バーチャル マシンのオペレーティング システムの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-115">Specifies the operating system settings for the virtual machine.</span></span></param>
        <param name="networkProfile"><span data-ttu-id="f4304-116">仮想マシンのネットワーク インターフェイスを指定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-116">Specifies the network interfaces of the virtual machine.</span></span></param>
        <param name="diagnosticsProfile"><span data-ttu-id="f4304-117">ブート診断設定の状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-117">Specifies the boot diagnostic settings state.</span></span> <span data-ttu-id="f4304-118">&lt;ブラジル&gt;&lt;br&gt;最小 api バージョン: 2015-06-15 です。</span><span class="sxs-lookup"><span data-stu-id="f4304-118">&lt;br&gt;&lt;br&gt;Minimum api-version: 2015-06-15.</span></span></param>
        <param name="availabilitySet"><span data-ttu-id="f4304-119">仮想マシンに割り当てられる可用性セットに関する情報を指定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-119">Specifies information about the availability set that the virtual machine should be assigned to.</span></span>
            <span data-ttu-id="f4304-120">同じ可用性セットで指定された仮想マシンは、可用性が最大限に別のノードに割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="f4304-120">Virtual machines specified in the same availability set are allocated to different nodes to maximize availability.</span></span> <span data-ttu-id="f4304-121">可用性セットの詳細については、次を参照してください。[仮想マシンの可用性管理](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-manage-availability?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json)です。</span><span class="sxs-lookup"><span data-stu-id="f4304-121">For more information about availability sets, see [Manage the availability of virtual machines](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-manage-availability?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span></span>
            <span data-ttu-id="f4304-122">&lt;ブラジル&gt;&lt;br&gt; Azure の計画されたメンテナンスの詳細については、次を参照してください[Azure の仮想マシンの定期保守](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-planned-maintenance?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;ブラジル。&gt;現時点では、VM のみに追加できます可用性セットの作成時にします。</span><span class="sxs-lookup"><span data-stu-id="f4304-122">&lt;br&gt;&lt;br&gt; For more information on Azure planned maintainance, see [Planned maintenance for virtual machines in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-planned-maintenance?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;br&gt; Currently, a VM can only be added to availability set at creation time.</span></span> <span data-ttu-id="f4304-123">既存の仮想マシンは、可用性セットに追加できません。</span><span class="sxs-lookup"><span data-stu-id="f4304-123">An existing VM cannot be added to an availability set.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="f4304-124">プロビジョニングの状態、応答でのみ表示されます。</span><span class="sxs-lookup"><span data-stu-id="f4304-124">The provisioning state, which only appears in the response.</span></span></param>
        <param name="instanceView"><span data-ttu-id="f4304-125">仮想マシン インスタンス ビューです。</span><span class="sxs-lookup"><span data-stu-id="f4304-125">The virtual machine instance view.</span></span></param>
        <param name="licenseType"><span data-ttu-id="f4304-126">イメージまたは使用されているディスクがライセンス済み、内部設置型を指定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-126">Specifies that the image or disk that is being used was licensed on-premises.</span></span> <span data-ttu-id="f4304-127">この要素は、Windows Server オペレーティング システムを含むイメージでのみ使用します。</span><span class="sxs-lookup"><span data-stu-id="f4304-127">This element is only used for images that contain the Windows Server operating system.</span></span>
            <span data-ttu-id="f4304-128">&lt;ブラジル&gt;&lt;br&gt;指定できる値は: &lt;br&gt;&lt;br&gt; Windows_Client &lt;br&gt;&lt;br&gt;Windows_Server &lt;br&gt;&lt;br&gt;この要素が更新プログラムの要求に含まれている場合、値が初期値に一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f4304-128">&lt;br&gt;&lt;br&gt; Possible values are: &lt;br&gt;&lt;br&gt; Windows_Client &lt;br&gt;&lt;br&gt; Windows_Server &lt;br&gt;&lt;br&gt; If this element is included in a request for an update, the value must match the initial value.</span></span> <span data-ttu-id="f4304-129">この値を更新することはできません。</span><span class="sxs-lookup"><span data-stu-id="f4304-129">This value cannot be updated.</span></span> <span data-ttu-id="f4304-130">&lt;ブラジル&gt;&lt;br&gt;詳細については、次を参照してください[ハイブリッドを使用して特典 Windows Server 用 Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;br&gt;最小値。api バージョン: 2015-06-15</span><span class="sxs-lookup"><span data-stu-id="f4304-130">&lt;br&gt;&lt;br&gt; For more information, see [Azure Hybrid Use Benefit for Windows Server](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;br&gt; Minimum api-version: 2015-06-15</span></span></param>
        <param name="vmId"><span data-ttu-id="f4304-131">エンコードされ、すべての Azure IaaS Vm SMBIOS で格納される 128 ビット識別子である VM の一意な ID を指定およびできます使用されている読み取りプラットフォーム BIOS コマンド。</span><span class="sxs-lookup"><span data-stu-id="f4304-131">Specifies the VM unique ID which is a 128-bits identifier that is encoded and stored in all Azure IaaS VMs SMBIOS and can be read using platform BIOS commands.</span></span></param>
        <param name="resources"><span data-ttu-id="f4304-132">仮想マシンの子の拡張機能リソース。</span><span class="sxs-lookup"><span data-stu-id="f4304-132">The virtual machine child extension resources.</span></span></param>
        <param name="identity"><span data-ttu-id="f4304-133">構成されている場合、仮想マシンの id。</span><span class="sxs-lookup"><span data-stu-id="f4304-133">The identity of the virtual machine, if configured.</span></span></param>
        <param name="zones"><span data-ttu-id="f4304-134">仮想マシンのゾーンです。</span><span class="sxs-lookup"><span data-stu-id="f4304-134">The virtual machine zones.</span></span></param>
        <summary>
            <span data-ttu-id="f4304-135">VirtualMachine クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f4304-135">Initializes a new instance of the VirtualMachine class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilitySet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource AvailabilitySet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource AvailabilitySet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.AvailabilitySet" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailabilitySet As SubResource" />
      <MemberSignature Language="F#" Value="member this.AvailabilitySet : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.AvailabilitySet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availabilitySet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4304-136">取得または設定は、仮想マシンに割り当てられる可用性セットに関する情報を指定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-136">Gets or sets specifies information about the availability set that the virtual machine should be assigned to.</span></span> <span data-ttu-id="f4304-137">同じ可用性セットで指定された仮想マシンは、可用性が最大限に別のノードに割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="f4304-137">Virtual machines specified in the same availability set are allocated to different nodes to maximize availability.</span></span> <span data-ttu-id="f4304-138">可用性セットの詳細については、次を参照してください。[仮想マシンの可用性管理](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-manage-availability?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json)です。</span><span class="sxs-lookup"><span data-stu-id="f4304-138">For more information about availability sets, see [Manage the availability of virtual machines](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-manage-availability?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span></span>
            <span data-ttu-id="f4304-139">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Azure の計画されたメンテナンスの詳細については、次を参照してください[Azure の仮想マシンの定期保守](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-planned-maintenance?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt; br&amp;gt;&amp; 。lt; br&amp;gt;現時点では、VM は可用性セットの作成時にのみ追加できます。</span><span class="sxs-lookup"><span data-stu-id="f4304-139">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For more information on Azure planned maintainance, see [Planned maintenance for virtual machines in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-planned-maintenance?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Currently, a VM can only be added to availability set at creation time.</span></span> <span data-ttu-id="f4304-140">既存の仮想マシンは、可用性セットに追加できません。</span><span class="sxs-lookup"><span data-stu-id="f4304-140">An existing VM cannot be added to an availability set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile DiagnosticsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile DiagnosticsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.DiagnosticsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property DiagnosticsProfile As DiagnosticsProfile" />
      <MemberSignature Language="F#" Value="member this.DiagnosticsProfile : Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.DiagnosticsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.diagnosticsProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4304-141">取得または設定は、ブート診断設定の状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-141">Gets or sets specifies the boot diagnostic settings state.</span></span>
            <span data-ttu-id="f4304-142">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;最小 api バージョン: 2015-06-15 です。</span><span class="sxs-lookup"><span data-stu-id="f4304-142">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt;Minimum api-version: 2015-06-15.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HardwareProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.HardwareProfile HardwareProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.HardwareProfile HardwareProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.HardwareProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property HardwareProfile As HardwareProfile" />
      <MemberSignature Language="F#" Value="member this.HardwareProfile : Microsoft.Azure.Management.Compute.Models.HardwareProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.HardwareProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hardwareProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.HardwareProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4304-143">取得または設定は、仮想マシンのハードウェアの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-143">Gets or sets specifies the hardware settings for the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As VirtualMachineIdentity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4304-144">取得または構成されている場合に、仮想マシンの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-144">Gets or sets the identity of the virtual machine, if configured.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceView">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView InstanceView { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView InstanceView" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.InstanceView" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceView As VirtualMachineInstanceView" />
      <MemberSignature Language="F#" Value="member this.InstanceView : Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.InstanceView" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.instanceView")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4304-145">仮想マシン インスタンス ビューを取得します。</span><span class="sxs-lookup"><span data-stu-id="f4304-145">Gets the virtual machine instance view.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.licenseType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4304-146">取得または設定は、イメージまたは使用されているディスクがライセンス済み、内部設置型を指定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-146">Gets or sets specifies that the image or disk that is being used was licensed on-premises.</span></span> <span data-ttu-id="f4304-147">この要素は、Windows Server オペレーティング システムを含むイメージでのみ使用します。</span><span class="sxs-lookup"><span data-stu-id="f4304-147">This element is only used for images that contain the Windows Server operating system.</span></span>
            <span data-ttu-id="f4304-148">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;指定できる値は: &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Windows_Client &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Windows_Server &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;この要素が更新プログラムの要求に含まれている場合、値は、初期値と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f4304-148">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Possible values are: &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Windows_Client &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Windows_Server &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; If this element is included in a request for an update, the value must match the initial value.</span></span>
            <span data-ttu-id="f4304-149">この値を更新することはできません。</span><span class="sxs-lookup"><span data-stu-id="f4304-149">This value cannot be updated.</span></span> <span data-ttu-id="f4304-150">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;詳細については、次を参照してください[ハイブリッドを使用して特典 Windows Server 用 Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt; br&amp;gt;&amp; 。lt; br&amp;gt;最小 api バージョン: 2015-06-15</span><span class="sxs-lookup"><span data-stu-id="f4304-150">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For more information, see [Azure Hybrid Use Benefit for Windows Server](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Minimum api-version: 2015-06-15</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.NetworkProfile NetworkProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.NetworkProfile NetworkProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.NetworkProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkProfile As NetworkProfile" />
      <MemberSignature Language="F#" Value="member this.NetworkProfile : Microsoft.Azure.Management.Compute.Models.NetworkProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.NetworkProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.NetworkProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4304-151">取得または設定は、仮想マシンのネットワーク インターフェイスを指定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-151">Gets or sets specifies the network interfaces of the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.OSProfile OsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.OSProfile OsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.OsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property OsProfile As OSProfile" />
      <MemberSignature Language="F#" Value="member this.OsProfile : Microsoft.Azure.Management.Compute.Models.OSProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.OsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.osProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OSProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4304-152">取得または設定は、バーチャル マシンのオペレーティング システムの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-152">Gets or sets specifies the operating system settings for the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Plan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.Plan Plan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.Plan Plan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.Plan" />
      <MemberSignature Language="VB.NET" Value="Public Property Plan As Plan" />
      <MemberSignature Language="F#" Value="member this.Plan : Microsoft.Azure.Management.Compute.Models.Plan with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.Plan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="plan")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Plan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4304-153">取得または設定は、仮想マシンの作成に使用する marketplace イメージに関する情報を指定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-153">Gets or sets specifies information about the marketplace image used to create the virtual machine.</span></span> <span data-ttu-id="f4304-154">この要素は marketplace イメージのみ使用されます。</span><span class="sxs-lookup"><span data-stu-id="f4304-154">This element is only used for marketplace images.</span></span> <span data-ttu-id="f4304-155">API から marketplace イメージを使用することができます、前に、画像がプログラムでの使用を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f4304-155">Before you can use a marketplace image from an API, you must enable the image for programmatic use.</span></span>  <span data-ttu-id="f4304-156">Azure ポータルで、検索、marketplace イメージを使用して、をクリックする**はじめに - をプログラムでは、展開する&amp;gt;**です。</span><span class="sxs-lookup"><span data-stu-id="f4304-156">In the Azure portal, find the marketplace image that you want to use and then click **Want to deploy programmatically, Get Started -&amp;gt;**.</span></span>
            <span data-ttu-id="f4304-157">必要な情報を入力し、クリックして**保存**です。</span><span class="sxs-lookup"><span data-stu-id="f4304-157">Enter any required information and then click **Save**.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.ProvisioningState" />
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
            <span data-ttu-id="f4304-158">応答でのみ表示されます、プロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4304-158">Gets the provisioning state, which only appears in the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; Resources { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.Resources" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resources As IList(Of VirtualMachineExtension)" />
      <MemberSignature Language="F#" Value="member this.Resources : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.Resources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resources")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4304-159">拡張機能リソースの仮想マシンの子を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4304-159">Gets the virtual machine child extension resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.StorageProfile StorageProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.StorageProfile StorageProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.StorageProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageProfile As StorageProfile" />
      <MemberSignature Language="F#" Value="member this.StorageProfile : Microsoft.Azure.Management.Compute.Models.StorageProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.StorageProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.StorageProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4304-160">取得または設定は、仮想マシンのディスクの記憶域の設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-160">Gets or sets specifies the storage settings for the virtual machine disks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachine.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="virtualMachine.Validate " />
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
            <span data-ttu-id="f4304-161">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f4304-161">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f4304-162">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f4304-162">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmId">
      <MemberSignature Language="C#" Value="public string VmId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.VmId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VmId As String" />
      <MemberSignature Language="F#" Value="member this.VmId : string" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.VmId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f4304-163">取得エンコードされ、すべての Azure IaaS Vm SMBIOS で格納される 128 ビット識別子である VM の一意 ID を指定して読み取りを使用してインストール プラットフォーム BIOS コマンド。</span><span class="sxs-lookup"><span data-stu-id="f4304-163">Gets specifies the VM unique ID which is a 128-bits identifier that is encoded and stored in all Azure IaaS VMs SMBIOS and can be read using platform BIOS commands.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Zones">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Zones { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Zones" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachine.Zones" />
      <MemberSignature Language="VB.NET" Value="Public Property Zones As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Zones : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachine.Zones" />
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
            <span data-ttu-id="f4304-164">取得または仮想マシンのゾーンを設定します。</span><span class="sxs-lookup"><span data-stu-id="f4304-164">Gets or sets the virtual machine zones.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>