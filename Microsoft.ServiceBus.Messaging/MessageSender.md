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
    <summary> MessageSender クラスは、Service Bus からメッセージを送信する使用します。 </summary>
    <remarks>あるメッセージの配信メカニズムでは提供されません既定すべて時間信頼性の高いメッセージ受信に注意してください。 Service Bus は、システムの外になった後に、メッセージを削除します。 配信の保証 PeekLock 配信モードを使用することができます。
                      <example><code>
                      //********************************************************************************
             //                             Sending messages to a Queue
             //********************************************************************************
             
             送信者 MessageSender myMessageSender 作成 myQueueClient.CreateSender(SendMode.Default); を =
             
             メッセージ ボックスの一覧を送信&lt;オブジェクト&gt;問題新しいリストを =&lt;オブジェクト&gt;(); (var 問題に関連した問題) foreach {myMessageSender.Send (新しい BrokeredMessage(issue));}
             </code></example><example><code>
             //********************************************************************************
             //                           Recieving messages from a Queue
             //********************************************************************************
             
             受信者 MessageReceiver myMessageReceiver 作成 myQueueClient.CreateReceiver(ReceiveMode.PeekLock); を =
             
             メッセージを受信する (int カウント = 0 になります。 カウント&lt;Issues.Count; 数 + +) {var メッセージ = myMessageReceiver.Receive(); message.Complete() です。}
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
        <summary>バッチのフラッシュ間隔を取得します。</summary>
        <value>バッチのフラッシュ間隔。 既定値は、20 ミリ秒です。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">場合にスローされる、<see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" />を閉じると、終了、またはエラーが発生した状態にします。</exception>
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
        <summary>バッチ処理が有効になっているかどうかを示す値を取得します。</summary>
        <value>バッチ処理が有効である場合は true。それ以外の場合は false です。</value>
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
        <param name="trackingContext">追跡コンテキストを使用します。</param>
        <param name="sequenceNumbers">キャンセル メッセージのシーケンス番号。</param>
        <param name="timeout">操作のクライアント側のタイムアウト値。 操作を中止するか取り消したり期間はこのタイムアウトを超過した場合。</param>
        <param name="callback">操作の完了時に呼び出すユーザー コールバック。</param>
        <param name="state">操作の完了時に、コールバックに渡される状態。</param>
        <summary>
            これにより、(必要な場合) のオーバーライドを実装する具体的な新機能は、スケジュールされた送信をキャンセルする行う必要があります
            </summary>
        <returns><see cref="T:System.IAsyncResult" />操作します。</returns>
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
        <param name="trackingContext">追跡コンテキストを使用します。</param>
        <param name="messages">スケジュールされるメッセージです。</param>
        <param name="timeout">操作のクライアント側のタイムアウト値。 操作を中止するか取り消したり期間はこのタイムアウトを超過した場合。</param>
        <param name="callback">操作の完了時に呼び出すユーザー コールバック。</param>
        <param name="state">操作の完了時に、コールバックに渡される状態。</param>
        <summary>
            これにより、(必要な場合) をオーバーライドする具体的な実装をスケジュールに実行する内容を送信
            </summary>
        <returns><see cref="T:System.IAsyncResult" />操作します。</returns>
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
        <summary>Begin 送信アクションを実行します。 このメソッドは、社内従量課金プランのためのものでは、し、ユーザーが具象クラスで実装することはできません。</summary>
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
        <summary>Begin 送信イベント データのアクションを実行します。 このメソッドは、社内従量課金プランのためのものでは、し、ユーザーが具象クラスで実装することはできません。</summary>
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
        <param name="result">操作の結果。</param>
        <summary>スケジュールされたメッセージの取り消し処理を終了したときにイベントを発生させます。</summary>
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
        <param name="result">操作の結果。</param>
        <summary>メッセージのスケジュールを終了したときにイベントを発生させます。</summary>
        <returns>操作の結果。</returns>
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
        <summary>最後の送信アクションを実行します。 このメソッドは、社内従量課金プランのためのものでは、し、ユーザーが具象クラスで実装することはできません。</summary>
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
        <param name="result">操作の結果。</param>
        <summary>最後の送信イベント データ アクションを実行します。 このメソッドは、社内従量課金プランのためのものでは、し、ユーザーが具象クラスで実装することはできません。</summary>
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
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="messages">一連の<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />送出します。</param>
        <param name="timeout">操作のクライアント側のタイムアウト値。 操作を中止するか取り消したり期間はこのタイムアウトを超過した場合。
            </param>
        <summary>
            これにより、(必要な場合) をオーバーライドする具体的な実装を送信するときに実行する内容<paramref name="messages" />に同期的にします。
            </summary>
        <remarks>
          <para>通常、タイムアウトに由来<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</para>
          <para>OnSend と等しい<c>これです。(この OnEndSend。OnBeginSend (メッセージ、タイムアウト、null、null)) です。</c>.</para>
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
        <summary>キューまたはトピックからの相対パスを取得、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />ベース アドレス。</summary>
        <value>キューまたはトピックからの相対パス、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />ベース アドレス。</value>
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
        <param name="message">送信する仲介型メッセージ。</param>
        <summary>指定された仲介型メッセージを送信します。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたときにスローされます。タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />です。 値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</exception>
        <exception cref="T:System.ArgumentException">場合にスローされる<paramref name="message" />が null です。</exception>
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
        <param name="message">送信する仲介型メッセージ。</param>
        <summary>指定された仲介型メッセージを非同期的に送信します。</summary>
        <returns>操作の非同期の結果。</returns>
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
        <param name="messages">送信するための仲介型メッセージのコレクション。</param>
        <summary>一連の (バッチ処理) の仲介型メッセージを送信します。</summary>
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
        <param name="messages">送信するための仲介型メッセージのコレクション。</param>
        <summary>(バッチ処理) の仲介型メッセージのセットが非同期的に送信します。</summary>
        <returns>操作の非同期の結果。</returns>
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