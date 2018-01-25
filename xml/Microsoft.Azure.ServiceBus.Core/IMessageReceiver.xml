<Type Name="IMessageReceiver" FullName="Microsoft.Azure.ServiceBus.Core.IMessageReceiver">
  <TypeSignature Language="C#" Value="public interface IMessageReceiver : Microsoft.Azure.ServiceBus.Core.IReceiverClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMessageReceiver implements class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMessageReceiver&#xA;Implements IReceiverClient" />
  <TypeSignature Language="F#" Value="type IMessageReceiver = interface&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.IReceiverClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="f8e54-101">キューとサブスクリプションからメッセージを受信し、それらを認識する、MessageReceiver を使用できます。</span><span class="sxs-lookup"><span data-stu-id="f8e54-101">The MessageReceiver can be used to receive messages from Queues and Subscriptions and acknowledge them.</span></span>
             </summary>
    <remarks>
             <span data-ttu-id="f8e54-102">MessageReceiver は高度な機能を提供する、<see cref="T:Microsoft.Azure.ServiceBus.QueueClient" />または<see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />です。</span><span class="sxs-lookup"><span data-stu-id="f8e54-102">The MessageReceiver provides advanced functionality that is not found in the <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" /> or <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />.</span></span> <span data-ttu-id="f8e54-103">たとえば、<see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />を必要に応じて、メッセージを受信することができますもする必要しますが、ありますを使用してロックを手動で更新する<see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />です。</span><span class="sxs-lookup"><span data-stu-id="f8e54-103">For instance, <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />, which allows you to receive messages on demand, but also requires you to manually renew locks using <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />.</span></span>
             </remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.QueueClient" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />
    <example>
             <span data-ttu-id="f8e54-104">サブスクリプションからメッセージを受信する新しい MessageReceiver を作成します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-104">Create a new MessageReceiver to receive a message from a Subscription</span></span>
             <code>
             IMessageReceiver messageReceiver = new MessageReceiver(
                 namespaceConnectionString,
                 EntityNameHelper.FormatSubscriptionPath(topicName, subscriptionName),
                 ReceiveMode.PeekLock);
             </code>
            
             <span data-ttu-id="f8e54-105">サブスクリプションからメッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-105">Receive a message from the Subscription.</span></span>
             <code>
             var message = await messageReceiver.ReceiveAsync();
             await messageReceiver.CompleteAsync(message.SystemProperties.LockToken);
             </code></example>
  </Docs>
  <Members>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (System.Collections.Generic.IEnumerable&lt;string&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.CompleteAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockTokens As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="iMessageReceiver.CompleteAsync lockTokens" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="lockTokens"><span data-ttu-id="f8e54-106"><see cref="T:System.Collections.Generic.IEnumerable`1" />を完了する、対応するメッセージのロック トークンを含んでいます。</span><span class="sxs-lookup"><span data-stu-id="f8e54-106">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> containing the lock tokens of the corresponding messages to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f8e54-107">完了する一連の<see cref="T:Microsoft.Azure.ServiceBus.Message" />ロック トークンのリストを使用します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-107">Completes a series of <see cref="T:Microsoft.Azure.ServiceBus.Message" /> using a list of lock tokens.</span></span> <span data-ttu-id="f8e54-108">これにより、サービスからのメッセージが削除されます。</span><span class="sxs-lookup"><span data-stu-id="f8e54-108">This will delete the message from the service.</span></span>
            </summary>
        <returns><span data-ttu-id="f8e54-109">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="f8e54-109">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="f8e54-110">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="f8e54-110">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="iMessageReceiver.DeferAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="f8e54-111">ロック トークン、<see cref="T:Microsoft.Azure.ServiceBus.Message" />です。</span><span class="sxs-lookup"><span data-stu-id="f8e54-111">The lock token of the <see cref="T:Microsoft.Azure.ServiceBus.Message" />.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="f8e54-112">メッセージを保留中に変更するメッセージのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="f8e54-112">The properties of the message to modify while deferring the message.</span></span></param>
        <summary><span data-ttu-id="f8e54-113">受信側がメッセージの処理を遅延することを示します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-113">Indicates that the receiver wants to defer the processing for the message.</span></span></summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f8e54-114">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="f8e54-114">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="f8e54-115">このメッセージを受信するためにもう一度、将来必要がありますを保存する、<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" />を使用してメッセージを受信および<see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />です。</span><span class="sxs-lookup"><span data-stu-id="f8e54-115">In order to receive this message again in the future, you will need to save the <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" /> and receive it using <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />.</span></span>
            <span data-ttu-id="f8e54-116">遅延メッセージの期限切れのメッセージ、遅延メッセージの期限切れできますも意味に影響しません。</span><span class="sxs-lookup"><span data-stu-id="f8e54-116">Deferring messages does not impact message's expiration, meaning that deferred messages can still expire.</span></span>
            <span data-ttu-id="f8e54-117">この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="f8e54-117">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastPeekedSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastPeekedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastPeekedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.LastPeekedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastPeekedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastPeekedSequenceNumber : int64" Usage="Microsoft.Azure.ServiceBus.Core.IMessageReceiver.LastPeekedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f8e54-118">最後のピークされたメッセージのシーケンス番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-118">Gets the sequence number of the last peeked message.</span></span></summary>
        <value><span data-ttu-id="f8e54-119">最後のピークされたメッセージのシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="f8e54-119">The sequence number of the last peeked message.</span></span></value>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" />
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="iMessageReceiver.PeekAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f8e54-120">受信側またはメッセージの送信元の状態を変更せずには、次の作業中のメッセージをフェッチします。</span><span class="sxs-lookup"><span data-stu-id="f8e54-120">Fetches the next active message without changing the state of the receiver or the message source.</span></span>
            </summary>
        <returns><span data-ttu-id="f8e54-121"><see cref="T:Microsoft.Azure.ServiceBus.Message" />を読み取るには、次のメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="f8e54-121">The <see cref="T:Microsoft.Azure.ServiceBus.Message" /> that represents the next message to be read.</span></span> <span data-ttu-id="f8e54-122">ピークが無い場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-122">Returns null when nothing to peek.</span></span></returns>
        <remarks>
            <span data-ttu-id="f8e54-123">最初に呼び出す<see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" />この受信者の最初の作業中のメッセージをフェッチします。</span><span class="sxs-lookup"><span data-stu-id="f8e54-123">The first call to <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" /> fetches the first active message for this receiver.</span></span> <span data-ttu-id="f8e54-124">後続の各呼び出しは、エンティティの後続のメッセージをフェッチします。</span><span class="sxs-lookup"><span data-stu-id="f8e54-124">Each subsequent call fetches the subsequent message in the entity.</span></span>
            <span data-ttu-id="f8e54-125">異なり、受信したメッセージの数、ピーク メッセージには、それに関連付けられたロック トークンがないし、ため完了/破棄/遅延/配信不能になりました/Renewed は指定できません。</span><span class="sxs-lookup"><span data-stu-id="f8e54-125">Unlike a received messaged, peeked message will not have lock token associated with it, and hence it cannot be Completed/Abandoned/Deferred/Deadlettered/Renewed.</span></span>
            <span data-ttu-id="f8e54-126">またとは異なり<see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />、このメソッドがフェッチされいても遅延メッセージ (ただし越えたメッセージではなく)</span><span class="sxs-lookup"><span data-stu-id="f8e54-126">Also, unlike <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />, this method will fetch even Deferred messages (but not Deadlettered message)</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekAsync (int maxMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekAsync(int32 maxMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (maxMessageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="iMessageReceiver.PeekAsync maxMessageCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount"><span data-ttu-id="f8e54-127">メッセージ数。</span><span class="sxs-lookup"><span data-stu-id="f8e54-127">The number of messages.</span></span></param>
        <summary>
            <span data-ttu-id="f8e54-128">受信側またはメッセージの送信元の状態を変更することがなく、アクティブなメッセージの次のバッチをフェッチします。</span><span class="sxs-lookup"><span data-stu-id="f8e54-128">Fetches the next batch of active messages without changing the state of the receiver or the message source.</span></span>
            </summary>
        <returns><span data-ttu-id="f8e54-129">一覧の<see cref="T:Microsoft.Azure.ServiceBus.Message" />を読み取るには、次のメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="f8e54-129">List of <see cref="T:Microsoft.Azure.ServiceBus.Message" /> that represents the next message to be read.</span></span> <span data-ttu-id="f8e54-130">ピークが無い場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-130">Returns null when nothing to peek.</span></span></returns>
        <remarks>
            <span data-ttu-id="f8e54-131">最初に呼び出す<see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" />この受信者の最初の作業中のメッセージをフェッチします。</span><span class="sxs-lookup"><span data-stu-id="f8e54-131">The first call to <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" /> fetches the first active message for this receiver.</span></span> <span data-ttu-id="f8e54-132">後続の各呼び出しは、エンティティの後続のメッセージをフェッチします。</span><span class="sxs-lookup"><span data-stu-id="f8e54-132">Each subsequent call fetches the subsequent message in the entity.</span></span>
            <span data-ttu-id="f8e54-133">受信したメッセージとは異なりピーク メッセージには、それに関連付けられたロック トークンがないし、ため完了/破棄/遅延/配信不能になりました/Renewed は指定できません。</span><span class="sxs-lookup"><span data-stu-id="f8e54-133">Unlike a received message, peeked message will not have lock token associated with it, and hence it cannot be Completed/Abandoned/Deferred/Deadlettered/Renewed.</span></span>
            <span data-ttu-id="f8e54-134">またとは異なり<see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />、このメソッドがフェッチされいても遅延メッセージ (ただし越えたメッセージではなく)</span><span class="sxs-lookup"><span data-stu-id="f8e54-134">Also, unlike <see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />, this method will fetch even Deferred messages (but not Deadlettered message)</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBySequenceNumberAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; PeekBySequenceNumberAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; PeekBySequenceNumberAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekBySequenceNumberAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBySequenceNumberAsync (fromSequenceNumber As Long) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member PeekBySequenceNumberAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="iMessageReceiver.PeekBySequenceNumberAsync fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"><span data-ttu-id="f8e54-135">メッセージを読み取る場所からシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="f8e54-135">The sequence number from where to read the message.</span></span></param>
        <summary>
            <span data-ttu-id="f8e54-136">受信側またはメッセージの送信元の状態を変更することがなく、次のメッセージを非同期に読み取ります。</span><span class="sxs-lookup"><span data-stu-id="f8e54-136">Asynchronously reads the next message without changing the state of the receiver or the message source.</span></span>
            </summary>
        <returns><span data-ttu-id="f8e54-137">返す非同期操作、<see cref="T:Microsoft.Azure.ServiceBus.Message" />を読み取るには、次のメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="f8e54-137">The asynchronous operation that returns the <see cref="T:Microsoft.Azure.ServiceBus.Message" /> that represents the next message to be read.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBySequenceNumberAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekBySequenceNumberAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekBySequenceNumberAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekBySequenceNumberAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBySequenceNumberAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member PeekBySequenceNumberAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="iMessageReceiver.PeekBySequenceNumberAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"><span data-ttu-id="f8e54-138">メッセージのバッチを参照する開始点です。</span><span class="sxs-lookup"><span data-stu-id="f8e54-138">The starting point from which to browse a batch of messages.</span></span></param>
        <param name="messageCount"><span data-ttu-id="f8e54-139">メッセージ数。</span><span class="sxs-lookup"><span data-stu-id="f8e54-139">The number of messages.</span></span></param>
        <summary><span data-ttu-id="f8e54-140">バッチのメッセージをピークします。</span><span class="sxs-lookup"><span data-stu-id="f8e54-140">Peeks a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="f8e54-141">バッチのメッセージをピークします。</span><span class="sxs-lookup"><span data-stu-id="f8e54-141">A batch of messages peeked.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="iMessageReceiver.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f8e54-142">定義されているエンティティからメッセージを受信<see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" />を使用して<see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />モード。</span><span class="sxs-lookup"><span data-stu-id="f8e54-142">Receive a message from the entity defined by <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" /> using <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> mode.</span></span>
            </summary>
        <returns><span data-ttu-id="f8e54-143">受信したメッセージ。</span><span class="sxs-lookup"><span data-stu-id="f8e54-143">The message received.</span></span> <span data-ttu-id="f8e54-144">メッセージがない場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-144">Returns null if no message is found.</span></span></returns>
        <remarks><span data-ttu-id="f8e54-145">期間の後に操作がタイムアウト<see cref="P:Microsoft.Azure.ServiceBus.ClientEntity.OperationTimeout" /></span><span class="sxs-lookup"><span data-stu-id="f8e54-145">Operation will time out after duration of <see cref="P:Microsoft.Azure.ServiceBus.ClientEntity.OperationTimeout" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync (int maxMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync(int32 maxMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="iMessageReceiver.ReceiveAsync maxMessageCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount"><span data-ttu-id="f8e54-146">受信するメッセージの最大数。</span><span class="sxs-lookup"><span data-stu-id="f8e54-146">The maximum number of messages that will be received.</span></span></param>
        <summary>
            <span data-ttu-id="f8e54-147">最大値を受け取る<paramref name="maxMessageCount" />によって定義されているエンティティからのメッセージ<see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" />を使用して<see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />モード。</span><span class="sxs-lookup"><span data-stu-id="f8e54-147">Receives a maximum of <paramref name="maxMessageCount" /> messages from the entity defined by <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" /> using <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> mode.</span></span>
            </summary>
        <returns><span data-ttu-id="f8e54-148">受信したメッセージの一覧です。</span><span class="sxs-lookup"><span data-stu-id="f8e54-148">List of messages received.</span></span> <span data-ttu-id="f8e54-149">メッセージがない場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-149">Returns null if no message is found.</span></span></returns>
        <remarks><span data-ttu-id="f8e54-150">も少ない受信<paramref name="maxMessageCount" />メッセージは空のエンティティを示す値ではありません。</span><span class="sxs-lookup"><span data-stu-id="f8e54-150">Receiving less than <paramref name="maxMessageCount" /> messages is not an indication of empty entity.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync (TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync(valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (operationTimeout As TimeSpan) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="iMessageReceiver.ReceiveAsync operationTimeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationTimeout"><span data-ttu-id="f8e54-151">タイムアウトになる前にメッセージを受信するためクライアントが待機するを期間します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-151">The time span the client waits for receiving a message before it times out.</span></span></param>
        <summary>
            <span data-ttu-id="f8e54-152">定義されているエンティティからメッセージを受信<see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" />を使用して<see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />モード。</span><span class="sxs-lookup"><span data-stu-id="f8e54-152">Receive a message from the entity defined by <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" /> using <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> mode.</span></span>
            </summary>
        <returns><span data-ttu-id="f8e54-153">受信したメッセージ。</span><span class="sxs-lookup"><span data-stu-id="f8e54-153">The message received.</span></span> <span data-ttu-id="f8e54-154">メッセージがない場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-154">Returns null if no message is found.</span></span></returns>
        <remarks>
            <span data-ttu-id="f8e54-155">パラメーター <paramref name="operationTimeout" /> (いずれかまたは接続を再確立する必要がある場合、最初の受信時に) 接続を確立するために、受信側にかかる時間が含まれています。</span><span class="sxs-lookup"><span data-stu-id="f8e54-155">The parameter <paramref name="operationTimeout" /> includes the time taken by the receiver to establish a connection (either during the first receive or when connection needs to be re-established).</span></span> <span data-ttu-id="f8e54-156">これがスローされる場合は、接続の確立がタイムアウトになる、<see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="f8e54-156">If establishing the connection times out, this will throw <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync (int maxMessageCount, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync(int32 maxMessageCount, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer, operationTimeout As TimeSpan) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="iMessageReceiver.ReceiveAsync (maxMessageCount, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount"><span data-ttu-id="f8e54-157">受信するメッセージの最大数。</span><span class="sxs-lookup"><span data-stu-id="f8e54-157">The maximum number of messages that will be received.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f8e54-158">タイムアウトになる前にメッセージを受信するためクライアントが待機するを期間します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-158">The time span the client waits for receiving a message before it times out.</span></span></param>
        <summary>
            <span data-ttu-id="f8e54-159">最大値を受け取る<paramref name="maxMessageCount" />によって定義されているエンティティからのメッセージ<see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" />を使用して<see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />モード。</span><span class="sxs-lookup"><span data-stu-id="f8e54-159">Receives a maximum of <paramref name="maxMessageCount" /> messages from the entity defined by <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" /> using <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> mode.</span></span>
            </summary>
        <returns><span data-ttu-id="f8e54-160">受信したメッセージの一覧です。</span><span class="sxs-lookup"><span data-stu-id="f8e54-160">List of messages received.</span></span> <span data-ttu-id="f8e54-161">メッセージがない場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-161">Returns null if no message is found.</span></span></returns>
        <remarks><span data-ttu-id="f8e54-162">も少ない受信<paramref name="maxMessageCount" />メッセージは空のエンティティを示す値ではありません。</span><span class="sxs-lookup"><span data-stu-id="f8e54-162">Receiving less than <paramref name="maxMessageCount" /> messages is not an indication of empty entity.</span></span>
            <span data-ttu-id="f8e54-163">パラメーター <paramref name="operationTimeout" /> (いずれかまたは接続を再確立する必要がある場合、最初の受信時に) 接続を確立するために、受信側にかかる時間が含まれています。</span><span class="sxs-lookup"><span data-stu-id="f8e54-163">The parameter <paramref name="operationTimeout" /> includes the time taken by the receiver to establish a connection (either during the first receive or when connection needs to be re-established).</span></span> <span data-ttu-id="f8e54-164">これがスローされる場合は、接続の確立がタイムアウトになる、<see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="f8e54-164">If establishing the connection times out, this will throw <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveDeferredMessageAsync (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveDeferredMessageAsync(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveDeferredMessageAsync (sequenceNumbers As IEnumerable(Of Long)) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveDeferredMessageAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="iMessageReceiver.ReceiveDeferredMessageAsync sequenceNumbers" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers"><span data-ttu-id="f8e54-165"><see cref="T:System.Collections.Generic.IEnumerable`1" />を受信するシーケンス番号を含むです。</span><span class="sxs-lookup"><span data-stu-id="f8e54-165">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> containing the sequence numbers to receive.</span></span></param>
        <summary>
            <span data-ttu-id="f8e54-166">受信、<see cref="T:System.Collections.Generic.IList`1" />で識別される遅延メッセージの<paramref name="sequenceNumbers" />します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-166">Receives a <see cref="T:System.Collections.Generic.IList`1" /> of deferred messages identified by <paramref name="sequenceNumbers" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f8e54-167">シーケンス番号によって識別されるメッセージが返されます。</span><span class="sxs-lookup"><span data-stu-id="f8e54-167">Messages identified by sequence number are returned.</span></span> <span data-ttu-id="f8e54-168">メッセージが見つからない場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-168">Returns null if no messages are found.</span></span>
            <span data-ttu-id="f8e54-169">メッセージが遅延されていない場合をスローします。</span><span class="sxs-lookup"><span data-stu-id="f8e54-169">Throws if the messages have not been deferred.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      </Docs>
    </Member>
    <Member MemberName="ReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveDeferredMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveDeferredMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveDeferredMessageAsync (sequenceNumber As Long) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveDeferredMessageAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="iMessageReceiver.ReceiveDeferredMessageAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><span data-ttu-id="f8e54-170">受信するメッセージのシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="f8e54-170">The sequence number of the message that will be received.</span></span></param>
        <summary>
            <span data-ttu-id="f8e54-171">によって識別される特定の遅延メッセージ受信<paramref name="sequenceNumber" />です。</span><span class="sxs-lookup"><span data-stu-id="f8e54-171">Receives a specific deferred message identified by <paramref name="sequenceNumber" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f8e54-172">メッセージのシーケンス番号によって識別<paramref name="sequenceNumber" />です。</span><span class="sxs-lookup"><span data-stu-id="f8e54-172">Message identified by sequence number <paramref name="sequenceNumber" />.</span></span> <span data-ttu-id="f8e54-173">このようなメッセージが存在しない場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-173">Returns null if no such message is found.</span></span>
            <span data-ttu-id="f8e54-174">メッセージは保留されていない場合にスローします。</span><span class="sxs-lookup"><span data-stu-id="f8e54-174">Throws if the message has not been deferred.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewLockAsync (Microsoft.Azure.ServiceBus.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewLockAsync(class Microsoft.Azure.ServiceBus.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />
      <MemberSignature Language="F#" Value="abstract member RenewLockAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task" Usage="iMessageReceiver.RenewLockAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>
            <span data-ttu-id="f8e54-175">メッセージのロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-175">Renews the lock on the message.</span></span> <span data-ttu-id="f8e54-176">ロックは、キューに指定された設定に基づいて更新されます。</span><span class="sxs-lookup"><span data-stu-id="f8e54-176">The lock will be renewed based on the setting specified on the queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f8e54-177">メッセージを受信する<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />モードでは、メッセージがロックされているこの受信者インスタンス用のサーバーに指定された期間中 (LockDuration) キュー/サブスクリプションの作成中にします。</span><span class="sxs-lookup"><span data-stu-id="f8e54-177">When a message is received in <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> mode, the message is locked on the server for this receiver instance for a duration as specified during the Queue/Subscription creation (LockDuration).</span></span>
            <span data-ttu-id="f8e54-178">メッセージの処理は、この期間を超える必要がある場合、ロックを更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8e54-178">If processing of the message requires longer than this duration, the lock needs to be renewed.</span></span>
            <span data-ttu-id="f8e54-179">各更新のエンティティに設定 LockDuration によってメッセージがロックされている時間にリセットされます。</span><span class="sxs-lookup"><span data-stu-id="f8e54-179">For each renewal, it resets the time the message is locked by the LockDuration set on the Entity.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;DateTime&gt; RenewLockAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.DateTime&gt; RenewLockAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewLockAsync (lockToken As String) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="abstract member RenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="iMessageReceiver.RenewLockAsync lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="f8e54-180">メッセージに関連付けられたロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="f8e54-180">Lock token associated with the message.</span></span></param>
        <summary>
            <span data-ttu-id="f8e54-181">メッセージのロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="f8e54-181">Renews the lock on the message.</span></span> <span data-ttu-id="f8e54-182">ロックは、キューに指定された設定に基づいて更新されます。</span><span class="sxs-lookup"><span data-stu-id="f8e54-182">The lock will be renewed based on the setting specified on the queue.</span></span>
            <span data-ttu-id="f8e54-183"><returns>トークンの有効期限の日付と時刻 (utc) 形式での新しいロックします。</returns></span><span class="sxs-lookup"><span data-stu-id="f8e54-183"><returns>New lock token expiry date and time in UTC format.</returns></span></span></summary>
        <returns><span data-ttu-id="f8e54-184">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="f8e54-184">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="f8e54-185">メッセージを受信する<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />モードでは、メッセージがロックされているこの受信者インスタンス用のサーバーに指定された期間中 (LockDuration) キュー/サブスクリプションの作成中にします。</span><span class="sxs-lookup"><span data-stu-id="f8e54-185">When a message is received in <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> mode, the message is locked on the server for this receiver instance for a duration as specified during the Queue/Subscription creation (LockDuration).</span></span>
            <span data-ttu-id="f8e54-186">メッセージの処理は、この期間を超える必要がある場合、ロックを更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f8e54-186">If processing of the message requires longer than this duration, the lock needs to be renewed.</span></span>
            <span data-ttu-id="f8e54-187">各更新のエンティティに設定 LockDuration によってメッセージがロックされている時間にリセットされます。</span><span class="sxs-lookup"><span data-stu-id="f8e54-187">For each renewal, it resets the time the message is locked by the LockDuration set on the Entity.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>