<Type Name="EventProcessorOptions" FullName="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions">
  <TypeSignature Language="C#" Value="public sealed class EventProcessorOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventProcessorOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventProcessorOptions" />
  <TypeSignature Language="F#" Value="type EventProcessorOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            登録するときに、実行時オプションを定義、 <see cref="T:Microsoft.Azure.EventHubs.Processor.IEventProcessor" /> EventHubConsumerGroup を持つインターフェイスです。 これで使用される IEventProcessor インスタンスからの例外をキャッチするためのメカニズムでも、<see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorHost" />オブジェクト。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            新しい <see cref="T:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions" /> オブジェクトを作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultOptions">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.Processor.EventProcessorOptions DefaultOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.EventHubs.Processor.EventProcessorOptions DefaultOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.DefaultOptions" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DefaultOptions As EventProcessorOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultOptions : Microsoft.Azure.EventHubs.Processor.EventProcessorOptions" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.DefaultOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.Processor.EventProcessorOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            既定値に設定されたすべてのオプションと EventProcessorOptions インスタンスを返します。
            既定値は、: <para>MaxBatchSize: 10</para><para>ReceiveTimeOut: 1 分</para><para>PrefetchCount: 300</para><para>InitialOffsetProvider: 最後のオフセットを使用チェックポイントが設定された、または StartOfStream</para><para>InvokeProcessorAfterReceiveTimeout: false</para></summary>
        <value>既定値に設定されたすべてのオプションを使用して EventProcessorOptions インスタンス</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableReceiverRuntimeMetric">
      <MemberSignature Language="C#" Value="public bool EnableReceiverRuntimeMetric { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableReceiverRuntimeMetric" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.EnableReceiverRuntimeMetric" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableReceiverRuntimeMetric As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableReceiverRuntimeMetric : bool with get, set" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.EnableReceiverRuntimeMetric" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> 取得または受信側のランタイム メトリックが有効になっているかどうかを示す値を設定します。 </summary>
        <value> クライアントがアクセスする場合は true。<see cref="T:Microsoft.Azure.EventHubs.ReceiverRuntimeInformation" />を使用して<see cref="T:Microsoft.Azure.EventHubs.Processor.PartitionContext" />です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialOffsetProvider">
      <MemberSignature Language="C#" Value="public Func&lt;string,object&gt; InitialOffsetProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;string, object&gt; InitialOffsetProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.InitialOffsetProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialOffsetProvider As Func(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.InitialOffsetProvider : Func&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.InitialOffsetProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の現在の関数の最初のパーティションのイベントの受信を開始する位置のオフセットを決定するために使用します。
            <para>Null の戻り値は、(以外の場合) に使用されていること (存在する場合)、最後のチェックポイントのオフセット値を使用して、内部のプロバイダーまたは StartOfSTream を示します。</para></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeProcessorAfterReceiveTimeout">
      <MemberSignature Language="C#" Value="public bool InvokeProcessorAfterReceiveTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool InvokeProcessorAfterReceiveTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.InvokeProcessorAfterReceiveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property InvokeProcessorAfterReceiveTimeout As Boolean" />
      <MemberSignature Language="F#" Value="member this.InvokeProcessorAfterReceiveTimeout : bool with get, set" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.InvokeProcessorAfterReceiveTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            か受信タイムアウトが (true) が発生したときに、EventProcessorHost が IEventProcessor.OnEvents(null) を呼び出すかどうかを返します (false)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBatchSize">
      <MemberSignature Language="C#" Value="public int MaxBatchSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBatchSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.MaxBatchSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBatchSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBatchSize : int with get, set" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.MaxBatchSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IEventProcessor.ProcessEventsAsync で呼び出されるイベントのバッチの最大サイズを返します
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または基になるクライアントの現在のプリフェッチ数を設定します。
            既定値は、300 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ReceiveTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ReceiveTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.ReceiveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ReceiveTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ReceiveTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.ReceiveTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            タイムアウト設定を取得または受信操作での長さ。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetExceptionHandler">
      <MemberSignature Language="C#" Value="public void SetExceptionHandler (Action&lt;Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs&gt; exceptionHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetExceptionHandler(class System.Action`1&lt;class Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs&gt; exceptionHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.EventProcessorOptions.SetExceptionHandler(System.Action{Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs})" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetExceptionHandler (exceptionHandler As Action(Of ExceptionReceivedEventArgs))" />
      <MemberSignature Language="F#" Value="member this.SetExceptionHandler : Action&lt;Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs&gt; -&gt; unit" Usage="eventProcessorOptions.SetExceptionHandler exceptionHandler" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exceptionHandler" Type="System.Action&lt;Microsoft.Azure.EventHubs.Processor.ExceptionReceivedEventArgs&gt;" />
      </Parameters>
      <Docs>
        <param name="exceptionHandler">例外が発生したときに呼び出されるハンドラー。 処理を停止する場合は null に設定されます。</param>
        <summary>
            汎用的な例外の通知を受信するハンドラーを設定します。
            <para>特定のイベント ハブ パーティションからのイベントを処理中に発生した例外は、そのパーティションに対して、イベント プロセッサの onError メソッドに配信されます。ときにスロー元のアクティビティに関連付けられたイベント プロセッサがないか、イベント プロセッサを作成できませんでしたの場合、このハンドラーが呼び出されます。</para></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>