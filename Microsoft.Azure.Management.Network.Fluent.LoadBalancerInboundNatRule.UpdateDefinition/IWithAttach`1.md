<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.HasBackendPort.UpdateDefinition.IWithBackendPort&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;, Microsoft.Azure.Management.Network.Fluent.HasFloatingIP.UpdateDefinition.IWithFloatingIP&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;, Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithBackendPort&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithFloatingIP&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithIdleTimeout&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.HasBackendPort.UpdateDefinition.IWithBackendPort`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt;&gt;, class Microsoft.Azure.Management.Network.Fluent.HasFloatingIP.UpdateDefinition.IWithFloatingIP`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt;&gt;, class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithBackendPort`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithFloatingIP`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithIdleTimeout`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IInUpdate(Of ParentT), IWithBackendPort(Of IWithAttach(Of ParentT)), IWithBackendPort(Of ParentT), IWithFloatingIP(Of IWithAttach(Of ParentT)), IWithFloatingIP(Of ParentT), IWithIdleTimeout(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInUpdate&lt;'ParentT&gt;&#xA;    interface IWithBackendPort&lt;'ParentT&gt;&#xA;    interface IWithBackendPort&lt;IWithAttach&lt;'ParentT&gt;&gt;&#xA;    interface IWithFloatingIP&lt;'ParentT&gt;&#xA;    interface IWithFloatingIP&lt;IWithAttach&lt;'ParentT&gt;&gt;&#xA;    interface IWithIdleTimeout&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasBackendPort.UpdateDefinition.IWithBackendPort&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasFloatingIP.UpdateDefinition.IWithFloatingIP&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithBackendPort&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithFloatingIP&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IWithIdleTimeout&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="aa52f-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="aa52f-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="aa52f-102">受信の NAT ルール定義の最終段階です。</span><span class="sxs-lookup"><span data-stu-id="aa52f-102">The final stage of the inbound NAT rule definition.</span></span>
            <span data-ttu-id="aa52f-103">この段階で、残りの省略可能な設定を指定することができます、または着信 NAT ルールの定義は WithAttach.attach() を使用して親ロード バランサーの定義に関連付けることができます。</span><span class="sxs-lookup"><span data-stu-id="aa52f-103">At this stage, any remaining optional settings can be specified, or the inbound NAT rule definition can be attached to the parent load balancer definition using  WithAttach.attach().</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>