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
            <span data-ttu-id="628bf-101">イベント プロセッサ クラスで実装する必要があるインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="628bf-101">Interface that must be implemented by event processor classes.</span></span>
            
            <span data-ttu-id="628bf-102"><para>イベント プロセッサ クラスのインスタンスには、1 つのイベント ハブの 1 つのパーティションからのイベントのみが処理されます。PartitionContext は、いくつかのパラメーターが変更される可能性が同じパーティションは常に、イベント プロセッサへの各呼び出しで提供されます。</para><para>が EventProcessorHost はマルチ スレッド、OnError() を除き、イベント プロセッサ クラスの特定のインスタンスへの呼び出しがシリアル化します。OnEvents() を 0 回以上呼び出されるその OnOpen() が最初に、呼び出されます。イベント プロセッサ必要がある場合にシャット ダウンできないエラーがどこか、またはパーティションのリースが失われているか、プロセッサ全体のホストがシャット ダウンされているため、OnClose() が OnEvents() の最後の呼び出しが戻った後と呼ばれるかどうか。</para> <para>OnError() でした OnEvents() 中は呼び出せませんまたは OnClose() を実行します。可能性のあるデッドロックを回避するためには、同期は行われません。</para></span><span class="sxs-lookup"><span data-stu-id="628bf-102"><para>Any given instance of an event processor class will only process events from one partition of one Event Hub. A PartitionContext is provided with each call to the event processor because some parameters could change, but it will always be the same partition.</para><para>Although EventProcessorHost is multithreaded, calls to a given instance of an event processor class are serialized, except for OnError(). OnOpen() is called first, then OnEvents() will be called zero or more times. When the event processor needs to be shut down, whether because there was a failure somewhere, or the lease for the partition has been lost, or because the entire processor host is being shut down, OnClose() is called after the last OnEvents() call returns.</para><para>OnError() could be called while OnEvents() or OnClose() is executing. No synchronization is attempted in order to avoid possibly deadlocking.</para></span></span></summary>
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
        <param name="context"><span data-ttu-id="628bf-103">パーティションに関する情報です。</span><span class="sxs-lookup"><span data-stu-id="628bf-103">Information about the partition.</span></span></param>
        <param name="reason"><span data-ttu-id="628bf-104">理由は、イベント プロセッサが停止する理由です。</span><span class="sxs-lookup"><span data-stu-id="628bf-104">Reason why the event processor is being stopped.</span></span></param>
        <summary>
            <span data-ttu-id="628bf-105">イベント プロセッサが停止されていることを示すためにプロセッサ ホストによって呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="628bf-105">Called by processor host to indicate that the event processor is being stopped.</span></span>
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
        <param name="context"><span data-ttu-id="628bf-106">このイベント プロセッサからのイベントを処理するパーティションに関する情報です。</span><span class="sxs-lookup"><span data-stu-id="628bf-106">Information about the partition that this event processor will process events from.</span></span></param>
        <summary>
            <span data-ttu-id="628bf-107">イベント プロセッサを初期化するためにプロセッサ ホストによって呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="628bf-107">Called by processor host to initialize the event processor.</span></span>
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
        <param name="context"><span data-ttu-id="628bf-108">パーティションに関する情報です。</span><span class="sxs-lookup"><span data-stu-id="628bf-108">Information about the partition.</span></span></param>
        <param name="error"><span data-ttu-id="628bf-109">発生したエラー。</span><span class="sxs-lookup"><span data-stu-id="628bf-109">The error that occured.</span></span></param>
        <summary>
            <span data-ttu-id="628bf-110">基になるクライアントが受信中にエラーが発生したときに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="628bf-110">Called when the underlying client experiences an error while receiving.</span></span> <span data-ttu-id="628bf-111">エラーから回復して、コードから必要なアクションがないため、メッセージをポンプ続行 EventProcessorHost くれます。</span><span class="sxs-lookup"><span data-stu-id="628bf-111">EventProcessorHost will take care of recovering from the error and continuing to pump messages, so no action is required from your code.</span></span> <span data-ttu-id="628bf-112">このメソッドは、情報提供を目的に提供されます。</span><span class="sxs-lookup"><span data-stu-id="628bf-112">This method is provided for informational purposes.</span></span>
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
        <param name="context"><span data-ttu-id="628bf-113">パーティションに関する情報です。</span><span class="sxs-lookup"><span data-stu-id="628bf-113">Information about the partition.</span></span></param>
        <param name="messages"><span data-ttu-id="628bf-114">処理するイベントです。</span><span class="sxs-lookup"><span data-stu-id="628bf-114">The events to be processed.</span></span></param>
        <summary>
            <span data-ttu-id="628bf-115">イベントのバッチが到着したときに、プロセッサ ホストによって呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="628bf-115">Called by the processor host when a batch of events has arrived.</span></span>
            <span data-ttu-id="628bf-116"><para>これは、イベント プロセッサの実際の作業が行われます。</para></span><span class="sxs-lookup"><span data-stu-id="628bf-116"><para>This is where the real work of the event processor is done.</para></span></span></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>