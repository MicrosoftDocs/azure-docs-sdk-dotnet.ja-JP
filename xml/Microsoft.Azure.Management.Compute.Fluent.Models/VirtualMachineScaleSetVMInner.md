<Type Name="VirtualMachineScaleSetVMInner" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetVMInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetVMInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetVMInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetVMInner = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="d3e44-101">仮想マシン スケール セットの仮想マシンについて説明します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-101">Describes a virtual machine scale set virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVMInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d3e44-102">VirtualMachineScaleSetVMInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-102">Initializes a new instance of the VirtualMachineScaleSetVMInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetVMInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string instanceId = null, Microsoft.Azure.Management.Compute.Fluent.Models.Sku sku = null, Nullable&lt;bool&gt; latestModelApplied = null, string vmId = null, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView instanceView = null, Microsoft.Azure.Management.Compute.Fluent.Models.HardwareProfile hardwareProfile = null, Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile storageProfile = null, Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile osProfile = null, Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile networkProfile = null, Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile diagnosticsProfile = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource availabilitySet = null, string provisioningState = null, string licenseType = null, Microsoft.Azure.Management.Compute.Fluent.Models.Plan plan = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt; resources = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string instanceId, class Microsoft.Azure.Management.Compute.Fluent.Models.Sku sku, valuetype System.Nullable`1&lt;bool&gt; latestModelApplied, string vmId, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView instanceView, class Microsoft.Azure.Management.Compute.Fluent.Models.HardwareProfile hardwareProfile, class Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile storageProfile, class Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile osProfile, class Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile networkProfile, class Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile diagnosticsProfile, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource availabilitySet, string provisioningState, string licenseType, class Microsoft.Azure.Management.Compute.Fluent.Models.Plan plan, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt; resources) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.Compute.Fluent.Models.Sku,System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView,Microsoft.Azure.Management.Compute.Fluent.Models.HardwareProfile,Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile,Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile,Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile,Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile,Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.Plan,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.Compute.Fluent.Models.Sku * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView * Microsoft.Azure.Management.Compute.Fluent.Models.HardwareProfile * Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile * Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile * Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile * Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.Plan * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner (location, id, name, type, tags, instanceId, sku, latestModelApplied, vmId, instanceView, hardwareProfile, storageProfile, osProfile, networkProfile, diagnosticsProfile, availabilitySet, provisioningState, licenseType, plan, resources)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Compute.Fluent.Models.Sku" />
        <Parameter Name="latestModelApplied" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="vmId" Type="System.String" />
        <Parameter Name="instanceView" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView" />
        <Parameter Name="hardwareProfile" Type="Microsoft.Azure.Management.Compute.Fluent.Models.HardwareProfile" />
        <Parameter Name="storageProfile" Type="Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile" />
        <Parameter Name="osProfile" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile" />
        <Parameter Name="networkProfile" Type="Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile" />
        <Parameter Name="diagnosticsProfile" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile" />
        <Parameter Name="availabilitySet" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="licenseType" Type="System.String" />
        <Parameter Name="plan" Type="Microsoft.Azure.Management.Compute.Fluent.Models.Plan" />
        <Parameter Name="resources" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="instanceId"><span data-ttu-id="d3e44-103">仮想マシン インスタンスの id。</span><span class="sxs-lookup"><span data-stu-id="d3e44-103">The virtual machine instance ID.</span></span></param>
        <param name="sku"><span data-ttu-id="d3e44-104">バーチャル マシン SKU です。</span><span class="sxs-lookup"><span data-stu-id="d3e44-104">The virtual machine SKU.</span></span></param>
        <param name="latestModelApplied"><span data-ttu-id="d3e44-105">仮想マシンに最新のモデルが適用されているかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-105">Specifies whether the latest model has been applied to the virtual machine.</span></span></param>
        <param name="vmId"><span data-ttu-id="d3e44-106">Azure VM 一意の id。</span><span class="sxs-lookup"><span data-stu-id="d3e44-106">Azure VM unique ID.</span></span></param>
        <param name="instanceView"><span data-ttu-id="d3e44-107">仮想マシン インスタンス ビューです。</span><span class="sxs-lookup"><span data-stu-id="d3e44-107">The virtual machine instance view.</span></span></param>
        <param name="hardwareProfile"><span data-ttu-id="d3e44-108">ハードウェア プロファイル。</span><span class="sxs-lookup"><span data-stu-id="d3e44-108">The hardware profile.</span></span></param>
        <param name="storageProfile"><span data-ttu-id="d3e44-109">ストレージ プロファイル。</span><span class="sxs-lookup"><span data-stu-id="d3e44-109">The storage profile.</span></span></param>
        <param name="osProfile"><span data-ttu-id="d3e44-110">OS プロファイル。</span><span class="sxs-lookup"><span data-stu-id="d3e44-110">The OS profile.</span></span></param>
        <param name="networkProfile"><span data-ttu-id="d3e44-111">ネットワーク プロファイル。</span><span class="sxs-lookup"><span data-stu-id="d3e44-111">The network profile.</span></span></param>
        <param name="diagnosticsProfile"><span data-ttu-id="d3e44-112">診断プロファイル。</span><span class="sxs-lookup"><span data-stu-id="d3e44-112">The diagnostics profile.</span></span></param>
        <param name="availabilitySet"><span data-ttu-id="d3e44-113">このバーチャル マシンが属しているをセットの参照を可用性の Id。</span><span class="sxs-lookup"><span data-stu-id="d3e44-113">The reference Id of the availability set to which this virtual machine belongs.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="d3e44-114">プロビジョニングの状態、応答でのみ表示されます。</span><span class="sxs-lookup"><span data-stu-id="d3e44-114">The provisioning state, which only appears in the response.</span></span></param>
        <param name="licenseType"><span data-ttu-id="d3e44-115">ライセンスの種類はの表示、独自のシナリオのライセンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-115">The license type, which is for bring your own license scenario.</span></span></param>
        <param name="plan"><span data-ttu-id="d3e44-116">購入プラン VM Marketplace イメージから仮想マシンを展開するときにします。</span><span class="sxs-lookup"><span data-stu-id="d3e44-116">The purchase plan when deploying virtual machine from VM Marketplace images.</span></span></param>
        <param name="resources"><span data-ttu-id="d3e44-117">仮想マシンの子の拡張機能リソース。</span><span class="sxs-lookup"><span data-stu-id="d3e44-117">The virtual machine child extension resources.</span></span></param>
        <summary>
            <span data-ttu-id="d3e44-118">VirtualMachineScaleSetVMInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-118">Initializes a new instance of the VirtualMachineScaleSetVMInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilitySet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource AvailabilitySet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource AvailabilitySet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.AvailabilitySet" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailabilitySet As SubResource" />
      <MemberSignature Language="F#" Value="member this.AvailabilitySet : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.AvailabilitySet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availabilitySet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3e44-119">取得または設定がこの仮想マシンが属する可用性の Id の参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-119">Gets or sets the reference Id of the availability set to which this virtual machine belongs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile DiagnosticsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile DiagnosticsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.DiagnosticsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property DiagnosticsProfile As DiagnosticsProfile" />
      <MemberSignature Language="F#" Value="member this.DiagnosticsProfile : Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.DiagnosticsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.diagnosticsProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3e44-120">取得または診断プロファイルを設定します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-120">Gets or sets the diagnostics profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HardwareProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.HardwareProfile HardwareProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.HardwareProfile HardwareProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.HardwareProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property HardwareProfile As HardwareProfile" />
      <MemberSignature Language="F#" Value="member this.HardwareProfile : Microsoft.Azure.Management.Compute.Fluent.Models.HardwareProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.HardwareProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hardwareProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.HardwareProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3e44-121">取得またはハードウェア プロファイルを設定します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-121">Gets or sets the hardware profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceId">
      <MemberSignature Language="C#" Value="public string InstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.InstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceId As String" />
      <MemberSignature Language="F#" Value="member this.InstanceId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.InstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="instanceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3e44-122">仮想マシン インスタンスの ID を取得します</span><span class="sxs-lookup"><span data-stu-id="d3e44-122">Gets the virtual machine instance ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceView">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView InstanceView { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView InstanceView" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.InstanceView" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceView As VirtualMachineInstanceView" />
      <MemberSignature Language="F#" Value="member this.InstanceView : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.InstanceView" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.instanceView")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3e44-123">仮想マシン インスタンス ビューを取得します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-123">Gets the virtual machine instance view.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LatestModelApplied">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; LatestModelApplied { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; LatestModelApplied" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.LatestModelApplied" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LatestModelApplied As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.LatestModelApplied : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.LatestModelApplied" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.latestModelApplied")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3e44-124">取得するには、仮想マシンに最新のモデルが適用されているかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-124">Gets specifies whether the latest model has been applied to the virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LicenseType">
      <MemberSignature Language="C#" Value="public string LicenseType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LicenseType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.LicenseType" />
      <MemberSignature Language="VB.NET" Value="Public Property LicenseType As String" />
      <MemberSignature Language="F#" Value="member this.LicenseType : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.LicenseType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="d3e44-125">取得または設定が、ライセンスの種類、ライセンス シナリオを表示します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-125">Gets or sets the license type, which is for bring your own license scenario.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile NetworkProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile NetworkProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.NetworkProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkProfile As NetworkProfile" />
      <MemberSignature Language="F#" Value="member this.NetworkProfile : Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.NetworkProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.NetworkProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3e44-126">取得またはネットワークのプロファイルを設定します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-126">Gets or sets the network profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile OsProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile OsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.OsProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property OsProfile As OSProfile" />
      <MemberSignature Language="F#" Value="member this.OsProfile : Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.OsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.osProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3e44-127">取得または OS プロファイルを設定します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-127">Gets or sets the OS profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Plan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.Plan Plan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.Plan Plan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.Plan" />
      <MemberSignature Language="VB.NET" Value="Public Property Plan As Plan" />
      <MemberSignature Language="F#" Value="member this.Plan : Microsoft.Azure.Management.Compute.Fluent.Models.Plan with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.Plan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="plan")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.Plan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3e44-128">取得または VM Marketplace イメージから仮想マシンを展開するときに、購入プランを設定します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-128">Gets or sets the purchase plan when deploying virtual machine from VM Marketplace images.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.ProvisioningState" />
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
            <span data-ttu-id="d3e44-129">応答でのみ表示されます、プロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-129">Gets the provisioning state, which only appears in the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt; Resources { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt; Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.Resources" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resources As IList(Of VirtualMachineExtensionInner)" />
      <MemberSignature Language="F#" Value="member this.Resources : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.Resources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resources")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3e44-130">拡張機能リソースの仮想マシンの子を取得します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-130">Gets the virtual machine child extension resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.Sku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Fluent.Models.Sku" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.Sku" />
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
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3e44-131">仮想マシンの SKU を取得します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-131">Gets the virtual machine SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile StorageProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile StorageProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.StorageProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageProfile As StorageProfile" />
      <MemberSignature Language="F#" Value="member this.StorageProfile : Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.StorageProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d3e44-132">取得またはストレージ プロファイルを設定します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-132">Gets or sets the storage profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetVMInner.Validate " />
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
            <span data-ttu-id="d3e44-133">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="d3e44-133">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d3e44-134">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3e44-134">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmId">
      <MemberSignature Language="C#" Value="public string VmId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.VmId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VmId As String" />
      <MemberSignature Language="F#" Value="member this.VmId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner.VmId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="d3e44-135">Azure VM の一意な ID を取得します</span><span class="sxs-lookup"><span data-stu-id="d3e44-135">Gets azure VM unique ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>