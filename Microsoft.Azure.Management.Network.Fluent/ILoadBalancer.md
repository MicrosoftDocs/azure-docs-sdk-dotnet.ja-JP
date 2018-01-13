<Type Name="ILoadBalancer" FullName="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer">
  <TypeSignature Language="C#" Value="public interface ILoadBalancer : Microsoft.Azure.Management.Network.Fluent.IHasLoadBalancingRules, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager,Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILoadBalancer implements class Microsoft.Azure.Management.Network.Fluent.IHasLoadBalancingRules, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManager, class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILoadBalancer&#xA;Implements IBeta, IGroupableResource(Of INetworkManager, LoadBalancerInner), IHasInner(Of LoadBalancerInner), IHasLoadBalancingRules, IHasManager(Of INetworkManager), ILoadBalancerBeta, IRefreshable(Of ILoadBalancer), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type ILoadBalancer = interface&#xA;    interface IGroupableResource&lt;INetworkManager, LoadBalancerInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;INetworkManager&gt;&#xA;    interface IHasInner&lt;LoadBalancerInner&gt;&#xA;    interface IRefreshable&lt;ILoadBalancer&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;&#xA;    interface IHasLoadBalancingRules&#xA;    interface ILoadBalancerBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasLoadBalancingRules</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager,Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancerInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="2b6f9-101">Azure でのロード バランサー管理 API のエントリ ポイント。</span><span class="sxs-lookup"><span data-stu-id="2b6f9-101">Entry point for load balancer management API in Azure.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="2b6f9-102">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="2b6f9-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Backends">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt; Backends { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt; Backends" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.Backends" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Backends As IReadOnlyDictionary(Of String, ILoadBalancerBackend)" />
      <MemberSignature Language="F#" Value="member this.Backends : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.Backends" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b6f9-103">取得負荷を分散するには、このロード バランサーのバックエンド間で、着信トラフィック名でインデックスを作成します。</span><span class="sxs-lookup"><span data-stu-id="2b6f9-103">Gets backends for this load balancer to load balance the incoming traffic among, indexed by name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FindFrontendByPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPublicFrontend FindFrontendByPublicIPAddress (Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress publicIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPublicFrontend FindFrontendByPublicIPAddress(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress publicIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.FindFrontendByPublicIPAddress(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress)" />
      <MemberSignature Language="VB.NET" Value="Public Function FindFrontendByPublicIPAddress (publicIPAddress As IPublicIPAddress) As ILoadBalancerPublicFrontend" />
      <MemberSignature Language="F#" Value="abstract member FindFrontendByPublicIPAddress : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress -&gt; Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPublicFrontend" Usage="iLoadBalancer.FindFrontendByPublicIPAddress publicIPAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPublicFrontend</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publicIPAddress" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress" />
      </Parameters>
      <Docs>
        <param name="publicIPAddress">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FindFrontendByPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPublicFrontend FindFrontendByPublicIPAddress (string publicIPAddressId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPublicFrontend FindFrontendByPublicIPAddress(string publicIPAddressId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.FindFrontendByPublicIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function FindFrontendByPublicIPAddress (publicIPAddressId As String) As ILoadBalancerPublicFrontend" />
      <MemberSignature Language="F#" Value="abstract member FindFrontendByPublicIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPublicFrontend" Usage="iLoadBalancer.FindFrontendByPublicIPAddress publicIPAddressId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPublicFrontend</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publicIPAddressId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publicIPAddressId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Frontends">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerFrontend&gt; Frontends { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerFrontend&gt; Frontends" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.Frontends" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Frontends As IReadOnlyDictionary(Of String, ILoadBalancerFrontend)" />
      <MemberSignature Language="F#" Value="member this.Frontends : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerFrontend&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.Frontends" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerFrontend&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b6f9-104">着信トラフィックをこのロード バランサーのフロント エンドを取得します。</span><span class="sxs-lookup"><span data-stu-id="2b6f9-104">Gets frontends for this load balancer, for the incoming traffic to come from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpProbes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerHttpProbe&gt; HttpProbes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerHttpProbe&gt; HttpProbes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.HttpProbes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HttpProbes As IReadOnlyDictionary(Of String, ILoadBalancerHttpProbe)" />
      <MemberSignature Language="F#" Value="member this.HttpProbes : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerHttpProbe&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.HttpProbes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerHttpProbe&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b6f9-105">このロード バランサーは、名前によってインデックス設定の HTTP プローブを取得します。</span><span class="sxs-lookup"><span data-stu-id="2b6f9-105">Gets HTTP probes of this load balancer, indexed by the name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundNatPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt; InboundNatPools { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt; InboundNatPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.InboundNatPools" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InboundNatPools As IReadOnlyDictionary(Of String, ILoadBalancerInboundNatPool)" />
      <MemberSignature Language="F#" Value="member this.InboundNatPools : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.InboundNatPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b6f9-106">取得着信 NAT プール、名前でインデックスを作成します。</span><span class="sxs-lookup"><span data-stu-id="2b6f9-106">Gets inbound NAT pools, indexed by name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundNatRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatRule&gt; InboundNatRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatRule&gt; InboundNatRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.InboundNatRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InboundNatRules As IReadOnlyDictionary(Of String, ILoadBalancerInboundNatRule)" />
      <MemberSignature Language="F#" Value="member this.InboundNatRules : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatRule&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.InboundNatRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b6f9-107">このバランサー、受信 NAT 規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="2b6f9-107">Gets inbound NAT rules for this balancer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateFrontends">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPrivateFrontend&gt; PrivateFrontends { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPrivateFrontend&gt; PrivateFrontends" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.PrivateFrontends" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrivateFrontends As IReadOnlyDictionary(Of String, ILoadBalancerPrivateFrontend)" />
      <MemberSignature Language="F#" Value="member this.PrivateFrontends : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPrivateFrontend&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.PrivateFrontends" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPrivateFrontend&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicFrontends">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPublicFrontend&gt; PublicFrontends { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPublicFrontend&gt; PublicFrontends" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.PublicFrontends" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicFrontends As IReadOnlyDictionary(Of String, ILoadBalancerPublicFrontend)" />
      <MemberSignature Language="F#" Value="member this.PublicFrontends : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPublicFrontend&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.PublicFrontends" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPublicFrontend&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAddressIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; PublicIPAddressIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; PublicIPAddressIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.PublicIPAddressIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicIPAddressIds As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddressIds : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.PublicIPAddressIds" />
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
            <span data-ttu-id="2b6f9-108">このロード バランサーのフロント エンドに割り当てられたパブリック IP アドレスのリソース Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="2b6f9-108">Gets resource IDs of the public IP addresses assigned to the frontends of this load balancer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TcpProbes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerTcpProbe&gt; TcpProbes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerTcpProbe&gt; TcpProbes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.TcpProbes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TcpProbes As IReadOnlyDictionary(Of String, ILoadBalancerTcpProbe)" />
      <MemberSignature Language="F#" Value="member this.TcpProbes : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerTcpProbe&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer.TcpProbes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerTcpProbe&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b6f9-109">このロード バランサーは、名前によってインデックス設定の TCP プローブを取得します。</span><span class="sxs-lookup"><span data-stu-id="2b6f9-109">Gets TCP probes of this load balancer, indexed by the name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>