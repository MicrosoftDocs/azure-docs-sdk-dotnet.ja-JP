<Type Name="TopicDescription" FullName="Microsoft.ServiceBus.Messaging.TopicDescription">
  <TypeSignature Language="C#" Value="public sealed class TopicDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TopicDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.TopicDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TopicDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type TopicDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.EntityDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="TopicDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="f7e6a-101">トピックの説明を表します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-101">Represents a description of the topic.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicDescription (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.TopicDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.TopicDescription : string -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="new Microsoft.ServiceBus.Messaging.TopicDescription path" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="f7e6a-102">サービス名前空間のベース アドレスを基準としたトピックのパス。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-102">The path of the topic relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="f7e6a-103">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" />指定された相対パスを持つクラス。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> class with the specified relative path.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public DateTime AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-104">メッセージをトピックに最後に送信された日付と時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-104">Gets the time and date at which a message was last sent to the topic.</span></span></summary>
        <value><span data-ttu-id="f7e6a-105">日付と時刻をメッセージが送信された前回のトピックにします。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-105">The time and date at which a message was last sent to the topic.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.AuthorizationRules Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authorization As AuthorizationRules" />
      <MemberSignature Language="F#" Value="member this.Authorization : Microsoft.ServiceBus.Messaging.AuthorizationRules" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.AuthorizationRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-106">説明の承認規則を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-106">Gets the authorization rules for the description.</span></span></summary>
        <value><span data-ttu-id="f7e6a-107">説明の承認規則。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-107">The authorization rules for the description.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public TimeSpan AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.AutoDeleteOnIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-108">取得または設定、<see cref="T:System.TimeSpan" />トピックは自動的に削除するまでアイドル状態の間隔。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-108">Gets or sets the <see cref="T:System.TimeSpan" /> idle interval after which the topic is automatically deleted.</span></span> <span data-ttu-id="f7e6a-109">最小時間は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-109">The minimum duration is 5 minutes.</span></span></summary>
        <value><span data-ttu-id="f7e6a-110">トピックのアイドル時間の範囲の自動削除します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-110">The auto delete on idle time span for the topic.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityStatus">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.AvailabilityStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityStatus As EntityAvailabilityStatus" />
      <MemberSignature Language="F#" Value="member this.AvailabilityStatus : Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.AvailabilityStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-111">このインスタンスの可用性の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-111">Gets the status of the availability of this instance.</span></span></summary>
        <value><span data-ttu-id="f7e6a-112">このインスタンスの可用性の状態です。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-112">The status of the availability of this instance.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-113">トピックが作成された日付と時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-113">Gets the time and date when the topic was created.</span></span></summary>
        <value><span data-ttu-id="f7e6a-114">トピックが作成された日付と時刻。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-114">The time and date when the topic was created.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.DefaultMessageTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-115">取得または既定メッセージの time to live のトピックの値を設定します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-115">Gets or sets the default message time to live value for a topic.</span></span> <span data-ttu-id="f7e6a-116">これは、その後、メッセージは期限切れ、メッセージが Service Bus に送信されたときから開始期間です。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-116">This is the duration after which the message expires, starting from when the message is sent to the Service Bus.</span></span> <span data-ttu-id="f7e6a-117">これは、既定値が使用されるときに<see cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" />メッセージ自体に設定されていません。その TimeToLive の値よりも古いメッセージは、有効期限が切れるし、メッセージ ストアに保持されなくです。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-117">This is the default value used when <see cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" /> is not set on a message itself.Messages older than their TimeToLive value will expire and no longer be retained in the message store.</span></span> <span data-ttu-id="f7e6a-118">サブスクライバーは期限切れのメッセージを受信することができません。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-118">Subscribers will be unable to receive expired messages.</span></span></summary>
        <value><span data-ttu-id="f7e6a-119">トピックの有効期限の既定のメッセージ時刻。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-119">The default message time to live for a topic.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateDetectionHistoryTimeWindow">
      <MemberSignature Language="C#" Value="public TimeSpan DuplicateDetectionHistoryTimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property DuplicateDetectionHistoryTimeWindow As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DuplicateDetectionHistoryTimeWindow : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.DuplicateDetectionHistoryTimeWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-120">取得または設定、<see cref="T:System.TimeSpan" />重複データ検出の履歴の期間を定義する構造体。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-120">Gets or sets the <see cref="T:System.TimeSpan" /> structure that defines the duration of the duplicate detection history.</span></span></summary>
        <value><span data-ttu-id="f7e6a-121"><see cref="T:System.TimeSpan" />重複データ検出の履歴の期間を定義する構造体。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-121">The <see cref="T:System.TimeSpan" /> structure that defines the duration of the duplicate detection history.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBatchedOperations">
      <MemberSignature Language="C#" Value="public bool EnableBatchedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableBatchedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.EnableBatchedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBatchedOperations As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableBatchedOperations : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.EnableBatchedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-122">取得またはサーバー側のバッチ操作が有効になっているかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-122">Gets or sets a value that indicates whether server-side batched operations are enabled.</span></span></summary>
        <value><span data-ttu-id="f7e6a-123">バッチ操作が有効な場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-123">true if the batched operations are enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableExpress">
      <MemberSignature Language="C#" Value="public bool EnableExpress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableExpress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.EnableExpress" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableExpress As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableExpress : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.EnableExpress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-124">取得または Express のエンティティが有効になっているかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-124">Gets or sets a value that indicates whether Express Entities are enabled.</span></span> <span data-ttu-id="f7e6a-125">高速のトピックでは、永続的ストレージに書き込む前に一時的にメモリにメッセージを保持します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-125">An express topic holds a message in memory temporarily before writing it to persistent storage.</span></span></summary>
        <value><span data-ttu-id="f7e6a-126">エクスプレス エンティティが有効な場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-126">true if the Express Entities are enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableFilteringMessagesBeforePublishing">
      <MemberSignature Language="C#" Value="public bool EnableFilteringMessagesBeforePublishing { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableFilteringMessagesBeforePublishing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.EnableFilteringMessagesBeforePublishing" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableFilteringMessagesBeforePublishing As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableFilteringMessagesBeforePublishing : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.EnableFilteringMessagesBeforePublishing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-127">取得またはパブリッシュする前に、メッセージをフィルター処理する必要かどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-127">Gets or sets whether messages should be filtered before publishing.</span></span></summary>
        <value><span data-ttu-id="f7e6a-128">パブリッシュする前にメッセージのフィルター処理が有効になっている場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-128">true if message filtering is enabled before publishing; otherwise, false.</span></span></value>
        <remarks> <span data-ttu-id="f7e6a-129">この機能は開発およびテスト目的でのみ使用することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-129">This feature is recommended to be used only for development and testing purposes.</span></span>  
            <span data-ttu-id="f7e6a-130">たとえば、トピックに新しいルールやフィルターが追加されて、ときにこの機能は新しいフィルター式が期待どおりに動作していることを確認する使用できます。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-130">For example, when  new Rules or Filters are being added to the topic, this feature can be used to verify that the new filter expression is working as expected.</span></span> <span data-ttu-id="f7e6a-131">テストおよびと正常に動作して、機能は実稼働環境でオフにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-131">Once tested and working fine, the feature should be turned off in production.</span></span> </remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.NoMatchingSubscriptionException"><span data-ttu-id="f7e6a-132">サブスクリプションが一致しない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-132">Thrown if the subscriptions do not match.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="EnablePartitioning">
      <MemberSignature Language="C#" Value="public bool EnablePartitioning { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnablePartitioning" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.EnablePartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Property EnablePartitioning As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnablePartitioning : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.EnablePartitioning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-133">取得または複数のメッセージ ブローカーにわたって分割するトピックを有効にするかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-133">Gets or sets whether to enable the topic to be partitioned across multiple message brokers.</span></span> <span data-ttu-id="f7e6a-134">高速のトピックでは、永続的ストレージに書き込む前に一時的にメモリにメッセージを保持します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-134">An express topic holds a message in memory temporarily before writing it to persistent storage.</span></span></summary>
        <value><span data-ttu-id="f7e6a-135">複数のメッセージ ブローカーにわたって分割するトピックを有効にする場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-135">true to enable the topic to be partitioned across multiple message brokers; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAnonymousAccessible">
      <MemberSignature Language="C#" Value="public bool IsAnonymousAccessible { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAnonymousAccessible" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.IsAnonymousAccessible" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAnonymousAccessible As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAnonymousAccessible : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.IsAnonymousAccessible" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-136">匿名アクセスが許可されているかどうかを取得します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-136">Gets whether anonymous access is allowed.</span></span></summary>
        <value><span data-ttu-id="f7e6a-137">匿名アクセスが許可されている以外の場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-137">true if anonymous access is allowed; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeInMegabytes">
      <MemberSignature Language="C#" Value="public long MaxSizeInMegabytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxSizeInMegabytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.MaxSizeInMegabytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeInMegabytes As Long" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInMegabytes : int64 with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.MaxSizeInMegabytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-138">取得またはトピックに割り当てられたメモリのサイズはメガバイト単位で、このトピックの最大サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-138">Gets or sets the maximum size of the topic in megabytes, which is the size of memory allocated for the topic.</span></span></summary>
        <value><span data-ttu-id="f7e6a-139">最大サイズ (メガバイト単位)。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-139">The maximum size in megabytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.MessageCountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.MessageCountDetails : Microsoft.ServiceBus.Messaging.MessageCountDetails" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.MessageCountDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageCountDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-140">このトピックに関するメッセージの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-140">Gets message details about the topic.</span></span></summary>
        <value><span data-ttu-id="f7e6a-141"><see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" />数を格納しているアクティブなメッセージ、配信不能メッセージ、スケジュールされたメッセージの場合は、他のキュー、サブスクリプション、またはトピックについてにメッセージが転送され、メッセージの数が配信不能キューに転送します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-141">The <see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" /> that contains the number of active messages, dead letters, scheduled messages, messages transferred to other queues, subscriptions, or topics, and the number of messages transferred to the dead letter queue.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageTimeToLiveDefaultValue">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan MessageTimeToLiveDefaultValue;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.TopicDescription.MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly MessageTimeToLiveDefaultValue As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable MessageTimeToLiveDefaultValue : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.MessageTimeToLiveDefaultValue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
              <span data-ttu-id="f7e6a-142">メッセージの time to live の既定値</span><span class="sxs-lookup"><span data-stu-id="f7e6a-142">The message time to live default value</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-143">トピックのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-143">Gets the path of the topic.</span></span></summary>
        <value><span data-ttu-id="f7e6a-144">トピックのパス。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-144">The path of the topic.</span></span></value>
        <remarks>
              <span data-ttu-id="f7e6a-145">これへの相対パス、<see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />です。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-145">This is a relative path to the <see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresDuplicateDetection">
      <MemberSignature Language="C#" Value="public bool RequiresDuplicateDetection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresDuplicateDetection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.RequiresDuplicateDetection" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresDuplicateDetection As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresDuplicateDetection : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.RequiresDuplicateDetection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-146">取得またはトピックに重複データ検出が必要とするかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-146">Gets or sets the value that indicates whether a topic requires duplication detection.</span></span></summary>
        <value><span data-ttu-id="f7e6a-147">トピックには、重複データ検出; が必要な場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-147">true if a topic requires duplication detection; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public long SizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : int64" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-148">トピックのサイズをバイト単位で取得します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-148">Gets the size of the topic in bytes.</span></span></summary>
        <value><span data-ttu-id="f7e6a-149">(バイト単位) のトピックのサイズ。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-149">The size of the topic in bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As EntityStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.ServiceBus.Messaging.EntityStatus with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-150">取得または設定 (有効または無効になっています)、このトピックの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-150">Gets or sets the current status of the topic (enabled or disabled).</span></span> <span data-ttu-id="f7e6a-151">エンティティを無効にすると、そのエンティティが送信またはメッセージを受信できません。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-151">When an entity is disabled, that entity cannot send or receive messages.</span></span></summary>
        <value><span data-ttu-id="f7e6a-152">トピックの状態です。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-152">The status of the topic.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionCount">
      <MemberSignature Language="C#" Value="public int SubscriptionCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SubscriptionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.SubscriptionCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionCount As Integer" />
      <MemberSignature Language="F#" Value="member this.SubscriptionCount : int" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.SubscriptionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-153">取得してから、サブスクリプションの数。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-153">Gets then number of subscriptions.</span></span></summary>
        <value><span data-ttu-id="f7e6a-154"><see cref="T:System.Int32" />サブスクリプションの数を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-154">An <see cref="T:System.Int32" /> that represents the number of subscriptions.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportOrdering">
      <MemberSignature Language="C#" Value="public bool SupportOrdering { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportOrdering" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.SupportOrdering" />
      <MemberSignature Language="VB.NET" Value="Public Property SupportOrdering As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportOrdering : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.SupportOrdering" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-155">取得またはメソッドを順序付けのサポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-155">Gets or sets the support ordering method.</span></span></summary>
        <value><span data-ttu-id="f7e6a-156">メソッドを順序付けのサポート。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-156">The support ordering method.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-157">トピックが更新された日付と時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-157">Gets the time and date when the topic was updated.</span></span></summary>
        <value><span data-ttu-id="f7e6a-158">トピックが更新された日付と時刻。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-158">The time and date when the topic was updated.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.TopicDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.ServiceBus.Messaging.TopicDescription.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f7e6a-159">取得または説明に関連付けられているユーザーのメタデータを設定します。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-159">Gets or sets the user metadata associated with the description.</span></span></summary>
        <value><span data-ttu-id="f7e6a-160">説明に関連付けられているユーザーのメタデータ。</span><span class="sxs-lookup"><span data-stu-id="f7e6a-160">The user metadata associated with the description.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>