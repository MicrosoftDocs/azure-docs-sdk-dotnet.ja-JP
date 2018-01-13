<Type Name="IWithPrivateIP&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPrivateIP&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Definition.IWithPrivateIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrivateIP`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Definition.IWithPrivateIPAddress`1&lt;class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach`1&lt;class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrivateIP(Of ParentT)&#xA;Implements IWithPrivateIPAddress(Of IWithAttach(Of IWithCreate))" />
  <TypeSignature Language="F#" Value="type IWithPrivateIP&lt;'ParentT&gt; = interface&#xA;    interface IWithPrivateIPAddress&lt;IWithAttach&lt;IWithCreate&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Definition.IWithPrivateIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">最終的な Attachable.attach() の戻り値の型。</typeparam>
    <summary>
            仮想ネットワーク サブネット内のプライベート IP アドレスを指定を許可するネットワーク インターフェイス IP 構成定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrivateIPVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;ParentT&gt; WithPrivateIPVersion (Microsoft.Azure.Management.Network.Fluent.Models.IPVersion ipVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach`1&lt;!ParentT&gt; WithPrivateIPVersion(class Microsoft.Azure.Management.Network.Fluent.Models.IPVersion ipVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP`1.WithPrivateIPVersion(Microsoft.Azure.Management.Network.Fluent.Models.IPVersion)" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateIPVersion : Microsoft.Azure.Management.Network.Fluent.Models.IPVersion -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithPrivateIP.WithPrivateIPVersion ipVersion" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipVersion" Type="Microsoft.Azure.Management.Network.Fluent.Models.IPVersion" />
      </Parameters>
      <Docs>
        <param name="ipVersion">IP バージョン。</param>
        <summary>
            プライベート IP アドレスで IP のバージョンを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>