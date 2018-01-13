<Type Name="IReceiverClient" FullName="Microsoft.Azure.ServiceBus.Core.IReceiverClient">
  <TypeSignature Language="C#" Value="public interface IReceiverClient : Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReceiverClient implements class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Core.IReceiverClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReceiverClient&#xA;Implements IClientEntity" />
  <TypeSignature Language="F#" Value="type IReceiverClient = interface&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.IClientEntity</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="df969-101">メッセージを受信するための共通の機能の記述に使用されるインターフェイス<see cref="T:Microsoft.Azure.ServiceBus.IQueueClient" />と<see cref="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />です。</span><span class="sxs-lookup"><span data-stu-id="df969-101">An interface used to describe common functionality for receiving messages from <see cref="T:Microsoft.Azure.ServiceBus.IQueueClient" /> and <see cref="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />.</span></span>
            </summary>
    <remarks><span data-ttu-id="df969-102">使用して<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />の高度な機能セット。</span><span class="sxs-lookup"><span data-stu-id="df969-102">Use <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" /> for advanced set of functionality.</span></span></remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.IQueueClient" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />
  </Docs>
  <Members>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="iReceiverClient.AbandonAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="df969-103">中止するのには、対応するメッセージのロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="df969-103">The lock token of the corresponding message to abandon.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="df969-104">メッセージの破棄中に変更するメッセージのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="df969-104">The properties of the message to modify while abandoning the message.</span></span></param>
        <summary>
            <span data-ttu-id="df969-105">破棄、<see cref="T:Microsoft.Azure.ServiceBus.Message" />ロックのトークンを使用します。</span><span class="sxs-lookup"><span data-stu-id="df969-105">Abandons a <see cref="T:Microsoft.Azure.ServiceBus.Message" /> using a lock token.</span></span> <span data-ttu-id="df969-106">これにより、メッセージ処理用にもう一度使用できます。</span><span class="sxs-lookup"><span data-stu-id="df969-106">This will make the message available again for processing.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="df969-107">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="df969-107">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="df969-108">メッセージを破棄すると、メッセージの配信回数が増加します。</span><span class="sxs-lookup"><span data-stu-id="df969-108">Abandoning a message will increase the delivery count on the message.</span></span>
            <span data-ttu-id="df969-109">この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="df969-109">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.CompleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : string -&gt; System.Threading.Tasks.Task" Usage="iReceiverClient.CompleteAsync lockToken" />
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
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="df969-110">完了する、対応するメッセージのロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="df969-110">The lock token of the corresponding message to complete.</span></span></param>
        <summary>
            <span data-ttu-id="df969-111">完了、<see cref="T:Microsoft.Azure.ServiceBus.Message" />のロック トークンを使用します。</span><span class="sxs-lookup"><span data-stu-id="df969-111">Completes a <see cref="T:Microsoft.Azure.ServiceBus.Message" /> using its lock token.</span></span> <span data-ttu-id="df969-112">これにより、メッセージがキューから削除されます。</span><span class="sxs-lookup"><span data-stu-id="df969-112">This will delete the message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="df969-113">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="df969-113">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="df969-114">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="df969-114">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="df969-115">この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="df969-115">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="iReceiverClient.DeadLetterAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="df969-116">対応する配信不能メッセージのロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="df969-116">The lock token of the corresponding message to deadletter.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="df969-117">サブをキューに移動中に変更するメッセージのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="df969-117">The properties of the message to modify while moving to sub-queue.</span></span></param>
        <summary>
            <span data-ttu-id="df969-118">メッセージを配信不能サブキューに移動します。</span><span class="sxs-lookup"><span data-stu-id="df969-118">Moves a message to the deadletter sub-queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="df969-119">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="df969-119">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="df969-120">を配信不能キューからメッセージを受信するために必要になります、新しい<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />、対応するパスにします。</span><span class="sxs-lookup"><span data-stu-id="df969-120">In order to receive a message from the deadletter queue, you will need a new <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, with the corresponding path.</span></span>
            <span data-ttu-id="df969-121">使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />これを支援します。</span><span class="sxs-lookup"><span data-stu-id="df969-121">You can use <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> to help with this.</span></span>
            <span data-ttu-id="df969-122">この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="df969-122">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, string deadLetterReason, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, deadLetterReason As String, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task" Usage="iReceiverClient.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
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
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="df969-123">対応する配信不能メッセージのロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="df969-123">The lock token of the corresponding message to deadletter.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="df969-124">メッセージの配信不能の理由です。</span><span class="sxs-lookup"><span data-stu-id="df969-124">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="df969-125">メッセージの配信不能のエラーの説明。</span><span class="sxs-lookup"><span data-stu-id="df969-125">The error description for deadlettering the message.</span></span></param>
        <summary>
            <span data-ttu-id="df969-126">メッセージを配信不能サブキューに移動します。</span><span class="sxs-lookup"><span data-stu-id="df969-126">Moves a message to the deadletter sub-queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="df969-127">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="df969-127">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="df969-128">を配信不能キューからメッセージを受信するために必要になります、新しい<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />、対応するパスにします。</span><span class="sxs-lookup"><span data-stu-id="df969-128">In order to receive a message from the deadletter queue, you will need a new <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, with the corresponding path.</span></span>
            <span data-ttu-id="df969-129">使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />これを支援します。</span><span class="sxs-lookup"><span data-stu-id="df969-129">You can use <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> to help with this.</span></span>
            <span data-ttu-id="df969-130">この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="df969-130">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="df969-131">パスを取得、<see cref="T:Microsoft.Azure.ServiceBus.Core.IReceiverClient" />です。</span><span class="sxs-lookup"><span data-stu-id="df969-131">Gets the path of the <see cref="T:Microsoft.Azure.ServiceBus.Core.IReceiverClient" />.</span></span> <span data-ttu-id="df969-132">これは、キューの名前またはサブスクリプションの完全なパスのいずれかです。</span><span class="sxs-lookup"><span data-stu-id="df969-132">This is either the name of the queue, or the full path of the subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.ServiceBus.Core.IReceiverClient.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="df969-133">メッセージ フローと、1 つのアプリケーションが要求する前にローカルの取得のためすぐに使用できるメッセージがあることを目指していますによってプリフェッチ速度では、受信を使用します。</span><span class="sxs-lookup"><span data-stu-id="df969-133">Prefetch speeds up the message flow by aiming to have a message readily available for local retrieval when and before the application asks for one using Receive.</span></span>
            <span data-ttu-id="df969-134">メッセージ数の PrefetchCount をプリフェッチする 0 以外の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="df969-134">Setting a non-zero value prefetches PrefetchCount number of messages.</span></span>
            <span data-ttu-id="df969-135">プリフェッチをオフに値を 0 に設定します。</span><span class="sxs-lookup"><span data-stu-id="df969-135">Setting the value to zero turns prefetch off.</span></span>
            <span data-ttu-id="df969-136">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="df969-136">Defaults to 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="df969-137">プリフェッチを有効にすると、受信側はサイレント モードでどのようなアプリケーションすぐに確認のより PrefetchCount 上限に達するまで、多くのメッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="df969-137">When Prefetch is enabled, the receiver will quietly acquire more messages, up to the PrefetchCount limit, than what the application immediately asks for.</span></span> <span data-ttu-id="df969-138">初期の単一の受信/ReceiveAsync 呼び出ししたがって取得するメッセージに対して返されるとすぐに利用可能な即時の消費量と、クライアントでは、バック グラウンドでプリフェッチ バッファーが満杯にさらにメッセージの取得に進みます。</span><span class="sxs-lookup"><span data-stu-id="df969-138">A single initial Receive/ReceiveAsync call will therefore acquire a message for immediate consumption that will be returned as soon as available, and the client will proceed to acquire further messages to fill the prefetch buffer in the background.</span></span>
            </para>
          <para>
            <span data-ttu-id="df969-139">メッセージは、プリフェッチ バッファーで使用できますが、後続の ReceiveAsync 呼び出しは、バッファーからすぐに満たされ、空き領域ができるように、バック グラウンドでバッファーが補充です。にない場合のメッセージ配信のために使用できる、受信操作は、バッファーのドレインを実行し、まで待機するかどおりをブロックします。</span><span class="sxs-lookup"><span data-stu-id="df969-139">While messages are available in the prefetch buffer, any subsequent ReceiveAsync calls will be immediately satisfied from the buffer, and the buffer is replenished in the background as space becomes available.If there are no messages available for delivery, the receive operation will drain the buffer and then wait or block as expected.</span></span>
            </para>
          <para><span data-ttu-id="df969-140">この値に更新プログラムは、サービスの受信呼び出しは、[次へ] を有効になります。</span><span class="sxs-lookup"><span data-stu-id="df969-140">Updates to this value take effect on the next receive call to the service.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceiveMode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.ReceiveMode : Microsoft.Azure.ServiceBus.ReceiveMode" Usage="Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.ReceiveMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="df969-141">取得、<see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />現在受信機のです。</span><span class="sxs-lookup"><span data-stu-id="df969-141">Gets the <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> of the current receiver.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), registerHandlerOptions As MessageHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit" Usage="iReceiverClient.RegisterMessageHandler (handler, messageHandlerOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="registerHandlerOptions" Type="Microsoft.Azure.ServiceBus.MessageHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handler"><span data-ttu-id="df969-142">A<see cref="T:System.Func`3" />メッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="df969-142">A <see cref="T:System.Func`3" /> that processes messages.</span></span></param>
        <param name="messageHandlerOptions"><span data-ttu-id="df969-143"><see cref="T:Microsoft.Azure.ServiceBus.MessageHandlerOptions" />オプション、ポンプの設定を構成するために使用します。</span><span class="sxs-lookup"><span data-stu-id="df969-143">The <see cref="T:Microsoft.Azure.ServiceBus.MessageHandlerOptions" /> options used to configure the settings of the pump.</span></span></param>
        <summary>
            <span data-ttu-id="df969-144">継続的に、エンティティからメッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="df969-144">Receive messages continuously from the entity.</span></span> <span data-ttu-id="df969-145">メッセージ ハンドラーを登録し、メッセージを受信する新しいスレッドを開始します。</span><span class="sxs-lookup"><span data-stu-id="df969-145">Registers a message handler and begins a new thread to receive messages.</span></span>
            <span data-ttu-id="df969-146">このハンドラー (<see cref="T:System.Func`3" />)、受信側で新しいメッセージを受信するたびにでは待機します。</span><span class="sxs-lookup"><span data-stu-id="df969-146">This handler(<see cref="T:System.Func`3" />) is awaited on every time a new message is received by the receiver.</span></span>
            </summary>
        <remarks><span data-ttu-id="df969-147">受信レートを高速化するプリフェッチを有効にします。</span><span class="sxs-lookup"><span data-stu-id="df969-147">Enable prefetch to speed up the receive rate.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="iReceiverClient.RegisterMessageHandler (handler, exceptionReceivedHandler)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="exceptionReceivedHandler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="handler"><span data-ttu-id="df969-148">A<see cref="T:System.Func`3" />メッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="df969-148">A <see cref="T:System.Func`3" /> that processes messages.</span></span></param>
        <param name="exceptionReceivedHandler"><span data-ttu-id="df969-149">A<see cref="T:System.Func`2" />例外時に呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="df969-149">A <see cref="T:System.Func`2" /> that is invoked during exceptions.</span></span>
            <span data-ttu-id="df969-150"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />例外に関するコンテキスト情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="df969-150"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" /> contains contextual information regarding the exception.</span></span></param>
        <summary>
            <span data-ttu-id="df969-151">継続的に、エンティティからメッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="df969-151">Receive messages continuously from the entity.</span></span> <span data-ttu-id="df969-152">メッセージ ハンドラーを登録し、メッセージを受信する新しいスレッドを開始します。</span><span class="sxs-lookup"><span data-stu-id="df969-152">Registers a message handler and begins a new thread to receive messages.</span></span>
            <span data-ttu-id="df969-153">このハンドラー (<see cref="T:System.Func`3" />)、受信側で新しいメッセージを受信するたびにでは待機します。</span><span class="sxs-lookup"><span data-stu-id="df969-153">This handler(<see cref="T:System.Func`3" />) is awaited on every time a new message is received by the receiver.</span></span>
            </summary>
        <remarks><span data-ttu-id="df969-154">受信レートを高速化するプリフェッチを有効にします。</span><span class="sxs-lookup"><span data-stu-id="df969-154">Enable prefetch to speed up the receive rate.</span></span>
            <span data-ttu-id="df969-155">使用して<see cref="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />ポンプの設定を構成します。</span><span class="sxs-lookup"><span data-stu-id="df969-155">Use <see cref="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" /> to configure the settings of the pump.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>