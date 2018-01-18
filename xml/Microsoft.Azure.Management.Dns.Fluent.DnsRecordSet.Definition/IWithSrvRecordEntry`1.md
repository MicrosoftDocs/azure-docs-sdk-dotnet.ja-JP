<Type Name="IWithSrvRecordEntry&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithSrvRecordEntry&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSrvRecordEntry&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSrvRecordEntry`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithSrvRecordEntry`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSrvRecordEntry(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithSrvRecordEntry&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="9d724-101">WithAttach.attach() の戻り値の型。</span><span class="sxs-lookup"><span data-stu-id="9d724-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="9d724-102">サービスの最初のレコードを追加できるように SRV レコードの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="9d724-102">The stage of the SRV record definition allowing to add first service record.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRecord">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithSrvRecordEntryOrAttachable&lt;ParentT&gt; WithRecord (string target, int port, int priority, int weight);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithSrvRecordEntryOrAttachable`1&lt;!ParentT&gt; WithRecord(string target, int32 port, int32 priority, int32 weight) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithSrvRecordEntry`1.WithRecord(System.String,System.Int32,System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRecord (target As String, port As Integer, priority As Integer, weight As Integer) As IWithSrvRecordEntryOrAttachable(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithRecord : string * int * int * int -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithSrvRecordEntryOrAttachable&lt;'ParentT&gt;" Usage="iWithSrvRecordEntry.WithRecord (target, port, priority, weight)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithSrvRecordEntryOrAttachable&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="port" Type="System.Int32" />
        <Parameter Name="priority" Type="System.Int32" />
        <Parameter Name="weight" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="target"><span data-ttu-id="9d724-103">サービスを実行して、ターゲット ホストの正規の名前。</span><span class="sxs-lookup"><span data-stu-id="9d724-103">The canonical name of the target host running the service.</span></span></param>
        <param name="port"><span data-ttu-id="9d724-104">サービスは範囲指定されたポートです。</span><span class="sxs-lookup"><span data-stu-id="9d724-104">The port on which the service is bounded.</span></span></param>
        <param name="priority"><span data-ttu-id="9d724-105">ターゲット ホストの優先度は、値より大きい値に優先順位を下げます。</span><span class="sxs-lookup"><span data-stu-id="9d724-105">The priority of the target host, lower the value higher the priority.</span></span></param>
        <param name="weight"><span data-ttu-id="9d724-106">同じ優先順位が、上位レコードの相対的な重み (優先) より優先順位の値。</span><span class="sxs-lookup"><span data-stu-id="9d724-106">The relative weight (preference) of the records with the same priority, higher the value more the preference.</span></span></param>
        <summary>
            <span data-ttu-id="9d724-107">サービスのサービスのレコードを指定します。</span><span class="sxs-lookup"><span data-stu-id="9d724-107">Specifies a service record for a service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9d724-108">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="9d724-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>