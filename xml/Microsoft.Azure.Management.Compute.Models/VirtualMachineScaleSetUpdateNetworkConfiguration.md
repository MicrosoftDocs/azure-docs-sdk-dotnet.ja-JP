<Type Name="VirtualMachineScaleSetUpdateNetworkConfiguration" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetUpdateNetworkConfiguration : Microsoft.Azure.Management.Compute.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetUpdateNetworkConfiguration extends Microsoft.Azure.Management.Compute.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetUpdateNetworkConfiguration&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetUpdateNetworkConfiguration = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="dcf5b-101">仮想マシン スケール セット ネットワーク プロファイルのネットワーク構成をについて説明します。</span><span class="sxs-lookup"><span data-stu-id="dcf5b-101">Describes a virtual machine scale set network profile's network configurations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetUpdateNetworkConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dcf5b-102">VirtualMachineScaleSetUpdateNetworkConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dcf5b-102">Initializes a new instance of the VirtualMachineScaleSetUpdateNetworkConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetUpdateNetworkConfiguration (string id = null, string name = null, Nullable&lt;bool&gt; primary = null, Nullable&lt;bool&gt; enableAcceleratedNetworking = null, Microsoft.Azure.Management.Compute.Models.SubResource networkSecurityGroup = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings dnsSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration&gt; ipConfigurations = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, valuetype System.Nullable`1&lt;bool&gt; primary, valuetype System.Nullable`1&lt;bool&gt; enableAcceleratedNetworking, class Microsoft.Azure.Management.Compute.Models.SubResource networkSecurityGroup, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings dnsSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration&gt; ipConfigurations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration.#ctor(System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},Microsoft.Azure.Management.Compute.Models.SubResource,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional primary As Nullable(Of Boolean) = null, Optional enableAcceleratedNetworking As Nullable(Of Boolean) = null, Optional networkSecurityGroup As SubResource = null, Optional dnsSettings As VirtualMachineScaleSetNetworkConfigurationDnsSettings = null, Optional ipConfigurations As IList(Of VirtualMachineScaleSetUpdateIPConfiguration) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration : string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.Compute.Models.SubResource * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration (id, name, primary, enableAcceleratedNetworking, networkSecurityGroup, dnsSettings, ipConfigurations)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="primary" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableAcceleratedNetworking" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="networkSecurityGroup" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
        <Parameter Name="dnsSettings" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings" />
        <Parameter Name="ipConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="dcf5b-103">リソース Id</span><span class="sxs-lookup"><span data-stu-id="dcf5b-103">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="dcf5b-104">ネットワークの構成名。</span><span class="sxs-lookup"><span data-stu-id="dcf5b-104">The network configuration name.</span></span></param>
        <param name="primary"><span data-ttu-id="dcf5b-105">これは、プライマリ仮想マシンの NIC であるかどうか。</span><span class="sxs-lookup"><span data-stu-id="dcf5b-105">Whether this is a primary NIC on a virtual machine.</span></span></param>
        <param name="enableAcceleratedNetworking"><span data-ttu-id="dcf5b-106">ネットワーク インターフェイスは高速ネットワークで有効になっているかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="dcf5b-106">Specifies whether the network interface is accelerated networking-enabled.</span></span></param>
        <param name="networkSecurityGroup"><span data-ttu-id="dcf5b-107">ネットワーク セキュリティ グループです。</span><span class="sxs-lookup"><span data-stu-id="dcf5b-107">The network security group.</span></span></param>
        <param name="dnsSettings"><span data-ttu-id="dcf5b-108">ネットワーク インターフェイスに適用する dns 設定。</span><span class="sxs-lookup"><span data-stu-id="dcf5b-108">The dns settings to be applied on the network interfaces.</span></span></param>
        <param name="ipConfigurations"><span data-ttu-id="dcf5b-109">仮想マシンのスケールでは、IP 構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="dcf5b-109">The virtual machine scale set IP Configuration.</span></span></param>
        <summary>
            <span data-ttu-id="dcf5b-110">VirtualMachineScaleSetUpdateNetworkConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dcf5b-110">Initializes a new instance of the VirtualMachineScaleSetUpdateNetworkConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings DnsSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings DnsSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration.DnsSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSettings As VirtualMachineScaleSetNetworkConfigurationDnsSettings" />
      <MemberSignature Language="F#" Value="member this.DnsSettings : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration.DnsSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dcf5b-111">取得またはネットワーク インターフェイスに適用する dns 設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="dcf5b-111">Gets or sets the dns settings to be applied on the network interfaces.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAcceleratedNetworking">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableAcceleratedNetworking { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableAcceleratedNetworking" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration.EnableAcceleratedNetworking" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableAcceleratedNetworking As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableAcceleratedNetworking : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration.EnableAcceleratedNetworking" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="dcf5b-112">取得または設定は、ネットワーク インターフェイスは高速ネットワークで有効になっているかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="dcf5b-112">Gets or sets specifies whether the network interface is accelerated networking-enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration&gt; IpConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration&gt; IpConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration.IpConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property IpConfigurations As IList(Of VirtualMachineScaleSetUpdateIPConfiguration)" />
      <MemberSignature Language="F#" Value="member this.IpConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration.IpConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dcf5b-113">取得または設定、仮想マシンのスケールは、IP 構成を設定します。</span><span class="sxs-lookup"><span data-stu-id="dcf5b-113">Gets or sets the virtual machine scale set IP Configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
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
            <span data-ttu-id="dcf5b-114">取得またはネットワーク構成の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="dcf5b-114">Gets or sets the network configuration name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource NetworkSecurityGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource NetworkSecurityGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration.NetworkSecurityGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkSecurityGroup As SubResource" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroup : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration.NetworkSecurityGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkSecurityGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dcf5b-115">取得またはネットワーク セキュリティ グループを設定します。</span><span class="sxs-lookup"><span data-stu-id="dcf5b-115">Gets or sets the network security group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Primary">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Primary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Primary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration.Primary" />
      <MemberSignature Language="VB.NET" Value="Public Property Primary As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Primary : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdateNetworkConfiguration.Primary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="dcf5b-116">取得または、これは、仮想マシン上のプライマリ NIC かどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="dcf5b-116">Gets or sets whether this is a primary NIC on a virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>