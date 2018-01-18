<Type Name="IWithExpiredMessageMovedToDeadLetterQueue" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithExpiredMessageMovedToDeadLetterQueue">
  <TypeSignature Language="C#" Value="public interface IWithExpiredMessageMovedToDeadLetterQueue" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExpiredMessageMovedToDeadLetterQueue" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithExpiredMessageMovedToDeadLetterQueue" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExpiredMessageMovedToDeadLetterQueue" />
  <TypeSignature Language="F#" Value="type IWithExpiredMessageMovedToDeadLetterQueue = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9ef26-101">セカンダリの配信不能キューに期限切れのメッセージを移動できるかどうかを指定できるように、キューの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="9ef26-101">The stage of the queue definition allowing to specify whether expired message can be moved to secondary dead-letter queue.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExpiredMessageMovedToDeadLetterQueue">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithExpiredMessageMovedToDeadLetterQueue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithExpiredMessageMovedToDeadLetterQueue() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithExpiredMessageMovedToDeadLetterQueue.WithExpiredMessageMovedToDeadLetterQueue" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExpiredMessageMovedToDeadLetterQueue () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExpiredMessageMovedToDeadLetterQueue : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate" Usage="iWithExpiredMessageMovedToDeadLetterQueue.WithExpiredMessageMovedToDeadLetterQueue " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9ef26-102">その有効期限が切れたメッセージは配信不能キューに移動する必要がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="9ef26-102">Specifies that expired message must be moved to dead-letter queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9ef26-103">キュー定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="9ef26-103">The next stage of queue definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>