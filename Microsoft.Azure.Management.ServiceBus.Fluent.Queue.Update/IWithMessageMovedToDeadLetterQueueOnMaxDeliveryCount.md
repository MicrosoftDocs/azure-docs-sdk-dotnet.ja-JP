<Type Name="IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount">
  <TypeSignature Language="C#" Value="public interface IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount" />
  <TypeSignature Language="F#" Value="type IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            配信不能キューに移動する前にメッセージの最大配信数を指定できるように、キューの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount (int deliveryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount(int32 deliveryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount.WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount (deliveryCount As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount : int -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithMessageMovedToDeadLetterQueueOnMaxDeliveryCount.WithMessageMovedToDeadLetterQueueOnMaxDeliveryCount deliveryCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deliveryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="deliveryCount">最大配信数。</param>
        <summary>
            メッセージを配信する最大回数を指定します。 この数を超えていると、メッセージは配信不能キューに移動されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>キュー更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>