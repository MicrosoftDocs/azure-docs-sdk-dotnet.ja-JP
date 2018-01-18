<Type Name="VirtualNetworkInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner">
  <TypeSignature Language="C#" Value="public class VirtualNetworkInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualNetworkInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualNetworkInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualNetworkInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
            <span data-ttu-id="4bcdf-101">仮想ネットワークのリソースです。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-101">Virtual Network resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4bcdf-102">VirtualNetworkInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-102">Initializes a new instance of the VirtualNetworkInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace addressSpace = null, Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions dhcpOptions = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; subnets = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; virtualNetworkPeerings = null, string resourceGuid = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace addressSpace, class Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions dhcpOptions, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; subnets, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; virtualNetworkPeerings, string resourceGuid, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace,Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner},System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace * Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner (location, id, name, type, tags, addressSpace, dhcpOptions, subnets, virtualNetworkPeerings, resourceGuid, provisioningState, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="addressSpace" Type="Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace" />
        <Parameter Name="dhcpOptions" Type="Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions" />
        <Parameter Name="subnets" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;" />
        <Parameter Name="virtualNetworkPeerings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="addressSpace"><span data-ttu-id="4bcdf-103">サブネットで使用できる IP アドレス範囲の配列を含む AddressSpace です。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-103">The AddressSpace that contains an array of IP address ranges that can be used by subnets.</span></span></param>
        <param name="dhcpOptions"><span data-ttu-id="4bcdf-104">仮想ネットワークにデプロイされた Vm で利用できる DNS サーバーの配列を含む dhcpOptions です。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-104">The dhcpOptions that contains an array of DNS servers available to VMs deployed in the virtual network.</span></span></param>
        <param name="subnets"><span data-ttu-id="4bcdf-105">仮想ネットワークのサブネットの一覧。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-105">A list of subnets in a Virtual Network.</span></span></param>
        <param name="virtualNetworkPeerings"><span data-ttu-id="4bcdf-106">仮想ネットワーク内のピアリングの一覧。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-106">A list of peerings in a Virtual Network.</span></span></param>
        <param name="resourceGuid"><span data-ttu-id="4bcdf-107">仮想ネットワーク リソースの resourceGuid プロパティです。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-107">The resourceGuid property of the Virtual Network resource.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="4bcdf-108">パブリック Ip リソースのプロビジョニングの状態。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-108">The provisioning state of the PublicIP resource.</span></span> <span data-ttu-id="4bcdf-109">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-109">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="etag"><span data-ttu-id="4bcdf-110">リソースを更新するたびに変化する一意の読み取り専用文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-110">Gets a unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="4bcdf-111">VirtualNetworkInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-111">Initializes a new instance of the VirtualNetworkInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddressSpace">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace AddressSpace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace AddressSpace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.AddressSpace" />
      <MemberSignature Language="VB.NET" Value="Public Property AddressSpace As AddressSpace" />
      <MemberSignature Language="F#" Value="member this.AddressSpace : Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.AddressSpace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.addressSpace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4bcdf-112">取得またはサブネットで使用できる IP アドレス範囲の配列を含む AddressSpace を設定します。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-112">Gets or sets the AddressSpace that contains an array of IP address ranges that can be used by subnets.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DhcpOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions DhcpOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions DhcpOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.DhcpOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property DhcpOptions As DhcpOptions" />
      <MemberSignature Language="F#" Value="member this.DhcpOptions : Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.DhcpOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dhcpOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4bcdf-113">取得または仮想ネットワークにデプロイされた Vm で利用できる DNS サーバーの配列を含む dhcpOptions を設定します。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-113">Gets or sets the dhcpOptions that contains an array of DNS servers available to VMs deployed in the virtual network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4bcdf-114">リソースを更新するたびに変化する一意の読み取り専用文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-114">Gets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
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
            <span data-ttu-id="4bcdf-115">取得またはパブリック Ip リソースのプロビジョニングの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-115">Gets or sets the provisioning state of the PublicIP resource.</span></span>
            <span data-ttu-id="4bcdf-116">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-116">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.ResourceGuid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceGuid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4bcdf-117">取得または仮想ネットワーク リソースの resourceGuid プロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-117">Gets or sets the resourceGuid property of the Virtual Network resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; Subnets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; Subnets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.Subnets" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnets As IList(Of SubnetInner)" />
      <MemberSignature Language="F#" Value="member this.Subnets : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.Subnets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4bcdf-118">取得または仮想ネットワークのサブネットのリストを設定します。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-118">Gets or sets a list of subnets in a Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkPeerings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; VirtualNetworkPeerings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; VirtualNetworkPeerings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.VirtualNetworkPeerings" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetworkPeerings As IList(Of VirtualNetworkPeeringInner)" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkPeerings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.VirtualNetworkPeerings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualNetworkPeerings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4bcdf-119">取得または仮想ネットワークのピアリングの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="4bcdf-119">Gets or sets a list of peerings in a Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>