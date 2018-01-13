<Type Name="SubscriptionClient" FullName="Microsoft.Azure.ServiceBus.SubscriptionClient">
  <TypeSignature Language="C#" Value="public class SubscriptionClient : Microsoft.Azure.ServiceBus.ClientEntity, Microsoft.Azure.ServiceBus.ISubscriptionClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubscriptionClient extends Microsoft.Azure.ServiceBus.ClientEntity implements class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity, class Microsoft.Azure.ServiceBus.ISubscriptionClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />
  <TypeSignature Language="VB.NET" Value="Public Class SubscriptionClient&#xA;Inherits ClientEntity&#xA;Implements ISubscriptionClient" />
  <TypeSignature Language="F#" Value="type SubscriptionClient = class&#xA;    inherit ClientEntity&#xA;    interface ISubscriptionClient&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
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
      <InterfaceName>Microsoft.Azure.ServiceBus.ISubscriptionClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="8b122-101">SubscriptionClient は、すべての基本的な対話をサービス バスのサブスクリプションで使用できます。</span><span class="sxs-lookup"><span data-stu-id="8b122-101">SubscriptionClient can be used for all basic interactions with a Service Bus Subscription.</span></span>
             </summary>
    <remarks><span data-ttu-id="8b122-102">サービス バスと通信するため、AMQP プロトコルを使用します。</span><span class="sxs-lookup"><span data-stu-id="8b122-102">It uses AMQP protocol for communicating with service bus.</span></span> <span data-ttu-id="8b122-103">使用して<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />の高度な機能セット。</span><span class="sxs-lookup"><span data-stu-id="8b122-103">Use <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> for advanced set of functionality.</span></span></remarks>
    <example>
             <span data-ttu-id="8b122-104">新しい SubscriptionClient を作成します。</span><span class="sxs-lookup"><span data-stu-id="8b122-104">Create a new SubscriptionClient</span></span>
             <code>
             ISubscriptionClient subscriptionClient = new SubscriptionClient(
                 namespaceConnectionString,
                 topicName,
                 subscriptionName,
                 ReceiveMode.PeekLock,
                 RetryExponential);
             </code>
            
             <span data-ttu-id="8b122-105">メッセージを受信するたびに呼び出されるメッセージのハンドラーを登録します。</span><span class="sxs-lookup"><span data-stu-id="8b122-105">Register a message handler which will be invoked every time a message is received.</span></span>
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
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionClient (Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, string subscriptionName, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, string subscriptionName, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.#ctor(Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder,System.String,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SubscriptionClient : Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder * string * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.SubscriptionClient" Usage="new Microsoft.Azure.ServiceBus.SubscriptionClient (connectionStringBuilder, subscriptionName, receiveMode, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionStringBuilder" Type="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="connectionStringBuilder">
          <span data-ttu-id="8b122-106"><see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />名前空間とトピックの情報を持ちます。</span><span class="sxs-lookup"><span data-stu-id="8b122-106"><see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /> having namespace and topic information.</span></span></param>
        <param name="subscriptionName"><span data-ttu-id="8b122-107">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="8b122-107">Name of the subscription.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="8b122-108">メッセージの受信のモードです。</span><span class="sxs-lookup"><span data-stu-id="8b122-108">Mode of receive of messages.</span></span> <span data-ttu-id="8b122-109">既定値は<see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />します。PeekLock です。</span><span class="sxs-lookup"><span data-stu-id="8b122-109">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />.PeekLock.</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="8b122-110">ポリシーのサブスクリプション操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="8b122-110">Retry policy for subscription operations.</span></span> <span data-ttu-id="8b122-111">既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span><span class="sxs-lookup"><span data-stu-id="8b122-111">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span></span></param>
        <summary>
            <span data-ttu-id="8b122-112">新しいインスタンスを作成<see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />サブスクリプションに対して操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="8b122-112">Instantiates a new <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" /> to perform operations on a subscription.</span></span>
            </summary>
        <remarks><span data-ttu-id="8b122-113">新たに作成中、最初に開かれると、サブスクリプションへの接続の受信操作します。</span><span class="sxs-lookup"><span data-stu-id="8b122-113">Creates a new connection to the subscription, which is opened during the first receive operation.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionClient (string connectionString, string topicPath, string subscriptionName, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string topicPath, string subscriptionName, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.#ctor(System.String,System.String,System.String,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SubscriptionClient : string * string * string * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.SubscriptionClient" Usage="new Microsoft.Azure.ServiceBus.SubscriptionClient (connectionString, topicPath, subscriptionName, receiveMode, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="8b122-114">Namespace 接続文字列です。</span><span class="sxs-lookup"><span data-stu-id="8b122-114">Namespace connection string.</span></span> <span data-ttu-id="8b122-115">トピック サブスクリプションまたはサブスクリプションの情報を含めないでください。</span><span class="sxs-lookup"><span data-stu-id="8b122-115">Must not contain topic or subscription information.</span></span></param>
        <param name="topicPath"><span data-ttu-id="8b122-116">トピックへのパス。</span><span class="sxs-lookup"><span data-stu-id="8b122-116">Path to the topic.</span></span></param>
        <param name="subscriptionName"><span data-ttu-id="8b122-117">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="8b122-117">Name of the subscription.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="8b122-118">メッセージの受信のモードです。</span><span class="sxs-lookup"><span data-stu-id="8b122-118">Mode of receive of messages.</span></span> <span data-ttu-id="8b122-119">既定値は<see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />します。PeekLock です。</span><span class="sxs-lookup"><span data-stu-id="8b122-119">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />.PeekLock.</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="8b122-120">ポリシーのサブスクリプション操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="8b122-120">Retry policy for subscription operations.</span></span> <span data-ttu-id="8b122-121">既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span><span class="sxs-lookup"><span data-stu-id="8b122-121">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span></span></param>
        <summary>
            <span data-ttu-id="8b122-122">新しいインスタンスを作成<see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />サブスクリプションに対して操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="8b122-122">Instantiates a new <see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" /> to perform operations on a subscription.</span></span>
            </summary>
        <remarks><span data-ttu-id="8b122-123">新たに作成中、最初に開かれると、サブスクリプションへの接続の受信操作します。</span><span class="sxs-lookup"><span data-stu-id="8b122-123">Creates a new connection to the subscription, which is opened during the first receive operation.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionClient (string endpoint, string topicPath, string subscriptionName, Microsoft.Azure.ServiceBus.Primitives.ITokenProvider tokenProvider, Microsoft.Azure.ServiceBus.TransportType transportType = Microsoft.Azure.ServiceBus.TransportType.Amqp, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string topicPath, string subscriptionName, class Microsoft.Azure.ServiceBus.Primitives.ITokenProvider tokenProvider, valuetype Microsoft.Azure.ServiceBus.TransportType transportType, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.#ctor(System.String,System.String,System.String,Microsoft.Azure.ServiceBus.Primitives.ITokenProvider,Microsoft.Azure.ServiceBus.TransportType,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SubscriptionClient : string * string * string * Microsoft.Azure.ServiceBus.Primitives.ITokenProvider * Microsoft.Azure.ServiceBus.TransportType * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.SubscriptionClient" Usage="new Microsoft.Azure.ServiceBus.SubscriptionClient (endpoint, topicPath, subscriptionName, tokenProvider, transportType, receiveMode, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.ServiceBus.Primitives.ITokenProvider" />
        <Parameter Name="transportType" Type="Microsoft.Azure.ServiceBus.TransportType" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="8b122-124">Service Bus の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="8b122-124">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="8b122-125">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="8b122-125">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="topicPath"><span data-ttu-id="8b122-126">トピック パスです。</span><span class="sxs-lookup"><span data-stu-id="8b122-126">Topic path.</span></span></param>
        <param name="subscriptionName"><span data-ttu-id="8b122-127">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="8b122-127">Subscription name.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="8b122-128">認証のセキュリティ トークンを生成するトークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="8b122-128">Token provider which will generate security tokens for authorization.</span></span></param>
        <param name="transportType"><span data-ttu-id="8b122-129">トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="8b122-129">Transport type.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="8b122-130">メッセージの受信のモードです。</span><span class="sxs-lookup"><span data-stu-id="8b122-130">Mode of receive of messages.</span></span> <span data-ttu-id="8b122-131">既定値は<see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />します。PeekLock です。</span><span class="sxs-lookup"><span data-stu-id="8b122-131">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />.PeekLock.</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="8b122-132">ポリシーのサブスクリプション操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="8b122-132">Retry policy for subscription operations.</span></span> <span data-ttu-id="8b122-133">既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span><span class="sxs-lookup"><span data-stu-id="8b122-133">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span></span></param>
        <summary>
            <span data-ttu-id="8b122-134">サブスクリプションを指定されたエンドポイント、エンティティのパス、およびトークン プロバイダーを使用してクライアントの新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="8b122-134">Creates a new instance of the Subscription client using the specified endpoint, entity path, and token provider.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AbandonAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
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
        <param name="lockToken"><span data-ttu-id="8b122-135">中止するのには、対応するメッセージのロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="8b122-135">The lock token of the corresponding message to abandon.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="8b122-136">メッセージの破棄中に変更するメッセージのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="8b122-136">The properties of the message to modify while abandoning the message.</span></span></param>
        <summary>
            <span data-ttu-id="8b122-137">破棄、<see cref="T:Microsoft.Azure.ServiceBus.Message" />ロックのトークンを使用します。</span><span class="sxs-lookup"><span data-stu-id="8b122-137">Abandons a <see cref="T:Microsoft.Azure.ServiceBus.Message" /> using a lock token.</span></span> <span data-ttu-id="8b122-138">これにより、メッセージ処理用にもう一度使用できます。</span><span class="sxs-lookup"><span data-stu-id="8b122-138">This will make the message available again for processing.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="8b122-139">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="8b122-139">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="8b122-140">メッセージを破棄すると、メッセージの配信回数が増加します。</span><span class="sxs-lookup"><span data-stu-id="8b122-140">Abandoning a message will increase the delivery count on the message.</span></span>
            <span data-ttu-id="8b122-141">この操作は、このクライアントで受信したメッセージでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="8b122-141">This operation can only be performed on messages that were received by this client.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (Microsoft.Azure.ServiceBus.RuleDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddRuleAsync(class Microsoft.Azure.ServiceBus.RuleDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.AddRuleAsync(Microsoft.Azure.ServiceBus.RuleDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function AddRuleAsync (description As RuleDescription) As Task" />
      <MemberSignature Language="F#" Value="abstract member AddRuleAsync : Microsoft.Azure.ServiceBus.RuleDescription -&gt; System.Threading.Tasks.Task&#xA;override this.AddRuleAsync : Microsoft.Azure.ServiceBus.RuleDescription -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AddRuleAsync description" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.AddRuleAsync(Microsoft.Azure.ServiceBus.RuleDescription)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SubscriptionClient/&lt;AddRuleAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.ServiceBus.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="8b122-142">規則の説明を追加するルールを提供します。</span><span class="sxs-lookup"><span data-stu-id="8b122-142">The rule description that provides the rule to add.</span></span></param>
        <summary>
            <span data-ttu-id="8b122-143">サブスクリプションに達しようとしてトピックからメッセージをフィルター処理の現在のサブスクリプションにルールを追加します。</span><span class="sxs-lookup"><span data-stu-id="8b122-143">Adds a rule to the current subscription to filter the messages reaching from topic to the subscription.</span></span>
            </summary>
        <returns><span data-ttu-id="8b122-144">非同期の追加ルールの操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="8b122-144">A task instance that represents the asynchronous add rule operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8b122-145">規則は、トピックからメッセージがサブスクリプションにアクセスする必要がありますを決定するサブスクリプションを追加できます。</span><span class="sxs-lookup"><span data-stu-id="8b122-145">You can add rules to the subscription that decides which messages from the topic should reach the subscription.</span></span>
            <span data-ttu-id="8b122-146">既定の<see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" />という名前のルール<see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" />サブスクリプションの作成中には常に追加します。</span><span class="sxs-lookup"><span data-stu-id="8b122-146">A default <see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" /> rule named <see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" /> is always added while creation of the Subscription.</span></span>
            <span data-ttu-id="8b122-147">個別の名前を持つ複数のルールは、同じサブスクリプションに追加できます。</span><span class="sxs-lookup"><span data-stu-id="8b122-147">You can add multiple rules with distinct names to the same subscription.</span></span>
            <span data-ttu-id="8b122-148">複数のフィルターは、論理 OR 条件を使用して相互に結合します。</span><span class="sxs-lookup"><span data-stu-id="8b122-148">Multiple filters combine with each other using logical OR condition.</span></span> <span data-ttu-id="8b122-149">つまり、任意のフィルターが成功した場合、メッセージに渡されますサブスクリプション。</span><span class="sxs-lookup"><span data-stu-id="8b122-149">i.e., If any filter succeeds, the message is passed on to the subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (string ruleName, Microsoft.Azure.ServiceBus.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddRuleAsync(string ruleName, class Microsoft.Azure.ServiceBus.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.AddRuleAsync(System.String,Microsoft.Azure.ServiceBus.Filter)" />
      <MemberSignature Language="F#" Value="abstract member AddRuleAsync : string * Microsoft.Azure.ServiceBus.Filter -&gt; System.Threading.Tasks.Task&#xA;override this.AddRuleAsync : string * Microsoft.Azure.ServiceBus.Filter -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AddRuleAsync (ruleName, filter)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.AddRuleAsync(System.String,Microsoft.Azure.ServiceBus.Filter)</InterfaceMember>
      </Implements>
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
        <param name="filter"><span data-ttu-id="8b122-150">対象となるメッセージが一致するフィルター式です。</span><span class="sxs-lookup"><span data-stu-id="8b122-150">The filter expression against which messages will be matched.</span></span></param>
        <summary>
            <span data-ttu-id="8b122-151">サブスクリプションに達しようとしてトピックからメッセージをフィルター処理の現在のサブスクリプションにルールを追加します。</span><span class="sxs-lookup"><span data-stu-id="8b122-151">Adds a rule to the current subscription to filter the messages reaching from topic to the subscription.</span></span>
            </summary>
        <returns><span data-ttu-id="8b122-152">非同期の追加ルールの操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="8b122-152">A task instance that represents the asynchronous add rule operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8b122-153">規則は、トピックからメッセージがサブスクリプションにアクセスする必要がありますを決定するサブスクリプションを追加できます。</span><span class="sxs-lookup"><span data-stu-id="8b122-153">You can add rules to the subscription that decides which messages from the topic should reach the subscription.</span></span>
            <span data-ttu-id="8b122-154">既定の<see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" />という名前のルール<see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" />サブスクリプションの作成中には常に追加します。</span><span class="sxs-lookup"><span data-stu-id="8b122-154">A default <see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" /> rule named <see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" /> is always added while creation of the Subscription.</span></span>
            <span data-ttu-id="8b122-155">個別の名前を持つ複数のルールは、同じサブスクリプションに追加できます。</span><span class="sxs-lookup"><span data-stu-id="8b122-155">You can add multiple rules with distinct names to the same subscription.</span></span>
            <span data-ttu-id="8b122-156">複数のフィルターは、論理 OR 条件を使用して相互に結合します。</span><span class="sxs-lookup"><span data-stu-id="8b122-156">Multiple filters combine with each other using logical OR condition.</span></span> <span data-ttu-id="8b122-157">つまり、任意のフィルターが成功した場合、メッセージに渡されますサブスクリプション。</span><span class="sxs-lookup"><span data-stu-id="8b122-157">i.e., If any filter succeeds, the message is passed on to the subscription.</span></span>
            <span data-ttu-id="8b122-158">ルール名の最大許容長は、50 文字です。</span><span class="sxs-lookup"><span data-stu-id="8b122-158">Max allowed length of rule name is 50 chars.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.CompleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.CompleteAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="8b122-159">完了する、対応するメッセージのロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="8b122-159">The lock token of the corresponding message to complete.</span></span></param>
        <summary>
            <span data-ttu-id="8b122-160">完了、<see cref="T:Microsoft.Azure.ServiceBus.Message" />のロック トークンを使用します。</span><span class="sxs-lookup"><span data-stu-id="8b122-160">Completes a <see cref="T:Microsoft.Azure.ServiceBus.Message" /> using its lock token.</span></span> <span data-ttu-id="8b122-161">これにより、サブスクリプションからメッセージが削除されます。</span><span class="sxs-lookup"><span data-stu-id="8b122-161">This will delete the message from the subscription.</span></span>
            </summary>
        <returns><span data-ttu-id="8b122-162">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="8b122-162">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8b122-163">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="8b122-163">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="8b122-164">この操作は、このクライアントで受信したメッセージでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="8b122-164">This operation can only be performed on messages that were received by this client.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.DeadLetterAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeadLetterAsync : string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="8b122-165">対応する配信不能メッセージのロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="8b122-165">The lock token of the corresponding message to deadletter.</span></span></param>
        <summary>
            <span data-ttu-id="8b122-166">メッセージを配信不能サブキューに移動します。</span><span class="sxs-lookup"><span data-stu-id="8b122-166">Moves a message to the deadletter sub-queue.</span></span>
            </summary>
        <returns><span data-ttu-id="8b122-167">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="8b122-167">The asynchronous operation.</span></span></returns>
        <remarks>
            <span data-ttu-id="8b122-168">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="8b122-168">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="8b122-169">を配信不能サブキューからメッセージを受信するために必要になります、新しい<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />または<see cref="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />、対応するパスにします。</span><span class="sxs-lookup"><span data-stu-id="8b122-169">In order to receive a message from the deadletter sub-queue, you will need a new <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" /> or <see cref="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />, with the corresponding path.</span></span>
            <span data-ttu-id="8b122-170">使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />これを支援します。</span><span class="sxs-lookup"><span data-stu-id="8b122-170">You can use <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> to help with this.</span></span>
            <span data-ttu-id="8b122-171">この操作は、このクライアントで受信したメッセージでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="8b122-171">This operation can only be performed on messages that were received by this client.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
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
        <param name="lockToken"><span data-ttu-id="8b122-172">対応する配信不能メッセージのロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="8b122-172">The lock token of the corresponding message to deadletter.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="8b122-173">サブをキューに移動中に変更するメッセージのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="8b122-173">The properties of the message to modify while moving to sub-queue.</span></span></param>
        <summary>
            <span data-ttu-id="8b122-174">メッセージを配信不能サブキューに移動します。</span><span class="sxs-lookup"><span data-stu-id="8b122-174">Moves a message to the deadletter sub-queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8b122-175">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="8b122-175">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="8b122-176">を配信不能キューからメッセージを受信するために必要になります、新しい<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />、対応するパスにします。</span><span class="sxs-lookup"><span data-stu-id="8b122-176">In order to receive a message from the deadletter queue, you will need a new <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, with the corresponding path.</span></span>
            <span data-ttu-id="8b122-177">使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />これを支援します。</span><span class="sxs-lookup"><span data-stu-id="8b122-177">You can use <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> to help with this.</span></span>
            <span data-ttu-id="8b122-178">この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="8b122-178">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, string deadLetterReason, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.DeadLetterAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, deadLetterReason As String, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.String,System.String)</InterfaceMember>
      </Implements>
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
        <param name="lockToken"><span data-ttu-id="8b122-179">対応する配信不能メッセージのロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="8b122-179">The lock token of the corresponding message to deadletter.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="8b122-180">メッセージの配信不能の理由です。</span><span class="sxs-lookup"><span data-stu-id="8b122-180">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="8b122-181">メッセージの配信不能のエラーの説明。</span><span class="sxs-lookup"><span data-stu-id="8b122-181">The error description for deadlettering the message.</span></span></param>
        <summary>
            <span data-ttu-id="8b122-182">メッセージを配信不能サブキューに移動します。</span><span class="sxs-lookup"><span data-stu-id="8b122-182">Moves a message to the deadletter sub-queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8b122-183">ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。</span><span class="sxs-lookup"><span data-stu-id="8b122-183">A lock token can be found in <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />, only when <see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" /> is set to <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />.</span></span>
            <span data-ttu-id="8b122-184">を配信不能キューからメッセージを受信するために必要になります、新しい<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />、対応するパスにします。</span><span class="sxs-lookup"><span data-stu-id="8b122-184">In order to receive a message from the deadletter queue, you will need a new <see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />, with the corresponding path.</span></span>
            <span data-ttu-id="8b122-185">使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />これを支援します。</span><span class="sxs-lookup"><span data-stu-id="8b122-185">You can use <see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" /> to help with this.</span></span>
            <span data-ttu-id="8b122-186">この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。</span><span class="sxs-lookup"><span data-stu-id="8b122-186">This operation can only be performed on messages that were received by this receiver.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRulesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt; GetRulesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt; GetRulesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.GetRulesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRulesAsync () As Task(Of IEnumerable(Of RuleDescription))" />
      <MemberSignature Language="F#" Value="abstract member GetRulesAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt;&#xA;override this.GetRulesAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt;" Usage="subscriptionClient.GetRulesAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.GetRulesAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SubscriptionClient/&lt;GetRulesAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8b122-187">サブスクリプションに関連付けられているすべてのルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b122-187">Get all rules associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClosingAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnClosingAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnClosingAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.OnClosingAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnClosingAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.OnClosingAsync : unit -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.OnClosingAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SubscriptionClient/&lt;OnClosingAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public override TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.OperationTimeout" />
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
            <span data-ttu-id="8b122-188">個々 の操作がタイムアウトする期間です。</span><span class="sxs-lookup"><span data-stu-id="8b122-188">Duration after which individual operations will timeout.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.Path" />
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
        <summary>
            <span data-ttu-id="8b122-189">サブスクリプション クライアントの形式のパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b122-189">Gets the formatted path of the subscription client.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatSubscriptionPath(System.String,System.String)" />
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.PrefetchCount" />
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
            <span data-ttu-id="8b122-190">メッセージ フローと、1 つのアプリケーションが要求する前にローカルの取得のためすぐに使用できるメッセージがあることを目指していますによってプリフェッチ速度では、受信を使用します。</span><span class="sxs-lookup"><span data-stu-id="8b122-190">Prefetch speeds up the message flow by aiming to have a message readily available for local retrieval when and before the application asks for one using Receive.</span></span>
            <span data-ttu-id="8b122-191">メッセージ数の PrefetchCount をプリフェッチする 0 以外の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="8b122-191">Setting a non-zero value prefetches PrefetchCount number of messages.</span></span>
            <span data-ttu-id="8b122-192">プリフェッチをオフに値を 0 に設定します。</span><span class="sxs-lookup"><span data-stu-id="8b122-192">Setting the value to zero turns prefetch off.</span></span>
            <span data-ttu-id="8b122-193">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="8b122-193">Defaults to 0.</span></span>
            </summary>
        <value><span data-ttu-id="8b122-194">サブスクリプション クライアントが同時に要求メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="8b122-194">The number of messages that the subscription client can simultaneously request.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="8b122-195">プリフェッチを有効にすると、クライアントはサイレント モードでどのようなアプリケーションすぐに確認のより PrefetchCount 上限に達するまで、多くのメッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b122-195">When Prefetch is enabled, the client will quietly acquire more messages, up to the PrefetchCount limit, than what the application immediately asks for.</span></span> <span data-ttu-id="8b122-196">メッセージ ポンプが、メッセージが返されます、すぐに利用できる即時の消費量を取得するためと、クライアントはさらに、バック グラウンドでプリフェッチ バッファーへのメッセージの取得を続行します。</span><span class="sxs-lookup"><span data-stu-id="8b122-196">The message pump will therefore acquire a message for immediate consumption that will be returned as soon as available, and the client will proceed to acquire further messages to fill the prefetch buffer in the background.</span></span>
            </para>
          <para>
            <span data-ttu-id="8b122-197">メッセージは、プリフェッチ バッファーで使用できますが、後続の ReceiveAsync 呼び出しは、バッファーからすぐに満たされ、空き領域ができるように、バック グラウンドでバッファーが補充です。にない場合のメッセージ配信のために使用できる、受信操作は、バッファーのドレインを実行し、まで待機するかどおりをブロックします。</span><span class="sxs-lookup"><span data-stu-id="8b122-197">While messages are available in the prefetch buffer, any subsequent ReceiveAsync calls will be immediately satisfied from the buffer, and the buffer is replenished in the background as space becomes available.If there are no messages available for delivery, the receive operation will drain the buffer and then wait or block as expected.</span></span>
            </para>
          <para><span data-ttu-id="8b122-198">この値に更新プログラムは、サービスの受信呼び出しは、[次へ] を有効になります。</span><span class="sxs-lookup"><span data-stu-id="8b122-198">Updates to this value take effect on the next receive call to the service.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceiveMode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.ReceiveMode : Microsoft.Azure.ServiceBus.ReceiveMode" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode</InterfaceMember>
      </Implements>
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
            <span data-ttu-id="8b122-199">取得、 <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> SubscriptionClient 用です。</span><span class="sxs-lookup"><span data-stu-id="8b122-199">Gets the <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> for the SubscriptionClient.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.RegisteredPlugins" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.IClientEntity.RegisteredPlugins</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8b122-200">この SubscriptionClient 現在登録されているプラグインの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b122-200">Gets a list of currently registered plugins for this SubscriptionClient.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), registerHandlerOptions As MessageHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit" Usage="subscriptionClient.RegisterMessageHandler (handler, messageHandlerOptions)" />
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
        <Parameter Name="registerHandlerOptions" Type="Microsoft.Azure.ServiceBus.MessageHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handler"><span data-ttu-id="8b122-201">A<see cref="T:System.Func`3" />メッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="8b122-201">A <see cref="T:System.Func`3" /> that processes messages.</span></span></param>
        <param name="messageHandlerOptions"><span data-ttu-id="8b122-202"><see cref="T:Microsoft.Azure.ServiceBus.MessageHandlerOptions" />オプション、ポンプの設定を構成するために使用します。</span><span class="sxs-lookup"><span data-stu-id="8b122-202">The <see cref="T:Microsoft.Azure.ServiceBus.MessageHandlerOptions" /> options used to configure the settings of the pump.</span></span></param>
        <summary>
            <span data-ttu-id="8b122-203">継続的に、エンティティからメッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="8b122-203">Receive messages continuously from the entity.</span></span> <span data-ttu-id="8b122-204">メッセージ ハンドラーを登録し、メッセージを受信する新しいスレッドを開始します。</span><span class="sxs-lookup"><span data-stu-id="8b122-204">Registers a message handler and begins a new thread to receive messages.</span></span>
            <span data-ttu-id="8b122-205">このハンドラー (<see cref="T:System.Func`3" />)、受信側で新しいメッセージを受信するたびにでは待機します。</span><span class="sxs-lookup"><span data-stu-id="8b122-205">This handler(<see cref="T:System.Func`3" />) is awaited on every time a new message is received by the receiver.</span></span>
            </summary>
        <remarks><span data-ttu-id="8b122-206">受信レートを高速化するプリフェッチを有効にします。</span><span class="sxs-lookup"><span data-stu-id="8b122-206">Enable prefetch to speed up the receive rate.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="subscriptionClient.RegisterMessageHandler (handler, exceptionReceivedHandler)" />
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
        <param name="handler"><span data-ttu-id="8b122-207">A<see cref="T:System.Func`3" />メッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="8b122-207">A <see cref="T:System.Func`3" /> that processes messages.</span></span></param>
        <param name="exceptionReceivedHandler"><span data-ttu-id="8b122-208">A<see cref="T:System.Func`2" />例外時に呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="8b122-208">A <see cref="T:System.Func`2" /> that is invoked during exceptions.</span></span>
            <span data-ttu-id="8b122-209"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />例外に関するコンテキスト情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="8b122-209"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" /> contains contextual information regarding the exception.</span></span></param>
        <summary>
            <span data-ttu-id="8b122-210">継続的に、エンティティからメッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="8b122-210">Receive messages continuously from the entity.</span></span> <span data-ttu-id="8b122-211">メッセージ ハンドラーを登録し、メッセージを受信する新しいスレッドを開始します。</span><span class="sxs-lookup"><span data-stu-id="8b122-211">Registers a message handler and begins a new thread to receive messages.</span></span>
            <span data-ttu-id="8b122-212">このハンドラー (<see cref="T:System.Func`3" />)、受信側で新しいメッセージを受信するたびにでは待機します。</span><span class="sxs-lookup"><span data-stu-id="8b122-212">This handler(<see cref="T:System.Func`3" />) is awaited on every time a new message is received by the receiver.</span></span>
            </summary>
        <remarks><span data-ttu-id="8b122-213">受信レートを高速化するプリフェッチを有効にします。</span><span class="sxs-lookup"><span data-stu-id="8b122-213">Enable prefetch to speed up the receive rate.</span></span>
            <span data-ttu-id="8b122-214">使用して<see cref="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />ポンプの設定を構成します。</span><span class="sxs-lookup"><span data-stu-id="8b122-214">Use <see cref="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" /> to configure the settings of the pump.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public override void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="override this.RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="subscriptionClient.RegisterPlugin serviceBusPlugin" />
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
        <param name="serviceBusPlugin"><span data-ttu-id="8b122-215"><see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />を登録するには</span><span class="sxs-lookup"><span data-stu-id="8b122-215">The <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> to register</span></span></param>
        <summary>
            <span data-ttu-id="8b122-216">登録、 <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> Service Bus からメッセージを受信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="8b122-216">Registers a <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> to be used for receiving messages from Service Bus.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.SessionHandlerOptions -&gt; unit&#xA;override this.RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.SessionHandlerOptions -&gt; unit" Usage="subscriptionClient.RegisterSessionHandler (handler, sessionHandlerOptions)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)</InterfaceMember>
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
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="sessionHandlerOptions" Type="Microsoft.Azure.ServiceBus.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handler"><span data-ttu-id="8b122-217">A<see cref="T:System.Func`4" />メッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="8b122-217">A <see cref="T:System.Func`4" /> that processes messages.</span></span>
            <span data-ttu-id="8b122-218"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />セッション情報が含まれており、配信不能完了/破棄/やその他のような操作の実行に使用する必要があります、<see cref="T:Microsoft.Azure.ServiceBus.Message" /></span><span class="sxs-lookup"><span data-stu-id="8b122-218"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> contains the session information, and must be used to perform Complete/Abandon/Deadletter or other such operations on the <see cref="T:Microsoft.Azure.ServiceBus.Message" /></span></span></param>
        <param name="sessionHandlerOptions"><span data-ttu-id="8b122-219">オプションは、セッションのポンプの設定を構成するために使用します。</span><span class="sxs-lookup"><span data-stu-id="8b122-219">Options used to configure the settings of the session pump.</span></span></param>
        <summary>
            <span data-ttu-id="8b122-220">継続的に、キューからセッション メッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="8b122-220">Receive session messages continuously from the queue.</span></span> <span data-ttu-id="8b122-221">メッセージ ハンドラーを登録し、セッション メッセージを受信する新しいスレッドを開始します。</span><span class="sxs-lookup"><span data-stu-id="8b122-221">Registers a message handler and begins a new thread to receive session-messages.</span></span>
            <span data-ttu-id="8b122-222">このハンドラー (<see cref="T:System.Func`4" />) サブスクリプション クライアントが新しいメッセージを受信するたびにでは待機します。</span><span class="sxs-lookup"><span data-stu-id="8b122-222">This handler(<see cref="T:System.Func`4" />) is awaited on every time a new message is received by the subscription client.</span></span>
            </summary>
        <remarks><span data-ttu-id="8b122-223">受信レートを高速化するプリフェッチを有効にします。</span><span class="sxs-lookup"><span data-stu-id="8b122-223">Enable prefetch to speed up the receive rate.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handler As Func(Of IMessageSession, Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="subscriptionClient.RegisterSessionHandler (handler, exceptionReceivedHandler)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})</InterfaceMember>
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
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="exceptionReceivedHandler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="handler"><span data-ttu-id="8b122-224">A<see cref="T:System.Func`4" />メッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="8b122-224">A <see cref="T:System.Func`4" /> that processes messages.</span></span>
            <span data-ttu-id="8b122-225"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />セッション情報が含まれており、配信不能完了/破棄/やその他のような操作の実行に使用する必要があります、<see cref="T:Microsoft.Azure.ServiceBus.Message" /></span><span class="sxs-lookup"><span data-stu-id="8b122-225"><see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> contains the session information, and must be used to perform Complete/Abandon/Deadletter or other such operations on the <see cref="T:Microsoft.Azure.ServiceBus.Message" /></span></span></param>
        <param name="exceptionReceivedHandler"><span data-ttu-id="8b122-226">A<see cref="T:System.Func`2" />例外時に呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="8b122-226">A <see cref="T:System.Func`2" /> that is invoked during exceptions.</span></span>
            <span data-ttu-id="8b122-227"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />例外に関するコンテキスト情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="8b122-227"><see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" /> contains contextual information regarding the exception.</span></span></param>
        <summary>
            <span data-ttu-id="8b122-228">継続的に、キューからセッション メッセージを受信します。</span><span class="sxs-lookup"><span data-stu-id="8b122-228">Receive session messages continuously from the queue.</span></span> <span data-ttu-id="8b122-229">メッセージ ハンドラーを登録し、セッション メッセージを受信する新しいスレッドを開始します。</span><span class="sxs-lookup"><span data-stu-id="8b122-229">Registers a message handler and begins a new thread to receive session-messages.</span></span>
            <span data-ttu-id="8b122-230">このハンドラー (<see cref="T:System.Func`4" />) サブスクリプション クライアントが新しいメッセージを受信するたびにでは待機します。</span><span class="sxs-lookup"><span data-stu-id="8b122-230">This handler(<see cref="T:System.Func`4" />) is awaited on every time a new message is received by the subscription client.</span></span>
            </summary>
        <remarks>  <span data-ttu-id="8b122-231">受信レートを高速化するプリフェッチを有効にします。</span><span class="sxs-lookup"><span data-stu-id="8b122-231">Enable prefetch to speed up the receive rate.</span></span>
            <span data-ttu-id="8b122-232">使用して<see cref="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />ポンプの設定を構成します。</span><span class="sxs-lookup"><span data-stu-id="8b122-232">Use <see cref="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" /> to configure the settings of the pump.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveRuleAsync (string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveRuleAsync(string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RemoveRuleAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveRuleAsync (ruleName As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveRuleAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.RemoveRuleAsync : string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RemoveRuleAsync ruleName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RemoveRuleAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SubscriptionClient/&lt;RemoveRuleAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ruleName"><span data-ttu-id="8b122-233">ルールの名前。</span><span class="sxs-lookup"><span data-stu-id="8b122-233">The name of the rule.</span></span></param>
        <summary>
            <span data-ttu-id="8b122-234">によって識別されるサブスクリプションの規則を削除します<paramref name="ruleName" />です。</span><span class="sxs-lookup"><span data-stu-id="8b122-234">Removes the rule on the subscription identified by <paramref name="ruleName" />.</span></span>
            </summary>
        <returns><span data-ttu-id="8b122-235">非同期の削除規則の操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="8b122-235">A task instance that represents the asynchronous remove rule operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionName">
      <MemberSignature Language="C#" Value="public string SubscriptionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.SubscriptionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionName As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionName : string" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.SubscriptionName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.ISubscriptionClient.SubscriptionName</InterfaceMember>
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
        <summary>
            <span data-ttu-id="8b122-236">サブスクリプションの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="8b122-236">Gets the name of the subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicPath">
      <MemberSignature Language="C#" Value="public string TopicPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.TopicPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TopicPath As String" />
      <MemberSignature Language="F#" Value="member this.TopicPath : string" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.TopicPath" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.ISubscriptionClient.TopicPath</InterfaceMember>
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
        <summary>
            <span data-ttu-id="8b122-237">対応するトピックのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="8b122-237">Gets the path of the corresponding topic.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public override void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="override this.UnregisterPlugin : string -&gt; unit" Usage="subscriptionClient.UnregisterPlugin serviceBusPluginName" />
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
        <param name="serviceBusPluginName"><span data-ttu-id="8b122-238">名前<see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" />登録解除する</span><span class="sxs-lookup"><span data-stu-id="8b122-238">The name <see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" /> to be unregistered</span></span></param>
        <summary>
            <span data-ttu-id="8b122-239">登録を解除、<see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />です。</span><span class="sxs-lookup"><span data-stu-id="8b122-239">Unregisters a <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>