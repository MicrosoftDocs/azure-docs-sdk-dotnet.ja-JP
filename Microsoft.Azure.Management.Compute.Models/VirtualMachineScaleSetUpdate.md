<Type Name="VirtualMachineScaleSetUpdate" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetUpdate : Microsoft.Azure.Management.Compute.Models.UpdateResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetUpdate extends Microsoft.Azure.Management.Compute.Models.UpdateResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetUpdate&#xA;Inherits UpdateResource" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetUpdate = class&#xA;    inherit UpdateResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.UpdateResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="fb459-101">仮想マシン スケール セットをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="fb459-101">Describes a Virtual Machine Scale Set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fb459-102">VirtualMachineScaleSetUpdate クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fb459-102">Initializes a new instance of the VirtualMachineScaleSetUpdate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetUpdate (System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Compute.Models.Sku sku = null, Microsoft.Azure.Management.Compute.Models.Plan plan = null, Microsoft.Azure.Management.Compute.Models.UpgradePolicy upgradePolicy = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile virtualMachineProfile = null, Nullable&lt;bool&gt; overprovision = null, Nullable&lt;bool&gt; singlePlacementGroup = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity identity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Compute.Models.Sku sku, class Microsoft.Azure.Management.Compute.Models.Plan plan, class Microsoft.Azure.Management.Compute.Models.UpgradePolicy upgradePolicy, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile virtualMachineProfile, valuetype System.Nullable`1&lt;bool&gt; overprovision, valuetype System.Nullable`1&lt;bool&gt; singlePlacementGroup, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity identity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.#ctor(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Compute.Models.Sku,Microsoft.Azure.Management.Compute.Models.Plan,Microsoft.Azure.Management.Compute.Models.UpgradePolicy,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile,System.Nullable{System.Boolean},System.Nullable{System.Boolean},Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Compute.Models.Sku * Microsoft.Azure.Management.Compute.Models.Plan * Microsoft.Azure.Management.Compute.Models.UpgradePolicy * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate (tags, sku, plan, upgradePolicy, virtualMachineProfile, overprovision, singlePlacementGroup, identity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Compute.Models.Sku" />
        <Parameter Name="plan" Type="Microsoft.Azure.Management.Compute.Models.Plan" />
        <Parameter Name="upgradePolicy" Type="Microsoft.Azure.Management.Compute.Models.UpgradePolicy" />
        <Parameter Name="virtualMachineProfile" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile" />
        <Parameter Name="overprovision" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="singlePlacementGroup" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity" />
      </Parameters>
      <Docs>
        <param name="tags"><span data-ttu-id="fb459-103">リソース タグ</span><span class="sxs-lookup"><span data-stu-id="fb459-103">Resource tags</span></span></param>
        <param name="sku"><span data-ttu-id="fb459-104">仮想マシン スケール セットの sku。</span><span class="sxs-lookup"><span data-stu-id="fb459-104">The virtual machine scale set sku.</span></span></param>
        <param name="plan"><span data-ttu-id="fb459-105">購入プラン VM Marketplace イメージから設定する仮想マシンのスケールを展開するときにします。</span><span class="sxs-lookup"><span data-stu-id="fb459-105">The purchase plan when deploying a virtual machine scale set from VM Marketplace images.</span></span></param>
        <param name="upgradePolicy"><span data-ttu-id="fb459-106">アップグレードのポリシー。</span><span class="sxs-lookup"><span data-stu-id="fb459-106">The upgrade policy.</span></span></param>
        <param name="virtualMachineProfile"><span data-ttu-id="fb459-107">バーチャル マシン プロファイル。</span><span class="sxs-lookup"><span data-stu-id="fb459-107">The virtual machine profile.</span></span></param>
        <param name="overprovision"><span data-ttu-id="fb459-108">仮想マシン スケール セットを overprovisioned する必要があるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="fb459-108">Specifies whether the Virtual Machine Scale Set should be overprovisioned.</span></span></param>
        <param name="singlePlacementGroup"><span data-ttu-id="fb459-109">True の場合は、スケールの最大サイズは 100 の仮想マシンの 1 つの配置グループ セットが制限されます。</span><span class="sxs-lookup"><span data-stu-id="fb459-109">When true this limits the scale set to a single placement group, of max size 100 virtual machines.</span></span></param>
        <param name="identity"><span data-ttu-id="fb459-110">構成されている場合、仮想マシン スケール セットの id。</span><span class="sxs-lookup"><span data-stu-id="fb459-110">The identity of the virtual machine scale set, if configured.</span></span></param>
        <summary>
            <span data-ttu-id="fb459-111">VirtualMachineScaleSetUpdate クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fb459-111">Initializes a new instance of the VirtualMachineScaleSetUpdate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As VirtualMachineScaleSetIdentity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb459-112">取得または構成されている場合に、仮想マシン スケール セットの id を設定します。</span><span class="sxs-lookup"><span data-stu-id="fb459-112">Gets or sets the identity of the virtual machine scale set, if configured.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Overprovision">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Overprovision { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Overprovision" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Overprovision" />
      <MemberSignature Language="VB.NET" Value="Public Property Overprovision As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Overprovision : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Overprovision" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.overprovision")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb459-113">取得または設定は、仮想マシン スケール セットを overprovisioned する必要があるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="fb459-113">Gets or sets specifies whether the Virtual Machine Scale Set should be overprovisioned.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Plan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.Plan Plan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.Plan Plan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Plan" />
      <MemberSignature Language="VB.NET" Value="Public Property Plan As Plan" />
      <MemberSignature Language="F#" Value="member this.Plan : Microsoft.Azure.Management.Compute.Models.Plan with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Plan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
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
            <span data-ttu-id="fb459-114">取得または VM Marketplace イメージから設定する仮想マシンのスケールを展開するときに、購入プランを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb459-114">Gets or sets the purchase plan when deploying a virtual machine scale set from VM Marketplace images.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SinglePlacementGroup">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SinglePlacementGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SinglePlacementGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.SinglePlacementGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property SinglePlacementGroup As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SinglePlacementGroup : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.SinglePlacementGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.singlePlacementGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb459-115">取得または true の場合は、スケール サイズの最大 100 の仮想マシンの 1 つの配置のグループに設定されてこの制限を設定します。</span><span class="sxs-lookup"><span data-stu-id="fb459-115">Gets or sets when true this limits the scale set to a single placement group, of max size 100 virtual machines.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb459-116">取得または仮想マシン スケール セットの sku を設定します。</span><span class="sxs-lookup"><span data-stu-id="fb459-116">Gets or sets the virtual machine scale set sku.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradePolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.UpgradePolicy UpgradePolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.UpgradePolicy UpgradePolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.UpgradePolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradePolicy As UpgradePolicy" />
      <MemberSignature Language="F#" Value="member this.UpgradePolicy : Microsoft.Azure.Management.Compute.Models.UpgradePolicy with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.UpgradePolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.upgradePolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.UpgradePolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb459-117">取得またはアップグレード ポリシーを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb459-117">Gets or sets the upgrade policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetUpdate.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fb459-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="fb459-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fb459-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fb459-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile VirtualMachineProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile VirtualMachineProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.VirtualMachineProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineProfile As VirtualMachineScaleSetUpdateVMProfile" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineProfile : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate.VirtualMachineProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualMachineProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateVMProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb459-120">取得またはバーチャル マシンのプロファイルを設定します。</span><span class="sxs-lookup"><span data-stu-id="fb459-120">Gets or sets the virtual machine profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>