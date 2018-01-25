<Type Name="SessionClient" FullName="Microsoft.Azure.ServiceBus.SessionClient">
  <TypeSignature Language="C#" Value="public sealed class SessionClient : Microsoft.Azure.ServiceBus.ClientEntity, Microsoft.Azure.ServiceBus.ISessionClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SessionClient extends Microsoft.Azure.ServiceBus.ClientEntity implements class Microsoft.Azure.ServiceBus.IClientEntity, class Microsoft.Azure.ServiceBus.ISessionClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.SessionClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SessionClient&#xA;Inherits ClientEntity&#xA;Implements ISessionClient" />
  <TypeSignature Language="F#" Value="type SessionClient = class&#xA;    inherit ClientEntity&#xA;    interface ISessionClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.ISessionClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="23c08-101">セッションのクライアントは、同じセッション Id ですべてのメッセージと対話するために使用するセッション オブジェクトを受け入れるように使用できます。</span><span class="sxs-lookup"><span data-stu-id="23c08-101">A session client can be used to accept session objects which can be used to interact with all messages with the same sessionId.</span></span>
             </summary>
    <remarks>
             <span data-ttu-id="23c08-102">任意のセッションまたは特定のセッションを受け入れることができます (によって識別される<see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />セッション クライアントを使用します。</span><span class="sxs-lookup"><span data-stu-id="23c08-102">You can accept any session or a given session (identified by <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> using a session client.</span></span>
             <span data-ttu-id="23c08-103">セッションを同意すると、としてそれを使用できます、<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />同じセッション id を持つメッセージのみを受信します。参照してください<see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />セッション オブジェクトの使用法をします。</span><span class="sxs-lookup"><span data-stu-id="23c08-103">Once you accept a session, you can use it as a <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> which receives only messages having the same session id. See <see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> for usage of session object.</span></span>
             <span data-ttu-id="23c08-104">これは、AMQP プロトコルを使用して、サービスと通信します。</span><span class="sxs-lookup"><span data-stu-id="23c08-104">This uses AMQP protocol to communicate with the service.</span></span>
             </remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />
    <example>
             <span data-ttu-id="23c08-105">新しい SessionClient を作成するには</span><span class="sxs-lookup"><span data-stu-id="23c08-105">To create a new SessionClient</span></span>
             <code>
             ISessionClient sessionClient = new SessionClient(
                 namespaceConnectionString,
                 queueName,
                 ReceiveMode.PeekLock);
             </code>
            
             <span data-ttu-id="23c08-106">指定したセッション Id のセッション オブジェクトを受信するには</span><span class="sxs-lookup"><span data-stu-id="23c08-106">To receive a session object for a given sessionId</span></span>
             <code>
             IMessageSession session = await sessionClient.AcceptMessageSessionAsync(sessionId);
             </code>
            
             <span data-ttu-id="23c08-107">任意のセッションを受信するには</span><span class="sxs-lookup"><span data-stu-id="23c08-107">To receive any session</span></span>
             <code>
             IMessageSession session = await sessionClient.AcceptMessageSessionAsync();
             </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionClient (Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null, int prefetchCount = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy, int32 prefetchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.#ctor(Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SessionClient : Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy * int -&gt; Microsoft.Azure.ServiceBus.SessionClient" Usage="new Microsoft.Azure.ServiceBus.SessionClient (connectionStringBuilder, receiveMode, retryPolicy, prefetchCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
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
        <param name="connectionStringBuilder"><span data-ttu-id="23c08-108"><see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />エンティティ レベルの接続の詳細を持ちます。</span><span class="sxs-lookup"><span data-stu-id="23c08-108">The <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /> having entity level connection details.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="23c08-109"><see cref="P:Microsoft.Azure.ServiceBus.SessionClient.ReceiveMode" />メッセージを受信する方法を指定するために使用します。</span><span class="sxs-lookup"><span data-stu-id="23c08-109">The <see cref="P:Microsoft.Azure.ServiceBus.SessionClient.ReceiveMode" /> used to specify how messages are received.</span></span> <span data-ttu-id="23c08-110">PeekLock モードに既定値です。</span><span class="sxs-lookup"><span data-stu-id="23c08-110">Defaults to PeekLock mode.</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="23c08-111"><see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> ServiceBus との通信に使用されます。</span><span class="sxs-lookup"><span data-stu-id="23c08-111">The <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> that will be used when communicating with ServiceBus.</span></span> <span data-ttu-id="23c08-112">既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span><span class="sxs-lookup"><span data-stu-id="23c08-112">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span></span></param>
        <param name="prefetchCount"><span data-ttu-id="23c08-113"><see cref="P:Microsoft.Azure.ServiceBus.SessionClient.PrefetchCount" />セッション オブジェクトは、受信操作が保留されているかどうかに関係なくアクティブに受信メッセージの数の上限を指定します。</span><span class="sxs-lookup"><span data-stu-id="23c08-113">The <see cref="P:Microsoft.Azure.ServiceBus.SessionClient.PrefetchCount" /> that specifies the upper limit of messages the session object will actively receive regardless of whether a receive operation is pending.</span></span> <span data-ttu-id="23c08-114">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="23c08-114">Defaults to 0.</span></span></param>
        <summary>
            <span data-ttu-id="23c08-115">新しい SessionClient を作成します。<see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /></span><span class="sxs-lookup"><span data-stu-id="23c08-115">Creates a new SessionClient from a <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /></span></span></summary>
        <remarks><span data-ttu-id="23c08-116">すべてのセッション オブジェクトに使用すると、エンティティに新しい接続を作成するこのクライアントを使用して受け入れられます。</span><span class="sxs-lookup"><span data-stu-id="23c08-116">Creates a new connection to the entity, which is used for all the sessions objects accepted using this client.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionClient (string connectionString, string entityPath, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null, int prefetchCount = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string entityPath, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy, int32 prefetchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SessionClient : string * string * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy * int -&gt; Microsoft.Azure.ServiceBus.SessionClient" Usage="new Microsoft.Azure.ServiceBus.SessionClient (connectionString, entityPath, receiveMode, retryPolicy, prefetchCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
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
        <param name="connectionString"><span data-ttu-id="23c08-117">Service Bus との通信に使用される Namespace 接続文字列。</span><span class="sxs-lookup"><span data-stu-id="23c08-117">Namespace connection string used to communicate with Service Bus.</span></span> <span data-ttu-id="23c08-118">エンティティの詳細が含まれていない必要があります。</span><span class="sxs-lookup"><span data-stu-id="23c08-118">Must not contain entity details.</span></span></param>
        <param name="entityPath"><span data-ttu-id="23c08-119">この受信者を表すエンティティのパス。</span><span class="sxs-lookup"><span data-stu-id="23c08-119">The path of the entity for this receiver.</span></span> <span data-ttu-id="23c08-120">キューのこれは、名前ですが完全なパスを指定このサブスクリプションの場合。</span><span class="sxs-lookup"><span data-stu-id="23c08-120">For Queues this will be the name, but for Subscriptions this will be the full path.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="23c08-121"><see cref="P:Microsoft.Azure.ServiceBus.SessionClient.ReceiveMode" />メッセージを受信する方法を指定するために使用します。</span><span class="sxs-lookup"><span data-stu-id="23c08-121">The <see cref="P:Microsoft.Azure.ServiceBus.SessionClient.ReceiveMode" /> used to specify how messages are received.</span></span> <span data-ttu-id="23c08-122">PeekLock モードに既定値です。</span><span class="sxs-lookup"><span data-stu-id="23c08-122">Defaults to PeekLock mode.</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="23c08-123"><see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> ServiceBus との通信に使用されます。</span><span class="sxs-lookup"><span data-stu-id="23c08-123">The <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> that will be used when communicating with ServiceBus.</span></span> <span data-ttu-id="23c08-124">既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span><span class="sxs-lookup"><span data-stu-id="23c08-124">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span></span></param>
        <param name="prefetchCount"><span data-ttu-id="23c08-125"><see cref="P:Microsoft.Azure.ServiceBus.SessionClient.PrefetchCount" />セッション オブジェクトは、受信操作が保留されているかどうかに関係なくアクティブに受信メッセージの数の上限を指定します。</span><span class="sxs-lookup"><span data-stu-id="23c08-125">The <see cref="P:Microsoft.Azure.ServiceBus.SessionClient.PrefetchCount" /> that specifies the upper limit of messages the session object will actively receive regardless of whether a receive operation is pending.</span></span> <span data-ttu-id="23c08-126">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="23c08-126">Defaults to 0.</span></span></param>
        <summary>
            <span data-ttu-id="23c08-127">指定された接続文字列およびエンティティ パスから新しい SessionClient を作成します。</span><span class="sxs-lookup"><span data-stu-id="23c08-127">Creates a new SessionClient from a specified connection string and entity path.</span></span>
            </summary>
        <remarks><span data-ttu-id="23c08-128">すべてのセッション オブジェクトに使用すると、エンティティに新しい接続を作成するこのクライアントを使用して受け入れられます。</span><span class="sxs-lookup"><span data-stu-id="23c08-128">Creates a new connection to the entity, which is used for all the sessions objects accepted using this client.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="sessionClient.AcceptMessageSessionAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23c08-129">任意のセッション オブジェクトを取得<see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />そのわかり、sessionId のメッセージの受信に使用できます。</span><span class="sxs-lookup"><span data-stu-id="23c08-129">Gets a session object of any <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> that can be used to receive messages for that sessionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="23c08-130">登録されているすべてのプラグイン<see cref="T:Microsoft.Azure.ServiceBus.SessionClient" />それぞれに適用される<see cref="T:Microsoft.Azure.ServiceBus.MessageSession" />は受け入れられます。</span><span class="sxs-lookup"><span data-stu-id="23c08-130">All plugins registered on <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> will be applied to each <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> that is accepted.</span></span>
            <span data-ttu-id="23c08-131">個別のセッションは、追加プラグインをさらに登録できます。</span><span class="sxs-lookup"><span data-stu-id="23c08-131">Individual sessions can further register additional plugins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.AcceptMessageSessionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="sessionClient.AcceptMessageSessionAsync sessionId" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sessionId"><span data-ttu-id="23c08-132">SessionId そのすべてのメッセージ内に存在します。</span><span class="sxs-lookup"><span data-stu-id="23c08-132">The sessionId present in all its messages.</span></span></param>
        <summary>
            <span data-ttu-id="23c08-133">によって識別される特定のセッション オブジェクトを取得<paramref name="sessionId" />そのわかり、sessionId のメッセージの受信に使用できます。</span><span class="sxs-lookup"><span data-stu-id="23c08-133">Gets a particular session object identified by <paramref name="sessionId" /> that can be used to receive messages for that sessionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="23c08-134">登録されているすべてのプラグイン<see cref="T:Microsoft.Azure.ServiceBus.SessionClient" />それぞれに適用される<see cref="T:Microsoft.Azure.ServiceBus.MessageSession" />は受け入れられます。</span><span class="sxs-lookup"><span data-stu-id="23c08-134">All plugins registered on <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> will be applied to each <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> that is accepted.</span></span>
            <span data-ttu-id="23c08-135">個別のセッションは、追加プラグインをさらに登録できます。</span><span class="sxs-lookup"><span data-stu-id="23c08-135">Individual sessions can further register additional plugins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="sessionClient.AcceptMessageSessionAsync serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime"><span data-ttu-id="23c08-136">呼び出しが 次のセッションをフェッチする待機時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="23c08-136">Amount of time for which the call should wait to fetch the next session.</span></span></param>
        <summary>
            <span data-ttu-id="23c08-137">任意のセッション オブジェクトを取得<see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />そのわかり、sessionId のメッセージの受信に使用できます。</span><span class="sxs-lookup"><span data-stu-id="23c08-137">Gets a session object of any <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> that can be used to receive messages for that sessionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="23c08-138">登録されているすべてのプラグイン<see cref="T:Microsoft.Azure.ServiceBus.SessionClient" />それぞれに適用される<see cref="T:Microsoft.Azure.ServiceBus.MessageSession" />は受け入れられます。</span><span class="sxs-lookup"><span data-stu-id="23c08-138">All plugins registered on <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> will be applied to each <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> that is accepted.</span></span>
            <span data-ttu-id="23c08-139">個別のセッションは、追加プラグインをさらに登録できます。</span><span class="sxs-lookup"><span data-stu-id="23c08-139">Individual sessions can further register additional plugins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, serverWaitTime As TimeSpan) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="sessionClient.AcceptMessageSessionAsync (sessionId, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SessionClient/&lt;AcceptMessageSessionAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId"><span data-ttu-id="23c08-140">SessionId そのすべてのメッセージ内に存在します。</span><span class="sxs-lookup"><span data-stu-id="23c08-140">The sessionId present in all its messages.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="23c08-141">呼び出しが 次のセッションをフェッチする待機時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="23c08-141">Amount of time for which the call should wait to fetch the next session.</span></span></param>
        <summary>
            <span data-ttu-id="23c08-142">によって識別される特定のセッション オブジェクトを取得<paramref name="sessionId" />そのわかり、sessionId のメッセージの受信に使用できます。</span><span class="sxs-lookup"><span data-stu-id="23c08-142">Gets a particular session object identified by <paramref name="sessionId" /> that can be used to receive messages for that sessionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="23c08-143">登録されているすべてのプラグイン<see cref="T:Microsoft.Azure.ServiceBus.SessionClient" />それぞれに適用される<see cref="T:Microsoft.Azure.ServiceBus.MessageSession" />は受け入れられます。</span><span class="sxs-lookup"><span data-stu-id="23c08-143">All plugins registered on <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> will be applied to each <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> that is accepted.</span></span>
            <span data-ttu-id="23c08-144">個別のセッションは、追加プラグインをさらに登録できます。</span><span class="sxs-lookup"><span data-stu-id="23c08-144">Individual sessions can further register additional plugins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionClient.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string" Usage="Microsoft.Azure.ServiceBus.SessionClient.EntityPath" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.ISessionClient.EntityPath</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23c08-145">エンティティのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="23c08-145">Gets the path of the entity.</span></span> <span data-ttu-id="23c08-146">これは、キューの名前またはサブスクリプションの完全なパスのいずれかです。</span><span class="sxs-lookup"><span data-stu-id="23c08-146">This is either the name of the queue, or the full path of the subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClosingAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnClosingAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnClosingAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.OnClosingAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnClosingAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.OnClosingAsync : unit -&gt; System.Threading.Tasks.Task" Usage="sessionClient.OnClosingAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SessionClient/&lt;OnClosingAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public override TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionClient.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.SessionClient.OperationTimeout" />
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
            <span data-ttu-id="23c08-147">個々 の操作がタイムアウトする期間です。</span><span class="sxs-lookup"><span data-stu-id="23c08-147">Duration after which individual operations will timeout.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionClient.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.SessionClient.RegisteredPlugins" />
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
            <span data-ttu-id="23c08-148">現在登録されているプラグインの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="23c08-148">Gets a list of currently registered plugins.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public override void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="override this.RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="sessionClient.RegisterPlugin serviceBusPlugin" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IClientEntity.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)</InterfaceMember>
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
        <Parameter Name="serviceBusPlugin" Type="Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />
      </Parameters>
      <Docs>
        <param name="serviceBusPlugin"><span data-ttu-id="23c08-149">登録する <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />。</span><span class="sxs-lookup"><span data-stu-id="23c08-149">The <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> to register.</span></span></param>
        <summary>
            <span data-ttu-id="23c08-150">登録、<see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />このレシーバーと共に使用します。</span><span class="sxs-lookup"><span data-stu-id="23c08-150">Registers a <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> to be used with this receiver.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public override void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="override this.UnregisterPlugin : string -&gt; unit" Usage="sessionClient.UnregisterPlugin serviceBusPluginName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IClientEntity.UnregisterPlugin(System.String)</InterfaceMember>
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
        <Parameter Name="serviceBusPluginName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceBusPluginName"><span data-ttu-id="23c08-151"><see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" />の登録解除するプラグイン。</span><span class="sxs-lookup"><span data-stu-id="23c08-151">The <see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" /> of the plugin to be unregistered.</span></span></param>
        <summary>
            <span data-ttu-id="23c08-152">登録を解除、<see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />です。</span><span class="sxs-lookup"><span data-stu-id="23c08-152">Unregisters a <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>