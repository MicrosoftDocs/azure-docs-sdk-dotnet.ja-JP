<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithHostName&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithProtocol&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithServerNameIndication&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.HasHostName.Definition.IWithHostName&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;&gt;, Microsoft.Azure.Management.Network.Fluent.HasServerNameIndication.Definition.IWithServerNameIndication&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithHostName`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithProtocol`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithServerNameIndication`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.HasHostName.Definition.IWithHostName`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;&gt;, class Microsoft.Azure.Management.Network.Fluent.HasServerNameIndication.Definition.IWithServerNameIndication`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IInDefinition(Of ParentT), IWithHostName(Of IWithAttach(Of IWithCreate)), IWithHostName(Of ParentT), IWithProtocol(Of ParentT), IWithServerNameIndication(Of IWithAttach(Of IWithCreate)), IWithServerNameIndication(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInDefinition&lt;'ParentT&gt;&#xA;    interface IWithProtocol&lt;'ParentT&gt;&#xA;    interface IWithHostName&lt;'ParentT&gt;&#xA;    interface IWithHostName&lt;IWithAttach&lt;IWithCreate&gt;&gt;&#xA;    interface IWithServerNameIndication&lt;'ParentT&gt;&#xA;    interface IWithServerNameIndication&lt;IWithAttach&lt;IWithCreate&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithHostName&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithProtocol&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithServerNameIndication&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasHostName.Definition.IWithHostName&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasServerNameIndication.Definition.IWithServerNameIndication&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="82e01-101">この定義をアタッチした後に戻るには、親アプリケーション ゲートウェイ定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="82e01-101">The stage of the parent application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="82e01-102">アプリケーション ゲートウェイ HTTP リスナーの最終段階です。</span><span class="sxs-lookup"><span data-stu-id="82e01-102">The final stage of an application gateway HTTP listener.</span></span>
            <span data-ttu-id="82e01-103">この段階で、残りの省略可能な設定を指定することができます、または定義 WithAttach.attach() を使用して親アプリケーション ゲートウェイ定義にアタッチできます。</span><span class="sxs-lookup"><span data-stu-id="82e01-103">At this stage, any remaining optional settings can be specified, or the definition can be attached to the parent application gateway definition using  WithAttach.attach().</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>