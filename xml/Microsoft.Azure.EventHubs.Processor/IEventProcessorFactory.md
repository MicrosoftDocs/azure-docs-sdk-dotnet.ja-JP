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
            <span data-ttu-id="8f102-101">イベント プロセッサ ファクトリ クラスで実装する必要がありますのあるインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="8f102-101">Interface that must be implemented by an event processor factory class.</span></span>
            
            <span data-ttu-id="8f102-102"><para>だけを持つ新しいパラメーターなしのコンス トラクターのよりも多く作業が必要なイベント プロセッサ オブジェクトを作成する場合は、ユーザー指定のファクトリが必要です。</para></span><span class="sxs-lookup"><span data-stu-id="8f102-102"><para>User-provided factories are needed if creating an event processor object requires more work than just a new with a parameterless constructor.</para></span></span></summary>
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
        <param name="context"><span data-ttu-id="8f102-103">パーティションのコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="8f102-103">Partition context information.</span></span></param>
        <summary>
            <span data-ttu-id="8f102-104">インスタンスを作成するメソッド<see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />パーティションを指定します。</span><span class="sxs-lookup"><span data-stu-id="8f102-104">Method to create instance of <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> given a partition.</span></span>
            </summary>
        <returns><span data-ttu-id="8f102-105"><see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="8f102-105">An instance of <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>