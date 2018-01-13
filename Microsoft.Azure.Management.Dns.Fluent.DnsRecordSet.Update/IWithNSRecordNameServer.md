<Type Name="IWithNSRecordNameServer" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithNSRecordNameServer">
  <TypeSignature Language="C#" Value="public interface IWithNSRecordNameServer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNSRecordNameServer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithNSRecordNameServer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNSRecordNameServer" />
  <TypeSignature Language="F#" Value="type IWithNSRecordNameServer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            NS レコード セットの定義を許可するを追加または削除の NS レコードの段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNameServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet WithNameServer (string nameServerHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet WithNameServer(string nameServerHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithNSRecordNameServer.WithNameServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNameServer (nameServerHostName As String) As IUpdateNSRecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithNameServer : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet" Usage="iWithNSRecordNameServer.WithNameServer nameServerHostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nameServerHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nameServerHostName">サーバーの名前のホスト名です。</param>
        <summary>
            このレコード セットで指定された名前のサーバーを NS レコードを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>レコードの次のステージでは、更新プログラムを設定します。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutNameServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet WithoutNameServer (string nameServerHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet WithoutNameServer(string nameServerHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithNSRecordNameServer.WithoutNameServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutNameServer (nameServerHostName As String) As IUpdateNSRecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithoutNameServer : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet" Usage="iWithNSRecordNameServer.WithoutNameServer nameServerHostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nameServerHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nameServerHostName">サーバーの名前のホスト名です。</param>
        <summary>
            Rmoves このレコードから指定された名前のサーバーとの NS レコードを設定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>レコードの次のステージでは、更新プログラムを設定します。</return>
      </Docs>
    </Member>
  </Members>
</Type>