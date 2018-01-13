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
    <typeparam name="ParentT">WithAttach.attach() の戻り値の型。</typeparam>
    <summary>
            セキュリティ ルールの定義の最終段階です。
            この段階で、残りの省略可能な設定を指定することができます、またはセキュリティ ルールの定義は、親ネットワーク セキュリティ グループを使用して定義 WithAttach.attach() に関連付けることができます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>