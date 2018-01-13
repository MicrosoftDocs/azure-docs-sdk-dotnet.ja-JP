<Type Name="IEventProcessor" FullName="Microsoft.Azure.EventHubs.Processor.IEventProcessor">
  <TypeSignature Language="C#" Value="public interface IEventProcessor" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IEventProcessor" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" />
  <TypeSignature Language="VB.NET" Value="Public Interface IEventProcessor" />
  <TypeSignature Language="F#" Value="type IEventProcessor = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            イベント プロセッサ クラスで実装する必要があるインターフェイスです。
            
            <para>イベント プロセッサ クラスのインスタンスには、1 つのイベント ハブの 1 つのパーティションからのイベントのみが処理されます。PartitionContext は、いくつかのパラメーターが変更される可能性が同じパーティションは常に、イベント プロセッサへの各呼び出しで提供されます。</para><para>が EventProcessorHost はマルチ スレッド、OnError() を除き、イベント プロセッサ クラスの特定のインスタンスへの呼び出しがシリアル化します。OnEvents() を 0 回以上呼び出されるその OnOpen() が最初に、呼び出されます。イベント プロセッサ必要がある場合にシャット ダウンできないエラーがどこか、またはパーティションのリースが失われているか、プロセッサ全体のホストがシャット ダウンされているため、OnClose() が OnEvents() の最後の呼び出しが戻った後と呼ばれるかどうか。</para> <para>OnError() でした OnEvents() 中は呼び出せませんまたは OnClose() を実行します。可能性のあるデッドロックを回避するためには、同期は行われません。</para></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (Microsoft.Azure.EventHubs.Processor.PartitionContext context, Microsoft.Azure.EventHubs.Processor.CloseReason reason);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(class Microsoft.Azure.EventHubs.Processor.PartitionContext context, valuetype Microsoft.Azure.EventHubs.Processor.CloseReason reason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.IEventProcessor.CloseAsync(Microsoft.Azure.EventHubs.Processor.PartitionContext,Microsoft.Azure.EventHubs.Processor.CloseReason)" />
      <MemberSignature Language="VB.NET" Value="Public Function CloseAsync (context As PartitionContext, reason As CloseReason) As Task" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : Microsoft.Azure.EventHubs.Processor.PartitionContext * Microsoft.Azure.EventHubs.Processor.CloseReason -&gt; System.Threading.Tasks.Task" Usage="iEventProcessor.CloseAsync (context, reason)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.Azure.EventHubs.Processor.PartitionContext" />
        <Parameter Name="reason" Type="Microsoft.Azure.EventHubs.Processor.CloseReason" />
      </Parameters>
      <Docs>
        <param name="context">パーティションに関する情報です。</param>
        <param name="reason">理由は、イベント プロセッサが停止する理由です。</param>
        <summary>
            イベント プロセッサが停止されていることを示すためにプロセッサ ホストによって呼び出されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OpenAsync (Microsoft.Azure.EventHubs.Processor.PartitionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OpenAsync(class Microsoft.Azure.EventHubs.Processor.PartitionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.IEventProcessor.OpenAsync(Microsoft.Azure.EventHubs.Processor.PartitionContext)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenAsync (context As PartitionContext) As Task" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : Microsoft.Azure.EventHubs.Processor.PartitionContext -&gt; System.Threading.Tasks.Task" Usage="iEventProcessor.OpenAsync context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.Azure.EventHubs.Processor.PartitionContext" />
      </Parameters>
      <Docs>
        <param name="context">このイベント プロセッサからのイベントを処理するパーティションに関する情報です。</param>
        <summary>
            イベント プロセッサを初期化するためにプロセッサ ホストによって呼び出されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessErrorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProcessErrorAsync (Microsoft.Azure.EventHubs.Processor.PartitionContext context, Exception error);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ProcessErrorAsync(class Microsoft.Azure.EventHubs.Processor.PartitionContext context, class System.Exception error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.IEventProcessor.ProcessErrorAsync(Microsoft.Azure.EventHubs.Processor.PartitionContext,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Function ProcessErrorAsync (context As PartitionContext, error As Exception) As Task" />
      <MemberSignature Language="F#" Value="abstract member ProcessErrorAsync : Microsoft.Azure.EventHubs.Processor.PartitionContext * Exception -&gt; System.Threading.Tasks.Task" Usage="iEventProcessor.ProcessErrorAsync (context, error)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.Azure.EventHubs.Processor.PartitionContext" />
        <Parameter Name="error" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="context">パーティションに関する情報です。</param>
        <param name="error">発生したエラー。</param>
        <summary>
            基になるクライアントが受信中にエラーが発生したときに呼び出されます。 エラーから回復して、コードから必要なアクションがないため、メッセージをポンプ続行 EventProcessorHost くれます。 このメソッドは、情報提供を目的に提供されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessEventsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProcessEventsAsync (Microsoft.Azure.EventHubs.Processor.PartitionContext context, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ProcessEventsAsync(class Microsoft.Azure.EventHubs.Processor.PartitionContext context, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.IEventProcessor.ProcessEventsAsync(Microsoft.Azure.EventHubs.Processor.PartitionContext,System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Function ProcessEventsAsync (context As PartitionContext, messages As IEnumerable(Of EventData)) As Task" />
      <MemberSignature Language="F#" Value="abstract member ProcessEventsAsync : Microsoft.Azure.EventHubs.Processor.PartitionContext * seq&lt;Microsoft.Azure.EventHubs.EventData&gt; -&gt; System.Threading.Tasks.Task" Usage="iEventProcessor.ProcessEventsAsync (context, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.Azure.EventHubs.Processor.PartitionContext" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="context">パーティションに関する情報です。</param>
        <param name="messages">処理するイベントです。</param>
        <summary>
            イベントのバッチが到着したときに、プロセッサ ホストによって呼び出されます。
            <para>これは、イベント プロセッサの実際の作業が行われます。</para></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>