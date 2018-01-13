<Type Name="MessageReceiver" FullName="Microsoft.ServiceBus.Messaging.MessageReceiver">
  <TypeSignature Language="C#" Value="public abstract class MessageReceiver : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MessageReceiver extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessageReceiver" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MessageReceiver&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type MessageReceiver = class&#xA;    inherit ClientEntity&#xA;    interface IMessageReceiver&#xA;    interface IMessageBrowser" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary> <span data-ttu-id="4786f-101">MessageReceiver クラスは、メッセージ コンテナーからメッセージを受信し、それらを承認に使用します。</span><span class="sxs-lookup"><span data-stu-id="4786f-101">The MessageReceiver class is used to receive messages from the message container and acknowledge them.</span></span> </summary>
    <remarks><span data-ttu-id="4786f-102">あるメッセージの配信メカニズムでは提供されません既定すべて時間信頼性の高いメッセージ受信に注意してください。</span><span class="sxs-lookup"><span data-stu-id="4786f-102">Please note that message delivery mechanism does not provide by default all time reliable message receiving.</span></span> <span data-ttu-id="4786f-103">Service Bus は、システムの外になった後に、メッセージを削除します。</span><span class="sxs-lookup"><span data-stu-id="4786f-103">Service Bus deletes the message once it goes out of the system.</span></span> <span data-ttu-id="4786f-104">配信の保証 PeekLock 配信モードを使用することができます。</span><span class="sxs-lookup"><span data-stu-id="4786f-104">For a guaranteed delivery, you can use the PeekLock delivery mode.</span></span>
                      <example><code>
                      //********************************************************************************
             //                             Sending messages to a Queue
             //********************************************************************************
             
             <span data-ttu-id="4786f-105">送信者 MessageSender myMessageSender 作成 myQueueClient.CreateSender(SendMode.Default); を =</span><span class="sxs-lookup"><span data-stu-id="4786f-105">// Create a sender MessageSender myMessageSender = myQueueClient.CreateSender(SendMode.Default);</span></span>
             
             <span data-ttu-id="4786f-106">メッセージ ボックスの一覧を送信&lt;文字列&gt;問題新しいリストを =&lt;文字列&gt;(); (var 問題に関連した問題) foreach {myMessageSender.Send (新しい BrokeredMessage(issue));}</span><span class="sxs-lookup"><span data-stu-id="4786f-106">// Send messages List&lt;string&gt; Issues = new List&lt;string&gt;(); foreach (var issue in Issues) { myMessageSender.Send(new BrokeredMessage(issue)); }</span></span>
             </code></example><example><code>
             //********************************************************************************
             //                           Recieving messages from a Queue
             //********************************************************************************
             
             <span data-ttu-id="4786f-107">受信者 MessageReceiver myMessageReceiver 作成 myQueueClient.CreateReceiver(ReceiveMode.PeekLock); を =</span><span class="sxs-lookup"><span data-stu-id="4786f-107">// Create a receiver MessageReceiver myMessageReceiver = myQueueClient.CreateReceiver(ReceiveMode.PeekLock);</span></span>
             
             <span data-ttu-id="4786f-108">メッセージを受信する (int カウント = 0 になります。 カウント&lt;Issues.Count; 数 + +) {var メッセージ = myMessageReceiver.Receive(); message.Complete() です。}</span><span class="sxs-lookup"><span data-stu-id="4786f-108">// Receive messages for (int count = 0; count &lt; Issues.Count; count++) { var message = myMessageReceiver.Receive(); message.Complete(); }</span></span>
             </code></example><example><code>
             //********************************************************************************
             //                    Receiving messages from a particular session
             //********************************************************************************
             
             <span data-ttu-id="4786f-109">サブスクリプション クライアント SubscriptionClient mySubscriptionClient を作成するファクトリを = です。CreateSubscriptionClient(mySubscription) です。</span><span class="sxs-lookup"><span data-stu-id="4786f-109">// Create subscription client SubscriptionClient mySubscriptionClient = factory.CreateSubscriptionClient(mySubscription);</span></span>
             
             <span data-ttu-id="4786f-110">受信者 MessageReceiver myMessageReceiver 作成 mySubscriptionClient.AcceptMessageSession(ReceiveMode.PeekLock); を =</span><span class="sxs-lookup"><span data-stu-id="4786f-110">// Create a receiver MessageReceiver myMessageReceiver = mySubscriptionClient.AcceptMessageSession(ReceiveMode.PeekLock);</span></span>
            
             <span data-ttu-id="4786f-111">メッセージを受信する (int カウント = 0; 数 \* lt;Issues.Count です。+ +) カウント {var メッセージ = myMessageReceiver.Receive(); message.Complete() です。}</span><span class="sxs-lookup"><span data-stu-id="4786f-111">// Receive messages for (int count = 0; count \*lt; Issues.Count; count++) { var message = myMessageReceiver.Receive(); message.Complete(); }</span></span>
             </code></example></remarks>
  </Docs>
  <Members>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Abandon(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid -&gt; unit&#xA;override this.Abandon : Guid -&gt; unit" Usage="messageReceiver.Abandon lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Abandon(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="4786f-112">ロック トークンは、破棄するロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4786f-112">The lock token bound to the locked message instance to abandon.</span></span></param>
        <summary><span data-ttu-id="4786f-113">メッセージを破棄し、メッセージのロックの所有権を放棄します。</span><span class="sxs-lookup"><span data-stu-id="4786f-113">Discards the message and relinquishes the message lock ownership.</span></span></summary>
        <remarks><span data-ttu-id="4786f-114">メッセージの受信者は、キュー/トピックからメッセージを取得します。 失敗した場合、このメソッドを呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="4786f-114">When the message receiver fails to get the message from the queue/topic, this method should be called.</span></span> <span data-ttu-id="4786f-115">Service Bus には、メッセージの配信回数が 1 ずつ増分されます。</span><span class="sxs-lookup"><span data-stu-id="4786f-115">The Service Bus will increment the delivery count of the message.</span></span> <span data-ttu-id="4786f-116">メッセージの受信者は今すぐ、メッセージが再度表示されるか、配信不能キューに移動を試行できますか。</span><span class="sxs-lookup"><span data-stu-id="4786f-116">The message receiver now can either attempt to receive the message again or move it to the dead-letter queue.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Abandon(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="messageReceiver.Abandon (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Abandon(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="4786f-117">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="4786f-117">The lock token.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4786f-118">変更するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="4786f-118">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="4786f-119">メッセージを破棄し、メッセージのロックの所有権を放棄します。</span><span class="sxs-lookup"><span data-stu-id="4786f-119">Discards the message and relinquishes the message lock ownership.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.AbandonAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.AbandonAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.AbandonAsync(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="4786f-120">ロック トークンは、破棄するロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4786f-120">The lock token bound to the locked message instance to abandon.</span></span></param>
        <summary><span data-ttu-id="4786f-121">非同期的にメッセージを破棄し、メッセージのロックの所有権を放棄します。</span><span class="sxs-lookup"><span data-stu-id="4786f-121">Asynchronously discards the message and relinquishes the message lock ownership.</span></span></summary>
        <returns><span data-ttu-id="4786f-122">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-122">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.AbandonAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.AbandonAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.AbandonAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="4786f-123">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="4786f-123">The lock token.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4786f-124">変更するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="4786f-124">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="4786f-125">非同期的にメッセージを破棄し、メッセージのロックの所有権を放棄します。</span><span class="sxs-lookup"><span data-stu-id="4786f-125">Asynchronously discards the message and relinquishes the message lock ownership.</span></span></summary>
        <returns><span data-ttu-id="4786f-126">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-126">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchFlushInterval">
      <MemberSignature Language="C#" Value="public virtual TimeSpan BatchFlushInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan BatchFlushInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.BatchFlushInterval" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property BatchFlushInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.BatchFlushInterval : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.BatchFlushInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4786f-127">バッチのフラッシュ間隔を取得します。</span><span class="sxs-lookup"><span data-stu-id="4786f-127">Gets the batch flush interval.</span></span></summary>
        <value><span data-ttu-id="4786f-128">バッチのフラッシュ間隔。</span><span class="sxs-lookup"><span data-stu-id="4786f-128">The batch flush interval.</span></span> <span data-ttu-id="4786f-129">既定値は、20 ミリ秒です。</span><span class="sxs-lookup"><span data-stu-id="4786f-129">The default value is 20 ms.</span></span></value>
        <remarks><span data-ttu-id="4786f-130">SbmpTransportSetting.BatchFlushInterval 経由でその値を設定することができます。</span><span class="sxs-lookup"><span data-stu-id="4786f-130">You can set the value of it via SbmpTransportSetting.BatchFlushInterval</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchingEnabled">
      <MemberSignature Language="C#" Value="protected bool BatchingEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool BatchingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.BatchingEnabled" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property BatchingEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.BatchingEnabled : bool" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.BatchingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4786f-131">バッチ処理が有効になっているかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="4786f-131">Gets a value indicating whether the batching is enabled.</span></span></summary>
        <value><span data-ttu-id="4786f-132">バッチ処理が有効である場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="4786f-132">true if batching is enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Complete">
      <MemberSignature Language="C#" Value="public void Complete (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Complete(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Complete(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Complete (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Complete : Guid -&gt; unit&#xA;override this.Complete : Guid -&gt; unit" Usage="messageReceiver.Complete lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Complete(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="4786f-133">ロック トークン、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />です。</span><span class="sxs-lookup"><span data-stu-id="4786f-133">The lock token of the <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</span></span> <span data-ttu-id="4786f-134">これはピーク ロックのモードでメッセージが受信したときにのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="4786f-134">This is only available when a message is received in peek-lock mode.</span></span> <span data-ttu-id="4786f-135">ロック トークンは、完了するか、メッセージを破棄する内部的に使用されます。</span><span class="sxs-lookup"><span data-stu-id="4786f-135">The lock token is used internally to complete or abandon a message.</span></span></param>
        <summary><span data-ttu-id="4786f-136">メッセージの受信操作を完了します。</span><span class="sxs-lookup"><span data-stu-id="4786f-136">Completes the receive operation on a message.</span></span>
            <span data-ttu-id="4786f-137">AMQP を使用して場合、この操作はこのレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="4786f-137">If using AMQP, this operation can only be performed on messages that were received by this receiver.</span></span></summary>
        <remarks> <span data-ttu-id="4786f-138">このメソッドは、メッセージの確実な配信の受信機と Service Bus との間のハンドシェイクとして使用されます。</span><span class="sxs-lookup"><span data-stu-id="4786f-138">This method is used as a handshake between the receiver and Service Bus for a guaranteed delivery of the message.</span></span> <span data-ttu-id="4786f-139">このメソッドを呼び出す前に、受信側に失敗した場合、メッセージがキューに保持されます。</span><span class="sxs-lookup"><span data-stu-id="4786f-139">If the receiver failed before calling this method, the message will be kept in the queue.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.CompleteAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.CompleteAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.CompleteAsync(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="4786f-140">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="4786f-140">The lock token.</span></span></param>
        <summary><span data-ttu-id="4786f-141">非同期的にメッセージの受信操作を完了します。</span><span class="sxs-lookup"><span data-stu-id="4786f-141">Asynchronously completes the receive operation on a message.</span></span>
            <span data-ttu-id="4786f-142">AMQP を使用して場合、この操作はこのレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="4786f-142">If using AMQP, this operation can only be performed on messages that were received by this receiver.</span></span></summary>
        <returns><span data-ttu-id="4786f-143">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-143">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatch">
      <MemberSignature Language="C#" Value="public void CompleteBatch (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CompleteBatch(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.CompleteBatch(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CompleteBatch (lockTokens As IEnumerable(Of Guid))" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatch : seq&lt;Guid&gt; -&gt; unit&#xA;override this.CompleteBatch : seq&lt;Guid&gt; -&gt; unit" Usage="messageReceiver.CompleteBatch lockTokens" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.CompleteBatch(System.Collections.Generic.IEnumerable{System.Guid})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="lockTokens"><span data-ttu-id="4786f-144">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="4786f-144">The lock tokens.</span></span></param>
        <summary><span data-ttu-id="4786f-145">メッセージのバッチの受信操作を完了します。</span><span class="sxs-lookup"><span data-stu-id="4786f-145">Completes the receive operation on a batch of message.</span></span>
            <span data-ttu-id="4786f-146">AMQP を使用して場合、この操作はこのレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="4786f-146">If using AMQP, this operation can only be performed on messages that were received by this receiver.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteBatchAsync (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.CompleteBatchAsync(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteBatchAsync (lockTokens As IEnumerable(Of Guid)) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.CompleteBatchAsync lockTokens" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.CompleteBatchAsync(System.Collections.Generic.IEnumerable{System.Guid})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="lockTokens"><span data-ttu-id="4786f-147">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="4786f-147">The lock tokens.</span></span></param>
        <summary><span data-ttu-id="4786f-148">非同期的にメッセージのバッチの受信操作を完了します。</span><span class="sxs-lookup"><span data-stu-id="4786f-148">Asynchronously completes the receive operation on a batch of message.</span></span>
            <span data-ttu-id="4786f-149">AMQP を使用して場合、この操作はこのレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="4786f-149">If using AMQP, this operation can only be performed on messages that were received by this receiver.</span></span></summary>
        <returns><span data-ttu-id="4786f-150">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-150">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetter(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid -&gt; unit&#xA;override this.DeadLetter : Guid -&gt; unit" Usage="messageReceiver.DeadLetter lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetter(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="4786f-151">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4786f-151">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="4786f-152">配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="4786f-152">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetter(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="messageReceiver.DeadLetter (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetter(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="4786f-153">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4786f-153">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4786f-154">変更するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="4786f-154">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="4786f-155">配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="4786f-155">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetter(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * string * string -&gt; unit&#xA;override this.DeadLetter : Guid * string * string -&gt; unit" Usage="messageReceiver.DeadLetter (lockToken, deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetter(System.Guid,System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="4786f-156">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4786f-156">The lock token bound to the locked message instance.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="4786f-157">メッセージの配信不能の理由です。</span><span class="sxs-lookup"><span data-stu-id="4786f-157">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="4786f-158">メッセージの配信不能のエラーの説明。</span><span class="sxs-lookup"><span data-stu-id="4786f-158">The error description for deadlettering the message.</span></span></param>
        <summary><span data-ttu-id="4786f-159">配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="4786f-159">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetterAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetterAsync(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="4786f-160">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4786f-160">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="4786f-161">非同期的に配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="4786f-161">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="4786f-162">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-162">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetterAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetterAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="4786f-163">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4786f-163">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4786f-164">変更するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="4786f-164">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="4786f-165">非同期的に配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="4786f-165">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="4786f-166">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-166">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetterAsync(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetterAsync(System.Guid,System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="4786f-167">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4786f-167">The lock token bound to the locked message instance.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="4786f-168">メッセージの配信不能の理由です。</span><span class="sxs-lookup"><span data-stu-id="4786f-168">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="4786f-169">メッセージの配信不能のエラーの説明。</span><span class="sxs-lookup"><span data-stu-id="4786f-169">The error description for deadlettering the message.</span></span></param>
        <summary><span data-ttu-id="4786f-170">非同期的に配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="4786f-170">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="4786f-171">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-171">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Defer(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid -&gt; unit&#xA;override this.Defer : Guid -&gt; unit" Usage="messageReceiver.Defer lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Defer(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="4786f-172">ロック トークン、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />です。</span><span class="sxs-lookup"><span data-stu-id="4786f-172">The lock token of the <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />.</span></span> <span data-ttu-id="4786f-173">これはピーク ロックのモードでメッセージが受信したときにのみ使用できます。</span><span class="sxs-lookup"><span data-stu-id="4786f-173">This is only available when a message is received in peek-lock mode.</span></span> <span data-ttu-id="4786f-174">ロック トークンは、完了するか、メッセージを破棄する内部的に使用されます。</span><span class="sxs-lookup"><span data-stu-id="4786f-174">The lock token is used internally to complete or abandon a message.</span></span></param>
        <summary><span data-ttu-id="4786f-175">受信側がメッセージの処理を遅延することを示します。</span><span class="sxs-lookup"><span data-stu-id="4786f-175">Indicates that the receiver wants to defer the processing for the message.</span></span></summary>
        <remarks><span data-ttu-id="4786f-176">ユーザーを保留する前にする必要がありますを確保メッセージの受信確認を後で取得します。</span><span class="sxs-lookup"><span data-stu-id="4786f-176">Before deferring user should set aside the message receipt for later retrieval.</span></span> </remarks>
        <exception cref="P:Microsoft.ServiceBus.Common.Fx.Exception"><span data-ttu-id="4786f-177">受信コンテキストが null です。</span><span class="sxs-lookup"><span data-stu-id="4786f-177">Receive context is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Defer(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="messageReceiver.Defer (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Defer(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="4786f-178">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="4786f-178">The lock token.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4786f-179">変更するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="4786f-179">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="4786f-180">受信側がメッセージの処理を遅延することを示します。</span><span class="sxs-lookup"><span data-stu-id="4786f-180">Indicates that the receiver wants to defer the processing for the message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeferAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeferAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeferAsync(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="4786f-181">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="4786f-181">The lock token.</span></span></param>
        <summary><span data-ttu-id="4786f-182">非同期的にメッセージの処理を延期します。</span><span class="sxs-lookup"><span data-stu-id="4786f-182">Asynchronously defer the processing of the message.</span></span></summary>
        <returns><span data-ttu-id="4786f-183">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-183">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeferAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeferAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeferAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="4786f-184">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="4786f-184">The lock token.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4786f-185">変更するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="4786f-185">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="4786f-186">非同期的にメッセージの処理を延期します。</span><span class="sxs-lookup"><span data-stu-id="4786f-186">Asynchronously defer the processing of the message.</span></span></summary>
        <returns><span data-ttu-id="4786f-187">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-187">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLockToken">
      <MemberSignature Language="C#" Value="protected static Guid GetLockToken (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig valuetype System.Guid GetLockToken(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.GetLockToken(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function GetLockToken (message As BrokeredMessage) As Guid" />
      <MemberSignature Language="F#" Value="static member GetLockToken : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; Guid" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.GetLockToken message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="4786f-188"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />ロック トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="4786f-188">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> from which to get the lock token.</span></span></param>
        <summary><span data-ttu-id="4786f-189">メッセージにバインドされているロック トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="4786f-189">Gets the lock token bound to the message.</span></span></summary>
        <returns><span data-ttu-id="4786f-190">メッセージのロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="4786f-190">The lock token of the message.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLockTokens">
      <MemberSignature Language="C#" Value="protected static System.Collections.Generic.IEnumerable&lt;Guid&gt; GetLockTokens (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; GetLockTokens(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.GetLockTokens(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function GetLockTokens (messages As IEnumerable(Of BrokeredMessage)) As IEnumerable(Of Guid)" />
      <MemberSignature Language="F#" Value="static member GetLockTokens : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; seq&lt;Guid&gt;" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.GetLockTokens messages" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages"><span data-ttu-id="4786f-191">ロック トークンを取得するメッセージのコレクション。</span><span class="sxs-lookup"><span data-stu-id="4786f-191">The collection of messages from which to get the lock tokens.</span></span></param>
        <summary><span data-ttu-id="4786f-192">指定されたメッセージのコレクションからロックのトークンのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="4786f-192">Gets the collection of lock tokens from the specified collection of messages.</span></span></summary>
        <returns><span data-ttu-id="4786f-193">指定されたメッセージからロックのトークンのコレクション。</span><span class="sxs-lookup"><span data-stu-id="4786f-193">The collection of lock tokens from the specified messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty&lt;T&gt;">
      <MemberSignature Language="C#" Value="protected internal virtual T GetProperty&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig newslot virtual instance !!T GetProperty&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.GetProperty``1" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Function GetProperty(Of T) () As T" />
      <MemberSignature Language="F#" Value="abstract member GetProperty : unit -&gt; 'T&#xA;override this.GetProperty : unit -&gt; 'T" Usage="messageReceiver.GetProperty " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T"></typeparam>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastPeekedSequenceNumber">
      <MemberSignature Language="C#" Value="public virtual long LastPeekedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastPeekedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.LastPeekedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property LastPeekedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastPeekedSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.LastPeekedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4786f-194">取得または設定が、メッセージのシーケンス番号の最後のピークします。</span><span class="sxs-lookup"><span data-stu-id="4786f-194">Gets or sets the sequence number of the message last peeked.</span></span></summary>
        <value><span data-ttu-id="4786f-195">メッセージのシーケンス番号は最後ピークします。</span><span class="sxs-lookup"><span data-stu-id="4786f-195">The sequence number of the message last peeked.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ReceiveMode Mode { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.ReceiveMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.Messaging.ReceiveMode with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ReceiveMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4786f-196">メッセージを取得します受信モード。</span><span class="sxs-lookup"><span data-stu-id="4786f-196">Gets the message receive mode.</span></span></summary>
        <value><span data-ttu-id="4786f-197">メッセージは受信モードです。</span><span class="sxs-lookup"><span data-stu-id="4786f-197">The message receive mode.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OffsetInclusive">
      <MemberSignature Language="C#" Value="protected internal virtual bool OffsetInclusive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool OffsetInclusive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.OffsetInclusive" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Property OffsetInclusive As Boolean" />
      <MemberSignature Language="F#" Value="member this.OffsetInclusive : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.OffsetInclusive" />
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
    <Member MemberName="OnAbandon">
      <MemberSignature Language="C#" Value="protected virtual void OnAbandon (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnAbandon(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnAbandon(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit&#xA;override this.OnAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit" Usage="messageReceiver.OnAbandon (trackingContext, lockTokens, propertiesToModify, timeout)" />
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
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="4786f-198">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="4786f-198">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="4786f-199">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="4786f-199">The lock tokens.</span></span> </param>
        <param name="propertiesToModify"></param>
        <param name="timeout">    <span data-ttu-id="4786f-200">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="4786f-200">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="4786f-201">破棄操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-201">Executes the abandon action.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAbandon">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAbandon (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAbandon(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginAbandon(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginAbandon (trackingContext, lockTokens, propertiesToModify, fromSync, timeout, callback, state)" />
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
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="4786f-202">この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="4786f-202">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="4786f-203">ロックのトークンのコレクションはロックされているメッセージ インスタンスにバインドされます。</span><span class="sxs-lookup"><span data-stu-id="4786f-203">The collection of lock tokens bound to the locked message instances.</span></span></param>
        <param name="propertiesToModify"> <span data-ttu-id="4786f-204">変更するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="4786f-204">The properties to modify.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="4786f-205">同期の開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="4786f-205">The start of the synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="4786f-206">時間間隔、操作は、タイムアウトになるまで待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-206">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="4786f-207">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="4786f-207">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="4786f-208">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4786f-208">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="4786f-209">OnAbandon または BeginAbandon 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-209">Executes upon calling the OnAbandon or BeginAbandon operation.</span></span></summary>
        <returns><span data-ttu-id="4786f-210"><see cref="T:System.IAsyncResult" />メッセージを破棄し、そのロックを解放する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="4786f-210">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to abandon the messages and relinquish its lock.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginComplete">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt; deliveryTags, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; deliveryTags, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.ArraySegment{System.Byte}},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;ArraySegment&lt;byte&gt;&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginComplete (trackingContext, deliveryTags, fromSync, timeout, callback, state)" />
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
        <Parameter Name="deliveryTags" Type="System.Collections.Generic.IEnumerable&lt;System.ArraySegment&lt;System.Byte&gt;&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="4786f-211">この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="4786f-211">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="deliveryTags"> <span data-ttu-id="4786f-212">配信のタグのコレクション。</span><span class="sxs-lookup"><span data-stu-id="4786f-212">A collection of delivery tags.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="4786f-213">同期の開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="4786f-213">The start of the synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="4786f-214">時間間隔、操作は、タイムアウトになるまで待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-214">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="4786f-215">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="4786f-215">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="4786f-216">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4786f-216">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="4786f-217">OnComplete または BeginComplete 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-217">Executes upon calling the OnComplete or BeginComplete operation.</span></span></summary>
        <returns><span data-ttu-id="4786f-218"><see cref="T:System.IAsyncResult" />メッセージの受信を完了する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="4786f-218">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to complete receiving of messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginComplete">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginComplete (trackingContext, lockTokens, fromSync, timeout, callback, state)" />
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
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="4786f-219">この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="4786f-219">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="4786f-220">ロックのトークンのコレクションはロックされているメッセージ インスタンスにバインドされます。</span><span class="sxs-lookup"><span data-stu-id="4786f-220">The collection of lock tokens bound to the locked message instances.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="4786f-221">同期の開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="4786f-221">The start of the synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="4786f-222">時間間隔、操作は、タイムアウトになるまで待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-222">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="4786f-223">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="4786f-223">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="4786f-224">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4786f-224">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="4786f-225">OnComplete または BeginComplete 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-225">Executes upon calling the OnComplete or BeginComplete operation.</span></span></summary>
        <returns><span data-ttu-id="4786f-226"><see cref="T:System.IAsyncResult" />メッセージの受信を完了する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="4786f-226">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to complete receiving of messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginDeadLetter">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginDeadLetter (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginDeadLetter(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginDeadLetter(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginDeadLetter (trackingContext, lockTokens, propertiesToModify, deadLetterReason, deadLetterErrorDescription, fromSync, timeout, callback, state)" />
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
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="4786f-227">この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="4786f-227">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="4786f-228">ロックのトークンのコレクションはロックされているメッセージ インスタンスにバインドされます。</span><span class="sxs-lookup"><span data-stu-id="4786f-228">The collection of lock tokens bound to the locked message instances.</span></span></param>
        <param name="propertiesToModify"> <span data-ttu-id="4786f-229">変更するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="4786f-229">The properties to modify.</span></span></param>
        <param name="deadLetterReason"> <span data-ttu-id="4786f-230">理由の配信不能メッセージ。</span><span class="sxs-lookup"><span data-stu-id="4786f-230">The reason for deadlettering the messages.</span></span></param>
        <param name="deadLetterErrorDescription"> <span data-ttu-id="4786f-231">配信不能のエラーの説明メッセージ。</span><span class="sxs-lookup"><span data-stu-id="4786f-231">The error description for deadlettering the messages.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="4786f-232">同期の開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="4786f-232">The start of the synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="4786f-233">時間間隔、操作は、タイムアウトになるまで待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-233">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="4786f-234">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="4786f-234">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="4786f-235">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4786f-235">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="4786f-236">OnDeadLetter または BeginDeadLetter 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-236">Executes upon calling the OnDeadLetter or BeginDeadLetter operation.</span></span></summary>
        <returns><span data-ttu-id="4786f-237"><see cref="T:System.IAsyncResult" />配信不能キューにメッセージの配信できなかったを移動する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="4786f-237">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to move undelivered of messages to the deadletter queue.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginDefer">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginDefer (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginDefer(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginDefer(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginDefer (trackingContext, lockTokens, propertiesToModify, fromSync, timeout, callback, state)" />
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
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="4786f-238">この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="4786f-238">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="4786f-239">ロックのトークンのコレクションはロックされているメッセージ インスタンスにバインドされます。</span><span class="sxs-lookup"><span data-stu-id="4786f-239">The collection of lock tokens bound to the locked message instances.</span></span></param>
        <param name="propertiesToModify"> <span data-ttu-id="4786f-240">変更するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="4786f-240">The properties to modify.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="4786f-241">同期の開始。</span><span class="sxs-lookup"><span data-stu-id="4786f-241">The start of synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="4786f-242">時間間隔、操作は、タイムアウトになるまで待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-242">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="4786f-243">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="4786f-243">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="4786f-244">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4786f-244">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="4786f-245">OnDefer または BeginDefer 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-245">Executes upon calling the OnDefer or BeginDefer operation.</span></span></summary>
        <returns><span data-ttu-id="4786f-246"><see cref="T:System.IAsyncResult" />メッセージの処理を中断する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="4786f-246">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to suspend processing of messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginPeek">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginPeek (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, long fromSequenceNumber, int messageCount, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginPeek(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int64 fromSequenceNumber, int32 messageCount, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginPeek(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int64,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginPeek : Microsoft.ServiceBus.Tracing.TrackingContext * int64 * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginPeek (trackingContext, fromSequenceNumber, messageCount, timeout, callback, state)" />
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
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="4786f-247">この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="4786f-247">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="fromSequenceNumber"> <span data-ttu-id="4786f-248">操作を開始する位置のシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4786f-248">The sequence number from where to begin the operation.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="4786f-249">メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4786f-249">The number of message.</span></span></param>
        <param name="timeout"> <span data-ttu-id="4786f-250">時間間隔、操作は、タイムアウトになるまで待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-250">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="4786f-251">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="4786f-251">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="4786f-252">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4786f-252">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="4786f-253">BeginPeek 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-253">Executes upon calling the BeginPeek operation.</span></span></summary>
        <returns><span data-ttu-id="4786f-254">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="4786f-254">The result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginRenewMessageLocks (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginRenewMessageLocks(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginRenewMessageLocks(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginRenewMessageLocks : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginRenewMessageLocks (trackingContext, lockTokens, fromSync, timeout, callback, state)" />
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
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="4786f-255">この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="4786f-255">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="4786f-256">ロックのトークンのコレクションはロックされているメッセージ インスタンスにバインドされます。</span><span class="sxs-lookup"><span data-stu-id="4786f-256">The collection of lock tokens bound to the locked message instances.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="4786f-257">同期の開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="4786f-257">The start of the synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="4786f-258">時間間隔、操作は、タイムアウトになるまで待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-258">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="4786f-259">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="4786f-259">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="4786f-260">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4786f-260">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="4786f-261">メッセージのロックの OnBegin 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-261">Executes upon calling the OnBegin operation for lock messages.</span></span></summary>
        <returns><span data-ttu-id="4786f-262"><see cref="T:System.IAsyncResult" />ロック メッセージの処理を更新する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="4786f-262">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to renew processing of lock messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Int64},System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginTryReceive (trackingContext, sequenceNumbers, timeout, callback, state)" />
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
        <param name="trackingContext"><span data-ttu-id="4786f-263">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="4786f-263">TrackingContext to use.</span></span></param>
        <param name="sequenceNumbers"> <span data-ttu-id="4786f-264">SequenceNumbers です。</span><span class="sxs-lookup"><span data-stu-id="4786f-264">The sequenceNumbers.</span></span> </param>
        <param name="timeout">  <span data-ttu-id="4786f-265">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="4786f-265">The timeout.</span></span> </param>
        <param name="callback"> <span data-ttu-id="4786f-266">コールバック。</span><span class="sxs-lookup"><span data-stu-id="4786f-266">The callback.</span></span> </param>
        <param name="state">    <span data-ttu-id="4786f-267">状態。</span><span class="sxs-lookup"><span data-stu-id="4786f-267">The state.</span></span> </param>
        <summary> <span data-ttu-id="4786f-268">Begin try を実行するアクションを受信します。</span><span class="sxs-lookup"><span data-stu-id="4786f-268">Executes the begin try receive action.</span></span> </summary>
        <returns> <span data-ttu-id="4786f-269">が必要です。</span><span class="sxs-lookup"><span data-stu-id="4786f-269">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginTryReceive (trackingContext, messageCount, serverWaitTime, callback, state)" />
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
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="4786f-270">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="4786f-270">TrackingContext to use.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="4786f-271">メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4786f-271">Number of messages.</span></span> </param>
        <param name="serverWaitTime"> <span data-ttu-id="4786f-272">サーバーがタイムアウトするまでの時間を待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-272">The server wait time before it times out.</span></span> </param>
        <param name="callback">     <span data-ttu-id="4786f-273">コールバック。</span><span class="sxs-lookup"><span data-stu-id="4786f-273">The callback.</span></span> </param>
        <param name="state">        <span data-ttu-id="4786f-274">状態。</span><span class="sxs-lookup"><span data-stu-id="4786f-274">The state.</span></span> </param>
        <summary> <span data-ttu-id="4786f-275">Begin try を実行するアクションを受信します。</span><span class="sxs-lookup"><span data-stu-id="4786f-275">Executes the begin try receive action.</span></span> </summary>
        <returns> <span data-ttu-id="4786f-276">が必要です。</span><span class="sxs-lookup"><span data-stu-id="4786f-276">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive2">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginTryReceive2 (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginTryReceive2(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginTryReceive2(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginTryReceive2 : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginTryReceive2 (trackingContext, messageCount, serverWaitTime, callback, state)" />
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
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="4786f-277">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="4786f-277">TrackingContext to use.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="4786f-278">メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4786f-278">Number of messages.</span></span> </param>
        <param name="serverWaitTime"> <span data-ttu-id="4786f-279">サーバーがタイムアウトするまでの時間を待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-279">The server wait time before it times out.</span></span> </param>
        <param name="callback">     <span data-ttu-id="4786f-280">コールバック。</span><span class="sxs-lookup"><span data-stu-id="4786f-280">The callback.</span></span> </param>
        <param name="state">        <span data-ttu-id="4786f-281">状態。</span><span class="sxs-lookup"><span data-stu-id="4786f-281">The state.</span></span> </param>
        <summary> <span data-ttu-id="4786f-282">Begin try を実行するアクションを受信します。</span><span class="sxs-lookup"><span data-stu-id="4786f-282">Executes the begin try receive action.</span></span> </summary>
        <returns> <span data-ttu-id="4786f-283">が必要です。</span><span class="sxs-lookup"><span data-stu-id="4786f-283">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceiveEventData">
      <MemberSignature Language="C#" Value="protected virtual IAsyncResult OnBeginTryReceiveEventData (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginTryReceiveEventData(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginTryReceiveEventData(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginTryReceiveEventData : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult&#xA;override this.OnBeginTryReceiveEventData : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginTryReceiveEventData (trackingContext, messageCount, serverWaitTime, callback, state)" />
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
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="4786f-284">この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="4786f-284">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="messageCount"><span data-ttu-id="4786f-285">受信メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4786f-285">The number of messages to try receiving.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4786f-286">時間間隔、操作は、タイムアウトになるまで待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-286">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"><span data-ttu-id="4786f-287">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="4786f-287">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="4786f-288">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4786f-288">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="4786f-289">イベント データの OnTryReceive または BeginTryReceive 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-289">Executes upon calling the OnTryReceive or BeginTryReceive operation for the event data.</span></span></summary>
        <returns><span data-ttu-id="4786f-290"><see cref="T:System.IAsyncResult" />イベント データを受信しようとする非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="4786f-290">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to try to receive event data.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnComplete">
      <MemberSignature Language="C#" Value="protected virtual void OnComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * TimeSpan -&gt; unit&#xA;override this.OnComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * TimeSpan -&gt; unit" Usage="messageReceiver.OnComplete (trackingContext, lockTokens, timeout)" />
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
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="4786f-291">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="4786f-291">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="4786f-292">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="4786f-292">The lock tokens.</span></span> </param>
        <param name="timeout">    <span data-ttu-id="4786f-293">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="4786f-293">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="4786f-294">完全なアクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-294">Executes the complete action.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeadLetter">
      <MemberSignature Language="C#" Value="protected virtual void OnDeadLetter (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnDeadLetter(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnDeadLetter(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * TimeSpan -&gt; unit&#xA;override this.OnDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * TimeSpan -&gt; unit" Usage="messageReceiver.OnDeadLetter (trackingContext, lockTokens, propertiesToModify, deadLetterReason, deadLetterErrorDescription, timeout)" />
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
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="4786f-295">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="4786f-295">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="4786f-296">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="4786f-296">The lock tokens.</span></span> </param>
        <param name="propertiesToModify"></param>
        <param name="deadLetterReason">  <span data-ttu-id="4786f-297">メッセージの配信不能の理由です。</span><span class="sxs-lookup"><span data-stu-id="4786f-297">The reason for deadlettering the message.</span></span> </param>
        <param name="deadLetterErrorDescription">  <span data-ttu-id="4786f-298">メッセージの配信不能の説明情報。</span><span class="sxs-lookup"><span data-stu-id="4786f-298">The description information for deadlettering the message.</span></span> </param>
        <param name="timeout">    <span data-ttu-id="4786f-299">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="4786f-299">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="4786f-300">配信不能メッセージ キュー アクションへの移行を実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-300">Executes the move to dead letter queue action.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDefer">
      <MemberSignature Language="C#" Value="protected virtual void OnDefer (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnDefer(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnDefer(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit&#xA;override this.OnDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit" Usage="messageReceiver.OnDefer (trackingContext, lockTokens, propertiesToModify, timeout)" />
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
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="4786f-301">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="4786f-301">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="4786f-302">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="4786f-302">The lock tokens.</span></span> </param>
        <param name="propertiesToModify"></param>
        <param name="timeout">    <span data-ttu-id="4786f-303">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="4786f-303">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="4786f-304">Defer アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-304">Executes the defer action.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAbandon">
      <MemberSignature Language="C#" Value="protected abstract void OnEndAbandon (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndAbandon(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndAbandon(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndAbandon (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndAbandon : IAsyncResult -&gt; unit" Usage="messageReceiver.OnEndAbandon result" />
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
        <param name="result"><span data-ttu-id="4786f-305">結果。</span><span class="sxs-lookup"><span data-stu-id="4786f-305">The result.</span></span></param>
        <summary><span data-ttu-id="4786f-306">最後の破棄アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-306">Executes the end abandon action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndComplete">
      <MemberSignature Language="C#" Value="protected abstract void OnEndComplete (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndComplete(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndComplete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndComplete (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndComplete : IAsyncResult -&gt; unit" Usage="messageReceiver.OnEndComplete result" />
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
        <param name="result"><span data-ttu-id="4786f-307">結果。</span><span class="sxs-lookup"><span data-stu-id="4786f-307">The result.</span></span></param>
        <summary><span data-ttu-id="4786f-308">最後の完全なアクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-308">Executes the end complete action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndDeadLetter">
      <MemberSignature Language="C#" Value="protected abstract void OnEndDeadLetter (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndDeadLetter(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndDeadLetter(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndDeadLetter (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndDeadLetter : IAsyncResult -&gt; unit" Usage="messageReceiver.OnEndDeadLetter result" />
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
        <param name="result"><span data-ttu-id="4786f-309"><see cref="T:System.IAsyncResult" />を非同期的に完了した操作を参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4786f-309">An <see cref="T:System.IAsyncResult" /> object that references the asynchronously completed operation.</span></span></param>
        <summary><span data-ttu-id="4786f-310">配信不能メッセージ キュー アクションへの移行は終了を実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-310">Executes the end move to dead letter queue action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndDefer">
      <MemberSignature Language="C#" Value="protected abstract void OnEndDefer (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndDefer(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndDefer(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndDefer (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndDefer : IAsyncResult -&gt; unit" Usage="messageReceiver.OnEndDefer result" />
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
        <param name="result"><span data-ttu-id="4786f-311">結果。</span><span class="sxs-lookup"><span data-stu-id="4786f-311">The result.</span></span></param>
        <summary><span data-ttu-id="4786f-312">最後の実行アクションを延期します。</span><span class="sxs-lookup"><span data-stu-id="4786f-312">Executes the end defer action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndPeek">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnEndPeek (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnEndPeek(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndPeek(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndPeek (result As IAsyncResult) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member OnEndPeek : IAsyncResult -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.OnEndPeek result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="4786f-313">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="4786f-313">The result of the operation.</span></span></param>
        <summary><span data-ttu-id="4786f-314">EndPeek 操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-314">Executes the EndPeek operation.</span></span></summary>
        <returns><span data-ttu-id="4786f-315">メッセージの一覧。</span><span class="sxs-lookup"><span data-stu-id="4786f-315">A list of messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;DateTime&gt; OnEndRenewMessageLocks (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;valuetype System.DateTime&gt; OnEndRenewMessageLocks(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndRenewMessageLocks(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndRenewMessageLocks (result As IAsyncResult) As IEnumerable(Of DateTime)" />
      <MemberSignature Language="F#" Value="abstract member OnEndRenewMessageLocks : IAsyncResult -&gt; seq&lt;DateTime&gt;" Usage="messageReceiver.OnEndRenewMessageLocks result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="4786f-316">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="4786f-316">The result of the operation.</span></span></param>
        <summary><span data-ttu-id="4786f-317">メッセージ ロック EndRenew アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-317">Executes the EndRenew action for message locks.</span></span></summary>
        <returns><span data-ttu-id="4786f-318">A<see cref="T:System.Collections.Generic.IEnumerable`1" />ロック メッセージのです。</span><span class="sxs-lookup"><span data-stu-id="4786f-318">A <see cref="T:System.Collections.Generic.IEnumerable`1" /> of lock messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceive">
      <MemberSignature Language="C#" Value="protected abstract bool OnEndTryReceive (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnEndTryReceive(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndTryReceive(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndTryReceive (result As IAsyncResult, ByRef messages As IEnumerable(Of BrokeredMessage)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member OnEndTryReceive : IAsyncResult *  -&gt; bool" Usage="messageReceiver.OnEndTryReceive (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="4786f-319">結果。</span><span class="sxs-lookup"><span data-stu-id="4786f-319">The result.</span></span></param>
        <param name="messages"><span data-ttu-id="4786f-320">受信したメッセージのコレクションです。</span><span class="sxs-lookup"><span data-stu-id="4786f-320">The received message collection.</span></span></param>
        <summary><span data-ttu-id="4786f-321">最後の実行の受信アクションを再試行してください。</span><span class="sxs-lookup"><span data-stu-id="4786f-321">Executes the end try receive action.</span></span></summary>
        <returns><span data-ttu-id="4786f-322">これが成功した場合は true。失敗した場合は false。</span><span class="sxs-lookup"><span data-stu-id="4786f-322">true if it succeeds; false if it fails.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceive2">
      <MemberSignature Language="C#" Value="protected abstract bool OnEndTryReceive2 (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnEndTryReceive2(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndTryReceive2(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndTryReceive2 (result As IAsyncResult, ByRef messages As IEnumerable(Of BrokeredMessage)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member OnEndTryReceive2 : IAsyncResult *  -&gt; bool" Usage="messageReceiver.OnEndTryReceive2 (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="4786f-323">結果。</span><span class="sxs-lookup"><span data-stu-id="4786f-323">The result.</span></span></param>
        <param name="messages"><span data-ttu-id="4786f-324">受信したメッセージのコレクションです。</span><span class="sxs-lookup"><span data-stu-id="4786f-324">The received message collection.</span></span></param>
        <summary><span data-ttu-id="4786f-325">最後の実行の受信アクションを再試行してください。</span><span class="sxs-lookup"><span data-stu-id="4786f-325">Executes the end try receive action.</span></span></summary>
        <returns><span data-ttu-id="4786f-326">これが成功した場合は true。失敗した場合は false。</span><span class="sxs-lookup"><span data-stu-id="4786f-326">true if it succeeds; false if it fails.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceiveEventData">
      <MemberSignature Language="C#" Value="protected virtual bool OnEndTryReceiveEventData (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnEndTryReceiveEventData(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndTryReceiveEventData(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData}@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnEndTryReceiveEventData (result As IAsyncResult, ByRef messages As IEnumerable(Of EventData)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member OnEndTryReceiveEventData : IAsyncResult *  -&gt; bool&#xA;override this.OnEndTryReceiveEventData : IAsyncResult *  -&gt; bool" Usage="messageReceiver.OnEndTryReceiveEventData (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="4786f-327">結果。</span><span class="sxs-lookup"><span data-stu-id="4786f-327">The result.</span></span></param>
        <param name="messages"><span data-ttu-id="4786f-328">受信したメッセージのコレクションです。</span><span class="sxs-lookup"><span data-stu-id="4786f-328">The received message collection.</span></span></param>
        <summary><span data-ttu-id="4786f-329">イベント データの EndTryReceive アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-329">Executes the EndTryReceive action for the event data.</span></span></summary>
        <returns><span data-ttu-id="4786f-330">これが成功した場合は true。失敗した場合は false。</span><span class="sxs-lookup"><span data-stu-id="4786f-330">true if it succeeds; false if it fails.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessage">
      <MemberSignature Language="C#" Value="public void OnMessage (Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessage(class System.Action`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessage (callback As Action(Of BrokeredMessage), options As OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessage : Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="messageReceiver.OnMessage (callback, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.OnMessageOptions" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="4786f-331">この操作は完了時に呼び出すメソッド。</span><span class="sxs-lookup"><span data-stu-id="4786f-331">The method to invoke when the operation is complete.</span></span></param>
        <param name="options"><span data-ttu-id="4786f-332">指定します、<see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />メッセージ ポンプをインスタンス化するオプションです。</span><span class="sxs-lookup"><span data-stu-id="4786f-332">Specifies the <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />options with which to instantiate the message pump.</span></span></param>
        <summary><span data-ttu-id="4786f-333">イベント駆動型メッセージ ポンプにメッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="4786f-333">Processes a message in an event-driven message pump.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="public void OnMessageAsync (Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessageAsync(class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage, class System.Threading.Tasks.Task&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnMessageAsync(System.Func{Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessageAsync (callback As Func(Of BrokeredMessage, Task), options As OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessageAsync : Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage, System.Threading.Tasks.Task&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="messageReceiver.OnMessageAsync (callback, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.OnMessageOptions" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="4786f-334">この操作は完了時に呼び出すメソッド。</span><span class="sxs-lookup"><span data-stu-id="4786f-334">The method to invoke when the operation is complete.</span></span></param>
        <param name="options"><span data-ttu-id="4786f-335">指定します、<see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />メッセージ ポンプをインスタンス化するオプションです。</span><span class="sxs-lookup"><span data-stu-id="4786f-335">Specifies the <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />options with which to instantiate the message pump.</span></span></param>
        <summary><span data-ttu-id="4786f-336">イベント駆動型メッセージ ポンプにメッセージを非同期的に処理します。</span><span class="sxs-lookup"><span data-stu-id="4786f-336">Asynchronously processes a message in an event-driven message pump.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnPeek">
      <MemberSignature Language="C#" Value="protected virtual System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnPeek (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, long fromSequenceNumber, int messageCount, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnPeek(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int64 fromSequenceNumber, int32 messageCount, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnPeek(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int64,System.Int32,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnPeek : Microsoft.ServiceBus.Tracing.TrackingContext * int64 * int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.OnPeek : Microsoft.ServiceBus.Tracing.TrackingContext * int64 * int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.OnPeek (trackingContext, fromSequenceNumber, messageCount, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="4786f-337">追跡コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="4786f-337">The tracking context.</span></span></param>
        <param name="fromSequenceNumber"> <span data-ttu-id="4786f-338">ここに表示する場所からシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4786f-338">The sequence number from where to peek.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="4786f-339">メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4786f-339">The number of message.</span></span></param>
        <param name="timeout"> <span data-ttu-id="4786f-340">時間間隔、操作は、タイムアウトになるまで待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-340">The time span the operation waits before it times out.</span></span></param>
        <summary><span data-ttu-id="4786f-341">ピーク操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-341">Executes upon calling the Peek operation.</span></span></summary>
        <returns><span data-ttu-id="4786f-342">メッセージをピークします。</span><span class="sxs-lookup"><span data-stu-id="4786f-342">The messages peeked.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected virtual System.Collections.Generic.IEnumerable&lt;DateTime&gt; OnRenewMessageLocks (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;valuetype System.DateTime&gt; OnRenewMessageLocks(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnRenewMessageLocks(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnRenewMessageLocks : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * TimeSpan -&gt; seq&lt;DateTime&gt;&#xA;override this.OnRenewMessageLocks : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * TimeSpan -&gt; seq&lt;DateTime&gt;" Usage="messageReceiver.OnRenewMessageLocks (trackingContext, lockTokens, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="4786f-343">追跡コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="4786f-343">The tracking context.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="4786f-344">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="4786f-344">The lock tokens.</span></span></param>
        <param name="timeout"> <span data-ttu-id="4786f-345">時間間隔、操作は、タイムアウトになるまで待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-345">The time span the operation waits before it times out.</span></span></param>
        <summary><span data-ttu-id="4786f-346">メッセージのロックの更新アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="4786f-346">Executes the Renew action for lock messages.</span></span></summary>
        <returns><span data-ttu-id="4786f-347">更新されたロック メッセージです。</span><span class="sxs-lookup"><span data-stu-id="4786f-347">The renewed lock messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTryReceive">
      <MemberSignature Language="C#" Value="protected virtual bool OnTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers, TimeSpan timeout, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers, valuetype System.TimeSpan timeout, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Int64},System.TimeSpan,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="F#" Value="abstract member OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan *  -&gt; bool&#xA;override this.OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan *  -&gt; bool" Usage="messageReceiver.OnTryReceive (trackingContext, sequenceNumbers, timeout, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="4786f-348">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="4786f-348">TrackingContext to use.</span></span></param>
        <param name="sequenceNumbers"> <span data-ttu-id="4786f-349">配信確認メッセージ。</span><span class="sxs-lookup"><span data-stu-id="4786f-349">The receipts.</span></span> </param>
        <param name="timeout">  <span data-ttu-id="4786f-350">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="4786f-350">The timeout.</span></span> </param>
        <param name="messages"> <span data-ttu-id="4786f-351">[out]メッセージ。</span><span class="sxs-lookup"><span data-stu-id="4786f-351">[out] The messages.</span></span> </param>
        <summary> <span data-ttu-id="4786f-352">再試行を実行するアクションを受信します。</span><span class="sxs-lookup"><span data-stu-id="4786f-352">Executes the try receive action.</span></span> </summary>
        <returns> <span data-ttu-id="4786f-353">成功した場合、false が失敗した場合は true。</span><span class="sxs-lookup"><span data-stu-id="4786f-353">true if it succeeds, false if it fails.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTryReceive">
      <MemberSignature Language="C#" Value="protected virtual bool OnTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="F#" Value="abstract member OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan *  -&gt; bool&#xA;override this.OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan *  -&gt; bool" Usage="messageReceiver.OnTryReceive (trackingContext, messageCount, serverWaitTime, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="4786f-354">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="4786f-354">TrackingContext to use.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="4786f-355">メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4786f-355">Number of messages.</span></span> </param>
        <param name="serverWaitTime">  <span data-ttu-id="4786f-356">サーバーがタイムアウトするまでの時間を待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-356">The server wait time before it times out.</span></span> </param>
        <param name="messages">     <span data-ttu-id="4786f-357">[out]メッセージ。</span><span class="sxs-lookup"><span data-stu-id="4786f-357">[out] The messages.</span></span> </param>
        <summary> <span data-ttu-id="4786f-358">再試行を実行するアクションを受信します。</span><span class="sxs-lookup"><span data-stu-id="4786f-358">Executes the try receive action.</span></span> </summary>
        <returns> <span data-ttu-id="4786f-359">成功した場合、false が失敗した場合は true。</span><span class="sxs-lookup"><span data-stu-id="4786f-359">true if it succeeds, false if it fails.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public abstract string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.Path" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4786f-360">に対して相対的なキューまたはトピックのパスを取得、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />ベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="4786f-360">Gets the path of the queue or topic, relative to the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> base address.</span></span></summary>
        <value><span data-ttu-id="4786f-361">キューまたはトピックのパスを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="4786f-361">A string representing the path of the queue or topic.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Peek" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="messageReceiver.Peek " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.Peek</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="4786f-362">受信側またはメッセージの送信元の状態を変更することがなく、次のメッセージを読み取ります。</span><span class="sxs-lookup"><span data-stu-id="4786f-362">Reads the next message without changing the state of the receiver or the message source.</span></span></summary>
        <returns><span data-ttu-id="4786f-363"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />を読み取るには、次のメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="4786f-363">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> that represents the next message to be read.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Peek(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek (fromSequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="messageReceiver.Peek fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.Peek(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"><span data-ttu-id="4786f-364">メッセージを読み取る場所からシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4786f-364">The sequence number from where to read the message.</span></span></param>
        <summary><span data-ttu-id="4786f-365">受信側またはメッセージの送信元の状態を変更することがなく、次のメッセージを読み取ります。</span><span class="sxs-lookup"><span data-stu-id="4786f-365">Reads the next message without changing the state of the receiver or the message source.</span></span></summary>
        <returns><span data-ttu-id="4786f-366"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />を読み取るには、次のメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="4786f-366">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> that represents the next message to be read.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.PeekAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="4786f-367">受信側またはメッセージの送信元の状態を変更することがなく、次のメッセージを非同期に読み取ります。</span><span class="sxs-lookup"><span data-stu-id="4786f-367">Asynchronously reads the next message without changing the state of the receiver or the message source.</span></span></summary>
        <returns><span data-ttu-id="4786f-368">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-368">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (fromSequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.PeekAsync fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"><span data-ttu-id="4786f-369">メッセージを読み取る場所からシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4786f-369">The sequence number from where to read the message.</span></span></param>
        <summary><span data-ttu-id="4786f-370">受信側またはメッセージの送信元の状態を変更することがなく、次のメッセージを非同期に読み取ります。</span><span class="sxs-lookup"><span data-stu-id="4786f-370">Asynchronously reads the next message without changing the state of the receiver or the message source.</span></span></summary>
        <returns><span data-ttu-id="4786f-371">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-371">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.PeekBatch messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatch(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="4786f-372">メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4786f-372">The number of message.</span></span></param>
        <summary><span data-ttu-id="4786f-373">受信側またはメッセージの送信元の状態を変更することがなく次のバッチのメッセージを読み取ります。</span><span class="sxs-lookup"><span data-stu-id="4786f-373">Reads the next batch of message without changing the state of the receiver or the message source.</span></span></summary>
        <returns><span data-ttu-id="4786f-374">読み取られるメッセージのバッチです。</span><span class="sxs-lookup"><span data-stu-id="4786f-374">The batch of message to be read.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekBatch(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (fromSequenceNumber As Long, messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.PeekBatch (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatch(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"><span data-ttu-id="4786f-375">バッチ メッセージの読み取りにどこからシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4786f-375">The sequence number from where to read a batch message.</span></span></param>
        <param name="messageCount"><span data-ttu-id="4786f-376">メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4786f-376">The number of message.</span></span></param>
        <summary><span data-ttu-id="4786f-377">受信側またはメッセージの送信元の状態を変更することがなく次のバッチのメッセージを読み取ります。</span><span class="sxs-lookup"><span data-stu-id="4786f-377">Reads the next batch of message without changing the state of the receiver or the message source.</span></span></summary>
        <returns><span data-ttu-id="4786f-378">読み取られるメッセージのバッチです。</span><span class="sxs-lookup"><span data-stu-id="4786f-378">The batch of message to be read.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="messageReceiver.PeekBatchAsync messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatchAsync(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="4786f-379">メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4786f-379">The number of message.</span></span></param>
        <summary><span data-ttu-id="4786f-380">受信側またはメッセージの送信元の状態を変更することがなく、メッセージの次のバッチを非同期に読み取ります。</span><span class="sxs-lookup"><span data-stu-id="4786f-380">Asynchronously reads the next batch of message without changing the state of the receiver or the message source.</span></span></summary>
        <returns><span data-ttu-id="4786f-381">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-381">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekBatchAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="messageReceiver.PeekBatchAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatchAsync(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"><span data-ttu-id="4786f-382">バッチ メッセージの読み取りにどこからシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4786f-382">The sequence number from where to read a batch message.</span></span></param>
        <param name="messageCount"><span data-ttu-id="4786f-383">メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4786f-383">The number of message.</span></span></param>
        <summary><span data-ttu-id="4786f-384">受信側またはメッセージの送信元の状態を変更することがなく、メッセージの次のバッチを非同期に読み取ります。</span><span class="sxs-lookup"><span data-stu-id="4786f-384">Asynchronously reads the next batch of message without changing the state of the receiver or the message source.</span></span></summary>
        <returns><span data-ttu-id="4786f-385">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-385">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public virtual int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4786f-386">取得またはメッセージの受信者が同時に要求メッセージの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="4786f-386">Gets or sets the number of messages that the message receiver can simultaneously request.</span></span></summary>
        <value><span data-ttu-id="4786f-387">メッセージの受信者が同時に要求メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4786f-387">The number of messages that the message receiver can simultaneously request.</span></span></value>
        <remarks> <span data-ttu-id="4786f-388">サーバーに次の受信呼び出しで有効になります。</span><span class="sxs-lookup"><span data-stu-id="4786f-388">Takes effect on the next receive call to the server.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Receive" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="messageReceiver.Receive " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Receive</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="4786f-389">受信、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />が現在のキューまたはトピックからです。</span><span class="sxs-lookup"><span data-stu-id="4786f-389">Receives a <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> from the current queue or topic.</span></span></summary>
        <returns><span data-ttu-id="4786f-390"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />受信したメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="4786f-390">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />  that represents the received message.</span></span></returns>
        <remarks><span data-ttu-id="4786f-391">Null 値によって返されるこの API 操作を超えた場合、指定したタイムアウトまたは操作に成功しましたが、これ以上メッセージを受信することがあります。</span><span class="sxs-lookup"><span data-stu-id="4786f-391">A Null can be returned by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Receive(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (sequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="messageReceiver.Receive sequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Receive(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><span data-ttu-id="4786f-392">受信するメッセージのシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4786f-392">The sequence number of the message to receive.</span></span></param>
        <summary><span data-ttu-id="4786f-393">現在のキューまたはトピックからメッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="4786f-393">Receives a message from the current queue or topic.</span></span></summary>
        <returns><span data-ttu-id="4786f-394"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />受信したメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="4786f-394">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />  that represents the received message.</span></span></returns>
        <remarks><span data-ttu-id="4786f-395">Null 値によって返されるこの API 操作を超えた場合、指定したタイムアウトまたは操作に成功しましたが、要求された sequenceNumber を持つメッセージを配置することはできません。</span><span class="sxs-lookup"><span data-stu-id="4786f-395">A Null can be returned by this API if operation exceeded the timeout specified, or the operations succeeded but the message with the requested sequenceNumber cannot be located.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Receive(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (serverWaitTime As TimeSpan) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="messageReceiver.Receive serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Receive(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime"><span data-ttu-id="4786f-396">操作がタイムアウトする前に、期間、サーバーが待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-396">The time span the server waits before the operation times out.</span></span></param>
        <summary><span data-ttu-id="4786f-397">受信、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />が現在のキューまたはトピックからです。</span><span class="sxs-lookup"><span data-stu-id="4786f-397">Receives a <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> from the current queue or topic.</span></span></summary>
        <returns><span data-ttu-id="4786f-398"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />受信したメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="4786f-398">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />  that represents the received message.</span></span></returns>
        <remarks><span data-ttu-id="4786f-399">Null 値によって返されるこの API 操作を超えた場合、指定したタイムアウトまたは操作に成功しましたが、これ以上メッセージを受信することがあります。</span><span class="sxs-lookup"><span data-stu-id="4786f-399">A Null can be returned by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="4786f-400">非同期的に、現在のキューまたはトピックからメッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="4786f-400">Asynchronously receives a message from the current queue or topic.</span></span></summary>
        <returns><span data-ttu-id="4786f-401">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-401">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (sequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><span data-ttu-id="4786f-402">受信するメッセージのシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4786f-402">The sequence number of the message to receive.</span></span></param>
        <summary><span data-ttu-id="4786f-403">非同期的に、現在のキューまたはトピックからメッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="4786f-403">Asynchronously receives a message from the current queue or topic.</span></span></summary>
        <returns><span data-ttu-id="4786f-404">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-404">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (serverWaitTime As TimeSpan) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveAsync serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveAsync(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime"><span data-ttu-id="4786f-405">操作がタイムアウトする前に、期間、サーバーが待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-405">The time span the server waits before the operation times out.</span></span></param>
        <summary><span data-ttu-id="4786f-406">非同期的に、現在のキューまたはトピックからメッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="4786f-406">Asynchronously receives a message from the current queue or topic.</span></span></summary>
        <returns><span data-ttu-id="4786f-407">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-407">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatch(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (sequenceNumbers As IEnumerable(Of Long)) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveBatch sequenceNumbers" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatch(System.Collections.Generic.IEnumerable{System.Int64})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers"><span data-ttu-id="4786f-408">シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4786f-408">The sequence numbers.</span></span></param>
        <summary><span data-ttu-id="4786f-409">メッセージのバッチを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="4786f-409">Receives a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="4786f-410">メッセージのバッチです。</span><span class="sxs-lookup"><span data-stu-id="4786f-410">A batch of messages.</span></span></returns>
        <remarks><span data-ttu-id="4786f-411">Null 値によって返されるこの API 操作を超えた場合、指定したタイムアウトまたは操作に成功しましたが、要求された sequenceNumber を持つメッセージを配置することはできません。</span><span class="sxs-lookup"><span data-stu-id="4786f-411">A Null can be returned by this API if operation exceeded the timeout specified, or the operations succeeded but the message with the requested sequenceNumber cannot be located.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveBatch messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatch(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="4786f-412">バッチに返されるメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4786f-412">The number of messages to return in the batch.</span></span> <span data-ttu-id="4786f-413">これは、概算値よりも少ないまたは複数のメッセージとして<paramref name="messageCount" />返される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4786f-413">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <summary><span data-ttu-id="4786f-414">メッセージのバッチを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="4786f-414">Receives a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="4786f-415">メッセージのバッチです。</span><span class="sxs-lookup"><span data-stu-id="4786f-415">A batch of messages.</span></span></returns>
        <remarks><span data-ttu-id="4786f-416">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="4786f-416">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatch(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer, serverWaitTime As TimeSpan) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveBatch (messageCount, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatch(System.Int32,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="4786f-417">バッチに返されるメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4786f-417">The number of messages to return in the batch.</span></span> <span data-ttu-id="4786f-418">これは、概算値よりも少ないまたは複数のメッセージとして<paramref name="messageCount" />返される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4786f-418">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4786f-419">サーバーは、時間を待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-419">The server wait time.</span></span></param>
        <summary><span data-ttu-id="4786f-420">メッセージのバッチを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="4786f-420">Receives a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="4786f-421">メッセージのバッチです。</span><span class="sxs-lookup"><span data-stu-id="4786f-421">A batch of messages.</span></span></returns>
        <remarks><span data-ttu-id="4786f-422">Null 値によって返されるこの API 操作を超えた場合、指定したタイムアウトまたは操作に成功しましたが、これ以上メッセージを受信することがあります。</span><span class="sxs-lookup"><span data-stu-id="4786f-422">A Null can be returned by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatchAsync(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (sequenceNumbers As IEnumerable(Of Long)) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="messageReceiver.ReceiveBatchAsync sequenceNumbers" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatchAsync(System.Collections.Generic.IEnumerable{System.Int64})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers"><span data-ttu-id="4786f-423">シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4786f-423">The sequence numbers.</span></span></param>
        <summary><span data-ttu-id="4786f-424">非同期的にメッセージのバッチを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="4786f-424">Asynchronously receives a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="4786f-425">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-425">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="messageReceiver.ReceiveBatchAsync messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatchAsync(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="4786f-426">バッチに返されるメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4786f-426">The number of messages to return in the batch.</span></span> <span data-ttu-id="4786f-427">これは、概算値よりも少ないまたは複数のメッセージとして<paramref name="messageCount" />返される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4786f-427">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <summary><span data-ttu-id="4786f-428">非同期的にメッセージのバッチを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="4786f-428">Asynchronously receives a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="4786f-429">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-429">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatchAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer, serverWaitTime As TimeSpan) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="messageReceiver.ReceiveBatchAsync (messageCount, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatchAsync(System.Int32,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="4786f-430">バッチに返されるメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4786f-430">The number of messages to return in the batch.</span></span> <span data-ttu-id="4786f-431">これは、概算値よりも少ないまたは複数のメッセージとして<paramref name="messageCount" />返される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4786f-431">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4786f-432">サーバーは、時間を待機します。</span><span class="sxs-lookup"><span data-stu-id="4786f-432">The server wait time.</span></span></param>
        <summary><span data-ttu-id="4786f-433">非同期的にメッセージのバッチを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="4786f-433">Asynchronously receives a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="4786f-434">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4786f-434">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiverStartTime">
      <MemberSignature Language="C#" Value="protected internal virtual Nullable&lt;DateTime&gt; ReceiverStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ReceiverStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiverStartTime" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Property ReceiverStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ReceiverStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiverStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4786f-435">取得または受信側の開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="4786f-435">Gets or sets the start time of the receiver.</span></span></summary>
        <value><span data-ttu-id="4786f-436">受信側の開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="4786f-436">The start time of the receiver.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOffset">
      <MemberSignature Language="C#" Value="protected internal virtual string StartOffset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.StartOffset" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Property StartOffset As String" />
      <MemberSignature Language="F#" Value="member this.StartOffset : string with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.StartOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4786f-437">取得またはオフセットの開始位置を設定します。</span><span class="sxs-lookup"><span data-stu-id="4786f-437">Gets or sets the starting point of the offset.</span></span></summary>
        <value><span data-ttu-id="4786f-438">オフセットの開始点です。</span><span class="sxs-lookup"><span data-stu-id="4786f-438">The starting point of the offset.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportsGetRuntimeEntityDescription">
      <MemberSignature Language="C#" Value="protected internal abstract bool SupportsGetRuntimeEntityDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="VB.NET" Value="Protected Friend MustOverride ReadOnly Property SupportsGetRuntimeEntityDescription As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportsGetRuntimeEntityDescription : bool" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.SupportsGetRuntimeEntityDescription" />
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