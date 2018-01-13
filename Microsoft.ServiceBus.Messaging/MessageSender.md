<Type Name="MessageSender" FullName="Microsoft.ServiceBus.Messaging.MessageSender">
  <TypeSignature Language="C#" Value="public abstract class MessageSender : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MessageSender extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessageSender" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MessageSender&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type MessageSender = class&#xA;    inherit ClientEntity&#xA;    interface IMessageSender" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary> <span data-ttu-id="49075-101">MessageSender クラスは、Service Bus からメッセージを送信する使用します。</span><span class="sxs-lookup"><span data-stu-id="49075-101">The MessageSender class is used to send messages from the Service Bus.</span></span> </summary>
    <remarks><span data-ttu-id="49075-102">あるメッセージの配信メカニズムでは提供されません既定すべて時間信頼性の高いメッセージ受信に注意してください。</span><span class="sxs-lookup"><span data-stu-id="49075-102">Please note that message delivery mechanism does not provide by default all time reliable message receiving.</span></span> <span data-ttu-id="49075-103">Service Bus は、システムの外になった後に、メッセージを削除します。</span><span class="sxs-lookup"><span data-stu-id="49075-103">Service Bus deletes the message once it goes out of the system.</span></span> <span data-ttu-id="49075-104">配信の保証 PeekLock 配信モードを使用することができます。</span><span class="sxs-lookup"><span data-stu-id="49075-104">For a guaranteed delivery, you can use the PeekLock delivery mode.</span></span>
                      <example><code>
                      //********************************************************************************
             //                             Sending messages to a Queue
             //********************************************************************************
             
             <span data-ttu-id="49075-105">送信者 MessageSender myMessageSender 作成 myQueueClient.CreateSender(SendMode.Default); を =</span><span class="sxs-lookup"><span data-stu-id="49075-105">// Create a sender MessageSender myMessageSender = myQueueClient.CreateSender(SendMode.Default);</span></span>
             
             <span data-ttu-id="49075-106">メッセージ ボックスの一覧を送信&lt;オブジェクト&gt;問題新しいリストを =&lt;オブジェクト&gt;(); (var 問題に関連した問題) foreach {myMessageSender.Send (新しい BrokeredMessage(issue));}</span><span class="sxs-lookup"><span data-stu-id="49075-106">// Send messages List&lt;object&gt; Issues = new List&lt;object&gt;(); foreach (var issue in Issues) { myMessageSender.Send(new BrokeredMessage(issue)); }</span></span>
             </code></example><example><code>
             //********************************************************************************
             //                           Recieving messages from a Queue
             //********************************************************************************
             
             <span data-ttu-id="49075-107">受信者 MessageReceiver myMessageReceiver 作成 myQueueClient.CreateReceiver(ReceiveMode.PeekLock); を =</span><span class="sxs-lookup"><span data-stu-id="49075-107">// Create a receiver MessageReceiver myMessageReceiver = myQueueClient.CreateReceiver(ReceiveMode.PeekLock);</span></span>
             
             <span data-ttu-id="49075-108">メッセージを受信する (int カウント = 0 になります。 カウント&lt;Issues.Count; 数 + +) {var メッセージ = myMessageReceiver.Receive(); message.Complete() です。}</span><span class="sxs-lookup"><span data-stu-id="49075-108">// Receive messages for (int count = 0; count &lt; Issues.Count; count++) { var message = myMessageReceiver.Receive(); message.Complete(); }</span></span>
             </code></example></remarks>
  </Docs>
  <Members>
    <Member MemberName="BatchFlushInterval">
      <MemberSignature Language="C#" Value="public virtual TimeSpan BatchFlushInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan BatchFlushInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSender.BatchFlushInterval" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property BatchFlushInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.BatchFlushInterval : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.MessageSender.BatchFlushInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="49075-109">バッチのフラッシュ間隔を取得します。</span><span class="sxs-lookup"><span data-stu-id="49075-109">Gets the batch flush interval.</span></span></summary>
        <value><span data-ttu-id="49075-110">バッチのフラッシュ間隔。</span><span class="sxs-lookup"><span data-stu-id="49075-110">A batch flush interval.</span></span> <span data-ttu-id="49075-111">既定値は、20 ミリ秒です。</span><span class="sxs-lookup"><span data-stu-id="49075-111">The default value is 20 ms.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="49075-112">場合にスローされる、<see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" />を閉じると、終了、またはエラーが発生した状態にします。</span><span class="sxs-lookup"><span data-stu-id="49075-112">Thrown when the <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> is in closing, closed, or faulted state.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="BatchingEnabled">
      <MemberSignature Language="C#" Value="protected bool BatchingEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool BatchingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSender.BatchingEnabled" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property BatchingEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.BatchingEnabled : bool" Usage="Microsoft.ServiceBus.Messaging.MessageSender.BatchingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="49075-113">バッチ処理が有効になっているかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="49075-113">Gets a value indicating whether the batching is enabled.</span></span></summary>
        <value><span data-ttu-id="49075-114">バッチ処理が有効である場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="49075-114">true if batching is enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCancelScheduledMessage">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCancelScheduledMessage (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCancelScheduledMessage(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnBeginCancelScheduledMessage(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Int64},System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCancelScheduledMessage : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSender.OnBeginCancelScheduledMessage (trackingContext, sequenceNumbers, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="49075-115">追跡コンテキストを使用します。</span><span class="sxs-lookup"><span data-stu-id="49075-115">Tracking context to use.</span></span></param>
        <param name="sequenceNumbers"><span data-ttu-id="49075-116">キャンセル メッセージのシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="49075-116">Sequence Number of the message to cancelled.</span></span></param>
        <param name="timeout"><span data-ttu-id="49075-117">操作のクライアント側のタイムアウト値。</span><span class="sxs-lookup"><span data-stu-id="49075-117">A client side timeout value for the operation.</span></span> <span data-ttu-id="49075-118">操作を中止するか取り消したり期間はこのタイムアウトを超過した場合。</span><span class="sxs-lookup"><span data-stu-id="49075-118">The operation should be aborted or cancel if the duration exceeded this timeout.</span></span></param>
        <param name="callback"><span data-ttu-id="49075-119">操作の完了時に呼び出すユーザー コールバック。</span><span class="sxs-lookup"><span data-stu-id="49075-119">A user callback to be invoked when the operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="49075-120">操作の完了時に、コールバックに渡される状態。</span><span class="sxs-lookup"><span data-stu-id="49075-120">The state to be passed to the callback when the operation completes.</span></span></param>
        <summary>
            <span data-ttu-id="49075-121">これにより、(必要な場合) のオーバーライドを実装する具体的な新機能は、スケジュールされた送信をキャンセルする行う必要があります</span><span class="sxs-lookup"><span data-stu-id="49075-121">This allows concrete implementations to override (if needed) what should be done to cancel scheduled sends</span></span>
            </summary>
        <returns><span data-ttu-id="49075-122"><see cref="T:System.IAsyncResult" />操作します。</span><span class="sxs-lookup"><span data-stu-id="49075-122">a <see cref="T:System.IAsyncResult" /> for the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginScheduleMessage">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginScheduleMessage (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginScheduleMessage(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnBeginScheduleMessage(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage},System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginScheduleMessage : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSender.OnBeginScheduleMessage (trackingContext, messages, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="49075-123">追跡コンテキストを使用します。</span><span class="sxs-lookup"><span data-stu-id="49075-123">Tracking context to use.</span></span></param>
        <param name="messages"><span data-ttu-id="49075-124">スケジュールされるメッセージです。</span><span class="sxs-lookup"><span data-stu-id="49075-124">Messages to be scheduled.</span></span></param>
        <param name="timeout"><span data-ttu-id="49075-125">操作のクライアント側のタイムアウト値。</span><span class="sxs-lookup"><span data-stu-id="49075-125">A client side timeout value for the operation.</span></span> <span data-ttu-id="49075-126">操作を中止するか取り消したり期間はこのタイムアウトを超過した場合。</span><span class="sxs-lookup"><span data-stu-id="49075-126">The operation should be aborted or cancel if the duration exceeded this timeout.</span></span></param>
        <param name="callback"><span data-ttu-id="49075-127">操作の完了時に呼び出すユーザー コールバック。</span><span class="sxs-lookup"><span data-stu-id="49075-127">A user callback to be invoked when the operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="49075-128">操作の完了時に、コールバックに渡される状態。</span><span class="sxs-lookup"><span data-stu-id="49075-128">The state to be passed to the callback when the operation completes.</span></span></param>
        <summary>
            <span data-ttu-id="49075-129">これにより、(必要な場合) をオーバーライドする具体的な実装をスケジュールに実行する内容を送信</span><span class="sxs-lookup"><span data-stu-id="49075-129">This allows concrete implementations to override (if needed) what should be done to schedule sends</span></span>
            </summary>
        <returns><span data-ttu-id="49075-130"><see cref="T:System.IAsyncResult" />操作します。</span><span class="sxs-lookup"><span data-stu-id="49075-130">a <see cref="T:System.IAsyncResult" /> for the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginSend">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginSend (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginSend(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnBeginSend(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginSend : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSender.OnBeginSend (trackingContext, messages, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"></param>
        <param name="messages"></param>
        <param name="fromSync"></param>
        <param name="timeout"></param>
        <param name="callback"></param>
        <param name="state"></param>
        <summary><span data-ttu-id="49075-131">Begin 送信アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="49075-131">Executes the begin send action.</span></span> <span data-ttu-id="49075-132">このメソッドは、社内従量課金プランのためのものでは、し、ユーザーが具象クラスで実装することはできません。</span><span class="sxs-lookup"><span data-stu-id="49075-132">This method is intended for internal consumption and cannot be implemented in a concrete class by the user.</span></span></summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginSendEventData">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginSendEventData (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; eventDatas, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginSendEventData(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; eventDatas, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnBeginSendEventData(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData},System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginSendEventData : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt; * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSender.OnBeginSendEventData (trackingContext, eventDatas, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="eventDatas" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"></param>
        <param name="eventDatas"></param>
        <param name="timeout"></param>
        <param name="callback"></param>
        <param name="state"></param>
        <summary><span data-ttu-id="49075-133">Begin 送信イベント データのアクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="49075-133">Executes the begin send event data action.</span></span> <span data-ttu-id="49075-134">このメソッドは、社内従量課金プランのためのものでは、し、ユーザーが具象クラスで実装することはできません。</span><span class="sxs-lookup"><span data-stu-id="49075-134">This method is intended for internal consumption and cannot be implemented in a concrete class by the user.</span></span></summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCancelScheduledMessage">
      <MemberSignature Language="C#" Value="protected abstract void OnEndCancelScheduledMessage (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndCancelScheduledMessage(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnEndCancelScheduledMessage(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndCancelScheduledMessage (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndCancelScheduledMessage : IAsyncResult -&gt; unit" Usage="messageSender.OnEndCancelScheduledMessage result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="49075-135">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="49075-135">The result of the operation.</span></span></param>
        <summary><span data-ttu-id="49075-136">スケジュールされたメッセージの取り消し処理を終了したときにイベントを発生させます。</span><span class="sxs-lookup"><span data-stu-id="49075-136">Raises an event when ending the cancellation of the scheduled message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndScheduleMessage">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;long&gt; OnEndScheduleMessage (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;int64&gt; OnEndScheduleMessage(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnEndScheduleMessage(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndScheduleMessage (result As IAsyncResult) As IEnumerable(Of Long)" />
      <MemberSignature Language="F#" Value="abstract member OnEndScheduleMessage : IAsyncResult -&gt; seq&lt;int64&gt;" Usage="messageSender.OnEndScheduleMessage result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="49075-137">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="49075-137">The result of the operation.</span></span></param>
        <summary><span data-ttu-id="49075-138">メッセージのスケジュールを終了したときにイベントを発生させます。</span><span class="sxs-lookup"><span data-stu-id="49075-138">Raises an event when ending the message schedule.</span></span></summary>
        <returns><span data-ttu-id="49075-139">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="49075-139">The result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndSend">
      <MemberSignature Language="C#" Value="protected abstract void OnEndSend (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndSend(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnEndSend(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndSend (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndSend : IAsyncResult -&gt; unit" Usage="messageSender.OnEndSend result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"></param>
        <summary><span data-ttu-id="49075-140">最後の送信アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="49075-140">Executes the end send action.</span></span> <span data-ttu-id="49075-141">このメソッドは、社内従量課金プランのためのものでは、し、ユーザーが具象クラスで実装することはできません。</span><span class="sxs-lookup"><span data-stu-id="49075-141">This method is intended for internal consumption and cannot be implemented in a concrete class by the user.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndSendEventData">
      <MemberSignature Language="C#" Value="protected abstract void OnEndSendEventData (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndSendEventData(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnEndSendEventData(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndSendEventData (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndSendEventData : IAsyncResult -&gt; unit" Usage="messageSender.OnEndSendEventData result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="49075-142">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="49075-142">The result of the operation.</span></span></param>
        <summary><span data-ttu-id="49075-143">最後の送信イベント データ アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="49075-143">Executes the end send event data action.</span></span> <span data-ttu-id="49075-144">このメソッドは、社内従量課金プランのためのものでは、し、ユーザーが具象クラスで実装することはできません。</span><span class="sxs-lookup"><span data-stu-id="49075-144">This method is intended for internal consumption and cannot be implemented in a concrete class by the user.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnSend">
      <MemberSignature Language="C#" Value="protected virtual void OnSend (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnSend(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.OnSend(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnSend : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * TimeSpan -&gt; unit&#xA;override this.OnSend : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * TimeSpan -&gt; unit" Usage="messageSender.OnSend (trackingContext, messages, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="49075-145">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="49075-145">TrackingContext to use.</span></span></param>
        <param name="messages"><span data-ttu-id="49075-146">一連の<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />送出します。</span><span class="sxs-lookup"><span data-stu-id="49075-146">A list of <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> to be sent.</span></span></param>
        <param name="timeout"><span data-ttu-id="49075-147">操作のクライアント側のタイムアウト値。</span><span class="sxs-lookup"><span data-stu-id="49075-147">A client side timeout value for the operation.</span></span> <span data-ttu-id="49075-148">操作を中止するか取り消したり期間はこのタイムアウトを超過した場合。</span><span class="sxs-lookup"><span data-stu-id="49075-148">The operation should be aborted or cancel if the duration exceeded this timeout.</span></span>
            </param>
        <summary>
            <span data-ttu-id="49075-149">これにより、(必要な場合) をオーバーライドする具体的な実装を送信するときに実行する内容<paramref name="messages" />に同期的にします。</span><span class="sxs-lookup"><span data-stu-id="49075-149">This allows concrete implementations to override (if needed) what should be done when sending <paramref name="messages" /> in a synchronous manner.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="49075-150">通常、タイムアウトに由来<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="49075-150">Typically the timeout comes from <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></para>
          <para><span data-ttu-id="49075-151">OnSend と等しい<c>これです。(この OnEndSend。OnBeginSend (メッセージ、タイムアウト、null、null)) です。</c>.</span><span class="sxs-lookup"><span data-stu-id="49075-151">OnSend is equal to <c>this.OnEndSend(this.OnBeginSend(messages, timeout, null, null));</c>.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public abstract string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSender.Path" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.MessageSender.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="49075-152">キューまたはトピックからの相対パスを取得、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />ベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="49075-152">Gets the path of the queue or topic relative to the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> base address.</span></span></summary>
        <value><span data-ttu-id="49075-153">キューまたはトピックからの相対パス、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />ベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="49075-153">The path of the queue or topic relative to the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> base address.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Send">
      <MemberSignature Language="C#" Value="public void Send (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Send(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.Send(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Send (message As BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member Send : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit&#xA;override this.Send : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit" Usage="messageSender.Send message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.Send(Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="49075-154">送信する仲介型メッセージ。</span><span class="sxs-lookup"><span data-stu-id="49075-154">The brokered message to send.</span></span></param>
        <summary><span data-ttu-id="49075-155">指定された仲介型メッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="49075-155">Sends the specified brokered message.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="49075-156">操作がタイムアウトしたときにスローされます。タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />です。</span><span class="sxs-lookup"><span data-stu-id="49075-156">Thrown when operation times out. Timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />.</span></span> <span data-ttu-id="49075-157">値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</span><span class="sxs-lookup"><span data-stu-id="49075-157">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="49075-158">場合にスローされる<paramref name="message" />が null です。</span><span class="sxs-lookup"><span data-stu-id="49075-158">Thrown when <paramref name="message" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.SendAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (message As BrokeredMessage) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task" Usage="messageSender.SendAsync message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="49075-159">送信する仲介型メッセージ。</span><span class="sxs-lookup"><span data-stu-id="49075-159">The brokered message to send.</span></span></param>
        <summary><span data-ttu-id="49075-160">指定された仲介型メッセージを非同期的に送信します。</span><span class="sxs-lookup"><span data-stu-id="49075-160">Asynchronously sends the specified brokered message.</span></span></summary>
        <returns><span data-ttu-id="49075-161">操作の非同期の結果。</span><span class="sxs-lookup"><span data-stu-id="49075-161">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatch">
      <MemberSignature Language="C#" Value="public void SendBatch (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SendBatch(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub SendBatch (messages As IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit&#xA;override this.SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit" Usage="messageSender.SendBatch messages" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages"><span data-ttu-id="49075-162">送信するための仲介型メッセージのコレクション。</span><span class="sxs-lookup"><span data-stu-id="49075-162">The collection of brokered messages to send.</span></span></param>
        <summary><span data-ttu-id="49075-163">一連の (バッチ処理) の仲介型メッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="49075-163">Sends a set of brokered messages (for batch processing).</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendBatchAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSender.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBatchAsync (messages As IEnumerable(Of BrokeredMessage)) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; System.Threading.Tasks.Task" Usage="messageSender.SendBatchAsync messages" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages"><span data-ttu-id="49075-164">送信するための仲介型メッセージのコレクション。</span><span class="sxs-lookup"><span data-stu-id="49075-164">The collection of brokered messages to send.</span></span></param>
        <summary><span data-ttu-id="49075-165">(バッチ処理) の仲介型メッセージのセットが非同期的に送信します。</span><span class="sxs-lookup"><span data-stu-id="49075-165">Asynchronously sends a set of brokered messages (for batch processing).</span></span></summary>
        <returns><span data-ttu-id="49075-166">操作の非同期の結果。</span><span class="sxs-lookup"><span data-stu-id="49075-166">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportsGetRuntimeEntityDescription">
      <MemberSignature Language="C#" Value="protected internal abstract bool SupportsGetRuntimeEntityDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSender.SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="VB.NET" Value="Protected Friend MustOverride ReadOnly Property SupportsGetRuntimeEntityDescription As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportsGetRuntimeEntityDescription : bool" Usage="Microsoft.ServiceBus.Messaging.MessageSender.SupportsGetRuntimeEntityDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>