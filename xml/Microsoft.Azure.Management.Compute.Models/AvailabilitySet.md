<Type Name="AvailabilitySet" FullName="Microsoft.Azure.Management.Compute.Models.AvailabilitySet">
  <TypeSignature Language="C#" Value="public class AvailabilitySet : Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AvailabilitySet extends Microsoft.Azure.Management.Compute.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.AvailabilitySet" />
  <TypeSignature Language="VB.NET" Value="Public Class AvailabilitySet&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type AvailabilitySet = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="6473b-101">仮想マシンに割り当てられる可用性セットに関する情報を指定します。</span><span class="sxs-lookup"><span data-stu-id="6473b-101">Specifies information about the availability set that the virtual machine should be assigned to.</span></span> <span data-ttu-id="6473b-102">同じ可用性セットで指定された仮想マシンは、可用性が最大限に別のノードに割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="6473b-102">Virtual machines specified in the same availability set are allocated to different nodes to maximize availability.</span></span> <span data-ttu-id="6473b-103">可用性セットの詳細については、次を参照してください。[仮想マシンの可用性管理](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-manage-availability?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json)です。</span><span class="sxs-lookup"><span data-stu-id="6473b-103">For more information about availability sets, see [Manage the availability of virtual machines](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-manage-availability?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json).</span></span>
            <span data-ttu-id="6473b-104">&lt;ブラジル&gt;&lt;br&gt; Azure の計画されたメンテナンスの詳細については、次を参照してください[Azure の仮想マシンの定期保守](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-planned-maintenance?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;ブラジル。&gt;現時点では、VM のみに追加できます可用性セットの作成時にします。</span><span class="sxs-lookup"><span data-stu-id="6473b-104">&lt;br&gt;&lt;br&gt; For more information on Azure planned maintainance, see [Planned maintenance for virtual machines in Azure](https://docs.microsoft.com/azure/virtual-machines/virtual-machines-windows-planned-maintenance?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json) &lt;br&gt;&lt;br&gt; Currently, a VM can only be added to availability set at creation time.</span></span> <span data-ttu-id="6473b-105">既存の仮想マシンは、可用性セットに追加できません。</span><span class="sxs-lookup"><span data-stu-id="6473b-105">An existing VM cannot be added to an availability set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailabilitySet ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.AvailabilitySet.#ctor" />
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
            <span data-ttu-id="6473b-106">可用性クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6473b-106">Initializes a new instance of the AvailabilitySet class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailabilitySet (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;int&gt; platformUpdateDomainCount = null, Nullable&lt;int&gt; platformFaultDomainCount = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; virtualMachines = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; statuses = null, Microsoft.Azure.Management.Compute.Models.Sku sku = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;int32&gt; platformUpdateDomainCount, valuetype System.Nullable`1&lt;int32&gt; platformFaultDomainCount, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; virtualMachines, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; statuses, class Microsoft.Azure.Management.Compute.Models.Sku sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.AvailabilitySet.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.SubResource},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.InstanceViewStatus},Microsoft.Azure.Management.Compute.Models.Sku)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.AvailabilitySet : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; * Microsoft.Azure.Management.Compute.Models.Sku -&gt; Microsoft.Azure.Management.Compute.Models.AvailabilitySet" Usage="new Microsoft.Azure.Management.Compute.Models.AvailabilitySet (location, id, name, type, tags, platformUpdateDomainCount, platformFaultDomainCount, virtualMachines, statuses, sku)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="platformUpdateDomainCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="platformFaultDomainCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="virtualMachines" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;" />
        <Parameter Name="statuses" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Compute.Models.Sku" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="6473b-107">リソースの場所</span><span class="sxs-lookup"><span data-stu-id="6473b-107">Resource location</span></span></param>
        <param name="id"><span data-ttu-id="6473b-108">リソース Id</span><span class="sxs-lookup"><span data-stu-id="6473b-108">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="6473b-109">リソース名</span><span class="sxs-lookup"><span data-stu-id="6473b-109">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="6473b-110">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="6473b-110">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="6473b-111">リソース タグ</span><span class="sxs-lookup"><span data-stu-id="6473b-111">Resource tags</span></span></param>
        <param name="platformUpdateDomainCount"><span data-ttu-id="6473b-112">ドメインの数を更新します。</span><span class="sxs-lookup"><span data-stu-id="6473b-112">Update Domain count.</span></span></param>
        <param name="platformFaultDomainCount"><span data-ttu-id="6473b-113">ドメインの数をフォールトします。</span><span class="sxs-lookup"><span data-stu-id="6473b-113">Fault Domain count.</span></span></param>
        <param name="virtualMachines"><span data-ttu-id="6473b-114">可用性内のすべての仮想マシンへの参照の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="6473b-114">A list of references to all virtual machines in the availability set.</span></span></param>
        <param name="statuses"><span data-ttu-id="6473b-115">リソースの状態情報です。</span><span class="sxs-lookup"><span data-stu-id="6473b-115">The resource status information.</span></span></param>
        <param name="sku"><span data-ttu-id="6473b-116">可用性セットの Sku</span><span class="sxs-lookup"><span data-stu-id="6473b-116">Sku of the availability set</span></span></param>
        <summary>
            <span data-ttu-id="6473b-117">可用性クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6473b-117">Initializes a new instance of the AvailabilitySet class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformFaultDomainCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PlatformFaultDomainCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PlatformFaultDomainCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.AvailabilitySet.PlatformFaultDomainCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PlatformFaultDomainCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PlatformFaultDomainCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.AvailabilitySet.PlatformFaultDomainCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.platformFaultDomainCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6473b-118">取得またはフォールト ドメイン数を設定します。</span><span class="sxs-lookup"><span data-stu-id="6473b-118">Gets or sets fault Domain count.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformUpdateDomainCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PlatformUpdateDomainCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PlatformUpdateDomainCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.AvailabilitySet.PlatformUpdateDomainCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PlatformUpdateDomainCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PlatformUpdateDomainCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.AvailabilitySet.PlatformUpdateDomainCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.platformUpdateDomainCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6473b-119">取得または設定は、ドメインの数を更新します。</span><span class="sxs-lookup"><span data-stu-id="6473b-119">Gets or sets update Domain count.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.AvailabilitySet.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Compute.Models.AvailabilitySet.Sku" />
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
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6473b-120">取得または設定の可用性セットの sku</span><span class="sxs-lookup"><span data-stu-id="6473b-120">Gets or sets sku of the availability set</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statuses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; Statuses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt; Statuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.AvailabilitySet.Statuses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Statuses As IList(Of InstanceViewStatus)" />
      <MemberSignature Language="F#" Value="member this.Statuses : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt;" Usage="Microsoft.Azure.Management.Compute.Models.AvailabilitySet.Statuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.statuses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6473b-121">リソースの状態情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="6473b-121">Gets the resource status information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.AvailabilitySet.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="availabilitySet.Validate " />
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
            <span data-ttu-id="6473b-122">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="6473b-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6473b-123">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6473b-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachines">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; VirtualMachines { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.SubResource&gt; VirtualMachines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.AvailabilitySet.VirtualMachines" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachines As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.VirtualMachines : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.AvailabilitySet.VirtualMachines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualMachines")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6473b-124">取得または可用性セットのすべての仮想マシンへの参照の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="6473b-124">Gets or sets a list of references to all virtual machines in the availability set.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>