<Type Name="IWithQueue" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Definition.IWithQueue">
  <TypeSignature Language="C#" Value="public interface IWithQueue" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithQueue" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Definition.IWithQueue" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithQueue" />
  <TypeSignature Language="F#" Value="type IWithQueue = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0a34a-101">名前空間に新しいキューに追加するを許可する Service Bus 名前空間の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="0a34a-101">The stage of the Service Bus namespace definition allowing to add a new queue in the namespace.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewQueue">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Definition.IWithCreate WithNewQueue (string name, int maxSizeInMB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Definition.IWithCreate WithNewQueue(string name, int32 maxSizeInMB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Definition.IWithQueue.WithNewQueue(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewQueue (name As String, maxSizeInMB As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewQueue : string * int -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Definition.IWithCreate" Usage="iWithQueue.WithNewQueue (name, maxSizeInMB)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="maxSizeInMB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="0a34a-102">キューの名前です。</span><span class="sxs-lookup"><span data-stu-id="0a34a-102">Queue name.</span></span></param>
        <param name="maxSizeInMB"><span data-ttu-id="0a34a-103">キュー エンティティに割り当てられたメモリの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="0a34a-103">Maximum size of memory allocated for the queue entity.</span></span></param>
        <summary>
            <span data-ttu-id="0a34a-104">Service Bus 名前空間のキュー エンティティを作成します。</span><span class="sxs-lookup"><span data-stu-id="0a34a-104">Creates a queue entity in the Service Bus namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0a34a-105">Service Bus 名前空間の定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0a34a-105">Next stage of the Service Bus namespace definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>