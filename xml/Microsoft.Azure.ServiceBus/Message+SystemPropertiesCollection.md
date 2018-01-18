<Type Name="Message+SystemPropertiesCollection" FullName="Microsoft.Azure.ServiceBus.Message+SystemPropertiesCollection">
  <TypeSignature Language="C#" Value="public sealed class Message.SystemPropertiesCollection" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit Message/SystemPropertiesCollection extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Message.SystemPropertiesCollection" />
  <TypeSignature Language="F#" Value="type Message.SystemPropertiesCollection = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1ea77-101">Service Bus サービスによって設定されるプロパティの保存に使用されるコレクション。</span><span class="sxs-lookup"><span data-stu-id="1ea77-101">A collection used to store properties which are set by the Service Bus service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SystemPropertiesCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterSource">
      <MemberSignature Language="C#" Value="public string DeadLetterSource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeadLetterSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeadLetterSource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeadLetterSource As String" />
      <MemberSignature Language="F#" Value="member this.DeadLetterSource : string" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeadLetterSource" />
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
            <span data-ttu-id="1ea77-102">このメッセージがエンキューされた、配信不能になりましたが、前に、キューまたはサブスクリプションの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ea77-102">Gets the name of the queue or subscription that this message was enqueued on, before it was deadlettered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
                Only set in messages that have been dead-lettered and subsequently auto-forwarded from the dead-letter queue 
                <span data-ttu-id="1ea77-103">別のエンティティです。</span><span class="sxs-lookup"><span data-stu-id="1ea77-103">to another entity.</span></span> <span data-ttu-id="1ea77-104">メッセージが配信不能になったエンティティを示します。</span><span class="sxs-lookup"><span data-stu-id="1ea77-104">Indicates the entity in which the message was dead-lettered.</span></span> <span data-ttu-id="1ea77-105">このプロパティは読み取り専用です。</span><span class="sxs-lookup"><span data-stu-id="1ea77-105">This property is read-only.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeliveryCount">
      <MemberSignature Language="C#" Value="public int DeliveryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DeliveryCount : int" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeliveryCount" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="1ea77-106">現在の配信回数を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ea77-106">Get the current delivery count.</span></span>
            </summary>
        <value><span data-ttu-id="1ea77-107">この値は、1 から始まります。</span><span class="sxs-lookup"><span data-stu-id="1ea77-107">This value starts at 1.</span></span></value>
        <remarks>
               <span data-ttu-id="1ea77-108">このメッセージに対して試行された配信の数です。</span><span class="sxs-lookup"><span data-stu-id="1ea77-108">Number of deliveries that have been attempted for this message.</span></span> <span data-ttu-id="1ea77-109">このカウントは、メッセージのロックが有効期限切れになった場合、またはメッセージが受信者によって明示的に破棄された場合に増分されます。</span><span class="sxs-lookup"><span data-stu-id="1ea77-109">The count is incremented when a message lock expires, or the message is explicitly abandoned by the receiver.</span></span> <span data-ttu-id="1ea77-110">このプロパティは読み取り専用です。</span><span class="sxs-lookup"><span data-stu-id="1ea77-110">This property is read-only.</span></span>
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedSequenceNumber">
      <MemberSignature Language="C#" Value="public long EnqueuedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 EnqueuedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.EnqueuedSequenceNumber : int64" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedSequenceNumber" />
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
        <summary><span data-ttu-id="1ea77-111">取得またはメッセージの元のシーケンス番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="1ea77-111">Gets or sets the original sequence number of the message.</span></span></summary>
        <value><span data-ttu-id="1ea77-112">メッセージのエンキューされたシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="1ea77-112">The enqueued sequence number of the message.</span></span></value>
        <remarks>
            <span data-ttu-id="1ea77-113">このプロパティは、自動転送されたメッセージの場合に、元の送信地点で最初にメッセージに割り当てられたシーケンス番号を示します。</span><span class="sxs-lookup"><span data-stu-id="1ea77-113">For messages that have been auto-forwarded, this property reflects the sequence number that had first been assigned to the message at its original point of submission.</span></span> <span data-ttu-id="1ea77-114">このプロパティは読み取り専用です。</span><span class="sxs-lookup"><span data-stu-id="1ea77-114">This property is read-only.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="1ea77-115">取得または送信時刻の日時を UTC に設定します。</span><span class="sxs-lookup"><span data-stu-id="1ea77-115">Gets or sets the date and time of the sent time in UTC.</span></span></summary>
        <value><span data-ttu-id="1ea77-116">エンキュー刻 (utc)。</span><span class="sxs-lookup"><span data-stu-id="1ea77-116">The enqueue time in UTC.</span></span> </value>
        <remarks>
               <span data-ttu-id="1ea77-117">メッセージがエンティティで受け入れおよび格納された UTC 時刻。</span><span class="sxs-lookup"><span data-stu-id="1ea77-117">The UTC instant at which the message has been accepted and stored in the entity.</span></span> <span data-ttu-id="1ea77-118">この値は、受信者が送信者の時計を信頼したくない場合に、信頼できる中立的な到着時間インジケーターとして使用できます。</span><span class="sxs-lookup"><span data-stu-id="1ea77-118">This value can be used as an authoritative and neutral arrival time indicator when the receiver does not want to trust the sender's clock.</span></span> <span data-ttu-id="1ea77-119">このプロパティは読み取り専用です。</span><span class="sxs-lookup"><span data-stu-id="1ea77-119">This property is read-only.</span></span>
               </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsLockTokenSet">
      <MemberSignature Language="C#" Value="public bool IsLockTokenSet { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsLockTokenSet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.IsLockTokenSet" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsLockTokenSet As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsLockTokenSet : bool" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.IsLockTokenSet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ea77-120">現在のメッセージの設定のロック トークンがあるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="1ea77-120">Specifies whether or not there is a lock token set on the current message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks><span data-ttu-id="1ea77-121">ロック トークンにのみを使用してメッセージを受信したかどうかの指定<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /></span><span class="sxs-lookup"><span data-stu-id="1ea77-121">A lock token will only be specified if the message was received using <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReceived">
      <MemberSignature Language="C#" Value="public bool IsReceived { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReceived" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.IsReceived" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReceived As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReceived : bool" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.IsReceived" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="1ea77-122">メッセージがブローカーから取得されたかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="1ea77-122">Specifies if the message has been obtained from the broker.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="1ea77-123">キュー/サブスクリプションで、メッセージをロックするまで (utc) 日付と時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ea77-123">Gets the date and time in UTC until which the message will be locked in the queue/subscription.</span></span></summary>
        <value><span data-ttu-id="1ea77-124">日時キュー/サブスクリプションになるまで、メッセージがロックされます。</span><span class="sxs-lookup"><span data-stu-id="1ea77-124">The date and time until which the message will be locked in the queue/subscription.</span></span></value>
        <remarks>
                For messages retrieved under a lock (peek-lock receive mode, not pre-settled) this property reflects the UTC 
                <span data-ttu-id="1ea77-125">インスタント メッセージを保持するまでは、キューまたはサブスクリプションでロックされています。</span><span class="sxs-lookup"><span data-stu-id="1ea77-125">instant until which the message is held locked in the queue/subscription.</span></span> <span data-ttu-id="1ea77-126">ロックの有効期限、<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeliveryCount" />がインクリメントされます、メッセージが再び取得するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="1ea77-126">When the lock expires, the <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.DeliveryCount" /> is incremented and the message is again available for retrieval.</span></span> <span data-ttu-id="1ea77-127">このプロパティは読み取り専用です。</span><span class="sxs-lookup"><span data-stu-id="1ea77-127">This property is read-only.</span></span>
                </remarks>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public string LockToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockToken As String" />
      <MemberSignature Language="F#" Value="member this.LockToken : string" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />
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
            <span data-ttu-id="1ea77-128">現在のメッセージのロック トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="1ea77-128">Gets the lock token for the current message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
              <span data-ttu-id="1ea77-129">ロック トークンは、ブローカーによって保持されているロックへの参照を<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />モード。</span><span class="sxs-lookup"><span data-stu-id="1ea77-129">The lock token is a reference to the lock that is being held by the broker in <see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" /> mode.</span></span> <span data-ttu-id="1ea77-130">説明したようにメッセージを明示的に決済するロックは使用、<a href="https://docs.microsoft.com/azure/service-bus-messaging/message-transfers-locks-settlement">製品ドキュメントで詳しく</a>です。</span><span class="sxs-lookup"><span data-stu-id="1ea77-130">Locks are used to explicitly settle messages as explained in the <a href="https://docs.microsoft.com/azure/service-bus-messaging/message-transfers-locks-settlement">product documentation in more detail</a>.</span></span>
              <span data-ttu-id="1ea77-131">完全にロックをピン留めするトークンを使用することができますも、<a href="https://docs.microsoft.com/azure/service-bus-messaging/message-deferral">遅延 API</a>と、正規の配信状態フローからメッセージを受け取る、します。</span><span class="sxs-lookup"><span data-stu-id="1ea77-131">The token can also be used to pin the lock permanently through the <a href="https://docs.microsoft.com/azure/service-bus-messaging/message-deferral">Deferral API</a> and, with that, take the message out of the regular delivery state flow.</span></span> <span data-ttu-id="1ea77-132">このプロパティは読み取り専用です。</span><span class="sxs-lookup"><span data-stu-id="1ea77-132">This property is read-only.</span></span>
              </remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" />
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
        <summary><span data-ttu-id="1ea77-133">Service Bus によってメッセージに割り当てられた一意の番号を取得します。</span><span class="sxs-lookup"><span data-stu-id="1ea77-133">Gets the unique number assigned to a message by Service Bus.</span></span></summary>
        <value>To be added.</value>
        <remarks>
                <span data-ttu-id="1ea77-134">このシーケンス番号は、メッセージがブローカーおよび関数によって受け入れおよび格納されるときに真の識別子として割り当てられる 64 ビットの整数です。</span><span class="sxs-lookup"><span data-stu-id="1ea77-134">The sequence number is a unique 64-bit integer assigned to a message as it is accepted and stored by the broker and functions as its true identifier.</span></span> <span data-ttu-id="1ea77-135">パーティション分割されたエンティティの場合、最上位の 16 ビットはパーティション識別子を表します。</span><span class="sxs-lookup"><span data-stu-id="1ea77-135">For partitioned entities, the topmost 16 bits reflect the partition identifier.</span></span> <span data-ttu-id="1ea77-136">シーケンス番号は単調に増加します。</span><span class="sxs-lookup"><span data-stu-id="1ea77-136">Sequence numbers monotonically increase.</span></span> <span data-ttu-id="1ea77-137">48 - 64 ビット範囲が使い果たされると、0 にロールオーバーされます。</span><span class="sxs-lookup"><span data-stu-id="1ea77-137">They roll over to 0 when the 48-64 bit range is exhausted.</span></span> <span data-ttu-id="1ea77-138">このプロパティは読み取り専用です。</span><span class="sxs-lookup"><span data-stu-id="1ea77-138">This property is read-only.</span></span>
                </remarks>
      </Docs>
    </Member>
  </Members>
</Type>