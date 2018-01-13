<Type Name="IWithMXRecordMailExchange" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithMXRecordMailExchange">
  <TypeSignature Language="C#" Value="public interface IWithMXRecordMailExchange" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMXRecordMailExchange" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithMXRecordMailExchange" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMXRecordMailExchange" />
  <TypeSignature Language="F#" Value="type IWithMXRecordMailExchange = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            MX レコードのステージでは、定義を追加または MX レコードを削除する許可を設定します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMailExchange">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet WithMailExchange (string mailExchangeHostName, int priority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet WithMailExchange(string mailExchangeHostName, int32 priority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithMXRecordMailExchange.WithMailExchange(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMailExchange (mailExchangeHostName As String, priority As Integer) As IUpdateMXRecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithMailExchange : string * int -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet" Usage="iWithMXRecordMailExchange.WithMailExchange (mailExchangeHostName, priority)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mailExchangeHostName" Type="System.String" />
        <Parameter Name="priority" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="mailExchangeHostName">メール サーバーのホスト名。</param>
        <param name="priority">メール exchange ホストの優先順位は、値より大きい値に優先順位を下げます。</param>
        <summary>
            作成し、このレコード セット内の指定されたメールの exchange server との MX レコードに優先順位を割り当てます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>レコードの次のステージでは、更新プログラムを設定します。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutMailExchange">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet WithoutMailExchange (string mailExchangeHostName, int priority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet WithoutMailExchange(string mailExchangeHostName, int32 priority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithMXRecordMailExchange.WithoutMailExchange(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMailExchange (mailExchangeHostName As String, priority As Integer) As IUpdateMXRecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithoutMailExchange : string * int -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet" Usage="iWithMXRecordMailExchange.WithoutMailExchange (mailExchangeHostName, priority)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mailExchangeHostName" Type="System.String" />
        <Parameter Name="priority" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="mailExchangeHostName">メール サーバーのホスト名。</param>
        <param name="priority">メール exchange ホストの優先順位は、値より大きい値に優先順位を下げます。</param>
        <summary>
            このレコード セットから、指定されたメールの exchange サーバーと優先順位で MX レコードを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>レコードの次のステージでは、更新プログラムを設定します。</return>
      </Docs>
    </Member>
  </Members>
</Type>