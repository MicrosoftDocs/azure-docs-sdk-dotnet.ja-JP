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
             TopicClient を Service Bus トピックのすべての基本的な通信に使用できます。
             </summary>
    <remarks>To be added.</remarks>
    <example>
      <code>
            
             TopicClient ITopicClient myTopicClient を作成する新しい TopicClient (serviceBusConnectionString、topicName); を =
             
                 /トピックにメッセージを送信する///* * *
                 
            メッセージ ボックスの一覧を送信&lt;byte[]&gt;問題 GetIssues(); = (var 問題に関連した問題) foreach {myTopicClient.SendAsync (新しい Message(issue));}
             </code>
    </example>
    <example>
             新しい TopicClient を作成します。
             <code>
             ITopicClient topicClient = new TopicClient(
                 namespaceConnectionString,
                 topicName,
                 RetryExponential);
             </code>
            
             トピックにメッセージを送信します。
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
            トピックの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>