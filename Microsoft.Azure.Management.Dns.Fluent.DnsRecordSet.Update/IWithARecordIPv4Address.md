<Type Name="IWithARecordIPv4Address" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithARecordIPv4Address">
  <TypeSignature Language="C#" Value="public interface IWithARecordIPv4Address" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithARecordIPv4Address" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithARecordIPv4Address" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithARecordIPv4Address" />
  <TypeSignature Language="F#" Value="type IWithARecordIPv4Address = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="89e30-101">A レコードのステージでは、追加またはレコードを削除する更新プログラムを許可するを設定します。</span><span class="sxs-lookup"><span data-stu-id="89e30-101">The stage of the A record set update allowing to add or remove A record.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIPv4Address">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet WithIPv4Address (string ipv4Address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet WithIPv4Address(string ipv4Address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithARecordIPv4Address.WithIPv4Address(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIPv4Address (ipv4Address As String) As IUpdateARecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithIPv4Address : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet" Usage="iWithARecordIPv4Address.WithIPv4Address ipv4Address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipv4Address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipv4Address"><span data-ttu-id="89e30-102">IPv4 アドレス。</span><span class="sxs-lookup"><span data-stu-id="89e30-102">An IPv4 address.</span></span></param>
        <summary>
            <span data-ttu-id="89e30-103">レコード セットで指定された IPv4 アドレスを使って、A レコードを作成します。</span><span class="sxs-lookup"><span data-stu-id="89e30-103">Creates an A record with the provided IPv4 address in the record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="89e30-104">レコードの次のステージでは、更新プログラムを設定します。</span><span class="sxs-lookup"><span data-stu-id="89e30-104">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutIPv4Address">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet WithoutIPv4Address (string ipv4Address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet WithoutIPv4Address(string ipv4Address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithARecordIPv4Address.WithoutIPv4Address(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutIPv4Address (ipv4Address As String) As IUpdateARecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithoutIPv4Address : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet" Usage="iWithARecordIPv4Address.WithoutIPv4Address ipv4Address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipv4Address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipv4Address"><span data-ttu-id="89e30-105">IPv4 アドレス。</span><span class="sxs-lookup"><span data-stu-id="89e30-105">An IPv4 address.</span></span></param>
        <summary>
            <span data-ttu-id="89e30-106">レコード セットから提供された IPv4 アドレスを使って、A レコードを削除します。</span><span class="sxs-lookup"><span data-stu-id="89e30-106">Removes the A record with the provided IPv4 address from the record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="89e30-107">レコードの次のステージでは、更新プログラムを設定します。</span><span class="sxs-lookup"><span data-stu-id="89e30-107">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>