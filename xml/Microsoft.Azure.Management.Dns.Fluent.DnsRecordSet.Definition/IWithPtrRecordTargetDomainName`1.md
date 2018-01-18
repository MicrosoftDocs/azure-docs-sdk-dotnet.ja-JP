<Type Name="IWithPtrRecordTargetDomainName&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithPtrRecordTargetDomainName&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPtrRecordTargetDomainName&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPtrRecordTargetDomainName`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithPtrRecordTargetDomainName`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPtrRecordTargetDomainName(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithPtrRecordTargetDomainName&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="a53d1-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="a53d1-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="a53d1-102">PTR レコードのステージでは、定義を最初の CNAME レコードを追加する許可を設定します。</span><span class="sxs-lookup"><span data-stu-id="a53d1-102">The stage of the PTR record set definition allowing to add first CNAME record.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTargetDomainName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithPtrRecordTargetDomainNameOrAttachable&lt;ParentT&gt; WithTargetDomainName (string targetDomainName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithPtrRecordTargetDomainNameOrAttachable`1&lt;!ParentT&gt; WithTargetDomainName(string targetDomainName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithPtrRecordTargetDomainName`1.WithTargetDomainName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTargetDomainName (targetDomainName As String) As IWithPtrRecordTargetDomainNameOrAttachable(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTargetDomainName : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithPtrRecordTargetDomainNameOrAttachable&lt;'ParentT&gt;" Usage="iWithPtrRecordTargetDomainName.WithTargetDomainName targetDomainName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithPtrRecordTargetDomainNameOrAttachable&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="targetDomainName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetDomainName"><span data-ttu-id="a53d1-103">対象のドメイン名。</span><span class="sxs-lookup"><span data-stu-id="a53d1-103">The target domain name.</span></span></param>
        <summary>
            <span data-ttu-id="a53d1-104">このレコード セットで指定されたターゲットのドメイン名での PTR レコードを作成します。</span><span class="sxs-lookup"><span data-stu-id="a53d1-104">Creates a PTR record with the provided target domain name in this record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a53d1-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="a53d1-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>