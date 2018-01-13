<Type Name="IWithARecordIPv4Address&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithARecordIPv4Address&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithARecordIPv4Address&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithARecordIPv4Address`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithARecordIPv4Address`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithARecordIPv4Address(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithARecordIPv4Address&lt;'ParentT&gt; = interface" />
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
            A レコードのステージでは、定義を最初のレコードを追加する許可を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIPv4Address">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithARecordIPv4AddressOrAttachable&lt;ParentT&gt; WithIPv4Address (string ipv4Address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithARecordIPv4AddressOrAttachable`1&lt;!ParentT&gt; WithIPv4Address(string ipv4Address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithARecordIPv4Address`1.WithIPv4Address(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIPv4Address (ipv4Address As String) As IWithARecordIPv4AddressOrAttachable(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithIPv4Address : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithARecordIPv4AddressOrAttachable&lt;'ParentT&gt;" Usage="iWithARecordIPv4Address.WithIPv4Address ipv4Address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithARecordIPv4AddressOrAttachable&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipv4Address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipv4Address">IPv4 アドレスです。</param>
        <summary>
            このレコード セット内の指定された IPv4 アドレスを使って、A レコードを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>