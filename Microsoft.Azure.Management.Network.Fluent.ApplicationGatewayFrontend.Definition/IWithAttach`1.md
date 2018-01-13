<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Definition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Definition.IWithPrivateIP&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Definition.IWithSubnet&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Definition.IWithPrivateIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Definition.IWithAttach&lt;ParentT&gt;&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.IInDefinitionAlt&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Definition.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Definition.IWithAttach&lt;ParentT&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Definition.IWithPrivateIP`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Definition.IWithSubnet`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Definition.IWithPrivateIPAddress`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Definition.IWithAttach`1&lt;!ParentT&gt;&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.IInDefinitionAlt`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Definition.IWithSubnet`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Definition.IWithAttach`1&lt;!ParentT&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Definition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IInDefinitionAlt(Of ParentT), IWithPrivateIP(Of ParentT), IWithPrivateIPAddress(Of IWithAttach(Of ParentT)), IWithSubnet(Of IWithAttach(Of ParentT)), IWithSubnet(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInDefinitionAlt&lt;'ParentT&gt;&#xA;    interface IWithSubnet&lt;'ParentT&gt;&#xA;    interface IWithSubnet&lt;IWithAttach&lt;'ParentT&gt;&gt;&#xA;    interface IWithPrivateIP&lt;'ParentT&gt;&#xA;    interface IWithPrivateIPAddress&lt;IWithAttach&lt;'ParentT&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Definition.IWithPrivateIP&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Definition.IWithSubnet&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Definition.IWithPrivateIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Definition.IWithAttach&lt;ParentT&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.IInDefinitionAlt&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Definition.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Definition.IWithAttach&lt;ParentT&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るには、親アプリケーション ゲートウェイ定義の段階です。</typeparam>
    <summary>
            アプリケーション ゲートウェイのフロント エンド定義の最終段階です。
            この段階で、残りの省略可能な設定を指定することができます、または、フロント エンドの定義は親アプリケーション ゲートウェイ定義にアタッチできます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>