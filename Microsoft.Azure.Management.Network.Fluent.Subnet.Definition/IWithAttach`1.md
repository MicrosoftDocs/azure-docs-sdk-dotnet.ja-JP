<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithNetworkSecurityGroup&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithRouteTable&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithNetworkSecurityGroup`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithRouteTable`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IInDefinition(Of ParentT), IWithNetworkSecurityGroup(Of ParentT), IWithRouteTable(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInDefinition&lt;'ParentT&gt;&#xA;    interface IWithNetworkSecurityGroup&lt;'ParentT&gt;&#xA;    interface IWithRouteTable&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithNetworkSecurityGroup&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithRouteTable&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">WithAttach.attach() の戻り値の型。</typeparam>
    <summary>
            サブネットの定義の最終段階です。
            この段階で、残りの省略可能な設定を指定することができます、または WithAttach.attach() を使用して、親仮想ネットワーク定義をサブネット定義を関連付けることができます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>