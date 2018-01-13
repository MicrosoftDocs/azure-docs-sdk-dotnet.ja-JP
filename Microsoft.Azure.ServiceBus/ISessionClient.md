<Type Name="ISessionClient" FullName="Microsoft.Azure.ServiceBus.ISessionClient">
  <TypeSignature Language="C#" Value="public interface ISessionClient : Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISessionClient implements class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ISessionClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISessionClient&#xA;Implements IClientEntity" />
  <TypeSignature Language="F#" Value="type ISessionClient = interface&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
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
             <span data-ttu-id="4a98d-101">セッションのクライアントについて説明します。</span><span class="sxs-lookup"><span data-stu-id="4a98d-101">Describes a Session client.</span></span> <span data-ttu-id="4a98d-102">セッションのクライアントは、同じセッション Id ですべてのメッセージと対話するために使用するセッション オブジェクトを受け入れるように使用できます。</span><span class="sxs-lookup"><span data-stu-id="4a98d-102">A session client can be used to accept session objects which can be used to interact with all messages with the same sessionId.</span></span>
             </summary>
    <remarks>
             <span data-ttu-id="4a98d-103">任意のセッションまたは特定のセッションを受け入れることができます (によって識別される<see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />セッション クライアントを使用します。</span><span class="sxs-lookup"><span data-stu-id="4a98d-103">You can accept any session or a given session (identified by <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> using a session client.</span></span>
             <span data-ttu-id="4a98d-104">セッションを同意すると、としてそれを使用できます、<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />同じセッション id を持つメッセージのみを受信します。参照してください<see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />セッション オブジェクトの使用法をします。</span><span class="sxs-lookup"><span data-stu-id="4a98d-104">Once you accept a session, you can use it as a <see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" /> which receives only messages having the same session id. See <see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" /> for usage of session object.</span></span>
             <span data-ttu-id="4a98d-105"><example>新しい SessionClient を作成するには</span><span class="sxs-lookup"><span data-stu-id="4a98d-105"><example> To create a new SessionClient</span></span>
             <code>
             ISessionClient sessionClient = new SessionClient(
             namespaceConnectionString,
             queueName,
                 ReceiveMode.PeekLock);
                 </code>
                 
             <span data-ttu-id="4a98d-106">指定したセッション Id のセッション オブジェクトを受信するには</span><span class="sxs-lookup"><span data-stu-id="4a98d-106">To receive a session object for a given sessionId</span></span>
            <code>
             IMessageSession session = await sessionClient.AcceptMessageSessionAsync(sessionId);
             </code>
             
             <span data-ttu-id="4a98d-107">任意のセッションを受信するには</span><span class="sxs-lookup"><span data-stu-id="4a98d-107">To receive any session</span></span>
            <code>
             IMessageSession session = await sessionClient.AcceptMessageSessionAsync();
             </code></example></remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.SessionClient" />
  </Docs>
  <Members>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="iSessionClient.AcceptMessageSessionAsync " />
      <MemberType>Method</MemberType>
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
            <span data-ttu-id="4a98d-108">任意のセッション オブジェクトを取得<see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />そのわかり、sessionId のメッセージの受信に使用できます。</span><span class="sxs-lookup"><span data-stu-id="4a98d-108">Gets a session object of any <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> that can be used to receive messages for that sessionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="4a98d-109">登録されているすべてのプラグイン<see cref="T:Microsoft.Azure.ServiceBus.SessionClient" />それぞれに適用される<see cref="T:Microsoft.Azure.ServiceBus.MessageSession" />は受け入れられます。</span><span class="sxs-lookup"><span data-stu-id="4a98d-109">All plugins registered on <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> will be applied to each <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> that is accepted.</span></span>
            <span data-ttu-id="4a98d-110">個別のセッションは、追加プラグインをさらに登録できます。</span><span class="sxs-lookup"><span data-stu-id="4a98d-110">Individual sessions can further register additional plugins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="iSessionClient.AcceptMessageSessionAsync sessionId" />
      <MemberType>Method</MemberType>
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
        <param name="sessionId"><span data-ttu-id="4a98d-111">SessionId そのすべてのメッセージ内に存在します。</span><span class="sxs-lookup"><span data-stu-id="4a98d-111">The sessionId present in all its messages.</span></span></param>
        <summary>
            <span data-ttu-id="4a98d-112">によって識別される特定のセッション オブジェクトを取得<paramref name="sessionId" />そのわかり、sessionId のメッセージの受信に使用できます。</span><span class="sxs-lookup"><span data-stu-id="4a98d-112">Gets a particular session object identified by <paramref name="sessionId" /> that can be used to receive messages for that sessionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="4a98d-113">登録されているすべてのプラグイン<see cref="T:Microsoft.Azure.ServiceBus.SessionClient" />それぞれに適用される<see cref="T:Microsoft.Azure.ServiceBus.MessageSession" />は受け入れられます。</span><span class="sxs-lookup"><span data-stu-id="4a98d-113">All plugins registered on <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> will be applied to each <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> that is accepted.</span></span>
            <span data-ttu-id="4a98d-114">個別のセッションは、追加プラグインをさらに登録できます。</span><span class="sxs-lookup"><span data-stu-id="4a98d-114">Individual sessions can further register additional plugins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="iSessionClient.AcceptMessageSessionAsync serverWaitTime" />
      <MemberType>Method</MemberType>
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
        <param name="serverWaitTime"><span data-ttu-id="4a98d-115">呼び出しが待機する対象の次のセッションをフェッチする時間です。</span><span class="sxs-lookup"><span data-stu-id="4a98d-115">Amount of time for which the call should wait for to fetch the next session.</span></span></param>
        <summary>
            <span data-ttu-id="4a98d-116">任意のセッション オブジェクトを取得<see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />そのわかり、sessionId のメッセージの受信に使用できます。</span><span class="sxs-lookup"><span data-stu-id="4a98d-116">Gets a session object of any <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> that can be used to receive messages for that sessionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="4a98d-117">登録されているすべてのプラグイン<see cref="T:Microsoft.Azure.ServiceBus.SessionClient" />それぞれに適用される<see cref="T:Microsoft.Azure.ServiceBus.MessageSession" />は受け入れられます。</span><span class="sxs-lookup"><span data-stu-id="4a98d-117">All plugins registered on <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> will be applied to each <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> that is accepted.</span></span>
            <span data-ttu-id="4a98d-118">個別のセッションは、追加プラグインをさらに登録できます。</span><span class="sxs-lookup"><span data-stu-id="4a98d-118">Individual sessions can further register additional plugins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, serverWaitTime As TimeSpan) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="iSessionClient.AcceptMessageSessionAsync (sessionId, serverWaitTime)" />
      <MemberType>Method</MemberType>
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
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId"><span data-ttu-id="4a98d-119">SessionId そのすべてのメッセージ内に存在します。</span><span class="sxs-lookup"><span data-stu-id="4a98d-119">The sessionId present in all its messages.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4a98d-120">呼び出しが待機する対象の次のセッションをフェッチする時間です。</span><span class="sxs-lookup"><span data-stu-id="4a98d-120">Amount of time for which the call should wait for to fetch the next session.</span></span></param>
        <summary>
            <span data-ttu-id="4a98d-121">によって識別される特定のセッション オブジェクトを取得<paramref name="sessionId" />そのわかり、sessionId のメッセージの受信に使用できます。</span><span class="sxs-lookup"><span data-stu-id="4a98d-121">Gets a particular session object identified by <paramref name="sessionId" /> that can be used to receive messages for that sessionId.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="4a98d-122">登録されているすべてのプラグイン<see cref="T:Microsoft.Azure.ServiceBus.SessionClient" />それぞれに適用される<see cref="T:Microsoft.Azure.ServiceBus.MessageSession" />は受け入れられます。</span><span class="sxs-lookup"><span data-stu-id="4a98d-122">All plugins registered on <see cref="T:Microsoft.Azure.ServiceBus.SessionClient" /> will be applied to each <see cref="T:Microsoft.Azure.ServiceBus.MessageSession" /> that is accepted.</span></span>
            <span data-ttu-id="4a98d-123">個別のセッションは、追加プラグインをさらに登録できます。</span><span class="sxs-lookup"><span data-stu-id="4a98d-123">Individual sessions can further register additional plugins.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ISessionClient.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string" Usage="Microsoft.Azure.ServiceBus.ISessionClient.EntityPath" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="4a98d-124">エンティティのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="4a98d-124">Gets the path of the entity.</span></span> <span data-ttu-id="4a98d-125">これは、キューの名前またはサブスクリプションの完全なパスのいずれかです。</span><span class="sxs-lookup"><span data-stu-id="4a98d-125">This is either the name of the queue, or the full path of the subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>