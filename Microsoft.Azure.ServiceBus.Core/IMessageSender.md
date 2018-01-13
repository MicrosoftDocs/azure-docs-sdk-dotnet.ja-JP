<Type Name="IMessageSender" FullName="Microsoft.Azure.ServiceBus.Core.IMessageSender">
  <TypeSignature Language="C#" Value="public interface IMessageSender : Microsoft.Azure.ServiceBus.Core.ISenderClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMessageSender implements class Microsoft.Azure.ServiceBus.Core.ISenderClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Core.IMessageSender" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMessageSender&#xA;Implements ISenderClient" />
  <TypeSignature Language="F#" Value="type IMessageSender = interface&#xA;    interface ISenderClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
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
             キューまたはトピックにメッセージを送信、MessageSender を使用できます。
             </summary>
    <remarks>To be added.</remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.Core.MessageSender" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.QueueClient" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.TopicClient" />
    <example>
             キューに送信する新しい MessageSender を作成します。
             <code>
             IMessageSender messageSender = new MessageSender(
                 namespaceConnectionString,
                 queueName)
             </code>
            
             メッセージを送信する
             <code>
             byte[] data = GetData();
             await messageSender.SendAsync(data);
             </code></example>
  </Docs>
  <Members />
</Type>