<Type Name="SubscriptionClient" FullName="Microsoft.ServiceBus.Messaging.SubscriptionClient">
  <TypeSignature Language="C#" Value="public abstract class SubscriptionClient : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit SubscriptionClient extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class SubscriptionClient&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type SubscriptionClient = class&#xA;    inherit ClientEntity&#xA;    interface IMessageSessionEntity&#xA;    interface IMessageClientEntity&#xA;    interface IMessageReceiver&#xA;    interface IMessageBrowser" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="09329-101">トピック サブスクリプションに関連する実行時の操作で使用されるアンカー クラスを表します。</span><span class="sxs-lookup"><span data-stu-id="09329-101">Represents the anchor class used in run-time operations related to a topic subscription.</span></span></summary>
    <remarks>To be added.</remarks>
    <example>
      <code>
            <span data-ttu-id="09329-102">サブスクリプション クライアント SubscriptionClient mySubscriptionClient を作成するファクトリを = です。CreateSubscriptionClient(mySubscription) です。</span><span class="sxs-lookup"><span data-stu-id="09329-102">// Create subscription client SubscriptionClient mySubscriptionClient = factory.CreateSubscriptionClient(mySubscription);</span></span>
            
            <span data-ttu-id="09329-103">メッセージを受信する (int カウント = 0 になります。 カウント&lt;MsgCount; 数 + +) {var メッセージ = mySubscriptionClient.Receive(); message.Complete() です。}</span><span class="sxs-lookup"><span data-stu-id="09329-103">// Receive messages for (int count = 0; count &lt; MsgCount; count++) { var message = mySubscriptionClient.Receive(); message.Complete(); }</span></span>
            </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Abandon(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid -&gt; unit&#xA;override this.Abandon : Guid -&gt; unit" Usage="subscriptionClient.Abandon lockToken" />
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
        <param name="lockToken"><span data-ttu-id="09329-104">ロック トークンは、破棄するロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-104">The lock token bound to the locked message instance to abandon.</span></span></param>
        <summary><span data-ttu-id="09329-105">メッセージを破棄し、メッセージのロックの所有権を放棄します。</span><span class="sxs-lookup"><span data-stu-id="09329-105">Discards the message and relinquishes the message lock ownership.</span></span></summary>
        <remarks><span data-ttu-id="09329-106">クライアントは、キュー/トピックからメッセージを取得します。 失敗した場合、このメソッドを呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="09329-106">When the client fails to get the message from the queue/topic, this method should be called.</span></span> <span data-ttu-id="09329-107">Service Bus には、メッセージの配信回数が 1 ずつ増分されます。</span><span class="sxs-lookup"><span data-stu-id="09329-107">Service Bus will increment the delivery count of the message.</span></span> <span data-ttu-id="09329-108">クライアントには、メッセージが再度表示されるか、配信不能キューに移動を試行するか、ようになりましたことができます。</span><span class="sxs-lookup"><span data-stu-id="09329-108">The client now can either attempt to receive the message again or move it to the dead-letter queue.</span></span></remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="09329-109">操作を使用して設定されたタイムアウト値を超過した場合にスロー<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-109">Thrown if the operation exceeded the timeout value set via <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="09329-110">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-110">Thrown if the client entity has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Abandon(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="subscriptionClient.Abandon (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="09329-111">ロック トークンは、破棄するロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-111">The lock token bound to the locked message instance to abandon.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="09329-112">変更するプロパティ オブジェクトのコレクション。</span><span class="sxs-lookup"><span data-stu-id="09329-112">A collection of property objects to be modified.</span></span></param>
        <summary><span data-ttu-id="09329-113">メッセージを破棄し、メッセージのロックの所有権を放棄します。</span><span class="sxs-lookup"><span data-stu-id="09329-113">Discards the message and relinquishes the message lock ownership.</span></span></summary>
        <remarks><span data-ttu-id="09329-114">クライアントは、キュー/トピックからメッセージを取得します。 失敗した場合、このメソッドを呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="09329-114">When the client fails to get the message from the queue/topic, this method should be called.</span></span> <span data-ttu-id="09329-115">Service Bus には、メッセージの配信回数が 1 ずつ増分されます。</span><span class="sxs-lookup"><span data-stu-id="09329-115">Service Bus will increment the delivery count of the message.</span></span> <span data-ttu-id="09329-116">クライアントには、メッセージが再度表示されるか、配信不能キューに移動を試行するか、ようになりましたことができます。</span><span class="sxs-lookup"><span data-stu-id="09329-116">The client now can either attempt to receive the message again or move it to the dead-letter queue.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AbandonAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AbandonAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="09329-117">ロック トークンは、破棄するロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-117">The lock token bound to the locked message instance to abandon.</span></span></param>
        <summary><span data-ttu-id="09329-118">非同期的にメッセージを破棄し、メッセージのロックの所有権を放棄します。</span><span class="sxs-lookup"><span data-stu-id="09329-118">Asynchronously discards the message and relinquishes the message lock ownership.</span></span></summary>
        <returns><span data-ttu-id="09329-119">非同期の破棄操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-119">A task instance that represents the asynchronous abandon operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AbandonAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AbandonAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="09329-120">ロック トークンは、破棄するロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-120">The lock token bound to the locked message instance to abandon.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="09329-121">変更するプロパティ オブジェクトのコレクション。</span><span class="sxs-lookup"><span data-stu-id="09329-121">A collection of property objects to be modified.</span></span></param>
        <summary><span data-ttu-id="09329-122">非同期的にメッセージを破棄し、メッセージのロックの所有権を放棄します。</span><span class="sxs-lookup"><span data-stu-id="09329-122">Asynchronously discards the message and relinquishes the message lock ownership.</span></span></summary>
        <returns><span data-ttu-id="09329-123">非同期の破棄操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-123">A task instance that represents the asynchronous abandon operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession () As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : unit -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : unit -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="09329-124">1 つのトランザクションで処理するための関連するメッセージのグループ化したメッセージのセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="09329-124">Accepts a message session that allows grouping of related messages for processing in a single transaction.</span></span></summary>
        <returns><span data-ttu-id="09329-125">A<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</span><span class="sxs-lookup"><span data-stu-id="09329-125">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (isExclusiveMode As Boolean) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession isExclusiveMode" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="isExclusiveMode">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession sessionId" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sessionId"><span data-ttu-id="09329-126">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="09329-126">The session identifier of the message session.</span></span></param>
        <summary><span data-ttu-id="09329-127">特定のセッション識別子を使用して、単一のトランザクションで処理するための関連するメッセージのグループ化をできるメッセージ セッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="09329-127">Accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier.</span></span></summary>
        <returns><span data-ttu-id="09329-128">A<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</span><span class="sxs-lookup"><span data-stu-id="09329-128">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="09329-129">セッション Id が null、空、または空白文字である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-129">Thrown if sessionId is null, empty, or white spaces.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="09329-130">操作によって設定されたタイムアウト値を超過した場合にスロー<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-130">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="09329-131">クライアントが既に終了、中止、または破棄される場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-131">Thrown if the client is already closed, aborted, or disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime"><span data-ttu-id="09329-132">メッセージの処理がタイムアウトする前に、サーバーが待機するを期間します。</span><span class="sxs-lookup"><span data-stu-id="09329-132">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="09329-133">指定されたサーバー待機時間を使用して、単一のトランザクションで処理するための関連するメッセージのグループ化したメッセージのセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="09329-133">Accepts a message session that allows grouping of related messages for processing in a single transaction using the specified server wait time.</span></span></summary>
        <returns><span data-ttu-id="09329-134">A<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</span><span class="sxs-lookup"><span data-stu-id="09329-134">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="09329-135">ServerWaitTime が正の TimeSpan 値である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-135">Thrown if serverWaitTime is not a positive TimeSpan value.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="09329-136">操作によって設定されたタイムアウト値を超過した場合にスロー<paramref name="serverWaitTime" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-136">Thrown if the operation exceeded the timeout value set by <paramref name="serverWaitTime" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="09329-137">クライアントが既に終了、中止、または破棄される場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-137">Thrown if the client is already closed, aborted, or disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (isExclusiveMode, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.Boolean,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="isExclusiveMode">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, isExclusiveMode As Boolean) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (sessionId, isExclusiveMode)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String,System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sessionId">To be added.</param>
        <param name="isExclusiveMode">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, lockToken As Guid) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * Guid -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * Guid -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (sessionId, lockToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String,System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="sessionId">To be added.</param>
        <param name="lockToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (sessionId, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId"><span data-ttu-id="09329-138">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="09329-138">The session identifier of the message session.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="09329-139">メッセージの処理がタイムアウトする前に、サーバーが待機するを期間します。</span><span class="sxs-lookup"><span data-stu-id="09329-139">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="09329-140">特定のセッション識別子と待機時間を使用して、単一のトランザクションで処理するための関連するメッセージのグループ化をできるメッセージ セッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="09329-140">Accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier and wait time.</span></span></summary>
        <returns><span data-ttu-id="09329-141">A<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</span><span class="sxs-lookup"><span data-stu-id="09329-141">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="09329-142">セッション Id が null、空、または空白文字である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-142">Thrown if sessionId is null, empty, or white spaces.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="09329-143">ServerWaitTime が正の TimeSpan 値である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-143">Thrown if serverWaitTime is not a positive TimeSpan value.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="09329-144">操作によって設定されたタイムアウト値を超過した場合にスロー<paramref name="serverWaitTime" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-144">Thrown if the operation exceeded the timeout value set by <paramref name="serverWaitTime" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="09329-145">クライアントが既に終了、中止、または破棄される場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-145">Thrown if the client is already closed, aborted, or disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (sessionId, isExclusiveMode, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String,System.Boolean,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">To be added.</param>
        <param name="isExclusiveMode">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, Guid lockToken, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.Guid lockToken, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSession(System.String,System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, lockToken As Guid, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * Guid * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * Guid * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.AcceptMessageSession (sessionId, lockToken, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSession(System.String,System.Guid,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">To be added.</param>
        <param name="lockToken">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="09329-146">非同期的に、指定されたサーバー待機時間を使用して、単一のトランザクションで処理するための関連するメッセージのグループ化したメッセージのセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="09329-146">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction using the specified server wait time.</span></span></summary>
        <returns><span data-ttu-id="09329-147">非同期の受信メッセージのセッションの操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-147">A task instance that represents the asynchronous accept message session operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (isExclusiveMode As Boolean) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync isExclusiveMode" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="isExclusiveMode">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync sessionId" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sessionId"><span data-ttu-id="09329-148">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="09329-148">The session identifier of the message session.</span></span></param>
        <summary><span data-ttu-id="09329-149">非同期的に、指定されたサーバー待機時間を使用して、単一のトランザクションで処理するための関連するメッセージのグループ化したメッセージのセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="09329-149">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction using the specified server wait time.</span></span></summary>
        <returns><span data-ttu-id="09329-150">非同期の受信メッセージのセッションの操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-150">A task instance that represents the asynchronous accept message session operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime"><span data-ttu-id="09329-151">メッセージの処理がタイムアウトする前に、サーバーが待機するを期間します。</span><span class="sxs-lookup"><span data-stu-id="09329-151">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="09329-152">非同期的に、指定されたサーバー待機時間を使用して、単一のトランザクションで処理するための関連するメッセージのグループ化したメッセージのセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="09329-152">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction using the specified server wait time.</span></span></summary>
        <returns><span data-ttu-id="09329-153">非同期の受信メッセージのセッションの操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-153">A task instance that represents the asynchronous accept message session operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (isExclusiveMode, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.Boolean,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="isExclusiveMode">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, isExclusiveMode As Boolean) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (sessionId, isExclusiveMode)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String,System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="sessionId">To be added.</param>
        <param name="isExclusiveMode">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, lockToken As Guid) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (sessionId, lockToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String,System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="sessionId">To be added.</param>
        <param name="lockToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (sessionId, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId"><span data-ttu-id="09329-154">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="09329-154">The session identifier of the message session.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="09329-155">メッセージの処理がタイムアウトする前に、サーバーが待機するを期間します。</span><span class="sxs-lookup"><span data-stu-id="09329-155">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="09329-156">非同期的に、指定されたサーバー待機時間を使用して、単一のトランザクションで処理するための関連するメッセージのグループ化したメッセージのセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="09329-156">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction using the specified server wait time.</span></span></summary>
        <returns><span data-ttu-id="09329-157">非同期の受信メッセージのセッションの操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-157">A task instance that represents the asynchronous accept message session operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (sessionId, isExclusiveMode, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String,System.Boolean,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">To be added.</param>
        <param name="isExclusiveMode">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, Guid lockToken, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.Guid lockToken, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AcceptMessageSessionAsync(System.String,System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, lockToken As Guid, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.AcceptMessageSessionAsync (sessionId, lockToken, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.AcceptMessageSessionAsync(System.String,System.Guid,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">To be added.</param>
        <param name="lockToken">To be added.</param>
        <param name="serverWaitTime">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRule">
      <MemberSignature Language="C#" Value="public void AddRule (Microsoft.ServiceBus.Messaging.RuleDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddRule(class Microsoft.ServiceBus.Messaging.RuleDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AddRule(Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddRule (description As RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.AddRule : Microsoft.ServiceBus.Messaging.RuleDescription -&gt; unit" Usage="subscriptionClient.AddRule description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="09329-158">規則の説明を追加するルールのメタデータを提供します。</span><span class="sxs-lookup"><span data-stu-id="09329-158">The rule description that provides metadata of the rule to add.</span></span></param>
        <summary><span data-ttu-id="09329-159">新しい規則を追加、<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />指定した規則の説明を使用します。</span><span class="sxs-lookup"><span data-stu-id="09329-159">Adds a new rule to the <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> using the specified rule description.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="09329-160">場合にスロー<paramref name="description" />が null です。</span><span class="sxs-lookup"><span data-stu-id="09329-160">Thrown if <paramref name="description" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="09329-161">場合にスロー<paramref name="description.Name.Name" />空であるか、適切な形式ではなく、null、白の領域がします。</span><span class="sxs-lookup"><span data-stu-id="09329-161">Thrown if <paramref name="description.Name.Name" /> is null, white space empty or not in the right format.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="09329-162">場合にスロー<paramref name="description.Name.Name" />の長さは 50 文字の制限を超えています。</span><span class="sxs-lookup"><span data-stu-id="09329-162">Thrown if <paramref name="description.Name.Name" /> length has exceeded the limit of 50 characters.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="09329-163">操作によって設定されたタイムアウト値を超過した場合にスロー<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-163">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="09329-164">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-164">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException"><span data-ttu-id="09329-165">既に追加されている 1 つとして同じ名前の別のルールを追加する試みが行われたときにスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-165">Thrown when an attempt is made to add another rule with same name as one that has already been added.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AddRule">
      <MemberSignature Language="C#" Value="public void AddRule (string ruleName, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddRule(string ruleName, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AddRule(System.String,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.AddRule : string * Microsoft.ServiceBus.Messaging.Filter -&gt; unit" Usage="subscriptionClient.AddRule (ruleName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="ruleName"><span data-ttu-id="09329-166">追加するルールの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-166">The name of the rule to add.</span></span></param>
        <param name="filter"><span data-ttu-id="09329-167">対象となるメッセージが一致するフィルター式です。</span><span class="sxs-lookup"><span data-stu-id="09329-167">The filter expression against which messages will be matched.</span></span></param>
        <summary><span data-ttu-id="09329-168">指定された名前およびフィルター式に現在のサブスクリプションにルールを追加します。</span><span class="sxs-lookup"><span data-stu-id="09329-168">Adds a rule to the current subscription with the specified name and filter expression.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="09329-169">場合にスロー<paramref name="filter" />が null です。</span><span class="sxs-lookup"><span data-stu-id="09329-169">Thrown if <paramref name="filter" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="09329-170">場合にスロー<paramref name="ruleName" />空であるか、適切な形式ではなく、null、白の領域がします。</span><span class="sxs-lookup"><span data-stu-id="09329-170">Thrown if <paramref name="ruleName" /> is null, white space empty or not in the right format.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="09329-171">場合にスロー<paramref name="ruleName" />の長さは 50 文字の制限を超えています。</span><span class="sxs-lookup"><span data-stu-id="09329-171">Thrown if <paramref name="ruleName" /> length has exceeded the limit of 50 characters.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="09329-172">操作を使用して設定されたタイムアウト値を超過した場合にスロー<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-172">Thrown if the operation exceeded the timeout value set via <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="09329-173">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-173">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException"><span data-ttu-id="09329-174">既に追加されている 1 つとして同じ名前の別のルールを追加する試みが行われたときにスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-174">Thrown when an attempt is made to add another rule with same name as one that has already been added.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (Microsoft.ServiceBus.Messaging.RuleDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddRuleAsync(class Microsoft.ServiceBus.Messaging.RuleDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AddRuleAsync(Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function AddRuleAsync (description As RuleDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.AddRuleAsync : Microsoft.ServiceBus.Messaging.RuleDescription -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AddRuleAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="09329-175">規則の説明を追加するルールのメタデータを提供します。</span><span class="sxs-lookup"><span data-stu-id="09329-175">The rule description that provides metadata of the rule to add.</span></span></param>
        <summary><span data-ttu-id="09329-176">非同期にする新しい規則を追加、<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />指定した規則の説明を使用します。</span><span class="sxs-lookup"><span data-stu-id="09329-176">Asynchronously adds a new rule to the <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> using the specified rule description.</span></span></summary>
        <returns><span data-ttu-id="09329-177">非同期の追加ルールの操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-177">A task instance that represents the asynchronous add rule operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (string ruleName, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddRuleAsync(string ruleName, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.AddRuleAsync(System.String,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.AddRuleAsync : string * Microsoft.ServiceBus.Messaging.Filter -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AddRuleAsync (ruleName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="ruleName"><span data-ttu-id="09329-178">追加するルールの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-178">The name of the rule to add.</span></span></param>
        <param name="filter"><span data-ttu-id="09329-179">対象となるメッセージが一致するフィルター式です。</span><span class="sxs-lookup"><span data-stu-id="09329-179">The filter expression against which messages will be matched.</span></span></param>
        <summary><span data-ttu-id="09329-180">非同期的に、規則を指定した名前とフィルター式を現在のサブスクリプションに追加します。</span><span class="sxs-lookup"><span data-stu-id="09329-180">Asynchronously adds a rule to the current subscription with the specified name and filter expression.</span></span></summary>
        <returns><span data-ttu-id="09329-181">非同期の追加ルールの操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-181">A task instance that represents the asynchronous add rule operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Complete">
      <MemberSignature Language="C#" Value="public void Complete (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Complete(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Complete(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Complete (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Complete : Guid -&gt; unit&#xA;override this.Complete : Guid -&gt; unit" Usage="subscriptionClient.Complete lockToken" />
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
        <param name="lockToken"><span data-ttu-id="09329-182">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-182">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="09329-183">メッセージの処理を完了します。</span><span class="sxs-lookup"><span data-stu-id="09329-183">Completes processing of a message.</span></span></summary>
        <remarks> <span data-ttu-id="09329-184">このメソッドは、メッセージの配信の保証の Service Bus とクライアント間のハンドシェイクとして使用されます。</span><span class="sxs-lookup"><span data-stu-id="09329-184">This method is used as a handshake between the client and Service Bus for a guaranteed delivery of the message.</span></span> <span data-ttu-id="09329-185">このメソッドを呼び出す前に、クライアントが失敗した場合、メッセージがキューに保持されます。</span><span class="sxs-lookup"><span data-stu-id="09329-185">If the client failed before calling this method, the message will be kept in the queue.</span></span></remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="09329-186">操作によって設定されたタイムアウト値を超過した場合にスロー<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-186">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="09329-187">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-187">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="09329-188">メッセージがによって表される場合にスロー<paramref name="lockToken" />メッセージのロックを失いました。</span><span class="sxs-lookup"><span data-stu-id="09329-188">Thrown if the message represented by <paramref name="lockToken" /> has lost the message lock.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CompleteAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.CompleteAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="09329-189">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-189">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="09329-190">非同期的にメッセージの処理を完了します。</span><span class="sxs-lookup"><span data-stu-id="09329-190">Asynchronously completes processing of a message.</span></span></summary>
        <returns><span data-ttu-id="09329-191">非同期の完了操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-191">A task instance that represents the asynchronous complete operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatch">
      <MemberSignature Language="C#" Value="public void CompleteBatch (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CompleteBatch(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CompleteBatch(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CompleteBatch (lockTokens As IEnumerable(Of Guid))" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatch : seq&lt;Guid&gt; -&gt; unit&#xA;override this.CompleteBatch : seq&lt;Guid&gt; -&gt; unit" Usage="subscriptionClient.CompleteBatch lockTokens" />
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
        <param name="lockTokens"><span data-ttu-id="09329-192">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-192">The lock tokens bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="09329-193">バッチの処理を完了します。</span><span class="sxs-lookup"><span data-stu-id="09329-193">Completes processing of a batch.</span></span></summary>
        <remarks> <span data-ttu-id="09329-194">このメソッドは、メッセージの配信の保証の Service Bus とクライアント間のハンドシェイクとして使用されます。</span><span class="sxs-lookup"><span data-stu-id="09329-194">This method is used as a handshake between the client and Service Bus for a guaranteed delivery of the message.</span></span> <span data-ttu-id="09329-195">このメソッドを呼び出す前に、クライアントが失敗した場合、メッセージがキューに保持されます。</span><span class="sxs-lookup"><span data-stu-id="09329-195">If the client failed before calling this method, the message will be kept in the queue.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteBatchAsync (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CompleteBatchAsync(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteBatchAsync (lockTokens As IEnumerable(Of Guid)) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.CompleteBatchAsync lockTokens" />
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
        <param name="lockTokens"><span data-ttu-id="09329-196">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-196">The lock tokens bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="09329-197">非同期的に、バッチの処理を完了します。</span><span class="sxs-lookup"><span data-stu-id="09329-197">Asynchronously completes processing of a batch.</span></span></summary>
        <returns><span data-ttu-id="09329-198">非同期の完全なバッチ操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-198">A task instance that represents the asynchronous complete batch operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (topicPath As String, name As String) As SubscriptionClient" />
      <MemberSignature Language="F#" Value="static member Create : string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="09329-199">トピックの完全なパス名。</span><span class="sxs-lookup"><span data-stu-id="09329-199">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="09329-200">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-200">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="09329-201">新しいコピーを作成<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />名とトピックのパスを指定しています。</span><span class="sxs-lookup"><span data-stu-id="09329-201">Creates a new copy of <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> with specified name and topic path.</span></span></summary>
        <returns><span data-ttu-id="09329-202">新しいコピー<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-202">A new copy of <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode mode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (topicPath As String, name As String, mode As ReceiveMode) As SubscriptionClient" />
      <MemberSignature Language="F#" Value="static member Create : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (topicPath, name, mode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="09329-203">トピックの完全なパス名。</span><span class="sxs-lookup"><span data-stu-id="09329-203">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="09329-204">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-204">The name of the subscription.</span></span></param>
        <param name="mode"><span data-ttu-id="09329-205">メッセージは受信モードです。</span><span class="sxs-lookup"><span data-stu-id="09329-205">The message receive mode.</span></span></param>
        <summary><span data-ttu-id="09329-206">新しいコピーを作成<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />指定された名前、トピック パスおよびモードを使用します。</span><span class="sxs-lookup"><span data-stu-id="09329-206">Creates a new copy of <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> with specified name, topic path and mode.</span></span></summary>
        <returns><span data-ttu-id="09329-207">新しいコピー<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-207">A new copy of <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (Uri endpointAddress, string topicPath, string name, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(class System.Uri endpointAddress, string topicPath, string name, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.Uri,System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (endpointAddress, topicPath, name, authContext, clientAssertionCertificate, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="09329-208">Sercvice バスの完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="09329-208">Fully qualified domain name for Sercvice Bus.</span></span> <span data-ttu-id="09329-209">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="09329-209">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="topicPath"><span data-ttu-id="09329-210">トピックの完全なパス名。</span><span class="sxs-lookup"><span data-stu-id="09329-210">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="09329-211">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-211">The name of the subscription.</span></span></param>
        <param name="authContext"><span data-ttu-id="09329-212">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="09329-212">AuthenticationContext for AAD.</span></span></param>
        <param name="clientAssertionCertificate"><span data-ttu-id="09329-213">アサーションの証明書のクライアント資格情報でします。</span><span class="sxs-lookup"><span data-stu-id="09329-213">The client assertion certificate credential.</span></span></param>
        <param name="mode"><span data-ttu-id="09329-214">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="09329-214">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="09329-215"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="09329-215"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="09329-216">メッセージング トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="09329-216">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="09329-217">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> Azure Active Directory 認証コンテキストを使用しています。</span><span class="sxs-lookup"><span data-stu-id="09329-217">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="09329-218">作成された <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />。</span><span class="sxs-lookup"><span data-stu-id="09329-218">The created <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (Uri endpointAddress, string topicPath, string name, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(class System.Uri endpointAddress, string topicPath, string name, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.Uri,System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (endpointAddress, topicPath, name, authContext, clientCredential, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="09329-219">Service Bus の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="09329-219">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="09329-220">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="09329-220">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="topicPath"><span data-ttu-id="09329-221">トピックの完全なパス名。</span><span class="sxs-lookup"><span data-stu-id="09329-221">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="09329-222">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-222">The name of the subscription.</span></span></param>
        <param name="authContext"><span data-ttu-id="09329-223">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="09329-223">AuthenticationContext for AAD.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="09329-224">アプリの資格情報。</span><span class="sxs-lookup"><span data-stu-id="09329-224">The app credential.</span></span></param>
        <param name="mode"><span data-ttu-id="09329-225">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="09329-225">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="09329-226"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="09329-226"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="09329-227">メッセージング トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="09329-227">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="09329-228">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> Azure Active Directory 認証コンテキストを使用しています。</span><span class="sxs-lookup"><span data-stu-id="09329-228">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="09329-229">作成された <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />。</span><span class="sxs-lookup"><span data-stu-id="09329-229">The created <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (Uri endpointAddress, string topicPath, string name, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(class System.Uri endpointAddress, string topicPath, string name, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.Uri,System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (endpointAddress, topicPath, name, authContext, clientId, userPasswordCredential, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userPasswordCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="09329-230">Service Bus の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="09329-230">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="09329-231">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="09329-231">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="topicPath"><span data-ttu-id="09329-232">トピックの完全なパス名。</span><span class="sxs-lookup"><span data-stu-id="09329-232">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="09329-233">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-233">The name of the subscription.</span></span></param>
        <param name="authContext"><span data-ttu-id="09329-234">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="09329-234">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="09329-235">AAD の ClientId です。</span><span class="sxs-lookup"><span data-stu-id="09329-235">ClientId for AAD.</span></span></param>
        <param name="userPasswordCredential"><span data-ttu-id="09329-236">ユーザーのパスワード資格情報です。</span><span class="sxs-lookup"><span data-stu-id="09329-236">The user password credential.</span></span></param>
        <param name="mode"><span data-ttu-id="09329-237">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="09329-237">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="09329-238"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="09329-238"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="09329-239">メッセージング トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="09329-239">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="09329-240">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> Azure Active Directory 認証コンテキストを使用しています。</span><span class="sxs-lookup"><span data-stu-id="09329-240">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="09329-241">作成された <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />。</span><span class="sxs-lookup"><span data-stu-id="09329-241">The created <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient Create (Uri endpointAddress, string topicPath, string name, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient Create(class System.Uri endpointAddress, string topicPath, string name, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Create(System.Uri,System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Create (endpointAddress, topicPath, name, authContext, clientId, redirectUri, platformParameters, userIdentifier, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="platformParameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userIdentifier" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="09329-242">Service Bus の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="09329-242">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="09329-243">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="09329-243">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="topicPath"><span data-ttu-id="09329-244">トピックの完全なパス名。</span><span class="sxs-lookup"><span data-stu-id="09329-244">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="09329-245">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-245">The name of the subscription.</span></span></param>
        <param name="authContext"><span data-ttu-id="09329-246">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="09329-246">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="09329-247">AAD の ClientId です。</span><span class="sxs-lookup"><span data-stu-id="09329-247">ClientId for AAD.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="09329-248">クライアント アプリで redrectUri です。</span><span class="sxs-lookup"><span data-stu-id="09329-248">The redrectUri on Client App.</span></span></param>
        <param name="platformParameters"><span data-ttu-id="09329-249">プラットフォームのパラメーター</span><span class="sxs-lookup"><span data-stu-id="09329-249">Platform parameters</span></span></param>
        <param name="userIdentifier"><span data-ttu-id="09329-250">ユーザーの識別子</span><span class="sxs-lookup"><span data-stu-id="09329-250">User Identifier</span></span></param>
        <param name="mode"><span data-ttu-id="09329-251">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="09329-251">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="09329-252"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="09329-252"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="09329-253">メッセージング トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="09329-253">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="09329-254">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> Azure Active Directory 認証コンテキストを使用しています。</span><span class="sxs-lookup"><span data-stu-id="09329-254">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="09329-255">作成された <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />。</span><span class="sxs-lookup"><span data-stu-id="09329-255">The created <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient CreateFromConnectionString (string connectionString, string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateFromConnectionString(string connectionString, string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateFromConnectionString(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, topicPath As String, name As String) As SubscriptionClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateFromConnectionString (connectionString, topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="09329-256">接続文字列。</span><span class="sxs-lookup"><span data-stu-id="09329-256">The connection string.</span></span></param>
        <param name="topicPath"><span data-ttu-id="09329-257">トピックの完全なパス名。</span><span class="sxs-lookup"><span data-stu-id="09329-257">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="09329-258">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-258">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="09329-259">新しいコピーを作成<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />指定されたトピック パスと名前を接続文字列から。</span><span class="sxs-lookup"><span data-stu-id="09329-259">Creates a new copy of <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> from a connection string with specified topic path and name.</span></span></summary>
        <returns><span data-ttu-id="09329-260">新しいコピー<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-260">A new copy of <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient CreateFromConnectionString (string connectionString, string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode mode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateFromConnectionString(string connectionString, string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateFromConnectionString(System.String,System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, topicPath As String, name As String, mode As ReceiveMode) As SubscriptionClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateFromConnectionString (connectionString, topicPath, name, mode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="09329-261">接続文字列。</span><span class="sxs-lookup"><span data-stu-id="09329-261">The connection string.</span></span></param>
        <param name="topicPath"><span data-ttu-id="09329-262">トピックの完全なパス名。</span><span class="sxs-lookup"><span data-stu-id="09329-262">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="09329-263">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-263">The name of the subscription.</span></span></param>
        <param name="mode"><span data-ttu-id="09329-264">メッセージは受信モードです。</span><span class="sxs-lookup"><span data-stu-id="09329-264">The message receive mode.</span></span></param>
        <summary><span data-ttu-id="09329-265">新しいコピーを作成<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />指定されたトピック パス、名前およびモードで接続文字列から。</span><span class="sxs-lookup"><span data-stu-id="09329-265">Creates a new copy of <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> from a connection string with specified topic path, name and mode.</span></span></summary>
        <returns><span data-ttu-id="09329-266">新しいコピー<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-266">A new copy of <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateWithManagedServiceIdentity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.SubscriptionClient CreateWithManagedServiceIdentity (Uri endpointAddress, string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateWithManagedServiceIdentity(class System.Uri endpointAddress, string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateWithManagedServiceIdentity(System.Uri,System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateWithManagedServiceIdentity : Uri * string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.CreateWithManagedServiceIdentity (endpointAddress, topicPath, name, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="09329-267">Service Bus の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="09329-267">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="09329-268">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="09329-268">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="topicPath"><span data-ttu-id="09329-269">トピックの完全なパス名。</span><span class="sxs-lookup"><span data-stu-id="09329-269">The full pathname of the topic.</span></span></param>
        <param name="name"><span data-ttu-id="09329-270">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-270">The name of the subscription.</span></span></param>
        <param name="mode"><span data-ttu-id="09329-271">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="09329-271">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="09329-272"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="09329-272"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="09329-273">メッセージング トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="09329-273">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="09329-274">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> Azure 管理サービス Id の認証を使用しています。</span><span class="sxs-lookup"><span data-stu-id="09329-274">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" /> by using Azure Managed Service Identity authentication.</span></span></summary>
        <returns><span data-ttu-id="09329-275">作成された <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />。</span><span class="sxs-lookup"><span data-stu-id="09329-275">The created <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetter(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid -&gt; unit&#xA;override this.DeadLetter : Guid -&gt; unit" Usage="subscriptionClient.DeadLetter lockToken" />
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
        <param name="lockToken"><span data-ttu-id="09329-276">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-276">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="09329-277">配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="09329-277">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="09329-278">操作によって設定されたタイムアウト値を超過した場合にスロー<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-278">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="09329-279">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-279">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="09329-280">メッセージがによって表される場合にスロー<paramref name="lockToken" />メッセージのロックを失いました。</span><span class="sxs-lookup"><span data-stu-id="09329-280">Thrown if the message represented by <paramref name="lockToken" /> has lost the message lock.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetter(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="subscriptionClient.DeadLetter (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="09329-281">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-281">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="09329-282">変更するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="09329-282">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="09329-283">配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="09329-283">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetter(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * string * string -&gt; unit&#xA;override this.DeadLetter : Guid * string * string -&gt; unit" Usage="subscriptionClient.DeadLetter (lockToken, deadLetterReason, deadLetterErrorDescription)" />
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
        <param name="lockToken"><span data-ttu-id="09329-284">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-284">The lock token bound to the locked message instance.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="09329-285">メッセージの配信不能の理由です。</span><span class="sxs-lookup"><span data-stu-id="09329-285">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="09329-286">メッセージの配信不能のエラーの説明。</span><span class="sxs-lookup"><span data-stu-id="09329-286">The error description for deadlettering the message.</span></span></param>
        <summary><span data-ttu-id="09329-287">配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="09329-287">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="09329-288">操作によって設定されたタイムアウト値を超過した場合にスロー<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-288">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="09329-289">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-289">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="09329-290">メッセージがによって表される場合にスロー<paramref name="lockToken" />メッセージのロックを失いました。</span><span class="sxs-lookup"><span data-stu-id="09329-290">Thrown if the message represented by <paramref name="lockToken" /> has lost the message lock.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetterAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="09329-291">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-291">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="09329-292">非同期的に配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="09329-292">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="09329-293">配信不能の非同期操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-293">A task instance that represents the asynchronous deadletter operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetterAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="09329-294">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-294">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="09329-295">変更するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="09329-295">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="09329-296">非同期的に配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="09329-296">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="09329-297">配信不能の非同期操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-297">A task instance that represents the asynchronous deadletter operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeadLetterAsync(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
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
        <param name="lockToken"><span data-ttu-id="09329-298">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-298">The lock token bound to the locked message instance.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="09329-299">メッセージの配信不能の理由です。</span><span class="sxs-lookup"><span data-stu-id="09329-299">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="09329-300">メッセージの配信不能のエラーの説明。</span><span class="sxs-lookup"><span data-stu-id="09329-300">The error description for deadlettering the message.</span></span></param>
        <summary><span data-ttu-id="09329-301">非同期的に配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="09329-301">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="09329-302">配信不能の非同期操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-302">A task instance that represents the asynchronous deadletter operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Defer(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid -&gt; unit&#xA;override this.Defer : Guid -&gt; unit" Usage="subscriptionClient.Defer lockToken" />
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
        <param name="lockToken"><span data-ttu-id="09329-303">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-303">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="09329-304">メッセージの処理を中断します。</span><span class="sxs-lookup"><span data-stu-id="09329-304">Suspends the processing of a message.</span></span></summary>
        <remarks><span data-ttu-id="09329-305">を保留する前にする必要があります確保しておいたメッセージの受信確認を後で取得します。</span><span class="sxs-lookup"><span data-stu-id="09329-305">Before deferring, you should set aside the message receipt for later retrieval.</span></span> </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="09329-306">操作によって設定されたタイムアウト値を超過した場合にスロー<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-306">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="09329-307">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-307">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="09329-308">メッセージがによって表される場合にスロー<paramref name="lockToken" />メッセージのロックを失いました。</span><span class="sxs-lookup"><span data-stu-id="09329-308">Thrown if the message represented by <paramref name="lockToken" /> has lost the message lock.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Defer(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="subscriptionClient.Defer (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="09329-309">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-309">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="09329-310">変更するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="09329-310">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="09329-311">メッセージの処理を中断します。</span><span class="sxs-lookup"><span data-stu-id="09329-311">Suspends the processing of a message.</span></span></summary>
        <remarks><span data-ttu-id="09329-312">を保留する前にする必要があります確保しておいたメッセージの受信確認を後で取得します。</span><span class="sxs-lookup"><span data-stu-id="09329-312">Before deferring, you should set aside the message receipt for later retrieval.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeferAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeferAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="09329-313">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-313">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="09329-314">非同期的にメッセージの処理を中断します。</span><span class="sxs-lookup"><span data-stu-id="09329-314">Asynchronously suspends the processing of a message.</span></span></summary>
        <returns><span data-ttu-id="09329-315">非同期を表すタスク インスタンスは、操作を延期します。</span><span class="sxs-lookup"><span data-stu-id="09329-315">A task instance that represents the asynchronous defer operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.DeferAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeferAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="09329-316">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="09329-316">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="09329-317">変更するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="09329-317">The properties to modify.</span></span></param>
        <summary><span data-ttu-id="09329-318">非同期的にメッセージの処理を中断します。</span><span class="sxs-lookup"><span data-stu-id="09329-318">Asynchronously suspends the processing of a message.</span></span></summary>
        <returns><span data-ttu-id="09329-319">非同期を表すタスク インスタンスは、操作を延期します。</span><span class="sxs-lookup"><span data-stu-id="09329-319">A task instance that represents the asynchronous defer operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatDeadLetterPath">
      <MemberSignature Language="C#" Value="public static string FormatDeadLetterPath (string topicPath, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatDeadLetterPath(string topicPath, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.FormatDeadLetterPath(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatDeadLetterPath (topicPath As String, subscriptionName As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatDeadLetterPath : string * string -&gt; string" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.FormatDeadLetterPath (topicPath, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="09329-320">トピックの完全なパス名。</span><span class="sxs-lookup"><span data-stu-id="09329-320">The full pathname of the topic.</span></span></param>
        <param name="subscriptionName"><span data-ttu-id="09329-321">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-321">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="09329-322">指定したトピックのパスとサブスクリプションの名前を使用して、形式名の配信不能のパスを構築します。</span><span class="sxs-lookup"><span data-stu-id="09329-322">Builds a format name deadletter path using the specified topic path and subscription name.</span></span></summary>
        <returns><span data-ttu-id="09329-323"><see cref="T:System.String" />から指定したトピックのパスとサブスクリプションの名前を使用して形式名の配信不能パスのビルドが発生しました。</span><span class="sxs-lookup"><span data-stu-id="09329-323">The <see cref="T:System.String" /> resulted from building the format name deadletter path using the specified topic path and subscription name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatSubscriptionPath">
      <MemberSignature Language="C#" Value="public static string FormatSubscriptionPath (string topicPath, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatSubscriptionPath(string topicPath, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.FormatSubscriptionPath(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatSubscriptionPath (topicPath As String, subscriptionName As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatSubscriptionPath : string * string -&gt; string" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.FormatSubscriptionPath (topicPath, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="09329-324">トピックの完全なパス名。</span><span class="sxs-lookup"><span data-stu-id="09329-324">The full pathname of the topic.</span></span></param>
        <param name="subscriptionName"><span data-ttu-id="09329-325">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-325">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="09329-326">指定したトピックのパスとサブスクリプションの名前を使用して、形式名のサブスクリプションのパスを構築します。</span><span class="sxs-lookup"><span data-stu-id="09329-326">Builds a format name subscription path using the specified topic path and subscription name.</span></span></summary>
        <returns><span data-ttu-id="09329-327"><see cref="T:System.String" />から指定したトピックのパスとサブスクリプションの名前を使用して、形式名サブスクリプション パスのビルドが発生しました。</span><span class="sxs-lookup"><span data-stu-id="09329-327">The <see cref="T:System.String" /> resulted from building the format name subscription path using the specified topic path and subscription name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.GetMessageSessions" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessions () As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessions : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.GetMessageSessions : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.GetMessageSessions " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.GetMessageSessions</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="09329-328">1 つのトランザクションで処理するための関連するメッセージのグループ化したメッセージのセッションを取得します。</span><span class="sxs-lookup"><span data-stu-id="09329-328">Gets a message session that allows grouping of related messages for processing in a single transaction.</span></span></summary>
        <returns><span data-ttu-id="09329-329">グループ化したメッセージのセッションには、1 つのトランザクションで処理するためのメッセージが関連します。</span><span class="sxs-lookup"><span data-stu-id="09329-329">A message session that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions (DateTime lastUpdatedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions(valuetype System.DateTime lastUpdatedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.GetMessageSessions(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessions (lastUpdatedTime As DateTime) As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessions : DateTime -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.GetMessageSessions : DateTime -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.GetMessageSessions lastUpdatedTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.GetMessageSessions(System.DateTime)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastUpdatedTime" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="lastUpdatedTime"><span data-ttu-id="09329-330">セッションの最終更新時刻。</span><span class="sxs-lookup"><span data-stu-id="09329-330">The time the session was last updated.</span></span></param>
        <summary><span data-ttu-id="09329-331">すべてのメッセージのセッションがセッション状態が以降更新された取得<paramref name="lastUpdatedTime" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-331">Retrieves all message sessions whose session state was updated since <paramref name="lastUpdatedTime" />.</span></span></summary>
        <returns><span data-ttu-id="09329-332">グループ化したメッセージのセッションには、1 つのトランザクションで処理するためのメッセージが関連します。</span><span class="sxs-lookup"><span data-stu-id="09329-332">A message session that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.GetMessageSessionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessionsAsync () As Task(Of IEnumerable(Of MessageSession))" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;&#xA;override this.GetMessageSessionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;" Usage="subscriptionClient.GetMessageSessionsAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.GetMessageSessionsAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="09329-333">1 つのトランザクションで処理するための関連するメッセージのグループ化したメッセージのセッションを非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="09329-333">Asynchronously gets a message session that allows grouping of related messages for processing in a single transaction.</span></span></summary>
        <returns><span data-ttu-id="09329-334">メッセージのセッションの非同期取得操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-334">A task instance that represents the asynchronous get message sessions operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync (DateTime lastUpdatedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync(valuetype System.DateTime lastUpdatedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.GetMessageSessionsAsync(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessionsAsync (lastUpdatedTime As DateTime) As Task(Of IEnumerable(Of MessageSession))" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessionsAsync : DateTime -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;&#xA;override this.GetMessageSessionsAsync : DateTime -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;" Usage="subscriptionClient.GetMessageSessionsAsync lastUpdatedTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.GetMessageSessionsAsync(System.DateTime)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastUpdatedTime" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="lastUpdatedTime"><span data-ttu-id="09329-335">セッションの最終更新時刻。</span><span class="sxs-lookup"><span data-stu-id="09329-335">The time the session was last updated.</span></span></param>
        <summary><span data-ttu-id="09329-336">1 つのトランザクションで処理するための関連するメッセージのグループ化したメッセージのセッションを非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="09329-336">Asynchronously gets a message session that allows grouping of related messages for processing in a single transaction.</span></span></summary>
        <returns><span data-ttu-id="09329-337">メッセージのセッションの非同期取得操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-337">A task instance that represents the asynchronous get message sessions operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessagingFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.MessagingFactory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessagingFactory As MessagingFactory" />
      <MemberSignature Language="F#" Value="member this.MessagingFactory : Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.MessagingFactory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="09329-338">このサブスクリプション クライアントを作成するために使用するメッセージング ファクトリを取得します。</span><span class="sxs-lookup"><span data-stu-id="09329-338">Gets the messaging factory used to create this subscription client.</span></span></summary>
        <value><span data-ttu-id="09329-339">このサブスクリプション クライアントを作成するために使用するメッセージング ファクトリ。</span><span class="sxs-lookup"><span data-stu-id="09329-339">The messaging factory used to create this subscription client.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ReceiveMode Mode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.ReceiveMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.Mode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Mode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.Messaging.ReceiveMode" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ReceiveMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="09329-340">メッセージを取得、受信したメッセージを処理するときに、受信モード。</span><span class="sxs-lookup"><span data-stu-id="09329-340">Gets the message receive mode when processing the received message.</span></span></summary>
        <value><span data-ttu-id="09329-341">メッセージ<see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />受信したメッセージを処理するときにします。</span><span class="sxs-lookup"><span data-stu-id="09329-341">The message <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" /> when processing the received message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="09329-342">サブスクリプションの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="09329-342">Gets the name of the subscription.</span></span></summary>
        <value><span data-ttu-id="09329-343">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-343">The name of the subscription.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="subscriptionClient.OnAbort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="09329-344">中断アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="09329-344">Executes the abort action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAcceptMessageSession (string sessionId, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, bool isExclusiveMode, Nullable&lt;Guid&gt; lockToken, TimeSpan serverWaitTime, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAcceptMessageSession(string sessionId, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, bool isExclusiveMode, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; lockToken, valuetype System.TimeSpan serverWaitTime, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginAcceptMessageSession(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Boolean,System.Nullable{System.Guid},System.TimeSpan,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAcceptMessageSession : string * Microsoft.ServiceBus.Messaging.ReceiveMode * bool * Nullable&lt;Guid&gt; * TimeSpan * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginAcceptMessageSession (sessionId, receiveMode, isExclusiveMode, lockToken, serverWaitTime, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="lockToken" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="sessionId"><span data-ttu-id="09329-345">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="09329-345">The session identifier of the message session.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="09329-346">受信メッセージを処理するときに、受信モードです。</span><span class="sxs-lookup"><span data-stu-id="09329-346">The receive mode when processing with the receive messages.</span></span></param>
        <param name="isExclusiveMode"></param>
        <param name="lockToken"></param>
        <param name="serverWaitTime"><span data-ttu-id="09329-347">メッセージの処理がタイムアウトする前に、サーバーが待機するを期間します。</span><span class="sxs-lookup"><span data-stu-id="09329-347">The time span the server waits for processing messages before it times out</span></span></param>
        <param name="timeout"><span data-ttu-id="09329-348">メッセージの処理がタイムアウトする前に、サーバーが待機するを期間します。</span><span class="sxs-lookup"><span data-stu-id="09329-348">The time span the server waits for processing messages before it times out.</span></span></param>
        <param name="callback"><span data-ttu-id="09329-349">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="09329-349">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="09329-350">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="09329-350">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="09329-351">BeginAcceptMessageSession 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="09329-351">Executes upon calling the BeginAcceptMessageSession operation.</span></span></summary>
        <returns><span data-ttu-id="09329-352"><see cref="T:System.IAsyncResult" />をメッセージのセッションを受け入れる非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="09329-352">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to accept a message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAddRule">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAddRule (Microsoft.ServiceBus.Messaging.RuleDescription description, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAddRule(class Microsoft.ServiceBus.Messaging.RuleDescription description, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginAddRule(Microsoft.ServiceBus.Messaging.RuleDescription,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginAddRule (description As RuleDescription, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAddRule : Microsoft.ServiceBus.Messaging.RuleDescription * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginAddRule (description, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="09329-353">規則の説明を追加するルールのメタデータを提供します。</span><span class="sxs-lookup"><span data-stu-id="09329-353">The rule description that provides metadata of the rule to add.</span></span></param>
        <param name="timeout"><span data-ttu-id="09329-354">この操作は、タイムアウトになるまで待機する時間間隔です。</span><span class="sxs-lookup"><span data-stu-id="09329-354">The time span this operation waits before it times out.</span></span></param>
        <param name="callback"><span data-ttu-id="09329-355">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="09329-355">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="09329-356">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="09329-356">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="09329-357">BeginAddRule 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="09329-357">Executes upon calling the BeginAddRule operation.</span></span></summary>
        <returns><span data-ttu-id="09329-358"><see cref="T:System.IAsyncResult" />サブスクリプションに新しいルールを追加する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="09329-358">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to add a new rule to the subscription.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginClose (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="09329-359">操作の前に、待機時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="09329-359">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="09329-360">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="09329-360">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="09329-361">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="09329-361">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="09329-362">このオブジェクトは、BeginClose に渡されるデリゲート、操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="09329-362">This object is passed to the BeginClose delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="09329-363">開始の閉じる操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="09329-363">Executes the begin close action.</span></span></summary>
        <returns><span data-ttu-id="09329-364"><see cref="T:System.IAsyncResult" />非同期 BeginClose を参照します。</span><span class="sxs-lookup"><span data-stu-id="09329-364">An <see cref="T:System.IAsyncResult" />that references the asynchronous BeginClose.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateReceiver (Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateReceiver(valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginCreateReceiver(Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateReceiver : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginCreateReceiver (receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="receiveMode"><span data-ttu-id="09329-365">メッセージ<see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-365">The message <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="09329-366">操作の前に、待機時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="09329-366">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="09329-367">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="09329-367">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="09329-368">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="09329-368">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="09329-369">このオブジェクトは、操作の完了時に <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.EndCreateReceiver(System.IAsyncResult)" /> デリゲートに渡されます。</span><span class="sxs-lookup"><span data-stu-id="09329-369">This object is passed to the <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.EndCreateReceiver(System.IAsyncResult)" /> delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="09329-370">実行の開始操作の受信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="09329-370">Executes the begin create receiver action.</span></span></summary>
        <returns><span data-ttu-id="09329-371"><see cref="T:System.IAsyncResult" />親の非同期メソッドを参照します。</span><span class="sxs-lookup"><span data-stu-id="09329-371">An <see cref="T:System.IAsyncResult" /> that references the asynchronous parent method.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateReceiver (string subQueuePath, string subQueueName, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateReceiver(string subQueuePath, string subQueueName, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginCreateReceiver(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginCreateReceiver (subQueuePath, subQueueName, receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subQueuePath" Type="System.String" />
        <Parameter Name="subQueueName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="subQueuePath"><span data-ttu-id="09329-372">サブキューのパス。</span><span class="sxs-lookup"><span data-stu-id="09329-372">The path of the subqueue.</span></span></param>
        <param name="subQueueName"><span data-ttu-id="09329-373">サブキューの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-373">The name of the subqueue.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="09329-374">メッセージ<see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-374">The message <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />.</span></span></param>
        <param name="timeout"><span data-ttu-id="09329-375">操作の前に、待機時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="09329-375">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="09329-376">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="09329-376">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="09329-377">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="09329-377">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="09329-378">このオブジェクトは、操作の完了時に <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.EndCreateReceiver(System.IAsyncResult)" /> デリゲートに渡されます。</span><span class="sxs-lookup"><span data-stu-id="09329-378">This object is passed to the <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.EndCreateReceiver(System.IAsyncResult)" /> delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="09329-379">実行の開始操作の受信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="09329-379">Executes the begin create receiver action.</span></span></summary>
        <returns><span data-ttu-id="09329-380"><see cref="T:System.IAsyncResult" />非同期親非同期メソッドを参照します。</span><span class="sxs-lookup"><span data-stu-id="09329-380">An <see cref="T:System.IAsyncResult" /> that references the asynchronous parent async method.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetMessageSessions">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetMessageSessions (DateTime lastUpdatedTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetMessageSessions(valuetype System.DateTime lastUpdatedTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginGetMessageSessions(System.DateTime,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetMessageSessions (lastUpdatedTime As DateTime, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetMessageSessions : DateTime * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginGetMessageSessions (lastUpdatedTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastUpdatedTime" Type="System.DateTime" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="lastUpdatedTime"><span data-ttu-id="09329-381">セッションの最終更新時刻。</span><span class="sxs-lookup"><span data-stu-id="09329-381">The time the session was last updated.</span></span></param>
        <param name="callback"><span data-ttu-id="09329-382">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="09329-382">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="09329-383">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="09329-383">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="09329-384">BeginGetMessageSessions 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="09329-384">Executes upon calling the BeginGetMessageSessions operation.</span></span></summary>
        <returns><span data-ttu-id="09329-385"><see cref="T:System.IAsyncResult" />サブスクリプションに新しいルールを追加する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="09329-385">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to add a new rule to the subscription.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetRules">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetRules (int top, int skip, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetRules(int32 top, int32 skip, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginGetRules(System.Int32,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetRules (top As Integer, skip As Integer, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetRules : int * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginGetRules (top, skip, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="skip" Type="System.Int32" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="top">To be added.</param>
        <param name="skip">To be added.</param>
        <param name="timeout">To be added.</param>
        <param name="callback">To be added.</param>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRemoveRule">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginRemoveRule (string ruleName, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginRemoveRule(string ruleName, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginRemoveRule (ruleName As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginRemoveRule : string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginRemoveRule (ruleName, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="ruleName"><span data-ttu-id="09329-386">削除する規則の名前。</span><span class="sxs-lookup"><span data-stu-id="09329-386">The name of the rule to remove.</span></span></param>
        <param name="timeout"><span data-ttu-id="09329-387">操作の前に、待機時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="09329-387">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="09329-388">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="09329-388">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="09329-389">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="09329-389">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="09329-390">このオブジェクトは、操作の完了時に <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" /> デリゲートに渡されます。</span><span class="sxs-lookup"><span data-stu-id="09329-390">This object is passed to the <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" /> delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="09329-391">削除が開始、<see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" />から、<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />実行時のクライアント プロトコルを使用します。</span><span class="sxs-lookup"><span data-stu-id="09329-391">Begins removing a <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> from a <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> through the run-time client protocol.</span></span></summary>
        <returns><span data-ttu-id="09329-392"><see cref="T:System.IAsyncResult" />非同期の参照を<see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-392">An <see cref="T:System.IAsyncResult" /> that references the asynchronous <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRemoveRulesByTag">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginRemoveRulesByTag (string tag, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginRemoveRulesByTag(string tag, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRulesByTag(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginRemoveRulesByTag (tag As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginRemoveRulesByTag : string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="subscriptionClient.OnBeginRemoveRulesByTag (tag, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tag" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="tag"><span data-ttu-id="09329-393">使用するタグです。</span><span class="sxs-lookup"><span data-stu-id="09329-393">The tag to be used.</span></span></param>
        <param name="timeout"><span data-ttu-id="09329-394">操作の前に、待機時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="09329-394">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="09329-395">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="09329-395">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="09329-396">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="09329-396">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="09329-397">このオブジェクトは、操作の完了時に <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" /> デリゲートに渡されます。</span><span class="sxs-lookup"><span data-stu-id="09329-397">This object is passed to the <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" /> delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="09329-398">削除が開始、<see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" />から、<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />タグを使用して実行時のクライアント プロトコルを使用します。</span><span class="sxs-lookup"><span data-stu-id="09329-398">Begins removing a <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> from a <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> through the run-time client protocol using a tag.</span></span></summary>
        <returns><span data-ttu-id="09329-399"><see cref="T:System.IAsyncResult" />サブスクリプションに新しいルールを追加する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="09329-399">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to add a new rule to the subscription.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="subscriptionClient.OnClose timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="09329-400">操作の前に、待機時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="09329-400">The wait time before the operation times out.</span></span></param>
        <summary><span data-ttu-id="09329-401">閉じる操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="09329-401">Executes the close action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndAcceptMessageSession(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndAcceptMessageSession (result As IAsyncResult) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member OnEndAcceptMessageSession : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="subscriptionClient.OnEndAcceptMessageSession result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="09329-402"><see cref="T:System.IAsyncResult" />を表す非同期の受信メッセージのセッションの操作の状態。</span><span class="sxs-lookup"><span data-stu-id="09329-402">An <see cref="T:System.IAsyncResult" /> that represents the status of the asynchronous accept message session operation.</span></span></param>
        <summary><span data-ttu-id="09329-403">EndAcceptMessageSession 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="09329-403">Executes upon calling the EndAcceptMessageSession operation.</span></span></summary>
        <returns><span data-ttu-id="09329-404"><see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</span><span class="sxs-lookup"><span data-stu-id="09329-404">The <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAddRule">
      <MemberSignature Language="C#" Value="protected abstract void OnEndAddRule (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndAddRule(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndAddRule(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndAddRule (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndAddRule : IAsyncResult -&gt; unit" Usage="subscriptionClient.OnEndAddRule result" />
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
        <param name="result"><span data-ttu-id="09329-405"><see cref="T:System.IAsyncResult" />から、<see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginAddRule(Microsoft.ServiceBus.Messaging.RuleDescription,System.TimeSpan,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-405">An <see cref="T:System.IAsyncResult" /> from a <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginAddRule(Microsoft.ServiceBus.Messaging.RuleDescription,System.TimeSpan,System.AsyncCallback,System.Object)" />.</span></span></param>
        <summary><span data-ttu-id="09329-406">非同期呼び出しを終了<see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginAddRule(Microsoft.ServiceBus.Messaging.RuleDescription,System.TimeSpan,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-406">Ends the asynchronous call to <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginAddRule(Microsoft.ServiceBus.Messaging.RuleDescription,System.TimeSpan,System.AsyncCallback,System.Object)" />.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="subscriptionClient.OnEndClose result" />
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
        <param name="result"><span data-ttu-id="09329-407"><see cref="T:System.IAsyncResult" />非同期 BeginClose を参照します。</span><span class="sxs-lookup"><span data-stu-id="09329-407">An <see cref="T:System.IAsyncResult" /> that references the asynchronous BeginClose.</span></span></param>
        <summary><span data-ttu-id="09329-408">最後の閉じる操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="09329-408">Executes the end close action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateReceiver (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateReceiver(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndCreateReceiver(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateReceiver (result As IAsyncResult) As MessageReceiver" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateReceiver : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="subscriptionClient.OnEndCreateReceiver result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="09329-409"><see cref="T:System.IAsyncResult" />を参照するオブジェクト、<see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.EndCreateReceiver(System.IAsyncResult)" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-409">An <see cref="T:System.IAsyncResult" /> object that references the <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.EndCreateReceiver(System.IAsyncResult)" />.</span></span></param>
        <summary><span data-ttu-id="09329-410">最後の実行操作の受信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="09329-410">Executes the end create receiver action.</span></span></summary>
        <returns><span data-ttu-id="09329-411">新しく作成<see cref="T:Microsoft.ServiceBus.Messaging.MessageReceiver" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="09329-411">A newly-created <see cref="T:Microsoft.ServiceBus.Messaging.MessageReceiver" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetMessageSessions">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; OnEndGetMessageSessions (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; OnEndGetMessageSessions(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndGetMessageSessions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetMessageSessions (result As IAsyncResult) As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetMessageSessions : IAsyncResult -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="subscriptionClient.OnEndGetMessageSessions result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="09329-412">メッセージの結果。</span><span class="sxs-lookup"><span data-stu-id="09329-412">The result of the message.</span></span></param>
        <summary><span data-ttu-id="09329-413">End get メッセージのアクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="09329-413">Executes the end get message action.</span></span></summary>
        <returns><span data-ttu-id="09329-414">最後は、メッセージのアクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="09329-414">The end get message action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetRules">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt; OnEndGetRules (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RuleDescription&gt; OnEndGetRules(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndGetRules(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetRules (result As IAsyncResult) As IEnumerable(Of RuleDescription)" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetRules : IAsyncResult -&gt; seq&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;" Usage="subscriptionClient.OnEndGetRules result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRemoveRule">
      <MemberSignature Language="C#" Value="protected abstract void OnEndRemoveRule (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndRemoveRule(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndRemoveRule(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndRemoveRule (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndRemoveRule : IAsyncResult -&gt; unit" Usage="subscriptionClient.OnEndRemoveRule result" />
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
        <param name="result"><span data-ttu-id="09329-415"><see cref="T:System.IAsyncResult" />から、<see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-415">An <see cref="T:System.IAsyncResult" /> from a <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />.</span></span></param>
        <summary><span data-ttu-id="09329-416">非同期呼び出しを終了<see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-416">Ends the asynchronous call to <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRemoveRules">
      <MemberSignature Language="C#" Value="protected abstract void OnEndRemoveRules (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndRemoveRules(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnEndRemoveRules(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndRemoveRules (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndRemoveRules : IAsyncResult -&gt; unit" Usage="subscriptionClient.OnEndRemoveRules result" />
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
        <param name="result"><span data-ttu-id="09329-417">Asynchronization の結果。</span><span class="sxs-lookup"><span data-stu-id="09329-417">The result of the asynchronization.</span></span></param>
        <summary><span data-ttu-id="09329-418">非同期呼び出しを終了<see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-418">Ends the asynchronous call to <see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnBeginRemoveRule(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessage">
      <MemberSignature Language="C#" Value="public void OnMessage (Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessage(class System.Action`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessage (callback As Action(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="member this.OnMessage : Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit" Usage="subscriptionClient.OnMessage callback" />
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
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="09329-419">この操作は完了時に呼び出すメソッド。</span><span class="sxs-lookup"><span data-stu-id="09329-419">The method to invoke when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="09329-420">イベント駆動型メッセージ ポンプにメッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="09329-420">Processes a message in an event-driven message pump.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessage">
      <MemberSignature Language="C#" Value="public void OnMessage (Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessage(class System.Action`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessage : Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="subscriptionClient.OnMessage (callback, onMessageOptions)" />
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
        <Parameter Name="onMessageOptions" Type="Microsoft.ServiceBus.Messaging.OnMessageOptions" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="09329-421">この操作は完了時に呼び出すメソッド。</span><span class="sxs-lookup"><span data-stu-id="09329-421">The method to invoke when the operation is complete.</span></span></param>
        <param name="onMessageOptions"><span data-ttu-id="09329-422">指定します、<see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />メッセージ ポンプをインスタンス化するオプションです。</span><span class="sxs-lookup"><span data-stu-id="09329-422">Specifies the <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" /> options with which to instantiate the message pump.</span></span></param>
        <summary><span data-ttu-id="09329-423">指定されたセットで、イベント駆動型メッセージ ポンプにメッセージを処理<see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />オプション。</span><span class="sxs-lookup"><span data-stu-id="09329-423">Processes a message in an event-driven message pump, with the given set of <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" /> options.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="public void OnMessageAsync (Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt; callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessageAsync(class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage, class System.Threading.Tasks.Task&gt; callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnMessageAsync(System.Func{Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessageAsync (callback As Func(Of BrokeredMessage, Task))" />
      <MemberSignature Language="F#" Value="member this.OnMessageAsync : Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="subscriptionClient.OnMessageAsync callback" />
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
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="09329-424">操作が完了したときに呼び出される非同期のメソッドです。</span><span class="sxs-lookup"><span data-stu-id="09329-424">The asynchronous method to invoke when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="09329-425">非同期的にメッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="09329-425">Asynchronously processes a message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="public void OnMessageAsync (Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessageAsync(class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage, class System.Threading.Tasks.Task&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnMessageAsync(System.Func{Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessageAsync : Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage, System.Threading.Tasks.Task&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="subscriptionClient.OnMessageAsync (callback, onMessageOptions)" />
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
        <Parameter Name="onMessageOptions" Type="Microsoft.ServiceBus.Messaging.OnMessageOptions" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="09329-426">操作が完了したときに呼び出される非同期のメソッドです。</span><span class="sxs-lookup"><span data-stu-id="09329-426">The asynchronous method to invoke when the operation is complete.</span></span></param>
        <param name="onMessageOptions"><span data-ttu-id="09329-427">メッセージに関連付けられているオプションです。</span><span class="sxs-lookup"><span data-stu-id="09329-427">The options associated with the message.</span></span></param>
        <summary><span data-ttu-id="09329-428">非同期的にメッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="09329-428">Asynchronously processes a message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Peek" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="subscriptionClient.Peek " />
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
        <summary><span data-ttu-id="09329-429">キュー内の最初のメッセージを削除することがなくを返します。</span><span class="sxs-lookup"><span data-stu-id="09329-429">Returns without removing the first message in the queue.</span></span></summary>
        <returns><span data-ttu-id="09329-430">返されるメッセージ。</span><span class="sxs-lookup"><span data-stu-id="09329-430">The returned message.</span></span></returns>
        <remarks><span data-ttu-id="09329-431">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="09329-431">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Peek(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek (fromSequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="subscriptionClient.Peek fromSequenceNumber" />
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
        <param name="fromSequenceNumber"><span data-ttu-id="09329-432">元のメッセージを参照する開始点です。</span><span class="sxs-lookup"><span data-stu-id="09329-432">The starting point from which to browse a message.</span></span></param>
        <summary><span data-ttu-id="09329-433">キュー内の最初のメッセージを削除することがなくを返します。</span><span class="sxs-lookup"><span data-stu-id="09329-433">Returns without removing the first message in the queue.</span></span></summary>
        <returns><span data-ttu-id="09329-434">返されるメッセージ。</span><span class="sxs-lookup"><span data-stu-id="09329-434">The returned message.</span></span></returns>
        <remarks><span data-ttu-id="09329-435">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="09329-435">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.PeekAsync " />
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
        <summary><span data-ttu-id="09329-436">非同期的にキューに最初のメッセージを削除せずに返します。</span><span class="sxs-lookup"><span data-stu-id="09329-436">Asynchronously returns without removing the first message in the queue.</span></span></summary>
        <returns><span data-ttu-id="09329-437">非同期操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-437">A task instance that represents the asynchronous peek operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (fromSequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.PeekAsync fromSequenceNumber" />
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
        <param name="fromSequenceNumber"><span data-ttu-id="09329-438">元のメッセージを参照する開始点です。</span><span class="sxs-lookup"><span data-stu-id="09329-438">The starting point from which to browse a message.</span></span></param>
        <summary><span data-ttu-id="09329-439">非同期的にキューに最初のメッセージを削除せずに返します。</span><span class="sxs-lookup"><span data-stu-id="09329-439">Asynchronously returns without removing the first message in the queue.</span></span></summary>
        <returns><span data-ttu-id="09329-440">非同期操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-440">A task instance that represents the asynchronous peek operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.PeekBatch messageCount" />
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
        <param name="messageCount"><span data-ttu-id="09329-441">バッチ内のメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="09329-441">The number of messages in a batch.</span></span></param>
        <summary><span data-ttu-id="09329-442">バッチ内の最初のメッセージを削除することがなくを返します。</span><span class="sxs-lookup"><span data-stu-id="09329-442">Returns without removing the first messages in a batch.</span></span></summary>
        <returns><span data-ttu-id="09329-443">バッチ内の最初のメッセージのコレクション。</span><span class="sxs-lookup"><span data-stu-id="09329-443">The collection of first messages in a batch.</span></span></returns>
        <remarks><span data-ttu-id="09329-444">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="09329-444">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekBatch(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (fromSequenceNumber As Long, messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.PeekBatch (fromSequenceNumber, messageCount)" />
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
        <param name="fromSequenceNumber"><span data-ttu-id="09329-445">元のメッセージを参照する開始点です。</span><span class="sxs-lookup"><span data-stu-id="09329-445">The starting point from which to browse a message.</span></span></param>
        <param name="messageCount"><span data-ttu-id="09329-446">バッチ内のメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="09329-446">The number of messages in a batch.</span></span></param>
        <summary><span data-ttu-id="09329-447">バッチ内の最初のメッセージを削除することがなくを返します。</span><span class="sxs-lookup"><span data-stu-id="09329-447">Returns without removing the first messages in a batch.</span></span></summary>
        <returns><span data-ttu-id="09329-448">バッチ内の最初のメッセージのコレクション。</span><span class="sxs-lookup"><span data-stu-id="09329-448">The collection of first messages in a batch.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="subscriptionClient.PeekBatchAsync messageCount" />
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
        <param name="messageCount"><span data-ttu-id="09329-449">バッチ内のメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="09329-449">The number of messages in a batch.</span></span></param>
        <summary><span data-ttu-id="09329-450">非同期的にバッチ内で最初のメッセージを削除せずに返します。</span><span class="sxs-lookup"><span data-stu-id="09329-450">Asynchronously returns without removing the first messages in a batch.</span></span></summary>
        <returns><span data-ttu-id="09329-451">非同期のピーク バッチ操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-451">A task instance that represents the asynchronous peek batch operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.PeekBatchAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="subscriptionClient.PeekBatchAsync (fromSequenceNumber, messageCount)" />
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
        <param name="fromSequenceNumber"><span data-ttu-id="09329-452">元のメッセージを参照する開始点です。</span><span class="sxs-lookup"><span data-stu-id="09329-452">The starting point from which to browse a message.</span></span></param>
        <param name="messageCount"><span data-ttu-id="09329-453">バッチ内のメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="09329-453">The number of messages in a batch.</span></span></param>
        <summary><span data-ttu-id="09329-454">非同期的にバッチ内で最初のメッセージを削除せずに返します。</span><span class="sxs-lookup"><span data-stu-id="09329-454">Asynchronously returns without removing the first messages in a batch.</span></span></summary>
        <returns><span data-ttu-id="09329-455">非同期のピーク バッチ操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-455">A task instance that represents the asynchronous peek batch operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.PrefetchCount" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceBus.Messaging.IMessageSessionEntity.PrefetchCount</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="09329-456">取得またはメッセージの受信者が同時に要求メッセージの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="09329-456">Gets or sets the number of messages that the message receiver can simultaneously request.</span></span></summary>
        <value><span data-ttu-id="09329-457">メッセージの受信者が同時に要求メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="09329-457">The number of messages that the message receiver can simultaneously request.</span></span></value>
        <remarks> <span data-ttu-id="09329-458">サーバーに次の受信呼び出しで有効になります。</span><span class="sxs-lookup"><span data-stu-id="09329-458">Takes effect on the next receive call to the server.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Receive" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="subscriptionClient.Receive " />
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
        <summary><span data-ttu-id="09329-459">使用してメッセージを受け取る、<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-459">Receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="09329-460"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />受信したメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="09329-460">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> that represents the received message.</span></span></returns>
        <remarks><span data-ttu-id="09329-461">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="09329-461">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="09329-462">サブスクリプションが存在しない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-462">Thrown when the subscription does not exist.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="09329-463">操作を使用して設定されたタイムアウト値を超過した場合にスロー<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-463">Thrown if the operation exceeded the timeout value set via <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="09329-464">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-464">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="09329-465">認証エラーがある場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-465">Thrown if there is an authentication error.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Receive(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (sequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="subscriptionClient.Receive sequenceNumber" />
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
        <param name="sequenceNumber"><span data-ttu-id="09329-466">遅延を受信するメッセージのシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="09329-466">The sequence number of the deferred message to receive.</span></span></param>
        <summary><span data-ttu-id="09329-467">使用してメッセージを受け取る、<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-467">Receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="09329-468"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />受信したメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="09329-468">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />  that represents the received message.</span></span></returns>
        <remarks><span data-ttu-id="09329-469">Null は、操作が、指定したタイムアウトを超えたか、または要求 sequenceNumber を持つメッセージが成功した操作が存在することはできない場合にこの API で戻り値に指定できます。</span><span class="sxs-lookup"><span data-stu-id="09329-469">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but the message with the requested sequenceNumber cannot be located.</span></span></remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="09329-470">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-470">Thrown if the client entity has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Receive(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (serverWaitTime As TimeSpan) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="subscriptionClient.Receive serverWaitTime" />
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
        <param name="serverWaitTime"><span data-ttu-id="09329-471">期間、サーバーは、タイムアウトになる前に、メッセージの受信を待機します。</span><span class="sxs-lookup"><span data-stu-id="09329-471">The time span the server waits for receiving a message before it times out.</span></span></param>
        <summary><span data-ttu-id="09329-472">使用してメッセージを受け取る、<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-472">Receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="09329-473"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />受信したメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="09329-473">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />  that represents the received message.</span></span></returns>
        <remarks><span data-ttu-id="09329-474">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="09329-474">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="09329-475">場合にスローされます、<paramref name="serverWaitTime" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="09329-475">Thrown if the <paramref name="serverWaitTime" /> is negative.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="09329-476">サブスクリプションが存在しない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-476">Thrown when the subscription does not exist.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="09329-477">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-477">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="09329-478">操作を使用して設定されたタイムアウト値を超過した場合にスロー<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-478">Thrown if the operation exceeded the timeout value set via <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="09329-479">認証エラーがある場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-479">Thrown if there is an authentication error.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveAsync " />
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
        <summary><span data-ttu-id="09329-480">使用してメッセージを非同期的に受信、<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-480">Asynchronously receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="09329-481">非同期を表すタスク インスタンスは、操作を受信します。</span><span class="sxs-lookup"><span data-stu-id="09329-481">A task instance that represents the asynchronous receive operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (sequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveAsync sequenceNumber" />
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
        <param name="sequenceNumber"><span data-ttu-id="09329-482">遅延を受信するメッセージのシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="09329-482">The sequence number of the deferred message to receive.</span></span></param>
        <summary><span data-ttu-id="09329-483">使用してメッセージを非同期的に受信、<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-483">Asynchronously receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="09329-484">非同期を表すタスク インスタンスは、操作を受信します。</span><span class="sxs-lookup"><span data-stu-id="09329-484">A task instance that represents the asynchronous receive operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (serverWaitTime As TimeSpan) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveAsync serverWaitTime" />
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
        <param name="serverWaitTime"><span data-ttu-id="09329-485">期間、サーバーは、タイムアウトになる前に、メッセージの受信を待機します。</span><span class="sxs-lookup"><span data-stu-id="09329-485">The time span the server waits for receiving a message before it times out.</span></span></param>
        <summary><span data-ttu-id="09329-486">使用してメッセージを非同期的に受信、<see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-486">Asynchronously receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="09329-487">非同期を表すタスク インスタンスは、操作を受信します。</span><span class="sxs-lookup"><span data-stu-id="09329-487">A task instance that represents the asynchronous receive operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatch(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (sequenceNumbers As IEnumerable(Of Long)) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveBatch sequenceNumbers" />
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
        <param name="sequenceNumbers"><span data-ttu-id="09329-488">シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="09329-488">The sequence number.</span></span></param>
        <summary><span data-ttu-id="09329-489">非同期操作の後にバッチを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="09329-489">Receives a batch after the asynchronous operation.</span></span></summary>
        <returns><span data-ttu-id="09329-490">非同期操作の後にバッチです。</span><span class="sxs-lookup"><span data-stu-id="09329-490">A batch after the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="09329-491">Null は、操作が、指定したタイムアウトを超えたか、または要求 sequenceNumber を持つメッセージが成功した操作が存在することはできない場合にこの API で戻り値に指定できます。</span><span class="sxs-lookup"><span data-stu-id="09329-491">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but the message with the requested sequenceNumber cannot be located.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveBatch messageCount" />
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
        <param name="messageCount"><span data-ttu-id="09329-492">バッチに返されるメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="09329-492">The number of messages to return in the batch.</span></span> <span data-ttu-id="09329-493">これは、概算値よりも少ないまたは複数のメッセージとして<paramref name="messageCount" />返される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="09329-493">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <summary><span data-ttu-id="09329-494">非同期操作の後にバッチを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="09329-494">Receives a batch after the asynchronous operation.</span></span></summary>
        <returns><span data-ttu-id="09329-495">非同期操作の後にバッチです。</span><span class="sxs-lookup"><span data-stu-id="09329-495">A batch after the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="09329-496">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="09329-496">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatch(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer, serverWaitTime As TimeSpan) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="subscriptionClient.ReceiveBatch (messageCount, serverWaitTime)" />
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
        <param name="messageCount"><span data-ttu-id="09329-497">バッチに返されるメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="09329-497">The number of messages to return in the batch.</span></span> <span data-ttu-id="09329-498">これは、概算値よりも少ないまたは複数のメッセージとして<paramref name="messageCount" />返される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="09329-498">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="09329-499">期間、サーバーは、メッセージの処理を待機します。</span><span class="sxs-lookup"><span data-stu-id="09329-499">The time span the server waits for processing messages.</span></span></param>
        <summary><span data-ttu-id="09329-500">非同期操作の後にバッチを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="09329-500">Receives a batch after the asynchronous operation.</span></span></summary>
        <returns><span data-ttu-id="09329-501">非同期操作の後にバッチです。</span><span class="sxs-lookup"><span data-stu-id="09329-501">A batch after the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="09329-502">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="09329-502">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatchAsync(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (sequenceNumbers As IEnumerable(Of Long)) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="subscriptionClient.ReceiveBatchAsync sequenceNumbers" />
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
        <param name="sequenceNumbers"><span data-ttu-id="09329-503">シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="09329-503">The sequence number.</span></span></param>
        <summary><span data-ttu-id="09329-504">非同期的に (バッチ処理) のメッセージのセットを受信します。</span><span class="sxs-lookup"><span data-stu-id="09329-504">Asynchronously receives a set of messages (for batch processing).</span></span></summary>
        <returns><span data-ttu-id="09329-505">非同期の受信のバッチ操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-505">A task instance that represents the asynchronous receive batch operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="subscriptionClient.ReceiveBatchAsync messageCount" />
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
        <param name="messageCount"><span data-ttu-id="09329-506">バッチに返されるメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="09329-506">The number of messages to return in the batch.</span></span> <span data-ttu-id="09329-507">これは、概算値よりも少ないまたは複数のメッセージとして<paramref name="messageCount" />返される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="09329-507">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <summary><span data-ttu-id="09329-508">非同期的に (バッチ処理) のメッセージのセットを受信します。</span><span class="sxs-lookup"><span data-stu-id="09329-508">Asynchronously receives a set of messages (for batch processing).</span></span></summary>
        <returns><span data-ttu-id="09329-509">非同期の受信のバッチ操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-509">A task instance that represents the asynchronous receive batch operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.ReceiveBatchAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer, serverWaitTime As TimeSpan) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="subscriptionClient.ReceiveBatchAsync (messageCount, serverWaitTime)" />
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
        <param name="messageCount"><span data-ttu-id="09329-510">バッチに返されるメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="09329-510">The number of messages to return in the batch.</span></span> <span data-ttu-id="09329-511">これは、概算値よりも少ないまたは複数のメッセージとして<paramref name="messageCount" />返される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="09329-511">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="09329-512">期間、サーバーは、メッセージの処理を待機します。</span><span class="sxs-lookup"><span data-stu-id="09329-512">The time span the server waits for processing messages.</span></span></param>
        <summary><span data-ttu-id="09329-513">非同期的に (バッチ処理) のメッセージのセットを受信します。</span><span class="sxs-lookup"><span data-stu-id="09329-513">Asynchronously receives a set of messages (for batch processing).</span></span></summary>
        <returns><span data-ttu-id="09329-514">非同期の受信のバッチ操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-514">A task instance that represents the asynchronous receive batch operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Type handlerType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandler(class System.Type handlerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandler(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handlerType As Type)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandler : Type -&gt; unit" Usage="subscriptionClient.RegisterSessionHandler handlerType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handlerType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="handlerType"><span data-ttu-id="09329-515">ハンドラーの型。</span><span class="sxs-lookup"><span data-stu-id="09329-515">The type of the handler.</span></span></param>
        <summary><span data-ttu-id="09329-516">クライアントのセッションのハンドラーを登録します。</span><span class="sxs-lookup"><span data-stu-id="09329-516">Registers the handler for the client session.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Type handlerType, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandler(class System.Type handlerType, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandler(System.Type,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handlerType As Type, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandler : Type * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="subscriptionClient.RegisterSessionHandler (handlerType, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handlerType" Type="System.Type" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handlerType"><span data-ttu-id="09329-517">ハンドラーの型。</span><span class="sxs-lookup"><span data-stu-id="09329-517">The type of the handler.</span></span></param>
        <param name="options"><span data-ttu-id="09329-518">セッション ハンドラー オプション。</span><span class="sxs-lookup"><span data-stu-id="09329-518">The session handler options.</span></span></param>
        <summary><span data-ttu-id="09329-519">クライアントのセッションのハンドラーを登録します。</span><span class="sxs-lookup"><span data-stu-id="09329-519">Registers the handler for the client session.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerAsync (Type handlerType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerAsync(class System.Type handlerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerAsync(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerAsync (handlerType As Type) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerAsync : Type -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RegisterSessionHandlerAsync handlerType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handlerType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="handlerType"><span data-ttu-id="09329-520">ハンドラーの型。</span><span class="sxs-lookup"><span data-stu-id="09329-520">The type of the handler.</span></span></param>
        <summary><span data-ttu-id="09329-521">非同期的にクライアントのセッションのハンドラーを登録します。</span><span class="sxs-lookup"><span data-stu-id="09329-521">Asynchronously registers the handler for the client session.</span></span></summary>
        <returns><span data-ttu-id="09329-522">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="09329-522">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerAsync (Type handlerType, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerAsync(class System.Type handlerType, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerAsync(System.Type,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerAsync (handlerType As Type, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerAsync : Type * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RegisterSessionHandlerAsync (handlerType, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handlerType" Type="System.Type" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handlerType"><span data-ttu-id="09329-523">ハンドラーの型。</span><span class="sxs-lookup"><span data-stu-id="09329-523">The type of the handler.</span></span></param>
        <param name="options"><span data-ttu-id="09329-524">セッション ハンドラー オプション。</span><span class="sxs-lookup"><span data-stu-id="09329-524">The session handler options.</span></span></param>
        <summary><span data-ttu-id="09329-525">非同期的にクライアントのセッションのハンドラーを登録します。</span><span class="sxs-lookup"><span data-stu-id="09329-525">Asynchronously registers the handler for the client session.</span></span></summary>
        <returns><span data-ttu-id="09329-526">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="09329-526">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactory">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandlerFactory (Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandlerFactory(class Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerFactory(Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandlerFactory (factory As IMessageSessionAsyncHandlerFactory, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactory : Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="subscriptionClient.RegisterSessionHandlerFactory (factory, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="factory"><span data-ttu-id="09329-527">メッセージのセッションに関連付けられたハンドラー ファクトリのインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="09329-527">The interface for the handler factory associated with the message session.</span></span></param>
        <param name="options"><span data-ttu-id="09329-528">セッション ハンドラー オプション。</span><span class="sxs-lookup"><span data-stu-id="09329-528">The session handler options.</span></span></param>
        <summary><span data-ttu-id="09329-529">クライアントのセッションのハンドラー ファクトリを登録します。</span><span class="sxs-lookup"><span data-stu-id="09329-529">Registers the handler factory for the client session.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactory">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandlerFactory (Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandlerFactory(class Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerFactory(Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandlerFactory (factory As IMessageSessionHandlerFactory, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactory : Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="subscriptionClient.RegisterSessionHandlerFactory (factory, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="factory"><span data-ttu-id="09329-530">メッセージのセッションに関連付けられたハンドラー ファクトリのインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="09329-530">The interface for the handler factory associated with the message session.</span></span></param>
        <param name="options"><span data-ttu-id="09329-531">セッション ハンドラー オプション。</span><span class="sxs-lookup"><span data-stu-id="09329-531">The session handler options.</span></span></param>
        <summary><span data-ttu-id="09329-532">クライアントのセッションのハンドラー ファクトリを登録します。</span><span class="sxs-lookup"><span data-stu-id="09329-532">Registers the handler factory for the client session.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync (Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync(class Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerFactoryAsync(Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerFactoryAsync (factory As IMessageSessionAsyncHandlerFactory, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactoryAsync : Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RegisterSessionHandlerFactoryAsync (factory, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="factory"><span data-ttu-id="09329-533">メッセージのセッションに関連付けられたハンドラー ファクトリのインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="09329-533">The interface for the handler factory associated with the message session.</span></span></param>
        <param name="options"><span data-ttu-id="09329-534">セッション ハンドラー オプション。</span><span class="sxs-lookup"><span data-stu-id="09329-534">The session handler options.</span></span></param>
        <summary><span data-ttu-id="09329-535">非同期的に、クライアント セッションのハンドラー ファクトリを登録します。</span><span class="sxs-lookup"><span data-stu-id="09329-535">Asynchronously registers the handler factory for the client session.</span></span></summary>
        <returns><span data-ttu-id="09329-536">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="09329-536">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync (Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync(class Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RegisterSessionHandlerFactoryAsync(Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerFactoryAsync (factory As IMessageSessionHandlerFactory, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactoryAsync : Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RegisterSessionHandlerFactoryAsync (factory, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="factory" Type="Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="factory"><span data-ttu-id="09329-537">メッセージのセッションに関連付けられたハンドラー ファクトリのインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="09329-537">The interface for the handler factory associated with the message session.</span></span></param>
        <param name="options"><span data-ttu-id="09329-538">セッション ハンドラー オプション。</span><span class="sxs-lookup"><span data-stu-id="09329-538">The session handler options.</span></span></param>
        <summary><span data-ttu-id="09329-539">非同期的に、クライアント セッションのハンドラー ファクトリを登録します。</span><span class="sxs-lookup"><span data-stu-id="09329-539">Asynchronously registers the handler factory for the client session.</span></span></summary>
        <returns><span data-ttu-id="09329-540">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="09329-540">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveRule">
      <MemberSignature Language="C#" Value="public void RemoveRule (string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveRule(string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveRule (ruleName As String)" />
      <MemberSignature Language="F#" Value="member this.RemoveRule : string -&gt; unit" Usage="subscriptionClient.RemoveRule ruleName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ruleName"><span data-ttu-id="09329-541">ルールの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-541">The name of the rule.</span></span></param>
        <summary><span data-ttu-id="09329-542">により記述された規則を削除します<paramref name="ruleName" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-542">Removes the rule described by <paramref name="ruleName" />.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="09329-543">場合にスロー<paramref name="ruleName" />空であるか、適切な形式ではなく、null、白の領域がします。</span><span class="sxs-lookup"><span data-stu-id="09329-543">Thrown if <paramref name="ruleName" /> is null, white space empty or not in the right format.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="09329-544">操作は、OperationTimeout プロパティを使用して設定されたタイムアウト値を超えた場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-544">Thrown if the operation exceeded the timeout value set via the OperationTimeout Property.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="09329-545">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="09329-545">Thrown if the client entity has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveRuleAsync (string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveRuleAsync(string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RemoveRuleAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveRuleAsync (ruleName As String) As Task" />
      <MemberSignature Language="F#" Value="member this.RemoveRuleAsync : string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RemoveRuleAsync ruleName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ruleName"><span data-ttu-id="09329-546">ルールの名前。</span><span class="sxs-lookup"><span data-stu-id="09329-546">The name of the rule.</span></span></param>
        <summary><span data-ttu-id="09329-547">により記述されたルールを非同期に削除します<paramref name="ruleName" />です。</span><span class="sxs-lookup"><span data-stu-id="09329-547">Asynchronously removes the rule described by <paramref name="ruleName" />.</span></span></summary>
        <returns><span data-ttu-id="09329-548">非同期の削除規則の操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="09329-548">A task instance that represents the asynchronous remove rule operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewMessageLock">
      <MemberSignature Language="C#" Value="public DateTime RenewMessageLock (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.DateTime RenewMessageLock(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RenewMessageLock(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewMessageLock (lockToken As Guid) As DateTime" />
      <MemberSignature Language="F#" Value="member this.RenewMessageLock : Guid -&gt; DateTime" Usage="subscriptionClient.RenewMessageLock lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewMessageLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;DateTime&gt; RenewMessageLockAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;valuetype System.DateTime&gt; RenewMessageLockAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.RenewMessageLockAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewMessageLockAsync (lockToken As Guid) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RenewMessageLockAsync : Guid -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="subscriptionClient.RenewMessageLockAsync lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicPath">
      <MemberSignature Language="C#" Value="public string TopicPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionClient.TopicPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TopicPath As String" />
      <MemberSignature Language="F#" Value="member this.TopicPath : string" Usage="Microsoft.ServiceBus.Messaging.SubscriptionClient.TopicPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="09329-549">トピックの完全なパス名を取得します。</span><span class="sxs-lookup"><span data-stu-id="09329-549">Gets the full pathname of the topic.</span></span></summary>
        <value><span data-ttu-id="09329-550">トピックの完全なパス名。</span><span class="sxs-lookup"><span data-stu-id="09329-550">The full pathname of the topic.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>