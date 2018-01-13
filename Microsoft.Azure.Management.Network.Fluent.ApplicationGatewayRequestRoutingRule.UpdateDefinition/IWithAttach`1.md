<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithCookieBasedAffinity&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithHostName&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithRedirectConfig&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithRedirectConfigBeta&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.HasCookieBasedAffinity.UpdateDefinition.IWithCookieBasedAffinity&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;, Microsoft.Azure.Management.Network.Fluent.HasHostName.UpdateDefinition.IWithHostName&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithCookieBasedAffinity`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithHostName`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithRedirectConfig`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithRedirectConfigBeta`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.HasCookieBasedAffinity.UpdateDefinition.IWithCookieBasedAffinity`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt;&gt;, class Microsoft.Azure.Management.Network.Fluent.HasHostName.UpdateDefinition.IWithHostName`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt;&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IBeta, IInUpdate(Of ParentT), IWithCookieBasedAffinity(Of IWithAttach(Of ParentT)), IWithCookieBasedAffinity(Of ParentT), IWithHostName(Of IWithAttach(Of ParentT)), IWithHostName(Of ParentT), IWithRedirectConfig(Of ParentT), IWithRedirectConfigBeta(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInUpdate&lt;'ParentT&gt;&#xA;    interface IWithHostName&lt;'ParentT&gt;&#xA;    interface IWithHostName&lt;IWithAttach&lt;'ParentT&gt;&gt;&#xA;    interface IWithCookieBasedAffinity&lt;'ParentT&gt;&#xA;    interface IWithCookieBasedAffinity&lt;IWithAttach&lt;'ParentT&gt;&gt;&#xA;    interface IWithRedirectConfig&lt;'ParentT&gt;&#xA;    interface IWithRedirectConfigBeta&lt;'ParentT&gt;&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithCookieBasedAffinity&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithHostName&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithRedirectConfig&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithRedirectConfigBeta&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasCookieBasedAffinity.UpdateDefinition.IWithCookieBasedAffinity&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasHostName.UpdateDefinition.IWithHostName&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
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