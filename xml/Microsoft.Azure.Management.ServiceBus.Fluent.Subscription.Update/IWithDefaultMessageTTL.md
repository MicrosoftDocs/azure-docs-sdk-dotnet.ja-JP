<Type Name="IWithDefaultMessageTTL" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithDefaultMessageTTL">
  <TypeSignature Language="C#" Value="public interface IWithDefaultMessageTTL" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDefaultMessageTTL" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithDefaultMessageTTL" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDefaultMessageTTL" />
  <TypeSignature Language="F#" Value="type IWithDefaultMessageTTL = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0dbb5-101">メッセージの TTL の既定値を定義できるように、サブスクリプション定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="0dbb5-101">The stage of the subscription definition allowing to define default TTL for messages.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDefaultMessageTTL">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithDefaultMessageTTL (TimeSpan ttl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithDefaultMessageTTL(valuetype System.TimeSpan ttl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithDefaultMessageTTL.WithDefaultMessageTTL(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDefaultMessageTTL (ttl As TimeSpan) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDefaultMessageTTL : TimeSpan -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate" Usage="iWithDefaultMessageTTL.WithDefaultMessageTTL ttl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ttl" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="ttl"><span data-ttu-id="0dbb5-102">ライブの期間を時間です。</span><span class="sxs-lookup"><span data-stu-id="0dbb5-102">Time to live duration.</span></span></param>
        <summary>
            <span data-ttu-id="0dbb5-103">メッセージが切れるまでの期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="0dbb5-103">Specifies the duration after which the message expires.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="0dbb5-104">サブスクリプションの更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="0dbb5-104">The next stage of subscription update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>