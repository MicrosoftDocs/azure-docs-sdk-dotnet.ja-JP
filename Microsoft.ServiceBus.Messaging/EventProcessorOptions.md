<Type Name="EventProcessorOptions" FullName="Microsoft.ServiceBus.Messaging.EventProcessorOptions">
  <TypeSignature Language="C#" Value="public class EventProcessorOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventProcessorOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class EventProcessorOptions" />
  <TypeSignature Language="F#" Value="type EventProcessorOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>登録するときに、実行時オプションを定義、<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />とのインターフェイス、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />です。 これからの例外をキャッチするためのメカニズムでも、 <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> EventProcessorHost オブジェクトによって使用されるインスタンスです。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventProcessorOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventProcessorOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultOptions">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventProcessorOptions DefaultOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.ServiceBus.Messaging.EventProcessorOptions DefaultOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.DefaultOptions" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DefaultOptions As EventProcessorOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultOptions : Microsoft.ServiceBus.Messaging.EventProcessorOptions" Usage="Microsoft.ServiceBus.Messaging.EventProcessorOptions.DefaultOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventProcessorOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>既定のオプションを取得の 10 は、<see cref="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.MaxBatchSize" />との 1 分、<see cref="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.ReceiveTimeOut" />プロパティです。</summary>
        <value><see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableReceiverRuntimeMetric">
      <MemberSignature Language="C#" Value="public bool EnableReceiverRuntimeMetric { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableReceiverRuntimeMetric" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.EnableReceiverRuntimeMetric" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableReceiverRuntimeMetric As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableReceiverRuntimeMetric : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.EventProcessorOptions.EnableReceiverRuntimeMetric" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> 取得または受信側のランタイム メトリックが有効になっているかどうかを示す値を設定します。 </summary>
        <value> クライアントがアクセスする場合は true。<see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" />を使用して<see cref="T:Microsoft.ServiceBus.Messaging.PartitionContext" />です。 </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionReceived">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; ExceptionReceived;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; ExceptionReceived" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.Messaging.EventProcessorOptions.ExceptionReceived" />
      <MemberSignature Language="VB.NET" Value="Public Event ExceptionReceived As EventHandler(Of ExceptionReceivedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.ExceptionReceived : EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; " Usage="member this.ExceptionReceived : System.EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このイベントは、イベントを処理するときに例外が発生するたびに発生します。 ユーザーは、例外通知を取得するには、このイベントのハンドラーを登録できます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialOffsetProvider">
      <MemberSignature Language="C#" Value="public Func&lt;string,object&gt; InitialOffsetProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;string, object&gt; InitialOffsetProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.InitialOffsetProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialOffsetProvider As Func(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.InitialOffsetProvider : Func&lt;string, obj&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.EventProcessorOptions.InitialOffsetProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を特定のパーティションを作成する初期オフセットを取得するために使用されるデリゲート<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />です。
            パーティション Id を渡すことによってデリゲートが呼び出され、実際のユーザーが、文字列としてのオフセットを開始または開始メッセージを受信するための UTC 時刻にし、返すことができます。
            これは、場合にのみ使用<see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />が指定されていない受信者が非常に最初に作成されるとします。
            <remarks>これはいずれかに対応<see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />または<see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.DateTime,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />デリゲートからの戻り値の型によって異なります。</remarks></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeProcessorAfterReceiveTimeout">
      <MemberSignature Language="C#" Value="public bool InvokeProcessorAfterReceiveTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool InvokeProcessorAfterReceiveTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.InvokeProcessorAfterReceiveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property InvokeProcessorAfterReceiveTimeout As Boolean" />
      <MemberSignature Language="F#" Value="member this.InvokeProcessorAfterReceiveTimeout : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.EventProcessorOptions.InvokeProcessorAfterReceiveTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このオプションを有効にすると、<see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.ProcessEventsAsync(Microsoft.ServiceBus.Messaging.PartitionContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" />パーティションのストリーム内にこれ以上メッセージが存在する場合は、すべて ReceiveTimeout 後に呼び出されます。
            </summary>
        <value>To be added.</value>
        <remarks>既定では、このオプションはオフに設定します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBatchSize">
      <MemberSignature Language="C#" Value="public int MaxBatchSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBatchSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.MaxBatchSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBatchSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBatchSize : int with get, set" Usage="Microsoft.ServiceBus.Messaging.EventProcessorOptions.MaxBatchSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはユーザーは、受信ループあたりの処理のために許容される最大イベント数を設定します。 この数は、イベント ハブ パーティション レベルでです。</summary>
        <value><see cref="T:System.Int32" /> を返します。</value>
        <remarks>これには、maxCount の引数に対応しています<see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.EventProcessorOptions.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または現在所有されているパーティションのすべての受信者がアクティブにキャッシュするイベントの数を設定します。 このプロパティの既定値は、300 です。</summary>
        <value><see cref="T:System.Int32" /> を返します。</value>
        <remarks>このプロパティが設定を使用して<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactory.PrefetchCount" />ホストによって作成された基になる MessagingFactory プロパティ</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveTimeOut">
      <MemberSignature Language="C#" Value="public TimeSpan ReceiveTimeOut { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ReceiveTimeOut" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.ReceiveTimeOut" />
      <MemberSignature Language="VB.NET" Value="Public Property ReceiveTimeOut As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ReceiveTimeOut : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.EventProcessorOptions.ReceiveTimeOut" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはユーザーのイベント プロセッサが受信操作を実行するときに待機する期間を設定します。</summary>
        <value><see cref="T:System.TimeSpan" /> を返します。</value>
        <remarks>これで waitTime 引数に対応します。<see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" /></remarks>
      </Docs>
    </Member>
  </Members>
</Type>