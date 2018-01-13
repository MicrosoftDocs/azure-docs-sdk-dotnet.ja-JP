<Type Name="IEventProcessorFactory" FullName="Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory">
  <TypeSignature Language="C#" Value="public interface IEventProcessorFactory" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IEventProcessorFactory" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory" />
  <TypeSignature Language="VB.NET" Value="Public Interface IEventProcessorFactory" />
  <TypeSignature Language="F#" Value="type IEventProcessorFactory = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            イベント プロセッサ ファクトリ クラスで実装する必要がありますのあるインターフェイスです。
            
            <para>だけを持つ新しいパラメーターなしのコンス トラクターのよりも多く作業が必要なイベント プロセッサ オブジェクトを作成する場合は、ユーザー指定のファクトリが必要です。</para></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateEventProcessor">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.EventHubs.Processor.IEventProcessor CreateEventProcessor (Microsoft.Azure.EventHubs.Processor.PartitionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.EventHubs.Processor.IEventProcessor CreateEventProcessor(class Microsoft.Azure.EventHubs.Processor.PartitionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.IEventProcessorFactory.CreateEventProcessor(Microsoft.Azure.EventHubs.Processor.PartitionContext)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventProcessor (context As PartitionContext) As IEventProcessor" />
      <MemberSignature Language="F#" Value="abstract member CreateEventProcessor : Microsoft.Azure.EventHubs.Processor.PartitionContext -&gt; Microsoft.Azure.EventHubs.Processor.IEventProcessor" Usage="iEventProcessorFactory.CreateEventProcessor context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.Processor.IEventProcessor</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.Azure.EventHubs.Processor.PartitionContext" />
      </Parameters>
      <Docs>
        <param name="context">パーティションのコンテキスト情報。</param>
        <summary>
            インスタンスを作成するメソッド<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />パーティションを指定します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> のインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>