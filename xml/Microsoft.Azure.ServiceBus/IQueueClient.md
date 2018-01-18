<Type Name="IQueueClient" FullName="Microsoft.Azure.ServiceBus.IQueueClient">
  <TypeSignature Language="C#" Value="public interface IQueueClient : Microsoft.Azure.ServiceBus.Core.IReceiverClient, Microsoft.Azure.ServiceBus.Core.ISenderClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IQueueClient implements class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.Core.ISenderClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.IQueueClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IQueueClient&#xA;Implements IReceiverClient, ISenderClient" />
  <TypeSignature Language="F#" Value="type IQueueClient = interface&#xA;    interface IReceiverClient&#xA;    interface IClientEntity&#xA;    interface ISenderClient" />
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
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.ISenderClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="6e1a9-101">QueueClient は、すべての基本的な対話 Service Bus キューを使用できます。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-101">QueueClient can be used for all basic interactions with a Service Bus Queue.</span></span>
             </summary>
    <remarks><span data-ttu-id="6e1a9-102">使用して<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageSender" />または<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />の高度な機能セット。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-102">Use <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageSender" /> or <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" /> for advanced set of functionality.</span></span></remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.QueueClient" />
    <example>
             <span data-ttu-id="6e1a9-103">新しい QueueClient を作成します。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-103">Create a new QueueClient</span></span>
             <code>
             IQueueClient queueClient = new QueueClient(
                 namespaceConnectionString,
                 queueName,
                 ReceiveMode.PeekLock,
                 RetryExponential);
             </code>
            
             <span data-ttu-id="6e1a9-104">キューにメッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-104">Send a message to the queue:</span></span>
             <code>
             byte[] data = GetData();
             await queueClient.SendAsync(data);
             </code>
            
             <span data-ttu-id="6e1a9-105">メッセージを受信するたびに呼び出されるメッセージのハンドラーを登録します。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-105">Register a message handler which will be invoked every time a message is received.</span></span>
             <code>
             queueClient.RegisterMessageHandler(
                    async (message, token) =&gt;
                    {
                        // Process the message
                        Console.WriteLine($"Received message: SequenceNumber:{message.SystemProperties.SequenceNumber} Body:{Encoding.UTF8.GetString(message.Body)}");
            
                        // Complete the message so that it is not received again.
                        // This can be done only if the queueClient is opened in ReceiveMode.PeekLock mode.
                        await queueClient.CompleteAsync(message.SystemProperties.LockToken);
                    },
                    async (exceptionEvent) =&gt;
                    {
                        // Process the exception
                        Console.WriteLine("Exception = " + exceptionEvent.Exception);
                        return Task.CompletedTask;
                    });
             </code></example>
  </Docs>
  <Members>
    <Member MemberName="QueueName">
      <MemberSignature Language="C#" Value="public string QueueName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QueueName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.IQueueClient.QueueName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueueName As String" />
      <MemberSignature Language="F#" Value="member this.QueueName : string" Usage="Microsoft.Azure.ServiceBus.IQueueClient.QueueName" />
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
            <span data-ttu-id="6e1a9-106">キューの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-106">Gets the name of the queue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IQueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.SessionHandlerOptions -&gt; unit" Usage="iQueueClient.RegisterSessionHandler (handler, sessionHandlerOptions)" />
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
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="sessionHandlerOptions" Type="Microsoft.Azure.ServiceBus.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handler"><span data-ttu-id="6e1a9-107">A<see cref="T:System.Func`4" />メッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-107">A <see cref="T:System.Func`4" /> that processes messages.</span></span>
            <span data-ttu-id="6e1a9-108"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />セッション情報が含まれており、配信不能完了/破棄/やその他のような操作の実行に使用する必要があります、<see cref="T:Microsoft.Azure.ServiceBus.Message" /></span><span class="sxs-lookup"><span data-stu-id="6e1a9-108"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> contains the session information, and must be used to perform Complete/Abandon/Deadletter or other such operations on the <see cref="T:Microsoft.Azure.ServiceBus.Message" /></span></span></param>
        <param name="sessionHandlerOptions"><span data-ttu-id="6e1a9-109">オプションは、セッションのポンプの設定を構成するために使用します。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-109">Options used to configure the settings of the session pump.</span></span></param>
        <summary>
            <span data-ttu-id="6e1a9-110">継続的に、キューからセッション メッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-110">Receive session messages continuously from the queue.</span></span> <span data-ttu-id="6e1a9-111">メッセージ ハンドラーを登録し、セッション メッセージを受信する新しいスレッドを開始します。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-111">Registers a message handler and begins a new thread to receive session-messages.</span></span>
            <span data-ttu-id="6e1a9-112">このハンドラー (<see cref="T:System.Func`4" />)、新しいメッセージがキュー クライアントによって受信されるたびにでは待機します。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-112">This handler(<see cref="T:System.Func`4" />) is awaited on every time a new message is received by the queue client.</span></span>
            </summary>
        <remarks><span data-ttu-id="6e1a9-113">受信レートを高速化するプリフェッチを有効にします。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-113">Enable prefetch to speed up the receive rate.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IQueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handler As Func(Of IMessageSession, Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="iQueueClient.RegisterSessionHandler (handler, exceptionReceivedHandler)" />
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
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="exceptionReceivedHandler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="handler"><span data-ttu-id="6e1a9-114">A<see cref="T:System.Func`4" />メッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-114">A <see cref="T:System.Func`4" /> that processes messages.</span></span>
            <span data-ttu-id="6e1a9-115"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />セッション情報が含まれており、配信不能完了/破棄/やその他のような操作の実行に使用する必要があります、<see cref="T:Microsoft.Azure.ServiceBus.Message" /></span><span class="sxs-lookup"><span data-stu-id="6e1a9-115"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> contains the session information, and must be used to perform Complete/Abandon/Deadletter or other such operations on the <see cref="T:Microsoft.Azure.ServiceBus.Message" /></span></span></param>
        <param name="exceptionReceivedHandler"><span data-ttu-id="6e1a9-116">A<see cref="T:System.Func`2" />例外時に呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-116">A <see cref="T:System.Func`2" /> that is invoked during exceptions.</span></span>
            <span data-ttu-id="6e1a9-117"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />例外に関するコンテキスト情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-117"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" /> contains contextual information regarding the exception.</span></span></param>
        <summary>
            <span data-ttu-id="6e1a9-118">継続的に、キューからセッション メッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-118">Receive session messages continuously from the queue.</span></span> <span data-ttu-id="6e1a9-119">メッセージ ハンドラーを登録し、セッション メッセージを受信する新しいスレッドを開始します。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-119">Registers a message handler and begins a new thread to receive session-messages.</span></span>
            <span data-ttu-id="6e1a9-120">このハンドラー (<see cref="T:System.Func`4" />)、新しいメッセージがキュー クライアントによって受信されるたびにでは待機します。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-120">This handler(<see cref="T:System.Func`4" />) is awaited on every time a new message is received by the queue client.</span></span>
            </summary>
        <remarks><span data-ttu-id="6e1a9-121">受信レートを高速化するプリフェッチを有効にします。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-121">Enable prefetch to speed up the receive rate.</span></span>
            <span data-ttu-id="6e1a9-122">使用して<see cref="M:Microsoft.Azure.ServiceBus.IQueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />ポンプの設定を構成します。</span><span class="sxs-lookup"><span data-stu-id="6e1a9-122">Use <see cref="M:Microsoft.Azure.ServiceBus.IQueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" /> to configure the settings of the pump.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>