<Type Name="QueueClient" FullName="Microsoft.ServiceBus.Messaging.QueueClient">
  <TypeSignature Language="C#" Value="public abstract class QueueClient : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit QueueClient extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.QueueClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class QueueClient&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type QueueClient = class&#xA;    inherit ClientEntity&#xA;    interface IMessageSessionEntity&#xA;    interface IMessageClientEntity&#xA;    interface IMessageSender&#xA;    interface IMessageReceiver&#xA;    interface IMessageBrowser" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="4bbe2-101">キュー クライアント オブジェクトを表します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-101">Represents the queue client object.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Abandon(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid -&gt; unit&#xA;override this.Abandon : Guid -&gt; unit" Usage="queueClient.Abandon lockToken" />
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
        <param name="lockToken"><span data-ttu-id="4bbe2-102">ロック トークンは、破棄するロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-102">The lock token bound to the locked message instance to abandon.</span></span></param>
        <summary><span data-ttu-id="4bbe2-103">メッセージを破棄し、メッセージのロックの所有権を放棄します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-103">Discards the message and relinquishes the message lock ownership.</span></span></summary>
        <remarks><span data-ttu-id="4bbe2-104">クライアントは、キュー/トピックからメッセージを取得します。 失敗した場合、このメソッドを呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-104">When the client fails to get the message from the queue/topic, this method should be called.</span></span> <span data-ttu-id="4bbe2-105">Service Bus には、メッセージの配信回数が 1 ずつ増分されます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-105">The Service Bus will increment the delivery count of the message.</span></span> <span data-ttu-id="4bbe2-106">クライアントには、メッセージが再度表示されるか、配信不能キューに移動を試行するか、ようになりましたことができます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-106">The client now can either attempt to receive the message again or move it to the dead-letter queue.</span></span></remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4bbe2-107">操作によって設定されたタイムアウト値を超過した場合にスロー<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-107">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4bbe2-108">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-108">Thrown if the client entity has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Abandon(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="queueClient.Abandon (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="4bbe2-109">ロック トークンは、破棄するロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-109">The lock token bound to the locked message instance to abandon.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4bbe2-110">変更するメッセージのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-110">The properties of the message to modify.</span></span></param>
        <summary><span data-ttu-id="4bbe2-111">メッセージを破棄し、メッセージのロックの所有権を放棄します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-111">Discards the message and relinquishes the message lock ownership.</span></span></summary>
        <remarks><span data-ttu-id="4bbe2-112">クライアントは、キュー/トピックからメッセージを取得します。 失敗した場合、このメソッドを呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-112">When the client fails to get the message from the queue/topic, this method should be called.</span></span> <span data-ttu-id="4bbe2-113">Service Bus には、メッセージの配信回数が 1 ずつ増分されます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-113">The Service Bus will increment the delivery count of the message.</span></span> <span data-ttu-id="4bbe2-114">クライアントには、メッセージが再度表示されるか、配信不能キューに移動を試行するか、ようになりましたことができます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-114">The client now can either attempt to receive the message again or move it to the dead-letter queue.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AbandonAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="queueClient.AbandonAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="4bbe2-115">ロック トークンは、破棄するロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-115">The lock token bound to the locked message instance to abandon.</span></span></param>
        <summary><span data-ttu-id="4bbe2-116">非同期的にメッセージを破棄し、メッセージのロックの所有権を放棄します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-116">Asynchronously discards the message and relinquishes the message lock ownership.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-117">破棄されたメッセージ。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-117">The discarded message.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AbandonAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.AbandonAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="4bbe2-118">ロック トークンは、破棄するロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-118">The lock token bound to the locked message instance to abandon.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4bbe2-119">変更するメッセージのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-119">The properties of the message to modify.</span></span></param>
        <summary><span data-ttu-id="4bbe2-120">非同期的にメッセージを破棄し、メッセージのロックの所有権を放棄します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-120">Asynchronously discards the message and relinquishes the message lock ownership.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-121">破棄されたメッセージ。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-121">The discarded message.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession () As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : unit -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : unit -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession " />
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
        <summary><span data-ttu-id="4bbe2-122">1 つのトランザクションで処理するための関連するメッセージのグループ化したメッセージのセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-122">Accepts a message session that allows grouping of related messages for processing in a single transaction.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-123">A<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-123">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4bbe2-124">操作によって設定されたタイムアウト値を超過した場合にスロー<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-124">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4bbe2-125">クライアントが既に終了、中止、または破棄される場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-125">Thrown if the client is already closed, aborted, or disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (isExclusiveMode As Boolean) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession isExclusiveMode" />
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
        <param name="isExclusiveMode"><span data-ttu-id="4bbe2-126">囲ま排他モード、または false がない場合。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-126">Ture if exclusive mode, or false is not.</span></span></param>
        <summary>
            <span data-ttu-id="4bbe2-127">排他モードであるかどうかを 1 つのトランザクション i 番目で処理するための関連するメッセージのグループ化をできるメッセージ セッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-127">Accepts a message session that allows grouping of related messages for processing in a single transaction ith whether in exclusive mode.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession sessionId" />
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
        <param name="sessionId"><span data-ttu-id="4bbe2-128">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-128">The session identifier of the message session.</span></span></param>
        <summary><span data-ttu-id="4bbe2-129">特定のセッション識別子を使用して、単一のトランザクションで処理するための関連するメッセージのグループ化をできるメッセージ セッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-129">Accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-130">A<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-130">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="4bbe2-131">セッション Id が null、空、または空白文字である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-131">Thrown if sessionId is null, empty, or white spaces.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4bbe2-132">操作によって設定されたタイムアウト値を超過した場合にスロー<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-132">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4bbe2-133">クライアントが既に終了、中止、または破棄される場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-133">Thrown if the client is already closed, aborted, or disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession serverWaitTime" />
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
        <param name="serverWaitTime"><span data-ttu-id="4bbe2-134">メッセージの処理がタイムアウトする前に、サーバーが待機するを期間します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-134">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="4bbe2-135">指定されたサーバー待機時間を使用して、単一のトランザクションで処理するための関連するメッセージのグループ化したメッセージのセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-135">Accepts a message session that allows grouping of related messages for processing in a single transaction using the specified server wait time.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-136">A<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-136">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="4bbe2-137">場合にスロー<paramref name="serverWaitTime" />正の TimeSpan 値ではありません。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-137">Thrown if <paramref name="serverWaitTime" /> is not a positive TimeSpan value.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4bbe2-138">操作によって設定されたタイムアウト値を超過した場合にスロー<paramref name="serverWaitTime" />です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-138">Thrown if the operation exceeded the timeout value set by <paramref name="serverWaitTime" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4bbe2-139">クライアントが既に終了、中止、または破棄される場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-139">Thrown if the client is already closed, aborted, or disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (isExclusiveMode, serverWaitTime)" />
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
        <param name="isExclusiveMode"><span data-ttu-id="4bbe2-140">囲ま排他モード、または false がない場合。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-140">Ture if exclusive mode, or false is not.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4bbe2-141">サーバーのタイムアウト</span><span class="sxs-lookup"><span data-stu-id="4bbe2-141">The server wait timeout</span></span></param>
        <summary>
            <span data-ttu-id="4bbe2-142">排他モードであるかどうかを 1 つのトランザクション i 番目で処理するための関連するメッセージのグループ化をできるメッセージ セッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-142">Accepts a message session that allows grouping of related messages for processing in a single transaction ith whether in exclusive mode.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, isExclusiveMode As Boolean) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * bool -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (sessionId, isExclusiveMode)" />
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
        <param name="sessionId"><span data-ttu-id="4bbe2-143">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-143">The session identifier of the message session.</span></span></param>
        <param name="isExclusiveMode"><span data-ttu-id="4bbe2-144">囲ま排他モード、または false がない場合。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-144">Ture if exclusive mode, or false is not.</span></span></param>
        <summary>
            <span data-ttu-id="4bbe2-145">排他モードでかどうかと、単一のトランザクションで処理するための関連するメッセージのグループ化したメッセージのセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-145">Accepts a message session that allows grouping of related messages for processing in a single transaction with whether in exclusive mode.</span></span>
            </summary>
        <returns><span data-ttu-id="4bbe2-146">A<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-146">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, lockToken As Guid) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * Guid -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * Guid -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (sessionId, lockToken)" />
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
        <param name="sessionId"><span data-ttu-id="4bbe2-147">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-147">The session identifier of the message session.</span></span></param>
        <param name="lockToken"><span data-ttu-id="4bbe2-148">セッション ロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-148">The session lock token.</span></span></param>
        <summary>
            <span data-ttu-id="4bbe2-149">指定したセッション識別子とセッションのロック トークンを使用して、単一のトランザクションで処理するための関連するメッセージのグループ化したメッセージ非排他的なロックされているセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-149">Accepts a message non-exclusive locked session that allows grouping of related messages for processing in a single transaction using the given session identifier and session lock token.</span></span>
            </summary>
        <returns><span data-ttu-id="4bbe2-150">A<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-150">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (sessionId, serverWaitTime)" />
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
        <param name="sessionId"><span data-ttu-id="4bbe2-151">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-151">The session identifier of the message session.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4bbe2-152">メッセージの処理がタイムアウトする前に、サーバーが待機するを期間します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-152">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="4bbe2-153">特定のセッション識別子と待機時間を使用して、単一のトランザクションで処理するための関連するメッセージのグループ化をできるメッセージ セッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-153">Accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier and wait time.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-154">A<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-154">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="4bbe2-155">セッション Id が null、空、または空白文字である場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-155">Thrown if sessionId is null, empty, or white spaces.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="4bbe2-156">場合にスロー<paramref name="serverWaitTime" />正の TimeSpan 値ではありません。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-156">Thrown if <paramref name="serverWaitTime" /> is not a positive TimeSpan value.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4bbe2-157">操作によって設定されたタイムアウト値を超過した場合にスロー<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-157">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4bbe2-158">クライアントが既に終了、中止、または破棄される場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-158">Thrown if the client is already closed, aborted, or disposed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * bool * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (sessionId, isExclusiveMode, serverWaitTime)" />
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
        <param name="sessionId"><span data-ttu-id="4bbe2-159">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-159">The session identifier of the message session.</span></span></param>
        <param name="isExclusiveMode"><span data-ttu-id="4bbe2-160">囲ま排他モード、または false がない場合。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-160">Ture if exclusive mode, or false is not.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4bbe2-161">サーバーのタイムアウト</span><span class="sxs-lookup"><span data-stu-id="4bbe2-161">The server wait timeout</span></span></param>
        <summary>
            <span data-ttu-id="4bbe2-162">排他モードでかどうかを指定したセッション識別子を使用して、単一のトランザクションで処理するための関連するメッセージのグループ化をできるメッセージ セッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-162">Accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier with whether in exclusive mode.</span></span>
            </summary>
        <returns><span data-ttu-id="4bbe2-163">A<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-163">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (string sessionId, Guid lockToken, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(string sessionId, valuetype System.Guid lockToken, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSession(System.String,System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (sessionId As String, lockToken As Guid, serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSession : string * Guid * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.AcceptMessageSession : string * Guid * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.AcceptMessageSession (sessionId, lockToken, serverWaitTime)" />
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
        <param name="sessionId"><span data-ttu-id="4bbe2-164">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-164">The session identifier of the message session.</span></span></param>
        <param name="lockToken"><span data-ttu-id="4bbe2-165">セッション locktoken</span><span class="sxs-lookup"><span data-stu-id="4bbe2-165">The session locktoken</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4bbe2-166">サーバーのタイムアウト</span><span class="sxs-lookup"><span data-stu-id="4bbe2-166">The server wait timeout</span></span></param>
        <summary>
            <span data-ttu-id="4bbe2-167">指定したセッション識別子とセッションのロック トークンを使用して、単一のトランザクションで処理するための関連するメッセージのグループ化したメッセージ非排他的なロックされているセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-167">Accepts a message non-exclusive locked session that allows grouping of related messages for processing in a single transaction using the given session identifier and session lock token.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync " />
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
        <summary><span data-ttu-id="4bbe2-168">非同期的に 1 つのトランザクションで処理するための関連するメッセージのグループ化したメッセージのセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-168">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-169">非同期操作の結果。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-169">The result of an asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (isExclusiveMode As Boolean) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync isExclusiveMode" />
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
        <param name="isExclusiveMode"><span data-ttu-id="4bbe2-170">囲ま排他モード、または false がない場合。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-170">Ture if exclusive mode, or false is not.</span></span></param>
        <summary><span data-ttu-id="4bbe2-171">非同期的にかどうかを単一のトランザクションで排他モードと待機時間での処理に関連するメッセージのグループ化したメッセージのセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-171">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction with whether in exclusive mode and wait time.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-172">非同期操作の結果。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-172">The result of an asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync sessionId" />
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
        <param name="sessionId"><span data-ttu-id="4bbe2-173">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-173">The session identifier of the message session.</span></span></param>
        <summary><span data-ttu-id="4bbe2-174">非同期的に特定のセッション識別子を使用して、単一のトランザクションで処理するための関連するメッセージのグループ化をできるメッセージ セッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-174">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-175">非同期操作の結果。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-175">The result of an asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync serverWaitTime" />
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
        <param name="serverWaitTime"><span data-ttu-id="4bbe2-176">メッセージの処理がタイムアウトする前に、サーバーが待機するを期間します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-176">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="4bbe2-177">非同期的に、指定されたサーバー待機時間を使用して、単一のトランザクションで処理するための関連するメッセージのグループ化したメッセージのセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-177">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction using the specified server wait time.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-178">非同期操作の結果。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-178">The result of an asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (isExclusiveMode, serverWaitTime)" />
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
        <param name="isExclusiveMode"><span data-ttu-id="4bbe2-179">囲ま排他モード、または false がない場合。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-179">Ture if exclusive mode, or false is not.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4bbe2-180">メッセージの処理がタイムアウトする前に、サーバーが待機するを期間します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-180">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="4bbe2-181">非同期的にかどうかを単一のトランザクションで排他モードと待機時間での処理に関連するメッセージのグループ化したメッセージのセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-181">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction with whether in exclusive mode and wait time.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-182">非同期操作の結果。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-182">The result of an asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, bool isExclusiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, bool isExclusiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, isExclusiveMode As Boolean) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (sessionId, isExclusiveMode)" />
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
        <param name="sessionId"><span data-ttu-id="4bbe2-183">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-183">The session identifier of the message session.</span></span></param>
        <param name="isExclusiveMode"><span data-ttu-id="4bbe2-184">囲ま排他モード、または false がない場合。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-184">Ture if exclusive mode, or false is not.</span></span></param>
        <summary>
            <span data-ttu-id="4bbe2-185">排他モードでかどうかを指定したセッション識別子を使用して、単一のトランザクションで処理するための関連するメッセージのグループ化をできるメッセージ セッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-185">Accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier with whether in exclusive mode.</span></span>
            </summary>
        <returns><span data-ttu-id="4bbe2-186">非同期操作の結果。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-186">The result of an asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, lockToken As Guid) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (sessionId, lockToken)" />
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
        <param name="sessionId"><span data-ttu-id="4bbe2-187">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-187">The session identifier of the message session.</span></span></param>
        <param name="lockToken"><span data-ttu-id="4bbe2-188">セッション ロック トークンです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-188">The session lock token.</span></span></param>
        <summary>
            <span data-ttu-id="4bbe2-189">指定したセッション識別子とセッションのロック トークンを使用して、単一のトランザクションで処理するための関連するメッセージのグループ化したメッセージ非排他的なロックされているセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-189">Accepts a message non-exclusive locked session that allows grouping of related messages for processing in a single transaction using the given session identifier and session lock token.</span></span>
            </summary>
        <returns><span data-ttu-id="4bbe2-190">非同期操作の結果。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-190">The result of an asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (sessionId, serverWaitTime)" />
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
        <param name="sessionId"><span data-ttu-id="4bbe2-191">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-191">The session identifier of the message session.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4bbe2-192">メッセージの処理がタイムアウトする前に、サーバーが待機するを期間します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-192">The time span the server waits for processing messages before it times out.</span></span></param>
        <summary><span data-ttu-id="4bbe2-193">非同期的に特定のセッション識別子と待機時間を使用して、単一のトランザクションで処理するための関連するメッセージのグループ化をできるメッセージ セッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-193">Asynchronously accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier and wait time.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-194">非同期操作の結果。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-194">The result of an asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, bool isExclusiveMode, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, bool isExclusiveMode, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, isExclusiveMode As Boolean, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * bool * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (sessionId, isExclusiveMode, serverWaitTime)" />
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
        <param name="sessionId"><span data-ttu-id="4bbe2-195">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-195">The session identifier of the message session.</span></span></param>
        <param name="isExclusiveMode"><span data-ttu-id="4bbe2-196">囲ま排他モード、または false がない場合。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-196">Ture if exclusive mode, or false is not.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4bbe2-197">サーバーのタイムアウト</span><span class="sxs-lookup"><span data-stu-id="4bbe2-197">The server wait timeout</span></span></param>
        <summary>
            <span data-ttu-id="4bbe2-198">排他モードでかどうかを指定したセッション識別子を使用して、単一のトランザクションで処理するための関連するメッセージのグループ化をできるメッセージ セッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-198">Accepts a message session that allows grouping of related messages for processing in a single transaction using the given session identifier with whether in exclusive mode.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (string sessionId, Guid lockToken, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.Guid lockToken, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.AcceptMessageSessionAsync(System.String,System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, lockToken As Guid, serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.AcceptMessageSessionAsync (sessionId, lockToken, serverWaitTime)" />
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
        <param name="sessionId"><span data-ttu-id="4bbe2-199">メッセージ セッションのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-199">The session identifier of the message session.</span></span></param>
        <param name="lockToken"><span data-ttu-id="4bbe2-200">セッション locktoken</span><span class="sxs-lookup"><span data-stu-id="4bbe2-200">The session locktoken</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4bbe2-201">サーバーのタイムアウト</span><span class="sxs-lookup"><span data-stu-id="4bbe2-201">The server wait timeout</span></span></param>
        <summary>
            <span data-ttu-id="4bbe2-202">指定したセッション識別子とセッションのロック トークンを使用して、単一のトランザクションで処理するための関連するメッセージのグループ化したメッセージ非排他的なロックされているセッションを受け入れます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-202">Accepts a message non-exclusive locked session that allows grouping of related messages for processing in a single transaction using the given session identifier and session lock token.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelScheduledMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelScheduledMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelScheduledMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CancelScheduledMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelScheduledMessageAsync (sequenceNumber As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelScheduledMessageAsync : int64 -&gt; System.Threading.Tasks.Task" Usage="queueClient.CancelScheduledMessageAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><span data-ttu-id="4bbe2-203">メッセージのスケジュール設定に返されます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-203">Returned on scheduling a message.</span></span></param>
        <summary>
            <span data-ttu-id="4bbe2-204">スケジュールされたメッセージを取り消します</span><span class="sxs-lookup"><span data-stu-id="4bbe2-204">Cancels a scheduled message</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Complete">
      <MemberSignature Language="C#" Value="public void Complete (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Complete(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Complete(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Complete (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Complete : Guid -&gt; unit&#xA;override this.Complete : Guid -&gt; unit" Usage="queueClient.Complete lockToken" />
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
        <param name="lockToken"><span data-ttu-id="4bbe2-205">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-205">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="4bbe2-206">メッセージの処理を完了します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-206">Completes processing of a message.</span></span></summary>
        <remarks> <span data-ttu-id="4bbe2-207">このメソッドは、メッセージの配信の保証の Service Bus とクライアント間のハンドシェイクとして使用されます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-207">This method is used as a handshake between the client and Service Bus for a guaranteed delivery of the message.</span></span> <span data-ttu-id="4bbe2-208">このメソッドを呼び出す前に、クライアントが失敗した場合、メッセージがキューに保持されます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-208">If the client failed before calling this method, the message will be kept in the queue.</span></span></remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4bbe2-209">操作によって設定されたタイムアウト値を超過した場合にスローされます。<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></span><span class="sxs-lookup"><span data-stu-id="4bbe2-209">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4bbe2-210">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-210">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="4bbe2-211">メッセージがによって表される場合にスローされます、<paramref name="lockToken" />メッセージのロックを失いました。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-211">Thrown if the message represented by the <paramref name="lockToken" /> has lost the message lock.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CompleteAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="queueClient.CompleteAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="4bbe2-212">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-212">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="4bbe2-213">非同期的にメッセージの処理を完了します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-213">Asynchronously completes processing of a message.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-214">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-214">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatch">
      <MemberSignature Language="C#" Value="public void CompleteBatch (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CompleteBatch(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CompleteBatch(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CompleteBatch (lockTokens As IEnumerable(Of Guid))" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatch : seq&lt;Guid&gt; -&gt; unit&#xA;override this.CompleteBatch : seq&lt;Guid&gt; -&gt; unit" Usage="queueClient.CompleteBatch lockTokens" />
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
        <param name="lockTokens"><span data-ttu-id="4bbe2-215">バッチ内のロックされたメッセージに関連付けられたロック トークン。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-215">The lock tokens associated with locked messages in the batch.</span></span></param>
        <summary><span data-ttu-id="4bbe2-216">メッセージ バッチの処理を完了します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-216">Completes processing of a message batch.</span></span></summary>
        <remarks> <span data-ttu-id="4bbe2-217">このメソッドは、メッセージの配信の保証の Service Bus とクライアント間のハンドシェイクとして使用されます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-217">This method is used as a handshake between the client and Service Bus for a guaranteed delivery of the message.</span></span> <span data-ttu-id="4bbe2-218">このメソッドを呼び出す前に、クライアントが失敗した場合、メッセージがキューに保持されます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-218">If the client failed before calling this method, the message will be kept in the queue.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteBatchAsync (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CompleteBatchAsync(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteBatchAsync (lockTokens As IEnumerable(Of Guid)) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.CompleteBatchAsync lockTokens" />
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
        <param name="lockTokens"><span data-ttu-id="4bbe2-219">バッチ内のロックされたメッセージに関連付けられたロック トークン。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-219">The lock tokens associated with locked messages in the batch.</span></span></param>
        <summary><span data-ttu-id="4bbe2-220">非同期的にメッセージ バッチの処理を完了します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-220">Asynchronously completes processing of a message batch.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-221">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-221">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (path As String) As QueueClient" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="4bbe2-222">パス。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-222">The path.</span></span></param>
        <summary><span data-ttu-id="4bbe2-223">新しいコピーを作成<see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />指定されたパスにします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-223">Creates a new copy of <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> with specified path.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-224">作成された <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-224">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks><span data-ttu-id="4bbe2-225">このメソッドは、app.config または web.config ファイルのどちらかから接続文字列情報を取得しようとします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-225">This method will attempt to retrieve the connection string information from either app.config, or web.config files.</span></span> <span data-ttu-id="4bbe2-226">ユーザーは、構成の「AppSettings」セクションを使用して接続文字列を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-226">User must supply the connection string using the "AppSettings" section of the configuration.</span></span> <span data-ttu-id="4bbe2-227">セクションの形式は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-227">The format of the section is as follows:</span></span>
            
            <code><appSettings><!-- Service Bus specific app setings for messaging connections --><add key="Microsoft.ServiceBus.ConnectionString" value="Endpoint=sb://[your namespace].servicebus.windows.net;SharedSecretIssuer=owner;SharedSecretValue=[your secret]" /></appSettings></code></remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (string path, Microsoft.ServiceBus.Messaging.ReceiveMode mode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (path As String, mode As ReceiveMode) As QueueClient" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create (path, mode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="4bbe2-228">パス。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-228">The path.</span></span></param>
        <param name="mode"><span data-ttu-id="4bbe2-229">モードです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-229">The mode.</span></span></param>
        <summary><span data-ttu-id="4bbe2-230">新しいコピーを作成<see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />指定されたパスとモードを使用します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-230">Creates a new copy of <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> with specified path and mode.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-231">作成された <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-231">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks><span data-ttu-id="4bbe2-232">このメソッドは、app.config または web.config ファイルのどちらかから接続文字列情報を取得しようとします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-232">This method will attempt to retrieve the connection string information from either app.config, or web.config files.</span></span> <span data-ttu-id="4bbe2-233">ユーザーは、構成の「AppSettings」セクションを使用して接続文字列を指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-233">User must supply the connection string using the "AppSettings" section of the configuration.</span></span> <span data-ttu-id="4bbe2-234">セクションの形式は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-234">The format of the section is as follows:</span></span>
            
            <code><appSettings><!-- Service Bus specific app setings for messaging connections --><add key="Microsoft.ServiceBus.ConnectionString" value="Endpoint=sb://[your namespace].servicebus.windows.net;SharedSecretIssuer=owner;SharedSecretValue=[your secret]" /></appSettings></code></remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create (endpointAddress, path, authContext, clientAssertionCertificate, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="4bbe2-235">Sercvice バスの完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-235">Fully qualified domain name for Sercvice Bus.</span></span> <span data-ttu-id="4bbe2-236">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="4bbe2-236">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="4bbe2-237">キューへのパス。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-237">The path to the queue.</span></span></param>
        <param name="authContext"><span data-ttu-id="4bbe2-238">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-238">AuthenticationContext for AAD.</span></span></param>
        <param name="clientAssertionCertificate"><span data-ttu-id="4bbe2-239">アサーションの証明書のクライアント資格情報でします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-239">The client assertion certificate credential.</span></span></param>
        <param name="mode"><span data-ttu-id="4bbe2-240">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-240">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="4bbe2-241"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-241"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="4bbe2-242">メッセージング トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-242">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="4bbe2-243">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> Azure Active Directory 認証コンテキストを使用しています。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-243">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-244">作成された <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-244">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create (endpointAddress, path, authContext, clientCredential, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="4bbe2-245">Service Bus の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-245">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="4bbe2-246">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="4bbe2-246">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="4bbe2-247">キューへのパス。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-247">The path to the queue.</span></span></param>
        <param name="authContext"><span data-ttu-id="4bbe2-248">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-248">AuthenticationContext for AAD.</span></span></param>
        <param name="clientCredential"><span data-ttu-id="4bbe2-249">アプリの資格情報。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-249">The app credential.</span></span></param>
        <param name="mode"><span data-ttu-id="4bbe2-250">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-250">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="4bbe2-251"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-251"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="4bbe2-252">メッセージング トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-252">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="4bbe2-253">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> Azure Active Directory 認証コンテキストを使用しています。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-253">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-254">作成された <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-254">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential userPasswordCredential, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create (endpointAddress, path, authContext, clientId, userPasswordCredential, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userPasswordCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="4bbe2-255">Service Bus の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-255">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="4bbe2-256">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="4bbe2-256">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="4bbe2-257">キューへのパス。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-257">The path to the queue.</span></span></param>
        <param name="authContext"><span data-ttu-id="4bbe2-258">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-258">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="4bbe2-259">AAD の ClientId です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-259">ClientId for AAD.</span></span></param>
        <param name="userPasswordCredential"><span data-ttu-id="4bbe2-260">ユーザーのパスワード資格情報です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-260">The user password credential.</span></span></param>
        <param name="mode"><span data-ttu-id="4bbe2-261">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-261">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="4bbe2-262"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-262"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="4bbe2-263">メッセージング トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-263">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="4bbe2-264">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> Azure Active Directory 認証コンテキストを使用しています。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-264">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-265">作成された <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-265">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient Create (Uri endpointAddress, string path, Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient Create(class System.Uri endpointAddress, string path, class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Create(System.Uri,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * string * Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Create (endpointAddress, path, authContext, clientId, redirectUri, platformParameters, userIdentifier, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
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
        <param name="endpointAddress"><span data-ttu-id="4bbe2-266">Service Bus の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-266">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="4bbe2-267">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="4bbe2-267">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="4bbe2-268">キューへのパス。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-268">The path to the queue.</span></span></param>
        <param name="authContext"><span data-ttu-id="4bbe2-269">AAD の AuthenticationContext します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-269">AuthenticationContext for AAD.</span></span></param>
        <param name="clientId"><span data-ttu-id="4bbe2-270">AAD の ClientId です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-270">ClientId for AAD.</span></span></param>
        <param name="redirectUri"><span data-ttu-id="4bbe2-271">クライアント アプリで redrectUri です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-271">The redrectUri on Client App.</span></span></param>
        <param name="platformParameters"><span data-ttu-id="4bbe2-272">プラットフォームのパラメーター</span><span class="sxs-lookup"><span data-stu-id="4bbe2-272">Platform parameters</span></span></param>
        <param name="userIdentifier"><span data-ttu-id="4bbe2-273">ユーザーの識別子</span><span class="sxs-lookup"><span data-stu-id="4bbe2-273">User Identifier</span></span></param>
        <param name="mode"><span data-ttu-id="4bbe2-274">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-274">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="4bbe2-275"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-275"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="4bbe2-276">メッセージング トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-276">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="4bbe2-277">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> Azure Active Directory 認証コンテキストを使用しています。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-277">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> by using Azure Active Directory authentication context.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-278">作成された <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-278">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As QueueClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="4bbe2-279">使用する接続文字列。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-279">The connection string to use.</span></span></param>
        <summary><span data-ttu-id="4bbe2-280">新しいインスタンスを作成<see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />指定された接続文字列を使用します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-280">Creates a new instance of <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> using the specified connection string.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-281">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-281">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> instance.</span></span></returns>
        <remarks><span data-ttu-id="4bbe2-282">このメソッドは、指定された接続文字列がエンティティのパスなどのエンティティ レベルの情報と提供された認証情報が必要です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-282">This method expects the connection string supplied has entity level information such as the entity path and authentication information supplied.</span></span></remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="4bbe2-283">場合にスローされるの形式、<paramref name="connectionString" />パラメーターが正しくありません。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-283">Thrown when the format of the <paramref name="connectionString" /> parameter is incorrect.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString (string connectionString, Microsoft.ServiceBus.Messaging.ReceiveMode mode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString(string connectionString, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, mode As ReceiveMode) As QueueClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString (connectionString, mode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="4bbe2-284">使用する接続文字列。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-284">The connection string to use.</span></span></param>
        <param name="mode"><span data-ttu-id="4bbe2-285"><see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-285">The <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />.</span></span></param>
        <summary><span data-ttu-id="4bbe2-286">新しいインスタンスを作成<see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />モードを指定した接続文字列を使用して送受信されます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-286">Creates a new instance of <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> using the specified connection string and receiving mode.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-287">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-287">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> instance.</span></span></returns>
        <remarks><span data-ttu-id="4bbe2-288">このメソッドは、指定された接続文字列がエンティティのパスなどのエンティティ レベルの情報と提供された認証情報が必要です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-288">This method expects the connection string supplied has entity level information such as the entity path and authentication information supplied.</span></span></remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="4bbe2-289">場合にスローされるの形式、<paramref name="connectionString" />パラメーターが正しくありません。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-289">Thrown when the format of the <paramref name="connectionString" /> parameter is incorrect.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString (string connectionString, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString(string connectionString, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, path As String) As QueueClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString (connectionString, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="4bbe2-290">使用する接続文字列。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-290">The connection string used.</span></span></param>
        <param name="path"><span data-ttu-id="4bbe2-291">キューへのパス。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-291">The path to the queue.</span></span></param>
        <summary><span data-ttu-id="4bbe2-292">新しいコピーを作成<see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />指定したキューのパスを接続文字列から。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-292">Creates a new copy of <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> from a connection string with the specified queue path.</span></span> <span data-ttu-id="4bbe2-293">接続文字列で使用しない場合にのみ、このオーバー ロードを使用して、<see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-293">Use this overload only when the connection string does not use the <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" /> property.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-294">作成された <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-294">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks><span data-ttu-id="4bbe2-295">このメソッドを指定する接続文字列には、エンティティ レベル情報が関連付けられている必要がありますいないために、名前空間レベルの認証を持つ接続文字列でのみ使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-295">This method should only be used with a connection string that has namespace level authentication because the connection string supplied should not have entity level information associated with it.</span></span></remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="4bbe2-296">場合にスローされるの形式、<paramref name="connectionString" />パラメーターが正しくありません。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-296">Thrown when the format of the <paramref name="connectionString" /> parameter is incorrect.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString (string connectionString, string path, Microsoft.ServiceBus.Messaging.ReceiveMode mode);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient CreateFromConnectionString(string connectionString, string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String, path As String, mode As ReceiveMode) As QueueClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.CreateFromConnectionString (connectionString, path, mode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="4bbe2-297">接続文字列。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-297">The connection string.</span></span></param>
        <param name="path"><span data-ttu-id="4bbe2-298">キューへのパス。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-298">The path to the queue.</span></span></param>
        <param name="mode"><span data-ttu-id="4bbe2-299"><see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-299">The <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />.</span></span></param>
        <summary><span data-ttu-id="4bbe2-300">新しいインスタンスを作成<see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />、指定したパスおよびモードで接続文字列から。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-300">Creates a new instance of <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> from a connection string with the specified path and mode.</span></span> <span data-ttu-id="4bbe2-301">接続文字列で使用しない場合にのみ、このオーバー ロードを使用して、<see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-301">Use this overload only when the connection string does not use the <see cref="P:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder.EntityPath" /> property.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-302">作成された <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-302">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks><span data-ttu-id="4bbe2-303">このメソッドを指定する接続文字列には、エンティティ レベル情報が関連付けられている必要がありますいないために、名前空間レベルの認証を持つ接続文字列でのみ使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-303">This method should only be used with a connection string that has namespace level authentication because the connection string supplied should not have entity level information associated with it.</span></span></remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="4bbe2-304">場合にスローされるの形式、<paramref name="connectionString" />パラメーターが正しくありません。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-304">Thrown when the format of the <paramref name="connectionString" /> parameter is incorrect.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithManagedServiceIdentity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.QueueClient CreateWithManagedServiceIdentity (Uri endpointAddress, string path, Microsoft.ServiceBus.Messaging.ReceiveMode mode = Microsoft.ServiceBus.Messaging.ReceiveMode.PeekLock, Nullable&lt;TimeSpan&gt; operationTimeout = null, Microsoft.ServiceBus.Messaging.TransportType transportType = Microsoft.ServiceBus.Messaging.TransportType.NetMessaging);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.QueueClient CreateWithManagedServiceIdentity(class System.Uri endpointAddress, string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode mode, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; operationTimeout, valuetype Microsoft.ServiceBus.Messaging.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.CreateWithManagedServiceIdentity(System.Uri,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Nullable{System.TimeSpan},Microsoft.ServiceBus.Messaging.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateWithManagedServiceIdentity : Uri * string * Microsoft.ServiceBus.Messaging.ReceiveMode * Nullable&lt;TimeSpan&gt; * Microsoft.ServiceBus.Messaging.TransportType -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="Microsoft.ServiceBus.Messaging.QueueClient.CreateWithManagedServiceIdentity (endpointAddress, path, mode, operationTimeout, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointAddress" Type="System.Uri" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="operationTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="transportType" Type="Microsoft.ServiceBus.Messaging.TransportType" />
      </Parameters>
      <Docs>
        <param name="endpointAddress"><span data-ttu-id="4bbe2-305">Service Bus の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-305">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="4bbe2-306">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="4bbe2-306">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="path"><span data-ttu-id="4bbe2-307">キューへのパス。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-307">The path to the queue.</span></span></param>
        <param name="mode"><span data-ttu-id="4bbe2-308">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-308">The receive mode.</span></span></param>
        <param name="operationTimeout">
          <span data-ttu-id="4bbe2-309"><see cref="T:System.TimeSpan" />メッセージング操作が開始がタイムアウトになるまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-309"><see cref="T:System.TimeSpan" /> that specifies how long the messaging operation has to complete before timing out</span></span></param>
        <param name="transportType"><span data-ttu-id="4bbe2-310">メッセージング トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-310">Messaging transport type.</span></span></param>
        <summary><span data-ttu-id="4bbe2-311">新しいインスタンスを作成、 <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> Azure 管理サービス Id の認証を使用しています。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-311">Creates a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" /> by using Azure Managed Service Identity authentication.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-312">作成された <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-312">The created <see cref="T:Microsoft.ServiceBus.Messaging.QueueClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetter(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid -&gt; unit&#xA;override this.DeadLetter : Guid -&gt; unit" Usage="queueClient.DeadLetter lockToken" />
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
        <param name="lockToken"><span data-ttu-id="4bbe2-313">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-313">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="4bbe2-314">配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-314">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4bbe2-315">操作によって設定されたタイムアウト値を超過した場合にスローされます。<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></span><span class="sxs-lookup"><span data-stu-id="4bbe2-315">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4bbe2-316">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-316">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="4bbe2-317">メッセージがによって表される場合にスローされます、<paramref name="lockToken" />メッセージのロックを失いました。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-317">Thrown if the message represented by the <paramref name="lockToken" /> has lost the message lock.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetter(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="queueClient.DeadLetter (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="4bbe2-318">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-318">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4bbe2-319">変更するメッセージのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-319">The properties of the message to modify.</span></span></param>
        <summary><span data-ttu-id="4bbe2-320">配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-320">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetter(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * string * string -&gt; unit&#xA;override this.DeadLetter : Guid * string * string -&gt; unit" Usage="queueClient.DeadLetter (lockToken, deadLetterReason, deadLetterErrorDescription)" />
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
        <param name="lockToken"><span data-ttu-id="4bbe2-321">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-321">The lock token bound to the locked message instance.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="4bbe2-322">メッセージの配信不能の理由です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-322">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="4bbe2-323">メッセージの配信不能のエラーの説明。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-323">The error description for deadlettering the message.</span></span></param>
        <summary><span data-ttu-id="4bbe2-324">配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-324">Moves the undelivered message to the dead letter queue.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4bbe2-325">操作によって設定されたタイムアウト値を超過した場合にスローされます。<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></span><span class="sxs-lookup"><span data-stu-id="4bbe2-325">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4bbe2-326">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-326">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="4bbe2-327">メッセージがによって表される場合にスローされます、<paramref name="lockToken" />メッセージのロックを失いました。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-327">Thrown if the message represented by the <paramref name="lockToken" /> has lost the message lock.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetterAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeadLetterAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="4bbe2-328">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-328">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="4bbe2-329">非同期的に配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-329">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-330">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-330">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetterAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeadLetterAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="4bbe2-331">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-331">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4bbe2-332">変更するメッセージのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-332">The properties of the message to modify.</span></span></param>
        <summary><span data-ttu-id="4bbe2-333">非同期的に配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-333">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-334">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-334">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeadLetterAsync(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
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
        <param name="lockToken"><span data-ttu-id="4bbe2-335">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-335">The lock token bound to the locked message instance.</span></span></param>
        <param name="deadLetterReason"><span data-ttu-id="4bbe2-336">メッセージの配信不能の理由です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-336">The reason for deadlettering the message.</span></span></param>
        <param name="deadLetterErrorDescription"><span data-ttu-id="4bbe2-337">メッセージの配信不能のエラーの説明。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-337">The error description for deadlettering the message.</span></span></param>
        <summary><span data-ttu-id="4bbe2-338">非同期的に配信不能メッセージを配信不能キューに移動します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-338">Asynchronously moves the undelivered message to the dead letter queue.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-339">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-339">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Defer(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid -&gt; unit&#xA;override this.Defer : Guid -&gt; unit" Usage="queueClient.Defer lockToken" />
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
        <param name="lockToken"><span data-ttu-id="4bbe2-340">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-340">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="4bbe2-341">メッセージの処理を中断します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-341">Suspends the processing of a message.</span></span></summary>
        <remarks><span data-ttu-id="4bbe2-342">を保留する前にする必要があります確保しておいたメッセージの受信確認を後で取得します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-342">Before deferring, you should set aside the message receipt for later retrieval.</span></span> </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4bbe2-343">操作によって設定されたタイムアウト値を超過した場合にスローされます。<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></span><span class="sxs-lookup"><span data-stu-id="4bbe2-343">Thrown if the operation exceeded the timeout value set by <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4bbe2-344">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-344">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException"><span data-ttu-id="4bbe2-345">メッセージがによって表される場合にスローされます、<paramref name="lockToken" />メッセージのロックを失いました。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-345">Thrown if the message represented by the <paramref name="lockToken" /> has lost the message lock.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Defer(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="queueClient.Defer (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="4bbe2-346">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-346">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4bbe2-347">変更するメッセージのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-347">The properties of the message to modify.</span></span></param>
        <summary><span data-ttu-id="4bbe2-348">メッセージの処理を中断します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-348">Suspends the processing of a message.</span></span></summary>
        <remarks><span data-ttu-id="4bbe2-349">を保留する前にする必要があります確保しておいたメッセージの受信確認を後で取得します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-349">Before deferring, you should set aside the message receipt for later retrieval.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeferAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeferAsync lockToken" />
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
        <param name="lockToken"><span data-ttu-id="4bbe2-350">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-350">The lock token bound to the locked message instance.</span></span></param>
        <summary><span data-ttu-id="4bbe2-351">非同期的にメッセージの処理を中断します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-351">Asynchronously suspends the processing of a message.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-352">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-352">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.DeferAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeferAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken"><span data-ttu-id="4bbe2-353">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-353">The lock token bound to the locked message instance.</span></span></param>
        <param name="propertiesToModify"><span data-ttu-id="4bbe2-354">変更するメッセージのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-354">The properties of the message to modify.</span></span></param>
        <summary><span data-ttu-id="4bbe2-355">非同期的にメッセージの処理を中断します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-355">Asynchronously suspends the processing of a message.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-356">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-356">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatDeadLetterPath">
      <MemberSignature Language="C#" Value="public static string FormatDeadLetterPath (string queuePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatDeadLetterPath(string queuePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.FormatDeadLetterPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatDeadLetterPath (queuePath As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatDeadLetterPath : string -&gt; string" Usage="Microsoft.ServiceBus.Messaging.QueueClient.FormatDeadLetterPath queuePath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queuePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="queuePath"><span data-ttu-id="4bbe2-357">配信不能キューへのパス。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-357">The path to the dead letter queue.</span></span></param>
        <summary><span data-ttu-id="4bbe2-358">指定された配信不能キューのパスの形式名を構築します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-358">Builds a format name from the specified dead letter queue path.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-359"><see cref="T:System.String" />から指定された配信不能キューのパスの形式名のビルドが発生しました。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-359">The <see cref="T:System.String" /> resulted from building the format name for the specified dead letter queue path.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FormatTransferDeadLetterPath">
      <MemberSignature Language="C#" Value="public static string FormatTransferDeadLetterPath (string queuePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string FormatTransferDeadLetterPath(string queuePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.FormatTransferDeadLetterPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FormatTransferDeadLetterPath (queuePath As String) As String" />
      <MemberSignature Language="F#" Value="static member FormatTransferDeadLetterPath : string -&gt; string" Usage="Microsoft.ServiceBus.Messaging.QueueClient.FormatTransferDeadLetterPath queuePath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queuePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="queuePath"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.GetMessageSessions" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessions () As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessions : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.GetMessageSessions : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.GetMessageSessions " />
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
        <summary><span data-ttu-id="4bbe2-360">キュー上のセッションを参照できるように、メッセージのセッションを取得します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-360">Gets the message sessions, enabling you to browse sessions on queues.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-361">メッセージ セッションです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-361">The message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions (DateTime lastUpdatedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; GetMessageSessions(valuetype System.DateTime lastUpdatedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.GetMessageSessions(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessions (lastUpdatedTime As DateTime) As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessions : DateTime -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&#xA;override this.GetMessageSessions : DateTime -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.GetMessageSessions lastUpdatedTime" />
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
        <param name="lastUpdatedTime"><span data-ttu-id="4bbe2-362">セッションの最終更新時刻。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-362">The time the session was last updated.</span></span></param>
        <summary><span data-ttu-id="4bbe2-363">すべてのメッセージのセッションがセッション状態が以降更新された取得<paramref name="lastUpdatedTime" />です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-363">Retrieves all message sessions whose session state was updated since <paramref name="lastUpdatedTime" />.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-364">メッセージのセッションです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-364">The message sessions.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.GetMessageSessionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessionsAsync () As Task(Of IEnumerable(Of MessageSession))" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;&#xA;override this.GetMessageSessionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;" Usage="queueClient.GetMessageSessionsAsync " />
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
        <summary><span data-ttu-id="4bbe2-365">キュー上のセッションを参照できるように、メッセージのセッションを非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-365">Asynchronously gets the message sessions, enabling you to browse sessions on queues.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-366">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-366">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageSessionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync (DateTime lastUpdatedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt; GetMessageSessionsAsync(valuetype System.DateTime lastUpdatedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.GetMessageSessionsAsync(System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMessageSessionsAsync (lastUpdatedTime As DateTime) As Task(Of IEnumerable(Of MessageSession))" />
      <MemberSignature Language="F#" Value="abstract member GetMessageSessionsAsync : DateTime -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;&#xA;override this.GetMessageSessionsAsync : DateTime -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;&gt;" Usage="queueClient.GetMessageSessionsAsync lastUpdatedTime" />
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
        <param name="lastUpdatedTime"><span data-ttu-id="4bbe2-367">セッションの最終更新時刻。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-367">The time the session was last updated.</span></span></param>
        <summary><span data-ttu-id="4bbe2-368">以降のセッション状態が更新されたすべてのメッセージ セッションを非同期に取得<paramref name="lastUpdatedTime" />です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-368">Asynchronously retrieves all message sessions whose session state was updated since <paramref name="lastUpdatedTime" />.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-369">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-369">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessagingFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessagingFactory MessagingFactory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueClient.MessagingFactory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessagingFactory As MessagingFactory" />
      <MemberSignature Language="F#" Value="member this.MessagingFactory : Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.QueueClient.MessagingFactory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4bbe2-370">取得またはメッセージング ファクトリを設定します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-370">Gets or sets the messaging factory.</span></span></summary>
        <value><span data-ttu-id="4bbe2-371">メッセージング ファクトリ。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-371">The messaging factory.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ReceiveMode Mode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.ReceiveMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueClient.Mode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Mode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.Messaging.ReceiveMode" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ReceiveMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4bbe2-372">メッセージを取得、受信したメッセージを処理するときに、受信モード。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-372">Gets the message receive mode when processing the received message.</span></span></summary>
        <value><span data-ttu-id="4bbe2-373">メッセージ<see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />受信したメッセージを処理するときにします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-373">The message <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" /> when processing the received message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="queueClient.OnAbort " />
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
        <summary><span data-ttu-id="4bbe2-374">中断イベントの呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-374">Executes upon calling the Abort event.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAcceptMessageSession (string sessionId, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, int prefetchCount, bool isExclusiveMode, Nullable&lt;Guid&gt; lockToken, TimeSpan serverWaitTime, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAcceptMessageSession(string sessionId, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, int32 prefetchCount, bool isExclusiveMode, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; lockToken, valuetype System.TimeSpan serverWaitTime, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginAcceptMessageSession(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.Int32,System.Boolean,System.Nullable{System.Guid},System.TimeSpan,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAcceptMessageSession : string * Microsoft.ServiceBus.Messaging.ReceiveMode * int * bool * Nullable&lt;Guid&gt; * TimeSpan * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginAcceptMessageSession (sessionId, receiveMode, prefetchCount, isExclusiveMode, lockToken, serverWaitTime, timeout, callback, state)" />
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
        <Parameter Name="prefetchCount" Type="System.Int32" />
        <Parameter Name="isExclusiveMode" Type="System.Boolean" />
        <Parameter Name="lockToken" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="sessionId"></param>
        <param name="receiveMode"></param>
        <param name="prefetchCount"></param>
        <param name="isExclusiveMode"></param>
        <param name="lockToken"></param>
        <param name="serverWaitTime"></param>
        <param name="timeout"></param>
        <param name="callback"></param>
        <param name="state"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginClose (timeout, callback, state)" />
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
        <param name="timeout"><span data-ttu-id="4bbe2-375">クローズ操作がタイムアウトするまでの最大時間。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-375">The maximum time before the close operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="4bbe2-376">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-376">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="4bbe2-377">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-377">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="4bbe2-378">このオブジェクトは、EndClose に渡されるデリゲート、操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-378">This object is passed to the EndClose delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="4bbe2-379">クローズ操作が呼び出されたときに実行します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-379">Executes when the Close operation is called.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-380"><see cref="T:System.IAsyncResult" />親の非同期メソッドを参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-380">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous parent method.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateReceiver (Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateReceiver(valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginCreateReceiver(Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateReceiver : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginCreateReceiver (receiveMode, timeout, callback, state)" />
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
        <param name="receiveMode"><span data-ttu-id="4bbe2-381">メッセージ<see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />受信モード。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-381">The message <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" /> receive mode.</span></span></param>
        <param name="timeout"><span data-ttu-id="4bbe2-382">この操作の前に最大の時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-382">The maximum time before this operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="4bbe2-383">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-383">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="4bbe2-384">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-384">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="4bbe2-385">このオブジェクトは、操作の完了時に <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateReceiver(System.IAsyncResult)" /> デリゲートに渡されます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-385">This object is passed to the <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateReceiver(System.IAsyncResult)" /> delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="4bbe2-386">実行の開始操作の受信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-386">Executes the begin create receiver action.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-387"><see cref="T:System.IAsyncResult" />親の非同期メソッドを参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-387">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous parent method.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateReceiver (string subQueueName, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateReceiver(string subQueueName, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginCreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginCreateReceiver (subQueueName, receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subQueueName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="subQueueName"><span data-ttu-id="4bbe2-388">サブ キューの名前。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-388">Name of the sub-queue.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="4bbe2-389">メッセージ<see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" />受信モード。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-389">The message <see cref="T:Microsoft.ServiceBus.Messaging.ReceiveMode" /> receive mode.</span></span></param>
        <param name="timeout"><span data-ttu-id="4bbe2-390">この操作の前に最大の時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-390">The maximum time before this operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="4bbe2-391">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-391">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="4bbe2-392">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-392">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="4bbe2-393">このオブジェクトは、操作の完了時に <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateReceiver(System.IAsyncResult)" /> デリゲートに渡されます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-393">This object is passed to the <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateReceiver(System.IAsyncResult)" /> delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="4bbe2-394">実行の開始操作の受信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-394">Executes the begin create receiver action.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-395"><see cref="T:System.IAsyncResult" />親の非同期メソッドを参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-395">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous parent method.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateSender">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateSender (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateSender(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginCreateSender(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginCreateSender (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateSender : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginCreateSender (timeout, callback, state)" />
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
        <param name="timeout"><span data-ttu-id="4bbe2-396">この操作の前に最大の時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-396">The maximum time before this operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="4bbe2-397">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-397">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="4bbe2-398">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-398">A user-defined object that contains information about the receive operation.</span></span> <span data-ttu-id="4bbe2-399">このオブジェクトは、操作の完了時に <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateSender(System.IAsyncResult)" /> デリゲートに渡されます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-399">This object is passed to the <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateSender(System.IAsyncResult)" /> delegate when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="4bbe2-400">実行開始操作の送信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-400">Executes the begin create sender action.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-401"><see cref="T:System.IAsyncResult" />親の非同期メソッドを参照するオブジェクト</span><span class="sxs-lookup"><span data-stu-id="4bbe2-401">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous parent method</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetMessageSessions">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetMessageSessions (DateTime lastUpdatedTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetMessageSessions(valuetype System.DateTime lastUpdatedTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnBeginGetMessageSessions(System.DateTime,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginGetMessageSessions (lastUpdatedTime As DateTime, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetMessageSessions : DateTime * AsyncCallback * obj -&gt; IAsyncResult" Usage="queueClient.OnBeginGetMessageSessions (lastUpdatedTime, callback, state)" />
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
        <param name="lastUpdatedTime"><span data-ttu-id="4bbe2-402">日付と最終更新時刻です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-402">The date and time of the last update.</span></span></param>
        <param name="callback"><span data-ttu-id="4bbe2-403">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-403">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="4bbe2-404">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-404">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="4bbe2-405">BeginGetMessageSessions アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-405">Executes the BeginGetMessageSessions action.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-406"><see cref="T:System.IAsyncResult" />メッセージ セッションを取得する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-406">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to get the message sessions.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="queueClient.OnClose timeout" />
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
        <param name="timeout"><span data-ttu-id="4bbe2-407">クローズ操作がタイムアウトするまでの最大時間。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-407">The maximum time before the close operation times out.</span></span></param>
        <summary><span data-ttu-id="4bbe2-408">終了アクションの呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-408">Executes upon calling the Close action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnEndAcceptMessageSession(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndAcceptMessageSession (result As IAsyncResult) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member OnEndAcceptMessageSession : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="queueClient.OnEndAcceptMessageSession result" />
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
        <param name="result"><span data-ttu-id="4bbe2-409"><see cref="T:System.IAsyncResult" />を表す非同期の受信メッセージのセッションの操作の状態。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-409">An <see cref="T:System.IAsyncResult" /> that represents the status of the asynchronous accept message session operation.</span></span></param>
        <summary><span data-ttu-id="4bbe2-410">EndAcceptMessageSession 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-410">Executes upon calling the EndAcceptMessageSession operation.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-411"><see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-411">The <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="queueClient.OnEndClose result" />
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
        <param name="result"><span data-ttu-id="4bbe2-412">非同期の親メソッドの結果。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-412">The result of the asynchronous parent method.</span></span></param>
        <summary><span data-ttu-id="4bbe2-413">最後の閉じる操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-413">Executes the end close action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateReceiver (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateReceiver(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnEndCreateReceiver(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateReceiver (result As IAsyncResult) As MessageReceiver" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateReceiver : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="queueClient.OnEndCreateReceiver result" />
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
        <param name="result"><span data-ttu-id="4bbe2-414">非同期の結果<see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateReceiver(System.IAsyncResult)" />操作します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-414">The result of the asynchronous <see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.EndCreateReceiver(System.IAsyncResult)" /> operation.</span></span></param>
        <summary><span data-ttu-id="4bbe2-415">最後の実行操作の受信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-415">Executes the end create receiver action.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-416"><see cref="T:Microsoft.ServiceBus.Messaging.MessageReceiver" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-416">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageReceiver" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateSender">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateSender (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateSender(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnEndCreateSender(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateSender (result As IAsyncResult) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateSender : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="queueClient.OnEndCreateSender result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="4bbe2-417"><see cref="T:System.IAsyncResult" />親の非同期メソッドを参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-417">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous parent method.</span></span></param>
        <summary><span data-ttu-id="4bbe2-418">最後の実行操作の送信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-418">Executes the end create sender action.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-419"><see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-419">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetMessageSessions">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; OnEndGetMessageSessions (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; OnEndGetMessageSessions(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnEndGetMessageSessions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetMessageSessions (result As IAsyncResult) As IEnumerable(Of MessageSession)" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetMessageSessions : IAsyncResult -&gt; seq&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="queueClient.OnEndGetMessageSessions result" />
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
        <param name="result"><span data-ttu-id="4bbe2-420">セッションの結果。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-420">The result of the session.</span></span></param>
        <summary><span data-ttu-id="4bbe2-421">End get メッセージのアクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-421">Executes the end get message action.</span></span></summary>
        <returns> <span data-ttu-id="4bbe2-422"><see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-422">The <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessage">
      <MemberSignature Language="C#" Value="public void OnMessage (Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessage(class System.Action`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessage (callback As Action(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="member this.OnMessage : Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit" Usage="queueClient.OnMessage callback" />
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
        <param name="callback"><span data-ttu-id="4bbe2-423">この操作は完了時に呼び出すメソッド。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-423">The method to invoke when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="4bbe2-424">イベント駆動型メッセージ ポンプにメッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-424">Processes a message in an event-driven message pump.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessage">
      <MemberSignature Language="C#" Value="public void OnMessage (Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessage(class System.Action`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessage : Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="queueClient.OnMessage (callback, onMessageOptions)" />
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
        <param name="callback"><span data-ttu-id="4bbe2-425">この操作は完了時に呼び出すメソッド。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-425">The method to invoke when the operation is complete.</span></span></param>
        <param name="onMessageOptions"><span data-ttu-id="4bbe2-426">指定します、<see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />メッセージ ポンプをインスタンス化するオプションです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-426">Specifies the <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" /> options with which to instantiate the message pump.</span></span></param>
        <summary><span data-ttu-id="4bbe2-427">指定されたセットで、イベント駆動型メッセージ ポンプにメッセージを処理<see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />オプション。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-427">Processes a message in an event-driven message pump, with the given set of <see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" /> options.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="public void OnMessageAsync (Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt; callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessageAsync(class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage, class System.Threading.Tasks.Task&gt; callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnMessageAsync(System.Func{Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessageAsync (callback As Func(Of BrokeredMessage, Task))" />
      <MemberSignature Language="F#" Value="member this.OnMessageAsync : Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="queueClient.OnMessageAsync callback" />
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
        <param name="callback"><span data-ttu-id="4bbe2-428">この操作は完了時に呼び出すメソッド。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-428">The method to invoke when the operation is complete.</span></span></param>
        <summary><span data-ttu-id="4bbe2-429">非同期的にメッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-429">Asynchronously processes a message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="public void OnMessageAsync (Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessageAsync(class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage, class System.Threading.Tasks.Task&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions onMessageOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.OnMessageAsync(System.Func{Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessageAsync : Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage, System.Threading.Tasks.Task&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="queueClient.OnMessageAsync (callback, onMessageOptions)" />
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
        <param name="callback"><span data-ttu-id="4bbe2-430">この操作は完了時に呼び出すメソッド。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-430">The method to invoke when the operation is complete.</span></span></param>
        <param name="onMessageOptions"><span data-ttu-id="4bbe2-431">メッセージ オプションを呼び出します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-431">Calls a message option.</span></span></param>
        <summary><span data-ttu-id="4bbe2-432">非同期的にメッセージを処理します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-432">Asynchronously processes a message.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.QueueClient.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4bbe2-433">取得またはキューの完全なパス名を設定します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-433">Gets or sets the full path name of the queue.</span></span></summary>
        <value><span data-ttu-id="4bbe2-434">キューのパスを基準とする、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />ベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-434">The queue path relative to the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> base address.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Peek" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="queueClient.Peek " />
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
        <summary><span data-ttu-id="4bbe2-435">キュー内の最初のメッセージを削除することがなくを返します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-435">Returns without removing the first message in the queue.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-436">仲介型メッセージです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-436">A brokered message.</span></span> <span data-ttu-id="4bbe2-437">すべてのプロパティと、メッセージ本文を返します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-437">Returns all properties and the message body.</span></span></returns>
        <remarks><span data-ttu-id="4bbe2-438">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-438">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Peek(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek (fromSequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="queueClient.Peek fromSequenceNumber" />
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
        <param name="fromSequenceNumber"><span data-ttu-id="4bbe2-439">元のメッセージを参照する開始点です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-439">The starting point from which to browse a message.</span></span></param>
        <summary><span data-ttu-id="4bbe2-440">キュー内の最初のメッセージを削除することがなくを返します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-440">Returns without removing the first message in the queue.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-441">仲介型メッセージです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-441">The brokered message.</span></span></returns>
        <remarks><span data-ttu-id="4bbe2-442">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-442">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.PeekAsync " />
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
        <summary><span data-ttu-id="4bbe2-443">非同期的にキューに最初のメッセージを削除せずに返します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-443">Asynchronously returns without removing the first message in the queue.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-444">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-444">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (fromSequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.PeekAsync fromSequenceNumber" />
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
        <param name="fromSequenceNumber"><span data-ttu-id="4bbe2-445">メッセージをピークする場所からシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-445">The sequence number from where to peek a message.</span></span></param>
        <summary><span data-ttu-id="4bbe2-446">非同期的にキューに最初のメッセージを削除せずに返します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-446">Asynchronously returns without removing the first message in the queue.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-447">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-447">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.PeekBatch messageCount" />
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
        <param name="messageCount"><span data-ttu-id="4bbe2-448">メッセージ数。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-448">The number of messages.</span></span></param>
        <summary><span data-ttu-id="4bbe2-449">バッチのメッセージをピークします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-449">Peeks a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-450">バッチのメッセージをピークします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-450">A batch of messages peeked.</span></span> <span data-ttu-id="4bbe2-451">すべてのプロパティと、メッセージ本文を返します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-451">Returns all properties and the message body.</span></span></returns>
        <remarks><span data-ttu-id="4bbe2-452">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-452">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekBatch(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (fromSequenceNumber As Long, messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.PeekBatch (fromSequenceNumber, messageCount)" />
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
        <param name="fromSequenceNumber"><span data-ttu-id="4bbe2-453">メッセージのバッチを参照する開始点です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-453">The starting point from which to browse a batch of messages.</span></span></param>
        <param name="messageCount"><span data-ttu-id="4bbe2-454">メッセージ数。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-454">The number of messages.</span></span></param>
        <summary><span data-ttu-id="4bbe2-455">バッチのメッセージをピークします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-455">Peeks a batch of messages.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-456">バッチのメッセージをピークします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-456">A batch of messages peeked.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="queueClient.PeekBatchAsync messageCount" />
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
        <param name="messageCount"><span data-ttu-id="4bbe2-457">メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-457">The number of message.</span></span></param>
        <summary><span data-ttu-id="4bbe2-458">非同期的にメッセージのバッチをピークします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-458">Asynchronously peeks a batch of message.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-459">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-459">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.PeekBatchAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="queueClient.PeekBatchAsync (fromSequenceNumber, messageCount)" />
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
        <param name="fromSequenceNumber"><span data-ttu-id="4bbe2-460">メッセージのバッチをここに表示する場所からシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-460">The sequence number from where to peek a batch of message.</span></span></param>
        <param name="messageCount"><span data-ttu-id="4bbe2-461">メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-461">The number of message.</span></span></param>
        <summary><span data-ttu-id="4bbe2-462">非同期的にメッセージのバッチをピークします。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-462">Asynchronously peeks a batch of message.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-463">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-463">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.QueueClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.QueueClient.PrefetchCount" />
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
        <summary><span data-ttu-id="4bbe2-464">取得またはキューの受信側が同時に要求メッセージの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-464">Gets or sets the number of messages that the queue receiver can simultaneously request.</span></span></summary>
        <value><span data-ttu-id="4bbe2-465">キューの受信側が同時に要求メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-465">The number of messages that the queue receiver can simultaneously request.</span></span></value>
        <remarks> <span data-ttu-id="4bbe2-466">サーバーに次の受信呼び出しで有効になります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-466">Takes effect on the next receive call to the server.</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Receive" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="queueClient.Receive " />
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
        <summary><span data-ttu-id="4bbe2-467">使用してメッセージを受け取る、<see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-467">Receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-468"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />受信したメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-468">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> that represents the received message.</span></span> <span data-ttu-id="4bbe2-469">受信できるメッセージがない場合は、メソッド、NULL を返し、後で操作を再試行することができます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-469">If no message is available to be received, the method returns NULL, and you can retry the operation at a later time.</span></span></returns>
        <remarks><span data-ttu-id="4bbe2-470">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-470">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4bbe2-471">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-471">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4bbe2-472">メッセージ受信操作がタイムアウトになる場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-472">Thrown if the message receive operation times out.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="4bbe2-473">I/O やセキュリティ エラーが発生した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-473">Thrown if an I/O or security error occurs.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="4bbe2-474">操作に関連付けられているメッセージング エンティティが存在しないか、削除されている場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-474">Thrown if the messaging entity associated with the operation does not exist or it has been deleted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="4bbe2-475">ユーザー コードでは、いくつか予期しない操作を実行します。 または、Service Bus ゲートウェイがダウンする場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-475">Thrown if the user code has performed some unexpected operations, or the Service Bus gateway is down.</span></span> <span data-ttu-id="4bbe2-476">実際のエラーの例外メッセージを確認します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-476">Check the exception message for the actual error.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Receive(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (sequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="queueClient.Receive sequenceNumber" />
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
        <param name="sequenceNumber"><span data-ttu-id="4bbe2-477">遅延を受信するメッセージのシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-477">The sequence number of the deferred message to receive.</span></span> </param>
        <summary><span data-ttu-id="4bbe2-478">使用してメッセージを受け取る、<see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-478">Receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-479"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />受信したメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-479">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> that represents the received message.</span></span> <span data-ttu-id="4bbe2-480">受信できるメッセージがない場合は、メソッド、NULL を返し、後で操作を再試行することができます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-480">If no message is available to be received, the method returns NULL, and you can retry the operation at a later time.</span></span></returns>
        <remarks><span data-ttu-id="4bbe2-481">Null は、操作が、指定したタイムアウトを超えたか、または要求 sequenceNumber を持つメッセージが成功した操作が存在することはできない場合にこの API で戻り値に指定できます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-481">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but the message with the requested sequenceNumber cannot be located.</span></span></remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4bbe2-482">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-482">Thrown if the client entity has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Receive(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (serverWaitTime As TimeSpan) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="queueClient.Receive serverWaitTime" />
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
        <param name="serverWaitTime"><span data-ttu-id="4bbe2-483">期間、サーバーは、タイムアウトになる前に、メッセージの受信を待機します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-483">The time span the server waits for receiving a message before it times out.</span></span></param>
        <summary><span data-ttu-id="4bbe2-484">使用してメッセージを受け取る、<see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-484">Receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-485"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />受信したメッセージを表すです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-485">The <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> that represents the received message.</span></span> <span data-ttu-id="4bbe2-486">受信できるメッセージがない場合は、メソッド、NULL を返し、後で操作を再試行することができます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-486">If no message is available to be received, the method returns NULL, and you can retry the operation at a later time.</span></span></returns>
        <remarks><span data-ttu-id="4bbe2-487">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-487">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="4bbe2-488">場合にスローされます、<paramref name="serverWaitTime" />が負の値。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-488">Thrown if the <paramref name="serverWaitTime" /> is negative.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4bbe2-489">メッセージ受信操作がタイムアウトになる場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-489">Thrown if the message receive operation times out.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4bbe2-490">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-490">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="4bbe2-491">I/O やセキュリティ エラーが発生した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-491">Thrown if an I/O or security error occurs.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="4bbe2-492">操作に関連付けられているメッセージング エンティティが存在しないか、削除されている場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-492">Thrown if the messaging entity associated with the operation does not exist or it has been deleted.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="4bbe2-493">ユーザー コードでは、いくつか予期しない操作を実行します。 または、Service Bus ゲートウェイがダウンする場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-493">Thrown if the user code has performed some unexpected operations, or the Service Bus gateway is down.</span></span> <span data-ttu-id="4bbe2-494">実際のエラーの例外メッセージを確認します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-494">Check the exception message for the actual error.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveAsync " />
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
        <summary><span data-ttu-id="4bbe2-495">使用してメッセージを非同期的に受信、<see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-495">Asynchronously receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-496">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-496">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (sequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveAsync sequenceNumber" />
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
        <param name="sequenceNumber"><span data-ttu-id="4bbe2-497">遅延を受信するメッセージのシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-497">The sequence number of the deferred message to receive.</span></span></param>
        <summary><span data-ttu-id="4bbe2-498">使用してメッセージを非同期的に受信、<see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-498">Asynchronously receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-499">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-499">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (serverWaitTime As TimeSpan) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveAsync serverWaitTime" />
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
        <param name="serverWaitTime"><span data-ttu-id="4bbe2-500">期間、サーバーは、タイムアウトになる前に、メッセージの受信を待機します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-500">The time span the server waits for receiving a message before it times out.</span></span></param>
        <summary><span data-ttu-id="4bbe2-501">使用してメッセージを非同期的に受信、<see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-501">Asynchronously receives a message using the <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalReceiver" />.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-502">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-502">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatch(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (sequenceNumbers As IEnumerable(Of Long)) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveBatch sequenceNumbers" />
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
        <param name="sequenceNumbers"><span data-ttu-id="4bbe2-503">バッチ内のメッセージに関連付けられているシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-503">The sequence numbers associated with the messages in the batch.</span></span></param>
        <summary><span data-ttu-id="4bbe2-504">メッセージ バッチを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-504">Receives a message batch.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-505">メッセージ バッチです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-505">A message batch.</span></span></returns>
        <remarks><span data-ttu-id="4bbe2-506">Null は、操作が、指定したタイムアウトを超えたか、または要求 sequenceNumber を持つメッセージが成功した操作が存在することはできない場合にこの API で戻り値に指定できます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-506">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but the message with the requested sequenceNumber cannot be located.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveBatch messageCount" />
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
        <param name="messageCount"><span data-ttu-id="4bbe2-507">バッチに返されるメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-507">The number of messages to return in the batch.</span></span> <span data-ttu-id="4bbe2-508">これは、概算値よりも少ないまたは複数のメッセージとして<paramref name="messageCount" />返される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-508">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <summary><span data-ttu-id="4bbe2-509">メッセージ バッチを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-509">Receives a message batch.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-510">メッセージ バッチです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-510">A message batch.</span></span></returns>
        <remarks><span data-ttu-id="4bbe2-511">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-511">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatch(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer, serverWaitTime As TimeSpan) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="queueClient.ReceiveBatch (messageCount, serverWaitTime)" />
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
        <param name="messageCount"><span data-ttu-id="4bbe2-512">バッチで受信するメッセージの数。これは、概算値よりも少ないまたは複数のメッセージとして<paramref name="messageCount" />返される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-512">The number of messages to receive in a batch.As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4bbe2-513">サーバーがタイムアウトになる前に到着するメッセージのバッチを待機する時間間隔です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-513">The time span that the server will wait for the message batch to arrive before it times out.</span></span></param>
        <summary><span data-ttu-id="4bbe2-514">メッセージ バッチを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-514">Receives a message batch.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-515">メッセージ バッチです。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-515">A message batch.</span></span></returns>
        <remarks><span data-ttu-id="4bbe2-516">Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-516">A Null can be return by this API if operation exceeded the timeout specified, or the operations succeeded but there are no more messages to be received.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatchAsync(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (sequenceNumbers As IEnumerable(Of Long)) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="queueClient.ReceiveBatchAsync sequenceNumbers" />
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
        <param name="sequenceNumbers"><span data-ttu-id="4bbe2-517">バッチ内のメッセージに関連付けられているシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-517">The sequence numbers associated with the messages in the batch.</span></span></param>
        <summary><span data-ttu-id="4bbe2-518">非同期的にメッセージのバッチを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-518">Asynchronously receives a message batch.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-519">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-519">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="queueClient.ReceiveBatchAsync messageCount" />
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
        <param name="messageCount"><span data-ttu-id="4bbe2-520">バッチに返されるメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-520">The number of messages to return in the batch.</span></span> <span data-ttu-id="4bbe2-521">これは、概算値よりも少ないまたは複数のメッセージとして<paramref name="messageCount" />返される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-521">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <summary><span data-ttu-id="4bbe2-522">非同期的にメッセージのバッチを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-522">Asynchronously receives a message batch.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-523">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-523">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ReceiveBatchAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer, serverWaitTime As TimeSpan) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="queueClient.ReceiveBatchAsync (messageCount, serverWaitTime)" />
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
        <param name="messageCount"><span data-ttu-id="4bbe2-524">バッチに返されるメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-524">The number of messages to return in the batch.</span></span> <span data-ttu-id="4bbe2-525">これは、概算値よりも少ないまたは複数のメッセージとして<paramref name="messageCount" />返される可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-525">As this is an approximation, fewer or more messages than <paramref name="messageCount" /> may be returned.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="4bbe2-526">サーバーがタイムアウトになる前に到着するメッセージのバッチを待機する時間間隔です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-526">The time span that the server will wait for the message batch to arrive before it times out.</span></span></param>
        <summary><span data-ttu-id="4bbe2-527">非同期的にメッセージのバッチを受け取ります。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-527">Asynchronously receives a message batch.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-528">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-528">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Type handlerType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandler(class System.Type handlerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandler(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handlerType As Type)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandler : Type -&gt; unit" Usage="queueClient.RegisterSessionHandler handlerType" />
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
        <param name="handlerType"><span data-ttu-id="4bbe2-529">ハンドラーの型。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-529">The handler type.</span></span></param>
        <summary><span data-ttu-id="4bbe2-530">特定の種類をセッション ハンドラーを登録します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-530">Registers the session handler with specific type.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Type handlerType, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandler(class System.Type handlerType, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandler(System.Type,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handlerType As Type, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandler : Type * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="queueClient.RegisterSessionHandler (handlerType, options)" />
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
        <param name="handlerType"><span data-ttu-id="4bbe2-531">ハンドラーの型。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-531">The handler type.</span></span></param>
        <param name="options"><span data-ttu-id="4bbe2-532">セッション ハンドラー オプション。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-532">The session handler options.</span></span></param>
        <summary><span data-ttu-id="4bbe2-533">特定の種類とハンドラー オプションを持つ、セッション ハンドラーを登録します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-533">Registers the session handler with specific type and handler options.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerAsync (Type handlerType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerAsync(class System.Type handlerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerAsync(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerAsync (handlerType As Type) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerAsync : Type -&gt; System.Threading.Tasks.Task" Usage="queueClient.RegisterSessionHandlerAsync handlerType" />
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
        <param name="handlerType"><span data-ttu-id="4bbe2-534">ハンドラーの型。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-534">The handler type.</span></span></param>
        <summary><span data-ttu-id="4bbe2-535">非同期的に特定の種類をセッション ハンドラーを登録します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-535">Asynchronously registers the session handler with specific type.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-536">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-536">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerAsync (Type handlerType, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerAsync(class System.Type handlerType, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerAsync(System.Type,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerAsync (handlerType As Type, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerAsync : Type * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="queueClient.RegisterSessionHandlerAsync (handlerType, options)" />
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
        <param name="handlerType"><span data-ttu-id="4bbe2-537">ハンドラーの型。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-537">The handler type.</span></span></param>
        <param name="options"><span data-ttu-id="4bbe2-538">セッション ハンドラー オプション。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-538">The session handler options.</span></span></param>
        <summary><span data-ttu-id="4bbe2-539">非同期的に特定の種類とハンドラー オプションを持つ、セッション ハンドラーを登録します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-539">Asynchronously registers the session handler with specific type and handler options.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-540">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-540">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactory">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandlerFactory (Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandlerFactory(class Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerFactory(Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandlerFactory (factory As IMessageSessionAsyncHandlerFactory, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactory : Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="queueClient.RegisterSessionHandlerFactory (factory, options)" />
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
        <param name="factory"><span data-ttu-id="4bbe2-541">登録するためにハンドラー ファクトリ。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-541">The handler factory to be registered.</span></span></param>
        <param name="options"><span data-ttu-id="4bbe2-542">ハンドラー オプション。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-542">The handler options.</span></span></param>
        <summary><span data-ttu-id="4bbe2-543">指定したオプションで、メッセージのセッション ハンドラー ファクトリを登録します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-543">Registers a message session handler factory with specified options.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactory">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandlerFactory (Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterSessionHandlerFactory(class Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerFactory(Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandlerFactory (factory As IMessageSessionHandlerFactory, options As SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactory : Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; unit" Usage="queueClient.RegisterSessionHandlerFactory (factory, options)" />
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
        <param name="factory"><span data-ttu-id="4bbe2-544">登録するためにハンドラー ファクトリ。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-544">The handler factory to be registered.</span></span></param>
        <param name="options"><span data-ttu-id="4bbe2-545">ハンドラー オプション。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-545">The handler options.</span></span></param>
        <summary><span data-ttu-id="4bbe2-546">指定したオプションで、メッセージのセッション ハンドラー ファクトリを登録します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-546">Registers a message session handler factory with specified options.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync (Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync(class Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerFactoryAsync(Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerFactoryAsync (factory As IMessageSessionAsyncHandlerFactory, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactoryAsync : Microsoft.ServiceBus.Messaging.IMessageSessionAsyncHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="queueClient.RegisterSessionHandlerFactoryAsync (factory, options)" />
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
        <param name="factory"><span data-ttu-id="4bbe2-547">登録するためにハンドラー ファクトリ。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-547">The handler factory to be registered.</span></span></param>
        <param name="options"><span data-ttu-id="4bbe2-548">ハンドラー オプション。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-548">The handler options.</span></span></param>
        <summary><span data-ttu-id="4bbe2-549">非同期的にメッセージのセッション ハンドラー ファクトリを登録します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-549">Asynchronously registers a message session handler factory.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-550">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-550">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandlerFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync (Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, Microsoft.ServiceBus.Messaging.SessionHandlerOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterSessionHandlerFactoryAsync(class Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory factory, class Microsoft.ServiceBus.Messaging.SessionHandlerOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RegisterSessionHandlerFactoryAsync(Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory,Microsoft.ServiceBus.Messaging.SessionHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterSessionHandlerFactoryAsync (factory As IMessageSessionHandlerFactory, options As SessionHandlerOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.RegisterSessionHandlerFactoryAsync : Microsoft.ServiceBus.Messaging.IMessageSessionHandlerFactory * Microsoft.ServiceBus.Messaging.SessionHandlerOptions -&gt; System.Threading.Tasks.Task" Usage="queueClient.RegisterSessionHandlerFactoryAsync (factory, options)" />
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
        <param name="factory"><span data-ttu-id="4bbe2-551">登録するためにハンドラー ファクトリ。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-551">The handler factory to be registered.</span></span></param>
        <param name="options"><span data-ttu-id="4bbe2-552">ハンドラー オプション。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-552">The handler options.</span></span></param>
        <summary><span data-ttu-id="4bbe2-553">非同期的にメッセージのセッション ハンドラー ファクトリを登録します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-553">Asynchronously registers a message session handler factory.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-554">非同期操作を表すタスク オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-554">The task object representing the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewMessageLock">
      <MemberSignature Language="C#" Value="public DateTime RenewMessageLock (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.DateTime RenewMessageLock(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RenewMessageLock(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewMessageLock (lockToken As Guid) As DateTime" />
      <MemberSignature Language="F#" Value="member this.RenewMessageLock : Guid -&gt; DateTime" Usage="queueClient.RenewMessageLock lockToken" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.RenewMessageLockAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewMessageLockAsync (lockToken As Guid) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RenewMessageLockAsync : Guid -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="queueClient.RenewMessageLockAsync lockToken" />
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
    <Member MemberName="ScheduleMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ScheduleMessageAsync (Microsoft.ServiceBus.Messaging.BrokeredMessage message, DateTimeOffset scheduleEnqueueTimeUtc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; ScheduleMessageAsync(class Microsoft.ServiceBus.Messaging.BrokeredMessage message, valuetype System.DateTimeOffset scheduleEnqueueTimeUtc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.ScheduleMessageAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage,System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Function ScheduleMessageAsync (message As BrokeredMessage, scheduleEnqueueTimeUtc As DateTimeOffset) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ScheduleMessageAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="queueClient.ScheduleMessageAsync (message, scheduleEnqueueTimeUtc)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
        <Parameter Name="scheduleEnqueueTimeUtc" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="4bbe2-555">スケジュールされるメッセージ</span><span class="sxs-lookup"><span data-stu-id="4bbe2-555">Message to be scheduled</span></span></param>
        <param name="scheduleEnqueueTimeUtc"><span data-ttu-id="4bbe2-556">エンキューの時刻</span><span class="sxs-lookup"><span data-stu-id="4bbe2-556">Time of enqueue</span></span></param>
        <summary>
            <span data-ttu-id="4bbe2-557">スケジュールされたメッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-557">Sends a scheduled message</span></span>
            </summary>
        <returns><span data-ttu-id="4bbe2-558">キャンセルするために必要なシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-558">Sequence number that is needed for cancelling.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Send">
      <MemberSignature Language="C#" Value="public void Send (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Send(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.Send(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Send (message As BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member Send : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit&#xA;override this.Send : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; unit" Usage="queueClient.Send message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.Send(Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="4bbe2-559">送信するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-559">The message to send.</span></span></param>
        <summary><span data-ttu-id="4bbe2-560">使用してメッセージを送信、<see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalSender" />です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-560">Sends a message using the <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalSender" />.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="4bbe2-561">操作がタイムアウトしたときにスローされます。タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />の値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-561">Thrown when operation times out. Timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if timeout value is relatively low.</span></span> </exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="4bbe2-562">場合にスローされる、<paramref name="message" />が null です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-562">Thrown when the <paramref name="message" /> is null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="4bbe2-563">送信操作をサポートしないように、トピック/サブスクリプションが指している場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-563">Thrown if the topic/subscription pointed to does not support the send operation.</span></span> <span data-ttu-id="4bbe2-564">つまり、配信不能キューはサポートしていませんは、操作を送信します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-564">That is, Deadletter queue does not support send operations.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="4bbe2-565">クライアントのエンティティを閉じているか、中止された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-565">Thrown if the client entity has been closed or aborted.</span></span></exception>
        <exception cref="T:System.UnauthorizedAccessException"><span data-ttu-id="4bbe2-566">I/O やセキュリティ エラーがある場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-566">Thrown if there is an I/O or security error.</span></span></exception>
        <exception cref="T:System.Runtime.Serialization.SerializationException"><span data-ttu-id="4bbe2-567">シリアル化または逆シリアル化中にエラーが発生した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-567">Thrown when an error occurs during serialization or deserialization.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException"><span data-ttu-id="4bbe2-568">キューが存在しない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-568">Thrown if the queue does not exist.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="4bbe2-569">メッセージングのエラーがある場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-569">Thrown if there is a messaging error.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.SendAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (message As BrokeredMessage) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; System.Threading.Tasks.Task" Usage="queueClient.SendAsync message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendAsync(Microsoft.ServiceBus.Messaging.BrokeredMessage)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="4bbe2-570">送信するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-570">The message to send.</span></span></param>
        <summary><span data-ttu-id="4bbe2-571">使用してメッセージを非同期的に送信、<see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalSender" />です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-571">Asynchronously sends a message using the <see cref="P:Microsoft.ServiceBus.Messaging.QueueClient.InternalSender" />.</span></span></summary>
        <returns><span data-ttu-id="4bbe2-572">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-572">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatch">
      <MemberSignature Language="C#" Value="public void SendBatch (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SendBatch(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub SendBatch (messages As IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit&#xA;override this.SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; unit" Usage="queueClient.SendBatch messages" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages"><span data-ttu-id="4bbe2-573">送信するための仲介型メッセージのコレクション。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-573">The collection of brokered messages to send.</span></span></param>
        <summary><span data-ttu-id="4bbe2-574">一連の (バッチ処理) の仲介型メッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-574">Sends a set of brokered messages (for batch processing).</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendBatchAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.QueueClient.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBatchAsync (messages As IEnumerable(Of BrokeredMessage)) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.SendBatchAsync messages" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageSender.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages"><span data-ttu-id="4bbe2-575">送信するための仲介型メッセージのコレクション。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-575">The collection of brokered messages to send.</span></span></param>
        <summary><span data-ttu-id="4bbe2-576">(バッチ処理) の仲介型メッセージのセットが非同期的に送信します。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-576">Asynchronously sends a set of brokered messages (for batch processing).</span></span></summary>
        <returns><span data-ttu-id="4bbe2-577">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="4bbe2-577">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>