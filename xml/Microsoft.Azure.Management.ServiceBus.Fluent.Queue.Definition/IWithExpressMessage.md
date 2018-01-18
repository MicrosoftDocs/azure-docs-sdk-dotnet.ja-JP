<Type Name="IWithExpressMessage" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithExpressMessage">
  <TypeSignature Language="C#" Value="public interface IWithExpressMessage" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExpressMessage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithExpressMessage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExpressMessage" />
  <TypeSignature Language="F#" Value="type IWithExpressMessage = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e918b-101">高速メッセージとしてメッセージを開封済みにできるようにする、キューの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="e918b-101">The stage of the queue definition allowing to mark messages as express messages.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExpressMessage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithExpressMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate WithExpressMessage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithExpressMessage.WithExpressMessage" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExpressMessage () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExpressMessage : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Definition.IWithCreate" Usage="iWithExpressMessage.WithExpressMessage " />
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
            <span data-ttu-id="e918b-102">このキューにメッセージがエクスプレスためしばらくの間メッセージング ストアに格納する前にメモリにキャッシュすることができますを指定します。</span><span class="sxs-lookup"><span data-stu-id="e918b-102">Specifies that messages in this queue are express hence they can be cached in memory for some time before storing it in messaging store.</span></span>
            <span data-ttu-id="e918b-103">注: 既定ではキュー express ではありません。</span><span class="sxs-lookup"><span data-stu-id="e918b-103">Note: By default queue is not express.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e918b-104">キュー定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e918b-104">The next stage of queue definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>