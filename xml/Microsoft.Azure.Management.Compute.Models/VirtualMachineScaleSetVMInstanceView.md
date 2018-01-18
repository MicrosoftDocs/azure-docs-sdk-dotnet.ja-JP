<Type Name="VirtualMachineScaleSetVMInstanceView" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetVMInstanceView" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetVMInstanceView extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetVMInstanceView" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetVMInstanceView = class" />
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
            <span data-ttu-id="27a87-101">仮想マシンのスケールのインスタンス ビューでは、VM を設定します。</span><span class="sxs-lookup"><span data-stu-id="27a87-101">The instance view of a virtual machine scale set VM.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVMInstanceView ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.#ctor" />
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
            <span data-ttu-id="27a87-102">VirtualMachineScaleSetVMInstanceView クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="27a87-102">Initializes a new instance of the VirtualMachineScaleSetVMInstanceView class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVMInstanceView (Nullable&lt;int&gt; platformUpdateDomain = null, Nullable&lt;int&gt; platformFaultDomain = null, string rdpThumbPrint = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView vmAgent = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskInstanceView&gt; disks = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView&gt; extensions = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus vmHealth = null, Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView bootDiagnostics = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; statuses = null, string placementGroupId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; platformUpdateDomain, valuetype System.Nullable`1&lt;int32&gt; platformFaultDomain, string rdpThumbPrint, class Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView vmAgent, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.DiskInstanceView&gt; disks, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView&gt; extensions, class Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus vmHealth, class Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView bootDiagnostics, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; statuses, string placementGroupId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.DiskInstanceView},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView},Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus,Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.InstanceViewStatus},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional platformUpdateDomain As Nullable(Of Integer) = null, Optional platformFaultDomain As Nullable(Of Integer) = null, Optional rdpThumbPrint As String = null, Optional vmAgent As VirtualMachineAgentInstanceView = null, Optional disks As IList(Of DiskInstanceView) = null, Optional extensions As IList(Of VirtualMachineExtensionInstanceView) = null, Optional vmHealth As VirtualMachineHealthStatus = null, Optional bootDiagnostics As BootDiagnosticsInstanceView = null, Optional statuses As IList(Of InstanceViewStatus) = null, Optional placementGroupId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView : Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskInstanceView&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView&gt; * Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus * Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView (platformUpdateDomain, platformFaultDomain, rdpThumbPrint, vmAgent, disks, extensions, vmHealth, bootDiagnostics, statuses, placementGroupId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="platformUpdateDomain" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="platformFaultDomain" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="rdpThumbPrint" Type="System.String" />
        <Parameter Name="vmAgent" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView" />
        <Parameter Name="disks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskInstanceView&gt;" />
        <Parameter Name="extensions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView&gt;" />
        <Parameter Name="vmHealth" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus" />
        <Parameter Name="bootDiagnostics" Type="Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView" />
        <Parameter Name="statuses" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt;" />
        <Parameter Name="placementGroupId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="platformUpdateDomain"><span data-ttu-id="27a87-103">更新ドメインの数。</span><span class="sxs-lookup"><span data-stu-id="27a87-103">The Update Domain count.</span></span></param>
        <param name="platformFaultDomain"><span data-ttu-id="27a87-104">フォールト ドメインの数。</span><span class="sxs-lookup"><span data-stu-id="27a87-104">The Fault Domain count.</span></span></param>
        <param name="rdpThumbPrint"><span data-ttu-id="27a87-105">リモート デスクトップ証明書の拇印。</span><span class="sxs-lookup"><span data-stu-id="27a87-105">The Remote desktop certificate thumbprint.</span></span></param>
        <param name="vmAgent"><span data-ttu-id="27a87-106">VM エージェントは、仮想マシンで実行します。</span><span class="sxs-lookup"><span data-stu-id="27a87-106">The VM Agent running on the virtual machine.</span></span></param>
        <param name="disks"><span data-ttu-id="27a87-107">ディスク情報です。</span><span class="sxs-lookup"><span data-stu-id="27a87-107">The disks information.</span></span></param>
        <param name="extensions"><span data-ttu-id="27a87-108">拡張機能の情報です。</span><span class="sxs-lookup"><span data-stu-id="27a87-108">The extensions information.</span></span></param>
        <param name="vmHealth"><span data-ttu-id="27a87-109">仮想マシンの正常性状態です。</span><span class="sxs-lookup"><span data-stu-id="27a87-109">The health status for the VM.</span></span></param>
        <param name="bootDiagnostics"><span data-ttu-id="27a87-110">ブート診断は、デバッグ機能を VM の状態を診断するには、コンソール出力とスクリーン ショットを表示することができます。</span><span class="sxs-lookup"><span data-stu-id="27a87-110">Boot Diagnostics is a debugging feature which allows you to view Console Output and Screenshot to diagnose VM status.</span></span> <span data-ttu-id="27a87-111">&lt;ブラジル&gt;&lt;br&gt; Linux 仮想マシンのコンソールのログの出力に簡単に表示できます。</span><span class="sxs-lookup"><span data-stu-id="27a87-111">&lt;br&gt;&lt;br&gt; For Linux Virtual Machines, you can easily view the output of your console log.</span></span>
            <span data-ttu-id="27a87-112">&lt;ブラジル&gt;&lt;br&gt; Windows と Linux の両方の仮想マシンの Azure することもできます、ハイパーバイザーから仮想マシンのスクリーン ショットを参照してください。</span><span class="sxs-lookup"><span data-stu-id="27a87-112">&lt;br&gt;&lt;br&gt; For both Windows and Linux virtual machines, Azure also enables you to see a screenshot of the VM from the hypervisor.</span></span></param>
        <param name="statuses"><span data-ttu-id="27a87-113">リソースの状態情報です。</span><span class="sxs-lookup"><span data-stu-id="27a87-113">The resource status information.</span></span></param>
        <param name="placementGroupId"><span data-ttu-id="27a87-114">VM が実行されている配置グループです。</span><span class="sxs-lookup"><span data-stu-id="27a87-114">The placement group in which the VM is running.</span></span> <span data-ttu-id="27a87-115">VM の割り当てが解除された場合、placementGroupId は与えられません。</span><span class="sxs-lookup"><span data-stu-id="27a87-115">If the VM is deallocated it will not have a placementGroupId.</span></span></param>
        <summary>
            <span data-ttu-id="27a87-116">VirtualMachineScaleSetVMInstanceView クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="27a87-116">Initializes a new instance of the VirtualMachineScaleSetVMInstanceView class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BootDiagnostics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView BootDiagnostics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView BootDiagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.BootDiagnostics" />
      <MemberSignature Language="VB.NET" Value="Public Property BootDiagnostics As BootDiagnosticsInstanceView" />
      <MemberSignature Language="F#" Value="member this.BootDiagnostics : Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.BootDiagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="bootDiagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.BootDiagnosticsInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27a87-117">取得またはブート診断は VM の状態を診断するには、コンソール出力とスクリーン ショットを表示することができますが、デバッグ機能を設定します。</span><span class="sxs-lookup"><span data-stu-id="27a87-117">Gets or sets boot Diagnostics is a debugging feature which allows you to view Console Output and Screenshot to diagnose VM status.</span></span>
            <span data-ttu-id="27a87-118">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Linux 仮想マシンのコンソールのログの出力に簡単に表示できます。</span><span class="sxs-lookup"><span data-stu-id="27a87-118">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For Linux Virtual Machines, you can easily view the output of your console log.</span></span>
            <span data-ttu-id="27a87-119">&amp;lt; br&amp;gt;&amp;lt; br&amp;gt;Windows と Linux の両方の仮想マシンの Azure することもできます、ハイパーバイザーから仮想マシンのスクリーン ショットを参照してください。</span><span class="sxs-lookup"><span data-stu-id="27a87-119">&amp;lt;br&amp;gt;&amp;lt;br&amp;gt; For both Windows and Linux virtual machines, Azure also enables you to see a screenshot of the VM from the hypervisor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Disks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskInstanceView&gt; Disks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.DiskInstanceView&gt; Disks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.Disks" />
      <MemberSignature Language="VB.NET" Value="Public Property Disks As IList(Of DiskInstanceView)" />
      <MemberSignature Language="F#" Value="member this.Disks : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskInstanceView&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.Disks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="disks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.DiskInstanceView&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27a87-120">取得またはディスクの情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="27a87-120">Gets or sets the disks information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Extensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView&gt; Extensions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView&gt; Extensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.Extensions" />
      <MemberSignature Language="VB.NET" Value="Public Property Extensions As IList(Of VirtualMachineExtensionInstanceView)" />
      <MemberSignature Language="F#" Value="member this.Extensions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.Extensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extensions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionInstanceView&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27a87-121">取得または拡張機能の情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="27a87-121">Gets or sets the extensions information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlacementGroupId">
      <MemberSignature Language="C#" Value="public string PlacementGroupId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PlacementGroupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.PlacementGroupId" />
      <MemberSignature Language="VB.NET" Value="Public Property PlacementGroupId As String" />
      <MemberSignature Language="F#" Value="member this.PlacementGroupId : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.PlacementGroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="placementGroupId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27a87-122">取得または VM が実行されている配置グループを設定します。</span><span class="sxs-lookup"><span data-stu-id="27a87-122">Gets or sets the placement group in which the VM is running.</span></span> <span data-ttu-id="27a87-123">VM の割り当てが解除された場合、placementGroupId は与えられません。</span><span class="sxs-lookup"><span data-stu-id="27a87-123">If the VM is deallocated it will not have a placementGroupId.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformFaultDomain">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PlatformFaultDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PlatformFaultDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.PlatformFaultDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property PlatformFaultDomain As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PlatformFaultDomain : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.PlatformFaultDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="platformFaultDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27a87-124">取得またはフォールト ドメインの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="27a87-124">Gets or sets the Fault Domain count.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformUpdateDomain">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PlatformUpdateDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PlatformUpdateDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.PlatformUpdateDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property PlatformUpdateDomain As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PlatformUpdateDomain : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.PlatformUpdateDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="platformUpdateDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27a87-125">取得または更新ドメインの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="27a87-125">Gets or sets the Update Domain count.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RdpThumbPrint">
      <MemberSignature Language="C#" Value="public string RdpThumbPrint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RdpThumbPrint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.RdpThumbPrint" />
      <MemberSignature Language="VB.NET" Value="Public Property RdpThumbPrint As String" />
      <MemberSignature Language="F#" Value="member this.RdpThumbPrint : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.RdpThumbPrint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rdpThumbPrint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27a87-126">取得またはリモート デスクトップ証明書の拇印を設定します。</span><span class="sxs-lookup"><span data-stu-id="27a87-126">Gets or sets the Remote desktop certificate thumbprint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statuses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; Statuses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; Statuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.Statuses" />
      <MemberSignature Language="VB.NET" Value="Public Property Statuses As IList(Of InstanceViewStatus)" />
      <MemberSignature Language="F#" Value="member this.Statuses : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.Statuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statuses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27a87-127">取得またはリソースの状態情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="27a87-127">Gets or sets the resource status information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VmAgent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView VmAgent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView VmAgent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.VmAgent" />
      <MemberSignature Language="VB.NET" Value="Public Property VmAgent As VirtualMachineAgentInstanceView" />
      <MemberSignature Language="F#" Value="member this.VmAgent : Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.VmAgent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmAgent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineAgentInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27a87-128">取得または仮想マシンで実行されている VM エージェントを設定します。</span><span class="sxs-lookup"><span data-stu-id="27a87-128">Gets or sets the VM Agent running on the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VmHealth">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus VmHealth { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus VmHealth" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.VmHealth" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VmHealth As VirtualMachineHealthStatus" />
      <MemberSignature Language="F#" Value="member this.VmHealth : Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView.VmHealth" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmHealth")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineHealthStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="27a87-129">仮想マシンの正常性状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="27a87-129">Gets the health status for the VM.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>