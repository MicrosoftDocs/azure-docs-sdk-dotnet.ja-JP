<Type Name="ILoadBalancerPrivateFrontend" FullName="Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPrivateFrontend">
  <TypeSignature Language="C#" Value="public interface ILoadBalancerPrivateFrontend : Microsoft.Azure.Management.Network.Fluent.IHasPrivateIPAddress, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerFrontend, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPrivateFrontendBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasSubnet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILoadBalancerPrivateFrontend implements class Microsoft.Azure.Management.Network.Fluent.IHasLoadBalancingRules, class Microsoft.Azure.Management.Network.Fluent.IHasPrivateIPAddress, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerFrontend, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPrivateFrontendBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasSubnet, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPrivateFrontend" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILoadBalancerPrivateFrontend&#xA;Implements IBeta, IChildResource(Of ILoadBalancer), IHasInner(Of FrontendIPConfigurationInner), IHasParent(Of ILoadBalancer), IHasPrivateIPAddress, IHasSubnet, ILoadBalancerFrontend, ILoadBalancerPrivateFrontendBeta" />
  <TypeSignature Language="F#" Value="type ILoadBalancerPrivateFrontend = interface&#xA;    interface ILoadBalancerFrontend&#xA;    interface IHasInner&lt;FrontendIPConfigurationInner&gt;&#xA;    interface IChildResource&lt;ILoadBalancer&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;ILoadBalancer&gt;&#xA;    interface IHasLoadBalancingRules&#xA;    interface IHasPrivateIPAddress&#xA;    interface IHasSubnet&#xA;    interface ILoadBalancerPrivateFrontendBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasPrivateIPAddress</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ILoadBalancerFrontend</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPrivateFrontendBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.FrontendIPConfigurationInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasSubnet</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="28cee-101">内部ロード バランサーのプライベート フロント エンドの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="28cee-101">An immutable client-side representation of a private frontend of an internal load balancer.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="28cee-102">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="28cee-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ISubnet GetSubnet ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ISubnet GetSubnet() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ILoadBalancerPrivateFrontend.GetSubnet" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubnet () As ISubnet" />
      <MemberSignature Language="F#" Value="abstract member GetSubnet : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ISubnet" Usage="iLoadBalancerPrivateFrontend.GetSubnet " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ISubnet</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            <span data-ttu-id="28cee-103">注これにより、Azure に別個の呼び出しのサブネットが関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="28cee-103">Associated subnet Note this makes a separate call to Azure.</span></span>
            </return>
      </Docs>
    </Member>
  </Members>
</Type>