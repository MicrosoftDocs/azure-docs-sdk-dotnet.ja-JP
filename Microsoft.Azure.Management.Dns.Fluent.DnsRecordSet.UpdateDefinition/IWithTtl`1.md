<Type Name="IWithTtl&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithTtl&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithTtl&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTtl`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithTtl`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTtl(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithTtl&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="9452c-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="9452c-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="9452c-102">レコードのステージでは、定義がこのレコード セット内のレコードの TTL を指定する許可を設定します。</span><span class="sxs-lookup"><span data-stu-id="9452c-102">The stage of the record set definition allowing to specify TTL for the records in this record set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTimeToLive">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithTimeToLive (long ttlInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithTimeToLive(int64 ttlInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithTtl`1.WithTimeToLive(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTimeToLive (ttlInSeconds As Long) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTimeToLive : int64 -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithTtl.WithTimeToLive ttlInSeconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ttlInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="ttlInSeconds"><span data-ttu-id="9452c-103">秒単位で TTL です。</span><span class="sxs-lookup"><span data-stu-id="9452c-103">TTL in seconds.</span></span></param>
        <summary>
            <span data-ttu-id="9452c-104">レコード セット内のレコードの TTL を指定します。</span><span class="sxs-lookup"><span data-stu-id="9452c-104">Specifies the TTL for the records in the record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9452c-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="9452c-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>