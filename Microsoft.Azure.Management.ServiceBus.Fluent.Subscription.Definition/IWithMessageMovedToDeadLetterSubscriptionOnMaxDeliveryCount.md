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
            配信不能メッセージのサブスクリプションに移動する前にメッセージの最大配信数を指定できるように、サブスクリプション定義の段階です。
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
        <param name="deliveryCount">最大配信数。</param>
        <summary>
            メッセージを配信する最大回数を指定します。 この数を超えていると、メッセージは配信不能メッセージのサブスクリプションに移動されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>サブスクリプション定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>