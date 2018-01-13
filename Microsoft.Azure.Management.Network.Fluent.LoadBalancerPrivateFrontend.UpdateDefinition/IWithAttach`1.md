<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.UpdateDefinition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.UpdateDefinition.IWithPrivateIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;, Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.UpdateDefinition.IWithAvailabilityZone&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.IInUpdateAlt&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.UpdateDefinition.IWithPrivateIPAddress`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt;&gt;, class Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.UpdateDefinition.IWithAvailabilityZone`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.IInUpdateAlt`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.UpdateDefinition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IBeta, IInUpdateAlt(Of ParentT), IWithAvailabilityZone(Of ParentT), IWithPrivateIPAddress(Of IWithAttach(Of ParentT))" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInUpdateAlt&lt;'ParentT&gt;&#xA;    interface IWithPrivateIPAddress&lt;IWithAttach&lt;'ParentT&gt;&gt;&#xA;    interface IWithAvailabilityZone&lt;'ParentT&gt;&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.UpdateDefinition.IWithPrivateIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.UpdateDefinition.IWithAttach&lt;ParentT&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.UpdateDefinition.IWithAvailabilityZone&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.IInUpdateAlt&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">WithAttach.attach() の戻り値の型。</typeparam>
    <summary>
            内部のフロント エンド定義の最終段階です。
            この段階で、残りの省略可能な設定を指定することができます、またはフロント エンド定義 WithAttach.attach() を使用して親ロード バランサーの定義にアタッチできます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>