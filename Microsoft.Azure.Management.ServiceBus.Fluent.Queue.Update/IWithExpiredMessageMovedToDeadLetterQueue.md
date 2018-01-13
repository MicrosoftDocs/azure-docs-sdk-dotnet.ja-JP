<Type Name="IWithExpiredMessageMovedToDeadLetterQueue" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithExpiredMessageMovedToDeadLetterQueue">
  <TypeSignature Language="C#" Value="public interface IWithExpiredMessageMovedToDeadLetterQueue" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExpiredMessageMovedToDeadLetterQueue" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithExpiredMessageMovedToDeadLetterQueue" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExpiredMessageMovedToDeadLetterQueue" />
  <TypeSignature Language="F#" Value="type IWithExpiredMessageMovedToDeadLetterQueue = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b0cf7-101">セカンダリの配信不能キューに期限切れのメッセージを移動できるかどうかを指定できるように、キューの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="b0cf7-101">The stage of the queue definition allowing to specify whether expired message can be moved to secondary dead-letter queue.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExpiredMessageMovedToDeadLetterQueue">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithExpiredMessageMovedToDeadLetterQueue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithExpiredMessageMovedToDeadLetterQueue() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithExpiredMessageMovedToDeadLetterQueue.WithExpiredMessageMovedToDeadLetterQueue" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExpiredMessageMovedToDeadLetterQueue () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExpiredMessageMovedToDeadLetterQueue : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithExpiredMessageMovedToDeadLetterQueue.WithExpiredMessageMovedToDeadLetterQueue " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b0cf7-102">その有効期限が切れたメッセージは配信不能キューに移動する必要がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="b0cf7-102">Specifies that expired message must be moved to dead-letter queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b0cf7-103">キュー更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b0cf7-103">The next stage of queue update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutExpiredMessageMovedToDeadLetterQueue">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithoutExpiredMessageMovedToDeadLetterQueue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithoutExpiredMessageMovedToDeadLetterQueue() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithExpiredMessageMovedToDeadLetterQueue.WithoutExpiredMessageMovedToDeadLetterQueue" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutExpiredMessageMovedToDeadLetterQueue () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutExpiredMessageMovedToDeadLetterQueue : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithExpiredMessageMovedToDeadLetterQueue.WithoutExpiredMessageMovedToDeadLetterQueue " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b0cf7-104">その有効期限が切れたメッセージを配信不能キューに移動してはなりませんを指定します。</span><span class="sxs-lookup"><span data-stu-id="b0cf7-104">Specifies that expired message should not be moved to dead-letter queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b0cf7-105">キュー更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="b0cf7-105">The next stage of queue update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>