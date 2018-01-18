<Type Name="INetworkInterfaceBase" FullName="Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase">
  <TypeSignature Language="C#" Value="public interface INetworkInterfaceBase : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract INetworkInterfaceBase implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase" />
  <TypeSignature Language="VB.NET" Value="Public Interface INetworkInterfaceBase&#xA;Implements IHasInner(Of NetworkInterfaceInner), IHasManager(Of INetworkManager)" />
  <TypeSignature Language="F#" Value="type INetworkInterfaceBase = interface&#xA;    interface IHasManager&lt;INetworkManager&gt;&#xA;    interface IHasInner&lt;NetworkInterfaceInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="915f3-101">標準ベースのネットワーク インターフェイスが共有され、仮想マシン スケール セットのネットワーク インターフェイス。</span><span class="sxs-lookup"><span data-stu-id="915f3-101">The base network interface shared across regular and virtual machine scale set network interface.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AppliedDnsServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; AppliedDnsServers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; AppliedDnsServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.AppliedDnsServers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppliedDnsServers As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AppliedDnsServers : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.AppliedDnsServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="915f3-102">DNS サーバーの適用を取得します。</span><span class="sxs-lookup"><span data-stu-id="915f3-102">Gets applied DNS servers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; DnsServers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; DnsServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.DnsServers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DnsServers As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DnsServers : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.DnsServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="915f3-103">インターフェイスの DNS サーバーにこのネットワークの IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="915f3-103">Gets IP addresses of this network interface's DNS servers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup GetNetworkSecurityGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup GetNetworkSecurityGroup() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.GetNetworkSecurityGroup" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNetworkSecurityGroup () As INetworkSecurityGroup" />
      <MemberSignature Language="F#" Value="abstract member GetNetworkSecurityGroup : unit -&gt; Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup" Usage="iNetworkInterfaceBase.GetNetworkSecurityGroup " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="915f3-104">取得、ネットワーク セキュリティ グループには、このネットワーク インターフェイスが関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="915f3-104">Gets the network security group associated this network interface.</span></span>
            <span data-ttu-id="915f3-105">このメソッドは、rest API 呼び出しをネットワーク セキュリティ グループのリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="915f3-105">This method makes a rest API call to fetch the Network Security Group resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="915f3-106">このネットワーク インターフェイスに関連付けられたネットワーク セキュリティ グループ。</span><span class="sxs-lookup"><span data-stu-id="915f3-106">The network security group associated with this network interface.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="InternalDnsNameLabel">
      <MemberSignature Language="C#" Value="public string InternalDnsNameLabel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalDnsNameLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.InternalDnsNameLabel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InternalDnsNameLabel As String" />
      <MemberSignature Language="F#" Value="member this.InternalDnsNameLabel : string" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.InternalDnsNameLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="915f3-107">このネットワーク インターフェイスに割り当てられた内部 DNS 名を取得します。</span><span class="sxs-lookup"><span data-stu-id="915f3-107">Gets the Internal DNS name assigned to this network interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalDomainNameSuffix">
      <MemberSignature Language="C#" Value="public string InternalDomainNameSuffix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalDomainNameSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.InternalDomainNameSuffix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InternalDomainNameSuffix As String" />
      <MemberSignature Language="F#" Value="member this.InternalDomainNameSuffix : string" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.InternalDomainNameSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="915f3-108">内部ドメイン名サフィックスを取得します。</span><span class="sxs-lookup"><span data-stu-id="915f3-108">Gets the internal domain name suffix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalFqdn">
      <MemberSignature Language="C#" Value="public string InternalFqdn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalFqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.InternalFqdn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InternalFqdn As String" />
      <MemberSignature Language="F#" Value="member this.InternalFqdn : string" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.InternalFqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="915f3-109">修飾ドメイン名を取得します。</span><span class="sxs-lookup"><span data-stu-id="915f3-109">Gets the qualified domain name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAcceleratedNetworkingEnabled">
      <MemberSignature Language="C#" Value="public bool IsAcceleratedNetworkingEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAcceleratedNetworkingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.IsAcceleratedNetworkingEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsAcceleratedNetworkingEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAcceleratedNetworkingEnabled : bool" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.IsAcceleratedNetworkingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsIPForwardingEnabled">
      <MemberSignature Language="C#" Value="public bool IsIPForwardingEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsIPForwardingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.IsIPForwardingEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsIPForwardingEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsIPForwardingEnabled : bool" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.IsIPForwardingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="915f3-110">取得<tt>true</tt>このネットワーク インターフェイスの IP 転送が有効になっている場合。</span><span class="sxs-lookup"><span data-stu-id="915f3-110">Gets <tt>true</tt> if IP forwarding is enabled in this network interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MacAddress">
      <MemberSignature Language="C#" Value="public string MacAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MacAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.MacAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MacAddress As String" />
      <MemberSignature Language="F#" Value="member this.MacAddress : string" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.MacAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="915f3-111">ネットワーク インターフェイスの MAC アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="915f3-111">Gets the MAC Address of the network interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroupId">
      <MemberSignature Language="C#" Value="public string NetworkSecurityGroupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NetworkSecurityGroupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.NetworkSecurityGroupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkSecurityGroupId As String" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroupId : string" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.NetworkSecurityGroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="915f3-112">このネットワーク インターフェイスに関連付けられたネットワーク セキュリティ グループのリソース id を取得します。</span><span class="sxs-lookup"><span data-stu-id="915f3-112">Gets the network security group resource id associated with this network interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryPrivateIP">
      <MemberSignature Language="C#" Value="public string PrimaryPrivateIP { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryPrivateIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.PrimaryPrivateIP" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryPrivateIP As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryPrivateIP : string" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.PrimaryPrivateIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="915f3-113">プライベート IP アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="915f3-113">Gets the private IP addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryPrivateIPAllocationMethod">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.IPAllocationMethod PrimaryPrivateIPAllocationMethod { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.IPAllocationMethod PrimaryPrivateIPAllocationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.PrimaryPrivateIPAllocationMethod" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryPrivateIPAllocationMethod As IPAllocationMethod" />
      <MemberSignature Language="F#" Value="member this.PrimaryPrivateIPAllocationMethod : Microsoft.Azure.Management.Network.Fluent.Models.IPAllocationMethod" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.PrimaryPrivateIPAllocationMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.IPAllocationMethod</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="915f3-114">このネットワーク インターフェイスのプライマリ IP 構成のプライベートの IP 割り当て方法 (動的、静的) を取得します。</span><span class="sxs-lookup"><span data-stu-id="915f3-114">Gets the private IP allocation method (Dynamic, Static) of this network interface's primary IP configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineId">
      <MemberSignature Language="C#" Value="public string VirtualMachineId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.VirtualMachineId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineId As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineId : string" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkInterfaceBase.VirtualMachineId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="915f3-115">存在しない場合は、関連付けられたバーチャル マシン、または null のリソース ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="915f3-115">Gets the resource ID of the associated virtual machine, or null if none.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>