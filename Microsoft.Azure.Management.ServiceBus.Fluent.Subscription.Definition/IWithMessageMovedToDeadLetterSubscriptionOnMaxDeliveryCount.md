<Type Name="IWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount">
  <TypeSignature Language="C#" Value="public interface IWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount" />
  <TypeSignature Language="F#" Value="type IWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="38c39-101">配信不能メッセージのサブスクリプションに移動する前にメッセージの最大配信数を指定できるように、サブスクリプション定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="38c39-101">The stage of the subscription definition allowing to specify maximum delivery count of message before moving it to dead-letter subscription.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate WithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount (int deliveryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate WithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount(int32 deliveryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount.WithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount (deliveryCount As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount : int -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate" Usage="iWithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount.WithMessageMovedToDeadLetterSubscriptionOnMaxDeliveryCount deliveryCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deliveryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="deliveryCount"><span data-ttu-id="38c39-102">最大配信数。</span><span class="sxs-lookup"><span data-stu-id="38c39-102">Maximum delivery count.</span></span></param>
        <summary>
            <span data-ttu-id="38c39-103">メッセージを配信する最大回数を指定します。</span><span class="sxs-lookup"><span data-stu-id="38c39-103">Specifies maximum number of times a message can be delivered.</span></span> <span data-ttu-id="38c39-104">この数を超えていると、メッセージは配信不能メッセージのサブスクリプションに移動されます。</span><span class="sxs-lookup"><span data-stu-id="38c39-104">Once this count has exceeded, message will be moved to dead-letter subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="38c39-105">サブスクリプション定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="38c39-105">The next stage of subscription definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>