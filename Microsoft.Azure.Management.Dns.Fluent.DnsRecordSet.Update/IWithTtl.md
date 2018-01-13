<Type Name="IWithTtl" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithTtl">
  <TypeSignature Language="C#" Value="public interface IWithTtl" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTtl" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithTtl" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTtl" />
  <TypeSignature Language="F#" Value="type IWithTtl = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            レコードのステージでは、更新プログラムがこのレコード セット内のレコードの TTL を指定する許可を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTimeToLive">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate WithTimeToLive (long ttlInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate WithTimeToLive(int64 ttlInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithTtl.WithTimeToLive(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTimeToLive (ttlInSeconds As Long) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithTimeToLive : int64 -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate" Usage="iWithTtl.WithTimeToLive ttlInSeconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ttlInSeconds" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="ttlInSeconds">秒単位で TTL です。</param>
        <summary>
            レコード セット内のレコードの TTL を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>レコードの次のステージでは、更新プログラムを設定します。</return>
      </Docs>
    </Member>
  </Members>
</Type>