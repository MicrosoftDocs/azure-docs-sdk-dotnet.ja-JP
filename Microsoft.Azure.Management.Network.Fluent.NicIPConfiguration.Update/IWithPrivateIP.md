<Type Name="IWithPrivateIP" FullName="Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IWithPrivateIP">
  <TypeSignature Language="C#" Value="public interface IWithPrivateIP : Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Update.IWithPrivateIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrivateIP implements class Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Update.IWithPrivateIPAddress`1&lt;class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IWithPrivateIP" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrivateIP&#xA;Implements IWithPrivateIPAddress(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IWithPrivateIP = interface&#xA;    interface IWithPrivateIPAddress&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Update.IWithPrivateIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            ネットワーク インターフェイス IP 構成をプライベート IP の指定を許可する更新の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrivateIPVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithPrivateIPVersion (Microsoft.Azure.Management.Network.Fluent.Models.IPVersion ipVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithPrivateIPVersion(class Microsoft.Azure.Management.Network.Fluent.Models.IPVersion ipVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IWithPrivateIP.WithPrivateIPVersion(Microsoft.Azure.Management.Network.Fluent.Models.IPVersion)" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateIPVersion : Microsoft.Azure.Management.Network.Fluent.Models.IPVersion -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate" Usage="iWithPrivateIP.WithPrivateIPVersion ipVersion" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate</ReturnType>
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
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>