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
            <span data-ttu-id="0dae1-101">AAAA レコードのステージでは、更新を追加または AAAA レコードを削除する許可を設定します。</span><span class="sxs-lookup"><span data-stu-id="0dae1-101">The stage of the AAAA record set update allowing to add or remove AAAA record.</span></span>
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
        <param name="ipv6Address"><span data-ttu-id="0dae1-102">IPv6 アドレス。</span><span class="sxs-lookup"><span data-stu-id="0dae1-102">The IPv6 address.</span></span></param>
        <summary>
            <span data-ttu-id="0dae1-103">このレコード セット内の指定された IPv6 アドレスを持つ AAAA レコードを作成します。</span><span class="sxs-lookup"><span data-stu-id="0dae1-103">Creates an AAAA record with the provided IPv6 address in this record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0dae1-104">レコードの次のステージでは、更新プログラムを設定します。</span><span class="sxs-lookup"><span data-stu-id="0dae1-104">The next stage of the record set update.</span></span></return>
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
        <param name="ipv6Address"><span data-ttu-id="0dae1-105">IPv6 アドレス。</span><span class="sxs-lookup"><span data-stu-id="0dae1-105">The IPv6 address.</span></span></param>
        <summary>
            <span data-ttu-id="0dae1-106">このレコード セットから指定された IPv6 アドレスを持つ AAAA レコードを削除します。</span><span class="sxs-lookup"><span data-stu-id="0dae1-106">Removes an AAAA record with the provided IPv6 address from this record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0dae1-107">レコードの次のステージでは、更新プログラムを設定します。</span><span class="sxs-lookup"><span data-stu-id="0dae1-107">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>