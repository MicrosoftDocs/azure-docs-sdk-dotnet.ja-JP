<Type Name="IWithMXRecordMailExchange&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMXRecordMailExchange&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithMXRecordMailExchange&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMXRecordMailExchange`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMXRecordMailExchange`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMXRecordMailExchange(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithMXRecordMailExchange&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="68d1f-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="68d1f-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="68d1f-102">MX レコードのステージでは、定義を最初の MX レコードを追加する許可を設定します。</span><span class="sxs-lookup"><span data-stu-id="68d1f-102">The stage of the MX record set definition allowing to add first MX record.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMailExchange">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMXRecordMailExchangeOrAttachable&lt;ParentT&gt; WithMailExchange (string mailExchangeHostName, int priority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMXRecordMailExchangeOrAttachable`1&lt;!ParentT&gt; WithMailExchange(string mailExchangeHostName, int32 priority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMXRecordMailExchange`1.WithMailExchange(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMailExchange (mailExchangeHostName As String, priority As Integer) As IWithMXRecordMailExchangeOrAttachable(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithMailExchange : string * int -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMXRecordMailExchangeOrAttachable&lt;'ParentT&gt;" Usage="iWithMXRecordMailExchange.WithMailExchange (mailExchangeHostName, priority)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMXRecordMailExchangeOrAttachable&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mailExchangeHostName" Type="System.String" />
        <Parameter Name="priority" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="mailExchangeHostName"><span data-ttu-id="68d1f-103">メール サーバーのホスト名。</span><span class="sxs-lookup"><span data-stu-id="68d1f-103">The host name of the mail exchange server.</span></span></param>
        <param name="priority"><span data-ttu-id="68d1f-104">メール exchange ホストの優先順位は、値より大きい値に優先順位を下げます。</span><span class="sxs-lookup"><span data-stu-id="68d1f-104">The priority for the mail exchange host, lower the value higher the priority.</span></span></param>
        <summary>
            <span data-ttu-id="68d1f-105">作成し、このレコード セット内の指定されたメールの exchange server との MX レコードに優先順位を割り当てます。</span><span class="sxs-lookup"><span data-stu-id="68d1f-105">Creates and assigns priority to a MX record with the provided mail exchange server in this record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="68d1f-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="68d1f-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>