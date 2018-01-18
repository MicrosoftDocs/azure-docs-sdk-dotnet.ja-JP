<Type Name="ITopicClient" FullName="Microsoft.Azure.ServiceBus.ITopicClient">
  <TypeSignature Language="C#" Value="public interface ITopicClient : Microsoft.Azure.ServiceBus.Core.ISenderClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITopicClient implements class Microsoft.Azure.ServiceBus.Core.ISenderClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ITopicClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITopicClient&#xA;Implements ISenderClient" />
  <TypeSignature Language="F#" Value="type ITopicClient = interface&#xA;    interface ISenderClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.ISenderClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="16077-101">TopicClient を Service Bus トピックのすべての基本的な通信に使用できます。</span><span class="sxs-lookup"><span data-stu-id="16077-101">TopicClient can be used for all basic interactions with a Service Bus topic.</span></span>
             </summary>
    <remarks>To be added.</remarks>
    <example>
      <code>
            
             <span data-ttu-id="16077-102">TopicClient ITopicClient myTopicClient を作成する新しい TopicClient (serviceBusConnectionString、topicName); を =</span><span class="sxs-lookup"><span data-stu-id="16077-102">// Create the TopicClient ITopicClient myTopicClient = new TopicClient( serviceBusConnectionString, topicName);</span></span>
             
                 <span data-ttu-id="16077-103">/トピックにメッセージを送信する///\* \* \*</span><span class="sxs-lookup"><span data-stu-id="16077-103">//******************************************************************************** //                          Sending messages to a Topic //********************************************************************************</span></span>
                 
            <span data-ttu-id="16077-104">メッセージ ボックスの一覧を送信&lt;byte[]&gt;問題 GetIssues(); = (var 問題に関連した問題) foreach {myTopicClient.SendAsync (新しい Message(issue));}</span><span class="sxs-lookup"><span data-stu-id="16077-104">// Send messages List &lt;byte[]&gt; Issues = GetIssues(); foreach (var issue in Issues) { myTopicClient.SendAsync(new Message(issue)); }</span></span>
             </code>
    </example>
    <example>
             <span data-ttu-id="16077-105">新しい TopicClient を作成します。</span><span class="sxs-lookup"><span data-stu-id="16077-105">Create a new TopicClient</span></span>
             <code>
             ITopicClient topicClient = new TopicClient(
                 namespaceConnectionString,
                 topicName,
                 RetryExponential);
             </code>
            
             <span data-ttu-id="16077-106">トピックにメッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="16077-106">Send a message to the topic:</span></span>
             <code>
             byte[] data = GetData();
             await topicClient.SendAsync(data);
             </code></example>
  </Docs>
  <Members>
    <Member MemberName="TopicName">
      <MemberSignature Language="C#" Value="public string TopicName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ITopicClient.TopicName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TopicName As String" />
      <MemberSignature Language="F#" Value="member this.TopicName : string" Usage="Microsoft.Azure.ServiceBus.ITopicClient.TopicName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16077-107">トピックの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="16077-107">Gets the name of the topic.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>