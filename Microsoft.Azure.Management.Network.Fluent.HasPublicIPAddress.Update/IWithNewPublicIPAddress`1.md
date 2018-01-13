<Type Name="IWithNewPublicIPAddress&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithNewPublicIPAddress&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNewPublicIPAddress&lt;ReturnT&gt; : Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithNewPublicIPAddressNoDnsLabel&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNewPublicIPAddress`1&lt;ReturnT&gt; implements class Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithNewPublicIPAddressNoDnsLabel`1&lt;!ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithNewPublicIPAddress`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNewPublicIPAddress(Of ReturnT)&#xA;Implements IWithNewPublicIPAddressNoDnsLabel(Of ReturnT)" />
  <TypeSignature Language="F#" Value="type IWithNewPublicIPAddress&lt;'ReturnT&gt; = interface&#xA;    interface IWithNewPublicIPAddressNoDnsLabel&lt;'ReturnT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ReturnT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithNewPublicIPAddressNoDnsLabel&lt;ReturnT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ReturnT">定義の次のステージ。</typeparam>
    <summary>
            関連付ける新しいパブリック IP アドレス リソースを許可する更新プログラムの段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewPublicIPAddress">
      <MemberSignature Language="C#" Value="public ReturnT WithNewPublicIPAddress (string leafDnsLabel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithNewPublicIPAddress(string leafDnsLabel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithNewPublicIPAddress`1.WithNewPublicIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPublicIPAddress (leafDnsLabel As String) As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithNewPublicIPAddress : string -&gt; 'ReturnT" Usage="iWithNewPublicIPAddress.WithNewPublicIPAddress leafDnsLabel" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leafDnsLabel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="leafDnsLabel">リーフ ドメイン ラベルです。</param>
        <summary>
            指定した DNS ラベルで、リソースと同じリージョンとグループに新しいパブリック IP アドレスを作成し、リソースに関連付けます。
            パブリック IP アドレスの内部名は、DNS ラベルから導き出されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>