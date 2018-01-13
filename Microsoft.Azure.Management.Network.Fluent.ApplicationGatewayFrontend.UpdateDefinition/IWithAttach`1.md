<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithPrivateIP&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithPublicIPAddress&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithSubnet&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.UpdateDefinition.IWithPrivateIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;, Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.UpdateDefinition.IWithExistingPublicIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.IInUpdateAlt&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.UpdateDefinition.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithPrivateIP`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithPublicIPAddress`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithSubnet`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.UpdateDefinition.IWithPrivateIPAddress`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt;&gt;, class Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.UpdateDefinition.IWithExistingPublicIPAddress`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt;&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.IInUpdateAlt`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.UpdateDefinition.IWithSubnet`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IInUpdateAlt(Of ParentT), IWithExistingPublicIPAddress(Of IWithAttach(Of ParentT)), IWithPrivateIP(Of ParentT), IWithPrivateIPAddress(Of IWithAttach(Of ParentT)), IWithPublicIPAddress(Of ParentT), IWithSubnet(Of IWithAttach(Of ParentT)), IWithSubnet(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInUpdateAlt&lt;'ParentT&gt;&#xA;    interface IWithPublicIPAddress&lt;'ParentT&gt;&#xA;    interface IWithExistingPublicIPAddress&lt;IWithAttach&lt;'ParentT&gt;&gt;&#xA;    interface IWithSubnet&lt;'ParentT&gt;&#xA;    interface IWithSubnet&lt;IWithAttach&lt;'ParentT&gt;&gt;&#xA;    interface IWithPrivateIP&lt;'ParentT&gt;&#xA;    interface IWithPrivateIPAddress&lt;IWithAttach&lt;'ParentT&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithPrivateIP&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithPublicIPAddress&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithSubnet&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.UpdateDefinition.IWithPrivateIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.UpdateDefinition.IWithExistingPublicIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.IInUpdateAlt&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.UpdateDefinition.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="60a6b-101">この定義をアタッチした後に戻るには、親アプリケーション ゲートウェイ定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="60a6b-101">The stage of the parent application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="60a6b-102">アプリケーション ゲートウェイのフロント エンド定義の最終段階です。</span><span class="sxs-lookup"><span data-stu-id="60a6b-102">The final stage of an application gateway frontend definition.</span></span>
            <span data-ttu-id="60a6b-103">この段階で、残りの省略可能な設定を指定することができます、または、フロント エンドの定義は親アプリケーション ゲートウェイ定義にアタッチできます。</span><span class="sxs-lookup"><span data-stu-id="60a6b-103">At this stage, any remaining optional settings can be specified, or the frontend definition can be attached to the parent application gateway definition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>