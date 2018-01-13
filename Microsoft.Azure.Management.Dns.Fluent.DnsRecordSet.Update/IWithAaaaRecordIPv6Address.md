<Type Name="IWithAaaaRecordIPv6Address" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithAaaaRecordIPv6Address">
  <TypeSignature Language="C#" Value="public interface IWithAaaaRecordIPv6Address" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAaaaRecordIPv6Address" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithAaaaRecordIPv6Address" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAaaaRecordIPv6Address" />
  <TypeSignature Language="F#" Value="type IWithAaaaRecordIPv6Address = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            AAAA レコードのステージでは、更新を追加または AAAA レコードを削除する許可を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIPv6Address">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateAaaaRecordSet.IUpdateAaaaRecordSet WithIPv6Address (string ipv6Address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateAaaaRecordSet.IUpdateAaaaRecordSet WithIPv6Address(string ipv6Address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithAaaaRecordIPv6Address.WithIPv6Address(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIPv6Address (ipv6Address As String) As IUpdateAaaaRecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithIPv6Address : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateAaaaRecordSet.IUpdateAaaaRecordSet" Usage="iWithAaaaRecordIPv6Address.WithIPv6Address ipv6Address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateAaaaRecordSet.IUpdateAaaaRecordSet</ReturnType>
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
        <return>レコードの次のステージでは、更新プログラムを設定します。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutIPv6Address">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateAaaaRecordSet.IUpdateAaaaRecordSet WithoutIPv6Address (string ipv6Address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateAaaaRecordSet.IUpdateAaaaRecordSet WithoutIPv6Address(string ipv6Address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithAaaaRecordIPv6Address.WithoutIPv6Address(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutIPv6Address (ipv6Address As String) As IUpdateAaaaRecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithoutIPv6Address : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateAaaaRecordSet.IUpdateAaaaRecordSet" Usage="iWithAaaaRecordIPv6Address.WithoutIPv6Address ipv6Address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateAaaaRecordSet.IUpdateAaaaRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipv6Address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipv6Address">IPv6 アドレス。</param>
        <summary>
            このレコード セットから指定された IPv6 アドレスを持つ AAAA レコードを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>レコードの次のステージでは、更新プログラムを設定します。</return>
      </Docs>
    </Member>
  </Members>
</Type>