<Type Name="IWithAaaaRecordIPv6Address&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithAaaaRecordIPv6Address&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAaaaRecordIPv6Address&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAaaaRecordIPv6Address`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithAaaaRecordIPv6Address`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAaaaRecordIPv6Address(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAaaaRecordIPv6Address&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">WithAttach.attach() の戻り値の型。</typeparam>
    <summary>
            AAAA レコードのステージでは、定義を最初の AAAA レコードを追加する許可を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIPv6Address">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithAaaaRecordIPv6AddressOrAttachable&lt;ParentT&gt; WithIPv6Address (string ipv6Address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithAaaaRecordIPv6AddressOrAttachable`1&lt;!ParentT&gt; WithIPv6Address(string ipv6Address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithAaaaRecordIPv6Address`1.WithIPv6Address(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIPv6Address (ipv6Address As String) As IWithAaaaRecordIPv6AddressOrAttachable(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithIPv6Address : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithAaaaRecordIPv6AddressOrAttachable&lt;'ParentT&gt;" Usage="iWithAaaaRecordIPv6Address.WithIPv6Address ipv6Address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithAaaaRecordIPv6AddressOrAttachable&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipv6Address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipv6Address">IPv6 アドレス。</param>
        <summary>
            このレコード セット内の指定された IPv6 アドレスを持つ AAAA レコードを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>