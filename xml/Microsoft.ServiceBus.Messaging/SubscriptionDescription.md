<Type Name="SubscriptionDescription" FullName="Microsoft.ServiceBus.Messaging.SubscriptionDescription">
  <TypeSignature Language="C#" Value="public sealed class SubscriptionDescription : Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SubscriptionDescription extends Microsoft.ServiceBus.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SubscriptionDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type SubscriptionDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="SubscriptionDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="a8187-101">サブスクリプションの説明を表します。</span><span class="sxs-lookup"><span data-stu-id="a8187-101">Represents a description of the subscription.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionDescription (string topicPath, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string topicPath, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SubscriptionDescription.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (topicPath As String, subscriptionName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SubscriptionDescription : string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="new Microsoft.ServiceBus.Messaging.SubscriptionDescription (topicPath, subscriptionName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="a8187-102">トピックのパスです。</span><span class="sxs-lookup"><span data-stu-id="a8187-102">The topic path.</span></span></param>
        <param name="subscriptionName"><span data-ttu-id="a8187-103">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="a8187-103">The subscription name.</span></span></param>
        <summary><span data-ttu-id="a8187-104"><see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a8187-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public DateTime AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-105">このサブスクリプションの受信要求が、最終時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="a8187-105">Gets the last time a there was a receive request to this subscription.</span></span></summary>
        <value><span data-ttu-id="a8187-106">最後がこのサブスクリプションの受信要求します。</span><span class="sxs-lookup"><span data-stu-id="a8187-106">The last time a there was a receive request to this subscription.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public TimeSpan AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.AutoDeleteOnIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-107">取得または設定、<see cref="T:System.TimeSpan" />アイドル状態の間隔がその後、サブスクリプションは自動的に削除します。</span><span class="sxs-lookup"><span data-stu-id="a8187-107">Gets or sets the <see cref="T:System.TimeSpan" /> idle interval after which the subscription is automatically deleted.</span></span> <span data-ttu-id="a8187-108">最小時間は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="a8187-108">The minimum duration is 5 minutes.</span></span></summary>
        <value><span data-ttu-id="a8187-109">サブスクリプションのアイドル時間の範囲の自動削除します。</span><span class="sxs-lookup"><span data-stu-id="a8187-109">The auto delete on idle time span for the subscription.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityStatus">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus AvailabilityStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.AvailabilityStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityStatus As EntityAvailabilityStatus" />
      <MemberSignature Language="F#" Value="member this.AvailabilityStatus : Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.AvailabilityStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityAvailabilityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-110">メッセージング エンティティの可用性の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="a8187-110">Gets the entity availability status for the messaging.</span></span></summary>
        <value><span data-ttu-id="a8187-111">メッセージング エンティティの可用性の状態。</span><span class="sxs-lookup"><span data-stu-id="a8187-111">The entity availability status for the messaging.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public DateTime CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-112">メッセージが作成された正確な時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="a8187-112">Gets the exact time the message was created.</span></span></summary>
        <value><span data-ttu-id="a8187-113">メッセージが作成された時刻。</span><span class="sxs-lookup"><span data-stu-id="a8187-113">The time the message was created.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.DefaultMessageTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-114">取得または既定メッセージの time to live の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8187-114">Gets or sets the default message time to live value.</span></span> <span data-ttu-id="a8187-115">これは、その後、メッセージは期限切れ、メッセージが Service Bus に送信されたときから開始期間です。</span><span class="sxs-lookup"><span data-stu-id="a8187-115">This is the duration after which the message expires, starting from when the message is sent to the Service Bus.</span></span> <span data-ttu-id="a8187-116">これは、既定値が使用されるときに<see cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" />メッセージ自体に設定されていません。その TimeToLive の値よりも古いメッセージは、有効期限が切れるし、メッセージ ストアに保持されなくです。</span><span class="sxs-lookup"><span data-stu-id="a8187-116">This is the default value used when <see cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" /> is not set on a message itself.Messages older than their TimeToLive value will expire and no longer be retained in the message store.</span></span> <span data-ttu-id="a8187-117">サブスクライバーは期限切れのメッセージを受信することができません。メッセージできます、TimeToLive 値より小さく、ここで指定されているが、既定で、TimeToLive に設定されて<see cref="F:System.TimeSpan.MaxValue" />です。</span><span class="sxs-lookup"><span data-stu-id="a8187-117">Subscribers will be unable to receive expired messages.A message can have a lower TimeToLive value than that specified here, but by default TimeToLive is set to <see cref="F:System.TimeSpan.MaxValue" />.</span></span> <span data-ttu-id="a8187-118">そのため、このプロパティは、有効期限の値をメッセージに適用される既定の時間になります。</span><span class="sxs-lookup"><span data-stu-id="a8187-118">Therefore, this property becomes the default time to live value applied to messages.</span></span></summary>
        <value><span data-ttu-id="a8187-119">サブスクリプションの有効期限の既定のメッセージ時刻。</span><span class="sxs-lookup"><span data-stu-id="a8187-119">The default message time to live for a subscription.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBatchedOperations">
      <MemberSignature Language="C#" Value="public bool EnableBatchedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableBatchedOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableBatchedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBatchedOperations As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableBatchedOperations : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableBatchedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-120">取得またはバッチの操作が有効になっているかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8187-120">Gets or sets a value that indicates whether the batched operations are enabled.</span></span></summary>
        <value><span data-ttu-id="a8187-121">バッチ操作が有効な場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="a8187-121">true if the batched operations are enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDeadLetteringOnFilterEvaluationExceptions">
      <MemberSignature Language="C#" Value="public bool EnableDeadLetteringOnFilterEvaluationExceptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableDeadLetteringOnFilterEvaluationExceptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableDeadLetteringOnFilterEvaluationExceptions" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDeadLetteringOnFilterEvaluationExceptions As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableDeadLetteringOnFilterEvaluationExceptions : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableDeadLetteringOnFilterEvaluationExceptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-122">取得またはサブスクリプションがフィルター評価例外ではサポート停止している文字がかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8187-122">Gets or sets the value that indicates if a subscription has dead letter support on Filter evaluation exceptions.</span></span></summary>
        <value><span data-ttu-id="a8187-123">true の場合、サブスクリプションがフィルター評価例外ではサポート停止している文字それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="a8187-123">true if a subscription has dead letter support on Filter evaluation exceptions; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDeadLetteringOnMessageExpiration">
      <MemberSignature Language="C#" Value="public bool EnableDeadLetteringOnMessageExpiration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableDeadLetteringOnMessageExpiration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableDeadLetteringOnMessageExpiration" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDeadLetteringOnMessageExpiration As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableDeadLetteringOnMessageExpiration : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.EnableDeadLetteringOnMessageExpiration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-124">取得またはサブスクリプションがメッセージの有効期限が切れるときに、配信不能サポートがかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8187-124">Gets or sets the value that indicates if a subscription has dead letter support when a message expires.</span></span></summary>
        <value><span data-ttu-id="a8187-125">true がある場合、メッセージの配信不能メッセージのサポートをサブスクリプションを期限切れです。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="a8187-125">true if a subscription has dead letter support when a message expires; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardDeadLetteredMessagesTo">
      <MemberSignature Language="C#" Value="public string ForwardDeadLetteredMessagesTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardDeadLetteredMessagesTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardDeadLetteredMessagesTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.ForwardDeadLetteredMessagesTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-126">取得またはデッド文字のメッセージを転送する、受信者へのパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8187-126">Gets or sets the path to the recipient to which the dead lettered messages are forwarded.</span></span></summary>
        <value><span data-ttu-id="a8187-127">デッド文字のメッセージを転送する受信者へのパス。</span><span class="sxs-lookup"><span data-stu-id="a8187-127">The path to the recipient to which the dead lettered messages are forwarded.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardTo">
      <MemberSignature Language="C#" Value="public string ForwardTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.ForwardTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.ForwardTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-128">取得またはメッセージが転送される受信者へのパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8187-128">Gets or sets the path to the recipient to which the message is forwarded.</span></span></summary>
        <value><span data-ttu-id="a8187-129">メッセージが転送される受信者へのパス。</span><span class="sxs-lookup"><span data-stu-id="a8187-129">The path to the recipient to which the message is forwarded.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LockDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LockDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property LockDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LockDuration : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-130">取得または設定、ロック期間の期間サブスクリプション。</span><span class="sxs-lookup"><span data-stu-id="a8187-130">Gets or sets the lock duration time span for the subscription.</span></span></summary>
        <value><span data-ttu-id="a8187-131">ロック期間は、サブスクリプションを期間します。</span><span class="sxs-lookup"><span data-stu-id="a8187-131">The lock duration time span for the subscription.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCount">
      <MemberSignature Language="C#" Value="public int MaxDeliveryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.MaxDeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.MaxDeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-132">取得または最大配信回数を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8187-132">Gets or sets the number of maximum deliveries.</span></span></summary>
        <value><span data-ttu-id="a8187-133">最大配信回数。</span><span class="sxs-lookup"><span data-stu-id="a8187-133">The number of maximum deliveries.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCount">
      <MemberSignature Language="C#" Value="public long MessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCount As Long" />
      <MemberSignature Language="F#" Value="member this.MessageCount : int64" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-134">メッセージの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="a8187-134">Gets the number of messages.</span></span></summary>
        <value><span data-ttu-id="a8187-135">メッセージ数。</span><span class="sxs-lookup"><span data-stu-id="a8187-135">The number of messages.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessageCountDetails MessageCountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageCountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.MessageCountDetails : Microsoft.ServiceBus.Messaging.MessageCountDetails" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageCountDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageCountDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-136">サブスクリプションに関するメッセージの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="a8187-136">Gets message details about the subscription.</span></span></summary>
        <value><span data-ttu-id="a8187-137">返します<see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" />アクティブなメッセージ、配信不能メッセージ、スケジュールされたメッセージの数、メッセージと転送されるその他のキュー、サブスクリプション、またはトピックについては、メッセージの数が配信不能キューに転送します。</span><span class="sxs-lookup"><span data-stu-id="a8187-137">Returns <see cref="T:Microsoft.ServiceBus.Messaging.MessageCountDetails" /> with the number of active messages, dead letters, scheduled messages, messages transferred to other queues, subscriptions, or topics, and the number of messages transferred to the dead letter queue.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageTimeToLiveDefaultValue">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan MessageTimeToLiveDefaultValue;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageTimeToLiveDefaultValue" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly MessageTimeToLiveDefaultValue As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable MessageTimeToLiveDefaultValue : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.MessageTimeToLiveDefaultValue" />
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
              <span data-ttu-id="a8187-138">メッセージの time to live の既定値</span><span class="sxs-lookup"><span data-stu-id="a8187-138">The message time to live default value</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-139">サブスクリプションの説明の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="a8187-139">Gets the name of the subscription description.</span></span></summary>
        <value><span data-ttu-id="a8187-140">サブスクリプションの説明の名前。</span><span class="sxs-lookup"><span data-stu-id="a8187-140">The name of the subscription description.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresSession">
      <MemberSignature Language="C#" Value="public bool RequiresSession { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.RequiresSession" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresSession As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresSession : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.RequiresSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-141">取得またはサブスクリプションがセッションの概念をサポートしているかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8187-141">Gets or sets the value indicating if a subscription supports the concept of session.</span></span></summary>
        <value><span data-ttu-id="a8187-142">受信側のアプリケーションを使用してキューからのみ受信できる場合は true、<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />を使用してキューを利用できない場合は false です。<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />です。</span><span class="sxs-lookup"><span data-stu-id="a8187-142">true if the receiver application can only receive from the queue through a <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />; false if a queue cannot receive using <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EntityStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.EntityStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As EntityStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.ServiceBus.Messaging.EntityStatus with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EntityStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-143">取得またはサブスクリプション (有効または無効になっている) の現在の状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="a8187-143">Gets or sets the current status of the subscription (enabled or disabled).</span></span> <span data-ttu-id="a8187-144">エンティティを無効にすると、そのエンティティが送信またはメッセージを受信できません。</span><span class="sxs-lookup"><span data-stu-id="a8187-144">When an entity is disabled, that entity cannot send or receive messages.</span></span></summary>
        <value><span data-ttu-id="a8187-145">サブスクリプションの現在の状態。</span><span class="sxs-lookup"><span data-stu-id="a8187-145">The current status of the subscription.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicPath">
      <MemberSignature Language="C#" Value="public string TopicPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.TopicPath" />
      <MemberSignature Language="VB.NET" Value="Public Property TopicPath As String" />
      <MemberSignature Language="F#" Value="member this.TopicPath : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.TopicPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-146">このサブスクリプションの説明が属するトピックのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="a8187-146">Gets the path of the topic that this subscription description belongs to.</span></span></summary>
        <value><span data-ttu-id="a8187-147">このサブスクリプションの説明が属するトピックのパス。</span><span class="sxs-lookup"><span data-stu-id="a8187-147">The path of the topic that this subscription description belongs to.</span></span></value>
        <remarks>
              <span data-ttu-id="a8187-148">これへの相対パス、<see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />です。</span><span class="sxs-lookup"><span data-stu-id="a8187-148">This is a relative path to the <see cref="P:Microsoft.ServiceBus.NamespaceManager.Address" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public DateTime UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : DateTime" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-149">メッセージが更新された正確な時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="a8187-149">Gets the exact time the message has been updated.</span></span></summary>
        <value><span data-ttu-id="a8187-150">メッセージが更新された時刻。</span><span class="sxs-lookup"><span data-stu-id="a8187-150">The time the message has been updated.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SubscriptionDescription.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a8187-151">取得またはユーザーのメタデータを設定します。</span><span class="sxs-lookup"><span data-stu-id="a8187-151">Gets or sets the user metadata.</span></span></summary>
        <value><span data-ttu-id="a8187-152">ユーザーのメタデータ。</span><span class="sxs-lookup"><span data-stu-id="a8187-152">The user metadata.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>