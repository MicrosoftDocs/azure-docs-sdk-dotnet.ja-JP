<Type Name="VirtualMachineScaleSetNetworkConfiguration" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetNetworkConfiguration : Microsoft.Azure.Management.Compute.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetNetworkConfiguration extends Microsoft.Azure.Management.Compute.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetNetworkConfiguration&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetNetworkConfiguration = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f977f-101">仮想マシン スケール セット ネットワーク プロファイルのネットワーク構成をについて説明します。</span><span class="sxs-lookup"><span data-stu-id="f977f-101">Describes a virtual machine scale set network profile's network configurations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetNetworkConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration.#ctor" />
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
            <span data-ttu-id="f977f-102">VirtualMachineScaleSetNetworkConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f977f-102">Initializes a new instance of the VirtualMachineScaleSetNetworkConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetNetworkConfiguration (string name, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration&gt; ipConfigurations, string id = null, Nullable&lt;bool&gt; primary = null, Nullable&lt;bool&gt; enableAcceleratedNetworking = null, Microsoft.Azure.Management.Compute.Models.SubResource networkSecurityGroup = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings dnsSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration&gt; ipConfigurations, string id, valuetype System.Nullable`1&lt;bool&gt; primary, valuetype System.Nullable`1&lt;bool&gt; enableAcceleratedNetworking, class Microsoft.Azure.Management.Compute.Models.SubResource networkSecurityGroup, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings dnsSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},Microsoft.Azure.Management.Compute.Models.SubResource,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, ipConfigurations As IList(Of VirtualMachineScaleSetIPConfiguration), Optional id As String = null, Optional primary As Nullable(Of Boolean) = null, Optional enableAcceleratedNetworking As Nullable(Of Boolean) = null, Optional networkSecurityGroup As SubResource = null, Optional dnsSettings As VirtualMachineScaleSetNetworkConfigurationDnsSettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.Compute.Models.SubResource * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration (name, ipConfigurations, id, primary, enableAcceleratedNetworking, networkSecurityGroup, dnsSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="ipConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="primary" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableAcceleratedNetworking" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="networkSecurityGroup" Type="Microsoft.Azure.Management.Compute.Models.SubResource" />
        <Parameter Name="dnsSettings" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="f977f-103">ネットワークの構成名。</span><span class="sxs-lookup"><span data-stu-id="f977f-103">The network configuration name.</span></span></param>
        <param name="ipConfigurations"><span data-ttu-id="f977f-104">ネットワーク インターフェイスの IP 構成を指定します。</span><span class="sxs-lookup"><span data-stu-id="f977f-104">Specifies the IP configurations of the network interface.</span></span></param>
        <param name="id"><span data-ttu-id="f977f-105">リソース Id</span><span class="sxs-lookup"><span data-stu-id="f977f-105">Resource Id</span></span></param>
        <param name="primary"><span data-ttu-id="f977f-106">バーチャル マシンが 1 つ以上のネットワーク インターフェイスを持つ場合に、プライマリ ネットワーク インターフェイスを指定します。</span><span class="sxs-lookup"><span data-stu-id="f977f-106">Specifies the primary network interface in case the virtual machine has more than 1 network interface.</span></span></param>
        <param name="enableAcceleratedNetworking"><span data-ttu-id="f977f-107">ネットワーク インターフェイスは高速ネットワークで有効になっているかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="f977f-107">Specifies whether the network interface is accelerated networking-enabled.</span></span></param>
        <param name="networkSecurityGroup"><span data-ttu-id="f977f-108">ネットワーク セキュリティ グループです。</span><span class="sxs-lookup"><span data-stu-id="f977f-108">The network security group.</span></span></param>
        <param name="dnsSettings"><span data-ttu-id="f977f-109">ネットワーク インターフェイスに適用する dns 設定。</span><span class="sxs-lookup"><span data-stu-id="f977f-109">The dns settings to be applied on the network interfaces.</span></span></param>
        <summary>
            <span data-ttu-id="f977f-110">VirtualMachineScaleSetNetworkConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f977f-110">Initializes a new instance of the VirtualMachineScaleSetNetworkConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings DnsSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings DnsSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration.DnsSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSettings As VirtualMachineScaleSetNetworkConfigurationDnsSettings" />
      <MemberSignature Language="F#" Value="member this.DnsSettings : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfigurationDnsSettings with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration.DnsSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f977f-111">取得またはネットワーク インターフェイスに適用する dns 設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="f977f-111">Gets or sets the dns settings to be applied on the network interfaces.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAcceleratedNetworking">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableAcceleratedNetworking { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableAcceleratedNetworking" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration.EnableAcceleratedNetworking" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableAcceleratedNetworking As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableAcceleratedNetworking : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration.EnableAcceleratedNetworking" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f977f-112">取得または設定は、ネットワーク インターフェイスは高速ネットワークで有効になっているかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="f977f-112">Gets or sets specifies whether the network interface is accelerated networking-enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration&gt; IpConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration&gt; IpConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration.IpConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property IpConfigurations As IList(Of VirtualMachineScaleSetIPConfiguration)" />
      <MemberSignature Language="F#" Value="member this.IpConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration.IpConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f977f-113">取得または設定は、ネットワーク インターフェイスの IP 構成を指定します。</span><span class="sxs-lookup"><span data-stu-id="f977f-113">Gets or sets specifies the IP configurations of the network interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration.Name" />
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
            <span data-ttu-id="f977f-114">取得またはネットワーク構成の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="f977f-114">Gets or sets the network configuration name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.SubResource NetworkSecurityGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.SubResource NetworkSecurityGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration.NetworkSecurityGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkSecurityGroup As SubResource" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroup : Microsoft.Azure.Management.Compute.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration.NetworkSecurityGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f977f-115">取得またはネットワーク セキュリティ グループを設定します。</span><span class="sxs-lookup"><span data-stu-id="f977f-115">Gets or sets the network security group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Primary">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Primary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Primary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration.Primary" />
      <MemberSignature Language="VB.NET" Value="Public Property Primary As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Primary : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration.Primary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f977f-116">取得または設定は、バーチャル マシンが 1 つ以上のネットワーク インターフェイスを持つ場合に、プライマリ ネットワーク インターフェイスを指定します。</span><span class="sxs-lookup"><span data-stu-id="f977f-116">Gets or sets specifies the primary network interface in case the virtual machine has more than 1 network interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetNetworkConfiguration.Validate " />
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
            <span data-ttu-id="f977f-117">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="f977f-117">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f977f-118">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f977f-118">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>