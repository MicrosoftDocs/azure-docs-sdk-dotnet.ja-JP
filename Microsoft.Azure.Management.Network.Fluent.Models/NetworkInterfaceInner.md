<Type Name="NetworkInterfaceInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner">
  <TypeSignature Language="C#" Value="public class NetworkInterfaceInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkInterfaceInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkInterfaceInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type NetworkInterfaceInner = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="4b35e-101">リソース グループ内のネットワーク インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="4b35e-101">A network interface in a resource group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4b35e-102">NetworkInterfaceInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4b35e-102">Initializes a new instance of the NetworkInterfaceInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource virtualMachine = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource networkSecurityGroup = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt; ipConfigurations = null, Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings dnsSettings = null, string macAddress = null, Nullable&lt;bool&gt; primary = null, Nullable&lt;bool&gt; enableAcceleratedNetworking = null, Nullable&lt;bool&gt; enableIPForwarding = null, string resourceGuid = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource virtualMachine, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource networkSecurityGroup, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt; ipConfigurations, class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings dnsSettings, string macAddress, valuetype System.Nullable`1&lt;bool&gt; primary, valuetype System.Nullable`1&lt;bool&gt; enableAcceleratedNetworking, valuetype System.Nullable`1&lt;bool&gt; enableIPForwarding, string resourceGuid, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner},Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional virtualMachine As SubResource = null, Optional networkSecurityGroup As SubResource = null, Optional ipConfigurations As IList(Of NetworkInterfaceIPConfigurationInner) = null, Optional dnsSettings As NetworkInterfaceDnsSettings = null, Optional macAddress As String = null, Optional primary As Nullable(Of Boolean) = null, Optional enableAcceleratedNetworking As Nullable(Of Boolean) = null, Optional enableIPForwarding As Nullable(Of Boolean) = null, Optional resourceGuid As String = null, Optional provisioningState As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt; * Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner (location, id, name, type, tags, virtualMachine, networkSecurityGroup, ipConfigurations, dnsSettings, macAddress, primary, enableAcceleratedNetworking, enableIPForwarding, resourceGuid, provisioningState, etag)" />
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
        <Parameter Name="virtualMachine" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="networkSecurityGroup" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="ipConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt;" />
        <Parameter Name="dnsSettings" Type="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings" />
        <Parameter Name="macAddress" Type="System.String" />
        <Parameter Name="primary" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableAcceleratedNetworking" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableIPForwarding" Type="System.Nullable&lt;System.Boolean&gt;" />
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
        <param name="virtualMachine">To be added.</param>
        <param name="networkSecurityGroup">To be added.</param>
        <param name="ipConfigurations">To be added.</param>
        <param name="dnsSettings">To be added.</param>
        <param name="macAddress">To be added.</param>
        <param name="primary">To be added.</param>
        <param name="enableAcceleratedNetworking">To be added.</param>
        <param name="enableIPForwarding">To be added.</param>
        <param name="resourceGuid">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <param name="etag">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings DnsSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings DnsSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.DnsSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSettings As NetworkInterfaceDnsSettings" />
      <MemberSignature Language="F#" Value="member this.DnsSettings : Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.DnsSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceDnsSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b35e-103">取得またはネットワーク インターフェイスで DNS 設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="4b35e-103">Gets or sets the DNS settings in network interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAcceleratedNetworking">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableAcceleratedNetworking { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableAcceleratedNetworking" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.EnableAcceleratedNetworking" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableAcceleratedNetworking As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableAcceleratedNetworking : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.EnableAcceleratedNetworking" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableAcceleratedNetworking")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b35e-104">取得または設定、ネットワーク インターフェイスがある場合は、有効になっているネットワークを高速化。</span><span class="sxs-lookup"><span data-stu-id="4b35e-104">Gets or sets if the network interface is accelerated networking enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableIPForwarding">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableIPForwarding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableIPForwarding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.EnableIPForwarding" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableIPForwarding As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableIPForwarding : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.EnableIPForwarding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableIPForwarding")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b35e-105">取得または設定は、このネットワーク インターフェイスの IP 転送が有効になっているかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="4b35e-105">Gets or sets indicates whether IP forwarding is enabled on this network interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.Etag" />
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
            <span data-ttu-id="4b35e-106">取得または設定、リソースを更新するたびに変化する一意の読み取り専用文字列。</span><span class="sxs-lookup"><span data-stu-id="4b35e-106">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt; IpConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt; IpConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.IpConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property IpConfigurations As IList(Of NetworkInterfaceIPConfigurationInner)" />
      <MemberSignature Language="F#" Value="member this.IpConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.IpConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceIPConfigurationInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b35e-107">取得またはネットワーク インターフェイスの ip 構成の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="4b35e-107">Gets or sets a list of IPConfigurations of the network interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MacAddress">
      <MemberSignature Language="C#" Value="public string MacAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MacAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.MacAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property MacAddress As String" />
      <MemberSignature Language="F#" Value="member this.MacAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.MacAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.macAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b35e-108">取得またはネットワーク インターフェイスの MAC アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="4b35e-108">Gets or sets the MAC address of the network interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource NetworkSecurityGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource NetworkSecurityGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.NetworkSecurityGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkSecurityGroup As SubResource" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroup : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.NetworkSecurityGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkSecurityGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b35e-109">取得または NetworkSecurityGroup リソースへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="4b35e-109">Gets or sets the reference of the NetworkSecurityGroup resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Primary">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Primary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Primary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.Primary" />
      <MemberSignature Language="VB.NET" Value="Public Property Primary As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Primary : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.Primary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b35e-110">これは、仮想マシン上のプライマリ ネットワーク インターフェイスであるかどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="4b35e-110">Gets whether this is a primary network interface on a virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.ProvisioningState" />
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
            <span data-ttu-id="4b35e-111">取得またはパブリック IP リソースのプロビジョニングの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="4b35e-111">Gets or sets the provisioning state of the public IP resource.</span></span>
            <span data-ttu-id="4b35e-112">使用可能な値が: '更新'、'削除' および '失敗' です。</span><span class="sxs-lookup"><span data-stu-id="4b35e-112">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.ResourceGuid" />
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
            <span data-ttu-id="4b35e-113">取得またはリソース GUID、ネットワーク インターフェイスのリソースのプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="4b35e-113">Gets or sets the resource GUID property of the network interface resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachine">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource VirtualMachine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource VirtualMachine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.VirtualMachine" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachine As SubResource" />
      <MemberSignature Language="F#" Value="member this.VirtualMachine : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner.VirtualMachine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualMachine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b35e-114">取得または仮想マシンへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="4b35e-114">Gets or sets the reference of a virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>