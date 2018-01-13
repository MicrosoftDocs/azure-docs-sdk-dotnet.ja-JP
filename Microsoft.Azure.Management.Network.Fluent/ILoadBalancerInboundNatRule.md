<Type Name="ILoadBalancerInboundNatRule" FullName="Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatRule">
  <TypeSignature Language="C#" Value="public interface ILoadBalancerInboundNatRule : Microsoft.Azure.Management.Network.Fluent.IHasBackendPort, Microsoft.Azure.Management.Network.Fluent.IHasFloatingIP, Microsoft.Azure.Management.Network.Fluent.IHasFrontend, Microsoft.Azure.Management.Network.Fluent.IHasFrontendPort, Microsoft.Azure.Management.Network.Fluent.IHasProtocol&lt;Microsoft.Azure.Management.Network.Fluent.Models.TransportProtocol&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILoadBalancerInboundNatRule implements class Microsoft.Azure.Management.Network.Fluent.IHasBackendPort, class Microsoft.Azure.Management.Network.Fluent.IHasFloatingIP, class Microsoft.Azure.Management.Network.Fluent.IHasFrontend, class Microsoft.Azure.Management.Network.Fluent.IHasFrontendPort, class Microsoft.Azure.Management.Network.Fluent.IHasProtocol`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TransportProtocol&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILoadBalancerInboundNatRule&#xA;Implements IChildResource(Of ILoadBalancer), IHasBackendPort, IHasFloatingIP, IHasFrontend, IHasFrontendPort, IHasInner(Of InboundNatRuleInner), IHasParent(Of ILoadBalancer), IHasProtocol(Of TransportProtocol)" />
  <TypeSignature Language="F#" Value="type ILoadBalancerInboundNatRule = interface&#xA;    interface IHasFrontend&#xA;    interface IHasBackendPort&#xA;    interface IHasProtocol&lt;TransportProtocol&gt;&#xA;    interface IHasFloatingIP&#xA;    interface IHasFrontendPort&#xA;    interface IHasInner&lt;InboundNatRuleInner&gt;&#xA;    interface IChildResource&lt;ILoadBalancer&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;ILoadBalancer&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasBackendPort</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasFloatingIP</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasFrontend</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasFrontendPort</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasProtocol&lt;Microsoft.Azure.Management.Network.Fluent.Models.TransportProtocol&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.InboundNatRuleInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="cec0f-101">受信 NAT 規則の変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="cec0f-101">An immutable client-side representation of an inbound NAT rule.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="cec0f-102">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="cec0f-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="BackendNetworkInterfaceId">
      <MemberSignature Language="C#" Value="public string BackendNetworkInterfaceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackendNetworkInterfaceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatRule.BackendNetworkInterfaceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackendNetworkInterfaceId As String" />
      <MemberSignature Language="F#" Value="member this.BackendNetworkInterfaceId : string" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatRule.BackendNetworkInterfaceId" />
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
            <span data-ttu-id="cec0f-103">この受信 NAT 規則のバックエンドとして割り当てられているネットワーク インターフェイスのリソース ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="cec0f-103">Gets the resource ID of the network interface assigned as the backend of this inbound NAT rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendNicIPConfigurationName">
      <MemberSignature Language="C#" Value="public string BackendNicIPConfigurationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackendNicIPConfigurationName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatRule.BackendNicIPConfigurationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackendNicIPConfigurationName As String" />
      <MemberSignature Language="F#" Value="member this.BackendNicIPConfigurationName : string" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatRule.BackendNicIPConfigurationName" />
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
            <span data-ttu-id="cec0f-104">この NAT 規則に関連付けられているネットワーク インターフェイス IP 構成の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="cec0f-104">Gets the name of the IP configuration within the network interface associated with this NAT rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public int IdleTimeoutInMinutes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 IdleTimeoutInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatRule.IdleTimeoutInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IdleTimeoutInMinutes As Integer" />
      <MemberSignature Language="F#" Value="member this.IdleTimeoutInMinutes : int" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatRule.IdleTimeoutInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cec0f-105">アイドル状態の接続を閉じる前に分単位の数を取得します。</span><span class="sxs-lookup"><span data-stu-id="cec0f-105">Gets the number of minutes before an idle connection is closed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>