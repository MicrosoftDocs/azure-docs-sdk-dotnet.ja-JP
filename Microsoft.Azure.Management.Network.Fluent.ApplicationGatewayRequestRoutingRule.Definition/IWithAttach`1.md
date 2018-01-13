<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithCookieBasedAffinity&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithHostName&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.HasCookieBasedAffinity.Definition.IWithCookieBasedAffinity&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithAttach&lt;ParentT&gt;&gt;, Microsoft.Azure.Management.Network.Fluent.HasHostName.Definition.IWithHostName&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithAttach&lt;ParentT&gt;&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithCookieBasedAffinity`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithHostName`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.HasCookieBasedAffinity.Definition.IWithCookieBasedAffinity`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithAttach`1&lt;!ParentT&gt;&gt;, class Microsoft.Azure.Management.Network.Fluent.HasHostName.Definition.IWithHostName`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithAttach`1&lt;!ParentT&gt;&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IInDefinition(Of ParentT), IWithCookieBasedAffinity(Of IWithAttach(Of ParentT)), IWithCookieBasedAffinity(Of ParentT), IWithHostName(Of IWithAttach(Of ParentT)), IWithHostName(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInDefinition&lt;'ParentT&gt;&#xA;    interface IWithHostName&lt;'ParentT&gt;&#xA;    interface IWithHostName&lt;IWithAttach&lt;'ParentT&gt;&gt;&#xA;    interface IWithCookieBasedAffinity&lt;'ParentT&gt;&#xA;    interface IWithCookieBasedAffinity&lt;IWithAttach&lt;'ParentT&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithCookieBasedAffinity&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithHostName&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasCookieBasedAffinity.Definition.IWithCookieBasedAffinity&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithAttach&lt;ParentT&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasHostName.Definition.IWithHostName&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithAttach&lt;ParentT&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に返される、アプリケーション ゲートウェイの定義の段階です。</typeparam>
    <summary>
            Application gateway の最終段階では、ルーティング ルールの定義を要求します。
            この段階で、残りの省略可能な設定を指定することができます、または定義 WithAttach.attach() を使用して親アプリケーション ゲートウェイ定義にアタッチできます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>