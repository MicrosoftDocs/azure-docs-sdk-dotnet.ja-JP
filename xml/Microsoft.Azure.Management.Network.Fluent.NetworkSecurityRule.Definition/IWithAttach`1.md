<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDescription&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithPriority&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDescription`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithPriority`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IInDefinition(Of ParentT), IWithDescription(Of ParentT), IWithPriority(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInDefinition&lt;'ParentT&gt;&#xA;    interface IWithPriority&lt;'ParentT&gt;&#xA;    interface IWithDescription&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDescription&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithPriority&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="fcf00-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="fcf00-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="fcf00-102">セキュリティ ルールの定義の最終段階です。</span><span class="sxs-lookup"><span data-stu-id="fcf00-102">The final stage of the security rule definition.</span></span>
            <span data-ttu-id="fcf00-103">この段階で、残りの省略可能な設定を指定することができます、またはセキュリティ ルールの定義は、親ネットワーク セキュリティ グループを使用して定義 WithAttach.attach() に関連付けることができます。</span><span class="sxs-lookup"><span data-stu-id="fcf00-103">At this stage, any remaining optional settings can be specified, or the security rule definition can be attached to the parent network security group definition using  WithAttach.attach().</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>