<Type Name="IWithDefaultMessageTTL" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithDefaultMessageTTL">
  <TypeSignature Language="C#" Value="public interface IWithDefaultMessageTTL" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDefaultMessageTTL" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithDefaultMessageTTL" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDefaultMessageTTL" />
  <TypeSignature Language="F#" Value="type IWithDefaultMessageTTL = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="22405-101">メッセージの TTL の既定値を定義できるようにトピックの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="22405-101">The stage of the topic definition allowing to define default TTL for messages.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDefaultMessageTTL">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate WithDefaultMessageTTL (TimeSpan ttl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate WithDefaultMessageTTL(valuetype System.TimeSpan ttl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithDefaultMessageTTL.WithDefaultMessageTTL(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDefaultMessageTTL (ttl As TimeSpan) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDefaultMessageTTL : TimeSpan -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate" Usage="iWithDefaultMessageTTL.WithDefaultMessageTTL ttl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Topic.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ttl" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="ttl"><span data-ttu-id="22405-102">ライブの期間を時間です。</span><span class="sxs-lookup"><span data-stu-id="22405-102">Time to live duration.</span></span></param>
        <summary>
            <span data-ttu-id="22405-103">メッセージが切れるまでの期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="22405-103">Specifies the duration after which the message expires.</span></span>
            <span data-ttu-id="22405-104">注: これが明示的にオーバーライドされない限り、既定の ttl は無期限 (TimeSpan.Max)。</span><span class="sxs-lookup"><span data-stu-id="22405-104">Note: unless it is explicitly overridden the default ttl is infinite (TimeSpan.Max).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="22405-105">トピックの定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="22405-105">The next stage of topic definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>