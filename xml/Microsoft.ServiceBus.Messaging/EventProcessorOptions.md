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
    <summary><span data-ttu-id="b2427-101">登録するときに、実行時オプションを定義、<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />とのインターフェイス、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />です。</span><span class="sxs-lookup"><span data-stu-id="b2427-101">Defines the runtime options when registering an <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> interface with an <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />.</span></span> <span data-ttu-id="b2427-102">これからの例外をキャッチするためのメカニズムでも、 <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> EventProcessorHost オブジェクトによって使用されるインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="b2427-102">This is also the mechanism for catching exceptions from an <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> instance used by an EventProcessorHost object.</span></span></summary>
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
        <summary><span data-ttu-id="b2427-103">既定のオプションを取得の 10 は、<see cref="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.MaxBatchSize" />との 1 分、<see cref="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.ReceiveTimeOut" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="b2427-103">Gets the default options, which is 10 for the <see cref="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.MaxBatchSize" />, and 1 minute for the <see cref="P:Microsoft.ServiceBus.Messaging.EventProcessorOptions.ReceiveTimeOut" /> property.</span></span></summary>
        <value><span data-ttu-id="b2427-104"><see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="b2427-104">Returns <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" />.</span></span></value>
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
        <summary> <span data-ttu-id="b2427-105">取得または受信側のランタイム メトリックが有効になっているかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="b2427-105">Gets or sets a value indicating whether the runtime metric of a receiver is enabled.</span></span> </summary>
        <value> <span data-ttu-id="b2427-106">クライアントがアクセスする場合は true。<see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" />を使用して<see cref="T:Microsoft.ServiceBus.Messaging.PartitionContext" />です。</span><span class="sxs-lookup"><span data-stu-id="b2427-106">true if a client wants to access <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" /> using <see cref="T:Microsoft.ServiceBus.Messaging.PartitionContext" />.</span></span> </value>
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
            <span data-ttu-id="b2427-107">このイベントは、イベントを処理するときに例外が発生するたびに発生します。</span><span class="sxs-lookup"><span data-stu-id="b2427-107">This event fires whenever an exception is encountered when processing events.</span></span> <span data-ttu-id="b2427-108">ユーザーは、例外通知を取得するには、このイベントのハンドラーを登録できます。</span><span class="sxs-lookup"><span data-stu-id="b2427-108">User can register an handler to this event for getting exception notification.</span></span>
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
            <span data-ttu-id="b2427-109">取得または設定を特定のパーティションを作成する初期オフセットを取得するために使用されるデリゲート<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="b2427-109">Gets or sets a delegate which is used to get the initial offset for a given partition to create <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span>
            <span data-ttu-id="b2427-110">パーティション Id を渡すことによってデリゲートが呼び出され、実際のユーザーが、文字列としてのオフセットを開始または開始メッセージを受信するための UTC 時刻にし、返すことができます。</span><span class="sxs-lookup"><span data-stu-id="b2427-110">Delegate is invoked by passing in PartitionId and then user can return either the starting offset as string or starting UTC time for receiving messages.</span></span>
            <span data-ttu-id="b2427-111">これは、場合にのみ使用<see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />が指定されていない受信者が非常に最初に作成されるとします。</span><span class="sxs-lookup"><span data-stu-id="b2427-111">This is only used when <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" /> is not provided and receiver is being created for the very first time.</span></span>
            <span data-ttu-id="b2427-112"><remarks>これはいずれかに対応<see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />または<see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.DateTime,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />デリゲートからの戻り値の型によって異なります。</remarks></span><span class="sxs-lookup"><span data-stu-id="b2427-112"><remarks>This corresponds to either <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> or <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.DateTime,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> depending on the type of return value from delegate.</remarks></span></span></summary>
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
            <span data-ttu-id="b2427-113">このオプションを有効にすると、<see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.ProcessEventsAsync(Microsoft.ServiceBus.Messaging.PartitionContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" />パーティションのストリーム内にこれ以上メッセージが存在する場合は、すべて ReceiveTimeout 後に呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="b2427-113">Enabling this option will cause <see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.ProcessEventsAsync(Microsoft.ServiceBus.Messaging.PartitionContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" /> to be invoked after every ReceiveTimeout when there are no more messages in the stream for a partition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks><span data-ttu-id="b2427-114">既定では、このオプションはオフに設定します。</span><span class="sxs-lookup"><span data-stu-id="b2427-114">By default this option is turned off.</span></span></remarks>
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
        <summary><span data-ttu-id="b2427-115">取得またはユーザーは、受信ループあたりの処理のために許容される最大イベント数を設定します。</span><span class="sxs-lookup"><span data-stu-id="b2427-115">Gets or sets the maximum event count that a user is willing to accept for processing per receive loop.</span></span> <span data-ttu-id="b2427-116">この数は、イベント ハブ パーティション レベルでです。</span><span class="sxs-lookup"><span data-stu-id="b2427-116">This count is on a per-Event Hub partition level.</span></span></summary>
        <value><span data-ttu-id="b2427-117"><see cref="T:System.Int32" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="b2427-117">Returns <see cref="T:System.Int32" />.</span></span></value>
        <remarks><span data-ttu-id="b2427-118">これには、maxCount の引数に対応しています<see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" /></span><span class="sxs-lookup"><span data-stu-id="b2427-118">This corresponds to the maxCount argument in <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" /></span></span></remarks>
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
        <summary><span data-ttu-id="b2427-119">取得または現在所有されているパーティションのすべての受信者がアクティブにキャッシュするイベントの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="b2427-119">Gets or sets the number of events that any receiver in the currently owned partition will actively cache.</span></span> <span data-ttu-id="b2427-120">このプロパティの既定値は、300 です。</span><span class="sxs-lookup"><span data-stu-id="b2427-120">The default value for this property is 300.</span></span></summary>
        <value><span data-ttu-id="b2427-121"><see cref="T:System.Int32" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="b2427-121">Returns <see cref="T:System.Int32" />.</span></span></value>
        <remarks><span data-ttu-id="b2427-122">このプロパティが設定を使用して<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactory.PrefetchCount" />ホストによって作成された基になる MessagingFactory プロパティ</span><span class="sxs-lookup"><span data-stu-id="b2427-122">This property is use to set <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactory.PrefetchCount" /> property on the underlying MessagingFactory created by host</span></span></remarks>
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
        <summary><span data-ttu-id="b2427-123">取得またはユーザーのイベント プロセッサが受信操作を実行するときに待機する期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="b2427-123">Gets or sets the timespan in which the user is willing to wait when the event processor is performing a receive operation.</span></span></summary>
        <value><span data-ttu-id="b2427-124"><see cref="T:System.TimeSpan" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="b2427-124">Returns <see cref="T:System.TimeSpan" />.</span></span></value>
        <remarks><span data-ttu-id="b2427-125">これで waitTime 引数に対応します。<see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" /></span><span class="sxs-lookup"><span data-stu-id="b2427-125">This correspond to the waitTime argument in <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" /></span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>