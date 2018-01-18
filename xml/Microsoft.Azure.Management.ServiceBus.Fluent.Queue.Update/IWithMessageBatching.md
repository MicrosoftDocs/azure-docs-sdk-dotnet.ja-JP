<Type Name="IWithMessageBatching" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithMessageBatching">
  <TypeSignature Language="C#" Value="public interface IWithMessageBatching" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMessageBatching" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithMessageBatching" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMessageBatching" />
  <TypeSignature Language="F#" Value="type IWithMessageBatching = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="193a5-101">許可するキューの定義のステージでは、メッセージの動作をバッチ処理を構成します。</span><span class="sxs-lookup"><span data-stu-id="193a5-101">The stage of the queue definition allowing configure message batching behaviour.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMessageBatching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithMessageBatching ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithMessageBatching() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithMessageBatching.WithMessageBatching" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMessageBatching () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithMessageBatching : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithMessageBatching.WithMessageBatching " />
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
            <span data-ttu-id="193a5-102">内部ストアからへのメッセージまたは削除するメッセージを記述、ときに、Service Bus に複数のメッセージをバッチできますを指定します。</span><span class="sxs-lookup"><span data-stu-id="193a5-102">Specifies that Service Bus can batch multiple message when it write messages to or delete messages from it's internal store.</span></span> <span data-ttu-id="193a5-103">これにより、スループットが向上します。</span><span class="sxs-lookup"><span data-stu-id="193a5-103">This increases the throughput.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="193a5-104">キュー更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="193a5-104">The next stage of queue update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutMessageBatching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithoutMessageBatching ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithoutMessageBatching() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithMessageBatching.WithoutMessageBatching" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMessageBatching () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutMessageBatching : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithMessageBatching.WithoutMessageBatching " />
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
            <span data-ttu-id="193a5-105">メッセージのバッチ処理するメッセージの Service Bus の書き込み時に無効にする必要があるか指定します内部ストアからメッセージを削除します。</span><span class="sxs-lookup"><span data-stu-id="193a5-105">Specifies that batching of messages should be disabled when Service Bus write messages to or delete messages from it's internal store.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="193a5-106">キュー更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="193a5-106">The next stage of queue update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>