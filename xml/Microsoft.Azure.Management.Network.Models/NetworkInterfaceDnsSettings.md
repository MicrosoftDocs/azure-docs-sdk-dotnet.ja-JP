<Type Name="NetworkInterfaceDnsSettings" FullName="Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings">
  <TypeSignature Language="C#" Value="public class NetworkInterfaceDnsSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkInterfaceDnsSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkInterfaceDnsSettings" />
  <TypeSignature Language="F#" Value="type NetworkInterfaceDnsSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="346e8-101">ネットワーク インターフェイスの DNS 設定。</span><span class="sxs-lookup"><span data-stu-id="346e8-101">DNS settings of a network interface.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceDnsSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="346e8-102">NetworkInterfaceDnsSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="346e8-102">Initializes a new instance of the NetworkInterfaceDnsSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceDnsSettings (System.Collections.Generic.IList&lt;string&gt; dnsServers = null, System.Collections.Generic.IList&lt;string&gt; appliedDnsServers = null, string internalDnsNameLabel = null, string internalFqdn = null, string internalDomainNameSuffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; dnsServers, class System.Collections.Generic.IList`1&lt;string&gt; appliedDnsServers, string internalDnsNameLabel, string internalFqdn, string internalDomainNameSuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.#ctor(System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dnsServers As IList(Of String) = null, Optional appliedDnsServers As IList(Of String) = null, Optional internalDnsNameLabel As String = null, Optional internalFqdn As String = null, Optional internalDomainNameSuffix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings : System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings" Usage="new Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings (dnsServers, appliedDnsServers, internalDnsNameLabel, internalFqdn, internalDomainNameSuffix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dnsServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="appliedDnsServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="internalDnsNameLabel" Type="System.String" />
        <Parameter Name="internalFqdn" Type="System.String" />
        <Parameter Name="internalDomainNameSuffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dnsServers"><span data-ttu-id="346e8-103">DNS サーバーの IP アドレスの一覧です。</span><span class="sxs-lookup"><span data-stu-id="346e8-103">List of DNS servers IP addresses.</span></span> <span data-ttu-id="346e8-104">Azure に切り替えるには、使用する 'は AzureProvidedDNS' には、DNS 解決が用意されています。</span><span class="sxs-lookup"><span data-stu-id="346e8-104">Use 'AzureProvidedDNS' to switch to azure provided DNS resolution.</span></span>
            <span data-ttu-id="346e8-105">'AzureProvidedDNS' の値は、他の ip アドレスと組み合わせることはできません、dnsServers コレクション内の値のみをする必要があります。</span><span class="sxs-lookup"><span data-stu-id="346e8-105">'AzureProvidedDNS' value cannot be combined with other IPs, it must be the only value in dnsServers collection.</span></span></param>
        <param name="appliedDnsServers"><span data-ttu-id="346e8-106">この NIC を使用する VM が可用性セットの一部である場合は、この一覧は、可用性セットの一部であるすべての Nic からのすべての DNS サーバーの和集合があります。</span><span class="sxs-lookup"><span data-stu-id="346e8-106">If the VM that uses this NIC is part of an Availability Set, then this list will have the union of all DNS servers from all NICs that are part of the Availability Set.</span></span> <span data-ttu-id="346e8-107">このプロパティは、各 Vm 上に構成されました。</span><span class="sxs-lookup"><span data-stu-id="346e8-107">This property is what is configured on each of those VMs.</span></span></param>
        <param name="internalDnsNameLabel"><span data-ttu-id="346e8-108">同じ仮想ネットワーク内の Vm 間の内部通信に使用されるこの NIC の相対的な DNS 名。</span><span class="sxs-lookup"><span data-stu-id="346e8-108">Relative DNS name for this NIC used for internal communications between VMs in the same virtual network.</span></span></param>
        <param name="internalFqdn"><span data-ttu-id="346e8-109">完全修飾 DNS 名が同じ仮想ネットワーク内の Vm 間の内部通信をサポートします。</span><span class="sxs-lookup"><span data-stu-id="346e8-109">Fully qualified DNS name supporting internal communications between VMs in the same virtual network.</span></span></param>
        <param name="internalDomainNameSuffix"><span data-ttu-id="346e8-110">InternalDnsNameLabel が指定されていない場合でも、プライマリ仮想マシンの NIC の DNS エントリが作成されます。</span><span class="sxs-lookup"><span data-stu-id="346e8-110">Even if internalDnsNameLabel is not specified, a DNS entry is created for the primary NIC of the VM.</span></span> <span data-ttu-id="346e8-111">この DNS 名は、internalDomainNameSuffix の値は、VM の名前を連結して作成できます。</span><span class="sxs-lookup"><span data-stu-id="346e8-111">This DNS name can be constructed by concatenating the VM name with the value of internalDomainNameSuffix.</span></span></param>
        <summary>
            <span data-ttu-id="346e8-112">NetworkInterfaceDnsSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="346e8-112">Initializes a new instance of the NetworkInterfaceDnsSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppliedDnsServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AppliedDnsServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AppliedDnsServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.AppliedDnsServers" />
      <MemberSignature Language="VB.NET" Value="Public Property AppliedDnsServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AppliedDnsServers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.AppliedDnsServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="appliedDnsServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="346e8-113">取得またはの場合、この一覧は、可用性セットの一部であるすべての Nic からのすべての DNS サーバーの和集合に、この NIC を使用する VM を可用性セットの一部である場合を設定します。</span><span class="sxs-lookup"><span data-stu-id="346e8-113">Gets or sets if the VM that uses this NIC is part of an Availability Set, then this list will have the union of all DNS servers from all NICs that are part of the Availability Set.</span></span> <span data-ttu-id="346e8-114">このプロパティは、各 Vm 上に構成されました。</span><span class="sxs-lookup"><span data-stu-id="346e8-114">This property is what is configured on each of those VMs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DnsServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DnsServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.DnsServers" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DnsServers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.DnsServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dnsServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="346e8-115">取得または DNS サーバーの IP アドレスの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="346e8-115">Gets or sets list of DNS servers IP addresses.</span></span> <span data-ttu-id="346e8-116">Azure に切り替えるには、使用する 'は AzureProvidedDNS' には、DNS 解決が用意されています。</span><span class="sxs-lookup"><span data-stu-id="346e8-116">Use 'AzureProvidedDNS' to switch to azure provided DNS resolution.</span></span>
            <span data-ttu-id="346e8-117">'AzureProvidedDNS' の値は、他の ip アドレスと組み合わせることはできません、dnsServers コレクション内の値のみをする必要があります。</span><span class="sxs-lookup"><span data-stu-id="346e8-117">'AzureProvidedDNS' value cannot be combined with other IPs, it must be the only value in dnsServers collection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalDnsNameLabel">
      <MemberSignature Language="C#" Value="public string InternalDnsNameLabel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalDnsNameLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.InternalDnsNameLabel" />
      <MemberSignature Language="VB.NET" Value="Public Property InternalDnsNameLabel As String" />
      <MemberSignature Language="F#" Value="member this.InternalDnsNameLabel : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.InternalDnsNameLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="internalDnsNameLabel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="346e8-118">取得または同じ仮想ネットワーク内の Vm 間の内部通信に使用される NIC がこの相対 DNS 名を設定します。</span><span class="sxs-lookup"><span data-stu-id="346e8-118">Gets or sets relative DNS name for this NIC used for internal communications between VMs in the same virtual network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalDomainNameSuffix">
      <MemberSignature Language="C#" Value="public string InternalDomainNameSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalDomainNameSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.InternalDomainNameSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property InternalDomainNameSuffix As String" />
      <MemberSignature Language="F#" Value="member this.InternalDomainNameSuffix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.InternalDomainNameSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="internalDomainNameSuffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="346e8-119">取得または設定の VM のプライマリ NIC の DNS エントリが作成された internalDnsNameLabel が指定されていない場合でもです。</span><span class="sxs-lookup"><span data-stu-id="346e8-119">Gets or sets even if internalDnsNameLabel is not specified, a DNS entry is created for the primary NIC of the VM.</span></span> <span data-ttu-id="346e8-120">この DNS 名は、internalDomainNameSuffix の値は、VM の名前を連結して作成できます。</span><span class="sxs-lookup"><span data-stu-id="346e8-120">This DNS name can be constructed by concatenating the VM name with the value of internalDomainNameSuffix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalFqdn">
      <MemberSignature Language="C#" Value="public string InternalFqdn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalFqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.InternalFqdn" />
      <MemberSignature Language="VB.NET" Value="Public Property InternalFqdn As String" />
      <MemberSignature Language="F#" Value="member this.InternalFqdn : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.InternalFqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="internalFqdn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="346e8-121">取得または同じ仮想ネットワーク内の Vm 間の内部通信をサポートする完全修飾 DNS 名を設定します。</span><span class="sxs-lookup"><span data-stu-id="346e8-121">Gets or sets fully qualified DNS name supporting internal communications between VMs in the same virtual network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>