<Type Name="ISubscriptionClient" FullName="Microsoft.Azure.ServiceBus.ISubscriptionClient">
  <TypeSignature Language="C#" Value="public interface ISubscriptionClient : Microsoft.Azure.ServiceBus.Core.IReceiverClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISubscriptionClient implements class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISubscriptionClient&#xA;Implements IReceiverClient" />
  <TypeSignature Language="F#" Value="type ISubscriptionClient = interface&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
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
             <span data-ttu-id="968b4-101">SubscriptionClient は、すべての基本的な対話をサービス バスのサブスクリプションで使用できます。</span><span class="sxs-lookup"><span data-stu-id="968b4-101">SubscriptionClient can be used for all basic interactions with a Service Bus Subscription.</span></span>
             </summary>
    <remarks><span data-ttu-id="968b4-102">使用して<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />の高度な機能セット。</span><span class="sxs-lookup"><span data-stu-id="968b4-102">Use <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> for advanced set of functionality.</span></span></remarks>
    <example>
             <span data-ttu-id="968b4-103">新しい SubscriptionClient を作成します。</span><span class="sxs-lookup"><span data-stu-id="968b4-103">Create a new SubscriptionClient</span></span>
             <code>
             ISubscriptionClient subscriptionClient = new SubscriptionClient(
                 namespaceConnectionString,
                 topicName,
                 subscriptionName,
                 ReceiveMode.PeekLock,
                 RetryExponential);
             </code>
            
             <span data-ttu-id="968b4-104">メッセージを受信するたびに呼び出されるメッセージのハンドラーを登録します。</span><span class="sxs-lookup"><span data-stu-id="968b4-104">Register a message handler which will be invoked every time a message is received.</span></span>
             <code>
             subscriptionClient.RegisterMessageHandler(
                    async (message, token) =&gt;
                    {
                        // Process the message
                        Console.WriteLine($"Received message: SequenceNumber:{message.SystemProperties.SequenceNumber} Body:{Encoding.UTF8.GetString(message.Body)}");
            
                        // Complete the message so that it is not received again.
                        // This can be done only if the subscriptionClient is opened in ReceiveMode.PeekLock mode.
                        await subscriptionClient.CompleteAsync(message.SystemProperties.LockToken);
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
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (Microsoft.Azure.ServiceBus.RuleDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddRuleAsync(class Microsoft.Azure.ServiceBus.RuleDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.AddRuleAsync(Microsoft.Azure.ServiceBus.RuleDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function AddRuleAsync (description As RuleDescription) As Task" />
      <MemberSignature Language="F#" Value="abstract member AddRuleAsync : Microsoft.Azure.ServiceBus.RuleDescription -&gt; System.Threading.Tasks.Task" Usage="iSubscriptionClient.AddRuleAsync description" />
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
        <Parameter Name="description" Type="Microsoft.Azure.ServiceBus.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="968b4-105">規則の説明を追加するルールを提供します。</span><span class="sxs-lookup"><span data-stu-id="968b4-105">The rule description that provides the rule to add.</span></span></param>
        <summary>
            <span data-ttu-id="968b4-106">サブスクリプションに達しようとしてトピックからメッセージをフィルター処理の現在のサブスクリプションにルールを追加します。</span><span class="sxs-lookup"><span data-stu-id="968b4-106">Adds a rule to the current subscription to filter the messages reaching from topic to the subscription.</span></span>
            </summary>
        <returns><span data-ttu-id="968b4-107">非同期の追加ルールの操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="968b4-107">A task instance that represents the asynchronous add rule operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="968b4-108">規則は、トピックからメッセージがサブスクリプションに反映されるようにフィルターを決定するサブスクリプションを追加できます。</span><span class="sxs-lookup"><span data-stu-id="968b4-108">You can add rules to the subscription that will decide filter which messages from the topic should reach the subscription.</span></span>
            <span data-ttu-id="968b4-109">既定の<see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" />という名前のルール<see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" />サブスクリプションの作成中には常に追加します。</span><span class="sxs-lookup"><span data-stu-id="968b4-109">A default <see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" /> rule named <see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" /> is always added while creation of the Subscription.</span></span>
            <span data-ttu-id="968b4-110">個別の名前を持つ複数のルールは、同じサブスクリプションに追加できます。</span><span class="sxs-lookup"><span data-stu-id="968b4-110">You can add multiple rules with distinct names to the same subscription.</span></span>
            <span data-ttu-id="968b4-111">複数のフィルターは、論理 OR 条件を使用して相互に結合します。</span><span class="sxs-lookup"><span data-stu-id="968b4-111">Multiple filters combine with each other using logical OR condition.</span></span> <span data-ttu-id="968b4-112">つまり、任意のフィルターが成功した場合、メッセージに渡されますサブスクリプション。</span><span class="sxs-lookup"><span data-stu-id="968b4-112">i.e., If any filter succeeds, the message is passed on to the subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (string ruleName, Microsoft.Azure.ServiceBus.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddRuleAsync(string ruleName, class Microsoft.Azure.ServiceBus.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.AddRuleAsync(System.String,Microsoft.Azure.ServiceBus.Filter)" />
      <MemberSignature Language="F#" Value="abstract member AddRuleAsync : string * Microsoft.Azure.ServiceBus.Filter -&gt; System.Threading.Tasks.Task" Usage="iSubscriptionClient.AddRuleAsync (ruleName, filter)" />
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
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.Azure.ServiceBus.Filter" />
      </Parameters>
      <Docs>
        <param name="ruleName">To be added.</param>
        <param name="filter"><span data-ttu-id="968b4-113">対象となるメッセージが一致するフィルター式です。</span><span class="sxs-lookup"><span data-stu-id="968b4-113">The filter expression against which messages will be matched.</span></span></param>
        <summary>
            <span data-ttu-id="968b4-114">サブスクリプションに達しようとしてトピックからメッセージをフィルター処理の現在のサブスクリプションにルールを追加します。</span><span class="sxs-lookup"><span data-stu-id="968b4-114">Adds a rule to the current subscription to filter the messages reaching from topic to the subscription.</span></span>
            </summary>
        <returns><span data-ttu-id="968b4-115">非同期の追加ルールの操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="968b4-115">A task instance that represents the asynchronous add rule operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="968b4-116">規則は、トピックからメッセージがサブスクリプションに反映されるようにフィルターを決定するサブスクリプションを追加できます。</span><span class="sxs-lookup"><span data-stu-id="968b4-116">You can add rules to the subscription that will decide filter which messages from the topic should reach the subscription.</span></span>
            <span data-ttu-id="968b4-117">既定の<see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" />という名前のルール<see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" />サブスクリプションの作成中には常に追加します。</span><span class="sxs-lookup"><span data-stu-id="968b4-117">A default <see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" /> rule named <see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" /> is always added while creation of the Subscription.</span></span>
            <span data-ttu-id="968b4-118">個別の名前を持つ複数のルールは、同じサブスクリプションに追加できます。</span><span class="sxs-lookup"><span data-stu-id="968b4-118">You can add multiple rules with distinct names to the same subscription.</span></span>
            <span data-ttu-id="968b4-119">複数のフィルターは、論理 OR 条件を使用して相互に結合します。</span><span class="sxs-lookup"><span data-stu-id="968b4-119">Multiple filters combine with each other using logical OR condition.</span></span> <span data-ttu-id="968b4-120">つまり、任意のフィルターが成功した場合、メッセージに渡されますサブスクリプション。</span><span class="sxs-lookup"><span data-stu-id="968b4-120">i.e., If any filter succeeds, the message is passed on to the subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRulesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt; GetRulesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt; GetRulesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.GetRulesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRulesAsync () As Task(Of IEnumerable(Of RuleDescription))" />
      <MemberSignature Language="F#" Value="abstract member GetRulesAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt;" Usage="iSubscriptionClient.GetRulesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="968b4-121">サブスクリプションに関連付けられているすべてのルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="968b4-121">Get all rules associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.SessionHandlerOptions -&gt; unit" Usage="iSubscriptionClient.RegisterSessionHandler (handler, sessionHandlerOptions)" />
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
        <param name="handler"><span data-ttu-id="968b4-122">A<see cref="T:System.Func`4" />メッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="968b4-122">A <see cref="T:System.Func`4" /> that processes messages.</span></span>
            <span data-ttu-id="968b4-123"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />セッション情報が含まれており、配信不能完了/破棄/やその他のような操作の実行に使用する必要があります、<see cref="T:Microsoft.Azure.ServiceBus.Message" /></span><span class="sxs-lookup"><span data-stu-id="968b4-123"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> contains the session information, and must be used to perform Complete/Abandon/Deadletter or other such operations on the <see cref="T:Microsoft.Azure.ServiceBus.Message" /></span></span></param>
        <param name="sessionHandlerOptions"><span data-ttu-id="968b4-124">オプションは、セッションのポンプの設定を構成するために使用します。</span><span class="sxs-lookup"><span data-stu-id="968b4-124">Options used to configure the settings of the session pump.</span></span></param>
        <summary>
            <span data-ttu-id="968b4-125">サブスクリプションから継続的にセッションのメッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="968b4-125">Receive session messages continuously from the subscription.</span></span> <span data-ttu-id="968b4-126">メッセージ ハンドラーを登録し、セッション メッセージを受信する新しいスレッドを開始します。</span><span class="sxs-lookup"><span data-stu-id="968b4-126">Registers a message handler and begins a new thread to receive session-messages.</span></span>
            <span data-ttu-id="968b4-127">このハンドラー (<see cref="T:System.Func`4" />) サブスクリプション クライアントが新しいメッセージを受信するたびにでは待機します。</span><span class="sxs-lookup"><span data-stu-id="968b4-127">This handler(<see cref="T:System.Func`4" />) is awaited on every time a new message is received by the subscription client.</span></span>
            </summary>
        <remarks><span data-ttu-id="968b4-128">受信レートを高速化するプリフェッチを有効にします。</span><span class="sxs-lookup"><span data-stu-id="968b4-128">Enable prefetch to speed up the receive rate.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handler As Func(Of IMessageSession, Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="iSubscriptionClient.RegisterSessionHandler (handler, exceptionReceivedHandler)" />
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
        <param name="handler"><span data-ttu-id="968b4-129">A<see cref="T:System.Func`4" />メッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="968b4-129">A <see cref="T:System.Func`4" /> that processes messages.</span></span>
            <span data-ttu-id="968b4-130"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />セッション情報が含まれており、配信不能完了/破棄/やその他のような操作の実行に使用する必要があります、<see cref="T:Microsoft.Azure.ServiceBus.Message" /></span><span class="sxs-lookup"><span data-stu-id="968b4-130"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> contains the session information, and must be used to perform Complete/Abandon/Deadletter or other such operations on the <see cref="T:Microsoft.Azure.ServiceBus.Message" /></span></span></param>
        <param name="exceptionReceivedHandler"><span data-ttu-id="968b4-131">A<see cref="T:System.Func`2" />例外時に呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="968b4-131">A <see cref="T:System.Func`2" /> that is invoked during exceptions.</span></span>
            <span data-ttu-id="968b4-132"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />例外に関するコンテキスト情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="968b4-132"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" /> contains contextual information regarding the exception.</span></span></param>
        <summary>
            <span data-ttu-id="968b4-133">サブスクリプションから継続的にセッションのメッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="968b4-133">Receive session messages continuously from the subscription.</span></span> <span data-ttu-id="968b4-134">メッセージ ハンドラーを登録し、セッション メッセージを受信する新しいスレッドを開始します。</span><span class="sxs-lookup"><span data-stu-id="968b4-134">Registers a message handler and begins a new thread to receive session-messages.</span></span>
            <span data-ttu-id="968b4-135">このハンドラー (<see cref="T:System.Func`4" />) サブスクリプション クライアントが新しいメッセージを受信するたびにでは待機します。</span><span class="sxs-lookup"><span data-stu-id="968b4-135">This handler(<see cref="T:System.Func`4" />) is awaited on every time a new message is received by the subscription client.</span></span>
            </summary>
        <remarks><span data-ttu-id="968b4-136">受信レートを高速化するプリフェッチを有効にします。</span><span class="sxs-lookup"><span data-stu-id="968b4-136">Enable prefetch to speed up the receive rate.</span></span>
            <span data-ttu-id="968b4-137">使用して<see cref="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />ポンプの設定を構成します。</span><span class="sxs-lookup"><span data-stu-id="968b4-137">Use <see cref="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" /> to configure the settings of the pump.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveRuleAsync (string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveRuleAsync(string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RemoveRuleAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveRuleAsync (ruleName As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveRuleAsync : string -&gt; System.Threading.Tasks.Task" Usage="iSubscriptionClient.RemoveRuleAsync ruleName" />
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
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ruleName"><span data-ttu-id="968b4-138">ルールの名前。</span><span class="sxs-lookup"><span data-stu-id="968b4-138">The name of the rule.</span></span></param>
        <summary>
            <span data-ttu-id="968b4-139">によって識別されるサブスクリプションの規則を削除します<paramref name="ruleName" />です。</span><span class="sxs-lookup"><span data-stu-id="968b4-139">Removes the rule on the subscription identified by <paramref name="ruleName" />.</span></span>
            </summary>
        <returns><span data-ttu-id="968b4-140">非同期の削除規則の操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="968b4-140">A task instance that represents the asynchronous remove rule operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionName">
      <MemberSignature Language="C#" Value="public string SubscriptionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ISubscriptionClient.SubscriptionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionName As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionName : string" Usage="Microsoft.Azure.ServiceBus.ISubscriptionClient.SubscriptionName" />
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
            <span data-ttu-id="968b4-141">サブスクリプションの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="968b4-141">Gets the name of subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicPath">
      <MemberSignature Language="C#" Value="public string TopicPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ISubscriptionClient.TopicPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TopicPath As String" />
      <MemberSignature Language="F#" Value="member this.TopicPath : string" Usage="Microsoft.Azure.ServiceBus.ISubscriptionClient.TopicPath" />
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
            <span data-ttu-id="968b4-142">このサブスクリプションのトピックのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="968b4-142">Gets the path of the topic, for this subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>