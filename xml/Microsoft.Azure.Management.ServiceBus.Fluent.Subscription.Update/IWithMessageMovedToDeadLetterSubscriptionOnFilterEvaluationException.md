<Type Name="IWithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException">
  <TypeSignature Language="C#" Value="public interface IWithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException" />
  <TypeSignature Language="F#" Value="type IWithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="58361-101">フィルターの評価に失敗しましたが、メッセージをセカンダリの配信不能メッセージ サブスクリプションに移動できるかどうかを指定できるようにサブスクリプション定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="58361-101">The stage of the subscription definition allowing to specify whether message those are failed on filter evaluation can be moved to secondary dead-letter subscription.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException.WithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate" Usage="iWithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException.WithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="58361-102">そのフィルターの評価に失敗しましたメッセージは、配信不能メッセージのサブスクリプションに移動する必要がありますを指定します。</span><span class="sxs-lookup"><span data-stu-id="58361-102">Specifies that filter evaluation failed message must be moved to dead-letter subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="58361-103">サブスクリプションの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="58361-103">The next stage of subscription update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithoutMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithoutMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException.WithoutMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate" Usage="iWithMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException.WithoutMessageMovedToDeadLetterSubscriptionOnFilterEvaluationException " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="58361-104">そのフィルターの評価に失敗メッセージを配信不能メッセージのサブスクリプションに移動してはなりませんを指定します。</span><span class="sxs-lookup"><span data-stu-id="58361-104">Specifies that filter evaluation failed message should not be moved to dead-letter subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="58361-105">サブスクリプションの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="58361-105">The next stage of subscription update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>