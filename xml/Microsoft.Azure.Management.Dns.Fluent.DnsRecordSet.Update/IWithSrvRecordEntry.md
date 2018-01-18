<Type Name="IWithSrvRecordEntry" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSrvRecordEntry">
  <TypeSignature Language="C#" Value="public interface IWithSrvRecordEntry" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSrvRecordEntry" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSrvRecordEntry" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSrvRecordEntry" />
  <TypeSignature Language="F#" Value="type IWithSrvRecordEntry = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3706a-101">追加または削除するサービスのレコードを許可する SRV レコードの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="3706a-101">The stage of the SRV record definition allowing to add or remove service record.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutRecord">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSrvRecordSet.IUpdateSrvRecordSet WithoutRecord (string target, int port, int priority, int weight);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSrvRecordSet.IUpdateSrvRecordSet WithoutRecord(string target, int32 port, int32 priority, int32 weight) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSrvRecordEntry.WithoutRecord(System.String,System.Int32,System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutRecord (target As String, port As Integer, priority As Integer, weight As Integer) As IUpdateSrvRecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithoutRecord : string * int * int * int -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSrvRecordSet.IUpdateSrvRecordSet" Usage="iWithSrvRecordEntry.WithoutRecord (target, port, priority, weight)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSrvRecordSet.IUpdateSrvRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="port" Type="System.Int32" />
        <Parameter Name="priority" Type="System.Int32" />
        <Parameter Name="weight" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="target"><span data-ttu-id="3706a-102">サービスを実行して、ターゲット ホストの正規の名前。</span><span class="sxs-lookup"><span data-stu-id="3706a-102">The canonical name of the target host running the service.</span></span></param>
        <param name="port"><span data-ttu-id="3706a-103">サービスは範囲指定されたポートです。</span><span class="sxs-lookup"><span data-stu-id="3706a-103">The port on which the service is bounded.</span></span></param>
        <param name="priority"><span data-ttu-id="3706a-104">ターゲット ホストの優先度です。</span><span class="sxs-lookup"><span data-stu-id="3706a-104">The priority of the target host.</span></span></param>
        <param name="weight"><span data-ttu-id="3706a-105">レコードの相対的な重み (設定)。</span><span class="sxs-lookup"><span data-stu-id="3706a-105">The relative weight (preference) of the records.</span></span></param>
        <summary>
            <span data-ttu-id="3706a-106">サービスのサービスのレコードを削除します。</span><span class="sxs-lookup"><span data-stu-id="3706a-106">Removes a service record for a service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3706a-107">レコードの次のステージでは、更新プログラムを設定します。</span><span class="sxs-lookup"><span data-stu-id="3706a-107">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRecord">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSrvRecordSet.IUpdateSrvRecordSet WithRecord (string target, int port, int priority, int weight);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSrvRecordSet.IUpdateSrvRecordSet WithRecord(string target, int32 port, int32 priority, int32 weight) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithSrvRecordEntry.WithRecord(System.String,System.Int32,System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRecord (target As String, port As Integer, priority As Integer, weight As Integer) As IUpdateSrvRecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithRecord : string * int * int * int -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSrvRecordSet.IUpdateSrvRecordSet" Usage="iWithSrvRecordEntry.WithRecord (target, port, priority, weight)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSrvRecordSet.IUpdateSrvRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="port" Type="System.Int32" />
        <Parameter Name="priority" Type="System.Int32" />
        <Parameter Name="weight" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="target"><span data-ttu-id="3706a-108">サービスを実行して、ターゲット ホストの正規の名前。</span><span class="sxs-lookup"><span data-stu-id="3706a-108">The canonical name of the target host running the service.</span></span></param>
        <param name="port"><span data-ttu-id="3706a-109">サービスは範囲指定されたポートです。</span><span class="sxs-lookup"><span data-stu-id="3706a-109">The port on which the service is bounded.</span></span></param>
        <param name="priority"><span data-ttu-id="3706a-110">ターゲット ホストの優先度は、値より大きい値に優先順位を下げます。</span><span class="sxs-lookup"><span data-stu-id="3706a-110">The priority of the target host, lower the value higher the priority.</span></span></param>
        <param name="weight"><span data-ttu-id="3706a-111">同じ優先順位が、上位レコードの相対的な重み (優先) より優先順位の値。</span><span class="sxs-lookup"><span data-stu-id="3706a-111">The relative weight (preference) of the records with the same priority, higher the value more the preference.</span></span></param>
        <summary>
            <span data-ttu-id="3706a-112">サービスのサービスのレコードを指定します。</span><span class="sxs-lookup"><span data-stu-id="3706a-112">Specifies a service record for a service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3706a-113">レコードの次のステージでは、更新プログラムを設定します。</span><span class="sxs-lookup"><span data-stu-id="3706a-113">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>