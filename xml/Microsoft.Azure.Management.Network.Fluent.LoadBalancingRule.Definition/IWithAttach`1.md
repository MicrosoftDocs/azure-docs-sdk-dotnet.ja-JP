<Type Name="IWithAttach&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithAttach&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ReturnT&gt; : Microsoft.Azure.Management.Network.Fluent.HasFloatingIP.Definition.IWithFloatingIP&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithAttach&lt;ReturnT&gt;&gt;, Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithFloatingIP&lt;ReturnT&gt;, Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithIdleTimeoutInMinutes&lt;ReturnT&gt;, Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithLoadDistribution&lt;ReturnT&gt;, Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithProbe&lt;ReturnT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ReturnT&gt; implements class Microsoft.Azure.Management.Network.Fluent.HasFloatingIP.Definition.IWithFloatingIP`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithAttach`1&lt;!ReturnT&gt;&gt;, class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithFloatingIP`1&lt;!ReturnT&gt;, class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithIdleTimeoutInMinutes`1&lt;!ReturnT&gt;, class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithLoadDistribution`1&lt;!ReturnT&gt;, class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithProbe`1&lt;!ReturnT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition`1&lt;!ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ReturnT)&#xA;Implements IInDefinition(Of ReturnT), IWithFloatingIP(Of IWithAttach(Of ReturnT)), IWithFloatingIP(Of ReturnT), IWithIdleTimeoutInMinutes(Of ReturnT), IWithLoadDistribution(Of ReturnT), IWithProbe(Of ReturnT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ReturnT&gt; = interface&#xA;    interface IInDefinition&lt;'ReturnT&gt;&#xA;    interface IWithFloatingIP&lt;'ReturnT&gt;&#xA;    interface IWithFloatingIP&lt;IWithAttach&lt;'ReturnT&gt;&gt;&#xA;    interface IWithIdleTimeoutInMinutes&lt;'ReturnT&gt;&#xA;    interface IWithLoadDistribution&lt;'ReturnT&gt;&#xA;    interface IWithProbe&lt;'ReturnT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasFloatingIP.Definition.IWithFloatingIP&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithAttach&lt;ReturnT&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithFloatingIP&lt;ReturnT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithIdleTimeoutInMinutes&lt;ReturnT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithLoadDistribution&lt;ReturnT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Definition.IWithProbe&lt;ReturnT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ReturnT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ReturnT"><span data-ttu-id="53c07-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="53c07-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="53c07-102">負荷分散のルールの定義の最終段階です。</span><span class="sxs-lookup"><span data-stu-id="53c07-102">The final stage of the load balancing rule definition.</span></span>
            <span data-ttu-id="53c07-103">この段階で、残りの省略可能な設定を指定することができます、または負荷分散のルールの定義を WithAttach.attach() を使用して親ロード バランサーの定義にアタッチできます。</span><span class="sxs-lookup"><span data-stu-id="53c07-103">At this stage, any remaining optional settings can be specified, or the load balancing rule definition can be attached to the parent load balancer definition using  WithAttach.attach().</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>