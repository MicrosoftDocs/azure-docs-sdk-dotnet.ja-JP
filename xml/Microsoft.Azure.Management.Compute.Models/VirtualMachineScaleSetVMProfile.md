<Type Name="VirtualMachineScaleSetVMProfile" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetVMProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetVMProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetVMProfile" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetVMProfile = class" />
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
            <span data-ttu-id="0233f-101">仮想マシン スケール セットの仮想マシン プロファイルをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="0233f-101">Describes a virtual machine scale set virtual machine profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVMProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.#ctor" />
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
            <span data-ttu-id="0233f-102">VirtualMachineScaleSetVMProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0233f-102">Initializes a new instance of the VirtualMachineScaleSetVMProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVMProfile (Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile osProfile = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile storageProfile = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile networkProfile = null, Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile diagnosticsProfile = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile extensionProfile = null, string licenseType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile osProfile, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile storageProfile, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile networkProfile, class Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile diagnosticsProfile, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile extensionProfile, string licenseType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.#ctor(Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile,Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile * Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile (osProfile, storageProfile, networkProfile, diagnosticsProfile, extensionProfile, licenseType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="osProfile" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile" />
        <Parameter Name="storageProfile" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile" />
        <Parameter Name="networkProfile" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile" />
        <Parameter Name="diagnosticsProfile" Type="Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile" />
        <Parameter Name="extensionProfile" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile" />
        <Parameter Name="licenseType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="osProfile"><span data-ttu-id="0233f-103">スケール セット内の仮想マシンのオペレーティング システムの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="0233f-103">Specifies the operating system settings for the virtual machines in the scale set.</span></span></param>
        <param name="storageProfile"><span data-ttu-id="0233f-104">仮想マシンのディスクの記憶域の設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="0233f-104">Specifies the storage settings for the virtual machine disks.</span></span></param>
        <param name="networkProfile"><span data-ttu-id="0233f-105">スケール セット内の仮想マシンのネットワーク インターフェイスのプロパティを指定します。</span><span class="sxs-lookup"><span data-stu-id="0233f-105">Specifies properties of the network interfaces of the virtual machines in the scale set.</span></span></param>
        <param name="diagnosticsProfile"><span data-ttu-id="0233f-106">ブート診断設定の状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="0233f-106">Specifies the boot diagnostic settings state.</span></span> <span data-ttu-id="0233f-107">&lt;ブラジル&gt;&lt;br&gt;最小 api バージョン: 2015-06-15 です。</span><span class="sxs-lookup"><span data-stu-id="0233f-107">&lt;br&gt;&lt;br&gt;Minimum api-version: 2015-06-15.</span></span></param>
        <param name="extensionProfile"><span data-ttu-id="0233f-108">仮想マシン スケール セット内にインストールされている拡張機能の設定のコレクションを指定します。</span><span class="sxs-lookup"><span data-stu-id="0233f-108">Specifies a collection of settings for extensions installed on virtual machines in the scale set.</span></span></param>
        <param name="licenseType"><span data-ttu-id="0233f-109">イメージまたは使用されているディスクがライセンス済み、内部設置型を指定します。</span><span class="sxs-lookup"><span data-stu-id="0233f-109">Specifies that the image or disk that is being used was licensed on-premises.</span></span> <span data-ttu-id="0233f-110">この要素は、Windows Server オペレーティング システムを含むイメージでのみ使用します。</span><span class="sxs-lookup"><span data-stu-id="0233f-110">This element is only used for images that contain the Windows Server operating system.</span></span>
            <span data-ttu-id="0233f-111">&lt;ブラジル&gt;&lt;br&gt;指定できる値は: &lt;br&gt;&lt;br&gt; Windows_Client &lt;br&gt;&lt;br&gt;Windows_Server &lt;br&gt;&lt;br&gt;この要素が更新プログラムの要求に含まれている場合、値が初期値に一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0233f-111">&lt;br&gt;&lt;br&gt; Possible values are: &lt;br&gt;&lt;br&gt; Windows_Client &lt;br&gt;&lt;br&gt; Windows_Server &lt;br&gt;&lt;br&gt; If this element is included in a request for an update, the value must match the initial value.</span></span> <span data-ttu-id="0233f-112">この値を更新することはできません。</span><span class="sxs-lookup"><span data-stu-id="0233f-112">This value cannot be updated.</span></span> <span data-ttu-id="0233f-113">&lt;ブラジル&gt;&lt;br&gt;詳細については、次を参照してください[ハイブリッドを使用して特典 Windows Server 用 Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;br&gt;最小値。api バージョン: 2015-06-15</span><span class="sxs-lookup"><span data-stu-id="0233f-113">&lt;br&gt;&lt;br&gt; For more information, see [Azure Hybrid Use Benefit for Windows Server](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;br&gt; Minimum api-version: 2015-06-15</span></span></param>
        <summary>
            <span data-ttu-id="0233f-114">VirtualMachineScaleSetVMProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0233f-114">Initializes a new instance of the VirtualMachineScaleSetVMProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile DiagnosticsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile DiagnosticsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.DiagnosticsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property DiagnosticsProfile As DiagnosticsProfile" />
      <MemberSignature Language="F#" Value="member this.DiagnosticsProfile : Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.DiagnosticsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diagnosticsProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.DiagnosticsProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0233f-115">取得または設定は、ブート診断設定の状態を指定します。</span><span class="sxs-lookup"><span data-stu-id="0233f-115">Gets or sets specifies the boot diagnostic settings state.</span></span>
            <span data-ttu-id="0233f-116">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;最小 api バージョン: 2015-06-15 です。</span><span class="sxs-lookup"><span data-stu-id="0233f-116">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt;Minimum api-version: 2015-06-15.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtensionProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile ExtensionProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile ExtensionProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.ExtensionProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtensionProfile As VirtualMachineScaleSetExtensionProfile" />
      <MemberSignature Language="F#" Value="member this.ExtensionProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.ExtensionProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extensionProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtensionProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0233f-117">取得または設定は、仮想マシン スケール セット内にインストールされている拡張機能の設定のコレクションを指定します。</span><span class="sxs-lookup"><span data-stu-id="0233f-117">Gets or sets specifies a collection of settings for extensions installed on virtual machines in the scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="licenseType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0233f-118">取得または設定は、イメージまたは使用されているディスクがライセンス済み、内部設置型を指定します。</span><span class="sxs-lookup"><span data-stu-id="0233f-118">Gets or sets specifies that the image or disk that is being used was licensed on-premises.</span></span> <span data-ttu-id="0233f-119">この要素は、Windows Server オペレーティング システムを含むイメージでのみ使用します。</span><span class="sxs-lookup"><span data-stu-id="0233f-119">This element is only used for images that contain the Windows Server operating system.</span></span>
            <span data-ttu-id="0233f-120">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;指定できる値は: &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Windows_Client &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Windows_Server &amp;lt; br&amp;gt;&amp;lt; br&amp;gt;この要素が更新プログラムの要求に含まれている場合、値は、初期値と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0233f-120">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Possible values are: &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Windows_Client &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Windows_Server &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; If this element is included in a request for an update, the value must match the initial value.</span></span>
            <span data-ttu-id="0233f-121">この値を更新することはできません。</span><span class="sxs-lookup"><span data-stu-id="0233f-121">This value cannot be updated.</span></span> <span data-ttu-id="0233f-122">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;詳細については、次を参照してください[ハイブリッドを使用して特典 Windows Server 用 Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt; br&amp;gt;&amp; 。lt; br&amp;gt;最小 api バージョン: 2015-06-15</span><span class="sxs-lookup"><span data-stu-id="0233f-122">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For more information, see [Azure Hybrid Use Benefit for Windows Server](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-hybrid-use-benefit-licensing?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &amp;lt;br&amp;gt;&amp;lt;br&amp;gt; Minimum api-version: 2015-06-15</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile NetworkProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile NetworkProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.NetworkProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkProfile As VirtualMachineScaleSetNetworkProfile" />
      <MemberSignature Language="F#" Value="member this.NetworkProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.NetworkProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0233f-123">取得または設定は、スケール セット内の仮想マシンのネットワーク インターフェイスのプロパティを指定します。</span><span class="sxs-lookup"><span data-stu-id="0233f-123">Gets or sets specifies properties of the network interfaces of the virtual machines in the scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile OsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile OsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.OsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property OsProfile As VirtualMachineScaleSetOSProfile" />
      <MemberSignature Language="F#" Value="member this.OsProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.OsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetOSProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0233f-124">取得または設定は、スケール セット内の仮想マシンのオペレーティング システムの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="0233f-124">Gets or sets specifies the operating system settings for the virtual machines in the scale set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile StorageProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile StorageProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.StorageProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageProfile As VirtualMachineScaleSetStorageProfile" />
      <MemberSignature Language="F#" Value="member this.StorageProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.StorageProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetStorageProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0233f-125">取得または設定は、仮想マシンのディスクの記憶域の設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="0233f-125">Gets or sets specifies the storage settings for the virtual machine disks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetVMProfile.Validate " />
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
            <span data-ttu-id="0233f-126">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="0233f-126">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0233f-127">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0233f-127">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>