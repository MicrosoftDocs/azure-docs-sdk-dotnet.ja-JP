<Type Name="MessageSession" FullName="Microsoft.ServiceBus.Messaging.MessageSession">
  <TypeSignature Language="C#" Value="public abstract class MessageSession : Microsoft.ServiceBus.Messaging.MessageReceiver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MessageSession extends Microsoft.ServiceBus.Messaging.MessageReceiver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessageSession" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MessageSession&#xA;Inherits MessageReceiver" />
  <TypeSignature Language="F#" Value="type MessageSession = class&#xA;    inherit MessageReceiver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.MessageReceiver</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="f4f25-101">1 つのトランザクションで処理するための関連メッセージのグループをできるメッセージ セッションを表します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-101">Represents a message session that allows grouping of related messages for processing in a single transaction.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetState">
      <MemberSignature Language="C#" Value="public System.IO.Stream GetState ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IO.Stream GetState() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.GetState" />
      <MemberSignature Language="VB.NET" Value="Public Function GetState () As Stream" />
      <MemberSignature Language="F#" Value="member this.GetState : unit -&gt; System.IO.Stream" Usage="messageSession.GetState " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="f4f25-102">メッセージ セッションの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-102">Gets the state of the message session.</span></span></summary>
        <returns><span data-ttu-id="f4f25-103">元の状態情報が永続化されるストリーム。</span><span class="sxs-lookup"><span data-stu-id="f4f25-103">The stream from which the state information is persisted.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.IO.Stream&gt; GetStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; GetStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.GetStateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetStateAsync () As Task(Of Stream)" />
      <MemberSignature Language="F#" Value="member this.GetStateAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="messageSession.GetStateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="f4f25-104">非同期的にメッセージ セッションの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-104">Asynchronously gets the state of the message session.</span></span></summary>
        <returns><span data-ttu-id="f4f25-105">元の状態情報が永続化されるストリーム。</span><span class="sxs-lookup"><span data-stu-id="f4f25-105">The stream from which the state information is persisted.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsExclusiveMode">
      <MemberSignature Language="C#" Value="public bool IsExclusiveMode { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsExclusiveMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.IsExclusiveMode" />
      <MemberSignature Language="VB.NET" Value="Public Property IsExclusiveMode As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsExclusiveMode : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.IsExclusiveMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastPeekedSequenceNumber">
      <MemberSignature Language="C#" Value="public override long LastPeekedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastPeekedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.LastPeekedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property LastPeekedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastPeekedSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.MessageSession.LastPeekedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f4f25-106">取得またはセッションで最後のピークのシーケンス番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-106">Gets or sets the last peeked sequence number in the session.</span></span></summary>
        <value><span data-ttu-id="f4f25-107">セッションの最後のピークのシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="f4f25-107">The last peeked sequence number in the session.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f4f25-108">取得または日付と時刻をメッセージのセッションがロック解除を設定します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-108">Gets or sets the date and time at which the message session is unlocked.</span></span></summary>
        <value><span data-ttu-id="f4f25-109">日付とロックするメッセージ セッションの時間。</span><span class="sxs-lookup"><span data-stu-id="f4f25-109">The date and time for the message session to be locked.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; LockToken { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public Property LockToken As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.LockToken : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value><span data-ttu-id="f4f25-110">ロック トークン</span><span class="sxs-lookup"><span data-stu-id="f4f25-110">The lock token</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbandon">
      <MemberSignature Language="C#" Value="protected override void OnAbandon (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbandon(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnAbandon(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit" Usage="messageSession.OnAbandon (trackingContext, lockTokens, propertiesToModify, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="f4f25-111">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-111">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="f4f25-112">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="f4f25-112">The lock tokens.</span></span> </param>
        <param name="propertiesToModify"></param>
        <param name="timeout"> <span data-ttu-id="f4f25-113">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f4f25-113">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="f4f25-114">ピークを排除には、メッセージがロックされています。</span><span class="sxs-lookup"><span data-stu-id="f4f25-114">Abandons a peek locked message.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="messageSession.OnAbort " />
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
        <summary><span data-ttu-id="f4f25-115">メッセージ セッションを中止します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-115">Aborts the message session.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAbandon">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginAbandon (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginAbandon(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginAbandon(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginAbandon (trackingContext, lockTokens, propertiesToModify, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"></param>
        <param name="lockTokens"> <span data-ttu-id="f4f25-116">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="f4f25-116">The lock tokens.</span></span> </param>
        <param name="propertiesToModify"> <span data-ttu-id="f4f25-117">電話放棄呼アクションを追加するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="f4f25-117">The properties to add for the abandon action.</span></span></param>
        <param name="fromSync"></param>
        <param name="timeout">    <span data-ttu-id="f4f25-118">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f4f25-118">The timeout.</span></span> </param>
        <param name="callback">   <span data-ttu-id="f4f25-119">コールバック。</span><span class="sxs-lookup"><span data-stu-id="f4f25-119">The callback.</span></span> </param>
        <param name="state">      <span data-ttu-id="f4f25-120">状態。</span><span class="sxs-lookup"><span data-stu-id="f4f25-120">The state.</span></span> </param>
        <summary>
            <span data-ttu-id="f4f25-121">Begin 破棄アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-121">Executes the begin abandon action.</span></span> 
            </summary>
        <returns> <span data-ttu-id="f4f25-122">が必要です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-122">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginClose (timeout, callback, state)" />
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
        <param name="timeout"><span data-ttu-id="f4f25-123">操作がタイムアウトまでの待機間隔を時間にわたっています。</span><span class="sxs-lookup"><span data-stu-id="f4f25-123">The time span interval the operation waits before it times out.</span></span></param>
        <param name="callback"><span data-ttu-id="f4f25-124">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="f4f25-124">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="f4f25-125">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4f25-125">A user-defined object that contains state information about the asynchronous operation.</span></span> </param>
        <summary><span data-ttu-id="f4f25-126">メッセージ セッションの通信オブジェクトを終了する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-126">Begins an asynchronous operation to close the communication object for the message session.</span></span></summary>
        <returns><span data-ttu-id="f4f25-127"><see cref="T:System.IAsyncResult" />メッセージ セッションの通信オブジェクトを閉じる非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-127">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to close the communication object for the message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginComplete">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt; deliveryTags, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; deliveryTags, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.ArraySegment{System.Byte}},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;ArraySegment&lt;byte&gt;&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginComplete (trackingContext, deliveryTags, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="deliveryTags" Type="System.Collections.Generic.IEnumerable&lt;System.ArraySegment&lt;System.Byte&gt;&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="f4f25-128">この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="f4f25-128">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="deliveryTags"> <span data-ttu-id="f4f25-129">配信のタグのコレクション。</span><span class="sxs-lookup"><span data-stu-id="f4f25-129">A collection of delivery tags.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="f4f25-130">同期の開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-130">The start of the synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="f4f25-131">操作がタイムアウトまでの待機間隔を時間にわたっています。</span><span class="sxs-lookup"><span data-stu-id="f4f25-131">The time span interval the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="f4f25-132">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="f4f25-132">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="f4f25-133">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4f25-133">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="f4f25-134">OnComplete または BeginComplete 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-134">Executes upon calling the OnComplete or BeginComplete operation.</span></span></summary>
        <returns><span data-ttu-id="f4f25-135"><see cref="T:System.IAsyncResult" />メッセージ セッションの通信オブジェクトを閉じる非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-135">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to close the communication object for the message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginComplete">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginComplete (trackingContext, lockTokens, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="f4f25-136">この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="f4f25-136">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="f4f25-137">ロックのトークンのコレクションはロックされているメッセージ インスタンスにバインドされます。</span><span class="sxs-lookup"><span data-stu-id="f4f25-137">The collection of lock tokens bound to the locked message instances.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="f4f25-138">同期の開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-138">The start of the synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="f4f25-139">操作がタイムアウトまでの待機間隔を時間にわたっています。</span><span class="sxs-lookup"><span data-stu-id="f4f25-139">The time span interval the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="f4f25-140">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="f4f25-140">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="f4f25-141">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4f25-141">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="f4f25-142">OnComplete または BeginComplete 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-142">Executes upon calling the OnComplete or BeginComplete operation.</span></span></summary>
        <returns><span data-ttu-id="f4f25-143"><see cref="T:System.IAsyncResult" />メッセージ セッションの通信オブジェクトを閉じる非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-143">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to close the communication object for the message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginDeadLetter">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginDeadLetter (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginDeadLetter(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginDeadLetter(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginDeadLetter (trackingContext, lockTokens, propertiesToModify, deadLetterReason, deadLetterErrorDescription, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="f4f25-144">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-144">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="f4f25-145">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="f4f25-145">The lock tokens.</span></span> </param>
        <param name="propertiesToModify"> <span data-ttu-id="f4f25-146">メッセージを変更するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="f4f25-146">message properties to modify.</span></span> </param>
        <param name="deadLetterReason">  <span data-ttu-id="f4f25-147">メッセージの配信不能の理由です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-147">The reason for deadlettering the message.</span></span> </param>
        <param name="deadLetterErrorDescription">  <span data-ttu-id="f4f25-148">メッセージの配信不能の説明情報。</span><span class="sxs-lookup"><span data-stu-id="f4f25-148">The description information for deadlettering the message.</span></span> </param>
        <param name="fromSync"> <span data-ttu-id="f4f25-149">この場合は true、同期メソッドから呼び出されました。</span><span class="sxs-lookup"><span data-stu-id="f4f25-149">true if this was called from a sync method.</span></span></param>
        <param name="timeout">    <span data-ttu-id="f4f25-150">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f4f25-150">The timeout.</span></span> </param>
        <param name="callback">   <span data-ttu-id="f4f25-151">コールバック。</span><span class="sxs-lookup"><span data-stu-id="f4f25-151">The callback.</span></span> </param>
        <param name="state">      <span data-ttu-id="f4f25-152">状態。</span><span class="sxs-lookup"><span data-stu-id="f4f25-152">The state.</span></span> </param>
        <summary> <span data-ttu-id="f4f25-153">配信不能メッセージ キューの操作を開始移動を実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-153">Executes the begin move to dead letter queue action.</span></span> </summary>
        <returns> <span data-ttu-id="f4f25-154">が必要です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-154">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginDefer">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginDefer (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginDefer(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginDefer(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginDefer (trackingContext, lockTokens, propertiesToModify, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="f4f25-155">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-155">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="f4f25-156">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="f4f25-156">The lock tokens.</span></span> </param>
        <param name="propertiesToModify"> <span data-ttu-id="f4f25-157">メッセージを変更するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="f4f25-157">message properties to modify.</span></span> </param>
        <param name="fromSync"></param>
        <param name="timeout">    <span data-ttu-id="f4f25-158">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f4f25-158">The timeout.</span></span> </param>
        <param name="callback">   <span data-ttu-id="f4f25-159">コールバック。</span><span class="sxs-lookup"><span data-stu-id="f4f25-159">The callback.</span></span> </param>
        <param name="state">      <span data-ttu-id="f4f25-160">状態。</span><span class="sxs-lookup"><span data-stu-id="f4f25-160">The state.</span></span> </param>
        <summary> <span data-ttu-id="f4f25-161">実行開始アクションを延期します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-161">Executes the begin defer action.</span></span> </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginGetState">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginGetState (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginGetState(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginGetState(Microsoft.ServiceBus.Tracing.TrackingContext,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginGetState : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginGetState (trackingContext, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">  <span data-ttu-id="f4f25-162">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-162">The TrackingContext to use.</span></span> </param>
        <param name="timeout">  <span data-ttu-id="f4f25-163">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f4f25-163">The timeout.</span></span> </param>
        <param name="callback"> <span data-ttu-id="f4f25-164">コールバック。</span><span class="sxs-lookup"><span data-stu-id="f4f25-164">The callback.</span></span> </param>
        <param name="state">    <span data-ttu-id="f4f25-165">状態。</span><span class="sxs-lookup"><span data-stu-id="f4f25-165">The state.</span></span> </param>
        <summary> <span data-ttu-id="f4f25-166">Begin get 状態アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-166">Executes the begin get state action.</span></span> </summary>
        <returns> <span data-ttu-id="f4f25-167">が必要です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-167">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginOpen">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginOpen (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginOpen(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginOpen(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginOpen (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginOpen : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginOpen (timeout, callback, state)" />
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
        <param name="timeout"><span data-ttu-id="f4f25-168">操作がタイムアウトまでの待機間隔を時間にわたっています。</span><span class="sxs-lookup"><span data-stu-id="f4f25-168">The time span interval the operation waits before it times out.</span></span></param>
        <param name="callback"><span data-ttu-id="f4f25-169">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="f4f25-169">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="f4f25-170">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4f25-170">A user-defined object that contains state information about the asynchronous operation.</span></span> </param>
        <summary><span data-ttu-id="f4f25-171">メッセージの受信者の OnOpen 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-171">Executes upon calling the OnOpen operation of the message receiver.</span></span></summary>
        <returns><span data-ttu-id="f4f25-172"><see cref="T:System.IAsyncResult" />メッセージ セッションの通信オブジェクトを開く非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-172">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to open a communication object for the message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginPeek">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginPeek (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, long fromSequenceNumber, int messageCount, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginPeek(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int64 fromSequenceNumber, int32 messageCount, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginPeek(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int64,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginPeek : Microsoft.ServiceBus.Tracing.TrackingContext * int64 * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginPeek (trackingContext, fromSequenceNumber, messageCount, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="f4f25-173">この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="f4f25-173">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="fromSequenceNumber"> <span data-ttu-id="f4f25-174">セッションから表示するシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="f4f25-174">The sequence number to peek from the session.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="f4f25-175">操作でメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f4f25-175">The number of message in the operation.</span></span></param>
        <param name="timeout"> <span data-ttu-id="f4f25-176">操作がタイムアウトまでの待機間隔を時間にわたっています。</span><span class="sxs-lookup"><span data-stu-id="f4f25-176">The time span interval the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="f4f25-177">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="f4f25-177">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="f4f25-178">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4f25-178">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="f4f25-179">OnPeek または BeginPeek の操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-179">Executes upon calling the OnPeek or BeginPeek operation.</span></span></summary>
        <returns><span data-ttu-id="f4f25-180"><see cref="T:System.IAsyncResult" />メッセージ セッションの通信をピークする非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-180">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to peek a communication of the message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRenewLock">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginRenewLock (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginRenewLock(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginRenewLock(Microsoft.ServiceBus.Tracing.TrackingContext,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginRenewLock : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginRenewLock (trackingContext, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="f4f25-181">この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="f4f25-181">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="timeout"> <span data-ttu-id="f4f25-182">操作がタイムアウトまでの待機間隔を時間にわたっています。</span><span class="sxs-lookup"><span data-stu-id="f4f25-182">The time span interval the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="f4f25-183">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="f4f25-183">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="f4f25-184">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4f25-184">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="f4f25-185">RenewLock または BeginRenewLock 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-185">Executes upon calling the RenewLock or BeginRenewLock operation.</span></span></summary>
        <returns><span data-ttu-id="f4f25-186"><see cref="T:System.IAsyncResult" />操作の状態を取得する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-186">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to get the state of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginRenewMessageLocks (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginRenewMessageLocks(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginRenewMessageLocks(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginRenewMessageLocks : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginRenewMessageLocks (trackingContext, lockTokens, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="f4f25-187">この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="f4f25-187">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="f4f25-188">ロックのトークンのコレクションはロックされているメッセージ インスタンスにバインドされます。</span><span class="sxs-lookup"><span data-stu-id="f4f25-188">The collection of lock tokens bound to the locked message instances.</span></span></param>
        <param name="fromSync"> <span data-ttu-id="f4f25-189">同期の開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-189">The start of the synchronization.</span></span></param>
        <param name="timeout"> <span data-ttu-id="f4f25-190">時間間隔、操作は、タイムアウトになるまで待機します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-190">The time span the operation waits before it times out.</span></span></param>
        <param name="callback"> <span data-ttu-id="f4f25-191">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="f4f25-191">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"> <span data-ttu-id="f4f25-192">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f4f25-192">A user-defined object that contains state information about the asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="f4f25-193">メッセージのロックの OnBegin 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-193">Executes upon calling the OnBegin operation for lock messages.</span></span></summary>
        <returns><span data-ttu-id="f4f25-194"><see cref="T:System.IAsyncResult" />ロック メッセージの処理を更新する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-194">An<see cref="T:System.IAsyncResult" /> that references the asynchronous operation to renew processing of lock messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginSetState">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginSetState (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.IO.Stream sessionState, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginSetState(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.IO.Stream sessionState, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginSetState(Microsoft.ServiceBus.Tracing.TrackingContext,System.IO.Stream,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginSetState : Microsoft.ServiceBus.Tracing.TrackingContext * System.IO.Stream * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginSetState (trackingContext, sessionState, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="sessionState" Type="System.IO.Stream" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">  <span data-ttu-id="f4f25-195">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-195">The TrackingContext to use.</span></span> </param>
        <param name="sessionState">   <span data-ttu-id="f4f25-196">状態。</span><span class="sxs-lookup"><span data-stu-id="f4f25-196">The state.</span></span> </param>
        <param name="timeout">  <span data-ttu-id="f4f25-197">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f4f25-197">The timeout.</span></span> </param>
        <param name="callback"> <span data-ttu-id="f4f25-198">コールバック。</span><span class="sxs-lookup"><span data-stu-id="f4f25-198">The callback.</span></span> </param>
        <param name="state">    <span data-ttu-id="f4f25-199">状態。</span><span class="sxs-lookup"><span data-stu-id="f4f25-199">The state.</span></span> </param>
        <summary> <span data-ttu-id="f4f25-200">開始状態の設定のアクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-200">Executes the begin set state action.</span></span> </summary>
        <returns> <span data-ttu-id="f4f25-201">が必要です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-201">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;long&gt; receipts, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;int64&gt; receipts, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Int64},System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginTryReceive (trackingContext, receipts, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="receipts" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="f4f25-202">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-202">TrackingContext to use.</span></span></param>
        <param name="receipts"> <span data-ttu-id="f4f25-203">配信確認メッセージ。</span><span class="sxs-lookup"><span data-stu-id="f4f25-203">The receipts.</span></span> </param>
        <param name="timeout">  <span data-ttu-id="f4f25-204">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f4f25-204">The timeout.</span></span> </param>
        <param name="callback"> <span data-ttu-id="f4f25-205">コールバック。</span><span class="sxs-lookup"><span data-stu-id="f4f25-205">The callback.</span></span> </param>
        <param name="state">    <span data-ttu-id="f4f25-206">状態。</span><span class="sxs-lookup"><span data-stu-id="f4f25-206">The state.</span></span> </param>
        <summary> <span data-ttu-id="f4f25-207">Begin try を実行するアクションを受信します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-207">Executes the begin try receive action.</span></span> </summary>
        <returns> <span data-ttu-id="f4f25-208">が必要です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-208">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginTryReceive (trackingContext, messageCount, serverWaitTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="f4f25-209">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-209">TrackingContext to use.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="f4f25-210">メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f4f25-210">Number of messages.</span></span> </param>
        <param name="serverWaitTime"> <span data-ttu-id="f4f25-211">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f4f25-211">The timeout.</span></span> </param>
        <param name="callback">     <span data-ttu-id="f4f25-212">コールバック。</span><span class="sxs-lookup"><span data-stu-id="f4f25-212">The callback.</span></span> </param>
        <param name="state">        <span data-ttu-id="f4f25-213">状態。</span><span class="sxs-lookup"><span data-stu-id="f4f25-213">The state.</span></span> </param>
        <summary> <span data-ttu-id="f4f25-214">Begin try を実行するアクションを受信します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-214">Executes the begin try receive action.</span></span> </summary>
        <returns> <span data-ttu-id="f4f25-215">が必要です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-215">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive2">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginTryReceive2 (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginTryReceive2(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnBeginTryReceive2(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="override this.OnBeginTryReceive2 : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageSession.OnBeginTryReceive2 (trackingContext, messageCount, serverWaitTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="f4f25-216">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-216">TrackingContext to use.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="f4f25-217">メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f4f25-217">Number of messages.</span></span> </param>
        <param name="serverWaitTime"> <span data-ttu-id="f4f25-218">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f4f25-218">The timeout.</span></span> </param>
        <param name="callback">     <span data-ttu-id="f4f25-219">コールバック。</span><span class="sxs-lookup"><span data-stu-id="f4f25-219">The callback.</span></span> </param>
        <param name="state">        <span data-ttu-id="f4f25-220">状態。</span><span class="sxs-lookup"><span data-stu-id="f4f25-220">The state.</span></span> </param>
        <summary> <span data-ttu-id="f4f25-221">Begin try を実行するアクションを受信します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-221">Executes the begin try receive action.</span></span> </summary>
        <returns> <span data-ttu-id="f4f25-222">が必要です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-222">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnComplete">
      <MemberSignature Language="C#" Value="protected override void OnComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * TimeSpan -&gt; unit" Usage="messageSession.OnComplete (trackingContext, lockTokens, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="f4f25-223">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-223">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="f4f25-224">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="f4f25-224">The lock tokens.</span></span> </param>
        <param name="timeout"> <span data-ttu-id="f4f25-225">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f4f25-225">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="f4f25-226">ピーク ロックされているメッセージを完了します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-226">Completes a peek locked message.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeadLetter">
      <MemberSignature Language="C#" Value="protected override void OnDeadLetter (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnDeadLetter(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnDeadLetter(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * TimeSpan -&gt; unit" Usage="messageSession.OnDeadLetter (trackingContext, lockTokens, propertiesToModify, deadLetterReason, deadLetterErrorDescription, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">To be added.</param>
        <param name="lockTokens">To be added.</param>
        <param name="propertiesToModify">To be added.</param>
        <param name="deadLetterReason">To be added.</param>
        <param name="deadLetterErrorDescription">To be added.</param>
        <param name="timeout">To be added.</param>
        <summary> <span data-ttu-id="f4f25-227">配信不能キューにメッセージを移動します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-227">Moves a message to the dead letter queue.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDefer">
      <MemberSignature Language="C#" Value="protected override void OnDefer (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnDefer(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnDefer(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit" Usage="messageSession.OnDefer (trackingContext, lockTokens, propertiesToModify, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="f4f25-228">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-228">TrackingContext to use.</span></span></param>
        <param name="lockTokens"> <span data-ttu-id="f4f25-229">ロック トークン。</span><span class="sxs-lookup"><span data-stu-id="f4f25-229">The lock tokens.</span></span> </param>
        <param name="propertiesToModify"> <span data-ttu-id="f4f25-230">メッセージを変更するプロパティです。</span><span class="sxs-lookup"><span data-stu-id="f4f25-230">message properties to modify.</span></span> </param>
        <param name="timeout">    <span data-ttu-id="f4f25-231">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f4f25-231">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="f4f25-232">メッセージを延期します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-232">Defers a message.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAbandon">
      <MemberSignature Language="C#" Value="protected override void OnEndAbandon (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndAbandon(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndAbandon(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndAbandon (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndAbandon : IAsyncResult -&gt; unit" Usage="messageSession.OnEndAbandon result" />
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
        <param name="result"><span data-ttu-id="f4f25-233"><see cref="T:System.IAsyncResult" />メッセージを破棄し、そのロックを解放する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-233">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to abandon the messages and relinquish its lock.</span></span></param>
        <summary><span data-ttu-id="f4f25-234">メッセージを破棄し、そのロックを解放する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-234">Ends an asynchronous operation to abandon the message and relinquish its lock.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="messageSession.OnEndClose result" />
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
        <param name="result"><span data-ttu-id="f4f25-235"><see cref="T:System.IAsyncResult" />メッセージ セッションの通信オブジェクトを閉じる非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-235">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to close the communication object for the message session.</span></span></param>
        <summary><span data-ttu-id="f4f25-236">メッセージ セッションの通信オブジェクトを終了する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-236">Ends an asynchronous operation to close the communication object for the message session.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndComplete">
      <MemberSignature Language="C#" Value="protected override void OnEndComplete (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndComplete(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndComplete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndComplete (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndComplete : IAsyncResult -&gt; unit" Usage="messageSession.OnEndComplete result" />
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
        <param name="result"><span data-ttu-id="f4f25-237"><see cref="T:System.IAsyncResult" />メッセージの受信を完了する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-237">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to complete receiving of messages.</span></span></param>
        <summary><span data-ttu-id="f4f25-238">メッセージの受信者の完了操作の終了を実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-238">Executes the end complete operation of the message receiver.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndDeadLetter">
      <MemberSignature Language="C#" Value="protected override void OnEndDeadLetter (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndDeadLetter(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndDeadLetter(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndDeadLetter (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndDeadLetter : IAsyncResult -&gt; unit" Usage="messageSession.OnEndDeadLetter result" />
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
        <param name="result"><span data-ttu-id="f4f25-239"><see cref="T:System.IAsyncResult" />配信不能キューに配信不能メッセージを移動する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-239">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to move undelivered messages to the deadletter queue.</span></span></param>
        <summary><span data-ttu-id="f4f25-240">メッセージ受信側の配信不能操作の終了を実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-240">Executes the end deadletter operation of the message receiver.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndDefer">
      <MemberSignature Language="C#" Value="protected override void OnEndDefer (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndDefer(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndDefer(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndDefer (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndDefer : IAsyncResult -&gt; unit" Usage="messageSession.OnEndDefer result" />
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
        <param name="result"><span data-ttu-id="f4f25-241"><see cref="T:System.IAsyncResult" />メッセージの処理を中断する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-241">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to suspend processing of messages.</span></span></param>
        <summary><span data-ttu-id="f4f25-242">最後の実行、メッセージ受信側の操作の保留します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-242">Executes the end defer operation of the message receiver.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndGetState">
      <MemberSignature Language="C#" Value="protected abstract System.IO.Stream OnEndGetState (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IO.Stream OnEndGetState(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndGetState(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndGetState (result As IAsyncResult) As Stream" />
      <MemberSignature Language="F#" Value="abstract member OnEndGetState : IAsyncResult -&gt; System.IO.Stream" Usage="messageSession.OnEndGetState result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="f4f25-243"><see cref="T:System.IAsyncResult" />メッセージ セッションの状態を取得する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-243">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to get the state of the message session.</span></span></param>
        <summary><span data-ttu-id="f4f25-244">OnGetState または EndGetState 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-244">Executes upon calling the OnGetState or EndGetState operation.</span></span></summary>
        <returns><span data-ttu-id="f4f25-245">元の状態情報が永続化されるストリーム。</span><span class="sxs-lookup"><span data-stu-id="f4f25-245">The stream from which the state information is persisted.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndOpen">
      <MemberSignature Language="C#" Value="protected override void OnEndOpen (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndOpen(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndOpen(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndOpen (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndOpen : IAsyncResult -&gt; unit" Usage="messageSession.OnEndOpen result" />
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
        <param name="result"><span data-ttu-id="f4f25-246"><see cref="T:System.IAsyncResult" />メッセージ セッションの通信オブジェクトを開く非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-246">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to open a communication object for the message session.</span></span></param>
        <summary><span data-ttu-id="f4f25-247">メッセージ セッションの通信オブジェクトを開く非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-247">Ends the asynchronous operation to open a communication object for the message session.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndPeek">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnEndPeek (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnEndPeek(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndPeek(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndPeek (result As IAsyncResult) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="override this.OnEndPeek : IAsyncResult -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageSession.OnEndPeek result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="f4f25-248"><see cref="T:System.IAsyncResult" />メッセージ セッションの通信をピークする非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-248">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to peek a communication of the message session.</span></span></param>
        <summary><span data-ttu-id="f4f25-249">EndPeek 操作の呼び出し時に実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-249">Executes upon calling the EndPeek operation.</span></span></summary>
        <returns><span data-ttu-id="f4f25-250">セッションからのメッセージの一覧。</span><span class="sxs-lookup"><span data-stu-id="f4f25-250">The list of message from the session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRenewLock">
      <MemberSignature Language="C#" Value="protected abstract DateTime OnEndRenewLock (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance valuetype System.DateTime OnEndRenewLock(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndRenewLock(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndRenewLock (result As IAsyncResult) As DateTime" />
      <MemberSignature Language="F#" Value="abstract member OnEndRenewLock : IAsyncResult -&gt; DateTime" Usage="messageSession.OnEndRenewLock result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="f4f25-251"><see cref="T:System.IAsyncResult" />メッセージ セッションの状態を取得する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-251">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to get the state of the message session.</span></span></param>
        <summary><span data-ttu-id="f4f25-252">メッセージの受信者の EndRenewLock 操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-252">Executes the EndRenewLock operation of the message receiver.</span></span></summary>
        <returns><span data-ttu-id="f4f25-253">日付とロックの更新の終了時刻。</span><span class="sxs-lookup"><span data-stu-id="f4f25-253">The date and time when the renewal of lock ends.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;DateTime&gt; OnEndRenewMessageLocks (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;valuetype System.DateTime&gt; OnEndRenewMessageLocks(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndRenewMessageLocks(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndRenewMessageLocks (result As IAsyncResult) As IEnumerable(Of DateTime)" />
      <MemberSignature Language="F#" Value="override this.OnEndRenewMessageLocks : IAsyncResult -&gt; seq&lt;DateTime&gt;" Usage="messageSession.OnEndRenewMessageLocks result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="f4f25-254">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="f4f25-254">The result of the operation.</span></span></param>
        <summary><span data-ttu-id="f4f25-255">メッセージ ロック EndRenew アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-255">Executes the EndRenew action for message locks.</span></span></summary>
        <returns><span data-ttu-id="f4f25-256"><see cref="T:System.Collections.Generic.IEnumerable`1" />ロックされたメッセージの.</span><span class="sxs-lookup"><span data-stu-id="f4f25-256">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> of locked messages..</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndSetState">
      <MemberSignature Language="C#" Value="protected abstract void OnEndSetState (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndSetState(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndSetState(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndSetState (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndSetState : IAsyncResult -&gt; unit" Usage="messageSession.OnEndSetState result" />
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
        <param name="result"><span data-ttu-id="f4f25-257"><see cref="T:System.IAsyncResult" />メッセージ セッションの状態を設定する非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-257">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to set the state of the message session.</span></span></param>
        <summary><span data-ttu-id="f4f25-258">メッセージ セッションの状態を設定する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-258">Ends the asynchronous operation to set the state of the message session.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceive">
      <MemberSignature Language="C#" Value="protected override bool OnEndTryReceive (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnEndTryReceive(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndTryReceive(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndTryReceive (result As IAsyncResult, ByRef messages As IEnumerable(Of BrokeredMessage)) As Boolean" />
      <MemberSignature Language="F#" Value="override this.OnEndTryReceive : IAsyncResult *  -&gt; bool" Usage="messageSession.OnEndTryReceive (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="f4f25-259"><see cref="T:System.IAsyncResult" />メッセージを受信しようとする非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-259">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to try to receive messages.</span></span></param>
        <param name="messages"><span data-ttu-id="f4f25-260">このメソッドが戻るときに、受信したメッセージのコレクションが含まれています。</span><span class="sxs-lookup"><span data-stu-id="f4f25-260">When this method returns, contains the received message collection.</span></span></param>
        <summary><span data-ttu-id="f4f25-261">最後に実行される受信メッセージの受信側の操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="f4f25-261">Executes the end try receive operation of the message receiver.</span></span></summary>
        <returns><span data-ttu-id="f4f25-262">これが成功した場合は true。失敗した場合は false。</span><span class="sxs-lookup"><span data-stu-id="f4f25-262">true if it succeeds; false if it fails.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceive2">
      <MemberSignature Language="C#" Value="protected override bool OnEndTryReceive2 (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnEndTryReceive2(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnEndTryReceive2(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnEndTryReceive2 (result As IAsyncResult, ByRef messages As IEnumerable(Of BrokeredMessage)) As Boolean" />
      <MemberSignature Language="F#" Value="override this.OnEndTryReceive2 : IAsyncResult *  -&gt; bool" Usage="messageSession.OnEndTryReceive2 (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="f4f25-263"><see cref="T:System.IAsyncResult" />メッセージを受信しようとする非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-263">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation to try to receive messages.</span></span></param>
        <param name="messages"><span data-ttu-id="f4f25-264">このメソッドが戻るときに、受信したメッセージのコレクションが含まれています。</span><span class="sxs-lookup"><span data-stu-id="f4f25-264">When this method returns, contains the received message collection.</span></span></param>
        <summary><span data-ttu-id="f4f25-265">最後に実行される受信メッセージの受信側の操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="f4f25-265">Executes the end try receive operation of the message receiver.</span></span></summary>
        <returns><span data-ttu-id="f4f25-266">これが成功した場合は true。失敗した場合は false。</span><span class="sxs-lookup"><span data-stu-id="f4f25-266">true if it succeeds; false if it fails.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnGetState">
      <MemberSignature Language="C#" Value="protected virtual System.IO.Stream OnGetState (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IO.Stream OnGetState(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnGetState(Microsoft.ServiceBus.Tracing.TrackingContext,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnGetState : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan -&gt; System.IO.Stream&#xA;override this.OnGetState : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan -&gt; System.IO.Stream" Usage="messageSession.OnGetState (trackingContext, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">  <span data-ttu-id="f4f25-267">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-267">The TrackingContext to use.</span></span> </param>
        <param name="timeout"> <span data-ttu-id="f4f25-268">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f4f25-268">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="f4f25-269">Get 状態アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-269">Executes the get state action.</span></span> </summary>
        <returns> <span data-ttu-id="f4f25-270">が必要です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-270">.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRenewLock">
      <MemberSignature Language="C#" Value="protected virtual DateTime OnRenewLock (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance valuetype System.DateTime OnRenewLock(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnRenewLock(Microsoft.ServiceBus.Tracing.TrackingContext,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnRenewLock : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan -&gt; DateTime&#xA;override this.OnRenewLock : Microsoft.ServiceBus.Tracing.TrackingContext * TimeSpan -&gt; DateTime" Usage="messageSession.OnRenewLock (trackingContext, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> <span data-ttu-id="f4f25-271">この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="f4f25-271">The context information associated by a transaction tracking this operation.</span></span></param>
        <param name="timeout"> <span data-ttu-id="f4f25-272">操作がタイムアウトまでの待機間隔を時間にわたっています。</span><span class="sxs-lookup"><span data-stu-id="f4f25-272">The time span interval the operation waits before it times out.</span></span></param>
        <summary><span data-ttu-id="f4f25-273">メッセージ ロック RenewLock アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-273">Executes the RenewLock action for message locks.</span></span></summary>
        <returns><span data-ttu-id="f4f25-274">時間間隔、操作は、タイムアウトになるまで待機します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-274">The time span the operation waits before it times out.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnSetState">
      <MemberSignature Language="C#" Value="protected virtual void OnSetState (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.IO.Stream stream, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnSetState(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.IO.Stream stream, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnSetState(Microsoft.ServiceBus.Tracing.TrackingContext,System.IO.Stream,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnSetState : Microsoft.ServiceBus.Tracing.TrackingContext * System.IO.Stream * TimeSpan -&gt; unit&#xA;override this.OnSetState : Microsoft.ServiceBus.Tracing.TrackingContext * System.IO.Stream * TimeSpan -&gt; unit" Usage="messageSession.OnSetState (trackingContext, stream, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="stream" Type="System.IO.Stream" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">  <span data-ttu-id="f4f25-275">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-275">The TrackingContext to use.</span></span> </param>
        <param name="stream">  <span data-ttu-id="f4f25-276">ストリーム。</span><span class="sxs-lookup"><span data-stu-id="f4f25-276">The stream.</span></span> </param>
        <param name="timeout"> <span data-ttu-id="f4f25-277">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f4f25-277">The timeout.</span></span> </param>
        <summary> <span data-ttu-id="f4f25-278">状態の設定アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-278">Executes the set state action.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTryReceive">
      <MemberSignature Language="C#" Value="protected override bool OnTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;long&gt; receipts, TimeSpan timeout, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;int64&gt; receipts, valuetype System.TimeSpan timeout, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Int64},System.TimeSpan,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="F#" Value="override this.OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan *  -&gt; bool" Usage="messageSession.OnTryReceive (trackingContext, receipts, timeout, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="receipts" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="f4f25-279">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-279">TrackingContext to use.</span></span></param>
        <param name="receipts"> <span data-ttu-id="f4f25-280">配信確認メッセージ。</span><span class="sxs-lookup"><span data-stu-id="f4f25-280">The receipts.</span></span> </param>
        <param name="timeout">  <span data-ttu-id="f4f25-281">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f4f25-281">The timeout.</span></span> </param>
        <param name="messages"> <span data-ttu-id="f4f25-282">出力メッセージ (送信)</span><span class="sxs-lookup"><span data-stu-id="f4f25-282">the output message (out)</span></span></param>
        <summary> <span data-ttu-id="f4f25-283">再試行を実行するアクションを受信します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-283">Executes the try receive action.</span></span> </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTryReceive">
      <MemberSignature Language="C#" Value="protected override bool OnTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.OnTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="F#" Value="override this.OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan *  -&gt; bool" Usage="messageSession.OnTryReceive (trackingContext, messageCount, serverWaitTime, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="trackingContext"><span data-ttu-id="f4f25-284">使用する TrackingContext です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-284">TrackingContext to use.</span></span></param>
        <param name="messageCount"> <span data-ttu-id="f4f25-285">メッセージ数。</span><span class="sxs-lookup"><span data-stu-id="f4f25-285">The number of messages.</span></span> </param>
        <param name="serverWaitTime">  <span data-ttu-id="f4f25-286">サーバーがタイムアウトするまでの時間を待機します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-286">The server wait time before it times out.</span></span> </param>
        <param name="messages">  <span data-ttu-id="f4f25-287">返されるメッセージ。</span><span class="sxs-lookup"><span data-stu-id="f4f25-287">returned messages.</span></span> </param>
        <summary> <span data-ttu-id="f4f25-288">再試行を実行するアクションを受信します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-288">Executes the try receive action.</span></span> </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public override string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.Path" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.MessageSession.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f4f25-289">に対して相対的なキューまたはトピックのパスを取得、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />ベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="f4f25-289">Gets the path of the queue or topic, relative to the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> base address.</span></span></summary>
        <value><span data-ttu-id="f4f25-290">キューまたはトピックのパスを表す文字列。</span><span class="sxs-lookup"><span data-stu-id="f4f25-290">A string representing the path of the queue or topic.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public override int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f4f25-291">取得またはメッセージの受信者が同時に要求メッセージの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-291">Gets or sets the number of messages that the message receiver can simultaneously request.</span></span></summary>
        <value><span data-ttu-id="f4f25-292">メッセージの受信者が同時に要求メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f4f25-292">The number of messages that the message receiver can simultaneously request.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessException">
      <MemberSignature Language="C#" Value="protected Exception ProcessException (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Exception ProcessException(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.ProcessException(System.Exception)" />
      <MemberSignature Language="F#" Value="member this.ProcessException : Exception -&gt; Exception" Usage="messageSession.ProcessException exception" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="exception"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLock">
      <MemberSignature Language="C#" Value="public void RenewLock ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RenewLock() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.RenewLock" />
      <MemberSignature Language="VB.NET" Value="Public Sub RenewLock ()" />
      <MemberSignature Language="F#" Value="member this.RenewLock : unit -&gt; unit" Usage="messageSession.RenewLock " />
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
        <summary><span data-ttu-id="f4f25-293">ホストがそのメッセージのロックを更新するまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-293">Specifies the time period within which the host renews its lock on a message.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="f4f25-294">場合<see cref="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" />が true の場合、すぐに操作を再試行することができます。</span><span class="sxs-lookup"><span data-stu-id="f4f25-294">If <see cref="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" /> is true, you can retry the operation immediately.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="f4f25-295">操作をすぐに再試行することができます。</span><span class="sxs-lookup"><span data-stu-id="f4f25-295">You can retry the operation immediately.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f4f25-296">操作をすぐに再試行することができます。</span><span class="sxs-lookup"><span data-stu-id="f4f25-296">You can retry the operation immediately.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException"><span data-ttu-id="f4f25-297">代わりにスローされる<see cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException" />場合は、メッセージは、<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-297">Thrown instead of <see cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException" /> if the message is from a <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewLockAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RenewLockAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.RenewLockAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewLockAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RenewLockAsync : unit -&gt; System.Threading.Tasks.Task" Usage="messageSession.RenewLockAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="f4f25-298">ホストがそのメッセージのロックを更新するまでの時間を指定します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-298">Specifies the time period within which the host renews its lock on a message.</span></span></summary>
        <returns><span data-ttu-id="f4f25-299">ロックされているホスト。</span><span class="sxs-lookup"><span data-stu-id="f4f25-299">The host that is being locked.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public virtual string SessionId { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageSession.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f4f25-300">取得またはメッセージのセッション識別子を設定します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-300">Gets or sets the message session identifier.</span></span></summary>
        <value><span data-ttu-id="f4f25-301">メッセージのセッション識別子です。</span><span class="sxs-lookup"><span data-stu-id="f4f25-301">The message session identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetState">
      <MemberSignature Language="C#" Value="public void SetState (System.IO.Stream sessionState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetState(class System.IO.Stream sessionState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.SetState(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetState (sessionState As Stream)" />
      <MemberSignature Language="F#" Value="member this.SetState : System.IO.Stream -&gt; unit" Usage="messageSession.SetState sessionState" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionState" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="sessionState"><span data-ttu-id="f4f25-302">状態情報が永続化されるストリーム。</span><span class="sxs-lookup"><span data-stu-id="f4f25-302">The stream to which the state information is persisted.</span></span></param>
        <summary><span data-ttu-id="f4f25-303">メッセージ セッションの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-303">Sets the state of the message session.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetStateAsync (System.IO.Stream sessionState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SetStateAsync(class System.IO.Stream sessionState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageSession.SetStateAsync(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetStateAsync (sessionState As Stream) As Task" />
      <MemberSignature Language="F#" Value="member this.SetStateAsync : System.IO.Stream -&gt; System.Threading.Tasks.Task" Usage="messageSession.SetStateAsync sessionState" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionState" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="sessionState"><span data-ttu-id="f4f25-304">状態情報が永続化されるストリーム。</span><span class="sxs-lookup"><span data-stu-id="f4f25-304">The stream to which the state information is persisted.</span></span></param>
        <summary><span data-ttu-id="f4f25-305">メッセージ セッションの状態を非同期に設定します。</span><span class="sxs-lookup"><span data-stu-id="f4f25-305">Asynchronously sets the state of the message session.</span></span></summary>
        <returns><span data-ttu-id="f4f25-306">メッセージ セッションの状態。</span><span class="sxs-lookup"><span data-stu-id="f4f25-306">The state of the message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportsGetRuntimeEntityDescription">
      <MemberSignature Language="C#" Value="protected internal override bool SupportsGetRuntimeEntityDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageSession.SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overrides ReadOnly Property SupportsGetRuntimeEntityDescription As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportsGetRuntimeEntityDescription : bool" Usage="Microsoft.ServiceBus.Messaging.MessageSession.SupportsGetRuntimeEntityDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>