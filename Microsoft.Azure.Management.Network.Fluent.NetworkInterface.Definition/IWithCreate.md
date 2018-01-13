<Type Name="IWithCreate" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate">
  <TypeSignature Language="C#" Value="public interface IWithCreate : Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithAcceleratedNetworking, Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithLoadBalancer, Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithNetworkSecurityGroup, Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPublicIPAddress, Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithSecondaryIPConfiguration, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCreate implements class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithAcceleratedNetworking, class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithLoadBalancer, class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithNetworkSecurityGroup, class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPublicIPAddress, class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithSecondaryIPConfiguration, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCreate&#xA;Implements ICreatable(Of INetworkInterface), IDefinitionWithTags(Of IWithCreate), IWithAcceleratedNetworking, IWithLoadBalancer, IWithNetworkSecurityGroup, IWithPrimaryPublicIPAddress, IWithSecondaryIPConfiguration" />
  <TypeSignature Language="F#" Value="type IWithCreate = interface&#xA;    interface ICreatable&lt;INetworkInterface&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;&#xA;    interface IWithPrimaryPublicIPAddress&#xA;    interface IWithNetworkSecurityGroup&#xA;    interface IWithSecondaryIPConfiguration&#xA;    interface IWithAcceleratedNetworking&#xA;    interface IWithLoadBalancer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithAcceleratedNetworking</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithLoadBalancer</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithNetworkSecurityGroup</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPublicIPAddress</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithSecondaryIPConfiguration</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            含むすべての最低限必要な入力を作成するリソースのネットワーク インターフェイス定義のステージ (WithCreate.create())、経由での他の省略可能な設定を指定することもできますが、します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDnsServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithDnsServer (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithDnsServer(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate.WithDnsServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDnsServer (ipAddress As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDnsServer : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithCreate.WithDnsServer ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress">DNS サーバーの IP アドレス。</param>
        <summary>
            ネットワーク インターフェイスに関連付けるカスタムの DNS サーバーの IP アドレスを指定します。
            このメソッドの効果は加法、つまりたびにこれを使用すると、新しい dns サーバーは追加ネットワーク インターフェイスにします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithInternalDnsNameLabel">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithInternalDnsNameLabel (string dnsNameLabel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithInternalDnsNameLabel(string dnsNameLabel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate.WithInternalDnsNameLabel(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithInternalDnsNameLabel (dnsNameLabel As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithInternalDnsNameLabel : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithCreate.WithInternalDnsNameLabel dnsNameLabel" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dnsNameLabel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dnsNameLabel">内部 DNS 名ラベルです。</param>
        <summary>
            ネットワーク インターフェイスの内部 DNS 名ラベルを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithIPForwarding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithIPForwarding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithIPForwarding() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate.WithIPForwarding" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIPForwarding () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithIPForwarding : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithCreate.WithIPForwarding " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ネットワーク インターフェイスの IP 転送を有効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>