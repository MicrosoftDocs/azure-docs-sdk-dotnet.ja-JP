<Type Name="IEventProcessorFactory" FullName="Microsoft.ServiceBus.Messaging.IEventProcessorFactory">
  <TypeSignature Language="C#" Value="public interface IEventProcessorFactory" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IEventProcessorFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />
  <TypeSignature Language="VB.NET" Value="Public Interface IEventProcessorFactory" />
  <TypeSignature Language="F#" Value="type IEventProcessorFactory = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>インスタンスを作成するファクトリを提供するインターフェイスを<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</summary>
    <remarks>複数の事前方法を作成する必要がある場合にファクトリを使用して<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。 それ以外の場合、イベント プロセッサの種類だけを指定する EventHubConsumerGroup.RegisterProcessor を使用することができます。</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateEventProcessor">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.IEventProcessor CreateEventProcessor (Microsoft.ServiceBus.Messaging.PartitionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.IEventProcessor CreateEventProcessor(class Microsoft.ServiceBus.Messaging.PartitionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.IEventProcessorFactory.CreateEventProcessor(Microsoft.ServiceBus.Messaging.PartitionContext)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventProcessor (context As PartitionContext) As IEventProcessor" />
      <MemberSignature Language="F#" Value="abstract member CreateEventProcessor : Microsoft.ServiceBus.Messaging.PartitionContext -&gt; Microsoft.ServiceBus.Messaging.IEventProcessor" Usage="iEventProcessorFactory.CreateEventProcessor context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.IEventProcessor</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.ServiceBus.Messaging.PartitionContext" />
      </Parameters>
      <Docs>
        <param name="context">パーティションのコンテキスト情報。</param>
        <summary>指定したパーティションには、イベント プロセッサの新しいインスタンスを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> のインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>