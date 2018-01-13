<Type Name="IEventProcessor" FullName="Microsoft.ServiceBus.Messaging.IEventProcessor">
  <TypeSignature Language="C#" Value="public interface IEventProcessor" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IEventProcessor" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />
  <TypeSignature Language="VB.NET" Value="Public Interface IEventProcessor" />
  <TypeSignature Language="F#" Value="type IEventProcessor = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>イベント プロセッサのメソッドを提供します。 アプリケーションでは、Event Hub からのイベントの処理を有効に、このインターフェイスを実装する必要があります。 このインターフェイスは、メインの機能拡張ポイント、EventProcessorHost と<see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager)" />です。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (Microsoft.ServiceBus.Messaging.PartitionContext context, Microsoft.ServiceBus.Messaging.CloseReason reason);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(class Microsoft.ServiceBus.Messaging.PartitionContext context, valuetype Microsoft.ServiceBus.Messaging.CloseReason reason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.IEventProcessor.CloseAsync(Microsoft.ServiceBus.Messaging.PartitionContext,Microsoft.ServiceBus.Messaging.CloseReason)" />
      <MemberSignature Language="VB.NET" Value="Public Function CloseAsync (context As PartitionContext, reason As CloseReason) As Task" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : Microsoft.ServiceBus.Messaging.PartitionContext * Microsoft.ServiceBus.Messaging.CloseReason -&gt; System.Threading.Tasks.Task" Usage="iEventProcessor.CloseAsync (context, reason)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.ServiceBus.Messaging.PartitionContext" />
        <Parameter Name="reason" Type="Microsoft.ServiceBus.Messaging.CloseReason" />
      </Parameters>
      <Docs>
        <param name="context">このプロセッサのインスタンスが動作するパーティションのパーティションの所有権情報です。 呼び出すことができます<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync" />Event Hub のストリームからメッセージの処理中のチェックポイントの進行状況をします。</param>
        <param name="reason">呼び出す理由<see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.CloseAsync(Microsoft.ServiceBus.Messaging.PartitionContext,Microsoft.ServiceBus.Messaging.CloseReason)" />です。</param>
        <summary>負荷分散のパーティションの所有権が別のノードに移動したときに呼び出されます目的、またはホストをシャット ダウンするとします。 応答と呼ばれる<see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessorAsync(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" />です。</summary>
        <returns> クローズ操作が完了したことを示すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OpenAsync (Microsoft.ServiceBus.Messaging.PartitionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OpenAsync(class Microsoft.ServiceBus.Messaging.PartitionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.IEventProcessor.OpenAsync(Microsoft.ServiceBus.Messaging.PartitionContext)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenAsync (context As PartitionContext) As Task" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : Microsoft.ServiceBus.Messaging.PartitionContext -&gt; System.Threading.Tasks.Task" Usage="iEventProcessor.OpenAsync context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.ServiceBus.Messaging.PartitionContext" />
      </Parameters>
      <Docs>
        <param name="context">このプロセッサのインスタンスが動作するパーティションの所有権情報です。 呼び出すしようとすると<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync" />の Open 操作中に失敗します。</param>
        <summary>Event Hub のプロセッサのインスタンスを初期化します。 このプロセッサのインスタンスに、イベント データが渡される前に、このメソッドが呼び出されます。</summary>
        <returns>このタスクは、オープン操作が完了したことを示します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessEventsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProcessEventsAsync (Microsoft.ServiceBus.Messaging.PartitionContext context, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ProcessEventsAsync(class Microsoft.ServiceBus.Messaging.PartitionContext context, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.IEventProcessor.ProcessEventsAsync(Microsoft.ServiceBus.Messaging.PartitionContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Function ProcessEventsAsync (context As PartitionContext, messages As IEnumerable(Of EventData)) As Task" />
      <MemberSignature Language="F#" Value="abstract member ProcessEventsAsync : Microsoft.ServiceBus.Messaging.PartitionContext * seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt; -&gt; System.Threading.Tasks.Task" Usage="iEventProcessor.ProcessEventsAsync (context, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.ServiceBus.Messaging.PartitionContext" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="context">このプロセッサのインスタンスが動作するパーティションの所有権情報です。</param>
        <param name="messages">Event Hubs のイベントのバッチです。</param>
        <summary>指定したコンテキストとメッセージを非同期的に処理します。 Event Hubs ストリーム内に新しいメッセージが存在する場合は、このメソッドが呼び出されます。 各バッチ内のすべてのイベントの処理を終了した場合にのみ、チェックポイントを確認してください。</summary>
        <returns>示すタスク<see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.ProcessEventsAsync(Microsoft.ServiceBus.Messaging.PartitionContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" />が完了しました。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>