<Type Name="IWithTopic" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Definition.IWithTopic">
  <TypeSignature Language="C#" Value="public interface IWithTopic" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTopic" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Definition.IWithTopic" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTopic" />
  <TypeSignature Language="F#" Value="type IWithTopic = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="055c1-101">名前空間内の新しいトピックの追加を許可する Service Bus 名前空間の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="055c1-101">The stage of the Service Bus namespace definition allowing to add a new topic in the namespace.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewTopic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Definition.IWithCreate WithNewTopic (string name, int maxSizeInMB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Definition.IWithCreate WithNewTopic(string name, int32 maxSizeInMB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Definition.IWithTopic.WithNewTopic(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewTopic (name As String, maxSizeInMB As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewTopic : string * int -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusNamespace.Definition.IWithCreate" Usage="iWithTopic.WithNewTopic (name, maxSizeInMB)" />
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
        <param name="name"><span data-ttu-id="055c1-102">トピックの名前です。</span><span class="sxs-lookup"><span data-stu-id="055c1-102">Topic name.</span></span></param>
        <param name="maxSizeInMB"><span data-ttu-id="055c1-103">トピック エンティティに割り当てられたメモリの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="055c1-103">Maximum size of memory allocated for the topic entity.</span></span></param>
        <summary>
            <span data-ttu-id="055c1-104">Service Bus 名前空間にトピック エンティティを作成します。</span><span class="sxs-lookup"><span data-stu-id="055c1-104">Creates a topic entity in the Service Bus namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="055c1-105">Service Bus 名前空間の定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="055c1-105">Next stage of the Service Bus namespace definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>