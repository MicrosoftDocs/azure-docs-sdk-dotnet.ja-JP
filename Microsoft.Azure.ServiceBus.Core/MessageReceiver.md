<Type Name="MessageReceiver" FullName="Microsoft.Azure.ServiceBus.Core.MessageReceiver">
  <TypeSignature Language="C#" Value="public class MessageReceiver : Microsoft.Azure.ServiceBus.ClientEntity, Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MessageReceiver extends Microsoft.Azure.ServiceBus.ClientEntity implements class Microsoft.Azure.ServiceBus.Core.IMessageReceiver, class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />
  <TypeSignature Language="VB.NET" Value="Public Class MessageReceiver&#xA;Inherits ClientEntity&#xA;Implements IMessageReceiver" />
  <TypeSignature Language="F#" Value="type MessageReceiver = class&#xA;    inherit ClientEntity&#xA;    interface IMessageReceiver&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.IMessageReceiver</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="fdb3a-101">キューとサブスクリプションからメッセージを受信し、それらを認識する、MessageReceiver を使用できます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-101">The MessageReceiver can be used to receive messages from Queues and Subscriptions and acknowledge them.</span></span>
             </summary>
    <remarks>
             <span data-ttu-id="fdb3a-102">MessageReceiver は高度な機能を提供する、<see cref="T:Microsoft.Azure.ServiceBus.QueueClient" />または<see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-102">The MessageReceiver provides advanced functionality that is not found in the <see cref="T:Microsoft.Azure.ServiceBus.QueueClient" /> or <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />.</span></span> <span data-ttu-id="fdb3a-103">たとえば、<see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />を必要に応じて、メッセージを受信することができますもする必要しますが、ありますを使用してロックを手動で更新する<see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-103">For instance, <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />, which allows you to receive messages on demand, but also requires you to manually renew locks using <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />.</span></span>
             <span data-ttu-id="fdb3a-104">AMQP プロトコルを使用して、サービスと通信します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-104">It uses AMQP protocol to communicate with service.</span></span>
             </remarks>
    <example>
             <span data-ttu-id="fdb3a-105">サブスクリプションからメッセージを受信する新しい MessageReceiver を作成します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-105">Create a new MessageReceiver to receive a message from a Subscription</span></span>
             <code>
             IMessageReceiver messageReceiver = new MessageReceiver(
                 namespaceConnectionString,
                 EntityNameHelper.FormatSubscriptionPath(topicName, subscriptionName),
                 ReceiveMode.PeekLock);
             </code>
            
             <span data-ttu-id="fdb3a-106">サブスクリプションからメッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-106">Receive a message from the Subscription.</span></span>
             <code>
             var message = await messageReceiver.ReceiveAsync();
             await messageReceiver.CompleteAsync(message.SystemProperties.LockToken);
             </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageReceiver (Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null, int prefetchCount = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy, int32 prefetchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.#ctor(Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.Core.MessageReceiver : Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy * int -&gt; Microsoft.Azure.ServiceBus.Core.MessageReceiver" Usage="new Microsoft.Azure.ServiceBus.Core.MessageReceiver (connectionStringBuilder, receiveMode, retryPolicy, prefetchCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionStringBuilder" Type="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
        <Parameter Name="prefetchCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="connectionStringBuilder"><span data-ttu-id="fdb3a-107"><see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />エンティティ レベルの接続の詳細を持ちます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-107">The <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /> having entity level connection details.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="fdb3a-108"><see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />メッセージを受信する方法を指定するために使用します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-108">The <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> used to specify how messages are received.</span></span> <span data-ttu-id="fdb3a-109">PeekLock モードに既定値です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-109">Defaults to PeekLock mode.</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="fdb3a-110"><see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> Service Bus との通信に使用されます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-110">The <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> that will be used when communicating with Service Bus.</span></span> <span data-ttu-id="fdb3a-111">既定値は <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /> です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-111">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" />.</span></span></param>
        <param name="prefetchCount"><span data-ttu-id="fdb3a-112"><see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" />この受信者は受信操作が保留されているかどうかに関係なくアクティブに受信メッセージの数の上限を指定します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-112">The <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" /> that specifies the upper limit of messages this receiver will actively receive regardless of whether a receive operation is pending.</span></span> <span data-ttu-id="fdb3a-113">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-113">Defaults to 0.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-114">新しい MessageReceiver を作成、<see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-114">Creates a new MessageReceiver from a <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />.</span></span>
            </summary>
        <remarks><span data-ttu-id="fdb3a-115">最初の操作中に開かれると、エンティティへの新しい接続を作成します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-115">Creates a new connection to the entity, which is opened during the first operation.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageReceiver (string connectionString, string entityPath, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null, int prefetchCount = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string entityPath, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy, int32 prefetchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.Core.MessageReceiver : string * string * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy * int -&gt; Microsoft.Azure.ServiceBus.Core.MessageReceiver" Usage="new Microsoft.Azure.ServiceBus.Core.MessageReceiver (connectionString, entityPath, receiveMode, retryPolicy, prefetchCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
        <Parameter Name="prefetchCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="fdb3a-116">Service Bus との通信に使用される Namespace 接続文字列。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-116">Namespace connection string used to communicate with Service Bus.</span></span> <span data-ttu-id="fdb3a-117">エンティティの詳細が含まれていない必要があります。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-117">Must not contain Entity details.</span></span></param>
        <param name="entityPath"><span data-ttu-id="fdb3a-118">この受信者を表すエンティティのパス。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-118">The path of the entity for this receiver.</span></span> <span data-ttu-id="fdb3a-119">キューのこれは、名前ですが、パスになりますこのサブスクリプションはします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-119">For Queues this will be the name, but for Subscriptions this will be the path.</span></span>
            <span data-ttu-id="fdb3a-120">使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatSubscriptionPath(System.String,System.String)" />、このパスを作成するためにします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-120">You can use <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatSubscriptionPath(System.String,System.String)" />, to help create this path.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="fdb3a-121"><see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />メッセージを受信する方法を指定するために使用します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-121">The <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> used to specify how messages are received.</span></span> <span data-ttu-id="fdb3a-122">PeekLock モードに既定値です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-122">Defaults to PeekLock mode.</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="fdb3a-123"><see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> Service Bus との通信に使用されます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-123">The <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> that will be used when communicating with Service Bus.</span></span> <span data-ttu-id="fdb3a-124">既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span><span class="sxs-lookup"><span data-stu-id="fdb3a-124">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span></span></param>
        <param name="prefetchCount"><span data-ttu-id="fdb3a-125"><see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" />この受信者は受信操作が保留されているかどうかに関係なくアクティブに受信メッセージの数の上限を指定します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-125">The <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" /> that specifies the upper limit of messages this receiver will actively receive regardless of whether a receive operation is pending.</span></span> <span data-ttu-id="fdb3a-126">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-126">Defaults to 0.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-127">指定された接続文字列およびエンティティ パスから新しい MessageReceiver を作成します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-127">Creates a new MessageReceiver from a specified connection string and entity path.</span></span>
            </summary>
        <remarks><span data-ttu-id="fdb3a-128">最初の操作中に開かれると、エンティティへの新しい接続を作成します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-128">Creates a new connection to the entity, which is opened during the first operation.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.AbandonAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;AbandonAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="fdb3a-129">中止するのには、対応するメッセージのロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-129">The lock token of the corresponding message to abandon.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="fdb3a-130">メッセージの破棄中に変更するメッセージのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-130">The properties of the message to modify while abandoning the message.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-131">破棄、<see cref="T:Microsoft.Azure.ServiceBus.Message" />ロックのトークンを使用します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-131">Abandons a <see cref="T:Microsoft.Azure.ServiceBus.Message" /> using a lock token.</span></span> <span data-ttu-id="fdb3a-132">これにより、メッセージ処理用にもう一度使用できます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-132">This will make the message available again for processing.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="fdb3a-133">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-133">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="fdb3a-134">メッセージを破棄すると、メッセージの配信回数が増加します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-134">Abandoning a message will increase the delivery count on the message.</span></span>
            <span data-ttu-id="fdb3a-135">この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-135">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (System.Collections.Generic.IEnumerable&lt;string&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.CompleteAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockTokens As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.CompleteAsync lockTokens" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.CompleteAsync(System.Collections.Generic.IEnumerable{System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;CompleteAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="lockTokens"><span data-ttu-id="fdb3a-136"><see cref="T:System.Collections.Generic.IEnumerable`1" />を完了する、対応するメッセージのロック トークンを含んでいます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-136">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> containing the lock tokens of the corresponding messages to complete.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-137">完了する一連の<see cref="T:Microsoft.Azure.ServiceBus.Message" />ロック トークンのリストを使用します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-137">Completes a series of <see cref="T:Microsoft.Azure.ServiceBus.Message" /> using a list of lock tokens.</span></span> <span data-ttu-id="fdb3a-138">これにより、サービスからのメッセージが削除されます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-138">This will delete the message from the service.</span></span>
            </summary>
        <returns><span data-ttu-id="fdb3a-139">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-139">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="fdb3a-140">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-140">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="fdb3a-141">この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-141">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.CompleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : string -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.CompleteAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.CompleteAsync(System.String)</InterfaceMember>
      </Implements>
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
        <param name="lockToken"><span data-ttu-id="fdb3a-142">完了する、対応するメッセージのロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-142">The lock token of the corresponding message to complete.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-143">完了、<see cref="T:Microsoft.Azure.ServiceBus.Message" />のロック トークンを使用します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-143">Completes a <see cref="T:Microsoft.Azure.ServiceBus.Message" /> using its lock token.</span></span> <span data-ttu-id="fdb3a-144">これにより、サービスからのメッセージが削除されます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-144">This will delete the message from the service.</span></span>
            </summary>
        <returns><span data-ttu-id="fdb3a-145">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-145">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="fdb3a-146">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-146">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="fdb3a-147">この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-147">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;DeadLetterAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="fdb3a-148">対応する配信不能メッセージのロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-148">The lock token of the corresponding message to deadletter.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="fdb3a-149">サブをキューに移動中に変更するメッセージのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-149">The properties of the message to modify while moving to sub-queue.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-150">メッセージを配信不能サブキューに移動します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-150">Moves a message to the deadletter sub-queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="fdb3a-151">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-151">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="fdb3a-152">を配信不能キューからメッセージを受信するために必要になります、新しい<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />、対応するパスにします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-152">In order to receive a message from the deadletter queue, you will need a new <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, with the corresponding path.</span></span>
            <span data-ttu-id="fdb3a-153">使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />これを支援します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-153">You can use <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> to help with this.</span></span>
            <span data-ttu-id="fdb3a-154">この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-154">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, string deadLetterReason, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeadLetterAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, deadLetterReason As String, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;DeadLetterAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="fdb3a-155">対応する配信不能メッセージのロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-155">The lock token of the corresponding message to deadletter.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="fdb3a-156">メッセージの配信不能の理由です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-156">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="fdb3a-157">メッセージの配信不能のエラーの説明。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-157">The error description for deadlettering the message.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-158">メッセージを配信不能サブキューに移動します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-158">Moves a message to the deadletter sub-queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="fdb3a-159">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-159">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="fdb3a-160">を配信不能キューからメッセージを受信するために必要になります、新しい<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />、対応するパスにします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-160">In order to receive a message from the deadletter queue, you will need a new <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, with the corresponding path.</span></span>
            <span data-ttu-id="fdb3a-161">使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />これを支援します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-161">You can use <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> to help with this.</span></span>
            <span data-ttu-id="fdb3a-162">この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-162">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeferAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;DeferAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="fdb3a-163">ロック トークン、<see cref="T:Microsoft.Azure.ServiceBus.Message" />です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-163">The lock token of the <see cref="T:Microsoft.Azure.ServiceBus.Message" />.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="fdb3a-164">メッセージを保留中に変更するメッセージのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-164">The properties of the message to modify while deferring the message.</span></span></param>
        <summary><span data-ttu-id="fdb3a-165">受信側がメッセージの処理を遅延することを示します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-165">Indicates that the receiver wants to defer the processing for the message.</span></span></summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="fdb3a-166">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-166">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="fdb3a-167">このメッセージを受信するためにもう一度、将来必要がありますを保存する、<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" />を使用してメッセージを受信および<see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-167">In order to receive this message again in the future, you will need to save the <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" /> and receive it using <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />.</span></span>
            <span data-ttu-id="fdb3a-168">遅延メッセージの期限切れのメッセージ、遅延メッセージの期限切れできますも意味に影響しません。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-168">Deferring messages does not impact message's expiration, meaning that deferred messages can still expire.</span></span>
            <span data-ttu-id="fdb3a-169">この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-169">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastPeekedSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastPeekedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastPeekedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.LastPeekedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastPeekedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastPeekedSequenceNumber : int64" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.LastPeekedSequenceNumber" />
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
        <summary><span data-ttu-id="fdb3a-170">最後のピークされたメッセージのシーケンス番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-170">Gets the sequence number of the last peeked message.</span></span></summary>
        <value><span data-ttu-id="fdb3a-171">最後のピークされたメッセージのシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-171">The sequence number of the last peeked message.</span></span></value>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" />
      </Docs>
    </Member>
    <Member MemberName="OnAbandonAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnAbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnAbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnAbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnAbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnAbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.OnAbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnAbandonAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken">To be added.</param>
        <param name="propertiesToModify">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClosingAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnClosingAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnClosingAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnClosingAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnClosingAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.OnClosingAsync : unit -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnClosingAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnClosingAsync&gt;d__84))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns><span data-ttu-id="fdb3a-172">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-172">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCompleteAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCompleteAsync (System.Collections.Generic.IEnumerable&lt;string&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCompleteAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnCompleteAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCompleteAsync (lockTokens As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnCompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.OnCompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnCompleteAsync lockTokens" />
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
        <param name="lockTokens"></param>
        <summary />
        <returns><span data-ttu-id="fdb3a-173">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-173">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeadLetterAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnDeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null, string deadLetterReason = null, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnDeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnDeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnDeadLetterAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null, Optional deadLetterReason As String = null, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnDeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.OnDeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnDeadLetterAsync (lockToken, propertiesToModify, deadLetterReason, deadLetterErrorDescription)" />
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
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">To be added.</param>
        <param name="propertiesToModify">To be added.</param>
        <param name="deadLetterReason">To be added.</param>
        <param name="deadLetterErrorDescription">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeferAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnDeferAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnDeferAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnDeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnDeferAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnDeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.OnDeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnDeferAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken">To be added.</param>
        <param name="propertiesToModify">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageHandler">
      <MemberSignature Language="C#" Value="protected virtual void OnMessageHandler (Microsoft.Azure.ServiceBus.MessageHandlerOptions registerHandlerOptions, Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; callback);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnMessageHandler(class Microsoft.Azure.ServiceBus.MessageHandlerOptions registerHandlerOptions, class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnMessageHandler(Microsoft.Azure.ServiceBus.MessageHandlerOptions,System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnMessageHandler (registerHandlerOptions As MessageHandlerOptions, callback As Func(Of Message, CancellationToken, Task))" />
      <MemberSignature Language="F#" Value="abstract member OnMessageHandler : Microsoft.Azure.ServiceBus.MessageHandlerOptions * Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.OnMessageHandler : Microsoft.Azure.ServiceBus.MessageHandlerOptions * Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="messageReceiver.OnMessageHandler (registerHandlerOptions, callback)" />
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
        <Parameter Name="registerHandlerOptions" Type="Microsoft.Azure.ServiceBus.MessageHandlerOptions" />
        <Parameter Name="callback" Type="System.Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="registerHandlerOptions">To be added.</param>
        <param name="callback">To be added.</param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnPeekAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; OnPeekAsync (long fromSequenceNumber, int messageCount = 1);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; OnPeekAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnPeekAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnPeekAsync (fromSequenceNumber As Long, Optional messageCount As Integer = 1) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member OnPeekAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.OnPeekAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.OnPeekAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnPeekAsync&gt;d__86))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"></param>
        <param name="messageCount"></param>
        <summary />
        <returns><span data-ttu-id="fdb3a-174">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-174">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnReceiveAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; OnReceiveAsync (int maxMessageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; OnReceiveAsync(int32 maxMessageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnReceiveAsync (maxMessageCount As Integer, serverWaitTime As TimeSpan) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member OnReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.OnReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.OnReceiveAsync (maxMessageCount, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnReceiveAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount"></param>
        <param name="serverWaitTime"></param>
        <summary />
        <returns><span data-ttu-id="fdb3a-175">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-175">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; OnReceiveDeferredMessageAsync (long[] sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; OnReceiveDeferredMessageAsync(int64[] sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnReceiveDeferredMessageAsync(System.Int64[])" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnReceiveDeferredMessageAsync (sequenceNumbers As Long()) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member OnReceiveDeferredMessageAsync : int64[] -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.OnReceiveDeferredMessageAsync : int64[] -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.OnReceiveDeferredMessageAsync sequenceNumbers" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnReceiveDeferredMessageAsync&gt;d__87))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Int64[]" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRenewLockAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;DateTime&gt; OnRenewLockAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.DateTime&gt; OnRenewLockAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnRenewLockAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnRenewLockAsync (lockToken As String) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="abstract member OnRenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;&#xA;override this.OnRenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="messageReceiver.OnRenewLockAsync lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnRenewLockAsync&gt;d__92))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"></param>
        <summary />
        <returns><span data-ttu-id="fdb3a-176">Asynchronour 操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-176">The asynchronour operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public override TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.OperationTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.IClientEntity.OperationTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb3a-177">個々 の操作がタイムアウトする期間です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-177">Duration after which individual operations will timeout.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public virtual string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path</InterfaceMember>
      </Implements>
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
        <summary><span data-ttu-id="fdb3a-178">この受信者を表すエンティティのパス。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-178">The path of the entity for this receiver.</span></span> <span data-ttu-id="fdb3a-179">キューのこれは、名前ですが、パスになりますこのサブスクリプションはします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-179">For Queues this will be the name, but for Subscriptions this will be the path.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.PeekAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="fdb3a-180">受信側またはメッセージの送信元の状態を変更せずには、次の作業中のメッセージをフェッチします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-180">Fetches the next active message without changing the state of the receiver or the message source.</span></span>
            </summary>
        <returns><span data-ttu-id="fdb3a-181"><see cref="T:Microsoft.Azure.ServiceBus.Message" />を読み取るには、次のメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-181">The <see cref="T:Microsoft.Azure.ServiceBus.Message" /> that represents the next message to be read.</span></span> <span data-ttu-id="fdb3a-182">ピークが無い場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-182">Returns null when nothing to peek.</span></span></returns>
        <remarks>
            <span data-ttu-id="fdb3a-183">最初に呼び出す<see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" />この受信者の最初の作業中のメッセージをフェッチします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-183">The first call to <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" /> fetches the first active message for this receiver.</span></span> <span data-ttu-id="fdb3a-184">後続の各呼び出しは、エンティティの後続のメッセージをフェッチします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-184">Each subsequent call fetches the subsequent message in the entity.</span></span>
            <span data-ttu-id="fdb3a-185">受信したメッセージとは異なりピーク メッセージには、それに関連付けられたロック トークンがないし、ため完了/破棄/遅延/配信不能になりました/Renewed は指定できません。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-185">Unlike a received message, peeked message will not have lock token associated with it, and hence it cannot be Completed/Abandoned/Deferred/Deadlettered/Renewed.</span></span>
            <span data-ttu-id="fdb3a-186">またとは異なり<see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />、このメソッドがフェッチされいても遅延メッセージ (ただし越えたメッセージではなく)</span><span class="sxs-lookup"><span data-stu-id="fdb3a-186">Also, unlike <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />, this method will fetch even Deferred messages (but not Deadlettered message)</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekAsync (int maxMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekAsync(int32 maxMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (maxMessageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.PeekAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.PeekAsync maxMessageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync(System.Int32)</InterfaceMember>
      </Implements>
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
        <param name="maxMessageCount"><span data-ttu-id="fdb3a-187">メッセージ数。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-187">The number of messages.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-188">受信側またはメッセージの送信元の状態を変更することがなく、アクティブなメッセージの次のバッチをフェッチします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-188">Fetches the next batch of active messages without changing the state of the receiver or the message source.</span></span>
            </summary>
        <returns><span data-ttu-id="fdb3a-189">一覧の<see cref="T:Microsoft.Azure.ServiceBus.Message" />を読み取るには、次のメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-189">List of <see cref="T:Microsoft.Azure.ServiceBus.Message" /> that represents the next message to be read.</span></span> <span data-ttu-id="fdb3a-190">ピークが無い場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-190">Returns null when nothing to peek.</span></span></returns>
        <remarks>
            <span data-ttu-id="fdb3a-191">最初に呼び出す<see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" />この受信者の最初の作業中のメッセージをフェッチします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-191">The first call to <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" /> fetches the first active message for this receiver.</span></span> <span data-ttu-id="fdb3a-192">後続の各呼び出しは、エンティティの後続のメッセージをフェッチします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-192">Each subsequent call fetches the subsequent message in the entity.</span></span>
            <span data-ttu-id="fdb3a-193">受信したメッセージとは異なりピーク メッセージには、それに関連付けられたロック トークンがないし、ため完了/破棄/遅延/配信不能になりました/Renewed は指定できません。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-193">Unlike a received message, peeked message will not have lock token associated with it, and hence it cannot be Completed/Abandoned/Deferred/Deadlettered/Renewed.</span></span>
            <span data-ttu-id="fdb3a-194">またとは異なり<see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />、このメソッドがフェッチされいても遅延メッセージ (ただし越えたメッセージではなく)</span><span class="sxs-lookup"><span data-stu-id="fdb3a-194">Also, unlike <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />, this method will fetch even Deferred messages (but not Deadlettered message)</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBySequenceNumberAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; PeekBySequenceNumberAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; PeekBySequenceNumberAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekBySequenceNumberAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBySequenceNumberAsync (fromSequenceNumber As Long) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member PeekBySequenceNumberAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.PeekBySequenceNumberAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.PeekBySequenceNumberAsync fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekBySequenceNumberAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;PeekBySequenceNumberAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"><span data-ttu-id="fdb3a-195">メッセージを読み取る場所からシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-195">The sequence number from where to read the message.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-196">受信側またはメッセージの送信元の状態を変更することがなく、次のメッセージを非同期に読み取ります。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-196">Asynchronously reads the next message without changing the state of the receiver or the message source.</span></span>
            </summary>
        <returns><span data-ttu-id="fdb3a-197">返す非同期操作、<see cref="T:Microsoft.Azure.ServiceBus.Message" />を読み取るには、次のメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-197">The asynchronous operation that returns the <see cref="T:Microsoft.Azure.ServiceBus.Message" /> that represents the next message to be read.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBySequenceNumberAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekBySequenceNumberAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekBySequenceNumberAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekBySequenceNumberAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBySequenceNumberAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member PeekBySequenceNumberAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.PeekBySequenceNumberAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.PeekBySequenceNumberAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekBySequenceNumberAsync(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;PeekBySequenceNumberAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"><span data-ttu-id="fdb3a-198">メッセージのバッチを参照する開始点です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-198">The starting point from which to browse a batch of messages.</span></span></param>
        <param name="messageCount"><span data-ttu-id="fdb3a-199">取得するメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-199">The number of messages to retrieve.</span></span></param>
        <summary><span data-ttu-id="fdb3a-200">バッチのメッセージをピークします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-200">Peeks a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="fdb3a-201">バッチのメッセージをピークします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-201">A batch of messages peeked.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.PrefetchCount</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb3a-202">メッセージ フローと、1 つのアプリケーションが要求する前にローカルの取得のためすぐに使用できるメッセージがあることを目指していますによってプリフェッチ速度では、受信を使用します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-202">Prefetch speeds up the message flow by aiming to have a message readily available for local retrieval when and before the application asks for one using Receive.</span></span>
            <span data-ttu-id="fdb3a-203">メッセージ数の PrefetchCount をプリフェッチする 0 以外の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-203">Setting a non-zero value prefetches PrefetchCount number of messages.</span></span>
            <span data-ttu-id="fdb3a-204">プリフェッチをオフに値を 0 に設定します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-204">Setting the value to zero turns prefetch off.</span></span>
            <span data-ttu-id="fdb3a-205">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-205">Defaults to 0.</span></span>
            </summary>
        <value><span data-ttu-id="fdb3a-206">メッセージの受信者が同時に要求メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-206">The number of messages that the message receiver can simultaneously request.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="fdb3a-207">プリフェッチを有効にすると、受信側はサイレント モードでどのようなアプリケーションすぐに確認のより PrefetchCount 上限に達するまで、多くのメッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-207">When Prefetch is enabled, the receiver will quietly acquire more messages, up to the PrefetchCount limit, than what the application immediately asks for.</span></span> <span data-ttu-id="fdb3a-208">初期の単一の受信/ReceiveAsync 呼び出ししたがって取得するメッセージに対して返されるとすぐに利用可能な即時の消費量と、クライアントでは、バック グラウンドでプリフェッチ バッファーが満杯にさらにメッセージの取得に進みます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-208">A single initial Receive/ReceiveAsync call will therefore acquire a message for immediate consumption that will be returned as soon as available, and the client will proceed to acquire further messages to fill the prefetch buffer in the background.</span></span>
            </para>
          <para>
            <span data-ttu-id="fdb3a-209">メッセージは、プリフェッチ バッファーで使用できますが、後続の ReceiveAsync 呼び出しは、バッファーからすぐに満たされ、空き領域ができるように、バック グラウンドでバッファーが補充です。にない場合のメッセージ配信のために使用できる、受信操作は、バッファーのドレインを実行し、まで待機するかどおりをブロックします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-209">While messages are available in the prefetch buffer, any subsequent ReceiveAsync calls will be immediately satisfied from the buffer, and the buffer is replenished in the background as space becomes available.If there are no messages available for delivery, the receive operation will drain the buffer and then wait or block as expected.</span></span>
            </para>
          <para><span data-ttu-id="fdb3a-210">プリフェッチ同等のでも、 <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" /> Api です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-210">Prefetch also works equivalently with the <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" /> APIs.</span></span></para>
          <para><span data-ttu-id="fdb3a-211">この値に更新プログラムは、サービスの受信呼び出しは、[次へ] を有効になります。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-211">Updates to this value take effect on the next receive call to the service.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="fdb3a-212">定義されているエンティティからメッセージを受信<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" />を使用して<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />モード。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-212">Receive a message from the entity defined by <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" /> using <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> mode.</span></span>
            </summary>
        <returns><span data-ttu-id="fdb3a-213">受信したメッセージ。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-213">The message received.</span></span> <span data-ttu-id="fdb3a-214">メッセージがない場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-214">Returns null if no message is found.</span></span></returns>
        <remarks><span data-ttu-id="fdb3a-215">期間の後に操作がタイムアウト<see cref="P:Microsoft.Azure.ServiceBus.ClientEntity.OperationTimeout" /></span><span class="sxs-lookup"><span data-stu-id="fdb3a-215">Operation will time out after duration of <see cref="P:Microsoft.Azure.ServiceBus.ClientEntity.OperationTimeout" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync (int maxMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync(int32 maxMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.ReceiveAsync maxMessageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.Int32)</InterfaceMember>
      </Implements>
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
        <param name="maxMessageCount"><span data-ttu-id="fdb3a-216">受信するメッセージの最大数。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-216">The maximum number of messages that will be received.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-217">最大値を受け取る<paramref name="maxMessageCount" />によって定義されているエンティティからのメッセージ<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" />を使用して<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />モード。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-217">Receives a maximum of <paramref name="maxMessageCount" /> messages from the entity defined by <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" /> using <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> mode.</span></span>
            </summary>
        <returns><span data-ttu-id="fdb3a-218">受信したメッセージの一覧です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-218">List of messages received.</span></span> <span data-ttu-id="fdb3a-219">メッセージがない場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-219">Returns null if no message is found.</span></span></returns>
        <remarks><span data-ttu-id="fdb3a-220">も少ない受信<paramref name="maxMessageCount" />メッセージは空のエンティティを示す値ではありません。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-220">Receiving less than <paramref name="maxMessageCount" /> messages is not an indication of empty entity.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync (TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync(valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (operationTimeout As TimeSpan) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.ReceiveAsync operationTimeout" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;ReceiveAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationTimeout"><span data-ttu-id="fdb3a-221">タイムアウトになる前にメッセージを受信するためクライアントが待機するを期間します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-221">The time span the client waits for receiving a message before it times out.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-222">定義されているエンティティからメッセージを受信<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" />を使用して<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />モード。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-222">Receive a message from the entity defined by <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" /> using <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> mode.</span></span>
            </summary>
        <returns><span data-ttu-id="fdb3a-223">受信したメッセージ。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-223">The message received.</span></span> <span data-ttu-id="fdb3a-224">メッセージがない場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-224">Returns null if no message is found.</span></span></returns>
        <remarks>
            <span data-ttu-id="fdb3a-225">パラメーター <paramref name="operationTimeout" /> (いずれかまたは接続を再確立する必要がある場合、最初の受信時に) 接続を確立するために、受信側にかかる時間が含まれています。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-225">The parameter <paramref name="operationTimeout" /> includes the time taken by the receiver to establish a connection (either during the first receive or when connection needs to be re-established).</span></span> <span data-ttu-id="fdb3a-226">これがスローされる場合は、接続の確立がタイムアウトになる、<see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-226">If establishing the connection times out, this will throw <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync (int maxMessageCount, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync(int32 maxMessageCount, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer, operationTimeout As TimeSpan) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.ReceiveAsync (maxMessageCount, operationTimeout)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.Int32,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;ReceiveAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount"><span data-ttu-id="fdb3a-227">受信するメッセージの最大数。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-227">The maximum number of messages that will be received.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="fdb3a-228">タイムアウトになる前にメッセージを受信するためクライアントが待機するを期間します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-228">The time span the client waits for receiving a message before it times out.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-229">最大値を受け取る<paramref name="maxMessageCount" />によって定義されているエンティティからのメッセージ<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" />を使用して<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />モード。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-229">Receives a maximum of <paramref name="maxMessageCount" /> messages from the entity defined by <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" /> using <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" /> mode.</span></span>
            </summary>
        <returns><span data-ttu-id="fdb3a-230">受信したメッセージの一覧です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-230">List of messages received.</span></span> <span data-ttu-id="fdb3a-231">メッセージがない場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-231">Returns null if no message is found.</span></span></returns>
        <remarks><span data-ttu-id="fdb3a-232">も少ない受信<paramref name="maxMessageCount" />メッセージは空のエンティティを示す値ではありません。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-232">Receiving less than <paramref name="maxMessageCount" /> messages is not an indication of empty entity.</span></span>
            <span data-ttu-id="fdb3a-233">パラメーター <paramref name="operationTimeout" /> (いずれかまたは接続を再確立する必要がある場合、最初の受信時に) 接続を確立するために、受信側にかかる時間が含まれています。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-233">The parameter <paramref name="operationTimeout" /> includes the time taken by the receiver to establish a connection (either during the first receive or when connection needs to be re-established).</span></span> <span data-ttu-id="fdb3a-234">これがスローされる場合は、接続の確立がタイムアウトになる、<see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-234">If establishing the connection times out, this will throw <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveDeferredMessageAsync (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveDeferredMessageAsync(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveDeferredMessageAsync(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveDeferredMessageAsync (sequenceNumbers As IEnumerable(Of Long)) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveDeferredMessageAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.ReceiveDeferredMessageAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.ReceiveDeferredMessageAsync sequenceNumbers" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Collections.Generic.IEnumerable{System.Int64})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;ReceiveDeferredMessageAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers"><span data-ttu-id="fdb3a-235"><see cref="T:System.Collections.Generic.IEnumerable`1" />を受信するシーケンス番号を含むです。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-235">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> containing the sequence numbers to receive.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-236">受信、<see cref="T:System.Collections.Generic.IList`1" />で識別される遅延メッセージの<paramref name="sequenceNumbers" />します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-236">Receives a <see cref="T:System.Collections.Generic.IList`1" /> of deferred messages identified by <paramref name="sequenceNumbers" />.</span></span>
            </summary>
        <returns><span data-ttu-id="fdb3a-237">シーケンス番号によって識別されるメッセージが返されます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-237">Messages identified by sequence number are returned.</span></span> <span data-ttu-id="fdb3a-238">メッセージが見つからない場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-238">Returns null if no messages are found.</span></span>
            <span data-ttu-id="fdb3a-239">メッセージが遅延されていない場合をスローします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-239">Throws if the messages have not been deferred.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      </Docs>
    </Member>
    <Member MemberName="ReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveDeferredMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveDeferredMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveDeferredMessageAsync (sequenceNumber As Long) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveDeferredMessageAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.ReceiveDeferredMessageAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.ReceiveDeferredMessageAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;ReceiveDeferredMessageAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><span data-ttu-id="fdb3a-240">受信するメッセージのシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-240">The sequence number of the message that will be received.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-241">によって識別される特定の遅延メッセージ受信<paramref name="sequenceNumber" />です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-241">Receives a specific deferred message identified by <paramref name="sequenceNumber" />.</span></span>
            </summary>
        <returns><span data-ttu-id="fdb3a-242">メッセージのシーケンス番号によって識別<paramref name="sequenceNumber" />です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-242">Message identified by sequence number <paramref name="sequenceNumber" />.</span></span> <span data-ttu-id="fdb3a-243">このようなメッセージが存在しない場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-243">Returns null if no such message is found.</span></span>
            <span data-ttu-id="fdb3a-244">メッセージは保留されていない場合にスローします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-244">Throws if the message has not been deferred.</span></span></returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      </Docs>
    </Member>
    <Member MemberName="ReceiveMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ReceiveMode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.ReceiveMode : Microsoft.Azure.ServiceBus.ReceiveMode with get, set" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />
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
            <span data-ttu-id="fdb3a-245">取得、<see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />現在受信機のです。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-245">Gets the <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> of the current receiver.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisteredPlugins" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.IClientEntity.RegisteredPlugins</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdb3a-246">現在登録されているプラグインの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-246">Gets a list of currently registered plugins.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit" Usage="messageReceiver.RegisterMessageHandler (handler, messageHandlerOptions)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)</InterfaceMember>
      </Implements>
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
        <Parameter Name="messageHandlerOptions" Type="Microsoft.Azure.ServiceBus.MessageHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handler"><span data-ttu-id="fdb3a-247">A<see cref="T:System.Func`3" />メッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-247">A <see cref="T:System.Func`3" /> that processes messages.</span></span></param>
        <param name="messageHandlerOptions"><span data-ttu-id="fdb3a-248"><see cref="T:Microsoft.Azure.ServiceBus.MessageHandlerOptions" />オプション、ポンプの設定を構成するために使用します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-248">The <see cref="T:Microsoft.Azure.ServiceBus.MessageHandlerOptions" /> options used to configure the settings of the pump.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-249">継続的に、エンティティからメッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-249">Receive messages continuously from the entity.</span></span> <span data-ttu-id="fdb3a-250">メッセージ ハンドラーを登録し、メッセージを受信する新しいスレッドを開始します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-250">Registers a message handler and begins a new thread to receive messages.</span></span>
            <span data-ttu-id="fdb3a-251">このハンドラー (<see cref="T:System.Func`3" />)、受信側で新しいメッセージを受信するたびにでは待機します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-251">This handler(<see cref="T:System.Func`3" />) is awaited on every time a new message is received by the receiver.</span></span>
            </summary>
        <remarks><span data-ttu-id="fdb3a-252">受信レートを高速化するプリフェッチを有効にします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-252">Enable prefetch to speed up the receive rate.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="messageReceiver.RegisterMessageHandler (handler, exceptionReceivedHandler)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})</InterfaceMember>
      </Implements>
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
        <param name="handler"><span data-ttu-id="fdb3a-253">A<see cref="T:System.Func`3" />メッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-253">A <see cref="T:System.Func`3" /> that processes messages.</span></span></param>
        <param name="exceptionReceivedHandler"><span data-ttu-id="fdb3a-254">A<see cref="T:System.Func`2" />を使用して例外を通知します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-254">A <see cref="T:System.Func`2" /> that is used to notify exceptions.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-255">継続的に、エンティティからメッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-255">Receive messages continuously from the entity.</span></span> <span data-ttu-id="fdb3a-256">メッセージ ハンドラーを登録し、メッセージを受信する新しいスレッドを開始します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-256">Registers a message handler and begins a new thread to receive messages.</span></span>
            <span data-ttu-id="fdb3a-257">このハンドラー (<see cref="T:System.Func`3" />)、受信側で新しいメッセージを受信するたびにでは待機します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-257">This handler(<see cref="T:System.Func`3" />) is awaited on every time a new message is received by the receiver.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public override void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="override this.RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="messageReceiver.RegisterPlugin serviceBusPlugin" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IClientEntity.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)</InterfaceMember>
      </Implements>
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
        <Parameter Name="serviceBusPlugin" Type="Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />
      </Parameters>
      <Docs>
        <param name="serviceBusPlugin"><span data-ttu-id="fdb3a-258"><see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />を登録するには</span><span class="sxs-lookup"><span data-stu-id="fdb3a-258">The <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> to register</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-259">登録、<see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />このレシーバーと共に使用します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-259">Registers a <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> to be used with this receiver.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewLockAsync (Microsoft.Azure.ServiceBus.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewLockAsync(class Microsoft.Azure.ServiceBus.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />
      <MemberSignature Language="F#" Value="abstract member RenewLockAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task&#xA;override this.RenewLockAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.RenewLockAsync message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;RenewLockAsync&gt;d__72))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>
            <span data-ttu-id="fdb3a-260">ロック トークンで指定されたメッセージのロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-260">Renews the lock on the message specified by the lock token.</span></span> <span data-ttu-id="fdb3a-261">ロックは、キューに指定された設定に基づいて更新されます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-261">The lock will be renewed based on the setting specified on the queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="fdb3a-262">メッセージを受信する<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />モードでは、メッセージがロックされているこの受信者インスタンス用のサーバーに指定された期間中 (LockDuration) キュー/サブスクリプションの作成中にします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-262">When a message is received in <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> mode, the message is locked on the server for this receiver instance for a duration as specified during the Queue/Subscription creation (LockDuration).</span></span>
            <span data-ttu-id="fdb3a-263">メッセージの処理は、この期間を超える必要がある場合、ロックを更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-263">If processing of the message requires longer than this duration, the lock needs to be renewed.</span></span>
            <span data-ttu-id="fdb3a-264">各更新のエンティティに設定 LockDuration によってメッセージがロックされている時間にリセットされます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-264">For each renewal, it resets the time the message is locked by the LockDuration set on the Entity.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;DateTime&gt; RenewLockAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.DateTime&gt; RenewLockAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RenewLockAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewLockAsync (lockToken As String) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="abstract member RenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;&#xA;override this.RenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="messageReceiver.RenewLockAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;RenewLockAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"><span data-ttu-id="fdb3a-265">メッセージに関連付けられたロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-265">Lock token associated with the message.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-266">メッセージのロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-266">Renews the lock on the message.</span></span> <span data-ttu-id="fdb3a-267">ロックは、キューに指定された設定に基づいて更新されます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-267">The lock will be renewed based on the setting specified on the queue.</span></span>
            <span data-ttu-id="fdb3a-268"><returns>トークンの有効期限の日付と時刻 (utc) 形式での新しいロックします。</returns></span><span class="sxs-lookup"><span data-stu-id="fdb3a-268"><returns>New lock token expiry date and time in UTC format.</returns></span></span></summary>
        <returns><span data-ttu-id="fdb3a-269">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-269">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="fdb3a-270">メッセージを受信する<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />モードでは、メッセージがロックされているこの受信者インスタンス用のサーバーに指定された期間中 (LockDuration) キュー/サブスクリプションの作成中にします。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-270">When a message is received in <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> mode, the message is locked on the server for this receiver instance for a duration as specified during the Queue/Subscription creation (LockDuration).</span></span>
            <span data-ttu-id="fdb3a-271">メッセージの処理は、この期間を超える必要がある場合、ロックを更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-271">If processing of the message requires longer than this duration, the lock needs to be renewed.</span></span>
            <span data-ttu-id="fdb3a-272">各更新のエンティティに設定 LockDuration によってメッセージがロックされている時間にリセットされます。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-272">For each renewal, it resets the time the message is locked by the LockDuration set on the Entity.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public override void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="override this.UnregisterPlugin : string -&gt; unit" Usage="messageReceiver.UnregisterPlugin serviceBusPluginName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IClientEntity.UnregisterPlugin(System.String)</InterfaceMember>
      </Implements>
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
        <Parameter Name="serviceBusPluginName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceBusPluginName"><span data-ttu-id="fdb3a-273"><see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" />の登録解除するプラグイン。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-273">The <see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" /> of the plugin to be unregistered.</span></span></param>
        <summary>
            <span data-ttu-id="fdb3a-274">登録を解除、<see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />です。</span><span class="sxs-lookup"><span data-stu-id="fdb3a-274">Unregisters a <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>