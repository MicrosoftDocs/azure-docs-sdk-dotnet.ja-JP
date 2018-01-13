<Type Name="IWithExpiredMessageMovedToDeadLetterSubscription" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithExpiredMessageMovedToDeadLetterSubscription">
  <TypeSignature Language="C#" Value="public interface IWithExpiredMessageMovedToDeadLetterSubscription" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExpiredMessageMovedToDeadLetterSubscription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithExpiredMessageMovedToDeadLetterSubscription" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExpiredMessageMovedToDeadLetterSubscription" />
  <TypeSignature Language="F#" Value="type IWithExpiredMessageMovedToDeadLetterSubscription = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            セカンダリの配信不能メッセージ サブスクリプションに期限切れのメッセージを移動できるかどうかを指定する許可するサブスクリプションの更新の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExpiredMessageMovedToDeadLetterSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithExpiredMessageMovedToDeadLetterSubscription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithExpiredMessageMovedToDeadLetterSubscription() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithExpiredMessageMovedToDeadLetterSubscription.WithExpiredMessageMovedToDeadLetterSubscription" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExpiredMessageMovedToDeadLetterSubscription () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExpiredMessageMovedToDeadLetterSubscription : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate" Usage="iWithExpiredMessageMovedToDeadLetterSubscription.WithExpiredMessageMovedToDeadLetterSubscription " />
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
            その有効期限が切れたメッセージは、配信不能メッセージのサブスクリプションに移動する必要がありますを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>サブスクリプションの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutExpiredMessageMovedToDeadLetterSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithoutExpiredMessageMovedToDeadLetterSubscription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithoutExpiredMessageMovedToDeadLetterSubscription() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithExpiredMessageMovedToDeadLetterSubscription.WithoutExpiredMessageMovedToDeadLetterSubscription" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutExpiredMessageMovedToDeadLetterSubscription () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutExpiredMessageMovedToDeadLetterSubscription : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate" Usage="iWithExpiredMessageMovedToDeadLetterSubscription.WithoutExpiredMessageMovedToDeadLetterSubscription " />
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
            その有効期限が切れたメッセージを配信不能メッセージのサブスクリプションに移動してはなりませんを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>サブスクリプションの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>